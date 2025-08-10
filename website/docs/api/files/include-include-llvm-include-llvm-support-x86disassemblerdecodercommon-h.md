---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `X86DisassemblerDecoderCommon.h` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/datatypes-h">llvm/Support/DataTypes.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/x86disassembler">X86Disassembler</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier">OperandSpecifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specification for how to extract and interpret one operand. <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/operandspecifier/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62a3fc430e98f080dc7e39325d2b9e54">INSTRUCTIONS_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerInstrSpecifiers</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5289563c2fd129668b3dfc2bcb36f1a9">CONTEXTS_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerContexts</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae053f9e80d644f47a6ee19185739162b">ONEBYTE_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerOneByteOpcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bfb472dc63adf5ea8919f054d4450e2">TWOBYTE_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerTwoByteOpcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892daf9647ea098765cb833eb8596234">THREEBYTE38_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerThreeByte38Opcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a9bb5a76c1dd6a02bb96ef407a6cb7d">THREEBYTE3A_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerThreeByte3AOpcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a6f64aec6a805d641a17c87a9d00b9">XOP8_MAP_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerXOP8Opcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349d73e2f39af064d9999d7780f9897d">XOP9_MAP_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerXOP9Opcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df14d49cac592bc2e51794ad434e9b2">XOPA_MAP_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerXOPAOpcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4856eb908bad869295dd7568a8d735c1">THREEDNOW_MAP_SYM</a>&nbsp;&nbsp;&nbsp;x86Disassembler3DNowOpcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a220b2f46f604cad58d418fb355d78865">MAP4_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerMap4Opcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae838bb5a1c81d099c811f6348ca9df">MAP5_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerMap5Opcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab695124c0e0dbddc8f1dbe567ee211de">MAP6_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerMap6Opcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2f331e9ce69df8e258199ea9c1f951">MAP7_SYM</a>&nbsp;&nbsp;&nbsp;x86DisassemblerMap7Opcodes</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a911147fbec5d6dbd706b84d032e428c4">INSTRUCTIONS_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerInstrSpecifiers"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9980d2d5b8167d598e8895c03f269849">CONTEXTS_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerContexts"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30409ed7db75f981d4c6e201698c4835">ONEBYTE_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerOneByteOpcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e160d69881ebf684f92a2ae79dbfb8">TWOBYTE_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerTwoByteOpcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5c7f622af95a2ab79356cb210306e0">THREEBYTE38_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerThreeByte38Opcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64cb507c60ff05e2a5413b86927b69d">THREEBYTE3A_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerThreeByte3AOpcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af69c8d51dace289192a3dc3dab217682">XOP8_MAP_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerXOP8Opcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae50369fe86d5409157eb30cb44fdd74d">XOP9_MAP_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerXOP9Opcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe22b0aeda49b6138cfc2041c3352bc3">XOPA_MAP_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerXOPAOpcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab58c0a83069532783cb9c38ab21cab3b">THREEDNOW_MAP_STR</a>&nbsp;&nbsp;&nbsp;"x86Disassembler3DNowOpcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db8bd0ffc1292e4732b5992e23dd8d0">MAP4_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerMap4Opcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5904e753ad8cb49d12e1e53f0f67a40">MAP5_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerMap5Opcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a961c572fedd37e035b6dec770c037622">MAP6_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerMap6Opcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac39cccdef04f9f22651bf31b3975ce29">MAP7_STR</a>&nbsp;&nbsp;&nbsp;"x86DisassemblerMap7Opcodes"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a254172912b86aaedc5718b18fa05d6cf">INSTRUCTION_CONTEXTS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(n, r, d)&nbsp;&nbsp;&nbsp;n,</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5406c5ad64936fc7e044d3dbbeeea377">MODRMTYPES</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86f2a86d6e853bb297bc32ba3085bcea">ENUM_ENTRY</a>(n)&nbsp;&nbsp;&nbsp;n,</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fd192bea7092fa66a95e4ca0cf236fe">CASE_ENCODING_RM</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7d2bc3ef8e759126222de6b4d440fe">CASE_ENCODING_VSIB</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a017007d191a0978aa8cb866f4b89cae3">ENCODINGS</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8978b44e045a2606fae8089e314d610">ENUM_ENTRY</a>(n, d)&nbsp;&nbsp;&nbsp;n,</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85d942a7aa8b718de83d06343f12aa8a">TYPES</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7397ec807bf36eb3fe3ef24b18dd9c2">ENUM_ENTRY</a>(n, d)&nbsp;&nbsp;&nbsp;n,</td>
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


