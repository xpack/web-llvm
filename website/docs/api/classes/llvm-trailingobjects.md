---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/trailingobjects
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TrailingObjects` Class Template Reference

<p>See the file comment for details on the usage of the <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename BaseTy, typename... TrailingTys&gt;
class llvm::TrailingObjects&lt;BaseTy, TrailingTys&gt; { ... }
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/trailingobjectsimpl">trailing_objects_internal::TrailingObjectsImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/alignmentcalchelper">trailing_objects_internal::AlignmentCalcHelper</a>&lt; TrailingTys... &gt;::Alignment, BaseTy, <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a>&lt; BaseTy, TrailingTys... &gt;, BaseTy, TrailingTys... &gt; <a href="#a8f89e2371726a185d106d246f797d0c6">ParentType</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad386e759886338dd62855c2bb13561d1">TrailingObjectsBase</a> = <a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/trailingobjectsbase">trailing_objects_internal::TrailingObjectsBase</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;int A, typename B, typename T, typename P, typename... M&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a309b74e3d99ea55a89fd4479204af67a">trailing_objects_internal::TrailingObjectsImpl</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#accd664b9851260e5905e27962e1fad3a">TrailingObjects</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad4cd65fc17ab07da90e7da0bae1ce35d">TrailingObjects</a> (const TrailingObjects &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aad667619865a54811fa04e8677a8b8c8">TrailingObjects</a> (TrailingObjects &amp;&amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7bd76c167e117ea61c23f01539e033c3">operator=</a> (const TrailingObjects &amp;)=delete</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a101c322d5e3d8dd4f00412a5151f9110">operator=</a> (TrailingObjects &amp;&amp;)=delete</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5f3828c41150c05c9b8142e98c35218">getTrailingObjects</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the trailing object array of the given type (which must be one of those specified in the class template). <a href="#ab5f3828c41150c05c9b8142e98c35218">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">T *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab56bb6c417717ab6db8bd093837dd208">getTrailingObjects</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the trailing object array of the given type (which must be one of those specified in the class template). <a href="#ab56bb6c417717ab6db8bd093837dd208">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Tys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a94ff4239f8807df0db66ade77e6b4f29">additionalSizeToAlloc</a> (typename trailing_objects_internal::ExtractSecondType&lt; TrailingTys, size_t &gt;::type... Counts) -&gt; std::enable_if_t&lt; std::is_same_v&lt; Foo&lt; TrailingTys... &gt;, Foo&lt; Tys... &gt; &gt;, size_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size of the trailing data, if an object were allocated with the given counts (The counts are in the same order as the template arguments). <a href="#a94ff4239f8807df0db66ade77e6b4f29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Tys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b733cf2a7d7206c2d2601cc5b024488">totalSizeToAlloc</a> (typename trailing_objects_internal::ExtractSecondType&lt; TrailingTys, size_t &gt;::type... Counts) -&gt; std::enable_if_t&lt; std::is_same_v&lt; Foo&lt; TrailingTys... &gt;, Foo&lt; Tys... &gt; &gt;, size_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the total size of an object if it were allocated with the given trailing object counts. <a href="#a5b733cf2a7d7206c2d2601cc5b024488">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6a47b68a66dc2135727d43f96b9fd469">verifyTrailingObjectsAssertions</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a31866ede7f0d5f5d4471732b4e5cce6c">getTrailingObjectsImpl</a> (const BaseTy *Obj, TrailingObjectsBase::OverloadToken&lt; BaseTy &gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static BaseTy *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acad72463b2f37d4f905a11046306cfaa">getTrailingObjectsImpl</a> (BaseTy *Obj, TrailingObjectsBase::OverloadToken&lt; BaseTy &gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BaseTy, typename... TrailingTys&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3d3faa0d97b9d17b31ce8110f7f3d027">callNumTrailingObjects</a> (const BaseTy *Obj, TrailingObjectsBase::OverloadToken&lt; BaseTy &gt;)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a903d473e5ee4bddafec815f893105399">callNumTrailingObjects</a> (const BaseTy *Obj, TrailingObjectsBase::OverloadToken&lt; T &gt;)</td>
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

<p>See the file comment for details on the usage of the <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> type.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ParentType {#a8f89e2371726a185d106d246f797d0c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef trailing_objects_internal::TrailingObjectsImpl&lt; trailing_objects_internal::AlignmentCalcHelper&lt;TrailingTys...&gt;::Alignment, BaseTy, TrailingObjects&lt;BaseTy, TrailingTys...&gt;, BaseTy, TrailingTys...&gt; llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::ParentType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

### TrailingObjectsBase {#ad386e759886338dd62855c2bb13561d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjectsBase =  trailing_objects_internal::TrailingObjectsBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### trailing\_objects\_internal::TrailingObjectsImpl {#a309b74e3d99ea55a89fd4479204af67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/trailing-objects-internal/trailingobjectsimpl">trailing_objects_internal::TrailingObjectsImpl</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TrailingObjects() {#accd664b9851260e5905e27962e1fad3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Referenced by <a href="#a7bd76c167e117ea61c23f01539e033c3">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::operator=</a>, <a href="#a101c322d5e3d8dd4f00412a5151f9110">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::operator=</a>, <a href="#ad4cd65fc17ab07da90e7da0bae1ce35d">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects</a> and <a href="#aad667619865a54811fa04e8677a8b8c8">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects</a>.</p>

</div>
</div>

### TrailingObjects() {#ad4cd65fc17ab07da90e7da0bae1ce35d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Reference <a href="#accd664b9851260e5905e27962e1fad3a">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects</a>.</p>

</div>
</div>

### TrailingObjects() {#aad667619865a54811fa04e8677a8b8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects (<a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Reference <a href="#accd664b9851260e5905e27962e1fad3a">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a7bd76c167e117ea61c23f01539e033c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrailingObjects &amp; llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Reference <a href="#accd664b9851260e5905e27962e1fad3a">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects</a>.</p>

</div>
</div>

### operator=() {#a101c322d5e3d8dd4f00412a5151f9110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TrailingObjects &amp; llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::operator= (<a href="/web-llvm/docs/api/classes/llvm/trailingobjects">TrailingObjects</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Reference <a href="#accd664b9851260e5905e27962e1fad3a">llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::TrailingObjects</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getTrailingObjects() {#ab5f3828c41150c05c9b8142e98c35218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const T * llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::getTrailingObjects ()</td>
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

<p>Returns a pointer to the trailing object array of the given type (which must be one of those specified in the class template).</p>


<p>The array may have zero or more elements in it.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getTrailingObjects() {#ab56bb6c417717ab6db8bd093837dd208}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T * llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::getTrailingObjects ()</td>
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

<p>Returns a pointer to the trailing object array of the given type (which must be one of those specified in the class template).</p>


<p>The array may have zero or more elements in it.</p>


<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### additionalSizeToAlloc() {#a94ff4239f8807df0db66ade77e6b4f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Tys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr std::enable_if_t&lt; std::is_same_v&lt; Foo&lt; TrailingTys... &gt;, Foo&lt; Tys... &gt; &gt;, size_t &gt; llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::additionalSizeToAlloc (typename <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/extractsecondtype">trailing_objects_internal::ExtractSecondType</a>&lt; TrailingTys, size_t &gt;::type... Counts)</td>
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

<p>Returns the size of the trailing data, if an object were allocated with the given counts (The counts are in the same order as the template arguments).</p>


<p>This does not include the size of the base object. The template arguments must be the same as those used in the class; they are supplied here redundantly only so that it's clear what the counts are counting in callers.</p>


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

### totalSizeToAlloc() {#a5b733cf2a7d7206c2d2601cc5b024488}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Tys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr std::enable_if_t&lt; std::is_same_v&lt; Foo&lt; TrailingTys... &gt;, Foo&lt; Tys... &gt; &gt;, size_t &gt; llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::totalSizeToAlloc (typename <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/extractsecondtype">trailing_objects_internal::ExtractSecondType</a>&lt; TrailingTys, size_t &gt;::type... Counts)</td>
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

<p>Returns the total size of an object if it were allocated with the given trailing object counts.</p>


<p>This is the same as additionalSizeToAlloc, except it <em>does</em> include the size of the base object.</p>


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrangelistattributeimpl/#a86df45aa005496277266b034a8ddfdcd">llvm::ConstantRangeListAttributeImpl::totalSizeToAlloc</a> and <a href="/web-llvm/docs/api/classes/llvm/stringattributeimpl/#ad3ad8ac9b5c1d0ee83844044220d691c">llvm::StringAttributeImpl::totalSizeToAlloc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### callNumTrailingObjects() {#a3d3faa0d97b9d17b31ce8110f7f3d027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::callNumTrailingObjects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseTy * Obj, <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">TrailingObjectsBase::OverloadToken</a>&lt; BaseTy &gt;)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

### callNumTrailingObjects() {#a903d473e5ee4bddafec815f893105399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::callNumTrailingObjects (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseTy * Obj, <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">TrailingObjectsBase::OverloadToken</a>&lt; T &gt;)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

### getTrailingObjectsImpl() {#a31866ede7f0d5f5d4471732b4e5cce6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BaseTy * llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::getTrailingObjectsImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> BaseTy * Obj, <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">TrailingObjectsBase::OverloadToken</a>&lt; BaseTy &gt;)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

### getTrailingObjectsImpl() {#acad72463b2f37d4f905a11046306cfaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BaseTy * llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::getTrailingObjectsImpl (BaseTy * Obj, <a href="/web-llvm/docs/api/structs/llvm/trailing-objects-internal/trailingobjectsbase/overloadtoken">TrailingObjectsBase::OverloadToken</a>&lt; BaseTy &gt;)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

### verifyTrailingObjectsAssertions() {#a6a47b68a66dc2135727d43f96b9fd469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BaseTy, typename... TrailingTys&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TrailingObjects&lt; BaseTy, TrailingTys &gt;::verifyTrailingObjectsAssertions ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/trailingobjects-h">TrailingObjects.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
