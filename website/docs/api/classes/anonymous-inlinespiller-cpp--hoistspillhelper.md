---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `HoistSpillHelper` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{InlineSpiller.cpp}::HoistSpillHelper { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate">Delegate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback methods for <a href="/web-llvm/docs/api/classes/llvm/liverangeedit">LiveRangeEdit</a> owners. <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/delegate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6eddf452a261acf792516aa3e6cc4ab9">MergeableSpillsMap</a> = <a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; std::pair&lt; int, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9060125be37c7bf45b516967b013f94c">HoistSpillHelper</a> (const Spiller::RequiredAnalyses &amp;Analyses, MachineFunction &amp;mf, VirtRegMap &amp;vrm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a802b241b8cfc1f00f85b1d4da7eeed73">addToMergeableSpills</a> (MachineInstr &amp;Spill, int StackSlot, unsigned Original)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When a spill is inserted, add the spill to MergeableSpills map. <a href="#a802b241b8cfc1f00f85b1d4da7eeed73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bed72d6ec635da0c0a6c57442012e6e">rmFromMergeableSpills</a> (MachineInstr &amp;Spill, int StackSlot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When a spill is removed, remove the spill from MergeableSpills map. <a href="#a4bed72d6ec635da0c0a6c57442012e6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597bb5d7ef9a22f44dbe867d8eaa7fd6">hoistAllSpills</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For spills with equal values, remove redundant spills and hoist those left to less hot spots. <a href="#a597bb5d7ef9a22f44dbe867d8eaa7fd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad395a85b9e11855611ae547a3d332b8f">LRE_DidCloneVirtReg</a> (Register, Register) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For VirtReg clone, the <span class="doxyComputerOutput">New</span> register should have the same physreg or stackslot as the <span class="doxyComputerOutput">old</span> register. <a href="#ad395a85b9e11855611ae547a3d332b8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0a515c8f5f551759ff3b06476ec7ba9">isSpillCandBB</a> (LiveInterval &amp;OrigLI, VNInfo &amp;OrigVNI, MachineBasicBlock &amp;BB, Register &amp;LiveReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check BB to see if it is a possible target BB to place a hoisted spill, i.e., there should be a living sibling of OrigReg at the insert point. <a href="#af0a515c8f5f551759ff3b06476ec7ba9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0216a7efb7d1d151d9e7547af0875a5a">rmRedundantSpills</a> (SmallPtrSet&lt; MachineInstr *, 16 &gt; &amp;Spills, SmallVectorImpl&lt; MachineInstr * &gt; &amp;SpillsToRm, DenseMap&lt; MachineDomTreeNode *, MachineInstr * &gt; &amp;SpillBBToSpill)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove redundant spills in the same BB. <a href="#a0216a7efb7d1d151d9e7547af0875a5a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a340502b165cdaf9a02be2dbb873f1d04">getVisitOrders</a> (MachineBasicBlock *Root, SmallPtrSet&lt; MachineInstr *, 16 &gt; &amp;Spills, SmallVectorImpl&lt; MachineDomTreeNode * &gt; &amp;Orders, SmallVectorImpl&lt; MachineInstr * &gt; &amp;SpillsToRm, DenseMap&lt; MachineDomTreeNode *, unsigned &gt; &amp;SpillsToKeep, DenseMap&lt; MachineDomTreeNode *, MachineInstr * &gt; &amp;SpillBBToSpill)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Starting from <span class="doxyComputerOutput">Root</span> find a top-down traversal order of the dominator tree to visit all basic blocks containing the elements of <span class="doxyComputerOutput">Spills</span>. <a href="#a340502b165cdaf9a02be2dbb873f1d04">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f7ed1a22c4d2a891cd66441f5ff73a">runHoistSpills</a> (LiveInterval &amp;OrigLI, VNInfo &amp;OrigVNI, SmallPtrSet&lt; MachineInstr *, 16 &gt; &amp;Spills, SmallVectorImpl&lt; MachineInstr * &gt; &amp;SpillsToRm, DenseMap&lt; MachineBasicBlock *, unsigned &gt; &amp;SpillsToIns)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to hoist spills according to BB hotness. <a href="#ac5f7ed1a22c4d2a891cd66441f5ff73a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7590148f139a9e6c54b135b38167206c">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/liveintervals">LiveIntervals</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ad508b3a4696f929c0ec9966819b756">LIS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livestacks">LiveStacks</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046b6338e408734a118f6d14322be766">LSS</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26c89d59615075ff75e376a7f232761">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36b0b08206669e87bb857841c008cba">VRM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d04c556e575fd6f867c8e457f3cfac">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950195c4956976283fa918b08f6e1d2a">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b1eae2b83a10fd0667402188ad1b6d">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo">MachineBlockFrequencyInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad944096f6192c11034423589e6369bfb">MBFI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/insertpointanalysis">InsertPointAnalysis</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae89f60e383c1fc26b1afdde5ae09276d">IPA</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; int, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d6eb463f146cba734fbb2136e747f45">StackSlotToOrigLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MergeableSpillsMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7002e5075b2f2e71774e15ae3ab5dcc">MergeableSpills</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/smallsetvector">SmallSetVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 16 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52ba090f7be4ecd8bd113a72cd3ff675">Virt2SiblingsMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the map from original register to a set containing all its siblings. <a href="#a52ba090f7be4ecd8bd113a72cd3ff675">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### MergeableSpillsMap {#a6eddf452a261acf792516aa3e6cc4ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{InlineSpiller.cpp}::HoistSpillHelper::MergeableSpillsMap = 
      MapVector&lt;std::pair&lt;int, VNInfo *&gt;, SmallPtrSet&lt;MachineInstr *, 16&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HoistSpillHelper() {#a9060125be37c7bf45b516967b013f94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineSpiller.cpp}::HoistSpillHelper::HoistSpillHelper (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/spiller/requiredanalyses">Spiller::RequiredAnalyses</a> &amp; Analyses, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp; vrm)</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addToMergeableSpills() {#a802b241b8cfc1f00f85b1d4da7eeed73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HoistSpillHelper::addToMergeableSpills (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Spill, int StackSlot, unsigned Original)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When a spill is inserted, add the spill to MergeableSpills map.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/liverange/#ae7eb95d6c78b269fe03ed9c78cf2c33f">llvm::LiveRange::assign</a>, <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a14d46e70db7e417c8ed5bc66fb295185">llvm::LiveInterval::reg</a> and <a href="/web-llvm/docs/api/classes/llvm/liveinterval/#a0fc46dffc68d1302d150b7e4c28c7983">llvm::LiveInterval::weight</a>.</p>

</div>
</div>

### hoistAllSpills() {#a597bb5d7ef9a22f44dbe867d8eaa7fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HoistSpillHelper::hoistAllSpills ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For spills with equal values, remove redundant spills and hoist those left to less hot spots.</p>


<p>Spills with equal values will be collected into the same set in MergeableSpills when spill is inserted. These equal spills are originated from the same defining instruction and are dominated by the instruction. Before hoisting all the equal spills, redundant spills inside in the same BB are first marked to be deleted. Then starting from the spills left, walk up on the dominator tree towards the Root node where the define instruction is located, mark the dominated spills to be deleted along the way and collect the BB nodes on the path from non-dominated spills to the define instruction into a WorkSet. The nodes in WorkSet are the candidate places where we are considering to hoist the spills. We iterate the WorkSet in bottom-up order, and for each node, we will decide whether to hoist spills inside its subtree to that node. In this way, we can get benefit locally even if hoisting all the equal spills to one cold place is impossible.</p>


<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrspan/#a80cf68c228dc30772af16e45ec4f825c">llvm::MachineInstrSpan::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/liverangeedit/#add47e6d974ce584ea3fa3fc80ee34259">llvm::LiveRangeEdit::eliminateDeadDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp/#ac370c41caa198ae51b35d5b35f9b8c81">getVDefInterval</a>, <a href="/web-llvm/docs/api/classes/llvm/vninfo/#ad989a0c1b26066308798f4d11a0e69df">llvm::VNInfo::id</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaee820701392c55ad54235d3d7201206">llvm::MachineOperand::isDead</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a75eb135014670ce946e78739cdc9b51b">llvm::MachineOperand::isDef</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a3bf161859e1ad7fd3da485d3cb688d34">llvm::MachineOperand::isImplicit</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="/web-llvm/docs/api/classes/llvm/liverange/#a325a4ec9c33a3dead9ff01c9e70fd534">llvm::LiveRange::MergeValueInAsValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### LRE\_DidCloneVirtReg() {#ad395a85b9e11855611ae547a3d332b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HoistSpillHelper::LRE_DidCloneVirtReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> New, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Old)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For VirtReg clone, the <span class="doxyComputerOutput">New</span> register should have the same physreg or stackslot as the <span class="doxyComputerOutput">old</span> register.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregmap/#ad2e99ae080aa934d64b0ff504dab0158">llvm::VirtRegMap::NO_STACK_SLOT</a>.</p>

</div>
</div>

### rmFromMergeableSpills() {#a4bed72d6ec635da0c0a6c57442012e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HoistSpillHelper::rmFromMergeableSpills (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; Spill, int StackSlot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When a spill is removed, remove the spill from MergeableSpills map.</p>


<p>Return true if the spill is removed successfully.</p>


<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/slotindex/#ae3b98982e2036f3d26806de5ed5e02d0">llvm::SlotIndex::getRegSlot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getVisitOrders() {#a340502b165cdaf9a02be2dbb873f1d04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HoistSpillHelper::getVisitOrders (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt; &amp; Spills, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> * &gt; &amp; Orders, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; SpillsToRm, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> *, unsigned &gt; &amp; SpillsToKeep, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; SpillBBToSpill)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Starting from <span class="doxyComputerOutput">Root</span> find a top-down traversal order of the dominator tree to visit all basic blocks containing the elements of <span class="doxyComputerOutput">Spills</span>.</p>


<p>Redundant spills will be found and put into <span class="doxyComputerOutput">SpillsToRm</span> at the same time. <span class="doxyComputerOutput">SpillBBToSpill</span> will be populated as part of the process and maps a basic block to the first store occurring in the basic block.</p>


<dl class="doxySectionUser">
<dt>Postcondition</dt>
<dd><p>SpillsToRm.union(Spills@post) == Spills@pre</p></dd>
</dl>


<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### isSpillCandBB() {#af0a515c8f5f551759ff3b06476ec7ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool HoistSpillHelper::isSpillCandBB (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; OrigLI, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> &amp; OrigVNI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> &amp; LiveReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check BB to see if it is a possible target BB to place a hoisted spill, i.e., there should be a living sibling of OrigReg at the insert point.</p>

<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### rmRedundantSpills() {#a0216a7efb7d1d151d9e7547af0875a5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HoistSpillHelper::rmRedundantSpills (<a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt; &amp; Spills, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; SpillsToRm, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a94b65b831ad8756f7d3a029a1e599f75">MachineDomTreeNode</a> *, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; SpillBBToSpill)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove redundant spills in the same BB.</p>


<p>Save those redundant spills in SpillsToRm, and save the spill to keep and its BB in SpillBBToSpill map.</p>


<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### runHoistSpills() {#ac5f7ed1a22c4d2a891cd66441f5ff73a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HoistSpillHelper::runHoistSpills (<a href="/web-llvm/docs/api/classes/llvm/liveinterval">LiveInterval</a> &amp; OrigLI, <a href="/web-llvm/docs/api/classes/llvm/vninfo">VNInfo</a> &amp; OrigVNI, <a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 16 &gt; &amp; Spills, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt; &amp; SpillsToRm, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> *, unsigned &gt; &amp; SpillsToIns)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to hoist spills according to BB hotness.</p>


<p>The spills to removed will be saved in <span class="doxyComputerOutput">SpillsToRm</span>. The spills to be inserted will be saved in <span class="doxyComputerOutput">SpillsToIns</span>.</p>


<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IPA {#ae89f60e383c1fc26b1afdde5ae09276d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InsertPointAnalysis anonymous{InlineSpiller.cpp}::HoistSpillHelper::IPA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### LIS {#a2ad508b3a4696f929c0ec9966819b756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveIntervals&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::LIS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### LSS {#a046b6338e408734a118f6d14322be766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveStacks&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::LSS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### MBFI {#ad944096f6192c11034423589e6369bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBlockFrequencyInfo&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::MBFI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### MDT {#aa26c89d59615075ff75e376a7f232761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### MergeableSpills {#af7002e5075b2f2e71774e15ae3ab5dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MergeableSpillsMap anonymous{InlineSpiller.cpp}::HoistSpillHelper::MergeableSpills</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### MF {#a7590148f139a9e6c54b135b38167206c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### MRI {#a96d04c556e575fd6f867c8e457f3cfac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### StackSlotToOrigLI {#a4d6eb463f146cba734fbb2136e747f45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;int, std::unique_ptr&lt;LiveInterval&gt; &gt; anonymous{InlineSpiller.cpp}::HoistSpillHelper::StackSlotToOrigLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### TII {#a950195c4956976283fa918b08f6e1d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### TRI {#a13b1eae2b83a10fd0667402188ad1b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### Virt2SiblingsMap {#a52ba090f7be4ecd8bd113a72cd3ff675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, SmallSetVector&lt;Register, 16&gt; &gt; anonymous{InlineSpiller.cpp}::HoistSpillHelper::Virt2SiblingsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is the map from original register to a set containing all its siblings.</p>


<p>To hoist a spill to another BB, we need to find out a live sibling there and use it as the source of the new spill.</p>


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

### VRM {#af36b0b08206669e87bb857841c008cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap&amp; anonymous{InlineSpiller.cpp}::HoistSpillHelper::VRM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/inlinespiller-cpp">InlineSpiller.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
