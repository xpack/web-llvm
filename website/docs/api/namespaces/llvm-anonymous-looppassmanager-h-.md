---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/anonymous-looppassmanager-h-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{LoopPassManager.h}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::anonymous{LoopPassManager.h} { ... }
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename PassT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af6eec826c5aeacabf6df4ebbc4542183">HasRunOnLoopT</a> = decltype(std::declval&lt; PassT &gt;().run( std::declval&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; &gt;(), std::declval&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a58dde534a0ea2a23cb6c779c5c283f75">LoopAnalysisManager</a> &amp; &gt;(), std::declval&lt; <a href="/web-llvm/docs/api/structs/llvm/loopstandardanalysisresults">LoopStandardAnalysisResults</a> &amp; &gt;(), std::declval&lt; <a href="/web-llvm/docs/api/classes/llvm/lpmupdater">LPMUpdater</a> &amp; &gt;()))</td>
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

## Typedefs

### HasRunOnLoopT {#af6eec826c5aeacabf6df4ebbc4542183}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename PassT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::anonymous{LoopPassManager.h}::HasRunOnLoopT =  decltype(std::declval&lt;PassT&gt;().run(
    std::declval&lt;Loop &amp;&gt;(), std::declval&lt;LoopAnalysisManager &amp;&gt;(),
    std::declval&lt;LoopStandardAnalysisResults &amp;&gt;(),
    std::declval&lt;LPMUpdater &amp;&gt;()))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">LoopPassManager.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/looppassmanager-h">LoopPassManager.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
