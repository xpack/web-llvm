---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `BitcodeWriter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodewriter-h">llvm/Bitcode/BitcodeWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/valueenumerator-h">ValueEnumerator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringmap-h">llvm/ADT/StringMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodecommon-h">llvm/Bitcode/BitcodeCommon.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/bitcodereader-h">llvm/Bitcode/BitcodeReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitcode/llvmbitcodes-h">llvm/Bitcode/LLVMBitCodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitcodes-h">llvm/Bitstream/BitCodes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/bitstream/bitstreamwriter-h">llvm/Bitstream/BitstreamWriter.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">llvm/IR/Comdat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">llvm/IR/ConstantRangeList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugloc-h">llvm/IR/DebugLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalifunc-h">llvm/IR/GlobalIFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/uselistorder-h">llvm/IR/UseListOrder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">llvm/IR/ValueSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/stringtablebuilder-h">llvm/MC/StringTableBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/irsymtab-h">llvm/Object/IRSymtab.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprof-h">llvm/ProfileData/MemProf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/atomicordering-h">llvm/Support/AtomicOrdering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/endian-h">llvm/Support/Endian.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sha1-h">llvm/Support/SHA1.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/triple-h">llvm/TargetParser/Triple.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;map&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
#include "llvm/IR/Metadata.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-bitcodewriter-cpp-">anonymous{BitcodeWriter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase">BitcodeWriterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract class to manage the bitcode writing, subclassed for each bitcode file type. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/bitcodewriterbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase">ModuleBitcodeWriterBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class to manage the module bitcode writing, currently subclassed for <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a>. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter">ModuleBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a module. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter">IndexBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a combined index. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/indexbitcodewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter">ThinLinkBitcodeWriter</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class to manage the bitcode writing for a thin link bitcode file. <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/thinlinkbitcodewriter/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StringEncoding { <a href="#a3172cb0288d425ec480fb1e09f33b340">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MetadataAbbrev : unsigned { <a href="#af29f8d29920f8bbbab2ffd4bada693d0">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742dfa2fe7c03d9a1d16809dabb28d24">getEncodedCastOpcode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196e56f0349ef0faab66e90bc5d692bc">getEncodedUnaryOpcode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa64fbea0aa72356b8a21325912cb482">getEncodedBinaryOpcode</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63671ba30c39a0f6b0a5d03987eab820">getEncodedRMWOperation</a> (AtomicRMWInst::BinOp Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de734ed7f3bfddcdf0f612ba0799524">getEncodedOrdering</a> (AtomicOrdering Ordering)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad375d674219d643fe0ba85db2b7f172a">writeStringRecord</a> (BitstreamWriter &amp;Stream, unsigned Code, StringRef Str, unsigned AbbrevToUse)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12878f0b1cac777ce77109412ad3edff">getAttrKindEncoding</a> (Attribute::AttrKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2706d140844a6517f06fd552269a7aba">emitSignedInt64</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Vals, uint64_t V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad01068bdc00aaaf836419b53ccaf4b64">emitWideAPInt</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Vals, const APInt &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;Record, const ConstantRange &amp;CR, bool EmitBitWidth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a592963eb7d9c5f3f2601453232ee79f7">getEncodedLinkage</a> (const GlobalValue::LinkageTypes Linkage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa88d9de56393e21d759a360f4b4948c0">getEncodedLinkage</a> (const GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe6f580fa0cd5a5440bedd9caa5aa7a">getEncodedFFlags</a> (FunctionSummary::FFlags Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a4f77790cdf2a3857c91b5547743ea8">getEncodedGVSummaryFlags</a> (GlobalValueSummary::GVFlags Flags, bool ImportAsDecl=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2bdd6d7266a1d93028e8103ca09898f">getEncodedGVarFlags</a> (GlobalVarSummary::GVarFlags Flags)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace8fa717066f0a4ba5a2aab2cbc24d71">getEncodedHotnessCallEdgeInfo</a> (const CalleeInfo &amp;CI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92aacec4c813842a5686cf1f2a7ee8c8">getEncodedRelBFCallEdgeInfo</a> (const CalleeInfo &amp;CI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a7e88942eb67dbe7eb580dbdf75c648">getEncodedVisibility</a> (const GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c40040698f75dfff1fd6bb991c9ff8">getEncodedDLLStorageClass</a> (const GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d62b881d3a85b6b75b5c8153c8f693">getEncodedThreadLocalMode</a> (const GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a894ba697fde8dbcd0583f9eb684bc714">getEncodedComdatSelectionKind</a> (const Comdat &amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb389ba93facff2787add2c58128fcb">getEncodedUnnamedAddr</a> (const GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a3172cb0288d425ec480fb1e09f33b340">StringEncoding</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1bea7f5f828e03912c962c96e4e5e35">getStringEncoding</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the encoding to use for the given string name and length. <a href="#aa1bea7f5f828e03912c962c96e4e5e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08e573712fd20f9e30d20e581fb6f091">serializeSanitizerMetadata</a> (const GlobalValue::SanitizerMetadata &amp;Meta)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a513e443b4a433b36c8d325032a2fbc1c">getOptimizationFlags</a> (const Value *V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Fn&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac7e865e854ff6b0ba0eb2147e0ccb5cc">writeFunctionTypeMetadataRecords</a> (BitstreamWriter &amp;Stream, FunctionSummary *FS, Fn GetValueID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write the function type metadata related records that need to appear before a function summary entry (whether per-module or combined). <a href="#ac7e865e854ff6b0ba0eb2147e0ccb5cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110547082315f2a6d3b983698f89df88">getReferencedTypeIds</a> (FunctionSummary *FS, std::set&lt; GlobalValue::GUID &gt; &amp;ReferencedTypeIds)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect type IDs from type tests used by function. <a href="#a110547082315f2a6d3b983698f89df88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b4150a46b836d772425ab620d97e23">writeWholeProgramDevirtResolutionByArg</a> (SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, const std::vector&lt; uint64_t &gt; &amp;args, const WholeProgramDevirtResolution::ByArg &amp;ByArg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a> (SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, StringTableBuilder &amp;StrtabBuilder, uint64_t Id, const WholeProgramDevirtResolution &amp;Wpd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5a65c8b873ba60af3d6927d70551cc4">writeTypeIdSummaryRecord</a> (SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, StringTableBuilder &amp;StrtabBuilder, StringRef Id, const TypeIdSummary &amp;Summary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fcb5b0c8740137c1ba7ea67bc4e1986">writeTypeIdCompatibleVtableSummaryRecord</a> (SmallVector&lt; uint64_t, 64 &gt; &amp;NameVals, StringTableBuilder &amp;StrtabBuilder, StringRef Id, const TypeIdCompatibleVtableInfo &amp;Summary, ValueEnumerator &amp;VE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1871554e8a3734782e7f7a145cc17491">collectMemProfCallStacks</a> (FunctionSummary *FS, std::function&lt; LinearFrameId(unsigned)&gt; GetStackIndex, MapVector&lt; CallStackId, llvm::SmallVector&lt; LinearFrameId &gt; &gt; &amp;CallStacks)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a271f954222d61bd5dc7f5cb5dd836b52">LinearCallStackId</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddafba4af9c27c785a0d873fd3cb661">writeMemoryProfileRadixTree</a> (MapVector&lt; CallStackId, llvm::SmallVector&lt; LinearFrameId &gt; &gt; &amp;&amp;CallStacks, BitstreamWriter &amp;Stream, unsigned RadixAbbrev)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0850c8a2472500d4a79b9f48495a1d2f">writeFunctionHeapProfileRecords</a> (BitstreamWriter &amp;Stream, FunctionSummary *FS, unsigned CallsiteAbbrev, unsigned AllocAbbrev, unsigned ContextIdAbbvId, bool PerModule, std::function&lt; unsigned(const ValueInfo &amp;VI)&gt; GetValueID, std::function&lt; unsigned(unsigned)&gt; GetStackIndex, bool WriteContextSizeInfoIndex, DenseMap&lt; CallStackId, LinearCallStackId &gt; &amp;CallStackPos, CallStackId &amp;CallStackCount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71e02e853cce26400683e76984e82529">writeIdentificationBlock</a> (BitstreamWriter &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the "IDENTIFICATION_BLOCK_ID" containing a single string with the current llvm version, and a record for the epoch number. <a href="#a71e02e853cce26400683e76984e82529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1886b67a152078f035dc14be966dc8b">writeInt32ToBuffer</a> (uint32_t Value, SmallVectorImpl&lt; char &gt; &amp;Buffer, uint32_t &amp;Position)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea1d38f4a65135188eb7409818070e6">emitDarwinBCHeaderAndTrailer</a> (SmallVectorImpl&lt; char &gt; &amp;Buffer, const Triple &amp;TT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If generating a bc file on darwin, we have to emit a header and trailer to make it compatible with the system archiver. <a href="#a8ea1d38f4a65135188eb7409818070e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90f3f0ae5027fb62fc0090c0b0722d0f">writeBitcodeHeader</a> (BitstreamWriter &amp;Stream)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to write the header common to all bitcode files. <a href="#a90f3f0ae5027fb62fc0090c0b0722d0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af584ab078aff102fb30fcb68f1d64681">getSectionNameForBitcode</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa4c216848cbc41c0e519b84ced70579">getSectionNameForCommandline</a> (const Triple &amp;T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab937b5cbd57983fceac42c85eb831711">IndexThreshold</a>("bitcode-mdindex-threshold", cl::Hidden, cl::init(25), cl::desc("Number of metadatas above which we emit an index " "to enable lazy-loading"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4f14026a779acb2eda1e8107a62f24">FlushThreshold</a>("bitcode-flush-threshold", cl::Hidden, cl::init(512), cl::desc("The threshold (unit M) for flushing LLVM bitcode."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77a0d10689d50ceb5e955bc16121f3fa">WriteRelBFToSummary</a>("write-relbf-to-summary", cl::Hidden, cl::init(false), cl::desc("Write relative block frequency to function summary "))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cl/opt">llvm::cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a926189935285d6e5df83fc0f45bf9b36">UseNewDbgInfoFormat</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4060cc153ca27a61adf713615161fba3">HANDLE_MDNODE_LEAF</a>(CLASS)&nbsp;&nbsp;&nbsp;CLASS##AbbrevID,</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32240e87649f32aceeda23ea6499c4c">HANDLE_MDNODE_LEAF</a>(CLASS)&nbsp;&nbsp;&nbsp;unsigned CLASS##Abbrev = 0;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f378efe7b9888496956feb63c04314f">HANDLE_MDNODE_LEAF</a>(CLASS)&nbsp;&nbsp;&nbsp;...</td>
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

## Enumerations

### MetadataAbbrev {#af29f8d29920f8bbbab2ffd4bada693d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum MetadataAbbrev : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastPlusOne<a id="af29f8d29920f8bbbab2ffd4bada693d0a5d55521f67d67cacb8cfb91a5a983305"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 2393 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### StringEncoding {#a3172cb0288d425ec480fb1e09f33b340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum StringEncoding </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SE_Char6<a id="a3172cb0288d425ec480fb1e09f33b340a1937ce2d6b3aa788b1243878eb87b849"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SE_Fixed7<a id="a3172cb0288d425ec480fb1e09f33b340a86044faf6bf8662d099b43b3113eb7fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SE_Fixed8<a id="a3172cb0288d425ec480fb1e09f33b340a8d011ea49c4af540b560afd62e786365"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### collectMemProfCallStacks() {#a1871554e8a3734782e7f7a145cc17491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void collectMemProfCallStacks (<a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ac8f2e9a6f336bcafc02bbe895a6bf6db">LinearFrameId</a>(unsigned)&gt; GetStackIndex, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ac8f2e9a6f336bcafc02bbe895a6bf6db">LinearFrameId</a> &gt; &gt; &amp; CallStacks)</td>
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



<p>Definition at line 4212 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### emitConstantRange() {#a9a8a25b1415233054e701dd7a05594a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitConstantRange (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Record, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR, bool EmitBitWidth)</td>
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



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a2706d140844a6517f06fd552269a7aba">emitSignedInt64</a>, <a href="#ad01068bdc00aaaf836419b53ccaf4b64">emitWideAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#ad2c2b7a1d52ade8885995a54205a923b">llvm::APInt::getActiveWords</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ad7f81241f958a1f5917a3410942d3199">llvm::ConstantRange::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af2daa0ee117afefed4c82eee55bf97b7">llvm::APInt::getSExtValue</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a>.</p>

</div>
</div>

### emitDarwinBCHeaderAndTrailer() {#a8ea1d38f4a65135188eb7409818070e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitDarwinBCHeaderAndTrailer (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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

<p>If generating a bc file on darwin, we have to emit a header and trailer to make it compatible with the system archiver.</p>


<p>To do this we emit the following header, and then emit a trailer that pads the file out to be a multiple of 16 bytes.</p>


<p>struct bc_header { uint32_t Magic; // 0x0B17C0DE uint32_t Version; // Version, currently always 0. uint32_t BitcodeOffset; // Offset to traditional bitcode file. uint32_t BitcodeSize; // Size of traditional bitcode file. uint32_t CPUType; // CPU specifier. ... potentially more later ... };</p>


<p>Definition at line 5209 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a8b312a985e2504366d24a2200faf37ff">llvm::Triple::arm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35ecf782614a4d3dd4fce5c373c25be5aa0bac122dc15039041afae282817da50">llvm::BWH_HeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab22bd0f2fbea54c80774becf8d6aa704">llvm::Triple::ppc</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154aab15cb6de66f724829436a3466411993">llvm::Triple::ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154ab456eadbc2378864e9aa9e2a545a1e65">llvm::Triple::thumb</a>, <a href="#af1886b67a152078f035dc14be966dc8b">writeInt32ToBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a0eefa3e53db25b90828e42c64b138648">llvm::Triple::x86</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>.</p>

</div>
</div>

### emitSignedInt64() {#a2706d140844a6517f06fd552269a7aba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitSignedInt64 (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Vals, uint64_t V)</td>
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



<p>Definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a>, <a href="#ad01068bdc00aaaf836419b53ccaf4b64">emitWideAPInt</a> and <a href="#ac7e865e854ff6b0ba0eb2147e0ccb5cc">writeFunctionTypeMetadataRecords</a>.</p>

</div>
</div>

### emitWideAPInt() {#ad01068bdc00aaaf836419b53ccaf4b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void emitWideAPInt (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Vals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; A)</td>
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



<p>Definition at line 934 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a2706d140844a6517f06fd552269a7aba">emitSignedInt64</a>.</p>


<p>Referenced by <a href="#a9a8a25b1415233054e701dd7a05594a4">emitConstantRange</a>.</p>

</div>
</div>

### getAttrKindEncoding() {#a12878f0b1cac777ce77109412ad3edff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getAttrKindEncoding (Attribute::AttrKind Kind)</td>
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



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3abadb9d66c19008e4ddb353c55d2c28e2">llvm::bitc::ATTR_KIND_ALIGNMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a929955dc4b9681ed9cec5bc1ff962391">llvm::bitc::ATTR_KIND_ALLOC_ALIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a85f1c987a4cab98ae2d3cf15c46a5533">llvm::bitc::ATTR_KIND_ALLOC_KIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a512cc01a3fa4c51809cb905de3d30b4c">llvm::bitc::ATTR_KIND_ALLOC_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7a1023f40b7fdf89b8359106f07ce88d">llvm::bitc::ATTR_KIND_ALLOCATED_POINTER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac21e10518d20fe0353e65cca06bd5256">llvm::bitc::ATTR_KIND_ALWAYS_INLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a86f312d48859fc97a288d8718d4e4e81">llvm::bitc::ATTR_KIND_BUILTIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa3b7dab5234bc2c00ecd7e64878b715d">llvm::bitc::ATTR_KIND_BY_VAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a13b920c66e426fedc360a03dc19ae6b0">llvm::bitc::ATTR_KIND_BYREF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3af3a622a12140d6cfa18c6994cb9b93c5">llvm::bitc::ATTR_KIND_CAPTURES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6b5c1960ea5bf27bae724fbe40458671">llvm::bitc::ATTR_KIND_COLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a3b0c92f3637b859b97dd9575a33ffec9">llvm::bitc::ATTR_KIND_CONVERGENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a85c70a265e696fc216e55f0e6a0d3935">llvm::bitc::ATTR_KIND_CORO_ELIDE_SAFE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3af37c451700ab8aaad90854ec4b50a980">llvm::bitc::ATTR_KIND_CORO_ONLY_DESTROY_WHEN_COMPLETE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a3794a1f268da39dfa1c0815d936ae616">llvm::bitc::ATTR_KIND_DEAD_ON_UNWIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a94f778cea4955c8d871aa0ebc22b4852">llvm::bitc::ATTR_KIND_DEREFERENCEABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaec534c7d966b2ce46814f56cee8d88a">llvm::bitc::ATTR_KIND_DEREFERENCEABLE_OR_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7d923675347db880195935dd2859430b">llvm::bitc::ATTR_KIND_DISABLE_SANITIZER_INSTRUMENTATION</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a84639710ca4a56d99d1ada67fa19c40f">llvm::bitc::ATTR_KIND_ELEMENTTYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a289e17c3ab627b09ba25a1fdd4fd4dea">llvm::bitc::ATTR_KIND_FNRETTHUNK_EXTERN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ae09a861f046502814ccc8a1805966955">llvm::bitc::ATTR_KIND_HOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa9f6b695559a1f0368d1942031e4743b">llvm::bitc::ATTR_KIND_HYBRID_PATCHABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a8333f888d39f2fc0d6f18a96a16d902b">llvm::bitc::ATTR_KIND_IMMARG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab90bb54c98fe726dfded55b337f3cf71">llvm::bitc::ATTR_KIND_IN_ALLOCA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab535e133afc06aad0ae2a4cd2a3ba5b2">llvm::bitc::ATTR_KIND_IN_REG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a74e8f00480492bc7882bfd1bea39e29a">llvm::bitc::ATTR_KIND_INITIALIZES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a554f2b13f875de1d1b91fae8f22f1219">llvm::bitc::ATTR_KIND_INLINE_HINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad87194f39c5d544c6e47d387fad0087d">llvm::bitc::ATTR_KIND_JUMP_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a32b54e18317d6adae4c3570ecb4737d3">llvm::bitc::ATTR_KIND_MEMORY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1a3eec7201b20fd0a7be025a2c9c4325">llvm::bitc::ATTR_KIND_MIN_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a5ea40b0bf65fb6dfc7c19695921dfa43">llvm::bitc::ATTR_KIND_MUSTPROGRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a458ace7cc504125aa2a1d7160c41e7d4">llvm::bitc::ATTR_KIND_NAKED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4e8e90d675a52048aa4b579214515238">llvm::bitc::ATTR_KIND_NEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad330adbe19c74c6c37c35f4f5e796bc6">llvm::bitc::ATTR_KIND_NO_ALIAS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2f56428e2de63871e29676305d87de09">llvm::bitc::ATTR_KIND_NO_BUILTIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1bbfc846a3dd6eeac891c2696da093e6">llvm::bitc::ATTR_KIND_NO_CALLBACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2107a048bcc160f3ff3266424324ea31">llvm::bitc::ATTR_KIND_NO_CAPTURE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2d61eb1531fe7e8040651fc3e40f38c2">llvm::bitc::ATTR_KIND_NO_DIVERGENCE_SOURCE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a920b3cacbba0ced6115f2566900e127d">llvm::bitc::ATTR_KIND_NO_DUPLICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa6f71013a7a1d6d14768c4ab9ec3c228">llvm::bitc::ATTR_KIND_NO_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2efc67c46821e4185ae5480eb9dd26cd">llvm::bitc::ATTR_KIND_NO_IMPLICIT_FLOAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3adc9ed5109d2f0dca6fdd2b4bd83c41f7">llvm::bitc::ATTR_KIND_NO_INLINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a886acf88e3917643d0bfff579d3d90af">llvm::bitc::ATTR_KIND_NO_MERGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaebb0cdb7703aafd9d1a18dad8824b53">llvm::bitc::ATTR_KIND_NO_PROFILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a34c5bd95f79732a201f966cfc6421ea5">llvm::bitc::ATTR_KIND_NO_RECURSE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aaa665c4d4c4bc24191c6d60ae71fe62e">llvm::bitc::ATTR_KIND_NO_RED_ZONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a59af608118cf63c82feeb91c9d88b6e2">llvm::bitc::ATTR_KIND_NO_RETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ae73a1348bfbb82425a20b4f7cc6471f3">llvm::bitc::ATTR_KIND_NO_SANITIZE_BOUNDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad8352b9fa6aa94b6457fe509e811b19f">llvm::bitc::ATTR_KIND_NO_SANITIZE_COVERAGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a05dd5faacf5c7eb49825debc35136169">llvm::bitc::ATTR_KIND_NO_UNWIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aac037ec3f3273e872307022405e95ace">llvm::bitc::ATTR_KIND_NOCF_CHECK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac4d3e92d2ef62cf51f31676bd04e5105">llvm::bitc::ATTR_KIND_NOFPCLASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2b4a84f204f2f012d3df4cb8bc60e860">llvm::bitc::ATTR_KIND_NOFREE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a93538315516b14f95e92df987821a58a">llvm::bitc::ATTR_KIND_NON_LAZY_BIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a57d48f7ace267b453bc4d3ad164e58fb">llvm::bitc::ATTR_KIND_NON_NULL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad0259dc9cd682a7b9bc525e92ab94902">llvm::bitc::ATTR_KIND_NOSYNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7e86d7e0b4f5f52a3f2205f8b2b07d26">llvm::bitc::ATTR_KIND_NOUNDEF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a5877603f20796c0153d7ad23b03b2079">llvm::bitc::ATTR_KIND_NULL_POINTER_IS_VALID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6a01a6b667890a3a7fe291b2303729c0">llvm::bitc::ATTR_KIND_OPT_FOR_FUZZING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3afa58e5a377bd47affa71c9573ff393c4">llvm::bitc::ATTR_KIND_OPTIMIZE_FOR_DEBUGGING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a10ccf7458de7661ed59552aa375f91e8">llvm::bitc::ATTR_KIND_OPTIMIZE_FOR_SIZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa695e2248b1cb68eb1afcdc2c5d62491">llvm::bitc::ATTR_KIND_OPTIMIZE_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3afbba6578048f8900e6a59315caba4eb5">llvm::bitc::ATTR_KIND_PREALLOCATED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aced00bf2cc41b0b4b1cd9bed3bf70fc6">llvm::bitc::ATTR_KIND_PRESPLIT_COROUTINE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aca4c5725563d1c044a84ec3d4b818a5f">llvm::bitc::ATTR_KIND_RANGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a974c5448b13d159116dfa73138e2058c">llvm::bitc::ATTR_KIND_READ_NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3abac7a26689aa32f57183deb05ff4e8b7">llvm::bitc::ATTR_KIND_READ_ONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4d40d2b7ab76139b227d085040438acf">llvm::bitc::ATTR_KIND_RETURNED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6321311fb493fcbb0fbf655bda813424">llvm::bitc::ATTR_KIND_RETURNS_TWICE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa08af93fce49bf40ea23e92f7fd99b43">llvm::bitc::ATTR_KIND_S_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a100c3c2639fc32a8d64953a2c29741a5">llvm::bitc::ATTR_KIND_SAFESTACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a2e2b64c82183308aa47d372943092e39">llvm::bitc::ATTR_KIND_SANITIZE_ADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a598116e25b929c808e6bd52e35a2be17">llvm::bitc::ATTR_KIND_SANITIZE_HWADDRESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a063fce6939dfcc85c3d919cbb90cdbe1">llvm::bitc::ATTR_KIND_SANITIZE_MEMORY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aeda30207dd431bb2531c9c55972a207d">llvm::bitc::ATTR_KIND_SANITIZE_MEMTAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6d0eb2693e8bacfa8c3265554bb4de39">llvm::bitc::ATTR_KIND_SANITIZE_NUMERICAL_STABILITY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ab2f626bb70e4d6ccec7b48c473d06a29">llvm::bitc::ATTR_KIND_SANITIZE_REALTIME</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ae376cf8d2b2da2e690cea4abf5d52862">llvm::bitc::ATTR_KIND_SANITIZE_REALTIME_BLOCKING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3af4da5ef4d5aada8b57baf7b42330d168">llvm::bitc::ATTR_KIND_SANITIZE_THREAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3acaeef48f6534f29c49dd9068ae704f89">llvm::bitc::ATTR_KIND_SANITIZE_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6943bf6094f5e2e519172af2be91c182">llvm::bitc::ATTR_KIND_SHADOWCALLSTACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a7ef1dd025b0567b904f0da8c0624da9b">llvm::bitc::ATTR_KIND_SKIP_PROFILE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3adb2076c2e8152af22f43f8fe939b191a">llvm::bitc::ATTR_KIND_SPECULATABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac1811dc4c110f8e6a942d6e73da1bcc8">llvm::bitc::ATTR_KIND_SPECULATIVE_LOAD_HARDENING</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4d708f6ef22af69a714124a9e6d27a29">llvm::bitc::ATTR_KIND_STACK_ALIGNMENT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a02985b5b9b00d8fcf0c3456548704f89">llvm::bitc::ATTR_KIND_STACK_PROTECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a52eaba8bee5d2693ac99f44de939c95f">llvm::bitc::ATTR_KIND_STACK_PROTECT_REQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a05f5e41019f7c20785c7a657d9f8158c">llvm::bitc::ATTR_KIND_STACK_PROTECT_STRONG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a9128f6d8bce4c0521966580b79757e13">llvm::bitc::ATTR_KIND_STRICT_FP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a1a17ef11f6af6c1c96c256a885d2bba7">llvm::bitc::ATTR_KIND_STRUCT_RET</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3afebba069726cfcfaedb609eb2afc411e">llvm::bitc::ATTR_KIND_SWIFT_ASYNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a12f9c8d3abe9eadfc656fd9a2115c7ec">llvm::bitc::ATTR_KIND_SWIFT_ERROR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a4dfd1ab23712750b0c4d712ff9aefdb3">llvm::bitc::ATTR_KIND_SWIFT_SELF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa1ee732e66faee6f738611e8af19ba32">llvm::bitc::ATTR_KIND_UW_TABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ad34cad71bda2dfd0c79c83a4cfe64523">llvm::bitc::ATTR_KIND_VSCALE_RANGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3ac847497e79df6980c96592730db17323">llvm::bitc::ATTR_KIND_WILLRETURN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a6c6b4c48a4db5cb8b4dcd7400dc2a767">llvm::bitc::ATTR_KIND_WRITABLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3aa9bcf6b32c733bdfa2e2473fd1f18963">llvm::bitc::ATTR_KIND_WRITEONLY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a53da1c4a4f1ae171b53bae755abab1a3a656d32cce3f0da0c87a066dce0a9ae0f">llvm::bitc::ATTR_KIND_Z_EXT</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eaa108685538d49543443a0ce281efd1d8">llvm::Attribute::EmptyKey</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60eadf64174102f26dd4fd9d79cc93ddee1b">llvm::Attribute::EndAttrKinds</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea3e672d8a791835da7d662b61f79590a6">llvm::Attribute::TombstoneKey</a>.</p>

</div>
</div>

### getEncodedBinaryOpcode() {#afa64fbea0aa72356b8a21325912cb482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedBinaryOpcode (unsigned Opcode)</td>
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



<p>Definition at line 634 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a68d9d8c75aa2cbd98cc3cd6088cd88c3">llvm::bitc::BINOP_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1acecfe220fcf28ba017208977312a468c">llvm::bitc::BINOP_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9a30fed92fd54e316fd32e7e745aeb14">llvm::bitc::BINOP_ASHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9ec979797d756b39ae37a5f2e25a0d38">llvm::bitc::BINOP_LSHR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1aa4396fd4122548b531cc7177512b139e">llvm::bitc::BINOP_MUL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a9b125c378940a11c60ad335b0e60b1a2">llvm::bitc::BINOP_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1aa4e1b66237a655ae124026c28b26d481">llvm::bitc::BINOP_SDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a01aa051969198a4085e944234de2446e">llvm::bitc::BINOP_SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1ac799944d2a5b7b91210b803504e77319">llvm::bitc::BINOP_SREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1af044d7456abdac4e41aef374cbb43e12">llvm::bitc::BINOP_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a6fc7d38cbdd784e6f2573ba865138210">llvm::bitc::BINOP_UDIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1a26868218c32dc434e202a4d694ad3f45">llvm::bitc::BINOP_UREM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#afca56ef2a5802dc130b03b7f08833da1ac6a71c3796edcf421edd6fadb028be68">llvm::bitc::BINOP_XOR</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getEncodedCastOpcode() {#a742dfa2fe7c03d9a1d16809dabb28d24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedCastOpcode (unsigned Opcode)</td>
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



<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab8be0ead019884e9180369dcf5ca0470">llvm::bitc::CAST_ADDRSPACECAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a07f83ec620595d592fb799d051ac6e75">llvm::bitc::CAST_BITCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab585d6900abdafe339c6e9c910035859">llvm::bitc::CAST_FPEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a2d6fc7cca02f499939b68491dff00f58">llvm::bitc::CAST_FPTOSI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a84dd2da5c7f3314061ca10f524e7dcb0">llvm::bitc::CAST_FPTOUI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ac7c030dde4055cefd0471ef8fb27038d">llvm::bitc::CAST_FPTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aaa14daa58dc521dbc0ef0a696aa9e6dd">llvm::bitc::CAST_INTTOPTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ad441909766521e384654c38484c6f169">llvm::bitc::CAST_PTRTOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aacc1fb2c439b83d10dd250ff5a2b93f3">llvm::bitc::CAST_SEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a9eaca2882fcf0ec475854e8e5c2279e8">llvm::bitc::CAST_SITOFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078aa1a60e212be26cd7a84d0218675285c2">llvm::bitc::CAST_TRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078a0aa29b41007b5fbfce2da261d9816978">llvm::bitc::CAST_UITOFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a892950389892c3540c33bb112a4f6078ab1d860827fec09b9116e81923e3f20aa">llvm::bitc::CAST_ZEXT</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getEncodedComdatSelectionKind() {#a894ba697fde8dbcd0583f9eb684bc714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedComdatSelectionKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> &amp; C)</td>
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



<p>Definition at line 1344 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8c4ae4df3d085db275a58182612ff3be">llvm::Comdat::Any</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba228d51974aa5c21ba52010a40302a0fc">llvm::bitc::COMDAT_SELECTION_KIND_ANY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba8cfeeb1451c75f879a6876b6beaf6c6d">llvm::bitc::COMDAT_SELECTION_KIND_EXACT_MATCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba10c8fffe9e95a186479d54d05cb03507">llvm::bitc::COMDAT_SELECTION_KIND_LARGEST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266baa4e0a5bb065b0f0330ec4a9b80b47ca6">llvm::bitc::COMDAT_SELECTION_KIND_NO_DUPLICATES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a4ebe99a75644fe79a5a1c031c5d0266ba78a05db06e72b074e5ff734665534e49">llvm::bitc::COMDAT_SELECTION_KIND_SAME_SIZE</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035acceb065ea69a5e06e80bd6ceddd7b9a7">llvm::Comdat::ExactMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a2444b05a47619decc80c2ce0cc224dc8">llvm::Comdat::Largest</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035ab2d0d4bc9ba11b7324f5ffc20a9dc37a">llvm::Comdat::NoDeduplicate</a> and <a href="/web-llvm/docs/api/classes/llvm/comdat/#ab40cbf8243fad70968f9ecf82f48a035a8b148d3d05688ddb23b7abb81527b7ce">llvm::Comdat::SameSize</a>.</p>

</div>
</div>

### getEncodedDLLStorageClass() {#ae5c40040698f75dfff1fd6bb991c9ff8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedDLLStorageClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">llvm::GlobalValue::DefaultStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0">llvm::GlobalValue::DLLExportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8aadc8e43e72669932581b5243b4b444b6">llvm::GlobalValue::DLLImportStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#af09a662b4e302d0683d0fe9dc2a9335f">llvm::GlobalValue::getDLLStorageClass</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getEncodedFFlags() {#afbe6f580fa0cd5a5440bedd9caa5aa7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getEncodedFFlags (<a href="/web-llvm/docs/api/structs/llvm/functionsummary/fflags">FunctionSummary::FFlags</a> Flags)</td>
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



<p>Definition at line 1252 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### getEncodedGVarFlags() {#aa2bdd6d7266a1d93028e8103ca09898f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getEncodedGVarFlags (<a href="/web-llvm/docs/api/structs/llvm/globalvarsummary/gvarflags">GlobalVarSummary::GVarFlags</a> Flags)</td>
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



<p>Definition at line 1291 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### getEncodedGVSummaryFlags() {#a8a4f77790cdf2a3857c91b5547743ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getEncodedGVSummaryFlags (<a href="/web-llvm/docs/api/structs/llvm/globalvaluesummary/gvflags">GlobalValueSummary::GVFlags</a> Flags, bool ImportAsDecl=false)</td>
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



<p>Definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### getEncodedHotnessCallEdgeInfo() {#ace8fa717066f0a4ba5a2aab2cbc24d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getEncodedHotnessCallEdgeInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a> &amp; CI)</td>
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



<p>Definition at line 1297 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a99422c588622ee55308d9ee71be9eb11">llvm::CalleeInfo::HasTailCall</a> and <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a944041c1d7fceebe4968b5ab30f2ce66">llvm::CalleeInfo::Hotness</a>.</p>

</div>
</div>

### getEncodedLinkage() {#a592963eb7d9c5f3f2601453232ee79f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedLinkage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> Linkage)</td>
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



<p>Definition at line 1220 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">llvm::GlobalValue::AppendingLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilfinalizelinkage-cpp/#ae721973516c2b86042a5127b776e2806">Linkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="#aa88d9de56393e21d759a360f4b4948c0">getEncodedLinkage</a>.</p>

</div>
</div>

### getEncodedLinkage() {#aa88d9de56393e21d759a360f4b4948c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedLinkage (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Definition at line 1248 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="#a592963eb7d9c5f3f2601453232ee79f7">getEncodedLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3547d58a060ee2e4a29cbea85bef91af">llvm::GlobalValue::getLinkage</a>.</p>

</div>
</div>

### getEncodedOrdering() {#a7de734ed7f3bfddcdf0f612ba0799524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedOrdering (<a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> Ordering)</td>
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



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a133fea251780f2b0a86a520addd9c184">llvm::bitc::ORDERING_ACQREL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a0b468dec37bac00c148e2e9a20711bb9">llvm::bitc::ORDERING_ACQUIRE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077aec3d86ca51de0866abd0fc0d1ec71b9d">llvm::bitc::ORDERING_MONOTONIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a83f6d5a33251a1af65bfd012765dbec7">llvm::bitc::ORDERING_NOTATOMIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a47017037bf5808b06c2cd2e184c55de2">llvm::bitc::ORDERING_RELEASE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077ab5a2748be1fde542bf8baeb43f6f44cb">llvm::bitc::ORDERING_SEQCST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#aff6d462fc866dfab2fc79bd125310077a8768765e8f788907885fbd23ae6a8edb">llvm::bitc::ORDERING_UNORDERED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a>.</p>

</div>
</div>

### getEncodedRelBFCallEdgeInfo() {#a92aacec4c813842a5686cf1f2a7ee8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getEncodedRelBFCallEdgeInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/calleeinfo">CalleeInfo</a> &amp; CI)</td>
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



<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a99422c588622ee55308d9ee71be9eb11">llvm::CalleeInfo::HasTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#a5fd24958824ab5f36f840428c0778583">llvm::CalleeInfo::RelBlockFreq</a> and <a href="/web-llvm/docs/api/structs/llvm/calleeinfo/#afb34a60fa4d1c019369287f0e9e7482f">llvm::CalleeInfo::RelBlockFreqBits</a>.</p>

</div>
</div>

### getEncodedRMWOperation() {#a63671ba30c39a0f6b0a5d03987eab820}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedRMWOperation (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615">AtomicRMWInst::BinOp</a> Op)</td>
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



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0794c42b44989f9d9f1454d79ca0dd88">llvm::AtomicRMWInst::Add</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a660a31179bfecd737a256372e5fd6122">llvm::AtomicRMWInst::And</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a08ef06068dcd583c2476568dda59b324">llvm::AtomicRMWInst::FAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615acce124326ba87b0127b36c412bf555fd">llvm::AtomicRMWInst::FMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abd5e733a10a36f3572105b1a67538e18">llvm::AtomicRMWInst::FMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a92f66d4bc04fc8514bee80509f3e78d4">llvm::AtomicRMWInst::FSub</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa1184a7e35e94d162a2d40f2b11beeb2">llvm::AtomicRMWInst::Max</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a39edb6e51c1ad37244e8b32a2af4077d">llvm::AtomicRMWInst::Min</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afdcdc631cf4fa6829fd7499cd06a306b">llvm::AtomicRMWInst::Nand</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5954f59053121b87ebe0c5fe79942c6e">llvm::AtomicRMWInst::Or</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf3617c1779061deeeae4a24e1c45d015">llvm::bitc::RMW_ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa1fffe440fc04d4931be511a6759fb0bf">llvm::bitc::RMW_AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa56e0b4e94e457f1abf28de75d156eed2">llvm::bitc::RMW_FADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf6ff61c0bdbe5ab915efd9cdc1ffb3bc">llvm::bitc::RMW_FMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa0f985a5852d333645b18af7dd342b366">llvm::bitc::RMW_FMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaae916e663743bef5cdc843ae1fe2bb50">llvm::bitc::RMW_FSUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa0f7c09593b49ad69a24976fd79491ca9">llvm::bitc::RMW_MAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aafef3e0c3498ab6999f170022e942b675">llvm::bitc::RMW_MIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aaf1143967d78add27bf0a34cd120b05b9">llvm::bitc::RMW_NAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa659ec22852b50f1b2907cb553ccd3003">llvm::bitc::RMW_OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa7786115a5d20e2d7377870813a8e91fe">llvm::bitc::RMW_SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa87c17066a291c0b1ce3d143cb4b33afc">llvm::bitc::RMW_UDEC_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aadfffdd7e9faf02738adc9b4515142386">llvm::bitc::RMW_UINC_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa974e4f980368e5eb72fbc4693ce077bc">llvm::bitc::RMW_UMAX</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa3458453a8e9b396ca571f9c7ee12b9fd">llvm::bitc::RMW_UMIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa051d138a9600eacf2fe449622150a0c8">llvm::bitc::RMW_USUB_COND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa4d1e7498fe0b00010e93607c187c1c74">llvm::bitc::RMW_USUB_SAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa172fe635673085e6d5efc03db990e68e">llvm::bitc::RMW_XCHG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a182436d33a9a893dc643e0c886111a4aa75792f75bfdfd0639c08b8f4a6d7422e">llvm::bitc::RMW_XOR</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a5db6ca0c3e18acd87290f22ccb2ce564">llvm::AtomicRMWInst::Sub</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615ad3ed1a8c334bc3a50d59aaa57ee9e9f3">llvm::AtomicRMWInst::UDecWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a9334c9815ddc2b25804c6c03b68cc39b">llvm::AtomicRMWInst::UIncWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615abe171d96ba8de66fb30e08c00211591e">llvm::AtomicRMWInst::UMax</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615aa53854e09143f57d2ff2ad6ac89dc55d">llvm::AtomicRMWInst::UMin</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a0f94e2ef083268e45d22a220f92567a4">llvm::AtomicRMWInst::USubCond</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a7bf1abb23eccced685c706917aff605c">llvm::AtomicRMWInst::USubSat</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615afc870a548088c5b7a93a34f648889d77">llvm::AtomicRMWInst::Xchg</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a461cfbbb5c7a57ab73210498923cf615a71aab8ee954b6d71a4eed315e8f6556e">llvm::AtomicRMWInst::Xor</a>.</p>

</div>
</div>

### getEncodedThreadLocalMode() {#a63d62b881d3a85b6b75b5c8153c8f693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedThreadLocalMode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Definition at line 1333 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a55e32c080bb5217324a597d4fb441660">llvm::GlobalValue::GeneralDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a52126ae2091b18cecfd5ad0f0012839a">llvm::GlobalValue::getThreadLocalMode</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a92e26a4a1218d351f5a91e7385a3a320">llvm::GlobalValue::InitialExecTLSModel</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62ac9f6ea05a2d4cca9e093366042dfa6b8">llvm::GlobalValue::LocalDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a41529b6e723f5025e59ca9364cf70128">llvm::GlobalValue::LocalExecTLSModel</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>

</div>
</div>

### getEncodedUnaryOpcode() {#a196e56f0349ef0faab66e90bc5d692bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedUnaryOpcode (unsigned Opcode)</td>
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



<p>Definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a635e5fcb068bb33406c8f4478fec92acaff0bbded1d2517cb24d7d941a40cfd31">llvm::bitc::UNOP_FNEG</a>.</p>

</div>
</div>

### getEncodedUnnamedAddr() {#a7fb389ba93facff2787add2c58128fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedUnnamedAddr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Definition at line 1360 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac2417a3c6edd0db7a9ad84b82c4054b7">llvm::GlobalValue::getUnnamedAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a509820290d57f333403f490dde7316f4">llvm::GlobalValue::Local</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a6adf97f83acf6453d4a6a4b1070f3754">llvm::GlobalValue::None</a>.</p>

</div>
</div>

### getEncodedVisibility() {#a3a7e88942eb67dbe7eb580dbdf75c648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getEncodedVisibility (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a28b9561d9ef3d237ef894023187fa26c">llvm::GlobalValue::getVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">llvm::GlobalValue::ProtectedVisibility</a>.</p>

</div>
</div>

### getOptimizationFlags() {#a513e443b4a433b36c8d325032a2fbc1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t getOptimizationFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1688 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa4601e39685b21855202598fbbbf483c8">llvm::bitc::AllowContract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aaf1a502f88e347fddad4ee0750b994975">llvm::bitc::AllowReassoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aafa457615c7642f4cb8e1758bc6673c09">llvm::bitc::AllowReciprocal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa3f8ef5ee785e3c0ea9c691175a6de5b0">llvm::bitc::ApproxFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a33a73a3b8d28548e6e3216801bf93207a1d40dfa2a367a9a21810697c5cfc136a">llvm::bitc::GEP_INBOUNDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a33a73a3b8d28548e6e3216801bf93207acd28ff8cbc5d1a5526f142fb27c6c6a3">llvm::bitc::GEP_NUSW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a33a73a3b8d28548e6e3216801bf93207aa12e0bcbdd56def413c412f7ba95bd37">llvm::bitc::GEP_NUW</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#ab07949314720a391bf9a4ec0dfb6289aae42c00bdc25c89dc217009a8669ce7d6">llvm::bitc::ICMP_SAME_SIGN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa7615867f60ad3984f710b758a7fa794a">llvm::bitc::NoInfs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa0b6078f1d27619490c8569776bfaea2f">llvm::bitc::NoNaNs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abd587fc6c85f5fca5adea50beb5a040aa5570d4f40666e6352950e1e45696cbd2">llvm::bitc::NoSignedZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a5d729bc0f60b0cc1cee0d3d16e8a6954a23e6dd46c09ce9c6c771b637a5d3eb69">llvm::bitc::OBO_NO_SIGNED_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a5d729bc0f60b0cc1cee0d3d16e8a6954a2fc4d70f7ea4e9bb62acf87e73ad6508">llvm::bitc::OBO_NO_UNSIGNED_WRAP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#abbe7948ad74b8f0387de7e5ac03d6bcca729f268e07c71da60f9df42ccc9d0e64">llvm::bitc::PDI_DISJOINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a49372e72493c55831abbcfcd59a3d49ca2bb97e5d0b49ccf94e9cae8079c4a4b5">llvm::bitc::PEO_EXACT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a28b10e9b2658558a4b547ea0eb025ea4adb47173b64643c09b501e6314972e1ca">llvm::bitc::PNNI_NON_NEG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a5e90fa071e4abe5068075a0b4b439a38aea126ab6cd8b69e4de1361fe655d981f">llvm::bitc::TIO_NO_SIGNED_WRAP</a> and <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a5e90fa071e4abe5068075a0b4b439a38a7193269bf64e9b883163cf75b6aa2166">llvm::bitc::TIO_NO_UNSIGNED_WRAP</a>.</p>

</div>
</div>

### getReferencedTypeIds() {#a110547082315f2a6d3b983698f89df88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void getReferencedTypeIds (<a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS, std::set&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp; ReferencedTypeIds)</td>
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

<p>Collect type IDs from type tests used by function.</p>

<p>Definition at line 4125 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### getSectionNameForBitcode() {#af584ab078aff102fb30fcb68f1d64681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getSectionNameForBitcode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 5593 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca77be73c19a4451fa0580ac5b9018357b">llvm::Triple::AMD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">llvm::Triple::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a382f97aab858a35311f657a88f998a68">llvm::Triple::DXContainer</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">llvm::Triple::GOFF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201ae057411e10951f5a7dc545e6199c5490">llvm::Triple::SPIRV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">llvm::Triple::UnknownObjectFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb">llvm::Triple::Wasm</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">llvm::Triple::XCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>.</p>

</div>
</div>

### getSectionNameForCommandline() {#aaa4c216848cbc41c0e519b84ced70579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getSectionNameForCommandline (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; T)</td>
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



<p>Definition at line 5620 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a96fe35195867c94aef1adf2ad0e20eeca77be73c19a4451fa0580ac5b9018357b">llvm::Triple::AMD</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201aa943abc041caa1cc4c074bbf38b76267">llvm::Triple::COFF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a382f97aab858a35311f657a88f998a68">llvm::Triple::DXContainer</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a7d71851eea2209e547ae06c9c03768f5">llvm::Triple::GOFF</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a2ed78f59e2d35011e1d1ed0ad96cf411">llvm::Triple::MachO</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201ae057411e10951f5a7dc545e6199c5490">llvm::Triple::SPIRV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201af2f88d8b470958614a01866d4714b5a4">llvm::Triple::UnknownObjectFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a660d4029da29691e97daf8c8aabb1ffb">llvm::Triple::Wasm</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a1f7d761ca747e66d2ac0caa0d54b1824">llvm::Triple::XCOFF</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>.</p>

</div>
</div>

### getStringEncoding() {#aa1bea7f5f828e03912c962c96e4e5e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringEncoding getStringEncoding (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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

<p>Determine the encoding to use for the given string name and length.</p>

<p>Definition at line 1416 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a04864a36012093c3174c0e762331eb23">llvm::BitCodeAbbrevOp::isChar6</a>, <a href="#a3172cb0288d425ec480fb1e09f33b340a1937ce2d6b3aa788b1243878eb87b849">SE_Char6</a>, <a href="#a3172cb0288d425ec480fb1e09f33b340a86044faf6bf8662d099b43b3113eb7fb">SE_Fixed7</a> and <a href="#a3172cb0288d425ec480fb1e09f33b340a8d011ea49c4af540b560afd62e786365">SE_Fixed8</a>.</p>

</div>
</div>

### serializeSanitizerMetadata() {#a08e573712fd20f9e30d20e581fb6f091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned serializeSanitizerMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/globalvalue/sanitizermetadata">GlobalValue::SanitizerMetadata</a> &amp; Meta)</td>
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



<p>Definition at line 1433 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### writeBitcodeHeader() {#a90f3f0ae5027fb62fc0090c0b0722d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeBitcodeHeader (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream)</td>
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

<p>Helper to write the header common to all bitcode files.</p>

<p>Definition at line 5256 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a40de93ba2d72dc6bccd7a1fdde996718">llvm::BitstreamWriter::Emit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter/#a4d51c2e883aaae6b692f2babd7f6311f">llvm::BitcodeWriter::BitcodeWriter</a> and <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter/#aebebbee7033640e87126667a63bd2357">llvm::BitcodeWriter::BitcodeWriter</a>.</p>

</div>
</div>

### writeFunctionHeapProfileRecords() {#a0850c8a2472500d4a79b9f48495a1d2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeFunctionHeapProfileRecords (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS, unsigned CallsiteAbbrev, unsigned AllocAbbrev, unsigned ContextIdAbbvId, bool PerModule, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; unsigned(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &amp;VI)&gt; GetValueID, <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">std::function</a>&lt; unsigned(unsigned)&gt; GetStackIndex, bool WriteContextSizeInfoIndex, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#a271f954222d61bd5dc7f5cb5dd836b52">LinearCallStackId</a> &gt; &amp; CallStackPos, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a> &amp; CallStackCount)</td>
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



<p>Definition at line 4252 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a2a492ce167a19107e75ec372f68e8d7a">llvm::BitstreamWriter::EmitRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba52dd969c2b5e24add5ca2516ed0f200d">llvm::bitc::FS_ALLOC_CONTEXT_IDS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001babe5d1caab319ca559948c13bbcee0f25">llvm::bitc::FS_COMBINED_ALLOC_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001bab379fe6d08288d8a29cf0d8993b5f05a">llvm::bitc::FS_COMBINED_CALLSITE_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001bae00c1b00b0336f5f501530553eb51324">llvm::bitc::FS_PERMODULE_ALLOC_INFO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001badeba38c1dfee61f7d2dac12d39046937">llvm::bitc::FS_PERMODULE_CALLSITE_INFO</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a3d95cc2d359b8d9ed5bd9504b44930b5">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::size</a>.</p>

</div>
</div>

### writeFunctionTypeMetadataRecords() {#ac7e865e854ff6b0ba0eb2147e0ccb5cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Fn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeFunctionTypeMetadataRecords (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/functionsummary">FunctionSummary</a> * FS, Fn GetValueID)</td>
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

<p>Write the function type metadata related records that need to appear before a function summary entry (whether per-module or combined).</p>

<p>Definition at line 4049 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a2a492ce167a19107e75ec372f68e8d7a">llvm::BitstreamWriter::EmitRecord</a>, <a href="#a2706d140844a6517f06fd552269a7aba">emitSignedInt64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba59c59629c5fe384b7c23381d6bb44b14">llvm::bitc::FS_PARAM_ACCESS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001bafbca7a60ed87076dcc60f196385f0f84">llvm::bitc::FS_TYPE_CHECKED_LOAD_CONST_VCALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba504e48194f2217cbe18f1513474ee0fd">llvm::bitc::FS_TYPE_CHECKED_LOAD_VCALLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba70ca6811ccd6f4269cd2b835bcaa91a6">llvm::bitc::FS_TYPE_TEST_ASSUME_CONST_VCALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba88548f8be84646655fdcf04c9d07bb93">llvm::bitc::FS_TYPE_TEST_ASSUME_VCALLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001baa2b70896e3139d999510f2727813fc96">llvm::bitc::FS_TYPE_TESTS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a> and <a href="/web-llvm/docs/api/structs/llvm/functionsummary/paramaccess/#ad7b7723aa791b53f4fe0a4f88613a8bd">llvm::FunctionSummary::ParamAccess::RangeWidth</a>.</p>

</div>
</div>

### writeIdentificationBlock() {#a71e02e853cce26400683e76984e82529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeIdentificationBlock (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream)</td>
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

<p>Create the "IDENTIFICATION_BLOCK_ID" containing a single string with the current llvm version, and a record for the epoch number.</p>

<p>Definition at line 5085 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ac45cef5b964b589fb0741ccc577eaf2c">llvm::BitCodeAbbrevOp::Array</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a298addd8bf1eaddaaebcec3640429188a7f66f39da99244fad39ebe115c4053a0">llvm::bitc::BITCODE_CURRENT_EPOCH</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672a5a7811cd25e6ed838a03c49776237b4a">llvm::BitCodeAbbrevOp::Char6</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a032ac42ce93b41ccad6f2380a3efa207">llvm::BitstreamWriter::EmitAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a2a492ce167a19107e75ec372f68e8d7a">llvm::BitstreamWriter::EmitRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#ae6a40b4a5ea89bb8b5076c26e0d0b638">llvm::BitstreamWriter::EnterSubblock</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a5e8488041d80c56389002659004c6af7">llvm::BitstreamWriter::ExitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a802836c61fe369b670441d32741f933da574b2844e8b4baab9239f12c1b6b0d04">llvm::bitc::IDENTIFICATION_BLOCK_ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2dde66e038f5a0836d72e760f731a4b4ab33f9d97fa7abd55725a6a62e6250bd1">llvm::bitc::IDENTIFICATION_CODE_EPOCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2dde66e038f5a0836d72e760f731a4b4ad0b7a34426fe13ee6793888a32698b4e">llvm::bitc::IDENTIFICATION_CODE_STRING</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a8694ae7ca83441b2764d71711b17e672ade2457e8051855ad2911d62202458e20">llvm::BitCodeAbbrevOp::VBR</a> and <a href="#ad375d674219d643fe0ba85db2b7f172a">writeStringRecord</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriter/#a3ad01919d5d625704d2d69f86d3136b2">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriter::write</a>.</p>

</div>
</div>

### writeInt32ToBuffer() {#af1886b67a152078f035dc14be966dc8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeInt32ToBuffer (uint32_t Value, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Buffer, uint32_t &amp; Position)</td>
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



<p>Definition at line 5190 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4f05956d010455624c13f5eb2217bc8b">llvm::support::endian::write32le</a>.</p>


<p>Referenced by <a href="#a8ea1d38f4a65135188eb7409818070e6">emitDarwinBCHeaderAndTrailer</a>.</p>

</div>
</div>

### writeMemoryProfileRadixTree() {#a6ddafba4af9c27c785a0d873fd3cb661}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt; CallStackId, LinearCallStackId &gt; writeMemoryProfileRadixTree (<a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#acccd58d8f1e260d41aec72e4ce5e847f">CallStackId</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ac8f2e9a6f336bcafc02bbe895a6bf6db">LinearFrameId</a> &gt; &gt; &amp;&amp; CallStacks, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, unsigned RadixAbbrev)</td>
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



<p>Definition at line 4236 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#a05db798ae8ae11328fce938cd0d012f9">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::build</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memprof/#ac3df9071518d732327585d2dbf10ca1f">llvm::memprof::computeFrameHistogram&lt; LinearFrameId &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a2a492ce167a19107e75ec372f68e8d7a">llvm::BitstreamWriter::EmitRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/bitc/#a2889cf6772f22a2e9c802b6c4cb5001ba0b88f487f51959e29f9a30be85640735">llvm::bitc::FS_CONTEXT_RADIX_TREE_ARRAY</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#a952877a78325a5e2a3b1bd8cf623bb9b">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::getRadixArray</a> and <a href="/web-llvm/docs/api/classes/llvm/memprof/callstackradixtreebuilder/#ae5227f60eb0adb26e24a3d08457af5a5">llvm::memprof::CallStackRadixTreeBuilder&lt; FrameIdTy &gt;::takeCallStackPos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### writeStringRecord() {#ad375d674219d643fe0ba85db2b7f172a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeStringRecord (<a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter">BitstreamWriter</a> &amp; Stream, unsigned Code, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, unsigned AbbrevToUse)</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/bitstreamwriter/#a2a492ce167a19107e75ec372f68e8d7a">llvm::BitstreamWriter::EmitRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodeabbrevop/#a04864a36012093c3174c0e762331eb23">llvm::BitCodeAbbrevOp::isChar6</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a71e02e853cce26400683e76984e82529">writeIdentificationBlock</a>.</p>

</div>
</div>

### writeTypeIdCompatibleVtableSummaryRecord() {#a0fcb5b0c8740137c1ba7ea67bc4e1986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeTypeIdCompatibleVtableSummaryRecord (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ada2485ca228b028f8639ad86ce41d6ec">TypeIdCompatibleVtableInfo</a> &amp; Summary, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator">ValueEnumerator</a> &amp; VE)</td>
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



<p>Definition at line 4195 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae6ba484ec18769c20a3c576c02f0b2a7">llvm::StringTableBuilder::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriter-cpp-/modulebitcodewriterbase/#ad8b12ebb23f57815dfdaa7a14562aa5f">anonymous{BitcodeWriter.cpp}::ModuleBitcodeWriterBase::writePerModuleGlobalValueSummary</a>.</p>

</div>
</div>

### writeTypeIdSummaryRecord() {#ac5a65c8b873ba60af3d6927d70551cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeTypeIdSummaryRecord (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/typeidsummary">TypeIdSummary</a> &amp; Summary)</td>
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



<p>Definition at line 4176 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae6ba484ec18769c20a3c576c02f0b2a7">llvm::StringTableBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a>.</p>

</div>
</div>

### writeWholeProgramDevirtResolution() {#ae4770e119c132809f74cc6faaf62698e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeWholeProgramDevirtResolution (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a> &amp; StrtabBuilder, uint64_t Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> &amp; Wpd)</td>
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



<p>Definition at line 4162 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#ae6ba484ec18769c20a3c576c02f0b2a7">llvm::StringTableBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a1c0a0ec1654585583572f16e799176dc">llvm::WholeProgramDevirtResolution::ResByArg</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ab97c12959c5cc7b46b115da7e1ac5047">llvm::WholeProgramDevirtResolution::SingleImplName</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a11bddbadb47e3bd7803ded5d4f4248fc">llvm::WholeProgramDevirtResolution::TheKind</a> and <a href="#a96b4150a46b836d772425ab620d97e23">writeWholeProgramDevirtResolutionByArg</a>.</p>


<p>Referenced by <a href="#ac5a65c8b873ba60af3d6927d70551cc4">writeTypeIdSummaryRecord</a>.</p>

</div>
</div>

### writeWholeProgramDevirtResolutionByArg() {#a96b4150a46b836d772425ab620d97e23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeWholeProgramDevirtResolutionByArg (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t, 64 &gt; &amp; NameVals, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; uint64_t &gt; &amp; args, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg">WholeProgramDevirtResolution::ByArg</a> &amp; ByArg)</td>
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



<p>Definition at line 4150 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a4d6da696b3c753c5e5fbcc4d21d4cb71">args</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a74a555cfcbd8d83cdbf785f01b88be68">llvm::WholeProgramDevirtResolution::ByArg::Bit</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#afcc8593fe943d570b5a3fe549132fdff">llvm::WholeProgramDevirtResolution::ByArg::Byte</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#ac1e46342d3d79c56fb3b498722a66f18">llvm::WholeProgramDevirtResolution::ByArg::Info</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#acf13a890a40972d903f329d37c5ad98a">llvm::WholeProgramDevirtResolution::ByArg::TheKind</a>.</p>


<p>Referenced by <a href="#ae4770e119c132809f74cc6faaf62698e">writeWholeProgramDevirtResolution</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### FlushThreshold {#a7a4f14026a779acb2eda1e8107a62f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; uint32_t &gt; FlushThreshold("bitcode-flush-threshold", cl::Hidden, cl::init(512), cl::desc("The threshold (unit M) for flushing LLVM bitcode."))</td>
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



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitcodewriter/#a4d51c2e883aaae6b692f2babd7f6311f">llvm::BitcodeWriter::BitcodeWriter</a>.</p>

</div>
</div>

### IndexThreshold {#ab937b5cbd57983fceac42c85eb831711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; IndexThreshold("bitcode-mdindex-threshold", cl::Hidden, cl::init(25), cl::desc("Number of metadatas above which we emit an index " "to enable lazy-loading"))</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### UseNewDbgInfoFormat {#a926189935285d6e5df83fc0f45bf9b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::cl::opt&lt;bool&gt; UseNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

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



<p>Declaration at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### WriteRelBFToSummary {#a77a0d10689d50ceb5e955bc16121f3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; WriteRelBFToSummary("write-relbf-to-summary", cl::Hidden, cl::init(false), cl::desc("Write relative block frequency to function summary "))</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### HANDLE\_MDNODE\_LEAF {#a4060cc153ca27a61adf713615161fba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_MDNODE_LEAF(CLASS)&nbsp;&nbsp;&nbsp;CLASS##AbbrevID,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2394 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### HANDLE\_MDNODE\_LEAF {#ab32240e87649f32aceeda23ea6499c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_MDNODE_LEAF(CLASS)&nbsp;&nbsp;&nbsp;unsigned CLASS##Abbrev = 0;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2406 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

### HANDLE\_MDNODE\_LEAF {#a1f378efe7b9888496956feb63c04314f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_MDNODE_LEAF(CLASS)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case Metadata::CLASS##Kind:                                                  \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (MDAbbrevs)                                                             \
      <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#a79ab15165c16fbf94d6fd33bd890ea7e">write</a>##CLASS(cast&lt;CLASS&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>), <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>,                                     \
                   (*MDAbbrevs)[MetadataAbbrev::CLASS##AbbrevID]);             \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a0544c3fe466e421738dae463968b70ba">else</a>                                                                       \
      <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#a79ab15165c16fbf94d6fd33bd890ea7e">write</a>##CLASS(cast&lt;CLASS&gt;(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>), <a href="/web-llvm/docs/api/classes/llvm/record">Record</a>, CLASS##Abbrev);                     \
    continue;
</div>
</dd>
</dl>

<p>Definition at line 2418 of file <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/writer/bitcodewriter-cpp">BitcodeWriter.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
