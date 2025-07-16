---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/xcoffsymbolref
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XCOFFSymbolRef` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::XCOFFSymbolRef { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">llvm/Object/XCOFFObjectFile.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/symbolref">SymbolRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a value type class that represents a single symbol in the list of symbols in the object file. <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#ade25d600bbb69175395c080937b26432">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a494d7b1f056d074badea3ac8890ca73c">XCOFFSymbolRef</a> (DataRefImpl SymEntDataRef, const XCOFFObjectFile *OwningObjectPtr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsymbolentry32">XCOFFSymbolEntry32</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a505d506a424234d98ea617f60f69ddb3">getSymbol32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/xcoffsymbolentry64">XCOFFSymbolEntry64</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a421328a37b7de6fbb9712ec550d131a6">getSymbol64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e1cc599a5a829c5962a07153a9a8c1">getValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08b0ee12e4396d3b0b4f50863064f4a">getValue32</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb2d20e7ebc4ca9471bad9a00ed0b230">getValue64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38013df05132b768d4980f709b43b2ee">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ad87605387868c03e36dddba0aff91">getSectionNumber</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7033122210368081acb564a69e3ce350">getSymbolType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd59a3374d86b63062c7e36c5c8c4a15">getLanguageIdForCFile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbee638ba6d81acec9efec18822b973c">getCPUTypeIddForCFile</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70">XCOFF::StorageClass</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af60828c217c51c5f46cf6ecffb526a28">getStorageClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb64611059504e4f1ad84d559b736ec">getNumberOfAuxEntries</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uintptr_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12e28a6a9862376cd2e440636d6dfac">getEntryAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb68cddc1b5010571d488b639eb9d561">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b01026129dcc250501775442ac4b2e5">isFunction</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306cbb4386d868083a86447946e6ef6b">isCsectSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref">XCOFFCsectAuxRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046c53b9366f602644b022ee6e86c57e">getXCOFFCsectAuxRef</a> () const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile">XCOFFObjectFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8359acd9c23991360acf5b722696d20d">getObject</a> () const</td>
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


<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#ade25d600bbb69175395c080937b26432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
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
<td class="doxyEnumItemName">NAME_IN_STR_TBL_MAGIC<a id="ade25d600bbb69175395c080937b26432af61f2d9adb48d75296456e11766f3d5f"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### XCOFFSymbolRef() {#a494d7b1f056d074badea3ac8890ca73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::XCOFFSymbolRef::XCOFFSymbolRef (<a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl">DataRefImpl</a> SymEntDataRef, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile">XCOFFObjectFile</a> * OwningObjectPtr)</td>
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



<p>Definition at line 790 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a4cfb6c528a7cc26455f507d98b9e6f53">llvm::object::SymbolRef::SymbolRef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCPUTypeIddForCFile() {#abbee638ba6d81acec9efec18822b973c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::XCOFFSymbolRef::getCPUTypeIddForCFile ()</td>
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



<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ab3ab2990d9bd88d3ff52e29f0ad776bf">llvm::XCOFF::C_FILE</a>, <a href="#af60828c217c51c5f46cf6ecffb526a28">getStorageClass</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h/#a12d20b6a13c62bedb85b9bb44348b641">GETVALUE</a>.</p>

</div>
</div>

### getEntryAddress() {#af12e28a6a9862376cd2e440636d6dfac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uintptr_t llvm::object::XCOFFSymbolRef::getEntryAddress ()</td>
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



<p>Definition at line 851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#a046c53b9366f602644b022ee6e86c57e">getXCOFFCsectAuxRef</a>.</p>

</div>
</div>

### getLanguageIdForCFile() {#afd59a3374d86b63062c7e36c5c8c4a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::XCOFFSymbolRef::getLanguageIdForCFile ()</td>
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



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70ab3ab2990d9bd88d3ff52e29f0ad776bf">llvm::XCOFF::C_FILE</a>, <a href="#af60828c217c51c5f46cf6ecffb526a28">getStorageClass</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h/#a12d20b6a13c62bedb85b9bb44348b641">GETVALUE</a>.</p>

</div>
</div>

### getName() {#abb68cddc1b5010571d488b639eb9d561}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::XCOFFSymbolRef::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 855 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1356 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#abf04cdbb3bd4b5dc04636289e70ad71f">llvm::object::generateXCOFFFixedNameStringRef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aa08bcfd0fd633889120aa52eb115f3fb">llvm::object::SymbolRef::getObject</a>, <a href="#af60828c217c51c5f46cf6ecffb526a28">getStorageClass</a>, <a href="#a505d506a424234d98ea617f60f69ddb3">getSymbol32</a>, <a href="#a421328a37b7de6fbb9712ec550d131a6">getSymbol64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="#ade25d600bbb69175395c080937b26432af61f2d9adb48d75296456e11766f3d5f">NAME_IN_STR_TBL_MAGIC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a5663d03689c83dfe78cf82f2710c6115">llvm::object::XCOFFObjectFile::getSymbolName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a606ab46a34eecd59e09198799a982dc4">llvm::object::XCOFFObjectFile::getSymbolType</a> and <a href="#a046c53b9366f602644b022ee6e86c57e">getXCOFFCsectAuxRef</a>.</p>

</div>
</div>

### getNumberOfAuxEntries() {#aebb64611059504e4f1ad84d559b736ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::XCOFFSymbolRef::getNumberOfAuxEntries ()</td>
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



<p>Definition at line 847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h/#a12d20b6a13c62bedb85b9bb44348b641">GETVALUE</a>.</p>


<p>Referenced by <a href="#a046c53b9366f602644b022ee6e86c57e">getXCOFFCsectAuxRef</a>.</p>

</div>
</div>

### getSectionNumber() {#a26ad87605387868c03e36dddba0aff91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int16_t llvm::object::XCOFFSymbolRef::getSectionNumber ()</td>
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



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h/#a12d20b6a13c62bedb85b9bb44348b641">GETVALUE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#af0d12d4046ba19c552b1e86fbe25abe9">llvm::object::XCOFFObjectFile::getSymbolSection</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a71d6474e0580f137735002afb39321c4">llvm::object::XCOFFObjectFile::getSymbolSectionID</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a90303baf9d185097198f817b998136a6">llvm::object::XCOFFObjectFile::getSymbolSectionName</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a606ab46a34eecd59e09198799a982dc4">llvm::object::XCOFFObjectFile::getSymbolType</a>.</p>

</div>
</div>

### getSize() {#a38013df05132b768d4980f709b43b2ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFSymbolRef::getSize ()</td>
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



<p>Definition at line 820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aa08bcfd0fd633889120aa52eb115f3fb">llvm::object::SymbolRef::getObject</a> and <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a>.</p>


<p>Referenced by <a href="#a0b01026129dcc250501775442ac4b2e5">isFunction</a>.</p>

</div>
</div>

### getStorageClass() {#af60828c217c51c5f46cf6ecffb526a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XCOFF::StorageClass llvm::object::XCOFFSymbolRef::getStorageClass ()</td>
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



<p>Definition at line 845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h/#a12d20b6a13c62bedb85b9bb44348b641">GETVALUE</a>.</p>


<p>Referenced by <a href="#abbee638ba6d81acec9efec18822b973c">getCPUTypeIddForCFile</a>, <a href="#afd59a3374d86b63062c7e36c5c8c4a15">getLanguageIdForCFile</a>, <a href="#abb68cddc1b5010571d488b639eb9d561">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a606ab46a34eecd59e09198799a982dc4">llvm::object::XCOFFObjectFile::getSymbolType</a> and <a href="#a306cbb4386d868083a86447946e6ef6b">isCsectSymbol</a>.</p>

</div>
</div>

### getSymbol32() {#a505d506a424234d98ea617f60f69ddb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFSymbolEntry32 * llvm::object::XCOFFSymbolRef::getSymbol32 ()</td>
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



<p>Definition at line 798 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#abb68cddc1b5010571d488b639eb9d561">getName</a>.</p>

</div>
</div>

### getSymbol64() {#a421328a37b7de6fbb9712ec550d131a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFSymbolEntry64 * llvm::object::XCOFFSymbolRef::getSymbol64 ()</td>
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



<p>Definition at line 802 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#abb68cddc1b5010571d488b639eb9d561">getName</a>.</p>

</div>
</div>

### getSymbolType() {#a7033122210368081acb564a69e3ce350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::XCOFFSymbolRef::getSymbolType ()</td>
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



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h/#a12d20b6a13c62bedb85b9bb44348b641">GETVALUE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a> and <a href="#a0b01026129dcc250501775442ac4b2e5">isFunction</a>.</p>

</div>
</div>

### getValue() {#ab1e1cc599a5a829c5962a07153a9a8c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFSymbolRef::getValue ()</td>
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



<p>Definition at line 806 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aa08bcfd0fd633889120aa52eb115f3fb">llvm::object::SymbolRef::getObject</a>, <a href="#aa08b0ee12e4396d3b0b4f50863064f4a">getValue32</a>, <a href="#acb2d20e7ebc4ca9471bad9a00ed0b230">getValue64</a> and <a href="/web-llvm/docs/api/classes/llvm/object/symbolicfile/#a635a922ee4f32bce5b1f3ae39e065c31">llvm::object::SymbolicFile::is64Bit</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#afbca160cc61e2866976918c03e0135b6">llvm::object::XCOFFObjectFile::getSymbolAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a78b3dd58311eae0ca4186635d31c8655">llvm::object::XCOFFObjectFile::getSymbolValueImpl</a>.</p>

</div>
</div>

### getValue32() {#aa08b0ee12e4396d3b0b4f50863064f4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::object::XCOFFSymbolRef::getValue32 ()</td>
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



<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#ab1e1cc599a5a829c5962a07153a9a8c1">getValue</a>.</p>

</div>
</div>

### getValue64() {#acb2d20e7ebc4ca9471bad9a00ed0b230}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::XCOFFSymbolRef::getValue64 ()</td>
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



<p>Definition at line 815 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/basicsymbolref/#a4edbb76f7d11d8891e10524e40bdaa85">llvm::object::BasicSymbolRef::getRawDataRefImpl</a> and <a href="/web-llvm/docs/api/unions/llvm/object/datarefimpl/#a2d14abe832a3bf0cc963944bcd13d1cd">llvm::object::DataRefImpl::p</a>.</p>


<p>Referenced by <a href="#ab1e1cc599a5a829c5962a07153a9a8c1">getValue</a>.</p>

</div>
</div>

### getXCOFFCsectAuxRef() {#a046c53b9366f602644b022ee6e86c57e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; XCOFFCsectAuxRef &gt; llvm::object::XCOFFSymbolRef::getXCOFFCsectAuxRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 858 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1313 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a6d134aed42e1f7be67a8dc02c9bd401fab6ff03dac80c8cf393e7c3a876894607">llvm::XCOFF::AUX_CSECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#ac0d87919540a6096c1a44308a603c50e">llvm::object::XCOFFObjectFile::getAdvancedSymbolEntryAddress</a>, <a href="#af12e28a6a9862376cd2e440636d6dfac">getEntryAddress</a>, <a href="#abb68cddc1b5010571d488b639eb9d561">getName</a>, <a href="#aebb64611059504e4f1ad84d559b736ec">getNumberOfAuxEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aa08bcfd0fd633889120aa52eb115f3fb">llvm::object::SymbolRef::getObject</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="#a306cbb4386d868083a86447946e6ef6b">isCsectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/object/#af8cb7595a44be5c401fa70704948911a">llvm::object::viewAs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a69c221e2f2dc591094cf0b0d92fd42d3">llvm::object::XCOFFObjectFile::getCommonSymbolSizeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#afba35271cc6fce891ce2bda4576c87d5">llvm::object::XCOFFObjectFile::getSymbolAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#ad6cf6760f283737b422b80253b8828d2">llvm::object::XCOFFObjectFile::getSymbolSize</a> and <a href="#a0b01026129dcc250501775442ac4b2e5">isFunction</a>.</p>

</div>
</div>

### isCsectSymbol() {#a306cbb4386d868083a86447946e6ef6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::XCOFFSymbolRef::isCsectSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1307 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a19f57c169e86a4332accccf291954261">llvm::XCOFF::C_EXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70aeffba1492a002e3d506d9eca64672a24">llvm::XCOFF::C_HIDEXT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abcfbfa374a3d08b4ee55f054ceb27a70a8f5d26c17483f47bf923e263a4de4c2e">llvm::XCOFF::C_WEAKEXT</a> and <a href="#af60828c217c51c5f46cf6ecffb526a28">getStorageClass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a69c221e2f2dc591094cf0b0d92fd42d3">llvm::object::XCOFFObjectFile::getCommonSymbolSizeImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#afba35271cc6fce891ce2bda4576c87d5">llvm::object::XCOFFObjectFile::getSymbolAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a26063993809b386ab934532d1af8b56c">llvm::object::XCOFFObjectFile::getSymbolFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#ad6cf6760f283737b422b80253b8828d2">llvm::object::XCOFFObjectFile::getSymbolSize</a>, <a href="#a046c53b9366f602644b022ee6e86c57e">getXCOFFCsectAuxRef</a> and <a href="#a0b01026129dcc250501775442ac4b2e5">isFunction</a>.</p>

</div>
</div>

### isFunction() {#a0b01026129dcc250501775442ac4b2e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; llvm::object::XCOFFSymbolRef::isFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>, definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa1e1474f15df639f0d874b21f15666f7">llvm::cantFail</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a1c31173d8348908445a5ff51bb41ab94">llvm::object::createError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/object/#a9a7531bc9b966f61f5a00f2d4edb4401">llvm::object::FunctionSym</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#ac22d03239bd28b53a229486b43a9d3b8">llvm::object::SymbolRef::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a697780726aa58d4d97569aafa03367f5">llvm::object::XCOFFCsectAuxRef::getEntryAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#aa08bcfd0fd633889120aa52eb115f3fb">llvm::object::SymbolRef::getObject</a>, <a href="#a38013df05132b768d4980f709b43b2ee">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a0a8c26c5e6a324b7caf6c9eee6350480">llvm::object::XCOFFCsectAuxRef::getStorageMappingClass</a>, <a href="/web-llvm/docs/api/classes/llvm/object/xcoffcsectauxref/#a4bb4dcacc2b9e1dadcd353b2a4245cd3">llvm::object::XCOFFCsectAuxRef::getSymbolType</a>, <a href="#a7033122210368081acb564a69e3ce350">getSymbolType</a>, <a href="#a046c53b9366f602644b022ee6e86c57e">getXCOFFCsectAuxRef</a>, <a href="#a306cbb4386d868083a86447946e6ef6b">isCsectSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>, <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502ca4fbe0b67fd3e6e9e044d17e1c8ea171f">llvm::XCOFF::XMC_GL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#abf0ae26de1e332dddf7d1383bb68502cac7850ad5e926ed392928b68832be764e">llvm::XCOFF::XMC_PR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fa533de1d99e6b391e90e30a38b9e3a954">llvm::XCOFF::XTY_CM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fad8a6731bed03a3891075d7ba162f83ba">llvm::XCOFF::XTY_ER</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fac4e3fde018bdce1941b4fcb749178493">llvm::XCOFF::XTY_LD</a> and <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#ae6213556e13de39091f6861f199d7b1fabc703e0e4100086f310d23f214a3cf03">llvm::XCOFF::XTY_SD</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/xcoffobjectfile/#a606ab46a34eecd59e09198799a982dc4">llvm::object::XCOFFObjectFile::getSymbolType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getObject() {#a8359acd9c23991360acf5b722696d20d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XCOFFObjectFile * llvm::object::XCOFFSymbolRef::getObject ()</td>
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



<p>Definition at line 861 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/xcoffobjectfile-h">XCOFFObjectFile.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/xcoffobjectfile-cpp">XCOFFObjectFile.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
