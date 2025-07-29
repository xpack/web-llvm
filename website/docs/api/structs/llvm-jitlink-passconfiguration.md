---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/jitlink/passconfiguration
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `PassConfiguration` Struct

<p>An <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> pass configuration, consisting of a list of pre-prune, post-prune, and post-fixup passes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::jitlink::PassConfiguration { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">llvm/ExecutionEngine/JITLink/JITLink.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ada9aea1e107a797952d4106abd7e24fd">LinkGraphPassList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40c7648b8ad38b6d942e7194a4faa34">PrePrunePasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pre-prune passes. <a href="#ad40c7648b8ad38b6d942e7194a4faa34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ada9aea1e107a797952d4106abd7e24fd">LinkGraphPassList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2b6c33f0953b534738fb8d0a02e526d">PostPrunePasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Post-prune passes. <a href="#ac2b6c33f0953b534738fb8d0a02e526d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ada9aea1e107a797952d4106abd7e24fd">LinkGraphPassList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084adb14a6ed485ceafa7aeb5ddcdba9">PostAllocationPasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Post-allocation passes. <a href="#a084adb14a6ed485ceafa7aeb5ddcdba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ada9aea1e107a797952d4106abd7e24fd">LinkGraphPassList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37decb1a4d14127fabb251c498274d0b">PreFixupPasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pre-fixup passes. <a href="#a37decb1a4d14127fabb251c498274d0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ada9aea1e107a797952d4106abd7e24fd">LinkGraphPassList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a617bac95c4003dd176fa5cc119d2a919">PostFixupPasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Post-fixup passes. <a href="#a617bac95c4003dd176fa5cc119d2a919">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> pass configuration, consisting of a list of pre-prune, post-prune, and post-fixup passes.</p>

<p>Definition at line 1837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### PostAllocationPasses {#a084adb14a6ed485ceafa7aeb5ddcdba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphPassList llvm::jitlink::PassConfiguration::PostAllocationPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Post-allocation passes.</p>


<p>These passes are called on the graph after memory has been allocated and defined nodes have been assigned their final addresses, but before the context has been notified of these addresses. At this point externals have not been resolved, and symbol content has not yet been copied into working memory.</p>


<p>Notable use cases: Setting up data structures associated with addresses of defined symbols (e.g. a mapping of __dso_handle to JITDylib* for the JIT runtime) – using a PostAllocationPass for this ensures that the data structures are in-place before any query for resolved symbols can complete.</p>


<p>Definition at line 1868 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-i386/#a89ccec03f7c3d843efe42e81cc624c5a">llvm::jitlink::ELFJITLinker_i386::ELFJITLinker_i386</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-ppc64/#a381a272783a32fb51026f1792c884697">llvm::jitlink::ELFJITLinker_ppc64&lt; Endianness &gt;::ELFJITLinker_ppc64</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-riscv/#ae78abd990dbac43add7a09ff8bfe790c">llvm::jitlink::ELFJITLinker_riscv::ELFJITLinker_riscv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aa76aa840b0de153c5d9412db29f03e69">llvm::jitlink::link_ELF_aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae77f6c59e9c3e12b35c23a9202d9613a">llvm::jitlink::link_ELF_loongarch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#acfaec788ed9ebbc0ffe5b591c3d3e5f6">llvm::jitlink::link_ELF_riscv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae07f62502c521dbfc05720327b722c17">llvm::jitlink::link_ELF_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a3a5a64d0c1b7bad36afd4b742f3069db">llvm::jitlink::link_MachO_arm64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a8fe40b19af9c9f98b39e9c2f954e8d54">llvm::jitlink::link_MachO_x86_64</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/debugobjectmanagerplugin/#abf15a05cfd44aa92db5db5251a6f3631">llvm::orc::DebugObjectManagerPlugin::modifyPassConfig</a>.</p>

</div>
</div>

### PostFixupPasses {#a617bac95c4003dd176fa5cc119d2a919}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphPassList llvm::jitlink::PassConfiguration::PostFixupPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Post-fixup passes.</p>


<p>These passes are called on the graph after block contents has been copied to working memory, and fixups applied. Blocks have been updated to point to their fixed up content.</p>


<p>Notable use cases: Testing and validation.</p>


<p>Definition at line 1888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/ehframeregistrationplugin/#af93ceaebd60183ac320cd5927e2e3f81">llvm::orc::EHFrameRegistrationPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/perfsupportplugin/#a0b1cb2049314feb0a29760c548a604af">llvm::orc::PerfSupportPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/unwindinforegistrationplugin/#a00894cd95a0b87bee863081cfcd769aa">llvm::orc::UnwindInfoRegistrationPlugin::modifyPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/vtunesupportplugin/#a853290f0b4ae904b8ab68e6a06f8bab9">llvm::orc::VTuneSupportPlugin::modifyPassConfig</a>.</p>

</div>
</div>

### PostPrunePasses {#ac2b6c33f0953b534738fb8d0a02e526d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphPassList llvm::jitlink::PassConfiguration::PostPrunePasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Post-prune passes.</p>


<p>These passes are called on the graph after dead stripping, but before memory is allocated or nodes assigned their final addresses.</p>


<p>Notable use cases: Building GOT, stub, and TLV symbols.</p>


<p>Definition at line 1853 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-aarch32/#ae10dd491f32961b12c311a3b6de481fd">llvm::jitlink::ELFJITLinker_aarch32::JITLinker&lt; ELFJITLinker_aarch32 &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-i386/#a66686ad596abff4d3e45943c0bee6bc0">llvm::jitlink::ELFJITLinker_i386::JITLinker&lt; ELFJITLinker_i386 &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aa76aa840b0de153c5d9412db29f03e69">llvm::jitlink::link_ELF_aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae77f6c59e9c3e12b35c23a9202d9613a">llvm::jitlink::link_ELF_loongarch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a91410c9b2742990f02d5521fb6883156">llvm::jitlink::link_ELF_ppc64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#acfaec788ed9ebbc0ffe5b591c3d3e5f6">llvm::jitlink::link_ELF_riscv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae07f62502c521dbfc05720327b722c17">llvm::jitlink::link_ELF_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a3a5a64d0c1b7bad36afd4b742f3069db">llvm::jitlink::link_MachO_arm64</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a8fe40b19af9c9f98b39e9c2f954e8d54">llvm::jitlink::link_MachO_x86_64</a>.</p>

</div>
</div>

### PreFixupPasses {#a37decb1a4d14127fabb251c498274d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphPassList llvm::jitlink::PassConfiguration::PreFixupPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pre-fixup passes.</p>


<p>These passes are called on the graph after memory has been allocated, content copied into working memory, and all nodes (including externals) have been assigned their final addresses, but before any fixups have been applied.</p>


<p>Notable use cases: Late link-time optimizations like GOT and stub elimination.</p>


<p>Definition at line 1879 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-i386/#a66686ad596abff4d3e45943c0bee6bc0">llvm::jitlink::ELFJITLinker_i386::JITLinker&lt; ELFJITLinker_i386 &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad3400a6a692640ced07b8263331d8ca">llvm::jitlink::link_COFF_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae07f62502c521dbfc05720327b722c17">llvm::jitlink::link_ELF_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a3a5a64d0c1b7bad36afd4b742f3069db">llvm::jitlink::link_MachO_arm64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a8fe40b19af9c9f98b39e9c2f954e8d54">llvm::jitlink::link_MachO_x86_64</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/jitlinkreentrytrampolines/trampolineaddrscraperplugin/#ad103d53970f47b6c58ae7d48e00d1800">llvm::orc::JITLinkReentryTrampolines::TrampolineAddrScraperPlugin::modifyPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#a9244565368ee4c5e1c2666b63b6af76d">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::modifyPassConfig</a>.</p>

</div>
</div>

### PrePrunePasses {#ad40c7648b8ad38b6d942e7194a4faa34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkGraphPassList llvm::jitlink::PassConfiguration::PrePrunePasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pre-prune passes.</p>


<p>These passes are called on the graph after it is built, and before any symbols have been pruned. Graph nodes still have their original vmaddrs.</p>


<p>Notable use cases: Marking symbols live or should-discard.</p>


<p>Definition at line 1845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-aarch32/#ae10dd491f32961b12c311a3b6de481fd">llvm::jitlink::ELFJITLinker_aarch32::JITLinker&lt; ELFJITLinker_aarch32 &gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-i386/#a66686ad596abff4d3e45943c0bee6bc0">llvm::jitlink::ELFJITLinker_i386::JITLinker&lt; ELFJITLinker_i386 &gt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aad3400a6a692640ced07b8263331d8ca">llvm::jitlink::link_COFF_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#aa76aa840b0de153c5d9412db29f03e69">llvm::jitlink::link_ELF_aarch64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae77f6c59e9c3e12b35c23a9202d9613a">llvm::jitlink::link_ELF_loongarch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a91410c9b2742990f02d5521fb6883156">llvm::jitlink::link_ELF_ppc64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#acfaec788ed9ebbc0ffe5b591c3d3e5f6">llvm::jitlink::link_ELF_riscv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#ae07f62502c521dbfc05720327b722c17">llvm::jitlink::link_ELF_x86_64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a3a5a64d0c1b7bad36afd4b742f3069db">llvm::jitlink::link_MachO_arm64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a8fe40b19af9c9f98b39e9c2f954e8d54">llvm::jitlink::link_MachO_x86_64</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/debuginfopreservationplugin/#a4036e2d6e91b32eb77659cbdcc188218">llvm::orc::DebugInfoPreservationPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/ehframeregistrationplugin/#af93ceaebd60183ac320cd5927e2e3f81">llvm::orc::EHFrameRegistrationPlugin::modifyPassConfig</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/lazyobjectlinkinglayer/renamerplugin/#a3d67341ddf37cf397a977f8bca83d982">llvm::orc::LazyObjectLinkingLayer::RenamerPlugin::modifyPassConfig</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/linkgraphlinkinglayer/jitlinkctx/#a9244565368ee4c5e1c2666b63b6af76d">llvm::orc::LinkGraphLinkingLayer::JITLinkCtx::modifyPassConfig</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/jitlink-h">JITLink.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