<div class="doxySectionDef">

## Macro Definitions

### CASE\_ENCODING\_RM {#a3fd192bea7092fa66a95e4ca0cf236fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_ENCODING_RM&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case ENCODING_RM:                                                            \
  case ENCODING_RM_CD2:                                                        \
  case ENCODING_RM_CD4:                                                        \
  case ENCODING_RM_CD8:                                                        \
  case ENCODING_RM_CD16:                                                       \
  case ENCODING_RM_CD32:                                                       \
  case ENCODING_RM_CD64
</div>
</dd>
</dl>

<p>Definition at line 423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a42be988af3ae0e352befa7189bd50936">readOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### CASE\_ENCODING\_VSIB {#a2a7d2bc3ef8e759126222de6b4d440fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CASE_ENCODING_VSIB&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  case ENCODING_VSIB:                                                          \
  case ENCODING_VSIB_CD2:                                                      \
  case ENCODING_VSIB_CD4:                                                      \
  case ENCODING_VSIB_CD8:                                                      \
  case ENCODING_VSIB_CD16:                                                     \
  case ENCODING_VSIB_CD32:                                                     \
  case ENCODING_VSIB_CD64
</div>
</dd>
</dl>

<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a42be988af3ae0e352befa7189bd50936">readOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aeb806eaaca65c1a593f5af3078798819">translateOperand</a>.</p>

</div>
</div>

### CONTEXTS\_STR {#a9980d2d5b8167d598e8895c03f269849}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CONTEXTS_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerContexts"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### CONTEXTS\_SYM {#a5289563c2fd129668b3dfc2bcb36f1a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define CONTEXTS_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerContexts</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ENCODINGS {#a017007d191a0978aa8cb866f4b89cae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENCODINGS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ENUM\_ENTRY {#a2e2304974f2b7174c391028b0fb91efd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENUM_ENTRY(n, r, d)&nbsp;&nbsp;&nbsp;n,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ENUM\_ENTRY {#a86f2a86d6e853bb297bc32ba3085bcea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENUM_ENTRY(n)&nbsp;&nbsp;&nbsp;n,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ENUM\_ENTRY {#ae8978b44e045a2606fae8089e314d610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENUM_ENTRY(n, d)&nbsp;&nbsp;&nbsp;n,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ENUM\_ENTRY {#ae7397ec807bf36eb3fe3ef24b18dd9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENUM_ENTRY(n, d)&nbsp;&nbsp;&nbsp;n,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### INSTRUCTION\_CONTEXTS {#a254172912b86aaedc5718b18fa05d6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTRUCTION_CONTEXTS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### INSTRUCTIONS\_STR {#a911147fbec5d6dbd706b84d032e428c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTRUCTIONS_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerInstrSpecifiers"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### INSTRUCTIONS\_SYM {#a62a3fc430e98f080dc7e39325d2b9e54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define INSTRUCTIONS_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerInstrSpecifiers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### MAP4\_STR {#a3db8bd0ffc1292e4732b5992e23dd8d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP4_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerMap4Opcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### MAP4\_SYM {#a220b2f46f604cad58d418fb355d78865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP4_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerMap4Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### MAP5\_STR {#af5904e753ad8cb49d12e1e53f0f67a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP5_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerMap5Opcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### MAP5\_SYM {#aeae838bb5a1c81d099c811f6348ca9df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP5_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerMap5Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### MAP6\_STR {#a961c572fedd37e035b6dec770c037622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP6_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerMap6Opcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### MAP6\_SYM {#ab695124c0e0dbddc8f1dbe567ee211de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP6_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerMap6Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### MAP7\_STR {#ac39cccdef04f9f22651bf31b3975ce29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP7_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerMap7Opcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### MAP7\_SYM {#aca2f331e9ce69df8e258199ea9c1f951}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP7_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerMap7Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### MODRMTYPES {#a5406c5ad64936fc7e044d3dbbeeea377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MODRMTYPES&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  <a href="#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(MODRM_ONEENTRY)                                                   \
  <a href="#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(MODRM_SPLITRM)                                                    \
  <a href="#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(MODRM_SPLITMISC)                                                  \
  <a href="#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(MODRM_SPLITREG)                                                   \
  <a href="#a2e2304974f2b7174c391028b0fb91efd">ENUM_ENTRY</a>(MODRM_FULL)
