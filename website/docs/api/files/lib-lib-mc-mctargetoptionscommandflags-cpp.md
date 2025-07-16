---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/mc/mctargetoptionscommandflags-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MCTargetOptionsCommandFlags.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptionscommandflags-h">llvm/MC/MCTargetOptionsCommandFlags.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mctargetoptions-h">llvm/MC/MCTargetOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4671e507da4a46e0d548bdecc791fb28">MCOPT</a>(TY, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ac610f85e8a3d19a82189f2a0a8866b">MCOPT_EXP</a>(TY, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fd5f66256790789a1eeac65e180d15">MCBINDOPT</a>(NAME)&nbsp;&nbsp;&nbsp;...</td>
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

## Macro Definitions

### MCBINDOPT {#a09fd5f66256790789a1eeac65e180d15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MCBINDOPT(NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  do {                                                                         \
    NAME##View = std::addressof(NAME);                                         \
  } <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmreflect-cpp/#a503c0214540e80733c0a0c53c067e6ee">while</a> (0)
</div>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mctargetoptionscommandflags-cpp">MCTargetOptionsCommandFlags.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/mc/registermctargetoptionsflags/#a0eae824471e397e289e1344efac6cb1c">llvm::mc::RegisterMCTargetOptionsFlags::RegisterMCTargetOptionsFlags</a>.</p>

</div>
</div>

### MCOPT {#a4671e507da4a46e0d548bdecc791fb28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MCOPT(TY, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt;TY&gt; *NAME##View;                                              \
  TY <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::mc::get</a>##NAME() {                                                   \
    <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>(NAME##View &amp;&amp; "RegisterMCTargetOptionsFlags not created.");         \
    return *NAME##View;                                                        \
  }
</div>
</dd>
</dl>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mctargetoptionscommandflags-cpp">MCTargetOptionsCommandFlags.cpp</a>.</p>

</div>
</div>

### MCOPT\_EXP {#a9ac610f85e8a3d19a82189f2a0a8866b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MCOPT_EXP(TY, NAME)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a4671e507da4a46e0d548bdecc791fb28">MCOPT</a>(TY, NAME)                                                              \
  std::optional&lt;TY&gt; llvm::mc::getExplicit##NAME() {                            \
    <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> (NAME##View-&gt;getNumOccurrences()) {                                     \
      TY res = *NAME##View;                                                    \
      return res;                                                              \
    }                                                                          \
    return std::nullopt;                                                       \
  }
</div>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mctargetoptionscommandflags-cpp">MCTargetOptionsCommandFlags.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
