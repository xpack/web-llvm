---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `BitcodeReader.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/metadataloader-h">MetadataLoader.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/valuelist-h">ValueList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">llvm/Bitcode/BitcodeCommon.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">llvm/Bitcode/LLVMBitCodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamreader-h">llvm/Bitstream/BitstreamReader.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributemask-h">llvm/IR/AttributeMask.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/autoupgrade-h">llvm/IR/AutoUpgrade.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">llvm/IR/Comdat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">llvm/IR/ConstantRangeList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/datalayout-h">llvm/IR/DataLayout.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/gvmaterializer-h">llvm/IR/GVMaterializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/getelementptrtypeiterator-h">llvm/IR/GetElementPtrTypeIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalifunc-h">llvm/IR/GlobalIFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "llvm/IR/IntrinsicsAArch64.h"
#include "llvm/IR/IntrinsicsARM.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/profdatautils-h">llvm/IR/ProfDataUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/verifier-h">llvm/IR/Verifier.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/atomicordering-h">llvm/Support/AtomicOrdering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">llvm/Support/ModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;deque&gt;
#include &lt;map&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;set&gt;
#include &lt;string&gt;
#include &lt;system_error&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-bitcodereader-cpp-">anonymous{BitcodeReader.cpp}</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereaderbase">BitcodeReaderBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant">BitcodeConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a constant expression or constant aggregate using a custom structure internal to the bitcode reader. <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-bitcodereader-cpp-/bitcodeconstant/extrainfo">ExtraInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader">BitcodeReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-bitcodereader-cpp-/bitcodereader/functionoperandinfo">FunctionOperandInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader">ModuleSummaryIndexBitcodeReader</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage reading and parsing function summary index bitcode files/sections. <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeerrorcategorytype">BitcodeErrorCategoryType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b53d81cd663680d3924d4d3eba6bda">error</a> (const Twine &amp;Message)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95e3a85203eeaf11c26b7161a4557934">hasInvalidBitcodeHeader</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5a82b3045c92ee732ddca71ea91a65d">initStream</a> (MemoryBufferRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename StrTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2d7d3464870033ae244f10f24678e945">convertToString</a> (ArrayRef&lt; uint64_t &gt; Record, unsigned Idx, StrTy &amp;Result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a string from a record into an std::string, return true on failure. <a href="#a2d7d3464870033ae244f10f24678e945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32c765cabc6bab63ba8691a789db738b">stripTBAA</a> (Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the "IDENTIFICATION_BLOCK_ID" block, do some basic enforcement on the "epoch" encoded in the bitcode, and return the producer name if any. <a href="#adfdf631a8d0d417904f24c6ff6d9ed03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6235e5cdcd03f0d0dbb533debac0d9">readIdentificationCode</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3e993fa38b2fd4caaacd62e4e152a4">hasObjCCategory</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42cc3ae15d37346d7ca743801b572770">readTriple</a> (BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6ba1fc9ba48d7ddb59157f4309a134">hasImplicitComdat</a> (size_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9049fa6f0ceaa6bacf0a9bf51c0a2770">getDecodedLinkage</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags">FunctionSummary::FFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17b0f35cf88f5658433215c49fe12320">getDecodedFFlags</a> (uint64_t RawFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags">GlobalValueSummary::GVFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b48eac2502c5d45d4ed09c2d1382ecb">getDecodedGVSummaryFlags</a> (uint64_t RawFlags, uint64_t Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/globalvarsummary/gvarflags">GlobalVarSummary::GVarFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5931832ea87220f401de203134d472bb">getDecodedGVarFlags</a> (uint64_t RawFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::pair&lt; <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a2413e35985411a461b9ab03c17c01caa">CalleeInfo::HotnessType</a>, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1383985111f3dccd6dd84aed125f5881">getDecodedHotnessCallEdgeInfo</a> (uint64_t RawFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08ebdf89a78bb53144d1df14c5475c00">getDecodedRelBFCallEdgeInfo</a> (uint64_t RawFlags, uint64_t &amp;RelBF, bool &amp;HasTailCall)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195">GlobalValue::VisibilityTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afca97c2660719090403589cd03658cad">getDecodedVisibility</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8">GlobalValue::DLLStorageClassTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636064b7990868b8867890bcdb3e2b2d">getDecodedDLLStorageClass</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22fcab89e52afadf10ab18802ba4083a">getDecodedDSOLocal</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a298591ad7fece6fddd690511643d6e">getDecodedCodeModel</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static GlobalVariable::ThreadLocalMode</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb15ffa7287b5723c317de2986fe3ab">getDecodedThreadLocalMode</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static GlobalVariable::UnnamedAddr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff593b38ab7b31e6ddf38bda8011a21">getDecodedUnnamedAddrType</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb74d50adfdf3a22a186706c3f92f722">getDecodedCastOpcode</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42193bb1ec0e43f7eaaaabe307874518">getDecodedUnaryOpcode</a> (unsigned Val, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa52298c6762df1ff42322f0271c646b7">getDecodedBinaryOpcode</a> (unsigned Val, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7935ff3ae6dbf81e8185937361555a1">getDecodedRMWOperation</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cdbd26c024d7e2084d0a1a4ed6c2503">getDecodedOrdering</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035">Comdat::SelectionKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aefee473fa8e486202283927b80ac63">getDecodedComdatSelectionKind</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab35a64e2f9201e7d20db1ff384218ab1">getDecodedFastMathFlags</a> (unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ab0b4e3b20c68f71d543a2eb6a32ddf">upgradeDLLImportExportLinkage</a> (GlobalValue *GV, unsigned Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66c221eaf3589701aa0fa16c6cd61407">toGEPNoWrapFlags</a> (uint64_t Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae94b0d68e3880f919a56af17f7c40a73">isConstExprSupported</a> (const BitcodeConstant *BC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46f538c093b0e66e2e1310c5b8c83b88">getRawAttributeMask</a> (Attribute::AttrKind Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88097e7039070e670b83a2f0c420f977">addRawAttributeValue</a> (AttrBuilder &amp;B, uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680090be3d94b8e77d284da7e51f671f">decodeLLVMAttributesForBitcode</a> (AttrBuilder &amp;B, uint64_t EncodedAttrs, uint64_t AttrIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This fills an <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> object with the LLVM attributes that have been decoded from the given integer. <a href="#a680090be3d94b8e77d284da7e51f671f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59fb99fd6562d72cd606037e30c464d9">getAttrFromCode</a> (uint64_t Code)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a3a2ebeb9f0ceca766759a20ba60ac">upgradeOldMemoryAttribute</a> (MemoryEffects &amp;ME, uint64_t EncodedKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fca99afcf20fdf62a04843e8825d03f">jumpToValueSymbolTable</a> (uint64_t Offset, BitstreamCursor &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to note and return the current location, and jump to the given offset. <a href="#a5fca99afcf20fdf62a04843e8825d03f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab084a1deda97f9a90c7c8074c4e6ac6f">inferDSOLocal</a> (GlobalValue *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata">GlobalValue::SanitizerMetadata</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ad348dbd17ec77d4eb40574c44f9a8">deserializeSanitizerMetadata</a> (unsigned V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46bea8d236da27677962598b5bd45703">parseWholeProgramDevirtResolutionByArg</a> (ArrayRef&lt; uint64_t &gt; Record, size_t &amp;Slot, WholeProgramDevirtResolution &amp;Wpd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaffdb3054263427a7df8fdac667a0c5b">parseWholeProgramDevirtResolution</a> (ArrayRef&lt; uint64_t &gt; Record, StringRef Strtab, size_t &amp;Slot, TypeIdSummary &amp;TypeId)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a> (ArrayRef&lt; uint64_t &gt; Record, StringRef Strtab, ModuleSummaryIndex &amp;TheIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab33fa6fa7130c1c532556fcbddb32d">setSpecialRefs</a> (SmallVectorImpl&lt; ValueInfo &gt; &amp;Refs, unsigned ROCnt, unsigned WOCnt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3dcdf576f07a261c70f7eac121b3eec">readBlobInRecord</a> (BitstreamCursor &amp;Stream, unsigned Block, unsigned RecordID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::pair&lt; bool, bool &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d0c0fef256a92c13760a52971b805b5">getEnableSplitLTOUnitAndUnifiedFlag</a> (BitstreamCursor &amp;Stream, unsigned ID, BitcodeLTOInfo &amp;LTOInfo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule">BitcodeModule</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1a1464db1a7a577a3c9fb3e76e6f75">getSingleModule</a> (MemoryBufferRef Buffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cd7a38fa5e33363b919a3cd6aa23b08">PrintSummaryGUIDs</a>("print-summary-global-ids", cl::init(false), cl::Hidden, cl::desc("Print the global id for each value when reading the module summary"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd17dd727afda35058727b3cd0428722">ExpandConstantExprs</a>("expand-constant-exprs", cl::Hidden, cl::desc("Expand constant expressions to instructions for testing purposes"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c1181cf1d0d961944966c346a3564a">LoadBitcodeIntoNewDbgInfoFormat</a>("load-bitcode-into-experimental-debuginfo-iterators", cl::Hidden, cl::desc("Load bitcode directly into the new debug info format (regardless " "of input format)"))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load bitcode directly into RemoveDIs format (use debug records instead of debug intrinsics). <a href="#a87c1181cf1d0d961944966c346a3564a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecfc696c759c52249220099347df84da">UseNewDbgInfoFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; cl::boolOrDefault &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eee5efdaf0acfd7e7be22a487088c87">PreserveInputDbgFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d24bcd4c11f1c3237941d712ed3284">WriteNewDbgInfoFormatToBitcode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armloadstoreoptimizer-cpp/#ab3bfc7321acfbc3619170d5bed907cb3">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ef03caf2222804098e7c78eb0e39dc">WriteNewDbgInfoFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### addRawAttributeValue() {#a88097e7039070e670b83a2f0c420f977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addRawAttributeValue (<a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B, uint64_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1921 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a>, <a href="#a46f538c093b0e66e2e1310c5b8c83b88">getRawAttributeMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a44b9bbfc65ea129fe5c7fe72ea004d00">llvm::Attribute::isTypeAttrKind</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a>.</p>


<p>Referenced by <a href="#a680090be3d94b8e77d284da7e51f671f">decodeLLVMAttributesForBitcode</a>.</p>

</div>
</div>

### convertToString() {#a2d7d3464870033ae244f10f24678e945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename StrTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool convertToString (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, unsigned Idx, StrTy &amp; Result)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a string from a record into an std::string, return true on failure.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>, <a href="#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a> and <a href="#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>.</p>

</div>
</div>

### decodeLLVMAttributesForBitcode() {#a680090be3d94b8e77d284da7e51f671f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void decodeLLVMAttributesForBitcode (<a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B, uint64_t EncodedAttrs, uint64_t AttrIdx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This fills an <a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> object with the LLVM attributes that have been decoded from the given integer.</p>


<p>This function must stay in sync with 'encodeLLVMAttributesForBitcode'.</p>


<p>Definition at line 1942 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="#a88097e7039070e670b83a2f0c420f977">addRawAttributeValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a895001b186ed51e1cb7a256dbd3545f8">llvm::AttributeList::FunctionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5cba4a49c183c6c2f6168be64f04a7b9">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleMemOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#ad341f584befc40ff0aefca99682baf7c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleOrArgMemOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6dec2b5d3e04b47adf4d918d678e81c9">llvm::isPowerOf2_32</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a0dc1a3456bce25673dff8dce6f240a8f">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::readOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#aff771abf487136aeebb6862871d5e715">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::unknown</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a9e3dc568b5f51e03441c9c44b618f337">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::writeOnly</a>.</p>

</div>
</div>

### deserializeSanitizerMetadata() {#ab3ad348dbd17ec77d4eb40574c44f9a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::SanitizerMetadata deserializeSanitizerMetadata (unsigned V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4058 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### error() {#a31b53d81cd663680d3924d4d3eba6bda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error error (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Message)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#affc48873f7091ddc1879c70e6e613f61aa6b0a00d60d1a93ce8e14b757ee48cc0">llvm::CorruptedBitcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a20e3e08c7de6a230cd66f9e4322c3fbe">llvm::make_error_code</a>.</p>

</div>
</div>

### getAttrFromCode() {#a59fb99fd6562d72cd606037e30c464d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind getAttrFromCode (uint64_t Code)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2055 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3abadb9d66c19008e4ddb353c55d2c28e2">llvm::bitc::ATTR_KIND_ALIGNMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a929955dc4b9681ed9cec5bc1ff962391">llvm::bitc::ATTR_KIND_ALLOC_ALIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a85f1c987a4cab98ae2d3cf15c46a5533">llvm::bitc::ATTR_KIND_ALLOC_KIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a512cc01a3fa4c51809cb905de3d30b4c">llvm::bitc::ATTR_KIND_ALLOC_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7a1023f40b7fdf89b8359106f07ce88d">llvm::bitc::ATTR_KIND_ALLOCATED_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac21e10518d20fe0353e65cca06bd5256">llvm::bitc::ATTR_KIND_ALWAYS_INLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a86f312d48859fc97a288d8718d4e4e81">llvm::bitc::ATTR_KIND_BUILTIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa3b7dab5234bc2c00ecd7e64878b715d">llvm::bitc::ATTR_KIND_BY_VAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a13b920c66e426fedc360a03dc19ae6b0">llvm::bitc::ATTR_KIND_BYREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3af3a622a12140d6cfa18c6994cb9b93c5">llvm::bitc::ATTR_KIND_CAPTURES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6b5c1960ea5bf27bae724fbe40458671">llvm::bitc::ATTR_KIND_COLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a3b0c92f3637b859b97dd9575a33ffec9">llvm::bitc::ATTR_KIND_CONVERGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a85c70a265e696fc216e55f0e6a0d3935">llvm::bitc::ATTR_KIND_CORO_ELIDE_SAFE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3af37c451700ab8aaad90854ec4b50a980">llvm::bitc::ATTR_KIND_CORO_ONLY_DESTROY_WHEN_COMPLETE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a3794a1f268da39dfa1c0815d936ae616">llvm::bitc::ATTR_KIND_DEAD_ON_UNWIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a94f778cea4955c8d871aa0ebc22b4852">llvm::bitc::ATTR_KIND_DEREFERENCEABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaec534c7d966b2ce46814f56cee8d88a">llvm::bitc::ATTR_KIND_DEREFERENCEABLE_OR_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7d923675347db880195935dd2859430b">llvm::bitc::ATTR_KIND_DISABLE_SANITIZER_INSTRUMENTATION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a84639710ca4a56d99d1ada67fa19c40f">llvm::bitc::ATTR_KIND_ELEMENTTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a289e17c3ab627b09ba25a1fdd4fd4dea">llvm::bitc::ATTR_KIND_FNRETTHUNK_EXTERN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ae09a861f046502814ccc8a1805966955">llvm::bitc::ATTR_KIND_HOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a8333f888d39f2fc0d6f18a96a16d902b">llvm::bitc::ATTR_KIND_IMMARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab90bb54c98fe726dfded55b337f3cf71">llvm::bitc::ATTR_KIND_IN_ALLOCA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab535e133afc06aad0ae2a4cd2a3ba5b2">llvm::bitc::ATTR_KIND_IN_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a74e8f00480492bc7882bfd1bea39e29a">llvm::bitc::ATTR_KIND_INITIALIZES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a554f2b13f875de1d1b91fae8f22f1219">llvm::bitc::ATTR_KIND_INLINE_HINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad87194f39c5d544c6e47d387fad0087d">llvm::bitc::ATTR_KIND_JUMP_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a32b54e18317d6adae4c3570ecb4737d3">llvm::bitc::ATTR_KIND_MEMORY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1a3eec7201b20fd0a7be025a2c9c4325">llvm::bitc::ATTR_KIND_MIN_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a5ea40b0bf65fb6dfc7c19695921dfa43">llvm::bitc::ATTR_KIND_MUSTPROGRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a458ace7cc504125aa2a1d7160c41e7d4">llvm::bitc::ATTR_KIND_NAKED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4e8e90d675a52048aa4b579214515238">llvm::bitc::ATTR_KIND_NEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad330adbe19c74c6c37c35f4f5e796bc6">llvm::bitc::ATTR_KIND_NO_ALIAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2f56428e2de63871e29676305d87de09">llvm::bitc::ATTR_KIND_NO_BUILTIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1bbfc846a3dd6eeac891c2696da093e6">llvm::bitc::ATTR_KIND_NO_CALLBACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2107a048bcc160f3ff3266424324ea31">llvm::bitc::ATTR_KIND_NO_CAPTURE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2d61eb1531fe7e8040651fc3e40f38c2">llvm::bitc::ATTR_KIND_NO_DIVERGENCE_SOURCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a920b3cacbba0ced6115f2566900e127d">llvm::bitc::ATTR_KIND_NO_DUPLICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa6f71013a7a1d6d14768c4ab9ec3c228">llvm::bitc::ATTR_KIND_NO_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2efc67c46821e4185ae5480eb9dd26cd">llvm::bitc::ATTR_KIND_NO_IMPLICIT_FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3adc9ed5109d2f0dca6fdd2b4bd83c41f7">llvm::bitc::ATTR_KIND_NO_INLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a886acf88e3917643d0bfff579d3d90af">llvm::bitc::ATTR_KIND_NO_MERGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaebb0cdb7703aafd9d1a18dad8824b53">llvm::bitc::ATTR_KIND_NO_PROFILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a34c5bd95f79732a201f966cfc6421ea5">llvm::bitc::ATTR_KIND_NO_RECURSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaa665c4d4c4bc24191c6d60ae71fe62e">llvm::bitc::ATTR_KIND_NO_RED_ZONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a59af608118cf63c82feeb91c9d88b6e2">llvm::bitc::ATTR_KIND_NO_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ae73a1348bfbb82425a20b4f7cc6471f3">llvm::bitc::ATTR_KIND_NO_SANITIZE_BOUNDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad8352b9fa6aa94b6457fe509e811b19f">llvm::bitc::ATTR_KIND_NO_SANITIZE_COVERAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a05dd5faacf5c7eb49825debc35136169">llvm::bitc::ATTR_KIND_NO_UNWIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aac037ec3f3273e872307022405e95ace">llvm::bitc::ATTR_KIND_NOCF_CHECK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac4d3e92d2ef62cf51f31676bd04e5105">llvm::bitc::ATTR_KIND_NOFPCLASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2b4a84f204f2f012d3df4cb8bc60e860">llvm::bitc::ATTR_KIND_NOFREE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a93538315516b14f95e92df987821a58a">llvm::bitc::ATTR_KIND_NON_LAZY_BIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a57d48f7ace267b453bc4d3ad164e58fb">llvm::bitc::ATTR_KIND_NON_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad0259dc9cd682a7b9bc525e92ab94902">llvm::bitc::ATTR_KIND_NOSYNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7e86d7e0b4f5f52a3f2205f8b2b07d26">llvm::bitc::ATTR_KIND_NOUNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a5877603f20796c0153d7ad23b03b2079">llvm::bitc::ATTR_KIND_NULL_POINTER_IS_VALID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6a01a6b667890a3a7fe291b2303729c0">llvm::bitc::ATTR_KIND_OPT_FOR_FUZZING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3afa58e5a377bd47affa71c9573ff393c4">llvm::bitc::ATTR_KIND_OPTIMIZE_FOR_DEBUGGING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a10ccf7458de7661ed59552aa375f91e8">llvm::bitc::ATTR_KIND_OPTIMIZE_FOR_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa695e2248b1cb68eb1afcdc2c5d62491">llvm::bitc::ATTR_KIND_OPTIMIZE_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3afbba6578048f8900e6a59315caba4eb5">llvm::bitc::ATTR_KIND_PREALLOCATED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aced00bf2cc41b0b4b1cd9bed3bf70fc6">llvm::bitc::ATTR_KIND_PRESPLIT_COROUTINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aca4c5725563d1c044a84ec3d4b818a5f">llvm::bitc::ATTR_KIND_RANGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a974c5448b13d159116dfa73138e2058c">llvm::bitc::ATTR_KIND_READ_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3abac7a26689aa32f57183deb05ff4e8b7">llvm::bitc::ATTR_KIND_READ_ONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4d40d2b7ab76139b227d085040438acf">llvm::bitc::ATTR_KIND_RETURNED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6321311fb493fcbb0fbf655bda813424">llvm::bitc::ATTR_KIND_RETURNS_TWICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa08af93fce49bf40ea23e92f7fd99b43">llvm::bitc::ATTR_KIND_S_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a100c3c2639fc32a8d64953a2c29741a5">llvm::bitc::ATTR_KIND_SAFESTACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2e2b64c82183308aa47d372943092e39">llvm::bitc::ATTR_KIND_SANITIZE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a598116e25b929c808e6bd52e35a2be17">llvm::bitc::ATTR_KIND_SANITIZE_HWADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a063fce6939dfcc85c3d919cbb90cdbe1">llvm::bitc::ATTR_KIND_SANITIZE_MEMORY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aeda30207dd431bb2531c9c55972a207d">llvm::bitc::ATTR_KIND_SANITIZE_MEMTAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6d0eb2693e8bacfa8c3265554bb4de39">llvm::bitc::ATTR_KIND_SANITIZE_NUMERICAL_STABILITY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab2f626bb70e4d6ccec7b48c473d06a29">llvm::bitc::ATTR_KIND_SANITIZE_REALTIME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ae376cf8d2b2da2e690cea4abf5d52862">llvm::bitc::ATTR_KIND_SANITIZE_REALTIME_BLOCKING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3af4da5ef4d5aada8b57baf7b42330d168">llvm::bitc::ATTR_KIND_SANITIZE_THREAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3acaeef48f6534f29c49dd9068ae704f89">llvm::bitc::ATTR_KIND_SANITIZE_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6943bf6094f5e2e519172af2be91c182">llvm::bitc::ATTR_KIND_SHADOWCALLSTACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7ef1dd025b0567b904f0da8c0624da9b">llvm::bitc::ATTR_KIND_SKIP_PROFILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3adb2076c2e8152af22f43f8fe939b191a">llvm::bitc::ATTR_KIND_SPECULATABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac1811dc4c110f8e6a942d6e73da1bcc8">llvm::bitc::ATTR_KIND_SPECULATIVE_LOAD_HARDENING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4d708f6ef22af69a714124a9e6d27a29">llvm::bitc::ATTR_KIND_STACK_ALIGNMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a02985b5b9b00d8fcf0c3456548704f89">llvm::bitc::ATTR_KIND_STACK_PROTECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a52eaba8bee5d2693ac99f44de939c95f">llvm::bitc::ATTR_KIND_STACK_PROTECT_REQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a05f5e41019f7c20785c7a657d9f8158c">llvm::bitc::ATTR_KIND_STACK_PROTECT_STRONG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a9128f6d8bce4c0521966580b79757e13">llvm::bitc::ATTR_KIND_STRICT_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1a17ef11f6af6c1c96c256a885d2bba7">llvm::bitc::ATTR_KIND_STRUCT_RET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3afebba069726cfcfaedb609eb2afc411e">llvm::bitc::ATTR_KIND_SWIFT_ASYNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a12f9c8d3abe9eadfc656fd9a2115c7ec">llvm::bitc::ATTR_KIND_SWIFT_ERROR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4dfd1ab23712750b0c4d712ff9aefdb3">llvm::bitc::ATTR_KIND_SWIFT_SELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa1ee732e66faee6f738611e8af19ba32">llvm::bitc::ATTR_KIND_UW_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad34cad71bda2dfd0c79c83a4cfe64523">llvm::bitc::ATTR_KIND_VSCALE_RANGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac847497e79df6980c96592730db17323">llvm::bitc::ATTR_KIND_WILLRETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6c6b4c48a4db5cb8b4dcd7400dc2a767">llvm::bitc::ATTR_KIND_WRITABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa9bcf6b32c733bdfa2e2473fd1f18963">llvm::bitc::ATTR_KIND_WRITEONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a656d32cce3f0da0c87a066dce0a9ae0f">llvm::bitc::ATTR_KIND_Z_EXT</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a>.</p>

</div>
</div>

### getDecodedBinaryOpcode() {#aa52298c6762df1ff42322f0271c646b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getDecodedBinaryOpcode (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1314 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a68d9d8c75aa2cbd98cc3cd6088cd88c3">llvm::bitc::BINOP_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1acecfe220fcf28ba017208977312a468c">llvm::bitc::BINOP_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9a30fed92fd54e316fd32e7e745aeb14">llvm::bitc::BINOP_ASHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9ec979797d756b39ae37a5f2e25a0d38">llvm::bitc::BINOP_LSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1aa4396fd4122548b531cc7177512b139e">llvm::bitc::BINOP_MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9b125c378940a11c60ad335b0e60b1a2">llvm::bitc::BINOP_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1aa4e1b66237a655ae124026c28b26d481">llvm::bitc::BINOP_SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a01aa051969198a4085e944234de2446e">llvm::bitc::BINOP_SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1ac799944d2a5b7b91210b803504e77319">llvm::bitc::BINOP_SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1af044d7456abdac4e41aef374cbb43e12">llvm::bitc::BINOP_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a6fc7d38cbdd784e6f2573ba865138210">llvm::bitc::BINOP_UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a26868218c32dc434e202a4d694ad3f45">llvm::bitc::BINOP_UREM</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1ac6a71c3796edcf421edd6fadb028be68">llvm::bitc::BINOP_XOR</a>.</p>

</div>
</div>

### getDecodedCastOpcode() {#aeb74d50adfdf3a22a186706c3f92f722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getDecodedCastOpcode (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1281 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab8be0ead019884e9180369dcf5ca0470">llvm::bitc::CAST_ADDRSPACECAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a07f83ec620595d592fb799d051ac6e75">llvm::bitc::CAST_BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab585d6900abdafe339c6e9c910035859">llvm::bitc::CAST_FPEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a2d6fc7cca02f499939b68491dff00f58">llvm::bitc::CAST_FPTOSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a84dd2da5c7f3314061ca10f524e7dcb0">llvm::bitc::CAST_FPTOUI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ac7c030dde4055cefd0471ef8fb27038d">llvm::bitc::CAST_FPTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aaa14daa58dc521dbc0ef0a696aa9e6dd">llvm::bitc::CAST_INTTOPTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ad441909766521e384654c38484c6f169">llvm::bitc::CAST_PTRTOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aacc1fb2c439b83d10dd250ff5a2b93f3">llvm::bitc::CAST_SEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a9eaca2882fcf0ec475854e8e5c2279e8">llvm::bitc::CAST_SITOFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aa1a60e212be26cd7a84d0218675285c2">llvm::bitc::CAST_TRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a0aa29b41007b5fbfce2da261d9816978">llvm::bitc::CAST_UITOFP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab1d860827fec09b9116e81923e3f20aa">llvm::bitc::CAST_ZEXT</a>.</p>

</div>
</div>

### getDecodedCodeModel() {#a1a298591ad7fece6fddd690511643d6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CodeModel::Model &gt; getDecodedCodeModel (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1244 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a>.</p>

</div>
</div>

### getDecodedComdatSelectionKind() {#a8aefee473fa8e486202283927b80ac63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Comdat::SelectionKind getDecodedComdatSelectionKind (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1394 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba228d51974aa5c21ba52010a40302a0fc">llvm::bitc::COMDAT_SELECTION_KIND_ANY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba8cfeeb1451c75f879a6876b6beaf6c6d">llvm::bitc::COMDAT_SELECTION_KIND_EXACT_MATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba10c8fffe9e95a186479d54d05cb03507">llvm::bitc::COMDAT_SELECTION_KIND_LARGEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266baa4e0a5bb065b0f0330ec4a9b80b47ca6">llvm::bitc::COMDAT_SELECTION_KIND_NO_DUPLICATES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba78a05db06e72b074e5ff734665534e49">llvm::bitc::COMDAT_SELECTION_KIND_SAME_SIZE</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7">llvm::Comdat::ExactMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8">llvm::Comdat::Largest</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a> and <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce">llvm::Comdat::SameSize</a>.</p>

</div>
</div>

### getDecodedDLLStorageClass() {#a636064b7990868b8867890bcdb3e2b2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::DLLStorageClassTypes getDecodedDLLStorageClass (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1227 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">llvm::GlobalValue::DefaultStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0">llvm::GlobalValue::DLLExportStorageClass</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8aadc8e43e72669932581b5243b4b444b6">llvm::GlobalValue::DLLImportStorageClass</a>.</p>

</div>
</div>

### getDecodedDSOLocal() {#a22fcab89e52afadf10ab18802ba4083a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool getDecodedDSOLocal (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### getDecodedFastMathFlags() {#ab35a64e2f9201e7d20db1ff384218ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags getDecodedFastMathFlags (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1410 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa4601e39685b21855202598fbbbf483c8">llvm::bitc::AllowContract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aaf1a502f88e347fddad4ee0750b994975">llvm::bitc::AllowReassoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aafa457615c7642f4cb8e1758bc6673c09">llvm::bitc::AllowReciprocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa3f8ef5ee785e3c0ea9c691175a6de5b0">llvm::bitc::ApproxFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa7615867f60ad3984f710b758a7fa794a">llvm::bitc::NoInfs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa0b6078f1d27619490c8569776bfaea2f">llvm::bitc::NoNaNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa5570d4f40666e6352950e1e45696cbd2">llvm::bitc::NoSignedZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a17e649128903d9aec55cf75d3c14c545">llvm::FastMathFlags::setAllowContract</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#abd093480248d834428a5e8f9ad5a22dd">llvm::FastMathFlags::setAllowReassoc</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a449c5c7d9356857fe89132ab9223069a">llvm::FastMathFlags::setAllowReciprocal</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#acc2bf5d2312d38f951004a8900fc4f7f">llvm::FastMathFlags::setApproxFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a04a94a2848616d79534531d56bb82bfb">llvm::FastMathFlags::setFast</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#ad5fb387bdc497f49b0f556ed9f900560">llvm::FastMathFlags::setNoInfs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#abbceb1c6e5c4b49f53b381a8fad9e12a">llvm::FastMathFlags::setNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags/#a9b87b2b5c4b6b7d083212a0c93684f72">llvm::FastMathFlags::setNoSignedZeros</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aab9ae7390ca4271aea1cc0fd8ad959ed2">llvm::bitc::UnsafeAlgebra</a>.</p>

</div>
</div>

### getDecodedFFlags() {#a17b0f35cf88f5658433215c49fe12320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionSummary::FFlags getDecodedFFlags (uint64_t RawFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags/#aad73b3ba152f751834bf9a7a02a61cd9">llvm::FunctionSummary::FFlags::ReadNone</a>.</p>

</div>
</div>

### getDecodedGVarFlags() {#a5931832ea87220f401de203134d472bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVarSummary::GVarFlags getDecodedGVarFlags (uint64_t RawFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### getDecodedGVSummaryFlags() {#a4b48eac2502c5d45d4ed09c2d1382ecb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValueSummary::GVFlags getDecodedGVSummaryFlags (uint64_t RawFlags, uint64_t Version)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/globalmergefunctions-h/#a54f7429fa5826ff9909619b76d2bf319a509820290d57f333403f490dde7316f4">Local</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### getDecodedHotnessCallEdgeInfo() {#a1383985111f3dccd6dd84aed125f5881}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; CalleeInfo::HotnessType, bool &gt; getDecodedHotnessCallEdgeInfo (uint64_t RawFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### getDecodedLinkage() {#a9049fa6f0ceaa6bacf0a9bf51c0a2770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::LinkageTypes getDecodedLinkage (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1111 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">llvm::GlobalValue::AppendingLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/modulesummaryindexbitcodereader/#ae9f86888a27590c2d447d2f98b5f7cf8">anonymous{BitcodeReader.cpp}::ModuleSummaryIndexBitcodeReader::parseModule</a>.</p>

</div>
</div>

### getDecodedOrdering() {#a0cdbd26c024d7e2084d0a1a4ed6c2503}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicOrdering getDecodedOrdering (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1381 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a133fea251780f2b0a86a520addd9c184">llvm::bitc::ORDERING_ACQREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a0b468dec37bac00c148e2e9a20711bb9">llvm::bitc::ORDERING_ACQUIRE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077aec3d86ca51de0866abd0fc0d1ec71b9d">llvm::bitc::ORDERING_MONOTONIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a83f6d5a33251a1af65bfd012765dbec7">llvm::bitc::ORDERING_NOTATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a47017037bf5808b06c2cd2e184c55de2">llvm::bitc::ORDERING_RELEASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077ab5a2748be1fde542bf8baeb43f6f44cb">llvm::bitc::ORDERING_SEQCST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a8768765e8f788907885fbd23ae6a8edb">llvm::bitc::ORDERING_UNORDERED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### getDecodedRelBFCallEdgeInfo() {#a08ebdf89a78bb53144d1df14c5475c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getDecodedRelBFCallEdgeInfo (uint64_t RawFlags, uint64_t &amp; RelBF, bool &amp; HasTailCall)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1209 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#afb34a60fa4d1c019369287f0e9e7482f">llvm::CalleeInfo::RelBlockFreqBits</a>.</p>

</div>
</div>

### getDecodedRMWOperation() {#aa7935ff3ae6dbf81e8185937361555a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AtomicRMWInst::BinOp getDecodedRMWOperation (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1352 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">llvm::AtomicRMWInst::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a497e8f347648b1b2823ee0338c95f65f">llvm::AtomicRMWInst::BAD_BINOP</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324">llvm::AtomicRMWInst::FAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">llvm::AtomicRMWInst::FMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">llvm::AtomicRMWInst::FMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4">llvm::AtomicRMWInst::FSub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf3617c1779061deeeae4a24e1c45d015">llvm::bitc::RMW_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa1fffe440fc04d4931be511a6759fb0bf">llvm::bitc::RMW_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa56e0b4e94e457f1abf28de75d156eed2">llvm::bitc::RMW_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf6ff61c0bdbe5ab915efd9cdc1ffb3bc">llvm::bitc::RMW_FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa0f985a5852d333645b18af7dd342b366">llvm::bitc::RMW_FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaae916e663743bef5cdc843ae1fe2bb50">llvm::bitc::RMW_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa0f7c09593b49ad69a24976fd79491ca9">llvm::bitc::RMW_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aafef3e0c3498ab6999f170022e942b675">llvm::bitc::RMW_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf1143967d78add27bf0a34cd120b05b9">llvm::bitc::RMW_NAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa659ec22852b50f1b2907cb553ccd3003">llvm::bitc::RMW_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa7786115a5d20e2d7377870813a8e91fe">llvm::bitc::RMW_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa87c17066a291c0b1ce3d143cb4b33afc">llvm::bitc::RMW_UDEC_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aadfffdd7e9faf02738adc9b4515142386">llvm::bitc::RMW_UINC_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa974e4f980368e5eb72fbc4693ce077bc">llvm::bitc::RMW_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa3458453a8e9b396ca571f9c7ee12b9fd">llvm::bitc::RMW_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa051d138a9600eacf2fe449622150a0c8">llvm::bitc::RMW_USUB_COND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa4d1e7498fe0b00010e93607c187c1c74">llvm::bitc::RMW_USUB_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa172fe635673085e6d5efc03db990e68e">llvm::bitc::RMW_XCHG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa75792f75bfdfd0639c08b8f4a6d7422e">llvm::bitc::RMW_XOR</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">llvm::AtomicRMWInst::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3">llvm::AtomicRMWInst::UDecWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b">llvm::AtomicRMWInst::UIncWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4">llvm::AtomicRMWInst::USubCond</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c">llvm::AtomicRMWInst::USubSat</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>

</div>
</div>

### getDecodedThreadLocalMode() {#aacb15ffa7287b5723c317de2986fe3ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable::ThreadLocalMode getDecodedThreadLocalMode (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1261 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a55e32c080bb5217324a597d4fb441660">llvm::GlobalValue::GeneralDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a92e26a4a1218d351f5a91e7385a3a320">llvm::GlobalValue::InitialExecTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62ac9f6ea05a2d4cca9e093366042dfa6b8">llvm::GlobalValue::LocalDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a41529b6e723f5025e59ca9364cf70128">llvm::GlobalValue::LocalExecTLSModel</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>

</div>
</div>

### getDecodedUnaryOpcode() {#a42193bb1ec0e43f7eaaaabe307874518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int getDecodedUnaryOpcode (unsigned Val, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1300 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a635e5fcb068bb33406c8f4478fec92acaff0bbded1d2517cb24d7d941a40cfd31">llvm::bitc::UNOP_FNEG</a>.</p>

</div>
</div>

### getDecodedUnnamedAddrType() {#a2ff593b38ab7b31e6ddf38bda8011a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable::UnnamedAddr getDecodedUnnamedAddrType (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a509820290d57f333403f490dde7316f4">llvm::GlobalValue::Local</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a6adf97f83acf6453d4a6a4b1070f3754">llvm::GlobalValue::None</a>.</p>

</div>
</div>

### getDecodedVisibility() {#afca97c2660719090403589cd03658cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue::VisibilityTypes getDecodedVisibility (unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1217 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">llvm::GlobalValue::ProtectedVisibility</a>.</p>

</div>
</div>

### getEnableSplitLTOUnitAndUnifiedFlag() {#a3d0c0fef256a92c13760a52971b805b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::pair&lt; bool, bool &gt; &gt; getEnableSplitLTOUnitAndUnifiedFlag (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream, unsigned ID, <a href="/web-llvm/docs/api/structs/llvm/bitcodeltoinfo">BitcodeLTOInfo</a> &amp; LTOInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 8570 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a55da7252b067167e5ec22e4456503e6d">llvm::BitstreamCursor::advanceSkippingSubblocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001bab8c67884cc3a90c02a0a6916d896dd83">llvm::bitc::FS_FLAGS</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodemodule/#a9508697fd741b13841d7563c897e01f3">llvm::BitcodeModule::getLTOInfo</a>.</p>

</div>
</div>

### getRawAttributeMask() {#a46f538c093b0e66e2e1310c5b8c83b88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getRawAttributeMask (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1843 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eaa108685538d49543443a0ce281efd1d8">llvm::Attribute::EmptyKey</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea3e672d8a791835da7d662b61f79590a6">llvm::Attribute::TombstoneKey</a>.</p>


<p>Referenced by <a href="#a88097e7039070e670b83a2f0c420f977">addRawAttributeValue</a>.</p>

</div>
</div>

### getSingleModule() {#aaa1a1464db1a7a577a3c9fb3e76e6f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; BitcodeModule &gt; getSingleModule (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 8680 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84ff19acc1b6cba55e1006e5be8e6453">llvm::getBitcodeModuleList</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a85a0e09494dd27b580bd6100ffe1b39d">llvm::getBitcodeLTOInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6b551037bf3f327d3c280b59de0cace1">llvm::getLazyBitcodeModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59316b66df2176ff19458e2d624b98ad">llvm::getModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a170525c5f5e06bd2555d40a0499b8b6d">llvm::parseBitcodeFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae368e17bfcc41a6bc7891c4c84224c9c">llvm::readModuleSummaryIndex</a>.</p>

</div>
</div>

### hasImplicitComdat() {#a8f6ba1fc9ba48d7ddb59157f4309a134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasImplicitComdat (size_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### hasInvalidBitcodeHeader() {#a95e3a85203eeaf11c26b7161a4557934}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error hasInvalidBitcodeHeader (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#af93d0598951039581a9c4700247d5ee7">llvm::BitstreamCursor::canSkipToPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a455d3003d7f58d83850c9f33c259d3bf">llvm::BitstreamCursor::Read</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#ab5a82b3045c92ee732ddca71ea91a65d">initStream</a>.</p>

</div>
</div>

### hasObjCCategory() {#aac3e993fa38b2fd4caaacd62e4e152a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; hasObjCCategory (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="#a62f979fde2fca6e52e8789ff96ad830e">hasObjCCategoryInModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/dwarfdebug-cpp/#affb04f368f98abaa344a09796faf75b1">getObjCClassCategory</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a286038f4ba044b39a6bb7f86c4c1055c">llvm::isBitcodeContainingObjCCategory</a>.</p>

</div>
</div>

### hasObjCCategoryInModule() {#a62f979fde2fca6e52e8789ff96ad830e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; hasObjCCategoryInModule (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a55da7252b067167e5ec22e4456503e6d">llvm::BitstreamCursor::advanceSkippingSubblocks</a>, <a href="#a2d7d3464870033ae244f10f24678e945">convertToString</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a1af915356ab04e24ff6c7bfba7cf2e7e">llvm::bitc::MODULE_CODE_SECTIONNAME</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#aac3e993fa38b2fd4caaacd62e4e152a4">hasObjCCategory</a>.</p>

</div>
</div>

### inferDSOLocal() {#ab084a1deda97f9a90c7c8074c4e6ac6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void inferDSOLocal (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4051 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3e6237ebf8cf834ae6fa726efccaef8d">llvm::GlobalValue::hasDefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a51af265dc931258cdb8ffb37ee6decee">llvm::GlobalValue::hasExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a78c4d0538c7dbffa955486abae2b61bb">llvm::GlobalValue::setDSOLocal</a>.</p>

</div>
</div>

### initStream() {#ab5a82b3045c92ee732ddca71ea91a65d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; BitstreamCursor &gt; initStream (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> Buffer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a2036a4973d159e49dcc471488205656f">llvm::MemoryBufferRef::getBufferSize</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a62b2843b74e5f05930ebf5c63766a668">llvm::MemoryBufferRef::getBufferStart</a>, <a href="#a95e3a85203eeaf11c26b7161a4557934">hasInvalidBitcodeHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4600455d814c9fad71f2da0ab5d7b33">llvm::isBitcodeWrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac0fd79668dfc1a7627b754817553138f">llvm::SkipBitcodeWrapperHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a08a94dbba4f43e928c1d2bff541529">llvm::getBitcodeProducerString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a36ecc78d5979c7c250c9284a5211041d">llvm::getBitcodeTargetTriple</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a286038f4ba044b39a6bb7f86c4c1055c">llvm::isBitcodeContainingObjCCategory</a>.</p>

</div>
</div>

### isConstExprSupported() {#ae94b0d68e3880f919a56af17f7c40a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isConstExprSupported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BitcodeConstant * BC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1511 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="#abd17dd727afda35058727b3cd0428722">ExpandConstantExprs</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant/#abdc1c807247aef4be6fb6223ac66a738">anonymous{BitcodeReader.cpp}::BitcodeConstant::FirstSpecialOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a5c88132322ca3f46f242f7c023a57010">llvm::Instruction::isBinaryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a27997849d8982bf226891024fd68daee">llvm::Instruction::isCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab9be98d67001621cd40aa83ba3821740">llvm::ConstantExpr::isSupportedBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#aedb2a667fb397ab70f0f8374b7fc453e">llvm::ConstantExpr::isSupportedCastOp</a> and <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a7baf4632513de0fccabc65793c6b8dae">llvm::ConstantExpr::isSupportedGetElementPtr</a>.</p>

</div>
</div>

### jumpToValueSymbolTable() {#a5fca99afcf20fdf62a04843e8825d03f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; jumpToValueSymbolTable (uint64_t Offset, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to note and return the current location, and jump to the given offset.</p>

<p>Definition at line 2905 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a1dfc6241f79207e8c0a44d6c2ffb0801">llvm::BitstreamCursor::GetCurrentBitNo</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a003287dcd6e4d73526b117b2709e2347">llvm::BitstreamCursor::JumpToBit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933dad03d0513adaa3462afbc7be6241b7db2">llvm::bitc::VALUE_SYMTAB_BLOCK_ID</a>.</p>

</div>
</div>

### parseTypeIdSummaryRecord() {#a79b49cae32dc65f1026c9202d100da6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseTypeIdSummaryRecord (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Strtab, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; TheIndex)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7516 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#ad43ecb12669b6fda67694c153847ebdd">llvm::TypeTestResolution::AlignLog2</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a742493488e02c32e595b0052a4c247d5">llvm::TypeTestResolution::BitMask</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex/#a06ec58fca119b03f6ffea51610851571">llvm::ModuleSummaryIndex::getOrInsertTypeIdSummary</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#ad940f79d8b859f1b9bdbc4df5b9bda75">llvm::TypeTestResolution::InlineBits</a>, <a href="#aaffdb3054263427a7df8fdac667a0c5b">parseWholeProgramDevirtResolution</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a4f7d657b28994fc8695b080cb20b1c97">llvm::TypeTestResolution::SizeM1</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a453599f2782c97d48d8bcedf6f75122d">llvm::TypeTestResolution::SizeM1BitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a66ff82a2443a6f422cd95843084564f6">llvm::TypeTestResolution::TheKind</a> and <a href="/web-llvm/docs/api/structs/llvm/typeidsummary/#a80bc0b8f2041f3a3839f393f1a6aae33">llvm::TypeIdSummary::TTRes</a>.</p>

</div>
</div>

### parseWholeProgramDevirtResolution() {#aaffdb3054263427a7df8fdac667a0c5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseWholeProgramDevirtResolution (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Strtab, size_t &amp; Slot, <a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> &amp; TypeId)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7500 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a46bea8d236da27677962598b5bd45703">parseWholeProgramDevirtResolutionByArg</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ab97c12959c5cc7b46b115da7e1ac5047">llvm::WholeProgramDevirtResolution::SingleImplName</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a11bddbadb47e3bd7803ded5d4f4248fc">llvm::WholeProgramDevirtResolution::TheKind</a> and <a href="/web-llvm/docs/api/structs/llvm/typeidsummary/#a01d5759cee861fcfca3b26ff5927e83c">llvm::TypeIdSummary::WPDRes</a>.</p>


<p>Referenced by <a href="#a79b49cae32dc65f1026c9202d100da6f">parseTypeIdSummaryRecord</a>.</p>

</div>
</div>

### parseWholeProgramDevirtResolutionByArg() {#a46bea8d236da27677962598b5bd45703}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseWholeProgramDevirtResolutionByArg (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Record, size_t &amp; Slot, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &amp; Wpd)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7486 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a1c0a0ec1654585583572f16e799176dc">llvm::WholeProgramDevirtResolution::ResByArg</a>.</p>


<p>Referenced by <a href="#aaffdb3054263427a7df8fdac667a0c5b">parseWholeProgramDevirtResolution</a>.</p>

</div>
</div>

### readBlobInRecord() {#ad3dcdf576f07a261c70f7eac121b3eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; readBlobInRecord (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream, unsigned Block, unsigned RecordID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 8321 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3a73888ec542d14d981f9b9c49c247fa">llvm::getBitcodeFileContents</a>.</p>

</div>
</div>

### readIdentificationBlock() {#adfdf631a8d0d417904f24c6ff6d9ed03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; readIdentificationBlock (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read the "IDENTIFICATION_BLOCK_ID" block, do some basic enforcement on the "epoch" encoded in the bitcode, and return the producer name if any.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a298addd8bf1eaddaaebcec3640429188a7f66f39da99244fad39ebe115c4053a0">llvm::bitc::BITCODE_CURRENT_EPOCH</a>, <a href="#a2d7d3464870033ae244f10f24678e945">convertToString</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da574b2844e8b4baab9239f12c1b6b0d04">llvm::bitc::IDENTIFICATION_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2dde66e038f5a0836d72e760f731a4b4ab33f9d97fa7abd55725a6a62e6250bd1">llvm::bitc::IDENTIFICATION_CODE_EPOCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2dde66e038f5a0836d72e760f731a4b4ad0b7a34426fe13ee6793888a32698b4e">llvm::bitc::IDENTIFICATION_CODE_STRING</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a9f6235e5cdcd03f0d0dbb533debac0d9">readIdentificationCode</a>.</p>

</div>
</div>

### readIdentificationCode() {#a9f6235e5cdcd03f0d0dbb533debac0d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; readIdentificationCode (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a0b2540236df88a84a8b8ea3f7158ae47">llvm::BitstreamCursor::AtEndOfStream</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da574b2844e8b4baab9239f12c1b6b0d04">llvm::bitc::IDENTIFICATION_BLOCK_ID</a>, <a href="#adfdf631a8d0d417904f24c6ff6d9ed03">readIdentificationBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a> and <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6a08a94dbba4f43e928c1d2bff541529">llvm::getBitcodeProducerString</a>.</p>

</div>
</div>

### readModuleTriple() {#afa9c01a1d03b3af4714df3976056d46b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; readModuleTriple (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a55da7252b067167e5ec22e4456503e6d">llvm::BitstreamCursor::advanceSkippingSubblocks</a>, <a href="#a2d7d3464870033ae244f10f24678e945">convertToString</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a6ced3cd5539e8a620f270f3dbb0c48ab">llvm::BitstreamCursor::EnterSubBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a9d51b2066d2ce0b9fe4f39f1a80f7c81a61ad593c7421c65ebeb897f01da8b8bf">llvm::bitc::MODULE_CODE_TRIPLE</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a677592abe148dbc3de1ec00f3d9904c5">llvm::BitstreamCursor::readRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a42cc3ae15d37346d7ca743801b572770">readTriple</a>.</p>

</div>
</div>

### readTriple() {#a42cc3ae15d37346d7ca743801b572770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; readTriple (<a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor">BitstreamCursor</a> &amp; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a49c750caac5ed5f8a5333e14ada8d5ed">llvm::BitstreamCursor::advance</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea69bcb0a249ff563515ad5c77bc19ebfe">llvm::BitstreamEntry::EndBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaff48a2349df5a9fe16c80d1d6e32e479">llvm::BitstreamEntry::Error</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da31e5f441b78348934094a9dde0a326e2">llvm::bitc::MODULE_BLOCK_ID</a>, <a href="#afa9c01a1d03b3af4714df3976056d46b">readModuleTriple</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1cea05d3cc255293715b2712b9bbdfc6011c">llvm::BitstreamEntry::Record</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a73257c6f5ab8032f22e06c1da0bc109f">llvm::BitstreamCursor::SkipBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamcursor/#a8b13d5acaf9ffcc5a0f9969888a7db33">llvm::BitstreamCursor::skipRecord</a>, <a href="/web-llvm/docs/api/structs/llvm/bitstreamentry/#aabd7d39bf1ac32328fce0cb152a9f1ceaac45aef6d995e5c810f2824a40fb1e2a">llvm::BitstreamEntry::SubBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a36ecc78d5979c7c250c9284a5211041d">llvm::getBitcodeTargetTriple</a>.</p>

</div>
</div>

### setSpecialRefs() {#a1ab33fa6fa7130c1c532556fcbddb32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setSpecialRefs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &gt; &amp; Refs, unsigned ROCnt, unsigned WOCnt)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 7633 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>

</div>
</div>

### stripTBAA() {#a32c765cabc6bab63ba8691a789db738b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void stripTBAA (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>.</p>

</div>
</div>

### toGEPNoWrapFlags() {#a66c221eaf3589701aa0fa16c6cd61407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags toGEPNoWrapFlags (uint64_t Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1500 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a33a73a3b8d28548e6e3216801bf93207a1d40dfa2a367a9a21810697c5cfc136a">llvm::bitc::GEP_INBOUNDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a33a73a3b8d28548e6e3216801bf93207acd28ff8cbc5d1a5526f142fb27c6c6a3">llvm::bitc::GEP_NUSW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a33a73a3b8d28548e6e3216801bf93207aa12e0bcbdd56def413c412f7ba95bd37">llvm::bitc::GEP_NUW</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a0c32878bcc6e7bc1ac1e5fbcb1707591">llvm::GEPNoWrapFlags::inBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a794ead7ef727f6a684c5695b27040c67">llvm::GEPNoWrapFlags::noUnsignedSignedWrap</a> and <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a5bfde791508b16caf8509e95a8fdf7b9">llvm::GEPNoWrapFlags::noUnsignedWrap</a>.</p>

</div>
</div>

### upgradeDLLImportExportLinkage() {#a0ab0b4e3b20c68f71d543a2eb6a32ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void upgradeDLLImportExportLinkage (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV, unsigned Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1431 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0">llvm::GlobalValue::DLLExportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8aadc8e43e72669932581b5243b4b444b6">llvm::GlobalValue::DLLImportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3ba1af4b9d9faa4a33729bbbecee83d1">llvm::GlobalValue::hasLocalLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a40c699aba3d6b469357ef0b4e1aa2580">llvm::GlobalValue::setDLLStorageClass</a>.</p>

</div>
</div>

### upgradeOldMemoryAttribute() {#ad2a3a2ebeb9f0ceca766759a20ba60ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool upgradeOldMemoryAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a> &amp; ME, uint64_t EncodedKind)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2275 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5288b2ba178703d9e1f24a5d3708f594">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::argMemOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a76a225ab7641d99b9cc6b37fadc2f2cf">llvm::bitc::ATTR_KIND_ARGMEMONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a13ec7512d1a12c9a7593d91ce75e3be1">llvm::bitc::ATTR_KIND_INACCESSIBLEMEM_ONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4f31d5615da59be5df769d12d08a3565">llvm::bitc::ATTR_KIND_INACCESSIBLEMEM_OR_ARGMEMONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a974c5448b13d159116dfa73138e2058c">llvm::bitc::ATTR_KIND_READ_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3abac7a26689aa32f57183deb05ff4e8b7">llvm::bitc::ATTR_KIND_READ_ONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa9bcf6b32c733bdfa2e2473fd1f18963">llvm::bitc::ATTR_KIND_WRITEONLY</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5cba4a49c183c6c2f6168be64f04a7b9">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleMemOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#ad341f584befc40ff0aefca99682baf7c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleOrArgMemOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a0dc1a3456bce25673dff8dce6f240a8f">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::readOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a9e3dc568b5f51e03441c9c44b618f337">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::writeOnly</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ExpandConstantExprs {#abd17dd727afda35058727b3cd0428722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; ExpandConstantExprs("expand-constant-exprs", cl::Hidden, cl::desc( "Expand constant expressions to instructions for testing purposes"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>


<p>Referenced by <a href="#ae94b0d68e3880f919a56af17f7c40a73">isConstExprSupported</a>.</p>

</div>
</div>

### LoadBitcodeIntoNewDbgInfoFormat {#a87c1181cf1d0d961944966c346a3564a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; cl::boolOrDefault &gt; LoadBitcodeIntoNewDbgInfoFormat("load-bitcode-into-experimental-debuginfo-iterators", cl::Hidden, cl::desc("Load bitcode directly into the new debug info format (regardless " "of input format)"))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load bitcode directly into RemoveDIs format (use debug records instead of debug intrinsics).</p>


<p>UNSET is treated as FALSE, so the default action is to do nothing. Individual tools can override this to incrementally add support for the RemoveDIs format.</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### PreserveInputDbgFormat {#a1eee5efdaf0acfd7e7be22a487088c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;cl::boolOrDefault&gt; PreserveInputDbgFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### PrintSummaryGUIDs {#a0cd7a38fa5e33363b919a3cd6aa23b08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; PrintSummaryGUIDs("print-summary-global-ids", cl::init(false), cl::Hidden, cl::desc( "Print the global id for each value when reading the module summary"))</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### UseNewDbgInfoFormat {#aecfc696c759c52249220099347df84da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; UseNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### WriteNewDbgInfoFormat {#a71ef03caf2222804098e7c78eb0e39dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt;bool&gt; WriteNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>.</p>

</div>
</div>

### WriteNewDbgInfoFormatToBitcode {#a88d24bcd4c11f1c3237941d712ed3284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool WriteNewDbgInfoFormatToBitcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp">BitcodeReader.cpp</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
