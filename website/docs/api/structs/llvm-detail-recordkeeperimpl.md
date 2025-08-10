---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/detail/recordkeeperimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `RecordKeeperImpl` Struct

<p>This class represents the internal implementation of the <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::detail::RecordKeeperImpl { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a> (RecordKeeper &amp;RK)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc3aa7225f620417d5fb1e00b916c84c">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/bitsrecty">BitsRecTy</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a686db9c9203965a09be47d948800d0fe">SharedBitsRecTys</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitrecty">BitRecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4152d28407af25b62ab2ce8b04dbf64">SharedBitRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/intrecty">IntRecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2f40e9428437bc4ebab74672f142217">SharedIntRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringrecty">StringRecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a379e43dc7a3a96cb7341210482785583">SharedStringRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dagrecty">DagRecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73f80128a616ab845d1988433c39b17b">SharedDagRecTy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/recordrecty">RecordRecTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe06acd9f788b873dc27457de3dda93">AnyRecord</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unsetinit">UnsetInit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53dfbad31b92c5ce794cf6114494975">TheUnsetInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitinit">BitInit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeb426c5e82b238b260e882ae3cc9674">TrueBitInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/bitinit">BitInit</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae211a52613d6b03accf4a442a3bced0e">FalseBitInit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/argumentinit">ArgumentInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a354a22c7324b5c9589435a591de42544">TheArgumentInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/bitsinit">BitsInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a002c8778523ea4e7babfb5399bfb2a9b">TheBitsInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; int64_t, <a href="/web-llvm/docs/api/classes/llvm/intinit">IntInit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae8797983f19270144045222fa4a90d">TheIntInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4711c66d71057fad8e909392daf0770">StringInitStringPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> *, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45b8c8d01a3a9df9b8bf9e47933b4764">StringInitCodePool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/listinit">ListInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5251e4522a7a3693e8fdee74bb0ea50">TheListInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/unopinit">UnOpInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d3a1d7b1cdd5547d33b9573954e4ccc">TheUnOpInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/binopinit">BinOpInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31064463a9e071281b851e026f38dd09">TheBinOpInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ternopinit">TernOpInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b57e14c08c366db48feca6c47657c4">TheTernOpInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/foldopinit">FoldOpInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b7c8c73ed3c1ce4059644c7302fd077">TheFoldOpInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/isaopinit">IsAOpInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1220143566599bbb70550f9f50f2e3fd">TheIsAOpInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/existsopinit">ExistsOpInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e92972ff4e6e7a0734577f16e71ca3">TheExistsOpInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recty">RecTy</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/varinit">VarInit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0dcbc7172055c3ab61148b6198c682f8">TheVarInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/typedinit">TypedInit</a> *, unsigned &gt;, <a href="/web-llvm/docs/api/classes/llvm/varbitinit">VarBitInit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d8b00c13bc54218380461fba9d4863b">TheVarBitInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/vardefinit">VarDefInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a39d838dba7b78ac661b60cb22f64ed1f">TheVarDefInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/init">Init</a> *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringinit">StringInit</a> * &gt;, <a href="/web-llvm/docs/api/classes/llvm/fieldinit">FieldInit</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafdf6648bdd6bb8ebcf1fbaa31364fa8">TheFieldInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/condopinit">CondOpInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a233d085aeefe5d484201778ed7e648bd">TheCondOpInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/daginit">DagInit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6443cac27a1b84fb63bfa0e07adad6">TheDagInitPool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/recordrecty">RecordRecTy</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37aebac9674915d4066df49ae2d275e0">RecordTypePool</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c3916c9542da36d9bfd1d84da673c2">AnonCounter</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec9fd69ba3f48d5706ab65078de3103">LastRecordID</a></td>
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

<p>This class represents the internal implementation of the <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a>.</p>


<p>It contains all of the contextual static state of the <a href="/web-llvm/docs/api/classes/llvm/record">Record</a> classes. It is kept out-of-line to simplify dependencies, and also make it easier for internal classes to access the uniquer state of the keeper.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RecordKeeperImpl() {#af84c49c869ad907f891c5c1c81440b4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::detail::RecordKeeperImpl::RecordKeeperImpl (<a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; RK)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#abc3aa7225f620417d5fb1e00b916c84c">Allocator</a>, <a href="#af7c3916c9542da36d9bfd1d84da673c2">AnonCounter</a>, <a href="#a8fe06acd9f788b873dc27457de3dda93">AnyRecord</a>, <a href="#ae211a52613d6b03accf4a442a3bced0e">FalseBitInit</a>, <a href="#a3ec9fd69ba3f48d5706ab65078de3103">LastRecordID</a>, <a href="#ae4152d28407af25b62ab2ce8b04dbf64">SharedBitRecTy</a>, <a href="#a73f80128a616ab845d1988433c39b17b">SharedDagRecTy</a>, <a href="#aa2f40e9428437bc4ebab74672f142217">SharedIntRecTy</a>, <a href="#a379e43dc7a3a96cb7341210482785583">SharedStringRecTy</a>, <a href="#a45b8c8d01a3a9df9b8bf9e47933b4764">StringInitCodePool</a>, <a href="#ae4711c66d71057fad8e909392daf0770">StringInitStringPool</a>, <a href="#ac53dfbad31b92c5ce794cf6114494975">TheUnsetInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> and <a href="#aeeb426c5e82b238b260e882ae3cc9674">TrueBitInit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpAllocationStats() {#aaee2f2fd06a756743658cb259d7659aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void detail::RecordKeeperImpl::dumpAllocationStats (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>References <a href="#abc3aa7225f620417d5fb1e00b916c84c">Allocator</a>, <a href="#af7c3916c9542da36d9bfd1d84da673c2">AnonCounter</a>, <a href="#a3ec9fd69ba3f48d5706ab65078de3103">LastRecordID</a>, <a href="#a37aebac9674915d4066df49ae2d275e0">RecordTypePool</a>, <a href="#a45b8c8d01a3a9df9b8bf9e47933b4764">StringInitCodePool</a>, <a href="#ae4711c66d71057fad8e909392daf0770">StringInitStringPool</a>, <a href="#a354a22c7324b5c9589435a591de42544">TheArgumentInitPool</a>, <a href="#a31064463a9e071281b851e026f38dd09">TheBinOpInitPool</a>, <a href="#a002c8778523ea4e7babfb5399bfb2a9b">TheBitsInitPool</a>, <a href="#a233d085aeefe5d484201778ed7e648bd">TheCondOpInitPool</a>, <a href="#a1b6443cac27a1b84fb63bfa0e07adad6">TheDagInitPool</a>, <a href="#ad7e92972ff4e6e7a0734577f16e71ca3">TheExistsOpInitPool</a>, <a href="#aafdf6648bdd6bb8ebcf1fbaa31364fa8">TheFieldInitPool</a>, <a href="#a0b7c8c73ed3c1ce4059644c7302fd077">TheFoldOpInitPool</a>, <a href="#a0ae8797983f19270144045222fa4a90d">TheIntInitPool</a>, <a href="#a1220143566599bbb70550f9f50f2e3fd">TheIsAOpInitPool</a>, <a href="#af5251e4522a7a3693e8fdee74bb0ea50">TheListInitPool</a>, <a href="#ab8b57e14c08c366db48feca6c47657c4">TheTernOpInitPool</a>, <a href="#a7d3a1d7b1cdd5547d33b9573954e4ccc">TheUnOpInitPool</a>, <a href="#a4d8b00c13bc54218380461fba9d4863b">TheVarBitInitPool</a>, <a href="#a39d838dba7b78ac661b60cb22f64ed1f">TheVarDefInitPool</a> and <a href="#a0dcbc7172055c3ab61148b6198c682f8">TheVarInitPool</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Allocator {#abc3aa7225f620417d5fb1e00b916c84c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::detail::RecordKeeperImpl::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a>, <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a893536c2fd7da5432de36d921a28f43d">llvm::ArgumentInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a1717b7dc956fb447c4fd0a8ce3941b05">llvm::BinOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ad964d60acd20953d20b1e673a397d5e2">llvm::BitsInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/bitsrecty/#a69d60b388546684e9c996413e10a8277">llvm::BitsRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a181dad1cdd60a83a181108d90acd4738">llvm::CondOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/daginit/#a8068bfe8ffd6450e61e72665e6887abc">llvm::DagInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/existsopinit/#a6ac5a9f0855b6aca3ac69ac0e53dc74f">llvm::ExistsOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#ac7db1d01257de9e35b1e558e20dd972b">llvm::FieldInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#a5ba8defa3668a92cb593c24e470c5f46">llvm::FoldOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/isaopinit/#a57c423ecdbcd1ff885f552a699e57de3">llvm::IsAOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/listinit/#a43379a4cffc2ed53c7bf95fe72e60454">llvm::ListInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a>, <a href="/web-llvm/docs/api/classes/llvm/stringinit/#a63edb20ca7b47e34fcb1f8df74d6424f">llvm::StringInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#acfaa331daa279dcd3a22f04d1830cf7f">llvm::TernOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/unopinit/#aa8ac284a20b1ea9f96469bf3d39d1f81">llvm::UnOpInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/varbitinit/#a0496581f233ebba1beda1293a803b573">llvm::VarBitInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vardefinit/#a79b06bf58989430bbbad88e098ce32b6">llvm::VarDefInit::get</a>, <a href="/web-llvm/docs/api/classes/llvm/varinit/#a622b0acac89ccc288d4d81425fc037cf">llvm::VarInit::get</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### AnonCounter {#af7c3916c9542da36d9bfd1d84da673c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::detail::RecordKeeperImpl::AnonCounter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### AnyRecord {#a8fe06acd9f788b873dc27457de3dda93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RecordRecTy llvm::detail::RecordKeeperImpl::AnyRecord</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### FalseBitInit {#ae211a52613d6b03accf4a442a3bced0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitInit llvm::detail::RecordKeeperImpl::FalseBitInit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitinit/#a783941ee3db6dc99f068008ebca36a55">llvm::BitInit::get</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### LastRecordID {#a3ec9fd69ba3f48d5706ab65078de3103}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::detail::RecordKeeperImpl::LastRecordID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a>, <a href="/web-llvm/docs/api/classes/llvm/record/#a135a92f99d0c34b158c54a1f3191dae2">llvm::Record::getNewUID</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### RecordTypePool {#a37aebac9674915d4066df49ae2d275e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;RecordRecTy&gt; llvm::detail::RecordKeeperImpl::RecordTypePool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/recordrecty/#af99419a971a2b329732cb2a89e6a004b">llvm::RecordRecTy::get</a>.</p>

</div>
</div>

### SharedBitRecTy {#ae4152d28407af25b62ab2ce8b04dbf64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitRecTy llvm::detail::RecordKeeperImpl::SharedBitRecTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### SharedBitsRecTys {#a686db9c9203965a09be47d948800d0fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;BitsRecTy *&gt; llvm::detail::RecordKeeperImpl::SharedBitsRecTys</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitsrecty/#a69d60b388546684e9c996413e10a8277">llvm::BitsRecTy::get</a>.</p>

</div>
</div>

### SharedDagRecTy {#a73f80128a616ab845d1988433c39b17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DagRecTy llvm::detail::RecordKeeperImpl::SharedDagRecTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### SharedIntRecTy {#aa2f40e9428437bc4ebab74672f142217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntRecTy llvm::detail::RecordKeeperImpl::SharedIntRecTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### SharedStringRecTy {#a379e43dc7a3a96cb7341210482785583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRecTy llvm::detail::RecordKeeperImpl::SharedStringRecTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### StringInitCodePool {#a45b8c8d01a3a9df9b8bf9e47933b4764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;const StringInit *, BumpPtrAllocator &amp;&gt; llvm::detail::RecordKeeperImpl::StringInitCodePool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a>, <a href="/web-llvm/docs/api/classes/llvm/stringinit/#a63edb20ca7b47e34fcb1f8df74d6424f">llvm::StringInit::get</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### StringInitStringPool {#ae4711c66d71057fad8e909392daf0770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;const StringInit *, BumpPtrAllocator &amp;&gt; llvm::detail::RecordKeeperImpl::StringInitStringPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a>, <a href="/web-llvm/docs/api/classes/llvm/stringinit/#a63edb20ca7b47e34fcb1f8df74d6424f">llvm::StringInit::get</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### TheArgumentInitPool {#a354a22c7324b5c9589435a591de42544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;ArgumentInit&gt; llvm::detail::RecordKeeperImpl::TheArgumentInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/argumentinit/#a893536c2fd7da5432de36d921a28f43d">llvm::ArgumentInit::get</a>.</p>

</div>
</div>

### TheBinOpInitPool {#a31064463a9e071281b851e026f38dd09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;BinOpInit&gt; llvm::detail::RecordKeeperImpl::TheBinOpInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/binopinit/#a1717b7dc956fb447c4fd0a8ce3941b05">llvm::BinOpInit::get</a>.</p>

</div>
</div>

### TheBitsInitPool {#a002c8778523ea4e7babfb5399bfb2a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;BitsInit&gt; llvm::detail::RecordKeeperImpl::TheBitsInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/bitsinit/#ad964d60acd20953d20b1e673a397d5e2">llvm::BitsInit::get</a>.</p>

</div>
</div>

### TheCondOpInitPool {#a233d085aeefe5d484201778ed7e648bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;CondOpInit&gt; llvm::detail::RecordKeeperImpl::TheCondOpInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/condopinit/#a181dad1cdd60a83a181108d90acd4738">llvm::CondOpInit::get</a>.</p>

</div>
</div>

### TheDagInitPool {#a1b6443cac27a1b84fb63bfa0e07adad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;DagInit&gt; llvm::detail::RecordKeeperImpl::TheDagInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/daginit/#a8068bfe8ffd6450e61e72665e6887abc">llvm::DagInit::get</a>.</p>

</div>
</div>

### TheExistsOpInitPool {#ad7e92972ff4e6e7a0734577f16e71ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;ExistsOpInit&gt; llvm::detail::RecordKeeperImpl::TheExistsOpInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/existsopinit/#a6ac5a9f0855b6aca3ac69ac0e53dc74f">llvm::ExistsOpInit::get</a>.</p>

</div>
</div>

### TheFieldInitPool {#aafdf6648bdd6bb8ebcf1fbaa31364fa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const Init *, const StringInit *&gt;, FieldInit *&gt; llvm::detail::RecordKeeperImpl::TheFieldInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/fieldinit/#ac7db1d01257de9e35b1e558e20dd972b">llvm::FieldInit::get</a>.</p>

</div>
</div>

### TheFoldOpInitPool {#a0b7c8c73ed3c1ce4059644c7302fd077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;FoldOpInit&gt; llvm::detail::RecordKeeperImpl::TheFoldOpInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/foldopinit/#a5ba8defa3668a92cb593c24e470c5f46">llvm::FoldOpInit::get</a>.</p>

</div>
</div>

### TheIntInitPool {#a0ae8797983f19270144045222fa4a90d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;int64_t, IntInit *&gt; llvm::detail::RecordKeeperImpl::TheIntInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/intinit/#a1687f29bfe4a2532bf2351ce5fdba915">llvm::IntInit::get</a>.</p>

</div>
</div>

### TheIsAOpInitPool {#a1220143566599bbb70550f9f50f2e3fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;IsAOpInit&gt; llvm::detail::RecordKeeperImpl::TheIsAOpInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/isaopinit/#a57c423ecdbcd1ff885f552a699e57de3">llvm::IsAOpInit::get</a>.</p>

</div>
</div>

### TheListInitPool {#af5251e4522a7a3693e8fdee74bb0ea50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;ListInit&gt; llvm::detail::RecordKeeperImpl::TheListInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/listinit/#a43379a4cffc2ed53c7bf95fe72e60454">llvm::ListInit::get</a>.</p>

</div>
</div>

### TheTernOpInitPool {#ab8b57e14c08c366db48feca6c47657c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;TernOpInit&gt; llvm::detail::RecordKeeperImpl::TheTernOpInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/ternopinit/#acfaa331daa279dcd3a22f04d1830cf7f">llvm::TernOpInit::get</a>.</p>

</div>
</div>

### TheUnOpInitPool {#a7d3a1d7b1cdd5547d33b9573954e4ccc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;UnOpInit&gt; llvm::detail::RecordKeeperImpl::TheUnOpInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/unopinit/#aa8ac284a20b1ea9f96469bf3d39d1f81">llvm::UnOpInit::get</a>.</p>

</div>
</div>

### TheUnsetInit {#ac53dfbad31b92c5ce794cf6114494975}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnsetInit llvm::detail::RecordKeeperImpl::TheUnsetInit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

### TheVarBitInitPool {#a4d8b00c13bc54218380461fba9d4863b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const TypedInit *, unsigned&gt;, VarBitInit *&gt; llvm::detail::RecordKeeperImpl::TheVarBitInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/varbitinit/#a0496581f233ebba1beda1293a803b573">llvm::VarBitInit::get</a>.</p>

</div>
</div>

### TheVarDefInitPool {#a39d838dba7b78ac661b60cb22f64ed1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;VarDefInit&gt; llvm::detail::RecordKeeperImpl::TheVarDefInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/vardefinit/#a79b06bf58989430bbbad88e098ce32b6">llvm::VarDefInit::get</a>.</p>

</div>
</div>

### TheVarInitPool {#a0dcbc7172055c3ab61148b6198c682f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;const RecTy *, const Init *&gt;, VarInit *&gt; llvm::detail::RecordKeeperImpl::TheVarInitPool</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="#aaee2f2fd06a756743658cb259d7659aa">dumpAllocationStats</a> and <a href="/web-llvm/docs/api/classes/llvm/varinit/#a622b0acac89ccc288d4d81425fc037cf">llvm::VarInit::get</a>.</p>

</div>
</div>

### TrueBitInit {#aeeb426c5e82b238b260e882ae3cc9674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitInit llvm::detail::RecordKeeperImpl::TrueBitInit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/bitinit/#a783941ee3db6dc99f068008ebca36a55">llvm::BitInit::get</a> and <a href="#af84c49c869ad907f891c5c1c81440b4f">RecordKeeperImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/record-cpp">Record.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
