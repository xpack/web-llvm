---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PPCDAGToDAGISel` Class Reference

<p><a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel">PPCDAGToDAGISel</a> - <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> specific code to select <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> machine instructions for <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade47c634e1dae4818ebe400c7dfc7a90">PPCDAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28a4d138408c5bf4f436b616a119cf2a">PPCDAGToDAGISel</a> (PPCTargetMachine &amp;tm, CodeGenOptLevel OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3fc21d30eef606c68c9882dd8a97b0">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a734032526577f3bd7808bcc857f35537">PreprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts. <a href="#a734032526577f3bd7808bcc857f35537">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe20d7444c158ac7cb89ae3c2cb5cc55">PostprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PostprocessISelDAG - Perform some late peephole optimizations on the DAG representation. <a href="#afe20d7444c158ac7cb89ae3c2cb5cc55">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b4b13dbc4dc1bd4ec65281216388ada">getI16Imm</a> (unsigned Imm, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getI16Imm - Return a target constant with the specified value, of type i16. <a href="#a0b4b13dbc4dc1bd4ec65281216388ada">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e410b53f6d42671d51b6c11caecd9fd">getI32Imm</a> (unsigned Imm, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getI32Imm - Return a target constant with the specified value, of type i32. <a href="#a7e410b53f6d42671d51b6c11caecd9fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7920006274a32849b4cb9e7df0df53a">getI64Imm</a> (uint64_t Imm, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getI64Imm - Return a target constant with the specified value, of type i64. <a href="#ac7920006274a32849b4cb9e7df0df53a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc3295798fdd4639f3896719ad1cc94">getSmallIPtrImm</a> (int64_t Imm, const SDLoc &amp;dl)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getSmallIPtrImm - Return a target constant of pointer type. <a href="#aedc3295798fdd4639f3896719ad1cc94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac20ef8c91eac038ee0e6bcc32be560f5">getGlobalBaseReg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalBaseReg - insert code into the entry mbb to materialize the PIC base register. <a href="#ac20ef8c91eac038ee0e6bcc32be560f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa88de6884da5fde45eafb9b11fcb3e">selectFrameIndex</a> (SDNode *SN, SDNode *N, int64_t Offset=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main hook for targets to transform nodes into machine nodes. <a href="#a77bc2aad31cb4ad41441222b28c8080c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a377cd94b272a4c49477b765611e4a434">tryBitfieldInsert</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn an or of two masked values into the rotate left word immediate then mask insert (rlwimi) instruction. <a href="#a377cd94b272a4c49477b765611e4a434">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8db0d17fd3b822273f71549f1f9e70a">tryBitPermutation</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5129e150e18937b6123e93990c1c903">tryIntCompareInGPR</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68dfe495fc0800bc00b676bae53711bc">tryTLSXFormLoad</a> (LoadSDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea966a78e9df2ec2b419272c293d000">tryTLSXFormStore</a> (StoreSDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a481200c66d9f275e703dd248449186e4">SelectCC</a> (SDValue LHS, SDValue RHS, ISD::CondCode CC, const SDLoc &amp;dl, SDValue Chain=SDValue())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectCC - Select a comparison of the specified values with the specified condition code, returning the CR# of the expression. <a href="#a481200c66d9f275e703dd248449186e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6e8fc4ecfe9de885837c27e9102491">SelectAddrImmOffs</a> (SDValue N, SDValue &amp;Out) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrImmOffs - Return true if the operand is valid for a preinc immediate field. <a href="#aba6e8fc4ecfe9de885837c27e9102491">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a149a407f65b1895f0dd4a3e27cadd289">SelectDSForm</a> (SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectDSForm - Returns true if address N can be represented by the addressing mode of DSForm instructions (a base register, plus a signed 16-bit displacement that is a multiple of 4. <a href="#a149a407f65b1895f0dd4a3e27cadd289">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6d1f527b6d4e5f0bbfcff1e5576971">SelectDQForm</a> (SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectDQForm - Returns true if address N can be represented by the addressing mode of DQForm instructions (a base register, plus a signed 16-bit displacement that is a multiple of 16. <a href="#acf6d1f527b6d4e5f0bbfcff1e5576971">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28bd480d3b9f6836a2b99766b418f0ef">SelectDForm</a> (SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectDForm - Returns true if address N can be represented by the addressing mode of DForm instructions (a base register, plus a signed 16-bit immediate. <a href="#a28bd480d3b9f6836a2b99766b418f0ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694d03791f9cc383c2fedd9137107bfa">SelectPCRelForm</a> (SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectPCRelForm - Returns true if address N can be represented by PC-Relative addressing mode. <a href="#a694d03791f9cc383c2fedd9137107bfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6fe251b071b9f3290732b4970df81e4">SelectPDForm</a> (SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectPDForm - Returns true if address N can be represented by Prefixed DForm addressing mode (a base register, plus a signed 34-bit immediate. <a href="#aa6fe251b071b9f3290732b4970df81e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fba61fdfae4868d150378d9f41020bc">SelectXForm</a> (SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectXForm - Returns true if address N can be represented by the addressing mode of XForm instructions (an indexed [r+r] operation). <a href="#a6fba61fdfae4868d150378d9f41020bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad355575328b6adde4d94a15146966f19">SelectForceXForm</a> (SDNode *Parent, SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectForceXForm - Given the specified address, force it to be represented as an indexed [r+r] operation (an XForm instruction). <a href="#ad355575328b6adde4d94a15146966f19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d8186c7c451237496285289e500d767">SelectAddrIdx</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrIdx - Given the specified address, check to see if it can be represented as an indexed [r+r] operation. <a href="#a9d8186c7c451237496285289e500d767">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab64aad15e6ca6e1d636c8dba77158137">SelectAddrIdxX4</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrIdx4 - Given the specified address, check to see if it can be represented as an indexed [r+r] operation. <a href="#ab64aad15e6ca6e1d636c8dba77158137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b50976d9722bf4747e8bfca4999eba">SelectAddrIdxX16</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrIdx16 - Given the specified address, check to see if it can be represented as an indexed [r+r] operation. <a href="#ac5b50976d9722bf4747e8bfca4999eba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee86bfe2f1ee82d58ea774a002f39ee">SelectAddrIdxOnly</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrIdxOnly - Given the specified address, force it to be represented as an indexed [r+r] operation. <a href="#a4ee86bfe2f1ee82d58ea774a002f39ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c0a50338d1fb9d7177958ad0cbad701">SelectAddrImm</a> (SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrImm - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement [r+imm]. <a href="#a0c0a50338d1fb9d7177958ad0cbad701">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eff5989d155f6a5dfb3d14351826cc4">SelectAddrImmX4</a> (SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrImmX4 - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement that is a multiple of 4 (last parameter). <a href="#a3eff5989d155f6a5dfb3d14351826cc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca4d74dc26c2823424663e2bc5454540">SelectAddrImmX16</a> (SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrImmX16 - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement that is a multiple of 16(last parameter). <a href="#aca4d74dc26c2823424663e2bc5454540">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c5846b80e7e757ab3abc5bf545f3668">SelectAddrImmX34</a> (SDValue N, SDValue &amp;Disp, SDValue &amp;Base)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectAddrImmX34 - Returns true if the address N can be represented by a base register plus a signed 34-bit displacement. <a href="#a6c5846b80e7e757ab3abc5bf545f3668">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6931f19f358494cec46015be8d440500">SelectAddr</a> (SDValue N, SDValue &amp;Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcbf48892d45d9045a4b43189fab8edc">SelectAddrPCRel</a> (SDValue N, SDValue &amp;Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6182598aaa3c33b0c1e4eb1f7b1ce870">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SelectInlineAsmMemoryOperand - Implement addressing mode selection for inline asm expressions. <a href="#a6182598aaa3c33b0c1e4eb1f7b1ce870">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ef841ae971db8a984191c38136375e">trySETCC</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512f97d4497f3f3a08c9c9539ce3f506">tryFoldSWTestBRCC</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad951a93d0671f78fdbff0c8b77f8493d">trySelectLoopCountIntrinsic</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c2fed3c9aff9c93694648194edb87d">tryAsSingleRLDICL</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27636fb3ee361511e1337221c9400e68">tryAsSingleRLDCL</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83ba0f9e8b206385061004077a8e087">tryAsSingleRLDICR</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94028eb422f5228b7ba9f0fb141072c0">tryAsSingleRLWINM</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa525eca7661e41dc94e4351c6b5c03ac">tryAsSingleRLWINM8</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4a367d439f036ef7f7173cf9894e6b6">tryAsSingleRLWIMI</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc93049acb530a93aa5aedffbe2e4319">tryAsPairOfRLDICL</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b84ae0ccb52e58b27e19d177bf0250">tryAsSingleRLDIMI</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9689d382202cdba60ece7fecf58e2f1d">PeepholePPC64</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2d2df1940ea64203c8a92303a6062a">PeepholePPC64ZExt</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36202a40d9604e382db923ec32047284">PeepholeCROps</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbf2dc8054d476c0d4ff1d623513b2c">combineToCMPB</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf604aea8c741ccf7806f421acf17834">foldBoolExts</a> (SDValue &amp;Res, SDNode *&amp;N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7500f9ddd02a148b55b1b634f3c9c3a">AllUsersSelectZero</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7029225eaf0f0f9e28b02423a29025fa">SwapAllSelectUsers</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73cb863ac0b8ca5e5e5e3e55b54475e5">isOffsetMultipleOf</a> (SDNode *N, unsigned Val) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Does this node represent a load/store node whose address can be represented with a register plus an immediate that's a multiple of <span class="doxyComputerOutput">Val:</span> <a href="#a73cb863ac0b8ca5e5e5e3e55b54475e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5da4fb326c35f173f120a084cc68e545">transferMemOperands</a> (SDNode *N, SDNode *Result)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da35a1078f44239274d63982614f0ad">TM</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget">PPCSubtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8843bb8d60a80a9eb954ea5adcf22a74">Subtarget</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering">PPCTargetLowering</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0bdd87dc5639e31f157a3684d50f253">PPCLowering</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe76d304837723698511612ed3d793d4">GlobalBaseReg</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a678f88e041ed213103cc705ea75323a7">isRotateAndMask</a> (SDNode *N, unsigned Mask, bool isShiftMask, unsigned &amp;SH, unsigned &amp;MB, unsigned &amp;ME)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isRotateAndMask - Returns true if Mask and Shift can be folded into a rotate and mask opcode and mask operation. <a href="#a678f88e041ed213103cc705ea75323a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel">PPCDAGToDAGISel</a> - <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> specific code to select <a href="/web-llvm/docs/api/namespaces/llvm/ppc">PPC</a> machine instructions for <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operations.</p>

<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PPCDAGToDAGISel() {#ade47c634e1dae4818ebe400c7dfc7a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::PPCDAGToDAGISel ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>Referenced by <a href="#ac20ef8c91eac038ee0e6bcc32be560f5">getGlobalBaseReg</a>.</p>

</div>
</div>

### PPCDAGToDAGISel() {#a28a4d138408c5bf4f436b616a119cf2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::PPCDAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/ppctargetmachine">PPCTargetMachine</a> &amp; tm, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getGlobalBaseReg() {#ac20ef8c91eac038ee0e6bcc32be560f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * PPCDAGToDAGISel::getGlobalBaseReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getGlobalBaseReg - insert code into the entry mbb to materialize the PIC base register.</p>


<p>getGlobalBaseReg - Output the instructions required to put the base address to use for accessing globals into a register.</p>


<p>Return the virtual register that holds this value.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineinstrbuilder/#a927857fc69e4b4f0cde307f86f180df5">llvm::MachineInstrBuilder::addReg</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#ab2d91e7bec944efcbc39d8e30644f111">llvm::MachineBasicBlock::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a17e04afcf0c5efeb0eb6a9a45287b5e4">llvm::BuildMI</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/regstate/#ade26fe5c9b3fe6948def36f7ca12dfc5a72c17e2ff2d5af62a30e56ac152aa8d5">llvm::RegState::Define</a>, <a href="#ac20ef8c91eac038ee0e6bcc32be560f5">getGlobalBaseReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad5f691fdc1a09aaf6df5fef958b35a3d">MBBI</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="#ade47c634e1dae4818ebe400c7dfc7a90">PPCDAGToDAGISel</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a303effb01b1d92c71b15cc25b2438917">llvm::SelectionDAGISel::RegInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba930654495acf7b77bcf00f2c65c32347">llvm::PICLevel::SmallPIC</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a530363b25d555de667bf4f23bc6349a6">llvm::SelectionDAGISel::TII</a>.</p>


<p>Referenced by <a href="#ac20ef8c91eac038ee0e6bcc32be560f5">getGlobalBaseReg</a> and <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### getI16Imm() {#a0b4b13dbc4dc1bd4ec65281216388ada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::getI16Imm (unsigned Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>getI16Imm - Return a target constant with the specified value, of type i16.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### getI32Imm() {#a7e410b53f6d42671d51b6c11caecd9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::getI32Imm (unsigned Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>getI32Imm - Return a target constant with the specified value, of type i32.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>, <a href="#a481200c66d9f275e703dd248449186e4">SelectCC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af592a32d6bc2daeb7246699a24c76d8a">selectI64Imm</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#adb196c969d6d3af8de3eeeddf2bb9303">selectI64ImmDirect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#ac75a07531324f76bfb02992249135cfb">selectI64ImmDirectPrefix</a> and <a href="#a377cd94b272a4c49477b765611e4a434">tryBitfieldInsert</a>.</p>

</div>
</div>

### getI64Imm() {#ac7920006274a32849b4cb9e7df0df53a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::getI64Imm (uint64_t Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>getI64Imm - Return a target constant with the specified value, of type i64.</p>

<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>.</p>


<p>Referenced by <a href="#a481200c66d9f275e703dd248449186e4">SelectCC</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#ac75a07531324f76bfb02992249135cfb">selectI64ImmDirectPrefix</a>.</p>

</div>
</div>

### getSmallIPtrImm() {#aedc3295798fdd4639f3896719ad1cc94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::getSmallIPtrImm (int64_t Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl)</td>
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

<p>getSmallIPtrImm - Return a target constant of pointer type.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>.</p>


<p>Referenced by <a href="#aeaa88de6884da5fde45eafb9b11fcb3e">selectFrameIndex</a>.</p>

</div>
</div>

### PostprocessISelDAG() {#afe20d7444c158ac7cb89ae3c2cb5cc55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::PostprocessISelDAG ()</td>
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

<p>PostprocessISelDAG - Perform some late peephole optimizations on the DAG representation.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

### PreprocessISelDAG() {#a734032526577f3bd7808bcc857f35537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::PreprocessISelDAG ()</td>
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

<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a1f4346248feeb9d5c83ce930555936d1">llvm::SDNode::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a0f3fc21d30eef606c68c9882dd8a97b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machineframeinfo/#a1ae307f415a8989475e3f7ddd6eefc8b">llvm::MachineFrameInfo::CreateStackObject</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcsubtarget/#a6c9ac5a1dc657c32bc2999b98bcd7a6b">llvm::PPCSubtarget::getTargetLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/ppcfunctioninfo/#ae21fe4884f2a45dc34039874ddd9594e">llvm::PPCFunctionInfo::setROPProtectionHashSaveIndex</a>.</p>

</div>
</div>

### Select() {#a77bc2aad31cb4ad41441222b28c8080c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a046e97f3becfbef4e0b3e1760a809dca">llvm::PPCISD::ADDI_TLSGD_L_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a41664c9403b22dedab5a78fc8ef07b42">llvm::PPCISD::ADDI_TLSLD_L_ADDR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a320d58aba8e7aee5461dbb44378a83ba">llvm::PPCISD::ANDI_rec_1_EQ_BIT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a2f5e9e30846196a91f11a3e45e802eb7">llvm::PPCISD::ANDI_rec_1_GT_BIT</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a0afb938ef27c63f791a9e76d2c44e057">ANDIGlueBug</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a160ec67350dc5e964fc0a12a9cde1df8">llvm::PPCISD::BDNZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19addb9d78754c1f2e6d765a0da913f0800">llvm::PPCISD::BDZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a6d5e322b263f0d5ea4204efafc1d78bb">llvm::ISD::BR_CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a716765ad6ce5be71f987cd2097b1cdbf">llvm::ISD::BRIND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa09dfd0e28e0ffea73ccfc88fb2fd95c">llvm::PPCISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0ca86fac87a16ac9aa26f6ab3625a5aa">llvm::PPCISD::CALL_RM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a0992940624286ed6bc85cd7163501613">llvm::PPCISD::COND_BRANCH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#abbb93ba85eff4d25fd4c3919fddd779c">DM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a29bd51c0da5455ad260762b9cb116d41">EnableBranchHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#aa95456d21e4f2d841931cac6a7a40c44">EnableTLSOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4b437632fd9b97dd36010d85eb363efe">llvm::ISD::FrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a024d81db0692653f69a019d1c973ebd0">llvm::SelectionDAGISel::FuncInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a44361e635fd7461e3a8eeb7fc9ad4f04">llvm::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a7c6e64fef2ad2ba4052cd8365e97e8d2">llvm::SDNode::getAsZExtVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a9293c2849df988b06fecea7e1b021fee">getBranchHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5d70066b330f0860014d91d4974e56b0">getCodeModel</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a6e6eb8dd01b1658e75c6bc822e60254c">getCRIdxForSetCC</a>, <a href="#ac20ef8c91eac038ee0e6bcc32be560f5">getGlobalBaseReg</a>, <a href="#a0b4b13dbc4dc1bd4ec65281216388ada">getI16Imm</a>, <a href="#a7e410b53f6d42671d51b6c11caecd9fd">getI32Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorsdnode/#a449efebfbf16040c8d5c658f4c891f3f">llvm::ShuffleVectorSDNode::getMaskElt</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a6925b6f3924454060cc817238f2a8f2c">getPredicateForSetCC</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a6b2b8ca5b0fdf6484247d5ae74deb9ff">llvm::SDValue::getValueType</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a9e4500d93af7f70fdff992d9d748559d">llvm::PPCISD::GlobalBaseReg</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a342c0d4e8e59b30daefe9a05bc2098bd">llvm::SDValue::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a29ca9a2c296f3f458f12419d0fad2cc5">hasTocDataAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a2df96794a99f5d3b4415c4a84e616140">llvm::ISD::INTRINSIC_VOID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac771b9cda3b889242d457cc4d9b2159c">llvm::ISD::INTRINSIC_WO_CHAIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a7312dc1e31cba7889c13ff9ada91ff15">isInt64Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a5fa1cb1a1d96ce454ea9056f487d718e">isOpcWithIntImmediate</a>, <a href="#a678f88e041ed213103cc705ea75323a7">isRotateAndMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aae86ddfa346964171caa61f29d46294b">llvm::ISD::isSignedIntSetCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19aa95297a81ed350b1df6d0e322be12e23">llvm::PPCISD::LD_SPLAT</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9ac8e4e13ad96a39c3f8db9ed633ad2baff50b4aa1c9cc2197ef898436641c911">llvm::Lo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269b81f007000306e3e69d0d290c2159">llvm::ISD::LOAD</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#aa5760d31de51afcdd6a97ee28d7d403b">mayUseP9Setb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa29275c05d0afdbda643f7a0fbad83832">llvm::CodeModel::Medium</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a58202903ffe35789bd984f290d83e11f">llvm::PPCISD::MFOCRF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcii/#ae73836094d8b0399ba10a6e540a363ffab055ede9c173349e17e7aada20410b93">llvm::PPCII::MO_PLT</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a4aca2bf0c649ae08d5627e350bb80eb6">Mod</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ad8aec9273962cf78d087090c11a1dd1c">llvm::ISD::MUL</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a75da00c638a1f554457f78c4e2ef7a5c">llvm::PPCISD::PPC32_PICGOT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#abee7ecb577fcade34eb16ccb7f503e31ab5bb854fadd42503c849c4a48d7f3d90">llvm::ISD::PRE_INC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a34be5288a1bb24e5120358395f7f0dc3">llvm::PPC::PRED_EQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a44abec85091b571da2189ac4bd139095">llvm::PPC::PRED_GE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a8cd4d49277068c1eab8d4d7c4835b817">llvm::PPC::PRED_GT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355ac89b6a30c033abb18a7e81f48b0e3593">llvm::PPC::PRED_LE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355a46cd6e935d7b9cc679d9cb0cf025ae91">llvm::PPC::PRED_LT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a14028f7fe73a11dabc6583510cc0a355ad9add708b3d9680d64242cf06f448462">llvm::PPC::PRED_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a4fed17be029140e1e4721aedfa68fa4a">llvm::PPCISD::READ_TIME_BASE</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1200affbcdb869bf32076f90ad9d0eafa67f115c1fddc4ce1aeb1c754001585bc">llvm::Reverse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a99ad6b342b7457df56b91d24e66016b3">llvm::ISD::SELECT_CC</a>, <a href="#a4ee86bfe2f1ee82d58ea774a002f39ee">SelectAddrIdxOnly</a>, <a href="#a481200c66d9f275e703dd248449186e4">SelectCC</a>, <a href="#aeaa88de6884da5fde45eafb9b11fcb3e">selectFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#af592a32d6bc2daeb7246699a24c76d8a">selectI64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0158ee47dfa868be5d28e2cbef70d5d0">llvm::ISD::SETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa2554ef60dc191c6005ba9eecbc9aea0">llvm::CodeModel::Small</a>, <a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6ba930654495acf7b77bcf00f2c65c32347">llvm::PICLevel::SmallPIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19ad78bb5b4a8218f88e112b72fab5d508c">llvm::PPCISD::SRA_ADDZE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a047178c3b2c6a5df40ae22a407b8aca9">llvm::ISD::STORE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a0466b21bfb4f3596e41380d8e2d1956f">llvm::ISD::STRICT_FSETCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c8d07d668872f2176fb34724cd799c4">llvm::ISD::STRICT_FSETCCS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#a92a6b0a9b7228d190b0a7d8ae3ef03c7">SubReg</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac479e53ca98903b1028ec80e12fb0af8">llvm::ISD::TargetConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b8176af163ee944af127081d24f4a2">llvm::ISD::TargetGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa686bcdfaefdfe3f49acbfe6f680bc22d">llvm::CodeModel::Tiny</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a5ac8e8dafc2dd10379a59ceff7b237d6">llvm::PPCISD::TOC_ENTRY</a>, <a href="#a377cd94b272a4c49477b765611e4a434">tryBitfieldInsert</a>, <a href="#aa8db0d17fd3b822273f71549f1f9e70a">tryBitPermutation</a>, <a href="#aa5129e150e18937b6123e93990c1c903">tryIntCompareInGPR</a>, <a href="#a68dfe495fc0800bc00b676bae53711bc">tryTLSXFormLoad</a>, <a href="#a8ea966a78e9df2ec2b419272c293d000">tryTLSXFormStore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ppcisd/#ad1c32e5bb1cb213fb836bc3d221e4f19a63d10572d28760b1a149732cc760628a">llvm::PPCISD::VADD_SPLAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8d8773b28111d8898663d4a0f6223d68">llvm::ISD::VECTOR_SHUFFLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>

</div>
</div>

### SelectAddr() {#a6931f19f358494cec46015be8d440500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddr (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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



<p>Definition at line 373 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrIdx() {#a9d8186c7c451237496285289e500d767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdx (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index)</td>
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

<p>SelectAddrIdx - Given the specified address, check to see if it can be represented as an indexed [r+r] operation.</p>


<p>This is for xform instructions whose associated displacement form is D. The last parameter <span class="doxyComputerOutput">0</span> means associated D form has no requirment for 16 bit signed displacement. Returns false if it can be represented by [r+imm], which are preferred.</p>


<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrIdxOnly() {#a4ee86bfe2f1ee82d58ea774a002f39ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdxOnly (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index)</td>
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

<p>SelectAddrIdxOnly - Given the specified address, force it to be represented as an indexed [r+r] operation.</p>

<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### SelectAddrIdxX16() {#ac5b50976d9722bf4747e8bfca4999eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdxX16 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index)</td>
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

<p>SelectAddrIdx16 - Given the specified address, check to see if it can be represented as an indexed [r+r] operation.</p>


<p>This is for xform instructions whose associated displacement form is DQ. The last parameter <span class="doxyComputerOutput">16</span> means associated DQ form 16 bit signed displacement must be a multiple of 16. Returns false if it can be represented by [r+imm], which are preferred.</p>


<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrIdxX4() {#ab64aad15e6ca6e1d636c8dba77158137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrIdxX4 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index)</td>
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

<p>SelectAddrIdx4 - Given the specified address, check to see if it can be represented as an indexed [r+r] operation.</p>


<p>This is for xform instructions whose associated displacement form is DS. The last parameter <span class="doxyComputerOutput">4</span> means associated DS form 16 bit signed displacement must be a multiple of 4. Returns false if it can be represented by [r+imm], which are preferred.</p>


<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrImm() {#a0c0a50338d1fb9d7177958ad0cbad701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectAddrImm - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement [r+imm].</p>


<p>The last parameter <span class="doxyComputerOutput">0</span> means D form has no requirment for 16 bit signed displacement.</p>


<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrImmOffs() {#aba6e8fc4ecfe9de885837c27e9102491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmOffs (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Out)</td>
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

<p>SelectAddrImmOffs - Return true if the operand is valid for a preinc immediate field.</p>


<p>Note that the operand at this point is already the result of a prior SelectAddressRegImm call.</p>


<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac479e53ca98903b1028ec80e12fb0af8">llvm::ISD::TargetConstant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a87b8176af163ee944af127081d24f4a2">llvm::ISD::TargetGlobalAddress</a>.</p>

</div>
</div>

### SelectAddrImmX16() {#aca4d74dc26c2823424663e2bc5454540}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmX16 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectAddrImmX16 - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement that is a multiple of 16(last parameter).</p>


<p>Suitable for use by STXV and friends.</p>


<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrImmX34() {#a6c5846b80e7e757ab3abc5bf545f3668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmX34 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectAddrImmX34 - Returns true if the address N can be represented by a base register plus a signed 34-bit displacement.</p>


<p>Suitable for use by PSTXVP and friends.</p>


<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrImmX4() {#a3eff5989d155f6a5dfb3d14351826cc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrImmX4 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectAddrImmX4 - Returns true if the address N can be represented by a base register plus a signed 16-bit displacement that is a multiple of 4 (last parameter).</p>


<p>Suitable for use by STD and friends.</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectAddrPCRel() {#abcbf48892d45d9045a4b43189fab8edc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectAddrPCRel (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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



<p>Definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectCC() {#a481200c66d9f275e703dd248449186e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCDAGToDAGISel::SelectCC (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> LHS, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> RHS, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Chain=<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SelectCC - Select a comparison of the specified values with the specified condition code, returning the CR# of the expression.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="#a7e410b53f6d42671d51b6c11caecd9fd">getI32Imm</a>, <a href="#ac7920006274a32849b4cb9e7df0df53a">getI64Imm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a7312dc1e31cba7889c13ff9ada91ff15">isInt64Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a267dbd8fce711ee4a1adc8ee2b42fa0a">llvm::isIntS16Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87e65296f2a6d9570117a852af342764">llvm::isUInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#adb237925346ec53b00d3c82a42311318">llvm::ISD::isUnsignedIntSetCC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac7bb30d4918c1ee9dd208083154e109f">llvm::ISD::SETOGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a31d1e24e08b255d6aa290d67d16ce2c9">llvm::ISD::SETOGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a1febf3bac2f3d7d98ec19f1ff5c385ea">llvm::ISD::SETOLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a20257a4d3833cf88afd42caeaed70dde">llvm::ISD::SETOLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">llvm::ISD::SETUGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">llvm::ISD::SETULE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### SelectDForm() {#a28bd480d3b9f6836a2b99766b418f0ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectDForm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectDForm - Returns true if address N can be represented by the addressing mode of DForm instructions (a base register, plus a signed 16-bit immediate.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda14463e6ffd7cc9fd0b93c79fe4856931">llvm::PPC::AM_DForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectDQForm() {#acf6d1f527b6d4e5f0bbfcff1e5576971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectDQForm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectDQForm - Returns true if address N can be represented by the addressing mode of DQForm instructions (a base register, plus a signed 16-bit displacement that is a multiple of 16.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda40a73e5d0d8196bfe33b2866c06d870d">llvm::PPC::AM_DQForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectDSForm() {#a149a407f65b1895f0dd4a3e27cadd289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectDSForm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectDSForm - Returns true if address N can be represented by the addressing mode of DSForm instructions (a base register, plus a signed 16-bit displacement that is a multiple of 4.</p>

<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdafbe45acde65a4870e22102ab63f4643c">llvm::PPC::AM_DSForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectForceXForm() {#ad355575328b6adde4d94a15146966f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectForceXForm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectForceXForm - Given the specified address, force it to be represented as an indexed [r+r] operation (an XForm instruction).</p>

<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdaaac3056a5c906602555ed94a3636077c">llvm::PPC::AM_XForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### selectFrameIndex() {#aeaa88de6884da5fde45eafb9b11fcb3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::selectFrameIndex (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * SN, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, int64_t Offset=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="#aedc3295798fdd4639f3896719ad1cc94">getSmallIPtrImm</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a295d0b84f4e63438c0edb0021c41d47a">llvm::SDNode::hasOneUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#a6182598aaa3c33b0c1e4eb1f7b1ce870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
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

<p>SelectInlineAsmMemoryOperand - Implement addressing mode selection for inline asm expressions.</p>


<p>It is always correct to compute the value into a register. The case of adding a (possibly relocatable) constant to a register can be improved, but it is wrong to substitute Reg+Reg for Reg in an asm, because the load or store opcode would have to change.</p>


<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a12470fe406d44017d96eab37dd65fc14">llvm::InlineAsm::es</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass/#a32a8b65536822d50171455a6baa81da7">llvm::TargetRegisterClass::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#ade110db5cd02d02d8d11534fa679b52b">llvm::InlineAsm::getMemConstraintName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a6f8f57715090da2632453988d9a1501b">llvm::InlineAsm::m</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0ad95679752134a2d9eb61dbd7b91c4bcc">llvm::InlineAsm::o</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0af09564c9ca56850d4cd6b3319e541aee">llvm::InlineAsm::Q</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a0f36ed1bc17fc1aa97fe291c439a0698">TRI</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a21c2e59531c8710156d34a3c30ac81d5">llvm::InlineAsm::Z</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0ad94eb39b7c5996a928c1d97e2d336207">llvm::InlineAsm::Zy</a>.</p>

</div>
</div>

### SelectPCRelForm() {#a694d03791f9cc383c2fedd9137107bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectPCRelForm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectPCRelForm - Returns true if address N can be represented by PC-Relative addressing mode.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdab748f1b6c866a08f2b1e5a2216e8e73d">llvm::PPC::AM_PCRel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectPDForm() {#aa6fe251b071b9f3290732b4970df81e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectPDForm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectPDForm - Returns true if address N can be represented by Prefixed DForm addressing mode (a base register, plus a signed 34-bit immediate.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcda5615f105433d37ceb5557243c2ff09cb">llvm::PPC::AM_PrefixDForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### SelectXForm() {#a6fba61fdfae4868d150378d9f41020bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectXForm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base)</td>
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

<p>SelectXForm - Returns true if address N can be represented by the addressing mode of XForm instructions (an indexed [r+r] operation).</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/ppc/#a6965a3973aa13b20ebaee31424136dcdaaac3056a5c906602555ed94a3636077c">llvm::PPC::AM_XForm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### tryBitfieldInsert() {#a377cd94b272a4c49477b765611e4a434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryBitfieldInsert (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turn an or of two masked values into the rotate left word immediate then mask insert (rlwimi) instruction.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="#a7e410b53f6d42671d51b6c11caecd9fd">getI32Imm</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad41f0c8cd179d6fb3236c4b00a245153">llvm::isRunOfOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/knownbits/#aba205f553f24c184ea47fc1a6cb56537">llvm::KnownBits::One</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a> and <a href="/web-llvm/docs/api/structs/llvm/knownbits/#ac67bca6c764da76f5e152330d92ed916">llvm::KnownBits::Zero</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### tryBitPermutation() {#aa8db0d17fd3b822273f71549f1f9e70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryBitPermutation (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a19328c462764af5f4699fb1698dad994">llvm::ISD::BSWAP</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantsdnode/#a75d113cb1b8cc3c14b601d928dccee40">llvm::ConstantSDNode::getSExtValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a1369b25b7c783991e2fe2dd0f462dd4b">UseBitPermRewriter</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### tryIntCompareInGPR() {#aa5129e150e18937b6123e93990c1c903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryIntCompareInGPR (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#abc05a2c90af0bfe474b0e38a7bf51732">CmpInGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/integercompareeliminator/#a09fe3134a2922596d0704bf13f38560d">anonymous{PPCISelDAGToDAG.cpp}::IntegerCompareEliminator::Select</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### tryTLSXFormLoad() {#a68dfe495fc0800bc00b676bae53711bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryTLSXFormLoad (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a26ac022a6476b64058ee229046f54034">canOptimizeTLSDFormToXForm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7a6c61b6125c7901c549f90ee0e443a770">llvm::ISD::SEXTLOAD</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

### tryTLSXFormStore() {#a8ea966a78e9df2ec2b419272c293d000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryTLSXFormStore (<a href="/web-llvm/docs/api/classes/llvm/storesdnode">StoreSDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a26ac022a6476b64058ee229046f54034">canOptimizeTLSDFormToXForm</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a6a81c1cc06a00a0096d839032b5984e9">llvm::EVT::getSimpleVT</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#acd1bcf7bcbb18b94234b2bf5a505e925">llvm::SelectionDAGISel::ReplaceNode</a> and <a href="/web-llvm/docs/api/classes/llvm/mvt/#a27bda7d8e8e4f0337650a892f3c9b46a">llvm::MVT::SimpleTy</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AllUsersSelectZero() {#af7500f9ddd02a148b55b1b634f3c9c3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::AllUsersSelectZero (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### combineToCMPB() {#a6fbf2dc8054d476c0d4ff1d623513b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue PPCDAGToDAGISel::combineToCMPB (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### foldBoolExts() {#adf604aea8c741ccf7806f421acf17834}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::foldBoolExts (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Res, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *&amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isOffsetMultipleOf() {#a73cb863ac0b8ca5e5e5e3e55b54475e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::isOffsetMultipleOf (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Does this node represent a load/store node whose address can be represented with a register plus an immediate that's a multiple of <span class="doxyComputerOutput">Val:</span></p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PeepholeCROps() {#a36202a40d9604e382db923ec32047284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::PeepholeCROps ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PeepholePPC64() {#a9689d382202cdba60ece7fecf58e2f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::PeepholePPC64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PeepholePPC64ZExt() {#a3a2d2df1940ea64203c8a92303a6062a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::PeepholePPC64ZExt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SwapAllSelectUsers() {#a7029225eaf0f0f9e28b02423a29025fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::SwapAllSelectUsers (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### transferMemOperands() {#a5da4fb326c35f173f120a084cc68e545}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PPCDAGToDAGISel::transferMemOperands (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsPairOfRLDICL() {#afc93049acb530a93aa5aedffbe2e4319}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsPairOfRLDICL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsSingleRLDCL() {#a27636fb3ee361511e1337221c9400e68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsSingleRLDCL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsSingleRLDICL() {#ab0c2fed3c9aff9c93694648194edb87d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsSingleRLDICL (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsSingleRLDICR() {#aa83ba0f9e8b206385061004077a8e087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsSingleRLDICR (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsSingleRLDIMI() {#aa7b84ae0ccb52e58b27e19d177bf0250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsSingleRLDIMI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsSingleRLWIMI() {#aa4a367d439f036ef7f7173cf9894e6b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsSingleRLWIMI (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsSingleRLWINM() {#a94028eb422f5228b7ba9f0fb141072c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsSingleRLWINM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryAsSingleRLWINM8() {#aa525eca7661e41dc94e4351c6b5c03ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryAsSingleRLWINM8 (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryFoldSWTestBRCC() {#a512f97d4497f3f3a08c9c9539ce3f506}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::tryFoldSWTestBRCC (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### trySelectLoopCountIntrinsic() {#ad951a93d0671f78fdbff0c8b77f8493d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::trySelectLoopCountIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### trySETCC() {#ad4ef841ae971db8a984191c38136375e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::trySETCC (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### GlobalBaseReg {#abe76d304837723698511612ed3d793d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::GlobalBaseReg = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### PPCLowering {#af0bdd87dc5639e31f157a3684d50f253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCTargetLowering* anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::PPCLowering = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Subtarget {#a8843bb8d60a80a9eb954ea5adcf22a74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCSubtarget* anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::Subtarget = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### TM {#a7da35a1078f44239274d63982614f0ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PPCTargetMachine&amp; anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::TM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isRotateAndMask() {#a678f88e041ed213103cc705ea75323a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PPCDAGToDAGISel::isRotateAndMask (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned Mask, bool isShiftMask, unsigned &amp; SH, unsigned &amp; MB, unsigned &amp; ME)</td>
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

<p>isRotateAndMask - Returns true if Mask and Shift can be folded into a rotate and mask opcode and mask operation.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armiseldagtodag-cpp/#a7c97deb23c9a669470b42d2bd2e99f19">isInt32Immediate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad41f0c8cd179d6fb3236c4b00a245153">llvm::isRunOfOnes</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>.</p>


<p>Referenced by <a href="#a77bc2aad31cb4ad41441222b28c8080c">Select</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp">PPCISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
