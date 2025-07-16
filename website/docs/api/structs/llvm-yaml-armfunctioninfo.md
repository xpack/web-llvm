---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/armfunctioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ARMFunctionInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::ARMFunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">Target/ARM/ARMMachineFunctionInfo.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">MachineFunctionInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Targets should override this in a way that mirrors the implementation of <a href="/web-llvm/docs/api/structs/llvm/machinefunctioninfo">llvm::MachineFunctionInfo</a>. <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad27e8e529832e56dce36f34427d6589">ARMFunctionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0010258760d1081a418bcfeee5237b8">ARMFunctionInfo</a> (const llvm::ARMFunctionInfo &amp;MFI)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af82b54b7cc0d4357f49b7f1cbe8d1d7c">~ARMFunctionInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bab13a91bab1cce4494ddb9b2e963ee">mappingImpl</a> (yaml::IO &amp;YamlIO) override</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954dc16c4b8842ce6651de64480a30ed">LRSpilled</a></td>
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


<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMFunctionInfo() {#aad27e8e529832e56dce36f34427d6589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::ARMFunctionInfo::ARMFunctionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>.</p>

</div>
</div>

### ARMFunctionInfo() {#af0010258760d1081a418bcfeee5237b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yaml::ARMFunctionInfo::ARMFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo">llvm::ARMFunctionInfo</a> &amp; MFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-cpp">ARMMachineFunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64machinefunctioninfo-cpp/#ad8d9de20a2440d472786e299fc96a97e">isLRSpilled</a> and <a href="#a954dc16c4b8842ce6651de64480a30ed">LRSpilled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ARMFunctionInfo() {#af82b54b7cc0d4357f49b7f1cbe8d1d7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::yaml::ARMFunctionInfo::~ARMFunctionInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### mappingImpl() {#a5bab13a91bab1cce4494ddb9b2e963ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void yaml::ARMFunctionInfo::mappingImpl (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">yaml::IO</a> &amp; YamlIO)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-cpp">ARMMachineFunctionInfo.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### LRSpilled {#a954dc16c4b8842ce6651de64480a30ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::ARMFunctionInfo::LRSpilled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a>.</p>


<p>Referenced by <a href="#af0010258760d1081a418bcfeee5237b8">ARMFunctionInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/armfunctioninfo/#ac5a0e7bb4255e14883daabfa25ae201d">llvm::ARMFunctionInfo::initializeBaseYamlFields</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-09c1e2242983c1cfa2dfc4d5564c025c/#ad2dd68e90612561db8cf4454708b9b0b">llvm::yaml::MappingTraits&lt; ARMFunctionInfo &gt;::mapping</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-cpp">ARMMachineFunctionInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armmachinefunctioninfo-h">ARMMachineFunctionInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
