---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-x86asmparser-cpp-/x86asmparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `X86AsmParser` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{X86AsmParser.cpp}::X86AsmParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser">MCTargetAsmParser</a> - Generic interface to target specific assembly parsers. <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">OpcodePrefix { <a href="#a124a91e7e20c315cf4799c96376280fb">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">DispEncoding { <a href="#a6f22553cf9d75e5e84d64eae4f26e3cc">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">InfixCalculatorTok { <a href="#af2224eee28174be9ae2fd03465d2db15">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IntelOperatorKind { <a href="#a0e59de9ebd945e4a227cbee092b83f29">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MasmOperatorKind { <a href="#af3656c064767937b6d3ecf5f0779bd12">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IntelExprState { <a href="#a2be5c3c9a3193862f365ebcb5a4f2da7">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72fd0d993586f5ab41001151669a59ce">consumeToken</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/x86targetstreamer">X86TargetStreamer</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb24e96c40cbde7f1cc3feb6edbcd6fc">getTargetStreamer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b34d28a4543325621ecdae44b831743">MatchInstruction</a> (const OperandVector &amp;Operands, MCInst &amp;Inst, uint64_t &amp;ErrorInfo, FeatureBitset &amp;MissingFeatures, bool matchingInlineAsm, unsigned VariantID=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b9fe4655d16ea2cea2c157024fa2606">Error</a> (SMLoc L, const Twine &amp;Msg, SMRange Range=std::nullopt, bool MatchingInlineAsm=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c11ee44589d5047baa3e5d9fa8725de">MatchRegisterByName</a> (MCRegister &amp;RegNo, StringRef RegName, SMLoc StartLoc, SMLoc EndLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a1c63dbea293a51c65dec1f5d2ffae">ParseRegister</a> (MCRegister &amp;RegNo, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc, bool RestoreOnFailure)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77953f354d6d5a5157e236bca3796128">DefaultMemSIOperand</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d38b9b8741decac410e828fecd15d7f">DefaultMemDIOperand</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad732e9094ccebded64e6f9b88aa77c94">IsSIReg</a> (MCRegister Reg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab23ebec35ca95dc4abaea3234711931f">GetSIDIForRegClass</a> (unsigned RegClassID, bool IsSIReg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ed5ab1b0b8b2202e2ee943e50a2869">AddDefaultSrcDestOperands</a> (OperandVector &amp;Operands, std::unique_ptr&lt; llvm::MCParsedAsmOperand &gt; &amp;&amp;Src, std::unique_ptr&lt; llvm::MCParsedAsmOperand &gt; &amp;&amp;Dst)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa238b0043d726f733956417ee0860b7c">VerifyAndAdjustOperands</a> (OperandVector &amp;OrigOperands, OperandVector &amp;FinalOperands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3d502443396ce75bd979cbd49bd3a55">parseOperand</a> (OperandVector &amp;Operands, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9aa2d11f3d6d9abe10b1a016ace75340">parseATTOperand</a> (OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef8a783635f9413af25a59b948c3db9e">parseIntelOperand</a> (OperandVector &amp;Operands, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af583e0089f6ab77f812020212e266a2e">ParseIntelOffsetOperator</a> (const MCExpr *&amp;Val, StringRef &amp;ID, InlineAsmIdentifierInfo &amp;Info, SMLoc &amp;End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the 'offset' operator. <a href="#af583e0089f6ab77f812020212e266a2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca13064d965584e6c33d91efc09a7de1">ParseIntelDotOperator</a> (IntelExprStateMachine &amp;SM, SMLoc &amp;End)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the '.' operator. <a href="#aca13064d965584e6c33d91efc09a7de1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c6c12900202773eb50395256f2f96fd">IdentifyIntelInlineAsmOperator</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7543efc279ad8cb37a0bea98541f9e50">ParseIntelInlineAsmOperator</a> (unsigned OpKind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the 'LENGTH', 'TYPE' and 'SIZE' operators. <a href="#a7543efc279ad8cb37a0bea98541f9e50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4db96673b1d165d2ea52be5b3f651eba">IdentifyMasmOperator</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e4fb8440ed61ce6577dec0e459ad6f">ParseMasmOperator</a> (unsigned OpKind, int64_t &amp;Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the 'LENGTHOF', 'SIZEOF', and 'TYPE' operators. <a href="#ad2e4fb8440ed61ce6577dec0e459ad6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53cc612aaff45fe38c4e2746888ef900">ParseRoundingModeOp</a> (SMLoc Start, OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0668093a6c8b31a9e0464e59c270de">parseCFlagsOp</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse condtional flags for CCMP/CTEST, e.g {dfv=of,sf,zf,cf} right after mnemonic. <a href="#a0d0668093a6c8b31a9e0464e59c270de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac126994ef7bbe40d35be20f5a7b8cfe0">ParseIntelNamedOperator</a> (StringRef Name, IntelExprStateMachine &amp;SM, bool &amp;ParseError, SMLoc &amp;End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa944f9bf5ae3727f7dccf3b676e5bce8">ParseMasmNamedOperator</a> (StringRef Name, IntelExprStateMachine &amp;SM, bool &amp;ParseError, SMLoc &amp;End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560435d0454325c65e3a26eabe54882b">RewriteIntelExpression</a> (IntelExprStateMachine &amp;SM, SMLoc Start, SMLoc End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7ff1869e2abccf20b301ad210526cc">ParseIntelExpression</a> (IntelExprStateMachine &amp;SM, SMLoc &amp;End)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46ee9cabf0b5d8b5d29ec6fb5c1943aa">ParseIntelInlineAsmIdentifier</a> (const MCExpr *&amp;Val, StringRef &amp;Identifier, InlineAsmIdentifierInfo &amp;Info, bool IsUnevaluatedOperand, SMLoc &amp;End, bool IsParsingOffsetOperator=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed93de24dca65fd9291f96a28c9513c">tryParseOperandIdx</a> (AsmToken::TokenKind PrevTK, IntelExprStateMachine &amp;SM)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1029a44516e474d60eba60b88cf79e9b">ParseMemOperand</a> (MCRegister SegReg, const MCExpr *Disp, SMLoc StartLoc, SMLoc EndLoc, OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseMemOperand: 'seg : disp(basereg, indexreg, scale)'. <a href="#a1029a44516e474d60eba60b88cf79e9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2e">X86::CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a522b4e4aa17130badddfb6cd7ce0224e">ParseConditionCode</a> (StringRef CCode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a771c42c9c282ada0c746e21998772a53">ParseIntelMemoryOperandSize</a> (unsigned &amp;Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ece589926a3f03bda77c50992e01c8">CreateMemForMSInlineAsm</a> (MCRegister SegReg, const MCExpr *Disp, MCRegister BaseReg, MCRegister IndexReg, unsigned Scale, bool NonAbsMem, SMLoc Start, SMLoc End, unsigned Size, StringRef Identifier, const InlineAsmIdentifierInfo &amp;Info, OperandVector &amp;Operands)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83823dae975d0824ec199a2dbb6c792">parseDirectiveArch</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0310c4cbc9203cf8b0a532fd6df9c3">parseDirectiveNops</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveNops ::= .nops size[, control] <a href="#a4d0310c4cbc9203cf8b0a532fd6df9c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8545ac86eae868ca4c76089adc494d47">parseDirectiveEven</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDirectiveEven ::= .even <a href="#a8545ac86eae868ca4c76089adc494d47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018e3d2f50a9b47cca43065e8c7f1449">ParseDirectiveCode</a> (StringRef IDVal, SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirectiveCode ::= .code16 | .code32 | .code64. <a href="#a018e3d2f50a9b47cca43065e8c7f1449">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8f59ae4fae40217612878b384021c97">parseDirectiveFPOProc</a> (SMLoc L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CodeView FPO data directives. <a href="#af8f59ae4fae40217612878b384021c97">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b40fec8ea789e912ee3417c6dcbf9f0">parseDirectiveFPOSetFrame</a> (SMLoc L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae84db969eab06257399cf0993351df2a">parseDirectiveFPOPushReg</a> (SMLoc L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567c9281d7b63b649eb2da7b2fdfc98d">parseDirectiveFPOStackAlloc</a> (SMLoc L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5486f1919f39cd035027213b42b6635">parseDirectiveFPOStackAlign</a> (SMLoc L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad33a51c6b3b821bb67865ba8b6cc4a67">parseDirectiveFPOEndPrologue</a> (SMLoc L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffc0d5ab682b2e18e34a8392fee4e58">parseDirectiveFPOEndProc</a> (SMLoc L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa426827c3fcb02de36e7f25af32f8f">parseSEHRegisterNumber</a> (unsigned RegClassID, MCRegister &amp;RegNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>SEH directives. <a href="#a0fa426827c3fcb02de36e7f25af32f8f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cb1816972e89ce439df1330b7c875d">parseDirectiveSEHPushReg</a> (SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a674c57cccf1d4f32c6a373b6bbc20250">parseDirectiveSEHSetFrame</a> (SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66a4a34a07545adc08ac56ab703cb63">parseDirectiveSEHSaveReg</a> (SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcac48674f52dc256fe669f7afdf60bb">parseDirectiveSEHSaveXMM</a> (SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4c458a8fc4c04fce74a8098492e87d9">parseDirectiveSEHPushFrame</a> (SMLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0885c5c39ba67d1a0997f9097e65fec2">checkTargetMatchPredicate</a> (MCInst &amp;Inst) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>checkTargetMatchPredicate - Validate the instruction match against any complex target predicates not expressible via match classes. <a href="#a0885c5c39ba67d1a0997f9097e65fec2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9762c28da458edcaa884114ced796e">validateInstruction</a> (MCInst &amp;Inst, const OperandVector &amp;Ops)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa2d1b561f69c3807d704514b0a3a853">processInstruction</a> (MCInst &amp;Inst, const OperandVector &amp;Ops)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18299ae27e51c01266c6e64cf60e43e">emitWarningForSpecialLVIInstruction</a> (SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af831e82d6f199baa2deae827083e8d5f">applyLVICFIMitigation</a> (MCInst &amp;Inst, MCStreamer &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RET instructions and also instructions that indirect calls/jumps from memory combine a load and a branch within a single instruction. <a href="#af831e82d6f199baa2deae827083e8d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb26a0247ac5384de74d041cc83e734">applyLVILoadHardeningMitigation</a> (MCInst &amp;Inst, MCStreamer &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>To mitigate LVI, every instruction that performs a load can be followed by an LFENCE instruction to squash any potential mis-speculation. <a href="#a0cb26a0247ac5384de74d041cc83e734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04ec97c61992f334aa7c808343b5b531">emitInstruction</a> (MCInst &amp;Inst, OperandVector &amp;Operands, MCStreamer &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrapper around <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">MCStreamer::emitInstruction()</a>. <a href="#a04ec97c61992f334aa7c808343b5b531">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e31d9c2377a9f2667fd728ed09123ce">matchAndEmitInstruction</a> (SMLoc IDLoc, unsigned &amp;Opcode, OperandVector &amp;Operands, MCStreamer &amp;Out, uint64_t &amp;ErrorInfo, bool MatchingInlineAsm) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer. <a href="#a9e31d9c2377a9f2667fd728ed09123ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab84afea238b6e553746c44ea8664b24c">MatchFPUWaitAlias</a> (SMLoc IDLoc, X86Operand &amp;Op, OperandVector &amp;Operands, MCStreamer &amp;Out, bool MatchingInlineAsm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6eea8740506f540b26495bf8c2c2ef9">ErrorMissingFeature</a> (SMLoc IDLoc, const FeatureBitset &amp;MissingFeatures, bool MatchingInlineAsm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c9662495ac807f98058b873777d3faa">matchAndEmitATTInstruction</a> (SMLoc IDLoc, unsigned &amp;Opcode, MCInst &amp;Inst, OperandVector &amp;Operands, MCStreamer &amp;Out, uint64_t &amp;ErrorInfo, bool MatchingInlineAsm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76de494e55315adb7bebc60dab6c08a">matchAndEmitIntelInstruction</a> (SMLoc IDLoc, unsigned &amp;Opcode, MCInst &amp;Inst, OperandVector &amp;Operands, MCStreamer &amp;Out, uint64_t &amp;ErrorInfo, bool MatchingInlineAsm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97ffc1e30786a9fac0e88d73b3bc0c2b">omitRegisterFromClobberLists</a> (MCRegister Reg) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows targets to let registers opt out of clobber lists. <a href="#a97ffc1e30786a9fac0e88d73b3bc0c2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7deca67546fff040fb0abf7b07592cdf">HandleAVX512Operand</a> (OperandVector &amp;Operands)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses AVX512 specific operand primitives: masked registers ({k&lt;NUM&gt;}, {z}) and memory broadcasting ({1to&lt;NUM&gt;}) primitives, updating Operands vector if required. <a href="#a7deca67546fff040fb0abf7b07592cdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f3576efd59d334b3900ee44c457571c">ParseZ</a> (std::unique_ptr&lt; X86Operand &gt; &amp;Z, const SMLoc &amp;StartLoc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c9b91d5002edad4e02178144fc6cb21">is64BitMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d50ce65e801e7766690473cf0fb4f5">is32BitMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9f48e27a17f1b82c2decf74805ec7a0">is16BitMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1663f586507f46ef3b79c496c1e2ddaf">SwitchMode</a> (unsigned mode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a860d3e58d9c87e3295d272931c374620">getPointerWidth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670b205df2315822bcbb881d14a54d35">isParsingIntelSyntax</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/parseinstructioninfo">ParseInstructionInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18f4702e9c56efe22a8eb7ad289aafea">InstInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad04783805d2e4e5496de33b027d5317">Code16GCC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8682ee4b83402e3090367e4a325ec61">ForcedDataPrefix</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">OpcodePrefix</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c37dee6146ad93170b5c28ad6ade88">ForcedOpcodePrefix</a> = OpcodePrefix_Default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">DispEncoding</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e17b6cd6c0c85295fe020dae04f1f09">ForcedDispEncoding</a> = DispEncoding_Default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d139a53f31ac06cb9e5b33078850a28">UseApxExtendedReg</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e669e25e4ef49d7e163c07b83094b80">ForcedNoFlag</a> = false</td>
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

## Auto-generated Matcher Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">X86MatchResultTy { <a href="#a9541e059b6e49720e4f834778b1b0007">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>} <a href="#a9541e059b6e49720e4f834778b1b0007">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cc27f37e8b0326d1913531ad4ff42d">X86AsmParser</a> (const MCSubtargetInfo &amp;sti, MCAsmParser &amp;Parser, const MCInstrInfo &amp;mii, const MCTargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a646e1fdcf432ce9d1be57dc4a42d0eb9">parseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parsestatus">ParseStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a5f6fe20b3365323eedea54e79aa8c0">tryParseRegister</a> (MCRegister &amp;Reg, SMLoc &amp;StartLoc, SMLoc &amp;EndLoc) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tryParseRegister - parse one register if possible <a href="#a1a5f6fe20b3365323eedea54e79aa8c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d5396b9da70debca98957fef699a358">parsePrimaryExpr</a> (const MCExpr *&amp;Res, SMLoc &amp;EndLoc) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6230cdb8093ea54524821d036b2203">parseInstruction</a> (ParseInstructionInfo &amp;Info, StringRef Name, SMLoc NameLoc, OperandVector &amp;Operands) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse one assembly instruction. <a href="#abf6230cdb8093ea54524821d036b2203">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a605f317c5671abb87131f5dcb6b2fe4a">ParseDirective</a> (AsmToken DirectiveID) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ParseDirective - Parse a target specific assembler directive This method is deprecated, use 'parseDirective' instead. <a href="#a605f317c5671abb87131f5dcb6b2fe4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### DispEncoding {#a6f22553cf9d75e5e84d64eae4f26e3cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmParser.cpp}::X86AsmParser::DispEncoding </td>
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
<td class="doxyEnumItemName">DispEncoding_Default<a id="a6f22553cf9d75e5e84d64eae4f26e3cca397a657d5b8f9140d4953e4f7930d7a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DispEncoding_Disp8<a id="a6f22553cf9d75e5e84d64eae4f26e3cca7882dfcd20e505e8d2470ff43a3b6c4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DispEncoding_Disp32<a id="a6f22553cf9d75e5e84d64eae4f26e3cca1715c66b48314642e678239b4b58f3fa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### InfixCalculatorTok {#af2224eee28174be9ae2fd03465d2db15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmParser.cpp}::X86AsmParser::InfixCalculatorTok </td>
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
<td class="doxyEnumItemName">IC_OR<a id="af2224eee28174be9ae2fd03465d2db15a67987bffb99f1590670b892873c750e7"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_XOR<a id="af2224eee28174be9ae2fd03465d2db15a6527f19c85d9def41a2f8a3e18896899"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_AND<a id="af2224eee28174be9ae2fd03465d2db15adfffe7eaa9bedf02ad8f4b5e3909bd54"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_LSHIFT<a id="af2224eee28174be9ae2fd03465d2db15a10972e0a312385d6496f67bf4e0d0a7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_RSHIFT<a id="af2224eee28174be9ae2fd03465d2db15a1efc083f3b4aa7ed6fea2a5f96aa3469"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_PLUS<a id="af2224eee28174be9ae2fd03465d2db15a9cf903e96f2bea6a2b6896b60ed03098"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_MINUS<a id="af2224eee28174be9ae2fd03465d2db15a8bf3008f356115bbfeb74aad72334e60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_MULTIPLY<a id="af2224eee28174be9ae2fd03465d2db15acd881c4b51165bc79a5fc229d42f2b6d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_DIVIDE<a id="af2224eee28174be9ae2fd03465d2db15a35f9052121c0fdcbc4d424f304cce528"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_MOD<a id="af2224eee28174be9ae2fd03465d2db15a7d98f1be3ee1448ff4684db49bfadf86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_NOT<a id="af2224eee28174be9ae2fd03465d2db15ac631ff89bb06c485e9c22efe24e5c3be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_NEG<a id="af2224eee28174be9ae2fd03465d2db15a17a93c226a53bd2e07f4188123d6bfa2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_RPAREN<a id="af2224eee28174be9ae2fd03465d2db15a7ed7ad4636c8bbd3f58c15ced87a222c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_LPAREN<a id="af2224eee28174be9ae2fd03465d2db15a4be24ca9bb334a622cf09118f22f0aff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_IMM<a id="af2224eee28174be9ae2fd03465d2db15a04d614840edb5f53d1b5c0bdac670c8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_REGISTER<a id="af2224eee28174be9ae2fd03465d2db15a3573e68f1892ce2269cbe088e86aed23"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_EQ<a id="af2224eee28174be9ae2fd03465d2db15af88b2853ef23d83a3b34ad246818f40a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_NE<a id="af2224eee28174be9ae2fd03465d2db15ac9e00b7f7c23bed7e27b828118f73f44"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_LT<a id="af2224eee28174be9ae2fd03465d2db15a0ef1a58fd98a5e2bbfdab6a53195585e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_LE<a id="af2224eee28174be9ae2fd03465d2db15a85e355af25dd2cdfb2978040f27ab7ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_GT<a id="af2224eee28174be9ae2fd03465d2db15aa32b88f57495553e36b7e3282f4a479e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IC_GE<a id="af2224eee28174be9ae2fd03465d2db15acde962a95b767a8c88cb0e9f5612f60a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### IntelExprState {#a2be5c3c9a3193862f365ebcb5a4f2da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmParser.cpp}::X86AsmParser::IntelExprState </td>
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
<td class="doxyEnumItemName">IES_INIT<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a7792cc0620f3b1dd39d5bcfbde603df8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_OR<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a3a7a577d1cd925e2de6190635b40c571"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_XOR<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a60be7afc1f67a792ba0643c1751a4d7c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_AND<a id="a2be5c3c9a3193862f365ebcb5a4f2da7acac77a111948e8ed19dc73865b3f5221"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_EQ<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a1fa2836076f00ce19d2ced0d5ca6a248"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_NE<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a6b8d367bb14ebfebeac8700aaeb39435"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_LT<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a04375676d53043e48ab91da8b6b172e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_LE<a id="a2be5c3c9a3193862f365ebcb5a4f2da7abb3036df7b27060418f42de38694b92d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_GT<a id="a2be5c3c9a3193862f365ebcb5a4f2da7ae3feb9f9ff78860fcb9a2fa7e5b6ab9f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_GE<a id="a2be5c3c9a3193862f365ebcb5a4f2da7af52e279ca68c31d758bfe70725619bf2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_LSHIFT<a id="a2be5c3c9a3193862f365ebcb5a4f2da7aba6f14294b8240c1fb398228fa3a55bd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_RSHIFT<a id="a2be5c3c9a3193862f365ebcb5a4f2da7ad6d1c0324fe3fed224828ac8ebb96c51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_PLUS<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a9120d3d14445cb766c96cdd269a78a1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_MINUS<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a7fdec68aef3a9c462adc0beed0b980c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_OFFSET<a id="a2be5c3c9a3193862f365ebcb5a4f2da7af0602bc56ffcf0d05cb04b3cc0d844c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_CAST<a id="a2be5c3c9a3193862f365ebcb5a4f2da7abb90a39da4c7f38027fb748cebeeca36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_NOT<a id="a2be5c3c9a3193862f365ebcb5a4f2da7ae45c14ae35e406865803b2aba158bc43"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_MULTIPLY<a id="a2be5c3c9a3193862f365ebcb5a4f2da7abd7fb9278f5a02c804321aba0006c01a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_DIVIDE<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a83b00238a09c2bf5d2b2b2e5603e3ebf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_MOD<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a1abbe34978eea1a0a83ca88dea9911fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_LBRAC<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a146e2af8674e16d2bc3f6dfb3a18bab1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_RBRAC<a id="a2be5c3c9a3193862f365ebcb5a4f2da7aafa0839ef98d6f8febe9d067255ddc2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_LPAREN<a id="a2be5c3c9a3193862f365ebcb5a4f2da7acb34a8230f49bc36ce38e2254062bb5f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_RPAREN<a id="a2be5c3c9a3193862f365ebcb5a4f2da7aa2318409a13cfeecf2871529c74cf5ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_REGISTER<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a01b6b6902fc18a5be38059f4b72af5ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_INTEGER<a id="a2be5c3c9a3193862f365ebcb5a4f2da7a4f17ecad82523054631f4c5d46136a10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IES_ERROR<a id="a2be5c3c9a3193862f365ebcb5a4f2da7accdb27fb89bfdf89b9a64c3f06aac90b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### IntelOperatorKind {#a0e59de9ebd945e4a227cbee092b83f29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmParser.cpp}::X86AsmParser::IntelOperatorKind </td>
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
<td class="doxyEnumItemName">IOK_INVALID<a id="a0e59de9ebd945e4a227cbee092b83f29a0789992353fe80931aa7ac79b1d69d44"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOK_LENGTH<a id="a0e59de9ebd945e4a227cbee092b83f29ac9859613f7d2f8e45c039c3fbaeea3c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOK_SIZE<a id="a0e59de9ebd945e4a227cbee092b83f29a88f41372fd3426ec41fb233fba7d5a4f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IOK_TYPE<a id="a0e59de9ebd945e4a227cbee092b83f29afb71f3ffd989df23cf4c598782c361df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### MasmOperatorKind {#af3656c064767937b6d3ecf5f0779bd12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmParser.cpp}::X86AsmParser::MasmOperatorKind </td>
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
<td class="doxyEnumItemName">MOK_INVALID<a id="af3656c064767937b6d3ecf5f0779bd12a88fc27833c4d6448ffefc3304cd337bb"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOK_LENGTHOF<a id="af3656c064767937b6d3ecf5f0779bd12a37135ed0c9c9847bd8587fb6de9a3c3d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOK_SIZEOF<a id="af3656c064767937b6d3ecf5f0779bd12a0f602d55491dc375ece18f858611d811"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MOK_TYPE<a id="af3656c064767937b6d3ecf5f0779bd12a114f7c172970ae7f7e758a89e6a73c8e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### OpcodePrefix {#a124a91e7e20c315cf4799c96376280fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmParser.cpp}::X86AsmParser::OpcodePrefix </td>
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
<td class="doxyEnumItemName">OpcodePrefix_Default<a id="a124a91e7e20c315cf4799c96376280fba60f6aba575aef105aa0c1241e8c2846d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpcodePrefix_REX<a id="a124a91e7e20c315cf4799c96376280fbaba0bcd50b490e26677a8b7c11a43c05e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpcodePrefix_REX2<a id="a124a91e7e20c315cf4799c96376280fbad2dd7a14d7efed4e88ed073aca48d8ed"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpcodePrefix_VEX<a id="a124a91e7e20c315cf4799c96376280fbace1b45d3f748e399405fe4c52b656dc3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpcodePrefix_VEX2<a id="a124a91e7e20c315cf4799c96376280fbabb32e942ec5ffceb05aa1d5d790f9cb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpcodePrefix_VEX3<a id="a124a91e7e20c315cf4799c96376280fba3743ff702352b7cc883a017ce10e4a65"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OpcodePrefix_EVEX<a id="a124a91e7e20c315cf4799c96376280fba46280dd1def9fa3465428025bf43da35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AddDefaultSrcDestOperands() {#af3ed5ab1b0b8b2202e2ee943e50a2869}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::AddDefaultSrcDestOperands (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">llvm::MCParsedAsmOperand</a> &gt; &amp;&amp; Src, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">llvm::MCParsedAsmOperand</a> &gt; &amp;&amp; Dst)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### applyLVICFIMitigation() {#af831e82d6f199baa2deae827083e8d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::applyLVICFIMitigation (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RET instructions and also instructions that indirect calls/jumps from memory combine a load and a branch within a single instruction.</p>


<p>To mitigate these instructions against LVI, they must be decomposed into separate load and branch instructions, with an LFENCE in between. For more details, see:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loadvalueinjectionrethardening-cpp">X86LoadValueInjectionRetHardening.cpp</a></li>
<li>X86LoadValueInjectionIndirectThunks.cpp</li>
<li><a href="https://software.intel.com/security-software-guidance/insights/deep-dive-load-value-injection">https://software.intel.com/security-software-guidance/insights/deep-dive-load-value-injection</a></li>
</ul>

<p>Returns <span class="doxyComputerOutput">true</span> if a mitigation was applied or warning was emitted.</p>


<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### applyLVILoadHardeningMitigation() {#a0cb26a0247ac5384de74d041cc83e734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::applyLVILoadHardeningMitigation (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>To mitigate LVI, every instruction that performs a load can be followed by an LFENCE instruction to squash any potential mis-speculation.</p>


<p>There are some instructions that require additional considerations, and may requre manual mitigation. For more details, see: <a href="https://software.intel.com/security-software-guidance/insights/deep-dive-load-value-injection">https://software.intel.com/security-software-guidance/insights/deep-dive-load-value-injection</a></p>


<p>Returns <span class="doxyComputerOutput">true</span> if a mitigation was applied or warning was emitted.</p>


<p>Definition at line 1191 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### checkTargetMatchPredicate() {#a0885c5c39ba67d1a0997f9097e65fec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86AsmParser::checkTargetMatchPredicate (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst)</td>
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

<p>checkTargetMatchPredicate - Validate the instruction match against any complex target predicates not expressible via match classes.</p>

<p>Definition at line 1183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### consumeToken() {#a72fd0d993586f5ab41001151669a59ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc anonymous{X86AsmParser.cpp}::X86AsmParser::consumeToken ()</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### CreateMemForMSInlineAsm() {#a85ece589926a3f03bda77c50992e01c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::CreateMemForMSInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SegReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Disp, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> BaseReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> IndexReg, unsigned Scale, bool NonAbsMem, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End, unsigned Size, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Identifier, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/inlineasmidentifierinfo">InlineAsmIdentifierInfo</a> &amp; Info, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1154 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### DefaultMemDIOperand() {#a3d38b9b8741decac410e828fecd15d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; X86AsmParser::DefaultMemDIOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### DefaultMemSIOperand() {#a77953f354d6d5a5157e236bca3796128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; X86AsmParser::DefaultMemSIOperand (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### emitInstruction() {#a04ec97c61992f334aa7c808343b5b531}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::emitInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Wrapper around <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a2e263d122b10b0bcc1bbf6c63202208c">MCStreamer::emitInstruction()</a>.</p>


<p>Possibly adds instrumentation around Inst.</p>


<p>Definition at line 1195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### emitWarningForSpecialLVIInstruction() {#aa18299ae27e51c01266c6e64cf60e43e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::emitWarningForSpecialLVIInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### Error() {#a3b9fe4655d16ea2cea2c157024fa2606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::Error (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Msg, <a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a> Range=std::nullopt, bool MatchingInlineAsm=false)</td>
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



<p>Definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ErrorMissingFeature() {#af6eea8740506f540b26495bf8c2c2ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ErrorMissingFeature (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; MissingFeatures, bool MatchingInlineAsm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### getPointerWidth() {#a860d3e58d9c87e3295d272931c374620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86AsmParser.cpp}::X86AsmParser::getPointerWidth ()</td>
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



<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### GetSIDIForRegClass() {#ab23ebec35ca95dc4abaea3234711931f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister X86AsmParser::GetSIDIForRegClass (unsigned RegClassID, bool IsSIReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### getTargetStreamer() {#acb24e96c40cbde7f1cc3feb6edbcd6fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86TargetStreamer &amp; anonymous{X86AsmParser.cpp}::X86AsmParser::getTargetStreamer ()</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### HandleAVX512Operand() {#a7deca67546fff040fb0abf7b07592cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::HandleAVX512Operand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parses AVX512 specific operand primitives: masked registers ({k&lt;NUM&gt;}, {z}) and memory broadcasting ({1to&lt;NUM&gt;}) primitives, updating Operands vector if required.</p>


<p>return false if no parsing errors occurred, true otherwise.</p>


<p>Definition at line 1222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### IdentifyIntelInlineAsmOperator() {#a1c6c12900202773eb50395256f2f96fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86AsmParser::IdentifyIntelInlineAsmOperator (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### IdentifyMasmOperator() {#a4db96673b1d165d2ea52be5b3f651eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86AsmParser::IdentifyMasmOperator (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1130 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### is16BitMode() {#aa9f48e27a17f1b82c2decf74805ec7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::is16BitMode ()</td>
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



<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### is32BitMode() {#a44d50ce65e801e7766690473cf0fb4f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::is32BitMode ()</td>
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



<p>Definition at line 1230 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### is64BitMode() {#a5c9b91d5002edad4e02178144fc6cb21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::is64BitMode ()</td>
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



<p>Definition at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### isParsingIntelSyntax() {#a670b205df2315822bcbb881d14a54d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::isParsingIntelSyntax ()</td>
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



<p>Definition at line 1256 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### IsSIReg() {#ad732e9094ccebded64e6f9b88aa77c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::IsSIReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### matchAndEmitATTInstruction() {#a0c9662495ac807f98058b873777d3faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::matchAndEmitATTInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, unsigned &amp; Opcode, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, uint64_t &amp; ErrorInfo, bool MatchingInlineAsm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### matchAndEmitInstruction() {#a9e31d9c2377a9f2667fd728ed09123ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::matchAndEmitInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, unsigned &amp; Opcode, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, uint64_t &amp; ErrorInfo, bool MatchingInlineAsm)</td>
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

<p>Recognize a series of operands of a parsed instruction as an actual MCInst and emit it to the specified MCStreamer.</p>


<p>This returns false on success and returns true on failure to match.</p>


<p>On failure, the target parser is responsible for emitting a diagnostic explaining the match failure.</p>


<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### matchAndEmitIntelInstruction() {#ab76de494e55315adb7bebc60dab6c08a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::matchAndEmitIntelInstruction (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, unsigned &amp; Opcode, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, uint64_t &amp; ErrorInfo, bool MatchingInlineAsm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### MatchFPUWaitAlias() {#ab84afea238b6e553746c44ea8664b24c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::MatchFPUWaitAlias (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> IDLoc, <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &amp; Op, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; Out, bool MatchingInlineAsm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### MatchInstruction() {#a8b34d28a4543325621ecdae44b831743}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86AsmParser.cpp}::X86AsmParser::MatchInstruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, uint64_t &amp; ErrorInfo, <a href="/web-llvm/docs/api/classes/llvm/featurebitset">FeatureBitset</a> &amp; MissingFeatures, bool matchingInlineAsm, unsigned VariantID=0)</td>
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



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### MatchRegisterByName() {#a5c11ee44589d5047baa3e5d9fa8725de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::MatchRegisterByName (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; RegNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RegName, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### omitRegisterFromClobberLists() {#a97ffc1e30786a9fac0e88d73b3bc0c2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::omitRegisterFromClobberLists (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Allows targets to let registers opt out of clobber lists.</p>

<p>Definition at line 1217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseATTOperand() {#a9aa2d11f3d6d9abe10b1a016ace75340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseATTOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1123 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseCFlagsOp() {#a0d0668093a6c8b31a9e0464e59c270de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseCFlagsOp (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse condtional flags for CCMP/CTEST, e.g {dfv=of,sf,zf,cf} right after mnemonic.</p>

<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseConditionCode() {#a522b4e4aa17130badddfb6cd7ce0224e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode X86AsmParser::ParseConditionCode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CCode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveArch() {#ab83823dae975d0824ec199a2dbb6c792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveArch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseDirectiveCode() {#a018e3d2f50a9b47cca43065e8c7f1449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseDirectiveCode (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> IDVal, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseDirectiveCode ::= .code16 | .code32 | .code64.</p>

<p>Definition at line 1164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveEven() {#a8545ac86eae868ca4c76089adc494d47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveEven (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveEven ::= .even</p>

<p>Definition at line 1163 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFPOEndProc() {#a9ffc0d5ab682b2e18e34a8392fee4e58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveFPOEndProc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1173 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFPOEndPrologue() {#ad33a51c6b3b821bb67865ba8b6cc4a67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveFPOEndPrologue (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFPOProc() {#af8f59ae4fae40217612878b384021c97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveFPOProc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>CodeView FPO data directives.</p>

<p>Definition at line 1167 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFPOPushReg() {#ae84db969eab06257399cf0993351df2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveFPOPushReg (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1169 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFPOSetFrame() {#a0b40fec8ea789e912ee3417c6dcbf9f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveFPOSetFrame (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFPOStackAlign() {#ab5486f1919f39cd035027213b42b6635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveFPOStackAlign (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveFPOStackAlloc() {#a567c9281d7b63b649eb2da7b2fdfc98d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveFPOStackAlloc (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveNops() {#a4d0310c4cbc9203cf8b0a532fd6df9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveNops (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDirectiveNops ::= .nops size[, control]</p>

<p>Definition at line 1162 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSEHPushFrame() {#af4c458a8fc4c04fce74a8098492e87d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveSEHPushFrame (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSEHPushReg() {#a58cb1816972e89ce439df1330b7c875d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveSEHPushReg (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSEHSaveReg() {#ad66a4a34a07545adc08ac56ab703cb63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveSEHSaveReg (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSEHSaveXMM() {#adcac48674f52dc256fe669f7afdf60bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveSEHSaveXMM (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseDirectiveSEHSetFrame() {#a674c57cccf1d4f32c6a373b6bbc20250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseDirectiveSEHSetFrame (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseIntelDotOperator() {#aca13064d965584e6c33d91efc09a7de1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseIntelDotOperator (IntelExprStateMachine &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the '.' operator.</p>

<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseIntelExpression() {#a4d7ff1869e2abccf20b301ad210526cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseIntelExpression (IntelExprStateMachine &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1140 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseIntelInlineAsmIdentifier() {#a46ee9cabf0b5d8b5d29ec6fb5c1943aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseIntelInlineAsmIdentifier (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; Identifier, <a href="/web-llvm/docs/api/structs/llvm/inlineasmidentifierinfo">InlineAsmIdentifierInfo</a> &amp; Info, bool IsUnevaluatedOperand, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; End, bool IsParsingOffsetOperator=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1141 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseIntelInlineAsmOperator() {#a7543efc279ad8cb37a0bea98541f9e50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned X86AsmParser::ParseIntelInlineAsmOperator (unsigned OpKind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the 'LENGTH', 'TYPE' and 'SIZE' operators.</p>


<p>The LENGTH operator returns the number of elements in an array. It returns the value 1 for non-array variables. The SIZE operator returns the size of a C or C++ variable. A variable's size is the product of its LENGTH and TYPE. The TYPE operator returns the size of a C or C++ type or variable. If the variable is an array, TYPE returns the size of a single element.</p>


<p>Definition at line 1129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseIntelMemoryOperandSize() {#a771c42c9c282ada0c746e21998772a53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseIntelMemoryOperandSize (unsigned &amp; Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1153 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseIntelNamedOperator() {#ac126994ef7bbe40d35be20f5a7b8cfe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseIntelNamedOperator (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IntelExprStateMachine &amp; SM, bool &amp; ParseError, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseIntelOffsetOperator() {#af583e0089f6ab77f812020212e266a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseIntelOffsetOperator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Val, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; ID, <a href="/web-llvm/docs/api/structs/llvm/inlineasmidentifierinfo">InlineAsmIdentifierInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the 'offset' operator.</p>


<p>This operator is used to specify the location of a given operand</p>


<p>Definition at line 1125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseIntelOperand() {#aef8a783635f9413af25a59b948c3db9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseIntelOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1124 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseMasmNamedOperator() {#aa944f9bf5ae3727f7dccf3b676e5bce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseMasmNamedOperator (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, IntelExprStateMachine &amp; SM, bool &amp; ParseError, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1136 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseMasmOperator() {#ad2e4fb8440ed61ce6577dec0e459ad6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseMasmOperator (unsigned OpKind, int64_t &amp; Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the 'LENGTHOF', 'SIZEOF', and 'TYPE' operators.</p>


<p>The LENGTHOF operator returns the number of elements in an array. It returns the value 1 for non-array variables. The SIZEOF operator returns the size of a type or variable in bytes. A variable's size is the product of its LENGTH and TYPE. The TYPE operator returns the size of a variable. If the variable is an array, TYPE returns the size of a single element.</p>


<p>Definition at line 1131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseMemOperand() {#a1029a44516e474d60eba60b88cf79e9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseMemOperand (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SegReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Disp, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ParseMemOperand: 'seg : disp(basereg, indexreg, scale)'.</p>


<p>The 'ds:' prefix has already been parsed if present. disp may be provided as well.</p>


<p>Definition at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseOperand() {#ab3d502443396ce75bd979cbd49bd3a55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseOperand (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1122 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseRegister() {#ab1a1c63dbea293a51c65dec1f5d2ffae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; RegNo, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc, bool RestoreOnFailure)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseRoundingModeOp() {#a53cc612aaff45fe38c4e2746888ef900}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseRoundingModeOp (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### parseSEHRegisterNumber() {#a0fa426827c3fcb02de36e7f25af32f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseSEHRegisterNumber (unsigned RegClassID, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; RegNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>SEH directives.</p>

<p>Definition at line 1176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ParseZ() {#a9f3576efd59d334b3900ee44c457571c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseZ (std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt; &amp; Z, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### processInstruction() {#afa2d1b561f69c3807d704514b0a3a853}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::processInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### RewriteIntelExpression() {#a560435d0454325c65e3a26eabe54882b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::RewriteIntelExpression (IntelExprStateMachine &amp; SM, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### SwitchMode() {#a1663f586507f46ef3b79c496c1e2ddaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{X86AsmParser.cpp}::X86AsmParser::SwitchMode (unsigned mode)</td>
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



<p>Definition at line 1238 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### tryParseOperandIdx() {#a1ed93de24dca65fd9291f96a28c9513c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void X86AsmParser::tryParseOperandIdx (<a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039">AsmToken::TokenKind</a> PrevTK, IntelExprStateMachine &amp; SM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### validateInstruction() {#a0f9762c28da458edcaa884114ced796e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::validateInstruction (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Ops)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### VerifyAndAdjustOperands() {#aa238b0043d726f733956417ee0860b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::VerifyAndAdjustOperands (<a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; OrigOperands, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; FinalOperands)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1120 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Code16GCC {#aad04783805d2e4e5496de33b027d5317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::Code16GCC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ForcedDataPrefix {#ae8682ee4b83402e3090367e4a325ec61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{X86AsmParser.cpp}::X86AsmParser::ForcedDataPrefix = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ForcedDispEncoding {#a3e17b6cd6c0c85295fe020dae04f1f09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DispEncoding anonymous{X86AsmParser.cpp}::X86AsmParser::ForcedDispEncoding = DispEncoding_Default</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ForcedNoFlag {#a0e669e25e4ef49d7e163c07b83094b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::ForcedNoFlag = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### ForcedOpcodePrefix {#ad2c37dee6146ad93170b5c28ad6ade88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpcodePrefix anonymous{X86AsmParser.cpp}::X86AsmParser::ForcedOpcodePrefix = OpcodePrefix_Default</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### InstInfo {#a18f4702e9c56efe22a8eb7ad289aafea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseInstructionInfo* anonymous{X86AsmParser.cpp}::X86AsmParser::InstInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

### UseApxExtendedReg {#a1d139a53f31ac06cb9e5b33078850a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{X86AsmParser.cpp}::X86AsmParser::UseApxExtendedReg = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Auto-generated Matcher Functions



<p>{</p>


### ParseDirective {#a605f317c5671abb87131f5dcb6b2fe4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::ParseDirective (<a href="/web-llvm/docs/api/classes/llvm/asmtoken">AsmToken</a> DirectiveID)</td>
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

<p>ParseDirective - Parse a target specific assembler directive This method is deprecated, use 'parseDirective' instead.</p>


<p>The parser is positioned following the directive name. The target specific directive parser should parse the entire directive doing or recording any target specific work, or return true and do nothing if the directive is not target specific. If the directive is specific for the target, the entire line is parsed up to and including the end-of-statement token and false is returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DirectiveID</td>
<td class="doxyParamItemDescription"><p>- the identifier token of the directive.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 1295 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae46058c90a3c703357331a6501b32f1c">llvm::StringRef::equals_insensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#aefa517e84a358fccd59fb1815b87fa44">llvm::AsmToken::getIdentifier</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a16611db1be4d04f03c570d9302504c04">llvm::AsmToken::getLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>

</div>
</div>

### parseInstruction {#abf6230cdb8093ea54524821d036b2203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseInstruction (<a href="/web-llvm/docs/api/structs/llvm/parseinstructioninfo">ParseInstructionInfo</a> &amp; Info, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> NameLoc, <a href="/web-llvm/docs/api/namespaces/llvm/#a61e27c75c3334cffa54c44c02077da1e">OperandVector</a> &amp; Operands)</td>
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

<p>Parse one assembly instruction.</p>


<p>The parser is positioned following the instruction name. The target specific instruction parser should parse the entire instruction and construct the appropriate MCInst, or emit an error. On success, the entire line should be parsed up to and including the end-of-statement token. On failure, the parser is not required to read to the end of the line.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Name</td>
<td class="doxyParamItemDescription"><p>- The instruction name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NameLoc</td>
<td class="doxyParamItemDescription"><p>- The source location of the name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Operands</td>
<td class="doxyParamItemDescription"><p>[out] - The list of parsed operands, this returns ownership of them to the caller.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True on failure.</p></dd>
</dl>


<p>Definition at line 1292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda2273a4cd5bbad83c4f121c983185a8df">llvm::AOK_EndOfStatement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a262e7bca188555ee4b40df11450b4bfda7abdec48f548b1a8b8ce59f17b52e5ec">llvm::AOK_Skip</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5b6faabb08339ea1dd11e9d37a668634">llvm::StringRef::back</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#aa13f802513b39e1e2a7650011e5651d7">llvm::StringSwitch&lt; T, R &gt;::Cases</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ac4b2675d2cb80935b789d9f140092e25">llvm::AsmToken::Comma</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">llvm::X86::COND_INVALID</a>, <a href="/web-llvm/docs/api/classes/llvm/mcconstantexpr/#af9bdc4c9c65ea1ff077fbbb6407d7b2a">llvm::MCConstantExpr::create</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a1148364374905ec7fe1d2e05f8a97a58">llvm::X86Operand::CreateImm</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a2d42b1611036b87b39d2a79336f18dda">llvm::X86Operand::CreatePrefix</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a55c25fac84462530fd620a9d92ea3723">llvm::X86Operand::CreateReg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#acde7256b4b06b4bd9b75088863c32265">llvm::X86Operand::CreateToken</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae2705fd641fb3d1eefa2691b5117cf22">llvm::StringRef::drop_back</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039ae10c5f59f330bfd15608e1dda213a98f">llvm::AsmToken::EndOfStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae46058c90a3c703357331a6501b32f1c">llvm::StringRef::equals_insensitive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a902b0d55fddef6f8d651fe1035b7d4bd">llvm::Error</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aa7399d73f97fdf5bcf6b19f760264848">llvm::MCAsmParserExtension::getContext</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a6204d6d4477a1f29574110fbb57303f3">llvm::X86Operand::getEndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#afba734fed57c0c0343c2f8e096ce3c16">llvm::MCAsmParserExtension::getLexer</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a7428ebe08f75a705043e1bd005d0542d">llvm::SMLoc::getPointer</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#aebf941872ccba8bb10d98c73b8057401">llvm::X86Operand::getReg</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a090e68360629b3b65af38689970fda07">llvm::X86Operand::getStartLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a3168618a19701d0fb78aefb4d4e664de">llvm::AsmToken::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a4235d087dc899291be41be9db4d811a9">llvm::MCAsmParserExtension::getTok</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a21f6d8d4fc6a58587a2b022eb048a3bc">llvm::X86::IP_HAS_LOCK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a2352c35cf1f63002a6e595d1d1700dee">llvm::X86::IP_HAS_NOTRACK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350a6afdb4f34129d1756d5983acde2125ea">llvm::X86::IP_HAS_REPEAT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350aecd65b1d4484960a4b47c1ec3fbe5e75">llvm::X86::IP_HAS_REPEAT_NE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86/#ab45f29eafca4acc2a7240156af5ec350aec5df73a7c3497a61671eda217adc7ab">llvm::X86::IP_NO_PREFIX</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#adf84562f4a788ca9361c7fb9bc099bc1">llvm::X86Operand::isMem8</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#accff22ec9fbd872b5976a4a2dc20ef56">isNot</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a88440eb70840c5f98838457a5040014d">llvm::MCTargetAsmParser::isParsingMSInlineAsm</a>, <a href="/web-llvm/docs/api/structs/llvm/x86operand/#a65db4de47ce9d66f1dfc97ae7c3b46b0">llvm::X86Operand::isReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#a95ee9fb985a241fdefc130f885d4232c">IsVCMP</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a940bbb142e7bb0990d40889426def99c">llvm::AsmToken::LCurly</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mirnamerpass-cpp/#a05e4be4ec3e2c3587dda0e376bb6822c">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3847b0adce89a393ecf0b359d8ff8646">llvm::AsmToken::RCurly</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a9416ef6f33208f9c76db8f44ca45e61a">llvm::AsmToken::Slash</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5d4c961b9b6f1da17df74b4496ecb30e">llvm::StringRef::slice</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a871b85a46f471e616995b722df807211">llvm::AsmToken::Star</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a939005612707a0dd8c6cee10d302748f">llvm::MCAsmParserExtension::TokError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a0eaadb4fcb48a0a0ed7bc9868be9fbaa">llvm::Warning</a>.</p>

</div>
</div>

### parsePrimaryExpr {#a0d5396b9da70debca98957fef699a358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parsePrimaryExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *&amp; Res, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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



<p>Definition at line 1290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/x86mcexpr/#a978afb888874e014551b394a62564049">llvm::X86MCExpr::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#a4235d087dc899291be41be9db4d811a9">llvm::MCAsmParserExtension::getTok</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a806fe218bb80f0671afdad4cec36569b">llvm::AsmToken::Identifier</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/asmparser/aarch64asmparser-cpp/#a4ff6b3fd769bb0563feaa4fd3e58e23f">MatchRegisterName</a>, <a href="#a646e1fdcf432ce9d1be57dc4a42d0eb9">parseRegister</a> and <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#ab4316e41520ea53f789582c25bbec039a3307eed2aff3782f3d420aebbe433486">llvm::AsmToken::Percent</a>.</p>

</div>
</div>

### parseRegister {#a646e1fdcf432ce9d1be57dc4a42d0eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool X86AsmParser::parseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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



<p>Definition at line 1286 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>


<p>Referenced by <a href="#a0d5396b9da70debca98957fef699a358">parsePrimaryExpr</a>.</p>

</div>
</div>

### tryParseRegister {#a1a5f6fe20b3365323eedea54e79aa8c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParseStatus X86AsmParser::tryParseRegister (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> &amp; Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> &amp; EndLoc)</td>
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

<p>tryParseRegister - parse one register if possible</p>


<p>Check whether a register specification can be parsed at the current location, without failing the entire parse if it can't. Must not consume tokens if the parse fails.</p>


<p>Definition at line 1287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a07e0e7c7dba79a89519092de57d17358">llvm::ParseStatus::Failure</a>, <a href="/web-llvm/docs/api/classes/llvm/mcasmparserextension/#aef625855ca29806691daef93804afba0">llvm::MCAsmParserExtension::getParser</a>, <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a670f6078c68c861b8ecaa1ec082fd736">llvm::ParseStatus::NoMatch</a> and <a href="/web-llvm/docs/api/classes/llvm/parsestatus/#a66a81b1ff471ed3e871c93599118f34c">llvm::ParseStatus::Success</a>.</p>

</div>
</div>

### X86AsmParser {#af2cc27f37e8b0326d1913531ad4ff42d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{X86AsmParser.cpp}::X86AsmParser::X86AsmParser (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsubtargetinfo">MCSubtargetInfo</a> &amp; sti, <a href="/web-llvm/docs/api/classes/llvm/mcasmparser">MCAsmParser</a> &amp; Parser, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrinfo">MCInstrInfo</a> &amp; mii, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mctargetoptions">MCTargetOptions</a> &amp; Options)</td>
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



<p>Definition at line 1275 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#aa1990a3125ab983e6e90a452cb5a2e66">llvm::MCTargetAsmParser::getSTI</a>, <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a32cd9ae9007321c391a62dd4bd69d268">llvm::MCTargetAsmParser::MCTargetAsmParser</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a> and <a href="/web-llvm/docs/api/classes/llvm/mctargetasmparser/#a9bc309121dfab6b0c03a026eec7b2ab7">llvm::MCTargetAsmParser::setAvailableFeatures</a>.</p>

</div>
</div>

### X86MatchResultTy {#a9541e059b6e49720e4f834778b1b0007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{X86AsmParser.cpp}::X86AsmParser::X86MatchResultTy </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>}</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Match_Unsupported<a id="a9541e059b6e49720e4f834778b1b0007a2f846a3dfaa820608f821f83830427cf"></a></td>
<td class="doxyEnumItemDescription"> (= FIRST_TARGET_MATCH_RESULT_TY)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1269 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86asmparser-cpp">X86AsmParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
