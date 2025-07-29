---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvtypedefinition
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LVTypeDefinition` Class



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVTypeDefinition { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">llvm/DebugInfo/LogicalView/Core/LVType.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac50c53bddb15088fb00620444987ec9a">LVTypeDefinition</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add6595d68d785ff687c6c002fd1685ed">LVTypeDefinition</a> (const LVTypeDefinition &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345f00f61c0e99b36f7d24d499a4af4e">~LVTypeDefinition</a> ()=default</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypedefinition">LVTypeDefinition</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b34fb6ce3b526c998f02ee0f5e46032">operator=</a> (const LVTypeDefinition &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af657fa1caf4a331f63937074ab8e436f">getUnderlyingType</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d521724718fdbf0ff4b25354a56417">setUnderlyingType</a> (LVElement *Element) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa721c51598f1f69a1d3ca55583e78b55">resolveExtra</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9688ef01603ac0bca479534fc0bc0717">equals</a> (const LVType *Type) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae086815c5a9521817532e3d7731a0187">printExtra</a> (raw_ostream &amp;OS, bool Full=true) const override</td>
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


<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LVTypeDefinition() {#ac50c53bddb15088fb00620444987ec9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVTypeDefinition::LVTypeDefinition ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#a9b1a64632e0bf7ffc9bfc40032f0c5fc">llvm::logicalview::LVType::LVType</a>.</p>


<p>Referenced by <a href="#add6595d68d785ff687c6c002fd1685ed">LVTypeDefinition</a> and <a href="#a9b34fb6ce3b526c998f02ee0f5e46032">operator=</a>.</p>

</div>
</div>

### LVTypeDefinition() {#add6595d68d785ff687c6c002fd1685ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVTypeDefinition::LVTypeDefinition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypedefinition">LVTypeDefinition</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>.</p>


<p>Reference <a href="#ac50c53bddb15088fb00620444987ec9a">LVTypeDefinition</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LVTypeDefinition() {#a345f00f61c0e99b36f7d24d499a4af4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVTypeDefinition::~LVTypeDefinition ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a9b34fb6ce3b526c998f02ee0f5e46032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVTypeDefinition &amp; llvm::logicalview::LVTypeDefinition::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtypedefinition">LVTypeDefinition</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>.</p>


<p>Reference <a href="#ac50c53bddb15088fb00620444987ec9a">LVTypeDefinition</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### equals() {#a9688ef01603ac0bca479534fc0bc0717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LVTypeDefinition::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype">LVType</a> * Type)</td>
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



<p>Declaration at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvtype-cpp">LVType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#a3e59d42d760f1d17f9a8302662f3f058">llvm::logicalview::LVType::equals</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#a9b1a64632e0bf7ffc9bfc40032f0c5fc">llvm::logicalview::LVType::LVType</a>.</p>

</div>
</div>

### getUnderlyingType() {#af657fa1caf4a331f63937074ab8e436f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVElement * LVTypeDefinition::getUnderlyingType ()</td>
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



<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>, definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvtype-cpp">LVType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#af30958ffe9503fca0c1350052f0690cb">llvm::logicalview::LVElement::getTypeAsScope</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a9039a48898b66a5d8b0e8ede3236d378">llvm::logicalview::LVElement::getTypeAsType</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#a9b1a64632e0bf7ffc9bfc40032f0c5fc">llvm::logicalview::LVType::LVType</a>.</p>


<p>Referenced by <a href="#aa721c51598f1f69a1d3ca55583e78b55">resolveExtra</a>.</p>

</div>
</div>

### printExtra() {#ae086815c5a9521817532e3d7731a0187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVTypeDefinition::printExtra (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool Full=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvtype-cpp">LVType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a50fdebf875bf1c764f2dcea6d0eadb35">llvm::logicalview::formattedKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a975e05a429ba081a152682652ee640f9">llvm::logicalview::formattedName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5b7ced2aa529c892b2219cd29b08760abbd47109890259c0127154db1af26c75">llvm::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a9620f675da485c3d3afb01a155d32880">llvm::logicalview::LVElement::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#aa7cbe68716ea91cac7c8711ba94adc7a">llvm::logicalview::LVType::kind</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aca89a8628881d2bb14aac15c7ae94901">llvm::logicalview::LVElement::typeOffsetAsString</a>.</p>

</div>
</div>

### resolveExtra() {#aa721c51598f1f69a1d3ca55583e78b55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVTypeDefinition::resolveExtra ()</td>
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



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>, definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvtype-cpp">LVType.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a9620f675da485c3d3afb01a155d32880">llvm::logicalview::LVElement::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#af30958ffe9503fca0c1350052f0690cb">llvm::logicalview::LVElement::getTypeAsScope</a>, <a href="#af657fa1caf4a331f63937074ab8e436f">getUnderlyingType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#adc3278484dd140d018661381153aaf8d">llvm::logicalview::options</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a2766ba305c6868870f3c79a2d571e982">llvm::logicalview::LVElement::resolveFullname</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a7acb49478601af95b4023b911a973ecf">llvm::logicalview::LVElement::setName</a> and <a href="#a70d521724718fdbf0ff4b25354a56417">setUnderlyingType</a>.</p>

</div>
</div>

### setUnderlyingType() {#a70d521724718fdbf0ff4b25354a56417}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::logicalview::LVTypeDefinition::setUnderlyingType (<a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement">LVElement</a> * Element)</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#a0443a6aea3e495934ac8b6da347b18cc">llvm::logicalview::LVObject::Element</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aac48d6fa0f7c1727388feb115620d50e">llvm::logicalview::LVElement::setType</a>.</p>


<p>Referenced by <a href="#aa721c51598f1f69a1d3ca55583e78b55">resolveExtra</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvtype-h">LVType.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvtype-cpp">LVType.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
