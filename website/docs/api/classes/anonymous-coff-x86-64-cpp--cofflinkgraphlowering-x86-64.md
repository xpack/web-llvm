---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-coff-x86-64-cpp-/cofflinkgraphlowering-x86-64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `COFFLinkGraphLowering_x86_64` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{COFF_x86_64.cpp}::COFFLinkGraphLowering_x86_64 { ... }
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c3ad7e3022968cc44c435a1afa9c0a0">operator()</a> (LinkGraph &amp;G)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45776c0a2dccfc948149048e58ee0279">getSectionStart</a> (Section &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/getimagebasesymbol">GetImageBaseSymbol</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe4ee2d6b68ebea74bc7e0ce2c8d6d2a">GetImageBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> *, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a675aa13a666564db08dd620ce6d6a">SectionStartCache</a></td>
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


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/coff-x86-64-cpp">COFF_x86_64.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator()() {#a4c3ad7e3022968cc44c435a1afa9c0a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{COFF_x86_64.cpp}::COFFLinkGraphLowering_x86_64::operator() (<a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> &amp; G)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/coff-x86-64-cpp">COFF_x86_64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-coff-x86-64-cpp-/#a016c26c55bffa3e279cdd6186de666aeaab29b4db50e2f232e346ac5ec2d16cd1">anonymous{COFF_x86_64.cpp}::PCRel32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1a7cb0483abb6a27356f946cb706c696a9">llvm::jitlink::x86_64::PCRel32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1a9373b13e8458a9e8381f56fc053a90fb">llvm::jitlink::x86_64::Pointer16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1a12f965819db53282535bd5766d5783e3">llvm::jitlink::x86_64::Pointer32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-coff-x86-64-cpp-/#a016c26c55bffa3e279cdd6186de666aea5240801095e25e9bcd4110ec9398ef28">anonymous{COFF_x86_64.cpp}::Pointer32NB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-coff-x86-64-cpp-/#a016c26c55bffa3e279cdd6186de666aea201433a0059c2d563b95c13b80825fd1">anonymous{COFF_x86_64.cpp}::Pointer64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/x86-64/#aebb5822f6bda55afbca20f322d73a2a1aa9b0fce35f44572f2bddf0fe8a2c64e4">llvm::jitlink::x86_64::Pointer64</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-coff-x86-64-cpp-/#a016c26c55bffa3e279cdd6186de666aea336ad9a10983e848ad5fdd665a267b3b">anonymous{COFF_x86_64.cpp}::SecRel32</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-coff-x86-64-cpp-/#a016c26c55bffa3e279cdd6186de666aea09a39ab6dbcb675da9cd177c7aa400cf">anonymous{COFF_x86_64.cpp}::SectionIdx16</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getSectionStart() {#a45776c0a2dccfc948149048e58ee0279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::ExecutorAddr anonymous{COFF_x86_64.cpp}::COFFLinkGraphLowering_x86_64::getSectionStart (<a href="/web-llvm/docs/api/classes/llvm/jitlink/section">Section</a> &amp; Sec)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/coff-x86-64-cpp">COFF_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GetImageBase {#afe4ee2d6b68ebea74bc7e0ce2c8d6d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GetImageBaseSymbol anonymous{COFF_x86_64.cpp}::COFFLinkGraphLowering_x86_64::GetImageBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/coff-x86-64-cpp">COFF_x86_64.cpp</a>.</p>

</div>
</div>

### SectionStartCache {#af6a675aa13a666564db08dd620ce6d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Section *, orc::ExecutorAddr&gt; anonymous{COFF_x86_64.cpp}::COFFLinkGraphLowering_x86_64::SectionStartCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/coff-x86-64-cpp">COFF_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/coff-x86-64-cpp">COFF_x86_64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
