---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/symbolref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SymbolRef` Class

<p>This is a value type class that represents a single symbol in the list of symbols in the object file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::object::SymbolRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">llvm/Object/ObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref">BasicSymbolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a value type class that represents a single symbol in the list of symbols in the object file. <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref">ELFSymbolRef</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/goffsymbolref">GOFFSymbolRef</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref">XCOFFSymbolRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Type { <a href="#a2ea2ecb4f81936cc379aff129e440b04">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfb6c528a7cc26455f507d98b9e6f53">SymbolRef</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad38b7b052df6e4d4d0efc9b3372b9ea6">SymbolRef</a> (DataRefImpl SymbolP, const ObjectFile *Owner)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3916a0c57c63d466f8f9aee459b5ab8d">SymbolRef</a> (const BasicSymbolRef &amp;B)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6935271c0f6df1209adbb91f2f68d2c1">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac22d03239bd28b53a229486b43a9d3b8">getAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the symbol virtual address (i.e. <a href="#ac22d03239bd28b53a229486b43a9d3b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefbba218ff811c972e66adacb950989c">getValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the value of the symbol depending on the object this can be an offset or a virtual address. <a href="#aefbba218ff811c972e66adacb950989c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a964202e1e17cee946ac67303dd34a9a2">getAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the alignment of this symbol as the actual value (not log 2). <a href="#a964202e1e17cee946ac67303dd34a9a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc6576af9f6c428aaeb91be518ef565d">getCommonSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="#a2ea2ecb4f81936cc379aff129e440b04">SymbolRef::Type</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a234b2c90b26a44886a6f04c4281b1b65">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/object/#a18a35d6d108ec102a6bff8ac2bfd4c62">section_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b31890b3cf3677a9c279325661e3af">getSection</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get section this symbol is defined in reference to. <a href="#af8b31890b3cf3677a9c279325661e3af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a> () const</td>
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

## Description {#details}

<p>This is a value type class that represents a single symbol in the list of symbols in the object file.</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Type {#a2ea2ecb4f81936cc379aff129e440b04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::object::SymbolRef::Type </td>
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
<td class="doxyEnumItemName">ST_Unknown<a id="a2ea2ecb4f81936cc379aff129e440b04a2d334a713a4916963744a0cc31ab9552"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_Other<a id="a2ea2ecb4f81936cc379aff129e440b04a076f193658db35c0f4d60f9e0a3e329f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_Data<a id="a2ea2ecb4f81936cc379aff129e440b04a8a501fedaaa3e562541580b8f1db3975"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_Debug<a id="a2ea2ecb4f81936cc379aff129e440b04afe6722fa933ffee4c116ee60c2de5049"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_File<a id="a2ea2ecb4f81936cc379aff129e440b04a771f3523463fc179b4e89f60841a23b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ST_Function<a id="a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### SectionRef {#a84e7ca90f9c05219e1c82f602bad10fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/sectionref">SectionRef</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a>.</p>


<p>Referenced by <a href="#a84e7ca90f9c05219e1c82f602bad10fc">SectionRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SymbolRef() {#a4cfb6c528a7cc26455f507d98b9e6f53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::SymbolRef::SymbolRef ()</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a4d1e9186871dbe19b521894ce4c5a2ef">llvm::object::ELFSymbolRef::ELFSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffsymbolref/#a0c5486f544a4c441f30b5aba906b5ee9">llvm::object::GOFFSymbolRef::GOFFSymbolRef</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a494d7b1f056d074badea3ac8890ca73c">llvm::object::XCOFFSymbolRef::XCOFFSymbolRef</a>.</p>

</div>
</div>

### SymbolRef() {#ad38b7b052df6e4d4d0efc9b3372b9ea6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::SymbolRef::SymbolRef (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> SymbolP, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">ObjectFile</a> * Owner)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#ab8d4ee7c02c28928d25ad12952e8e194">llvm::object::BasicSymbolRef::BasicSymbolRef</a>.</p>

</div>
</div>

### SymbolRef() {#a3916a0c57c63d466f8f9aee459b5ab8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::SymbolRef::SymbolRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref">BasicSymbolRef</a> &amp; B)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#ab8d4ee7c02c28928d25ad12952e8e194">llvm::object::BasicSymbolRef::BasicSymbolRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a294f053bad4966edce6b5edb3697cb08">llvm::object::BasicSymbolRef::getObject</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddress() {#ac22d03239bd28b53a229486b43a9d3b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::object::SymbolRef::getAddress ()</td>
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

<p>Returns the symbol virtual address (i.e.</p>


<p>address at which it will be mapped).</p>


<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a51815869de4debd52444c1e3d3e79a31">llvm::object::ObjectFile::getSymbolAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a603eb2d37a31ea2c14318bedeecb8e3c">llvm::getOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aaca2a6196a0b153d686419f0fd252e91">getSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a0b01026129dcc250501775442ac4b2e5">llvm::object::XCOFFSymbolRef::isFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener/#acbf9525bdd6bfe26f04d293ee1d9a7ca">anonymous{OProfileJITEventListener.cpp}::OProfileJITEventListener::notifyObjectLoaded</a> and <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### getAlignment() {#a964202e1e17cee946ac67303dd34a9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::SymbolRef::getAlignment ()</td>
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

<p>Get the alignment of this symbol as the actual value (not log 2).</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a964fad6d745daec631670b795505f1b6">llvm::object::ObjectFile::getSymbolAlignment</a>.</p>

</div>
</div>

### getCommonSize() {#afc6576af9f6c428aaeb91be518ef565d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::SymbolRef::getCommonSize ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a0be1fdc703dfefdcd9298662351d5daf">llvm::object::ObjectFile::getCommonSymbolSize</a>, <a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a>.</p>

</div>
</div>

### getName() {#a6935271c0f6df1209adbb91f2f68d2c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::SymbolRef::getName ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#a381659cd808b1ca92fc7628a067d9346">llvm::object::ObjectFile::getSymbolName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener/#acbf9525bdd6bfe26f04d293ee1d9a7ca">anonymous{OProfileJITEventListener.cpp}::OProfileJITEventListener::notifyObjectLoaded</a> and <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### getObject() {#aa08bcfd0fd633889120aa52eb115f3fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ObjectFile * llvm::object::SymbolRef::getObject ()</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a294f053bad4966edce6b5edb3697cb08">llvm::object::BasicSymbolRef::getObject</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a4d1e9186871dbe19b521894ce4c5a2ef">llvm::object::ELFSymbolRef::ELFSymbolRef</a>, <a href="#ac22d03239bd28b53a229486b43a9d3b8">getAddress</a>, <a href="#a964202e1e17cee946ac67303dd34a9a2">getAlignment</a>, <a href="#afc6576af9f6c428aaeb91be518ef565d">getCommonSize</a>, <a href="#a6935271c0f6df1209adbb91f2f68d2c1">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#abb68cddc1b5010571d488b639eb9d561">llvm::object::XCOFFSymbolRef::getName</a>, <a href="#af8b31890b3cf3677a9c279325661e3af">getSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a38013df05132b768d4980f709b43b2ee">llvm::object::XCOFFSymbolRef::getSize</a>, <a href="#a234b2c90b26a44886a6f04c4281b1b65">getType</a>, <a href="#aefbba218ff811c972e66adacb950989c">getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#ab1e1cc599a5a829c5962a07153a9a8c1">llvm::object::XCOFFSymbolRef::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a046c53b9366f602644b022ee6e86c57e">llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/goffsymbolref/#a0c5486f544a4c441f30b5aba906b5ee9">llvm::object::GOFFSymbolRef::GOFFSymbolRef</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcoffsymbolref/#a0b01026129dcc250501775442ac4b2e5">llvm::object::XCOFFSymbolRef::isFunction</a>.</p>

</div>
</div>

### getSection() {#af8b31890b3cf3677a9c279325661e3af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; section_iterator &gt; llvm::object::SymbolRef::getSection ()</td>
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

<p>Get section this symbol is defined in reference to.</p>


<p>Result is section_end() if it is undefined or is an absolute symbol.</p>


<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#ab21d0cb75a969e21f3eb9271d80ffb36">llvm::object::ObjectFile::getSymbolSection</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/sectionref/#a9252daa21a3dd50c0c31a70c482a94a0">llvm::object::SectionRef::containsSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoffthumb/#ae71e8902775f8de0490455dc8c929d2f">llvm::RuntimeDyldCOFFThumb::getJITSymbolFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aaca2a6196a0b153d686419f0fd252e91">getSymbolInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a> and <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### getType() {#a234b2c90b26a44886a6f04c4281b1b65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; SymbolRef::Type &gt; llvm::object::SymbolRef::getType ()</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#af5dd4b48117d96394d09345a2b42f039">llvm::object::ObjectFile::getSymbolType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener/#acbf9525bdd6bfe26f04d293ee1d9a7ca">anonymous{OProfileJITEventListener.cpp}::OProfileJITEventListener::notifyObjectLoaded</a> and <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a>.</p>

</div>
</div>

### getValue() {#aefbba218ff811c972e66adacb950989c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; llvm::object::SymbolRef::getValue ()</td>
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

<p>Return the value of the symbol depending on the object this can be an offset or a virtual address.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a>.</p>


<p>References <a href="#aa08bcfd0fd633889120aa52eb115f3fb">getObject</a>, <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa520e1a721f81e1befb66b422c6e4a60">llvm::object::ObjectFile::getSymbolValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#acf228956812ef6e7722e8c114fe3b923">llvm::object::computeSymbolSizes</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimedyldcoff/#a2fe9aab3874eece3b45203f68bdc6079">llvm::RuntimeDyldCOFF::getSymbolOffset</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/objectfile-h">ObjectFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
