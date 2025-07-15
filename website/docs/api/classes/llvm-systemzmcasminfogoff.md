---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/systemzmcasminfogoff
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SystemZMCAsmInfoGOFF` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::SystemZMCAsmInfoGOFF { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-h">Target/SystemZ/MCTargetDesc/SystemZMCAsmInfo.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcasminfogoff">MCAsmInfoGOFF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae932e630ec354a982da5159a05ada642">SystemZMCAsmInfoGOFF</a> (const Triple &amp;TT)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a294a0de1718ea4d11c79b95a55fe5b15">isAcceptableChar</a> (char C) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if C is an acceptable character inside a symbol name. <a href="#a294a0de1718ea4d11c79b95a55fe5b15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-h">SystemZMCAsmInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZMCAsmInfoGOFF() {#ae932e630ec354a982da5159a05ada642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZMCAsmInfoGOFF::SystemZMCAsmInfoGOFF (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TT)</td>
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



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-h">SystemZMCAsmInfo.h</a>, definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-cpp">SystemZMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a64c658e001903c963cdb6b900ad035ada90ce16cc048b659bf69b469a1a4d4e2d">llvm::AD_HLASM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a17fc8ddaef7437aff31ec4b9aba7f224">llvm::MCAsmInfo::AllowAdditionalComments</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a672dc8291b4413bc99762222ef2581e5">llvm::MCAsmInfo::AllowAtAtStartOfIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a7d31e965e63658cf80af8577320924c8">llvm::MCAsmInfo::AllowAtInName</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a51f606f6112e0be13fda316c77035563">llvm::MCAsmInfo::AllowDollarAtStartOfIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aaab4eaa2f4de9c0d12606c176dd9d738">llvm::MCAsmInfo::AssemblerDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aeb608789bae103384e251c302a2215f9">llvm::MCAsmInfo::CalleeSaveStackSlotSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ae243a845fe9d46ed2cb7403700921e4a">llvm::MCAsmInfo::CodePointerSize</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#af30c385b021a371a04bacd22cef94c7b">llvm::MCAsmInfo::CommentString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a500ba2b2c0203d1d53b83a649551a6b5">llvm::MCAsmInfo::ExceptionsType</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aec6ef6dec2d625ced10ab9a0cb8d65f7">llvm::MCAsmInfo::IsHLASM</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#adfd724f11ba125f30c3bb516be0bb06f">llvm::MCAsmInfo::IsLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a824f02b302d147245dc0f553c63428db">llvm::MCAsmInfo::MaxInstLength</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#a98f40236cfff7278d4b57633fad2245d">llvm::MCAsmInfo::SupportsDebugInformation</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84a1e96588966115565402c00e156423f65">llvm::ZOS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isAcceptableChar() {#a294a0de1718ea4d11c79b95a55fe5b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZMCAsmInfoGOFF::isAcceptableChar (char C)</td>
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

<p>Return true if C is an acceptable character inside a symbol name.</p>

<p>Declaration at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-h">SystemZMCAsmInfo.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-cpp">SystemZMCAsmInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#aa6763a5ef33c11d633ff098c1b5c4a1a">llvm::MCAsmInfo::isAcceptableChar</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-cpp">SystemZMCAsmInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/lib/target/systemz/mctargetdesc/systemzmcasminfo-h">SystemZMCAsmInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
