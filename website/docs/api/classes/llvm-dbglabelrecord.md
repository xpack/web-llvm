---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dbglabelrecord
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DbgLabelRecord` Class Reference

<p>Records a position in IR for a source label (<a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a>). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DbgLabelRecord { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">llvm/IR/DebugProgramInstruction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for non-instruction debug metadata records that have positions within IR. <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608bdf3158d53073f05efa565ca6c14d">DbgLabelRecord</a> (DILabel *Label, DebugLoc DL)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4838b2b532478d11e5cd11cc7ea3255">DbgLabelRecord</a> (MDNode *Label, MDNode *DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructor intentionally left private, so that it is only called via "createUnresolvedDbgLabelRecord", which clearly expresses that it is for parsing only. <a href="#ad4838b2b532478d11e5cd11cc7ea3255">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord">DbgLabelRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1adab2fe4df7a403f8deb20265d933">clone</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a546804db12f646346b125a2d6e8a4bf9">print</a> (raw_ostream &amp;O, bool IsForDebug=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af01d77795bb3f385853944a0fb4dbc40">print</a> (raw_ostream &amp;ROS, ModuleSlotTracker &amp;MST, bool IsForDebug) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbglabelinst">DbgLabelInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc686ba917c4b589803df62f9a0c75d6">createDebugIntrinsic</a> (Module *M, Instruction *InsertBefore) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72cd04cc7acc3d97714644e241900d01">setLabel</a> (DILabel *NewLabel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbbe6f357cef13acb362ea10f466a87e">getLabel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11af0bfa48234611c77f38c3704a1fbc">getRawLabel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgrecordparamref">DbgRecordParamRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424f5748fddf45d2a1064fd86033c588">Label</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord">DbgLabelRecord</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5baa6360b3d00bdb8ccb84c306cf5088">createUnresolvedDbgLabelRecord</a> (MDNode *Label, MDNode *DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For use during parsing; creates a <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord">DbgLabelRecord</a> from as-of-yet unresolved MDNodes. <a href="#a5baa6360b3d00bdb8ccb84c306cf5088">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511d5322f03174c0ee3a84cb13119ae4">classof</a> (const DbgRecord *E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Support type inquiry through isa, cast, and dyn_cast. <a href="#a511d5322f03174c0ee3a84cb13119ae4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Records a position in IR for a source label (<a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a>).</p>


<p>Corresponds to the llvm.dbg.label intrinsic.</p>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DbgLabelRecord() {#a608bdf3158d53073f05efa565ca6c14d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgLabelRecord::DbgLabelRecord (<a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * Label, <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a269e66beb08d4b146aa23deb49f5f640">llvm::DbgRecord::DbgRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">llvm::DbgRecord::LabelKind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### DbgLabelRecord() {#ad4838b2b532478d11e5cd11cc7ea3255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DbgLabelRecord::DbgLabelRecord (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Label, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This constructor intentionally left private, so that it is only called via "createUnresolvedDbgLabelRecord", which clearly expresses that it is for parsing only.</p>

<p>Declaration at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a2e1adab2fe4df7a403f8deb20265d933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgLabelRecord * llvm::DbgLabelRecord::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a> and <a href="#adbbe6f357cef13acb362ea10f466a87e">getLabel</a>.</p>

</div>
</div>

### createDebugIntrinsic() {#adc686ba917c4b589803df62f9a0c75d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgLabelInst * llvm::DbgLabelRecord::createDebugIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 460 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue/#a3188a1aa0df768d8f254cd8d8fdeface">llvm::MetadataAsValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aeeca41a71460985e42575296d3546044">llvm::DbgRecord::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a3a0f4e00c3f6345c52c6acd178b3fca3">llvm::DbgRecord::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#adbbe6f357cef13acb362ea10f466a87e">getLabel</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>.</p>

</div>
</div>

### getLabel() {#adbbe6f357cef13acb362ea10f466a87e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILabel * llvm::DbgLabelRecord::getLabel ()</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>.</p>


<p>Referenced by <a href="#a2e1adab2fe4df7a403f8deb20265d933">clone</a> and <a href="#adc686ba917c4b589803df62f9a0c75d6">createDebugIntrinsic</a>.</p>

</div>
</div>

### getRawLabel() {#a11af0bfa48234611c77f38c3704a1fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::DbgLabelRecord::getRawLabel ()</td>
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



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

### print() {#a546804db12f646346b125a2d6e8a4bf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgLabelRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 5022 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### print() {#af01d77795bb3f385853944a0fb4dbc40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbgLabelRecord::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; ROS, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker">ModuleSlotTracker</a> &amp; MST, bool IsForDebug)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 5045 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#a802b848d702c132a97b3da454c1e68c1">llvm::ModuleSlotTracker::getMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleslottracker/#ace93d877ff9298d25a15e2a32f765653">llvm::ModuleSlotTracker::incorporateFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#ad025b1f45fbe33034c9c94c17684cbef">llvm::DbgRecord::Marker</a>.</p>

</div>
</div>

### setLabel() {#a72cd04cc7acc3d97714644e241900d01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DbgLabelRecord::setLabel (<a href="/web-llvm/docs/api/classes/llvm/dilabel">DILabel</a> * NewLabel)</td>
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



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Label {#a424f5748fddf45d2a1064fd86033c588}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgRecordParamRef&lt;DILabel&gt; llvm::DbgLabelRecord::Label</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a511d5322f03174c0ee3a84cb13119ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DbgLabelRecord::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * E)</td>
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

<p>Support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a269e66beb08d4b146aa23deb49f5f640">llvm::DbgRecord::DbgRecord</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a887a873e264b58ebc609ffc62b4372bca8f3283cf32bfb899b5547245313bd486">llvm::DbgRecord::LabelKind</a>.</p>

</div>
</div>

### createUnresolvedDbgLabelRecord() {#a5baa6360b3d00bdb8ccb84c306cf5088}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgLabelRecord * llvm::DbgLabelRecord::createUnresolvedDbgLabelRecord (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Label, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * DL)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For use during parsing; creates a <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord">DbgLabelRecord</a> from as-of-yet unresolved MDNodes.</p>


<p>Trying to access the resulting <a href="/web-llvm/docs/api/classes/llvm/dbglabelrecord">DbgLabelRecord</a>'s fields before they are resolved, or if they resolve to the wrong type, will result in a crash.</p>


<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debugprograminstruction-cpp">DebugProgramInstruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
