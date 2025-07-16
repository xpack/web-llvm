---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/asmparser/llparser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LLParser.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">llvm/AsmParser/LLParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/apsint-h">llvm/ADT/APSInt.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stlextras-h">llvm/ADT/STLExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/scopeexit-h">llvm/ADT/ScopeExit.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallptrset-h">llvm/ADT/SmallPtrSet.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/lltoken-h">llvm/AsmParser/LLToken.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/slotmapping-h">llvm/AsmParser/SlotMapping.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/argument-h">llvm/IR/Argument.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/autoupgrade-h">llvm/IR/AutoUpgrade.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/callingconv-h">llvm/IR/CallingConv.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/comdat-h">llvm/IR/Comdat.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrange-h">llvm/IR/ConstantRange.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constantrangelist-h">llvm/IR/ConstantRangeList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalifunc-h">llvm/IR/GlobalIFunc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/globalobject-h">llvm/IR/GlobalObject.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/institerator-h">llvm/IR/InstIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsicinst-h">llvm/IR/IntrinsicInst.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/intrinsics-h">llvm/IR/Intrinsics.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/llvmcontext-h">llvm/IR/LLVMContext.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/metadata-h">llvm/IR/Metadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/value-h">llvm/IR/Value.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuesymboltable-h">llvm/IR/ValueSymbolTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/mathextras-h">llvm/Support/MathExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/modref-h">llvm/Support/ModRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/saveandrestore-h">llvm/Support/SaveAndRestore.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;algorithm&gt;
#include &lt;cassert&gt;
#include &lt;cstring&gt;
#include &lt;optional&gt;
#include &lt;vector&gt;
#include "llvm/IR/Attributes.inc"
#include "llvm/IR/Metadata.def"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-llparser-cpp-">anonymous{LLParser.cpp}</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdfieldimpl">MDFieldImpl&lt;FieldTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Structure to represent an optional metadata field. <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdfieldimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl">MDEitherFieldImpl&lt;FieldTypeA, FieldTypeB&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Structure to represent an optional metadata field that can be of either type (A or B) and encapsulates the MD&lt;typeofA&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> and MD&lt;typeofB&gt;<a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a> structs, so not to reimplement the specifics for representing each <a href="/web-llvm/docs/api/files/lib/lib/support/optimizedstructlayout-cpp/#a5208f2b0568d811c542f8d8097dbc035">Field</a>. <a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdeitherfieldimpl/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdunsignedfield">MDUnsignedField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/linefield">LineField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/columnfield">ColumnField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/dwarftagfield">DwarfTagField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/dwarfmacinfotypefield">DwarfMacinfoTypeField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/dwarfattencodingfield">DwarfAttEncodingField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/dwarfvirtualityfield">DwarfVirtualityField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/dwarflangfield">DwarfLangField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/dwarfccfield">DwarfCCField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/emissionkindfield">EmissionKindField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/nametablekindfield">NameTableKindField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/diflagfield">DIFlagField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/dispflagfield">DISPFlagField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdapsintfield">MDAPSIntField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdsignedfield">MDSignedField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdboolfield">MDBoolField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdfield">MDField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdstringfield">MDStringField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdfieldlist">MDFieldList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/checksumkindfield">ChecksumKindField</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-llparser-cpp-/mdsignedormdfield">MDSignedOrMDField</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31297e70271da82249db4e0d3ccdd66">getTypeString</a> (Type *T)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab036d04a80df6b9a9f3dbf42a3884bb8">dropIntrinsicWithUnknownMetadataArgument</a> (IntrinsicInst *II)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1cc1d4deb4e05e7fc7c7afb70c5cc5c">isValidVisibilityForLinkage</a> (unsigned V, unsigned L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbd8730936ced41a4a321982c143fbda">isValidDLLStorageClassForLinkage</a> (unsigned S, unsigned L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bbf1b914ac436764ec303507b0dfc77">maybeSetDSOLocal</a> (bool DSOLocal, GlobalValue &amp;GV)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa170df8d213263b890104ebef52f7417">isSanitizer</a> (lltok::Kind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4882d403b294f57c1eeaedfd313db2d">tokenToAttribute</a> (lltok::Kind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a289f0904787d39d2f7a13725934f8767">upgradeMemoryAttr</a> (MemoryEffects &amp;ME, lltok::Kind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d6da0e1f35c3d34f969bc596d61b19">createGlobalFwdRef</a> (Module *M, PointerType *PTy)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f932875febb6508623dc741eadbb92">parseOptionalLinkageAux</a> (lltok::Kind Kind, bool &amp;HasLinkage)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1f">MemoryEffects::Location</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32074010b4570770828aa51b881e93de">keywordToLoc</a> (lltok::Kind Tok)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2e">ModRefInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5a59624e9f60aceef546391dcfacaa">keywordToModRef</a> (lltok::Kind Tok)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a919ec6d13814943d76df4587b533fcc7">keywordToFPClassTest</a> (lltok::Kind Tok)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1298b18b7e3099c7e9998d9970ec0bc">isOldDbgFormatIntrinsic</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d87a8ae724eba2205807b392fe8cc93">resolveFwdRef</a> (ValueInfo *Fwd, ValueInfo &amp;Resolved)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19f7ab77372e68d025c49fb29e306ec9">AllowIncompleteIR</a>("allow-incomplete-ir", cl::init(false), cl::Hidden, cl::desc("Allow incomplete IR on a best effort basis (references to unknown " "metadata will be dropped)"))</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada2ac5e1f921bd9aeb520dde0bd38572">EmptyVI</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbefbef47da9325952c0794854bdbe72">FwdVIRef</a> = (GlobalValueSummaryMapTy::value_type *)-8</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba63655d8ee18e876fc5cee12bbaa35e">GET_ATTR_NAMES</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac52fd56f4583e0aed1c9b900c3ac98c4">ATTRIBUTE_ENUM</a>(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4395a6e9b387da7779af9d12538b0fc9">HANDLE_SPECIALIZED_MDNODE_LEAF</a>(CLASS)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d48732979f09429678feca6ef8ae3c4">DECLARE_FIELD</a>(NAME, TYPE, INIT)&nbsp;&nbsp;&nbsp;TYPE NAME <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c/#af319751162595d897c085e511c7e7d4a">INIT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a682f88278e493b169aeb5d1f648eb75e">NOP_FIELD</a>(NAME, TYPE, INIT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76921ba6785305eb680bb2797802c8ca">REQUIRE_FIELD</a>(NAME, TYPE, INIT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5637a0c40a619399423f4f2ed5c8d35">PARSE_MD_FIELD</a>(NAME, TYPE, DEFAULT)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3429bc3e3beab695470f2072512ec49">PARSE_MD_FIELDS</a>()&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb35227be2ff51424e5ee991a94106e0">GET_OR_DISTINCT</a>(CLASS, ARGS)&nbsp;&nbsp;&nbsp;  (IsDistinct ? CLASS::getDistinct ARGS : CLASS::get ARGS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c67ee631491c7a41f94ab57f955509">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e48de7b196cc1dcbbb54c54b1f61450">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a7312720d68088c3cbd9b879861925">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8524ffb09e8bf9cc34614c28bb262a1">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e60835010cb18475f7f961190bd18fa">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a164102333d655020debf804a3c23c5c1">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209d2e63cc65f7494214d24e4550a055">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9f9ad3c8acb9fb6c986b3c05c732fbb">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2fd7ba3efe602325a0ac4c61ee05ed">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1be14c051024218ef6c27ee1047cd9">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06338927887fe7934f0716f48af5f961">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24e4d3c77456c254e27a47e34b93f29">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6f78c09138c43b6102f993a002e409">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b78526e79309c112c1242525f25be22">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4996da66cf2df124315bb0992278da1f">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08549ca1c540841bea354fa8e28b46c2">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5871abd427e7a5549de32b74c33a7138">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecad3299be2ea49b7b428a0670edc9e8">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06c20e3fcdd09ef9109aff28783ad50">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2746631c317ae72b1504401ae2572d39">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bbc0dd7ceff37945678a3584f721c3c">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9853d4b99a76ea98d3198a338244c4a">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f353c3b5950f0f7a3e657e43523da6a">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31ec2ebff96b13793a3184639a172c20">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43242f43522e0cc509179169afa63950">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad863d0970571721ea2c1b9df53758a24">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960369d543e112a40347a9d54a09713e">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757efeaaf919132f1e7c08f7331c88b4">VISIT_MD_FIELDS</a>(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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

