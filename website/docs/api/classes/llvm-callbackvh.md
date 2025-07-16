---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/callbackvh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallbackVH` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle with callbacks on RAUW and destruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CallbackVH { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the common base class of value handles. <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-asmprinter-cpp-/addrlabelmapcallbackptr">AddrLabelMapCallbackPtr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/gvmemoryblock">GVMemoryBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class which uses a value handler to automatically deletes the memory block when the <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> is destroyed. <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/gvmemoryblock/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lvivaluehandle">LVIValueHandle</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/ivstrideuse">IVStrideUse</a> - Keep track of one use of a strided induction variable. <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/preservedcfgcheckerinstrumentation/bbguard">BBGuard</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This means that we are dealing with an entirely unknown <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> value, and only represent it as its LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemapcallbackvh">ValueMapCallbackVH&lt;KeyT, ValueT, Config&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bfi-detail/bficallbackvh-49ff4c89ffda7f9a22c66676f1ddc8f8">BFICallbackVH&lt;BasicBlock, BFIImplT&gt;</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b64e4dd7471ef330b74ec0d5f112e29">CallbackVH</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec3602ff26e2f61e14a777a511fbf11">CallbackVH</a> (Value *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3388197aa4f644d4e871c763b59875af">CallbackVH</a> (const Value *P)</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">CallbackVH</a> (const CallbackVH &amp;)=default</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae87f9079f52b7bcb09b7e20b7699a6db">~CallbackVH</a> ()=default</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc26426e370328a52e00ddb75a0dfbd">operator Value *</a> () const</td>
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

## Protected Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5054c2936d9b8f44278866dbdaed0c4c">operator=</a> (const CallbackVH &amp;)=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93891950be05a0bae5743979913e13f3">deleted</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> destruction. <a href="#a93891950be05a0bae5743979913e13f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f633ad5396b6726039d26f5bbac940d">allUsesReplacedWith</a> (Value *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback for <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> RAUW. <a href="#a1f633ad5396b6726039d26f5bbac940d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3a25e82043f8a99ad6ed61fb9c9483c">setValPtr</a> (Value *P)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5637a9dba5e86322763831c5851b2b">anchor</a> ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> handle with callbacks on RAUW and destruction.</p>


<p>This is a value handle that allows subclasses to define callbacks that run when the underlying <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> has RAUW called on it or is destroyed. This class can be used as the key of a map, as long as the user takes it out of the map before calling <a href="#ab3a25e82043f8a99ad6ed61fb9c9483c">setValPtr()</a> (since the map has to rearrange itself when the pointer changes). Unlike <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase">ValueHandleBase</a>, this class has a vtable.</p>


<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallbackVH() {#a8b64e4dd7471ef330b74ec0d5f112e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallbackVH::CallbackVH ()</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4da670860d51b165a2d146356622a256418">llvm::ValueHandleBase::Callback</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a>.</p>

</div>
</div>

### CallbackVH() {#a5ec3602ff26e2f61e14a777a511fbf11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallbackVH::CallbackVH (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P)</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#ae2f1a12c55f1c06acc38407b8627cb4da670860d51b165a2d146356622a256418">llvm::ValueHandleBase::Callback</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#afd6a51b0b16b598bc41a2b32c6d0030f">llvm::ValueHandleBase::ValueHandleBase</a>.</p>

</div>
</div>

### CallbackVH() {#a3388197aa4f644d4e871c763b59875af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallbackVH::CallbackVH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P)</td>
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



<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">CallbackVH</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### CallbackVH() {#a7e87f4bd72a4d8b7f092b2a2ee69ba1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallbackVH::CallbackVH (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>Reference <a href="#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">CallbackVH</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-asmprinter-cpp-/addrlabelmapcallbackptr/#ab40a1ce088eaee128432e229340ed971">anonymous{AsmPrinter.cpp}::AddrLabelMapCallbackPtr::AddrLabelMapCallbackPtr</a>, <a href="/web-llvm/docs/api/structs/llvm/preservedcfgcheckerinstrumentation/bbguard/#a0e987dcd8776df983519ccb9ce676dc2">llvm::PreservedCFGCheckerInstrumentation::BBGuard::BBGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/bfi-detail/bficallbackvh-49ff4c89ffda7f9a22c66676f1ddc8f8/#a8250c86c5e4911c3c202a531cd95f5b9">llvm::bfi_detail::BFICallbackVH&lt; BasicBlock, BFIImplT &gt;::BFICallbackVH</a>, <a href="#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">CallbackVH</a>, <a href="#a3388197aa4f644d4e871c763b59875af">CallbackVH</a>, <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse/#ac2140ae8507867b97114724c6a6dbbba">llvm::IVStrideUse::IVStrideUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-lazyvalueinfo-cpp-/lvivaluehandle/#a3b44d2c9f51a87067e4839084626bb06">anonymous{LazyValueInfo.cpp}::LVIValueHandle::LVIValueHandle</a>, <a href="#a5054c2936d9b8f44278866dbdaed0c4c">operator=</a> and <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a15a0237aaba54972c69acad43448c093">llvm::SCEVUnknown::ScalarEvolution</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~CallbackVH() {#ae87f9079f52b7bcb09b7e20b7699a6db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallbackVH::~CallbackVH ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator Value \*() {#a3cc26426e370328a52e00ddb75a0dfbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallbackVH::operator Value * ()</td>
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



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a7d6d2457c839e340266704440f3bb243">llvm::ValueHandleBase::getValPtr</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Operators

### operator=() {#a5054c2936d9b8f44278866dbdaed0c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallbackVH &amp; llvm::CallbackVH::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbackvh">CallbackVH</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>Reference <a href="#a7e87f4bd72a4d8b7f092b2a2ee69ba1d">CallbackVH</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### allUsesReplacedWith() {#a1f633ad5396b6726039d26f5bbac940d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::CallbackVH::allUsesReplacedWith (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *)</td>
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


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>

</div>
</div>

### deleted() {#a93891950be05a0bae5743979913e13f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::CallbackVH::deleted ()</td>
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


<p>Definition at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>Reference <a href="#ab3a25e82043f8a99ad6ed61fb9c9483c">setValPtr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/preservedcfgcheckerinstrumentation/bbguard/#aaafe4931c1319404db21c79560795b4b">llvm::PreservedCFGCheckerInstrumentation::BBGuard::allUsesReplacedWith</a> and <a href="/web-llvm/docs/api/structs/llvm/preservedcfgcheckerinstrumentation/bbguard/#a89d3be53f4de8d5fc26dcc771e3b7493">llvm::PreservedCFGCheckerInstrumentation::BBGuard::deleted</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### setValPtr() {#ab3a25e82043f8a99ad6ed61fb9c9483c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallbackVH::setValPtr (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * P)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#a700177b68c18b9e00893b747d3de1453">llvm::ValueHandleBase::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/classes/llvm/valuehandlebase/#aeceedf6e1a7d48a588516ce2b1983d6f">llvm::ValueHandleBase::Value</a>.</p>


<p>Referenced by <a href="#a93891950be05a0bae5743979913e13f3">deleted</a> and <a href="/web-llvm/docs/api/classes/llvm/ivstrideuse/#acb8718e691dfd2e5d5a3e0d876e35cc9">llvm::IVStrideUse::setUser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#a4c5637a9dba5e86322763831c5851b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallbackVH::anchor ()</td>
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



<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a>, definition at line 1312 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">ValueHandle.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp">Value.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
