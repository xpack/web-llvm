---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/jitlink/i386
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `i386` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::jitlink::i386 { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/i386/gottablemanager">GOTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global Offset Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/i386/gottablemanager/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/i386/plttablemanager">PLTTableManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Procedure <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abee99c9c75d23a0304e5e58e3128a55f">Linkage</a> Table Builder. <a href="/web-llvm/docs/api/classes/llvm/jitlink/i386/plttablemanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeKind_i386 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> { <a href="#ab5b12c7ab25aac492521ed299ab357d4">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represets <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> fixups. <a href="#ab5b12c7ab25aac492521ed299ab357d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34d9ccf9d307a0f17db132d098383ec">getEdgeKindName</a> (Edge::Kind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a string name for the given <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> edge. <a href="#af34d9ccf9d307a0f17db132d098383ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf84875ae743236d8dd98fd56af9f7b">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E, const Symbol *GOTSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply fixup expression for edge to block content. <a href="#a1cf84875ae743236d8dd98fd56af9f7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac007f2f0fe33b64e019817ec931a4b79">createAnonymousPointer</a> (LinkGraph &amp;G, Section &amp;PointerSection, Symbol *InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new pointer block in the given section and returns an anonymous symbol pointing to it. <a href="#ac007f2f0fe33b64e019817ec931a4b79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c6b85409593a97182da9d8018eb8b2">createPointerJumpStubBlock</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a jump stub block that jumps via the pointer at the given symbol. <a href="#a10c6b85409593a97182da9d8018eb8b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b1c39140fb137040c2fa749b1aa300">createAnonymousPointerJumpStub</a> (LinkGraph &amp;G, Section &amp;StubSection, Symbol &amp;PointerSymbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a jump stub that jumps via the pointer at the given symbol and an anonymous symbol pointing to it. <a href="#a32b1c39140fb137040c2fa749b1aa300">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877b3d728be6b7084aef27f92242f8bf">optimizeGOTAndStubAccesses</a> (LinkGraph &amp;G)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimize the GOT and Stub relocations if the edge target address is in range. <a href="#a877b3d728be6b7084aef27f92242f8bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a470b8f4a62ef8353485a3570d0591">PointerSize</a> = 4</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> pointer size. <a href="#a60a470b8f4a62ef8353485a3570d0591">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd7edaafeb4fa06c154ac15f86d7ec0">NullPointerContent</a>[PointerSize] = {0x00, 0x00, 0x00, 0x00}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> null pointer content. <a href="#abbd7edaafeb4fa06c154ac15f86d7ec0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9431605d4e7f6a9d3296938180284ea">PointerJumpStubContent</a>[6] = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> pointer jump stub content. <a href="#aa9431605d4e7f6a9d3296938180284ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### EdgeKind\_i386 {#ab5b12c7ab25aac492521ed299ab357d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::i386::EdgeKind_i386 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represets <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> fixups.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="ab5b12c7ab25aac492521ed299ab357d4a54fe5e0c95650c41d0257689b94d8786"></a></td>
<td class="doxyEnumItemDescription">None (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer32<a id="ab5b12c7ab25aac492521ed299ab357d4ad4dd07c25270ad41112bab2f6144e5b8"></a></td>
<td class="doxyEnumItemDescription">A plain 32-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRel32<a id="ab5b12c7ab25aac492521ed299ab357d4a47d10bc81ee8242157fe8e01b342b73a"></a></td>
<td class="doxyEnumItemDescription">A 32-bit PC-relative relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pointer16<a id="ab5b12c7ab25aac492521ed299ab357d4ae9aae291a294099fd9442fbab0b4d1b0"></a></td>
<td class="doxyEnumItemDescription">A plain 16-bit pointer value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PCRel16<a id="ab5b12c7ab25aac492521ed299ab357d4a9461d47b61aeb45c0ae578c1f47257d5"></a></td>
<td class="doxyEnumItemDescription">A 16-bit PC-relative relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta32<a id="ab5b12c7ab25aac492521ed299ab357d4a5e468cc52cc2a56b6aadd5c67fac81b7"></a></td>
<td class="doxyEnumItemDescription">A 32-bit delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Delta32FromGOT<a id="ab5b12c7ab25aac492521ed299ab357d4a4733cbd257ce44d81ff8e234dd9c3ca0"></a></td>
<td class="doxyEnumItemDescription">A 32-bit GOT delta</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RequestGOTAndTransformToDelta32FromGOT<a id="ab5b12c7ab25aac492521ed299ab357d4aa8133be772984451fd00483f26395c24"></a></td>
<td class="doxyEnumItemDescription">A GOT entry offset within GOT getter/constructor, transformed to Delta32FromGOT pointing at the GOT entry for the original target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchPCRel32<a id="ab5b12c7ab25aac492521ed299ab357d4ab909c856e2b968674b459c652db52d21"></a></td>
<td class="doxyEnumItemDescription">A 32-bit PC-relative branch</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchPCRel32ToPtrJumpStub<a id="ab5b12c7ab25aac492521ed299ab357d4a645439244937f896e50b86e2de4f90a0"></a></td>
<td class="doxyEnumItemDescription">A 32-bit PC-relative branch to a pointer jump stub</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BranchPCRel32ToPtrJumpStubBypassable<a id="ab5b12c7ab25aac492521ed299ab357d4a032d3ec55a73bf3dd3dde3c7c15cd1d8"></a></td>
<td class="doxyEnumItemDescription">A relaxable version of BranchPCRel32ToPtrJumpStub</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/i386-h">i386.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### applyFixup() {#a1cf84875ae743236d8dd98fd56af9f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::i386::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * GOTSymbol)</td>
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

<p>Apply fixup expression for edge to block content.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/i386-h">i386.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ab909c856e2b968674b459c652db52d21">BranchPCRel32</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a645439244937f896e50b86e2de4f90a0">BranchPCRel32ToPtrJumpStub</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a032d3ec55a73bf3dd3dde3c7c15cd1d8">BranchPCRel32ToPtrJumpStubBypassable</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a5e468cc52cc2a56b6aadd5c67fac81b7">Delta32</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a4733cbd257ce44d81ff8e234dd9c3ca0">Delta32FromGOT</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="#af34d9ccf9d307a0f17db132d098383ec">getEdgeKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a54fe5e0c95650c41d0257689b94d8786">None</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a9461d47b61aeb45c0ae578c1f47257d5">PCRel16</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a47d10bc81ee8242157fe8e01b342b73a">PCRel32</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ae9aae291a294099fd9442fbab0b4d1b0">Pointer16</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ad4dd07c25270ad41112bab2f6144e5b8">Pointer32</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### createAnonymousPointer() {#ac007f2f0fe33b64e019817ec931a4b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::i386::createAnonymousPointer (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; PointerSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> * InitialTarget=nullptr, uint64_t InitialAddend=0)</td>
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

<p>Creates a new pointer block in the given section and returns an anonymous symbol pointing to it.</p>


<p>If InitialTarget is given then an Pointer32 relocation will be added to the block pointing at InitialTarget.</p>


<p>The pointer block will have the following default values: alignment: 32-bit alignment-offset: 0 address: highest allowable (~7U)</p>


<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/i386-h">i386.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#abbd7edaafeb4fa06c154ac15f86d7ec0">NullPointerContent</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ad4dd07c25270ad41112bab2f6144e5b8">Pointer32</a> and <a href="#a60a470b8f4a62ef8353485a3570d0591">PointerSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/i386/gottablemanager/#a94c61145b5bde0fda636f90d48ee9c3e">llvm::jitlink::i386::GOTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#af86dbecbbb47825e36f9af37bd6868ca">llvm::jitlink::getAnonymousPointerCreator</a>.</p>

</div>
</div>

### createAnonymousPointerJumpStub() {#a32b1c39140fb137040c2fa749b1aa300}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Symbol &amp; llvm::jitlink::i386::createAnonymousPointerJumpStub (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol)</td>
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

<p>Create a jump stub that jumps via the pointer at the given symbol and an anonymous symbol pointing to it.</p>


<p>Return the anonymous symbol.</p>


<p>The stub block will be created by createPointerJumpStubBlock.</p>


<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/i386-h">i386.h</a>.</p>


<p>References <a href="#a10c6b85409593a97182da9d8018eb8b2">createPointerJumpStubBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/i386/plttablemanager/#a56803ca2f0e3841ac19d4a3405a46704">llvm::jitlink::i386::PLTTableManager::createEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a6e58d27e8cd9ba5dadc9194100b69be4">llvm::jitlink::getPointerJumpStubCreator</a>.</p>

</div>
</div>

### createPointerJumpStubBlock() {#a10c6b85409593a97182da9d8018eb8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::i386::createPointerJumpStubBlock (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; StubSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; PointerSymbol)</td>
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

<p>Create a jump stub block that jumps via the pointer at the given symbol.</p>


<p>The stub block will have the following default values: alignment: 8-bit alignment-offset: 0 address: highest allowable: (~5U)</p>


<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/i386-h">i386.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ad4dd07c25270ad41112bab2f6144e5b8">Pointer32</a> and <a href="#aa9431605d4e7f6a9d3296938180284ea">PointerJumpStubContent</a>.</p>


<p>Referenced by <a href="#a32b1c39140fb137040c2fa749b1aa300">createAnonymousPointerJumpStub</a>.</p>

</div>
</div>

### getEdgeKindName() {#af34d9ccf9d307a0f17db132d098383ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::i386::getEdgeKindName (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a string name for the given <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> edge.</p>


<p>For debugging purposes only</p>


<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/i386-cpp">i386.cpp</a>.</p>


<p>References <a href="#ab5b12c7ab25aac492521ed299ab357d4ab909c856e2b968674b459c652db52d21">BranchPCRel32</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a645439244937f896e50b86e2de4f90a0">BranchPCRel32ToPtrJumpStub</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a032d3ec55a73bf3dd3dde3c7c15cd1d8">BranchPCRel32ToPtrJumpStubBypassable</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a5e468cc52cc2a56b6aadd5c67fac81b7">Delta32</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a4733cbd257ce44d81ff8e234dd9c3ca0">Delta32FromGOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a54fe5e0c95650c41d0257689b94d8786">None</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a9461d47b61aeb45c0ae578c1f47257d5">PCRel16</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a47d10bc81ee8242157fe8e01b342b73a">PCRel32</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ae9aae291a294099fd9442fbab0b4d1b0">Pointer16</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ad4dd07c25270ad41112bab2f6144e5b8">Pointer32</a> and <a href="#ab5b12c7ab25aac492521ed299ab357d4aa8133be772984451fd00483f26395c24">RequestGOTAndTransformToDelta32FromGOT</a>.</p>


<p>Referenced by <a href="#a1cf84875ae743236d8dd98fd56af9f7b">applyFixup</a> and <a href="#a877b3d728be6b7084aef27f92242f8bf">optimizeGOTAndStubAccesses</a>.</p>

</div>
</div>

### optimizeGOTAndStubAccesses() {#a877b3d728be6b7084aef27f92242f8bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::i386::optimizeGOTAndStubAccesses (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimize the GOT and Stub relocations if the edge target address is in range.</p>


<ol class="doxyList" type="1">
<li>PCRel32GOTLoadRelaxable. For this edge kind, if the target is in range, then replace GOT load with lea. (THIS IS UNIMPLEMENTED RIGHT NOW!)</li>
<li>BranchPCRel32ToPtrJumpStubRelaxable. For this edge kind, if the target is in range, replace a indirect jump by plt stub with a direct jump to the target</li>
</ol>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/i386-cpp">i386.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4ab909c856e2b968674b459c652db52d21">BranchPCRel32</a>, <a href="#ab5b12c7ab25aac492521ed299ab357d4a032d3ec55a73bf3dd3dde3c7c15cd1d8">BranchPCRel32ToPtrJumpStubBypassable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#af34d9ccf9d307a0f17db132d098383ec">getEdgeKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="#aa9431605d4e7f6a9d3296938180284ea">PointerJumpStubContent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad21474fff99853c3d22abfe6634ee9ed">llvm::jitlink::printEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-i386/#a66686ad596abff4d3e45943c0bee6bc0">llvm::jitlink::ELFJITLinker_i386::JITLinker&lt; ELFJITLinker_i386 &gt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### NullPointerContent {#abbd7edaafeb4fa06c154ac15f86d7ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::i386::NullPointerContent = {0x00, 0x00, 0x00, 0x00}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> null pointer content.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/i386-cpp">i386.cpp</a>.</p>


<p>Referenced by <a href="#ac007f2f0fe33b64e019817ec931a4b79">createAnonymousPointer</a>.</p>

</div>
</div>

### PointerJumpStubContent {#aa9431605d4e7f6a9d3296938180284ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char llvm::jitlink::i386::PointerJumpStubContent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> pointer jump stub content.</p>

<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    static_cast&lt;char&gt;(0xFFu), 0x25, 0x00, 0x00, 0x00, 0x00}
</div>
</dd>
</dl>


<p>Contains the instruction sequence for an indirect jump via an in-memory pointer: jmpq *ptr</p>


<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/i386-cpp">i386.cpp</a>.</p>


<p>Referenced by <a href="#a10c6b85409593a97182da9d8018eb8b2">createPointerJumpStubBlock</a> and <a href="#a877b3d728be6b7084aef27f92242f8bf">optimizeGOTAndStubAccesses</a>.</p>

</div>
</div>

### PointerSize {#a60a470b8f4a62ef8353485a3570d0591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::jitlink::i386::PointerSize = 4</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/i386">i386</a> pointer size.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/i386-h">i386.h</a>.</p>


<p>Referenced by <a href="#ac007f2f0fe33b64e019817ec931a4b79">createAnonymousPointer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/i386-h">i386.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/i386-cpp">i386.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