### createGlobalFwdRef() {#a10d6da0e1f35c3d34f969bc596d61b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue * createGlobalFwdRef (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/pointertype">PointerType</a> * PTy)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1753 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a05c6b3b9372b56d130e005db4837da62a7483b56cbb22b39c485b4648ea3374b0">llvm::GlobalValue::NotThreadLocal</a>.</p>

</div>
</div>

### dropIntrinsicWithUnknownMetadataArgument() {#ab036d04a80df6b9a9f3dbf42a3884bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void dropIntrinsicWithUnknownMetadataArgument (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * II)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getTypeString() {#af31297e70271da82249db4e0d3ccdd66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getTypeString (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#a6732e8d3ff8100a662ce73634840b990">llvm::raw_string_ostream::str</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a2cea2a552183ce91c9617c732d395ee0">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::emitStackSlotRemark</a> and <a href="/web-llvm/docs/api/structs/stackaccess/#a5be5f0677613e0b2b7ca1b43b93dae3b">StackAccess::print</a>.</p>

</div>
</div>

### isOldDbgFormatIntrinsic() {#af1298b18b7e3099c7e9998d9970ec0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isOldDbgFormatIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 6370 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a821cf516da0409f54e4cd8a5b7478ea7">llvm::Intrinsic::lookupIntrinsicID</a>.</p>

</div>
</div>

### isSanitizer() {#aa170df8d213263b890104ebef52f7417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSanitizer (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Kind)</td>
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



<p>Definition at line 1304 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa1b0672a58a313ca67ad195d8373b3db">llvm::lltok::kw_no_sanitize_address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a15a250982fb6d404f7c1a467da20d56b">llvm::lltok::kw_no_sanitize_hwaddress</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa2915d61202bc5ccfedc6e13083f2fcb">llvm::lltok::kw_sanitize_address_dyninit</a>.</p>

</div>
</div>

