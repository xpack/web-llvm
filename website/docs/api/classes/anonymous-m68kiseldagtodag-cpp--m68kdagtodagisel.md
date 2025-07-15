---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-m68kiseldagtodag-cpp-/m68kdagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `M68kDAGToDAGISel` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/selectiondagisel">SelectionDAGISel</a> - This is the common base class used for SelectionDAG-based pattern-matching instruction selectors. <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c959eff4e58b8fe36b9b49717f68e0">M68kDAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70b76acd23b6185975ec9730d597c0d">M68kDAGToDAGISel</a> (M68kTargetMachine &amp;TM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae21c8e2b21e8fb9142f8d7f36d966409">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d0983364ce56bbe4d50d55274587c73">IsProfitableToFold</a> (SDValue N, SDNode *U, SDNode *Root) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsProfitableToFold - Returns true if it's profitable to fold the specific operand node N of U during instruction selection that starts at Root. <a href="#a6d0983364ce56bbe4d50d55274587c73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine">M68kTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dd0ba45b7ad4ccdd133abce20bae9ef">getTargetMachine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getTargetMachine - Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>, casted to the target-specific type. <a href="#a2dd0ba45b7ad4ccdd133abce20bae9ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae937cf8d67149b557261c7a735d5fae5">Select</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main hook for targets to transform nodes into machine nodes. <a href="#ae937cf8d67149b557261c7a735d5fae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae55ba2bc2f62dc01e3119725f242d0e5">initGlobalBaseReg</a> (MachineFunction &amp;MF)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc3ec5969d007a7400efc7eb3e607fb6">foldOffsetIntoAddress</a> (uint64_t Offset, M68kISelAddressMode &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c0901795566daeca3b78ed12d23a49">matchLoadInAddress</a> (LoadSDNode *N, M68kISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>TODO Add TLS support. <a href="#ab0c0901795566daeca3b78ed12d23a49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e55d638c23241a9a095aef2454dbb7b">matchAddress</a> (SDValue N, M68kISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified node to the specified addressing mode, returning true if it cannot be done. <a href="#a0e55d638c23241a9a095aef2454dbb7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb883d9ab99f7d6e289832e07311762">matchAddressBase</a> (SDValue N, M68kISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for MatchAddress. <a href="#aacb883d9ab99f7d6e289832e07311762">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a609f48ca47e82986ef9363f5ee6c350f">matchAddressRecursively</a> (SDValue N, M68kISelAddressMode &amp;AM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93c8cd2387236ca98a1f54a65d7fca0b">matchADD</a> (SDValue &amp;N, M68kISelAddressMode &amp;AM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632f73437e641e55dc57bf462d04f2b3">matchWrapper</a> (SDValue N, M68kISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to match <a href="/web-llvm/docs/api/namespaces/llvm/m68kisd/#a5d785b7c28047e4e75d1fed254de7a5eaf0a730a8c230a66750922a4708e16963">M68kISD::Wrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/m68kisd/#a5d785b7c28047e4e75d1fed254de7a5eae5220eb9816fbc61516f67a9d7fbbaeb">M68kISD::WrapperPC</a> nodes into an addressing mode. <a href="#a632f73437e641e55dc57bf462d04f2b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; bool, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb3b8d5ad22bcb62faf4473aa8c67e7">selectNode</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d12069b044be938446eddb2fb67660">SelectARI</a> (SDNode *Parent, SDValue N, SDValue &amp;Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3254f5dde63d4a4432d372504e9e02bf">SelectARIPI</a> (SDNode *Parent, SDValue N, SDValue &amp;Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfa54795d850536ff60ef353f6629867">SelectARIPD</a> (SDNode *Parent, SDValue N, SDValue &amp;Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ac36fde00fc3ebedcf5e9ec62f19da">SelectARID</a> (SDNode *Parent, SDValue N, SDValue &amp;Imm, SDValue &amp;Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5bb0e0a602e1a841d783d4b927e8e7">SelectARII</a> (SDNode *Parent, SDValue N, SDValue &amp;Imm, SDValue &amp;Base, SDValue &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6f44968d2f2c5e65743bc45c6abde0e">SelectAL</a> (SDNode *Parent, SDValue N, SDValue &amp;Sym)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c3f774907a6bf269cb7c771a3aafdf">SelectPCD</a> (SDNode *Parent, SDValue N, SDValue &amp;Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58fbede699e1575cac0a70f202a80cd2">SelectPCI</a> (SDNode *Parent, SDValue N, SDValue &amp;Imm, SDValue &amp;Index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4740c376121a954db7f10ee7eb50d67a">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint. <a href="#a4740c376121a954db7f10ee7eb50d67a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d5933edf2c290f62b98e287d3444fb">getFrameIndexAddress</a> (M68kISelAddressMode &amp;AM, const SDLoc &amp;DL, SDValue &amp;Disp, SDValue &amp;Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f296ef96ecf0e6f39b6b4621e7f53c0">getSymbolicDisplacement</a> (M68kISelAddressMode &amp;AM, const SDLoc &amp;DL, SDValue &amp;Sym)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59a53e0d3a1609b9bacaf682540e4c6">getI8Imm</a> (int64_t Imm, const SDLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target constant with the specified value of type i8. <a href="#aa59a53e0d3a1609b9bacaf682540e4c6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6bc919aa421a218082d0cfb2a3de899">getI16Imm</a> (int64_t Imm, const SDLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target constant with the specified value of type i8. <a href="#af6bc919aa421a218082d0cfb2a3de899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abce4568c47b7cf3f5b64d08f094683">getI32Imm</a> (int64_t Imm, const SDLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target constant with the specified value, of type i32. <a href="#a7abce4568c47b7cf3f5b64d08f094683">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68kinstrinfo">M68kInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9187c5f5b6404d4b22166c6e7ad473f">getInstrInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a>, casted to the target-specific type. <a href="#ad9187c5f5b6404d4b22166c6e7ad473f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a94d8f7febc008eb1e6654a22b690ff">getGlobalBaseReg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that returns the value of the global base register. <a href="#a8a94d8f7febc008eb1e6654a22b690ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget">M68kSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2fb57a5f2a1c256e0e9274be8911886">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget">M68kSubtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#ad2fb57a5f2a1c256e0e9274be8911886">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### M68kDAGToDAGISel() {#a79c959eff4e58b8fe36b9b49717f68e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::M68kDAGToDAGISel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#a6d0983364ce56bbe4d50d55274587c73">IsProfitableToFold</a>.</p>

