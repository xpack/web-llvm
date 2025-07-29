---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coroidasyncinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CoroIdAsyncInst` Class

<p>This represents the llvm.coro.id.async instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CoroIdAsyncInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">llvm/Transforms/Coroutines/CoroInstr.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/anycoroidinst">AnyCoroIdInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents a common base class for llvm.coro.id instructions. <a href="/web-llvm/docs/api/classes/llvm/anycoroidinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a9b727606f466aac93cca3376ae61a0c9">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa384a27e0cb9e2e608147d53aa927cdd">checkWellFormed</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4aa55b08cc5603ffda9ca544e37a24eb">getStorageSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The initial async function context size. <a href="#a4aa55b08cc5603ffda9ca544e37a24eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ffbc186a4ed0d6f9889272500784445">getStorageAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The alignment of the initial async function context. <a href="#a0ffbc186a4ed0d6f9889272500784445">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4248dcad0da8c436e26fc3bf1d013b3">getStorage</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The async context parameter. <a href="#ad4248dcad0da8c436e26fc3bf1d013b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae025aa6bb0adb37f2b51714181627bc9">getStorageArgumentIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab461e95beef7d14d7d648575035c5e63">getAsyncFunctionPointer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the async function pointer address. <a href="#ab461e95beef7d14d7d648575035c5e63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad31b4d3947ba504b1d22135ae55e2864">classof</a> (const IntrinsicInst *I)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64aa7f058cbbd61433db4d43cd80c2e">classof</a> (const Value *V)</td>
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

<p>This represents the llvm.coro.id.async instruction.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a9b727606f466aac93cca3376ae61a0c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SizeArg<a id="a9b727606f466aac93cca3376ae61a0c9a6005d6feae801fccd484bdcc032687d9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignArg<a id="a9b727606f466aac93cca3376ae61a0c9a40d1977820dc56d87ee11abf0ae65ac1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StorageArg<a id="a9b727606f466aac93cca3376ae61a0c9a9c14b90ecc5a9d5014423539806bfb3a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AsyncFuncPtrArg<a id="a9b727606f466aac93cca3376ae61a0c9acf442b2f01ced88318bf73d747b703f1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### checkWellFormed() {#aa384a27e0cb9e2e608147d53aa927cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CoroIdAsyncInst::checkWellFormed ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>, definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#afab9b41ee90b1a38be566c582f290272">checkAsyncFuncPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#a394e27f50c3da62b86bfa0dbac5cf847">checkConstantInt</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>

</div>
</div>

### getAsyncFunctionPointer() {#ab461e95beef7d14d7d648575035c5e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * llvm::CoroIdAsyncInst::getAsyncFunctionPointer ()</td>
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

<p>Return the async function pointer address.</p>


<p>This should be the address of a async function pointer struct for the current async function. struct async_function_pointer { uint32_t context_size; uint32_t relative_async_function_pointer; };</p>


<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a966eb231e7d4e572874d2cb49b18faea">llvm::Value::stripPointerCasts</a>.</p>

</div>
</div>

### getStorage() {#ad4248dcad0da8c436e26fc3bf1d013b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::CoroIdAsyncInst::getStorage ()</td>
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

<p>The async context parameter.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; ilist_node_impl&lt; ilist_detail::compute_node_options&lt; Instruction, Options... &gt;::type &gt;, ilist_detail::compute_node_options&lt; Instruction, Options... &gt;::type::parent_ty &gt;::getParent</a> and <a href="#ae025aa6bb0adb37f2b51714181627bc9">getStorageArgumentIndex</a>.</p>

</div>
</div>

### getStorageAlignment() {#a0ffbc186a4ed0d6f9889272500784445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::CoroIdAsyncInst::getStorageAlignment ()</td>
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

<p>The alignment of the initial async function context.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>

</div>
</div>

### getStorageArgumentIndex() {#ae025aa6bb0adb37f2b51714181627bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CoroIdAsyncInst::getStorageArgumentIndex ()</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>


<p>Referenced by <a href="#ad4248dcad0da8c436e26fc3bf1d013b3">getStorage</a>.</p>

</div>
</div>

### getStorageSize() {#a4aa55b08cc5603ffda9ca544e37a24eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CoroIdAsyncInst::getStorageSize ()</td>
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

<p>The initial async function context size.</p>


<p>The fields of which are reserved for use by the frontend. The frame will be allocated as a tail of this context.</p>


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#aabd76e6a8a23a5af1ce4d3c310d88bcd">llvm::CallBase::getArgOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad31b4d3947ba504b1d22135ae55e2864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoroIdAsyncInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * I)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#af64aa7f058cbbd61433db4d43cd80c2e">classof</a>.</p>

</div>
</div>

### classof() {#af64aa7f058cbbd61433db4d43cd80c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CoroIdAsyncInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad31b4d3947ba504b1d22135ae55e2864">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/coroutines/coroinstr-h">CoroInstr.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp">Coroutines.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
