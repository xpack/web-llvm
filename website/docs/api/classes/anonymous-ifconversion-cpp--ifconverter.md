---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ifconversion-cpp-/ifconverter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IfConverter` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{IfConversion.cpp}::IfConverter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IfcvtKind { <a href="#af7b1770b2b12d8b2cf5a492532b86433">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaed2e7dcab6610335c9197555baaac11">IfConverter</a> (std::function&lt; bool(const MachineFunction &amp;)&gt; Ftor=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d02eb24e13645d5e8d4b5108a2b1933">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a9d02eb24e13645d5e8d4b5108a2b1933">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff4179252123a7710b2fa134be3f9d6">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#abff4179252123a7710b2fa134be3f9d6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55a60b717a250f6623209945ca4eef7e">getRequiredProperties</a> () const override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c502d25e0af1e16614f29d8b888918">reverseBranchCondition</a> (BBInfo &amp;BBI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverse the condition of the end of the block branch. <a href="#a50c502d25e0af1e16614f29d8b888918">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3669740c2af40861e4beb4b8a1cef006">ValidSimple</a> (BBInfo &amp;TrueBBI, unsigned &amp;Dups, BranchProbability Prediction) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the 'true' block (along with its predecessor) forms a valid simple shape for ifcvt. <a href="#a3669740c2af40861e4beb4b8a1cef006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeee23784568fa2afceb3f40191204d37">ValidTriangle</a> (BBInfo &amp;TrueBBI, BBInfo &amp;FalseBBI, bool FalseBranch, unsigned &amp;Dups, BranchProbability Prediction) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the 'true' and 'false' blocks (along with their common predecessor) forms a valid triangle shape for ifcvt. <a href="#aeee23784568fa2afceb3f40191204d37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a568ca69029c4c61724fcc77c327487c3">CountDuplicatedInstructions</a> (MachineBasicBlock::iterator &amp;TIB, MachineBasicBlock::iterator &amp;FIB, MachineBasicBlock::iterator &amp;TIE, MachineBasicBlock::iterator &amp;FIE, unsigned &amp;Dups1, unsigned &amp;Dups2, MachineBasicBlock &amp;TBB, MachineBasicBlock &amp;FBB, bool SkipUnconditionalBranches) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Count duplicated instructions and move the iterators to show where they are. <a href="#a568ca69029c4c61724fcc77c327487c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c6f1743a86e7ad2dc8a6095bd7c641d">ValidDiamond</a> (BBInfo &amp;TrueBBI, BBInfo &amp;FalseBBI, unsigned &amp;Dups1, unsigned &amp;Dups2, BBInfo &amp;TrueBBICalc, BBInfo &amp;FalseBBICalc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValidDiamond - Returns true if the 'true' and 'false' blocks (along with their common predecessor) forms a valid diamond shape for ifcvt. <a href="#a4c6f1743a86e7ad2dc8a6095bd7c641d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08944a00548637f5013b77ba588552b9">ValidForkedDiamond</a> (BBInfo &amp;TrueBBI, BBInfo &amp;FalseBBI, unsigned &amp;Dups1, unsigned &amp;Dups2, BBInfo &amp;TrueBBICalc, BBInfo &amp;FalseBBICalc) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ValidForkedDiamond - Returns true if the 'true' and 'false' blocks (along with their common predecessor) form a diamond if a common tail block is extracted. <a href="#a08944a00548637f5013b77ba588552b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f413257241ddad04e0996b240702201">AnalyzeBranches</a> (BBInfo &amp;BBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AnalyzeBranches - Look at the branches at the end of a block to determine if the block is predicable. <a href="#a2f413257241ddad04e0996b240702201">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc87e2d645f4fa128675bb068e883f8a">ScanInstructions</a> (BBInfo &amp;BBI, MachineBasicBlock::iterator &amp;Begin, MachineBasicBlock::iterator &amp;End, bool BranchUnpredicable=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ScanInstructions - Scan all the instructions in the block to determine if the block is predicable. <a href="#afc87e2d645f4fa128675bb068e883f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af21c1dbcb9b1324f7fc818ae76001134">RescanInstructions</a> (MachineBasicBlock::iterator &amp;TIB, MachineBasicBlock::iterator &amp;FIB, MachineBasicBlock::iterator &amp;TIE, MachineBasicBlock::iterator &amp;FIE, BBInfo &amp;TrueBBI, BBInfo &amp;FalseBBI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RescanInstructions - Run ScanInstructions on a pair of blocks. <a href="#af21c1dbcb9b1324f7fc818ae76001134">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95b32fd16fd12629e3b3099555f3509d">AnalyzeBlock</a> (MachineBasicBlock &amp;MBB, std::vector&lt; std::unique_ptr&lt; IfcvtToken &gt; &gt; &amp;Tokens)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze the structure of the sub-CFG starting from the specified block. <a href="#a95b32fd16fd12629e3b3099555f3509d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d6d2995789b622f48a477ef7b07b4ab">FeasibilityAnalysis</a> (BBInfo &amp;BBI, SmallVectorImpl&lt; MachineOperand &gt; &amp;Pred, bool isTriangle=false, bool RevBranch=false, bool hasCommonTail=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the block is a suitable candidate to be predicated by the specified predicate. <a href="#a5d6d2995789b622f48a477ef7b07b4ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a634cad5a6fc42a4b47ef8b5c17cb2db6">AnalyzeBlocks</a> (MachineFunction &amp;MF, std::vector&lt; std::unique_ptr&lt; IfcvtToken &gt; &gt; &amp;Tokens)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Analyze all blocks and find entries for all if-conversion candidates. <a href="#a634cad5a6fc42a4b47ef8b5c17cb2db6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4875f3cd33df0aeef9e7a5f7d94ef5">InvalidatePreds</a> (MachineBasicBlock &amp;MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invalidate predecessor BB info so it would be re-analyzed to determine if it can be if-converted. <a href="#aae4875f3cd33df0aeef9e7a5f7d94ef5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e034acbf8ebc1e32ef0dce0b74b47b8">IfConvertSimple</a> (BBInfo &amp;BBI, IfcvtKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If convert a simple (split, no rejoin) sub-CFG. <a href="#a7e034acbf8ebc1e32ef0dce0b74b47b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e4039399afcc1930b7d9ea1db1823b">IfConvertTriangle</a> (BBInfo &amp;BBI, IfcvtKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If convert a triangle sub-CFG. <a href="#a25e4039399afcc1930b7d9ea1db1823b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afec662f80c0ed6e21dab78eff047af85">IfConvertDiamondCommon</a> (BBInfo &amp;BBI, BBInfo &amp;TrueBBI, BBInfo &amp;FalseBBI, unsigned NumDups1, unsigned NumDups2, bool TClobbersPred, bool FClobbersPred, bool RemoveBranch, bool MergeAddEdges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common code shared between diamond conversions. <a href="#afec662f80c0ed6e21dab78eff047af85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f45ac15bf43495c5e95f54329c89f82">IfConvertDiamond</a> (BBInfo &amp;BBI, IfcvtKind Kind, unsigned NumDups1, unsigned NumDups2, bool TClobbers, bool FClobbers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If convert a diamond sub-CFG. <a href="#a5f45ac15bf43495c5e95f54329c89f82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a912eb918c070beafd9c6577fb7f80fd0">IfConvertForkedDiamond</a> (BBInfo &amp;BBI, IfcvtKind Kind, unsigned NumDups1, unsigned NumDups2, bool TClobbers, bool FClobbers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If convert an almost-diamond sub-CFG where the true and false blocks share a common tail. <a href="#a912eb918c070beafd9c6577fb7f80fd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf3ae4b99e536e04c378d2fab1f521b1">PredicateBlock</a> (BBInfo &amp;BBI, MachineBasicBlock::iterator E, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, SmallSet&lt; MCPhysReg, 4 &gt; *LaterRedefs=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> instructions from the start of the block to the specified end with the specified condition. <a href="#abf3ae4b99e536e04c378d2fab1f521b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0835c81d90fb6dd6e2fef9ee50a862d5">CopyAndPredicateBlock</a> (BBInfo &amp;ToBBI, BBInfo &amp;FromBBI, SmallVectorImpl&lt; MachineOperand &gt; &amp;Cond, bool IgnoreBr=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy and predicate instructions from source BB to the destination block. <a href="#a0835c81d90fb6dd6e2fef9ee50a862d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b84a44c12b1b02cc543dd541563618">MergeBlocks</a> (BBInfo &amp;ToBBI, BBInfo &amp;FromBBI, bool AddEdges=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move all instructions from FromBB to the end of ToBB. <a href="#a45b84a44c12b1b02cc543dd541563618">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2669542e2031873cefd0213694ade1e">MeetIfcvtSizeLimit</a> (MachineBasicBlock &amp;BB, unsigned Cycle, unsigned Extra, BranchProbability Prediction) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37a3d8b0401ea6155d4d53f83c0e8ce1">MeetIfcvtSizeLimit</a> (BBInfo &amp;TBBInfo, BBInfo &amp;FBBInfo, MachineBasicBlock &amp;CommBB, unsigned Dups, BranchProbability Prediction, bool Forked) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a840748be67b94d2be79adf2134aabdf5">blockAlwaysFallThrough</a> (BBInfo &amp;BBI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Block ends without a terminator. <a href="#a840748be67b94d2be79adf2134aabdf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; BBInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086d5cb5f3815379a55d67b64a978042">BBAnalysis</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Results of if-conversion feasibility analysis indexed by basic block number. <a href="#a086d5cb5f3815379a55d67b64a978042">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetschedmodel">TargetSchedModel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a7719dee50b3a2487077401d657e19f">SchedModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase">TargetLoweringBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14927048d36cfad317b3d68410a8831a">TLI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e07eb8df3e392777f6e020f71278925">TII</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b6b268e0dae861e5f55f66722e620c2">TRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebranchprobabilityinfo">MachineBranchProbabilityInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbd1b5521c5a6b159e1fd698c1d17387">MBPI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee4d848c4069ad9477d10fb7d0ee2540">MRI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/livephysregs">LivePhysRegs</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac98c01c76f3361a9800279590d94a257">Redefs</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcffa509e7bf71edd1d1cb216c00b556">PreRegAlloc</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5116693ee584b23cba55e80ea39fb0ed">MadeChange</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a360fcf564e43e2ea31fd1f508f95d9e1">FnNum</a> = -1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511b272047a9ef60f54ea720ddaa39d0">PredicateFtor</a></td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f82ba7920d194ca6b32cf24f6b377b9">IfcvtTokenCmp</a> (const std::unique_ptr&lt; IfcvtToken &gt; &amp;C1, const std::unique_ptr&lt; IfcvtToken &gt; &amp;C2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to sort if-conversion candidates. <a href="#a0f82ba7920d194ca6b32cf24f6b377b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a9f6cbb388a4af27b26c5a70bc2d815">ID</a> = 0</td>
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


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### IfcvtKind {#af7b1770b2b12d8b2cf5a492532b86433}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{IfConversion.cpp}::IfConverter::IfcvtKind </td>
</tr>
</table>
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
<td class="doxyEnumItemName">ICNotClassfied<a id="af7b1770b2b12d8b2cf5a492532b86433a5d3cd4fe771661cd8e5e63386545a4e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICSimpleFalse<a id="af7b1770b2b12d8b2cf5a492532b86433af132178c3569997eb7aeb157cf57a868"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICSimple<a id="af7b1770b2b12d8b2cf5a492532b86433a0c349c5ed7a8a237b4162b250ff5ec03"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICTriangleFRev<a id="af7b1770b2b12d8b2cf5a492532b86433a2d7a903b2aa1630111256dc861672bee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICTriangleRev<a id="af7b1770b2b12d8b2cf5a492532b86433abe9d49bedd51d4afd6aea330f7b8a22a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICTriangleFalse<a id="af7b1770b2b12d8b2cf5a492532b86433a0bcdd976aa1a8b72a3e1ed124cc9197a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICTriangle<a id="af7b1770b2b12d8b2cf5a492532b86433a89189f43fd0609530bf14bb5ac0c3612"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICDiamond<a id="af7b1770b2b12d8b2cf5a492532b86433abe68fe37e891ce6b3d942586a9ca1d93"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ICForkedDiamond<a id="af7b1770b2b12d8b2cf5a492532b86433aecdbaa7cf3266587241f175f257ca27c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IfConverter() {#aaed2e7dcab6610335c9197555baaac11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{IfConversion.cpp}::IfConverter::IfConverter (std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;)&gt; Ftor=nullptr)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a9a9f6cbb388a4af27b26c5a70bc2d815">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a26c4d47f02e65dcf05f2018373f310d3">llvm::initializeIfConverterPass</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1a6497e44e3650cd3d15d98f43e0eeb2">llvm::createIfConverter</a> and <a href="#abff4179252123a7710b2fa134be3f9d6">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a9d02eb24e13645d5e8d4b5108a2b1933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{IfConversion.cpp}::IfConverter::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a>.</p>

</div>
</div>

### getRequiredProperties() {#a55a60b717a250f6623209945ca4eef7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties anonymous{IfConversion.cpp}::IfConverter::getRequiredProperties ()</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### runOnMachineFunction() {#abff4179252123a7710b2fa134be3f9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a6e86f1dee13649140a9334c757b8b373">DisableDiamond</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a723b29a127263c51663f349b85bc0da6">DisableForkedDiamond</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#ab14b054bbb8599dacdc643a2d7e556f3">DisableSimple</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a9d0b4268eb0c62033decd26292677c07">DisableSimpleF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a009eab3f82842e62bf6819ae1d60dd1e">DisableTriangle</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a507f5f1d529762c0a978080e47db2d70">DisableTriangleF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a6f92bdc1b983f059609796a2005d3148">DisableTriangleR</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a3aa22d521bd6a7e6b9f35545dc7b0f1e">llvm::MachineBasicBlock::getNumber</a>, <a href="#aaed2e7dcab6610335c9197555baaac11">IfConverter</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a497181b343d72f8762168b0a92bc848c">IfCvtBranchFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#af8679d73ae132532b9ab2f4dea9a6d83">IfCvtFnStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a2d235e22369822c5d1de2913416a2aae">IfCvtFnStop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp/#a604fe46f65f52b5dcad2b755aa3a5da8">IfCvtLimit</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/branchfolder/#aa0d50fee4d0d41ccf591e29de109786f">llvm::BranchFolder::OptimizeFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af7881286e3ea4d7f1c4a63c87c132dac">llvm::printMBBReference</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa323e6c0586d706279d7e764fc18d1ba">llvm::recomputeLivenessFlags</a>, <a href="#abff4179252123a7710b2fa134be3f9d6">runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a>.</p>


<p>Referenced by <a href="#abff4179252123a7710b2fa134be3f9d6">runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AnalyzeBlock() {#a95b32fd16fd12629e3b3099555f3509d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::AnalyzeBlock (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, std::vector&lt; std::unique_ptr&lt; IfcvtToken &gt; &gt; &amp; Tokens)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze the structure of the sub-CFG starting from the specified block.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> its successors and whether it looks like an if-conversion candidate.</p>


<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### AnalyzeBlocks() {#a634cad5a6fc42a4b47ef8b5c17cb2db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::AnalyzeBlocks (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, std::vector&lt; std::unique_ptr&lt; IfcvtToken &gt; &gt; &amp; Tokens)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Analyze all blocks and find entries for all if-conversion candidates.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### AnalyzeBranches() {#a2f413257241ddad04e0996b240702201}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::AnalyzeBranches (BBInfo &amp; BBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AnalyzeBranches - Look at the branches at the end of a block to determine if the block is predicable.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### blockAlwaysFallThrough() {#a840748be67b94d2be79adf2134aabdf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{IfConversion.cpp}::IfConverter::blockAlwaysFallThrough (BBInfo &amp; BBI)</td>
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

<p>Returns true if Block ends without a terminator.</p>

<p>Definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### CopyAndPredicateBlock() {#a0835c81d90fb6dd6e2fef9ee50a862d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::CopyAndPredicateBlock (BBInfo &amp; ToBBI, BBInfo &amp; FromBBI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, bool IgnoreBr=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy and predicate instructions from source BB to the destination block.</p>


<p>Skip end of block branches if IgnoreBr is true.</p>


<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### CountDuplicatedInstructions() {#a568ca69029c4c61724fcc77c327487c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::CountDuplicatedInstructions (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; TIB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; FIB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; TIE, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; FIE, unsigned &amp; Dups1, unsigned &amp; Dups2, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; TBB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; FBB, bool SkipUnconditionalBranches)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Count duplicated instructions and move the iterators to show where they are.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TIB</td>
<td class="doxyParamItemDescription"><p>True Iterator Begin</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FIB</td>
<td class="doxyParamItemDescription"><p>False Iterator Begin These two iterators initially point to the first instruction of the two blocks, and finally point to the first non-shared instruction.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TIE</td>
<td class="doxyParamItemDescription"><p>True Iterator End</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FIE</td>
<td class="doxyParamItemDescription"><p>False Iterator End These two iterators initially point to End() for the two <a href="/web-llvm/docs/api/files/lib/lib/codegen/basicblocksections-cpp/#a6b480a971048f2d9cc342c18046d7774">blocks()</a> and finally point to the first shared instruction in the tail. Upon return [TIB, TIE), and [FIB, FIE) mark the un-duplicated portions of two blocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dups1</td>
<td class="doxyParamItemDescription"><p>count of duplicated instructions at the beginning of the 2 blocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Dups2</td>
<td class="doxyParamItemDescription"><p>count of duplicated instructions at the end of the 2 blocks.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SkipUnconditionalBranches</td>
<td class="doxyParamItemDescription"><p>if true, Don't make sure that unconditional branches at the end of the blocks are the same. True is passed when the blocks are analyzable to allow for fallthrough to be handled.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>false if the shared portion prevents if conversion.</p></dd>
</dl>


<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### FeasibilityAnalysis() {#a5d6d2995789b622f48a477ef7b07b4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::FeasibilityAnalysis (BBInfo &amp; BBI, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Pred, bool isTriangle=false, bool RevBranch=false, bool hasCommonTail=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the block is a suitable candidate to be predicated by the specified predicate.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">BBI</td>
<td class="doxyParamItemDescription"><p>BBInfo for the block to check</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Pred</td>
<td class="doxyParamItemDescription"><p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> array for the branch that leads to BBI</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isTriangle</td>
<td class="doxyParamItemDescription"><p>true if the Analysis is for a triangle</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">RevBranch</td>
<td class="doxyParamItemDescription"><p>true if <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa67f115c1fddc4ce1aeb1c754001585bc">Reverse(Pred)</a> leads to BBI (e.g. BBI is the false case</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">hasCommonTail</td>
<td class="doxyParamItemDescription"><p>true if BBI shares a tail with a sibling block that contains any instruction that would make the block unpredicable.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### IfConvertDiamond() {#a5f45ac15bf43495c5e95f54329c89f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::IfConvertDiamond (BBInfo &amp; BBI, IfcvtKind Kind, unsigned NumDups1, unsigned NumDups2, bool TClobbers, bool FClobbers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If convert a diamond sub-CFG.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### IfConvertDiamondCommon() {#afec662f80c0ed6e21dab78eff047af85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::IfConvertDiamondCommon (BBInfo &amp; BBI, BBInfo &amp; TrueBBI, BBInfo &amp; FalseBBI, unsigned NumDups1, unsigned NumDups2, bool TClobbersPred, bool FClobbersPred, bool RemoveBranch, bool MergeAddEdges)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common code shared between diamond conversions.</p>


<p><span class="doxyComputerOutput">BBI</span>, <span class="doxyComputerOutput">TrueBBI</span>, and <span class="doxyComputerOutput">FalseBBI</span> form the diamond shape. <span class="doxyComputerOutput">NumDups1</span> - number of shared instructions at the beginning of <span class="doxyComputerOutput">TrueBBI</span> and FalseBBI <span class="doxyComputerOutput">NumDups2</span> - number of shared instructions at the end of <span class="doxyComputerOutput">TrueBBI</span> and <span class="doxyComputerOutput">FalseBBI</span> <span class="doxyComputerOutput">RemoveBranch</span> - Remove the common branch of the two blocks before predicating. Only false for unanalyzable fallthrough cases. The caller will replace the branch if necessary. <span class="doxyComputerOutput">MergeAddEdges</span> - Add successor edges when merging blocks. Only false for unanalyzable fallthrough</p>


<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### IfConvertForkedDiamond() {#a912eb918c070beafd9c6577fb7f80fd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::IfConvertForkedDiamond (BBInfo &amp; BBI, IfcvtKind Kind, unsigned NumDups1, unsigned NumDups2, bool TClobbers, bool FClobbers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If convert an almost-diamond sub-CFG where the true and false blocks share a common tail.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### IfConvertSimple() {#a7e034acbf8ebc1e32ef0dce0b74b47b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::IfConvertSimple (BBInfo &amp; BBI, IfcvtKind Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If convert a simple (split, no rejoin) sub-CFG.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### IfConvertTriangle() {#a25e4039399afcc1930b7d9ea1db1823b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::IfConvertTriangle (BBInfo &amp; BBI, IfcvtKind Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If convert a triangle sub-CFG.</p>

<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### InvalidatePreds() {#aae4875f3cd33df0aeef9e7a5f7d94ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::InvalidatePreds (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Invalidate predecessor BB info so it would be re-analyzed to determine if it can be if-converted.</p>


<p>If predecessor is already enqueued, dequeue it!</p>


<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### MeetIfcvtSizeLimit() {#ac2669542e2031873cefd0213694ade1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{IfConversion.cpp}::IfConverter::MeetIfcvtSizeLimit (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; BB, unsigned Cycle, unsigned Extra, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prediction)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### MeetIfcvtSizeLimit() {#a37a3d8b0401ea6155d4d53f83c0e8ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{IfConversion.cpp}::IfConverter::MeetIfcvtSizeLimit (BBInfo &amp; TBBInfo, BBInfo &amp; FBBInfo, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; CommBB, unsigned Dups, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prediction, bool Forked)</td>
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



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### MergeBlocks() {#a45b84a44c12b1b02cc543dd541563618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::MergeBlocks (BBInfo &amp; ToBBI, BBInfo &amp; FromBBI, bool AddEdges=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move all instructions from FromBB to the end of ToBB.</p>


<p>This will leave FromBB as an empty block, so remove all of its successor edges and move it to the end of the function. If AddEdges is true, i.e., when FromBBI's branch is being moved, add those successor edges to ToBBI and remove the old edge from ToBBI to FromBBI.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### PredicateBlock() {#abf3ae4b99e536e04c378d2fab1f521b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::PredicateBlock (BBInfo &amp; BBI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> E, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt; &amp; Cond, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a>, 4 &gt; * LaterRedefs=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/predicate">Predicate</a> instructions from the start of the block to the specified end with the specified condition.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### RescanInstructions() {#af21c1dbcb9b1324f7fc818ae76001134}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::RescanInstructions (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; TIB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; FIB, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; TIE, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; FIE, BBInfo &amp; TrueBBI, BBInfo &amp; FalseBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RescanInstructions - Run ScanInstructions on a pair of blocks.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">TIB</td>
<td class="doxyParamItemDescription"><p>- True Iterator Begin, points to first non-shared instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FIB</td>
<td class="doxyParamItemDescription"><p>- False Iterator Begin, points to first non-shared instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TIE</td>
<td class="doxyParamItemDescription"><p>- True Iterator End, points past last non-shared instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FIE</td>
<td class="doxyParamItemDescription"><p>- False Iterator End, points past last non-shared instruction</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">TrueBBI</td>
<td class="doxyParamItemDescription"><p>- BBInfo to update for the true block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FalseBBI</td>
<td class="doxyParamItemDescription"><p>- BBInfo to update for the false block.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>- false if either block cannot be predicated or if both blocks end with a predicate-clobbering instruction.</p></dd>
</dl>


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### reverseBranchCondition() {#a50c502d25e0af1e16614f29d8b888918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::reverseBranchCondition (BBInfo &amp; BBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reverse the condition of the end of the block branch.</p>


<p>Swap block's 'true' and 'false' successors.</p>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### ScanInstructions() {#afc87e2d645f4fa128675bb068e883f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IfConverter::ScanInstructions (BBInfo &amp; BBI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; Begin, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; End, bool BranchUnpredicable=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ScanInstructions - Scan all the instructions in the block to determine if the block is predicable.</p>


<p>In most cases, that means all the instructions in the block are isPredicable(). Also checks if the block contains any instruction which can clobber a predicate (e.g. condition code register). If so, the block is not predicable unless it's the last instruction.</p>


<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### ValidDiamond() {#a4c6f1743a86e7ad2dc8a6095bd7c641d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::ValidDiamond (BBInfo &amp; TrueBBI, BBInfo &amp; FalseBBI, unsigned &amp; Dups1, unsigned &amp; Dups2, BBInfo &amp; TrueBBICalc, BBInfo &amp; FalseBBICalc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ValidDiamond - Returns true if the 'true' and 'false' blocks (along with their common predecessor) forms a valid diamond shape for ifcvt.</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### ValidForkedDiamond() {#a08944a00548637f5013b77ba588552b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::ValidForkedDiamond (BBInfo &amp; TrueBBI, BBInfo &amp; FalseBBI, unsigned &amp; Dups1, unsigned &amp; Dups2, BBInfo &amp; TrueBBICalc, BBInfo &amp; FalseBBICalc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ValidForkedDiamond - Returns true if the 'true' and 'false' blocks (along with their common predecessor) form a diamond if a common tail block is extracted.</p>


<p>While not strictly a diamond, this pattern would form a diamond if tail-merging had merged the shared tails. EBB _/ _ | | TBB FBB / \ / \ FalseBB TrueBB FalseBB Currently only handles analyzable branches. Specifically excludes actual diamonds to avoid overlap.</p>


<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### ValidSimple() {#a3669740c2af40861e4beb4b8a1cef006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::ValidSimple (BBInfo &amp; TrueBBI, unsigned &amp; Dups, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prediction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the 'true' block (along with its predecessor) forms a valid simple shape for ifcvt.</p>


<p>It also returns the number of instructions that the ifcvt would need to duplicate if performed in Dups.</p>


<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### ValidTriangle() {#aeee23784568fa2afceb3f40191204d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IfConverter::ValidTriangle (BBInfo &amp; TrueBBI, BBInfo &amp; FalseBBI, bool FalseBranch, unsigned &amp; Dups, <a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prediction)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the 'true' and 'false' blocks (along with their common predecessor) forms a valid triangle shape for ifcvt.</p>


<p>If 'FalseBranch' is true, it checks if 'true' block's false branch branches to the 'false' block rather than the other way around. It also returns the number of instructions that the ifcvt would need to duplicate if performed in 'Dups'.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BBAnalysis {#a086d5cb5f3815379a55d67b64a978042}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BBInfo&gt; anonymous{IfConversion.cpp}::IfConverter::BBAnalysis</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Results of if-conversion feasibility analysis indexed by basic block number.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### FnNum {#a360fcf564e43e2ea31fd1f508f95d9e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{IfConversion.cpp}::IfConverter::FnNum = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### MadeChange {#a5116693ee584b23cba55e80ea39fb0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{IfConversion.cpp}::IfConverter::MadeChange = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### MBPI {#acbd1b5521c5a6b159e1fd698c1d17387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MachineBranchProbabilityInfo* anonymous{IfConversion.cpp}::IfConverter::MBPI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### MRI {#aee4d848c4069ad9477d10fb7d0ee2540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{IfConversion.cpp}::IfConverter::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### PredicateFtor {#a511b272047a9ef60f54ea720ddaa39d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;bool(const MachineFunction &amp;)&gt; anonymous{IfConversion.cpp}::IfConverter::PredicateFtor</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### PreRegAlloc {#adcffa509e7bf71edd1d1cb216c00b556}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{IfConversion.cpp}::IfConverter::PreRegAlloc = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### Redefs {#ac98c01c76f3361a9800279590d94a257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LivePhysRegs anonymous{IfConversion.cpp}::IfConverter::Redefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### SchedModel {#a4a7719dee50b3a2487077401d657e19f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetSchedModel anonymous{IfConversion.cpp}::IfConverter::SchedModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### TII {#a1e07eb8df3e392777f6e020f71278925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{IfConversion.cpp}::IfConverter::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### TLI {#a14927048d36cfad317b3d68410a8831a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLoweringBase* anonymous{IfConversion.cpp}::IfConverter::TLI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

### TRI {#a4b6b268e0dae861e5f55f66722e620c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* anonymous{IfConversion.cpp}::IfConverter::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### IfcvtTokenCmp() {#a0f82ba7920d194ca6b32cf24f6b377b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{IfConversion.cpp}::IfConverter::IfcvtTokenCmp (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::unique_ptr&lt; IfcvtToken &gt; &amp; C1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::unique_ptr&lt; IfcvtToken &gt; &amp; C2)</td>
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

<p>Used to sort if-conversion candidates.</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a9a9f6cbb388a4af27b26c5a70bc2d815}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char IfConverter::ID = 0</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a>.</p>


<p>Referenced by <a href="#aaed2e7dcab6610335c9197555baaac11">IfConverter</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/ifconversion-cpp">IfConversion.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