### isValidDLLStorageClassForLinkage() {#afbd8730936ced41a4a321982c143fbda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidDLLStorageClassForLinkage (unsigned S, unsigned L)</td>
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



<p>Definition at line 1139 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6948096330886cc831391c75adbadaf8a5354f0f932438b7ec4d5d82d4ec1ae22">llvm::GlobalValue::DefaultStorageClass</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>.</p>

</div>
</div>

### isValidVisibilityForLinkage() {#af1cc1d4deb4e05e7fc7c7afb70c5cc5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isValidVisibilityForLinkage (unsigned V, unsigned L)</td>
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



<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a2491e41d821f1d8fd3958ce3df2fddb2">llvm::GlobalValue::DefaultVisibility</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a308b65a044b4f53e31a2026a81c991d2">llvm::GlobalValue::isLocalLinkage</a>.</p>

</div>
</div>

### keywordToFPClassTest() {#a919ec6d13814943d76df4587b533fcc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned keywordToFPClassTest (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Tok)</td>
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



<p>Definition at line 2568 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dabf7829a22591343ad790b1357955a7df">llvm::fcAllFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da00a4419741933f5cb7ec001aaa6e6bb5">llvm::fcInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dafe1646e5477c571f7791c524b54b11fe">llvm::fcNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da3ab665df1666568d7eac3b1373106638">llvm::fcNegInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab003a118cd0b76a814ba4dfc7077034a">llvm::fcNegNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da023ad3d9b33a1af5eb90b8b543fb3ccb">llvm::fcNegSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da1e8072411cd3959aa091c3cae8006dc0">llvm::fcNegZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dadb8c9ce3197adf47c7f889bab120b77c">llvm::fcNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dada0d259988860d7a2f882aa40b25fee1">llvm::fcPosInf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da052ace75708c251359ff22dd036417a6">llvm::fcPosNormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dad0940edb5f5bf512669b72928b527d0c">llvm::fcPosSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da7ace586671df3e62fa392d5144a8b3da">llvm::fcPosZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da05bb099c0a65e5b835ed8cd0b326df7c">llvm::fcQNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da9d366dced7a639841b0ced40c82ccb28">llvm::fcSNan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1da449c8fca7f540cc314102a67944fcd6e">llvm::fcSubnormal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1dab6ede72b2b2219068b9bb89732d24e2f">llvm::fcZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa47e53a2ba978205741d2162786f14d5">llvm::lltok::kw_all</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a168f077d7e35f4de95cd1b80f9f45af4">llvm::lltok::kw_inf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a90ff7b899c682efa9da7adbaca6048ba">llvm::lltok::kw_nan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1acceffabdbc4feafbda488564dff9eb01">llvm::lltok::kw_ninf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a69fe9c31217302c965b8424e83b6234e">llvm::lltok::kw_nnorm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a26af429feedc3f2bd2f5c1097dbf4454">llvm::lltok::kw_norm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a67499b09c37fbbfde216c15851b88833">llvm::lltok::kw_nsub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a874ae6e8608febad14f0ac7292e01fe1">llvm::lltok::kw_nzero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a9df6f5e917910f294b21c7e7334a6d33">llvm::lltok::kw_pinf</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa8d90c4f2d1e9adcdf9857e524685523">llvm::lltok::kw_pnorm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1af378892b79c63716fcb841288ca7062d">llvm::lltok::kw_psub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a48e2fe169bfae6d4923b19a784d9a916">llvm::lltok::kw_pzero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a546979af562aefebc573f10b46e8a399">llvm::lltok::kw_qnan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aaf04ecdc12d02d93d2c0a5d4462fa0ea">llvm::lltok::kw_snan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aaac2dade1d978e7ee9ba2276a9b07140">llvm::lltok::kw_sub</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a4277a659fb10eda43ea113cbc220235f">llvm::lltok::kw_zero</a>.</p>

</div>
</div>

### keywordToLoc() {#a32074010b4570770828aa51b881e93de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; MemoryEffects::Location &gt; keywordToLoc (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Tok)</td>
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



<p>Definition at line 2487 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa16fb931dad01a15ae45a7a90cd3e6276">llvm::ArgMem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1facf7e5975f35256eb4d98f15f212f2a4c">llvm::InaccessibleMem</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1afea6dfe46b2fbb7959d4887e406fa025">llvm::lltok::kw_argmem</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1af1a6f54e8e446f826cab5db61dc8f199">llvm::lltok::kw_inaccessiblemem</a>.</p>

</div>
</div>

### keywordToModRef() {#a9d5a59624e9f60aceef546391dcfacaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ModRefInfo &gt; keywordToModRef (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Tok)</td>
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



<p>Definition at line 2498 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a979bba312692fc126fd1dfccdf2ed1c5">llvm::lltok::kw_none</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa503ec403089083dcd1dfbb623392e7c">llvm::lltok::kw_read</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aaae1eca7aa2da4d63ad5bb1fb4267a01">llvm::lltok::kw_readwrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a3ed9cf9425bec05e166da7a70c538ca6">llvm::lltok::kw_write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea7aeb0277500c86e4aa6bd23f9a737942">llvm::Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea6524b183b5cd0850f2cff6d30d581af9">llvm::ModRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ead974636fce6d12e72054e61fb3c1e9a8">llvm::NoModRef</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9db8c44b250b90e3ab7e4d144e7c9c2ea60baadb22e80b147e4885ad16760e569">llvm::Ref</a>.</p>

