---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/riscvisautils-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `RISCVISAUtils.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/riscvisautils-h">llvm/Support/RISCVISAUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include &lt;cassert&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RankFlags { <a href="#ad985e2964c8c714cb0312dafaa297495">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0834ffd88d8197c3afbc8c356cfb27a">singleLetterExtensionRank</a> (char Ext)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf45c1638338f84c631d8f5a361fbf86">getExtensionRank</a> (const std::string &amp;ExtName)</td>
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

### RankFlags {#ad985e2964c8c714cb0312dafaa297495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum RankFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RF_Z_EXTENSION<a id="ad985e2964c8c714cb0312dafaa297495a68a40174d0ff37479b909d1ac5281e40"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RF_S_EXTENSION<a id="ad985e2964c8c714cb0312dafaa297495a4ffa824323e90c1aff1a555c1ebe14a3"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RF_X_EXTENSION<a id="ad985e2964c8c714cb0312dafaa297495add196453043c53c04fceb7352e921495"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RF_UNKNOWN_MULTILETTER_EXTENSION<a id="ad985e2964c8c714cb0312dafaa297495ad3e762400207d4f229b732e90407c487"></a></td>
<td class="doxyEnumItemDescription"> (= 4 &lt;&lt; 6)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp">RISCVISAUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getExtensionRank() {#adf45c1638338f84c631d8f5a361fbf86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getExtensionRank (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &amp; ExtName)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp">RISCVISAUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad985e2964c8c714cb0312dafaa297495a4ffa824323e90c1aff1a555c1ebe14a3">RF_S_EXTENSION</a>, <a href="#ad985e2964c8c714cb0312dafaa297495ad3e762400207d4f229b732e90407c487">RF_UNKNOWN_MULTILETTER_EXTENSION</a>, <a href="#ad985e2964c8c714cb0312dafaa297495add196453043c53c04fceb7352e921495">RF_X_EXTENSION</a>, <a href="#ad985e2964c8c714cb0312dafaa297495a68a40174d0ff37479b909d1ac5281e40">RF_Z_EXTENSION</a> and <a href="#ae0834ffd88d8197c3afbc8c356cfb27a">singleLetterExtensionRank</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/riscvisautils/#a654410af74995521d4f50201f8d88368">llvm::RISCVISAUtils::compareExtension</a>.</p>

</div>
</div>

### singleLetterExtensionRank() {#ae0834ffd88d8197c3afbc8c356cfb27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned singleLetterExtensionRank (char Ext)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/support/riscvisautils-cpp">RISCVISAUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/riscvisautils/#a065d642864b925bfe666f5faf6020165">llvm::RISCVISAUtils::AllStdExts</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a29d963f204d5c763f085c427876edfa7">llvm::isLower</a> and <a href="/web-llvm/docs/api/classes/anonymous-path-cpp-/stringref/#ad0f54a163ac500b144590640c6f1eb6b">anonymous{Path.cpp}::StringRef::npos</a>.</p>


<p>Referenced by <a href="#adf45c1638338f84c631d8f5a361fbf86">getExtensionRank</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
