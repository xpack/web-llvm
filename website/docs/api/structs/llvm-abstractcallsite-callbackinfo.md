---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/abstractcallsite/callbackinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CallbackInfo` Struct Reference

<p>The encoding of a callback with regards to the underlying instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AbstractCallSite::CallbackInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">llvm/IR/AbstractCallSite.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca1c3789a06bd03293acd7799c82778">ParameterEncodingTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 0 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For direct/indirect calls the parameter encoding is empty. <a href="#a8ca1c3789a06bd03293acd7799c82778">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8ca1c3789a06bd03293acd7799c82778">ParameterEncodingTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8fe46b9cdbd737fe10dda57651d6027">ParameterEncoding</a></td>
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

<p>The encoding of a callback with regards to the underlying instruction.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ParameterEncodingTy {#a8ca1c3789a06bd03293acd7799c82778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::AbstractCallSite::CallbackInfo::ParameterEncodingTy =  SmallVector&lt;int, 0&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For direct/indirect calls the parameter encoding is empty.</p>


<p>If it is not, the abstract call site represents a callback. In that case, the first element of the encoding vector represents which argument of the call site CB is the callback callee. The remaining elements map parameters (identified by their position) to the arguments that will be passed through (also identified by position but in the call site instruction).</p>


<p>NOTE that we use LLVM argument numbers (starting at 0) and not clang/source argument numbers (starting at 1). The -1 entries represent unknown values that are passed to the callee.</p>


<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ParameterEncoding {#af8fe46b9cdbd737fe10dda57651d6027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParameterEncodingTy llvm::AbstractCallSite::CallbackInfo::ParameterEncoding</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/abstractcallsite-h">AbstractCallSite.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
