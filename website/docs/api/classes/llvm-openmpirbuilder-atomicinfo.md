---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/openmpirbuilder/atomicinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AtomicInfo` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::OpenMPIRBuilder::AtomicInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">llvm/Frontend/OpenMP/OMPIRBuilder.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/atomicinfo">AtomicInfo</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55fdeba4e85100153b1078a53fe438c6">AtomicInfo</a> (IRBuilder&lt;&gt; *Builder, llvm::Type *Ty, uint64_t AtomicSizeInBits, uint64_t ValueSizeInBits, llvm::Align AtomicAlign, llvm::Align ValueAlign, bool UseLibcall, llvm::Value *AtomicVar)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec5e30f7d0149b065d7239ace7cf111">getAtomicPointer</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a037fae79e70e5c623d3b9fe3900f59">decorateWithTBAA</a> (llvm::Instruction *I) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/allocainst">llvm::AllocaInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27eedf5da8f111fe29254e21d94ffaa1">CreateAlloca</a> (llvm::Type *Ty, const llvm::Twine &amp;Name) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420900aa1c1dc4ab076d616c9750f00b">AtomicVar</a></td>
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


<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AtomicInfo() {#a55fdeba4e85100153b1078a53fe438c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::OpenMPIRBuilder::AtomicInfo::AtomicInfo (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; * Builder, <a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> * Ty, uint64_t AtomicSizeInBits, uint64_t ValueSizeInBits, <a href="/web-llvm/docs/api/structs/llvm/align">llvm::Align</a> AtomicAlign, <a href="/web-llvm/docs/api/structs/llvm/align">llvm::Align</a> ValueAlign, bool UseLibcall, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * AtomicVar)</td>
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



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a00ccd578d316a8e3cfb74c9d9512fb18">llvm::AtomicInfo::AtomicAlign</a>, <a href="#a55fdeba4e85100153b1078a53fe438c6">AtomicInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#aa93515e53e90f7b9686dd6a38e28863c">llvm::AtomicInfo::AtomicSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a2c27291b548e72b9bf4343a22ed4083f">llvm::AtomicInfo::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#af4f20dbabd4a3ee01be6dfb21b0a4848">llvm::AtomicInfo::Ty</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a19b0169936737092e5098af651e062b6">llvm::AtomicInfo::UseLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#ac2ff9d9e30bcb377a2ade9341657ab22">llvm::AtomicInfo::ValueAlign</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#aaec286e960801b56b3f89ed3dce070ff">llvm::AtomicInfo::ValueSizeInBits</a>.</p>


<p>Referenced by <a href="#a55fdeba4e85100153b1078a53fe438c6">AtomicInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### CreateAlloca() {#a27eedf5da8f111fe29254e21d94ffaa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AllocaInst * llvm::OpenMPIRBuilder::AtomicInfo::CreateAlloca (<a href="/web-llvm/docs/api/classes/llvm/type">llvm::Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">llvm::Twine</a> &amp; Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a2c27291b548e72b9bf4343a22ed4083f">llvm::AtomicInfo::Builder</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a35ee267850af7c235474a8c46c7ac5af">llvm::Value::setName</a> and <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#af4f20dbabd4a3ee01be6dfb21b0a4848">llvm::AtomicInfo::Ty</a>.</p>

</div>
</div>

### decorateWithTBAA() {#a5a037fae79e70e5c623d3b9fe3900f59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::OpenMPIRBuilder::AtomicInfo::decorateWithTBAA (<a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getAtomicPointer() {#afec5e30f7d0149b065d7239ace7cf111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Value * llvm::OpenMPIRBuilder::AtomicInfo::getAtomicPointer ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AtomicVar {#a420900aa1c1dc4ab076d616c9750f00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Value* llvm::OpenMPIRBuilder::AtomicInfo::AtomicVar</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/frontend/include/llvm/frontend/openmp/ompirbuilder-h">OMPIRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
