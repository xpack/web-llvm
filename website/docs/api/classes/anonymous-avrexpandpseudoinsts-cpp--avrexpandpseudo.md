---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-avrexpandpseudoinsts-cpp-/avrexpandpseudo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AVRExpandPseudo` Class Reference

<p>Expands "placeholder" instructions marked as pseudo into actual <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> instructions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo { ... }
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> <a href="#a2fd4f8e85075063b96289482773aacbb">Block</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ae34c996b58df9b9ce6695a0c8b70c533">Block::iterator</a> <a href="#a10f128a351455c96b6e037732194a382">BlockIt</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9340f714a9e64a69b5fd17649a5fb2">AVRExpandPseudo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba54307c769c172842accffb5c29e759">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#aba54307c769c172842accffb5c29e759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb237cdadc124e2393a8bee54821108a">getPassName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getPassName - Return a nice clean name for a pass. <a href="#afb237cdadc124e2393a8bee54821108a">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09424038b4f459c470c5b2167feca88e">expandMBB</a> (Block &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d57fadd38f04b846251afb30cb62ca9">expandMI</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned OP&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7463b2735f08a968d9da08f5679eb9f5">expand</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9ed99063ad117710d0023d55448014">buildMI</a> (Block &amp;MBB, BlockIt MBBI, unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder">MachineInstrBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f5dc2f83df04fc92a02f339bd29e8e9">buildMI</a> (Block &amp;MBB, BlockIt MBBI, unsigned Opcode, Register DstReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cbf7a408516d5d002edcb604ec63e78">getRegInfo</a> (Block &amp;MBB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aaca92ead3b2860062db0c0bfe8f1d6">expandArith</a> (unsigned OpLo, unsigned OpHi, Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b15206576161d59ca1e9b717171c3a1">expandLogic</a> (unsigned Op, Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa768f314a48744512cf0af76ece1f2d">expandLogicImm</a> (unsigned Op, Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24e22f2fd153a60047ed0690f62a5a23">isLogicImmOpRedundant</a> (unsigned Op, unsigned ImmVal) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad38b7f88a8765a7784b2eb4f84798ef">isLogicRegOpUndef</a> (unsigned Op, unsigned ImmVal) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04108aa656a5138b2b8797a40ae04866">expandAtomic</a> (Block &amp;MBB, BlockIt MBBI, Func f)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Func&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78b0bf1ede0dcf94cfacf7cb65251742">expandAtomicBinaryOp</a> (unsigned Opcode, Block &amp;MBB, BlockIt MBBI, Func f)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e46c44705687882410430de45fb6e6c">expandAtomicBinaryOp</a> (unsigned Opcode, Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a8a86090b6970a6bca3ed090f91612">expandLSLB7Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specific shift implementation for int8. <a href="#ae4a8a86090b6970a6bca3ed090f91612">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954f31d41841925421ab1d8430c15203">expandLSRB7Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb41be103c82ef3fedc446d523bea0cf">expandASRB6Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a533ee1f7966ef55f79ba5423168fe374">expandASRB7Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc0a36e24decb0adcfb36677fb0d083c">expandLSLW4Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specific shift implementation for int16. <a href="#adc0a36e24decb0adcfb36677fb0d083c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a975c9de8b0ebeb7bb14e7075c15801c9">expandLSRW4Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab11fcd2269e58023b47c74449237386">expandASRW7Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac070b8fc78266d168f0a46b2b6897094">expandLSLW8Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9e55b8eac64f0b35e8b70e5ca0af01">expandLSRW8Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c48a08f2023f115dc9efc4e76046a7">expandASRW8Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4d32cadee8af79d6e17fc73581c7a8c">expandLSLW12Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b4eb94a5f565c3e103d51b87bab3174">expandLSRW12Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a533ba81e1c5c7019d173701c5b541af3">expandASRW14Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae24f416290a5ca11a16bfcdfd4b0bebb">expandASRW15Rd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adceea6f51a9c137b655f3f0228aa41a1">expandLPMWELPMW</a> (Block &amp;MBB, BlockIt MBBI, bool IsELPM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3cb4e0c61add8e4e5185de37b0105f9">expandLPMBELPMB</a> (Block &amp;MBB, BlockIt MBBI, bool IsELPM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96ba6f66329f42b91156012f549ff355">expandROLBRd</a> (Block &amp;MBB, BlockIt MBBI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/avrregisterinfo">AVRRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8962bbafb5e5aedc4239c203d9c8b27a">TRI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76849a308b78b528817113105273f2b5">TII</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4be6752b04a112cc9f55da3c39e487ef">ID</a> = 0</td>
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

<p>Expands "placeholder" instructions marked as pseudo into actual <a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> instructions.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Block {#a2fd4f8e85075063b96289482773aacbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef MachineBasicBlock anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::Block</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### BlockIt {#a10f128a351455c96b6e037732194a382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef Block::iterator anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::BlockIt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AVRExpandPseudo() {#a3a9340f714a9e64a69b5fd17649a5fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::AVRExpandPseudo ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/passregistry/#a05a729900b76c89e808c6c3094921b2f">llvm::PassRegistry::getPassRegistry</a>, <a href="#a4be6752b04a112cc9f55da3c39e487ef">ID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16ceb4ec445b9783e0c4d1411876203b">llvm::initializeAVRExpandPseudoPass</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp/#a636eb49c556ccf27213b0a20028d4027">INITIALIZE_PASS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getPassName() {#afb237cdadc124e2393a8bee54821108a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::getPassName ()</td>
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

<p>getPassName - Return a nice clean name for a pass.</p>


<p>This usually implemented in terms of the name that is registered by one of the Registration templates, but can be overloaded directly.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp/#a977357d70c05cd350c98668b5a606acb">AVR_EXPAND_PSEUDO_NAME</a>.</p>

</div>
</div>

### runOnMachineFunction() {#aba54307c769c172842accffb5c29e759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/avrsubtarget/#a68197f257d323a42ac0143c2770e086d">llvm::AVRSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/avrsubtarget/#afcfa7aba3fbf0b2fa321cecf07028e03">llvm::AVRSubtarget::getRegisterInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#a5958512eae2979bd2eb383977996a600">MBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a0f1c83c3d08d80b12c424962a5e94ce8a35e0c8c0b180c95d4e122e55ed62cc64">Modified</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildMI() {#a0b9ed99063ad117710d0023d55448014}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::buildMI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI, unsigned Opcode)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### buildMI() {#a9f5dc2f83df04fc92a02f339bd29e8e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstrBuilder anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::buildMI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI, unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> DstReg)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expand() {#a7463b2735f08a968d9da08f5679eb9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned OP&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expand (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandArith() {#a6aaca92ead3b2860062db0c0bfe8f1d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandArith (unsigned OpLo, unsigned OpHi, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandASRB6Rd() {#abb41be103c82ef3fedc446d523bea0cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandASRB6Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandASRB7Rd() {#a533ee1f7966ef55f79ba5423168fe374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandASRB7Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandASRW14Rd() {#a533ba81e1c5c7019d173701c5b541af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandASRW14Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandASRW15Rd() {#ae24f416290a5ca11a16bfcdfd4b0bebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandASRW15Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandASRW7Rd() {#aab11fcd2269e58023b47c74449237386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandASRW7Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandASRW8Rd() {#ac0c48a08f2023f115dc9efc4e76046a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandASRW8Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandAtomic() {#a04108aa656a5138b2b8797a40ae04866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandAtomic (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI, Func f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandAtomicBinaryOp() {#a78b0bf1ede0dcf94cfacf7cb65251742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Func&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandAtomicBinaryOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI, Func f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandAtomicBinaryOp() {#a9e46c44705687882410430de45fb6e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandAtomicBinaryOp (unsigned Opcode, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLogic() {#a3b15206576161d59ca1e9b717171c3a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLogic (unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLogicImm() {#afa768f314a48744512cf0af76ece1f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLogicImm (unsigned Op, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLPMBELPMB() {#ab3cb4e0c61add8e4e5185de37b0105f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLPMBELPMB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI, bool IsELPM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLPMWELPMW() {#adceea6f51a9c137b655f3f0228aa41a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLPMWELPMW (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI, bool IsELPM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSLB7Rd() {#ae4a8a86090b6970a6bca3ed090f91612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSLB7Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specific shift implementation for int8.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSLW12Rd() {#af4d32cadee8af79d6e17fc73581c7a8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSLW12Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSLW4Rd() {#adc0a36e24decb0adcfb36677fb0d083c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSLW4Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specific shift implementation for int16.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSLW8Rd() {#ac070b8fc78266d168f0a46b2b6897094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSLW8Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSRB7Rd() {#a954f31d41841925421ab1d8430c15203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSRB7Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSRW12Rd() {#a6b4eb94a5f565c3e103d51b87bab3174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSRW12Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSRW4Rd() {#a975c9de8b0ebeb7bb14e7075c15801c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSRW4Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandLSRW8Rd() {#acd9e55b8eac64f0b35e8b70e5ca0af01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandLSRW8Rd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandMBB() {#a09424038b4f459c470c5b2167feca88e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandMBB (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandMI() {#a7d57fadd38f04b846251afb30cb62ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandMI (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### expandROLBRd() {#a96ba6f66329f42b91156012f549ff355}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::expandROLBRd (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB, <a href="/web-llvm/docs/api/classes/llvm/machineinstrbundleiterator">BlockIt</a> MBBI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### getRegInfo() {#a3cbf7a408516d5d002edcb604ec63e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo &amp; anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::getRegInfo (<a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">Block</a> &amp; MBB)</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### isLogicImmOpRedundant() {#a24e22f2fd153a60047ed0690f62a5a23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::isLogicImmOpRedundant (unsigned Op, unsigned ImmVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### isLogicRegOpUndef() {#aad38b7f88a8765a7784b2eb4f84798ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::isLogicRegOpUndef (unsigned Op, unsigned ImmVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### TII {#a76849a308b78b528817113105273f2b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::TII</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

### TRI {#a8962bbafb5e5aedc4239c203d9c8b27a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AVRRegisterInfo* anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::TRI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### ID {#a4be6752b04a112cc9f55da3c39e487ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char anonymous{AVRExpandPseudoInsts.cpp}::AVRExpandPseudo::ID = 0</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a>.</p>


<p>Referenced by <a href="#a3a9340f714a9e64a69b5fd17649a5fb2">AVRExpandPseudo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrexpandpseudoinsts-cpp">AVRExpandPseudoInsts.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
