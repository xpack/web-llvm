---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/machojitlinker-arm64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachOJITLinker_arm64` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::MachOJITLinker_arm64 { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinker">JITLinker&lt;LinkerImpl&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113f10ffe5b6be0ae401eaad984c4a4a">JITLinker&lt; MachOJITLinker_arm64 &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6574ee9b7d18397fec26d981978795a7">MachOJITLinker_arm64</a> (std::unique_ptr&lt; JITLinkContext &gt; Ctx, std::unique_ptr&lt; LinkGraph &gt; G, PassConfiguration PassConfig)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39535ff80d1e9de72f6204827a5c2208">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac104397d212ec3cbc42f5dbb028c53a7">NullValue</a> = 0</td>
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


<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### JITLinker&lt; MachOJITLinker\_arm64 &gt; {#a113f10ffe5b6be0ae401eaad984c4a4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinker">JITLinker</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/machojitlinker-arm64">MachOJITLinker_arm64</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a8d7dc75674b3fc58ba929cbef0217e4b">llvm::jitlink::aarch64::Delta32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043aa43de9079a03e5cf7ea9c96de2956a47">llvm::jitlink::aarch64::Delta64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a5985f13193937fb309c4a8c6bbc37389">llvm::orc::MachOEHFrameSectionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043ade36f74cb3bddd6f86b25f96238033c3">llvm::jitlink::aarch64::NegDelta32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043aad97367a7201c67ade1c6d15c96f0746">llvm::jitlink::aarch64::Pointer32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#adaafb311352b6b70437034d62373d043a9f6ab8a0d2f19948762b78f6d6c5f562">llvm::jitlink::aarch64::Pointer64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64/#a54a878e42755b4a0e4cc8709f3f34e51">llvm::jitlink::aarch64::PointerSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachOJITLinker\_arm64() {#a6574ee9b7d18397fec26d981978795a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::MachOJITLinker_arm64::MachOJITLinker_arm64 (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a> &gt; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &gt; G, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">PassConfiguration</a> PassConfig)</td>
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



<p>Definition at line 573 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyFixup() {#a39535ff80d1e9de72f6204827a5c2208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::MachOJITLinker_arm64::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NullValue {#ac104397d212ec3cbc42f5dbb028c53a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::jitlink::MachOJITLinker_arm64::NullValue = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
