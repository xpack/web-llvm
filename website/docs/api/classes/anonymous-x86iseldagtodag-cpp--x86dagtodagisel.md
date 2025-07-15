---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `X86DAGToDAGISel` Class Reference

<p>ISel - X86-specific code to select <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> machine instructions for <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operations. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ddaf89607cb63627908bb7018fd2ab2">X86DAGToDAGISel</a> ()=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefc52543c379b0bf5228f7aef22bff3c">X86DAGToDAGISel</a> (X86TargetMachine &amp;tm, CodeGenOptLevel OptLevel)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6f9a29ad172e38128860440cfd020b">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f6751ada1a6564d1346804078dfa6f1">emitFunctionEntryCode</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d5b4f84c3dda985bea36681d13bc55b">IsProfitableToFold</a> (SDValue N, SDNode *U, SDNode *Root) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsProfitableToFold - Returns true if it's profitable to fold the specific operand node N of U during instruction selection that starts at Root. <a href="#a6d5b4f84c3dda985bea36681d13bc55b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621eb8645a9f80882b80ac3c6d4e0091">PreprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PreprocessISelDAG - This hook allows targets to hack on the graph before instruction selection starts. <a href="#a621eb8645a9f80882b80ac3c6d4e0091">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5cb58b25423e45192ae938233ae4eae">PostprocessISelDAG</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#aa5cb58b25423e45192ae938233ae4eae">PostprocessISelDAG()</a> - This hook allows the target to hack on the graph right after selection. <a href="#aa5cb58b25423e45192ae938233ae4eae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbfa18f7fed751a6a8e4189d791785fb">Select</a> (SDNode *N) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Main hook for targets to transform nodes into machine nodes. <a href="#afbfa18f7fed751a6a8e4189d791785fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acedd7af0baa021e98cc7ef004a136a54">foldOffsetIntoAddress</a> (uint64_t Offset, X86ISelAddressMode &amp;AM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc76bdb6c3ca60508ac97660a2d30373">matchLoadInAddress</a> (LoadSDNode *N, X86ISelAddressMode &amp;AM, bool AllowSegmentRegForX32=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c6c5baf359f326178578f1288fbc0f3">matchWrapper</a> (SDValue N, X86ISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to match <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac52ade4e38c09090c08d423e886cb4b2">X86ISD::Wrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf9b840077b4580ddbfd3bf992fe359eb">X86ISD::WrapperRIP</a> nodes into an addressing mode. <a href="#a9c6c5baf359f326178578f1288fbc0f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6467d39e11b199823c9d3c584e07860e">matchAddress</a> (SDValue N, X86ISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add the specified node to the specified addressing mode, returning true if it cannot be done. <a href="#a6467d39e11b199823c9d3c584e07860e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9099e8919452dec4f53ebc2cc8d7466c">matchVectorAddress</a> (SDValue N, X86ISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for selectVectorAddr. <a href="#a9099e8919452dec4f53ebc2cc8d7466c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09964fd12c831a227aedcb3b2ecf081a">matchAdd</a> (SDValue &amp;N, X86ISelAddressMode &amp;AM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a73cd86e045301d83f4cdab017ec797">matchIndexRecursively</a> (SDValue N, X86ISelAddressMode &amp;AM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82fe8159f1acbf8d8e20b5e90fe3fbde">matchAddressRecursively</a> (SDValue N, X86ISelAddressMode &amp;AM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227d9460eeac058f40ed26c914d750b3">matchVectorAddressRecursively</a> (SDValue N, X86ISelAddressMode &amp;AM, unsigned Depth)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd152f633435b2d49b6655b9f9d151f">matchAddressBase</a> (SDValue N, X86ISelAddressMode &amp;AM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper for MatchAddress. <a href="#afcd152f633435b2d49b6655b9f9d151f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1c28e3aa8a4e42b1f3bb618d3b7d7e">selectAddr</a> (SDNode *Parent, SDValue N, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if it is able to pattern match an addressing mode. <a href="#a8c1c28e3aa8a4e42b1f3bb618d3b7d7e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2460b24ca719a462839d77e8e42d43">selectVectorAddr</a> (MemSDNode *Parent, SDValue BasePtr, SDValue IndexOp, SDValue ScaleOp, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac265ca7cd95f8e5016e1d6647e358ec8">selectMOV64Imm32</a> (SDValue N, SDValue &amp;Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6f9e126f39184489b148d996574481c">selectLEAAddr</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calls SelectAddr and determines if the maximal addressing mode it matches can be cost effectively emitted as an LEA instruction. <a href="#ac6f9e126f39184489b148d996574481c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b50deaf13946d7c809b37619dd5d8c8">selectLEA64_32Addr</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a9c21dc962cf3919c68c0ba8c3bcaa">selectTLSADDRAddr</a> (SDValue N, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is only run on TargetGlobalTLSAddress nodes. <a href="#a17a9c21dc962cf3919c68c0ba8c3bcaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8905e98551f1d38cc9137e20068af2">selectRelocImm</a> (SDValue N, SDValue &amp;Op)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5a84a479dd628c41b7a89dba6d438c">tryFoldLoad</a> (SDNode *Root, SDNode *P, SDValue N, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560493b67b7f664ee10cfa081f0fb191">tryFoldLoad</a> (SDNode *P, SDValue N, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae32113f788d6d00e89d7fd3a5c931b">tryFoldBroadcast</a> (SDNode *Root, SDNode *P, SDValue N, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24a490cf63602b9ee6bde9cb542cc27">isProfitableToFormMaskedOp</a> (SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5dfcb3a444cde7e3cd0cbb818f2c17">SelectInlineAsmMemoryOperand</a> (const SDValue &amp;Op, InlineAsm::ConstraintCode ConstraintID, std::vector&lt; SDValue &gt; &amp;OutOps) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement addressing mode selection for inline asm expressions. <a href="#a2f5dfcb3a444cde7e3cd0cbb818f2c17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74720ca4a8eb4c4a9af343fbc8ad878">emitSpecialCodeForMain</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit any code that needs to be executed only in the main function. <a href="#af74720ca4a8eb4c4a9af343fbc8ad878">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc758f62b124b0547938ac90f90136f1">getAddressOperands</a> (X86ISelAddressMode &amp;AM, const SDLoc &amp;DL, MVT VT, SDValue &amp;Base, SDValue &amp;Scale, SDValue &amp;Index, SDValue &amp;Disp, SDValue &amp;Segment)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f0782fd19d79c556c2b3a7ddce8c1e">isAMXSDNode</a> (SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57976737685c40737f5613ed2b092dbe">shouldAvoidImmediateInstFormsForSize</a> (SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01db83936fe90eb23a650dbe3574b57f">getI8Imm</a> (unsigned Imm, const SDLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target constant with the specified value of type i8. <a href="#a01db83936fe90eb23a650dbe3574b57f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ce4fd37a4a2249fe59b9607c9d6457a">getI32Imm</a> (unsigned Imm, const SDLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target constant with the specified value, of type i32. <a href="#a6ce4fd37a4a2249fe59b9607c9d6457a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0174a2eb27c09f859f819c0cf29da425">getI64Imm</a> (uint64_t Imm, const SDLoc &amp;DL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a target constant with the specified value, of type i64. <a href="#a0174a2eb27c09f859f819c0cf29da425">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa794bd08e54931f96c70f2ac13bceab9">getExtractVEXTRACTImmediate</a> (SDNode *N, unsigned VecWidth, const SDLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1a216989debc9adcfa1e228e2520c5">getInsertVINSERTImmediate</a> (SDNode *N, unsigned VecWidth, const SDLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2021311a67a00deee7bc40ce673736d8">getPermuteVINSERTCommutedImmediate</a> (SDNode *N, unsigned VecWidth, const SDLoc &amp;DL)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2296a0705f763fd8f5a356ab457493">getSBBZero</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c34b77046a12b39dddda9331f76b651">isUnneededShiftMask</a> (SDNode *N, unsigned Width) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af26347fb23f94e0afc5cc388f4651c1f">getGlobalBaseReg</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that returns the value of the global base register. <a href="#af26347fb23f94e0afc5cc388f4651c1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a509ec8a03e6ff667a14b4c82c5d46ec5">getTargetMachine</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>, casted to the target-specific type. <a href="#a509ec8a03e6ff667a14b4c82c5d46ec5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo">X86InstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d7d34de426cfb9bad7eb012ac21a968">getInstrInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a>, casted to the target-specific type. <a href="#a3d7d34de426cfb9bad7eb012ac21a968">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2e">X86::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa84da6100f3dc325a7560820be135ce4">getCondFromNode</a> (SDNode *N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a condition code of the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>. <a href="#aa84da6100f3dc325a7560820be135ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2c92787bb8987fffd1102481e28cba">ComplexPatternFuncMutatesDAG</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Address-mode matching performs shift-of-and to and-of-shift reassociation in order to expose more scaled addressing opportunities. <a href="#a5e2c92787bb8987fffd1102481e28cba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a196a4eca29e3c3413d2316b1f3d63925">isSExtAbsoluteSymbolRef</a> (unsigned Width, SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c685d60c5f80c63570cc552bd94e41">useNonTemporalLoad</a> (LoadSDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4447c36bc068cd850ae230eab490e4c">foldLoadStoreIntoMemOperand</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinesdnode">MachineSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad18fbe8c412dfd546613c156e68022d8">matchBEXTRFromAndImm</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd0e308ed42ab7199239eee3057ebed">matchBitExtract</a> (SDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b54a535a36a2d55ecddf562acf3b41">shrinkAndImmediate</a> (SDNode *N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the high bits of an 'and' operand are known zero, try setting the high bits of an 'and' constant operand to produce a smaller encoding by creating a small, sign-extended negative immediate rather than a large positive one. <a href="#a53b54a535a36a2d55ecddf562acf3b41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8321b2d6e800fee6d182724b099f9a08">isMaskZeroExtended</a> (SDNode *N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb92c06b25ebb31f36d350bd30e3d845">tryShiftAmountMod</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55baaa176e9af18b2b34beafb8ae6af">tryShrinkShlLogicImm</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9093da995f9b7c83ce07cf33ed6ed9">tryVPTERNLOG</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0480b86904bb1b0a853a30c377841127">matchVPTERNLOG</a> (SDNode *Root, SDNode *ParentA, SDNode *ParentB, SDNode *ParentC, SDValue A, SDValue B, SDValue C, uint8_t Imm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d18caa995fc388031553afd3c5c6a62">tryVPTESTM</a> (SDNode *Root, SDValue Setcc, SDValue Mask)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad49e6385edef89b1775d16113c825a83">tryMatchBitSelect</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinesdnode">MachineSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434b81d101318dbf7cc6c713f2f92b11">emitPCMPISTR</a> (unsigned ROpc, unsigned MOpc, bool MayFoldLoad, const SDLoc &amp;dl, MVT VT, SDNode *Node)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinesdnode">MachineSDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa84054ba554ddfcf082b55d24cd16141">emitPCMPESTR</a> (unsigned ROpc, unsigned MOpc, bool MayFoldLoad, const SDLoc &amp;dl, MVT VT, SDNode *Node, SDValue &amp;InGlue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb73900c7b0e70e434012cbe626f637a">tryOptimizeRem8Extend</a> (SDNode *N)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad498b953a8737b493705041627b314a0">onlyUsesZeroFlag</a> (SDValue Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the given <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa23260aedef0a54d543d227e57955c652">X86ISD::CMP</a> node has any users that use a flag other than ZF. <a href="#ad498b953a8737b493705041627b314a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ebf70d71264b183887eb913d651d01d">hasNoSignFlagUses</a> (SDValue Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the given <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa23260aedef0a54d543d227e57955c652">X86ISD::CMP</a> node has any uses which require the SF flag to be accurate. <a href="#a6ebf70d71264b183887eb913d651d01d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d922148137ea06549c142e3513a9195">hasNoCarryFlagUses</a> (SDValue Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether the given node which sets flags has any uses which require the CF flag to be accurate. <a href="#a1d922148137ea06549c142e3513a9195">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73d48dbcc262d10da1e02281a124e79">Subtarget</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets. <a href="#ac73d48dbcc262d10da1e02281a124e79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d32322e483f6cbfe23347d327c4b19">OptForMinSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, selector should try to optimize for minimum code size. <a href="#ae0d32322e483f6cbfe23347d327c4b19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f7548b2f66263002e910939bdc9f19">IndirectTlsSegRefs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable direct TLS access through segment registers. <a href="#a83f7548b2f66263002e910939bdc9f19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>ISel - X86-specific code to select <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> machine instructions for <a href="/web-llvm/docs/api/classes/llvm/selectiondag">SelectionDAG</a> operations.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### X86DAGToDAGISel() {#a7ddaf89607cb63627908bb7018fd2ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::X86DAGToDAGISel ()</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### X86DAGToDAGISel() {#aefc52543c379b0bf5228f7aef22bff3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::X86DAGToDAGISel (<a href="/web-llvm/docs/api/classes/llvm/x86targetmachine">X86TargetMachine</a> &amp; tm, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#aeac54a65abd3a93279e58b0f474028fc">llvm::SelectionDAGISel::SelectionDAGISel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitFunctionEntryCode() {#a0f6751ada1a6564d1346804078dfa6f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DAGToDAGISel::emitFunctionEntryCode ()</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>.</p>

