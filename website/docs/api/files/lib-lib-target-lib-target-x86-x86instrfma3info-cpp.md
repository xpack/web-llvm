---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `X86InstrFMA3Info.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-h">X86InstrFMA3Info.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>"
#include &lt;atomic&gt;
#include &lt;cassert&gt;
#include &lt;cstdint&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0063780933c83ab9a27e63c51772154f">verifyTables</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86instrfma3group">X86InstrFMA3Group</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab138684de9096eb96683328900f78e48">Groups</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86instrfma3group">X86InstrFMA3Group</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf87013d90ffd3ea37de6f45c75ee4cc">BroadcastGroups</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/x86instrfma3group">X86InstrFMA3Group</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a977cfc29f5e137f1c0ee356e1807e69d">RoundGroups</a>[] = ...</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;  { { X86::Name##132##Suf, X86::Name##213##Suf, X86::Name##231##Suf }, Attrs },</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3996f7e80344d0a10be995d4550fe57b">FMA3GROUP_MASKED_INT</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab04b7c6e3e1ef9e8e426d0a556069512">FMA3GROUP_PACKED_WIDTHS_Z</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2358c62879e5400fac71b7c8dd2d5ec1">FMA3GROUP_PACKED_WIDTHS_ALL</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae01e5b13f058c9700bdacc4ab22f2835">FMA3GROUP_PACKED_DHS</a>(Name, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a342e92da7f983cb190bf4cb1758c739f">FMA3GROUP_PACKED_BF16</a>(Name, Attrs)&nbsp;&nbsp;&nbsp;  <a href="#ab04b7c6e3e1ef9e8e426d0a556069512">FMA3GROUP_PACKED_WIDTHS_Z</a>(Name, BF16, Attrs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec2e67992a42ac29eac369bbf741fcf">FMA3GROUP_SCALAR_WIDTHS_Z</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284eec0aea3d9056d27928291115dd83">FMA3GROUP_SCALAR_WIDTHS_ALL</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77808655efb9d0f27409a6fc616ea27a">FMA3GROUP_SCALAR</a>(Name, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ce377839fc2ff87c9e4186b79ddef9">FMA3GROUP_FULL</a>(Name, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, Type, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b3cf61d12135c9ee02d0004a610d25a">FMA3GROUP_PACKED_AVX512_ALL</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c676ba15578d1cbddc730bbf2d40dc7">FMA3GROUP_PACKED_AVX512_DHS</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f17cb7c2bd6933b67c5e2b268147fa2">FMA3GROUP_PACKED_AVX512_ROUND</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565707f109a81d7a41634da245efad17">FMA3GROUP_SCALAR_AVX512_ROUND</a>(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
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

## Functions

### verifyTables() {#a0063780933c83ab9a27e63c51772154f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void verifyTables ()</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#adf87013d90ffd3ea37de6f45c75ee4cc">BroadcastGroups</a>, <a href="#ab138684de9096eb96683328900f78e48">Groups</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="#a977cfc29f5e137f1c0ee356e1807e69d">RoundGroups</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac81c73fb91e0b2c0c30ae63c671d23">llvm::getFMA3Group</a> and <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#aafe02ccc1e3c410eac85a36f70878f18">llvm::RISCVISAInfo::isSupportedExtension</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### BroadcastGroups {#adf87013d90ffd3ea37de6f45c75ee4cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrFMA3Group BroadcastGroups[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac81c73fb91e0b2c0c30ae63c671d23">llvm::getFMA3Group</a> and <a href="#a0063780933c83ab9a27e63c51772154f">verifyTables</a>.</p>

</div>
</div>

### Groups {#ab138684de9096eb96683328900f78e48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrFMA3Group Groups[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a0c7442486454c55b94469e8b7c8ab468">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::apply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac81c73fb91e0b2c0c30ae63c671d23">llvm::getFMA3Group</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinescheduler-cpp-/basememopclustermutation/#a456ce65cd7eb7154bc9a1460dcd3eb4a">anonymous{MachineScheduler.cpp}::BaseMemOpClusterMutation::groupMemOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aabed4dadfe0a32d2cc856553788212ba">upgradeArmOrAarch64IntrinsicFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7d22c115f5634f10ef137c93c762ebca">llvm::UpgradeDataLayoutString</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a0e3d706240976157dfd3542311dc48cb">upgradeIntrinsicFunction1</a>, <a href="#a0063780933c83ab9a27e63c51772154f">verifyTables</a> and <a href="/web-llvm/docs/api/structs/anonymous-elfobjectwriter-cpp-/elfwriter/#a27e478bd5208561e8eb16ec550509761">anonymous{ELFObjectWriter.cpp}::ELFWriter::writeObject</a>.</p>

</div>
</div>

### RoundGroups {#a977cfc29f5e137f1c0ee356e1807e69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrFMA3Group RoundGroups[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
}
</div>
</dd>
</dl>

<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6ac81c73fb91e0b2c0c30ae63c671d23">llvm::getFMA3Group</a> and <a href="#a0063780933c83ab9a27e63c51772154f">verifyTables</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### FMA3GROUP {#a9c43444659267043daf95826d8d2c345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;  { { X86::Name##132##Suf, X86::Name##213##Suf, X86::Name##231##Suf }, Attrs },</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_FULL {#af5ce377839fc2ff87c9e4186b79ddef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_FULL(Name, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a342e92da7f983cb190bf4cb1758c739f">FMA3GROUP_PACKED_BF16</a>(Name, Attrs) \
  <a href="#ae01e5b13f058c9700bdacc4ab22f2835">FMA3GROUP_PACKED_DHS</a>(Name, Attrs) \
  <a href="#a77808655efb9d0f27409a6fc616ea27a">FMA3GROUP_SCALAR</a>(Name, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_MASKED {#a49b8a98f76facd048364c87ce54c43d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_MASKED(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##k, Attrs | X86InstrFMA3Group::KMergeMasked) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##kz, Attrs | X86InstrFMA3Group::KZeroMasked)
</div>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_MASKED\_INT {#a3996f7e80344d0a10be995d4550fe57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_MASKED_INT(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##_Int, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##k_Int, Attrs | X86InstrFMA3Group::KMergeMasked) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##kz_Int, Attrs | X86InstrFMA3Group::KZeroMasked)
</div>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_AVX512\_ALL {#a3b3cf61d12135c9ee02d0004a610d25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_AVX512_ALL(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, BF16, Suf, Attrs)                       \
  <a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, PD, Suf, Attrs)                         \
  <a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, PH, Suf, Attrs)                         \
  <a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, PS, Suf, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_AVX512\_DHS {#a4c676ba15578d1cbddc730bbf2d40dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_AVX512_DHS(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, PD, Suf, Attrs) \
  <a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, PH, Suf, Attrs) \
  <a href="#ac4894917364e2c8c9fe656315f7cc821">FMA3GROUP_PACKED_AVX512_WIDTHS</a>(Name, PS, Suf, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_AVX512\_ROUND {#a2f17cb7c2bd6933b67c5e2b268147fa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_AVX512_ROUND(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, PDZ256##Suf, Attrs)                                   \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, PDZ##Suf, Attrs)                                      \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, PHZ256##Suf, Attrs)                                   \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, PHZ##Suf, Attrs)                                      \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, PSZ256##Suf, Attrs)                                   \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, PSZ##Suf, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_AVX512\_WIDTHS {#ac4894917364e2c8c9fe656315f7cc821}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_AVX512_WIDTHS(Name, Type, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>##Z128##Suf, Attrs) \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>##Z256##Suf, Attrs) \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a>##Z##Suf, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_BF16 {#a342e92da7f983cb190bf4cb1758c739f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_BF16(Name, Attrs)&nbsp;&nbsp;&nbsp;  <a href="#ab04b7c6e3e1ef9e8e426d0a556069512">FMA3GROUP_PACKED_WIDTHS_Z</a>(Name, BF16, Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_DHS {#ae01e5b13f058c9700bdacc4ab22f2835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_DHS(Name, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a2358c62879e5400fac71b7c8dd2d5ec1">FMA3GROUP_PACKED_WIDTHS_ALL</a>(Name, PD, Attrs) \
  <a href="#ab04b7c6e3e1ef9e8e426d0a556069512">FMA3GROUP_PACKED_WIDTHS_Z</a>(Name, PH, Attrs) \
  <a href="#a2358c62879e5400fac71b7c8dd2d5ec1">FMA3GROUP_PACKED_WIDTHS_ALL</a>(Name, PS, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_WIDTHS\_ALL {#a2358c62879e5400fac71b7c8dd2d5ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_WIDTHS_ALL(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##Ym, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##Yr, Attrs) \
  <a href="#ab04b7c6e3e1ef9e8e426d0a556069512">FMA3GROUP_PACKED_WIDTHS_Z</a>(Name, Suf, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##m, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##r, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_PACKED\_WIDTHS\_Z {#ab04b7c6e3e1ef9e8e426d0a556069512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_PACKED_WIDTHS_Z(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, Suf##Z128m, Attrs) \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, Suf##Z128r, Attrs) \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, Suf##Z256m, Attrs) \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, Suf##Z256r, Attrs) \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, Suf##Zm, Attrs) \
  <a href="#a49b8a98f76facd048364c87ce54c43d9">FMA3GROUP_MASKED</a>(Name, Suf##Zr, Attrs) \
</div>
</dd>
</dl>

<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_SCALAR {#a77808655efb9d0f27409a6fc616ea27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_SCALAR(Name, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a284eec0aea3d9056d27928291115dd83">FMA3GROUP_SCALAR_WIDTHS_ALL</a>(Name, SD, Attrs) \
  <a href="#a5ec2e67992a42ac29eac369bbf741fcf">FMA3GROUP_SCALAR_WIDTHS_Z</a>(Name, SH, Attrs) \
  <a href="#a284eec0aea3d9056d27928291115dd83">FMA3GROUP_SCALAR_WIDTHS_ALL</a>(Name, SS, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_SCALAR\_AVX512\_ROUND {#a565707f109a81d7a41634da245efad17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_SCALAR_AVX512_ROUND(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, SDZ##Suf, Attrs) \
  <a href="#a3996f7e80344d0a10be995d4550fe57b">FMA3GROUP_MASKED_INT</a>(Name, SDZ##Suf, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, SHZ##Suf, Attrs) \
  <a href="#a3996f7e80344d0a10be995d4550fe57b">FMA3GROUP_MASKED_INT</a>(Name, SHZ##Suf, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, SSZ##Suf, Attrs) \
  <a href="#a3996f7e80344d0a10be995d4550fe57b">FMA3GROUP_MASKED_INT</a>(Name, SSZ##Suf, Attrs)
</div>
</dd>
</dl>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_SCALAR\_WIDTHS\_ALL {#a284eec0aea3d9056d27928291115dd83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_SCALAR_WIDTHS_ALL(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a5ec2e67992a42ac29eac369bbf741fcf">FMA3GROUP_SCALAR_WIDTHS_Z</a>(Name, Suf, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##m, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##m_Int, Attrs | X86InstrFMA3Group::Intrinsic) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##r, Attrs) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##r_Int, Attrs | X86InstrFMA3Group::Intrinsic)
</div>
</dd>
</dl>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

### FMA3GROUP\_SCALAR\_WIDTHS\_Z {#a5ec2e67992a42ac29eac369bbf741fcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FMA3GROUP_SCALAR_WIDTHS_Z(Name, Suf, Attrs)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##Zm, Attrs) \
  <a href="#a3996f7e80344d0a10be995d4550fe57b">FMA3GROUP_MASKED_INT</a>(Name, Suf##Zm, Attrs | X86InstrFMA3Group::Intrinsic) \
  <a href="#a9c43444659267043daf95826d8d2c345">FMA3GROUP</a>(Name, Suf##Zr, Attrs) \
  <a href="#a3996f7e80344d0a10be995d4550fe57b">FMA3GROUP_MASKED_INT</a>(Name, Suf##Zr, Attrs | X86InstrFMA3Group::Intrinsic) \
</div>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrfma3info-cpp">X86InstrFMA3Info.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
