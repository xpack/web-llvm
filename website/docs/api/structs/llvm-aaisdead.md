---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aaisdead
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAIsDead` Struct Reference

<p>An abstract interface for liveness abstract attribute. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AAIsDead { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper&lt;StateTy, BaseType, Ts&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to tie a abstract state implementation to an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/statewrapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction">AAIsDeadFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl">AAIsDeadValueImpl</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca33c93ca05f3f1f4757e3e9377a7897">Base</a> = <a href="/web-llvm/docs/api/structs/llvm/statewrapper">StateWrapper</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate">BitIntegerState</a>&lt; uint8_t, 3, 0 &gt;, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a591a301d0f160e896e84309662b31b4a">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State encoding bits. A set bit in the state means the property holds. <a href="#a591a301d0f160e896e84309662b31b4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea22a140f2dacd1fd73d2b0cb8c26c10">AAIsDead</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce65dbd067cee1104e6042439615886">isAssumedDead</a> (const BasicBlock *BB) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">BB</span> is assumed dead. <a href="#a7ce65dbd067cee1104e6042439615886">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a290f1c20e4ed78922716dbf0546a6a">isEdgeDead</a> (const BasicBlock *From, const BasicBlock *To) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if the edge from <span class="doxyComputerOutput">From</span> BB to <span class="doxyComputerOutput">To</span> BB is assumed dead. <a href="#a2a290f1c20e4ed78922716dbf0546a6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac14fcbdb2794f675319e696a720b28e0">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a> <a href="#ac14fcbdb2794f675319e696a720b28e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3559216f5c1835417976a1a19f72c5">getIdAddr</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a> <a href="#aac3559216f5c1835417976a1a19f72c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5092ee8377153501a5d1cb113d15d073">isAssumedDead</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The query functions are protected such that other attributes need to go through the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> interfaces: <span class="doxyComputerOutput">Attributor::isAssumedDead(...)</span> <a href="#a5092ee8377153501a5d1cb113d15d073">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e3a8bdd3d3dbf0516eb3f5ff8c1ef2">isKnownDead</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the underlying value is known dead. <a href="#a23e3a8bdd3d3dbf0516eb3f5ff8c1ef2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b080351603fd668b738e5d3761d41f">isKnownDead</a> (const BasicBlock *BB) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">BB</span> is known dead. <a href="#a09b080351603fd668b738e5d3761d41f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a440aac0c07c6b7ad470f8edbd651a059">isAssumedDead</a> (const Instruction *I) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is assumed dead. <a href="#a440aac0c07c6b7ad470f8edbd651a059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec825f7828fa296055c71111af4ebcee">isKnownDead</a> (const Instruction *I) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">I</span> is known dead. <a href="#aec825f7828fa296055c71111af4ebcee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a533bdbd6237d8ec730db3c9242010cc4">isRemovableStore</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the underlying value is a store that is known to be removable. <a href="#a533bdbd6237d8ec730db3c9242010cc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a197b6c04a007a3c42624364e59f277f0">isLiveInstSet</a> (T begin, T end) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used to check if at least one instruction in a collection of instructions is live. <a href="#a197b6c04a007a3c42624364e59f277f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b6322e8503550536c5b31634875755a">isValidIRPositionForInit</a> (Attributor &amp;A, const IRPosition &amp;IRP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>. <a href="#a4b6322e8503550536c5b31634875755a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/aaisdead">AAIsDead</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ee03a36813075ab10099ad53d55e2f">createForPosition</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>. <a href="#a54ee03a36813075ab10099ad53d55e2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4185b617dbcb88c05a7434bb14967c4">mayCatchAsynchronousExceptions</a> (const Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if <span class="doxyComputerOutput">F</span> might catch asynchronous exceptions. <a href="#ae4185b617dbcb88c05a7434bb14967c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3806b600f18409e1dde999c69f69d2">classof</a> (const AbstractAttribute *AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aaisdead">AAIsDead</a>. <a href="#a0e3806b600f18409e1dde999c69f69d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11865a8f0eb5ad41b265395eafe487e2">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique ID (due to the unique address) <a href="#a11865a8f0eb5ad41b265395eafe487e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An abstract interface for liveness abstract attribute.</p>

<p>Definition at line 3984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Base {#aca33c93ca05f3f1f4757e3e9377a7897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AAIsDead::Base =  StateWrapper&lt;BitIntegerState&lt;uint8_t, 3, 0&gt;, AbstractAttribute&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a591a301d0f160e896e84309662b31b4a}

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

<p>State encoding bits. A set bit in the state means the property holds.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HAS_NO_EFFECT<a id="a591a301d0f160e896e84309662b31b4aabb1d5fa26c8d6533e83ec1285fe68ec3"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_REMOVABLE<a id="a591a301d0f160e896e84309662b31b4aa5857a79cfefc4a4daec69e313fd59e02"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IS_DEAD<a id="a591a301d0f160e896e84309662b31b4aa84ceb34b5f41b78640c74930450f2488"></a></td>
<td class="doxyEnumItemDescription"> (= HAS_NO_EFFECT | IS_REMOVABLE)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 3998 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Attributor {#a05f3b3169e1f6a561b0c38f0150b3867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 4077 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>


<p>Referenced by <a href="#aea22a140f2dacd1fd73d2b0cb8c26c10">AAIsDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadargument/#a84b4541154636b28a3f5bc4db4ce21e2">anonymous{AttributorAttributes.cpp}::AAIsDeadArgument::AAIsDeadArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsite/#ae0ef86220b51289221aeebe4841fd592">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSite::AAIsDeadCallSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a1105964783d1c7cc901ce8c314f16914">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::AAIsDeadCallSiteArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a8a059d1085e0ba3654bc942de5d175b2">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::AAIsDeadCallSiteReturned</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a924fde0a6a4b2f0271c700bd0f87ef6d">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::AAIsDeadFloating</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a5812672eee2d842c553ccb7d14419f38">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::AAIsDeadFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadreturned/#ad2371da6d1b21c88329618aea56df334">anonymous{AttributorAttributes.cpp}::AAIsDeadReturned::AAIsDeadReturned</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a8809fd5d7fcab7a9d38d3009d46002dc">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::AAIsDeadValueImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a50bddcd3343e78000f5f7a626614d50a">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::areAllUsesAssumedDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a544ea2dad2fbdae00ad2965dd3b93762">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::assumeLive</a>, <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>, <a href="#a54ee03a36813075ab10099ad53d55e2f">createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#add12a8a6d26c304684e816ad8241cc4b">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#adf4f579a309437c24aed6e78e5c566c2">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a86b1638912d3f2fbeaf9edffdaa00c10">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#add9c1c5a38893d00608c4e2473e6cce2">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsite/#adf87856893ffec2366a0a864c75e74ad">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#ac861cd301641588b3545b331f151cf9b">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a26e4580a4b5734beab116527fedd9cf0">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a6bb99a515b0f1ece7560275f4c47033c">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a5522acc0a362d7bea43440e227660448">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aeb97ea777b4c90532ce50e3f1bedcac6">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isAssumedDeadInternalFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a2758a929f5cb19b83ebb78e91b10ccb2">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::isAssumedSideEffectFree</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a64ffcd16d1457fc57339e15655b68627">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isDeadFence</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a2a4744a0553a69a758f119c04c303ae5">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isDeadStore</a>, <a href="#a4b6322e8503550536c5b31634875755a">isValidIRPositionForInit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadargument/#a26e9414eff6220d3277d7f7095a03617">anonymous{AttributorAttributes.cpp}::AAIsDeadArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5d6050f7be56f61036d2d194ac7f66f8">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a4c0d39301fbda30cede0fcbb4d649c75">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aa706a9b987f484bb0ac2c16422522dbc">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadreturned/#a5fbd0b238ec5abc8ab5dbc065b002c7a">anonymous{AttributorAttributes.cpp}::AAIsDeadReturned::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsite/#a85cb2e12e92f86599326efc164676e21">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5fb77be1b52b827ae66c6664e8e72420">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a7919aaff0b333257cd367569bae6f56d">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a416fe9863798afdfa2854866604d1bc4">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a6aaeb440ac0f45225f89b6b83444db1a">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadreturned/#a48f1fa48e2c1cd9fe84381387366cf1f">anonymous{AttributorAttributes.cpp}::AAIsDeadReturned::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAIsDead() {#aea22a140f2dacd1fd73d2b0cb8c26c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAIsDead::AAIsDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 3987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a5812672eee2d842c553ccb7d14419f38">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::AAIsDeadFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadvalueimpl/#a8809fd5d7fcab7a9d38d3009d46002dc">anonymous{AttributorAttributes.cpp}::AAIsDeadValueImpl::AAIsDeadValueImpl</a>, <a href="#a54ee03a36813075ab10099ad53d55e2f">createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aa706a9b987f484bb0ac2c16422522dbc">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::manifest</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5fb77be1b52b827ae66c6664e8e72420">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIdAddr() {#aac3559216f5c1835417976a1a19f72c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AAIsDead::getIdAddr ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a></p>

<p>Definition at line 4067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a11865a8f0eb5ad41b265395eafe487e2">ID</a>.</p>

</div>
</div>

### getName() {#ac14fcbdb2794f675319e696a720b28e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::AAIsDead::getName ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a></p>

<p>Definition at line 4064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isAssumedDead() {#a7ce65dbd067cee1104e6042439615886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isAssumedDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">BB</span> is assumed dead.</p>

<p>Definition at line 4055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isEdgeDead() {#a2a290f1c20e4ed78922716dbf0546a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isEdgeDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * To)</td>
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

<p>Return if the edge from <span class="doxyComputerOutput">From</span> BB to <span class="doxyComputerOutput">To</span> BB is assumed dead.</p>


<p>This is specifically useful in AAReachability.</p>


<p>Definition at line 4059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### isAssumedDead() {#a5092ee8377153501a5d1cb113d15d073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isAssumedDead ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The query functions are protected such that other attributes need to go through the <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> interfaces: <span class="doxyComputerOutput">Attributor::isAssumedDead(...)</span></p>


<p>Returns true if the underlying value is assumed dead.</p>


<p>Definition at line 4011 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsitereturned/#a26dfbcbd6c96fe2f56bdc08fbea402b8">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteReturned::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a28ca3a54ea9ef7dd53412258dc067de3">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a532d694575abb82423e79aedce3437cc">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0214244f107a21a911d07efd0c8e899b">llvm::Attributor::isAssumedDead</a> and <a href="#a197b6c04a007a3c42624364e59f277f0">isLiveInstSet</a>.</p>

</div>
</div>

### isAssumedDead() {#a440aac0c07c6b7ad470f8edbd651a059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isAssumedDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">I</span> is assumed dead.</p>

<p>Definition at line 4020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isKnownDead() {#a23e3a8bdd3d3dbf0516eb3f5ff8c1ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isKnownDead ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the underlying value is known dead.</p>

<p>Definition at line 4014 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a532d694575abb82423e79aedce3437cc">llvm::Attributor::isAssumedDead</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#a0214244f107a21a911d07efd0c8e899b">llvm::Attributor::isAssumedDead</a>.</p>

</div>
</div>

### isKnownDead() {#a09b080351603fd668b738e5d3761d41f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isKnownDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">BB</span> is known dead.</p>

<p>Definition at line 4017 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isKnownDead() {#aec825f7828fa296055c71111af4ebcee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isKnownDead (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <span class="doxyComputerOutput">I</span> is known dead.</p>

<p>Definition at line 4023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### isLiveInstSet() {#a197b6c04a007a3c42624364e59f277f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAIsDead::isLiveInstSet (T begin, T end)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is used to check if at least one instruction in a collection of instructions is live.</p>

<p>Definition at line 4033 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/aadepgraphnode/#aa0fdc2557596b4999278cfe51f228ab1">llvm::AADepGraphNode::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/aadepgraphnode/#abbf2add0f922e5947ad587adce417322">llvm::AADepGraphNode::end</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a054de50dbf11b87063f6a32f3bccee80">llvm::IRPosition::getAssociatedFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a5092ee8377153501a5d1cb113d15d073">isAssumedDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### isRemovableStore() {#a533bdbd6237d8ec730db3c9242010cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AAIsDead::isRemovableStore ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the underlying value is a store that is known to be removable.</p>


<p>This is different from dead stores as the removable store can have an effect on live values, especially loads, but that effect is propagated which allows us to remove the store in turn.</p>


<p>Definition at line 4029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/attributor/#a532d694575abb82423e79aedce3437cc">llvm::Attributor::isAssumedDead</a> and <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a0e3806b600f18409e1dde999c69f69d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAIsDead::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * AA)</td>
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

<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aaisdead">AAIsDead</a>.</p>

<p>Definition at line 4070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a11865a8f0eb5ad41b265395eafe487e2">ID</a>.</p>

</div>
</div>

### createForPosition() {#a54ee03a36813075ab10099ad53d55e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAIsDead &amp; llvm::AAIsDead::createForPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>.</p>

<p>Definition at line 4047 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#aea22a140f2dacd1fd73d2b0cb8c26c10">AAIsDead</a> and <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>.</p>

</div>
</div>

### isValidIRPositionForInit() {#a4b6322e8503550536c5b31634875755a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAIsDead::isValidIRPositionForInit (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>.</p>

<p>Definition at line 3990 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a05f3b3169e1f6a561b0c38f0150b3867">Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a9f40f87a556db81bd2403007b83acce7">llvm::IRPosition::getAnchorValue</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aea16db681aa18f4eded0015e284fdfe5">llvm::IRPosition::getPositionKind</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a53f576f97e0dfa8314afb16bd74a76d0aa823f70d88660d88196943a3f09301da">llvm::IRPosition::IRP_FUNCTION</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### mayCatchAsynchronousExceptions() {#ae4185b617dbcb88c05a7434bb14967c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAIsDead::mayCatchAsynchronousExceptions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>Determine if <span class="doxyComputerOutput">F</span> might catch asynchronous exceptions.</p>

<p>Definition at line 4050 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a57f0e4faf4e39fa79daf9de35b1c7244">llvm::canSimplifyInvokeNoUnwind</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a753ca373c3a99cb66666a497408ed72f">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#aa706a9b987f484bb0ac2c16422522dbc">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::manifest</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a11865a8f0eb5ad41b265395eafe487e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char AAIsDead::ID = 0</td>
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

<p>Unique ID (due to the unique address)</p>

<p>Definition at line 4075 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a0e3806b600f18409e1dde999c69f69d2">classof</a> and <a href="#aac3559216f5c1835417976a1a19f72c5">getIdAddr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
