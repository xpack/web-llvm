---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ReleaseModeModelRunner.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringextras-h">llvm/ADT/StringExtras.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/mlmodelrunner-h">llvm/Analysis/MLModelRunner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/tensorspec-h">llvm/Analysis/TensorSpec.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/md5-h">llvm/Support/MD5.h</a>"
#include &lt;memory&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/embeddedmodelrunneroptions">EmbeddedModelRunnerOptions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/releasemodemodelrunner">ReleaseModeModelRunner</a> - production mode implementation of the <a href="/web-llvm/docs/api/classes/llvm/mlmodelrunner">MLModelRunner</a>. <a href="/web-llvm/docs/api/structs/llvm/embeddedmodelrunneroptions/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/releasemodemodelrunner">ReleaseModeModelRunner&lt;TGen&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/noopsavedmodelimpl">NoopSavedModelImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A mock class satisfying the interface expected by <a href="/web-llvm/docs/api/classes/llvm/releasemodemodelrunner">ReleaseModeModelRunner</a> for its <span class="doxyComputerOutput">TGen</span> parameter. <a href="/web-llvm/docs/api/classes/llvm/noopsavedmodelimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7f87ff3f5204b0233b4968f5c9cfb8">NOOP_MODEL_ERRMSG</a>&nbsp;&nbsp;&nbsp;...</td>
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

### NOOP\_MODEL\_ERRMSG {#a9d7f87ff3f5204b0233b4968f5c9cfb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define NOOP_MODEL_ERRMSG&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  "The mock AOT-ed saved model is a compile-time stub and should not be "      \
  "called."
</div>
</dd>
</dl>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/releasemodemodelrunner-h">ReleaseModeModelRunner.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/noopsavedmodelimpl/#a99beec9f2fb96734c7e0c532ef38b858">llvm::NoopSavedModelImpl::arg_data</a>, <a href="/web-llvm/docs/api/classes/llvm/noopsavedmodelimpl/#a1ebe0f1ff4e9e25e69948fa8e97b71af">llvm::NoopSavedModelImpl::LookupArgIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/noopsavedmodelimpl/#adf0ec42cf1b987567c853140f8ce29f7">llvm::NoopSavedModelImpl::LookupResultIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/noopsavedmodelimpl/#aa0241e765326c23403358fa739029fa9">llvm::NoopSavedModelImpl::result_data</a> and <a href="/web-llvm/docs/api/classes/llvm/noopsavedmodelimpl/#a419e1cbbcb7dbf5ac884e5245fec8165">llvm::NoopSavedModelImpl::Run</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
