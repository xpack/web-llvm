---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/transfertracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TransferTracker` Class

<p>Tracker for converting machine value locations and variable values into variable locations (the output of <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a>), recorded as DBG_VALUEs specifying block live-in locations and transfers within blocks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class TransferTracker { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa24ee75e581d521a08c6731becbc964">ValueLocPair</a> = std::pair&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a>, <a href="/web-llvm/docs/api/classes/transfertracker/locationandquality">LocationAndQuality</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">LocationQuality : unsigned char { <a href="#aa5d994f6e3b0b93e697c85ca2002834d">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a> (const TargetInstrInfo *TII, MLocTracker *MTracker, MachineFunction &amp;MF, const DebugVariableMap &amp;DVMap, const TargetRegisterInfo &amp;TRI, const BitVector &amp;CalleeSavedRegs, const TargetPassConfig &amp;TPC)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac546420f6cd906a9b17e41c43e720e98">isCalleeSaved</a> (LocIdx L) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#aa5d994f6e3b0b93e697c85ca2002834d">LocationQuality</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79fb4ee603e9a1f3010aba7fb3da0f82">getLocQualityIfBetter</a> (LocIdx L, LocationQuality Min) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a> (MachineBasicBlock &amp;MBB, DbgOpIDMap &amp;DbgOpStore, const SmallVectorImpl&lt; ValueLocPair &gt; &amp;ValueToLoc, DebugVariableID VarID, DbgValue Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For a variable <span class="doxyComputerOutput">Var</span> with the live-in value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>, attempts to resolve the <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> to a concrete DBG_VALUE, emitting that value and loading the tracking information to track Var throughout the block. <a href="#af64654b3c46ec3154963aed1dbb016d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a> (MachineBasicBlock &amp;MBB, ValueTable &amp;MLocs, DbgOpIDMap &amp;DbgOpStore, const SmallVectorImpl&lt; std::pair&lt; DebugVariableID, DbgValue &gt; &gt; &amp;VLocs, unsigned NumLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load object with live-in variable values. <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46747b1281d39a5af4e522209198e3f2">addUseBeforeDef</a> (DebugVariableID VarID, const DbgValueProperties &amp;Properties, const SmallVectorImpl&lt; DbgOp &gt; &amp;DbgOps, unsigned Inst)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> that <span class="doxyComputerOutput">Var</span> has value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>, a value that becomes available later in the function. <a href="#a46747b1281d39a5af4e522209198e3f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a> (unsigned Inst, MachineBasicBlock::iterator pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>After the instruction at index <span class="doxyComputerOutput">Inst</span> and position <span class="doxyComputerOutput">pos</span> has been processed, check whether it defines a variable value in a use-before-def. <a href="#aa1129d2080e1308fd9bd27d20374ace5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf872fb0e884bca493cc867aac36ed79">flushDbgValues</a> (MachineBasicBlock::iterator Pos, MachineBasicBlock *MBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to move created DBG_VALUEs into Transfers collection. <a href="#acf872fb0e884bca493cc867aac36ed79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930c119c5ebcb496e7665a4521f42b94">isEntryValueVariable</a> (const DebugVariable &amp;Var, const DIExpression *Expr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76cea3708e144106a37446994e2482c">isEntryValueValue</a> (const ValueIDNum &amp;Val) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a> (DebugVariableID VarID, const DbgValueProperties &amp;Prop, const ValueIDNum &amp;Num)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Change a variable value after encountering a DBG_VALUE inside a block. <a href="#ac1753e9184a776f25f017ac1022f2a13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3b3d27cd53936e3c52e01a34817d6be">redefVar</a> (const MachineInstr &amp;MI, const DbgValueProperties &amp;Properties, SmallVectorImpl&lt; ResolvedDbgOp &gt; &amp;NewLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle a change in variable location within a block. <a href="#af3b3d27cd53936e3c52e01a34817d6be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ed6c9ebb7ede8539a8fe20bfeb36c2">clobberMloc</a> (LocIdx MLoc, MachineBasicBlock::iterator Pos, bool MakeUndef=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Account for a location <span class="doxyComputerOutput">mloc</span> being clobbered. <a href="#ac9ed6c9ebb7ede8539a8fe20bfeb36c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a> (LocIdx MLoc, ValueIDNum OldValue, MachineBasicBlock::iterator Pos, bool MakeUndef=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Overload that takes an explicit value <span class="doxyComputerOutput">OldValue</span> for when the value in <span class="doxyComputerOutput">MLoc</span> has changed and the <a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a>'s locations have not been updated yet. <a href="#aee68454c02cb09e9dc1213c607ee78b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a> (LocIdx Src, LocIdx Dst, MachineBasicBlock::iterator Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/transfertracker/transfer">Transfer</a> variables based on <span class="doxyComputerOutput">Src</span> to be based on <span class="doxyComputerOutput">Dst</span>. <a href="#a787205c8858064b56bad25b823faf3d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab17b4ddf05538aab17dbb53a0f5f4329">emitMOLoc</a> (const MachineOperand &amp;MO, const DebugVariable &amp;Var, const DbgValueProperties &amp;Properties)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1cef6664a3e135245b35927b6db11e5">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31452b4b5d9984ee5ed52db4b1a52d5e">TLI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This machine location tracker is assumed to always contain the up-to-date value mapping for all machine locations. <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79f160cf45e05ebc07c2751e0bd4d944">MF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/debugvariablemap">DebugVariableMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1088d1f2ac99145846bedd829c2a05e">ShouldEmitDebugEntryValues</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/transfertracker/transfer">Transfer</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af06b11c084b9a4ff7e063e146d4131d3">Transfers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collection of transfers (DBG_VALUEs) to be inserted. <a href="#af06b11c084b9a4ff7e063e146d4131d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a>, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a498b0782412a1488e7cb5c22a635188d">VarLocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Local cache of what-value-is-in-what-LocIdx. <a href="#a498b0782412a1488e7cb5c22a635188d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset">SmallSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from LocIdxes to which DebugVariables are based that location. <a href="#aacea713c5575395a3ce28a43c31f1df6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, <a href="/web-llvm/docs/api/structs/transfertracker/resolveddbgvalue">ResolvedDbgValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a495620f7b1dd27811000f102d1d40">ActiveVLocs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> to it's current location and qualifying meta information. <a href="#ae0a495620f7b1dd27811000f102d1d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * &gt;, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ee7f28da62a849df2fdb7a96be072d1">PendingDbgValues</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Temporary cache of DBG_VALUEs to be entered into the Transfers collection. <a href="#a7ee7f28da62a849df2fdb7a96be072d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/transfertracker/usebeforedef">UseBeforeDef</a>, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae485598414179a9523e127ad2df4756c">UseBeforeDefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from instruction index (within the block) to the set of UseBeforeDefs that become defined at that instruction. <a href="#ae485598414179a9523e127ad2df4756c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a162a58b620ec34701775d8d3e953fb20">UseBeforeDefVariables</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The set of variables that are in UseBeforeDefs and can become a location once the relevant value is defined. <a href="#a162a58b620ec34701775d8d3e953fb20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf13e97a9a5cff9aa06c88d1ac5172fb">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b1735405477716ee8dd95236d3257bf">CalleeSavedRegs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affb90f774e59ab28e9d3a9d72ac8f8d0">ValueToLocSort</a> (const ValueLocPair &amp;A, const ValueLocPair &amp;B)</td>
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

<p>Tracker for converting machine value locations and variable values into variable locations (the output of <a href="/web-llvm/docs/api/namespaces/livedebugvalues">LiveDebugValues</a>), recorded as DBG_VALUEs specifying block live-in locations and transfers within blocks.</p>


<p>Operating on a per-block basis, this class takes a (pre-loaded) <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> and must be initialized with the set of variable values that are live-in to the block. The caller then repeatedly calls process(). <a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a> picks out variable locations for the live-in variable values (if there <em>is</em> a location) and creates the corresponding DBG_VALUEs. Then, as the block is stepped through, transfers of values between machine locations are identified and if profitable, a DBG_VALUE created.</p>


<p>This is where debug use-before-defs would be resolved: a variable with an unavailable value could materialize in the middle of a block, when the value becomes available. Or, we could detect clobbers and re-specify the variable in a backup location. (XXX these are unimplemented).</p>


<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ValueLocPair {#afa24ee75e581d521a08c6731becbc964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using TransferTracker::ValueLocPair =  std::pair&lt;ValueIDNum, LocationAndQuality&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### LocationQuality {#aa5d994f6e3b0b93e697c85ca2002834d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class TransferTracker::LocationQuality : unsigned char</td>
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
<td class="doxyEnumItemName">Illegal<a id="aa5d994f6e3b0b93e697c85ca2002834da71f91e12ab77fda34a39063650e3b2e7"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="aa5d994f6e3b0b93e697c85ca2002834da0ba7583639a274c434bbe6ef797115a4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CalleeSavedRegister<a id="aa5d994f6e3b0b93e697c85ca2002834da356463ee55aa35f2112197b17e3e18f4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SpillSlot<a id="aa5d994f6e3b0b93e697c85ca2002834da927573a0209c7f5f0e934ebb6c90d3bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Best<a id="aa5d994f6e3b0b93e697c85ca2002834da68ef004de6166492c1d668eb8efe09bd"></a></td>
<td class="doxyEnumItemDescription"> (= SpillSlot)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TransferTracker() {#ab62a3902e9944a4a6da8a82cc72ea1c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TransferTracker::TransferTracker (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> * TII, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> * MTracker, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/debugvariablemap">DebugVariableMap</a> &amp; DVMap, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/bitvector">BitVector</a> &amp; CalleeSavedRegs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig">TargetPassConfig</a> &amp; TPC)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a1b1735405477716ee8dd95236d3257bf">CalleeSavedRegs</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="/web-llvm/docs/api/classes/llvm/targetpassconfig/#aca23623f476d3929484bdad4a5ce54d8">llvm::TargetPassConfig::getTM</a>, <a href="#a79f160cf45e05ebc07c2751e0bd4d944">MF</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#af1088d1f2ac99145846bedd829c2a05e">ShouldEmitDebugEntryValues</a>, <a href="#aa1cef6664a3e135245b35927b6db11e5">TII</a>, <a href="#a31452b4b5d9984ee5ed52db4b1a52d5e">TLI</a> and <a href="#abf13e97a9a5cff9aa06c88d1ac5172fb">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addUseBeforeDef() {#a46747b1281d39a5af4e522209198e3f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::addUseBeforeDef (<a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a> VarID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Properties, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a> &gt; &amp; DbgOps, unsigned Inst)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> that <span class="doxyComputerOutput">Var</span> has value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>, a value that becomes available later in the function.</p>

<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#ae485598414179a9523e127ad2df4756c">UseBeforeDefs</a> and <a href="#a162a58b620ec34701775d8d3e953fb20">UseBeforeDefVariables</a>.</p>


<p>Referenced by <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>.</p>

</div>
</div>

### checkInstForNewValues() {#aa1129d2080e1308fd9bd27d20374ace5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::checkInstForNewValues (unsigned Inst, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> pos)</td>
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

<p>After the instruction at index <span class="doxyComputerOutput">Inst</span> and position <span class="doxyComputerOutput">pos</span> has been processed, check whether it defines a variable value in a use-before-def.</p>


<p>If so, and the variable value hasn't changed since the start of the block, create a DBG_VALUE.</p>


<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a65520b9c67759099e313d0f4e7b5ff9e">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a0c047f127ed4380a6f383d70bec4eb94">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::find</a>, <a href="#acf872fb0e884bca493cc867aac36ed79">flushDbgValues</a>, <a href="#a79fb4ee603e9a1f3010aba7fb3da0f82">getLocQualityIfBetter</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#adb33f3ede2f5bfc9b3ee658aaf648492">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a40076b99dca773c0cc6c994d8445c00a">LiveDebugValues::LocIdx::isIllegal</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#a7ee7f28da62a849df2fdb7a96be072d1">PendingDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="#ae485598414179a9523e127ad2df4756c">UseBeforeDefs</a>, <a href="#a162a58b620ec34701775d8d3e953fb20">UseBeforeDefVariables</a> and <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a31d8fb0bf10235e84aae984909edee75">LiveDebugValues::ValueIDNum::Value</a>.</p>

</div>
</div>

### clobberMloc() {#ac9ed6c9ebb7ede8539a8fe20bfeb36c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::clobberMloc (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> MLoc, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Pos, bool MakeUndef=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Account for a location <span class="doxyComputerOutput">mloc</span> being clobbered.</p>


<p>Examine the variable locations that will be terminated: and try to recover them by using another location. Optionally, given <span class="doxyComputerOutput">MakeUndef</span>, emit a DBG_VALUE to explicitly terminate a location if it can't be recovered.</p>


<p>Definition at line 801 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a76c83b1cb30fe85e09f35ad1103fe75b">LiveDebugValues::LocIdx::asU64</a>, <a href="#ac9ed6c9ebb7ede8539a8fe20bfeb36c2">clobberMloc</a> and <a href="#a498b0782412a1488e7cb5c22a635188d">VarLocs</a>.</p>


<p>Referenced by <a href="#ac9ed6c9ebb7ede8539a8fe20bfeb36c2">clobberMloc</a>.</p>

</div>
</div>

### clobberMloc() {#aee68454c02cb09e9dc1213c607ee78b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::clobberMloc (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> MLoc, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> OldValue, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Pos, bool MakeUndef=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Overload that takes an explicit value <span class="doxyComputerOutput">OldValue</span> for when the value in <span class="doxyComputerOutput">MLoc</span> has changed and the <a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a>'s locations have not been updated yet.</p>

<p>Definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a>, <a href="#ae0a495620f7b1dd27811000f102d1d40">ActiveVLocs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a76c83b1cb30fe85e09f35ad1103fe75b">LiveDebugValues::LocIdx::asU64</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a98d44bec6b754ac8786ab97f219f06f1">LiveDebugValues::ValueIDNum::EmptyValue</a>, <a href="#acf872fb0e884bca493cc867aac36ed79">flushDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a8567f7c20eae6b2f5beabaa440df1097">LiveDebugValues::LocIdx::MakeIllegalLoc</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#a7ee7f28da62a849df2fdb7a96be072d1">PendingDbgValues</a>, <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1c97b8c8035fa91c5275ffb54d41634">llvm::replace_copy</a> and <a href="#a498b0782412a1488e7cb5c22a635188d">VarLocs</a>.</p>

</div>
</div>

### emitMOLoc() {#ab17b4ddf05538aab17dbb53a0f5f4329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder TransferTracker::emitMOLoc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &amp; Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Properties)</td>
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



<p>Definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#a87d598e34086fb45a3a64638bdc6097e">LiveDebugValues::DbgValueProperties::DIExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#ad2fecba192de6da1578bdcb78d524169">llvm::MDNode::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#a58e53986006a2e7d95385fe4e633fb2e">llvm::DebugVariable::getInlinedAt</a>, <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a38229438b1c22802074b3181b0b80b85">llvm::DILocalVariable::getScope</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#af2ca096ab72c055f6c2c7e3ffbe5d6bf">llvm::DebugVariable::getVariable</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#a7f88fbb422e5e0d5c0e227b3df0bd8a8">LiveDebugValues::DbgValueProperties::Indirect</a>, <a href="#a79f160cf45e05ebc07c2751e0bd4d944">MF</a> and <a href="#aa1cef6664a3e135245b35927b6db11e5">TII</a>.</p>


<p>Referenced by <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a>.</p>

</div>
</div>

### flushDbgValues() {#acf872fb0e884bca493cc867aac36ed79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::flushDbgValues (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * MBB)</td>
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

<p>Helper to move created DBG_VALUEs into Transfers collection.</p>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0b1a8d3b98bc35fd5cb5b04843beeea5">llvm::getBundleStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a7ee7f28da62a849df2fdb7a96be072d1">PendingDbgValues</a> and <a href="#af06b11c084b9a4ff7e063e146d4131d3">Transfers</a>.</p>


<p>Referenced by <a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a>, <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a>, <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a> and <a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a>.</p>

</div>
</div>

### getLocQualityIfBetter() {#a79fb4ee603e9a1f3010aba7fb3da0f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LocationQuality &gt; TransferTracker::getLocQualityIfBetter (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L, <a href="#aa5d994f6e3b0b93e697c85ca2002834d">LocationQuality</a> Min)</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aa5d994f6e3b0b93e697c85ca2002834da356463ee55aa35f2112197b17e3e18f4">CalleeSavedRegister</a>, <a href="#ac546420f6cd906a9b17e41c43e720e98">isCalleeSaved</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#aa5d994f6e3b0b93e697c85ca2002834da0ba7583639a274c434bbe6ef797115a4">Register</a> and <a href="#aa5d994f6e3b0b93e697c85ca2002834da927573a0209c7f5f0e934ebb6c90d3bf">SpillSlot</a>.</p>


<p>Referenced by <a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a> and <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>.</p>

</div>
</div>

### isCalleeSaved() {#ac546420f6cd906a9b17e41c43e720e98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::isCalleeSaved (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> L)</td>
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



<p>Definition at line 281 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#a1b1735405477716ee8dd95236d3257bf">CalleeSavedRegs</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a> and <a href="#abf13e97a9a5cff9aa06c88d1ac5172fb">TRI</a>.</p>


<p>Referenced by <a href="#a79fb4ee603e9a1f3010aba7fb3da0f82">getLocQualityIfBetter</a>.</p>

</div>
</div>

### isEntryValueValue() {#ab76cea3708e144106a37446994e2482c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::isEntryValueValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &amp; Val)</td>
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



<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64iseldagtodag-cpp/#a2098a5fa6ada61b6c4a1f210ad84e4a1a4ebada6a2af2bcba53ded1d7b414f081">FP</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#acd482282b8eb9755d8ac0e82ba23c20b">LiveDebugValues::ValueIDNum::getBlock</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#af0ee865517c9747fa74f9eb3ed54578a">LiveDebugValues::ValueIDNum::getLoc</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a29e1496690d23acbdb69c5b882f5bf45">LiveDebugValues::ValueIDNum::isPHI</a>, <a href="#a79f160cf45e05ebc07c2751e0bd4d944">MF</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#aa5d994f6e3b0b93e697c85ca2002834da0ba7583639a274c434bbe6ef797115a4">Register</a>, <a href="#a31452b4b5d9984ee5ed52db4b1a52d5e">TLI</a> and <a href="#abf13e97a9a5cff9aa06c88d1ac5172fb">TRI</a>.</p>


<p>Referenced by <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a>.</p>

</div>
</div>

### isEntryValueVariable() {#a930c119c5ebcb496e7665a4521f42b94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::isEntryValueVariable (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> &amp; Var, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a> * Expr)</td>
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



<p>Definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#a58e53986006a2e7d95385fe4e633fb2e">llvm::DebugVariable::getInlinedAt</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a1b59c8fe81267b338774bf6c542f90ee">llvm::DIExpression::getNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvariable/#af2ca096ab72c055f6c2c7e3ffbe5d6bf">llvm::DebugVariable::getVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a8facdaa3e5cf886085dbc81082bc8d41">llvm::DIExpression::isDeref</a> and <a href="/web-llvm/docs/api/classes/llvm/dilocalvariable/#a45c267092569766aa684c6ba3bae9634">llvm::DILocalVariable::isParameter</a>.</p>


<p>Referenced by <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a>.</p>

</div>
</div>

### loadInlocs() {#a304b877a673788ae4edd0e8f5fa1d5d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::loadInlocs (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a7697a3c717033a44ba7f9b272c1d5331">ValueTable</a> &amp; MLocs, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap">DbgOpIDMap</a> &amp; DbgOpStore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> &gt; &gt; &amp; VLocs, unsigned NumLocs)</td>
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

<p>Load object with live-in variable values.</p>


<p><span class="doxyComputerOutput">mlocs</span> contains the live-in values in each machine location, while <span class="doxyComputerOutput">vlocs</span> the live-in variable values. This method picks variable locations for the live-in variables, creates DBG_VALUEs and puts them in <a href="#af06b11c084b9a4ff7e063e146d4131d3">Transfers</a>, then prepares the other object fields to track variable locations as we step through the block. FIXME: could just examine mloctracker instead of passing in <span class="doxyComputerOutput">mlocs</span>?</p>


<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a>, <a href="#ae0a495620f7b1dd27811000f102d1d40">ActiveVLocs</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a76c83b1cb30fe85e09f35ad1103fe75b">LiveDebugValues::LocIdx::asU64</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue/#ac144ecd93e2625852097b3cab8a9d9bba953f120c5617d3f2b42df3fd424222ad">LiveDebugValues::DbgValue::Def</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a98d44bec6b754ac8786ab97f219f06f1">LiveDebugValues::ValueIDNum::EmptyValue</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap/#a0ff8cac5d6ff149c80d136de06314455">LiveDebugValues::DbgOpIDMap::find</a>, <a href="#acf872fb0e884bca493cc867aac36ed79">flushDbgValues</a>, <a href="#a79fb4ee603e9a1f3010aba7fb3da0f82">getLocQualityIfBetter</a>, <a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop/#a17b174ad71c91584d987861d5e8e5d2d">LiveDebugValues::DbgOp::ID</a>, <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74cdbd1e4f731e7d7cd83461b8b1de0b">llvm::sort</a>, <a href="#ae485598414179a9523e127ad2df4756c">UseBeforeDefs</a>, <a href="#a162a58b620ec34701775d8d3e953fb20">UseBeforeDefVariables</a>, <a href="#affb90f774e59ab28e9d3a9d72ac8f8d0">ValueToLocSort</a> and <a href="#a498b0782412a1488e7cb5c22a635188d">VarLocs</a>.</p>

</div>
</div>

### loadVarInloc() {#af64654b3c46ec3154963aed1dbb016d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::loadVarInloc (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap">DbgOpIDMap</a> &amp; DbgOpStore, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="#afa24ee75e581d521a08c6731becbc964">ValueLocPair</a> &gt; &amp; ValueToLoc, <a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a> VarID, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> Value)</td>
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

<p>For a variable <span class="doxyComputerOutput">Var</span> with the live-in value <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></span>, attempts to resolve the <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalue">DbgValue</a> to a concrete DBG_VALUE, emitting that value and loading the tracking information to track Var throughout the block.</p>


<p><span class="doxyComputerOutput">ValueToLoc</span> is a map containing the best known location for every <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> that <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> may use. <span class="doxyComputerOutput">MBB</span> is the basic block that we are loading the live-in value for. <span class="doxyComputerOutput">DbgOpStore</span> is the map containing the DbgOpID-&gt;<a href="/web-llvm/docs/api/structs/livedebugvalues/dbgop">DbgOp</a> mapping needed to determine the values used by <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>


<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a>, <a href="#ae0a495620f7b1dd27811000f102d1d40">ActiveVLocs</a>, <a href="#a46747b1281d39a5af4e522209198e3f2">addUseBeforeDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgopidmap/#a0ff8cac5d6ff149c80d136de06314455">LiveDebugValues::DbgOpIDMap::find</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#acd482282b8eb9755d8ac0e82ba23c20b">LiveDebugValues::ValueIDNum::getBlock</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a3092d50fe696007741e04fca94bd8caf">LiveDebugValues::ValueIDNum::getInst</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a29e1496690d23acbdb69c5b882f5bf45">LiveDebugValues::ValueIDNum::isPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#a7ee7f28da62a849df2fdb7a96be072d1">PendingDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a> and <a href="#affb90f774e59ab28e9d3a9d72ac8f8d0">ValueToLocSort</a>.</p>


<p>Referenced by <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>.</p>

</div>
</div>

### recoverAsEntryValue() {#ac441348b2e73e12e1d8657de17b76568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::recoverAsEntryValue (<a href="/web-llvm/docs/api/namespaces/livedebugvalues/#a2ad7532d3e36d429cab7c3ade85c5f77">DebugVariableID</a> VarID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Prop, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum">ValueIDNum</a> &amp; Num)</td>
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



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a854dc7a14b5443f6244301690474c7a0">llvm::DIExpression::convertToNonVariadicExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af2c351dad09a71aa08e1d85c67ae6e53">llvm::MachineOperand::CreateReg</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#a87d598e34086fb45a3a64638bdc6097e">LiveDebugValues::DbgValueProperties::DIExpr</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="#ab17b4ddf05538aab17dbb53a0f5f4329">emitMOLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a6472489551b8960cc115a93d95eef9f6a732b32a9387e1f0a0b49cd59b96905ae">llvm::DIExpression::EntryValue</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#af0ee865517c9747fa74f9eb3ed54578a">LiveDebugValues::ValueIDNum::getLoc</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#a7f88fbb422e5e0d5c0e227b3df0bd8a8">LiveDebugValues::DbgValueProperties::Indirect</a>, <a href="#ab76cea3708e144106a37446994e2482c">isEntryValueValue</a>, <a href="#a930c119c5ebcb496e7665a4521f42b94">isEntryValueVariable</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties/#aebaf15eb5116df110c1de27c5c8901a2">LiveDebugValues::DbgValueProperties::IsVariadic</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#a7ee7f28da62a849df2fdb7a96be072d1">PendingDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#ab804b15bb92ff685d7c1464b2816d608">llvm::DIExpression::prepend</a>, <a href="#aa5d994f6e3b0b93e697c85ca2002834da0ba7583639a274c434bbe6ef797115a4">Register</a> and <a href="#af1088d1f2ac99145846bedd829c2a05e">ShouldEmitDebugEntryValues</a>.</p>


<p>Referenced by <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a> and <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>.</p>

</div>
</div>

### redefVar() {#ac1753e9184a776f25f017ac1022f2a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::redefVar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
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

<p>Change a variable value after encountering a DBG_VALUE inside a block.</p>

<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a>, <a href="#ae0a495620f7b1dd27811000f102d1d40">ActiveVLocs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a>, <a href="#aa5d994f6e3b0b93e697c85ca2002834da0ba7583639a274c434bbe6ef797115a4">Register</a> and <a href="#a162a58b620ec34701775d8d3e953fb20">UseBeforeDefVariables</a>.</p>


<p>Referenced by <a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a>.</p>

</div>
</div>

### redefVar() {#af3b3d27cd53936e3c52e01a34817d6be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::redefVar (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/livedebugvalues/dbgvalueproperties">DbgValueProperties</a> &amp; Properties, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/livedebugvalues/resolveddbgop">ResolvedDbgOp</a> &gt; &amp; NewLocs)</td>
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

<p>Handle a change in variable location within a block.</p>


<p>Terminate the variables current location, and record the value it now refers to, so that we can detect location transfers later on.</p>


<p>Definition at line 731 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a>, <a href="#ae0a495620f7b1dd27811000f102d1d40">ActiveVLocs</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx/#a76c83b1cb30fe85e09f35ad1103fe75b">LiveDebugValues::LocIdx::asU64</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a162a58b620ec34701775d8d3e953fb20">UseBeforeDefVariables</a> and <a href="#a498b0782412a1488e7cb5c22a635188d">VarLocs</a>.</p>

</div>
</div>

### transferMlocs() {#a787205c8858064b56bad25b823faf3d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TransferTracker::transferMlocs (<a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> Src, <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a> Dst, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> Pos)</td>
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

<p><a href="/web-llvm/docs/api/structs/transfertracker/transfer">Transfer</a> variables based on <span class="doxyComputerOutput">Src</span> to be based on <span class="doxyComputerOutput">Dst</span>.</p>


<p>This handles both register copies as well as spills and restores. Creates DBG_VALUEs describing the movement.</p>


<p>Definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="#aacea713c5575395a3ce28a43c31f1df6">ActiveMLocs</a>, <a href="#ae0a495620f7b1dd27811000f102d1d40">ActiveVLocs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a05f0bb5e94aa2300445044a7a1da02">DVMap</a>, <a href="/web-llvm/docs/api/classes/livedebugvalues/valueidnum/#a98d44bec6b754ac8786ab97f219f06f1">LiveDebugValues::ValueIDNum::EmptyValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp/#afba85f0d2bfd9c12500fa7c93a6e3f91">EmulateOldLDV</a>, <a href="#acf872fb0e884bca493cc867aac36ed79">flushDbgValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a5ccc49e3b9263bbfcdeb391f17b84c2d">MTracker</a>, <a href="#a7ee7f28da62a849df2fdb7a96be072d1">PendingDbgValues</a> and <a href="#a498b0782412a1488e7cb5c22a635188d">VarLocs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ActiveMLocs {#aacea713c5575395a3ce28a43c31f1df6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;LocIdx, SmallSet&lt;DebugVariableID, 4&gt; &gt; TransferTracker::ActiveMLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from LocIdxes to which DebugVariables are based that location.</p>


<p>Mantained while stepping through the block. Not accurate if VarLocs[Idx] != MTracker-&gt;LocIdxToIDNum[Idx].</p>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ac9ed6c9ebb7ede8539a8fe20bfeb36c2">clobberMloc</a>, <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a>, <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>, <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>, <a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a>, <a href="#af3b3d27cd53936e3c52e01a34817d6be">redefVar</a> and <a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a>.</p>

</div>
</div>

### ActiveVLocs {#ae0a495620f7b1dd27811000f102d1d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;DebugVariableID, ResolvedDbgValue&gt; TransferTracker::ActiveVLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from <a href="/web-llvm/docs/api/classes/llvm/debugvariable">DebugVariable</a> to it's current location and qualifying meta information.</p>


<p>To be used in conjunction with ActiveMLocs to construct enough information for the DBG_VALUEs for a particular <a href="/web-llvm/docs/api/classes/livedebugvalues/locidx">LocIdx</a>.</p>


<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a>, <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>, <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>, <a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a>, <a href="#af3b3d27cd53936e3c52e01a34817d6be">redefVar</a> and <a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a>.</p>

</div>
</div>

### CalleeSavedRegs {#a1b1735405477716ee8dd95236d3257bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BitVector&amp; TransferTracker::CalleeSavedRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ac546420f6cd906a9b17e41c43e720e98">isCalleeSaved</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### DVMap {#a0a05f0bb5e94aa2300445044a7a1da02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugVariableMap&amp; TransferTracker::DVMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a>, <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a>, <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>, <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a>, <a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a>, <a href="#af3b3d27cd53936e3c52e01a34817d6be">redefVar</a>, <a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### MF {#a79f160cf45e05ebc07c2751e0bd4d944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction&amp; TransferTracker::MF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ab17b4ddf05538aab17dbb53a0f5f4329">emitMOLoc</a>, <a href="#ab76cea3708e144106a37446994e2482c">isEntryValueValue</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### MTracker {#a5ccc49e3b9263bbfcdeb391f17b84c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MLocTracker* TransferTracker::MTracker</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This machine location tracker is assumed to always contain the up-to-date value mapping for all machine locations.</p>


<p><a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a> only reads information from it. (XXX make it const?)</p>


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a>, <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a>, <a href="#a79fb4ee603e9a1f3010aba7fb3da0f82">getLocQualityIfBetter</a>, <a href="#ac546420f6cd906a9b17e41c43e720e98">isCalleeSaved</a>, <a href="#ab76cea3708e144106a37446994e2482c">isEntryValueValue</a>, <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>, <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>, <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a>, <a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a>, <a href="#af3b3d27cd53936e3c52e01a34817d6be">redefVar</a>, <a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### PendingDbgValues {#a7ee7f28da62a849df2fdb7a96be072d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::pair&lt;DebugVariableID, MachineInstr *&gt;, 4&gt; TransferTracker::PendingDbgValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Temporary cache of DBG_VALUEs to be entered into the Transfers collection.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a>, <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a>, <a href="#acf872fb0e884bca493cc867aac36ed79">flushDbgValues</a>, <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>, <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a> and <a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a>.</p>

</div>
</div>

### ShouldEmitDebugEntryValues {#af1088d1f2ac99145846bedd829c2a05e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::ShouldEmitDebugEntryValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ac441348b2e73e12e1d8657de17b76568">recoverAsEntryValue</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### TII {#aa1cef6664a3e135245b35927b6db11e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* TransferTracker::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ab17b4ddf05538aab17dbb53a0f5f4329">emitMOLoc</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### TLI {#a31452b4b5d9984ee5ed52db4b1a52d5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetLowering* TransferTracker::TLI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ab76cea3708e144106a37446994e2482c">isEntryValueValue</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### Transfers {#af06b11c084b9a4ff7e063e146d4131d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Transfer, 32&gt; TransferTracker::Transfers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collection of transfers (DBG_VALUEs) to be inserted.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#acf872fb0e884bca493cc867aac36ed79">flushDbgValues</a>.</p>

</div>
</div>

### TRI {#abf13e97a9a5cff9aa06c88d1ac5172fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo&amp; TransferTracker::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ac546420f6cd906a9b17e41c43e720e98">isCalleeSaved</a>, <a href="#ab76cea3708e144106a37446994e2482c">isEntryValueValue</a> and <a href="#ab62a3902e9944a4a6da8a82cc72ea1c9">TransferTracker</a>.</p>

</div>
</div>

### UseBeforeDefs {#ae485598414179a9523e127ad2df4756c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;unsigned, SmallVector&lt;UseBeforeDef, 1&gt; &gt; TransferTracker::UseBeforeDefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from instruction index (within the block) to the set of UseBeforeDefs that become defined at that instruction.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a46747b1281d39a5af4e522209198e3f2">addUseBeforeDef</a>, <a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a> and <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>.</p>

</div>
</div>

### UseBeforeDefVariables {#a162a58b620ec34701775d8d3e953fb20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;DebugVariableID&gt; TransferTracker::UseBeforeDefVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The set of variables that are in UseBeforeDefs and can become a location once the relevant value is defined.</p>


<p>An element being erased from this collection prevents the use-before-def materializing.</p>


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#a46747b1281d39a5af4e522209198e3f2">addUseBeforeDef</a>, <a href="#aa1129d2080e1308fd9bd27d20374ace5">checkInstForNewValues</a>, <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>, <a href="#ac1753e9184a776f25f017ac1022f2a13">redefVar</a> and <a href="#af3b3d27cd53936e3c52e01a34817d6be">redefVar</a>.</p>

</div>
</div>

### VarLocs {#a498b0782412a1488e7cb5c22a635188d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ValueIDNum, 32&gt; TransferTracker::VarLocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Local cache of what-value-is-in-what-LocIdx.</p>


<p>Used to identify differences between TransferTrackers view of variable locations and MLocTrackers. For example, <a href="/web-llvm/docs/api/classes/livedebugvalues/mloctracker">MLocTracker</a> observes all clobbers, but <a href="/web-llvm/docs/api/classes/transfertracker">TransferTracker</a> lazily does not.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>Referenced by <a href="#ac9ed6c9ebb7ede8539a8fe20bfeb36c2">clobberMloc</a>, <a href="#aee68454c02cb09e9dc1213c607ee78b9">clobberMloc</a>, <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a>, <a href="#af3b3d27cd53936e3c52e01a34817d6be">redefVar</a> and <a href="#a787205c8858064b56bad25b823faf3d0">transferMlocs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ValueToLocSort() {#affb90f774e59ab28e9d3a9d72ac8f8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TransferTracker::ValueToLocSort (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afa24ee75e581d521a08c6731becbc964">ValueLocPair</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#afa24ee75e581d521a08c6731becbc964">ValueLocPair</a> &amp; B)</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="#a304b877a673788ae4edd0e8f5fa1d5d8">loadInlocs</a> and <a href="#af64654b3c46ec3154963aed1dbb016d2">loadVarInloc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/livedebugvalues/instrrefbasedimpl-cpp">InstrRefBasedImpl.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
