---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/valuemapcallbackvh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ValueMapCallbackVH` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename KeyT, typename ValueT, typename Config&gt;
class llvm::ValueMapCallbackVH&lt;KeyT, ValueT, Config&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">llvm/IR/ValueMap.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle with callbacks on RAUW and destruction. <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4c5167e0e3ef7c06c4f255fb05390832">ValueMapT</a> = <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>&lt; KeyT, ValueT, Config &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a53cd6fdeef6c69c0a22c51cc450e1b1f">KeySansPointerT</a> = std::remove_pointer_t&lt; KeyT &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04762a324bf2e6e82b79dbcd8c4b4d55">ValueMap&lt; KeyT, ValueT, Config &gt;</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6198f1d5a96a85cf17df1abcbef9745f">DenseMapInfo&lt; ValueMapCallbackVH &gt;</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1cefacc58b46b796b888f966990258c8">ValueMapCallbackVH</a> (KeyT Key, ValueMapT *Map)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa370ea6c95290e176e514191253a7585">ValueMapCallbackVH</a> (Value *V)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">KeyT</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b6c5945f932c835ec27c368ef5e4cc7">Unwrap</a> () const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aea4ea133ec6b6bf6bf86d7960fe882fb">deleted</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> destruction. <a href="#aea4ea133ec6b6bf6bf86d7960fe882fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a864656b46737a285671cb60274a78ab1">allUsesReplacedWith</a> (Value *new_key) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> RAUW. <a href="#a864656b46737a285671cb60274a78ab1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename KeyT, typename ValueT, typename Config&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMapT</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad5f1b454199591d015332e72b8265b2c">Map</a></td>
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


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### KeySansPointerT {#a53cd6fdeef6c69c0a22c51cc450e1b1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::KeySansPointerT =  std::remove_pointer_t&lt;KeyT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

### ValueMapT {#a4c5167e0e3ef7c06c4f255fb05390832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::ValueMapT =  ValueMap&lt;KeyT, ValueT, Config&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DenseMapInfo&lt; ValueMapCallbackVH &gt; {#a6198f1d5a96a85cf17df1abcbef9745f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/valuemapcallbackvh">ValueMapCallbackVH</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

### ValueMap&lt; KeyT, ValueT, Config &gt; {#a04762a324bf2e6e82b79dbcd8c4b4d55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>&lt; KeyT, ValueT, Config &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ValueMapCallbackVH() {#a1cefacc58b46b796b888f966990258c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::ValueMapCallbackVH (KeyT Key, <a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMapT</a> * Map)</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

### ValueMapCallbackVH() {#aa370ea6c95290e176e514191253a7585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::ValueMapCallbackVH (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allUsesReplacedWith() {#a864656b46737a285671cb60274a78ab1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::allUsesReplacedWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback for <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> RAUW.</p>


<p>Called when this-&gt;<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a>-&gt;replaceAllUsesWith(new_value) is called, <em>before</em> any of the uses have actually been replaced. If <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> were implemented as a <a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a>, it would use this method to call setValPtr(new_value). <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a> would do nothing in this method.</p>


<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### deleted() {#aea4ea133ec6b6bf6bf86d7960fe882fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::deleted ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback for <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> destruction.</p>


<p>Called when this-&gt;<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a> is destroyed, inside ~Value(), so you may call any non-virtual <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> method on <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a>, but no subclass methods. If <a href="/web-llvm/docs/api/classes/llvm/weaktrackingvh">WeakTrackingVH</a> were implemented as a <a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a>, it would use this method to call setValPtr(NULL). <a href="/web-llvm/docs/api/classes/llvm/assertingvh">AssertingVH</a> would use this method to cause an assertion failure.</p>


<p>All implementations must remove the reference from this object to the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> that's being destroyed.</p>


<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

### Unwrap() {#a1b6c5945f932c835ec27c368ef5e4cc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">KeyT llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::Unwrap ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">llvm::ValueHandleBase::getValPtr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-cf976c6008d17910e6e4c099545e7635/#ac6bcc5488bf59d6bb2a04bb8cad5c86e">llvm::DenseMapInfo&lt; ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt; &gt;::getHashValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Map {#ad5f1b454199591d015332e72b8265b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename KeyT, typename ValueT, typename Config&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMapT* llvm::ValueMapCallbackVH&lt; KeyT, ValueT, Config &gt;::Map</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuemap-h">ValueMap.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