</div>
</div>

### M68kDAGToDAGISel() {#ae70b76acd23b6185975ec9730d597c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::M68kDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/m68ktargetmachine">M68kTargetMachine</a> &amp; TM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### IsProfitableToFold() {#a6d0983364ce56bbe4d50d55274587c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::IsProfitableToFold (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * U, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root)</td>
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

<p>IsProfitableToFold - Returns true if it's profitable to fold the specific operand node N of U during instruction selection that starts at Root.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="#a6d0983364ce56bbe4d50d55274587c73">IsProfitableToFold</a>, <a href="#a79c959eff4e58b8fe36b9b49717f68e0">M68kDAGToDAGISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a> and <a href="/web-llvm/docs/api/namespaces/llvm/m68kisd/#a5d785b7c28047e4e75d1fed254de7a5ea620f48dc3793e755e23c4a52570a5fe8">llvm::M68kISD::SUB</a>.</p>


<p>Referenced by <a href="#a6d0983364ce56bbe4d50d55274587c73">IsProfitableToFold</a>.</p>

</div>
</div>

### runOnMachineFunction() {#ae21c8e2b21e8fb9142f8d7f36d966409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### foldOffsetIntoAddress() {#adc3ec5969d007a7400efc7eb3e607fb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::foldOffsetIntoAddress (uint64_t Offset, <a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getFrameIndexAddress() {#a13d5933edf2c290f62b98e287d3444fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::getFrameIndexAddress (<a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getGlobalBaseReg() {#a8a94d8f7febc008eb1e6654a22b690ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * M68kDAGToDAGISel::getGlobalBaseReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that returns the value of the global base register.</p>


<p>Output instructions required to initialize the global base register, if necessary.</p>


