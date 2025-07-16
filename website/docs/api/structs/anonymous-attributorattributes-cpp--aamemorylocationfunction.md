---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aamemorylocationfunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AAMemoryLocationFunction` Struct Reference

<p>An <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> to represent the memory behavior function attributes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl">AAMemoryLocationImpl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b54badde15a6d2fb25316b128b53914">AAMemoryLocationFunction</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4de16ddc7d968804ec058444ee4145fd">updateImpl</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See AbstractAttribute::updateImpl(Attributor &amp;A). <a href="#a4de16ddc7d968804ec058444ee4145fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0634676415b9b78a340cc026357ce8">trackStatistics</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#add85e4d78cefc67429904d7492aff9a4">AbstractAttribute::trackStatistics()</a> <a href="#a8b0634676415b9b78a340cc026357ce8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> to represent the memory behavior function attributes.</p>

<p>Definition at line 8799 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AAMemoryLocationFunction() {#a4b54badde15a6d2fb25316b128b53914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::AAMemoryLocationFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 8800 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a14fd1a0c7ba79d015f0d48a648e1c74e">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::AAMemoryLocationImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### trackStatistics() {#a8b0634676415b9b78a340cc026357ce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::trackStatistics ()</td>
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

<p>Definition at line 8841 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#af6e57f7a255f09243d9c303563c08ceb">llvm::AAMemoryLocation::isAssumedArgMemOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a876121bc7d9e565f5627b2350d643c64">llvm::AAMemoryLocation::isAssumedInaccessibleMemOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#aa6830f20bec5f8746595c497d5c3c4ed">llvm::AAMemoryLocation::isAssumedInaccessibleOrArgMemOnly</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ae336b602cf0a89b2fa9551663c6f3295">llvm::AAMemoryLocation::isAssumedReadNone</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp/#a3c8de5408a05c800157fed555bcc739f">STATS_DECLTRACK_FN_ATTR</a>.</p>

</div>
</div>

### updateImpl() {#a4de16ddc7d968804ec058444ee4145fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAMemoryLocationFunction::updateImpl (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See AbstractAttribute::updateImpl(Attributor &amp;A).</p>

<p>Definition at line 8804 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#ae2c6df05bd2236b9d36680de5e09b78a">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeAccessedLocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a8791f3eb0abe69328cbf726f8d0716ce">llvm::IntegerStateBase&lt; uint32_t, BestState, 0 &gt;::getAssumed</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ad7370cc538424a0e12fd632cb076c14c">llvm::AAMemoryLocation::getAssumedNotAccessedLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a37f5c90d6e9853a204b4ca1da2317c66">llvm::AAMemoryLocation::getMemoryLocationsAsStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/integerstatebase/#a54591e342f7ba9c6ce57fe5327d3682b">llvm::IntegerStateBase&lt; uint32_t, BestState, 0 &gt;::indicateOptimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a93339349de364716175a03098d94d44f">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::indicatePessimisticFixpoint</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#afc0831ad69241e3cde373281a1024848">llvm::AAMemoryLocation::inverseLocation</a>, <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#ae336b602cf0a89b2fa9551663c6f3295">llvm::AAMemoryLocation::isAssumedReadNone</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1ab50339a10e1de285ac99d4c3990b8693">llvm::NONE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adadcb655edca867f08f7ea6068a7d8a1a7951811e4b085cf68ed3dc3191f36405">llvm::OPTIONAL</a>, <a href="/web-llvm/docs/api/structs/llvm/bitintegerstate/#a69055c62a711a6f503db05930ccb6ce7">llvm::BitIntegerState&lt; uint32_t, 511 &gt;::removeAssumedBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a> and <a href="/web-llvm/docs/api/structs/llvm/aamemorylocation/#a85955f71af20254ae831687849a1a737a9cac5c2e512a4b66789775333f4b5d53">llvm::AAMemoryLocation::VALID_STATE</a>.</p>

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
