---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-sifixsgprcopies-cpp-/sifixsgprcopies
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SIFixSGPRCopies` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e061d2165c0b69b33fd197d47cd5ebc">SIFixSGPRCopies</a> (MachineDominatorTree *MDT)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac937dffe1e0bab6bdb751371c1923928">run</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc3031d4170d4a972043c6dfa34508c2">fixSCCCopies</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d07e1b3e8e687a63a16ce96c39b9684">prepareRegSequenceAndPHIs</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a414fefcfb2e444166458ec0a1100a06a">getNextVGPRToSGPRCopyId</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776834e825e7fd9cd90c27f7ace1d9d2">needToBeConvertedToVALU</a> (V2SCopyInfo *I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8967731195e767bf313308f20b640de">analyzeVGPRToSGPRCopy</a> (MachineInstr *MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97298a7350df5e0302d0678065f5a1e2">lowerVGPR2SGPRCopies</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4b98ad5bdf4630720ecebfeb5253bd">lowerSpecialCase</a> (MachineInstr &amp;MI, MachineBasicBlock::iterator &amp;I)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadcf47d2bfa2abd153d66b001715198c">processPHINode</a> (MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c842ead18aca7681bd1cd596a3c8ba3">tryMoveVGPRConstToSGPR</a> (MachineOperand &amp;MO, Register NewDst, MachineBasicBlock *BlockToInsertTo, MachineBasicBlock::iterator PointToInsertTo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8197d36664236fc29f4fc53780465c53">MRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo">SIRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo">SIInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d99d3126b978f5a68386e128862b05">TII</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ec69d092297d29450cb584c50f6da9">MDT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a6a28cfca81059d0946388e68536875">SCCCopies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab950ac357764b6b8604d3d0fae0ce1c">RegSequences</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1ef24a0421035fea5913bc7073647a">PHINodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a159f5e004cf40c7db337cbea76e3d33b">S2VCopies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abde6ac2af5b958ff2ec89d0321f1f1d7">NextVGPRToSGPRCopyID</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; unsigned, <a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/v2scopyinfo">V2SCopyInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48a9b1e81d1cd56f2bf62afd8f3d400">V2SCopies</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *, <a href="/web-llvm/docs/api/classes/llvm/setvector">SetVector</a>&lt; unsigned &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300ae6f7a08f8eaa7f6bde02130099a5">SiblingPenalty</a></td>
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


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SIFixSGPRCopies() {#a9e061d2165c0b69b33fd197d47cd5ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::SIFixSGPRCopies (<a href="/web-llvm/docs/api/classes/llvm/machinedominatortree">MachineDominatorTree</a> * MDT)</td>
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



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### analyzeVGPRToSGPRCopy() {#af8967731195e767bf313308f20b640de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIFixSGPRCopies::analyzeVGPRToSGPRCopy (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#acbc921830578e2741be6549db716c0ce">llvm::MachineBasicBlock::end</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="#a414fefcfb2e444166458ec0a1100a06a">getNextVGPRToSGPRCopyId</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a9839b7e1d8811ea9d41f901ab6a0f23b">llvm::MachineInstr::getNumExplicitDefs</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1e855100f407ca4be098d0050be403b0">llvm::MachineInstr::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/cseinfo-cpp/#a75f8a8519c2c9b30e7c06dc5e256fffa">Info</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a1b0f3ebdced8fce4b22c6a63b25d9525">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a586262a958ca1593548855334ba99a12">llvm::MachineInstr::isCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a1912d4fbc40c61a12b1f770ad54dfd74">llvm::MachineInstr::isCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a8d97d09150ddcbcf5039f938111358ee">llvm::MachineInstr::isRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8197d36664236fc29f4fc53780465c53">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="#ab3d99d3126b978f5a68386e128862b05">TII</a>, <a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a7c8714527422f164b52d6daaa65850e8">tryChangeVGPRtoSGPRinCopy</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivusers-cpp/#a4e5b9edb51eec9dbca592075eb64dfcb">Users</a>.</p>


<p>Referenced by <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a>.</p>

</div>
</div>

### fixSCCCopies() {#acc3031d4170d4a972043c6dfa34508c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIFixSGPRCopies::fixSCCCopies (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a6c1f959947905135c7dd215b64957654">llvm::MachineInstrBuilder::addImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa5e4d7acf58e87826a15b94d37144f2b">llvm::getDefRegState</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8197d36664236fc29f4fc53780465c53">MRI</a>, <a href="#ab3d99d3126b978f5a68386e128862b05">TII</a> and <a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a>.</p>


<p>Referenced by <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a>.</p>

</div>
</div>

### getNextVGPRToSGPRCopyId() {#a414fefcfb2e444166458ec0a1100a06a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::getNextVGPRToSGPRCopyId ()</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>Referenced by <a href="#af8967731195e767bf313308f20b640de">analyzeVGPRToSGPRCopy</a>.</p>

</div>
</div>

### lowerSpecialCase() {#aff4b98ad5bdf4630720ecebfeb5253bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFixSGPRCopies::lowerSpecialCase (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> &amp; I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/siinstrworklist/#aed7def507592d4f53c51d552144531c5">llvm::SIInstrWorklist::insert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#abac45c592b45439ab9adbc6eb936c6c4">isSafeToFoldImmIntoCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8197d36664236fc29f4fc53780465c53">MRI</a>, <a href="#ab3d99d3126b978f5a68386e128862b05">TII</a>, <a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a> and <a href="#a7c842ead18aca7681bd1cd596a3c8ba3">tryMoveVGPRConstToSGPR</a>.</p>


<p>Referenced by <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a>.</p>

</div>
</div>

### lowerVGPR2SGPRCopies() {#a97298a7350df5e0302d0678065f5a1e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIFixSGPRCopies::lowerVGPR2SGPRCopies (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siloweri1copies-cpp/#a5cd9e4c7fe1a7ebe8b545eb891a2a949">Copies</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8197d36664236fc29f4fc53780465c53">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a776834e825e7fd9cd90c27f7ace1d9d2">needToBeConvertedToVALU</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="#ab3d99d3126b978f5a68386e128862b05">TII</a> and <a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a>.</p>


<p>Referenced by <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a>.</p>

</div>
</div>

### needToBeConvertedToVALU() {#a776834e825e7fd9cd90c27f7ace1d9d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFixSGPRCopies::needToBeConvertedToVALU (<a href="/web-llvm/docs/api/classes/anonymous-sifixsgprcopies-cpp-/v2scopyinfo">V2SCopyInfo</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#ad67c9230577a0b640c52852c75c93939">llvm::MachineInstr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a028a8c5113d40d8c3f4427053bf36738">llvm::MachineOperand::getSubReg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a120ccebe70e1b0ddf72fc776229d0025">llvm::MachineInstr::isImplicitDef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab4e6de707bff0fe8081c4da0711bba07">llvm::max_element</a> and <a href="/web-llvm/docs/api/classes/llvm/smallset/#afd7c135e18f2d7253d4f8545cd7b1756">llvm::SmallSet&lt; T, N, C &gt;::size</a>.</p>


<p>Referenced by <a href="#a97298a7350df5e0302d0678065f5a1e2">lowerVGPR2SGPRCopies</a>.</p>

</div>
</div>

### prepareRegSequenceAndPHIs() {#a1d07e1b3e8e687a63a16ce96c39b9684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::prepareRegSequenceAndPHIs (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### processPHINode() {#aadcf47d2bfa2abd153d66b001715198c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SIFixSGPRCopies::processPHINode (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#ac178f4fc4e4a0642610c374256b9fb27">llvm::SetVector&lt; T, Vector, Set, N &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af34eb71cc483e84d2eca80575cb9ccde">llvm::SetVector&lt; T, Vector, Set, N &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8197d36664236fc29f4fc53780465c53">MRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/setvector/#af9880d625c506aacc716ee1c9a29ff8b">llvm::SetVector&lt; T, Vector, Set, N &gt;::pop_back_val</a>, <a href="#aadcf47d2bfa2abd153d66b001715198c">processPHINode</a>, <a href="#ab3d99d3126b978f5a68386e128862b05">TII</a>, <a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a6cf2f8996b1e9aaf2d7a435aaa62382f">UseMI</a>.</p>


<p>Referenced by <a href="#aadcf47d2bfa2abd153d66b001715198c">processPHINode</a> and <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a>.</p>

</div>
</div>

### run() {#ac937dffe1e0bab6bdb751371c1923928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFixSGPRCopies::run (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="#af8967731195e767bf313308f20b640de">analyzeVGPRToSGPRCopy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a9404d5d9e4be534bb544777aae216691">llvm::MachineOperand::ChangeToRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a21461ed0167f9300e92dad0ca2ced0fc">EnableM0Merge</a>, <a href="#acc3031d4170d4a972043c6dfa34508c2">fixSCCCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a561542857883d396fc0c5dc9a1de342f">foldVGPRCopyIntoRegSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a01bc1ea0c681b4b2c171cc164805cf5a">getCopyRegClasses</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ad8c65b86ef286331d408a7a74c7b0b2f">llvm::MachineBasicBlock::getFirstInstrTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a38b28a85f818b49d8806c150b8a5b4f7">llvm::MachineOperand::getImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a27efe1286cc31f5fc95355af30b0356c">llvm::AMDGPU::getNamedOperandIdx</a>, <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a030edbec5a50c887caf3ec95c7c50c44">llvm::TargetMachine::getOptLevel</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac1f888bba00f32cb4f9a0010c958f397">llvm::MachineFunction::getProperties</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aacef05f16d3e71703f08bb4677e1d7a2">llvm::MachineFunctionProperties::hasProperty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a4e0750d12818ab0f8a301e4be935ea72">hoistAndMergeSGPRInits</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a76f61c6784df6dc8402a8b9011041926">llvm::MachineOperand::isImm</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a8e3874f05140c734fbc0e9f0ac91d85d">isSGPRToVGPRCopy</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a7c3e37fe69c334ec977a67eabc0da4ca">isVGPRToSGPRCopy</a>, <a href="#aff4b98ad5bdf4630720ecebfeb5253bd">lowerSpecialCase</a>, <a href="#a97298a7350df5e0302d0678065f5a1e2">lowerVGPR2SGPRCopies</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a8197d36664236fc29f4fc53780465c53">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="#aadcf47d2bfa2abd153d66b001715198c">processPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a91b442d385b54e1418d81adc34871053">llvm::MachineFunctionProperties::Selected</a>, <a href="#ab3d99d3126b978f5a68386e128862b05">TII</a>, <a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp/#a7c8714527422f164b52d6daaa65850e8">tryChangeVGPRtoSGPRinCopy</a> and <a href="#a7c842ead18aca7681bd1cd596a3c8ba3">tryMoveVGPRConstToSGPR</a>.</p>

</div>
</div>

### tryMoveVGPRConstToSGPR() {#a7c842ead18aca7681bd1cd596a3c8ba3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SIFixSGPRCopies::tryMoveVGPRConstToSGPR (<a href="/web-llvm/docs/api/classes/llvm/machineoperand">MachineOperand</a> &amp; MO, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> NewDst, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BlockToInsertTo, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">MachineBasicBlock::iterator</a> PointToInsertTo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a713eab58694282971c413a0d6de5975c">llvm::MachineInstrBuilder::add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#ad3ece0ac2421637044624c9b01c42466">DefMI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#ac0035d7c1c860501c877c20e6e93297b">llvm::MachineOperand::getReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a4c9594c955fec80c73ddd964b5efd554">llvm::MachineOperand::isReg</a>, <a href="#a8197d36664236fc29f4fc53780465c53">MRI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a682ba82f42f7903d0000ffbb13ea3b57">llvm::MachineOperand::setReg</a>, <a href="#ab3d99d3126b978f5a68386e128862b05">TII</a> and <a href="#a643dbae54a68131e786b5341cca4aee4">TRI</a>.</p>


<p>Referenced by <a href="#aff4b98ad5bdf4630720ecebfeb5253bd">lowerSpecialCase</a> and <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### MRI {#a8197d36664236fc29f4fc53780465c53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::MRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>Referenced by <a href="#af8967731195e767bf313308f20b640de">analyzeVGPRToSGPRCopy</a>, <a href="#acc3031d4170d4a972043c6dfa34508c2">fixSCCCopies</a>, <a href="#aff4b98ad5bdf4630720ecebfeb5253bd">lowerSpecialCase</a>, <a href="#a97298a7350df5e0302d0678065f5a1e2">lowerVGPR2SGPRCopies</a>, <a href="#aadcf47d2bfa2abd153d66b001715198c">processPHINode</a>, <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a> and <a href="#a7c842ead18aca7681bd1cd596a3c8ba3">tryMoveVGPRConstToSGPR</a>.</p>

</div>
</div>

### TII {#ab3d99d3126b978f5a68386e128862b05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIInstrInfo* anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>Referenced by <a href="#af8967731195e767bf313308f20b640de">analyzeVGPRToSGPRCopy</a>, <a href="#acc3031d4170d4a972043c6dfa34508c2">fixSCCCopies</a>, <a href="#aff4b98ad5bdf4630720ecebfeb5253bd">lowerSpecialCase</a>, <a href="#a97298a7350df5e0302d0678065f5a1e2">lowerVGPR2SGPRCopies</a>, <a href="#aadcf47d2bfa2abd153d66b001715198c">processPHINode</a>, <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a> and <a href="#a7c842ead18aca7681bd1cd596a3c8ba3">tryMoveVGPRConstToSGPR</a>.</p>

</div>
</div>

### TRI {#a643dbae54a68131e786b5341cca4aee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SIRegisterInfo* anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>


<p>Referenced by <a href="#af8967731195e767bf313308f20b640de">analyzeVGPRToSGPRCopy</a>, <a href="#acc3031d4170d4a972043c6dfa34508c2">fixSCCCopies</a>, <a href="#aff4b98ad5bdf4630720ecebfeb5253bd">lowerSpecialCase</a>, <a href="#a97298a7350df5e0302d0678065f5a1e2">lowerVGPR2SGPRCopies</a>, <a href="#aadcf47d2bfa2abd153d66b001715198c">processPHINode</a>, <a href="#ac937dffe1e0bab6bdb751371c1923928">run</a> and <a href="#a7c842ead18aca7681bd1cd596a3c8ba3">tryMoveVGPRConstToSGPR</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MDT {#a54ec69d092297d29450cb584c50f6da9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineDominatorTree* anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::MDT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### NextVGPRToSGPRCopyID {#abde6ac2af5b958ff2ec89d0321f1f1d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::NextVGPRToSGPRCopyID = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### PHINodes {#a0f1ef24a0421035fea5913bc7073647a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 4&gt; anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::PHINodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### RegSequences {#aab950ac357764b6b8604d3d0fae0ce1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 4&gt; anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::RegSequences</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### S2VCopies {#a159f5e004cf40c7db337cbea76e3d33b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 4&gt; anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::S2VCopies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### SCCCopies {#a9a6a28cfca81059d0946388e68536875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;MachineInstr*, 4&gt; anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::SCCCopies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### SiblingPenalty {#a300ae6f7a08f8eaa7f6bde02130099a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;MachineInstr *, SetVector&lt;unsigned&gt; &gt; anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::SiblingPenalty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

### V2SCopies {#ab48a9b1e81d1cd56f2bf62afd8f3d400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;unsigned, V2SCopyInfo&gt; anonymous{SIFixSGPRCopies.cpp}::SIFixSGPRCopies::V2SCopies</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/sifixsgprcopies-cpp">SIFixSGPRCopies.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
