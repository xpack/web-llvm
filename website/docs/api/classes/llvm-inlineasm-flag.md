---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/inlineasm/flag
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Flag` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::InlineAsm::Flag { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe6ea125f3d36ee9a67c031b31062ba4">KindField</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94">Kind</a>, 0, 3, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a00d0b4f2d7dcdaaef835b97cf5d1e0df">Kind::Func</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a42b800d7bb991fb44b7a312313fd9">NumOperands</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; unsigned, 3, 13 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e674f5c3a51c2fd3abcce7243958304">MatchedOperandNo</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; unsigned, 16, 15 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea082892918b4b796baa573f29929b50">MemConstraintCode</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">ConstraintCode</a>, 16, 15, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a6a061313d22e51e0f25b7cd4dc065233">ConstraintCode::Max</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acafc3157e4f642eec28b21186e6c9e01">RegClass</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; unsigned, 16, 14 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ba4c506bb503b011572a09314158391">RegMayBeFolded</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; bool, 30, 1 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe9df3f1649730de6e1ce33dc55e146">IsMatched</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; bool, 31, 1 &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e9d8e949b5dae1762f3a70898246ccd">Flag</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad600531cbe96e2c3bba3f43f0fcc8bd7">Flag</a> (uint32_t F)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5695f73e7e822cf666e2f47ee05fe6ce">Flag</a> (enum Kind K, unsigned NumOps)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a013c398154eddf42b35c431be43d61a1">operator uint32_t</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c081604f65f65850620181db33f548">getKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ad0684888a368762fa9b2cdc6acd025">isRegUseKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcdcd14f56fb520a400bc05c39078384">isRegDefKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade52bc57cc65e30baccebb56b76ec13a">isRegDefEarlyClobberKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a3c74e25ebbff757c8c2ecb35cf9892">isClobberKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28636c0e24d9760687e5f66d02051a2f">isImmKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a637e8098e756e55d2aba0a6f41adbd2f">isMemKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfcd5603bc1201c6c18a4f18f3278c10">isFuncKind</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2eb5d0f43cbb30debace7243c18a501a">getKindName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad425f5167e26c58c9849c6170450460b">getNumOperandRegisters</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getNumOperandRegisters - Extract the number of registers field from the inline asm operand flag. <a href="#ad425f5167e26c58c9849c6170450460b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab43f08d6db156a53503ccf3a7ef0176a">isUseOperandTiedToDef</a> (unsigned &amp;Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isUseOperandTiedToDef - Return true if the flag of the inline asm operand indicates it is an use operand that's matched to a def operand. <a href="#ab43f08d6db156a53503ccf3a7ef0176a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582ec155bb1507a15c1c7fb46bc53fb7">hasRegClassConstraint</a> (unsigned &amp;RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasRegClassConstraint - Returns true if the flag contains a register class constraint. <a href="#a582ec155bb1507a15c1c7fb46bc53fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">ConstraintCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a945eeecdf3b5f4969d9c5aa1d1eacec1">getMemoryConstraintID</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a3a4a2d14c39019e5cd648081a33419">setMatchingOp</a> (unsigned OperandNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setMatchingOp - Augment an existing flag with information indicating that this input operand is tied to a previous output operand. <a href="#a8a3a4a2d14c39019e5cd648081a33419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf882e839e78f88340e664afcd87e5d">setRegClass</a> (unsigned RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setRegClass - Augment an existing flag with the required register class for the following register operands. <a href="#a2cf882e839e78f88340e664afcd87e5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de6bf65ca1443186731a3391c02d1f9">setMemConstraint</a> (ConstraintCode C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setMemConstraint - Augment an existing flag with the constraint code for a memory constraint. <a href="#a8de6bf65ca1443186731a3391c02d1f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41a1d51570ca5ad847d74f1f7b020ad0">clearMemConstraint</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearMemConstraint - Similar to setMemConstraint(0), but without the assertion checking that the constraint has not been set previously. <a href="#a41a1d51570ca5ad847d74f1f7b020ad0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15203762d44a454199820de3b1e09f20">setRegMayBeFolded</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set a bit to denote that while this operand is some kind of register (use, def, ...), a memory flag did appear in the original constraint list. <a href="#a15203762d44a454199820de3b1e09f20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafed3f8d7e82cd37afdf3bb1cf6947dd">getRegMayBeFolded</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad229d9fd0dd47e5efab7847e146d2a11">getMatchedOperandNo</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27105df40cca150310c4bf7cc68b21da">getRegClass</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a449ce7a0c48a469392bdbfb0bf4be907">isMatched</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64014b6a3fcec66c9bcd7b3bf4a6efab">Storage</a></td>
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


<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### IsMatched {#aabe9df3f1649730de6e1ce33dc55e146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::Flag::IsMatched =  Bitfield::Element&lt;bool, 31, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### KindField {#abe6ea125f3d36ee9a67c031b31062ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::Flag::KindField =  Bitfield::Element&lt;Kind, 0, 3, Kind::Func&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### MatchedOperandNo {#a7e674f5c3a51c2fd3abcce7243958304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::Flag::MatchedOperandNo =  Bitfield::Element&lt;unsigned, 16, 15&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### MemConstraintCode {#aea082892918b4b796baa573f29929b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::Flag::MemConstraintCode =  Bitfield::Element&lt;ConstraintCode, 16, 15, ConstraintCode::Max&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### NumOperands {#a02a42b800d7bb991fb44b7a312313fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::Flag::NumOperands =  Bitfield::Element&lt;unsigned, 3, 13&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### RegClass {#acafc3157e4f642eec28b21186e6c9e01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::Flag::RegClass =  Bitfield::Element&lt;unsigned, 16, 14&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### RegMayBeFolded {#a2ba4c506bb503b011572a09314158391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::InlineAsm::Flag::RegMayBeFolded =  Bitfield::Element&lt;bool, 30, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Flag() {#a9e9d8e949b5dae1762f3a70898246ccd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsm::Flag::Flag ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### Flag() {#ad600531cbe96e2c3bba3f43f0fcc8bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsm::Flag::Flag (uint32_t F)</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### Flag() {#a5695f73e7e822cf666e2f47ee05fe6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsm::Flag::Flag (enum <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94">Kind</a> K, unsigned NumOps)</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfield/#aac5c44667e3b3ebe2ed424dbd12a35d5">llvm::Bitfield::set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator uint32\_t() {#a013c398154eddf42b35c431be43d61a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsm::Flag::operator uint32_t ()</td>
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



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearMemConstraint() {#a41a1d51570ca5ad847d74f1f7b020ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsm::Flag::clearMemConstraint ()</td>
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

<p>clearMemConstraint - Similar to setMemConstraint(0), but without the assertion checking that the constraint has not been set previously.</p>

<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#acfcd5603bc1201c6c18a4f18f3278c10">isFuncKind</a>, <a href="#a637e8098e756e55d2aba0a6f41adbd2f">isMemKind</a>, <a href="/web-llvm/docs/api/structs/llvm/bitfield/#aac5c44667e3b3ebe2ed424dbd12a35d5">llvm::Bitfield::set</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::InlineAsm::Unknown</a>.</p>

</div>
</div>

### getKind() {#a41c081604f65f65850620181db33f548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind llvm::InlineAsm::Flag::getKind ()</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/bitfield/#a3cd3d6331b8a3ea50db05696debf2075">llvm::Bitfield::get</a>.</p>


<p>Referenced by <a href="#a2eb5d0f43cbb30debace7243c18a501a">getKindName</a>, <a href="#a2a3c74e25ebbff757c8c2ecb35cf9892">isClobberKind</a>, <a href="#acfcd5603bc1201c6c18a4f18f3278c10">isFuncKind</a>, <a href="#a28636c0e24d9760687e5f66d02051a2f">isImmKind</a>, <a href="#a637e8098e756e55d2aba0a6f41adbd2f">isMemKind</a>, <a href="#ade52bc57cc65e30baccebb56b76ec13a">isRegDefEarlyClobberKind</a>, <a href="#afcdcd14f56fb520a400bc05c39078384">isRegDefKind</a> and <a href="#a5ad0684888a368762fa9b2cdc6acd025">isRegUseKind</a>.</p>

</div>
</div>

### getKindName() {#a2eb5d0f43cbb30debace7243c18a501a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::InlineAsm::Flag::getKindName ()</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94ac50132234eb8c934e71b7f2f0fa5099c">llvm::InlineAsm::Clobber</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a00d0b4f2d7dcdaaef835b97cf5d1e0df">llvm::InlineAsm::Func</a>, <a href="#a41c081604f65f65850620181db33f548">getKind</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94ada9470e1aa5be1858e667318254dcb4b">llvm::InlineAsm::Imm</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94adba5553473d129a7985fb532dc249ff4">llvm::InlineAsm::Mem</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a1fbd4693daf9a506101ec4cd36caa8dd">llvm::InlineAsm::RegDef</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94adda36cdb69635bdfb9f3d925753dc2d3">llvm::InlineAsm::RegDefEarlyClobber</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a4ac13b7b2bba42947e897ffdf8797788">llvm::InlineAsm::RegUse</a>.</p>

</div>
</div>

### getMemoryConstraintID() {#a945eeecdf3b5f4969d9c5aa1d1eacec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstraintCode llvm::InlineAsm::Flag::getMemoryConstraintID ()</td>
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



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bitfield/#a3cd3d6331b8a3ea50db05696debf2075">llvm::Bitfield::get</a>, <a href="#acfcd5603bc1201c6c18a4f18f3278c10">isFuncKind</a> and <a href="#a637e8098e756e55d2aba0a6f41adbd2f">isMemKind</a>.</p>


<p>Referenced by <a href="#a8de6bf65ca1443186731a3391c02d1f9">setMemConstraint</a>.</p>

</div>
</div>

### getNumOperandRegisters() {#ad425f5167e26c58c9849c6170450460b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InlineAsm::Flag::getNumOperandRegisters ()</td>
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

<p>getNumOperandRegisters - Extract the number of registers field from the inline asm operand flag.</p>

<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/bitfield/#a3cd3d6331b8a3ea50db05696debf2075">llvm::Bitfield::get</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#a94b063824e30c0f9c3e2a2f466f36ae0">llvm::AVRAsmPrinter::PrintAsmMemoryOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/avrasmprinter/#abb1c33c814741adb78a9ff7f10ff3552">llvm::AVRAsmPrinter::PrintAsmOperand</a>.</p>

</div>
</div>

### getRegMayBeFolded() {#aafed3f8d7e82cd37afdf3bb1cf6947dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::getRegMayBeFolded ()</td>
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



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/bitfield/#a3cd3d6331b8a3ea50db05696debf2075">llvm::Bitfield::get</a>, <a href="#ade52bc57cc65e30baccebb56b76ec13a">isRegDefEarlyClobberKind</a>, <a href="#afcdcd14f56fb520a400bc05c39078384">isRegDefKind</a> and <a href="#a5ad0684888a368762fa9b2cdc6acd025">isRegUseKind</a>.</p>

</div>
</div>

### hasRegClassConstraint() {#a582ec155bb1507a15c1c7fb46bc53fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::hasRegClassConstraint (unsigned &amp; RC)</td>
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

<p>hasRegClassConstraint - Returns true if the flag contains a register class constraint.</p>


<p>Sets RC to the register class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>.</p>


<p>Definition at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### isClobberKind() {#a2a3c74e25ebbff757c8c2ecb35cf9892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isClobberKind ()</td>
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



<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94ac50132234eb8c934e71b7f2f0fa5099c">llvm::InlineAsm::Clobber</a> and <a href="#a41c081604f65f65850620181db33f548">getKind</a>.</p>

</div>
</div>

### isFuncKind() {#acfcd5603bc1201c6c18a4f18f3278c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isFuncKind ()</td>
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



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a00d0b4f2d7dcdaaef835b97cf5d1e0df">llvm::InlineAsm::Func</a> and <a href="#a41c081604f65f65850620181db33f548">getKind</a>.</p>


<p>Referenced by <a href="#a41a1d51570ca5ad847d74f1f7b020ad0">clearMemConstraint</a> and <a href="#a945eeecdf3b5f4969d9c5aa1d1eacec1">getMemoryConstraintID</a>.</p>

</div>
</div>

### isImmKind() {#a28636c0e24d9760687e5f66d02051a2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isImmKind ()</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#a41c081604f65f65850620181db33f548">getKind</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94ada9470e1aa5be1858e667318254dcb4b">llvm::InlineAsm::Imm</a>.</p>


<p>Referenced by <a href="#a2cf882e839e78f88340e664afcd87e5d">setRegClass</a>.</p>

</div>
</div>

### isMemKind() {#a637e8098e756e55d2aba0a6f41adbd2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isMemKind ()</td>
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



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#a41c081604f65f65850620181db33f548">getKind</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94adba5553473d129a7985fb532dc249ff4">llvm::InlineAsm::Mem</a>.</p>


<p>Referenced by <a href="#a41a1d51570ca5ad847d74f1f7b020ad0">clearMemConstraint</a>, <a href="#a945eeecdf3b5f4969d9c5aa1d1eacec1">getMemoryConstraintID</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a> and <a href="#a2cf882e839e78f88340e664afcd87e5d">setRegClass</a>.</p>

</div>
</div>

### isRegDefEarlyClobberKind() {#ade52bc57cc65e30baccebb56b76ec13a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isRegDefEarlyClobberKind ()</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#a41c081604f65f65850620181db33f548">getKind</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94adda36cdb69635bdfb9f3d925753dc2d3">llvm::InlineAsm::RegDefEarlyClobber</a>.</p>


<p>Referenced by <a href="#aafed3f8d7e82cd37afdf3bb1cf6947dd">getRegMayBeFolded</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a> and <a href="#a15203762d44a454199820de3b1e09f20">setRegMayBeFolded</a>.</p>

</div>
</div>

### isRegDefKind() {#afcdcd14f56fb520a400bc05c39078384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isRegDefKind ()</td>
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



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#a41c081604f65f65850620181db33f548">getKind</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a1fbd4693daf9a506101ec4cd36caa8dd">llvm::InlineAsm::RegDef</a>.</p>


<p>Referenced by <a href="#aafed3f8d7e82cd37afdf3bb1cf6947dd">getRegMayBeFolded</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a> and <a href="#a15203762d44a454199820de3b1e09f20">setRegMayBeFolded</a>.</p>

</div>
</div>

### isRegUseKind() {#a5ad0684888a368762fa9b2cdc6acd025}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isRegUseKind ()</td>
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



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#a41c081604f65f65850620181db33f548">getKind</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a49585056d1d7051dd2bd6f012e5b5e94a4ac13b7b2bba42947e897ffdf8797788">llvm::InlineAsm::RegUse</a>.</p>


<p>Referenced by <a href="#aafed3f8d7e82cd37afdf3bb1cf6947dd">getRegMayBeFolded</a> and <a href="#a15203762d44a454199820de3b1e09f20">setRegMayBeFolded</a>.</p>

</div>
</div>

### isUseOperandTiedToDef() {#ab43f08d6db156a53503ccf3a7ef0176a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isUseOperandTiedToDef (unsigned &amp; Idx)</td>
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

<p>isUseOperandTiedToDef - Return true if the flag of the inline asm operand indicates it is an use operand that's matched to a def operand.</p>

<p>Definition at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### setMatchingOp() {#a8a3a4a2d14c39019e5cd648081a33419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsm::Flag::setMatchingOp (unsigned OperandNo)</td>
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

<p>setMatchingOp - Augment an existing flag with information indicating that this input operand is tied to a previous output operand.</p>

<p>Definition at line 391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfield/#aac5c44667e3b3ebe2ed424dbd12a35d5">llvm::Bitfield::set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>.</p>

</div>
</div>

### setMemConstraint() {#a8de6bf65ca1443186731a3391c02d1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsm::Flag::setMemConstraint (<a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0">ConstraintCode</a> C)</td>
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

<p>setMemConstraint - Augment an existing flag with the constraint code for a memory constraint.</p>

<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a945eeecdf3b5f4969d9c5aa1d1eacec1">getMemoryConstraintID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitfield/#aac5c44667e3b3ebe2ed424dbd12a35d5">llvm::Bitfield::set</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af73223719f15f8ca95f36ce43aa9d6d0a88183b946cc5f0e8c96b2e66e1c74a7e">llvm::InlineAsm::Unknown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>.</p>

</div>
</div>

### setRegClass() {#a2cf882e839e78f88340e664afcd87e5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsm::Flag::setRegClass (unsigned RC)</td>
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

<p>setRegClass - Augment an existing flag with the required register class for the following register operands.</p>


<p>A tied use operand cannot have a register class, use the register class from the def operand instead.</p>


<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a28636c0e24d9760687e5f66d02051a2f">isImmKind</a>, <a href="#a637e8098e756e55d2aba0a6f41adbd2f">isMemKind</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfield/#aac5c44667e3b3ebe2ed424dbd12a35d5">llvm::Bitfield::set</a>.</p>

</div>
</div>

### setRegMayBeFolded() {#a15203762d44a454199820de3b1e09f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InlineAsm::Flag::setRegMayBeFolded (bool B)</td>
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

<p>Set a bit to denote that while this operand is some kind of register (use, def, ...), a memory flag did appear in the original constraint list.</p>


<p>This is set by the instruction selection framework, and consumed by the register allocator. While the register allocator is generally responsible for spilling registers, we need to be able to distinguish between registers that the register allocator has permission to fold ("rm") vs ones it does not ("r"). This is because the inline asm may use instructions which don't support memory addressing modes for that operand.</p>


<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ade52bc57cc65e30baccebb56b76ec13a">isRegDefEarlyClobberKind</a>, <a href="#afcdcd14f56fb520a400bc05c39078384">isRegDefKind</a>, <a href="#a5ad0684888a368762fa9b2cdc6acd025">isRegUseKind</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfield/#aac5c44667e3b3ebe2ed424dbd12a35d5">llvm::Bitfield::set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getMatchedOperandNo() {#ad229d9fd0dd47e5efab7847e146d2a11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InlineAsm::Flag::getMatchedOperandNo ()</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### getRegClass() {#a27105df40cca150310c4bf7cc68b21da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InlineAsm::Flag::getRegClass ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

### isMatched() {#a449ce7a0c48a469392bdbfb0bf4be907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::Flag::isMatched ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Storage {#a64014b6a3fcec66c9bcd7b3bf4a6efab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::InlineAsm::Flag::Storage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
