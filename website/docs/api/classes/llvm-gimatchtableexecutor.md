---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gimatchtableexecutor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GIMatchTableExecutor` Class

<p>Provides the logic to execute GlobalISel match tables, which are used by the instruction selector and instruction combiners as their engine to match and apply MIR patterns. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GIMatchTableExecutor { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">llvm/CodeGen/GlobalISel/GIMatchTableExecutor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/combiner">Combiner</a> implementation. <a href="/web-llvm/docs/api/classes/llvm/combiner/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructionselector">InstructionSelector</a></td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86de393f150025719e982512eb086b2a">ComplexRendererFns</a> = std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a> &amp;)&gt;, 4 &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8af184f677d5c7d4eaae692428df99c9">RecordedMIVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ac0ddf7ea380f085ca48f45fa6035a5">NewMIVector</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a>, 4 &gt;</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54a74ca0c82840e37a9a92890385eee6">GIMatchTableExecutor</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab96d74d3dc284435fdeaee475c7c85cf">~GIMatchTableExecutor</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af441511571ed4ad4bc6b719b42934d96">setupGeneratedPerFunctionState</a> (MachineFunction &amp;MF)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc092c61ef888b461f955c86b994511c">setupMF</a> (MachineFunction &amp;mf, GISelKnownBits *kb, CodeGenCoverage *covinfo=nullptr, ProfileSummaryInfo *psi=nullptr, BlockFrequencyInfo *bfi=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setup per-MF executor state. <a href="#abc092c61ef888b461f955c86b994511c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9554b6a1531cc435fc2508a89a9748e0">shouldOptForSize</a> (const MachineFunction *MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a> (TgtExecutor &amp;Exec, MatcherState &amp;State, const ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt; &amp;ExecInfo, MachineIRBuilder &amp;Builder, const uint8_t *MatchTable, const TargetInstrInfo &amp;TII, MachineRegisterInfo &amp;MRI, const TargetRegisterInfo &amp;TRI, const RegisterBankInfo &amp;RBI, const PredicateBitset &amp;AvailableFeatures, CodeGenCoverage *CoverageInfo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Execute a given matcher table and return true if the match was successful and false otherwise. <a href="#a0a2955a941402b4280306f0142b21061">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f85d40b6bad4aaf700854ae1b370be0">getMatchTable</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a687b5956ba7da14119b517367930c1dc">testImmPredicate_I64</a> (unsigned, int64_t) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30455b548886763b211edbaf57ddb508">testImmPredicate_APInt</a> (unsigned, const APInt &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ee63f1b4a837790372b80495555ff62">testImmPredicate_APFloat</a> (unsigned, const APFloat &amp;) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b585bef87c3ab61a04267def7cbf4c5">testMIPredicate_MI</a> (unsigned, const MachineInstr &amp;, const MatcherState &amp;State) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a7e93988e5d41a4d7851bf21340476">testSimplePredicate</a> (unsigned) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad448a6032e3d1900673393daf481779e">runCustomAction</a> (unsigned, const MatcherState &amp;State, NewMIVector &amp;OutMIs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29ae3958e21ba305518fbad7c6ec004">isOperandImmEqual</a> (const MachineOperand &amp;MO, int64_t Value, const MachineRegisterInfo &amp;MRI, bool Splat=false) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596366d4034015c0668d2070e597425f">isBaseWithConstantOffset</a> (const MachineOperand &amp;Root, const MachineRegisterInfo &amp;MRI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified operand is a G_PTR_ADD with a G_CONSTANT on the right-hand side. <a href="#a596366d4034015c0668d2070e597425f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7375926290b7d52cce5ef2c03505f7">isObviouslySafeToFold</a> (MachineInstr &amp;MI, MachineInstr &amp;IntoMI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if MI can obviously be folded into IntoMI. <a href="#acc7375926290b7d52cce5ef2c03505f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codegencoverage">CodeGenCoverage</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5900cfb710c3c8b5f5d2a5b0cadabf9">CoverageInfo</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42689945d570c32ab32defb5469ca47b">KB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52fb4682a4be0321cf8eec99c1f76f93">MF</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2ed5c2002db167510960436bf654fc2">PSI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224495037f6eee0b6970aa0c30fffb74">BFI</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2000833f7ae5727959f4058707e206f7">CurMBB</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a338bdf98e9e600f582b7bef274bc9388">LLVM_ATTRIBUTE_ALWAYS_INLINE</a> uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa284de70c1521913d9eda75728495b36">fastDecodeULEB128</a> (const uint8_t *LLVM_ATTRIBUTE_RESTRICT MatchTable, uint64_t &amp;CurrentIdx)</td>
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

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Ty&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static Ty</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d26f4e678274a5d6300f87b0600d20e">readBytesAs</a> (const uint8_t *MatchTable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8bba411b15797dcf6969c2f6e636bcd">getRemainingOperands</a> (const MachineInstr &amp;MI, unsigned FirstVarOp)</td>
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

<p>Provides the logic to execute GlobalISel match tables, which are used by the instruction selector and instruction combiners as their engine to match and apply MIR patterns.</p>

<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### ComplexRendererFns {#a86de393f150025719e982512eb086b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GIMatchTableExecutor::ComplexRendererFns = 
      std::optional&lt;SmallVector&lt;std::function&lt;void(MachineInstrBuilder &amp;)&gt;, 4&gt;&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>

</div>
</div>

### NewMIVector {#a6ac0ddf7ea380f085ca48f45fa6035a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GIMatchTableExecutor::NewMIVector =  SmallVector&lt;MachineInstrBuilder, 4&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>

</div>
</div>

### RecordedMIVector {#a8af184f677d5c7d4eaae692428df99c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GIMatchTableExecutor::RecordedMIVector =  SmallVector&lt;MachineInstr *, 4&gt;</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### GIMatchTableExecutor() {#a54a74ca0c82840e37a9a92890385eee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GIMatchTableExecutor::GIMatchTableExecutor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>References <a href="#ae5900cfb710c3c8b5f5d2a5b0cadabf9">CoverageInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GIMatchTableExecutor() {#ab96d74d3dc284435fdeaee475c7c85cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::GIMatchTableExecutor::~GIMatchTableExecutor ()</td>
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



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setupGeneratedPerFunctionState() {#af441511571ed4ad4bc6b719b42934d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::GIMatchTableExecutor::setupGeneratedPerFunctionState (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="#a52fb4682a4be0321cf8eec99c1f76f93">MF</a>.</p>


<p>Referenced by <a href="#abc092c61ef888b461f955c86b994511c">setupMF</a>.</p>

</div>
</div>

### setupMF() {#abc092c61ef888b461f955c86b994511c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::GIMatchTableExecutor::setupMF (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; mf, <a href="/web-llvm/docs/api/classes/llvm/giselknownbits">GISelKnownBits</a> * kb, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage">CodeGenCoverage</a> * covinfo=nullptr, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo">ProfileSummaryInfo</a> * psi=nullptr, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo">BlockFrequencyInfo</a> * bfi=nullptr)</td>
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

<p>Setup per-MF executor state.</p>

<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>References <a href="#a224495037f6eee0b6970aa0c30fffb74">BFI</a>, <a href="#ae5900cfb710c3c8b5f5d2a5b0cadabf9">CoverageInfo</a>, <a href="#a2000833f7ae5727959f4058707e206f7">CurMBB</a>, <a href="#a42689945d570c32ab32defb5469ca47b">KB</a>, <a href="#a52fb4682a4be0321cf8eec99c1f76f93">MF</a>, <a href="#aa2ed5c2002db167510960436bf654fc2">PSI</a> and <a href="#af441511571ed4ad4bc6b719b42934d96">setupGeneratedPerFunctionState</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/combiner/#a4a3a16e02e0d2cbe78acd2dcab7dd388">llvm::Combiner::combineMachineInstrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#a83151fce4b310c403a42a444660e030b">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a5e1cc9de768ed92633aa0391a00234f7">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::setupMF</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#aaa901c06b2f29c59d5afab0e47e83962">llvm::AMDGPUInstructionSelector::setupMF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### executeMatchTable() {#a0a2955a941402b4280306f0142b21061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class TgtExecutor, class PredicateBitset, class ComplexMatcherMemFn, class CustomRendererFn&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GIMatchTableExecutor::executeMatchTable (TgtExecutor &amp; Exec, <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/matcherstate">MatcherState</a> &amp; State, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/execinfoty">ExecInfoTy</a>&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt; &amp; ExecInfo, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder">MachineIRBuilder</a> &amp; Builder, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * MatchTable, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> &amp; TII, <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp; TRI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo">RegisterBankInfo</a> &amp; RBI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> PredicateBitset &amp; AvailableFeatures, <a href="/web-llvm/docs/api/classes/llvm/codegencoverage">CodeGenCoverage</a> * CoverageInfo)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Execute a given matcher table and return true if the match was successful and false otherwise.</p>

<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>, definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutorimpl-h">GIMatchTableExecutorImpl.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#af751c28a69e1d07e19dad11e4e26a70d">llvm::MachineIRBuilder::buildConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a8bc92b8a902afb7675480ecc729a66d4">llvm::MachineIRBuilder::buildInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a708b9606a37961be41adad607c81c532">llvm::canReplaceReg</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a45a05a932f80f51023592ff5131d56a5">llvm::GISelChangeObserver::changedInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#ae260ef07f27a4b7f76496d9929bbb317">llvm::GISelChangeObserver::changingAllUsesOfReg</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a1f637715070a99aa4140444e12697f9a">llvm::GISelChangeObserver::changingInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/execinfoty/#aa0441f44fd3b7133723f769c0da5bc10">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::ComplexPredicates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0de00f38864016881b1182ebac4b7b30">llvm::constrainOperandRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2a0be879cebaa17d623212f729b1d4b1">llvm::constrainSelectedInstRegOperands</a>, <a href="#ae5900cfb710c3c8b5f5d2a5b0cadabf9">CoverageInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/execinfoty/#a85c636b7f99842fe3e0756bccd52a6e5">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::CustomRenderers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a3fcdc9f30e5e8b9ea4da99868a8ae4a9">DEBUG_WITH_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ae2863695d9b93a15492fa489f4f85e09">llvm::ConstantInt::equalsInt</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#adbcc821688d1687f0b5faf9ba83bd902">llvm::GISelChangeObserver::erasingInstr</a>, <a href="#aa284de70c1521913d9eda75728495b36">fastDecodeULEB128</a>, <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/execinfoty/#adfaf0a5cc6cb9b94145c30553caeace4">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::FeatureBitsets</a>, <a href="/web-llvm/docs/api/classes/llvm/giselchangeobserver/#a274ff6e49f7c082a254920495943be57">llvm::GISelChangeObserver::finishedChangingAllUsesOfReg</a>, <a href="/web-llvm/docs/api/classes/llvm/integertype/#a14f7b4f1aed38192fb6b7772eb506bdb">llvm::IntegerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a3f583e2bb417139560bde043214d064a">llvm::MachineMemOperand::getAddrSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abc15369ab4cc583332950b913e2ef1dd">llvm::MachineMemOperand::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a29e05cd075864928ae65e1751fdc346e">llvm::MachineOperand::getCImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4b2430ab5e686b82f8cd6fd588d6de6f">llvm::getDefIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a430daa77692b7b25f93a72d83e51964f">llvm::MachineIRBuilder::getInsertPt</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ad21d94ca6aa512e357a993e0e85a921e">llvm::MachineOperand::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ab05719438bdf4b46871e5ecd9730caeb">llvm::MachineInstr::getMF</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a035ff811981517c4885338606c70d928">llvm::MachineIRBuilder::getObserver</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af0d32d967ac31c4e6149c2adb89aa947">llvm::MachineOperand::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a7b7ace4016fc342a5535307a10198daa">llvm::RegisterBankInfo::getRegBank</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbankinfo/#a9a3a4079fc2830c334da4406288bce24">llvm::RegisterBankInfo::getRegBankFromRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/llt/#a32472b5afd0ae6edb4a233a25056a6aa">llvm::LLT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#a0ffa31699dee0349f9b9ae1d3ccb21f1">llvm::MachineMemOperand::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#abcceb535a4bb1e23c320e7628476bd5d">llvm::MachineMemOperand::getSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adb39eef3d8e7cf19a9145c51a5e46253">llvm::getSrcRegIgnoringCopies</a>, <a href="/web-llvm/docs/api/classes/llvm/locationsize/#a935a116f6c8690449f4eddd56a99504b">llvm::LocationSize::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6fd15e2e0832c90a220aec452a36396a0d78a7d38e0e6d17ce2235491dc2b3cf">llvm::GICXXCustomAction_Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6fd15e2e0832c90a220aec452a36396a85bfd2a214922aec43fefa8b70c2249c">llvm::GICXXPred_Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a65143d43d5603f9dba69a2d0004bc70d">llvm::GIM_CheckAPFloatImmPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a2a2cd395c22be85a98d02e5e29660c5f">llvm::GIM_CheckAPIntImmPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84acd2d9eb57c5ea30b572047573c647b24">llvm::GIM_CheckAtomicOrdering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a5490bd4d588069dab3dd706356683363">llvm::GIM_CheckAtomicOrderingOrStrongerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aed6cd1559f0cead69469c6d48527e44a">llvm::GIM_CheckAtomicOrderingWeakerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ac7f6cf201c898042205c3d82a907d6d6">llvm::GIM_CheckCanReplaceReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ad20dca4409f7590197f954cd1f033481">llvm::GIM_CheckCmpPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a39f09a67024023fbca53f2e125f3bbdb">llvm::GIM_CheckComplexPattern</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84af3a7ce7120cbfd6fa9ef64823a7de06c">llvm::GIM_CheckConstantInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ad1d09f02146c2c60dfcaf62b15474586">llvm::GIM_CheckConstantInt8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84afdf8e26b1fc5d330aa6d6e8fb4360813">llvm::GIM_CheckCxxInsnPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ac683a59968221140f5dd06fe97e85ec4">llvm::GIM_CheckFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a2b858a0624f463213b98796b9d584e7d">llvm::GIM_CheckHasNoUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ab43de658e6c5353b04d507de6bfb6a1f">llvm::GIM_CheckHasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a28ae25d9f6f40f340ca4e605d449f938">llvm::GIM_CheckI64ImmPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aecf89db6e41b1f144368611325331037">llvm::GIM_CheckImmOperandPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84af1e8acff65a95651ca919b09f7d18819">llvm::GIM_CheckIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a1cd0d7a1845188d7c5d17d4563ca8013">llvm::GIM_CheckIsBuildVectorAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a50aa64435de5b0c19a73ffc63320bac9">llvm::GIM_CheckIsBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ac15b17108c1cdd3f05023f9a5747afe4">llvm::GIM_CheckIsImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aa1eeb5bfb18be904fcb94e3e97772f7f">llvm::GIM_CheckIsMBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a5acb32c66d14688efea083bd3ceaa8cc">llvm::GIM_CheckIsSafeToFold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a98058684db37c8d2064041023dcc9d6f">llvm::GIM_CheckIsSameOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aa12c661e93d40f79d899e7e7a824d4d2">llvm::GIM_CheckIsSameOperandIgnoreCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aad83fa18e37413d9dffbcffa0511446b">llvm::GIM_CheckLiteralInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84acc19f364ec183a47e3a26d89470afa66">llvm::GIM_CheckMemoryAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a97fed2b9d2087a9ded7f8073ca157967">llvm::GIM_CheckMemoryAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a101c7a7ac7d86b18d2a14b3463fdc7b4">llvm::GIM_CheckMemorySizeEqualTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a341048dafbddd227ccef983523fed2c7">llvm::GIM_CheckMemorySizeEqualToLLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aa6e5bf3ced72bf15c5ef7fc7b66042c4">llvm::GIM_CheckMemorySizeGreaterThanLLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ab015e1251cc68953520f5ed4202b4005">llvm::GIM_CheckMemorySizeLessThanLLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a1fda933c7880a753a885156b6566ce21">llvm::GIM_CheckNumOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aa8e97db139042149f947763970c7d79e">llvm::GIM_CheckNumOperandsGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aa386181095f9c4c5ae579bf5f0794e51">llvm::GIM_CheckNumOperandsLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a5f5cf67489f8dc8c9a40848dd8bd82b0">llvm::GIM_CheckOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ad372783f9a2bc4bfa0b7ffb608aa9bc3">llvm::GIM_CheckOpcodeIsEither</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a314906da59dd2fb152e80972018df750">llvm::GIM_CheckPointerToAny</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aa740bcae35c784e560877c554c639820">llvm::GIM_CheckRegBankForClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84afea63447ca29f127d6cec5406254b8e9">llvm::GIM_CheckSimplePredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ace7723c2e6766e0a3d7443ec141d39fb">llvm::GIM_CheckType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a92df516d8a5a58b3b396308a804dfbb8">llvm::GIM_MIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a5cec1c5190fb61ac734ded11054eb555">llvm::GIM_MIFlagsNot</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ac10fd8c318f59bec57af6c68f6ff06c0">llvm::GIM_RecordInsn</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84af7baa2963d4273ad4781e1886f29ea6a">llvm::GIM_RecordInsnIgnoreCopies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a182c9e6f8c94e6977212337e065594dd">llvm::GIM_RecordNamedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ab2e7dcae37feb424f8a3dbad0a6aca85">llvm::GIM_RecordRegType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a668d91c9831986ecaf1e507aacc9b9f6">llvm::GIM_Reject</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a1611f07ba815c7298c4a5b6c25695114">llvm::GIM_RootCheckRegBankForClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a12d15f287e3cefccf1081ce1af2c08a2">llvm::GIM_RootCheckType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a63790ce46cd26b20d97c461c22326253">llvm::GIM_SwitchOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a438b8acf8a4b992c4264a83d20d627a4">llvm::GIM_SwitchType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a1b38cae4864b83c6662d70ed7755c732">llvm::GIM_Try</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a223e240a3183b4e28d5369073514db0a">llvm::GIR_AddCImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a83900c90d5d6cf501158ca949378bd3a">llvm::GIR_AddImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aa07680b50a3e485cb1e03a4b8fbf6196">llvm::GIR_AddImm8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a2974301dab2ecd88d750b9cfd6dc0bf0">llvm::GIR_AddImplicitDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ae83b298a9f209ea0cc61ba30d9fbe644">llvm::GIR_AddImplicitUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a0266c15934fc11c769bcd3fc3962c8f7">llvm::GIR_AddIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a57917e0d53f81522ab9bf380c4a6d584">llvm::GIR_AddRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a745183663ffac02b717a70b059c5fea3">llvm::GIR_AddSimpleTempRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a7a9328345c0c175b82874eca0f0d2303">llvm::GIR_AddTempRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a57cc1d3d879b036fc687d761492cec6b">llvm::GIR_AddTempSubRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84add5e6b57a70e3a67b67b6bf4487cdace">llvm::GIR_BuildConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84abf86dd527136097e4ef50098b47a0369">llvm::GIR_BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ac3a1fb0682facc726804a2551ff860c5">llvm::GIR_BuildRootMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a02fbdb2ad737aab648cbdda74b286b0c">llvm::GIR_ComplexRenderer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a05213d636af3b07e608ef474d15a6f65">llvm::GIR_ComplexSubOperandRenderer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84af7703ea27d7537f9cdcfc0f13ba9ad45">llvm::GIR_ComplexSubOperandSubRegRenderer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a2848ba22f180a28fbbbe26b7e1d2a7cd">llvm::GIR_ConstrainOperandRC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84afc79d662cc596d338cb5a83d8d536ef2">llvm::GIR_ConstrainSelectedInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a7aff73c32862ac27c8814471b0014987">llvm::GIR_Copy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a3f4f5e97276ad9d138f8a4b3da6fdb71">llvm::GIR_CopyConstantAsSImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a84bd2d59a7f26a059f49e39641648a4f">llvm::GIR_CopyFConstantAsFPImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ab8f45f0502469e2044380f3c140911f5">llvm::GIR_CopyMIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a97bd5d7159872feaeff08bbac3cf9c4f">llvm::GIR_CopyOrAddZeroReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a91f917ed872d98c61903d74b503b6187">llvm::GIR_CopyRemaining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a4892d4acf82fbcf2299b40b295a37dc1">llvm::GIR_CopySubReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aea1ef60ea5055083fb954a7e2f2ee62c">llvm::GIR_Coverage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84afacd20764289c28ed9ac7e288991e696">llvm::GIR_CustomOperandRenderer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84acc919467d5ad7054d4f2fab52052cb61">llvm::GIR_CustomRenderer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a163cb4909d585c3835baf2a6d66df440">llvm::GIR_Done</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84abe33bb8f1b6dbceed138e94ab44f91fd">llvm::GIR_DoneWithCustomAction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a42f131d412046ab6741376162d6a0277">llvm::GIR_EraseFromParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ab64446e49f757afd093d8b6d651b7fc1">llvm::GIR_EraseRootFromParent_Done</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a066f2dc31445dd5e74f41e43607e6c05">llvm::GIR_MakeTempReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aec963bbaf7fc97925f4538070b2174cd">llvm::GIR_MergeMemOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a4c733a5d0a8572f93e5a05426e64707d">llvm::GIR_MutateOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a5fab2fc8368f57fbd8b34835b8bb109a">llvm::GIR_ReplaceReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a03d829ac5438ded725144a7eea5af40c">llvm::GIR_ReplaceRegWithTempReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84a1be994013f6fb9fc774f1f71c001324e">llvm::GIR_RootConstrainSelectedInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84af74b3e669873cf7553b1c8626763b232">llvm::GIR_RootToRootCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84ad455ae9e50e58c6c80468ddd07d50a04">llvm::GIR_SetImplicitDefDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84aeef4fb2114a647b95873663988984e91">llvm::GIR_SetMIFlags</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aecc1a270efbc7afe5e8be928dbe9bf84adbb46023bf50160423d802af73e070e7">llvm::GIR_UnsetMIFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a0fec8ba6f4a4dc758b725205985eee99">llvm::RegState::Implicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f04318888b610cbdd037adc9b1b17e3">llvm::isAtLeastOrStrongerThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a882ca8d6de322e8bbc18be97b45085fc">llvm::isBuildVectorAllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0905ec01af203441d890c82574431329">llvm::isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a32ea768fbb182d6bbe3ff85ae1eb7031">llvm::MachineOperand::isCImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a44f92ba840149cc7f75e38279341257a">llvm::MachineOperand::isIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#afb486f9022a26e1cc53ff189710dbde5">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownGE</a>, <a href="/web-llvm/docs/api/classes/llvm/details/fixedorscalablequantity/#a338ba7ca7a526243ab1853d07d90fe38">llvm::details::FixedOrScalableQuantity&lt; TypeSize, uint64_t &gt;::isKnownLE</a>, <a href="#acc7375926290b7d52cce5ef2c03505f7">isObviouslySafeToFold</a>, <a href="#aa29ae3958e21ba305518fbad7c6ec004">isOperandImmEqual</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4039d2f36755814cb173552df270bddc">llvm::MachineOperand::isPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af21b12b7c8de1504a945c4c974e06bff">llvm::isStrongerThan</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a52fb4682a4be0321cf8eec99c1f76f93">MF</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59f98bbb1f440db8d5db1c8b5bd819f6">llvm::MinAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#aafacf84de1cb994a92dc045f4aa1d518a1cf224b3316c689f4735877ef0bbd893">llvm::MachineInstr::NoFPExcept</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a999b8f3e58e7ca479f26445bae791a7c">llvm::MachineInstr::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#a6d26f4e678274a5d6300f87b0600d20e">readBytesAs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#ad0b3d8447f88377b62d9c019f3c4e118">llvm::SmallVectorImpl&lt; T &gt;::resize</a>, <a href="#ad448a6032e3d1900673393daf481779e">runCustomAction</a>, <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0df93c0f752428162e14b54f8999172d">llvm::MachineIRBuilder::setInsertPt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a>, <a href="#a1ee63f1b4a837790372b80495555ff62">testImmPredicate_APFloat</a>, <a href="#a30455b548886763b211edbaf57ddb508">testImmPredicate_APInt</a>, <a href="#a687b5956ba7da14119b517367930c1dc">testImmPredicate_I64</a>, <a href="#a4b585bef87c3ab61a04267def7cbf4c5">testMIPredicate_MI</a>, <a href="#a04a7e93988e5d41a4d7851bf21340476">testSimplePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/execinfoty/#a9ca01bc8856409a03f8fa62e4cbcd9ed">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::TypeIDMap</a> and <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/execinfoty/#a32f82439a0e15f9e31515bcc7150df94">llvm::GIMatchTableExecutor::ExecInfoTy&lt; PredicateBitset, ComplexMatcherMemFn, CustomRendererFn &gt;::TypeObjects</a>.</p>

</div>
</div>

### getMatchTable() {#a2f85d40b6bad4aaf700854ae1b370be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const uint8_t * llvm::GIMatchTableExecutor::getMatchTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### isBaseWithConstantOffset() {#a596366d4034015c0668d2070e597425f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GIMatchTableExecutor::isBaseWithConstantOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; Root, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified operand is a G_PTR_ADD with a G_CONSTANT on the right-hand side.</p>


<p>GlobalISel's separation of pointer and integer types means that we don't need to worry about G_OR with equivalent semantics.</p>


<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/gimatchtableexecutor-cpp">GIMatchTableExecutor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a0363204b5fbab08a46f5a7cd7f376f78">llvm::MachineInstr::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>.</p>

</div>
</div>

### isObviouslySafeToFold() {#acc7375926290b7d52cce5ef2c03505f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GIMatchTableExecutor::isObviouslySafeToFold (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; IntoMI)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if MI can obviously be folded into IntoMI.</p>


<p>MI and IntoMI do not need to be in the same basic blocks, but MI must preceed IntoMI.</p>


<p>Declaration at line 731 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/gimatchtableexecutor-cpp">GIMatchTableExecutor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90f68a1fc5d44bb06164dc2188b8e486">llvm::instructionsWithoutDebug</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

### isOperandImmEqual() {#aa29ae3958e21ba305518fbad7c6ec004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GIMatchTableExecutor::isOperandImmEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, int64_t Value, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp; MRI, bool Splat=false)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/gimatchtableexecutor-cpp">GIMatchTableExecutor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1af9fe220013bab6cfd9c7bb1be42477">llvm::getIConstantSplatVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76eb82370e997f967454f441effbbff">llvm::getIConstantVRegValWithLookThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a766456df1dd21e804cd4596304e10764a5b9bf50c6579a978e5c1104bf8787651">llvm::Splat</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

### runCustomAction() {#ad448a6032e3d1900673393daf481779e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GIMatchTableExecutor::runCustomAction (unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/matcherstate">MatcherState</a> &amp; State, <a href="#a6ac0ddf7ea380f085ca48f45fa6035a5">NewMIVector</a> &amp; OutMIs)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

### shouldOptForSize() {#a9554b6a1531cc435fc2508a89a9748e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GIMatchTableExecutor::shouldOptForSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> * MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 637 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>References <a href="#a224495037f6eee0b6970aa0c30fffb74">BFI</a>, <a href="#a2000833f7ae5727959f4058707e206f7">CurMBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a52fb4682a4be0321cf8eec99c1f76f93">MF</a>, <a href="#aa2ed5c2002db167510960436bf654fc2">PSI</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3af72f14ea20f2c762c751d2d49e5ea3">llvm::shouldOptimizeForSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>.</p>

</div>
</div>

### testImmPredicate\_APFloat() {#a1ee63f1b4a837790372b80495555ff62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GIMatchTableExecutor::testImmPredicate_APFloat (unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

### testImmPredicate\_APInt() {#a30455b548886763b211edbaf57ddb508}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GIMatchTableExecutor::testImmPredicate_APInt (unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

### testImmPredicate\_I64() {#a687b5956ba7da14119b517367930c1dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GIMatchTableExecutor::testImmPredicate_I64 (unsigned, int64_t)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

### testMIPredicate\_MI() {#a4b585bef87c3ab61a04267def7cbf4c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GIMatchTableExecutor::testMIPredicate_MI (unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gimatchtableexecutor/matcherstate">MatcherState</a> &amp; State)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

### testSimplePredicate() {#a04a7e93988e5d41a4d7851bf21340476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GIMatchTableExecutor::testSimplePredicate (unsigned)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BFI {#a224495037f6eee0b6970aa0c30fffb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequencyInfo* llvm::GIMatchTableExecutor::BFI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#a31d8f3539028d6af3bbcd78745ea50bf">llvm::AMDGPUInstructionSelector::getName</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#a83151fce4b310c403a42a444660e030b">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a5e1cc9de768ed92633aa0391a00234f7">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8fc4d11927fc993885c41ace2b887447">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#aaa901c06b2f29c59d5afab0e47e83962">llvm::AMDGPUInstructionSelector::setupMF</a>, <a href="#abc092c61ef888b461f955c86b994511c">setupMF</a> and <a href="#a9554b6a1531cc435fc2508a89a9748e0">shouldOptForSize</a>.</p>

</div>
</div>

### CoverageInfo {#ae5900cfb710c3c8b5f5d2a5b0cadabf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenCoverage* llvm::GIMatchTableExecutor::CoverageInfo = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#a31d8f3539028d6af3bbcd78745ea50bf">llvm::AMDGPUInstructionSelector::getName</a>, <a href="#a54a74ca0c82840e37a9a92890385eee6">GIMatchTableExecutor</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstructionselector-cpp-/ppcinstructionselector/#a051c8a2638fc5f95b9ccd5e82a7a8559">anonymous{PPCInstructionSelector.cpp}::PPCInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a285142054aed60907906550e49ed07e2">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a4a8b881c0637c6f85c3eb6891abcfab4">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86instructionselector-cpp-/x86instructionselector/#a2f9fb38133cb5844e49ed1ad78588b2a">anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#a978498ac91a6e163a70f06bf1259e224">llvm::AMDGPUInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#a83151fce4b310c403a42a444660e030b">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a5e1cc9de768ed92633aa0391a00234f7">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8fc4d11927fc993885c41ace2b887447">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#aaa901c06b2f29c59d5afab0e47e83962">llvm::AMDGPUInstructionSelector::setupMF</a> and <a href="#abc092c61ef888b461f955c86b994511c">setupMF</a>.</p>

</div>
</div>

### CurMBB {#a2000833f7ae5727959f4058707e206f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineBasicBlock* llvm::GIMatchTableExecutor::CurMBB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#abc092c61ef888b461f955c86b994511c">setupMF</a> and <a href="#a9554b6a1531cc435fc2508a89a9748e0">shouldOptForSize</a>.</p>

</div>
</div>

### KB {#a42689945d570c32ab32defb5469ca47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GISelKnownBits* llvm::GIMatchTableExecutor::KB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#a31d8f3539028d6af3bbcd78745ea50bf">llvm::AMDGPUInstructionSelector::getName</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#a83151fce4b310c403a42a444660e030b">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a5e1cc9de768ed92633aa0391a00234f7">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8fc4d11927fc993885c41ace2b887447">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#aaa901c06b2f29c59d5afab0e47e83962">llvm::AMDGPUInstructionSelector::setupMF</a> and <a href="#abc092c61ef888b461f955c86b994511c">setupMF</a>.</p>

</div>
</div>

### MF {#a52fb4682a4be0321cf8eec99c1f76f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::GIMatchTableExecutor::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#a31d8f3539028d6af3bbcd78745ea50bf">llvm::AMDGPUInstructionSelector::getName</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#acf1575bd51e7b6b91a92904410f268aa">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcinstructionselector-cpp-/ppcinstructionselector/#a051c8a2638fc5f95b9ccd5e82a7a8559">anonymous{PPCInstructionSelector.cpp}::PPCInstructionSelector::select</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86instructionselector-cpp-/x86instructionselector/#a2f9fb38133cb5844e49ed1ad78588b2a">anonymous{X86InstructionSelector.cpp}::X86InstructionSelector::select</a>, <a href="#af441511571ed4ad4bc6b719b42934d96">setupGeneratedPerFunctionState</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#a83151fce4b310c403a42a444660e030b">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a5e1cc9de768ed92633aa0391a00234f7">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8fc4d11927fc993885c41ace2b887447">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#aaa901c06b2f29c59d5afab0e47e83962">llvm::AMDGPUInstructionSelector::setupMF</a>, <a href="#abc092c61ef888b461f955c86b994511c">setupMF</a> and <a href="#a9554b6a1531cc435fc2508a89a9748e0">shouldOptForSize</a>.</p>

</div>
</div>

### PSI {#aa2ed5c2002db167510960436bf654fc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProfileSummaryInfo* llvm::GIMatchTableExecutor::PSI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#a31d8f3539028d6af3bbcd78745ea50bf">llvm::AMDGPUInstructionSelector::getName</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64instructionselector-cpp-/aarch64instructionselector/#a83151fce4b310c403a42a444660e030b">anonymous{AArch64InstructionSelector.cpp}::AArch64InstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvinstructionselector-cpp-/riscvinstructionselector/#a5e1cc9de768ed92633aa0391a00234f7">anonymous{RISCVInstructionSelector.cpp}::RISCVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/anonymous-spirvinstructionselector-cpp-/spirvinstructionselector/#a8fc4d11927fc993885c41ace2b887447">anonymous{SPIRVInstructionSelector.cpp}::SPIRVInstructionSelector::setupMF</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpuinstructionselector/#aaa901c06b2f29c59d5afab0e47e83962">llvm::AMDGPUInstructionSelector::setupMF</a>, <a href="#abc092c61ef888b461f955c86b994511c">setupMF</a> and <a href="#a9554b6a1531cc435fc2508a89a9748e0">shouldOptForSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### fastDecodeULEB128() {#aa284de70c1521913d9eda75728495b36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_ATTRIBUTE_ALWAYS_INLINE uint64_t llvm::GIMatchTableExecutor::fastDecodeULEB128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a5b37bec11eb1346dfa611754d0b12263">LLVM_ATTRIBUTE_RESTRICT</a> MatchTable, uint64_t &amp; CurrentIdx)</td>
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



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a5b37bec11eb1346dfa611754d0b12263">LLVM_ATTRIBUTE_RESTRICT</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### getRemainingOperands() {#ae8bba411b15797dcf6969c2f6e636bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MachineOperand &gt; llvm::GIMatchTableExecutor::getRemainingOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned FirstVarOp)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>.</p>

</div>
</div>

### readBytesAs() {#a6d26f4e678274a5d6300f87b0600d20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Ty&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Ty llvm::GIMatchTableExecutor::readBytesAs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t * MatchTable)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a>.</p>


<p>Referenced by <a href="#a0a2955a941402b4280306f0142b21061">executeMatchTable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutor-h">GIMatchTableExecutor.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/gimatchtableexecutorimpl-h">GIMatchTableExecutorImpl.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/gimatchtableexecutor-cpp">GIMatchTableExecutor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
