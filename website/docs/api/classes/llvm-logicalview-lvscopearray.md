---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/logicalview/lvscopearray
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `LVScopeArray` Class



## Declaration

<div class="doxyDeclaration">
class llvm::logicalview::LVScopeArray { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">llvm/DebugInfo/LogicalView/Core/LVScope.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137fc4085c531245e2efe3fb58352723">LVScopeArray</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a334610f13e4a9a3ab4a748d0054b931d">LVScopeArray</a> (const LVScopeArray &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d59d4d5b12b2c81732ae32cd919cbb">~LVScopeArray</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopearray">LVScopeArray</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a829a839d435cea2dd537b754dbca4bf0">operator=</a> (const LVScopeArray &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea12d2cfc5954a2e0e3770f62d6b127">resolveExtra</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e490191363061814da0ee5d7edab798">equals</a> (const LVScope *Scope) const override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cca21a0cfd06315bcdc113e9ba4549c">printExtra</a> (raw_ostream &amp;OS, bool Full=true) const override</td>
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


<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LVScopeArray() {#a137fc4085c531245e2efe3fb58352723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVScopeArray::LVScopeArray ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a017581220d2b08c14948ff369764eb47">llvm::logicalview::LVScope::LVScope</a>.</p>


<p>Referenced by <a href="#a334610f13e4a9a3ab4a748d0054b931d">LVScopeArray</a> and <a href="#a829a839d435cea2dd537b754dbca4bf0">operator=</a>.</p>

</div>
</div>

### LVScopeArray() {#a334610f13e4a9a3ab4a748d0054b931d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVScopeArray::LVScopeArray (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopearray">LVScopeArray</a> &amp;)</td>
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



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>.</p>


<p>Reference <a href="#a137fc4085c531245e2efe3fb58352723">LVScopeArray</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~LVScopeArray() {#af1d59d4d5b12b2c81732ae32cd919cbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::logicalview::LVScopeArray::~LVScopeArray ()</td>
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



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad5b7ced2aa529c892b2219cd29b08760abbd47109890259c0127154db1af26c75">llvm::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a017581220d2b08c14948ff369764eb47">llvm::logicalview::LVScope::LVScope</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#af6ec25fbed1ba22e74fe2173798fc6c1">llvm::logicalview::LVObject::Scope</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a829a839d435cea2dd537b754dbca4bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LVScopeArray &amp; llvm::logicalview::LVScopeArray::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscopearray">LVScopeArray</a> &amp;)</td>
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



<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>.</p>


<p>Reference <a href="#a137fc4085c531245e2efe3fb58352723">LVScopeArray</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### equals() {#a6e490191363061814da0ee5d7edab798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LVScopeArray::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope">LVScope</a> * Scope)</td>
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



<p>Declaration at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>, definition at line 1155 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvscope-cpp">LVScope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#ab51adccd7ba20af96c2faad7107e9211">llvm::logicalview::LVScope::equalNumberOfChildren</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a9d5c17c50351c271bca1d2236c4f2343">llvm::logicalview::LVScope::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvtype/#a3e59d42d760f1d17f9a8302662f3f058">llvm::logicalview::LVType::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a8800edbf399aa751c03f610600b6e424">llvm::logicalview::LVScope::getTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a017581220d2b08c14948ff369764eb47">llvm::logicalview::LVScope::LVScope</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvobject/#af6ec25fbed1ba22e74fe2173798fc6c1">llvm::logicalview::LVObject::Scope</a>.</p>

</div>
</div>

### printExtra() {#a7cca21a0cfd06315bcdc113e9ba4549c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVScopeArray::printExtra (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool Full=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>, definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvscope-cpp">LVScope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a50fdebf875bf1c764f2dcea6d0eadb35">llvm::logicalview::formattedKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/logicalview/#a975e05a429ba081a152682652ee640f9">llvm::logicalview::formattedName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad5b7ced2aa529c892b2219cd29b08760abbd47109890259c0127154db1af26c75">llvm::Full</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a84e414a8ce9720ec080b00475cf799f6">llvm::logicalview::LVElement::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a2c59d36ed0f6aff3267222514f3b1bc6">llvm::logicalview::LVScope::kind</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aca89a8628881d2bb14aac15c7ae94901">llvm::logicalview::LVElement::typeOffsetAsString</a>.</p>

</div>
</div>

### resolveExtra() {#a1ea12d2cfc5954a2e0e3770f62d6b127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVScopeArray::resolveExtra ()</td>
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



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a>, definition at line 1084 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvscope-cpp">LVScope.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#ac5a196b62ca4642de22709f6a03723d8">llvm::logicalview::LVElement::ElementType</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a9620f675da485c3d3afb01a155d32880">llvm::logicalview::LVElement::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#aad7b9283d6b4f1c100b0843e370911ba">llvm::logicalview::LVElement::getTypeName</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a8800edbf399aa751c03f610600b6e424">llvm::logicalview::LVScope::getTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a2766ba305c6868870f3c79a2d571e982">llvm::logicalview::LVElement::resolveFullname</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvelement/#a7acb49478601af95b4023b911a973ecf">llvm::logicalview::LVElement::setName</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvscope/#a99aa323baf3c2bf245b57a39c167af76">llvm::logicalview::LVScope::Types</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/logicalview/include/llvm/debuginfo/logicalview/core/lvscope-h">LVScope.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvscope-cpp">LVScope.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
