---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/asmwriter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `AsmWriter.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apfloat-h">llvm/ADT/APFloat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apint-h">llvm/ADT/APInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/setvector-h">llvm/ADT/SetVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallstring-h">llvm/ADT/SmallString.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/iterator-range-h">llvm/ADT/iterator_range.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "llvm/Config/llvm-config.h"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/assemblyannotationwriter-h">llvm/IR/AssemblyAnnotationWriter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/attributes-h">llvm/IR/Attributes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/cfg-h">llvm/IR/CFG.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">llvm/IR/Comdat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constant-h">llvm/IR/Constant.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">llvm/IR/DebugProgramInstruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalalias-h">llvm/IR/GlobalAlias.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalifunc-h">llvm/IR/GlobalIFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvalue-h">llvm/IR/GlobalValue.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalvariable-h">llvm/IR/GlobalVariable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irprintingpasses-h">llvm/IR/IRPrintingPasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/moduleslottracker-h">llvm/IR/ModuleSlotTracker.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/type-h">llvm/IR/Type.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/typefinder-h">llvm/IR/TypeFinder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/typedpointertype-h">llvm/IR/TypedPointerType.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/use-h">llvm/IR/Use.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/user-h">llvm/IR/User.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/atomicordering-h">llvm/Support/AtomicOrdering.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formattedstream-h">llvm/Support/FormattedStream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/saveandrestore-h">llvm/Support/SaveAndRestore.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cassert&gt;
#include &lt;cctype&gt;
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;iterator&gt;
#include &lt;memory&gt;
#include &lt;optional&gt;
#include &lt;string&gt;
#include &lt;tuple&gt;
#include &lt;utility&gt;
#include &lt;vector&gt;
#include "llvm/IR/Metadata.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-asmwriter-cpp-">anonymous{AsmWriter.cpp}</a></td>
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

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting">TypePrinting</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class provides computation of slot numbers for LLVM Assembly writing. <a href="/web-llvm/docs/api/classes/llvm/slottracker/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/asmwritercontext">AsmWriterContext</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common instances used by most of the printer functions. <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/asmwritercontext/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/fieldseparator">FieldSeparator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter">MDFieldPrinter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter">AssemblyWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdtreeasmwritercontext">MDTreeAsmWriterContext</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1254a95dc7ef84df14d6c1357c6d7b46">OrderMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, unsigned &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dba8485af0d57fec37ee7bd17cafcc5">UseListOrderMap</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *, <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt; &gt; &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">PrefixType { <a href="#aec73ab739d6b324c9753c7071afd6c2f">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa51ef8da80e517883688d037a44c362">skipMetadataWrapper</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look for a value that might be wrapped as metadata, e.g. <a href="#afa51ef8da80e517883688d037a44c362">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a> (const Value *V, OrderMap &amp;OM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a1254a95dc7ef84df14d6c1357c6d7b46">OrderMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a899f5401a68379402b5754613e045620">orderModule</a> (const Module *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#ac760e37eba1d852d0a28011a1a0ce05f">std::vector</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a385464d789381c250f924d62222498f3">predictValueUseListOrder</a> (const Value *V, unsigned ID, const OrderMap &amp;OM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a9dba8485af0d57fec37ee7bd17cafcc5">UseListOrderMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4b315c2c9cb6fd233d549b85fc8e649">predictUseListOrder</a> (const Module *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a> (const DbgMarker *Marker)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af15b30bf916411af4026c84ef965ca">getModuleFromDPI</a> (const DbgRecord *DR)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13e35bdf0ecd9533b463d3c902d3659c">PrintCallingConv</a> (unsigned cc, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a> (raw_ostream &amp;OS, StringRef Name, PrefixType Prefix)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn the specified name into an 'LLVM name', which is either prefixed with % (if the string only contains simple characters) or is surrounded with ""'s (if it has special chars in it). <a href="#a3d6e60a917bf5f4052dbb2673f11e087">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4765c34bf6f6177ecba069bd53fb9570">PrintLLVMName</a> (raw_ostream &amp;OS, const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn the specified name into an 'LLVM name', which is either prefixed with % (if the string only contains simple characters) or is surrounded with ""'s (if it has special chars in it). <a href="#a4765c34bf6f6177ecba069bd53fb9570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a515ea398a2f882f4d1ea69c71ea8d39c">PrintShuffleMask</a> (raw_ostream &amp;Out, Type *Ty, ArrayRef&lt; int &gt; Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9869c4a9f8b770252b7041cb2edfc66f">createSlotTracker</a> (const Value *V)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> (raw_ostream &amp;Out, const Value *V, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b2195c3b9d667a9857b9bce7eb8e267">WriteAsOperandInternal</a> (raw_ostream &amp;Out, const Metadata *MD, AsmWriterContext &amp;WriterCtx, bool FromValue=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ced856c3217b5902cfc6e22ade76eaa">WriteOptimizationInfo</a> (raw_ostream &amp;Out, const User *U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a> (raw_ostream &amp;Out, const APFloat &amp;APF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a> (raw_ostream &amp;Out, const Constant *CV, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb4d18db2159531ff68606f587116f4">writeMDTuple</a> (raw_ostream &amp;Out, const MDTuple *Node, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a060c83e55e124b32a1b41542ee254d98">writeMetadataAsOperand</a> (raw_ostream &amp;Out, const Metadata *MD, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51487913b1d80a22af63de2ff1dcb89">writeGenericDINode</a> (raw_ostream &amp;Out, const GenericDINode *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d08596bb6d02dac5a3629abda510174">writeDILocation</a> (raw_ostream &amp;Out, const DILocation *DL, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae63e2c24c65979ed0c3a52704a8d6c29">writeDIAssignID</a> (raw_ostream &amp;Out, const DIAssignID *DL, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e7ff419d64524657abe5c1389f34dc">writeDISubrange</a> (raw_ostream &amp;Out, const DISubrange *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7cbec4f02d601d51217c096e1462805">writeDIGenericSubrange</a> (raw_ostream &amp;Out, const DIGenericSubrange *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad48e4b73f1c3fda1be498800e79bb2d1">writeDIEnumerator</a> (raw_ostream &amp;Out, const DIEnumerator *N, AsmWriterContext &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab007fb7393c2c55689a30b5c9f9b54e7">writeDIBasicType</a> (raw_ostream &amp;Out, const DIBasicType *N, AsmWriterContext &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3480bb9edd827c6105a2a28652142d9c">writeDIStringType</a> (raw_ostream &amp;Out, const DIStringType *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6d9d4bb9a4379614584f1dc6ec07cc">writeDIDerivedType</a> (raw_ostream &amp;Out, const DIDerivedType *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a187176da17ddab193a07b2cde86c2297">writeDICompositeType</a> (raw_ostream &amp;Out, const DICompositeType *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fbddbd7054d4a95232371b2c436ab7b">writeDISubroutineType</a> (raw_ostream &amp;Out, const DISubroutineType *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a593a29eb296078e4adc21c4735cbf089">writeDIFile</a> (raw_ostream &amp;Out, const DIFile *N, AsmWriterContext &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf928d48c46a6de39967c53eecfb6320">writeDICompileUnit</a> (raw_ostream &amp;Out, const DICompileUnit *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82755caf4693707060eaa24ed59ebd2a">writeDISubprogram</a> (raw_ostream &amp;Out, const DISubprogram *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae839d5f52524ed2102d25ae1ffe92deb">writeDILexicalBlock</a> (raw_ostream &amp;Out, const DILexicalBlock *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accd701498a663907e97c9dcedfa7a54a">writeDILexicalBlockFile</a> (raw_ostream &amp;Out, const DILexicalBlockFile *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d3673e478e66c19b06dcbfb588686c2">writeDINamespace</a> (raw_ostream &amp;Out, const DINamespace *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ab58811d85ab06ba2589190e42c409">writeDICommonBlock</a> (raw_ostream &amp;Out, const DICommonBlock *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01d062dbede1f91bf1c960a57fd349dc">writeDIMacro</a> (raw_ostream &amp;Out, const DIMacro *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6c1602b1a0ffbb1aad2c7cc9bac1d6">writeDIMacroFile</a> (raw_ostream &amp;Out, const DIMacroFile *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5584c0a21c6481a943ab39406bd62098">writeDIModule</a> (raw_ostream &amp;Out, const DIModule *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f46d7b60f100ca64722051bf8401b1">writeDITemplateTypeParameter</a> (raw_ostream &amp;Out, const DITemplateTypeParameter *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af836f3f665f5c5c4ba40edc1db6ab530">writeDITemplateValueParameter</a> (raw_ostream &amp;Out, const DITemplateValueParameter *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a754075676cf28fe91f2d0bb1b5fc44">writeDIGlobalVariable</a> (raw_ostream &amp;Out, const DIGlobalVariable *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6bcc5e28f19737a3b0ec69ff062c0f9">writeDILocalVariable</a> (raw_ostream &amp;Out, const DILocalVariable *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d889ad151bdaf0e37c410381812c17e">writeDILabel</a> (raw_ostream &amp;Out, const DILabel *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17ea3efcdbb81ab64b4b54031176d88">writeDIExpression</a> (raw_ostream &amp;Out, const DIExpression *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7fa07d6c1b002682729091f44ed713f">writeDIArgList</a> (raw_ostream &amp;Out, const DIArgList *N, AsmWriterContext &amp;WriterCtx, bool FromValue=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3f4b6a41a95ba9e3750a121736c90e">writeDIGlobalVariableExpression</a> (raw_ostream &amp;Out, const DIGlobalVariableExpression *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8197c96b5ae5517644ec4c331c648782">writeDIObjCProperty</a> (raw_ostream &amp;Out, const DIObjCProperty *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b805938ab35a8870fff225c689a3019">writeDIImportedEntity</a> (raw_ostream &amp;Out, const DIImportedEntity *N, AsmWriterContext &amp;WriterCtx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd54a7261fabfe58a4c7c66ff7846d0">WriteMDNodeBodyInternal</a> (raw_ostream &amp;Out, const MDNode *Node, AsmWriterContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227d0a32d5eaba74f96b14060c31ae26">getWholeProgDevirtResKindName</a> (WholeProgramDevirtResolution::Kind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e8c5d9850cd1e4bcbade2cfc82e56c7">getWholeProgDevirtResByArgKindName</a> (WholeProgramDevirtResolution::ByArg::Kind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab84b1a4040d0e23018b9bfe7ccfbacc5">getTTResKindName</a> (TypeTestResolution::Kind K)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84ad952468a5f8d7ffb8650ec9282cf8">getSummaryKindName</a> (GlobalValueSummary::SummaryKind SK)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd93da4be9b01ed5c96cbfa881aeb71">getLinkageName</a> (GlobalValue::LinkageTypes LT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34ed5c00494852d2cc92e00f1e692490">getLinkageNameWithSpace</a> (GlobalValue::LinkageTypes LT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c65115110985b60bf4d0f71a5ecd550">getVisibilityName</a> (GlobalValue::VisibilityTypes Vis)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb125dbd101f28ac21fec3eb0611dfa4">getImportTypeName</a> (GlobalValueSummary::ImportKind IK)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73529d591c6cc76d12ac7099bbd7e440">printMetadataIdentifier</a> (StringRef Name, formatted_raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac92ccaae13428fbf8fcb741c69863c70">PrintVisibility</a> (GlobalValue::VisibilityTypes Vis, formatted_raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae205407d61d26187ae589c4a4f78320e">PrintDSOLocation</a> (const GlobalValue &amp;GV, formatted_raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a19bb50ce0a6457bf0366b196c9a96">PrintDLLStorageClass</a> (GlobalValue::DLLStorageClassTypes SCT, formatted_raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c542b04650c506ccb8c7adb8984b137">PrintThreadLocalModel</a> (GlobalVariable::ThreadLocalMode TLM, formatted_raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab494dbedb6de02c4dc9f5b12f95100">getUnnamedAddrEncoding</a> (GlobalVariable::UnnamedAddr UA)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed6d706def80ab7bcb8b35112a9f94be">maybePrintComdat</a> (formatted_raw_ostream &amp;Out, const GlobalObject &amp;GO)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46926a2483bd793432d5ca0f7879de3">maybePrintCallAddrSpace</a> (const Value *Operand, const Instruction *I, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a885a6ab00ca58dbc03b09d0485e6f1">isReferencingMDNode</a> (const Instruction &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af20152d720e6ffc7cf0151f2f657c3be">printWithoutType</a> (const Value &amp;V, raw_ostream &amp;O, SlotTracker *Machine, const Module *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print without a type, skipping the <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting">TypePrinting</a> object. <a href="#af20152d720e6ffc7cf0151f2f657c3be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb3001e93d2e932542f82696da1ca4e">printAsOperandImpl</a> (const Value &amp;V, raw_ostream &amp;O, bool PrintType, ModuleSlotTracker &amp;MST)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98078ed9da1a2d013cd401e491649bf8">printMetadataImplRec</a> (raw_ostream &amp;ROS, const Metadata &amp;MD, AsmWriterContext &amp;WriterCtx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursive version of printMetadataImpl. <a href="#a98078ed9da1a2d013cd401e491649bf8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a> (raw_ostream &amp;ROS, const Metadata &amp;MD, ModuleSlotTracker &amp;MST, const Module *M, bool OnlyAsOperand, bool PrintAsTree=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af75b1b5b5c8d48fd86cba0363e9562fa">ST_DEBUG</a>(X)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4060cc153ca27a61adf713615161fba3">HANDLE_MDNODE_LEAF</a>(CLASS)&nbsp;&nbsp;&nbsp;...</td>
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

## Typedefs

### OrderMap {#a1254a95dc7ef84df14d6c1357c6d7b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using OrderMap =  MapVector&lt;const Value *, unsigned&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### UseListOrderMap {#a9dba8485af0d57fec37ee7bd17cafcc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using UseListOrderMap = 
    DenseMap&lt;const Function *, MapVector&lt;const Value *, std::vector&lt;unsigned&gt;&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### PrefixType {#aec73ab739d6b324c9753c7071afd6c2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum PrefixType </td>
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
<td class="doxyEnumItemName">GlobalPrefix<a id="aec73ab739d6b324c9753c7071afd6c2fa09785ab1af640cbe256adc30eb7c72e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ComdatPrefix<a id="aec73ab739d6b324c9753c7071afd6c2faef4db6f596a5ad992a85da3510c31c48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LabelPrefix<a id="aec73ab739d6b324c9753c7071afd6c2fa1c1c0a2fa257d4c584150dbc04ec2509"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LocalPrefix<a id="aec73ab739d6b324c9753c7071afd6c2fa5dd3523630566b2c032744029b66efbd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoPrefix<a id="aec73ab739d6b324c9753c7071afd6c2fad7d0e7a32ebf9b3814731865eac2660f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createSlotTracker() {#a9869c4a9f8b770252b7041cb2edfc66f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SlotTracker * createSlotTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 935 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>

</div>
</div>

### getImportTypeName() {#abb125dbd101f28ac21fec3eb0611dfa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getImportTypeName (<a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737">GlobalValueSummary::ImportKind</a> IK)</td>
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



<p>Definition at line 3375 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737a6d97eb4aadd430937e26cd9ab4813ba1">llvm::GlobalValueSummary::Declaration</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a04e3abfb7aee7a96d3d56a99c9f0b737acb646dd0be0c28c71a939dc87ab59340">llvm::GlobalValueSummary::Definition</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### getLinkageName() {#aacd93da4be9b01ed5c96cbfa881aeb71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getLinkageName (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> LT)</td>
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



<p>Definition at line 3326 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">llvm::GlobalValue::AppendingLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>


<p>Referenced by <a href="#a34ed5c00494852d2cc92e00f1e692490">getLinkageNameWithSpace</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### getLinkageNameWithSpace() {#a34ed5c00494852d2cc92e00f1e692490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getLinkageNameWithSpace (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57c">GlobalValue::LinkageTypes</a> LT)</td>
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



<p>Definition at line 3357 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a> and <a href="#aacd93da4be9b01ed5c96cbfa881aeb71">getLinkageName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>.</p>

</div>
</div>

### getModuleFromDPI() {#a7b98dd2ff18a320795917ace7f8010db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * getModuleFromDPI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> * Marker)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#acf6be32c12a1a6509d7ac0a4d0819f3f">llvm::DbgMarker::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a>.</p>


<p>Referenced by <a href="#a9af15b30bf916411af4026c84ef965ca">getModuleFromDPI</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#a546804db12f646346b125a2d6e8a4bf9">llvm::DbgLabelRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord/#af01d77795bb3f385853944a0fb4dbc40">llvm::DbgLabelRecord::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a5a91755a39059240dcc0a2cdaa8b03ec">llvm::DbgMarker::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#ad24a1b510b43c0dc48de0d37e6fff061">llvm::DbgMarker::print</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a3172de1fbc8c02b9b2cef0b24e3b558f">llvm::DbgVariableRecord::print</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad64862991023c01b0515a7d29716e6ad">llvm::DbgVariableRecord::print</a>.</p>

</div>
</div>

### getModuleFromDPI() {#a9af15b30bf916411af4026c84ef965ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * getModuleFromDPI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * DR)</td>
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



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aa1b7611e70113463caabc2bc84bd08bf">llvm::DbgRecord::getMarker</a> and <a href="#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a>.</p>

</div>
</div>

### getModuleFromVal() {#ac1b59b7799509e47193276bc8b9a716d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * getModuleFromVal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a411cf3e3932f209ce3374cb31adc1da6">llvm::Value::users</a>.</p>


<p>Referenced by <a href="#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a>, <a href="#ac46926a2483bd793432d5ca0f7879de3">maybePrintCallAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a7ba690234245eaba66ec19c429aaa7b3">llvm::Value::print</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a>.</p>

</div>
</div>

### getSummaryKindName() {#a84ad952468a5f8d7ffb8650ec9282cf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getSummaryKindName (<a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614c">GlobalValueSummary::SummaryKind</a> SK)</td>
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



<p>Definition at line 3280 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca9472a9af94b2b12a3e8530336f32685d">llvm::GlobalValueSummary::AliasKind</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca5034481e0a0691fa0f4b4321c33ecb5b">llvm::GlobalValueSummary::FunctionKind</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvaluesummary/#a0c8dfea65f1f5dfba143b1fc9768614ca461342c05a59e66da9d6b38eaccda99a">llvm::GlobalValueSummary::GlobalVarKind</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### getTTResKindName() {#ab84b1a4040d0e23018b9bfe7ccfbacc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getTTResKindName (<a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528bed">TypeTestResolution::Kind</a> K)</td>
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



<p>Definition at line 3169 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528bedacbf788f41139e3717dfde370ec59c0aa">llvm::TypeTestResolution::AllOnes</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528bedad6fc792b7da30012ba5aa2e942383f1f">llvm::TypeTestResolution::ByteArray</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528beda2f70fb5ef215b0969f3b319bab4b03c6">llvm::TypeTestResolution::Inline</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528beda2c2da6acce4cf440ed9351dfe34899f0">llvm::TypeTestResolution::Single</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528beda1893cdb6dc7d73055db02b7e1f46a276">llvm::TypeTestResolution::Unknown</a> and <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528beda5826b981efc11834692037f016343fca">llvm::TypeTestResolution::Unsat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0673433b10a762c449d89d6255ee9f4b">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeTestResolution</a>.</p>

</div>
</div>

### getUnnamedAddrEncoding() {#a4ab494dbedb6de02c4dc9f5b12f95100}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef getUnnamedAddrEncoding (GlobalVariable::UnnamedAddr UA)</td>
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



<p>Definition at line 3764 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a4cc6684df7b4a92b1dec6fce3264fac8">llvm::GlobalValue::Global</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a509820290d57f333403f490dde7316f4">llvm::GlobalValue::Local</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ae8df4be75bfc50b1eadd74e85c25fa45a6adf97f83acf6453d4a6a4b1070f3754">llvm::GlobalValue::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### getVisibilityName() {#a8c65115110985b60bf4d0f71a5ecd550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getVisibilityName (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195">GlobalValue::VisibilityTypes</a> Vis)</td>
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



<p>Definition at line 3363 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">llvm::GlobalValue::ProtectedVisibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a75d0df1adc907ec1c35df6ab26770f5b">anonymous{AsmWriter.cpp}::AssemblyWriter::printSummary</a>.</p>

</div>
</div>

### getWholeProgDevirtResByArgKindName() {#a4e8c5d9850cd1e4bcbade2cfc82e56c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getWholeProgDevirtResByArgKindName (<a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47e">WholeProgramDevirtResolution::ByArg::Kind</a> K)</td>
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



<p>Definition at line 3154 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea8c8876be61a5890671404484313a21e5">llvm::WholeProgramDevirtResolution::ByArg::Indir</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea635d252c06de8cd5c96ebcf3d8989ccf">llvm::WholeProgramDevirtResolution::ByArg::UniformRetVal</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea8bf72562c0a17a25f9e07863e68543b3">llvm::WholeProgramDevirtResolution::ByArg::UniqueRetVal</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea7382e969306ae2118ae88db2a241e833">llvm::WholeProgramDevirtResolution::ByArg::VirtualConstProp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a83d9a3fded69b1a33d8f581f75efe4f3">anonymous{AsmWriter.cpp}::AssemblyWriter::printWPDRes</a>.</p>

</div>
</div>

### getWholeProgDevirtResKindName() {#a227d0a32d5eaba74f96b14060c31ae26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getWholeProgDevirtResKindName (<a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208">WholeProgramDevirtResolution::Kind</a> K)</td>
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



<p>Definition at line 3142 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208ac74c33fab6fb30be2bf7db1f86b0853d">llvm::WholeProgramDevirtResolution::BranchFunnel</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208a332c5d66d09e0ce9c774ed84ce4aaa2d">llvm::WholeProgramDevirtResolution::Indir</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208a05ee7e7ff849410d68ccfd73e177387f">llvm::WholeProgramDevirtResolution::SingleImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a83d9a3fded69b1a33d8f581f75efe4f3">anonymous{AsmWriter.cpp}::AssemblyWriter::printWPDRes</a>.</p>

</div>
</div>

### isReferencingMDNode() {#a6a885a6ab00ca58dbc03b09d0485e6f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isReferencingMDNode (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 4984 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a>.</p>

</div>
</div>

### maybePrintCallAddrSpace() {#ac46926a2483bd793432d5ca0f7879de3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void maybePrintCallAddrSpace (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Operand, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 4236 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#ac1b59b7799509e47193276bc8b9a716d">getModuleFromVal</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>.</p>

</div>
</div>

### maybePrintComdat() {#aed6d706def80ab7bcb8b35112a9f94be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void maybePrintComdat (<a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a> &amp; GO)</td>
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



<p>Definition at line 3776 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#aec73ab739d6b324c9753c7071afd6c2faef4db6f596a5ad992a85da3510c31c48">ComdatPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a98140bed34afff96a44ab31ef977f5ec">llvm::GlobalObject::getComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### orderModule() {#a899f5401a68379402b5754613e045620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OrderMap orderModule (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a> and <a href="#afa51ef8da80e517883688d037a44c362">skipMetadataWrapper</a>.</p>


<p>Referenced by <a href="#aa4b315c2c9cb6fd233d549b85fc8e649">predictUseListOrder</a>.</p>

</div>
</div>

### orderValue() {#a3ae1d92a49245fac09d70bb91ff515ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void orderValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="#a1254a95dc7ef84df14d6c1357c6d7b46">OrderMap</a> &amp; OM)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abca23bddf517f69d28c6d30c58a7b6f9">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::lookup</a>, <a href="#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#acf4c09e1f30cdd4e0b5b1b8a236ead34">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::size</a>.</p>


<p>Referenced by <a href="#a899f5401a68379402b5754613e045620">orderModule</a> and <a href="#a3ae1d92a49245fac09d70bb91ff515ce">orderValue</a>.</p>

</div>
</div>

### predictUseListOrder() {#aa4b315c2c9cb6fd233d549b85fc8e649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UseListOrderMap predictUseListOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a899f5401a68379402b5754613e045620">orderModule</a> and <a href="#a385464d789381c250f924d62222498f3">predictValueUseListOrder</a>.</p>

</div>
</div>

### predictValueUseListOrder() {#a385464d789381c250f924d62222498f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; unsigned &gt; predictValueUseListOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a1254a95dc7ef84df14d6c1357c6d7b46">OrderMap</a> &amp; OM)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abca23bddf517f69d28c6d30c58a7b6f9">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#aa4b315c2c9cb6fd233d549b85fc8e649">predictUseListOrder</a>.</p>

</div>
</div>

### printAsOperandImpl() {#a7cb3001e93d2e932542f82696da1ca4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printAsOperandImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool PrintType, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST)</td>
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



<p>Definition at line 5132 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a12bf76af836ffe2d2e00435a3f0861e9">llvm::ModuleSlotTracker::getModule</a> and <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#a71c852fe821d8efa8a9cb0c359380ac7">llvm::Value::printAsOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a>.</p>

</div>
</div>

### PrintCallingConv() {#a13e35bdf0ecd9533b463d3c902d3659c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintCallingConv (unsigned cc, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca7c23dce1e95fc36e9d2c168f9e036cc7">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X0</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca963e14ac38d6e3b63f8e37085702951c">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca72069ecfe852db0ea1f10c1549989424">llvm::CallingConv::AArch64_SME_ABI_Support_Routines_PreserveMost_From_X2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca300efd85d130657d0d06f0469980bd0f">llvm::CallingConv::AArch64_SVE_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca0e62ecb2c693281fafd77f39b2ddd284">llvm::CallingConv::AArch64_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca16c3e679fa61136bfeb3c5c9b7542d9f">llvm::CallingConv::AMDGPU_CS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8d298f27ddf40e08cd5aacea9837784f">llvm::CallingConv::AMDGPU_CS_Chain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca521c5b7a44a8222c814379b57481aec9">llvm::CallingConv::AMDGPU_CS_ChainPreserve</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad61318e853e529ac703f52a853efa1d1">llvm::CallingConv::AMDGPU_ES</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f9824c54cfd32b3e38c01d5331f318b">llvm::CallingConv::AMDGPU_Gfx</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6f08d1631b96043fe0201973d84e5539">llvm::CallingConv::AMDGPU_GS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca5c0f66e45afd7c51f4ee51552d8fb606">llvm::CallingConv::AMDGPU_HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca27a385675142c462571165c839e41aa0">llvm::CallingConv::AMDGPU_KERNEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf2c5be679d7769a9f3e5e308f73a9ff8">llvm::CallingConv::AMDGPU_LS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca91283117ce67ebdae50cc7730694d8f8">llvm::CallingConv::AMDGPU_PS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1a9f243b16678fc294567b72bbe87223">llvm::CallingConv::AMDGPU_VS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4f42667edde6e9cb80cfae6361e5e76a">llvm::CallingConv::AnyReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca6460922e7050fc0dcff22631e4bc7fdb">llvm::CallingConv::ARM_AAPCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caf5725080d76d25fff371be12a0bf29f4">llvm::CallingConv::ARM_AAPCS_VFP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca39e4f9a6d108588930a09d779d4e812f">llvm::CallingConv::ARM_APCS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca44deee0b3babbda0be6f27856afaacf9">llvm::CallingConv::AVR_INTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca1e000300c2d50f08aa18761448d5860e">llvm::CallingConv::AVR_SIGNAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca3f8227288993442d6f4a0bb234c9bc5b">llvm::CallingConv::CFGuard_Check</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca94ec9273479164e4aec1d5d91b71dc85">llvm::CallingConv::Cold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca75c7c151466ad7e041e9ed8aa4d5a4bf">llvm::CallingConv::CXX_FAST_TLS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca51dcc0bcdca1d5609b0ec4b43c0d9971">llvm::CallingConv::DUMMY_HHVM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad710a26c741142a91059eff051990185">llvm::CallingConv::DUMMY_HHVM_C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cabc8e2ee40a84687a9e12fd08784b87ba">llvm::CallingConv::Fast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca8e8dc64aad833bd23d07d3384522575e">llvm::CallingConv::GHC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae9c6786f93f1d156d2b40ecc6be438bb">llvm::CallingConv::GRAAL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad47327c131a0990283111588b89587cb">llvm::CallingConv::Intel_OCL_BI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafb7645aeee7db3640bbfdad799b4cfe9">llvm::CallingConv::M68k_RTD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cac6355efbcea63774ceca1dfa7b237d42">llvm::CallingConv::MSP430_INTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9f6ac05d37c2fbf197de42295c23fd6e">llvm::CallingConv::PreserveAll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca4eeb29fe27dc20afa4f443765f45f9a5">llvm::CallingConv::PreserveMost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad5385f408f537fc279d485c77d2463ce">llvm::CallingConv::PreserveNone</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9b03ea185599539f24eb1f467627c111">llvm::CallingConv::PTX_Device</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae60325da71f0576e18cc0e5dd7e8afb6">llvm::CallingConv::PTX_Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca12164937f88e72c8b59ca563c70187e0">llvm::CallingConv::RISCV_VectorCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caacadec9c4ef27d184bcbbea409afebb2">llvm::CallingConv::SPIR_FUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca9b5e79699935bf721647d44339701860">llvm::CallingConv::SPIR_KERNEL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2740493172a4ce246941c8cff95e0f83">llvm::CallingConv::Swift</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae64b7afe33922c60d78fea3c08697daa">llvm::CallingConv::SwiftTail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cad6e9c0ff694f0fca0222e79e772b647e">llvm::CallingConv::Tail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cae41511c1ad4197da36cef403f34bac72">llvm::CallingConv::Win64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca10f11fb587acddab17f3ad85eb698fbe">llvm::CallingConv::X86_64_SysV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafde87569738f9e23963e8735f71c33eb">llvm::CallingConv::X86_FastCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca765508a953368531a7d69d1279e6cfb1">llvm::CallingConv::X86_INTR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafab01b07b85e043c71ad4e2715d22073">llvm::CallingConv::X86_RegCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caa88ccf4313b5bc700dec76fd9bc5d40e">llvm::CallingConv::X86_StdCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca97109ccd68cac64fb38dbd24fc4589c6">llvm::CallingConv::X86_ThisCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cacfa4cc9bcdaefd5e969c258c994052b9">llvm::CallingConv::X86_VectorCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>.</p>

</div>
</div>

### PrintDLLStorageClass() {#a81a19bb50ce0a6457bf0366b196c9a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintDLLStorageClass (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8">GlobalValue::DLLStorageClassTypes</a> SCT, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 3735 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">llvm::GlobalValue::DefaultStorageClass</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a81819441fb6de420d4290ac79aaf9dc0">llvm::GlobalValue::DLLExportStorageClass</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8aadc8e43e72669932581b5243b4b444b6">llvm::GlobalValue::DLLImportStorageClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### PrintDSOLocation() {#ae205407d61d26187ae589c4a4f78320e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintDSOLocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 3729 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a19db81b6f3d3ab342972dce7756fb077">llvm::GlobalValue::isDSOLocal</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a2df2f2e94b5493e9434dbf1c483dbc72">llvm::GlobalValue::isImplicitDSOLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>.</p>

</div>
</div>

### PrintLLVMName() {#a3d6e60a917bf5f4052dbb2673f11e087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintLLVMName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="#aec73ab739d6b324c9753c7071afd6c2f">PrefixType</a> Prefix)</td>
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

<p>Turn the specified name into an 'LLVM name', which is either prefixed with % (if the string only contains simple characters) or is surrounded with ""'s (if it has special chars in it).</p>


<p>Print it out.</p>


<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#aec73ab739d6b324c9753c7071afd6c2faef4db6f596a5ad992a85da3510c31c48">ComdatPrefix</a>, <a href="#aec73ab739d6b324c9753c7071afd6c2fa09785ab1af640cbe256adc30eb7c72e1">GlobalPrefix</a>, <a href="#aec73ab739d6b324c9753c7071afd6c2fa1c1c0a2fa257d4c584150dbc04ec2509">LabelPrefix</a>, <a href="#aec73ab739d6b324c9753c7071afd6c2fa5dd3523630566b2c032744029b66efbd">LocalPrefix</a>, <a href="#aec73ab739d6b324c9753c7071afd6c2fad7d0e7a32ebf9b3814731865eac2660f">NoPrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aef01c7734472703b7f3d76c5af23e1d3">llvm::printLLVMNameWithoutPrefix</a>.</p>


<p>Referenced by <a href="#aed6d706def80ab7bcb8b35112a9f94be">maybePrintComdat</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#a56cb601c486724c2c35a0c99db7a6c1e">llvm::Comdat::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ad57efe4558f8566bb06e708cd818578d">anonymous{AsmWriter.cpp}::AssemblyWriter::printArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a6f875a89b00cf04b3d413c954e9fe915">anonymous{AsmWriter.cpp}::AssemblyWriter::printBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="#a4765c34bf6f6177ecba069bd53fb9570">PrintLLVMName</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a399312b003f10b95ad890372a70e0bf8">anonymous{AsmWriter.cpp}::AssemblyWriter::printTypeIdentities</a> and <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>

</div>
</div>

### PrintLLVMName() {#a4765c34bf6f6177ecba069bd53fb9570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintLLVMName (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Turn the specified name into an 'LLVM name', which is either prefixed with % (if the string only contains simple characters) or is surrounded with ""'s (if it has special chars in it).</p>


<p>Print it out.</p>


<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#aec73ab739d6b324c9753c7071afd6c2fa09785ab1af640cbe256adc30eb7c72e1">GlobalPrefix</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#aec73ab739d6b324c9753c7071afd6c2fa5dd3523630566b2c032744029b66efbd">LocalPrefix</a> and <a href="#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a>.</p>

</div>
</div>

### printMetadataIdentifier() {#a73529d591c6cc76d12ac7099bbd7e440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printMetadataIdentifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 3674 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac514ffc60e99e3e3d07b1b11973e2547">anonymous{AsmWriter.cpp}::AssemblyWriter::printNamedMDNode</a>.</p>

</div>
</div>

### printMetadataImpl() {#a2c3485cc2e63a9ea902dccf6dc02a555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printMetadataImpl (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ROS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, bool OnlyAsOperand, bool PrintAsTree=false)</td>
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



<p>Definition at line 5225 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#a6dd54a7261fabfe58a4c7c66ff7846d0">WriteMDNodeBodyInternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/metadata/#a451513f65fe632b0369c9f016117263f">llvm::Metadata::print</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#af19061fd60c2e268172ccc93ab3f5449">llvm::Metadata::print</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#abea60f56bef2a0f9437eed8c8bb9ec58">llvm::Metadata::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/metadata/#a1266599a812617ff001dab4a94eb4a62">llvm::Metadata::printAsOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a141d2c5c786b979a8d86568213295eb2">llvm::MDNode::printTree</a> and <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a4da1f6ae9610c4014ae407ef37477761">llvm::MDNode::printTree</a>.</p>

</div>
</div>

### printMetadataImplRec() {#a98078ed9da1a2d013cd401e491649bf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printMetadataImplRec (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ROS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> &amp; MD, AsmWriterContext &amp; WriterCtx)</td>
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

<p>Recursive version of printMetadataImpl.</p>

<p>Definition at line 5169 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#a6dd54a7261fabfe58a4c7c66ff7846d0">WriteMDNodeBodyInternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdtreeasmwritercontext/#af98e3ae4a907ea6e0f8afdf5da18d283">anonymous{AsmWriter.cpp}::MDTreeAsmWriterContext::onWriteMetadataAsOperand</a>.</p>

</div>
</div>

### PrintShuffleMask() {#a515ea398a2f882f4d1ea69c71ea8d39c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintShuffleMask (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; int &gt; Mask)</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9965a6249be879ba3d336a75a4f3efa7">llvm::PoisonMaskElem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a> and <a href="#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>.</p>

</div>
</div>

### PrintThreadLocalModel() {#a3c542b04650c506ccb8c7adb8984b137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintThreadLocalModel (GlobalVariable::ThreadLocalMode TLM, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 3744 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a55e32c080bb5217324a597d4fb441660">llvm::GlobalValue::GeneralDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a92e26a4a1218d351f5a91e7385a3a320">llvm::GlobalValue::InitialExecTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62ac9f6ea05a2d4cca9e093366042dfa6b8">llvm::GlobalValue::LocalDynamicTLSModel</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a41529b6e723f5025e59ca9364cf70128">llvm::GlobalValue::LocalExecTLSModel</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>.</p>

</div>
</div>

### PrintVisibility() {#ac92ccaae13428fbf8fcb741c69863c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PrintVisibility (<a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195">GlobalValue::VisibilityTypes</a> Vis, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 3720 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195ae1cc9a390520055573d459de25747caa">llvm::GlobalValue::ProtectedVisibility</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>.</p>

</div>
</div>

### printWithoutType() {#af20152d720e6ffc7cf0151f2f657c3be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool printWithoutType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp; V, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/slottracker">SlotTracker</a> * Machine, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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

<p>Print without a type, skipping the <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting">TypePrinting</a> object.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><span class="doxyComputerOutput">true</span> iff printing was successful.</p></dd>
</dl>


<p>Definition at line 5121 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> and <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#a71c852fe821d8efa8a9cb0c359380ac7">llvm::Value::printAsOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a>.</p>

</div>
</div>

### skipMetadataWrapper() {#afa51ef8da80e517883688d037a44c362}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * skipMetadataWrapper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Look for a value that might be wrapped as metadata, e.g.</p>


<p>a value in a metadata operand. Returns the input value as-is if it is not wrapped.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a899f5401a68379402b5754613e045620">orderModule</a>.</p>

</div>
</div>

### WriteAPFloatInternal() {#a994f529208d670bae8bb32b2cd2f2147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WriteAPFloatInternal (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp; APF)</td>
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



<p>Definition at line 1443 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#ab46ff1a80ee89c9e22ca17c179a89ab1">llvm::APFloatBase::BFloat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a9c5a2112c559ffbe2c7bbf5698b6482f">llvm::APFloat::bitcastToAPInt</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a257e3cb529defa79ad7a9f42072f339a">llvm::APFloat::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a37733c4c22afc6a48194783dbd25487c">llvm::APFloat::convertToDouble</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1e29256284cbb6ab1c31bfcdf7770">llvm::format_hex_no_prefix</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a2d5c4385716b3fa4a96e879987cccedc">llvm::APInt::getHiBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a0fa9845f80fa0642b31c238f4ab0d5ef">llvm::APInt::getLoBits</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a07d7341cdcfc7d01525ca04b10fce7a9">llvm::APFloat::getSNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a6ba7c3d54a5a714f7a27861ee114cce3">llvm::APFloatBase::IEEEdouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a86415bb448a78ef1fed893f9eb0f5d06">llvm::APFloatBase::IEEEhalf</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a494661a175e7785032f9a05d963fc0e9">llvm::APFloatBase::IEEEquad</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a0c5765e9acba977f6e462c2917276d8f">llvm::APFloatBase::IEEEsingle</a>, <a href="/web-llvm/docs/api/files/lib/lib/demangle/rustdemangle-cpp/#a12d4f37888b638bcbd9fc0201492c776">isDigit</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#afdbfe0ba27cece5e333f4a7ae68fa82e">llvm::APFloat::isInfinity</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a763d4ccd87f2c21d2079796c0c9cd51a">llvm::APFloat::isNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a2b901c3a0625a7d7173e9bd4864e2775">llvm::APFloat::isNegative</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a833f6b183e2adebde0fb463e6a6297fe">llvm::APFloat::isSignaling</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a3b2fd910a2e9a7bfeb48751fe74f82ff">llvm::APFloatBase::PPCDoubleDouble</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a22ed74f1ed33c4d33f524a650ea536a6">llvm::APFloatBase::rmNearestTiesToEven</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a416dc650964ad640df99464a32aa49da">llvm::APFloat::toString</a> and <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a4830aff0741b3cd7a3920826ae6c0ece">llvm::APFloatBase::x87DoubleExtended</a>.</p>


<p>Referenced by <a href="#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>.</p>

</div>
</div>

### WriteAsOperandInternal() {#aa606b073a92a001293ee7320bad02c97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WriteAsOperandInternal (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2597 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a2c0e1ae3b31928af2e0a390bbc2ea9b8ac2322cfab42cb6c46aa198861244231e">llvm::InlineAsm::AD_Intel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9869c4a9f8b770252b7041cb2edfc66f">createSlotTracker</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>, <a href="#a3d6e60a917bf5f4052dbb2673f11e087">PrintLLVMName</a>, <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ae9005670841925a061ef19fe62955bce">anonymous{AsmWriter.cpp}::AssemblyWriter::printAlias</a>, <a href="#a7cb3001e93d2e932542f82696da1ca4e">printAsOperandImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a0550e356effa7d9246d22a6cf35a852b">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgLabelRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a7c33f7bfe854f12e21290f2a03a10a18">anonymous{AsmWriter.cpp}::AssemblyWriter::printDbgVariableRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a89d2a6c720f05584135f01f20cc3c9ee">anonymous{AsmWriter.cpp}::AssemblyWriter::printIFunc</a>, <a href="#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a>, <a href="#a98078ed9da1a2d013cd401e491649bf8">printMetadataImplRec</a>, <a href="#af20152d720e6ffc7cf0151f2f657c3be">printWithoutType</a>, <a href="#a3b2195c3b9d667a9857b9bce7eb8e267">WriteAsOperandInternal</a>, <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>, <a href="#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>, <a href="#af7fa07d6c1b002682729091f44ed713f">writeDIArgList</a>, <a href="#adfb4d18db2159531ff68606f587116f4">writeMDTuple</a>, <a href="#a060c83e55e124b32a1b41542ee254d98">writeMetadataAsOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac7a7c36cb1f1a299406e3cfa95b7404e">anonymous{AsmWriter.cpp}::AssemblyWriter::writeOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a404d6605bd1587cb6b67b8b1f575022e">anonymous{AsmWriter.cpp}::AssemblyWriter::writeOperandBundles</a> and <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#adc27aa83649282c846c35b22413ebf83">anonymous{AsmWriter.cpp}::AssemblyWriter::writeParamOperand</a>.</p>

</div>
</div>

### WriteAsOperandInternal() {#a3b2195c3b9d667a9857b9bce7eb8e267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WriteAsOperandInternal (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD, AsmWriterContext &amp; WriterCtx, bool FromValue=false)</td>
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



<p>Definition at line 2676 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>, <a href="#af7fa07d6c1b002682729091f44ed713f">writeDIArgList</a>, <a href="#ae17ea3efcdbb81ab64b4b54031176d88">writeDIExpression</a> and <a href="#a9d08596bb6d02dac5a3629abda510174">writeDILocation</a>.</p>

</div>
</div>

### WriteConstantInternal() {#aa58433c5fc6be661639b52de0822d890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WriteConstantInternal (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * CV, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 1536 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#acd530d0571f320d47d37e7ae51cf70ff">llvm::Constant::getAggregateElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a25ca2f3cb40ae1c26c73054659203b2d">llvm::Constant::getSplatValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regutils-h/#a1fa2460e32327ade49189c95740bc1b5">NC</a>, <a href="#a515ea398a2f882f4d1ea69c71ea8d39c">PrintShuffleMask</a>, <a href="#a994f529208d670bae8bb32b2cd2f2147">WriteAPFloatInternal</a>, <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a> and <a href="#a2ced856c3217b5902cfc6e22ade76eaa">WriteOptimizationInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/value/#a7ba690234245eaba66ec19c429aaa7b3">llvm::Value::print</a> and <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>

</div>
</div>

### writeDIArgList() {#af7fa07d6c1b002682729091f44ed713f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIArgList (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diarglist">DIArgList</a> * N, AsmWriterContext &amp; WriterCtx, bool FromValue=false)</td>
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



<p>Definition at line 2524 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a> and <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="#a3b2195c3b9d667a9857b9bce7eb8e267">WriteAsOperandInternal</a>.</p>

</div>
</div>

### writeDIAssignID() {#ae63e2c24c65979ed0c3a52704a8d6c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIAssignID (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> * DL, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2050 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIBasicType() {#ab007fb7393c2c55689a30b5c9f9b54e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIBasicType (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dibasictype">DIBasicType</a> * N, AsmWriterContext &amp;)</td>
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



<p>Definition at line 2160 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga8a7e29291b6e812a89dcdbb07948c0ac">llvm::dwarf::AttributeEncodingString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDICommonBlock() {#aa4ab58811d85ab06ba2589190e42c409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDICommonBlock (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicommonblock">DICommonBlock</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2380 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDICompileUnit() {#abf928d48c46a6de39967c53eecfb6320}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDICompileUnit (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompileunit">DICompileUnit</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2289 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga6040ef7c99341269e7c3ffe8347f72b3">llvm::dwarf::LanguageString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDICompositeType() {#a187176da17ddab193a07b2cde86c2297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDICompositeType (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2227 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga6040ef7c99341269e7c3ffe8347f72b3">llvm::dwarf::LanguageString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIDerivedType() {#a6f6d9d4bb9a4379614584f1dc6ec07cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIDerivedType (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diderivedtype">DIDerivedType</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2194 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIEnumerator() {#ad48e4b73f1c3fda1be498800e79bb2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIEnumerator (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dienumerator">DIEnumerator</a> * N, AsmWriterContext &amp;)</td>
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



<p>Definition at line 2148 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIExpression() {#ae17ea3efcdbb81ab64b4b54031176d88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIExpression (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2499 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga8a7e29291b6e812a89dcdbb07948c0ac">llvm::dwarf::AttributeEncodingString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0caee0952c3cd8bf8106bbfa0a323c1ca82">llvm::dwarf::DW_OP_LLVM_convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gad20f8c5eb7af765400eea967ff2645b3">llvm::dwarf::OperationEncodingString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac514ffc60e99e3e3d07b1b11973e2547">anonymous{AsmWriter.cpp}::AssemblyWriter::printNamedMDNode</a> and <a href="#a3b2195c3b9d667a9857b9bce7eb8e267">WriteAsOperandInternal</a>.</p>

</div>
</div>

### writeDIFile() {#a593a29eb296078e4adc21c4735cbf089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIFile (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/difile">DIFile</a> * N, AsmWriterContext &amp;)</td>
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



<p>Definition at line 2274 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIGenericSubrange() {#ac7cbec4f02d601d51217c096e1462805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIGenericSubrange (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/digenericsubrange">DIGenericSubrange</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2097 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a> and <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a5307ea3a541fa8d6d713f305541c0782a8a57732b81b5f0593b28e007f88acd95">llvm::DIExpression::SignedConstant</a>.</p>

</div>
</div>

### writeDIGlobalVariable() {#a3a754075676cf28fe91f2d0bb1b5fc44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariable">DIGlobalVariable</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2453 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIGlobalVariableExpression() {#a0f3f4b6a41a95ba9e3750a121736c90e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIGlobalVariableExpression (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diglobalvariableexpression">DIGlobalVariableExpression</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2539 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIImportedEntity() {#a7b805938ab35a8870fff225c689a3019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIImportedEntity (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diimportedentity">DIImportedEntity</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2563 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDILabel() {#a6d889ad151bdaf0e37c410381812c17e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDILabel (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2488 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDILexicalBlock() {#ae839d5f52524ed2102d25ae1ffe92deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDILexicalBlock (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilexicalblock">DILexicalBlock</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2347 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDILexicalBlockFile() {#accd701498a663907e97c9dcedfa7a54a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDILexicalBlockFile (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilexicalblockfile">DILexicalBlockFile</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2358 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDILocalVariable() {#ab6bcc5e28f19737a3b0ec69ff062c0f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDILocalVariable (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable">DILocalVariable</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2472 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDILocation() {#a9d08596bb6d02dac5a3629abda510174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDILocation (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * DL, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2036 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>


<p>Referenced by <a href="#a3b2195c3b9d667a9857b9bce7eb8e267">WriteAsOperandInternal</a>.</p>

</div>
</div>

### writeDIMacro() {#a01d062dbede1f91bf1c960a57fd349dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIMacro (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimacro">DIMacro</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2392 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIMacroFile() {#afd6c1602b1a0ffbb1aad2c7cc9bac1d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIMacroFile (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimacrofile">DIMacroFile</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2403 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIModule() {#a5584c0a21c6481a943ab39406bd62098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIModule (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dimodule">DIModule</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2413 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDINamespace() {#a9d3673e478e66c19b06dcbfb588686c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDINamespace (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dinamespace">DINamespace</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2370 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIObjCProperty() {#a8197c96b5ae5517644ec4c331c648782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIObjCProperty (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diobjcproperty">DIObjCProperty</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2549 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDIStringType() {#a3480bb9edd827c6105a2a28652142d9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDIStringType (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/distringtype">DIStringType</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2176 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga8a7e29291b6e812a89dcdbb07948c0ac">llvm::dwarf::AttributeEncodingString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDISubprogram() {#a82755caf4693707060eaa24ed59ebd2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDISubprogram (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubprogram">DISubprogram</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2319 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDISubrange() {#ac7e7ff419d64524657abe5c1389f34dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDISubrange (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubrange">DISubrange</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2056 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDISubroutineType() {#a5fbddbd7054d4a95232371b2c436ab7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDISubroutineType (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/disubroutinetype">DISubroutineType</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2263 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gac4a7b29b47eace62bb7a896f03954881">llvm::dwarf::ConventionString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDITemplateTypeParameter() {#ab9f46d7b60f100ca64722051bf8401b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDITemplateTypeParameter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditemplatetypeparameter">DITemplateTypeParameter</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2428 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeDITemplateValueParameter() {#af836f3f665f5c5c4ba40edc1db6ab530}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDITemplateValueParameter (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ditemplatevalueparameter">DITemplateValueParameter</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2439 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a>.</p>

</div>
</div>

### writeGenericDINode() {#ab51487913b1d80a22af63de2ff1dcb89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeGenericDINode (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/genericdinode">GenericDINode</a> * N, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 2018 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilprettyprinter-cpp/#aa60cf1897c36e79b878a6f3c6300cfba">Printer</a> and <a href="#a060c83e55e124b32a1b41542ee254d98">writeMetadataAsOperand</a>.</p>

</div>
</div>

### WriteMDNodeBodyInternal() {#a6dd54a7261fabfe58a4c7c66ff7846d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WriteMDNodeBodyInternal (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node, AsmWriterContext &amp; Ctx)</td>
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



<p>Definition at line 2577 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ac99997dcb417b8486233aed7f162cb0e">anonymous{AsmWriter.cpp}::AssemblyWriter::printMDNodeBody</a>, <a href="#a2c3485cc2e63a9ea902dccf6dc02a555">printMetadataImpl</a> and <a href="#a98078ed9da1a2d013cd401e491649bf8">printMetadataImplRec</a>.</p>

</div>
</div>

### writeMDTuple() {#adfb4d18db2159531ff68606f587116f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMDTuple (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mdtuple">MDTuple</a> * Node, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 1797 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1e56c814d11206720cc23059b871128d">llvm::Value::print</a> and <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>

</div>
</div>

### writeMetadataAsOperand() {#a060c83e55e124b32a1b41542ee254d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMetadataAsOperand (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD, AsmWriterContext &amp; WriterCtx)</td>
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



<p>Definition at line 1906 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#aa606b073a92a001293ee7320bad02c97">WriteAsOperandInternal</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-asmwriter-cpp-/mdfieldprinter/#a19cf59d0aa8b7582f631f08efb4c1bc1">anonymous{AsmWriter.cpp}::MDFieldPrinter::printMetadata</a> and <a href="#ab51487913b1d80a22af63de2ff1dcb89">writeGenericDINode</a>.</p>

</div>
</div>

### WriteOptimizationInfo() {#a2ced856c3217b5902cfc6e22ade76eaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void WriteOptimizationInfo (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/user">User</a> * U)</td>
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



<p>Definition at line 1400 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/micromipssizereduction-cpp/#aaac99696c5f396905a86fa853f41614f">InRange</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a> and <a href="#aa58433c5fc6be661639b52de0822d890">WriteConstantInternal</a>.</p>

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
    <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/runtimedyld/runtimedyldelf-cpp/#a79ab15165c16fbf94d6fd33bd890ea7e">write</a>##CLASS(Out, cast&lt;CLASS&gt;(<a href="/web-llvm/docs/api/classes/node">Node</a>), Ctx);                                 \
    break;
</div>
</dd>
</dl>

<p>Definition at line 2587 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>

</div>
</div>

### ST\_DEBUG {#af75b1b5b5c8d48fd86cba0363e9562fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ST_DEBUG(X)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/slottracker/#a3cbc4a42a4d42b46b1202a67ee830fb7">llvm::SlotTracker::purgeFunction</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
