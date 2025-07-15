---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-functionattrs-cpp-/argumentusestracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ArgumentUsesTracker` Struct Reference

<p>This tracker checks whether callees are in the SCC, and if so it does not consider that a capture, instead adding it to the "Uses" list and continuing with the analysis. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/capturetracker">CaptureTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This callback is used in conjunction with PointerMayBeCaptured. <a href="/web-llvm/docs/api/structs/llvm/capturetracker/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36bf7dad4e481045542e7c98f2373fbe">ArgumentUsesTracker</a> (const SCCNodeSet &amp;SCCNodes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3159d15771421a42528b46cf900a56c">tooManyUses</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tooManyUses - The depth of traversal has breached a limit. <a href="#ac3159d15771421a42528b46cf900a56c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa35ba8c73830d12eea5dda2a41aba718">captured</a> (const Use *U) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>captured - Information about the pointer was captured by the user of use U. <a href="#aa35ba8c73830d12eea5dda2a41aba718">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1439ae9ead20ad7b02ae6497fd79e839">Captured</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/argument">Argument</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf456bf76cdc566b51a628936353d660">Uses</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ae5e7383d35ed634befab95c8c2c99a1b">SCCNodeSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabf77cbe01ed9d30c5df0e3a978b167c">SCCNodes</a></td>
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

<p>This tracker checks whether callees are in the SCC, and if so it does not consider that a capture, instead adding it to the "Uses" list and continuing with the analysis.</p>

<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ArgumentUsesTracker() {#a36bf7dad4e481045542e7c98f2373fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::ArgumentUsesTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-functionattrs-cpp-/#ae5e7383d35ed634befab95c8c2c99a1b">SCCNodeSet</a> &amp; SCCNodes)</td>
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



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Reference <a href="#aabf77cbe01ed9d30c5df0e3a978b167c">SCCNodes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a5c54a34ab3372d252d9e9341bdff3dd3">addArgumentAttrs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### captured() {#aa35ba8c73830d12eea5dda2a41aba718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::captured (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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

<p>captured - Information about the pointer was captured by the user of use U.</p>


<p>Return true to stop the traversal or false to continue looking for more capturing instructions.</p>


<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#adde2ea00dd2613ee41bfe91908e4e68e">llvm::CallBase::arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1439ae9ead20ad7b02ae6497fd79e839">Captured</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a3ec61b88c722cd0e736fa93b4b599a19">llvm::CallBase::getDataOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aecc0c27ae96638bc9d8fa4caffa92c31">llvm::CallBase::hasOperandBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a754b47054852401f87e52805d15bdf05">llvm::CallBase::isCallee</a>, <a href="#aabf77cbe01ed9d30c5df0e3a978b167c">SCCNodes</a> and <a href="#abf456bf76cdc566b51a628936353d660">Uses</a>.</p>

</div>
</div>

### tooManyUses() {#ac3159d15771421a42528b46cf900a56c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::tooManyUses ()</td>
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

<p>tooManyUses - The depth of traversal has breached a limit.</p>


<p>There may be capturing instructions that will not be passed into <a href="#aa35ba8c73830d12eea5dda2a41aba718">captured()</a>.</p>


<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Reference <a href="#a1439ae9ead20ad7b02ae6497fd79e839">Captured</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Captured {#a1439ae9ead20ad7b02ae6497fd79e839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::Captured = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#aa35ba8c73830d12eea5dda2a41aba718">captured</a> and <a href="#ac3159d15771421a42528b46cf900a56c">tooManyUses</a>.</p>

</div>
</div>

### SCCNodes {#aabf77cbe01ed9d30c5df0e3a978b167c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCCNodeSet&amp; anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::SCCNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a36bf7dad4e481045542e7c98f2373fbe">ArgumentUsesTracker</a> and <a href="#aa35ba8c73830d12eea5dda2a41aba718">captured</a>.</p>

</div>
</div>

### Uses {#abf456bf76cdc566b51a628936353d660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Argument *, 4&gt; anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::Uses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#aa35ba8c73830d12eea5dda2a41aba718">captured</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp">FunctionAttrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