</div>
</div>

### IsProfitableToFold() {#a6d5b4f84c3dda985bea36681d13bc55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::IsProfitableToFold (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * U, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root)</td>
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

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa72deaddfd41882e7ddf09409d9528bc8">llvm::X86ISD::ADC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aacf42ecbf82f3dcbf52c109ee0e3f5838">llvm::X86ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8957fd90a0c765af6746fb0849ee1a8a">llvm::X86ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a23f2f5947fc429aff1270651c6d019ea">llvm::SDNode::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#ae779a9d142e6318d8fb0e4f0da32af0f">llvm::SDValue::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdnode/#a8388f666d6e735f35837ad03ed1f7a7a">llvm::SDNode::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#aaac3e239cbdfe15a8e9bad4f8e1e3a95">llvm::ISD::isBuildVectorAllZeros</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac926ae0b6871c2207db3e787f6dbcb80">llvm::isOneConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a1c861a21f795c3108ab690f3a45c881a">llvm::SDValue::isUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf362e78ded62dc71fd125ff7f8099475">llvm::X86ISD::OR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae8f8f81d8e8d7a557d67622c05786f1d">llvm::ISD::ROTL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa5d99076d052295315dc1e2dd067d2ad7">llvm::X86ISD::SBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa4affb47abdfdd54079d5a2f8c1d3e628">llvm::X86ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110afc9ad7857b7faf49dcde3dcf434e22a6">llvm::ISD::TargetGlobalTLSAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0f1e3ed26108fec69eb97209c0e39bf">llvm::ISD::UADDO_CARRY</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac52ade4e38c09090c08d423e886cb4b2">llvm::X86ISD::Wrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa483bad339c6126c64687d14c10979979">llvm::X86ISD::XOR</a>.</p>

