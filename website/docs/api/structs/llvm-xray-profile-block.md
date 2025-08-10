---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/xray/profile/block
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Block` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::xray::Profile::Block { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/profile-h">llvm/XRay/Profile.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/xray/profile/#a1175a81e557a905685674fb887f49176">ThreadID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0e28e54713a21bdc8ade4676643076">Thread</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::pair&lt; <a href="/web-llvm/docs/api/classes/llvm/xray/profile/#a61b53a1aaef1301a6bbd70c880789c0d">PathID</a>, <a href="/web-llvm/docs/api/structs/llvm/xray/profile/data">Data</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60d6984462ebf4f393e11aee27081f8b">PathData</a></td>
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


<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/profile-h">Profile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### PathData {#a60d6984462ebf4f393e11aee27081f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::pair&lt;PathID, Data&gt; &gt; llvm::xray::Profile::Block::PathData</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/profile-h">Profile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/xray/#a229677e06d6c451da4a65f045461967f">llvm::xray::mergeProfilesByStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xray/#adfd810967d993f91a4dc86c9bf728d4c">llvm::xray::mergeProfilesByThread</a> and <a href="/web-llvm/docs/api/classes/llvm/xray/profile/#abd02b54208ead98553182be8937f4def">llvm::xray::Profile::Profile</a>.</p>

</div>
</div>

### Thread {#a2a0e28e54713a21bdc8ade4676643076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadID llvm::xray::Profile::Block::Thread</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/profile-h">Profile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/xray/profile/#abd02b54208ead98553182be8937f4def">llvm::xray::Profile::Profile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/xray/profile-h">Profile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