</div>
</div>

### maybeSetDSOLocal() {#a1bbf1b914ac436764ec303507b0dfc77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void maybeSetDSOLocal (bool DSOLocal, <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> &amp; GV)</td>
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



<p>Definition at line 1146 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a78c4d0538c7dbffa955486abae2b61bb">llvm::GlobalValue::setDSOLocal</a>.</p>

</div>
</div>

### parseOptionalLinkageAux() {#a74f932875febb6508623dc741eadbb92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned parseOptionalLinkageAux (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Kind, bool &amp; HasLinkage)</td>
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



<p>Definition at line 2022 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca96ad6314ba9210b223b93dc3e15baf99">llvm::GlobalValue::AppendingLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa67f293befacbbf974525116ccf2ff42">llvm::GlobalValue::AvailableExternallyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca08c6a63ca3d9cdb39fb584655bf5c501">llvm::GlobalValue::CommonLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caa81fc8db28ac4af45766fbab2e79d466">llvm::GlobalValue::ExternalWeakLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1af1183160f68e281f63fabf22de5ccd32">llvm::lltok::kw_appending</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1ab6df28420b9c5c0c752b58cf802329b2">llvm::lltok::kw_available_externally</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1adcb7d44c53142ff56b77d95b7482308e">llvm::lltok::kw_common</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1ab028641b51874f8934d5ede6d56c885d">llvm::lltok::kw_extern_weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a5bf55c2e627123f19c3a18d83bc66b7d">llvm::lltok::kw_external</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a11a21e7bfe7c18cdb69f7726798eea0e">llvm::lltok::kw_internal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a1ea06522e5d4bcb19d10a8973474ffac">llvm::lltok::kw_linkonce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a43b88d52e4451eba8f1bc5bff46ff748">llvm::lltok::kw_linkonce_odr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a3a8aed8a424bcd8de2a699acccadccbf">llvm::lltok::kw_private</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a2df91eac232a0e7806e8a879837992d5">llvm::lltok::kw_weak</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a79877e4418e132c7b3648b473938d978">llvm::lltok::kw_weak_odr</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca5ebf288ceb5bbeb7025564727db6d705">llvm::GlobalValue::LinkOnceAnyLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57caf2b592edf18170e7aff4e8f3bae3360c">llvm::GlobalValue::LinkOnceODRLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca8d13a9bcecfac72febceb1103afa048f">llvm::GlobalValue::WeakAnyLinkage</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca696bb1c9b0b0e76bb70c61f68866452a">llvm::GlobalValue::WeakODRLinkage</a>.</p>

</div>
</div>

### resolveFwdRef() {#a5d87a8ae724eba2205807b392fe8cc93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void resolveFwdRef (<a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> * Fwd, <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a> &amp; Resolved)</td>
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



<p>Definition at line 9278 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/valueinfo/#aca57d10692713e1f20c11565e8b6af97">llvm::ValueInfo::isReadOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/valueinfo/#a710d65ae845d843fea253c1133641af1">llvm::ValueInfo::isWriteOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/valueinfo/#a1bbef87be5be5c7af41edc809b35f7a7">llvm::ValueInfo::setReadOnly</a> and <a href="/web-llvm/docs/api/structs/llvm/valueinfo/#a24abfad5938fe9dfac0ac45bdf77b154">llvm::ValueInfo::setWriteOnly</a>.</p>

</div>
</div>

### tokenToAttribute() {#ad4882d403b294f57c1eeaedfd313db2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute::AttrKind tokenToAttribute (<a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Kind)</td>
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



<p>Definition at line 1536 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a>.</p>

</div>
</div>

### upgradeMemoryAttr() {#a289f0904787d39d2f7a13725934f8767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool upgradeMemoryAttr (<a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a> &amp; ME, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1">lltok::Kind</a> Kind)</td>
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



<p>Definition at line 1656 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5288b2ba178703d9e1f24a5d3708f594">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::argMemOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5cba4a49c183c6c2f6168be64f04a7b9">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleMemOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#ad341f584befc40ff0aefca99682baf7c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleOrArgMemOnly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a7c6687b198db30a96226b6ac7e4ae9c6">llvm::lltok::kw_argmemonly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1aa1b9cb87eeeb24b6f51127789dd2c828">llvm::lltok::kw_inaccessiblemem_or_argmemonly</a>, <a href="/web-llvm/docs/api/namespaces/llvm/lltok/#af353621f14cb4b4b3af5ffaff84076b1a229916a2e488b9a6eac4100b95e0fe03">llvm::lltok::kw_inaccessiblememonly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a0dc1a3456bce25673dff8dce6f240a8f">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::readOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a9e3dc568b5f51e03441c9c44b618f337">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::writeOnly</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllowIncompleteIR {#a19f7ab77372e68d025c49fb29e306ec9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowIncompleteIR("allow-incomplete-ir", cl::init(false), cl::Hidden, cl::desc( "Allow incomplete IR on a best effort basis (references to unknown " "metadata will be dropped)"))</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### EmptyVI {#ada2ac5e1f921bd9aeb520dde0bd38572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueInfo EmptyVI</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
    <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a>(false, (GlobalValueSummaryMapTy::value_type *)-8)
