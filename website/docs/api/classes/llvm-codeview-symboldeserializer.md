---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/codeview/symboldeserializer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SymbolDeserializer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::codeview::SymbolDeserializer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">llvm/DebugInfo/CodeView/SymbolDeserializer.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitorcallbacks">SymbolVisitorCallbacks</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab30b0d95bfa4cdc2394907f0434ac7da">SymbolDeserializer</a> (SymbolVisitorDelegate *Delegate, CodeViewContainer Container)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a0e3e3c9a99f6401aeeeae595f654f">visitSymbolBegin</a> (CVSymbol &amp;Record, uint32_t Offset) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Paired begin/end actions for all symbols. <a href="#ad0a0e3e3c9a99f6401aeeeae595f654f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a4bfa2f170b5f2bd0ed9aa6a57b78b">visitSymbolBegin</a> (CVSymbol &amp;Record) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba56bd58eb8c8e20111dbe85ce3eab16">visitSymbolEnd</a> (CVSymbol &amp;Record) override</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6be06ab49738ca510caf385522904697">visitKnownRecordImpl</a> (CVSymbol &amp;CVR, T &amp;Record)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitordelegate">SymbolVisitorDelegate</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa718008ec2f734e60f60b4eea777f1fb">Delegate</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af42f3ce165cde9bb452003a89c110116">Container</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; MappingInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e4aa2ea7faf2470d833dd23cc684ae">Mapping</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4f31719a3302d53ef0f8ab28e7afc76e">deserializeAs</a> (CVSymbol Symbol, T &amp;Record)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae8888971c92ae4066f6278e3f6b3773a">deserializeAs</a> (CVSymbol Symbol) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; T &gt;</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SymbolDeserializer() {#ab30b0d95bfa4cdc2394907f0434ac7da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::codeview::SymbolDeserializer::SymbolDeserializer (<a href="/web-llvm/docs/api/classes/llvm/codeview/symbolvisitordelegate">SymbolVisitorDelegate</a> * Delegate, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6">CodeViewContainer</a> Container)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>


<p>Referenced by <a href="#a4f31719a3302d53ef0f8ab28e7afc76e">deserializeAs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visitSymbolBegin() {#ad0a0e3e3c9a99f6401aeeeae595f654f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::codeview::SymbolDeserializer::visitSymbolBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record, uint32_t Offset)</td>
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

<p>Paired begin/end actions for all symbols.</p>


<p>Receives all record data, including the fixed-length record prefix. <a href="#ad0a0e3e3c9a99f6401aeeeae595f654f">visitSymbolBegin()</a> should return the type of the Symbol, or an error if it cannot be determined.</p>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="#ad0a0e3e3c9a99f6401aeeeae595f654f">visitSymbolBegin</a>.</p>


<p>Referenced by <a href="#a4f31719a3302d53ef0f8ab28e7afc76e">deserializeAs</a> and <a href="#ad0a0e3e3c9a99f6401aeeeae595f654f">visitSymbolBegin</a>.</p>

</div>
</div>

### visitSymbolBegin() {#a29a4bfa2f170b5f2bd0ed9aa6a57b78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::codeview::SymbolDeserializer::visitSymbolBegin (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### visitSymbolEnd() {#aba56bd58eb8c8e20111dbe85ce3eab16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::codeview::SymbolDeserializer::visitSymbolEnd (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; Record)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>.</p>


<p>Referenced by <a href="#a4f31719a3302d53ef0f8ab28e7afc76e">deserializeAs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### visitKnownRecordImpl() {#a6be06ab49738ca510caf385522904697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::codeview::SymbolDeserializer::visitKnownRecordImpl (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> &amp; CVR, T &amp; Record)</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Container {#af42f3ce165cde9bb452003a89c110116}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeViewContainer llvm::codeview::SymbolDeserializer::Container</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>

</div>
</div>

### Delegate {#aa718008ec2f734e60f60b4eea777f1fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SymbolVisitorDelegate* llvm::codeview::SymbolDeserializer::Delegate</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>

</div>
</div>

### Mapping {#a67e4aa2ea7faf2470d833dd23cc684ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MappingInfo&gt; llvm::codeview::SymbolDeserializer::Mapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### deserializeAs() {#a4f31719a3302d53ef0f8ab28e7afc76e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::codeview::SymbolDeserializer::deserializeAs (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> Symbol, T &amp; Record)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6a95aca07e95d9459c1bb31f4e7f9fda10">llvm::codeview::ObjectFile</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#ab30b0d95bfa4cdc2394907f0434ac7da">SymbolDeserializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#ad0a0e3e3c9a99f6401aeeeae595f654f">visitSymbolBegin</a> and <a href="#aba56bd58eb8c8e20111dbe85ce3eab16">visitSymbolEnd</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/symbolrecordhelpers-cpp/#aec9b5f4a60552ed88346b2a37636ae4f">createRecord</a>, <a href="#ae8888971c92ae4066f6278e3f6b3773a">deserializeAs</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/nativefunctionsymbol/#a46cd97d4b03e3d554934be6b9083050b">llvm::pdb::NativeFunctionSymbol::findInlineFramesByVA</a>, <a href="/web-llvm/docs/api/structs/llvm/codeviewyaml/detail/symbolrecordimpl/#a946f92a0c1edf978ef6731937ec00109">llvm::CodeViewYAML::detail::SymbolRecordImpl&lt; T &gt;::fromCodeViewSymbol</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/symbolcache/#affa16ab83d35cb583b2ae91644aa8c68">llvm::pdb::SymbolCache::getOrCreateGlobalSymbolByOffset</a>.</p>

</div>
</div>

### deserializeAs() {#ae8888971c92ae4066f6278e3f6b3773a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; T &gt; llvm::codeview::SymbolDeserializer::deserializeAs (<a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a5cc6234b75e6212142e2a91d34af146f">CVSymbol</a> Symbol)</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a>.</p>


<p>References <a href="#a4f31719a3302d53ef0f8ab28e7afc76e">deserializeAs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/symboldeserializer-h">SymbolDeserializer.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
