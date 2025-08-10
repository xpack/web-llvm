---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/once-flag
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `once_flag` Struct

<p>The <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a> structure. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::once_flag { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">llvm/Support/Threading.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">volatile <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2311d06f966c58f271076e6b262fa092">sys::cas_flag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82f54c87a27d58ef5f372cabf0fcbcfc">status</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa040b97f9fe2d19769ff2f593111e416f">Uninitialized</a></td>
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

<p>The <a href="/web-llvm/docs/api/structs/llvm/once-flag">llvm::once_flag</a> structure.</p>


<p>This type is modeled after std::once_flag to use with <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>. This structure must be used as an opaque object. It is a struct to force autoinitialization and behave like std::once_flag.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### status {#a82f54c87a27d58ef5f372cabf0fcbcfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">volatile sys::cas_flag llvm::once_flag::status = <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fa040b97f9fe2d19769ff2f593111e416f">Uninitialized</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#abc08edd3ca31ae54f1a794719c4c153c">llvm::call_once</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/threading-h">Threading.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
