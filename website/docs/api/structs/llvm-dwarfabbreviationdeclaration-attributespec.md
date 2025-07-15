---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dwarfabbreviationdeclaration/attributespec
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AttributeSpec` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::DWARFAbbreviationDeclaration::AttributeSpec { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">llvm/DebugInfo/DWARF/DWARFAbbreviationDeclaration.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a425ba6e6cc155ad1a7df3893f865e33c">AttributeSpec</a> (dwarf::Attribute A, dwarf::Form F, int64_t Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48b6e664247405fecf3f095dbfb1c369">AttributeSpec</a> (dwarf::Attribute A, dwarf::Form F, std::optional&lt; uint8_t &gt; ByteSize)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3abfd85641f7025ead5cbc6ef45d59ad">getFormValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3a56ce95d62313369edc1e9c351032">isImplicitConst</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3441070f1a2550e5d8ff74aaa098c7c">getImplicitConstValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50a3d3171e9bba6ee3e3bcfc8db2af31">getByteSize</a> (const DWARFUnit &amp;U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the fixed byte size of this Form if possible. <a href="#a50a3d3171e9bba6ee3e3bcfc8db2af31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334610a585463d47be91041e10e9ba7a">Attr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a5d450fc1291db4a1981cfbd38fc0b">Form</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ByteSizeStorage</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe03f18443413e313f45a54366c4277d">ByteSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a112010382f814e3b8bef82bdbde3a98a">Value</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/dwarfabbreviationdeclaration/attributespec">llvm::DWARFAbbreviationDeclaration::AttributeSpec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba1f4fbd5f01560f93584b77d9e11bc3"></a></td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AttributeSpec() {#a425ba6e6cc155ad1a7df3893f865e33c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFAbbreviationDeclaration::AttributeSpec::AttributeSpec (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> A, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, int64_t Value)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a334610a585463d47be91041e10e9ba7a">Attr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ae1a5d450fc1291db4a1981cfbd38fc0b">Form</a>, <a href="#a9e3a56ce95d62313369edc1e9c351032">isImplicitConst</a> and <a href="#a112010382f814e3b8bef82bdbde3a98a">Value</a>.</p>

</div>
</div>

### AttributeSpec() {#a48b6e664247405fecf3f095dbfb1c369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFAbbreviationDeclaration::AttributeSpec::AttributeSpec (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> A, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a6c06a10ffac779879f6b62a1a904517b">dwarf::Form</a> F, std::optional&lt; uint8_t &gt; ByteSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a334610a585463d47be91041e10e9ba7a">Attr</a>, <a href="#afe03f18443413e313f45a54366c4277d">ByteSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#ae1a5d450fc1291db4a1981cfbd38fc0b">Form</a> and <a href="#a9e3a56ce95d62313369edc1e9c351032">isImplicitConst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getByteSize() {#a50a3d3171e9bba6ee3e3bcfc8db2af31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; int64_t &gt; DWARFAbbreviationDeclaration::AttributeSpec::getByteSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &amp; U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the fixed byte size of this Form if possible.</p>


<p>This function might use the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> to calculate the size of the Form, like for DW_AT_address and DW_AT_ref_addr, so this isn't just an accessor for the ByteSize member.</p>


<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>, definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a>.</p>


<p>References <a href="#afe03f18443413e313f45a54366c4277d">ByteSize</a>, <a href="#ae1a5d450fc1291db4a1981cfbd38fc0b">Form</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa03b0ad8792b784269332332eb61d8ad">llvm::dwarf::getFixedFormByteSize</a> and <a href="#a9e3a56ce95d62313369edc1e9c351032">isImplicitConst</a>.</p>

</div>
</div>

### getFormValue() {#a3abfd85641f7025ead5cbc6ef45d59ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFFormValue llvm::DWARFAbbreviationDeclaration::AttributeSpec::getFormValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#ac346eaa0ba929794c7261e78a757f7ad">llvm::DWARFFormValue::createFromSValue</a>, <a href="#ae1a5d450fc1291db4a1981cfbd38fc0b">Form</a> and <a href="#ae3441070f1a2550e5d8ff74aaa098c7c">getImplicitConstValue</a>.</p>

</div>
</div>

### getImplicitConstValue() {#ae3441070f1a2550e5d8ff74aaa098c7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::DWARFAbbreviationDeclaration::AttributeSpec::getImplicitConstValue ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9e3a56ce95d62313369edc1e9c351032">isImplicitConst</a> and <a href="#a112010382f814e3b8bef82bdbde3a98a">Value</a>.</p>


<p>Referenced by <a href="#a3abfd85641f7025ead5cbc6ef45d59ad">getFormValue</a>.</p>

</div>
</div>

### isImplicitConst() {#a9e3a56ce95d62313369edc1e9c351032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFAbbreviationDeclaration::AttributeSpec::isImplicitConst ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Reference <a href="#ae1a5d450fc1291db4a1981cfbd38fc0b">Form</a>.</p>


<p>Referenced by <a href="#a425ba6e6cc155ad1a7df3893f865e33c">AttributeSpec</a>, <a href="#a48b6e664247405fecf3f095dbfb1c369">AttributeSpec</a>, <a href="#a50a3d3171e9bba6ee3e3bcfc8db2af31">getByteSize</a> and <a href="#ae3441070f1a2550e5d8ff74aaa098c7c">getImplicitConstValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Attr {#a334610a585463d47be91041e10e9ba7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Attribute llvm::DWARFAbbreviationDeclaration::AttributeSpec::Attr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Referenced by <a href="#a425ba6e6cc155ad1a7df3893f865e33c">AttributeSpec</a>, <a href="#a48b6e664247405fecf3f095dbfb1c369">AttributeSpec</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#aba2b0348c09eb9e1b9245a012aab2503">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneAddressAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a00f85301e155c37fcab125f50a67cfb4">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneBlockAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a62035c942faa72252459166166847bff">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneDieRefAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a46b9ec0a91b5f1a1ea42559b16bcdc4d">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneScalarAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a77e10b3b8f2ee1990c6ea01fb817526c">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneStringAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a689c387664c7bbe7acdf44a5bb4d47ec">llvm::dwarf_linker::parallel::DIEAttributeCloner::shouldSkipAttribute</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6703ec589e30ef9b0142498c7043dc5b">llvm::shouldSkipAttribute</a>.</p>

</div>
</div>

### ByteSize {#afe03f18443413e313f45a54366c4277d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ByteSizeStorage llvm::DWARFAbbreviationDeclaration::AttributeSpec::ByteSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Referenced by <a href="#a48b6e664247405fecf3f095dbfb1c369">AttributeSpec</a> and <a href="#a50a3d3171e9bba6ee3e3bcfc8db2af31">getByteSize</a>.</p>

</div>
</div>

### Form {#ae1a5d450fc1291db4a1981cfbd38fc0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Form llvm::DWARFAbbreviationDeclaration::AttributeSpec::Form</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Referenced by <a href="#a425ba6e6cc155ad1a7df3893f865e33c">AttributeSpec</a>, <a href="#a48b6e664247405fecf3f095dbfb1c369">AttributeSpec</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#aba2b0348c09eb9e1b9245a012aab2503">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneAddressAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a00f85301e155c37fcab125f50a67cfb4">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneBlockAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a46b9ec0a91b5f1a1ea42559b16bcdc4d">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneScalarAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dieattributecloner/#a77e10b3b8f2ee1990c6ea01fb817526c">llvm::dwarf_linker::parallel::DIEAttributeCloner::cloneStringAttr</a>, <a href="#a50a3d3171e9bba6ee3e3bcfc8db2af31">getByteSize</a>, <a href="#a3abfd85641f7025ead5cbc6ef45d59ad">getFormValue</a> and <a href="#a9e3a56ce95d62313369edc1e9c351032">isImplicitConst</a>.</p>

</div>
</div>

### Value {#a112010382f814e3b8bef82bdbde3a98a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::DWARFAbbreviationDeclaration::AttributeSpec::Value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>


<p>Referenced by <a href="#a425ba6e6cc155ad1a7df3893f865e33c">AttributeSpec</a> and <a href="#ae3441070f1a2550e5d8ff74aaa098c7c">getImplicitConstValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

###  {#aba1f4fbd5f01560f93584b77d9e11bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::DWARFAbbreviationDeclaration::AttributeSpec llvm::DWARFAbbreviationDeclaration::AttributeSpec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfabbreviationdeclaration-h">DWARFAbbreviationDeclaration.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfabbreviationdeclaration-cpp">DWARFAbbreviationDeclaration.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
