---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/codegen/machinefunctionsplitter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `MachineFunctionSplitter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/branchprobabilityinfo-h">llvm/Analysis/BranchProbabilityInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/ehutils-h">llvm/Analysis/EHUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/profilesummaryinfo-h">llvm/Analysis/ProfileSummaryInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionutils-h">llvm/CodeGen/BasicBlockSectionUtils.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/basicblocksectionsprofilereader-h">llvm/CodeGen/BasicBlockSectionsProfileReader.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinebasicblock-h">llvm/CodeGen/MachineBasicBlock.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machineblockfrequencyinfo-h">llvm/CodeGen/MachineBlockFrequencyInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunction-h">llvm/CodeGen/MachineFunction.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinefunctionpass-h">llvm/CodeGen/MachineFunctionPass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinemoduleinfo-h">llvm/CodeGen/MachineModuleInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/passes-h">llvm/CodeGen/Passes.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetinstrinfo-h">llvm/CodeGen/TargetInstrInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/initializepasses-h">llvm/InitializePasses.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include &lt;optional&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-machinefunctionsplitter-cpp-">anonymous{MachineFunctionSplitter.cpp}</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter">MachineFunctionSplitter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d2e87ebd36e82a5a1cce7aa852e159">setDescendantEHBlocksCold</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setDescendantEHBlocksCold - This splits all EH pads and blocks reachable only by EH pad as cold. <a href="#a66d2e87ebd36e82a5a1cce7aa852e159">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3411b0b09b0cc99d828720c839a517">finishAdjustingBasicBlocksAndLandingPads</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a> (const MachineBasicBlock &amp;MBB, const MachineBlockFrequencyInfo *MBFI, ProfileSummaryInfo *PSI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ea0efceda8c2841963e9403722a1803">INITIALIZE_PASS</a> (MachineFunctionSplitter, "machine-function-splitter", "Split machine functions using profile information", false, false) MachineFunctionPass *llvm</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>("mfs-psi-cutoff", cl::desc("Percentile profile summary cutoff used to " "determine cold blocks. Unused if set to zero."), cl::init(999950), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17e9acf4f2e3f412e4af1da184beac9a">ColdCountThreshold</a>("mfs-count-threshold", cl::desc("Minimum number of times a block must be executed to be retained."), cl::init(1), cl::Hidden)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6957f10403e422e880713a771c17e9b">SplitAllEHCode</a>("mfs-split-ehcode", cl::desc("Splits all EH code and it's descendants by default."), cl::init(false), cl::Hidden)</td>
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

### finishAdjustingBasicBlocksAndLandingPads() {#a0e3411b0b09b0cc99d828720c839a517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void finishAdjustingBasicBlocksAndLandingPads (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp">MachineFunctionSplitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad42ea8aa2115313dc7f1b793b049e0b1">llvm::avoidZeroOffsetLandingPad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afad2bbe677ba3de73946c95070c7cdb1">llvm::sortBasicBlocksAndUpdateBranches</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>.</p>

</div>
</div>

### INITIALIZE\_PASS() {#a5ea0efceda8c2841963e9403722a1803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">INITIALIZE_PASS (MachineFunctionSplitter, "machine-<a href="/web-llvm/docs/api/files/lib/lib/analysis/regionprinter-cpp/#aa37fbbce2360106772fd97ed06455d55">function</a>-splitter", "Split machine <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowermoduleldspass-cpp/#a8818b45f8c07ddce635268ec684dc61a">functions</a> using profile information", false, false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp">MachineFunctionSplitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abbea1fe84353ae74e7c6ff5e122d2978">llvm::createMachineFunctionSplitterPass</a> and <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a7acc3b5f1afa6f3824eec2cb0dbd1d95">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::MachineFunctionSplitter</a>.</p>

</div>
</div>

### isColdBlock() {#a0045721a7b443c9ed664f9e41abf5cad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isColdBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> * MBFI, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * PSI)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp">MachineFunctionSplitter.cpp</a>.</p>


<p>References <a href="#a17e9acf4f2e3f412e4af1da184beac9a">ColdCountThreshold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#ac9d35ccc615084c6e7da873a9d49c2ed">llvm::MachineBlockFrequencyInfo::getBlockProfileCount</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a077d500a5e9209486b76dd5da3e673c4">llvm::ProfileSummaryInfo::hasCSInstrumentationProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a21a2dd574b9729dcd05b46dae856ebc4">llvm::ProfileSummaryInfo::hasInstrumentationProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a42c9b372f129ae40b72b97ce6df45eed">llvm::ProfileSummaryInfo::hasSampleProfile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a731b588787c30ac1905c449402cc8b06">llvm::ProfileSummaryInfo::isColdCountNthPercentile</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="#aa9a7a2d102bd9e5a4c6569f16de79b87">PercentileCutoff</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>.</p>

</div>
</div>

### setDescendantEHBlocksCold() {#a66d2e87ebd36e82a5a1cce7aa852e159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setDescendantEHBlocksCold (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>setDescendantEHBlocksCold - This splits all EH pads and blocks reachable only by EH pad as cold.</p>


<p>This will help mark EH pads statically cold instead of relying on profile data.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp">MachineFunctionSplitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/structs/llvm/mbbsectionid/#a2cbbe04f568b5890eeb2b58c0cbf6d71">llvm::MBBSectionID::ColdSectionID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a87783f5762b2359e185e5341a744030a">llvm::computeEHOnlyBlocks</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ColdCountThreshold {#a17e9acf4f2e3f412e4af1da184beac9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; ColdCountThreshold("mfs-count-threshold", cl::desc( "Minimum number of times a block must be executed to be retained."), cl::init(1), cl::Hidden)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp">MachineFunctionSplitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a78deffb09f38652d08cb57cce3119fc7">annotateAllFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummarybuilder/#ada15196a850a1aba577e73e5f29b14d9">llvm::ProfileSummaryBuilder::getColdCountThreshold</a>, <a href="#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontexttrimmer/#ab47fa20fa1c0dd43ae044963ee59049c">llvm::sampleprof::SampleContextTrimmer::trimAndMergeColdContextProfiles</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a6c13c3a269c58cac403ad567c29d679e">verifyFuncBFI</a>.</p>

</div>
</div>

### PercentileCutoff {#aa9a7a2d102bd9e5a4c6569f16de79b87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; unsigned &gt; PercentileCutoff("mfs-psi-cutoff", cl::desc("Percentile profile summary cutoff used to " "determine cold blocks. Unused if set to zero."), cl::init(999950), cl::Hidden)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp">MachineFunctionSplitter.cpp</a>.</p>


<p>Referenced by <a href="#a0045721a7b443c9ed664f9e41abf5cad">isColdBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#ac125007461291d169ae8c200550184ec">llvm::ProfileSummaryInfo::isColdBlockNthPercentile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#ada543df24b6c3fa80f90e0aab1bb68f2">llvm::ProfileSummaryInfo::isColdBlockNthPercentile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a731b588787c30ac1905c449402cc8b06">llvm::ProfileSummaryInfo::isColdCountNthPercentile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a3b3f19a7c246b09a46ab4dcf3b05e212">llvm::ProfileSummaryInfo::isFunctionColdInCallGraphNthPercentile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a6f820b8a83376970321b6e7211df6087">llvm::ProfileSummaryInfo::isFunctionHotInCallGraphNthPercentile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#af4346625334107fbea42a8e1d607a20a">llvm::ProfileSummaryInfo::isHotBlockNthPercentile</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a199ef173a063b51608e3438d8ab325d9">llvm::ProfileSummaryInfo::isHotBlockNthPercentile</a> and <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#a829b6546f1d344de8cc5a6be1dd1e424">llvm::ProfileSummaryInfo::isHotCountNthPercentile</a>.</p>

</div>
</div>

### SplitAllEHCode {#ab6957f10403e422e880713a771c17e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; SplitAllEHCode("mfs-split-ehcode", cl::desc("Splits all EH code and it's descendants by default."), cl::init(false), cl::Hidden)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinefunctionsplitter-cpp">MachineFunctionSplitter.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-machinefunctionsplitter-cpp-/machinefunctionsplitter/#a9f05c8e7366bb0f541cdc6c03b929ddd">anonymous{MachineFunctionSplitter.cpp}::MachineFunctionSplitter::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
