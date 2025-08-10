---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `Legalizer.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizer-h">llvm/CodeGen/GlobalISel/Legalizer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/postorderiterator-h">llvm/ADT/PostOrderIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/optimizationremarkemitter-h">llvm/Analysis/OptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/cseinfo-h">llvm/CodeGen/GlobalISel/CSEInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/csemirbuilder-h">llvm/CodeGen/GlobalISel/CSEMIRBuilder.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselchangeobserver-h">llvm/CodeGen/GlobalISel/GISelChangeObserver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselknownbits-h">llvm/CodeGen/GlobalISel/GISelKnownBits.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/giselworklist-h">llvm/CodeGen/GlobalISel/GISelWorkList.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizationartifactcombiner-h">llvm/CodeGen/GlobalISel/LegalizationArtifactCombiner.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerhelper-h">llvm/CodeGen/GlobalISel/LegalizerHelper.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/lostdebuglocobserver-h">llvm/CodeGen/GlobalISel/LostDebugLocObserver.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/utils-h">llvm/CodeGen/GlobalISel/Utils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineoptimizationremarkemitter-h">llvm/CodeGen/MachineOptimizationRemarkEmitter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetpassconfig-h">llvm/CodeGen/TargetPassConfig.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetsubtargetinfo-h">llvm/CodeGen/TargetSubtargetInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/error-h">llvm/Support/Error.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-legalizer-cpp-">anonymous{Legalizer.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-legalizer-cpp-/legalizerworklistmanager">LegalizerWorkListManager</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad606e18552ce522017caee6d1d5cc1da">InstListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/giselworklist">GISelWorkList</a>&lt; 256 &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24bf6f772022453429bea54ad04c37e0">ArtifactListTy</a> = <a href="/web-llvm/docs/api/classes/llvm/giselworklist">GISelWorkList</a>&lt; 128 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">DebugLocVerifyLevel { <a href="#a2fa4b566de1ff9deb94d257205ab1287">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3a321241cc2af15a42a976d4050fbf4">INITIALIZE_PASS_BEGIN</a> (Legalizer, DEBUG_TYPE, "Legalize the Machine IR a function's Machine IR", false, false) INITIALIZE_PASS_END(Legalizer</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af91cf54b65532db208b58da1d75beb95">isArtifact</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77f29714594e03e6610dd28c3e640121">EnableCSEInLegalizer</a>("enable-cse-in-legalizer", cl::desc("Should enable CSE in Legalizer"), cl::Optional, cl::init(false))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadc8d9f80f0db5f1b619cb8f6986fc54">AllowGInsertAsArtifact</a>("allow-ginsert-as-artifact", cl::desc("Allow G_INSERT to be considered an artifact. Hack around AMDGPU " "test infinite loops."), cl::Optional, cl::init(true))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="#a2fa4b566de1ff9deb94d257205ab1287">DebugLocVerifyLevel</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34be0c7a0e3ff464858db0d6cc470545">VerifyDebugLocs</a>("verify-legalizer-debug-locs", cl::desc("Verify that debug locations are handled"), cl::values(clEnumValN(DebugLocVerifyLevel::None, "none", "No verification"), clEnumValN(DebugLocVerifyLevel::Legalizations, "legalizations", "Verify legalizations"), clEnumValN(DebugLocVerifyLevel::LegalizationsAndArtifactCombiners, "legalizations+artifactcombiners", "Verify legalizations and artifact combines")), cl::init(DebugLocVerifyLevel::Legalizations))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a030569d5a541b6110f2ae1b6a3413a58">DEBUG_TYPE</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#a7c8629d171009c0e4c7c0ceffb88dc3f">Legalize</a> the <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> IR a <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> s <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ab4853f7153e537774d02580e761ec">IR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuregbanklegalize-cpp/#a7c8629d171009c0e4c7c0ceffb88dc3f">Legalize</a> the <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> <a href="#a05ab4853f7153e537774d02580e761ec">IR</a> a <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a> s <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717c6d0759916620a89cee19c1d86181">false</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"legalizer"</td>
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

## Typedefs

### ArtifactListTy {#a24bf6f772022453429bea54ad04c37e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ArtifactListTy =  GISelWorkList&lt;128&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>

</div>
</div>

### InstListTy {#ad606e18552ce522017caee6d1d5cc1da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using InstListTy =  GISelWorkList&lt;256&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### DebugLocVerifyLevel {#a2fa4b566de1ff9deb94d257205ab1287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class DebugLocVerifyLevel </td>
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
<td class="doxyEnumItemName">None<a id="a2fa4b566de1ff9deb94d257205ab1287a6adf97f83acf6453d4a6a4b1070f3754"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Legalizations<a id="a2fa4b566de1ff9deb94d257205ab1287af3b30f7606c3e044746ccbe1cde326ca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LegalizationsAndArtifactCombiners<a id="a2fa4b566de1ff9deb94d257205ab1287ab2adbb3cdb27a6125ee275fdb4479d08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### INITIALIZE\_PASS\_BEGIN() {#af3a321241cc2af15a42a976d4050fbf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS_BEGIN (<a href="/web-llvm/docs/api/classes/llvm/legalizer">Legalizer</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, "Legalize the <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> <a href="#a05ab4853f7153e537774d02580e761ec">IR</a> a <a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>'s <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a> IR", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/passsupport-h/#a14724f1ccf528e73bb29bc9230737967">INITIALIZE_PASS_DEPENDENCY</a>.</p>

</div>
</div>

### isArtifact() {#af91cf54b65532db208b58da1d75beb95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isArtifact (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>


<p>References <a href="#aadc8d9f80f0db5f1b619cb8f6986fc54">AllowGInsertAsArtifact</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-legalizer-cpp-/legalizerworklistmanager/#afde107b97f229ff453d99c9ef1c9a752">anonymous{Legalizer.cpp}::LegalizerWorkListManager::createdOrChangedInstr</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### AllowGInsertAsArtifact {#aadc8d9f80f0db5f1b619cb8f6986fc54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; AllowGInsertAsArtifact("allow-ginsert-as-artifact", cl::desc("Allow G_INSERT to be considered an artifact. Hack around AMDGPU " "test infinite loops."), cl::Optional, cl::init(true))</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>


<p>Referenced by <a href="#af91cf54b65532db208b58da1d75beb95">isArtifact</a>.</p>

</div>
</div>

### DEBUG\_TYPE {#a030569d5a541b6110f2ae1b6a3413a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DEBUG_TYPE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>

</div>
</div>

### EnableCSEInLegalizer {#a77f29714594e03e6610dd28c3e640121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; EnableCSEInLegalizer("enable-cse-in-legalizer", cl::desc("Should enable CSE in Legalizer"), cl::Optional, cl::init(false))</td>
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



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>.</p>

</div>
</div>

### false {#a717c6d0759916620a89cee19c1d86181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Legalize the Machine IR a function s Machine false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>

</div>
</div>

### IR {#a05ab4853f7153e537774d02580e761ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Legalize the Machine IR a function s Machine IR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/analysismanager/invalidator/#affedfb8108f90597f24e166b7a36953b">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::AnalysisManager</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a75514cc4632af88b58a31912c8bd9ecc">anonymous{InlineCost.cpp}::CallAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#ace15c0f86fa672d5a700a5f76b8b43e9">anonymous{InlineCost.cpp}::CallAnalyzer::analyzeBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#a9651d447561aa0aea1b3171eee94152c">llvm::mca::Scheduler::analyzeDataDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/ircomparer/#a8760ed87ce8c468e4567141d3000e67c">llvm::IRComparer&lt; T &gt;::analyzeIR</a>, <a href="/web-llvm/docs/api/classes/llvm/outeranalysismanagerproxy/result/#a51fc041b40fa7aa5f0171456b6954c5c">llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::Result::cachedResultExists</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour/#a17cb5a2e79bf568a343e0beb4176cbec">llvm::mca::AMDGPUCustomBehaviour::checkCustomHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour/#a1733693fc63741279331007c38453223">llvm::mca::CustomBehaviour::checkCustomHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/stage/#a5ae5aa19b925917430fcdc4ce6edd5ed">llvm::mca::Stage::checkNextStage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ac6ed6656160779919f747bc67182abd7">llvm::mca::checkRegisterHazard</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a4926331431f03253ee3ec8e6e3bb9d1c">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a4926331431f03253ee3ec8e6e3bb9d1c">llvm::AnalysisManager&lt; LazyCallGraph::SCC, LazyCallGraph &amp; &gt;::clear</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab88715985e19d51a306fb8be0cf857f3">llvm::mca::Scheduler::cycleEvent</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a1a46c32b644b2910e18fcfec055afeae">llvm::mca::ExecuteStage::cycleStart</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/inorderissuestage/#ab18add1ebf835902d6a2dd4feaa80719">llvm::mca::InOrderIssueStage::cycleStart</a>, <a href="/web-llvm/docs/api/classes/anonymous-deltatree-cpp-/deltatreeinteriornode/#ae2b126b1962c92377b948a1edcbdc223">anonymous{DeltaTree.cpp}::DeltaTreeInteriorNode::DeltaTreeInteriorNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#ac6a40d1885d6a63e525caab19137600d">llvm::mca::LSUnit::dispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a15ee706711d88e4858baa2af17133ab6">llvm::mca::LSUnitBase::dispatch</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#ad03428817244b060d06091dca8afdd9e">llvm::mca::RetireControlUnit::dispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab72375182cfa0b8e37b997b861e35208">llvm::mca::Scheduler::dispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/dispatchstage/#ad34ac262470372100379c302abe5b54f">llvm::mca::DispatchStage::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#ab745e03cf7c86d0b422cca9650a10175">llvm::mca::ExecuteStage::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/inorderissuestage/#a8de83f23b94fb81affc3528986eb9971">llvm::mca::InOrderIssueStage::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/instructiontables/#a6ffb9a2c7dd35d00caafff2f009ecd81">llvm::mca::InstructionTables::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/microopqueuestage/#ab4db56b3ab3cdbb7f70a228efba56839">llvm::mca::MicroOpQueueStage::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/retirestage/#a76d48aaace0410f399f254af62562d48">llvm::mca::RetireStage::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/stage/#a87e62ecf6f249b00c80cd222607af96d">llvm::mca::Stage::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#aaff2876b7e8a6b5df02f3a716d3270b6">llvm::mca::findFirstWriteBackCycle</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#a5b14d5da7cee7c1f361797aee3456a15">llvm::ChangeReporter&lt; IRUnitT &gt;::generateIRRepresentation</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a3ac37a6f140c650acd870e4c5713660f">llvm::DotCfgChangeReporter::generateIRRepresentation</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinechangeprinter/#aa5359fcdd79ecebad94c436ebed24322">llvm::InLineChangePrinter::generateIRRepresentation</a>, <a href="/web-llvm/docs/api/classes/llvm/irchangedprinter/#ab0ea023a570b1c06ae878cfef19ef84d">llvm::IRChangedPrinter::generateIRRepresentation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#abd2eb0563df3078fb91a47d6203fe1d6">llvm::detail::getAnalysisResult</a>, <a href="/web-llvm/docs/api/namespaces/llvm/detail/#a3e963cca46ea36a2967e79d149d302aa">llvm::detail::getAnalysisResultUnpackTuple</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a828ff8185f881fca9e3d534781244041">llvm::AnalysisManager&lt; LazyCallGraph::SCC, LazyCallGraph &amp; &gt;::getCachedResult</a>, <a href="/web-llvm/docs/api/classes/llvm/outeranalysismanagerproxy/result/#a11b47a107f405156c54ef83b8529459b">llvm::OuterAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::Result::getCachedResult</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6414ec52d659d2e3fcc5dc03510c228a">GetFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a625612d532a03e28fdb25753f7713df4">getIRFileDisplayName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a36e1a8f3f395e3a595cc1fa2e8c337b0">anonymous{StandardInstrumentations.cpp}::getIRName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a6367d869a0803b02032f225d9ff6d70c">anonymous{StandardInstrumentations.cpp}::getModuleForComparison</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#aaab1fad63e4f3b8679469720a873fedd">llvm::AnalysisManager&lt; LazyCallGraph::SCC, LazyCallGraph &amp; &gt;::getResult</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#abdd394d923544b065d3bacb30ab0eb14">llvm::DotCfgChangeReporter::handleAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinechangeprinter/#a6560be42758e4a21d3a0075d6b14ad89">llvm::InLineChangePrinter::handleAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/textchangereporter/#af52bf759710c0bfb3e5188a2e4c016c5">llvm::TextChangeReporter&lt; std::string &gt;::handleFiltered</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#a6fa0872bd1b79f2febb9d0d95c6e9feb">llvm::ChangeReporter&lt; IRUnitT &gt;::handleInitialIR</a>, <a href="/web-llvm/docs/api/classes/llvm/dotcfgchangereporter/#a615c5ec895d4fc067bccdf23990d691e">llvm::DotCfgChangeReporter::handleInitialIR</a>, <a href="/web-llvm/docs/api/classes/llvm/irchangedtester/#aba91e52ed6f18529949ae8aa7d46c4f7">llvm::IRChangedTester::handleInitialIR</a>, <a href="/web-llvm/docs/api/classes/llvm/textchangereporter/#a0717f8e10376a5a21049544f98ae975b">llvm::TextChangeReporter&lt; IRUnitT &gt;::handleInitialIR</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#a7a57fcd8f955992d5167dae6978748f2">llvm::ChangeReporter&lt; IRUnitT &gt;::handleIRAfterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#af68c0bcc1be9b7bb804bde87c0840009">llvm::mca::LSUnit::hasDependentUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#ad2672e3089d5229528b5d3f93ea2320d">llvm::mca::LSUnitBase::hasDependentUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a8e87df84ac950f96d723ee1cd6535cf1">llvm::mca::hasResourceHazard</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagongeninsert-cpp-/ifrecord/#a4636a7ebbae2ddea914abc2605e0fc2e">anonymous{HexagonGenInsert.cpp}::IFRecord::IFRecord</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ae2e95803b97c6de37b0d99d390102494">llvm::mca::Scheduler::instructionCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a64b2a209a16bcd41375b5cae12690eaa">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/invalidator/#a1a323b36498775645d82d4193998ed74">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/invalidator/#a5e8e9230fa677542877d1f3c6ff95ae2">llvm::AnalysisManager&lt; IRUnitT, ExtraArgTs &gt;::Invalidator::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a64b2a209a16bcd41375b5cae12690eaa">llvm::AnalysisManager&lt; LazyCallGraph::SCC, LazyCallGraph &amp; &gt;::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultconcept/#aed810e47a1f277849f34ba839bd8a587">llvm::detail::AnalysisResultConcept&lt; IRUnitT, Invalidator &gt;::invalidate</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/analysisresultmodel-e14ac5d3d3a9272adbd262bf85f25321/#aec053381974c9d23327fab318b6d92ed">llvm::detail::AnalysisResultModel&lt; IRUnitT, PassT, ResultT, InvalidatorT, true &gt;::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/functionanalysismanagermachinefunctionproxy/result/#adbea5f480de500f91ac892c6fa549750">llvm::FunctionAnalysisManagerMachineFunctionProxy::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/inneranalysismanagerproxy/result/#a47dfb02025fa19252d966afc602e6d5d">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs &gt;::Result::invalidate</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/dispatchstage/#ab376c6cdb1b9803565f1279410fc330f">llvm::mca::DispatchStage::isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a2f475f283edc7f4c973b827eb341378f">llvm::mca::ExecuteStage::isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/inorderissuestage/#a9e67f693cb5334c23fbe575f055915a1">llvm::mca::InOrderIssueStage::isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#a12bbf977180dc8455fc617db14cef788">llvm::mca::LSUnit::isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a4e3c49c1cddd6720166668d97871b923">llvm::mca::LSUnitBase::isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/microopqueuestage/#a03516d8eb67356141e2131bb410f6e33">llvm::mca::MicroOpQueueStage::isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#a5edfbe268d597c17c00c74ccc1cf59c4">llvm::mca::Scheduler::isAvailable</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/stage/#a67afd1b3d6c26fc6bbf165e27de8f8cd">llvm::mca::Stage::isAvailable</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#aedc4f4ea606ac0d1b036400c31d43da9">anonymous{StandardInstrumentations.cpp}::isInteresting</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#a0df69663296c20af0947fb360969568f">llvm::mca::LSUnit::isPending</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#abe96d6cd4238f910c5236885de8ac246">llvm::mca::LSUnitBase::isPending</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#a192996631c3d58d3c300c240a380ba1a">llvm::mca::LSUnit::isReady</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a393eeeb81c0a6b2883e64e20b54387bc">llvm::mca::LSUnitBase::isReady</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#a216ffefe6fe4a2b566a72228c0bd763d">llvm::mca::Scheduler::issueInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#aad2517356b24e7a39efa8f90aa36d39c">llvm::mca::LSUnit::isWaiting</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#aacfc59e75a326ee09a830b36c1dad6fa">llvm::mca::LSUnitBase::isWaiting</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/stage/#a5816a1de7e5ac29482ac337385e120c2">llvm::mca::Stage::moveToTheNextStage</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#ab8e4d85b5f90fc2efe108d87e78e9a87">llvm::mca::Scheduler::mustIssueImmediately</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a4ddf17adf885048e4c25d9d0449aa4b8">llvm::mca::ExecuteStage::notifyInstructionExecuted</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a77887564c07f9dd27b7ad75b5f8bfeb2">llvm::mca::ExecuteStage::notifyInstructionIssued</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#abc4b047857e33ad1c0049c77c80ca62b">llvm::mca::ExecuteStage::notifyInstructionPending</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a9fb6fe9824e5ece03a031ed4091027c6">llvm::mca::ExecuteStage::notifyInstructionReady</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/retirestage/#a2ec0334026766ccfcad56491d5a81110">llvm::mca::RetireStage::notifyInstructionRetired</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/executestage/#a835477504117bd95fb32a9ea60e4b42b">llvm::mca::ExecuteStage::notifyReservedOrReleasedBuffers</a>, <a href="/web-llvm/docs/api/classes/llvm/textchangereporter/#a8b6328ccff06e4ca69ae857e476b1df0">llvm::TextChangeReporter&lt; std::string &gt;::omitAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a2ed5eda3550114a31e99d480c045bfc2">llvm::mca::LSUnit::MemoryGroup::onGroupIssued</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#a4f4e4ae1e75e2e46828be5c0cc055d07">llvm::mca::LSUnit::MemoryGroup::onInstructionExecuted</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#a8201f572ba1e14162d280b841cb461de">llvm::mca::LSUnit::onInstructionExecuted</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a5b94065d1c6634bea32ff5560ed45c7d">llvm::mca::LSUnitBase::onInstructionExecuted</a>, <a href="/web-llvm/docs/api/structs/llvm/mca/retirecontrolunit/#a99eab7149433edc8264c153810849952">llvm::mca::RetireControlUnit::onInstructionExecuted</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/memorygroup/#ac97627baabc9947fa54f74274809b9d5">llvm::mca::LSUnit::MemoryGroup::onInstructionIssued</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#a51b3961e97dde2e7085c871c0c94cc92">llvm::mca::LSUnit::onInstructionIssued</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#afa067c3556c68e3b8a3527cf6b88d4e3">llvm::mca::LSUnitBase::onInstructionIssued</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunit/#aada932f39510a67ca421c25782d87e5d">llvm::mca::LSUnit::onInstructionRetired</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/lsunitbase/#a5b0a4d24a28315948079a27d13a6463a">llvm::mca::LSUnitBase::onInstructionRetired</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#a69edd837c2cd0bbf8d932e596ba7d85d">llvm::mca::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c543da82f5058d4a4270c45e33d0681">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/timeprofilingpasseshandler/#a0974d93ee646e86089181c0fcc12da7b">llvm::TimeProfilingPassesHandler::operator=</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a696283c30308704d020a9d86065aa3ae">planContainsAdditionalSimplifications</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e747628bd3eea8ba888d3615c900c9f">llvm::printIRUnitNameForStackTrace</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/classes/llvm/debugifyeachinstrumentation/#ac08162972dd07f89c515c12aa05aa279">llvm::DebugifyEachInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#a098ebeae73eb3b1c09384466602931e7">llvm::DroppedVariableStatsIR::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/optnoneinstrumentation/#a13ae8310145a23455c25478da7fa8e39">llvm::OptNoneInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgateinstrumentation/#ab2b73a9eaecb02a4ec3beebaa431b972">llvm::OptPassGateInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/preservedcfgcheckerinstrumentation/#aed649cf558f93dc41694657bc7f2442c">llvm::PreservedCFGCheckerInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/printcrashirinstrumentation/#af4e053aebd6ae8747dd34fbfc4c2ca47">llvm::PrintCrashIRInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/printirinstrumentation/#ab0452d76147dabbf5c7701d0a95aa068">llvm::PrintIRInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/printpassinstrumentation/#a632f3dfe4f8043f8c6b50498ad7aba02">llvm::PrintPassInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeverifier/#a3c0c496c912a11733edef199e5ae5473">llvm::PseudoProbeVerifier::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/timeprofilingpasseshandler/#a04ce26b9550579b73f15d79567dc8839">llvm::TimeProfilingPassesHandler::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/verifyinstrumentation/#abfec9362909844b463ec07ef82233199">llvm::VerifyInstrumentation::registerCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#aa2fb31feeaf10f23b54a75e244c80035">llvm::ChangeReporter&lt; IRUnitT &gt;::registerRequiredCallbacks</a>, <a href="/web-llvm/docs/api/classes/llvm/orderedchangeddata/#a08f0240b1df29f4783ccd0e0f7ced7b7">llvm::OrderedChangedData&lt; BlockDataT&lt; T &gt; &gt;::report</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassconcept/#a3a47515e955e83e139f7ff2a50bc9348">llvm::detail::AnalysisPassConcept&lt; IRUnitT, Invalidator, ExtraArgTs... &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/analysispassmodel/#ab7cb7eff46888a5b3c8b4d3d6578b13d">llvm::detail::AnalysisPassModel&lt; IRUnitT, PassT, InvalidatorT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/passconcept/#af397f5b2bf1d7cdc52a6032047f8fbc4">llvm::detail::PassConcept&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>, <a href="/web-llvm/docs/api/structs/llvm/detail/passmodel/#a75180e1269e5bc1ab15f89587ac1794c">llvm::detail::PassModel&lt; IRUnitT, PassT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontolooppassadaptor/#aee681bfb37f62d30a1d0a1f47d73b4f1">llvm::FunctionToLoopPassAdaptor::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/inneranalysismanagerproxy/#a3add1957ddf106ee6dc26ce921d8efd4">llvm::InnerAnalysisManagerProxy&lt; CGSCCAnalysisManager, Module &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; IRUnitT, AnalysisManagerT, ExtraArgTs &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passmanager/#aef5d9142acafceffd14c76b8ddd0fd4e">llvm::PassManager&lt; LazyCallGraph::SCC, CGSCCAnalysisManager, LazyCallGraph &amp;, CGSCCUpdateResult &amp; &gt;::run</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#adda8476ef0007c61013ba8e5c46c6693">llvm::PassInstrumentation::runAfterAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#abe7c231e11ef6c5345cbf3f9e9ae7979">llvm::DroppedVariableStatsIR::runAfterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#acec038dce9072b64301f6e5226c5579a">llvm::PassInstrumentation::runAfterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeverifier/#ac60402c1f75ca79798e4924098bd2066">llvm::PseudoProbeVerifier::runAfterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#a698253acb40299131fecdb9489f88fcd">llvm::PassInstrumentation::runAnalysisInvalidated</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#a5a2cc6fe0017dd7067b103118a7bc914">llvm::PassInstrumentation::runBeforeAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/droppedvariablestatsir/#a07f08df571060b6c07de22e8211a6b39">llvm::DroppedVariableStatsIR::runBeforePass</a>, <a href="/web-llvm/docs/api/classes/llvm/passinstrumentation/#aead32b9af4b66a742d37585c6d6b4cbc">llvm::PassInstrumentation::runBeforePass</a>, <a href="/web-llvm/docs/api/classes/llvm/changereporter/#a0cf6b2cb664ca54095b4f6dfc5e548cc">llvm::ChangeReporter&lt; IRUnitT &gt;::saveIRBeforePass</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/scheduler/#a0113fd8e2f25ac69b90b9ac8ded672f6">llvm::mca::Scheduler::select</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#aec8bb71b7152d7e2a5474bb8e1af963c">anonymous{StandardInstrumentations.cpp}::shouldPrintIR</a>, <a href="/web-llvm/docs/api/classes/llvm/optpassgateinstrumentation/#ae62ce11c6238e393618108540027706f">llvm::OptPassGateInstrumentation::shouldRun</a>, <a href="/web-llvm/docs/api/classes/llvm/textchangereporter/#a5463cbf4b9180422d433483572f9bde8">llvm::TextChangeReporter&lt; std::string &gt;::TextChangeReporter</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#adb1dafd461988f3d8e687eabb99e108d">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryInlineCandidate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a507e5d660f25cdd66f8289d7a2864c33">anonymous{StandardInstrumentations.cpp}::unwrapAndPrint</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#aadda06082cd66f0282ca446bc410dfb6">unwrapIR</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-standardinstrumentations-cpp-/#a88c780934618af67e6d51ba7f5e339f4">anonymous{StandardInstrumentations.cpp}::unwrapModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mca/#ab24e9ac7e416812424904af7a1da17c3">llvm::mca::verifyInstructionEliminated</a>, <a href="/web-llvm/docs/api/classes/llvm/analysismanager/#a29648f060d2dd1e126ed17733813cf0a">llvm::AnalysisManager&lt; LazyCallGraph::SCC, LazyCallGraph &amp; &gt;::verifyNotInvalidated</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/amdgpucustombehaviour/#a690f1af5fe823121581fc0f21e8dd21c">llvm::mca::AMDGPUCustomBehaviour::~AMDGPUCustomBehaviour</a>, <a href="/web-llvm/docs/api/classes/llvm/mca/custombehaviour/#a62666ccd5a13e55da4d4b03c80a4c75f">llvm::mca::CustomBehaviour::~CustomBehaviour</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinechangeprinter/#a225705ff0411d7a7d1f5b72754ea8388">llvm::InLineChangePrinter::~InLineChangePrinter</a> and <a href="/web-llvm/docs/api/classes/llvm/irchangedprinter/#a527c38a168e31fd5695da4b37784b876">llvm::IRChangedPrinter::~IRChangedPrinter</a>.</p>

</div>
</div>

### VerifyDebugLocs {#a34be0c7a0e3ff464858db0d6cc470545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; DebugLocVerifyLevel &gt; VerifyDebugLocs("verify-legalizer-debug-locs", cl::desc("Verify that debug locations are handled"), cl::values( clEnumValN(DebugLocVerifyLevel::None, "none", "No verification"), clEnumValN(DebugLocVerifyLevel::Legalizations, "legalizations", "Verify legalizations"), clEnumValN(DebugLocVerifyLevel::LegalizationsAndArtifactCombiners, "legalizations+artifactcombiners", "Verify legalizations and artifact combines")), cl::init(DebugLocVerifyLevel::Legalizations))</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a80314c2b261b78cb7335a265f43ba1b5">llvm::Legalizer::legalizeMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/legalizer/#a356f9de405c2904f7ad73659a2f378a0">llvm::Legalizer::runOnMachineFunction</a>.</p>

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
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"legalizer"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizer-cpp">Legalizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
