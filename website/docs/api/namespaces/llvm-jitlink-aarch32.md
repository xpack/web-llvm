---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/jitlink/aarch32
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `aarch32` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::jitlink::aarch32 { ... }
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/anonymous-aarch32-cpp-">anonymous{aarch32.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">ArmConfig</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>JITLink sub-arch configuration for Arm CPU models. <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Immutable pair of halfwords, Hi and Lo, with overflow check. <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfobase">FixupInfoBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo">FixupInfo</a> base class is required for dynamic lookups. <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfobase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfoarm">FixupInfoArm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo">FixupInfo</a> checks for Arm edge kinds work on 32-bit words. <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfoarm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfothumb">FixupInfoThumb</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo">FixupInfo</a> check for Thumb32 edge kinds work on a pair of 16-bit halfwords. <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfothumb/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo">FixupInfo&lt;Kind&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of named constants per fixup kind. <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfoarmbranch">FixupInfoArmBranch</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-4ede2b2b13760fe01d9ab911db9e8e2a">FixupInfo&lt;Arm_Jump24&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-3c3ba108eb25a804f3bb9d9eebac3bac">FixupInfo&lt;Arm_Call&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfoarmmov">FixupInfoArmMov</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-3a6705bc840d064de98ad200d95bcb8b">FixupInfo&lt;Arm_MovtAbs&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-4e1bcbac93acb3f8797a1fd92d12a7cb">FixupInfo&lt;Arm_MovwAbsNC&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-a20f68bd6c62806361a34699d69c87a2">FixupInfo&lt;Thumb_Jump24&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-a0b432e423892a018e58d4a602de1ef4">FixupInfo&lt;Thumb_Call&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfothumbmov">FixupInfoThumbMov</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-436663fca231f9db2863034e4eca8a01">FixupInfo&lt;Thumb_MovtAbs&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-63053542217302bb8db5cee7f728fd34">FixupInfo&lt;Thumb_MovtPrel&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-5a6b1d59f8d93593fffcbf9960e25895">FixupInfo&lt;Thumb_MovwAbsNC&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/fixupinfo-fc2feadb4f0b58f79a8d8e7b22e3ce7f">FixupInfo&lt;Thumb_MovwPrelNC&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/gotbuilder">GOTBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate a Global Offset Table from edges that request it. <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/gotbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-prev7">StubsManager_prev7</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stubs builder emits non-position-independent Arm stubs for pre-v7 CPUs. <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-prev7/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7">StubsManager_v7</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stubs builder for v7 emits non-position-independent Arm and Thumb stubs. <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeKind_aarch32 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> { <a href="#a1093624056b8864b4f523672eb1ab152">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>JITLink-internal AArch32 fixup kinds. <a href="#a1093624056b8864b4f523672eb1ab152">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TargetFlags_aarch32 : <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a> { <a href="#a8de4fa84b421de4e842bb78158a8ba4c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flags enum for AArch32-specific symbol properties. <a href="#a8de4fa84b421de4e842bb78158a8ba4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">StubsFlavor { <a href="#a66abed31cc3dfac01c8ed560eb6db1c5">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AArch32 uses stubs for a number of purposes, like branch range extension or interworking between Arm and Thumb instruction subsets. <a href="#a66abed31cc3dfac01c8ed560eb6db1c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6521de2d14ab48fafe3427e34a1e0405">hasTargetFlags</a> (Symbol &amp;Sym, TargetFlagsType Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given target flags are set for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>. <a href="#a6521de2d14ab48fafe3427e34a1e0405">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40551e1cf4261bded983399e19d7c565">getCPUArchName</a> (ARMBuildAttrs::CPUArch K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Human-readable name for a given CPU architecture kind. <a href="#a40551e1cf4261bded983399e19d7c565">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a604cf2e8a88455df3f053891be27be1b">getEdgeKindName</a> (Edge::Kind K)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a human-readable name for the given AArch32 edge kind. <a href="#a604cf2e8a88455df3f053891be27be1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">ArmConfig</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a95b507182908470f226c73349e0f15">getArmConfigForCPUArch</a> (ARMBuildAttrs::CPUArch CPUArch)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the sub-arch configuration for a given Arm CPU model. <a href="#a3a95b507182908470f226c73349e0f15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350d2681d6fabc606cb82e4ac365af9e">readAddendData</a> (LinkGraph &amp;G, Block &amp;B, Edge::OffsetT Offset, Edge::Kind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to read the initial addend for Data-class relocations. <a href="#a350d2681d6fabc606cb82e4ac365af9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa8cac7ba958e4a67c048331418a516f">readAddendArm</a> (LinkGraph &amp;G, Block &amp;B, Edge::OffsetT Offset, Edge::Kind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to read the initial addend for Arm-class relocations. <a href="#afa8cac7ba958e4a67c048331418a516f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6cf2c07bc856d1cb198de49c5523317">readAddendThumb</a> (LinkGraph &amp;G, Block &amp;B, Edge::OffsetT Offset, Edge::Kind Kind, const ArmConfig &amp;ArmCfg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to read the initial addend for Thumb-class relocations. <a href="#aa6cf2c07bc856d1cb198de49c5523317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; int64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f3b584ce0c2c4c0b4a627001d3ddf0">readAddend</a> (LinkGraph &amp;G, Block &amp;B, Edge::OffsetT Offset, Edge::Kind Kind, const ArmConfig &amp;ArmCfg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read the initial addend for a REL-type relocation. <a href="#a74f3b584ce0c2c4c0b4a627001d3ddf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc2e3fa12d8c5d0d37310647c9c3a4d">applyFixupData</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to apply the fixup for Data-class relocations. <a href="#a2cc2e3fa12d8c5d0d37310647c9c3a4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f135c84cfb135c8e3f890659a3f782">applyFixupArm</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to apply the fixup for Arm-class relocations. <a href="#a53f135c84cfb135c8e3f890659a3f782">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E, const ArmConfig &amp;ArmCfg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to apply the fixup for Thumb-class relocations. <a href="#a183363f7e8482b2c1e193956dea835ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227cdc692d0608ba443b1ad47e97e3e9">applyFixup</a> (LinkGraph &amp;G, Block &amp;B, const Edge &amp;E, const ArmConfig &amp;ArmCfg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply fixup expression for edge to block content. <a href="#a227cdc692d0608ba443b1ad47e97e3e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a352a75cb7a967bd415f8197171bcefc7">encodeImmBT4BlT1BlxT2</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode 22-bit immediate value for branch instructions without J1J2 range extension (formats B T4, BL T1 and BLX T2). <a href="#a352a75cb7a967bd415f8197171bcefc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ab42b95c481a2753758150c45022721">decodeImmBT4BlT1BlxT2</a> (uint32_t Hi, uint32_t Lo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode 22-bit immediate value for branch instructions without J1J2 range extension (formats B T4, BL T1 and BLX T2). <a href="#a1ab42b95c481a2753758150c45022721">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95780a3ac905657cdb0e5293c339ea50">encodeImmBT4BlT1BlxT2_J1J2</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode 25-bit immediate value for branch instructions with J1J2 range extension (formats B T4, BL T1 and BLX T2). <a href="#a95780a3ac905657cdb0e5293c339ea50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac29adb89b5f4baf10f136125eca43dd4">decodeImmBT4BlT1BlxT2_J1J2</a> (uint32_t Hi, uint32_t Lo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode 25-bit immediate value for branch instructions with J1J2 range extension (formats B T4, BL T1 and BLX T2). <a href="#ac29adb89b5f4baf10f136125eca43dd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454b552102bd4227eeb09e2d7c8db4a6">encodeImmBA1BlA1BlxA2</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode 26-bit immediate value for branch instructions (formats B A1, BL A1 and BLX A2). <a href="#a454b552102bd4227eeb09e2d7c8db4a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ee1f37691782bcfd16bc0ee1079272">decodeImmBA1BlA1BlxA2</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode 26-bit immediate value for branch instructions (formats B A1, BL A1 and BLX A2). <a href="#aa2ee1f37691782bcfd16bc0ee1079272">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a556a0d636ccdd8571f07d2a3cfab2dab">encodeImmMovtT1MovwT3</a> (uint16_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode 16-bit immediate value for move instruction formats MOVT T1 and MOVW T3. <a href="#a556a0d636ccdd8571f07d2a3cfab2dab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4362f40f8685bc3dd96872524615589a">decodeImmMovtT1MovwT3</a> (uint32_t Hi, uint32_t Lo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode 16-bit immediate value from move instruction formats MOVT T1 and MOVW T3. <a href="#a4362f40f8685bc3dd96872524615589a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26d693d81bb31f9af0d741788732f560">encodeRegMovtT1MovwT3</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for instruction formats MOVT T1 and MOVW T3. <a href="#a26d693d81bb31f9af0d741788732f560">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d8308e06367ebd45fd689971fa13fa9">decodeRegMovtT1MovwT3</a> (uint32_t Hi, uint32_t Lo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> from instruction formats MOVT T1 and MOVW T3. <a href="#a3d8308e06367ebd45fd689971fa13fa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a504c290392fc31205e292094b032c8f6">encodeImmMovtA1MovwA2</a> (uint16_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode 16-bit immediate value for move instruction formats MOVT A1 and MOVW A2. <a href="#a504c290392fc31205e292094b032c8f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8745c0e342c94d550c2b871d1fabe79d">decodeImmMovtA1MovwA2</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode 16-bit immediate value for move instruction formats MOVT A1 and MOVW A2. <a href="#a8745c0e342c94d550c2b871d1fabe79d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a347be6c2f2f8dad96abde951f0475a82">encodeRegMovtA1MovwA2</a> (int64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for instruction formats MOVT A1 and MOVW A2. <a href="#a347be6c2f2f8dad96abde951f0475a82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a612abdb994ba160e64598fc32e7ce26c">decodeRegMovtA1MovwA2</a> (uint64_t Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for instruction formats MOVT A1 and MOVW A2. <a href="#a612abdb994ba160e64598fc32e7ce26c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c7b359f8ba0aa2c37bb009808262df7">checkOpcode</a> (LinkGraph &amp;G, const ArmRelocation &amp;R, Edge::Kind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab081d8136bcb37bb0c6ab56a2714e308">checkOpcode</a> (LinkGraph &amp;G, const ThumbRelocation &amp;R, Edge::Kind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;EdgeKind_aarch32 Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab99fc0d5b2464663274f43ac29b12fd8">checkRegister</a> (const ThumbRelocation &amp;R, HalfWords Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;EdgeKind_aarch32 Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9b158c8be77ccffdf26833564b4f37f">checkRegister</a> (const ArmRelocation &amp;R, uint32_t Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;EdgeKind_aarch32 Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aaf50e0db42fa045e5c4161db69e98909">writeRegister</a> (WritableThumbRelocation &amp;R, HalfWords Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;EdgeKind_aarch32 Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d01c43e1d39cbe97b1c68d7e7c9fd35">writeRegister</a> (WritableArmRelocation &amp;R, uint32_t Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;EdgeKind_aarch32 Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae2292a4926037c9388d1c7a6eb5ea4d8">writeImmediate</a> (WritableThumbRelocation &amp;R, HalfWords Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;EdgeKind_aarch32 Kind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa35c7cb2b60e763112b40776ea9da9fc">writeImmediate</a> (WritableArmRelocation &amp;R, uint32_t Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t Size&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1c4e23621c8e46179f0fda5fc58b25c">allocPointer</a> (LinkGraph &amp;G, Section &amp;S, const uint8_t(&amp;Content)[Size])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new node in the link-graph for the given pointer value. <a href="#ad1c4e23621c8e46179f0fda5fc58b25c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;size_t Size&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a1ac23b74c74606a067297342490175">allocStub</a> (LinkGraph &amp;G, Section &amp;S, const uint8_t(&amp;Code)[Size])</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new node in the link-graph for the given stub template. <a href="#a7a1ac23b74c74606a067297342490175">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd85f4e10561495360d365f1bb6998dd">createStubPrev7</a> (LinkGraph &amp;G, Section &amp;S, Symbol &amp;Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a126e987204a06be667510edc866c3ea3">createStubThumbv7</a> (LinkGraph &amp;G, Section &amp;S, Symbol &amp;Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee0cc87627899fe951c9c8b7df170581">createStubArmv7</a> (LinkGraph &amp;G, Section &amp;S, Symbol &amp;Target)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2e126eb4caf72f59bf457da35c2005">needsStub</a> (const Edge &amp;E)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b1bde175fefd62202245e6271531006">GOTEntryInit</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528310c414bab7f3c95868b8a577d5d5">ArmThumbv5LdrPc</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa889d0367475b8ac2ace8b25b4e3a01">Armv7ABS</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885ac6c83ea16876a59df278f401d8dd">Thumbv7ABS</a>[] = ...</td>
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