</div>
</div>

### PostprocessISelDAG() {#aa5cb58b25423e45192ae938233ae4eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DAGToDAGISel::PostprocessISelDAG ()</td>
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

<p><a href="#aa5cb58b25423e45192ae938233ae4eae">PostprocessISelDAG()</a> - This hook allows the target to hack on the graph right after selection.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#ad48a3e977806261e0588099aea7e62a2">CASE</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#ad54233529ff66a30ae425613b6de5545">CASE_ND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead5bbb0f8b7dfd268d7ca01219b5ec3aa">llvm::X86II::EncodingMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea1224cf85d21a6023de72b90c2f225241">llvm::X86II::EVEX</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a9b4ec914400b58abea5b003fe772c7f0">FROM_TO</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#adef073885c881f48920ff6a8b4b36163">llvm::SDValue::getMachineOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a977e54da724d62e7b08e2ad69723731e">llvm::SDValue::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a75627d4da511ed986e105457709de4ae">llvm::SDValue::isMachineOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a84e771c0f56c984d8ee4a85c0cb46ed3">llvm::SelectionDAGISel::ReplaceUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec7c967a5416fa6e154433965357a50ea0cbc6611f5540bd0809a388dc95a615b">llvm::Test</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a0ead78650333eefc4d5591ca3db9ed4b">llvm::SelectionDAGISel::TM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6702853ec24d45d810d71e321eb9e256">llvm::X86II::VEX</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6bfb2e744793a1d413a8890afedb2503">llvm::X86II::XOP</a>.</p>

