---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/trailing-objects-internal/trailingobjectsimpl-d5dc5f9bc1738bd42d17ac7472482035
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TrailingObjectsImpl` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;int Align, typename BaseTy, typename TopTrailingObj, typename PrevTy, typename NextTy, typename... MoreTys&gt;
class llvm::trailing_objects_internal::TrailingObjectsImpl&lt;Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys...&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">llvm/Support/TrailingObjects.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/trailingobjectsimpl">TrailingObjectsImpl&lt;Align, BaseTy, TopTrailingObj, PrevTy, MoreTys&gt;</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/trailingobjectsimpl">TrailingObjectsImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/align">Align</a>, BaseTy, TopTrailingObj, NextTy, MoreTys... &gt; <a href="#a838b45a119d6ec91b52b5e804c67b5c7">ParentType</a></td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> NextTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a20f5f514b0855117c9f1bf769bcb627b">getTrailingObjectsImpl</a> (const BaseTy *Obj, TrailingObjectsBase::OverloadToken&lt; NextTy &gt;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static NextTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4777f416777ffb24914b0d4717585dbb">getTrailingObjectsImpl</a> (BaseTy *Obj, TrailingObjectsBase::OverloadToken&lt; NextTy &gt;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a400e94cc828cf6b7a65fea0d90b2b27f">additionalSizeToAllocImpl</a> (size_t SizeSoFar, size_t Count1, typename ExtractSecondType&lt; MoreTys, size_t &gt;::type... MoreCounts)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3ca2a35a81d5a68e2e629f8343c2b626">requiresRealignment</a> ()</td>
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


<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ParentType {#a838b45a119d6ec91b52b5e804c67b5c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Align, typename BaseTy, typename TopTrailingObj, typename PrevTy, typename NextTy, typename... MoreTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef TrailingObjectsImpl&lt;Align, BaseTy, TopTrailingObj, NextTy, MoreTys...&gt; llvm::trailing_objects_internal::TrailingObjectsImpl&lt; Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys... &gt;::ParentType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### additionalSizeToAllocImpl() {#a400e94cc828cf6b7a65fea0d90b2b27f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Align, typename BaseTy, typename TopTrailingObj, typename PrevTy, typename NextTy, typename... MoreTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr size_t llvm::trailing_objects_internal::TrailingObjectsImpl&lt; Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys... &gt;::additionalSizeToAllocImpl (size_t SizeSoFar, size_t Count1, typename <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/extractsecondtype">ExtractSecondType</a>&lt; MoreTys, size_t &gt;::type... MoreCounts)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>.</p>

</div>
</div>

### getTrailingObjectsImpl() {#a20f5f514b0855117c9f1bf769bcb627b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Align, typename BaseTy, typename TopTrailingObj, typename PrevTy, typename NextTy, typename... MoreTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NextTy * llvm::trailing_objects_internal::TrailingObjectsImpl&lt; Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys... &gt;::getTrailingObjectsImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseTy * Obj, <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">TrailingObjectsBase::OverloadToken</a>&lt; NextTy &gt;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a35d8c4da117386fb67db052a36ecce50">llvm::Align::Of</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

### getTrailingObjectsImpl() {#a4777f416777ffb24914b0d4717585dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Align, typename BaseTy, typename TopTrailingObj, typename PrevTy, typename NextTy, typename... MoreTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NextTy * llvm::trailing_objects_internal::TrailingObjectsImpl&lt; Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys... &gt;::getTrailingObjectsImpl (BaseTy * Obj, <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">TrailingObjectsBase::OverloadToken</a>&lt; NextTy &gt;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#afff5074588f0423a669618a7134e13ec">llvm::alignAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/align/#a35d8c4da117386fb67db052a36ecce50">llvm::Align::Of</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### requiresRealignment() {#a3ca2a35a81d5a68e2e629f8343c2b626}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;int Align, typename BaseTy, typename TopTrailingObj, typename PrevTy, typename NextTy, typename... MoreTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr bool llvm::trailing_objects_internal::TrailingObjectsImpl&lt; Align, BaseTy, TopTrailingObj, PrevTy, NextTy, MoreTys... &gt;::requiresRealignment ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
