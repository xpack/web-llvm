---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `X86DisassemblerDecoder.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/arrayref-h">llvm/ADT/ArrayRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/x86disassemblerdecodercommon-h">llvm/Support/X86DisassemblerDecoderCommon.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/x86disassembler/instructionspecifier">InstructionSpecifier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The specification for how to extract and interpret a full instruction and its operands. <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/instructionspecifier/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction">InternalInstruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The x86 internal instruction, which is produced by the decoder. <a href="/web-llvm/docs/api/structs/llvm/x86disassembler/internalinstruction/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14dfb0f8c4fad29bad8b975afca91b6b">bitFromOffset0</a>(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa41af96b120e2830065dd5db5e306886">bitFromOffset1</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 1) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 2) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af137cae5f3b74fb13e41bafaf68d053c">bitFromOffset3</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 3) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a8720de8124ef92822868c96799b0b">bitFromOffset4</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 4) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaead313f9ae3c0ddce51cb948dcef738">bitFromOffset5</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 5) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6fd123f533d2ac838dd1e4667c7af07">bitFromOffset6</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 6) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 7) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x3)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad14b3e2a3631bc2ee774e293c63d78e">twoBitsFromOffset6</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 6) &amp; 0x3)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x7)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79408464b0df85edda68168cdb416f93">threeBitsFromOffset3</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 3) &amp; 0x7)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602ef93433d1c57c6f75c09021ba9ed9">fourBitsFromOffset0</a>(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0xf)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa2d70ab66a44f7291bccd5f55555d1">fourBitsFromOffset3</a>(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 3) &amp; 0xf)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad56e18489af3b51ec8f8df907a8af1d">fiveBitsFromOffset0</a>(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x1f)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a7c033979baf89a519dbc9a3650d462">invertedBitFromOffset2</a>(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 2) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e2e1fe68476d61c1db9592b89ce674">invertedBitFromOffset3</a>(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 3) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098af9d0953652bc024bcc5b626a4611">invertedBitFromOffset4</a>(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 4) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef3c451d70ed84b6ec1921e88ef062a">invertedBitFromOffset5</a>(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 5) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade398aef350fef79329af5fe93227778">invertedBitFromOffset6</a>(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 6) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 7) &amp; 0x1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 3) &amp; 0xf)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bce531c2ed18d569a316029616e82f0">modFromModRM</a>(modRM)&nbsp;&nbsp;&nbsp;<a href="#aad14b3e2a3631bc2ee774e293c63d78e">twoBitsFromOffset6</a>(modRM)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8386ddf05ce05f470ca10679a78973bd">regFromModRM</a>(modRM)&nbsp;&nbsp;&nbsp;<a href="#a79408464b0df85edda68168cdb416f93">threeBitsFromOffset3</a>(modRM)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a384089e78b51b1b5773e879ed1d4e672">rmFromModRM</a>(modRM)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(modRM)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b5f49eafdca9d6be0464fccb94a4f33">scaleFromSIB</a>(sib)&nbsp;&nbsp;&nbsp;<a href="#aad14b3e2a3631bc2ee774e293c63d78e">twoBitsFromOffset6</a>(sib)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc11bcb515676078c7c25441c03bddbc">indexFromSIB</a>(sib)&nbsp;&nbsp;&nbsp;<a href="#a79408464b0df85edda68168cdb416f93">threeBitsFromOffset3</a>(sib)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439f21b8d5ea58ea5fe17d11d1547986">baseFromSIB</a>(sib)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(sib)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a567f29a688d316f9d1e149753d4d77da">wFromREX</a>(rex)&nbsp;&nbsp;&nbsp;<a href="#af137cae5f3b74fb13e41bafaf68d053c">bitFromOffset3</a>(rex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2e931225f964b581ab025f86a39872">rFromREX</a>(rex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(rex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af00d764f04a2d7143d9de59ea213f148">xFromREX</a>(rex)&nbsp;&nbsp;&nbsp;<a href="#aa41af96b120e2830065dd5db5e306886">bitFromOffset1</a>(rex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af112ae874f4cca98ba15a30f5743e5e1">bFromREX</a>(rex)&nbsp;&nbsp;&nbsp;<a href="#a14dfb0f8c4fad29bad8b975afca91b6b">bitFromOffset0</a>(rex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d641e102f527d081672914da33f917">mFromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb05c44e83d328ff61f3e6d95d9d098d">r2FromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#ad6fd123f533d2ac838dd1e4667c7af07">bitFromOffset6</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7181fa976e053d8a8a696f381df284c8">x2FromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#aaead313f9ae3c0ddce51cb948dcef738">bitFromOffset5</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89ead465c9b455052cc64ac9e270f9ec">b2FromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#ae4a8720de8124ef92822868c96799b0b">bitFromOffset4</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1082da2cd24fb0eaf8c38ab381934c02">wFromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#af137cae5f3b74fb13e41bafaf68d053c">bitFromOffset3</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fb25ff22b437983d21e368c64374334">rFromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3e731942caa7fdb6384f15a4af2a665">xFromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#aa41af96b120e2830065dd5db5e306886">bitFromOffset1</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b86d4baef893d56800b61fb8a936b50">bFromREX2</a>(rex2)&nbsp;&nbsp;&nbsp;<a href="#a14dfb0f8c4fad29bad8b975afca91b6b">bitFromOffset0</a>(rex2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5297b8410eeadfd658404a6cf3958c07">rFromXOP2of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa76783b724faa5f93e249184af820b9e">xFromXOP2of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#ade398aef350fef79329af5fe93227778">invertedBitFromOffset6</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215ec2d9ebe8a9be78a3cd8eabaeed71">bFromXOP2of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#a3ef3c451d70ed84b6ec1921e88ef062a">invertedBitFromOffset5</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbed9da0e0dde67954fe9e97f6befcc5">mmmmmFromXOP2of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#aad56e18489af3b51ec8f8df907a8af1d">fiveBitsFromOffset0</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea420e27120dd9f790849c9090b42256">wFromXOP3of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5714cb8f59b79c1938dca548bfb61f9">vvvvFromXOP3of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63266a63baf54bef487061a728d12908">lFromXOP3of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bdeef85650fa60106450fb24d9c500">ppFromXOP3of3</a>(xop)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(xop)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4543a64655e2abfbf25bc206c9219150">rFromVEX2of2</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc9745657ce1382ca803e1e3e62a049">vvvvFromVEX2of2</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6886436df5f38bbed7d036a5d8cb44bf">lFromVEX2of2</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba38d038bb20114ef792961068aebd9">ppFromVEX2of2</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb17652126644a237528e0153ee96b1">rFromVEX2of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2702d55c4b2a40989bd2b9cc8a71596e">xFromVEX2of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#ade398aef350fef79329af5fe93227778">invertedBitFromOffset6</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfc6f7a66e0c44fd2145dddeaa88497">bFromVEX2of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#a3ef3c451d70ed84b6ec1921e88ef062a">invertedBitFromOffset5</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30e003e4461758b6dba2c70f339ed6c3">mmmmmFromVEX2of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#aad56e18489af3b51ec8f8df907a8af1d">fiveBitsFromOffset0</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab11339ee1e5b8aaa4a706693c51041ae">wFromVEX3of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5608175fb4bc57fd5e6bcd7f5efed2">vvvvFromVEX3of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2fe87228fa8c1419f2a5f86baaa597">lFromVEX3of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac85472ee64d389babbd2c32deef16d89">ppFromVEX3of3</a>(vex)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(vex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02d842bd0f45034a398eecc59d65c805">rFromEVEX2of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1e56049a41a736160b7ed348bc7709">xFromEVEX2of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#ade398aef350fef79329af5fe93227778">invertedBitFromOffset6</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac938494c24cf099544f7e9a4075454c1">bFromEVEX2of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a3ef3c451d70ed84b6ec1921e88ef062a">invertedBitFromOffset5</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c7da8bddc41cbd0fdd48dd75309cc9d">r2FromEVEX2of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a098af9d0953652bc024bcc5b626a4611">invertedBitFromOffset4</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8940512bc6cf3af7ed8ba1f885f18f81">b2FromEVEX2of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#af137cae5f3b74fb13e41bafaf68d053c">bitFromOffset3</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac092c6a008116e099366148975855711">mmmFromEVEX2of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa9036cb371f65ab0c9aa3d7f2abb5f3">wFromEVEX3of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefa5ea2a9230c9f8dba9efa4d4e226b4">vvvvFromEVEX3of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de03b32789ed02aae9e8a4f881ef0c0">uFromEVEX3of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a5a7c033979baf89a519dbc9a3650d462">invertedBitFromOffset2</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a08eb3991a81513d973c4d1d70fd81b">ppFromEVEX3of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9a3936dedbb738365b55da9fa780f8">oszcFromEVEX3of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a0fa2d70ab66a44f7291bccd5f55555d1">fourBitsFromOffset3</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f317d7fd1a55926bed30febed7606da">zFromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d1ee61cb5494166e335ff64d2cffa8">l2FromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#ad6fd123f533d2ac838dd1e4667c7af07">bitFromOffset6</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a057966fda096251466bbdfda0b801081">lFromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#aaead313f9ae3c0ddce51cb948dcef738">bitFromOffset5</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4521a330feb2823d5f0a83db8233186a">bFromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#ae4a8720de8124ef92822868c96799b0b">bitFromOffset4</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b4847dc5b2960b63e97e71da1d802a4">v2FromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a90e2e1fe68476d61c1db9592b89ce674">invertedBitFromOffset3</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd318ed530c8fc71af093848beb0e2a9">aaaFromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e79075da5fbb18e84861838e5f60871">nfFromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7201603cc366bc19401cb3973b8ce209">scFromEVEX4of4</a>(evex)&nbsp;&nbsp;&nbsp;<a href="#a602ef93433d1c57c6f75c09021ba9ed9">fourBitsFromOffset0</a>(evex)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a258c72e73a946a158cc399bf90d94ce0">REGS_8BIT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a57a6eee386883e5e59e016eace859">EA_BASES_16BIT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9007c428c7b7ffd0ca765cb41c2e002d">REGS_16BIT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49626340dd008810da4c2f48358f4e5">EA_BASES_32BIT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ad23de5ab07419bd9fadd58ca615585">REGS_32BIT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e6e1688bcff4c9ea17a36f5cd8b8b0">EA_BASES_64BIT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b6730ebd5ca012ee84ca5ba1582608">REGS_64BIT</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71fa6e4885a38387a87080b979e926d8">REGS_MMX</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c194da583ffb0dd2fab50331e4cbc41">REGS_XMM</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fc6928518e9a8c348d985bec97d382e">REGS_YMM</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acffec50bf53b6bde81c96e0951d577eb">REGS_ZMM</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6092059fedeb6665004af3ce388d349">REGS_MASKS</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5104b8ba59e7d09cbee5ed71a4300d9">REGS_MASK_PAIRS</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4d47716cec167134dff7b8a6e91ed17">REGS_SEGMENT</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06e6891e879fdbd81834d827cecde67">REGS_DEBUG</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1acdd8e2cba2404a5dc403a385c58c">REGS_CONTROL</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18104863e381d9ab484d1a91d222c102">REGS_TMM</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf371d2bd1eff2fb3db219b73a1196b1">REGS_TMM_PAIRS</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1c2d19d6110a95f79a5e8cbe1f6e007">ALL_EA_BASES</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a967004f254ec4b0e36dca9b2db27f139">ALL_SIB_BASES</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f4c518929a964ae54a9d42780670cd2">ALL_REGS</a>&nbsp;&nbsp;&nbsp;...</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168a41dfc8e956c6180862aeca885db1">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;EA_BASE_##x,</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dbab080ad769a5f716ded6e9f272748">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;EA_REG_##x,</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7afd582f1c8713d60dbff8569cb6f0b">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;SIB_INDEX_##x,</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2201f841c4c6a1aec7f1e04fb00b0cab">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;SIB_BASE_##x,</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f201612cb32816265e25b6101b1f1e7">ENTRY</a>(x)&nbsp;&nbsp;&nbsp;MODRM_REG_##x,</td>
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

### aaaFromEVEX4of4 {#abd318ed530c8fc71af093848beb0e2a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define aaaFromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aa7089b50e7c7846d5b312d0148c30b5f">readMaskRegister</a>.</p>

</div>
</div>

### ALL\_EA\_BASES {#ae1c2d19d6110a95f79a5e8cbe1f6e007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ALL_EA_BASES&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a94a57a6eee386883e5e59e016eace859">EA_BASES_16BIT</a>                                                               \
  <a href="#aa49626340dd008810da4c2f48358f4e5">EA_BASES_32BIT</a>                                                               \
  <a href="#a67e6e1688bcff4c9ea17a36f5cd8b8b0">EA_BASES_64BIT</a>
</div>
</dd>
</dl>

<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aea1e232218bf327acf353b1f07db2f86">translateRMRegister</a>.</p>

</div>
</div>

### ALL\_REGS {#a8f4c518929a964ae54a9d42780670cd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ALL_REGS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a258c72e73a946a158cc399bf90d94ce0">REGS_8BIT</a>                                                                    \
  <a href="#a9007c428c7b7ffd0ca765cb41c2e002d">REGS_16BIT</a>                                                                   \
  <a href="#a4ad23de5ab07419bd9fadd58ca615585">REGS_32BIT</a>                                                                   \
  <a href="#a98b6730ebd5ca012ee84ca5ba1582608">REGS_64BIT</a>                                                                   \
  <a href="#a71fa6e4885a38387a87080b979e926d8">REGS_MMX</a>                                                                     \
  <a href="#a7c194da583ffb0dd2fab50331e4cbc41">REGS_XMM</a>                                                                     \
  <a href="#a6fc6928518e9a8c348d985bec97d382e">REGS_YMM</a>                                                                     \
  <a href="#acffec50bf53b6bde81c96e0951d577eb">REGS_ZMM</a>                                                                     \
  <a href="#af6092059fedeb6665004af3ce388d349">REGS_MASKS</a>                                                                   \
  <a href="#af5104b8ba59e7d09cbee5ed71a4300d9">REGS_MASK_PAIRS</a>                                                              \
  <a href="#ac4d47716cec167134dff7b8a6e91ed17">REGS_SEGMENT</a>                                                                 \
  <a href="#ab06e6891e879fdbd81834d827cecde67">REGS_DEBUG</a>                                                                   \
  <a href="#a4a1acdd8e2cba2404a5dc403a385c58c">REGS_CONTROL</a>                                                                 \
  <a href="#a18104863e381d9ab484d1a91d222c102">REGS_TMM</a>                                                                     \
  <a href="#aaf371d2bd1eff2fb3db219b73a1196b1">REGS_TMM_PAIRS</a>                                                               \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(RIP)
</div>
</dd>
</dl>

<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a06e3b1499180a2b92acc66f9203ac920">translateRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aea1e232218bf327acf353b1f07db2f86">translateRMRegister</a>.</p>

</div>
</div>

### ALL\_SIB\_BASES {#a967004f254ec4b0e36dca9b2db27f139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ALL_SIB_BASES&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="#a4ad23de5ab07419bd9fadd58ca615585">REGS_32BIT</a>                                                                   \
  <a href="#a98b6730ebd5ca012ee84ca5ba1582608">REGS_64BIT</a>
</div>
</dd>
</dl>

<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>.</p>

</div>
</div>

### b2FromEVEX2of4 {#a8940512bc6cf3af7ed8ba1f885f18f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define b2FromEVEX2of4(evex)&nbsp;&nbsp;&nbsp;<a href="#af137cae5f3b74fb13e41bafaf68d053c">bitFromOffset3</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### b2FromREX2 {#a89ead465c9b455052cc64ac9e270f9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define b2FromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#ae4a8720de8124ef92822868c96799b0b">bitFromOffset4</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab536506d0058cd6baa803890e9d648dd">readOpcodeRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### baseFromSIB {#a439f21b8d5ea58ea5fe17d11d1547986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define baseFromSIB(sib)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(sib)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### bFromEVEX2of4 {#ac938494c24cf099544f7e9a4075454c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bFromEVEX2of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a3ef3c451d70ed84b6ec1921e88ef062a">invertedBitFromOffset5</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### bFromEVEX4of4 {#a4521a330feb2823d5f0a83db8233186a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bFromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#ae4a8720de8124ef92822868c96799b0b">bitFromOffset4</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### bFromREX {#af112ae874f4cca98ba15a30f5743e5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bFromREX(rex)&nbsp;&nbsp;&nbsp;<a href="#a14dfb0f8c4fad29bad8b975afca91b6b">bitFromOffset0</a>(rex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab536506d0058cd6baa803890e9d648dd">readOpcodeRegister</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### bFromREX2 {#a3b86d4baef893d56800b61fb8a936b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bFromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#a14dfb0f8c4fad29bad8b975afca91b6b">bitFromOffset0</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### bFromVEX2of3 {#aabfc6f7a66e0c44fd2145dddeaa88497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bFromVEX2of3(vex)&nbsp;&nbsp;&nbsp;<a href="#a3ef3c451d70ed84b6ec1921e88ef062a">invertedBitFromOffset5</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### bFromXOP2of3 {#a215ec2d9ebe8a9be78a3cd8eabaeed71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bFromXOP2of3(xop)&nbsp;&nbsp;&nbsp;<a href="#a3ef3c451d70ed84b6ec1921e88ef062a">invertedBitFromOffset5</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### bitFromOffset0 {#a14dfb0f8c4fad29bad8b975afca91b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset0(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### bitFromOffset1 {#aa41af96b120e2830065dd5db5e306886}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset1(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 1) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### bitFromOffset2 {#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset2(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 2) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### bitFromOffset3 {#af137cae5f3b74fb13e41bafaf68d053c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset3(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 3) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### bitFromOffset4 {#ae4a8720de8124ef92822868c96799b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset4(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 4) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### bitFromOffset5 {#aaead313f9ae3c0ddce51cb948dcef738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset5(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 5) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### bitFromOffset6 {#ad6fd123f533d2ac838dd1e4667c7af07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset6(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 6) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### bitFromOffset7 {#a37e2d7ba595bfec360d1909728c490af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define bitFromOffset7(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 7) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### EA\_BASES\_16BIT {#a94a57a6eee386883e5e59e016eace859}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EA_BASES_16BIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### EA\_BASES\_32BIT {#aa49626340dd008810da4c2f48358f4e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EA_BASES_32BIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>.</p>

</div>
</div>

### EA\_BASES\_64BIT {#a67e6e1688bcff4c9ea17a36f5cd8b8b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define EA_BASES_64BIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>.</p>

</div>
</div>

### ENTRY {#a168a41dfc8e956c6180862aeca885db1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;EA_BASE_##x,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### ENTRY {#a4dbab080ad769a5f716ded6e9f272748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;EA_REG_##x,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### ENTRY {#ab7afd582f1c8713d60dbff8569cb6f0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;SIB_INDEX_##x,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 595 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### ENTRY {#a2201f841c4c6a1aec7f1e04fb00b0cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;SIB_BASE_##x,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 609 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### ENTRY {#a9f201612cb32816265e25b6101b1f1e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ENTRY(x)&nbsp;&nbsp;&nbsp;MODRM_REG_##x,</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### fiveBitsFromOffset0 {#aad56e18489af3b51ec8f8df907a8af1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define fiveBitsFromOffset0(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x1f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### fourBitsFromOffset0 {#a602ef93433d1c57c6f75c09021ba9ed9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define fourBitsFromOffset0(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0xf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### fourBitsFromOffset3 {#a0fa2d70ab66a44f7291bccd5f55555d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define fourBitsFromOffset3(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 3) &amp; 0xf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### indexFromSIB {#adc11bcb515676078c7c25441c03bddbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define indexFromSIB(sib)&nbsp;&nbsp;&nbsp;<a href="#a79408464b0df85edda68168cdb416f93">threeBitsFromOffset3</a>(sib)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### invertedBitFromOffset2 {#a5a7c033979baf89a519dbc9a3650d462}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define invertedBitFromOffset2(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 2) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### invertedBitFromOffset3 {#a90e2e1fe68476d61c1db9592b89ce674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define invertedBitFromOffset3(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 3) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### invertedBitFromOffset4 {#a098af9d0953652bc024bcc5b626a4611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define invertedBitFromOffset4(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 4) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### invertedBitFromOffset5 {#a3ef3c451d70ed84b6ec1921e88ef062a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define invertedBitFromOffset5(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 5) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### invertedBitFromOffset6 {#ade398aef350fef79329af5fe93227778}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define invertedBitFromOffset6(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 6) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### invertedBitFromOffset7 {#a5bf13eb8791f7b1d99a8fb0f428b2353}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define invertedBitFromOffset7(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 7) &amp; 0x1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### invertedFourBitsFromOffset3 {#aef9bece1b2d00fc39b1fd1be9fa1cf56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define invertedFourBitsFromOffset3(val)&nbsp;&nbsp;&nbsp;(((~(val)) &gt;&gt; 3) &amp; 0xf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### l2FromEVEX4of4 {#a05d1ee61cb5494166e335ff64d2cffa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define l2FromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#ad6fd123f533d2ac838dd1e4667c7af07">bitFromOffset6</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### lFromEVEX4of4 {#a057966fda096251466bbdfda0b801081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define lFromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#aaead313f9ae3c0ddce51cb948dcef738">bitFromOffset5</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### lFromVEX2of2 {#a6886436df5f38bbed7d036a5d8cb44bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define lFromVEX2of2(vex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### lFromVEX3of3 {#abf2fe87228fa8c1419f2a5f86baaa597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define lFromVEX3of3(vex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### lFromXOP3of3 {#a63266a63baf54bef487061a728d12908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define lFromXOP3of3(xop)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### mFromREX2 {#ae3d641e102f527d081672914da33f917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define mFromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a22cc5e803fedae95c7e1d22ffdb71cda">readOpcode</a>.</p>

</div>
</div>

### mmmFromEVEX2of4 {#ac092c6a008116e099366148975855711}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define mmmFromEVEX2of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a22cc5e803fedae95c7e1d22ffdb71cda">readOpcode</a>.</p>

</div>
</div>

### mmmmmFromVEX2of3 {#a30e003e4461758b6dba2c70f339ed6c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define mmmmmFromVEX2of3(vex)&nbsp;&nbsp;&nbsp;<a href="#aad56e18489af3b51ec8f8df907a8af1d">fiveBitsFromOffset0</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a22cc5e803fedae95c7e1d22ffdb71cda">readOpcode</a>.</p>

</div>
</div>

### mmmmmFromXOP2of3 {#abbed9da0e0dde67954fe9e97f6befcc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define mmmmmFromXOP2of3(xop)&nbsp;&nbsp;&nbsp;<a href="#aad56e18489af3b51ec8f8df907a8af1d">fiveBitsFromOffset0</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a22cc5e803fedae95c7e1d22ffdb71cda">readOpcode</a>.</p>

</div>
</div>

### modFromModRM {#a4bce531c2ed18d569a316029616e82f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define modFromModRM(modRM)&nbsp;&nbsp;&nbsp;<a href="#aad14b3e2a3631bc2ee774e293c63d78e">twoBitsFromOffset6</a>(modRM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ab3686bdd912c0d40035aa66dcffb36da">decode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### nfFromEVEX4of4 {#a8e79075da5fbb18e84861838e5f60871}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define nfFromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a8bfeb1239d117ffbcde8064ef6fcc5a5">isNF</a>.</p>

</div>
</div>

### oszcFromEVEX3of4 {#aec9a3936dedbb738365b55da9fa780f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define oszcFromEVEX3of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a0fa2d70ab66a44f7291bccd5f55555d1">fourBitsFromOffset3</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### ppFromEVEX3of4 {#a4a08eb3991a81513d973c4d1d70fd81b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ppFromEVEX3of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a8bfeb1239d117ffbcde8064ef6fcc5a5">isNF</a>.</p>

</div>
</div>

### ppFromVEX2of2 {#adba38d038bb20114ef792961068aebd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ppFromVEX2of2(vex)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### ppFromVEX3of3 {#ac85472ee64d389babbd2c32deef16d89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ppFromVEX3of3(vex)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

### ppFromXOP3of3 {#a91bdeef85650fa60106450fb24d9c500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ppFromXOP3of3(xop)&nbsp;&nbsp;&nbsp;<a href="#a09681345ab530933c1718419f5b0b723">twoBitsFromOffset0</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### r2FromEVEX2of4 {#a9c7da8bddc41cbd0fdd48dd75309cc9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define r2FromEVEX2of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a098af9d0953652bc024bcc5b626a4611">invertedBitFromOffset4</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### r2FromREX2 {#aeb05c44e83d328ff61f3e6d95d9d098d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define r2FromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#ad6fd123f533d2ac838dd1e4667c7af07">bitFromOffset6</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>.</p>

</div>
</div>

### regFromModRM {#a8386ddf05ce05f470ca10679a78973bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define regFromModRM(modRM)&nbsp;&nbsp;&nbsp;<a href="#a79408464b0df85edda68168cdb416f93">threeBitsFromOffset3</a>(modRM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ac0572c45b7c999d1ef69cece322f0e1c">isCCMPOrCTEST</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>.</p>

</div>
</div>

### REGS\_16BIT {#a9007c428c7b7ffd0ca765cb41c2e002d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_16BIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_32BIT {#a4ad23de5ab07419bd9fadd58ca615585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_32BIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_64BIT {#a98b6730ebd5ca012ee84ca5ba1582608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_64BIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_8BIT {#a258c72e73a946a158cc399bf90d94ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_8BIT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_CONTROL {#a4a1acdd8e2cba2404a5dc403a385c58c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_CONTROL&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR0)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR1)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR2)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR3)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR4)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR5)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR6)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR7)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR8)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR9)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR10)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR11)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR12)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR13)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR14)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CR15)
</div>
</dd>
</dl>

<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_DEBUG {#ab06e6891e879fdbd81834d827cecde67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_DEBUG&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR0)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR1)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR2)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR3)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR4)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR5)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR6)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR7)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR8)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR9)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR10)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR11)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR12)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR13)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR14)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DR15)
</div>
</dd>
</dl>

<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_MASK\_PAIRS {#af5104b8ba59e7d09cbee5ed71a4300d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_MASK_PAIRS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K0_K1)                                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K2_K3)                                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K4_K5)                                                                 \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K6_K7)
</div>
</dd>
</dl>

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_MASKS {#af6092059fedeb6665004af3ce388d349}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_MASKS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K0)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K1)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K2)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K3)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K4)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K5)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K6)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(K7)
</div>
</dd>
</dl>

<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_MMX {#a71fa6e4885a38387a87080b979e926d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_MMX&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM0)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM1)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM2)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM3)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM4)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM5)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM6)                                                                   \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(MM7)
</div>
</dd>
</dl>

<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_SEGMENT {#ac4d47716cec167134dff7b8a6e91ed17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_SEGMENT&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(ES)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(CS)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(SS)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(DS)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(FS)                                                                    \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(GS)
</div>
</dd>
</dl>

<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_TMM {#a18104863e381d9ab484d1a91d222c102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_TMM&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM0)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM1)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM2)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM3)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM4)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM5)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM6)                                                                  \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM7)
</div>
</dd>
</dl>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_TMM\_PAIRS {#aaf371d2bd1eff2fb3db219b73a1196b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_TMM_PAIRS&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM0_TMM1)                                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM2_TMM3)                                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM4_TMM5)                                                             \
  <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsectionmacho-cpp/#ac87f60246b2a01df58ca032da8463a14">ENTRY</a>(TMM6_TMM7)
</div>
</dd>
</dl>

<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### REGS\_XMM {#a7c194da583ffb0dd2fab50331e4cbc41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_XMM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>.</p>

</div>
</div>

### REGS\_YMM {#a6fc6928518e9a8c348d985bec97d382e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_YMM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>.</p>

</div>
</div>

### REGS\_ZMM {#acffec50bf53b6bde81c96e0951d577eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define REGS_ZMM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 433 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae82674c41a00b35f36f9ecf81932512e">translateRMMemory</a>.</p>

</div>
</div>

### rFromEVEX2of4 {#a02d842bd0f45034a398eecc59d65c805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rFromEVEX2of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### rFromREX {#a1c2e931225f964b581ab025f86a39872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rFromREX(rex)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(rex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>.</p>

</div>
</div>

### rFromREX2 {#a7fb25ff22b437983d21e368c64374334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rFromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#af7f4a0b2bcab7d6ba7f1c6d26d0f1ebb">bitFromOffset2</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### rFromVEX2of2 {#a4543a64655e2abfbf25bc206c9219150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rFromVEX2of2(vex)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### rFromVEX2of3 {#a0eb17652126644a237528e0153ee96b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rFromVEX2of3(vex)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### rFromXOP2of3 {#a5297b8410eeadfd658404a6cf3958c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rFromXOP2of3(xop)&nbsp;&nbsp;&nbsp;<a href="#a5bf13eb8791f7b1d99a8fb0f428b2353">invertedBitFromOffset7</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### rmFromModRM {#a384089e78b51b1b5773e879ed1d4e672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define rmFromModRM(modRM)&nbsp;&nbsp;&nbsp;<a href="#a918bebf89fcd6a50b94133b213564a1e">threeBitsFromOffset0</a>(modRM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#ae354b93b59d4f78cddbb50869bd5ef6b">readModRM</a>.</p>

</div>
</div>

### scaleFromSIB {#a7b5f49eafdca9d6be0464fccb94a4f33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define scaleFromSIB(sib)&nbsp;&nbsp;&nbsp;<a href="#aad14b3e2a3631bc2ee774e293c63d78e">twoBitsFromOffset6</a>(sib)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### scFromEVEX4of4 {#a7201603cc366bc19401cb3973b8ce209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define scFromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a602ef93433d1c57c6f75c09021ba9ed9">fourBitsFromOffset0</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a42be988af3ae0e352befa7189bd50936">readOperands</a>.</p>

</div>
</div>

### threeBitsFromOffset0 {#a918bebf89fcd6a50b94133b213564a1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define threeBitsFromOffset0(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x7)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### threeBitsFromOffset3 {#a79408464b0df85edda68168cdb416f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define threeBitsFromOffset3(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 3) &amp; 0x7)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### twoBitsFromOffset0 {#a09681345ab530933c1718419f5b0b723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define twoBitsFromOffset0(val)&nbsp;&nbsp;&nbsp;((val) &amp; 0x3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### twoBitsFromOffset6 {#aad14b3e2a3631bc2ee774e293c63d78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define twoBitsFromOffset6(val)&nbsp;&nbsp;&nbsp;(((val) &gt;&gt; 6) &amp; 0x3)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>

</div>
</div>

### uFromEVEX3of4 {#a9de03b32789ed02aae9e8a4f881ef0c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define uFromEVEX3of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a5a7c033979baf89a519dbc9a3650d462">invertedBitFromOffset2</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### v2FromEVEX4of4 {#a4b4847dc5b2960b63e97e71da1d802a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define v2FromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a90e2e1fe68476d61c1db9592b89ce674">invertedBitFromOffset3</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a42be988af3ae0e352befa7189bd50936">readOperands</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a8514fc80a87b940b85536ef125c05350">readVVVV</a>.</p>

</div>
</div>

### vvvvFromEVEX3of4 {#aefa5ea2a9230c9f8dba9efa4d4e226b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define vvvvFromEVEX3of4(evex)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a8514fc80a87b940b85536ef125c05350">readVVVV</a>.</p>

</div>
</div>

### vvvvFromVEX2of2 {#a8dc9745657ce1382ca803e1e3e62a049}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define vvvvFromVEX2of2(vex)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a8514fc80a87b940b85536ef125c05350">readVVVV</a>.</p>

</div>
</div>

### vvvvFromVEX3of3 {#a9b5608175fb4bc57fd5e6bcd7f5efed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define vvvvFromVEX3of3(vex)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a8514fc80a87b940b85536ef125c05350">readVVVV</a>.</p>

</div>
</div>

### vvvvFromXOP3of3 {#ae5714cb8f59b79c1938dca548bfb61f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define vvvvFromXOP3of3(xop)&nbsp;&nbsp;&nbsp;<a href="#aef9bece1b2d00fc39b1fd1be9fa1cf56">invertedFourBitsFromOffset3</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a8514fc80a87b940b85536ef125c05350">readVVVV</a>.</p>

</div>
</div>

### wFromEVEX3of4 {#aaa9036cb371f65ab0c9aa3d7f2abb5f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define wFromEVEX3of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### wFromREX {#a567f29a688d316f9d1e149753d4d77da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define wFromREX(rex)&nbsp;&nbsp;&nbsp;<a href="#af137cae5f3b74fb13e41bafaf68d053c">bitFromOffset3</a>(rex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### wFromREX2 {#a1082da2cd24fb0eaf8c38ab381934c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define wFromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#af137cae5f3b74fb13e41bafaf68d053c">bitFromOffset3</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### wFromVEX3of3 {#ab11339ee1e5b8aaa4a706693c51041ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define wFromVEX3of3(vex)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### wFromXOP3of3 {#aea420e27120dd9f790849c9090b42256}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define wFromXOP3of3(xop)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### x2FromREX2 {#a7181fa976e053d8a8a696f381df284c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define x2FromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#aaead313f9ae3c0ddce51cb948dcef738">bitFromOffset5</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### xFromEVEX2of4 {#acc1e56049a41a736160b7ed348bc7709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define xFromEVEX2of4(evex)&nbsp;&nbsp;&nbsp;<a href="#ade398aef350fef79329af5fe93227778">invertedBitFromOffset6</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#adb1fcba65d61d145b053ee0217b3dee7">fixupReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### xFromREX {#af00d764f04a2d7143d9de59ea213f148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define xFromREX(rex)&nbsp;&nbsp;&nbsp;<a href="#aa41af96b120e2830065dd5db5e306886">bitFromOffset1</a>(rex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a7d9a3ce3081e918d80b9770b584009a3">readSIB</a>.</p>

</div>
</div>

### xFromREX2 {#aa3e731942caa7fdb6384f15a4af2a665}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define xFromREX2(rex2)&nbsp;&nbsp;&nbsp;<a href="#aa41af96b120e2830065dd5db5e306886">bitFromOffset1</a>(rex2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### xFromVEX2of3 {#a2702d55c4b2a40989bd2b9cc8a71596e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define xFromVEX2of3(vex)&nbsp;&nbsp;&nbsp;<a href="#ade398aef350fef79329af5fe93227778">invertedBitFromOffset6</a>(vex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### xFromXOP2of3 {#aa76783b724faa5f93e249184af820b9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define xFromXOP2of3(xop)&nbsp;&nbsp;&nbsp;<a href="#ade398aef350fef79329af5fe93227778">invertedBitFromOffset6</a>(xop)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#aef1a8136ca4df8d11829c1aa2b708f5d">readPrefixes</a>.</p>

</div>
</div>

### zFromEVEX4of4 {#a0f317d7fd1a55926bed30febed7606da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define zFromEVEX4of4(evex)&nbsp;&nbsp;&nbsp;<a href="#a37e2d7ba595bfec360d1909728c490af">bitFromOffset7</a>(evex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassemblerdecoder-h">X86DisassemblerDecoder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a201a8b01dbfadf977a0b7b16b14bcb29">getInstructionID</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