</div>
</div>

### PreprocessISelDAG() {#a621eb8645a9f80882b80ac3c6d4e0091}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DAGToDAGISel::PreprocessISelDAG ()</td>
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

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a269996b43a1f3e1d1f84a70fd4387535">llvm::ISD::ADD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af14335020a68db7b9f722810e4a05180a421c6b20238e6e6585270538188f15b9">llvm::AllOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac513a7da1bf74fb3e3c594da8534f2d2">llvm::ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8957fd90a0c765af6746fb0849ee1a8a">llvm::X86ISD::AND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aae1624a99d3ee1309539c25a7afe2a852">llvm::X86ISD::ANDNP</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a27d5d8ef82302b739ba3ca8be1a5513d">llvm::ISD::ANY_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aaa275bf149ab5df1067cfb721936ecbc">llvm::ISD::ANY_EXTEND_VECTOR_INREG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa249e11d47119ca5c2666008857b3b534">llvm::X86ISD::BLENDV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8e74b6dccfb024d3f1f6dc71554e5513">llvm::X86ISD::CALL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a0351571482fea42a3b326147fb2ce9e2">llvm::EVT::changeVectorElementTypeToInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110aac2f0a84dd2aa5ee4c3f1385e9565f5e">llvm::ISD::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a2b37615f95f3e2fdd5564188c0965132">llvm::SelectionDAGISel::CurDAG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa873eda45cff31b9f5fe7af33ed2ec407">llvm::X86ISD::CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac6c8013c7f060d7023eb23cb32fc14c8">llvm::X86ISD::CVTTP2UI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ad4d48171b87ca51ff54c10a436bac4d7afab3fffd153f7d7770fed81272e4b78f">llvm::ISD::EXTLOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9070de8a5c5b71851732c4c54e2ffedf">llvm::ISD::EXTRACT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9329e79f62e9ab9b41cfbcafd314bcbd">llvm::ISD::EXTRACT_VECTOR_ELT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaed927d0ca1203766de671e7437d658b2">llvm::X86ISD::FAND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa97670c93c4c4e70151c63e534993e04a">llvm::X86ISD::FANDN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaa84fca900d9cdc9761f9e0f00d386b1e">llvm::X86ISD::FLD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaabe3cfcecab0e3b2e2ab496a566c8d1c">llvm::X86ISD::FOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adaf9a3cb5c2ef5eb713bd6bf4ae23aeb">llvm::ISD::FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac3f8f8d8437c64b2e2e9f978e2707210">llvm::ISD::FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a71640703ec096a8b07111e85cfff6987">llvm::ISD::FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa01d97a3473a8e41bf1dcc6ba3ea8c7eb">llvm::X86ISD::FST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa72b53026518573189b8a49ae5f5c2c2d">llvm::X86ISD::FXOR</a>, <a href="/web-llvm/docs/api/structs/llvm/machinepointerinfo/#ad8ce1aee13dbdcc05d20284a30e83170">llvm::MachinePointerInfo::getFixedStack</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#ae27319d06893854787961adf27b4d1a5">llvm::MVT::getHalfNumVectorElementsVT</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a2b08aa629a6326d1a0444ee6d477c39d">llvm::SDValue::getNode</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aea8bc2b59cb3fa833eb7895a3a216abd">llvm::MVT::getScalarType</a>, <a href="/web-llvm/docs/api/structs/llvm/evt/#a45e76d44a189e456d52e37ba3dda0fce">llvm::EVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a7be7c6dd92efc0d6f866d4a3b433eed0">llvm::MVT::getSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/sdvalue/#a64932427432abeb61241e98bea167580">llvm::SDValue::getValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a1eb420ba23c865af3024a336e491b983">llvm::MVT::getVectorMinNumElements</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86indirectbranchtracking-cpp/#a7cc1126e58ce31289690eca03dbe58c6">IndirectBranchTracking</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1617abaedbb1d902bb3a5b3136684f9c">llvm::ISD::INSERT_SUBVECTOR</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a0c1ae89f2c2765a979f999ecdc11304c">llvm::MVT::is128BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a9e3e2c5a531a6ff555d5302ba1745357">llvm::MVT::is256BitVector</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a776c0f4551869d18e571ae4e87583d86">llvm::MVT::is512BitVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#ac0a91fd2157f9b3a8880ce8373396108">isCalleeLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ae914ecbf92d09be7f8da203ec3dd5bbc">llvm::X86::isConstantSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#ae0dcfa85cc51fcda3c569bf1a638ddee">isEndbrImm64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#afaaeadcd82b42fc0d385a6247bf7bb52">llvm::ISD::isNormalLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aea5f26deda5ef97e02f6afc57c0c3920">llvm::APInt::isOne</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ab32d538e8058be86b0efc0d970b35735">llvm::X86TargetLowering::isScalarFPTypeInSSEReg</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a425636b56fa037ed7b19ef7f9de30df9">llvm::MVT::isVector</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#aafd16108bb2bfb19eed47e23dcbee3dd">llvm::X86::mayFoldLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2dda7d12be6206e5b0026c71bbcd5cb76494">llvm::MachineMemOperand::MOLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/machinememoperand/#aaa2020e47e35179234b9ea27d555b2ddaed357b1367bc90a56fefa4d1b0e17374">llvm::MachineMemOperand::MOStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a68ec2b2ff4e5854ccb107f08d0de92b0">moveBelowOrigChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp/#a2b9692b3adbae20b870650d5bf40427a">needBWI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a5386ceeb71599848944185c0035e0e94">llvm::SelectionDAGISel::OptLevel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a7415ab9f2172c59a2ee7c7a02afa56a4">llvm::ISD::OR</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a576080a08ef1bbab0308eac9d5838f75">llvm::ISD::SCALAR_TO_VECTOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a51cb24bd3e700fcf2f93d1afbb555a16">SDValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a8cc94e03dea594863073a02f5bb94997">llvm::ISD::SHL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a5183f3d72924bc7c77ba8d3f5de9f602">llvm::ISD::SIGN_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a4a055321c361a0f6ee77ed764730ffc1">llvm::ISD::SRA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a3c6553c8acebe1b57c211ee45e2d8f98">llvm::ISD::SRL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa64a6fc099c65248a3deba44a57f1d99f">llvm::X86ISD::STRICT_CVTTP2SI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa40f22ea742439c6dddbfe08b02d48331">llvm::X86ISD::STRICT_CVTTP2UI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a1fb1e48394636004fd75f5916f0d730f">llvm::ISD::STRICT_FCEIL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab74cbb3933c5f5d2cc90d299836c05cc">llvm::ISD::STRICT_FFLOOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ae463c3e40819d6e9de30d7d858867ef4">llvm::ISD::STRICT_FNEARBYINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac47e026e409ff39f319cbb3b096863e6">llvm::ISD::STRICT_FP_EXTEND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2273d9cd04ba6e4a7c1a4b28ab1aaba">llvm::ISD::STRICT_FP_ROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ac2618c1a69fa9d62427a5a6dc43e24ed">llvm::ISD::STRICT_FP_TO_SINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110abf955b4b70f63865e022c329d1775579">llvm::ISD::STRICT_FP_TO_UINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110af57a22f2843a1c3a79d17350945ede58">llvm::ISD::STRICT_FRINT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab7d5c27c800b79a02a1492f1965af72f">llvm::ISD::STRICT_FROUNDEVEN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a883c1084962f12018ca0fe3e1222fa7d">llvm::ISD::STRICT_FTRUNC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aab12f350653f681354125c5f9a97c6bab">llvm::X86ISD::STRICT_VFPROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa53be739a3b69a5d27e1a521ebcad8029">llvm::X86ISD::STRICT_VRNDSCALE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a9fa617e5567c3c2638938f7b9ddc3f1c">llvm::ISD::SUB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaaa37a4cc02090ea86d2448dc9d967d75">llvm::X86ISD::TC_RETURN</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a1ed864be04c93653277b0f5112a4f305">llvm::SelectionDAGISel::TLI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac3bc043916fd84786c2ac451e0a3cd24">llvm::X86ISD::VBROADCAST</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa78f74c46439b34ecc3b826e4bb5f1fc2">llvm::X86ISD::VBROADCAST_LOAD</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa931754702331756731a26916aebb794c">llvm::X86ISD::VFPROUND</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa2a83b0801da091b55c27832f5ad62959">llvm::X86ISD::VPTERNLOG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaaa13b769dd360fbb653f40a94a006bc4">llvm::X86ISD::VRNDSCALE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110ab0b7d2c769fd0fbaab3c4a2fc8e7ea0c">llvm::ISD::VSELECT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa8a2fc33ce2fe41ef2d20854eda49a4f6">llvm::X86ISD::VSHLV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa7b2c246cb3a5d3513041dab6a32b2901">llvm::X86ISD::VSRAV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa1e837f978c72eafaf138c1b0a7b6cddf">llvm::X86ISD::VSRLV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a92febb83e6ba116eb7aae8e7e3f70cc1">llvm::ISD::XOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110adf7f4fc30c272a1987e075d7470df84c">llvm::ISD::ZERO_EXTEND_VECTOR_INREG</a>.</p>

