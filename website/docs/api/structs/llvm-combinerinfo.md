---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/combinerinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CombinerInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CombinerInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">llvm/CodeGen/GlobalISel/CombinerInfo.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombinerinfo">MipsPreLegalizerCombinerInfo</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ObserverLevel { <a href="#af06305b83dbec881b832db7259d81257">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1c9021d2106bc67cb7e163919e2ff0">CombinerInfo</a> (bool AllowIllegalOps, bool ShouldLegalizeIllegal, const LegalizerInfo *LInfo, bool OptEnabled, bool OptSize, bool MinSize)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade46ef039dd9d4d77c6644e34a533b68">~CombinerInfo</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab2c3f1607c68901fcd6b8fe9509d0f4">IllegalOpsAllowed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">IllegalOpsAllowed</span> is false, the <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a> will make use of the legalizerInfo to check for legality before each transformation. <a href="#aab2c3f1607c68901fcd6b8fe9509d0f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a965ca618a929b51e7061940f57d75fe4">LegalizeIllegalOps</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <span class="doxyComputerOutput">LegalizeIllegalOps</span> is true, the <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> will also legalize the illegal ops that are created. <a href="#a965ca618a929b51e7061940f57d75fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a612b2473811497634f56887304c272a2">LInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73b725cabcf87656df214d1eea6fe8d">EnableOpt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether optimizations should be enabled. <a href="#ae73b725cabcf87656df214d1eea6fe8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3fed5a81a264dab279e81100662c69f">EnableOptSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether we're optimizing for size. <a href="#ae3fed5a81a264dab279e81100662c69f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a056c3b3fd3d728ac21a36445ff62fbaf">EnableMinSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether we're optimizing for minsize (-Oz). <a href="#a056c3b3fd3d728ac21a36445ff62fbaf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d19bf1d7a82f4d19c7bfe8ac56d9a5">MaxIterations</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum number of times the <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> will iterate over the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>. <a href="#a19d19bf1d7a82f4d19c7bfe8ac56d9a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af06305b83dbec881b832db7259d81257">ObserverLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1da24e61547ef0d45f6c0bfb982aef69">ObserverLvl</a> = <a href="#af06305b83dbec881b832db7259d81257a972e73b7a882d0802a4e3a16946a2f94">ObserverLevel::Basic</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Select how the <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> acts on MIR changes. <a href="#a1da24e61547ef0d45f6c0bfb982aef69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a751f02159e4303b50a4eb7baf1d517fc">EnableFullDCE</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether dead code elimination is performed before each <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> iteration. <a href="#a751f02159e4303b50a4eb7baf1d517fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ObserverLevel {#af06305b83dbec881b832db7259d81257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::CombinerInfo::ObserverLevel </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Basic<a id="af06305b83dbec881b832db7259d81257a972e73b7a882d0802a4e3a16946a2f94"></a></td>
<td class="doxyEnumItemDescription">Only retry combining created/changed instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DCE<a id="af06305b83dbec881b832db7259d81257a7ec86cdcd1ba706dcb1764fabd5ad86a"></a></td>
<td class="doxyEnumItemDescription">Enables Observer-based detection of dead instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SinglePass<a id="af06305b83dbec881b832db7259d81257afb4c9649ec491b503777cb90a6c37975"></a></td>
<td class="doxyEnumItemDescription">Enables Observer-based DCE and additional heuristics that retry combining defined and used instructions of modified instructions</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CombinerInfo() {#a1c1c9021d2106bc67cb7e163919e2ff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CombinerInfo::CombinerInfo (bool AllowIllegalOps, bool ShouldLegalizeIllegal, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/legalizerinfo">LegalizerInfo</a> * LInfo, bool OptEnabled, bool OptSize, bool MinSize)</td>
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



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a056c3b3fd3d728ac21a36445ff62fbaf">EnableMinSize</a>, <a href="#ae73b725cabcf87656df214d1eea6fe8d">EnableOpt</a>, <a href="#ae3fed5a81a264dab279e81100662c69f">EnableOptSize</a>, <a href="#aab2c3f1607c68901fcd6b8fe9509d0f4">IllegalOpsAllowed</a>, <a href="#a965ca618a929b51e7061940f57d75fe4">LegalizeIllegalOps</a> and <a href="#a612b2473811497634f56887304c272a2">LInfo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-mipsprelegalizercombiner-cpp-/mipsprelegalizercombinerinfo/#a9cea4fcdb705d5e757a450dab79e2da2">anonymous{MipsPreLegalizerCombiner.cpp}::MipsPreLegalizerCombinerInfo::MipsPreLegalizerCombinerInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~CombinerInfo() {#ade46ef039dd9d4d77c6644e34a533b68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::CombinerInfo::~CombinerInfo ()</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### EnableFullDCE {#a751f02159e4303b50a4eb7baf1d517fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerInfo::EnableFullDCE = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether dead code elimination is performed before each <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> iteration.</p>


<p>If Observer-based DCE is enabled, this controls if a full DCE pass is performed before the first <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> iteration.</p>


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>

</div>
</div>

### EnableMinSize {#a056c3b3fd3d728ac21a36445ff62fbaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerInfo::EnableMinSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether we're optimizing for minsize (-Oz).</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<p>Referenced by <a href="#a1c1c9021d2106bc67cb7e163919e2ff0">CombinerInfo</a>.</p>

</div>
</div>

### EnableOpt {#ae73b725cabcf87656df214d1eea6fe8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerInfo::EnableOpt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether optimizations should be enabled.</p>


<p>This is to distinguish between uses of the combiner unconditionally and only when optimizations are specifically enabled/</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<p>Referenced by <a href="#a1c1c9021d2106bc67cb7e163919e2ff0">CombinerInfo</a>.</p>

</div>
</div>

### EnableOptSize {#ae3fed5a81a264dab279e81100662c69f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerInfo::EnableOptSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether we're optimizing for size.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<p>Referenced by <a href="#a1c1c9021d2106bc67cb7e163919e2ff0">CombinerInfo</a>.</p>

</div>
</div>

### IllegalOpsAllowed {#aab2c3f1607c68901fcd6b8fe9509d0f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerInfo::IllegalOpsAllowed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">IllegalOpsAllowed</span> is false, the <a href="/web-llvm/docs/api/classes/llvm/combinerhelper">CombinerHelper</a> will make use of the legalizerInfo to check for legality before each transformation.</p>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<p>Referenced by <a href="#a1c1c9021d2106bc67cb7e163919e2ff0">CombinerInfo</a>.</p>

</div>
</div>

### LegalizeIllegalOps {#a965ca618a929b51e7061940f57d75fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CombinerInfo::LegalizeIllegalOps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <span class="doxyComputerOutput">LegalizeIllegalOps</span> is true, the <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> will also legalize the illegal ops that are created.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<p>Referenced by <a href="#a1c1c9021d2106bc67cb7e163919e2ff0">CombinerInfo</a>.</p>

</div>
</div>

### LInfo {#a612b2473811497634f56887304c272a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LegalizerInfo* llvm::CombinerInfo::LInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>


<p>Referenced by <a href="#a1c1c9021d2106bc67cb7e163919e2ff0">CombinerInfo</a>.</p>

</div>
</div>

### MaxIterations {#a19d19bf1d7a82f4d19c7bfe8ac56d9a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CombinerInfo::MaxIterations = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum number of times the <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> will iterate over the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a>.</p>


<p>Setting this to 0 enables fixed-point iteration.</p>


<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>

</div>
</div>

### ObserverLvl {#a1da24e61547ef0d45f6c0bfb982aef69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ObserverLevel llvm::CombinerInfo::ObserverLvl = <a href="#af06305b83dbec881b832db7259d81257a972e73b7a882d0802a4e3a16946a2f94">ObserverLevel::Basic</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Select how the <a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> acts on MIR changes.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/combinerinfo-h">CombinerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
