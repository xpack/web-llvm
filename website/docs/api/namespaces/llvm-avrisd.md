---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/avrisd
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `AVRISD` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::AVRISD { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">NodeType { <a href="#a074d5b8568a8b970d7cea9d14451303b">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> Specific DAG Nodes. <a href="#a074d5b8568a8b970d7cea9d14451303b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### NodeType {#a074d5b8568a8b970d7cea9d14451303b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::AVRISD::NodeType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> Specific DAG Nodes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FIRST_NUMBER<a id="a074d5b8568a8b970d7cea9d14451303baa8c9a5e4ac1259c102aec7d932b448c0"></a></td>
<td class="doxyEnumItemDescription">Start the numbering where the builtin ops leave off (= ISD::BUILTIN_OP_END)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RET_GLUE<a id="a074d5b8568a8b970d7cea9d14451303ba0fe9f2e594b0e7c8104f8eb94b938c47"></a></td>
<td class="doxyEnumItemDescription">Return from subroutine</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RETI_GLUE<a id="a074d5b8568a8b970d7cea9d14451303ba16d4b3472ceb7b6ed5bacb4f40fe5eec"></a></td>
<td class="doxyEnumItemDescription">Return from ISR</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CALL<a id="a074d5b8568a8b970d7cea9d14451303bacd14559412678950d5d722437202c764"></a></td>
<td class="doxyEnumItemDescription">Represents an abstract call instruction, which includes a bunch of information</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WRAPPER<a id="a074d5b8568a8b970d7cea9d14451303baf5220b1f83a9fdaeff55655fa5d85240"></a></td>
<td class="doxyEnumItemDescription">A wrapper node for TargetConstantPool, TargetExternalSymbol, and TargetGlobalAddress</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSL<a id="a074d5b8568a8b970d7cea9d14451303bae91912f6ac81186bcd74401ce3dae9e6"></a></td>
<td class="doxyEnumItemDescription">Logical shift left</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSLBN<a id="a074d5b8568a8b970d7cea9d14451303baeb0b2ed63cc1a8ba18f27cea171c809c"></a></td>
<td class="doxyEnumItemDescription">Byte logical shift left N bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSLWN<a id="a074d5b8568a8b970d7cea9d14451303ba9b17b489e06ed1a0c8ac9f961cb1cd8f"></a></td>
<td class="doxyEnumItemDescription">Word logical shift left N bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSLHI<a id="a074d5b8568a8b970d7cea9d14451303baed365826e51804fbc385059d143276e1"></a></td>
<td class="doxyEnumItemDescription">Higher 8-bit of word logical shift left</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSLW<a id="a074d5b8568a8b970d7cea9d14451303ba225f1576cd266bb6f1f39673f6c6c6ed"></a></td>
<td class="doxyEnumItemDescription">Wide logical shift left</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSR<a id="a074d5b8568a8b970d7cea9d14451303ba72f2a64dfa362e3deb6b106ebd0af33f"></a></td>
<td class="doxyEnumItemDescription">Logical shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSRBN<a id="a074d5b8568a8b970d7cea9d14451303ba8cb6630c354b94e74ee8cee9bc308937"></a></td>
<td class="doxyEnumItemDescription">Byte logical shift right N bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSRWN<a id="a074d5b8568a8b970d7cea9d14451303baf10fb10b48459fbb1df3a393a7662c85"></a></td>
<td class="doxyEnumItemDescription">Word logical shift right N bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSRLO<a id="a074d5b8568a8b970d7cea9d14451303ba868d804ecb6415e2c19bbedbd24ef175"></a></td>
<td class="doxyEnumItemDescription">Lower 8-bit of word logical shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSRW<a id="a074d5b8568a8b970d7cea9d14451303bae1d8c6f3deb398450b0fa485ef9a41a5"></a></td>
<td class="doxyEnumItemDescription">Wide logical shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASR<a id="a074d5b8568a8b970d7cea9d14451303bad5b417469dcce0a69957433fe19bdf0d"></a></td>
<td class="doxyEnumItemDescription">Arithmetic shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASRBN<a id="a074d5b8568a8b970d7cea9d14451303bab7c3602f9c5b607d67734a3341c75d41"></a></td>
<td class="doxyEnumItemDescription">Byte arithmetic shift right N bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASRWN<a id="a074d5b8568a8b970d7cea9d14451303ba0f1a35b2f1028a1b88a6782d3ccf3b48"></a></td>
<td class="doxyEnumItemDescription">Word arithmetic shift right N bits</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASRLO<a id="a074d5b8568a8b970d7cea9d14451303ba3f775cc57c2417270056f5b81afd041c"></a></td>
<td class="doxyEnumItemDescription">Lower 8-bit of word arithmetic shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASRW<a id="a074d5b8568a8b970d7cea9d14451303ba8d739a188d1bfb90d34ecb53a4371052"></a></td>
<td class="doxyEnumItemDescription">Wide arithmetic shift right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROR<a id="a074d5b8568a8b970d7cea9d14451303babfcaebe14f3cc66c1974c8cfcbfa077b"></a></td>
<td class="doxyEnumItemDescription">Bit rotate right</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROL<a id="a074d5b8568a8b970d7cea9d14451303ba5c414e366af8994716bbd800f722df1a"></a></td>
<td class="doxyEnumItemDescription">Bit rotate left</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSLLOOP<a id="a074d5b8568a8b970d7cea9d14451303bafbb71a53f4a84f5d0319c2936192881a"></a></td>
<td class="doxyEnumItemDescription">A loop of single logical shift left instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LSRLOOP<a id="a074d5b8568a8b970d7cea9d14451303ba5a159f6be4f131400e6ac50caef722f5"></a></td>
<td class="doxyEnumItemDescription">A loop of single logical shift right instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ROLLOOP<a id="a074d5b8568a8b970d7cea9d14451303ba23a515309f1d8c3724dce101b42df0e7"></a></td>
<td class="doxyEnumItemDescription">A loop of single left bit rotate instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RORLOOP<a id="a074d5b8568a8b970d7cea9d14451303baa155a4feb86198741d3bba85789d500d"></a></td>
<td class="doxyEnumItemDescription">A loop of single right bit rotate instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ASRLOOP<a id="a074d5b8568a8b970d7cea9d14451303ba52a92c1a49abdeeb5021024a948b5f2c"></a></td>
<td class="doxyEnumItemDescription">A loop of single arithmetic shift right instructions</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRCOND<a id="a074d5b8568a8b970d7cea9d14451303bafc7a1df4a46f450678066ed7228ffc38"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/avr">AVR</a> conditional branches</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMP<a id="a074d5b8568a8b970d7cea9d14451303baaa3b80e6e6efc426a0741b6de03fc651"></a></td>
<td class="doxyEnumItemDescription">Compare instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMPC<a id="a074d5b8568a8b970d7cea9d14451303ba99675982ea8ebe29f488fb7676b92e0d"></a></td>
<td class="doxyEnumItemDescription">Compare with carry instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TST<a id="a074d5b8568a8b970d7cea9d14451303ba89da6d5941083320a43ff88efc3b31b9"></a></td>
<td class="doxyEnumItemDescription">Test for zero or minus instruction</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SWAP<a id="a074d5b8568a8b970d7cea9d14451303ba130298741cbd1865c40ffcfa430b924c"></a></td>
<td class="doxyEnumItemDescription">Swap Rd[7:4] &lt;-&gt; Rd[3:0]</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SELECT_CC<a id="a074d5b8568a8b970d7cea9d14451303ba91b9df7ea090a0af7d41305041a53b49"></a></td>
<td class="doxyEnumItemDescription">Operand 0 and operand 1 are selection variable, operand 2 is condition code and operand 3 is flag operand</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrisellowering-h">AVRISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/avr/avrisellowering-h">AVRISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
