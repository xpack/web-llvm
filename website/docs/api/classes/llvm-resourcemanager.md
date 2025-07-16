---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/resourcemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ResourceManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::ResourceManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">llvm/CodeGen/MachinePipeliner.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b881604ed6d1c9eafbbd61e14dea2cf">ResourceManager</a> (const TargetSubtargetInfo *ST, ScheduleDAGInstrs *DAG)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53238e1dc17529bfe9b2a2802360fdb7">initProcResourceVectors</a> (const MCSchedModel &amp;SM, SmallVectorImpl&lt; uint64_t &gt; &amp;Masks)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfd05fb40b63f3fde78a81e119ed89e3">canReserveResources</a> (SUnit &amp;SU, int Cycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the resources occupied by a machine instruction are available in the current state. <a href="#adfd05fb40b63f3fde78a81e119ed89e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b0369aaa8c87a6969ec5b56700d0d8">reserveResources</a> (SUnit &amp;SU, int Cycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve the resources occupied by a machine instruction and change the current state to reflect that change. <a href="#a66b0369aaa8c87a6969ec5b56700d0d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13a8c4d3fbc72e8e2f7080411e2ea9cf">calculateResMII</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b7c7856215eac794f24f04aa43b93a">init</a> (int II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Initialize resources with the initiation interval II. <a href="#ad2b7c7856215eac794f24f04aa43b93a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09b68eede77d72d5edf13f8bb4603ebd">calculateResMIIDFA</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad80c7e84e1d00fd957afd69cba3a67ab">isOverbooked</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if MRT is overbooked. <a href="#ad80c7e84e1d00fd957afd69cba3a67ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f6a198c94a9c95dcdf95706b6bcde6">reserveResources</a> (const MCSchedClassDesc *SCDesc, int Cycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserve resources on MRT. <a href="#ab6f6a198c94a9c95dcdf95706b6bcde6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97b8fa407b2b9c219302d9b47c7ccc6c">unreserveResources</a> (const MCSchedClassDesc *SCDesc, int Cycle)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unreserve resources on MRT. <a href="#a97b8fa407b2b9c219302d9b47c7ccc6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a237c19a969fdbb390ee7da3a006be62c">positiveModulo</a> (int Dividend, int Divisor) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return M satisfying Dividend = Divisor * X + M, 0 &lt; M &lt; Divisor. <a href="#a237c19a969fdbb390ee7da3a006be62c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b9f77358ebfee6ad7cc189e1bfb85f5">dumpMRT</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3746cd8e60d550654fcefbc71e1e130c">STI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82019745da313b3daf517ad0acf1d589">SM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa36e674974d46fe16db9abeaad2aab30">ST</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9656ad3a1eb685bf812b407de7be414e">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b60cf586629fabe6d93d2964b1fec4">DAG</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581915588487ca634fb7152c2918fd77">UseDFA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dfapacketizer">DFAPacketizer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55877303cc864c2fc7321257d1144054">DFAResources</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DFA resources for each slot. <a href="#a55877303cc864c2fc7321257d1144054">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4060b270308b1756861e7a8e5f35917">DefaultProcResSize</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08c957a510b5f10dd6b03dd9129c508">MRT</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Modulo Reservation Table. <a href="#ad08c957a510b5f10dd6b03dd9129c508">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2128c1c5408bf4279f3a211da92408f">NumScheduledMops</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of scheduled micro operations for each slot. <a href="#ae2128c1c5408bf4279f3a211da92408f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">llvm::SmallVector</a>&lt; uint64_t, <a href="/web-llvm/docs/api/namespaces/llvm/#ae4060b270308b1756861e7a8e5f35917">DefaultProcResSize</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b137553584b6d48d736353c29ff854">ProcResourceMasks</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Each processor resource is associated with a so-called processor resource mask. <a href="#a63b137553584b6d48d736353c29ff854">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1e36c6d0f3e8bb782dda232c5d1fe0">InitiationInterval</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1556ec73df6b85c2878190942bc8547d">IssueWidth</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The number of micro operations that can be scheduled at a cycle. <a href="#a1556ec73df6b85c2878190942bc8547d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 582 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ResourceManager() {#a6b881604ed6d1c9eafbbd61e14dea2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ResourceManager::ResourceManager (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo">TargetSubtargetInfo</a> * ST, <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs">ScheduleDAGInstrs</a> * DAG)</td>
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



<p>Definition at line 632 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>


<p>References <a href="#a53238e1dc17529bfe9b2a2802360fdb7">initProcResourceVectors</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af79a93ddfb0d73e19baa7d6cf35a26aa">llvm::SwpForceIssueWidth</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### calculateResMII() {#a13a8c4d3fbc72e8e2f7080411e2ea9cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ResourceManager::calculateResMII ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3664 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#ab7b0ef1f5af7f95492f8bf39415123f2">llvm::MCSchedClassDesc::NumMicroOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a344d720a7ebe102df73347e41937f329">SwpDebugResource</a>.</p>

</div>
</div>

### canReserveResources() {#adfd05fb40b63f3fde78a81e119ed89e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceManager::canReserveResources (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU, int Cycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the resources occupied by a machine instruction are available in the current state.</p>

<p>Declaration at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3509 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abf37b74e017f80f204221fe3143ab89f">llvm::MachineInstr::isPseudo</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a344d720a7ebe102df73347e41937f329">SwpDebugResource</a>.</p>

</div>
</div>

### init() {#ad2b7c7856215eac794f24f04aa43b93a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceManager::init (int II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Initialize resources with the initiation interval II.</p>

<p>Declaration at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3739 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>.</p>

</div>
</div>

### initProcResourceVectors() {#a53238e1dc17529bfe9b2a2802360fdb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceManager::initProcResourceVectors (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedmodel">MCSchedModel</a> &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; Masks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3467 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc/#a51dc4747a7d39650884bcf19daaf5f54">llvm::MCProcResourceDesc::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/mcprocresourcedesc/#a9d4d0cc34fcce4779dc4445d8265fffc">llvm::MCProcResourceDesc::NumUnits</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#abf554e5ebe4ee5fa894e8842904376d0">SwpShowResMask</a>.</p>


<p>Referenced by <a href="#a6b881604ed6d1c9eafbbd61e14dea2cf">ResourceManager</a>.</p>

</div>
</div>

### reserveResources() {#a66b0369aaa8c87a6969ec5b56700d0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceManager::reserveResources (<a href="/web-llvm/docs/api/classes/llvm/sunit">SUnit</a> &amp; SU, int Cycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reserve the resources occupied by a machine instruction and change the current state to reflect that change.</p>

<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3535 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a75a5f7e3b3d4ec79610b4e556d2f35ce">llvm::MachineInstr::getDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/sunit/#afc98c2c5417cad1a90fc4fe241fe8ba4">llvm::SUnit::getInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#abf37b74e017f80f204221fe3143ab89f">llvm::MachineInstr::isPseudo</a>, <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc/#a03f7e8be243cde4843e2854d91bfa082">llvm::MCSchedClassDesc::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp/#a344d720a7ebe102df73347e41937f329">SwpDebugResource</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateResMIIDFA() {#a09b68eede77d72d5edf13f8bb4603ebd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ResourceManager::calculateResMIIDFA ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 608 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3601 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### dumpMRT() {#a7b9f77358ebfee6ad7cc189e1bfb85f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceManager::dumpMRT ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 628 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3445 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### isOverbooked() {#ad80c7e84e1d00fd957afd69cba3a67ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ResourceManager::isOverbooked ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if MRT is overbooked.</p>

<p>Declaration at line 610 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3587 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### positiveModulo() {#a237c19a969fdbb390ee7da3a006be62c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ResourceManager::positiveModulo (int Dividend, int Divisor)</td>
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

<p>Return M satisfying Dividend = Divisor * X + M, 0 &lt; M &lt; Divisor.</p>


<p>The slot on MRT to reserve a resource for the cycle C is positiveModulo(C,
II).</p>


<p>Definition at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### reserveResources() {#ab6f6a198c94a9c95dcdf95706b6bcde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceManager::reserveResources (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SCDesc, int Cycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reserve resources on MRT.</p>

<p>Declaration at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3563 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

### unreserveResources() {#a97b8fa407b2b9c219302d9b47c7ccc6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ResourceManager::unreserveResources (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/mcschedclassdesc">MCSchedClassDesc</a> * SCDesc, int Cycle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unreserve resources on MRT.</p>

<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>, definition at line 3575 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DAG {#ae1b60cf586629fabe6d93d2964b1fec4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScheduleDAGInstrs* llvm::ResourceManager::DAG</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### DFAResources {#a55877303cc864c2fc7321257d1144054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;std::unique_ptr&lt;DFAPacketizer&gt; &gt; llvm::ResourceManager::DFAResources</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>DFA resources for each slot.</p>

<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### InitiationInterval {#acc1e36c6d0f3e8bb782dda232c5d1fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ResourceManager::InitiationInterval = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### IssueWidth {#a1556ec73df6b85c2878190942bc8547d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::ResourceManager::IssueWidth</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of micro operations that can be scheduled at a cycle.</p>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### MRT {#ad08c957a510b5f10dd6b03dd9129c508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;llvm::SmallVector&lt;uint64_t, DefaultProcResSize&gt; &gt; llvm::ResourceManager::MRT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Modulo Reservation Table.</p>


<p>When a resource with <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> R is consumed in cycle C, it is counted in MRT[C mod II][R]. (Used when UseDFA == F)</p>


<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### NumScheduledMops {#ae2128c1c5408bf4279f3a211da92408f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;int&gt; llvm::ResourceManager::NumScheduledMops</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The number of scheduled micro operations for each slot.</p>


<p>Micro operations are assumed to be scheduled one per cycle, starting with the cycle in which the instruction is scheduled.</p>


<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### ProcResourceMasks {#a63b137553584b6d48d736353c29ff854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt;uint64_t, DefaultProcResSize&gt; llvm::ResourceManager::ProcResourceMasks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Each processor resource is associated with a so-called processor resource mask.</p>


<p>This vector allows to correlate processor resource IDs with processor resource masks. There is exactly one element per each processor resource declared by the scheduling model.</p>


<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### SM {#a82019745da313b3daf517ad0acf1d589}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSchedModel&amp; llvm::ResourceManager::SM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### ST {#aa36e674974d46fe16db9abeaad2aab30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetSubtargetInfo* llvm::ResourceManager::ST</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### STI {#a3746cd8e60d550654fcefbc71e1e130c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSubtargetInfo* llvm::ResourceManager::STI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### TII {#a9656ad3a1eb685bf812b407de7be414e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::ResourceManager::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

### UseDFA {#a581915588487ca634fb7152c2918fd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::ResourceManager::UseDFA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/machinepipeliner-h">MachinePipeliner.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/machinepipeliner-cpp">MachinePipeliner.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
