---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/livedebugvalues/vloctracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `VLocTracker` Class

<p>Collection of DBG_VALUEs observed when traversing a block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class LiveDebugValues::VLocTracker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">CodeGen/LiveDebugValues/InstrRefBasedImpl.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab39bb8a6465b629687d3423b49fcd148">VLocTracker</a> (DebugVariableMap &amp;DVMap, const OverlapMap &amp;O, const DIExpression *EmptyExpr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee9cda71a5c099141ed832aae3e70a0">defVar</a> (const MachineInstr &amp;MI, const DbgValueProperties &amp;Properties, const SmallVectorImpl&lt; DbgOpID &gt; &amp;DebugOps)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cdda7b73eb2f4c3d7749fcc6ab5335f">considerOverlaps</a> (const DebugVariable &amp;Var, const DILocation *Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a941c70e6c8e447d30b45779d712f6da7">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/debugvariablemap">DebugVariableMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7894258ae9583c840ebe37e2f8580df">DVMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ref to function-wide map of <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &lt;=&gt; ID-numbers. <a href="#ab7894258ae9583c840ebe37e2f8580df">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74b0a01b154dab18a9a6b54fd737bcff">Vars</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> to the latest <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> it's defined to have. <a href="#a74b0a01b154dab18a9a6b54fd737bcff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21984c2b174801d5ba5d58532ddb90c4">Scopes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736cdf55e7740ae9a7276e71795f7412">MBB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2fd2da038a0079e35e2d22f37984d4ee">OverlapMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8cf65085094dda16144d6cd14e1bc4">OverlappingFragments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae584bd7e3ba1614e32832e73f654c774">EmptyProperties</a></td>
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

<p>Collection of DBG_VALUEs observed when traversing a block.</p>


<p>Records each variable and the value the DBG_VALUE refers to. Requires the machine value location dataflow algorithm to have run already, so that values can be identified.</p>


<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VLocTracker() {#ab39bb8a6465b629687d3423b49fcd148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveDebugValues::VLocTracker::VLocTracker (<a href="/web-llvm/docs/api/classes/livedebugvalues/debugvariablemap">DebugVariableMap</a> &amp; DVMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2fd2da038a0079e35e2d22f37984d4ee">OverlapMap</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * EmptyExpr)</td>
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



<p>Definition at line 1056 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#ab7894258ae9583c840ebe37e2f8580df">DVMap</a>, <a href="#ae584bd7e3ba1614e32832e73f654c774">EmptyProperties</a> and <a href="#a1b8cf65085094dda16144d6cd14e1bc4">OverlappingFragments</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a941c70e6c8e447d30b45779d712f6da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::VLocTracker::clear ()</td>
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



<p>Definition at line 1106 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#a21984c2b174801d5ba5d58532ddb90c4">Scopes</a> and <a href="#a74b0a01b154dab18a9a6b54fd737bcff">Vars</a>.</p>

</div>
</div>

### considerOverlaps() {#a9cdda7b73eb2f4c3d7749fcc6ab5335f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::VLocTracker::considerOverlaps (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &amp; Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * Loc)</td>
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



<p>Definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="#ab7894258ae9583c840ebe37e2f8580df">DVMap</a>, <a href="#ae584bd7e3ba1614e32832e73f654c774">EmptyProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#acdbb430c0790f598aff0f9c79ea2d4c4">llvm::DebugVariable::getFragmentOrDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#a58e53986006a2e7d95385fe4e633fb2e">llvm::DebugVariable::getInlinedAt</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#af2ca096ab72c055f6c2c7e3ffbe5d6bf">llvm::DebugVariable::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#a2928acad2fcb688e4dffb48eb9252aa4">llvm::DebugVariable::isDefaultFragment</a>, <a href="#a1b8cf65085094dda16144d6cd14e1bc4">OverlappingFragments</a>, <a href="#a21984c2b174801d5ba5d58532ddb90c4">Scopes</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue/#ac144ecd93e2625852097b3cab8a9d9bba7c46001b3585fc4e42328dbe7123b5d4">LiveDebugValues::DbgValue::Undef</a> and <a href="#a74b0a01b154dab18a9a6b54fd737bcff">Vars</a>.</p>


<p>Referenced by <a href="#a7ee9cda71a5c099141ed832aae3e70a0">defVar</a>.</p>

</div>
</div>

### defVar() {#a7ee9cda71a5c099141ed832aae3e70a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LiveDebugValues::VLocTracker::defVar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Properties, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgopid">DbgOpID</a> &gt; &amp; DebugOps)</td>
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



<p>Definition at line 1061 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a9cdda7b73eb2f4c3d7749fcc6ab5335f">considerOverlaps</a>, <a href="#ab7894258ae9583c840ebe37e2f8580df">DVMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a21984c2b174801d5ba5d58532ddb90c4">Scopes</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue/#ac144ecd93e2625852097b3cab8a9d9bba7c46001b3585fc4e42328dbe7123b5d4">LiveDebugValues::DbgValue::Undef</a> and <a href="#a74b0a01b154dab18a9a6b54fd737bcff">Vars</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DVMap {#ab7894258ae9583c840ebe37e2f8580df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugVariableMap&amp; LiveDebugValues::VLocTracker::DVMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ref to function-wide map of <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &lt;=&gt; ID-numbers.</p>

<p>Definition at line 1039 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a9cdda7b73eb2f4c3d7749fcc6ab5335f">considerOverlaps</a>, <a href="#a7ee9cda71a5c099141ed832aae3e70a0">defVar</a> and <a href="#ab39bb8a6465b629687d3423b49fcd148">VLocTracker</a>.</p>

</div>
</div>

### EmptyProperties {#ae584bd7e3ba1614e32832e73f654c774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgValueProperties LiveDebugValues::VLocTracker::EmptyProperties</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1053 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a9cdda7b73eb2f4c3d7749fcc6ab5335f">considerOverlaps</a> and <a href="#ab39bb8a6465b629687d3423b49fcd148">VLocTracker</a>.</p>

</div>
</div>

### MBB {#a736cdf55e7740ae9a7276e71795f7412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* LiveDebugValues::VLocTracker::MBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>

</div>
</div>

### OverlappingFragments {#a1b8cf65085094dda16144d6cd14e1bc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OverlapMap&amp; LiveDebugValues::VLocTracker::OverlappingFragments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1052 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a9cdda7b73eb2f4c3d7749fcc6ab5335f">considerOverlaps</a> and <a href="#ab39bb8a6465b629687d3423b49fcd148">VLocTracker</a>.</p>

</div>
</div>

### Scopes {#a21984c2b174801d5ba5d58532ddb90c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallDenseMap&lt;DebugVariableID, const DILocation *, 8&gt; LiveDebugValues::VLocTracker::Scopes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1050 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a941c70e6c8e447d30b45779d712f6da7">clear</a>, <a href="#a9cdda7b73eb2f4c3d7749fcc6ab5335f">considerOverlaps</a> and <a href="#a7ee9cda71a5c099141ed832aae3e70a0">defVar</a>.</p>

</div>
</div>

### Vars {#a74b0a01b154dab18a9a6b54fd737bcff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallMapVector&lt;DebugVariableID, DbgValue, 8&gt; LiveDebugValues::VLocTracker::Vars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> to the latest <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> it's defined to have.</p>


<p>Needs to be a <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a> because we determine order-in-the-input-MIR from the order in this container. (FIXME: likely no longer true as the ordering is now provided by <a href="/web-llvm/docs/api/classes/livedebugvalues/debugvariablemap">DebugVariableMap</a>). We only retain the last <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> in each block for each variable, to determine the blocks live-out variable value. The Vars container forms the transfer function for this block, as part of the dataflow analysis. The movement of values between locations inside of a block is handled at a much later stage, in the <a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a> class.</p>


<p>Definition at line 1049 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a>.</p>


<p>Referenced by <a href="#a941c70e6c8e447d30b45779d712f6da7">clear</a>, <a href="#a9cdda7b73eb2f4c3d7749fcc6ab5335f">considerOverlaps</a> and <a href="#a7ee9cda71a5c099141ed832aae3e70a0">defVar</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-h">InstrRefBasedImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
