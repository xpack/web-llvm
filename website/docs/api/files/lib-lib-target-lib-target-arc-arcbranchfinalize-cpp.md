---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ARCBranchFinalize.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcinstrinfo-h">ARCInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arctargetmachine-h">ARCTargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinfo-h">MCTargetDesc/ARCInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineinstrbuilder-h">llvm/CodeGen/MachineInstrBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineregisterinfo-h">llvm/CodeGen/MachineRegisterInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include &lt;vector&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-arcbranchfinalize-cpp-">anonymous{ARCBranchFinalize.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize">ARCBranchFinalize</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e336498b652193459f31ade7e688900">INITIALIZE_PASS_BEGIN</a> (ARCBranchFinalize, "arc-branch-finalize", "ARC finalize branches", false, false) INITIALIZE_PASS_END(ARCBranchFinalize</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static arc branch ARC <a href="#a8e08eb3768ea6054b445ad1e5f0b9bba">finalize</a> static false unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e218e533106e4cab8c7976e409ddb39">getCCForBRcc</a> (unsigned CC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a799ea7c772c41b3d7e2a5b3005a335ea">isBRccPseudo</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60496892b6c37739438510061e0771ec">getBRccForPseudo</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a318a2d7a4a915ec9cb3a0000b94616b5">getCmpForPseudo</a> (MachineInstr *MI)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">arc branch</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e08eb3768ea6054b445ad1e5f0b9bba">finalize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">arc branch ARC <a href="#a8e08eb3768ea6054b445ad1e5f0b9bba">finalize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14311558a7445776def2d5bc13161ba3">branches</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">arc branch ARC <a href="#a8e08eb3768ea6054b445ad1e5f0b9bba">finalize</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6de30eaf607b4f57510a86cff2e5fb9">false</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"arc-branch-finalize"</td>
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


<div class="doxySectionDef">

## Functions

### getBRccForPseudo() {#a60496892b6c37739438510061e0771ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getBRccForPseudo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a799ea7c772c41b3d7e2a5b3005a335ea">isBRccPseudo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a49c5e597ebff3776f7a43c3d7f181680">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithBRcc</a>.</p>

</div>
</div>

### getCCForBRcc() {#a9e218e533106e4cab8c7976e409ddb39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arc branch ARC finalize static false unsigned getCCForBRcc (unsigned CC)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a06424d16ad2a930de1f57d6b564cbc1b">llvm::ARCCC::EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a815eaffff57498d8c26b03fb3510dec6">llvm::ARCCC::GE</a>, <a href="#a9e218e533106e4cab8c7976e409ddb39">getCCForBRcc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a4c1cec33829d627ebeeb767b3d2b2c36">llvm::ARCCC::HS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a01b7f88b89f69e354f814793602b2256">llvm::ARCCC::LO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a1695055effb07e0e8e69ff10aff4756b">llvm::ARCCC::LT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/arccc/#a9a81d9a1b379cf08150b22e81d7dd006a913770d7f2c3565cff9146efa0621b8d">llvm::ARCCC::NE</a>.</p>


<p>Referenced by <a href="#a9e218e533106e4cab8c7976e409ddb39">getCCForBRcc</a> and <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a49c5e597ebff3776f7a43c3d7f181680">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithBRcc</a>.</p>

</div>
</div>

### getCmpForPseudo() {#a318a2d7a4a915ec9cb3a0000b94616b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned getCmpForPseudo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a799ea7c772c41b3d7e2a5b3005a335ea">isBRccPseudo</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a22b62d53bdcd603d84866e9bf8a4fb45">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::replaceWithCmpBcc</a>.</p>

</div>
</div>

### INITIALIZE\_PASS\_BEGIN() {#a1e336498b652193459f31ade7e688900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (ARCBranchFinalize, "arc-branch-finalize", "ARC <a href="#a8e08eb3768ea6054b445ad1e5f0b9bba">finalize</a> branches", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isBRccPseudo() {#a799ea7c772c41b3d7e2a5b3005a335ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isBRccPseudo (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a60496892b6c37739438510061e0771ec">getBRccForPseudo</a>, <a href="#a318a2d7a4a915ec9cb3a0000b94616b5">getCmpForPseudo</a> and <a href="/web-llvm/docs/api/classes/anonymous-arcbranchfinalize-cpp-/arcbranchfinalize/#a1ef916f394f8815d4d51c9166920a6ab">anonymous{ARCBranchFinalize.cpp}::ARCBranchFinalize::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### branches {#a14311558a7445776def2d5bc13161ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arc branch ARC finalize branches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>

</div>
</div>

### false {#aa6de30eaf607b4f57510a86cff2e5fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arc branch ARC finalize false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>

</div>
</div>

### finalize {#a8e08eb3768ea6054b445ad1e5f0b9bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">arc branch finalize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder/#a8dbe73960ff993f556bc2b82131983fb">llvm::pdb::DbiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/tpistreambuilder/#a82a7a598a05d2c0e837d924da348c414">llvm::pdb::TpiStreamBuilder::commit</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/writer/#a0c6b0217a29520ff740cb32952eac94f">llvm::objcopy::wasm::Writer::write</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/xcoff/xcoffwriter/#af3adedc8850f537a3ba8e71bba9d9934">llvm::objcopy::xcoff::XCOFFWriter::write</a>, <a href="/web-llvm/docs/api/classes/anonymous-goffemitter-cpp-/goffostream/#a7f6280218d43b478c680f14e6aefaff5">anonymous{GOFFEmitter.cpp}::GOFFOstream::~GOFFOstream</a> and <a href="/web-llvm/docs/api/classes/anonymous-goffobjectwriter-cpp-/goffostream/#a7854c72c615013bccfba0ca2d7c61ef0">anonymous{GOFFObjectWriter.cpp}::GOFFOstream::~GOFFOstream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"arc-branch-finalize"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/arcbranchfinalize-cpp">ARCBranchFinalize.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