</div>
</dd>
</dl>

<p>Definition at line 8919 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/custommappingtraits-5afad16d6df5c47889a55ee752aaf37b/#a1874019c6f0fc2246bcc6a1aa3e5b383">llvm::yaml::CustomMappingTraits&lt; GlobalValueSummaryMapTy &gt;::fixAliaseeLinks</a>.</p>

</div>
</div>

### FwdVIRef {#afbefbef47da9325952c0794854bdbe72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const auto FwdVIRef = (GlobalValueSummaryMapTy::value_type *)-8</td>
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



<p>Definition at line 9276 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>.</p>

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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0a60b22edc59b0e3919841d92a72a8ef">llvm::printMIR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a47e52319ebd640bd762b84740e850e9d">llvm::printMIR</a>, <a href="/web-llvm/docs/api/classes/llvm/printfunctionpass/#a5d4b836698202124122a0ee03d37b3e8">llvm::PrintFunctionPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/printmodulepass/#abb1b61a3833aedd2fa62272bfd6740f3">llvm::PrintModulePass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-irprintingpasses-cpp-/printfunctionpasswrapper/#ad71c15d159562f071fe3b12feda61a64">anonymous{IRPrintingPasses.cpp}::PrintFunctionPassWrapper::runOnFunction</a> and <a href="/web-llvm/docs/api/classes/anonymous-irprintingpasses-cpp-/printmodulepasswrapper/#ab818e9e7d9bdacda0e8b043082b7b879">anonymous{IRPrintingPasses.cpp}::PrintModulePassWrapper::runOnModule</a>.</p>

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



<p>Declaration at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>, definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodereader/#a9154b11bdab240adc9c8acd18cf89717">anonymous{BitcodeReader.cpp}::BitcodeReader::materialize</a>, <a href="/web-llvm/docs/api/classes/llvm/bitcodewriterpass/#a2cf5fec0ba55756093b6c7e6c8f31c00">llvm::BitcodeWriterPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltobitcodewriterpass/#a407be825a5084267d383681109e30df9">llvm::ThinLTOBitcodeWriterPass::run</a> and <a href="/web-llvm/docs/api/classes/anonymous-bitcodewriterpass-cpp-/writebitcodepass/#a096138823f749d9386ca19b58996fb81">anonymous{BitcodeWriterPass.cpp}::WriteBitcodePass::runOnModule</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ATTRIBUTE\_ENUM {#ac52fd56f4583e0aed1c9b900c3ac98c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ATTRIBUTE_ENUM(ENUM_NAME, DISPLAY_NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  case lltok::kw_##DISPLAY_NAME: \
    return Attribute::ENUM_NAME;
</div>
</dd>
</dl>

<p>Definition at line 1539 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### DECLARE\_FIELD {#a9d48732979f09429678feca6ef8ae3c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DECLARE_FIELD(NAME, TYPE, INIT)&nbsp;&nbsp;&nbsp;TYPE NAME <a href="/web-llvm/docs/api/files/lib/lib/support/regexec-c/#af319751162595d897c085e511c7e7d4a">INIT</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5212 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### GET\_ATTR\_NAMES {#aba63655d8ee18e876fc5cee12bbaa35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_ATTR_NAMES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1538 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### GET\_OR\_DISTINCT {#adb35227be2ff51424e5ee991a94106e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define GET_OR_DISTINCT(CLASS, ARGS)&nbsp;&nbsp;&nbsp;  (IsDistinct ? CLASS::getDistinct ARGS : CLASS::get ARGS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5234 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### HANDLE\_SPECIALIZED\_MDNODE\_LEAF {#a4395a6e9b387da7779af9d12538b0fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HANDLE_SPECIALIZED_MDNODE_LEAF(CLASS)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Lex.getStrVal() == #CLASS)                                               \
    return <a href="/web-llvm/docs/api/structs/parse">parse</a>##CLASS(<a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, IsDistinct);
</div>
</dd>
</dl>

