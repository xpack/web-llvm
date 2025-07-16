---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAMemoryBehaviorCallSite` Struct Reference

<p>AAMemoryBehavior attribute for call sites. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite">AACalleeToCallSite&lt;AAType, BaseType, StateType, IntroduceCallBaseContext, IRAttributeKind&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for generic replication: function returned -&gt; cs returned. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f55a5db145ff144d2d4a2371cb2c05">AAMemoryBehaviorCallSite</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0451826f9ecd21f9d963cc51401b1b4d">manifest</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::manifest(...). <a href="#a0451826f9ecd21f9d963cc51401b1b4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2c4384f29f2d311b1248f9b831f374">trackStatistics</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a> <a href="#a5f2c4384f29f2d311b1248f9b831f374">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>AAMemoryBehavior attribute for call sites.</p>

<p>Definition at line 8077 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAMemoryBehaviorCallSite() {#a20f55a5db145ff144d2d4a2371cb2c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::AAMemoryBehaviorCallSite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 8079 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#a9cd344c1e9570c7b32f1196a3037999d">anonymous{AttributorAttributes.cpp}::AACalleeToCallSite&lt; AAMemoryBehavior, AAMemoryBehaviorImpl &gt;::AACalleeToCallSite</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#ad661bac9a38752d2abbbbf67130d5cdb">llvm::AAMemoryBehavior::AAMemoryBehavior</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### manifest() {#a0451826f9ecd21f9d963cc51401b1b4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::manifest(...).</p>

<p>Definition at line 8083 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorimpl/#a5f93e36de0b3b9a3777b20c3d7772cd5">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorImpl::AttrKinds</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4c17a71e75898bbc42578a1c0b94c6b6">llvm::IRPosition::callsite_argument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a9f40f87a556db81bd2403007b83acce7">llvm::IRPosition::getAnchorValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adaf42001b3cc4c8c631902cbb48106d5">llvm::Attribute::getWithMemoryEffects</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a9e33a52cf9594a3a2f962a24328b59bc">llvm::AAMemoryBehavior::isAssumedReadNone</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a0d5c2d97702f51db9f73d3147f2b25e9">llvm::AAMemoryBehavior::isAssumedReadOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#aa70372b8e98c0f7aa3422a936e0dab0e">llvm::AAMemoryBehavior::isAssumedWriteOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a8c57cabc627d282678d407f79da2b6e7">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyReadsMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a0dc1a3456bce25673dff8dce6f240a8f">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::readOnly</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#aff771abf487136aeebb6862871d5e715">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::unknown</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a9e3dc568b5f51e03441c9c44b618f337">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::writeOnly</a>.</p>

</div>
</div>

### trackStatistics() {#a5f2c4384f29f2d311b1248f9b831f374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::trackStatistics ()</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a></p>

<p>Definition at line 8105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a9e33a52cf9594a3a2f962a24328b59bc">llvm::AAMemoryBehavior::isAssumedReadNone</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#a0d5c2d97702f51db9f73d3147f2b25e9">llvm::AAMemoryBehavior::isAssumedReadOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorybehavior/#aa70372b8e98c0f7aa3422a936e0dab0e">llvm::AAMemoryBehavior::isAssumedWriteOnly</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a5fa8d57dba0bc7fc96c6d4b65451c1cd">STATS_DECLTRACK_CS_ATTR</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
