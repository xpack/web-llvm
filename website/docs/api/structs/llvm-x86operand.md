---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/x86operand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `X86Operand` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> - Instances of this class represent a parsed <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> machine instruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::X86Operand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">Target/X86/AsmParser/X86Operand.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand">MCParsedAsmOperand</a> - This abstract class represents a source-level assembly instruction operand. <a href="/web-llvm/docs/api/classes/llvm/mcparsedasmoperand/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">KindTy { <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae56d884e0aa40722ca010094914d00">X86Operand</a> (KindTy K, SMLoc Start, SMLoc End)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb6f353f69b061783ade3e3e68fc6b86">getSymName</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a511762f6331653150a005519781399a1">getOpDecl</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a090e68360629b3b65af38689970fda07">getStartLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getStartLoc - Get the location of the first token of this operand. <a href="#a090e68360629b3b65af38689970fda07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6204d6d4477a1f29574110fbb57303f3">getEndLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getEndLoc - Get the location of the last token of this operand. <a href="#a6204d6d4477a1f29574110fbb57303f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smrange">SMRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a0ab8e34b9f38f8e4ebc5c2accd5f9b">getLocRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getLocRange - Get the range between the first and last token of this operand. <a href="#a5a0ab8e34b9f38f8e4ebc5c2accd5f9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2a923810ad78e79e28e555b38dcf06b">getOffsetOfLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOffsetOfLoc - Get the location of the offset operator. <a href="#ad2a923810ad78e79e28e555b38dcf06b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59aaa2e922d6173cbeaed43a2d58423a">print</a> (raw_ostream &amp;OS) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>print - Print a debug representation of the operand to the given stream. <a href="#a59aaa2e922d6173cbeaed43a2d58423a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9de9100bfa3e53ca720f1f24f1aebc3">getToken</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a450d0abfd7db79e602bd9ded8967a84a">setTokenValue</a> (StringRef Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d87198a14f3a3df41aa3a398cdd4f2b">getPrefix</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2718878168e750f8341edec2c5c277b">getImm</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbdb3bc8b04cbcd6a46c3337be8fbe5a">getMemDefaultBaseReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab186130122afce40b50c5322855dec61">getMemModeSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1f867c585763697989e40cd8fc93d9">getMemFrontendSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcf9465c97907fca5466970e0108e54">isMaybeDirectBranchDest</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5e18bddceffd46f90828fb91143e684">isToken</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isToken - Is this a token operand? <a href="#af5e18bddceffd46f90828fb91143e684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isImm - Is this an immediate operand? <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a589f5952010fac7682138e63127be694">isImmSExti16i8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7de4e0ae5756923ef51185bdc381143a">isImmSExti32i8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36d5302f4f1b10115eee78745413c38f">isImmSExti64i8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a61fa0a696a44bb2d4c4ccf6349aa75">isImmSExti64i32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6925a00cf927a63d7e37cbfc01b23a4d">isImmUnsignedi4</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48dcaf841143a22ebebf70d9d109c5ed">isImmUnsignedi8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c42e2fa7f30c3261eb69b9202349dcf">isOffsetOfLocal</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isOffsetOfLocal - Do we need to emit code to get the offset of the local variable, rather than its value? <a href="#a1c42e2fa7f30c3261eb69b9202349dcf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf8c4a729ab0feb373fa212d3cb8b0da">needAddressOf</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>needAddressOf - Do we need to emit code to get the address of the variable/label? <a href="#abf8c4a729ab0feb373fa212d3cb8b0da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b38b8c28c19c6d4933ef67ce31d173">isMem</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMem - Is this a memory operand? <a href="#a66b38b8c28c19c6d4933ef67ce31d173">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad14239f4470c58ee36c34706a2e96d95">isMemUnsized</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf84562f4a788ca9361c7fb9bc099bc1">isMem8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbbc211a989964f8eef960b55ecb9d7">isMem16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba881e19bd5892a14da9e76805cd904">isMem80</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a514af8717f1887801525c9cdecaf3f2c">isMem128</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12981fa558be4fdc323708668b21f56">isMem256</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60699c36b71f5e4a45ce7a3c3241ca0e">isMem512</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543e73003a6f5467b84984e27cf1d8a1">isSibMem</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a972b6c9e72ea680cc385a26250c89b75">isMemIndexReg</a> (unsigned LowR, unsigned HighR) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a6985e57b1ec85f3ec46e64637ca0c">isMem32_RC128</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961d85f2caa9d853b7c2f7d80954e838">isMem64_RC128</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad701172b63f22a3e238c712fb7656809">isMem32_RC256</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8c9fe8831fe1c3d4467467d931f193e">isMem64_RC256</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf7c7a8670a44172ba5543a081d8a61">isMem32_RC128X</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af696541557d6fc4e1c83ad89a588c338">isMem64_RC128X</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd65473993a62586ddcab7dde6b26a4">isMem32_RC256X</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ad279fcfec0f9227f547633afd2de7e">isMem64_RC256X</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c7738b6d6730bbc74899674260e826e">isMem32_RC512</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee7a3ded94c63083e2627cdd7388013">isMem64_RC512</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c17a8268c0736d291a2bc525584bd90">isMem512_GR16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de950f79cc96b55dadb92ce88e8c0d3">isMem512_GR32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a452acb153ae96fb8bb97ea598d035935">isMem512_GR64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a65cab19ce9662be68fa6b792cc4c6c">isAVX512RC</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95856220935952727ee0807c3578b0ce">isAbsMem16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c7546ba631e3b4ef89ba82f87ab07f">isMemUseUpRegs</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMemUseUpRegs - Is memory operand use up regs, for example, intel MS inline asm may use ARR[baseReg + IndexReg + ...] which may use up regs in [...] expr, so ARR[baseReg + IndexReg + ...] can not use extra reg for ARR. <a href="#a10c7546ba631e3b4ef89ba82f87ab07f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a420cac2d28e139b40796648f5ade77e5">isSrcIdx8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9db87ee16dd973efb574e81111afd8">isSrcIdx16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fedd0acbdb046638a66c07eed76a2fb">isSrcIdx32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb62cb4670187d40b51d78a4a66f40c">isSrcIdx64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581e54ef28c14b479e09ebc80baeb8fd">isDstIdx8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05d6f488f4a0a52994c68e1913d660f">isDstIdx16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab72330a7aadb08a47f09723e24a8dccc">isDstIdx32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a879826874e6b8d02e7c5eb6b97f8cc6e">isDstIdx64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cb65977f1e80f2f00b35383a3700249">isMemOffs16_8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad795a3f8e6d70a29a4032d2951425f6a">isMemOffs16_16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee281ae3219d572cbbf370d637797f91">isMemOffs16_32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d469d804500ad3ce26991be9ee8761">isMemOffs32_8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6c3460a1b79625d27b62b82c5a6013">isMemOffs32_16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a305a25a19fb1523f61fd242ad66f1db5">isMemOffs32_32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1b78c81c7292bbc4b005c5c74ec57fe">isMemOffs32_64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5779b19cdf365d747c0b05102955ac02">isMemOffs64_8</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdcb17eda7ce4b3ad6feba1ba14083e3">isMemOffs64_16</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10cf4e0abda37a7725b14e9bcc419591">isMemOffs64_32</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a011f73c1ea251da7e051ae168540dded">isMemOffs64_64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cb6b9ca4ef45a66c8243ecf2b663b48">isPrefix</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65db4de47ce9d66f1dfc97ae7c3b46b0">isReg</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isReg - Is this a register operand? <a href="#a65db4de47ce9d66f1dfc97ae7c3b46b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ccc7d6c88cf28afe86d5d96955180e9">isDXReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ecb25e849b579a4e02f93af13b0be3">isGR32orGR64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb76a59133e0abcf11caf9ab31e32ccc">isGR16orGR32orGR64</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60893542cbdf81bc5ebf40d86b59afb">isVectorReg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507d5a660efc16447e5a33658fc35330">isVK1Pair</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5c69cd34baab3b3f3adb0187e20da7e">isVK2Pair</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e12082a24ba1ab62860d441b40cf062">isVK4Pair</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09493d661bb5dcd758403f54361ef8ec">isVK8Pair</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3dea0fc883e376307be8706e088d211">isVK16Pair</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16fc7281d45e1dfc3a9caf539e564d0f">addExpr</a> (MCInst &amp;Inst, const MCExpr *Expr) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8b46050f49c0070718cb24eaf4b44b0">addRegOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86467b8eb24fee4d7a713a537685d783">addGR32orGR64Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25127edbfd500680786a7964074d8629">addGR16orGR32orGR64Operands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f7ff37427c7091f644b497d94f4fcff">addAVX512RCOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c70f2eca46ec1276f2519a99ffae11">addImmOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1411797182fa22f898f4baf0e3eb7298">addMaskPairOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e3a46f7776ecfcab35620a41e319246">isTILEPair</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d9f319c365afc3c199b8d1f179003bd">addTILEPairOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb809c95f07fa9985fef7e95cf551c8">addAbsMemOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49468934edef8e57cda0f8aad36c57e9">addSrcIdxOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa957005d508608716aace06b32aedff5">addDstIdxOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46908e32f1979cb4f57d7d26df02bbf7">addMemOffsOperands</a> (MCInst &amp;Inst, unsigned N) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6">llvm::X86Operand::KindTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbe28cf220d7fd9cf74ffad6f2d0b60d">OffsetOfLoc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a99fde5a4b24c8e2129774fe1303c3b">SymName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e64e878c06d7163d8691a0fe6fedfc7">OpDecl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23c39c21b5c7e8f2351b674b173cdd10">AddressOf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32f1c7a8986b0d7bd5a076806bb00b81">UseUpRegs</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This used for inline asm which may specify base reg and index reg for <a href="/web-llvm/docs/api/structs/llvm/x86operand/memop">MemOp</a>. <a href="#a32f1c7a8986b0d7bd5a076806bb00b81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed069d1266226c171c267b4a3cc1f6ed">Tok</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb79a3e12c88ca2d15700cfae21334f">Reg</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fbc1ec5a4956ef599b9bcada81b8924">Imm</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3648c88df1546f6df4b9359c334bf2c">Pref</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union <a href="/web-llvm/docs/api/structs/llvm/x86operand">llvm::X86Operand</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6810b3012a3daaa208562355c1beb6"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde7256b4b06b4bd9b75088863c32265">CreateToken</a> (StringRef Str, SMLoc Loc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a> (MCRegister Reg, SMLoc StartLoc, SMLoc EndLoc, bool AddressOf=false, SMLoc OffsetOfLoc=SMLoc(), StringRef SymName=StringRef(), void *OpDecl=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31046024a7c3714c5864155dd5b4b740">CreateDXReg</a> (SMLoc StartLoc, SMLoc EndLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d42b1611036b87b39d2a79336f18dda">CreatePrefix</a> (unsigned Prefixes, SMLoc StartLoc, SMLoc EndLoc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1148364374905ec7fe1d2e05f8a97a58">CreateImm</a> (const MCExpr *Val, SMLoc StartLoc, SMLoc EndLoc, StringRef SymName=StringRef(), void *OpDecl=nullptr, bool GlobalRef=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a706b11b0c09a7d9e06208ff685a44fe3">CreateMem</a> (unsigned ModeSize, const MCExpr *Disp, SMLoc StartLoc, SMLoc EndLoc, unsigned Size=0, StringRef SymName=StringRef(), void *OpDecl=nullptr, unsigned FrontendSize=0, bool UseUpRegs=false, bool MaybeDirectBranchDest=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an absolute memory operand. <a href="#a706b11b0c09a7d9e06208ff685a44fe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab05d1fa246fe62a966a8b51f755bcb39">CreateMem</a> (unsigned ModeSize, MCRegister SegReg, const MCExpr *Disp, MCRegister BaseReg, MCRegister IndexReg, unsigned Scale, SMLoc StartLoc, SMLoc EndLoc, unsigned Size=0, MCRegister DefaultBaseReg=MCRegister(), StringRef SymName=StringRef(), void *OpDecl=nullptr, unsigned FrontendSize=0, bool UseUpRegs=false, bool MaybeDirectBranchDest=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a generalized memory operand. <a href="#ab05d1fa246fe62a966a8b51f755bcb39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/structs/llvm/x86operand">X86Operand</a> - Instances of this class represent a parsed <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> machine instruction.</p>

<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### KindTy {#a4edd4aeb4f5f68994c7dfd8d33bc15c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Operand::KindTy </td>
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
<td class="doxyEnumItemName">Token<a id="a4edd4aeb4f5f68994c7dfd8d33bc15c6a86e1f766d1e8740608e1323dc794048e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Register<a id="a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Immediate<a id="a4edd4aeb4f5f68994c7dfd8d33bc15c6a4d4f5ec9e5c39e9551b9a1a4cb33bba4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Memory<a id="a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Prefix<a id="a4edd4aeb4f5f68994c7dfd8d33bc15c6adee65df884422f3d6c7e770691409afa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DXRegister<a id="a4edd4aeb4f5f68994c7dfd8d33bc15c6a3948ffaf880576057e2f49f52d58554e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### X86Operand() {#a1ae56d884e0aa40722ca010094914d00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::X86Operand::X86Operand (<a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6">KindTy</a> K, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Start, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> End)</td>
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



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a23c39c21b5c7e8f2351b674b173cdd10">AddressOf</a>, <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a5e64e878c06d7163d8691a0fe6fedfc7">OpDecl</a> and <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAbsMemOperands() {#a3fb809c95f07fa9985fef7e95cf551c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addAbsMemOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addAVX512RCOperands() {#a0f7ff37427c7091f644b497d94f4fcff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addAVX512RCOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a16fc7281d45e1dfc3a9caf539e564d0f">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addDstIdxOperands() {#aa957005d508608716aace06b32aedff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addDstIdxOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addExpr() {#a16fc7281d45e1dfc3a9caf539e564d0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addExpr (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Expr)</td>
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



<p>Definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="#a0f7ff37427c7091f644b497d94f4fcff">addAVX512RCOperands</a>, <a href="#a41c70f2eca46ec1276f2519a99ffae11">addImmOperands</a> and <a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a>.</p>

</div>
</div>

### addGR16orGR32orGR64Operands() {#a25127edbfd500680786a7964074d8629}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addGR16orGR32orGR64Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addGR32orGR64Operands() {#a86467b8eb24fee4d7a713a537685d783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addGR32orGR64Operands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27b344a283e0620f484144889fe32064">llvm::getX86SubSuperRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addImmOperands() {#a41c70f2eca46ec1276f2519a99ffae11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addImmOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 589 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a16fc7281d45e1dfc3a9caf539e564d0f">addExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMaskPairOperands() {#a1411797182fa22f898f4baf0e3eb7298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addMaskPairOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#aafb79a3e12c88ca2d15700cfae21334f">Reg</a>.</p>

</div>
</div>

### addMemOffsOperands() {#a46908e32f1979cb4f57d7d26df02bbf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addMemOffsOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a17f407ba097404266dc3528bd68ac811">llvm::MCOperand::createExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a>, <a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addMemOperands() {#aa68185209b553ccd5de6d4cd21aae0b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addMemOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a16fc7281d45e1dfc3a9caf539e564d0f">addExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a595e70d3c4ee2ed95ece67a1957167a4">llvm::MCOperand::createImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#acbdb3bc8b04cbcd6a46c3337be8fbe5a">getMemDefaultBaseReg</a>, <a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a>, <a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a>, <a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addRegOperands() {#aa8b46050f49c0070718cb24eaf4b44b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addRegOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addSrcIdxOperands() {#a49468934edef8e57cda0f8aad36c57e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addSrcIdxOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

### addTILEPairOperands() {#a3d9f319c365afc3c199b8d1f179003bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::addTILEPairOperands (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; Inst, unsigned N)</td>
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



<p>Definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcinst/#ad5a79c04398dc86a3acfe7f8713216eb">llvm::MCInst::addOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a46271d9f83558334670c19539bceb965">llvm::MCOperand::createReg</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#aafb79a3e12c88ca2d15700cfae21334f">Reg</a>.</p>

</div>
</div>

### getEndLoc() {#a6204d6d4477a1f29574110fbb57303f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::X86Operand::getEndLoc ()</td>
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

<p>getEndLoc - Get the location of the last token of this operand.</p>

<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### getImm() {#ad2718878168e750f8341edec2c5c277b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::X86Operand::getImm ()</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a6fbc1ec5a4956ef599b9bcada81b8924">Imm</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4d4f5ec9e5c39e9551b9a1a4cb33bba4">Immediate</a> and <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>.</p>


<p>Referenced by <a href="#a0f7ff37427c7091f644b497d94f4fcff">addAVX512RCOperands</a>, <a href="#a41c70f2eca46ec1276f2519a99ffae11">addImmOperands</a>, <a href="#a589f5952010fac7682138e63127be694">isImmSExti16i8</a>, <a href="#a7de4e0ae5756923ef51185bdc381143a">isImmSExti32i8</a>, <a href="#a1a61fa0a696a44bb2d4c4ccf6349aa75">isImmSExti64i32</a>, <a href="#a36d5302f4f1b10115eee78745413c38f">isImmSExti64i8</a>, <a href="#a6925a00cf927a63d7e37cbfc01b23a4d">isImmUnsignedi4</a> and <a href="#a48dcaf841143a22ebebf70d9d109c5ed">isImmUnsignedi8</a>.</p>

</div>
</div>

### getLocRange() {#a5a0ab8e34b9f38f8e4ebc5c2accd5f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMRange llvm::X86Operand::getLocRange ()</td>
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

<p>getLocRange - Get the range between the first and last token of this operand.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a> and <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a>.</p>

</div>
</div>

### getMemBaseReg() {#a608463d0f6684b87e295a0118621d094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::X86Operand::getMemBaseReg ()</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#aa957005d508608716aace06b32aedff5">addDstIdxOperands</a>, <a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a>, <a href="#a49468934edef8e57cda0f8aad36c57e9">addSrcIdxOperands</a>, <a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a>, <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a>, <a href="#a2c17a8268c0736d291a2bc525584bd90">isMem512_GR16</a>, <a href="#a6de950f79cc96b55dadb92ce88e8c0d3">isMem512_GR32</a>, <a href="#a452acb153ae96fb8bb97ea598d035935">isMem512_GR64</a>, <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### getMemDefaultBaseReg() {#acbdb3bc8b04cbcd6a46c3337be8fbe5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::X86Operand::getMemDefaultBaseReg ()</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a>.</p>

</div>
</div>

### getMemDisp() {#a6be688276a5c36be639bb22fdf476630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCExpr * llvm::X86Operand::getMemDisp ()</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#a3fb809c95f07fa9985fef7e95cf551c8">addAbsMemOperands</a>, <a href="#a46908e32f1979cb4f57d7d26df02bbf7">addMemOffsOperands</a>, <a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a>, <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### getMemFrontendSize() {#ada1f867c585763697989e40cd8fc93d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86Operand::getMemFrontendSize ()</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>

</div>
</div>

### getMemIndexReg() {#ad34b22308a976812df0045fc185f1af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::X86Operand::getMemIndexReg ()</td>
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



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a>, <a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a>, <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a>, <a href="#a6de950f79cc96b55dadb92ce88e8c0d3">isMem512_GR32</a>, <a href="#a452acb153ae96fb8bb97ea598d035935">isMem512_GR64</a>, <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### getMemModeSize() {#ab186130122afce40b50c5322855dec61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86Operand::getMemModeSize ()</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>

</div>
</div>

### getMemScale() {#a61342600f805fab7306064f5d2a0e45f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86Operand::getMemScale ()</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a>, <a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a>, <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a>, <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### getMemSegReg() {#a1b9461bb1c20be7e65e4e91352862862}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::X86Operand::getMemSegReg ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#a46908e32f1979cb4f57d7d26df02bbf7">addMemOffsOperands</a>, <a href="#aa68185209b553ccd5de6d4cd21aae0b7">addMemOperands</a>, <a href="#a49468934edef8e57cda0f8aad36c57e9">addSrcIdxOperands</a>, <a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a> and <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a>.</p>

</div>
</div>

### getOffsetOfLoc() {#ad2a923810ad78e79e28e555b38dcf06b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::X86Operand::getOffsetOfLoc ()</td>
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

<p>getOffsetOfLoc - Get the location of the offset operator.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#afbe28cf220d7fd9cf74ffad6f2d0b60d">OffsetOfLoc</a>.</p>

</div>
</div>

### getOpDecl() {#a511762f6331653150a005519781399a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::X86Operand::getOpDecl ()</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#a5e64e878c06d7163d8691a0fe6fedfc7">OpDecl</a>.</p>

</div>
</div>

### getPrefix() {#a6d87198a14f3a3df41aa3a398cdd4f2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86Operand::getPrefix ()</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#ae3648c88df1546f6df4b9359c334bf2c">Pref</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6adee65df884422f3d6c7e770691409afa">Prefix</a>.</p>

</div>
</div>

### getReg() {#aebf941872ccba8bb10d98c73b8057401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::X86Operand::getReg ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#aafb79a3e12c88ca2d15700cfae21334f">Reg</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>


<p>Referenced by <a href="#a25127edbfd500680786a7964074d8629">addGR16orGR32orGR64Operands</a>, <a href="#a86467b8eb24fee4d7a713a537685d783">addGR32orGR64Operands</a>, <a href="#a1411797182fa22f898f4baf0e3eb7298">addMaskPairOperands</a>, <a href="#aa8b46050f49c0070718cb24eaf4b44b0">addRegOperands</a>, <a href="#a3d9f319c365afc3c199b8d1f179003bd">addTILEPairOperands</a>, <a href="#afb76a59133e0abcf11caf9ab31e32ccc">isGR16orGR32orGR64</a>, <a href="#a40ecb25e849b579a4e02f93af13b0be3">isGR32orGR64</a>, <a href="#a0e3a46f7776ecfcab35620a41e319246">isTILEPair</a>, <a href="#ab60893542cbdf81bc5ebf40d86b59afb">isVectorReg</a>, <a href="#ab3dea0fc883e376307be8706e088d211">isVK16Pair</a>, <a href="#a507d5a660efc16447e5a33658fc35330">isVK1Pair</a>, <a href="#aa5c69cd34baab3b3f3adb0187e20da7e">isVK2Pair</a>, <a href="#a6e12082a24ba1ab62860d441b40cf062">isVK4Pair</a>, <a href="#a09493d661bb5dcd758403f54361ef8ec">isVK8Pair</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### getStartLoc() {#a090e68360629b3b65af38689970fda07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::X86Operand::getStartLoc ()</td>
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

<p>getStartLoc - Get the location of the first token of this operand.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### getSymName() {#afb6f353f69b061783ade3e3e68fc6b86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::X86Operand::getSymName ()</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#a9a99fde5a4b24c8e2129774fe1303c3b">SymName</a>.</p>

</div>
</div>

### getToken() {#ad9de9100bfa3e53ca720f1f24f1aebc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::X86Operand::getToken ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#aed069d1266226c171c267b4a3cc1f6ed">Tok</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a86e1f766d1e8740608e1323dc794048e">Token</a>.</p>

</div>
</div>

### isAbsMem() {#acaeddb20bde113ab89272bb61daa9d4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isAbsMem ()</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a>, <a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a>, <a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a>, <a href="#a3bcf9465c97907fca5466970e0108e54">isMaybeDirectBranchDest</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#a95856220935952727ee0807c3578b0ce">isAbsMem16</a>.</p>

</div>
</div>

### isAbsMem16() {#a95856220935952727ee0807c3578b0ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isAbsMem16 ()</td>
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



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isAVX512RC() {#a6a65cab19ce9662be68fa6b792cc4c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isAVX512RC ()</td>
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



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a>.</p>

</div>
</div>

### isDstIdx() {#ac53ecb38d62cb038d33409628a6acc50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isDstIdx ()</td>
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



<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a>, <a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a>, <a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#ab05d6f488f4a0a52994c68e1913d660f">isDstIdx16</a>, <a href="#ab72330a7aadb08a47f09723e24a8dccc">isDstIdx32</a>, <a href="#a879826874e6b8d02e7c5eb6b97f8cc6e">isDstIdx64</a> and <a href="#a581e54ef28c14b479e09ebc80baeb8fd">isDstIdx8</a>.</p>

</div>
</div>

### isDstIdx16() {#ab05d6f488f4a0a52994c68e1913d660f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isDstIdx16 ()</td>
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



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a> and <a href="#a4dbbc211a989964f8eef960b55ecb9d7">isMem16</a>.</p>

</div>
</div>

### isDstIdx32() {#ab72330a7aadb08a47f09723e24a8dccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isDstIdx32 ()</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a> and <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a>.</p>

</div>
</div>

### isDstIdx64() {#a879826874e6b8d02e7c5eb6b97f8cc6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isDstIdx64 ()</td>
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



<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a> and <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a>.</p>

</div>
</div>

### isDstIdx8() {#a581e54ef28c14b479e09ebc80baeb8fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isDstIdx8 ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#ac53ecb38d62cb038d33409628a6acc50">isDstIdx</a> and <a href="#adf84562f4a788ca9361c7fb9bc099bc1">isMem8</a>.</p>

</div>
</div>

### isDXReg() {#a8ccc7d6c88cf28afe86d5d96955180e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isDXReg ()</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a3948ffaf880576057e2f49f52d58554e">DXRegister</a> and <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>.</p>

</div>
</div>

### isGR16orGR32orGR64() {#afb76a59133e0abcf11caf9ab31e32ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isGR16orGR32orGR64 ()</td>
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



<p>Definition at line 514 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isGR32orGR64() {#a40ecb25e849b579a4e02f93af13b0be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isGR32orGR64 ()</td>
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



<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isImm() {#a10b4dc5a8fcc00ee2c98d93571a2dba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isImm ()</td>
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

<p>isImm - Is this an immediate operand?</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4d4f5ec9e5c39e9551b9a1a4cb33bba4">Immediate</a> and <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>.</p>


<p>Referenced by <a href="#a6a65cab19ce9662be68fa6b792cc4c6c">isAVX512RC</a>, <a href="#a589f5952010fac7682138e63127be694">isImmSExti16i8</a>, <a href="#a7de4e0ae5756923ef51185bdc381143a">isImmSExti32i8</a>, <a href="#a1a61fa0a696a44bb2d4c4ccf6349aa75">isImmSExti64i32</a>, <a href="#a36d5302f4f1b10115eee78745413c38f">isImmSExti64i8</a>, <a href="#a6925a00cf927a63d7e37cbfc01b23a4d">isImmUnsignedi4</a>, <a href="#a48dcaf841143a22ebebf70d9d109c5ed">isImmUnsignedi8</a> and <a href="#a1c42e2fa7f30c3261eb69b9202349dcf">isOffsetOfLocal</a>.</p>

</div>
</div>

### isImmSExti16i8() {#a589f5952010fac7682138e63127be694}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isImmSExti16i8 ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad52471e93b27b0193f93f73496f86217">llvm::isImmSExti16i8Value</a>.</p>

</div>
</div>

### isImmSExti32i8() {#a7de4e0ae5756923ef51185bdc381143a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isImmSExti32i8 ()</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad6b27c3767fdc097716d1334107756cb">llvm::isImmSExti32i8Value</a>.</p>

</div>
</div>

### isImmSExti64i32() {#a1a61fa0a696a44bb2d4c4ccf6349aa75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isImmSExti64i32 ()</td>
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



<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a09a59325b2ffdefd288bb22fe7cb0951">llvm::isImmSExti64i32Value</a>.</p>

</div>
</div>

### isImmSExti64i8() {#a36d5302f4f1b10115eee78745413c38f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isImmSExti64i8 ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a650f6e76f6293524ff3e0f7acd552d47">llvm::isImmSExti64i8Value</a>.</p>

</div>
</div>

### isImmUnsignedi4() {#a6925a00cf927a63d7e37cbfc01b23a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isImmUnsignedi4 ()</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4da951a833dc40ddf6cf056b61c1d321">llvm::isImmUnsignedi4Value</a>.</p>

</div>
</div>

### isImmUnsignedi8() {#a48dcaf841143a22ebebf70d9d109c5ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isImmUnsignedi8 ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa32769e52e1ccdd486c7996e7075508e">llvm::isImmUnsignedi8Value</a>.</p>

</div>
</div>

### isMaybeDirectBranchDest() {#a3bcf9465c97907fca5466970e0108e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMaybeDirectBranchDest ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a>.</p>

</div>
</div>

### isMem() {#a66b38b8c28c19c6d4933ef67ce31d173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem ()</td>
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

<p>isMem - Is this a memory operand?</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#a543e73003a6f5467b84984e27cf1d8a1">isSibMem</a>.</p>

</div>
</div>

### isMem128() {#a514af8717f1887801525c9cdecaf3f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem128 ()</td>
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



<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>

</div>
</div>

### isMem16() {#a4dbbc211a989964f8eef960b55ecb9d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem16 ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#ab05d6f488f4a0a52994c68e1913d660f">isDstIdx16</a> and <a href="#aef9db87ee16dd973efb574e81111afd8">isSrcIdx16</a>.</p>

</div>
</div>

### isMem256() {#aa12981fa558be4fdc323708668b21f56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem256 ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>

</div>
</div>

### isMem32() {#aa3d2680e02d2b8d23e8d5bd2ece87378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem32 ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#ab72330a7aadb08a47f09723e24a8dccc">isDstIdx32</a>, <a href="#ad3a6985e57b1ec85f3ec46e64637ca0c">isMem32_RC128</a>, <a href="#a8cf7c7a8670a44172ba5543a081d8a61">isMem32_RC128X</a>, <a href="#ad701172b63f22a3e238c712fb7656809">isMem32_RC256</a>, <a href="#a4dd65473993a62586ddcab7dde6b26a4">isMem32_RC256X</a>, <a href="#a5c7738b6d6730bbc74899674260e826e">isMem32_RC512</a> and <a href="#a4fedd0acbdb046638a66c07eed76a2fb">isSrcIdx32</a>.</p>

</div>
</div>

### isMem32\_RC128() {#ad3a6985e57b1ec85f3ec46e64637ca0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem32_RC128 ()</td>
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



<p>Definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a> and <a href="#a972b6c9e72ea680cc385a26250c89b75">isMemIndexReg</a>.</p>

</div>
</div>

### isMem32\_RC128X() {#a8cf7c7a8670a44172ba5543a081d8a61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem32_RC128X ()</td>
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



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#aa9fd738474c4c822202e6d73a9509904">llvm::X86II::isXMMReg</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMem32\_RC256() {#ad701172b63f22a3e238c712fb7656809}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem32_RC256 ()</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a> and <a href="#a972b6c9e72ea680cc385a26250c89b75">isMemIndexReg</a>.</p>

</div>
</div>

### isMem32\_RC256X() {#a4dd65473993a62586ddcab7dde6b26a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem32_RC256X ()</td>
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



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#acc7da017f8afea15479e578fcc10a2e2">llvm::X86II::isYMMReg</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMem32\_RC512() {#a5c7738b6d6730bbc74899674260e826e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem32_RC512 ()</td>
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



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a301d6276fae739378e945ebbe0c8dd9b">llvm::X86II::isZMMReg</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMem512() {#a60699c36b71f5e4a45ce7a3c3241ca0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem512 ()</td>
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



<p>Definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#a2c17a8268c0736d291a2bc525584bd90">isMem512_GR16</a>, <a href="#a6de950f79cc96b55dadb92ce88e8c0d3">isMem512_GR32</a> and <a href="#a452acb153ae96fb8bb97ea598d035935">isMem512_GR64</a>.</p>

</div>
</div>

### isMem512\_GR16() {#a2c17a8268c0736d291a2bc525584bd90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem512_GR16 ()</td>
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



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a> and <a href="#a60699c36b71f5e4a45ce7a3c3241ca0e">isMem512</a>.</p>

</div>
</div>

### isMem512\_GR32() {#a6de950f79cc96b55dadb92ce88e8c0d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem512_GR32 ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a> and <a href="#a60699c36b71f5e4a45ce7a3c3241ca0e">isMem512</a>.</p>

</div>
</div>

### isMem512\_GR64() {#a452acb153ae96fb8bb97ea598d035935}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem512_GR64 ()</td>
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



<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a> and <a href="#a60699c36b71f5e4a45ce7a3c3241ca0e">isMem512</a>.</p>

</div>
</div>

### isMem64() {#a1c25df5adbe8323f5075147ffee7de67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem64 ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#a879826874e6b8d02e7c5eb6b97f8cc6e">isDstIdx64</a>, <a href="#a961d85f2caa9d853b7c2f7d80954e838">isMem64_RC128</a>, <a href="#af696541557d6fc4e1c83ad89a588c338">isMem64_RC128X</a>, <a href="#ab8c9fe8831fe1c3d4467467d931f193e">isMem64_RC256</a>, <a href="#a0ad279fcfec0f9227f547633afd2de7e">isMem64_RC256X</a>, <a href="#a8ee7a3ded94c63083e2627cdd7388013">isMem64_RC512</a> and <a href="#afdb62cb4670187d40b51d78a4a66f40c">isSrcIdx64</a>.</p>

</div>
</div>

### isMem64\_RC128() {#a961d85f2caa9d853b7c2f7d80954e838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem64_RC128 ()</td>
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



<p>Definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a> and <a href="#a972b6c9e72ea680cc385a26250c89b75">isMemIndexReg</a>.</p>

</div>
</div>

### isMem64\_RC128X() {#af696541557d6fc4e1c83ad89a588c338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem64_RC128X ()</td>
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



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#aa9fd738474c4c822202e6d73a9509904">llvm::X86II::isXMMReg</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMem64\_RC256() {#ab8c9fe8831fe1c3d4467467d931f193e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem64_RC256 ()</td>
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



<p>Definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a> and <a href="#a972b6c9e72ea680cc385a26250c89b75">isMemIndexReg</a>.</p>

</div>
</div>

### isMem64\_RC256X() {#a0ad279fcfec0f9227f547633afd2de7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem64_RC256X ()</td>
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



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#acc7da017f8afea15479e578fcc10a2e2">llvm::X86II::isYMMReg</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMem64\_RC512() {#a8ee7a3ded94c63083e2627cdd7388013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem64_RC512 ()</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a301d6276fae739378e945ebbe0c8dd9b">llvm::X86II::isZMMReg</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMem8() {#adf84562f4a788ca9361c7fb9bc099bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem8 ()</td>
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



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#a581e54ef28c14b479e09ebc80baeb8fd">isDstIdx8</a>, <a href="#a420cac2d28e139b40796648f5ade77e5">isSrcIdx8</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### isMem80() {#aeba881e19bd5892a14da9e76805cd904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMem80 ()</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>

</div>
</div>

### isMemIndexReg() {#a972b6c9e72ea680cc385a26250c89b75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemIndexReg (unsigned LowR, unsigned HighR)</td>
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



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#ad3a6985e57b1ec85f3ec46e64637ca0c">isMem32_RC128</a>, <a href="#ad701172b63f22a3e238c712fb7656809">isMem32_RC256</a>, <a href="#a961d85f2caa9d853b7c2f7d80954e838">isMem64_RC128</a> and <a href="#ab8c9fe8831fe1c3d4467467d931f193e">isMem64_RC256</a>.</p>

</div>
</div>

### isMemOffs() {#a8aa4944c7ea06fae8090787f7f2a3dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs ()</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a>, <a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>


<p>Referenced by <a href="#ad795a3f8e6d70a29a4032d2951425f6a">isMemOffs16_16</a>, <a href="#aee281ae3219d572cbbf370d637797f91">isMemOffs16_32</a>, <a href="#a6cb65977f1e80f2f00b35383a3700249">isMemOffs16_8</a>, <a href="#a9d6c3460a1b79625d27b62b82c5a6013">isMemOffs32_16</a>, <a href="#a305a25a19fb1523f61fd242ad66f1db5">isMemOffs32_32</a>, <a href="#af1b78c81c7292bbc4b005c5c74ec57fe">isMemOffs32_64</a>, <a href="#a52d469d804500ad3ce26991be9ee8761">isMemOffs32_8</a>, <a href="#abdcb17eda7ce4b3ad6feba1ba14083e3">isMemOffs64_16</a>, <a href="#a10cf4e0abda37a7725b14e9bcc419591">isMemOffs64_32</a>, <a href="#a011f73c1ea251da7e051ae168540dded">isMemOffs64_64</a> and <a href="#a5779b19cdf365d747c0b05102955ac02">isMemOffs64_8</a>.</p>

</div>
</div>

### isMemOffs16\_16() {#ad795a3f8e6d70a29a4032d2951425f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs16_16 ()</td>
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



<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs16\_32() {#aee281ae3219d572cbbf370d637797f91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs16_32 ()</td>
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



<p>Definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs16\_8() {#a6cb65977f1e80f2f00b35383a3700249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs16_8 ()</td>
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



<p>Definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs32\_16() {#a9d6c3460a1b79625d27b62b82c5a6013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs32_16 ()</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs32\_32() {#a305a25a19fb1523f61fd242ad66f1db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs32_32 ()</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs32\_64() {#af1b78c81c7292bbc4b005c5c74ec57fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs32_64 ()</td>
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



<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs32\_8() {#a52d469d804500ad3ce26991be9ee8761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs32_8 ()</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs64\_16() {#abdcb17eda7ce4b3ad6feba1ba14083e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs64_16 ()</td>
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



<p>Definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs64\_32() {#a10cf4e0abda37a7725b14e9bcc419591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs64_32 ()</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs64\_64() {#a011f73c1ea251da7e051ae168540dded}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs64_64 ()</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemOffs64\_8() {#a5779b19cdf365d747c0b05102955ac02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemOffs64_8 ()</td>
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



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isMemUnsized() {#ad14239f4470c58ee36c34706a2e96d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemUnsized ()</td>
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



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>.</p>

</div>
</div>

### isMemUseUpRegs() {#a10c7546ba631e3b4ef89ba82f87ab07f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isMemUseUpRegs ()</td>
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

<p>isMemUseUpRegs - Is memory operand use up regs, for example, intel MS inline asm may use ARR[baseReg + IndexReg + ...] which may use up regs in [...] expr, so ARR[baseReg + IndexReg + ...] can not use extra reg for ARR.</p>


<p>For example, calculating ARR address to a reg or use another base reg in PIC model.</p>


<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#a32f1c7a8986b0d7bd5a076806bb00b81">UseUpRegs</a>.</p>

</div>
</div>

### isOffsetOfLocal() {#a1c42e2fa7f30c3261eb69b9202349dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isOffsetOfLocal ()</td>
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

<p>isOffsetOfLocal - Do we need to emit code to get the offset of the local variable, rather than its value?</p>


<p>Only valid when parsing MS-style inline assembly.</p>


<p>Definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a6fbc1ec5a4956ef599b9bcada81b8924">Imm</a> and <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a>.</p>

</div>
</div>

### isPrefix() {#a0cb6b9ca4ef45a66c8243ecf2b663b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isPrefix ()</td>
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



<p>Definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6adee65df884422f3d6c7e770691409afa">Prefix</a>.</p>

</div>
</div>

### isReg() {#a65db4de47ce9d66f1dfc97ae7c3b46b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isReg ()</td>
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

<p>isReg - Is this a register operand?</p>

<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### isSibMem() {#a543e73003a6f5467b84984e27cf1d8a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isSibMem ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a66b38b8c28c19c6d4933ef67ce31d173">isMem</a> and <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>.</p>

</div>
</div>

### isSrcIdx() {#a441db67b29c2e65b957258aa12b3dfa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isSrcIdx ()</td>
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



<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a>, <a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#aef9db87ee16dd973efb574e81111afd8">isSrcIdx16</a>, <a href="#a4fedd0acbdb046638a66c07eed76a2fb">isSrcIdx32</a>, <a href="#afdb62cb4670187d40b51d78a4a66f40c">isSrcIdx64</a> and <a href="#a420cac2d28e139b40796648f5ade77e5">isSrcIdx8</a>.</p>

</div>
</div>

### isSrcIdx16() {#aef9db87ee16dd973efb574e81111afd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isSrcIdx16 ()</td>
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



<p>Definition at line 434 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a4dbbc211a989964f8eef960b55ecb9d7">isMem16</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### isSrcIdx32() {#a4fedd0acbdb046638a66c07eed76a2fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isSrcIdx32 ()</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### isSrcIdx64() {#afdb62cb4670187d40b51d78a4a66f40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isSrcIdx64 ()</td>
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



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### isSrcIdx8() {#a420cac2d28e139b40796648f5ade77e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isSrcIdx8 ()</td>
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



<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#adf84562f4a788ca9361c7fb9bc099bc1">isMem8</a> and <a href="#a441db67b29c2e65b957258aa12b3dfa9">isSrcIdx</a>.</p>

</div>
</div>

### isTILEPair() {#a0e3a46f7776ecfcab35620a41e319246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isTILEPair ()</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isToken() {#af5e18bddceffd46f90828fb91143e684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isToken ()</td>
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

<p>isToken - Is this a token operand?</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a86e1f766d1e8740608e1323dc794048e">Token</a>.</p>

</div>
</div>

### isVectorReg() {#ab60893542cbdf81bc5ebf40d86b59afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isVectorReg ()</td>
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



<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isVK16Pair() {#ab3dea0fc883e376307be8706e088d211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isVK16Pair ()</td>
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



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isVK1Pair() {#a507d5a660efc16447e5a33658fc35330}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isVK1Pair ()</td>
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



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isVK2Pair() {#aa5c69cd34baab3b3f3adb0187e20da7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isVK2Pair ()</td>
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



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isVK4Pair() {#a6e12082a24ba1ab62860d441b40cf062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isVK4Pair ()</td>
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



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### isVK8Pair() {#a09493d661bb5dcd758403f54361ef8ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::isVK8Pair ()</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>.</p>

</div>
</div>

### needAddressOf() {#abf8c4a729ab0feb373fa212d3cb8b0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::needAddressOf ()</td>
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

<p>needAddressOf - Do we need to emit code to get the address of the variable/label?</p>


<p>Only valid when parsing MS-style inline assembly.</p>


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Reference <a href="#a23c39c21b5c7e8f2351b674b173cdd10">AddressOf</a>.</p>

</div>
</div>

### print() {#a59aaa2e922d6173cbeaed43a2d58423a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>print - Print a debug representation of the operand to the given stream.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa66e286cc65e62341501e5b26feade28d">llvm::MCExpr::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a7b0fa1a82461032cdf16b7f6c59f0a6a">llvm::StringRef::data</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a3948ffaf880576057e2f49f52d58554e">DXRegister</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#af5d6e67c11188675c1309e098afac194">llvm::MCExpr::getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol/#a57c7b2b9784361914262eeb0a6f0b18d">llvm::MCSymbol::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/x86intelinstprinter/#adf85cc805086cbd68bc73592c3d5d904">llvm::X86IntelInstPrinter::getRegisterName</a>, <a href="#a6fbc1ec5a4956ef599b9bcada81b8924">Imm</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4d4f5ec9e5c39e9551b9a1a4cb33bba4">Immediate</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#a74a7fac6c70b520b88f61f77b24716cf">Mem</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>, <a href="#ae3648c88df1546f6df4b9359c334bf2c">Pref</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6adee65df884422f3d6c7e770691409afa">Prefix</a>, <a href="#aafb79a3e12c88ca2d15700cfae21334f">Reg</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexpr/#a83112ba0cecd7a7add9f1f9c441d606fa8cbc19c1660252a30c030fa945999a91">llvm::MCExpr::SymbolRef</a>, <a href="#aed069d1266226c171c267b4a3cc1f6ed">Tok</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a86e1f766d1e8740608e1323dc794048e">Token</a>.</p>

</div>
</div>

### setTokenValue() {#a450d0abfd7db79e602bd9ded8967a84a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86Operand::setTokenValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Value)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0a138060ad031327db33e5d3cb756d99">Kind</a>, <a href="#aed069d1266226c171c267b4a3cc1f6ed">Tok</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a86e1f766d1e8740608e1323dc794048e">Token</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#abf6810b3012a3daaa208562355c1beb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union llvm::X86Operand llvm::X86Operand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>

</div>
</div>

### AddressOf {#a23c39c21b5c7e8f2351b674b173cdd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::AddressOf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a>, <a href="#abf8c4a729ab0feb373fa212d3cb8b0da">needAddressOf</a> and <a href="#a1ae56d884e0aa40722ca010094914d00">X86Operand</a>.</p>

</div>
</div>

### EndLoc {#a2782ef3eed6a4450c187492800fd6bd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::X86Operand::EndLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a31046024a7c3714c5864155dd5b4b740">CreateDXReg</a>, <a href="#a1148364374905ec7fe1d2e05f8a97a58">CreateImm</a>, <a href="#a706b11b0c09a7d9e06208ff685a44fe3">CreateMem</a>, <a href="#ab05d1fa246fe62a966a8b51f755bcb39">CreateMem</a>, <a href="#a2d42b1611036b87b39d2a79336f18dda">CreatePrefix</a>, <a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a>, <a href="#acde7256b4b06b4bd9b75088863c32265">CreateToken</a>, <a href="#a6204d6d4477a1f29574110fbb57303f3">getEndLoc</a>, <a href="#a5a0ab8e34b9f38f8e4ebc5c2accd5f9b">getLocRange</a> and <a href="#a1ae56d884e0aa40722ca010094914d00">X86Operand</a>.</p>

</div>
</div>

### Imm {#a6fbc1ec5a4956ef599b9bcada81b8924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct ImmOp llvm::X86Operand::Imm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a1c42e2fa7f30c3261eb69b9202349dcf">isOffsetOfLocal</a> and <a href="#a59aaa2e922d6173cbeaed43a2d58423a">print</a>.</p>

</div>
</div>

### Kind {#a0a138060ad031327db33e5d3cb756d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86Operand::KindTy llvm::X86Operand::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#ad2718878168e750f8341edec2c5c277b">getImm</a>, <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#acbdb3bc8b04cbcd6a46c3337be8fbe5a">getMemDefaultBaseReg</a>, <a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a>, <a href="#ada1f867c585763697989e40cd8fc93d9">getMemFrontendSize</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a>, <a href="#ab186130122afce40b50c5322855dec61">getMemModeSize</a>, <a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a>, <a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a>, <a href="#a6d87198a14f3a3df41aa3a398cdd4f2b">getPrefix</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a>, <a href="#ad9de9100bfa3e53ca720f1f24f1aebc3">getToken</a>, <a href="#acaeddb20bde113ab89272bb61daa9d4b">isAbsMem</a>, <a href="#a8ccc7d6c88cf28afe86d5d96955180e9">isDXReg</a>, <a href="#afb76a59133e0abcf11caf9ab31e32ccc">isGR16orGR32orGR64</a>, <a href="#a40ecb25e849b579a4e02f93af13b0be3">isGR32orGR64</a>, <a href="#a10b4dc5a8fcc00ee2c98d93571a2dba1">isImm</a>, <a href="#a3bcf9465c97907fca5466970e0108e54">isMaybeDirectBranchDest</a>, <a href="#a66b38b8c28c19c6d4933ef67ce31d173">isMem</a>, <a href="#a514af8717f1887801525c9cdecaf3f2c">isMem128</a>, <a href="#a4dbbc211a989964f8eef960b55ecb9d7">isMem16</a>, <a href="#aa12981fa558be4fdc323708668b21f56">isMem256</a>, <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a>, <a href="#a60699c36b71f5e4a45ce7a3c3241ca0e">isMem512</a>, <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a>, <a href="#adf84562f4a788ca9361c7fb9bc099bc1">isMem8</a>, <a href="#aeba881e19bd5892a14da9e76805cd904">isMem80</a>, <a href="#a972b6c9e72ea680cc385a26250c89b75">isMemIndexReg</a>, <a href="#a8aa4944c7ea06fae8090787f7f2a3dda">isMemOffs</a>, <a href="#ad14239f4470c58ee36c34706a2e96d95">isMemUnsized</a>, <a href="#a0cb6b9ca4ef45a66c8243ecf2b663b48">isPrefix</a>, <a href="#a65db4de47ce9d66f1dfc97ae7c3b46b0">isReg</a>, <a href="#a0e3a46f7776ecfcab35620a41e319246">isTILEPair</a>, <a href="#af5e18bddceffd46f90828fb91143e684">isToken</a>, <a href="#ab60893542cbdf81bc5ebf40d86b59afb">isVectorReg</a>, <a href="#ab3dea0fc883e376307be8706e088d211">isVK16Pair</a>, <a href="#a507d5a660efc16447e5a33658fc35330">isVK1Pair</a>, <a href="#aa5c69cd34baab3b3f3adb0187e20da7e">isVK2Pair</a>, <a href="#a6e12082a24ba1ab62860d441b40cf062">isVK4Pair</a>, <a href="#a09493d661bb5dcd758403f54361ef8ec">isVK8Pair</a>, <a href="#a59aaa2e922d6173cbeaed43a2d58423a">print</a>, <a href="#a450d0abfd7db79e602bd9ded8967a84a">setTokenValue</a> and <a href="#a1ae56d884e0aa40722ca010094914d00">X86Operand</a>.</p>

</div>
</div>

### Mem {#a74a7fac6c70b520b88f61f77b24716cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct MemOp llvm::X86Operand::Mem</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a608463d0f6684b87e295a0118621d094">getMemBaseReg</a>, <a href="#acbdb3bc8b04cbcd6a46c3337be8fbe5a">getMemDefaultBaseReg</a>, <a href="#a6be688276a5c36be639bb22fdf476630">getMemDisp</a>, <a href="#ada1f867c585763697989e40cd8fc93d9">getMemFrontendSize</a>, <a href="#ad34b22308a976812df0045fc185f1af7">getMemIndexReg</a>, <a href="#ab186130122afce40b50c5322855dec61">getMemModeSize</a>, <a href="#a61342600f805fab7306064f5d2a0e45f">getMemScale</a>, <a href="#a1b9461bb1c20be7e65e4e91352862862">getMemSegReg</a>, <a href="#a95856220935952727ee0807c3578b0ce">isAbsMem16</a>, <a href="#a3bcf9465c97907fca5466970e0108e54">isMaybeDirectBranchDest</a>, <a href="#a514af8717f1887801525c9cdecaf3f2c">isMem128</a>, <a href="#a4dbbc211a989964f8eef960b55ecb9d7">isMem16</a>, <a href="#aa12981fa558be4fdc323708668b21f56">isMem256</a>, <a href="#aa3d2680e02d2b8d23e8d5bd2ece87378">isMem32</a>, <a href="#a8cf7c7a8670a44172ba5543a081d8a61">isMem32_RC128X</a>, <a href="#a4dd65473993a62586ddcab7dde6b26a4">isMem32_RC256X</a>, <a href="#a5c7738b6d6730bbc74899674260e826e">isMem32_RC512</a>, <a href="#a60699c36b71f5e4a45ce7a3c3241ca0e">isMem512</a>, <a href="#a1c25df5adbe8323f5075147ffee7de67">isMem64</a>, <a href="#af696541557d6fc4e1c83ad89a588c338">isMem64_RC128X</a>, <a href="#a0ad279fcfec0f9227f547633afd2de7e">isMem64_RC256X</a>, <a href="#a8ee7a3ded94c63083e2627cdd7388013">isMem64_RC512</a>, <a href="#adf84562f4a788ca9361c7fb9bc099bc1">isMem8</a>, <a href="#aeba881e19bd5892a14da9e76805cd904">isMem80</a>, <a href="#a972b6c9e72ea680cc385a26250c89b75">isMemIndexReg</a>, <a href="#ad795a3f8e6d70a29a4032d2951425f6a">isMemOffs16_16</a>, <a href="#aee281ae3219d572cbbf370d637797f91">isMemOffs16_32</a>, <a href="#a6cb65977f1e80f2f00b35383a3700249">isMemOffs16_8</a>, <a href="#a9d6c3460a1b79625d27b62b82c5a6013">isMemOffs32_16</a>, <a href="#a305a25a19fb1523f61fd242ad66f1db5">isMemOffs32_32</a>, <a href="#af1b78c81c7292bbc4b005c5c74ec57fe">isMemOffs32_64</a>, <a href="#a52d469d804500ad3ce26991be9ee8761">isMemOffs32_8</a>, <a href="#abdcb17eda7ce4b3ad6feba1ba14083e3">isMemOffs64_16</a>, <a href="#a10cf4e0abda37a7725b14e9bcc419591">isMemOffs64_32</a>, <a href="#a011f73c1ea251da7e051ae168540dded">isMemOffs64_64</a>, <a href="#a5779b19cdf365d747c0b05102955ac02">isMemOffs64_8</a>, <a href="#ad14239f4470c58ee36c34706a2e96d95">isMemUnsized</a>, <a href="#a543e73003a6f5467b84984e27cf1d8a1">isSibMem</a> and <a href="#a59aaa2e922d6173cbeaed43a2d58423a">print</a>.</p>

</div>
</div>

### OffsetOfLoc {#afbe28cf220d7fd9cf74ffad6f2d0b60d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::X86Operand::OffsetOfLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a> and <a href="#ad2a923810ad78e79e28e555b38dcf06b">getOffsetOfLoc</a>.</p>

</div>
</div>

### OpDecl {#a5e64e878c06d7163d8691a0fe6fedfc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::X86Operand::OpDecl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a1148364374905ec7fe1d2e05f8a97a58">CreateImm</a>, <a href="#a706b11b0c09a7d9e06208ff685a44fe3">CreateMem</a>, <a href="#ab05d1fa246fe62a966a8b51f755bcb39">CreateMem</a>, <a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a>, <a href="#a511762f6331653150a005519781399a1">getOpDecl</a> and <a href="#a1ae56d884e0aa40722ca010094914d00">X86Operand</a>.</p>

</div>
</div>

### Pref {#ae3648c88df1546f6df4b9359c334bf2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct PrefOp llvm::X86Operand::Pref</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a6d87198a14f3a3df41aa3a398cdd4f2b">getPrefix</a> and <a href="#a59aaa2e922d6173cbeaed43a2d58423a">print</a>.</p>

</div>
</div>

### Reg {#aafb79a3e12c88ca2d15700cfae21334f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct RegOp llvm::X86Operand::Reg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a1411797182fa22f898f4baf0e3eb7298">addMaskPairOperands</a>, <a href="#a3d9f319c365afc3c199b8d1f179003bd">addTILEPairOperands</a>, <a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a>, <a href="#aebf941872ccba8bb10d98c73b8057401">getReg</a> and <a href="#a59aaa2e922d6173cbeaed43a2d58423a">print</a>.</p>

</div>
</div>

### StartLoc {#a458ac7437c502c23e0d0c4caf62576e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMLoc llvm::X86Operand::StartLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a31046024a7c3714c5864155dd5b4b740">CreateDXReg</a>, <a href="#a1148364374905ec7fe1d2e05f8a97a58">CreateImm</a>, <a href="#a706b11b0c09a7d9e06208ff685a44fe3">CreateMem</a>, <a href="#ab05d1fa246fe62a966a8b51f755bcb39">CreateMem</a>, <a href="#a2d42b1611036b87b39d2a79336f18dda">CreatePrefix</a>, <a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a>, <a href="#a5a0ab8e34b9f38f8e4ebc5c2accd5f9b">getLocRange</a>, <a href="#a090e68360629b3b65af38689970fda07">getStartLoc</a> and <a href="#a1ae56d884e0aa40722ca010094914d00">X86Operand</a>.</p>

</div>
</div>

### SymName {#a9a99fde5a4b24c8e2129774fe1303c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::X86Operand::SymName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a1148364374905ec7fe1d2e05f8a97a58">CreateImm</a>, <a href="#a706b11b0c09a7d9e06208ff685a44fe3">CreateMem</a>, <a href="#ab05d1fa246fe62a966a8b51f755bcb39">CreateMem</a>, <a href="#a55c25fac84462530fd620a9d92ea3723">CreateReg</a> and <a href="#afb6f353f69b061783ade3e3e68fc6b86">getSymName</a>.</p>

</div>
</div>

### Tok {#aed069d1266226c171c267b4a3cc1f6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct TokOp llvm::X86Operand::Tok</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#ad9de9100bfa3e53ca720f1f24f1aebc3">getToken</a>, <a href="#a59aaa2e922d6173cbeaed43a2d58423a">print</a> and <a href="#a450d0abfd7db79e602bd9ded8967a84a">setTokenValue</a>.</p>

</div>
</div>

### UseUpRegs {#a32f1c7a8986b0d7bd5a076806bb00b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86Operand::UseUpRegs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This used for inline asm which may specify base reg and index reg for <a href="/web-llvm/docs/api/structs/llvm/x86operand/memop">MemOp</a>.</p>


<p>e.g. ARR[eax + ecx*4], so no extra reg can be used for <a href="/web-llvm/docs/api/structs/llvm/x86operand/memop">MemOp</a>.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>Referenced by <a href="#a706b11b0c09a7d9e06208ff685a44fe3">CreateMem</a>, <a href="#ab05d1fa246fe62a966a8b51f755bcb39">CreateMem</a> and <a href="#a10c7546ba631e3b4ef89ba82f87ab07f">isMemUseUpRegs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### CreateDXReg() {#a31046024a7c3714c5864155dd5b4b740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; llvm::X86Operand::CreateDXReg (<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
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



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a3948ffaf880576057e2f49f52d58554e">DXRegister</a>, <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a> and <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a>.</p>

</div>
</div>

### CreateImm() {#a1148364374905ec7fe1d2e05f8a97a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; llvm::X86Operand::CreateImm (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Val, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymName=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(), void * OpDecl=nullptr, bool GlobalRef=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4d4f5ec9e5c39e9551b9a1a4cb33bba4">Immediate</a>, <a href="#a5e64e878c06d7163d8691a0fe6fedfc7">OpDecl</a>, <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a> and <a href="#a9a99fde5a4b24c8e2129774fe1303c3b">SymName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### CreateMem() {#a706b11b0c09a7d9e06208ff685a44fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; llvm::X86Operand::CreateMem (unsigned ModeSize, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Disp, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc, unsigned Size=0, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymName=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(), void * OpDecl=nullptr, unsigned FrontendSize=0, bool UseUpRegs=false, bool MaybeDirectBranchDest=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Create an absolute memory operand.</p>

<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>, <a href="#a5e64e878c06d7163d8691a0fe6fedfc7">OpDecl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a>, <a href="#a9a99fde5a4b24c8e2129774fe1303c3b">SymName</a> and <a href="#a32f1c7a8986b0d7bd5a076806bb00b81">UseUpRegs</a>.</p>

</div>
</div>

### CreateMem() {#ab05d1fa246fe62a966a8b51f755bcb39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; llvm::X86Operand::CreateMem (unsigned ModeSize, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> SegReg, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcexpr">MCExpr</a> * Disp, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> BaseReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> IndexReg, unsigned Scale, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc, unsigned Size=0, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> DefaultBaseReg=<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>(), <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymName=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(), void * OpDecl=nullptr, unsigned FrontendSize=0, bool UseUpRegs=false, bool MaybeDirectBranchDest=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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

<p>Create a generalized memory operand.</p>

<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a4774cb24751b3e5defd433e8186d7722">Memory</a>, <a href="#a5e64e878c06d7163d8691a0fe6fedfc7">OpDecl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a>, <a href="#a9a99fde5a4b24c8e2129774fe1303c3b">SymName</a> and <a href="#a32f1c7a8986b0d7bd5a076806bb00b81">UseUpRegs</a>.</p>

</div>
</div>

### CreatePrefix() {#a2d42b1611036b87b39d2a79336f18dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; llvm::X86Operand::CreatePrefix (unsigned Prefixes, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc)</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6adee65df884422f3d6c7e770691409afa">Prefix</a> and <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### CreateReg() {#a55c25fac84462530fd620a9d92ea3723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; llvm::X86Operand::CreateReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> StartLoc, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> EndLoc, bool AddressOf=false, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> OffsetOfLoc=<a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a>(), <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SymName=<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>(), void * OpDecl=nullptr)</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a23c39c21b5c7e8f2351b674b173cdd10">AddressOf</a>, <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>, <a href="#afbe28cf220d7fd9cf74ffad6f2d0b60d">OffsetOfLoc</a>, <a href="#a5e64e878c06d7163d8691a0fe6fedfc7">OpDecl</a>, <a href="#aafb79a3e12c88ca2d15700cfae21334f">Reg</a>, <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a19631764fceb06d0928ba879ad4abfee">Register</a>, <a href="#a458ac7437c502c23e0d0c4caf62576e6">StartLoc</a> and <a href="#a9a99fde5a4b24c8e2129774fe1303c3b">SymName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

### CreateToken() {#acde7256b4b06b4bd9b75088863c32265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; X86Operand &gt; llvm::X86Operand::CreateToken (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/smloc">SMLoc</a> Loc)</td>
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



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a>.</p>


<p>References <a href="#a2782ef3eed6a4450c187492800fd6bd0">EndLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/smloc/#a16ebb09610e55f63cfc55f28e3a56ad5">llvm::SMLoc::getFromPointer</a> and <a href="#a4edd4aeb4f5f68994c7dfd8d33bc15c6a86e1f766d1e8740608e1323dc794048e">Token</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86asmparser-cpp-/x86asmparser/#abf6230cdb8093ea54524821d036b2203">anonymous{X86AsmParser.cpp}::X86AsmParser::parseInstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/asmparser/x86operand-h">X86Operand.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
