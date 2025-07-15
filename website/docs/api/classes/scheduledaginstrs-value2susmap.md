---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/scheduledaginstrs/value2susmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Value2SUsMap` Class Reference



## Declaration

<div class="doxyDeclaration">
class ScheduleDAGInstrs::Value2SUsMap { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector&lt;KeyT, ValueT, N&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> that performs no allocations if smaller than a certain size. <a href="/web-llvm/docs/api/structs/llvm/smallmapvector/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75fc536cd3210efa617d9b20832bc7f6">Value2SUsMap</a> (unsigned lat=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a1756c0c48acd95f08dbc4b5627627e">operator[]</a> (const SUList &amp;Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To keep NumNodes up to date, <a href="#a0b589d5a5454606a0a9024a106844cf1">insert()</a> is used instead of this operator w/ push_back(). <a href="#a9a1756c0c48acd95f08dbc4b5627627e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b589d5a5454606a0a9024a106844cf1">insert</a> (SUnit *SU, ValueType V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds SU to the <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8e1e9d0b1c64c405c0e99288f9225bd5">SUList</a> of V. <a href="#a0b589d5a5454606a0a9024a106844cf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849f288acb6b68b0987cb598bc36472e">clearList</a> (ValueType V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears the list of SUs mapped to V. <a href="#a849f288acb6b68b0987cb598bc36472e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62b8ec9cd0b46fe7a2a1d3cb3f9e6cf5">clear</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clears map from all contents. <a href="#a62b8ec9cd0b46fe7a2a1d3cb3f9e6cf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a877cc0c7417f2a791fc0d6db0ca39161">size</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a033628dbd3a02473543d533b5987f538">reComputeSize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Counts the number of SUs in this map after a reduction. <a href="#a033628dbd3a02473543d533b5987f538">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adff804a02fa1af4d4192309a8d4df8eb">getTrueMemOrderLatency</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2108e59efc127ea06bcd9e920d0b9261">dump</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652c3d48d0f0545df50681e5948f07f4">NumNodes</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current total number of SUs in map. <a href="#a652c3d48d0f0545df50681e5948f07f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4525fdaac69519c8b29bd1c2c51f707">TrueMemOrderLatency</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>1 for loads, 0 for stores. (see comment in <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8e1e9d0b1c64c405c0e99288f9225bd5">SUList</a>) <a href="#ad4525fdaac69519c8b29bd1c2c51f707">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Value2SUsMap() {#a75fc536cd3210efa617d9b20832bc7f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ScheduleDAGInstrs::Value2SUsMap::Value2SUsMap (unsigned lat=0)</td>
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



<p>Definition at line 628 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a9a1756c0c48acd95f08dbc4b5627627e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueType &amp; llvm::ScheduleDAGInstrs::Value2SUsMap::operator[] (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8e1e9d0b1c64c405c0e99288f9225bd5">SUList</a> &amp; Key)</td>
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

<p>To keep NumNodes up to date, <a href="#a0b589d5a5454606a0a9024a106844cf1">insert()</a> is used instead of this operator w/ push_back().</p>

<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a62b8ec9cd0b46fe7a2a1d3cb3f9e6cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGInstrs::Value2SUsMap::clear ()</td>
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

<p>Clears map from all contents.</p>

<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mapvector/#ae091b147039557cf8ce505740e7ff7ac">llvm::MapVector&lt; KeyT, ValueT, SmallDenseMap&lt; KeyT, unsigned, N &gt;, SmallVector&lt; std::pair&lt; KeyT, ValueT &gt;, N &gt; &gt;::clear</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a2cfd9da0e5724aa91bf1767dc1e2515e">llvm::ScheduleDAGInstrs::addBarrierChain</a>.</p>

</div>
</div>

### clearList() {#a849f288acb6b68b0987cb598bc36472e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGInstrs::Value2SUsMap::clearList (<a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> V)</td>
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

<p>Clears the list of SUs mapped to V.</p>

<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a21805259f54dab47c2b3da009216996a">llvm::ScheduleDAGInstrs::end</a> and <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a6b0c3e15c351ba9682837c29b0a141b6">llvm::MapVector&lt; ValueType, SUList, SmallDenseMap&lt; ValueType, unsigned, N &gt;, SmallVector&lt; std::pair&lt; ValueType, SUList &gt;, N &gt; &gt;::find</a>.</p>

</div>
</div>

### dump() {#a2108e59efc127ea06bcd9e920d0b9261}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGInstrs::Value2SUsMap::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp/#a7df8c7c3d357c407b3cfb1888f988353">dumpSUList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getTrueMemOrderLatency() {#adff804a02fa1af4d4192309a8d4df8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGInstrs::Value2SUsMap::getTrueMemOrderLatency ()</td>
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



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#afe11e438e3ecc0381047e0e01958fea0">llvm::ScheduleDAGInstrs::addChainDependencies</a> and <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a14962363da4c4a48ad6646cb05f49b77">llvm::ScheduleDAGInstrs::addChainDependencies</a>.</p>

</div>
</div>

### insert() {#a0b589d5a5454606a0a9024a106844cf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGInstrs::Value2SUsMap::insert (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> * SU, <a href="/web-llvm/docs/api/namespaces/llvm/#ad18871060ac1b051c7322cc6ad71e11c">ValueType</a> V)</td>
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

<p>Adds SU to the <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8e1e9d0b1c64c405c0e99288f9225bd5">SUList</a> of V.</p>


<p>If Map grows huge, reduce its size by calling <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6d827fc34f1b4371a0b7183d3ca5bcac">reduce()</a>.</p>


<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mapvector/#a32a1366139fd98139d346e5f8912a9b9">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::operator[]</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>.</p>

</div>
</div>

### reComputeSize() {#a033628dbd3a02473543d533b5987f538}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ScheduleDAGInstrs::Value2SUsMap::reComputeSize ()</td>
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

<p>Counts the number of SUs in this map after a reduction.</p>

<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ac483efdc6c5ab7a20f776b77f986b6cf">llvm::ScheduleDAGInstrs::insertBarrierChain</a>.</p>

</div>
</div>

### size() {#a877cc0c7417f2a791fc0d6db0ca39161}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGInstrs::Value2SUsMap::size ()</td>
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



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#ab580983de4f7b69ebcca992be9cb3223">llvm::ScheduleDAGInstrs::buildSchedGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NumNodes {#a652c3d48d0f0545df50681e5948f07f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGInstrs::Value2SUsMap::NumNodes = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current total number of SUs in map.</p>

<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>

</div>
</div>

### TrueMemOrderLatency {#ad4525fdaac69519c8b29bd1c2c51f707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::ScheduleDAGInstrs::Value2SUsMap::TrueMemOrderLatency</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>1 for loads, 0 for stores. (see comment in <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a8e1e9d0b1c64c405c0e99288f9225bd5">SUList</a>)</p>

<p>Definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/scheduledaginstrs-cpp">ScheduleDAGInstrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