</div>
</div>

### runOnMachineFunction() {#a0c6f9a29ad172e38128860440cfd020b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#a23107e32342f5488a5edfa71aff54700">llvm::SelectionDAGISel::MF</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagisel/#af17ffaab7d809b7d56e212a46f26f1a2">llvm::SelectionDAGISel::runOnMachineFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### ComplexPatternFuncMutatesDAG() {#a5e2c92787bb8987fffd1102481e28cba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::ComplexPatternFuncMutatesDAG ()</td>
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

<p>Address-mode matching performs shift-of-and to and-of-shift reassociation in order to expose more scaled addressing opportunities.</p>

<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### emitPCMPESTR() {#aa84054ba554ddfcf082b55d24cd16141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSDNode * X86DAGToDAGISel::emitPCMPESTR (unsigned ROpc, unsigned MOpc, bool MayFoldLoad, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; InGlue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### emitPCMPISTR() {#a434b81d101318dbf7cc6c713f2f92b11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSDNode * X86DAGToDAGISel::emitPCMPISTR (unsigned ROpc, unsigned MOpc, bool MayFoldLoad, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; dl, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 598 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### emitSpecialCodeForMain() {#af74720ca4a8eb4c4a9af343fbc8ad878}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DAGToDAGISel::emitSpecialCodeForMain ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit any code that needs to be executed only in the main function.</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### foldLoadStoreIntoMemOperand() {#ab4447c36bc068cd850ae230eab490e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::foldLoadStoreIntoMemOperand (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### foldOffsetIntoAddress() {#acedd7af0baa021e98cc7ef004a136a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::foldOffsetIntoAddress (uint64_t Offset, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getAddressOperands() {#acc758f62b124b0547938ac90f90136f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getAddressOperands (<a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> VT, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getCondFromNode() {#aa84da6100f3dc325a7560820be135ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode X86DAGToDAGISel::getCondFromNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a condition code of the given <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a>.</p>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getExtractVEXTRACTImmediate() {#aa794bd08e54931f96c70f2ac13bceab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getExtractVEXTRACTImmediate (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned VecWidth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getGlobalBaseReg() {#af26347fb23f94e0afc5cc388f4651c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDNode * X86DAGToDAGISel::getGlobalBaseReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> that returns the value of the global base register.</p>


