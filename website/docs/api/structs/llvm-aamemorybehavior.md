---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/aamemorybehavior
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AAMemoryBehavior` Struct

<p>An abstract interface for memory access kind related attributes (readnone/readonly/writeonly). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AAMemoryBehavior { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">llvm/Transforms/IPO/Attributor.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/irattribute">IRAttribute&lt;AK, BaseType, AAType&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class that provides common functionality to manifest IR attributes. <a href="/web-llvm/docs/api/structs/llvm/irattribute/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl">AAMemoryBehaviorImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a79d67102092193edc6d431f35cdb072d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State encoding bits. <a href="#a79d67102092193edc6d431f35cdb072d">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad661bac9a38752d2abbbbf67130d5cdb">AAMemoryBehavior</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55933ff4fba92b60ec3a44b108997bad">isKnownReadNone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value is not read or accessed in its respective scope. <a href="#a55933ff4fba92b60ec3a44b108997bad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e33a52cf9594a3a2f962a24328b59bc">isAssumedReadNone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value is not read or accessed in its respective scope. <a href="#a9e33a52cf9594a3a2f962a24328b59bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afed5e6d3d20c2ed8c757151340aa70ea">isKnownReadOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value is not accessed (=written) in its respective scope. <a href="#afed5e6d3d20c2ed8c757151340aa70ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5c2d97702f51db9f73d3147f2b25e9">isAssumedReadOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value is not accessed (=written) in its respective scope. <a href="#a0d5c2d97702f51db9f73d3147f2b25e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fe27a0a788e845e5e5e8600ba732217">isKnownWriteOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we know that the underlying value is not read in its respective scope. <a href="#a7fe27a0a788e845e5e5e8600ba732217">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa70372b8e98c0f7aa3422a936e0dab0e">isAssumedWriteOnly</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we assume that the underlying value is not read in its respective scope. <a href="#aa70372b8e98c0f7aa3422a936e0dab0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f5818aaf0d73a1489c328632a055b69">getName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a7d84d85c6cb8cc16db41d83859096256">AbstractAttribute::getName()</a> <a href="#a1f5818aaf0d73a1489c328632a055b69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3196387d5bfcbe7294c0c09fa449c52">getIdAddr</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afb1ae982372c7bd88717c53d8f8e5470">AbstractAttribute::getIdAddr()</a> <a href="#ae3196387d5bfcbe7294c0c09fa449c52">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11ae237be3261cc66ecdf24a1735b1c8">hasTrivialInitializer</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afdcbf0c6bc57e95a2975054b96839b85">AbstractAttribute::hasTrivialInitializer</a>. <a href="#a11ae237be3261cc66ecdf24a1735b1c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7efda60b9905c2287555f2e3e97e32">isValidIRPositionForInit</a> (Attributor &amp;A, const IRPosition &amp;IRP)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a0b23d1cedd8202d1b786e1ab43313084">AbstractAttribute::isValidIRPositionForInit</a>. <a href="#a1d7efda60b9905c2287555f2e3e97e32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior">AAMemoryBehavior</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34deafdbba58ec4162c3941ae5940112">createForPosition</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an abstract attribute view for the position <span class="doxyComputerOutput">IRP</span>. <a href="#a34deafdbba58ec4162c3941ae5940112">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a162e57b7e109d765f8dac145f648964a">classof</a> (const AbstractAttribute *AA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior">AAMemoryBehavior</a>. <a href="#a162e57b7e109d765f8dac145f648964a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5819afb332c2bf8d5e347df978c2fff5">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique ID (due to the unique address) <a href="#a5819afb332c2bf8d5e347df978c2fff5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An abstract interface for memory access kind related attributes (readnone/readonly/writeonly).</p>

<p>Definition at line 4635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a79d67102092193edc6d431f35cdb072d}

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

<p>State encoding bits.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_READS<a id="a79d67102092193edc6d431f35cdb072da968857ad600f95aa7d356e09c065c64f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_WRITES<a id="a79d67102092193edc6d431f35cdb072da855b6c4a37d05f98826cad5d6c26cb14"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_ACCESSES<a id="a79d67102092193edc6d431f35cdb072da99fd7a59be55148bc3363d90453cc368"></a></td>
<td class="doxyEnumItemDescription"> (= NO_READS | NO_WRITES)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BEST_STATE<a id="a79d67102092193edc6d431f35cdb072da6b8577d14abbaf2ef84df4df30780f1b"></a></td>
<td class="doxyEnumItemDescription"> (= NO_ACCESSES)</td>
</tr>

</table>
</dd>
</dl>


<p>A set bit in the state means the property holds. BEST_STATE is the best possible state, 0 the worst possible state.</p>


<p>Definition at line 4654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAMemoryBehavior() {#ad661bac9a38752d2abbbbf67130d5cdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AAMemoryBehavior::AAMemoryBehavior (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 4640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/irattribute/#ac3333cdcba76a6af382bcb7acd0d8419">llvm::IRAttribute&lt; Attribute::None, StateWrapper&lt; BitIntegerState&lt; uint8_t, 3 &gt;, AbstractAttribute &gt;, AAMemoryBehavior &gt;::IRAttribute</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a20f55a5db145ff144d2d4a2371cb2c05">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::AAMemoryBehaviorCallSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#ac1528f84762237cd607845b9f7d6295a">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::AAMemoryBehaviorImpl</a>, <a href="#a34deafdbba58ec4162c3941ae5940112">createForPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#a7cbfbbbb3a4ab59262caf3c1a7c6bd04">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::updateImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getIdAddr() {#ae3196387d5bfcbe7294c0c09fa449c52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::AAMemoryBehavior::getIdAddr ()</td>
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

<p>Definition at line 4695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a5819afb332c2bf8d5e347df978c2fff5">ID</a>.</p>

</div>
</div>

### getName() {#a1f5818aaf0d73a1489c328632a055b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string llvm::AAMemoryBehavior::getName ()</td>
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

<p>Definition at line 4692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isAssumedReadNone() {#a9e33a52cf9594a3a2f962a24328b59bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::isAssumedReadNone ()</td>
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

<p>Return true if we assume that the underlying value is not read or accessed in its respective scope.</p>

<p>Definition at line 4669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint8_t, 3 &gt;::isAssumed</a> and <a href="#a79d67102092193edc6d431f35cdb072da99fd7a59be55148bc3363d90453cc368">NO_ACCESSES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#aaf12a1e247ff067ec47e8c70ac160089">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a34e094853fc48c4acf66ca5e1c5a73dd">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorargument/#a0bbf9a04b849b2003962680da62cc817">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a5f2c4384f29f2d311b1248f9b831f374">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a03923360e5ebf60d5896d80fc9ae1733">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a1a9d67d71dd9794dc6c291dfb8fa80ad">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::trackStatistics</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#a20c5d873d90d90a17beb2df4caddf253">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::trackStatistics</a>.</p>

</div>
</div>

### isAssumedReadOnly() {#a0d5c2d97702f51db9f73d3147f2b25e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::isAssumedReadOnly ()</td>
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

<p>Return true if we assume that the underlying value is not accessed (=written) in its respective scope.</p>

<p>Definition at line 4677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint8_t, 3 &gt;::isAssumed</a> and <a href="#a79d67102092193edc6d431f35cdb072da855b6c4a37d05f98826cad5d6c26cb14">NO_WRITES</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#aaf12a1e247ff067ec47e8c70ac160089">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a34e094853fc48c4acf66ca5e1c5a73dd">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a9a1b2954b9c4eb6f178a0c7e66581822">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorargument/#a0bbf9a04b849b2003962680da62cc817">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a5f2c4384f29f2d311b1248f9b831f374">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a03923360e5ebf60d5896d80fc9ae1733">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a1a9d67d71dd9794dc6c291dfb8fa80ad">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::trackStatistics</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#a20c5d873d90d90a17beb2df4caddf253">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::trackStatistics</a>.</p>

</div>
</div>

### isAssumedWriteOnly() {#aa70372b8e98c0f7aa3422a936e0dab0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::isAssumedWriteOnly ()</td>
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

<p>Return true if we assume that the underlying value is not read in its respective scope.</p>

<p>Definition at line 4685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a38acb9f66b8669c71052db94e468b3a9">llvm::BitIntegerState&lt; uint8_t, 3 &gt;::isAssumed</a> and <a href="#a79d67102092193edc6d431f35cdb072da968857ad600f95aa7d356e09c065c64f">NO_READS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#aaf12a1e247ff067ec47e8c70ac160089">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getAsStr</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a34e094853fc48c4acf66ca5e1c5a73dd">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::getDeducedAttributes</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#ae444282c6d6bc8d5e9905620c936d39e">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorargument/#a0bbf9a04b849b2003962680da62cc817">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a5f2c4384f29f2d311b1248f9b831f374">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsiteargument/#a03923360e5ebf60d5896d80fc9ae1733">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSiteArgument::trackStatistics</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a1a9d67d71dd9794dc6c291dfb8fa80ad">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::trackStatistics</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfunction/#a20c5d873d90d90a17beb2df4caddf253">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFunction::trackStatistics</a>.</p>

</div>
</div>

### isKnownReadNone() {#a55933ff4fba92b60ec3a44b108997bad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::isKnownReadNone ()</td>
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

<p>Return true if we know that the underlying value is not read or accessed in its respective scope.</p>

<p>Definition at line 4665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint8_t, 3 &gt;::isKnown</a> and <a href="#a79d67102092193edc6d431f35cdb072da99fd7a59be55148bc3363d90453cc368">NO_ACCESSES</a>.</p>

</div>
</div>

### isKnownReadOnly() {#afed5e6d3d20c2ed8c757151340aa70ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::isKnownReadOnly ()</td>
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

<p>Return true if we know that the underlying value is not accessed (=written) in its respective scope.</p>

<p>Definition at line 4673 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint8_t, 3 &gt;::isKnown</a> and <a href="#a79d67102092193edc6d431f35cdb072da855b6c4a37d05f98826cad5d6c26cb14">NO_WRITES</a>.</p>

</div>
</div>

### isKnownWriteOnly() {#a7fe27a0a788e845e5e5e8600ba732217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::isKnownWriteOnly ()</td>
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

<p>Return true if we know that the underlying value is not read in its respective scope.</p>

<p>Definition at line 4681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#af53ef7825e1ab608c8b6cc2ab94e5ddf">llvm::BitIntegerState&lt; uint8_t, 3 &gt;::isKnown</a> and <a href="#a79d67102092193edc6d431f35cdb072da968857ad600f95aa7d356e09c065c64f">NO_READS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a162e57b7e109d765f8dac145f648964a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> * AA)</td>
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

<p>This function should return true if the type of the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a></span> is <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior">AAMemoryBehavior</a>.</p>

<p>Definition at line 4699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Reference <a href="#a5819afb332c2bf8d5e347df978c2fff5">ID</a>.</p>

</div>
</div>

### createForPosition() {#a34deafdbba58ec4162c3941ae5940112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMemoryBehavior &amp; llvm::AAMemoryBehavior::createForPosition (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>Definition at line 4688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#ad661bac9a38752d2abbbbf67130d5cdb">AAMemoryBehavior</a>.</p>

</div>
</div>

### hasTrivialInitializer() {#a11ae237be3261cc66ecdf24a1735b1c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::hasTrivialInitializer ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#afdcbf0c6bc57e95a2975054b96839b85">AbstractAttribute::hasTrivialInitializer</a>.</p>

<p>Definition at line 4643 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>

</div>
</div>

### isValidIRPositionForInit() {#a1d7efda60b9905c2287555f2e3e97e32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::AAMemoryBehavior::isValidIRPositionForInit (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP)</td>
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

<p>Definition at line 4646 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a6a0e4ff765ad5ab3c9a53c917f3cf1cd">llvm::IRPosition::getAssociatedType</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a79c71e9c03aff7ec01197395cab4e521">llvm::IRPosition::isFunctionScope</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a5819afb332c2bf8d5e347df978c2fff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char AAMemoryBehavior::ID = 0</td>
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

<p>Definition at line 4704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a>.</p>


<p>Referenced by <a href="#a162e57b7e109d765f8dac145f648964a">classof</a>, <a href="#ae3196387d5bfcbe7294c0c09fa449c52">getIdAddr</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a6c7a8371c75641e29a5259c131fd8408">runAttributorLightOnFunctions</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/attributor-h">Attributor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
