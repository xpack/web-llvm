---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/armmcasminfodarwin
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ARMMCAsmInfoDarwin` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ARMMCAsmInfoDarwin { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-h">Target/ARM/MCTargetDesc/ARMMCAsmInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfodarwin">MCAsmInfoDarwin</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9431bd9edb8400058b9caccf2c38f21e">ARMMCAsmInfoDarwin</a> (const Triple &amp;TheTriple)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d857186d185d82c12aaa912bf5eb705">anchor</a> ()</td>
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


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-h">ARMMCAsmInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ARMMCAsmInfoDarwin() {#a9431bd9edb8400058b9caccf2c38f21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ARMMCAsmInfoDarwin::ARMMCAsmInfoDarwin (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TheTriple)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-h">ARMMCAsmInfo.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-cpp">ARMMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154af65ab1964be676bea302940a45765021">llvm::Triple::armeb</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a68b1f3319120cc85d68179defe27e779">llvm::MCAsmInfo::Code16Directive</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a2e33f61b5be0bddcb4aba0c2e9685934">llvm::MCAsmInfo::Code32Directive</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af30c385b021a371a04bacd22cef94c7b">llvm::MCAsmInfo::CommentString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a3c136967a2fc9489724bcd8706a16fed">llvm::MCAsmInfo::Data64bitsDirective</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84ab4fe87e4046ecd1f9f3d96bbf63822b3">llvm::DwarfCFI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a500ba2b2c0203d1d53b83a649551a6b5">llvm::MCAsmInfo::ExceptionsType</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5fc23559f17bbe5ff83ec0fed0a5fdcf">llvm::Triple::getArch</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#adfd724f11ba125f30c3bb516be0bb06f">llvm::MCAsmInfo::IsLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ab6fdf9b428bc3d57837022121c155cbf">llvm::Triple::isOSDarwin</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a14aca434442ff741fa55e97ddccd15ed">llvm::Triple::isWatchABI</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a824f02b302d147245dc0f553c63428db">llvm::MCAsmInfo::MaxInstLength</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a0f60fd9b862dff366e18e32c6d98d96b">llvm::SjLj</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a98f40236cfff7278d4b57633fad2245d">llvm::MCAsmInfo::SupportsDebugInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a038a23cbd1756bf797c083c48229dcfd">llvm::Triple::thumbeb</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ad8ce9bafbf33806b98fec165f653a72b">llvm::MCAsmInfo::UseDataRegionDirectives</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a9d857186d185d82c12aaa912bf5eb705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ARMMCAsmInfoDarwin::anchor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-h">ARMMCAsmInfo.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-cpp">ARMMCAsmInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-cpp">ARMMCAsmInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/lib/target/arm/mctargetdesc/armmcasminfo-h">ARMMCAsmInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