<div class="doxySectionDef">

## Enumerations

### EdgeKind\_aarch32 {#a1093624056b8864b4f523672eb1ab152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::aarch32::EdgeKind_aarch32 : <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>JITLink-internal AArch32 fixup kinds.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstDataRelocation<a id="a1093624056b8864b4f523672eb1ab152aa207e0f66dfc30680ae41c5bbed8addb"></a></td>
<td class="doxyEnumItemDescription">Relocations of class Data respect target endianness (unless otherwise specified) (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Data_Delta32<a id="a1093624056b8864b4f523672eb1ab152ad1c4cc46fc74c040840a716668e13d55"></a></td>
<td class="doxyEnumItemDescription">Relative 32-bit value relocation (= FirstDataRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Data_Pointer32<a id="a1093624056b8864b4f523672eb1ab152a55c730148655277aa00b358e1eea1a9f"></a></td>
<td class="doxyEnumItemDescription">Absolute 32-bit value relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Data_PRel31<a id="a1093624056b8864b4f523672eb1ab152a5314af3f0742328c3d3e544e93415eee"></a></td>
<td class="doxyEnumItemDescription">Relative 31-bit value relocation that preserves the most-significant bit</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Data_RequestGOTAndTransformToDelta32<a id="a1093624056b8864b4f523672eb1ab152a154b0cafd77d1e3901c4fc6c2c602170"></a></td>
<td class="doxyEnumItemDescription">Create GOT entry and store offset</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastDataRelocation<a id="a1093624056b8864b4f523672eb1ab152a506908472f2bf50bc850d5d7b0329980"></a></td>
<td class="doxyEnumItemDescription"> (= Data_RequestGOTAndTransformToDelta32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstArmRelocation<a id="a1093624056b8864b4f523672eb1ab152acf92897f458625c1a5b927b2f00a610a"></a></td>
<td class="doxyEnumItemDescription">Relocations of class Arm (covers fixed-width 4-byte instruction subset)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Arm_Call<a id="a1093624056b8864b4f523672eb1ab152a8d257c062342dd6bddf5981b75a5b94f"></a></td>
<td class="doxyEnumItemDescription">Write immediate value for unconditional PC-relative branch with link (= FirstArmRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Arm_Jump24<a id="a1093624056b8864b4f523672eb1ab152ac91bb9bdd0b8d9d880e9c04f9af68da6"></a></td>
<td class="doxyEnumItemDescription">Write immediate value for conditional PC-relative branch without link</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Arm_MovwAbsNC<a id="a1093624056b8864b4f523672eb1ab152a77606cf82be61cc51fe6138a366275fd"></a></td>
<td class="doxyEnumItemDescription">Write immediate value to the lower halfword of the destination register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Arm_MovtAbs<a id="a1093624056b8864b4f523672eb1ab152a2d91f98fa8c8184510edb38bb3aaf7ba"></a></td>
<td class="doxyEnumItemDescription">Write immediate value to the top halfword of the destination register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastArmRelocation<a id="a1093624056b8864b4f523672eb1ab152a659d7e0b7695e33e47d072ac4aa0e97f"></a></td>
<td class="doxyEnumItemDescription"> (= Arm_MovtAbs)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FirstThumbRelocation<a id="a1093624056b8864b4f523672eb1ab152a5e6fcdc070a58fa9534181b9cf59f276"></a></td>
<td class="doxyEnumItemDescription">Relocations of class Thumb16 and Thumb32 (covers Thumb instruction subset)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Thumb_Call<a id="a1093624056b8864b4f523672eb1ab152ad44531ef9da0d0d1c38a4a3de03fd319"></a></td>
<td class="doxyEnumItemDescription">Write immediate value for unconditional PC-relative branch with link (= FirstThumbRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Thumb_Jump24<a id="a1093624056b8864b4f523672eb1ab152abf28fabfe322c11a4ae205087cb0222b"></a></td>
<td class="doxyEnumItemDescription">Write immediate value for PC-relative branch without link</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Thumb_MovwAbsNC<a id="a1093624056b8864b4f523672eb1ab152ac92c861c872461a89de51864c1721a57"></a></td>
<td class="doxyEnumItemDescription">Write immediate value to the lower halfword of the destination register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Thumb_MovtAbs<a id="a1093624056b8864b4f523672eb1ab152aedcc1fec15a76e4fbc06fb7db2d611ef"></a></td>
<td class="doxyEnumItemDescription">Write immediate value to the top halfword of the destination register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Thumb_MovwPrelNC<a id="a1093624056b8864b4f523672eb1ab152af60cee5b702f67960e413ca40d17c969"></a></td>
<td class="doxyEnumItemDescription">Write PC-relative immediate value to the lower halfword of the destination register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Thumb_MovtPrel<a id="a1093624056b8864b4f523672eb1ab152aa1a6fb356ad039e90d784aa4365560e5"></a></td>
<td class="doxyEnumItemDescription">Write PC-relative immediate value to the top halfword of the destination register</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastThumbRelocation<a id="a1093624056b8864b4f523672eb1ab152a60c957fb9ecd147dc3bf7b95d5c02d64"></a></td>
<td class="doxyEnumItemDescription"> (= Thumb_MovtPrel)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a1093624056b8864b4f523672eb1ab152ad72fb3d678aadcd83466b4820749007d"></a></td>
<td class="doxyEnumItemDescription">No-op relocation</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastRelocation<a id="a1093624056b8864b4f523672eb1ab152a0f1903da727148493e86e159865cb17a"></a></td>
<td class="doxyEnumItemDescription"> (= None)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>

</div>
</div>

### StubsFlavor {#a66abed31cc3dfac01c8ed560eb6db1c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::jitlink::aarch32::StubsFlavor </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AArch32 uses stubs for a number of purposes, like branch range extension or interworking between Arm and Thumb instruction subsets.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Undefined<a id="a66abed31cc3dfac01c8ed560eb6db1c5aec0fc0100c4fc1ce4eea230c3dc10360"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">pre_v7<a id="a66abed31cc3dfac01c8ed560eb6db1c5a25f05cdee23677d484144bcb0c438613"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">v7<a id="a66abed31cc3dfac01c8ed560eb6db1c5ae6dd71377633723164aeea0750ddafa8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>


<p>Stub implementations vary depending on CPU architecture (v4, v6, v7), instruction subset and branch type (absolute/PC-relative).</p>


<p>For each kind of stub, the <a href="#a66abed31cc3dfac01c8ed560eb6db1c5">StubsFlavor</a> defines one concrete form that is used throughout the <a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a>.</p>


<p>Stubs are often called "veneers" in the official docs and online.</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>

</div>
</div>

### TargetFlags\_aarch32 {#a8de4fa84b421de4e842bb78158a8ba4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::jitlink::aarch32::TargetFlags_aarch32 : <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flags enum for AArch32-specific symbol properties.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ThumbSymbol<a id="a8de4fa84b421de4e842bb78158a8ba4ca8c325ed3a8f210c3206b46cf846afe9b"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### allocPointer() {#ad1c4e23621c8e46179f0fda5fc58b25c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t Size&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::aarch32::allocPointer (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t(&amp;) Content=[Size])</td>
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

<p>Create a new node in the link-graph for the given pointer value.</p>

<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/gotbuilder/#af993d9fc28472c3aa7b2dbb5fce83b5e">llvm::jitlink::aarch32::GOTBuilder::createEntry</a>.</p>

</div>
</div>

### allocStub() {#a7a1ac23b74c74606a067297342490175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;size_t Size&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::aarch32::allocStub (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; S, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t(&amp;) Code=[Size])</td>
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

<p>Create a new node in the link-graph for the given stub template.</p>

<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a88ee8e4eea43084bd8964682683da88ca278c491bdd8a53618c149c4ac790da34">Template</a>.</p>


<p>Referenced by <a href="#aee0cc87627899fe951c9c8b7df170581">createStubArmv7</a>, <a href="#afd85f4e10561495360d365f1bb6998dd">createStubPrev7</a> and <a href="#a126e987204a06be667510edc866c3ea3">createStubThumbv7</a>.</p>

</div>
</div>

### applyFixup() {#a227cdc692d0608ba443b1ad47e97e3e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch32::applyFixup (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">ArmConfig</a> &amp; ArmCfg)</td>
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

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<p>References <a href="#a53f135c84cfb135c8e3f890659a3f782">applyFixupArm</a>, <a href="#a2cc2e3fa12d8c5d0d37310647c9c3a4d">applyFixupData</a>, <a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a1093624056b8864b4f523672eb1ab152a659d7e0b7695e33e47d072ac4aa0e97f">LastArmRelocation</a>, <a href="#a1093624056b8864b4f523672eb1ab152a506908472f2bf50bc850d5d7b0329980">LastDataRelocation</a>, <a href="#a1093624056b8864b4f523672eb1ab152a60c957fb9ecd147dc3bf7b95d5c02d64">LastThumbRelocation</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad72fb3d678aadcd83466b4820749007d">None</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### applyFixupArm() {#a53f135c84cfb135c8e3f890659a3f782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch32::applyFixupArm (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to apply the fixup for Arm-class relocations.</p>

<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a1093624056b8864b4f523672eb1ab152a8d257c062342dd6bddf5981b75a5b94f">Arm_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac91bb9bdd0b8d9d880e9c04f9af68da6">Arm_Jump24</a>, <a href="#a1093624056b8864b4f523672eb1ab152a2d91f98fa8c8184510edb38bb3aaf7ba">Arm_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152a77606cf82be61cc51fe6138a366275fd">Arm_MovwAbsNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a9c7b359f8ba0aa2c37bb009808262df7">checkOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a454b552102bd4227eeb09e2d7c8db4a6">encodeImmBA1BlA1BlxA2</a>, <a href="#a504c290392fc31205e292094b032c8f6">encodeImmMovtA1MovwA2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="#a6521de2d14ab48fafe3427e34a1e0405">hasTargetFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a8de4fa84b421de4e842bb78158a8ba4ca8c325ed3a8f210c3206b46cf846afe9b">ThumbSymbol</a> and <a href="#ae2292a4926037c9388d1c7a6eb5ea4d8">writeImmediate</a>.</p>


<p>Referenced by <a href="#a227cdc692d0608ba443b1ad47e97e3e9">applyFixup</a>.</p>

</div>
</div>

### applyFixupData() {#a2cc2e3fa12d8c5d0d37310647c9c3a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch32::applyFixupData (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to apply the fixup for Data-class relocations.</p>

<p>Definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad1c4cc46fc74c040840a716668e13d55">Data_Delta32</a>, <a href="#a1093624056b8864b4f523672eb1ab152a55c730148655277aa00b358e1eea1a9f">Data_Pointer32</a>, <a href="#a1093624056b8864b4f523672eb1ab152a5314af3f0742328c3d3e544e93415eee">Data_PRel31</a>, <a href="#a1093624056b8864b4f523672eb1ab152a154b0cafd77d1e3901c4fc6c2c602170">Data_RequestGOTAndTransformToDelta32</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a7a225814d4cc0d175373f7ffc59f66b4">llvm::support::endian::read32be</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#ae865d5defb8785b365f342375822beaa">llvm::support::endian::read32le</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a71eb44a745361d5437d4a53f9f30dd3d">llvm::support::endian::write32be</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4f05956d010455624c13f5eb2217bc8b">llvm::support::endian::write32le</a>.</p>


<p>Referenced by <a href="#a227cdc692d0608ba443b1ad47e97e3e9">applyFixup</a>.</p>

</div>
</div>

### applyFixupThumb() {#a183363f7e8482b2c1e193956dea835ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch32::applyFixupThumb (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">ArmConfig</a> &amp; ArmCfg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to apply the fixup for Thumb-class relocations.</p>

<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a9c7b359f8ba0aa2c37bb009808262df7">checkOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a352a75cb7a967bd415f8197171bcefc7">encodeImmBT4BlT1BlxT2</a>, <a href="#a95780a3ac905657cdb0e5293c339ea50">encodeImmBT4BlT1BlxT2_J1J2</a>, <a href="#a556a0d636ccdd8571f07d2a3cfab2dab">encodeImmMovtT1MovwT3</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a9266b50b560808e8f69eb394690d79c4">llvm::jitlink::Symbol::getAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr/#a4ee908fb9052f020e3c50e3f1a7d81c5">llvm::orc::ExecutorAddr::getValue</a>, <a href="#a6521de2d14ab48fafe3427e34a1e0405">hasTargetFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig/#a5e039f3a3b52cf453593a0b7be7e9615">llvm::jitlink::aarch32::ArmConfig::J1J2BranchEncoding</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a061c97aa3532f0b4a2390febaa911a65">llvm::jitlink::makeTargetOutOfRangeError</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad44531ef9da0d0d1c38a4a3de03fd319">Thumb_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152abf28fabfe322c11a4ae205087cb0222b">Thumb_Jump24</a>, <a href="#a1093624056b8864b4f523672eb1ab152aedcc1fec15a76e4fbc06fb7db2d611ef">Thumb_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152aa1a6fb356ad039e90d784aa4365560e5">Thumb_MovtPrel</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac92c861c872461a89de51864c1721a57">Thumb_MovwAbsNC</a>, <a href="#a1093624056b8864b4f523672eb1ab152af60cee5b702f67960e413ca40d17c969">Thumb_MovwPrelNC</a>, <a href="#a8de4fa84b421de4e842bb78158a8ba4ca8c325ed3a8f210c3206b46cf846afe9b">ThumbSymbol</a> and <a href="#ae2292a4926037c9388d1c7a6eb5ea4d8">writeImmediate</a>.</p>


<p>Referenced by <a href="#a227cdc692d0608ba443b1ad47e97e3e9">applyFixup</a>.</p>

</div>
</div>

### checkOpcode() {#a9c7b359f8ba0aa2c37bb009808262df7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch32::checkOpcode (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArmRelocation &amp; R, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Kind)</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1093624056b8864b4f523672eb1ab152acf92897f458625c1a5b927b2f00a610a">FirstArmRelocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="#a1093624056b8864b4f523672eb1ab152a659d7e0b7695e33e47d072ac4aa0e97f">LastArmRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="#a53f135c84cfb135c8e3f890659a3f782">applyFixupArm</a>, <a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a>, <a href="#afa8cac7ba958e4a67c048331418a516f">readAddendArm</a> and <a href="#aa6cf2c07bc856d1cb198de49c5523317">readAddendThumb</a>.</p>

</div>
</div>

### checkOpcode() {#ab081d8136bcb37bb0c6ab56a2714e308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::aarch32::checkOpcode (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ThumbRelocation &amp; R, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Kind)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1093624056b8864b4f523672eb1ab152a5e6fcdc070a58fa9534181b9cf59f276">FirstThumbRelocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="#a1093624056b8864b4f523672eb1ab152a60c957fb9ecd147dc3bf7b95d5c02d64">LastThumbRelocation</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### checkRegister() {#ab99fc0d5b2464663274f43ac29b12fd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;EdgeKind_aarch32 Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch32::checkRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ThumbRelocation &amp; R, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="#aee0cc87627899fe951c9c8b7df170581">createStubArmv7</a> and <a href="#a126e987204a06be667510edc866c3ea3">createStubThumbv7</a>.</p>

</div>
</div>

### checkRegister() {#ab9b158c8be77ccffdf26833564b4f37f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;EdgeKind_aarch32 Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch32::checkRegister (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArmRelocation &amp; R, uint32_t Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### createStubArmv7() {#aee0cc87627899fe951c9c8b7df170581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::aarch32::createStubArmv7 (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a7a1ac23b74c74606a067297342490175">allocStub</a>, <a href="#a1093624056b8864b4f523672eb1ab152a2d91f98fa8c8184510edb38bb3aaf7ba">Arm_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152a77606cf82be61cc51fe6138a366275fd">Arm_MovwAbsNC</a>, <a href="#aaa889d0367475b8ac2ace8b25b4e3a01">Armv7ABS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab99fc0d5b2464663274f43ac29b12fd8">checkRegister</a>, <a href="#a347be6c2f2f8dad96abde951f0475a82">encodeRegMovtA1MovwA2</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#a70ad29c3ed54a2bf6137e081d60a179c">llvm::jitlink::aarch32::StubsManager_v7::visitEdge</a>.</p>

</div>
</div>

### createStubPrev7() {#afd85f4e10561495360d365f1bb6998dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::aarch32::createStubPrev7 (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a7a1ac23b74c74606a067297342490175">allocStub</a>, <a href="#a528310c414bab7f3c95868b8a577d5d5">ArmThumbv5LdrPc</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1093624056b8864b4f523672eb1ab152a55c730148655277aa00b358e1eea1a9f">Data_Pointer32</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-prev7/#aa7eba3616569c9358af8634c9b93361c">llvm::jitlink::aarch32::StubsManager_prev7::visitEdge</a>.</p>

</div>
</div>

### createStubThumbv7() {#a126e987204a06be667510edc866c3ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block &amp; llvm::jitlink::aarch32::createStubThumbv7 (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; S, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Target)</td>
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



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a7a1ac23b74c74606a067297342490175">allocStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ab99fc0d5b2464663274f43ac29b12fd8">checkRegister</a>, <a href="#a26d693d81bb31f9af0d741788732f560">encodeRegMovtT1MovwT3</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a1093624056b8864b4f523672eb1ab152aedcc1fec15a76e4fbc06fb7db2d611ef">Thumb_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac92c861c872461a89de51864c1721a57">Thumb_MovwAbsNC</a> and <a href="#a885ac6c83ea16876a59df278f401d8dd">Thumbv7ABS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#a70ad29c3ed54a2bf6137e081d60a179c">llvm::jitlink::aarch32::StubsManager_v7::visitEdge</a>.</p>

</div>
</div>

### decodeImmBA1BlA1BlxA2() {#aa2ee1f37691782bcfd16bc0ee1079272}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::jitlink::aarch32::decodeImmBA1BlA1BlxA2 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode 26-bit immediate value for branch instructions (formats B A1, BL A1 and BLX A2).</p>


<p>00000000:Imm24 -&gt; Imm24:00</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="#afa8cac7ba958e4a67c048331418a516f">readAddendArm</a>.</p>

</div>
</div>

### decodeImmBT4BlT1BlxT2() {#a1ab42b95c481a2753758150c45022721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::jitlink::aarch32::decodeImmBT4BlT1BlxT2 (uint32_t Hi, uint32_t Lo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode 22-bit immediate value for branch instructions without J1J2 range extension (formats B T4, BL T1 and BLX T2).</p>


<p>[ 00000:Imm11H, 00000:Imm11L ] -&gt; 00000:Imm11H:Imm11L:0 J1^ ^J2 will always be 1</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="#aa6cf2c07bc856d1cb198de49c5523317">readAddendThumb</a>.</p>

</div>
</div>

### decodeImmBT4BlT1BlxT2\_J1J2() {#ac29adb89b5f4baf10f136125eca43dd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::jitlink::aarch32::decodeImmBT4BlT1BlxT2_J1J2 (uint32_t Hi, uint32_t Lo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode 25-bit immediate value for branch instructions with J1J2 range extension (formats B T4, BL T1 and BLX T2).</p>


<p>[ 00000:S:Imm10, 00:J1:0:J2:Imm11] -&gt; S:I1:I2:Imm10:Imm11:0</p>


<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="#aa6cf2c07bc856d1cb198de49c5523317">readAddendThumb</a>.</p>

</div>
</div>

### decodeImmMovtA1MovwA2() {#a8745c0e342c94d550c2b871d1fabe79d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::jitlink::aarch32::decodeImmMovtA1MovwA2 (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode 16-bit immediate value for move instruction formats MOVT A1 and MOVW A2.</p>


<p>000000000000:Imm4:0000:Imm12 -&gt; Imm4:Imm12</p>


<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#afa8cac7ba958e4a67c048331418a516f">readAddendArm</a>.</p>

</div>
</div>

### decodeImmMovtT1MovwT3() {#a4362f40f8685bc3dd96872524615589a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::jitlink::aarch32::decodeImmMovtT1MovwT3 (uint32_t Hi, uint32_t Lo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode 16-bit immediate value from move instruction formats MOVT T1 and MOVW T3.</p>


<p>[ 00000:i:000000:Imm4, 0:Imm3:0000:Imm8 ] -&gt; Imm4:Imm1:Imm3:Imm8</p>


<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>


<p>Referenced by <a href="#aa6cf2c07bc856d1cb198de49c5523317">readAddendThumb</a>.</p>

</div>
</div>

### decodeRegMovtA1MovwA2() {#a612abdb994ba160e64598fc32e7ce26c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::jitlink::aarch32::decodeRegMovtA1MovwA2 (uint64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for instruction formats MOVT A1 and MOVW A2.</p>


<p>0000000000000000:Rd4:000000000000 -&gt; Rd4</p>


<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>

</div>
</div>

### decodeRegMovtT1MovwT3() {#a3d8308e06367ebd45fd689971fa13fa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::jitlink::aarch32::decodeRegMovtT1MovwT3 (uint32_t Hi, uint32_t Lo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Decode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> from instruction formats MOVT T1 and MOVW T3.</p>


<p>[0000000000000000, 0000:Rd4:00000000] -&gt; Rd4</p>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2bac1a5298f939e87e8f962a5edfc206918">llvm::Hi</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>.</p>

</div>
</div>

### encodeImmBA1BlA1BlxA2() {#a454b552102bd4227eeb09e2d7c8db4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::jitlink::aarch32::encodeImmBA1BlA1BlxA2 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode 26-bit immediate value for branch instructions (formats B A1, BL A1 and BLX A2).</p>


<p>Imm24:00 -&gt; 00000000:Imm24</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#a53f135c84cfb135c8e3f890659a3f782">applyFixupArm</a>.</p>

</div>
</div>

### encodeImmBT4BlT1BlxT2() {#a352a75cb7a967bd415f8197171bcefc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HalfWords llvm::jitlink::aarch32::encodeImmBT4BlT1BlxT2 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode 22-bit immediate value for branch instructions without J1J2 range extension (formats B T4, BL T1 and BLX T2).</p>


<p>00000:Imm11H:Imm11L:0 -&gt; [ 00000:Imm11H, 00000:Imm11L ] J1^ ^J2 will always be 1</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a>.</p>

</div>
</div>

### encodeImmBT4BlT1BlxT2\_J1J2() {#a95780a3ac905657cdb0e5293c339ea50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HalfWords llvm::jitlink::aarch32::encodeImmBT4BlT1BlxT2_J1J2 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode 25-bit immediate value for branch instructions with J1J2 range extension (formats B T4, BL T1 and BLX T2).</p>


<p>S:I1:I2:Imm10:Imm11:0 -&gt; [ 00000:S:Imm10, 00:J1:0:J2:Imm11 ]</p>


<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a>.</p>

</div>
</div>

### encodeImmMovtA1MovwA2() {#a504c290392fc31205e292094b032c8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::jitlink::aarch32::encodeImmMovtA1MovwA2 (uint16_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode 16-bit immediate value for move instruction formats MOVT A1 and MOVW A2.</p>


<p>Imm4:Imm12 -&gt; 000000000000:Imm4:0000:Imm12</p>


<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#a53f135c84cfb135c8e3f890659a3f782">applyFixupArm</a>.</p>

</div>
</div>

### encodeImmMovtT1MovwT3() {#a556a0d636ccdd8571f07d2a3cfab2dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HalfWords llvm::jitlink::aarch32::encodeImmMovtT1MovwT3 (uint16_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode 16-bit immediate value for move instruction formats MOVT T1 and MOVW T3.</p>


<p>Imm4:Imm1:Imm3:Imm8 -&gt; [ 00000:i:000000:Imm4, 0:Imm3:0000:Imm8 ]</p>


<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a>.</p>

</div>
</div>

### encodeRegMovtA1MovwA2() {#a347be6c2f2f8dad96abde951f0475a82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::jitlink::aarch32::encodeRegMovtA1MovwA2 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for instruction formats MOVT A1 and MOVW A2.</p>


<p>Rd4 -&gt; 0000000000000000:Rd4:000000000000</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#aee0cc87627899fe951c9c8b7df170581">createStubArmv7</a>.</p>

</div>
</div>

### encodeRegMovtT1MovwT3() {#a26d693d81bb31f9af0d741788732f560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HalfWords llvm::jitlink::aarch32::encodeRegMovtT1MovwT3 (int64_t Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode register <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for instruction formats MOVT T1 and MOVW T3.</p>


<p>Rd4 -&gt; [0000000000000000, 0000:Rd4:00000000]</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#a126e987204a06be667510edc866c3ea3">createStubThumbv7</a>.</p>

</div>
</div>

### getArmConfigForCPUArch() {#a3a95b507182908470f226c73349e0f15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArmConfig llvm::jitlink::aarch32::getArmConfigForCPUArch (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04">ARMBuildAttrs::CPUArch</a> CPUArch)</td>
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

<p>Obtain the sub-arch configuration for a given Arm CPU model.</p>

<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig/#a5e039f3a3b52cf453593a0b7be7e9615">llvm::jitlink::aarch32::ArmConfig::J1J2BranchEncoding</a>, <a href="#a66abed31cc3dfac01c8ed560eb6db1c5a25f05cdee23677d484144bcb0c438613">pre_v7</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig/#a88f7625d1cdc07c59d18a80819e999b3">llvm::jitlink::aarch32::ArmConfig::Stubs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a3cf0cd428f021cea15953922332619e7">llvm::ARMBuildAttrs::v7</a>, <a href="#a66abed31cc3dfac01c8ed560eb6db1c5ae6dd71377633723164aeea0750ddafa8">v7</a> and <a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04a49b5daf5353b4da268f64fef514a443f">llvm::ARMBuildAttrs::v7E_M</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a85b7da2fbe9dbb9291c2ebeba26baa11">llvm::jitlink::createLinkGraphFromELFObject_aarch32</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/elfjitlinker-aarch32/#ae10dd491f32961b12c311a3b6de481fd">llvm::jitlink::ELFJITLinker_aarch32::JITLinker&lt; ELFJITLinker_aarch32 &gt;</a>.</p>

</div>
</div>

### getCPUArchName() {#a40551e1cf4261bded983399e19d7c565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::aarch32::getCPUArchName (<a href="/web-llvm/docs/api/namespaces/llvm/armbuildattrs/#a6f3569befc20dac7d092acbfc2ecbf04">ARMBuildAttrs::CPUArch</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Human-readable name for a given CPU architecture kind.</p>

<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp/#a835cc505d51bcf97c7b8bd1e2bf6f208">CPUARCH_NAME_CASE</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a66abed31cc3dfac01c8ed560eb6db1c5ae6dd71377633723164aeea0750ddafa8">v7</a>.</p>

</div>
</div>

### getEdgeKindName() {#a604cf2e8a88455df3f053891be27be1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::jitlink::aarch32::getEdgeKindName (<a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> K)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a human-readable name for the given AArch32 edge kind.</p>

<p>Definition at line 930 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a1093624056b8864b4f523672eb1ab152a8d257c062342dd6bddf5981b75a5b94f">Arm_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac91bb9bdd0b8d9d880e9c04f9af68da6">Arm_Jump24</a>, <a href="#a1093624056b8864b4f523672eb1ab152a2d91f98fa8c8184510edb38bb3aaf7ba">Arm_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152a77606cf82be61cc51fe6138a366275fd">Arm_MovwAbsNC</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad1c4cc46fc74c040840a716668e13d55">Data_Delta32</a>, <a href="#a1093624056b8864b4f523672eb1ab152a55c730148655277aa00b358e1eea1a9f">Data_Pointer32</a>, <a href="#a1093624056b8864b4f523672eb1ab152a5314af3f0742328c3d3e544e93415eee">Data_PRel31</a>, <a href="#a1093624056b8864b4f523672eb1ab152a154b0cafd77d1e3901c4fc6c2c602170">Data_RequestGOTAndTransformToDelta32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a06eee57acde48953ffd29ae8d337202e">llvm::jitlink::getGenericEdgeKindName</a>, <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp/#aef9ba900d85871db5625dfd07c8a0c66">KIND_NAME_CASE</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad72fb3d678aadcd83466b4820749007d">None</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad44531ef9da0d0d1c38a4a3de03fd319">Thumb_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152abf28fabfe322c11a4ae205087cb0222b">Thumb_Jump24</a>, <a href="#a1093624056b8864b4f523672eb1ab152aedcc1fec15a76e4fbc06fb7db2d611ef">Thumb_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152aa1a6fb356ad039e90d784aa4365560e5">Thumb_MovtPrel</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac92c861c872461a89de51864c1721a57">Thumb_MovwAbsNC</a> and <a href="#a1093624056b8864b4f523672eb1ab152af60cee5b702f67960e413ca40d17c969">Thumb_MovwPrelNC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a973318c52fa5f0593df8f3145940c516">llvm::jitlink::getELFAArch32EdgeKindName</a>.</p>

</div>
</div>

### hasTargetFlags() {#a6521de2d14ab48fafe3427e34a1e0405}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch32::hasTargetFlags (<a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> &amp; Sym, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> whether the given target flags are set for this <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a>.</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol/#a2a3a9f494399398e41e672eeec440aa4">llvm::jitlink::Symbol::getTargetFlags</a>.</p>


<p>Referenced by <a href="#a53f135c84cfb135c8e3f890659a3f782">applyFixupArm</a> and <a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a>.</p>

</div>
</div>

### needsStub() {#a1c2e126eb4caf72f59bf457da35c2005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::jitlink::aarch32::needsStub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge">Edge</a> &amp; E)</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a1093624056b8864b4f523672eb1ab152a8d257c062342dd6bddf5981b75a5b94f">Arm_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac91bb9bdd0b8d9d880e9c04f9af68da6">Arm_Jump24</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad44531ef9da0d0d1c38a4a3de03fd319">Thumb_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152abf28fabfe322c11a4ae205087cb0222b">Thumb_Jump24</a> and <a href="#a8de4fa84b421de4e842bb78158a8ba4ca8c325ed3a8f210c3206b46cf846afe9b">ThumbSymbol</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-prev7/#aa7eba3616569c9358af8634c9b93361c">llvm::jitlink::aarch32::StubsManager_prev7::visitEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/stubsmanager-v7/#a70ad29c3ed54a2bf6137e081d60a179c">llvm::jitlink::aarch32::StubsManager_v7::visitEdge</a>.</p>

</div>
</div>

### readAddend() {#a74f3b584ce0c2c4c0b4a627001d3ddf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; llvm::jitlink::aarch32::readAddend (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#a99b24e01e70f80708a8367e18915a4e5">Edge::OffsetT</a> Offset, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">ArmConfig</a> &amp; ArmCfg)</td>
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

<p>Read the initial addend for a REL-type relocation.</p>


<p>It's the value encoded in the immediate field of the fixup location by the compiler.</p>


<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="#a1093624056b8864b4f523672eb1ab152a659d7e0b7695e33e47d072ac4aa0e97f">LastArmRelocation</a>, <a href="#a1093624056b8864b4f523672eb1ab152a506908472f2bf50bc850d5d7b0329980">LastDataRelocation</a>, <a href="#a1093624056b8864b4f523672eb1ab152a60c957fb9ecd147dc3bf7b95d5c02d64">LastThumbRelocation</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad72fb3d678aadcd83466b4820749007d">None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#afa8cac7ba958e4a67c048331418a516f">readAddendArm</a>, <a href="#a350d2681d6fabc606cb82e4ac365af9e">readAddendData</a> and <a href="#aa6cf2c07bc856d1cb198de49c5523317">readAddendThumb</a>.</p>

</div>
</div>

### readAddendArm() {#afa8cac7ba958e4a67c048331418a516f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; llvm::jitlink::aarch32::readAddendArm (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#a99b24e01e70f80708a8367e18915a4e5">Edge::OffsetT</a> Offset, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to read the initial addend for Arm-class relocations.</p>

<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="#a1093624056b8864b4f523672eb1ab152a8d257c062342dd6bddf5981b75a5b94f">Arm_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac91bb9bdd0b8d9d880e9c04f9af68da6">Arm_Jump24</a>, <a href="#a1093624056b8864b4f523672eb1ab152a2d91f98fa8c8184510edb38bb3aaf7ba">Arm_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152a77606cf82be61cc51fe6138a366275fd">Arm_MovwAbsNC</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a9c7b359f8ba0aa2c37bb009808262df7">checkOpcode</a>, <a href="#aa2ee1f37691782bcfd16bc0ee1079272">decodeImmBA1BlA1BlxA2</a>, <a href="#a8745c0e342c94d550c2b871d1fabe79d">decodeImmMovtA1MovwA2</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a74f3b584ce0c2c4c0b4a627001d3ddf0">readAddend</a>.</p>

</div>
</div>

### readAddendData() {#a350d2681d6fabc606cb82e4ac365af9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; llvm::jitlink::aarch32::readAddendData (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#a99b24e01e70f80708a8367e18915a4e5">Edge::OffsetT</a> Offset, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to read the initial addend for Data-class relocations.</p>

<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad1c4cc46fc74c040840a716668e13d55">Data_Delta32</a>, <a href="#a1093624056b8864b4f523672eb1ab152a55c730148655277aa00b358e1eea1a9f">Data_Pointer32</a>, <a href="#a1093624056b8864b4f523672eb1ab152a5314af3f0742328c3d3e544e93415eee">Data_PRel31</a>, <a href="#a1093624056b8864b4f523672eb1ab152a154b0cafd77d1e3901c4fc6c2c602170">Data_RequestGOTAndTransformToDelta32</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a1fda585fbf18128d11d28fa4c5b0ad7d">llvm::support::endian::read32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>.</p>


<p>Referenced by <a href="#a74f3b584ce0c2c4c0b4a627001d3ddf0">readAddend</a>.</p>

</div>
</div>

### readAddendThumb() {#aa6cf2c07bc856d1cb198de49c5523317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; int64_t &gt; llvm::jitlink::aarch32::readAddendThumb (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#a99b24e01e70f80708a8367e18915a4e5">Edge::OffsetT</a> Offset, <a href="/web-llvm/docs/api/classes/llvm/jitlink/edge/#af18145da213e6c4033b368d657e80baa">Edge::Kind</a> Kind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">ArmConfig</a> &amp; ArmCfg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper function to read the initial addend for Thumb-class relocations.</p>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a9c7b359f8ba0aa2c37bb009808262df7">checkOpcode</a>, <a href="#a1ab42b95c481a2753758150c45022721">decodeImmBT4BlT1BlxT2</a>, <a href="#ac29adb89b5f4baf10f136125eca43dd4">decodeImmBT4BlT1BlxT2_J1J2</a>, <a href="#a4362f40f8685bc3dd96872524615589a">decodeImmMovtT1MovwT3</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig/#a5e039f3a3b52cf453593a0b7be7e9615">llvm::jitlink::aarch32::ArmConfig::J1J2BranchEncoding</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ae5b35beb6f127e5f47269e9124b886fb">LLVM_LIKELY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="#a1093624056b8864b4f523672eb1ab152ad44531ef9da0d0d1c38a4a3de03fd319">Thumb_Call</a>, <a href="#a1093624056b8864b4f523672eb1ab152abf28fabfe322c11a4ae205087cb0222b">Thumb_Jump24</a>, <a href="#a1093624056b8864b4f523672eb1ab152aedcc1fec15a76e4fbc06fb7db2d611ef">Thumb_MovtAbs</a>, <a href="#a1093624056b8864b4f523672eb1ab152aa1a6fb356ad039e90d784aa4365560e5">Thumb_MovtPrel</a>, <a href="#a1093624056b8864b4f523672eb1ab152ac92c861c872461a89de51864c1721a57">Thumb_MovwAbsNC</a> and <a href="#a1093624056b8864b4f523672eb1ab152af60cee5b702f67960e413ca40d17c969">Thumb_MovwPrelNC</a>.</p>


<p>Referenced by <a href="#a74f3b584ce0c2c4c0b4a627001d3ddf0">readAddend</a>.</p>

</div>
</div>

### writeImmediate() {#ae2292a4926037c9388d1c7a6eb5ea4d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;EdgeKind_aarch32 Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::aarch32::writeImmediate (WritableThumbRelocation &amp; R, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a> Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a53f135c84cfb135c8e3f890659a3f782">applyFixupArm</a> and <a href="#a183363f7e8482b2c1e193956dea835ee">applyFixupThumb</a>.</p>

</div>
</div>

### writeImmediate() {#aa35c7cb2b60e763112b40776ea9da9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;EdgeKind_aarch32 Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::aarch32::writeImmediate (WritableArmRelocation &amp; R, uint32_t Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 382 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### writeRegister() {#aaf50e0db42fa045e5c4161db69e98909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;EdgeKind_aarch32 Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::aarch32::writeRegister (WritableThumbRelocation &amp; R, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/halfwords">HalfWords</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

### writeRegister() {#a6d01c43e1d39cbe97b1c68d7e7c9fd35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;EdgeKind_aarch32 Kind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::jitlink::aarch32::writeRegister (WritableArmRelocation &amp; R, uint32_t Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ArmThumbv5LdrPc {#a528310c414bab7f3c95868b8a577d5d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::jitlink::aarch32::ArmThumbv5LdrPc[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x78, 0x47,             
    0xfd, 0xe7,             
    0x04, 0xf0, 0x1f, 0xe5, 
    0x00, 0x00, 0x00, 0x00, 
}
</div>
</dd>
</dl>

<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#afd85f4e10561495360d365f1bb6998dd">createStubPrev7</a>.</p>

</div>
</div>

### Armv7ABS {#aaa889d0367475b8ac2ace8b25b4e3a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::jitlink::aarch32::Armv7ABS[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x00, 0xc0, 0x00, 0xe3, 
    0x00, 0xc0, 0x40, 0xe3, 
    0x1c, 0xff, 0x2f, 0xe1  
}
</div>
</dd>
</dl>

<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#aee0cc87627899fe951c9c8b7df170581">createStubArmv7</a>.</p>

</div>
</div>

### GOTEntryInit {#a7b1bde175fefd62202245e6271531006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::jitlink::aarch32::GOTEntryInit[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x00,
    0x00,
    0x00,
    0x00,
}
</div>
</dd>
</dl>

<p>Definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jitlink/aarch32/gotbuilder/#af993d9fc28472c3aa7b2dbb5fce83b5e">llvm::jitlink::aarch32::GOTBuilder::createEntry</a>.</p>

</div>
</div>

### Thumbv7ABS {#a885ac6c83ea16876a59df278f401d8dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::jitlink::aarch32::Thumbv7ABS[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    0x40, 0xf2, 0x00, 0x0c, 
    0xc0, 0xf2, 0x00, 0x0c, 
    0x60, 0x47              
}
</div>
</dd>
</dl>

<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a>.</p>


<p>Referenced by <a href="#a126e987204a06be667510edc866c3ea3">createStubThumbv7</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/jitlink/aarch32-h">aarch32.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/aarch32-cpp">aarch32.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