<p>Definition at line 5204 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### NOP\_FIELD {#a682f88278e493b169aeb5d1f648eb75e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NOP_FIELD(NAME, TYPE, INIT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 5213 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### PARSE\_MD\_FIELD {#aa5637a0c40a619399423f4f2ed5c8d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PARSE_MD_FIELD(NAME, TYPE, DEFAULT)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (Lex.getStrVal() == #NAME)                                                \
    return parseMDField(#NAME, NAME);
</div>
</dd>
</dl>

<p>Definition at line 5217 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### PARSE\_MD\_FIELDS {#ab3429bc3e3beab695470f2072512ec49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PARSE_MD_FIELDS()&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#ae0c67ee631491c7a41f94ab57f955509">VISIT_MD_FIELDS</a>(<a href="#a9d48732979f09429678feca6ef8ae3c4">DECLARE_FIELD</a>, <a href="#a9d48732979f09429678feca6ef8ae3c4">DECLARE_FIELD</a>)                                \
  do {                                                                         \
    LocTy ClosingLoc;                                                          \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (parseMDFieldsImpl(                                                     \
            [&amp;]() -&gt; bool {                                                    \
              <a href="#ae0c67ee631491c7a41f94ab57f955509">VISIT_MD_FIELDS</a>(<a href="#aa5637a0c40a619399423f4f2ed5c8d35">PARSE_MD_FIELD</a>, <a href="#aa5637a0c40a619399423f4f2ed5c8d35">PARSE_MD_FIELD</a>)                  \
              return tokError(<a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a>("invalid field '") + Lex.getStrVal() +     \
                              "'");                                            \
            },                                                                 \
            ClosingLoc))                                                       \
      return <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>;                                                             \
    <a href="#ae0c67ee631491c7a41f94ab57f955509">VISIT_MD_FIELDS</a>(<a href="#a682f88278e493b169aeb5d1f648eb75e">NOP_FIELD</a>, <a href="#a76921ba6785305eb680bb2797802c8ca">REQUIRE_FIELD</a>)                                  \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (false)
</div>
</dd>
</dl>

<p>Definition at line 5220 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### REQUIRE\_FIELD {#a76921ba6785305eb680bb2797802c8ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REQUIRE_FIELD(NAME, TYPE, INIT)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (!NAME.Seen)                                                              \
    return <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordmapping-cpp/#a9cdf893c7d17e47fa1ed8bebf92a5da4">error</a>(ClosingLoc, "missing required field '" #NAME "'");
</div>
</dd>
</dl>

<p>Definition at line 5214 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#ae0c67ee631491c7a41f94ab57f955509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(column, ColumnField, );                                             \
  REQUIRED(scope, MDField, (/* AllowNull */ false));                           \
  OPTIONAL(inlinedAt, MDField, );                                              \
  OPTIONAL(isImplicitCode, MDBoolField, (false));
</div>
</dd>
</dl>

<p>Definition at line 5241 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a5e48de7b196cc1dcbbb54c54b1f61450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(tag, DwarfTagField, );                                              \
  OPTIONAL(header, MDStringField, );                                           \
  OPTIONAL(operands, MDFieldList, );
</div>
</dd>
</dl>

<p>Definition at line 5277 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a00a7312720d68088c3cbd9b879861925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(count, MDSignedOrMDField, (-1, -1, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#ad0d744f05898e32d01f73f8af3cd2071">INT64_MAX</a>, false));              \
  OPTIONAL(lowerBound, MDSignedOrMDField, );                                   \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ac209b9fe79c81cd5274229885cb8fb09">upperBound</a>, MDSignedOrMDField, );                                   \
  OPTIONAL(stride, MDSignedOrMDField, );
</div>
</dd>
</dl>

<p>Definition at line 5294 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#ac8524ffb09e8bf9cc34614c28bb262a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(count, MDSignedOrMDField, );                                        \
  OPTIONAL(lowerBound, MDSignedOrMDField, );                                   \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#ac209b9fe79c81cd5274229885cb8fb09">upperBound</a>, MDSignedOrMDField, );                                   \
  OPTIONAL(stride, MDSignedOrMDField, );
</div>
</dd>
</dl>

<p>Definition at line 5331 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a0e60835010cb18475f7f961190bd18fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  REQUIRED(value, MDAPSIntField, );                                            \
  OPTIONAL(isUnsigned, MDBoolField, (false));
</div>
</dd>
</dl>

<p>Definition at line 5363 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a164102333d655020debf804a3c23c5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(tag, DwarfTagField, (dwarf::DW_TAG_base_type));                     \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, MDUnsignedField, (0, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>));                            \
  OPTIONAL(align, MDUnsignedField, (0, UINT32_MAX));                           \
  OPTIONAL(encoding, DwarfAttEncodingField, );                                 \
  OPTIONAL(num_extra_inhabitants, MDUnsignedField, (0, UINT32_MAX));           \
  OPTIONAL(flags, DIFlagField, );
</div>
</dd>
</dl>

<p>Definition at line 5389 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a209d2e63cc65f7494214d24e4550a055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(tag, DwarfTagField, (dwarf::DW_TAG_string_type));                   \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(stringLength, MDField, );                                           \
  OPTIONAL(stringLengthExpression, MDField, );                                 \
  OPTIONAL(stringLocationExpression, MDField, );                               \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, MDUnsignedField, (0, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>));                            \
  OPTIONAL(align, MDUnsignedField, (0, UINT32_MAX));                           \
  OPTIONAL(encoding, DwarfAttEncodingField, );
</div>
</dd>
</dl>

<p>Definition at line 5409 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#af9f9ad3c8acb9fb6c986b3c05c732fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(tag, DwarfTagField, );                                              \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(scope, MDField, );                                                  \
  REQUIRED(baseType, MDField, );                                               \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, MDUnsignedField, (0, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>));                            \
  OPTIONAL(align, MDUnsignedField, (0, UINT32_MAX));                           \
  OPTIONAL(offset, MDUnsignedField, (0, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>));                          \
  OPTIONAL(flags, DIFlagField, );                                              \
  OPTIONAL(extraData, MDField, );                                              \
  OPTIONAL(dwarfAddressSpace, MDUnsignedField, (UINT32_MAX, UINT32_MAX));      \
  OPTIONAL(annotations, MDField, );                                            \
  OPTIONAL(ptrAuthKey, MDUnsignedField, (0, 7));                               \
  OPTIONAL(ptrAuthIsAddressDiscriminated, MDBoolField, );                      \
  OPTIONAL(ptrAuthExtraDiscriminator, MDUnsignedField, (0, 0xffff));           \
  OPTIONAL(ptrAuthIsaPointer, MDBoolField, );                                  \
  OPTIONAL(ptrAuthAuthenticatesNullValues, MDBoolField, );
</div>
</dd>
</dl>

<p>Definition at line 5438 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a4c2fd7ba3efe602325a0ac4c61ee05ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(tag, DwarfTagField, );                                              \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(scope, MDField, );                                                  \
  OPTIONAL(baseType, MDField, );                                               \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#ac934769d93af95250952646a3829df4c">size</a>, MDUnsignedField, (0, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>));                            \
  OPTIONAL(align, MDUnsignedField, (0, UINT32_MAX));                           \
  OPTIONAL(offset, MDUnsignedField, (0, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>));                          \
  OPTIONAL(flags, DIFlagField, );                                              \
  OPTIONAL(elements, MDField, );                                               \
  OPTIONAL(runtimeLang, DwarfLangField, );                                     \
  OPTIONAL(vtableHolder, MDField, );                                           \
  OPTIONAL(templateParams, MDField, );                                         \
  OPTIONAL(identifier, MDStringField, );                                       \
  OPTIONAL(discriminator, MDField, );                                          \
  OPTIONAL(dataLocation, MDField, );                                           \
  OPTIONAL(associated, MDField, );                                             \
  OPTIONAL(allocated, MDField, );                                              \
  OPTIONAL(rank, MDSignedOrMDField, );                                         \
  OPTIONAL(annotations, MDField, );                                            \
  OPTIONAL(num_extra_inhabitants, MDUnsignedField, (0, UINT32_MAX));           \
  OPTIONAL(specification, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 5479 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a3d1be14c051024218ef6c27ee1047cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(flags, DIFlagField, );                                              \
  OPTIONAL(cc, DwarfCCField, );                                                \
  REQUIRED(types, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 5539 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a06338927887fe7934f0716f48af5f961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(filename, MDStringField, );                                         \
  REQUIRED(directory, MDStringField, );                                        \
  OPTIONAL(checksumkind, ChecksumKindField, (DIFile::CSK_MD5));                \
  OPTIONAL(checksum, MDStringField, );                                         \
  OPTIONAL(source, MDStringField, );
</div>
</dd>
</dl>

<p>Definition at line 5560 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#ad24e4d3c77456c254e27a47e34b93f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(language, DwarfLangField, );                                        \
  REQUIRED(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, (/* AllowNull */ false));                            \
  OPTIONAL(producer, MDStringField, );                                         \
  OPTIONAL(isOptimized, MDBoolField, );                                        \
  OPTIONAL(flags, MDStringField, );                                            \
  OPTIONAL(runtimeVersion, MDUnsignedField, (0, UINT32_MAX));                  \
  OPTIONAL(splitDebugFilename, MDStringField, );                               \
  OPTIONAL(emissionKind, EmissionKindField, );                                 \
  OPTIONAL(enums, MDField, );                                                  \
  OPTIONAL(retainedTypes, MDField, );                                          \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxcontainerglobals-cpp/#ace9918659ef4a022d158646784619514">globals</a>, MDField, );                                                \
  OPTIONAL(imports, MDField, );                                                \
  OPTIONAL(macros, MDField, );                                                 \
  OPTIONAL(dwoId, MDUnsignedField, );                                          \
  OPTIONAL(splitDebugInlining, MDBoolField, = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>);                           \
  OPTIONAL(debugInfoForProfiling, MDBoolField, = false);                       \
  OPTIONAL(nameTableKind, NameTableKindField, );                               \
  OPTIONAL(rangesBaseAddress, MDBoolField, = false);                           \
  OPTIONAL(sysroot, MDStringField, );                                          \
  OPTIONAL(sdk, MDStringField, );
</div>
</dd>
</dl>

<p>Definition at line 5594 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a1d6f78c09138c43b6102f993a002e409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(scope, MDField, );                                                  \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(linkageName, MDStringField, );                                      \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(type, MDField, );                                                   \
  OPTIONAL(isLocal, MDBoolField, );                                            \
  OPTIONAL(isDefinition, MDBoolField, (<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>));                                 \
  OPTIONAL(scopeLine, LineField, );                                            \
  OPTIONAL(containingType, MDField, );                                         \
  OPTIONAL(virtuality, DwarfVirtualityField, );                                \
  OPTIONAL(virtualIndex, MDUnsignedField, (0, UINT32_MAX));                    \
  OPTIONAL(thisAdjustment, MDSignedField, (0, INT32_MIN, INT32_MAX));          \
  OPTIONAL(flags, DIFlagField, );                                              \
  OPTIONAL(spFlags, DISPFlagField, );                                          \
  OPTIONAL(isOptimized, MDBoolField, );                                        \
  OPTIONAL(unit, MDField, );                                                   \
  OPTIONAL(templateParams, MDField, );                                         \
  OPTIONAL(declaration, MDField, );                                            \
  OPTIONAL(retainedNodes, MDField, );                                          \
  OPTIONAL(thrownTypes, MDField, );                                            \
  OPTIONAL(annotations, MDField, );                                            \
  OPTIONAL(targetFuncName, MDStringField, );
</div>
</dd>
</dl>

<p>Definition at line 5638 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a2b78526e79309c112c1242525f25be22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(scope, MDField, (/* AllowNull */ false));                           \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(column, ColumnField, );
</div>
</dd>
</dl>

<p>Definition at line 5688 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a4996da66cf2df124315bb0992278da1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(scope, MDField, (/* AllowNull */ false));                           \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  REQUIRED(discriminator, MDUnsignedField, (0, UINT32_MAX));
</div>
</dd>
</dl>

<p>Definition at line 5704 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a08549ca1c540841bea354fa8e28b46c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(scope, MDField, );                                                  \
  OPTIONAL(declaration, MDField, );                                            \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );
</div>
</dd>
</dl>

<p>Definition at line 5719 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a5871abd427e7a5549de32b74c33a7138}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(scope, MDField, );                                                  \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(exportSymbols, MDBoolField, );
</div>
</dd>
</dl>

<p>Definition at line 5737 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#aecad3299be2ea49b7b428a0670edc9e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(type, DwarfMacinfoTypeField, );                                     \
  OPTIONAL(line, LineField, );                                                 \
  REQUIRED(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(value, MDStringField, );
</div>
</dd>
</dl>

<p>Definition at line 5753 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#ab06c20e3fcdd09ef9109aff28783ad50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(type, DwarfMacinfoTypeField, (dwarf::DW_MACINFO_start_file));       \
  OPTIONAL(line, LineField, );                                                 \
  REQUIRED(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#aaa253dd3e56c37edd403113782c0ef94">nodes</a>, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 5769 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a2746631c317ae72b1504401ae2572d39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(scope, MDField, );                                                  \
  REQUIRED(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(configMacros, MDStringField, );                                     \
  OPTIONAL(includePath, MDStringField, );                                      \
  OPTIONAL(apinotes, MDStringField, );                                         \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(isDecl, MDBoolField, );
</div>
</dd>
</dl>

<p>Definition at line 5787 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a8bbc0dd7ceff37945678a3584f721c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  REQUIRED(type, MDField, );                                                   \
  OPTIONAL(defaulted, MDBoolField, );
</div>
</dd>
</dl>

<p>Definition at line 5808 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#aa9853d4b99a76ea98d3198a338244c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(tag, DwarfTagField, (dwarf::DW_TAG_template_value_parameter));      \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(type, MDField, );                                                   \
  OPTIONAL(defaulted, MDBoolField, );                                          \
  REQUIRED(value, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 5825 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a2f353c3b5950f0f7a3e657e43523da6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, (/* AllowEmpty */ false));                     \
  OPTIONAL(scope, MDField, );                                                  \
  OPTIONAL(linkageName, MDStringField, );                                      \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(type, MDField, );                                                   \
  OPTIONAL(isLocal, MDBoolField, );                                            \
  OPTIONAL(isDefinition, MDBoolField, (<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>));                                 \
  OPTIONAL(templateParams, MDField, );                                         \
  OPTIONAL(declaration, MDField, );                                            \
  OPTIONAL(align, MDUnsignedField, (0, UINT32_MAX));                           \
  OPTIONAL(annotations, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 5847 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a31ec2ebff96b13793a3184639a172c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(scope, MDField, (/* AllowNull */ false));                           \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(arg, MDUnsignedField, (0, UINT16_MAX));                             \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(type, MDField, );                                                   \
  OPTIONAL(flags, DIFlagField, );                                              \
  OPTIONAL(align, MDUnsignedField, (0, UINT32_MAX));                           \
  OPTIONAL(annotations, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 5880 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a43242f43522e0cc509179169afa63950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(scope, MDField, (/* AllowNull */ false));                           \
  REQUIRED(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  REQUIRED(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  REQUIRED(line, LineField, );
</div>
</dd>
</dl>

<p>Definition at line 5903 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#ad863d0970571721ea2c1b9df53758a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(var, MDField, );                                                    \
  REQUIRED(expr, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 6001 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a960369d543e112a40347a9d54a09713e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(setter, MDStringField, );                                           \
  OPTIONAL(getter, MDStringField, );                                           \
  OPTIONAL(attributes, MDUnsignedField, (0, UINT32_MAX));                      \
  OPTIONAL(type, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 6016 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

### VISIT\_MD\_FIELDS {#a757efeaaf919132f1e7c08f7331c88b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define VISIT_MD_FIELDS(OPTIONAL, REQUIRED)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  REQUIRED(tag, DwarfTagField, );                                              \
  REQUIRED(scope, MDField, );                                                  \
  OPTIONAL(entity, MDField, );                                                 \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#a79dce2d3eafaf25bf0df59f56caf9712">file</a>, MDField, );                                                   \
  OPTIONAL(line, LineField, );                                                 \
  OPTIONAL(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a8f8f80d37794cde9472343e4487ba3eb">name</a>, MDStringField, );                                             \
  OPTIONAL(elements, MDField, );
</div>
</dd>
</dl>

<p>Definition at line 6037 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/llparser-cpp">LLParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
