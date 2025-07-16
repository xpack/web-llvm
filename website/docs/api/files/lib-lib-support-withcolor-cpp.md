---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/withcolor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `WithColor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/withcolor-h">llvm/Support/WithColor.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/support/debugoptions-h">DebugOptions.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/managedstatic-h">llvm/Support/ManagedStatic.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-withcolor-cpp-">anonymous{WithColor.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-withcolor-cpp-/createusecolor">CreateUseColor</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a217ca6e38806a2d0ea3712d69c0b06f6">DefaultAutoDetectFunction</a> (const raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/managedstatic">ManagedStatic</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44">cl::boolOrDefault</a> &gt;, CreateUseColor &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa02187bd9b39a38a9d8f65edf7995c8f">UseColor</a></td>
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

### DefaultAutoDetectFunction() {#a217ca6e38806a2d0ea3712d69c0b06f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefaultAutoDetectFunction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44ad7c4bd83c337c86d34f6c2d8eba1e736">llvm::cl::BOU_TRUE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/cl/#a9241f2e42b7587b123c885d7a659ad44aa5bd521ebe67ddf0e90f1a9e540a6d43">llvm::cl::BOU_UNSET</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#ae5c85e2158de685ed0c287a13c07ea49">llvm::raw_ostream::has_colors</a> and <a href="#aa02187bd9b39a38a9d8f65edf7995c8f">UseColor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#acc596b1a9d4cf50b3096702e25b42d70">llvm::WithColor::defaultAutoDetectFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### UseColor {#aa02187bd9b39a38a9d8f65edf7995c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ManagedStatic&lt;cl::opt&lt;cl::boolOrDefault&gt;, CreateUseColor&gt; UseColor</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp">WithColor.cpp</a>.</p>


<p>Referenced by <a href="#a217ca6e38806a2d0ea3712d69c0b06f6">DefaultAutoDetectFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0739379f5a2348f4a22afcfa79f7a41b">llvm::initWithColorOptions</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
