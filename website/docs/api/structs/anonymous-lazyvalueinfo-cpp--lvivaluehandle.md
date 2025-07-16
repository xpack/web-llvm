---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-lazyvalueinfo-cpp-/lvivaluehandle
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LVIValueHandle` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{LazyValueInfo.cpp}::LVIValueHandle { ... }
</div>

## Base struct

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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b44d2c9f51a87067e4839084626bb06">LVIValueHandle</a> (Value *V, LazyValueInfoCache *P=nullptr)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c692693c243dd89dd5909448d49159">deleted</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for Value destruction. <a href="#a04c692693c243dd89dd5909448d49159">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e2c302e5be1c52548682f51a085b972">allUsesReplacedWith</a> (Value *V) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for Value RAUW. <a href="#a1e2c302e5be1c52548682f51a085b972">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache">LazyValueInfoCache</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5094376f0864d756452fe7f2acf284bf">Parent</a></td>
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


<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LVIValueHandle() {#a3b44d2c9f51a87067e4839084626bb06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LazyValueInfo.cpp}::LVIValueHandle::LVIValueHandle (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/anonymous-lazyvalueinfo-cpp-/lazyvalueinfocache">LazyValueInfoCache</a> * P=nullptr)</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">llvm::CallbackVH::CallbackVH</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a5094376f0864d756452fe7f2acf284bf">Parent</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allUsesReplacedWith() {#a1e2c302e5be1c52548682f51a085b972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{LazyValueInfo.cpp}::LVIValueHandle::allUsesReplacedWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)</td>
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

<p>Callback for Value RAUW.</p>


<p>Called when this-&gt;<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a>-&gt;replaceAllUsesWith(new_value) is called, <em>before</em> any of the uses have actually been replaced. If WeakTrackingVH were implemented as a CallbackVH, it would use this method to call setValPtr(new_value). AssertingVH would do nothing in this method.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>References <a href="#a04c692693c243dd89dd5909448d49159">deleted</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

### deleted() {#a04c692693c243dd89dd5909448d49159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LVIValueHandle::deleted ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback for Value destruction.</p>


<p>Called when this-&gt;<a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a> is destroyed, inside ~Value(), so you may call any non-virtual Value method on <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">getValPtr()</a>, but no subclass methods. If WeakTrackingVH were implemented as a CallbackVH, it would use this method to call setValPtr(NULL). AssertingVH would use this method to cause an assertion failure.</p>


<p>All implementations must remove the reference from this object to the Value that's being destroyed.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>Reference <a href="#a5094376f0864d756452fe7f2acf284bf">Parent</a>.</p>


<p>Referenced by <a href="#a1e2c302e5be1c52548682f51a085b972">allUsesReplacedWith</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Parent {#a5094376f0864d756452fe7f2acf284bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LazyValueInfoCache* anonymous{LazyValueInfo.cpp}::LVIValueHandle::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a>.</p>


<p>Referenced by <a href="#a04c692693c243dd89dd5909448d49159">deleted</a> and <a href="#a3b44d2c9f51a87067e4839084626bb06">LVIValueHandle</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp">LazyValueInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
