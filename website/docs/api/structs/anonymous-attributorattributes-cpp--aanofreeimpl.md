---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aanofreeimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AANoFreeImpl` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AANoFreeImpl { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aanofree">AANoFree</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An <a href="/web-llvm/docs/api/structs/llvm/abstractattribute">AbstractAttribute</a> for nofree. <a href="/web-llvm/docs/api/structs/llvm/aanofree/#details">More...</a></p>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefloating">AANoFreeFloating</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>NoFree attribute for floating values. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefloating/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefunction">AANoFreeFunction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0a99973c86e45ef7205092a4becb407">AANoFreeImpl</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97c7dffaf9ec22a169ea965e2b255e95">initialize</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::initialize(...). <a href="#a97c7dffaf9ec22a169ea965e2b255e95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a642335d91f91ad57c209550723da37c2">updateImpl</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::updateImpl(...). <a href="#a642335d91f91ad57c209550723da37c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d23b0d9a00d895d55ac4aa92a94e2b2">getAsStr</a> (Attributor *A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>. <a href="#a6d23b0d9a00d895d55ac4aa92a94e2b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 2286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AANoFreeImpl() {#ad0a99973c86e45ef7205092a4becb407}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AANoFreeImpl::AANoFreeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 2287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/aanofree/#a3d647189717af5e0b76343c59f454864">llvm::AANoFree::AANoFree</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefloating/#a9ba82eafdf188c2a139dfbaf116de3af">anonymous{AttributorAttributes.cpp}::AANoFreeFloating::AANoFreeFloating</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanofreefunction/#a97e5a1af011bdc68984da9de9ef1db03">anonymous{AttributorAttributes.cpp}::AANoFreeFunction::AANoFreeFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsStr() {#a6d23b0d9a00d895d55ac4aa92a94e2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{AttributorAttributes.cpp}::AANoFreeImpl::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>.</p>

<p>Definition at line 2314 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a8791f3eb0abe69328cbf726f8d0716ce">llvm::IntegerStateBase&lt; bool, true, false &gt;::getAssumed</a>.</p>

</div>
</div>

### initialize() {#a97c7dffaf9ec22a169ea965e2b255e95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AANoFreeImpl::initialize (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::initialize(...).</p>

<p>Definition at line 2290 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ae8abeaeed2f11072b2d064fe70510e9f">llvm::AA::hasAssumedIRAttr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1ab50339a10e1de285ac99d4c3990b8693">llvm::NONE</a>.</p>

</div>
</div>

### updateImpl() {#a642335d91f91ad57c209550723da37c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AANoFreeImpl::updateImpl (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::updateImpl(...).</p>

<p>Definition at line 2298 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#aeef35bb007616add7418161b0313b56b">llvm::IRPosition::callsite_function</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ae8abeaeed2f11072b2d064fe70510e9f">llvm::AA::hasAssumedIRAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#aa3d9223692390a32c796d8160c6f058c">llvm::IntegerStateBase&lt; bool, true, false &gt;::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1aebdf9721be38d1fc1cd6db8c737d1be0">llvm::REQUIRED</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

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
