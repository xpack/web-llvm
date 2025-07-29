---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `FunctionImportUtils.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/functionimportutils-h">llvm/Transforms/Utils/FunctionImportUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cf73e5c2f477f5a3fbc3374dc82791">UseSourceFilenameForPromotedLocals</a>("use-source-filename-for-promoted-locals", cl::Hidden, cl::desc("Uses the source file name instead of the Module hash. " "This requires that the source filename has a unique name / " "path to avoid name collisions."))</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Uses the "source_filename" instead of a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> hash <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the suffix of promoted locals during LTO. <a href="#a12cf73e5c2f477f5a3fbc3374dc82791">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Variables

### UseSourceFilenameForPromotedLocals {#a12cf73e5c2f477f5a3fbc3374dc82791}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; UseSourceFilenameForPromotedLocals("use-source-filename-for-promoted-locals", cl::Hidden, cl::desc("Uses the source file name instead of the Module hash. " "This requires that the source filename has a unique name / " "path to avoid name collisions."))</td>
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

<p>Uses the "source_filename" instead of a <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> hash <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the suffix of promoted locals during LTO.</p>


<p>NOTE: This requires that the source filename has a unique name / path to avoid name collisions.</p>


<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/functionimportutils-cpp">FunctionImportUtils.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
