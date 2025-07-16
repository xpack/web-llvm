---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/machojitlinker-x86-64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachOJITLinker_x86_64` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::MachOJITLinker_x86_64 { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101116d137e537d1396ce74e4cb3ca6d">JITLinker&lt; MachOJITLinker_x86_64 &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab20914727cb602e63f2b18793ba78cda">MachOJITLinker_x86_64</a> (std::unique_ptr&lt; JITLinkContext &gt; Ctx, std::unique_ptr&lt; LinkGraph &gt; G, PassConfiguration PassConfig)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3067dde9d9a69d7fa428037bb1dbac0">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E) const</td>
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


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### JITLinker&lt; MachOJITLinker\_x86\_64 &gt; {#a101116d137e537d1396ce74e4cb3ca6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinker">JITLinker</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/machojitlinker-x86-64">MachOJITLinker_x86_64</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1ae8b3d9d60bcce88f74377f0b3a845a3c">llvm::jitlink::x86_64::Delta32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1a0813e2e217bec0a3795f7e0bf463bbdc">llvm::jitlink::x86_64::Delta64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a5985f13193937fb309c4a8c6bbc37389">llvm::orc::MachOEHFrameSectionName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1abd3d0bdbcb54e70a617ffa080e3befee">llvm::jitlink::x86_64::NegDelta32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1a12f965819db53282535bd5766d5783e3">llvm::jitlink::x86_64::Pointer32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4">llvm::jitlink::x86_64::Pointer64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#a73a3b0ce55e5217546f5140e284e5ae3">llvm::jitlink::x86_64::PointerSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachOJITLinker\_x86\_64() {#ab20914727cb602e63f2b18793ba78cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::MachOJITLinker_x86_64::MachOJITLinker_x86_64 (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a> &gt; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &gt; G, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">PassConfiguration</a> PassConfig)</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyFixup() {#ae3067dde9d9a69d7fa428037bb1dbac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::MachOJITLinker_x86_64::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