</div>
</dd>
</dl>

<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ONEBYTE\_STR {#a30409ed7db75f981d4c6e201698c4835}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ONEBYTE_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerOneByteOpcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### ONEBYTE\_SYM {#ae053f9e80d644f47a6ee19185739162b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ONEBYTE_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerOneByteOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### THREEBYTE38\_STR {#a0e5c7f622af95a2ab79356cb210306e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREEBYTE38_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerThreeByte38Opcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### THREEBYTE38\_SYM {#a892daf9647ea098765cb833eb8596234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREEBYTE38_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerThreeByte38Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### THREEBYTE3A\_STR {#aa64cb507c60ff05e2a5413b86927b69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREEBYTE3A_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerThreeByte3AOpcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### THREEBYTE3A\_SYM {#a6a9bb5a76c1dd6a02bb96ef407a6cb7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREEBYTE3A_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerThreeByte3AOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### THREEDNOW\_MAP\_STR {#ab58c0a83069532783cb9c38ab21cab3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREEDNOW_MAP_STR&nbsp;&nbsp;&nbsp;"x86Disassembler3DNowOpcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### THREEDNOW\_MAP\_SYM {#a4856eb908bad869295dd7568a8d735c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define THREEDNOW_MAP_SYM&nbsp;&nbsp;&nbsp;x86Disassembler3DNowOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### TWOBYTE\_STR {#a47e160d69881ebf684f92a2ae79dbfb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TWOBYTE_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerTwoByteOpcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### TWOBYTE\_SYM {#a0bfb472dc63adf5ea8919f054d4450e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TWOBYTE_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerTwoByteOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### TYPES {#a85d942a7aa8b718de83d06343f12aa8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TYPES</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a50d1e7c7632259688573e3e6788f3639">llvm::deserializeSectionKind</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a65e9a46202bf3a405d3465c68e54ff54">llvm::serializeSectionKind</a>.</p>

</div>
</div>

### XOP8\_MAP\_STR {#af69c8d51dace289192a3dc3dab217682}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XOP8_MAP_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerXOP8Opcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### XOP8\_MAP\_SYM {#a73a6f64aec6a805d641a17c87a9d00b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XOP8_MAP_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerXOP8Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### XOP9\_MAP\_STR {#ae50369fe86d5409157eb30cb44fdd74d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XOP9_MAP_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerXOP9Opcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### XOP9\_MAP\_SYM {#a349d73e2f39af064d9999d7780f9897d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XOP9_MAP_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerXOP9Opcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

### XOPA\_MAP\_STR {#afe22b0aeda49b6138cfc2041c3352bc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XOPA_MAP_STR&nbsp;&nbsp;&nbsp;"x86DisassemblerXOPAOpcodes"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>

</div>
</div>

### XOPA\_MAP\_SYM {#a9df14d49cac592bc2e51794ad434e9b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define XOPA_MAP_SYM&nbsp;&nbsp;&nbsp;x86DisassemblerXOPAOpcodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">X86DisassemblerDecoderCommon.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a77b7a7d41251f651fae4a8f7cf8b8311">getInstructionIDWithAttrMask</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
