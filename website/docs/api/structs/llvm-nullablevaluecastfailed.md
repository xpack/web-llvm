---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/nullablevaluecastfailed
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `NullableValueCastFailed` Struct Template Reference

<p>All of these cast traits are meant to be implementations for useful casts that users may want to use that are outside the standard behavior. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename To&gt;
struct llvm::NullableValueCastFailed&lt;To&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">llvm/Support/Casting.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/valuefrompointercast">ValueFromPointerCast&lt;To, From, Derived&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This cast trait provides casting for the specific case of casting to a value-typed object from a pointer-typed object. <a href="/web-llvm/docs/api/structs/llvm/valuefrompointercast/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename To&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static To</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a395343c9b06cb157bfe2ccc8b39d4572">castFailed</a> ()</td>
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

<p>All of these cast traits are meant to be implementations for useful casts that users may want to use that are outside the standard behavior.</p>


<p>An example of how to use a special cast called <span class="doxyComputerOutput">CastTrait</span> is:</p>


<p>template&lt;&gt; struct <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo&lt;foo, bar&gt;</a> : public CastTrait&lt;foo, bar&gt; {};</p>


<p>Essentially, if your use case falls directly into one of the use cases supported by a given cast trait, simply inherit your special <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo</a> directly from one of these to avoid having to reimplement the boilerplate <span class="doxyComputerOutput">isPossible/castFailed/doCast/doCastIfPossible</span>. A cast trait can also provide a subset of those functions. This cast trait just provides castFailed for the specified <span class="doxyComputerOutput">To</span> type to make <a href="/web-llvm/docs/api/structs/llvm/castinfo">CastInfo</a> specializations more declarative. In order to use this, the target result type must be <span class="doxyComputerOutput">To</span> and <span class="doxyComputerOutput">To</span> must be constructible from <span class="doxyComputerOutput">nullptr</span>.</p>


<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### castFailed() {#a395343c9b06cb157bfe2ccc8b39d4572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename To&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">To llvm::NullableValueCastFailed&lt; To &gt;::castFailed ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/casting-h">Casting.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