<p>Output instructions required to initialize the global base register, if necessary.</p>


<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getI32Imm() {#a6ce4fd37a4a2249fe59b9607c9d6457a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getI32Imm (unsigned Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getI64Imm() {#a0174a2eb27c09f859f819c0cf29da425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getI64Imm (uint64_t Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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

<p>Return a target constant with the specified value, of type i64.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getI8Imm() {#a01db83936fe90eb23a650dbe3574b57f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getI8Imm (unsigned Imm, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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

<p>Definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getInsertVINSERTImmediate() {#a6f1a216989debc9adcfa1e228e2520c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getInsertVINSERTImmediate (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned VecWidth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getInstrInfo() {#a3d7d34de426cfb9bad7eb012ac21a968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86InstrInfo * anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getInstrInfo ()</td>
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

<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getPermuteVINSERTCommutedImmediate() {#a2021311a67a00deee7bc40ce673736d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getPermuteVINSERTCommutedImmediate (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned VecWidth, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdloc">SDLoc</a> &amp; DL)</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getSBBZero() {#a4a2296a0705f763fd8f5a356ab457493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getSBBZero (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### getTargetMachine() {#a509ec8a03e6ff667a14b4c82c5d46ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86TargetMachine &amp; anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::getTargetMachine ()</td>
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

<p>Return a reference to the <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>, casted to the target-specific type.</p>

<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### hasNoCarryFlagUses() {#a1d922148137ea06549c142e3513a9195}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::hasNoCarryFlagUses (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the given node which sets flags has any uses which require the CF flag to be accurate.</p>

<p>Definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### hasNoSignFlagUses() {#a6ebf70d71264b183887eb913d651d01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::hasNoSignFlagUses (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the given <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa23260aedef0a54d543d227e57955c652">X86ISD::CMP</a> node has any uses which require the SF flag to be accurate.</p>

<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isAMXSDNode() {#a74f0782fd19d79c556c2b3a7ddce8c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::isAMXSDNode (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isMaskZeroExtended() {#a8321b2d6e800fee6d182724b099f9a08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::isMaskZeroExtended (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isProfitableToFormMaskedOp() {#aa24a490cf63602b9ee6bde9cb542cc27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::isProfitableToFormMaskedOp (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isSExtAbsoluteSymbolRef() {#a196a4eca29e3c3413d2316b1f3d63925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::isSExtAbsoluteSymbolRef (unsigned Width, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### isUnneededShiftMask() {#a8c34b77046a12b39dddda9331f76b651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::isUnneededShiftMask (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N, unsigned Width)</td>
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



<p>Definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchAdd() {#a09964fd12c831a227aedcb3b2ecf081a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchAdd (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchAddress() {#a6467d39e11b199823c9d3c584e07860e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add the specified node to the specified addressing mode, returning true if it cannot be done.</p>


<p>This just pattern matches for the addressing mode.</p>


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchAddressBase() {#afcd152f633435b2d49b6655b9f9d151f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchAddressBase (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for MatchAddress.</p>


<p>Add the specified node to the specified addressing mode without any further recursion.</p>


<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchAddressRecursively() {#a82fe8159f1acbf8d8e20b5e90fe3fbde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchAddressRecursively (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchBEXTRFromAndImm() {#ad18fbe8c412dfd546613c156e68022d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineSDNode * X86DAGToDAGISel::matchBEXTRFromAndImm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchBitExtract() {#abbd0e308ed42ab7199239eee3057ebed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchBitExtract (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchIndexRecursively() {#a2a73cd86e045301d83f4cdab017ec797}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SDValue X86DAGToDAGISel::matchIndexRecursively (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchLoadInAddress() {#afc76bdb6c3ca60508ac97660a2d30373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchLoadInAddress (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM, bool AllowSegmentRegForX32=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchVectorAddress() {#a9099e8919452dec4f53ebc2cc8d7466c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchVectorAddress (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper for selectVectorAddr.</p>


<p>Handles things that can be folded into a gather/scatter address. The index register and scale should have already been handled.</p>


<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchVectorAddressRecursively() {#a227d9460eeac058f40ed26c914d750b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchVectorAddressRecursively (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchVPTERNLOG() {#a0480b86904bb1b0a853a30c377841127}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchVPTERNLOG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * ParentA, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * ParentB, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * ParentC, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> A, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> B, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> C, uint8_t Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### matchWrapper() {#a9c6c5baf359f326178578f1288fbc0f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::matchWrapper (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/structs/anonymous-x86iseldagtodag-cpp-/x86iseladdressmode">X86ISelAddressMode</a> &amp; AM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to match <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aac52ade4e38c09090c08d423e886cb4b2">X86ISD::Wrapper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aaf9b840077b4580ddbfd3bf992fe359eb">X86ISD::WrapperRIP</a> nodes into an addressing mode.</p>


<p>These wrap things that will resolve down into a symbol reference. If no match is possible, this returns true, otherwise it returns false.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### onlyUsesZeroFlag() {#ad498b953a8737b493705041627b314a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::onlyUsesZeroFlag (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether the given <a href="/web-llvm/docs/api/namespaces/llvm/x86isd/#a9441a4f94d36d0f7c0c34aca42e3f76aa23260aedef0a54d543d227e57955c652">X86ISD::CMP</a> node has any users that use a flag other than ZF.</p>

<p>Definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Select() {#afbfa18f7fed751a6a8e4189d791785fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86DAGToDAGISel::Select (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectAddr() {#a8c1c28e3aa8a4e42b1f3bb618d3b7d7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::selectAddr (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if it is able to pattern match an addressing mode.</p>


<p>It returns the operands which make up the maximal addressing mode it can match by reference.</p>


<p>Parent is the parent node of the addr operand that is being matched. It is always a load, store, atomic node, or null. It is only null when checking memory operands for inline asm nodes.</p>


<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### SelectInlineAsmMemoryOperand() {#a2f5dfcb3a444cde7e3cd0cbb818f2c17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::SelectInlineAsmMemoryOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">InlineAsm::ConstraintCode</a> ConstraintID, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &gt; &amp; OutOps)</td>
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

<p>Implement addressing mode selection for inline asm expressions.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectLEA64\_32Addr() {#a0b50deaf13946d7c809b37619dd5d8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::selectLEA64_32Addr (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectLEAAddr() {#ac6f9e126f39184489b148d996574481c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::selectLEAAddr (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calls SelectAddr and determines if the maximal addressing mode it matches can be cost effectively emitted as an LEA instruction.</p>

<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectMOV64Imm32() {#ac265ca7cd95f8e5016e1d6647e358ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::selectMOV64Imm32 (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectRelocImm() {#a9c8905e98551f1d38cc9137e20068af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::selectRelocImm (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectTLSADDRAddr() {#a17a9c21dc962cf3919c68c0ba8c3bcaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::selectTLSADDRAddr (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is only run on TargetGlobalTLSAddress nodes.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### selectVectorAddr() {#a2a2460b24ca719a462839d77e8e42d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::selectVectorAddr (<a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> BasePtr, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> IndexOp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> ScaleOp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### shouldAvoidImmediateInstFormsForSize() {#a57976737685c40737f5613ed2b092dbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::shouldAvoidImmediateInstFormsForSize (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
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



<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### shrinkAndImmediate() {#a53b54a535a36a2d55ecddf562acf3b41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::shrinkAndImmediate (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * And)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the high bits of an 'and' operand are known zero, try setting the high bits of an 'and' constant operand to produce a smaller encoding by creating a small, sign-extended negative immediate rather than a large positive one.</p>


<p>This reverses a transform in SimplifyDemandedBits that shrinks mask constants by clearing bits. There is also a possibility that the 'and' mask can be made -1, so the 'and' itself is unnecessary. In that case, just replace the 'and'. Return 'true' if the node is replaced.</p>


<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryFoldBroadcast() {#a6ae32113f788d6d00e89d7fd3a5c931b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryFoldBroadcast (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * P, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryFoldLoad() {#a4b5a84a479dd628c41b7a89dba6d438c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryFoldLoad (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * P, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryFoldLoad() {#a560493b67b7f664ee10cfa081f0fb191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::tryFoldLoad (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * P, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> N, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Base, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Scale, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Disp, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> &amp; Segment)</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryMatchBitSelect() {#ad49e6385edef89b1775d16113c825a83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryMatchBitSelect (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryOptimizeRem8Extend() {#abb73900c7b0e70e434012cbe626f637a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryOptimizeRem8Extend (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryShiftAmountMod() {#adb92c06b25ebb31f36d350bd30e3d845}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryShiftAmountMod (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryShrinkShlLogicImm() {#af55baaa176e9af18b2b34beafb8ae6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryShrinkShlLogicImm (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryVPTERNLOG() {#aec9093da995f9b7c83ce07cf33ed6ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryVPTERNLOG (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### tryVPTESTM() {#a1d18caa995fc388031553afd3c5c6a62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86DAGToDAGISel::tryVPTESTM (<a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Root, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Setcc, <a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### useNonTemporalLoad() {#ab1c685d60c5f80c63570cc552bd94e41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::useNonTemporalLoad (<a href="/web-llvm/docs/api/classes/llvm/loadsdnode">LoadSDNode</a> * N)</td>
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



<p>Definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IndirectTlsSegRefs {#a83f7548b2f66263002e910939bdc9f19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::IndirectTlsSegRefs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disable direct TLS access through segment registers.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### OptForMinSize {#ae0d32322e483f6cbfe23347d327c4b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::OptForMinSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, selector should try to optimize for minimum code size.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

### Subtarget {#ac73d48dbcc262d10da1e02281a124e79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const X86Subtarget* anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::Subtarget</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep a pointer to the <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> around so that we can make the right decision when generating code for different targets.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iseldagtodag-cpp">X86ISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
