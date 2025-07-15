---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/elfjitlinker-aarch32
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ELFJITLinker_aarch32` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::jitlink::ELFJITLinker_aarch32 { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae10dd491f32961b12c311a3b6de481fd">JITLinker&lt; ELFJITLinker_aarch32 &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd0a9d8622cf69a434c79589fae3df53">ELFJITLinker_aarch32</a> (std::unique_ptr&lt; JITLinkContext &gt; Ctx, std::unique_ptr&lt; LinkGraph &gt; G, PassConfiguration PassCfg, aarch32::ArmConfig ArmCfg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f5b5f00433ca8e43b2595b639969d04">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">aarch32::ArmConfig</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4ee3320f2c62c9b078ca7c3b018d5d1">ArmCfg</a></td>
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


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### JITLinker&lt; ELFJITLinker\_aarch32 &gt; {#ae10dd491f32961b12c311a3b6de481fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinker">JITLinker</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-aarch32">ELFJITLinker_aarch32</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ad1f844075d800fea3b14f40b2bb5715e">llvm::jitlink::buildTables_ELF_aarch32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#acef653952013bd12b49c929eb1602a5e">llvm::ARM::getArchAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a3a95b507182908470f226c73349e0f15">llvm::jitlink::aarch32::getArmConfigForCPUArch</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinker/#a2323e0b7c36bea00e99fd1675b889970">llvm::jitlink::JITLinker&lt; ELFJITLinker_aarch32 &gt;::link</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a865b5baa2754c1ddeb497d1d2cbfbbe3">llvm::jitlink::markAllSymbolsLive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arm/#a75e18d4bc8fef7e89c1222c6b6cf8638">llvm::ARM::parseArch</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration/#ac2b6c33f0953b534738fb8d0a02e526d">llvm::jitlink::PassConfiguration::PostPrunePasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a66abed31cc3dfac01c8ed560eb6db1c5a25f05cdee23677d484144bcb0c438613">llvm::jitlink::aarch32::pre_v7</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration/#ad40c7648b8ad38b6d942e7194a4faa34">llvm::jitlink::PassConfiguration::PrePrunePasses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a66abed31cc3dfac01c8ed560eb6db1c5aec0fc0100c4fc1ce4eea230c3dc10360">llvm::jitlink::aarch32::Undefined</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a66abed31cc3dfac01c8ed560eb6db1c5ae6dd71377633723164aeea0750ddafa8">llvm::jitlink::aarch32::v7</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ELFJITLinker\_aarch32() {#afd0a9d8622cf69a434c79589fae3df53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::ELFJITLinker_aarch32::ELFJITLinker_aarch32 (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/jitlinkcontext">JITLinkContext</a> &gt; Ctx, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &gt; G, <a href="/web-llvm/docs/api/structs/llvm/jitlink/passconfiguration">PassConfiguration</a> PassCfg, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">aarch32::ArmConfig</a> ArmCfg)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### applyFixup() {#a5f5b5f00433ca8e43b2595b639969d04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFJITLinker_aarch32::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArmCfg {#aa4ee3320f2c62c9b078ca7c3b018d5d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">aarch32::ArmConfig llvm::jitlink::ELFJITLinker_aarch32::ArmCfg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
