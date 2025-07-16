---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/bfi-detail/bficallbackvh-49ff4c89ffda7f9a22c66676f1ddc8f8
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BFICallbackVH` Class Template Reference



## Declaration

<div class="doxyDeclaration">
template &lt;class BFIImplT&gt;
class llvm::bfi_detail::BFICallbackVH&lt;BasicBlock, BFIImplT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">llvm/Analysis/BlockFrequencyInfoImpl.h</a>"
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BFIImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ac263bfae10c34b4cb6c087e3811e2b72">BFICallbackVH</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BFIImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8250c86c5e4911c3c202a531cd95f5b9">BFICallbackVH</a> (const BasicBlock *BB, BFIImplT *BFIImpl)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BFIImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8b30f746394608ef7b8ec0fe8586315c">~BFICallbackVH</a> ()=default</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BFIImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a399fe6c055fa8053a5302a00cd29f8f1">deleted</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> destruction. <a href="#a399fe6c055fa8053a5302a00cd29f8f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class BFIImplT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BFIImplT *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab3da7a81b02b29c2dfcc3fea0635cd11">BFIImpl</a></td>
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


<p>Definition at line 1074 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BFICallbackVH() {#ac263bfae10c34b4cb6c087e3811e2b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BFIImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::bfi_detail::BFICallbackVH&lt; BasicBlock, BFIImplT &gt;::BFICallbackVH ()</td>
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



<p>Definition at line 1078 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

### BFICallbackVH() {#a8250c86c5e4911c3c202a531cd95f5b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BFIImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::bfi_detail::BFICallbackVH&lt; BasicBlock, BFIImplT &gt;::BFICallbackVH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, BFIImplT * BFIImpl)</td>
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



<p>Definition at line 1080 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/callbackvh/#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">llvm::CallbackVH::CallbackVH</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BFICallbackVH() {#a8b30f746394608ef7b8ec0fe8586315c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BFIImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::bfi_detail::BFICallbackVH&lt; BasicBlock, BFIImplT &gt;::~BFICallbackVH ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1083 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### deleted() {#a399fe6c055fa8053a5302a00cd29f8f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BFIImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::bfi_detail::BFICallbackVH&lt; BasicBlock, BFIImplT &gt;::deleted ()</td>
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


<p>Definition at line 1085 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">llvm::ValueHandleBase::getValPtr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BFIImpl {#ab3da7a81b02b29c2dfcc3fea0635cd11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class BFIImplT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BFIImplT* llvm::bfi_detail::BFICallbackVH&lt; BasicBlock, BFIImplT &gt;::BFIImpl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1075 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/blockfrequencyinfoimpl-h">BlockFrequencyInfoImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
