---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/scopedfatalerrorhandler
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ScopedFatalErrorHandler` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/scopedfatalerrorhandler">ScopedFatalErrorHandler</a> - This is a simple helper class which just calls install_fatal_error_handler in its constructor and remove_fatal_error_handler in its destructor. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ScopedFatalErrorHandler { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d58ae60a445b2ac50c74d4fb295935">ScopedFatalErrorHandler</a> (fatal_error_handler_t handler, void *user_data=nullptr)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d9e4e112d5448ea58d065dd9696598">~ScopedFatalErrorHandler</a> ()</td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/scopedfatalerrorhandler">ScopedFatalErrorHandler</a> - This is a simple helper class which just calls install_fatal_error_handler in its constructor and remove_fatal_error_handler in its destructor.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">ErrorHandling.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ScopedFatalErrorHandler() {#ab6d58ae60a445b2ac50c74d4fb295935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScopedFatalErrorHandler::ScopedFatalErrorHandler (<a href="/web-llvm/docs/api/namespaces/llvm/#a2965d7e028169f52bdc0f73a65617340">fatal_error_handler_t</a> handler, void * user_data=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">ErrorHandling.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a2aeb96bbf49b1dd8f8a6cf1ceb4e86a7">llvm::install_fatal_error_handler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ScopedFatalErrorHandler() {#a74d9e4e112d5448ea58d065dd9696598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScopedFatalErrorHandler::~ScopedFatalErrorHandler ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">ErrorHandling.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abdb4f14b8a339d669818c3c274d1add3">llvm::remove_fatal_error_handler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">ErrorHandling.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
