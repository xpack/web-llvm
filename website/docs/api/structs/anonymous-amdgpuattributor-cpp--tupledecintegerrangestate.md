---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-amdgpuattributor-cpp-/tupledecintegerrangestate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `TupleDecIntegerRangeState` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/abstractstate">AbstractState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An interface to query the internal state of an abstract attribute. <a href="/web-llvm/docs/api/structs/llvm/abstractstate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/tupledecintegerrangestate">TupleDecIntegerRangeState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a243b9d6ba301231c2b1305890e40afa2">operator^=</a> (const TupleDecIntegerRangeState &amp;Other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac191a239445c720a1810d159d340644">operator==</a> (const TupleDecIntegerRangeState &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6960f0bb2f0dcc703898d629e092c270">isValidState</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if this abstract state is in a valid state. <a href="#a6960f0bb2f0dcc703898d629e092c270">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a375f128f4ea94d6ca28fa009fe4a4c60">isAtFixpoint</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return if this abstract state is fixed, thus does not need to be updated if information changes as it cannot change itself. <a href="#a375f128f4ea94d6ca28fa009fe4a4c60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c19bd9fe097803d678ee48bebcf700c">indicateOptimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that the abstract state should converge to the optimistic state. <a href="#a8c19bd9fe097803d678ee48bebcf700c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed3a6ad08e3427e1b748171a9cdfc14d">indicatePessimisticFixpoint</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indicate that the abstract state should converge to the pessimistic state. <a href="#aed3a6ad08e3427e1b748171a9cdfc14d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/tupledecintegerrangestate">TupleDecIntegerRangeState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a4be0f438117d59a9ddccfddd2482d1">getAssumed</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/tupledecintegerrangestate">TupleDecIntegerRangeState</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa78878645d9cde0554c11ea6d9edcd67">getAssumed</a> () const</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/decintegerstate">DecIntegerState</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade4368b6c765f09ea9cace06848f9dad">X</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/decintegerstate">DecIntegerState</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd50212fe42872a9b992192e2448a1af">Y</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/decintegerstate">DecIntegerState</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2544cb9c5df173e909f87198a6862df">Z</a></td>
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


<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator^=() {#a243b9d6ba301231c2b1305890e40afa2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TupleDecIntegerRangeState anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::operator^= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/tupledecintegerrangestate">TupleDecIntegerRangeState</a> &amp; Other)</td>
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



<p>Definition at line 985 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#ade4368b6c765f09ea9cace06848f9dad">X</a>, <a href="#afd50212fe42872a9b992192e2448a1af">Y</a> and <a href="#ae2544cb9c5df173e909f87198a6862df">Z</a>.</p>

</div>
</div>

### operator==() {#aac191a239445c720a1810d159d340644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-amdgpuattributor-cpp-/tupledecintegerrangestate">TupleDecIntegerRangeState</a> &amp; Other)</td>
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



<p>Definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#ade4368b6c765f09ea9cace06848f9dad">X</a>, <a href="#afd50212fe42872a9b992192e2448a1af">Y</a> and <a href="#ae2544cb9c5df173e909f87198a6862df">Z</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAssumed() {#a4a4be0f438117d59a9ddccfddd2482d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TupleDecIntegerRangeState &amp; anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::getAssumed ()</td>
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



<p>Definition at line 996 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>

</div>
</div>

### getAssumed() {#aa78878645d9cde0554c11ea6d9edcd67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TupleDecIntegerRangeState &amp; anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::getAssumed ()</td>
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



<p>Definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>

</div>
</div>

### indicateOptimisticFixpoint() {#a8c19bd9fe097803d678ee48bebcf700c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::indicateOptimisticFixpoint ()</td>
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

<p>Indicate that the abstract state should converge to the optimistic state.</p>


<p>This will usually make the optimistically assumed state the known to be true state.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>ChangeStatus::UNCHANGED as the assumed value should not change.</p></dd>
</dl>


<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>References <a href="#ade4368b6c765f09ea9cace06848f9dad">X</a>, <a href="#afd50212fe42872a9b992192e2448a1af">Y</a> and <a href="#ae2544cb9c5df173e909f87198a6862df">Z</a>.</p>

</div>
</div>

### indicatePessimisticFixpoint() {#aed3a6ad08e3427e1b748171a9cdfc14d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::indicatePessimisticFixpoint ()</td>
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

<p>Indicate that the abstract state should converge to the pessimistic state.</p>


<p>This will usually revert the optimistically assumed state to the known to be true state.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>ChangeStatus::CHANGED as the assumed value may change.</p></dd>
</dl>


<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>References <a href="#ade4368b6c765f09ea9cace06848f9dad">X</a>, <a href="#afd50212fe42872a9b992192e2448a1af">Y</a> and <a href="#ae2544cb9c5df173e909f87198a6862df">Z</a>.</p>

</div>
</div>

### isAtFixpoint() {#a375f128f4ea94d6ca28fa009fe4a4c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::isAtFixpoint ()</td>
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

<p>Return if this abstract state is fixed, thus does not need to be updated if information changes as it cannot change itself.</p>

<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>References <a href="#ade4368b6c765f09ea9cace06848f9dad">X</a>, <a href="#afd50212fe42872a9b992192e2448a1af">Y</a> and <a href="#ae2544cb9c5df173e909f87198a6862df">Z</a>.</p>

</div>
</div>

### isValidState() {#a6960f0bb2f0dcc703898d629e092c270}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::isValidState ()</td>
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

<p>Return if this abstract state is in a valid state.</p>


<p>If false, no information provided should be used.</p>


<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>References <a href="#ade4368b6c765f09ea9cace06848f9dad">X</a>, <a href="#afd50212fe42872a9b992192e2448a1af">Y</a> and <a href="#ae2544cb9c5df173e909f87198a6862df">Z</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### X {#ade4368b6c765f09ea9cace06848f9dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecIntegerState&lt;uint32_t&gt; anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::X</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>Referenced by <a href="#a8c19bd9fe097803d678ee48bebcf700c">indicateOptimisticFixpoint</a>, <a href="#aed3a6ad08e3427e1b748171a9cdfc14d">indicatePessimisticFixpoint</a>, <a href="#a375f128f4ea94d6ca28fa009fe4a4c60">isAtFixpoint</a>, <a href="#a6960f0bb2f0dcc703898d629e092c270">isValidState</a>, <a href="#aac191a239445c720a1810d159d340644">operator==</a> and <a href="#a243b9d6ba301231c2b1305890e40afa2">operator^=</a>.</p>

</div>
</div>

### Y {#afd50212fe42872a9b992192e2448a1af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecIntegerState&lt;uint32_t&gt; anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::Y</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>Referenced by <a href="#a8c19bd9fe097803d678ee48bebcf700c">indicateOptimisticFixpoint</a>, <a href="#aed3a6ad08e3427e1b748171a9cdfc14d">indicatePessimisticFixpoint</a>, <a href="#a375f128f4ea94d6ca28fa009fe4a4c60">isAtFixpoint</a>, <a href="#a6960f0bb2f0dcc703898d629e092c270">isValidState</a>, <a href="#aac191a239445c720a1810d159d340644">operator==</a> and <a href="#a243b9d6ba301231c2b1305890e40afa2">operator^=</a>.</p>

</div>
</div>

### Z {#ae2544cb9c5df173e909f87198a6862df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DecIntegerState&lt;uint32_t&gt; anonymous{AMDGPUAttributor.cpp}::TupleDecIntegerRangeState::Z</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a>.</p>


<p>Referenced by <a href="#a8c19bd9fe097803d678ee48bebcf700c">indicateOptimisticFixpoint</a>, <a href="#aed3a6ad08e3427e1b748171a9cdfc14d">indicatePessimisticFixpoint</a>, <a href="#a375f128f4ea94d6ca28fa009fe4a4c60">isAtFixpoint</a>, <a href="#a6960f0bb2f0dcc703898d629e092c270">isValidState</a>, <a href="#aac191a239445c720a1810d159d340644">operator==</a> and <a href="#a243b9d6ba301231c2b1305890e40afa2">operator^=</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuattributor-cpp">AMDGPUAttributor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