<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getI16Imm() {#af6bc919aa421a218082d0cfb2a3de899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::getI16Imm (int64_t Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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

<p>Return a target constant with the specified value of type i8.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getI32Imm() {#a7abce4568c47b7cf3f5b64d08f094683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::getI32Imm (int64_t Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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

<p>Return a target constant with the specified value, of type i32.</p>

<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getI8Imm() {#aa59a53e0d3a1609b9bacaf682540e4c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::getI8Imm (int64_t Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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

<p>Return a target constant with the specified value of type i8.</p>

<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getInstrInfo() {#ad9187c5f5b6404d4b22166c6e7ad473f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kInstrInfo * anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::getInstrInfo ()</td>
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

<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a>, casted to the target-specific type.</p>

<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getSymbolicDisplacement() {#a4f296ef96ecf0e6f39b6b4621e7f53c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::getSymbolicDisplacement (<a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Sym)</td>
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



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getTargetMachine() {#a2dd0ba45b7ad4ccdd133abce20bae9ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kTargetMachine &amp; anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::getTargetMachine ()</td>
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

<p>getTargetMachine - Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>, casted to the target-specific type.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### initGlobalBaseReg() {#ae55ba2bc2f62dc01e3119725f242d0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::initGlobalBaseReg (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchADD() {#a93c8cd2387236ca98a1f54a65d7fca0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::matchADD (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; N, <a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchAddress() {#a0e55d638c23241a9a095aef2454dbb7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::matchAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the specified node to the specified addressing mode, returning true if it cannot be done.</p>


<p>This just pattern matches for the addressing mode.</p>


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchAddressBase() {#aacb883d9ab99f7d6e289832e07311762}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::matchAddressBase (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for MatchAddress.</p>


<p>Add the specified node to the specified addressing mode without any further recursion.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchAddressRecursively() {#a609f48ca47e82986ef9363f5ee6c350f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::matchAddressRecursively (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchLoadInAddress() {#ab0c0901795566daeca3b78ed12d23a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::matchLoadInAddress (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * N, <a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>TODO Add TLS support.</p>

<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchWrapper() {#a632f73437e641e55dc57bf462d04f2b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::matchWrapper (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-m68kiseldagtodag-cpp-/m68kiseladdressmode">M68kISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to match <a href="/web-llvm/docs/api/namespaces/llvm/m68kisd/#a5d785b7c28047e4e75d1fed254de7a5eaf0a730a8c230a66750922a4708e16963">M68kISD::Wrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/m68kisd/#a5d785b7c28047e4e75d1fed254de7a5eae5220eb9816fbc61516f67a9d7fbbaeb">M68kISD::WrapperPC</a> nodes into an addressing mode.</p>


<p>These wrap things that will resolve down into a symbol reference. If no match is possible, this returns true, otherwise it returns false.</p>


<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Select() {#ae937cf8d67149b557261c7a735d5fae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void M68kDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Main hook for targets to transform nodes into machine nodes.</p>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectAL() {#ab6f44968d2f2c5e65743bc45c6abde0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectAL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Sym)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectARI() {#ad3d12069b044be938446eddb2fb67660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectARI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectARID() {#af7ac36fde00fc3ebedcf5e9ec62f19da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectARID (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectARII() {#aed5bb0e0a602e1a841d783d4b927e8e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectARII (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectARIPD() {#abfa54795d850536ff60ef353f6629867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectARIPD (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectARIPI() {#a3254f5dde63d4a4432d372504e9e02bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectARIPI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#a4740c376121a954db7f10ee7eb50d67a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
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

<p>SelectInlineAsmMemoryOperand - Select the specified address as a target addressing mode, according to the specified constraint.</p>


<p>If this does not match or is not implemented, return true. The resultant operands (which will appear in the machine instruction) should be added to the OutOps vector.</p>


<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectNode() {#abbb3b8d5ad22bcb62faf4473aa8c67e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; bool, SDNode * &gt; anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::selectNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectPCD() {#af9c3f774907a6bf269cb7c771a3aafdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectPCD (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectPCI() {#a58fbede699e1575cac0a70f202a80cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool M68kDAGToDAGISel::SelectPCI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Subtarget {#ad2fb57a5f2a1c256e0e9274be8911886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const M68kSubtarget* anonymous{M68kISelDAGToDAG.cpp}::M68kDAGToDAGISel::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/m68ksubtarget">M68kSubtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kiseldagtodag-cpp">M68kISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
