---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/basicblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BasicBlock` Class Reference

<p>LLVM Basic Block Representation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BasicBlock { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">llvm/IR/BasicBlock.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> Representation. <a href="/web-llvm/docs/api/classes/llvm/value/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent">ilist_node_with_parent&lt;NodeTy, ParentTy, Options&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An ilist node that can access its parent list. <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a0ce432860a8f51d6128dd940f09439">InstListType</a> = <a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-iterator-bits">ilist_iterator_bits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> iterators... <a href="#a98c0a84a5dfa8bce341c829709f171e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a7d51fdde6913db72d098356c2c019">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">InstListType::const_iterator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d3231fb84ed4182ec22e9442a87dbf8">reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3597c16fc1832e39109d9848a63cc55c">InstListType::reverse_iterator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e3fb8772d71532ca4a0703ddea7f02">const_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a297861b8ff76496286b3bea882c2969a">InstListType::const_reverse_iterator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cee0dc827c0d67b44ee9e5e92c9e5c">phi_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/basicblock/phi-iterator-impl">phi_iterator_impl</a>&lt;&gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb55ac72e73c18333ef7af316b0a3352">const_phi_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/basicblock/phi-iterator-impl">phi_iterator_impl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, <a href="#a42a7d51fdde6913db72d098356c2c019">BasicBlock::const_iterator</a> &gt;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf5ebc4fa3006b5e52a0e6d02672a09e">BlockAddress</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11c7b04e5390fe7e163bf1ad039c757a">SymbolTableListTraits&lt; BasicBlock &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7aad53c2632b8eba7b192fdd35ff068">llvm::SymbolTableListTraits&lt; llvm::Instruction, ilist_iterator_bits&lt; true &gt;, ilist_parent&lt; BasicBlock &gt; &gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aeb66cb0986bfcb3c26e2b563194a25">llvm::ilist_node_with_parent&lt; llvm::Instruction, llvm::BasicBlock, ilist_iterator_bits&lt; true &gt;, ilist_parent&lt; BasicBlock &gt; &gt;</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be34ea0f6bb2f1c928e200c4a8fa5ef">Instruction::removeFromParent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c464ef563b721bcb04c8a998c30cabd">Instruction::eraseFromParent</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada9d53212698a02af2ec8cc05ae3f5d0">Instruction::insertInto</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193396bde318d1df3007eeb0a9afb296">Instruction::insertBefore</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff8c2039984eaa49dcaabc27d62ab89">Instruction::insertAfter</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98b1b6868b494dafb8501b53ce9b672">Instruction::insertAfter</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e35e2d0faac57d69f8ff3dab5b627fe">Instruction::insertBefore</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a728e79057a50862080bcc96dfce14f18">Instruction::moveBeforeImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a35975cf965c120e55130f30dd377418d">DbgRecord::self_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e0a718e94aeee6a4eab13eea47664da">Instruction::cloneDebugInfoFrom</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a092f0c59f208feb3688bcdf7795e228a">BasicBlock</a> (const BasicBlock &amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d81089e8a1627663ea9ae51707ff10">BasicBlock</a> (LLVMContext &amp;C, const Twine &amp;Name="", Function *Parent=nullptr, BasicBlock *InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor. <a href="#a27d81089e8a1627663ea9ae51707ff10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a03933e831cb54c02b5068ebc30478">~BasicBlock</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1818247419c0b8a88bf6de2f8cd4758">operator=</a> (const BasicBlock &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27413d863d6f6e778b34b1369b10ecf6">createMarker</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attach a <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> to the given instruction. <a href="#a27413d863d6f6e778b34b1369b10ecf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0269c36140cc599f3a97609c091f514d">createMarker</a> (InstListType::iterator It)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ead08d4d049585ee09421bcebd2ae25">convertToNewDbgValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert variable location debugging information stored in dbg.value intrinsics into DbgMarkers / DbgRecords. <a href="#a3ead08d4d049585ee09421bcebd2ae25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5753230c9e297fed32356ebf071074f0">convertFromNewDbgValues</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert variable location debugging information stored in DbgMarkers and DbgRecords into the dbg.value intrinsic representation. <a href="#a5753230c9e297fed32356ebf071074f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4425b120dc5e5600864748818fb1d923">setIsNewDbgInfoFormat</a> (bool NewFlag)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Ensure the block is in "old" dbg.value format (<span class="doxyComputerOutput">NewFlag</span> == false) or in the new format (<span class="doxyComputerOutput">NewFlag</span> == true), converting to the desired format if necessary. <a href="#a4425b120dc5e5600864748818fb1d923">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5249c00eee461ca4d26145eaaeac8c">setNewDbgInfoFormatFlag</a> (bool NewFlag)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bf3a7e9bff209ef9f8d2eb194196848">getNumber</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15ee901003da006e9da907c2bf70b9ec">setTrailingDbgRecords</a> (DbgMarker *M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> that the collection of DbgRecords in <span class="doxyComputerOutput">M</span> "trails" after the last instruction of this block. <a href="#a15ee901003da006e9da907c2bf70b9ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9e29bea40c1d36a6e36eeefefe7c073">getTrailingDbgRecords</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fetch the collection of DbgRecords that "trail" after the last instruction of this block, see <a href="#a15ee901003da006e9da907c2bf70b9ec">setTrailingDbgRecords</a>. <a href="#ac9e29bea40c1d36a6e36eeefefe7c073">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11abbc5a7c92e8a599756a5230761392">deleteTrailingDbgRecords</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete any trailing DbgRecords at the end of this block, see <a href="#a15ee901003da006e9da907c2bf70b9ec">setTrailingDbgRecords</a>. <a href="#a11abbc5a7c92e8a599756a5230761392">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6677f47b746b45e2b5018ac514b2f25a">dumpDbgValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952da10b9a7ffd3b3bdeefae13c525a3">getMarker</a> (InstListType::iterator It)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> for the position given by <span class="doxyComputerOutput">It</span>, so that DbgRecords can be inserted there. <a href="#a952da10b9a7ffd3b3bdeefae13c525a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefcf861b48fcdb3316d6f452519009c0">getNextMarker</a> (Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> for the position that comes after <span class="doxyComputerOutput">I</span>. <a href="#aefcf861b48fcdb3316d6f452519009c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a930f97c50e2e4eddb8a6cd55a4dfd5bd">insertDbgRecordAfter</a> (DbgRecord *DR, Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> into a block at the position given by <span class="doxyComputerOutput">I</span>. <a href="#a930f97c50e2e4eddb8a6cd55a4dfd5bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365301682c41f8a7094218176d712cda">insertDbgRecordBefore</a> (DbgRecord *DR, InstListType::iterator Here)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> into a block at the position given by <span class="doxyComputerOutput">Here</span>. <a href="#a365301682c41f8a7094218176d712cda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a7dc3732891611f559b06951a6ee85a">flushTerminatorDbgRecords</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Eject any debug-info trailing at the end of a block. <a href="#a7a7dc3732891611f559b06951a6ee85a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac15f880505f4cbe66f407f4e42a8b8b6">reinsertInstInDbgRecords</a> (Instruction *I, std::optional&lt; DbgRecord::self_iterator &gt; Pos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>In rare circumstances instructions can be speculatively removed from blocks, and then be re-inserted back into that position later. <a href="#ac15f880505f4cbe66f407f4e42a8b8b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa286a0f7f5d38488d593bb7ef0ba183e">getContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the context in which this basic block lives. <a href="#aa286a0f7f5d38488d593bb7ef0ba183e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4bf7c97cdc8159fd73d48063f0b250">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the enclosing method, or null if none. <a href="#a1b4bf7c97cdc8159fd73d48063f0b250">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8418f5e52a18c1b1ab5860eb591fd325">getParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc70e919c88c86159cc94cea29b6c210">getModule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the module owning the function this basic block belongs to, or nullptr if the function does not have a module. <a href="#afc70e919c88c86159cc94cea29b6c210">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48866af4e264e8d94bc56058eb74608b">getModule</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a858cab21fd29000697171b2f5b4bde31">getDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the data layout of the module this basic block belongs to. <a href="#a858cab21fd29000697171b2f5b4bde31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9e9fcf4c5dfce90276ca16d91b8e46">getTerminator</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the terminator instruction if the block is well formed or null if the block is not well formed. <a href="#aef9e9fcf4c5dfce90276ca16d91b8e46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf87930bfa1c4483b0d94ce7b8622a91">getTerminator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6796a84f02394ce6ebef227c866cd5eb">getTerminatingDeoptimizeCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the call instruction calling @llvm.experimental.deoptimize prior to the terminating return instruction of this basic block, if such a call is present. <a href="#a6796a84f02394ce6ebef227c866cd5eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab60db4e6c6df756daf688cf7ea76293c">getTerminatingDeoptimizeCall</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a9915f25abfe7ff5010da686e446c2">getPostdominatingDeoptimizeCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the call instruction calling @llvm.experimental.deoptimize that is present either in current basic block or in block that is a unique successor to current block, if such call is present. <a href="#ae8a9915f25abfe7ff5010da686e446c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa686e5eb0f14cc06211dd7b571736ff3">getPostdominatingDeoptimizeCall</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7038933b96247814b611635abb9686c">getTerminatingMustTailCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the call instruction marked 'musttail' prior to the terminating return instruction of this basic block, if such a call is present. <a href="#ad7038933b96247814b611635abb9686c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb5567bfc9bdf953e2d365ef7a3a54ae">getTerminatingMustTailCall</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05695d7068e19f1799ed15ed7523a957">getFirstNonPHI</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> instruction. <a href="#a05695d7068e19f1799ed15ed7523a957">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e1c5961974e47ac42e9c34efa0792b3">LLVM_DEPRECATED</a> ("Use iterators as instruction positions instead", "getFirstNonPHIIt") Instruction *getFirstNonPHI()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">InstListType::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a362b5e6097732cbc0d2fb555a1f73400">getFirstNonPHIIt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> instruction. <a href="#a362b5e6097732cbc0d2fb555a1f73400">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f7c650ab0603ed231ff2c0d1aac823">getFirstNonPHIIt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">InstListType::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50909227135ef69932bff39b8ea3f572">getFirstNonPHIOrDbg</a> (bool SkipPseudoOp=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> or a debug intrinsic, or any pseudo operation if <span class="doxyComputerOutput">SkipPseudoOp</span> is true. <a href="#a50909227135ef69932bff39b8ea3f572">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854ba9598d9eb6c82c8654d032ee6451">getFirstNonPHIOrDbg</a> (bool SkipPseudoOp=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">InstListType::const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac24cd8d28904d8a4eac2dc3d7545355e">getFirstNonPHIOrDbgOrLifetime</a> (bool SkipPseudoOp=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, a debug intrinsic, or a lifetime intrinsic, or any pseudo operation if <span class="doxyComputerOutput">SkipPseudoOp</span> is true. <a href="#ac24cd8d28904d8a4eac2dc3d7545355e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef52a2f1462579cc3c78aa20761288b">getFirstNonPHIOrDbgOrLifetime</a> (bool SkipPseudoOp=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a42a7d51fdde6913db72d098356c2c019">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a161fd4e9fa5367f64c2a4c9e921c3ad3">getFirstInsertionPt</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the first instruction in this block that is suitable for inserting a non-PHI instruction. <a href="#a161fd4e9fa5367f64c2a4c9e921c3ad3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd563bcff8320c4830cc0fc92b64f32">getFirstInsertionPt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a42a7d51fdde6913db72d098356c2c019">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4db88f47575918879912e8ca511756">getFirstNonPHIOrDbgOrAlloca</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, a debug intrinsic, a static alloca or any pseudo operation. <a href="#aab4db88f47575918879912e8ca511756">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab43659d50c2e4ec6521afab18783f1ec">getFirstNonPHIOrDbgOrAlloca</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af17df370366f173939c9b295734d3d63">getFirstMayFaultInst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the first potential AsynchEH faulty instruction currently it checks for loads/stores (which may dereference a null pointer) and calls/invokes (which may propagate exceptions) <a href="#af17df370366f173939c9b295734d3d63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed23acd7f851897e62880b4decaed6a">getFirstMayFaultInst</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="#a42a7d51fdde6913db72d098356c2c019">BasicBlock::const_iterator</a>, std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2069641f358ef416658a2f321ca19d74">instructionsWithoutDebug</a> (bool SkipPseudoOp=true) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a const iterator range over the instructions in the block, skipping any debug instructions. <a href="#a2069641f358ef416658a2f321ca19d74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a>, std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)&gt; &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2e7652c5b25f8c9bfbc4fb59fa912b">instructionsWithoutDebug</a> (bool SkipPseudoOp=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator range over the instructions in the block, skipping any debug instructions. <a href="#a8b2e7652c5b25f8c9bfbc4fb59fa912b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a34dde99f929971dfc4e50bb63dd7aecb">filter_iterator</a>&lt; <a href="#a42a7d51fdde6913db72d098356c2c019">BasicBlock::const_iterator</a>, std::function&lt; bool(constInstruction &amp;)&gt; &gt;::difference_type</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96768456ed4add9aa5b9f56cdd3f6d7f">sizeWithoutDebug</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the basic block ignoring debug instructions. <a href="#a96768456ed4add9aa5b9f56cdd3f6d7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629adad5a5d84929eac0f0b00132af1b">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink 'this' from the containing function, but do not delete it. <a href="#a629adad5a5d84929eac0f0b00132af1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dd327a937563afdb08250abc43820b0">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink 'this' from the containing function and delete it. <a href="#a8dd327a937563afdb08250abc43820b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1fd6437bbfce263b87f01767d950ce5">moveBefore</a> (BasicBlock *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this basic block from its current function and insert it into the function that <span class="doxyComputerOutput">MovePos</span> lives in, right before <span class="doxyComputerOutput">MovePos</span>. <a href="#ac1fd6437bbfce263b87f01767d950ce5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5092f4ba1618a1cf38a1558ee642912f">moveBefore</a> (SymbolTableList&lt; BasicBlock &gt;::iterator MovePos)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507bb47fc498540c91fec0bf95c25907">moveAfter</a> (BasicBlock *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this basic block from its current function and insert it right after <span class="doxyComputerOutput">MovePos</span> in the function <span class="doxyComputerOutput">MovePos</span> lives in. <a href="#a507bb47fc498540c91fec0bf95c25907">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b2a364cd110b83dc5af4e4ef54f0c9d">insertInto</a> (Function *Parent, BasicBlock *InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert unlinked basic block into a function. <a href="#a8b2a364cd110b83dc5af4e4ef54f0c9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59fb91d1691350f7d1b8e8a114e3f2a4">getSinglePredecessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the predecessor of this block if it has a single predecessor block. <a href="#a59fb91d1691350f7d1b8e8a114e3f2a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5688578838361dae8ae2e61da07bbd05">getSinglePredecessor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74aa9daea070e2ad3394a3ec58b7316a">getUniquePredecessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the predecessor of this block if it has a unique predecessor block. <a href="#a74aa9daea070e2ad3394a3ec58b7316a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50665af84942fe71431228a39ed198e9">getUniquePredecessor</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a526630ff85b48f29ac5b4c519c6c2243">hasNPredecessors</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this block has exactly N predecessors. <a href="#a526630ff85b48f29ac5b4c519c6c2243">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae020673b5ca2bae358005b8980413c4c">hasNPredecessorsOrMore</a> (unsigned N) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this block has N predecessors or more. <a href="#ae020673b5ca2bae358005b8980413c4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79c007dcf9fff57e1569e778d7885b5e">getSingleSuccessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the successor of this block if it has a single successor. <a href="#a79c007dcf9fff57e1569e778d7885b5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3f0f8155c3a807947cbd3550919929">getSingleSuccessor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57f1945911ca1e95d0f51d7c3516b529">getUniqueSuccessor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the successor of this block if it has a unique successor. <a href="#a57f1945911ca1e95d0f51d7c3516b529">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47f3ae1882f74b645a2075d7376232d0">getUniqueSuccessor</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4232efd6f56912332e8631bd828eca21">print</a> (raw_ostream &amp;OS, AssemblyAnnotationWriter *AAW=nullptr, bool ShouldPreserveUseListOrder=false, bool IsForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the basic block to an output stream with an optional <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a>. <a href="#a4232efd6f56912332e8631bd828eca21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ed5f3ab3c2e4196ee0cffffa080c062">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> iterator methods. <a href="#a0ed5f3ab3c2e4196ee0cffffa080c062">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a42a7d51fdde6913db72d098356c2c019">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9fdcfbadaf887aed46b04d2cae72865">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b4e7bee9b8575cc7db73329f1a561bd">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a42a7d51fdde6913db72d098356c2c019">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad15634f3c006d9c1ee9a79ceeb3accd9">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6d3231fb84ed4182ec22e9442a87dbf8">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c2af7a9e501d399f06ca7e10eef46e4">rbegin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac7e3fb8772d71532ca4a0703ddea7f02">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9baac351c917e7e5f60d81341f4df0b">rbegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6d3231fb84ed4182ec22e9442a87dbf8">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9237251072bf6816163abc2d053212ee">rend</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ac7e3fb8772d71532ca4a0703ddea7f02">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c3fa28a28df3fb064db524034812f4b">rend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f68be0e2bcdf14f503f45edea63023">size</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a266367eb01c634406b32f816d2d9c6bf">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63cfb2a0dae69153fd961eb335949caa">front</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a6d4a5d9b4dcd337096732c3a97fba">front</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d071e661a02790177ba05f62c7c27d1">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c8359947a7a39375d8f959e4e5bdd8f">back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#acb55ac72e73c18333ef7af316b0a3352">const_phi_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13da92d2694197fbcb5b95fd94e7570d">phis</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a range that iterates over the phis in the basic block. <a href="#a13da92d2694197fbcb5b95fd94e7570d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a07cee0dc827c0d67b44ee9e5e92c9e5c">phi_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0b11faf4e99c215582c8e83b0ac5792">phis</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcc523128392b84e17315b83f249ba1">getValueSymbolTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the symbol table if one exists. <a href="#a4fcc523128392b84e17315b83f249ba1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7844ce6d5301816e9a7bc21d7f08ef2">dropAllReferences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cause all subinstructions to "let go" of all the references that said subinstructions are maintaining. <a href="#ab7844ce6d5301816e9a7bc21d7f08ef2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe7af0c3ec2ef1f525173acd2ea4ba60">removePredecessor</a> (BasicBlock *Pred, bool KeepOneInputPHIs=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update PHI nodes in this <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> before removal of predecessor <span class="doxyComputerOutput">Pred</span>. <a href="#afe7af0c3ec2ef1f525173acd2ea4ba60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf79d516b188e20e18034e5bbfcf6c69">canSplitPredecessors</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52c990590792c91dd20b6d45acebe359">splitBasicBlock</a> (iterator I, const Twine &amp;BBName="", bool Before=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the basic block into two basic blocks at the specified instruction. <a href="#a52c990590792c91dd20b6d45acebe359">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc5caaabd6841e4ab97237ebcaeb86d">splitBasicBlock</a> (Instruction *I, const Twine &amp;BBName="", bool Before=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30def825db848cba7fe11baa870b978f">splitBasicBlockBefore</a> (iterator I, const Twine &amp;BBName="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Split the basic block into two basic blocks at the specified instruction and insert the new basic blocks as the predecessor of the current block. <a href="#a30def825db848cba7fe11baa870b978f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a370c83904cd61faa1cce22906ec5f4c0">splitBasicBlockBefore</a> (Instruction *I, const Twine &amp;BBName="")</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af29f89e91dfd0ae90950f0b1bf49798d">splice</a> (BasicBlock::iterator ToIt, BasicBlock *FromBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer all instructions from <span class="doxyComputerOutput">FromBB</span> to this basic block at <span class="doxyComputerOutput">ToIt</span>. <a href="#af29f89e91dfd0ae90950f0b1bf49798d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb640f1399f315fe3cd89e3168b98b2">splice</a> (BasicBlock::iterator ToIt, BasicBlock *FromBB, BasicBlock::iterator FromIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer one instruction from <span class="doxyComputerOutput">FromBB</span> at <span class="doxyComputerOutput">FromIt</span> to this basic block at <span class="doxyComputerOutput">ToIt</span>. <a href="#a7eb640f1399f315fe3cd89e3168b98b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec78f7040944cf02862cd8f41052979e">splice</a> (BasicBlock::iterator ToIt, BasicBlock *FromBB, BasicBlock::iterator FromBeginIt, BasicBlock::iterator FromEndIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer a range of instructions that belong to <span class="doxyComputerOutput">FromBB</span> from <span class="doxyComputerOutput">FromBeginIt</span> to <span class="doxyComputerOutput">FromEndIt</span>, to this basic block at <span class="doxyComputerOutput">ToIt</span>. <a href="#aec78f7040944cf02862cd8f41052979e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018d5142c1a4469d9296a26a59fe2783">erase</a> (BasicBlock::iterator FromIt, BasicBlock::iterator ToIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erases a range of instructions from <span class="doxyComputerOutput">FromIt</span> to (not including) <span class="doxyComputerOutput">ToIt</span>. <a href="#a018d5142c1a4469d9296a26a59fe2783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a315f26c899f5ea8a780db4740ba95ef4">hasAddressTaken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if there are any uses of this basic block other than direct branches, switches, etc. <a href="#a315f26c899f5ea8a780db4740ba95ef4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7349a5d6bf71f3d3344b37104dc25bf4">replacePhiUsesWith</a> (BasicBlock *Old, BasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update all phi nodes in this basic block to refer to basic block <span class="doxyComputerOutput">New</span> instead of basic block <span class="doxyComputerOutput">Old</span>. <a href="#a7349a5d6bf71f3d3344b37104dc25bf4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a089e003bb688e55b9a91ed4e7fed3678">replaceSuccessorsPhiUsesWith</a> (BasicBlock *Old, BasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update all phi nodes in this basic block's successors to refer to basic block <span class="doxyComputerOutput">New</span> instead of basic block <span class="doxyComputerOutput">Old</span>. <a href="#a089e003bb688e55b9a91ed4e7fed3678">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d40bb95f61f8696b3b802cb8c203e4">replaceSuccessorsPhiUsesWith</a> (BasicBlock *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update all phi nodes in this basic block's successors to refer to basic block <span class="doxyComputerOutput">New</span> instead of to it. <a href="#a51d40bb95f61f8696b3b802cb8c203e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9c170fde1808bbd4436a0dbd6d5e755">isEHPad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this basic block is an exception handling block. <a href="#ac9c170fde1808bbd4436a0dbd6d5e755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3a2a666b5703b8c9bda318ef18c731c">isLandingPad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this basic block is a landing pad. <a href="#ac3a2a666b5703b8c9bda318ef18c731c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/landingpadinst">LandingPadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1553a166adb52e29e3a240dd37627ad9">getLandingPadInst</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the landingpad instruction associated with the landing pad. <a href="#a1553a166adb52e29e3a240dd37627ad9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/landingpadinst">LandingPadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa7e147d7b2bfe8f75048f51b99ef318">getLandingPadInst</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbe1d6bd7544c2fd2efcdf2d348f264">isLegalToHoistInto</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if it is legal to hoist instructions into this block. <a href="#adfbe1d6bd7544c2fd2efcdf2d348f264">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ec05121d4b54b3691ad6203e78ff54e">isEntryBlock</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is the entry block of the containing function. <a href="#a4ec05121d4b54b3691ad6203e78ff54e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e873ca436db6d4200ac469fcc253374">getIrrLoopHeaderWeight</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4e597933a0ba6d26ec65cc1beb61eb2">isInstrOrderValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the Order field of child Instructions is valid. <a href="#ae4e597933a0ba6d26ec65cc1beb61eb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ae48e763a7081850f72cfe7695bcd5">invalidateOrders</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark instruction ordering invalid. Done on every instruction insert. <a href="#a38ae48e763a7081850f72cfe7695bcd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f6d0ee6e9018d68250f49b9e3001139">renumberInstructions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Renumber instructions and mark the ordering as valid. <a href="#a1f6d0ee6e9018d68250f49b9e3001139">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9458ac6ff40d62e47321f8681cc23d54">validateInstrOrdering</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asserts that instruction order numbers are marked invalid, or that they are in ascending order. <a href="#a9458ac6ff40d62e47321f8681cc23d54">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d222c91a3197e01b76a5d73cb58d80">setParent</a> (Function *parent)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a7a0ce432860a8f51d6128dd940f09439">InstListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5153e86482ada896764e15fa2c229e8">getInstList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the underlying instruction list container. <a href="#ad5153e86482ada896764e15fa2c229e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7a0ce432860a8f51d6128dd940f09439">InstListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ac16f503d0763b23aa9ebd5fa14ac6">getInstList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca70ca9ca9d95b2368c0d96f2088c2a">spliceDebugInfoEmptyBlock</a> (BasicBlock::iterator ToIt, BasicBlock *FromBB, BasicBlock::iterator FromBeginIt, BasicBlock::iterator FromEndIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dedicated function for splicing debug-info: when we have an empty splice (i.e. <a href="#a8ca70ca9ca9d95b2368c0d96f2088c2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adabab3e391aec9a349e44767635cf2f2">spliceDebugInfo</a> (BasicBlock::iterator ToIt, BasicBlock *FromBB, BasicBlock::iterator FromBeginIt, BasicBlock::iterator FromEndIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform any debug-info specific maintenence for the given splice activity. <a href="#adabab3e391aec9a349e44767635cf2f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8335e14738ac93e766958f1cd92a802a">spliceDebugInfoImpl</a> (BasicBlock::iterator ToIt, BasicBlock *FromBB, BasicBlock::iterator FromBeginIt, BasicBlock::iterator FromEndIt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">BasicBlockBits</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a645b50d89a22637c8edb57bd0dcd3d">getBasicBlockBits</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Safely reinterpret the subclass data bits to a more useful form. <a href="#a9a645b50d89a22637c8edb57bd0dcd3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab12b02ce0ec7bf2ebf95135e3e924a1f">setBasicBlockBits</a> (BasicBlockBits AsBits)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reinterpret our subclass bits and store them back into <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="#ab12b02ce0ec7bf2ebf95135e3e924a1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1fd63db7827caba1d32a6505ae8997">AdjustBlockAddressRefCount</a> (int Amt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increment the internal refcount of the number of BlockAddresses referencing this <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> by <span class="doxyComputerOutput">Amt</span>. <a href="#a5a1fd63db7827caba1d32a6505ae8997">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10611776c6385d9bb801c66f2d0d2ce0">setValueSubclassData</a> (unsigned short D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shadow <a href="/web-llvm/docs/api/classes/llvm/value/#aae37705b598ef612f698198dc33d6f65">Value::setValueSubclassData</a> with a private forwarding method so that any future subclasses cannot accidentally use it. <a href="#a10611776c6385d9bb801c66f2d0d2ce0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab571b8358a3a8b6db1327d06bdc5e9f4">IsNewDbgInfoFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag recording whether or not this block stores debug-info in the form of intrinsic instructions (false) or non-instruction records (true). <a href="#ab571b8358a3a8b6db1327d06bdc5e9f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af506f331e4060e97b4151e3bef031303">Number</a> = -1u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Per-function unique number. <a href="#af506f331e4060e97b4151e3bef031303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7a0ce432860a8f51d6128dd940f09439">InstListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc3eb171dc0b6709a64e74208e9a12e">InstList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc87bddc1d4bf05e11935e5845943505">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a5b798214be930cf8e133c032ba0129">Create</a> (LLVMContext &amp;Context, const Twine &amp;Name="", Function *Parent=nullptr, BasicBlock *InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>. <a href="#a4a5b798214be930cf8e133c032ba0129">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dfb5f698e35730791c0176a7c6c4b0a">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast. <a href="#a1dfb5f698e35730791c0176a7c6c4b0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a7a0ce432860a8f51d6128dd940f09439">InstListType</a> BasicBlock::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7709ac1c84ac480a6c0565d4b0182da">getSublistAccess</a> (Instruction *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to a member of the instruction list. <a href="#ab7709ac1c84ac480a6c0565d4b0182da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>LLVM Basic Block Representation.</p>


<p>This represents a single basic block in LLVM. A basic block is simply a container of instructions that execute sequentially. Basic blocks are Values because they are referenced by instructions such as branches and switch tables. The type of a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> is "Type::LabelTy" because the basic block represents a label to which a branch can jump.</p>


<p>A well formed basic block is formed of a list of non-terminating instructions followed by a single terminator instruction. Terminator instructions may not occur in the middle of basic blocks, and must terminate the blocks. The <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> class allows malformed basic blocks to occur because it may be useful in the intermediate stage of constructing or modifying a program. However, the verifier will ensure that basic blocks are "well formed".</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a42a7d51fdde6913db72d098356c2c019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BasicBlock::const_iterator =  InstListType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### const\_phi\_iterator {#acb55ac72e73c18333ef7af316b0a3352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BasicBlock::const_phi_iterator = 
      phi_iterator_impl&lt;const PHINode, BasicBlock::const_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#ac7e3fb8772d71532ca4a0703ddea7f02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BasicBlock::const_reverse_iterator =  InstListType::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### InstListType {#a7a0ce432860a8f51d6128dd940f09439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BasicBlock::InstListType =  SymbolTableList&lt;Instruction, ilist_iterator_bits&lt;true&gt;,
                                       ilist_parent&lt;BasicBlock&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### iterator {#a98c0a84a5dfa8bce341c829709f171e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BasicBlock::iterator =  InstListType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> iterators...</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### phi\_iterator {#a07cee0dc827c0d67b44ee9e5e92c9e5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BasicBlock::phi_iterator =  phi_iterator_impl&lt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### reverse\_iterator {#a6d3231fb84ed4182ec22e9442a87dbf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::BasicBlock::reverse_iterator =  InstListType::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### BlockAddress {#aaf5ebc4fa3006b5e52a0e6d02672a09e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/blockaddress">BlockAddress</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="#aaf5ebc4fa3006b5e52a0e6d02672a09e">BlockAddress</a>, <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aaf5ebc4fa3006b5e52a0e6d02672a09e">BlockAddress</a>.</p>

</div>
</div>

### Function {#ab7194606aa12931e96f8f5448d418ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/function">Function</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>


<p>Referenced by <a href="#aaf5ebc4fa3006b5e52a0e6d02672a09e">BlockAddress</a>, <a href="#a27413d863d6f6e778b34b1369b10ecf6">createMarker</a>, <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>, <a href="#a8418f5e52a18c1b1ab5860eb591fd325">getParent</a> and <a href="#a1b4bf7c97cdc8159fd73d48063f0b250">getParent</a>.</p>

</div>
</div>

### Instruction::cloneDebugInfoFrom {#a3e0a718e94aeee6a4eab13eea47664da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a35975cf965c120e55130f30dd377418d">DbgRecord::self_iterator</a> &gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * From, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a35975cf965c120e55130f30dd377418d">DbgRecord::self_iterator</a> &gt; FromHere, bool InsertAtHead</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a2c89a7c3adbeaf3cc5d02a41401801fb">llvm::Instruction::cloneDebugInfoFrom</a>.</p>

</div>
</div>

### Instruction::eraseFromParent {#a4c464ef563b721bcb04c8a998c30cabd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> undefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#aa8d611ee05eb26761a65e560e1481464">llvm::Function::BasicBlock::eraseFromParent</a>.</p>

</div>
</div>

### Instruction::insertAfter {#a9ff8c2039984eaa49dcaabc27d62ab89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#af09e4096de244d2fb345891328714a63">llvm::Instruction::insertAfter</a>.</p>

</div>
</div>

### Instruction::insertAfter {#ab98b1b6868b494dafb8501b53ce9b672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#af09e4096de244d2fb345891328714a63">llvm::Instruction::insertAfter</a>.</p>

</div>
</div>

### Instruction::insertBefore {#a193396bde318d1df3007eeb0a9afb296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> InsertPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>.</p>

</div>
</div>

### Instruction::insertBefore {#a3e35e2d0faac57d69f8ff3dab5b627fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> InsertPos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a482498a1c760122fd33c7fc8190dd277">llvm::Instruction::insertBefore</a>.</p>

</div>
</div>

### Instruction::insertInto {#ada9d53212698a02af2ec8cc05ae3f5d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> It</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### Instruction::moveBeforeImpl {#a728e79057a50862080bcc96dfce14f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> I, bool Preserve</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### Instruction::removeFromParent {#a3be34ea0f6bb2f1c928e200c4a8fa5ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend void undefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#a8c3fa281c85f015ea3ba20c7efc41714">llvm::Function::BasicBlock::removeFromParent</a>.</p>

</div>
</div>

### llvm::ilist\_node\_with\_parent&lt; llvm::Instruction, llvm::BasicBlock, ilist\_iterator\_bits&lt; true &gt;, ilist\_parent&lt; BasicBlock &gt; &gt; {#a3aeb66cb0986bfcb3c26e2b563194a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/ilist-node-with-parent">llvm::ilist_node_with_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-iterator-bits">ilist_iterator_bits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### llvm::SymbolTableListTraits&lt; llvm::Instruction, ilist\_iterator\_bits&lt; true &gt;, ilist\_parent&lt; BasicBlock &gt; &gt; {#ae7aad53c2632b8eba7b192fdd35ff068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">llvm::SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-iterator-bits">ilist_iterator_bits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; BasicBlock &gt; {#a11c7b04e5390fe7e163bf1ad039c757a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### BasicBlock() {#a092f0c59f208feb3688bcdf7795e228a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BasicBlock::BasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### BasicBlock() {#a27d81089e8a1627663ea9ae51707ff10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::BasicBlock (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Parent=nullptr, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBefore=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor.</p>


<p>If the function parameter is specified, the basic block is automatically inserted at either the end of the function (if InsertBefore is null), or before the specified basic block.</p>


<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~BasicBlock() {#a98a03933e831cb54c02b5068ebc30478}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::~BasicBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#ab1818247419c0b8a88bf6de2f8cd4758}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock &amp; llvm::BasicBlock::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp;)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### back() {#a2d071e661a02790177ba05f62c7c27d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; llvm::sandboxir::BasicBlock::back ()</td>
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



<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#aa08597bdb94f7c8409da1016e4d3900e">llvm::Function::back</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a43b79a254fba6ce00adf5b963382a0a4">llvm::Function::back</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#afaa8c01c6784e2dea310daf0a2b55fc1">llvm::AAResults::canBasicBlockModify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1b8715812b9f4dd2bd46163dd1b51128">llvm::FastISel::fastEmitBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42108fe3c2695cb429e6fe312908fa0d">llvm::SimplifyInstructionsInBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>.</p>

</div>
</div>

### back() {#a6c8359947a7a39375d8f959e4e5bdd8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; llvm::BasicBlock::back ()</td>
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



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### begin() {#a0ed5f3ab3c2e4196ee0cffffa080c062}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::BasicBlock::begin ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> iterator methods.</p>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#aa02431ef258154c74a391cc3c5fd7f8d">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::addIncomingPHIValuesForInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3fd09aad409fbbe332f6e29711d7698">llvm::calculateWasmEHInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#a7e36a63781989accf846f2e78f510d33">llvm::Interpreter::callFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a4fc6667c0f14f4e871d21234a6726246">canLoopBeDeleted</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#aab2eda4003703fcc548e36043debfafa">canSplitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a36f7b9a37f452349ad02d4d7f7d33972">anonymous{LoopDistribute.cpp}::InstPartitionContainer::cloneLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a21408b47716ef75ac95ded9097918f0a">llvm::FunctionComparator::cmpBasicBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#ae3af188e096e8a1152a33285a1c83c33">llvm::IRSimilarity::IRInstructionMapper::convertToUnsignedVec</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#ad5fb89357898044869d600aef33cd1ba">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::createDynamicAllocasInitStorage</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a6280f6984dd0e0455b73f22b3a5800c2">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::CreateEmptyPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#a8c9ae0be5e6bcad90cdf141962a117f3">createRetBitCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#abdf3ba57973320bd702d3b12b0b8fa8c">createRetPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aa12c0d3acb3f625ee09d2919907d4067">llvm::VPlan::createVPIRBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/postdominatortree/#ac74ec035b8eeaeb39cfea312fa876c75">llvm::PostDominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cd89ca702a817aac3a4521dd2462a2e">llvm::DuplicateInstructionsInSplitBetween</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa5133cfd6ce1419c7162cd0d7ba39ea9">EliminateDuplicatePHINodesNaiveImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a5bb62631ba6a4be0ae02f7365ee4a7d7">ensureValueAvailableInSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b303a16e5a77e48c8e724c52a3abbff">llvm::findAvailablePtrLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/dependencyanalysis-cpp/#aab3179ea6d16c5998772f644a2a205ac">findDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#af714eb55aced0ac27294c881d8be6ecb">findDuplicateOutputBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a19ce83f3f1fef433e2ba91a0b2a196a0">llvm::CodeExtractor::findOrCreateBlockForHoisting</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a58a5535f6186eecaf32ad97b8461eff4">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::FindPredecessorBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7e8be1d1ae7e526ea156b60c51c10e5">llvm::FoldSingleEntryPHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a8031442528bff99473596a0de4aa0422">llvm::CanonicalLoopInfo::getBodyIP</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a5751a2dd7306ff9a59eae6c1de8925">llvm::GetIfCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ac915a6d5d0d80a751be9852fbb74fa1e">llvm::sandboxir::getInsertPointAfterInstrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#af8ebafc2930bf25dfa6887c4b5bc2c33">getStrlenWithNull</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a94b383e649f60242503ff47c799fd22e">HandleByValArgumentInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab4d6b37c7f97bad2b1f441dc3fd43e0">llvm::hoistAllInstructionsInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a05dd87a2da7ddff8ce97716e3b479b2e">InsertSafepointPoll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a071886a7b42adae6a171e653e04bd216">insertTrivialPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c25087320a60ad7dc8494cb475e191b">llvm::instrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a5a7fe53bda3cbce584280a177a18d5ab">isBlockValidForExtraction</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ad3a4770e725305d3529cba8c6562c85a">llvm::CodeExtractor::isEligible</a>, <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/instrlowerer/#aa4a213aa8265b5907de86f84b12b5f8a">anonymous{InstrProfiling.cpp}::InstrLowerer::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a64307c8cbf811329320f43f90c434c08">moveBBContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/insertphistrategy/#a55f9b306ebb441abea69179650c2a4ad">llvm::InsertPHIStrategy::mutate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50754c809dc6a1aa65e3ab52f63f3467">optimizeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3c38fd13d9fa38356cca5ecdf7cfba23">optimizeSQRT</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a7a59feca56f2ecfe5c74d6c04b0c45c7">ProcessBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopidiomrecognize-cpp-/loopidiomrecognize/#acb7fb9d90a0af01462f9b0ce7b3e6414">anonymous{LoopIdiomRecognize.cpp}::LoopIdiomRecognize::processLoopMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#ab9222048f2d7f5912d8aedb736b56654">promoteMemoryToRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a1f69c303174793beec42b1ebaf13cfb6">reconnectPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9a1db01205f9a51a14b99e53e3068da1">rewritePHINodesForExitAndUnswitchedBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aa5bbbb258757741d38a876e5e203aa63">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reg2mem-cpp/#a984df453a762468ca683f6e83cf50e17">runPass</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroa/#a8317779540f30fe6a5dda2359f023675">anonymous{SROA.cpp}::SROA::runSROA</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a826d7a5a20d56ef31ee4111073700c93">scanInlinedCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42108fe3c2695cb429e6fe312908fa0d">llvm::SimplifyInstructionsInBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/simplifycfgopt/#a0cadca6f494db1ccdccb2256e49cb7fe">anonymous{SimplifyCFG.cpp}::SimplifyCFGOpt::simplifyOnce</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="#af29f89e91dfd0ae90950f0b1bf49798d">splice</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpblock/#afd6e09a5b9048b42dd46cc648d2b86c4">anonymous{MergeICmps.cpp}::BCECmpBlock::split</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a428f7b53e32934ae46a9aa35d3028d87">tryToMergeLandingPad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a4fd3bc9dead8a151c4cdf8c60d497931">UpdatePHINodes</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aae28ae8847a062e9113dbbc6a1db6861">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>, <a href="/web-llvm/docs/api/classes/llvm/interpreter/#ae9010576cc8633859d712499ff9d895f">llvm::Interpreter::visitIntrinsicInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### begin() {#aa9fdcfbadaf887aed46b04d2cae72865}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator llvm::sandboxir::BasicBlock::begin ()</td>
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



<p>Definition at line 469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### canSplitPredecessors() {#acf79d516b188e20e18034e5bbfcf6c69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlock::canSplitPredecessors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 567 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#aab2eda4003703fcc548e36043debfafa">canSplitCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a425e6fe374356efd05a49cab7e020166">canSplitPredecessors</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>.</p>

</div>
</div>

### convertFromNewDbgValues() {#a5753230c9e297fed32356ebf071074f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::convertFromNewDbgValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert variable location debugging information stored in DbgMarkers and DbgRecords into the dbg.value intrinsic representation.</p>


<p>Sets IsNewDbgInfoFormat = false.</p>


<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### convertToNewDbgValues() {#a3ead08d4d049585ee09421bcebd2ae25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::convertToNewDbgValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert variable location debugging information stored in dbg.value intrinsics into DbgMarkers / DbgRecords.</p>


<p>Deletes all dbg.values in the process and sets IsNewDbgInfoFormat = true. Only takes effect if the UseNewDbgInfoFormat LLVM command line option is given.</p>


<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### createMarker() {#a27413d863d6f6e778b34b1369b10ecf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker * BasicBlock::createMarker (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attach a <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> to the given instruction.</p>


<p>Enables the storage of any debug-info at this position in the program.</p>


<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>.</p>

</div>
</div>

### createMarker() {#a0269c36140cc599f3a97609c091f514d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker * BasicBlock::createMarker (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> It)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a206e2134ddd2312c3488d0632d98f554">llvm::enumerate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### deleteTrailingDbgRecords() {#a11abbc5a7c92e8a599756a5230761392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::deleteTrailingDbgRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete any trailing DbgRecords at the end of this block, see <a href="#a15ee901003da006e9da907c2bf70b9ec">setTrailingDbgRecords</a>.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### dropAllReferences() {#ab7844ce6d5301816e9a7bc21d7f08ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::dropAllReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Cause all subinstructions to "let go" of all the references that said subinstructions are maintaining.</p>


<p>This allows one to 'delete' a whole class at a time, even though there may be circular references... first all references are dropped, and all use counts go to zero. Then everything is delete'd for real. Note that no operations are valid on an object that has "dropped all references", except operator delete.</p>


<p>Declaration at line 584 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 476 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### dumpDbgValues() {#a6677f47b746b45e2b5018ac514b2f25a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::dumpDbgValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### empty() {#a266367eb01c634406b32f816d2d9c6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BasicBlock::empty ()</td>
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



<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a75514cc4632af88b58a31912c8bd9ecc">anonymous{InlineCost.cpp}::CallAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#a4683663d1041570f374ad7ac4ea119eb">anonymous{HotColdSplitting.cpp}::blockEndsInUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#ac915a6d5d0d80a751be9852fbb74fa1e">llvm::sandboxir::getInsertPointAfterInstrs</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>.</p>

</div>
</div>

### end() {#a0b4e7bee9b8575cc7db73329f1a561bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::BasicBlock::end ()</td>
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



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#a94cd9c4d5114d65e1cd802c23c080326">llvm::MemorySSAUpdater::changeToUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a21408b47716ef75ac95ded9097918f0a">llvm::FunctionComparator::cmpBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/#ae3af188e096e8a1152a33285a1c83c33">llvm::IRSimilarity::IRInstructionMapper::convertToUnsignedVec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60cf4cd57355563164d053dd470ac00f">llvm::convertUsersOfConstantsToInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#acae95016bcdeb105bcbcaaa872893f5f">createTargetLoopWorkshareCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a19ce83f3f1fef433e2ba91a0b2a196a0">llvm::CodeExtractor::findOrCreateBlockForHoisting</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac60599e6b45dd035fa354b12afdd195">getConvergenceEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a7bc99de2f3874d014ce70d70c12f3b12">getInsertionRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a7f5d9eaa8cd08c1bbf22faaa2dea67f4">getInsertPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotekernelarguments-cpp/#a7f5d9eaa8cd08c1bbf22faaa2dea67f4">getInsertPt</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#ac72ebc430ef7dcf1791c66080ddedd9d">llvm::CanonicalLoopInfo::getPreheaderIP</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab4d6b37c7f97bad2b1f441dc3fd43e0">llvm::hoistAllInstructionsInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9019e662ee1c0c04e06e9871650268c8">llvm::DIBuilder::insertDeclare</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a8b52fc13d6793d152a3d9dc210f5156e">llvm::sandboxir::Instruction::insertInto</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertposition/#ab20372cf3a96dbf003b55e9f75cd3831">llvm::sandboxir::InsertPosition::InsertPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a05dd87a2da7ddff8ce97716e3b479b2e">InsertSafepointPoll</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c25087320a60ad7dc8494cb475e191b">llvm::instrs</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a5a7fe53bda3cbce584280a177a18d5ab">isBlockValidForExtraction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2fadbd4626ccfbf3d2cabd27003d597">llvm::isInTailCallPosition</a>, <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/instrlowerer/#aa4a213aa8265b5907de86f84b12b5f8a">anonymous{InstrProfiling.cpp}::InstrLowerer::lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a3afc8c0c69b0c55edce3be13d5b7cc32">moveBBContents</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8b569b7040c15c2e2233b3064caa8f4f">llvm::RandomIRBuilder::newSource</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50754c809dc6a1aa65e3ab52f63f3467">optimizeBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7f49d3dc767d0f0789ffd9e332e7a49">llvm::PrepareToSplitEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a7a59feca56f2ecfe5c74d6c04b0c45c7">ProcessBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopidiomrecognize-cpp-/loopidiomrecognize/#acb7fb9d90a0af01462f9b0ce7b3e6414">anonymous{LoopIdiomRecognize.cpp}::LoopIdiomRecognize::processLoopMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#ab9222048f2d7f5912d8aedb736b56654">promoteMemoryToRegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a1f69c303174793beec42b1ebaf13cfb6">reconnectPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aa5bbbb258757741d38a876e5e203aa63">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/sroa/#a8317779540f30fe6a5dda2359f023675">anonymous{SROA.cpp}::SROA::runSROA</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aaff1d64460846955e8b33534649c0ebc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ad016e01a6a7d6f527043e7ded55dd65b">shouldInstrumentBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42108fe3c2695cb429e6fe312908fa0d">llvm::SimplifyInstructionsInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a24a3e4aad4cb2fdde7ce294a531cd52a">sinkCmpExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-scalarizer-cpp-/#ab918ecc49624aa2ae55ec900d4919ee7">anonymous{Scalarizer.cpp}::skipPastPhiNodesAndDbg</a>, <a href="#af29f89e91dfd0ae90950f0b1bf49798d">splice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a78e14f66d8a8405c6882b5ff6a3b7617">llvm::spliceBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a>, <a href="/web-llvm/docs/api/classes/anonymous-hotcoldsplitting-cpp-/outliningregion/#a631ea87e33f8e50c1b90ae334ceea4c8">anonymous{HotColdSplitting.cpp}::OutliningRegion::takeSingleEntrySubRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#a06b5d6856fd9067830ab0477c0b13f31">anonymous{UnifyFunctionExitNodes.cpp}::unifyReturnBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a4d1d15c0a00a9b9391977c8f482e0428">updateScopeLine</a>, <a href="/web-llvm/docs/api/classes/llvm/instvisitor/#aae28ae8847a062e9113dbbc6a1db6861">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### end() {#ad15634f3c006d9c1ee9a79ceeb3accd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::BasicBlock::end ()</td>
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



<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### erase() {#a018d5142c1a4469d9296a26a59fe2783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator BasicBlock::erase (<a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromIt, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ToIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erases a range of instructions from <span class="doxyComputerOutput">FromIt</span> to (not including) <span class="doxyComputerOutput">ToIt</span>.</p>


<p>\Returns <span class="doxyComputerOutput">ToIt</span>.</p>


<p>Declaration at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#ae20e35b50e6cf67987421c996cf14a8c">llvm::MemorySSA::removeFromLists</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#acd0427b84adce00e5b26f993c7aa48c8">llvm::MemorySSA::removeFromLookups</a>.</p>

</div>
</div>

### eraseFromParent() {#a8dd327a937563afdb08250abc43820b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iplist&lt; BasicBlock &gt;::iterator BasicBlock::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink 'this' from the containing function and delete it.</p>

<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 279 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a57d54880afa1fb74833cc7c43ad33377">analyzeAndPruneOutputBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater/#adcca375fa8086f6844e863abbf58f83b">llvm::DomTreeUpdater::deleteBB</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>.</p>

</div>
</div>

### flushTerminatorDbgRecords() {#a7a7dc3732891611f559b06951a6ee85a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::flushTerminatorDbgRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Eject any debug-info trailing at the end of a block.</p>


<p>DbgRecords can transiently be located "off the end" of a block if the blocks terminator is temporarily removed. Once a terminator is re-inserted this method will move such DbgRecords back to the right place (ahead of the terminator).</p>


<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>.</p>

</div>
</div>

### front() {#a63cfb2a0dae69153fd961eb335949caa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; llvm::sandboxir::BasicBlock::front ()</td>
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



<p>Definition at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a23260d8f091384125b149c89aaa00a8c">calculateStateNumbersForInvokes</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#afaa8c01c6784e2dea310daf0a2b55fc1">llvm::AAResults::canBasicBlockModify</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7a6386c071e1087512cdc8a4071a02b5">llvm::CloneAndPruneFunctionInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1b8715812b9f4dd2bd46163dd1b51128">llvm::FastISel::fastEmitBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a2295fc872f9e737d27abeffbc9016fbe">findArgParts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#abf30a45c2a2e88a614f4ff435aafceaf">llvm::Function::front</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a3ec0b920bf30d0e15bace383192691da">llvm::Function::front</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a1bcb8bb92d8385a81a07659c6e1ec6fc">llvm::MustBeExecutedContextExplorer::getMustBeExecutedNextInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4e25c5f8a8a770362e0ab9dcaa167dab">llvm::InstCombinerImpl::handlePotentiallyDeadBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a3aaf79ae3bce520f7cb4d573292922e9">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a0cb597b1f0cffe907fa834e9a95fe719">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a15231e29111a0d8c49ffbe239f7047b6">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::insertBaseTaggedPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aeab32388541e65c42e97d2ca8c7867d1">insertCallAtFunctionEntryPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a64f8e14ffe5fb52d552fcb9058286ad3">llvm::coro::isSuspendBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1f70470f7a7722fd55c58c81358107f2">mergeCleanupPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4972d73b274f1c9bb08ff314cba26522">llvm::moveInstructionsToTheEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#a63ce604ca599913727c7c8c7fbe4ca13">runSanitizeRealtimeBlocking</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>.</p>

</div>
</div>

### front() {#a49a6d4a5d9b4dcd337096732c3a97fba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; llvm::BasicBlock::front ()</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getContext() {#aa286a0f7f5d38488d593bb7ef0ba183e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; BasicBlock::getContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the context in which this basic block lives.</p>

<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a55c9054d63d1c6a39e9c09ba13a482fa">llvm::addStringMetadataToLoop</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfpreserveditype-cpp-/#a72adf7d117af6ebe1a3aee68b6e3e782">anonymous{BPFPreserveDIType.cpp}::BPFPreserveDITypeImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aae3714d6fe11a1e8c559880caf67fbc7">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a6bfe058b12abe3443b07d4f4d55d863f">createStringMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7aa8025f73f4e06135e6ba7083ad7aab">createUnreachableSwitchDefault</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#af30ff2458bb283e423c1fc242a468579">findOrCreatePHIBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#ab92aa8e12ea15943c53deddbdea43eb7">llvm::sandboxir::BlockAddress::get</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aeeca41a71460985e42575296d3546044">llvm::DbgRecord::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aebc682702f3ea424f06c4f56fe6c96e6">llvm::DbgRecord::getContext</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#adee485b8d8a010d18877f5f41286b079">llvm::BPFCoreSharedInfo::insertPassThrough</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/blockaddress/#a095a6dbd20e2611d899aa9f03380a573">llvm::sandboxir::BlockAddress::lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a745200db7bc2a7a3c17fa379fb1b56c3">llvm::parseWidenableBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a>, <a href="/web-llvm/docs/api/classes/anonymous-inductiverangecheckelimination-cpp-/inductiverangecheckelimination/#af56db9cf79e7501bf38278f849774369">anonymous{InductiveRangeCheckElimination.cpp}::InductiveRangeCheckElimination::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#ae27590daf21d575c9bb75c966fe256f2">llvm::Loop::setLoopAlreadyUnrolled</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#aa0930d54ec09b50bbfa09ec317e0df42">llvm::Loop::setLoopMustProgress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a81c8a5368d02d0b52654a3efe83dec38">llvm::LoopVersioning::versionLoop</a> and <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#a4a4171890acb275f5a66288e91a8d5ca">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitSwitchInst</a>.</p>

</div>
</div>

### getDataLayout() {#a858cab21fd29000697171b2f5b4bde31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; BasicBlock::getDataLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the data layout of the module this basic block belongs to.</p>


<p>Requires the basic block to have a parent module.</p>


<p>Declaration at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 296 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a4c35e6c65a8ef063f0acbdd56264cad5">computeAllocaDefaultAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a057e15a122129dc790055a5f344ddf2f">computeLoadStoreDefaultAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b303a16e5a77e48c8e724c52a3abbff">llvm::findAvailablePtrLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanrecipes-cpp/#ad5b9a4518a164330f914a84969ca7cce">getGEPIndexTy</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#ab46fb372d99dc0562d09cfdcd041d5ab">llvm::MemoryDependenceResults::getNonLocalPointerDependency</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a710878a88d68a9169313249bfd52862a">llvm::JumpThreadingPass::maybethreadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac06e19670a4cb86b0c885cf67bdb1bc4">llvm::JumpThreadingPass::processImpliedCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#acfadccba72143e2f818f0a355698ff10">processNonStringArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac2a5d254b5ec303b4d47ac3f0f578f09">llvm::simplifyCFG</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a42108fe3c2695cb429e6fe312908fa0d">llvm::SimplifyInstructionsInBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a> and <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a81c8a5368d02d0b52654a3efe83dec38">llvm::LoopVersioning::versionLoop</a>.</p>

</div>
</div>

### getFirstInsertionPt() {#a161fd4e9fa5367f64c2a4c9e921c3ad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::const_iterator BasicBlock::getFirstInsertionPt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator to the first instruction in this block that is suitable for inserting a non-PHI instruction.</p>


<p>In particular, it skips all PHIs and LandingPad instructions.</p>


<p>Declaration at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 437 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e6c0c958b2de133d4b9d0e2c62f1e4">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59e94595f29a0adde822a318f82dac61">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a60cf4cd57355563164d053dd470ac00f">llvm::convertUsersOfConstantsToInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a50ee598578572bbfadfb9279f650cdd7">llvm::RandomIRBuilder::createStackMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ac8803aa267830622708ede7b732c7ae2">DbgInserterHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a3ef88a20b7b51243e963ed25e0e0c30e">foldDependentIVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a73b18943dffc9db671d3217c90b15a4f">foldGuardedFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="#afcd563bcff8320c4830cc0fc92b64f32">getFirstInsertionPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a7bc99de2f3874d014ce70d70c12f3b12">getInsertionRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a7f5d9eaa8cd08c1bbf22faaa2dea67f4">getInsertPt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotekernelarguments-cpp/#a7f5d9eaa8cd08c1bbf22faaa2dea67f4">getInsertPt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a58bcd428c0ca38b723b8ef938868ec4a">llvm::coro::getSpillInsertionPt</a>, <a href="/web-llvm/docs/api/structs/llvm/objcarc/bottomupptrstate/#a92756d26ffe5c46811ee48f629857ba2">llvm::objcarc::BottomUpPtrState::HandlePotentialUse</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs/#a8fdb3ab3875b4306157d47d84e972405">llvm::objcarc::BundledRetainClaimRVs::insertAfterInvokes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fcd2292dd9e51480a2f43d41acfe2">llvm::invertCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#ae965a8b6001eaf1612d36d070594c706">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/shuffleblockstrategy/#a3bad39b7c7fd81aa15068f082eb6f0a6">llvm::ShuffleBlockStrategy::mutate</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8b569b7040c15c2e2233b3064caa8f4f">llvm::RandomIRBuilder::newSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a07714583aa2bea29cd0284d5340dd844">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::replaceUseWithTableLookup</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac8e72cc39ee52ef30175aa8278cd0dfc">setInsertionPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ad016e01a6a7d6f527043e7ded55dd65b">shouldInstrumentBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinephi-cpp/#a86ed982844e004af01652f203eda23c0">simplifyUsingControlFlow</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a24a3e4aad4cb2fdde7ce294a531cd52a">sinkCmpExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-scalarizer-cpp-/#ab918ecc49624aa2ae55ec900d4919ee7">anonymous{Scalarizer.cpp}::skipPastPhiNodesAndDbg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a0e01a9709ce029147b721bdfe476fbbe">anonymous{IndirectCallPromotion.cpp}::tryToSinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4b167ac2fde7b3d71172817650150a6">llvm::InstCombinerImpl::tryToSinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a9a06c7811f1ea67a51787ab0de806b5a">llvm::ObjectSizeOffsetEvaluator::visitPHINode</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>.</p>

</div>
</div>

### getFirstInsertionPt() {#afcd563bcff8320c4830cc0fc92b64f32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::BasicBlock::getFirstInsertionPt ()</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#a161fd4e9fa5367f64c2a4c9e921c3ad3">getFirstInsertionPt</a>.</p>

</div>
</div>

### getFirstMayFaultInst() {#af17df370366f173939c9b295734d3d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * BasicBlock::getFirstMayFaultInst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the first potential AsynchEH faulty instruction currently it checks for loads/stores (which may dereference a null pointer) and calls/invokes (which may propagate exceptions)</p>

<p>Declaration at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 358 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### getFirstMayFaultInst() {#a0ed23acd7f851897e62880b4decaed6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::BasicBlock::getFirstMayFaultInst ()</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getFirstNonPHI() {#a05695d7068e19f1799ed15ed7523a957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * BasicBlock::getFirstNonPHI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> instruction.</p>


<p>When adding instructions to the beginning of the basic block, they should be added before the returned value, not before the first instruction, which might be PHI. Returns 0 is there's no non-PHI instruction.</p>


<p>Deprecated in favour of getFirstNonPHIIt, which returns an iterator that preserves some debugging information.</p>


<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 367 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="#a4e1c5961974e47ac42e9c34efa0792b3">LLVM_DEPRECATED</a>.</p>

</div>
</div>

### getFirstNonPHIIt() {#a362b5e6097732cbc0d2fb555a1f73400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::const_iterator BasicBlock::getFirstNonPHIIt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> instruction.</p>


<p>When adding instructions to the beginning of the basic block, they should be added before the returned value, not before the first instruction, which might be PHI. Returns <a href="#a0b4e7bee9b8575cc7db73329f1a561bd">end()</a> if there's no non-PHI instruction.</p>


<p>Avoid unwrapping the iterator to an Instruction* before inserting here, as important debug-info is preserved in the iterator.</p>


<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a84a89ee9844b6cffc3660100168d7bee">llvm::MachineFunction::addLandingPad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afcc6ddcd882a86a3d6028e2530b4d4cc">llvm::calculateClrEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bf41f2408094f54097744991c82336a">llvm::calculateCXXStateForAsynchEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b49442c1c01ddc388c51d7599c0f876">llvm::calculateSEHStateForAsynchEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a23260d8f091384125b149c89aaa00a8c">calculateStateNumbersForInvokes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3fd09aad409fbbe332f6e29711d7698">llvm::calculateWasmEHInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a425e6fe374356efd05a49cab7e020166">canSplitPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3a97fed79c86bf242b0f090e1cb2e6">llvm::colorEHFunclets</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a6be998a03774a37c14d7077897b53bc9">llvm::objcarc::createCallInstWithColors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/vpirinstruction/#a82c7920e0c53dc071f1ac55f91a2895f">llvm::VPIRInstruction::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a19ce83f3f1fef433e2ba91a0b2a196a0">llvm::CodeExtractor::findOrCreateBlockForHoisting</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a48e98416c61da7bdde42d88ea460723c">findPHIForConditionForwarding</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a6289e8af46c9783382b346baa020087c">findUnwindDestinations</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#ac48ad402cb64f4c6bd6bb7158013a7be">findWasmUnwindDestinations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac60599e6b45dd035fa354b12afdd195">getConvergenceEntry</a>, <a href="#a24f7c650ab0603ed231ff2c0d1aac823">getFirstNonPHIIt</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/verifier-cpp/#a11e914a38efa916156b4f2c1e57de063">getSuccPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4e19285f051b80099ed8b36c5c94eaf2">getUnwindDestTokenHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a3a3a3183a327e1186dbe900032390ec6">hoist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4dfea19770364b880a77c3f0c1c0f67c">llvm::insertDebugValuesForPHIs</a>, <a href="#ac9c170fde1808bbd4436a0dbd6d5e755">isEHPad</a>, <a href="#a4e1c5961974e47ac42e9c34efa0792b3">LLVM_DEPRECATED</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a79f47e97963f500c113eb9bfee2e5b47">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#aabc37fb487455e5268d389333bc5c890">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0d8e70094baa4fcc5eb68b59de54dc92">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::mergeRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a5231b25125e1131002b5192820d3c969">populateEHOperandBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a55412d2c237115c95f20e12ba0d95922">relocationViaAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-objcarccontract-cpp-/objcarccontract/#a6b6cfbee1f1d7c9f17eb52722c89564d">anonymous{ObjCARCContract.cpp}::ObjCARCContract::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32aaa22eb69c944393cd5a1c79fa0d35">llvm::SplitBlockAndInsertSimpleForLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>.</p>

</div>
</div>

### getFirstNonPHIIt() {#a24f7c650ab0603ed231ff2c0d1aac823}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstListType::iterator llvm::BasicBlock::getFirstNonPHIIt ()</td>
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



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#a362b5e6097732cbc0d2fb555a1f73400">getFirstNonPHIIt</a>.</p>

</div>
</div>

### getFirstNonPHIOrDbg() {#a50909227135ef69932bff39b8ea3f572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::const_iterator BasicBlock::getFirstNonPHIOrDbg (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> or a debug intrinsic, or any pseudo operation if <span class="doxyComputerOutput">SkipPseudoOp</span> is true.</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a84b80673b9748e75da40fa84cca3a630">llvm::OutlinableRegion::findCorrespondingBlockIn</a>, <a href="#a854ba9598d9eb6c82c8654d032ee6451">getFirstNonPHIOrDbg</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a95851c48d68c2406ef12a7cca9c65f76">initializeUniqueCases</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a68d6e6643cf0af54add83ed1ab981085">isPredicatedOnPHI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9cfb65e6e11fa2b005afc1680a7756df">llvm::moveInstructionsToTheBeginning</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>.</p>

</div>
</div>

### getFirstNonPHIOrDbg() {#a854ba9598d9eb6c82c8654d032ee6451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstListType::iterator llvm::BasicBlock::getFirstNonPHIOrDbg (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#a50909227135ef69932bff39b8ea3f572">getFirstNonPHIOrDbg</a>.</p>

</div>
</div>

### getFirstNonPHIOrDbgOrAlloca() {#aab4db88f47575918879912e8ca511756}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::const_iterator BasicBlock::getFirstNonPHIOrDbgOrAlloca ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns an iterator to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, a debug intrinsic, a static alloca or any pseudo operation.</p>

<p>Declaration at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af59c587eddc75748a1e201369cd3dbac">llvm::InstCombinerImpl::freezeOtherUses</a>, <a href="#ab43659d50c2e4ec6521afab18783f1ec">getFirstNonPHIOrDbgOrAlloca</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/guardwidening-cpp/#af0470a389063c0b4665f29617596051a">getFreezeInsertPt</a>.</p>

</div>
</div>

### getFirstNonPHIOrDbgOrAlloca() {#ab43659d50c2e4ec6521afab18783f1ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::BasicBlock::getFirstNonPHIOrDbgOrAlloca ()</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#aab4db88f47575918879912e8ca511756">getFirstNonPHIOrDbgOrAlloca</a>.</p>

</div>
</div>

### getFirstNonPHIOrDbgOrLifetime() {#ac24cd8d28904d8a4eac2dc3d7545355e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::const_iterator BasicBlock::getFirstNonPHIOrDbgOrLifetime (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the first instruction in this block that is not a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a>, a debug intrinsic, or a lifetime intrinsic, or any pseudo operation if <span class="doxyComputerOutput">SkipPseudoOp</span> is true.</p>

<p>Declaration at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="#a1ef52a2f1462579cc3c78aa20761288b">getFirstNonPHIOrDbgOrLifetime</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ad016e01a6a7d6f527043e7ded55dd65b">shouldInstrumentBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>.</p>

</div>
</div>

### getFirstNonPHIOrDbgOrLifetime() {#a1ef52a2f1462579cc3c78aa20761288b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstListType::iterator llvm::BasicBlock::getFirstNonPHIOrDbgOrLifetime (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#ac24cd8d28904d8a4eac2dc3d7545355e">getFirstNonPHIOrDbgOrLifetime</a>.</p>

</div>
</div>

### getIrrLoopHeaderWeight() {#a5e873ca436db6d4200ac469fcc253374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; BasicBlock::getIrrLoopHeaderWeight ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 710 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 707 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### getLandingPadInst() {#a1553a166adb52e29e3a240dd37627ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LandingPadInst * BasicBlock::getLandingPadInst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the landingpad instruction associated with the landing pad.</p>

<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>.</p>

</div>
</div>

### getLandingPadInst() {#afa7e147d7b2bfe8f75048f51b99ef318}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LandingPadInst * llvm::BasicBlock::getLandingPadInst ()</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getMarker() {#a952da10b9a7ffd3b3bdeefae13c525a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker * BasicBlock::getMarker (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> It)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> for the position given by <span class="doxyComputerOutput">It</span>, so that DbgRecords can be inserted there.</p>


<p>This will either be nullptr if not present, a <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>, or TrailingDbgRecords if It is <a href="#a0b4e7bee9b8575cc7db73329f1a561bd">end()</a>.</p>


<p>Declaration at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>.</p>

</div>
</div>

### getModule() {#afc70e919c88c86159cc94cea29b6c210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * BasicBlock::getModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the module owning the function this basic block belongs to, or nullptr if the function does not have a module.</p>


<p>Note: this is undefined behavior if the block does not have a parent.</p>


<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49b93792c9c07b4d1c53fb9c3d903e14">callAppendArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#ac500e82c324a3dd8e9c5a87c256f2883">callAppendStringN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a246a48082d0e8d3e7ec999f91b584590">callBufferedPrintfArgPush</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49077c24022f5ec4c84d809abf92e91e">callBufferedPrintfStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a9349e05033852c48c123a000e134a453">callPrintfBegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#ad908d5abcd036d7ff7e277fda6821cf0">CanProveNotTakenFirstIteration</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1b8715812b9f4dd2bd46163dd1b51128">llvm::FastISel::fastEmitBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#af54e01fb7fd5db7ff76495fcabc90ea1">anonymous{AddressSanitizer.cpp}::AddressSanitizer::genAMDGPUReportBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a8da33528c75f7337a0a4b87118c63340">llvm::LazyValueInfo::getConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a4185eb721dbdc35f95d06445db6ad5e8">llvm::LazyValueInfo::getConstantOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a250c3d5c704c7c596ec914c18c40fbc2">llvm::LazyValueInfo::getConstantRange</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a6682d705e47b188e795f7f41a0cc6896">llvm::LazyValueInfo::getConstantRangeOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a09c33f7646ac5d4405d559737be252af">llvm::RISCVTargetLowering::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a30223a7e41ce3064f9d85b3fe3ee7005">llvm::LazyValueInfo::getPredicateOnEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="#a4232efd6f56912332e8631bd828eca21">print</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvisellowering-cpp/#aa919dd3a390d60e7b3971efe82c0b760">useTpOffset</a>.</p>

</div>
</div>

### getModule() {#a48866af4e264e8d94bc56058eb74608b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::BasicBlock::getModule ()</td>
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



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getNextMarker() {#aefcf861b48fcdb3316d6f452519009c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker * BasicBlock::getNextMarker (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> for the position that comes after <span class="doxyComputerOutput">I</span>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#a952da10b9a7ffd3b3bdeefae13c525a3">BasicBlock::getMarker</a>, this can be nullptr, a <a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a>, or TrailingDbgRecords <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a> there is no next instruction.</p></dd>
</dl>


<p>Declaration at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1096 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### getNumber() {#a0bf3a7e9bff209ef9f8d2eb194196848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BasicBlock::getNumber ()</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a1b4bf7c97cdc8159fd73d48063f0b250">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5a05fbafdbe696de6c83937542acc38e">emitBasicBlockLoopComments</a>, <a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo/#a14a2bf30885cc5b91b86a564759980bb">llvm::FunctionLoweringInfo::getMBB</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-2bc92823035f996577648daa23ed11c7/#a889ec52fffa7324d607afad54a2875b8">llvm::GraphTraits&lt; BasicBlock * &gt;::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-9656629af6fba4d53ea66c8963d0c72b/#a772a62399552424aeda1dcd8668620cc">llvm::GraphTraits&lt; const BasicBlock * &gt;::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-973e7b08b5b5818a1d5c6c69da1fa05b/#a4720bb2b577c2e8e213fade1872faedb">llvm::GraphTraits&lt; Inverse&lt; BasicBlock * &gt; &gt;::getNumber</a>, <a href="/web-llvm/docs/api/structs/llvm/graphtraits-d27a12f208359493deb55564e5902b74/#af26f967072c172a7c621a496396c721e">llvm::GraphTraits&lt; Inverse&lt; const BasicBlock * &gt; &gt;::getNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9e656ca6880429c47f777ef0d06ac030">PrintParentLoopComment</a> and <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>.</p>

</div>
</div>

### getParent() {#a1b4bf7c97cdc8159fd73d48063f0b250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::sandboxir::BasicBlock::getParent ()</td>
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

<p>Return the enclosing method, or null if none.</p>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#a6e46200e5b228c903356e02904987051">addReplicateRegions</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a994ac02d488546e86aeb825e0ea88059">llvm::CodeMetrics::analyzeBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#aaaced3d57d8877d30048b69be2787b21">calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#adbe30a5e0e6f5dc00dac4c72dbffb905">canProveExitOnFirstIteration</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6f244e1d6d34701da1f29d3a762974fd">llvm::cloneLoopWithPreheader</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a08610118e213de1b759470f0eafb9b18">llvm::OpenMPIRBuilder::collapseLoops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3a97fed79c86bf242b0f090e1cb2e6">llvm::colorEHFunclets</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a52fb7e69634a02e492f7285741b43f84">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::combineShadows</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a0e0ddbf81c5fa1ee764ba3f4bd6ddbf5">CompareValueComplexity</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a4c35e6c65a8ef063f0acbdd56264cad5">computeAllocaDefaultAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/loopsafetyinfo/#a183e3a3a68925c5689cd2149c940f59e">llvm::LoopSafetyInfo::computeBlockColors</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a057e15a122129dc790055a5f344ddf2f">computeLoadStoreDefaultAlign</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a993771e7c58c60044cbc4c57f689406e">llvm::RandomIRBuilder::connectToSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1542efe32b9a597a7d72d3b205dab176">convertToRelLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a1548d6cc07c1c5595817e73713d58a23">copyMustTailReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#af49d9ef5881a26b9bbbcd2a1002857bb">createAllocaInstAtEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae0287686a5ffe03bc264972c862726ea">llvm::OpenMPIRBuilder::createCanonicalLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#a21a84e5cc221f28b26321adf56f0bb05">llvm::IRSimilarity::IRSimilarityCandidate::createCanonicalRelationFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a2f89404be2430701edb3e9827aaab276">CreateGCStatepointInvokeCommon</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a7497538730b6264d4783b4cbd71db816">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::createPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7aa8025f73f4e06135e6ba7083ad7aab">createUnreachableSwitchDefault</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ac8803aa267830622708ede7b732c7ae2">DbgInserterHelper</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae046f3782a1242c97fe9fe937793fa3f">anonymous{DeadStoreElimination.cpp}::DSEState::dominatingConditionImpliesValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a61f3d93434dc9f576826799df553ed1b">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::doMultiRegionFunctionOutlining</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#aa06ef927da6dbc2b989bb4df7d1f5c6a">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::doSingleRegionFunctionOutlining</a>, <a href="/web-llvm/docs/api/structs/anonymous-materializationutils-cpp-/rematgraph/#ad14f78f54885b535974264a556bcfa05">anonymous{MaterializationUtils.cpp}::RematGraph::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/classes/llvm/anonymous-lazyvalueinfo-cpp-/lazyvalueinfoannotatedwriter/#a2303f83370acdc01a15562df07e20fc8">llvm::anonymous{LazyValueInfo.cpp}::LazyValueInfoAnnotatedWriter::emitBasicBlockStartAnnot</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a8631130c37aa54ae6c9127abc5fe392a">llvm::AArch64TargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab439771b84f342c37a8823fb2f797642">llvm::ARMTargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a683761fbb11ed0969edf7eee08b08bf3">llvm::PPCTargetLowering::emitMaskedAtomicCmpXchgIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a0e0d3c023e19c20fbf01b40d36aced80">llvm::PPCTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a625caa931f0d8ef201041febbfe42cca">llvm::InnerLoopVectorizer::emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a30c4bcea7beb42c7eb075a578bc3bc3e">llvm::InnerLoopVectorizer::emitSCEVChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#aaa3dfbded3ebc8068ad825a039bfdfaf">llvm::HexagonTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a0dca3347facf58865b34df5e5df676f0">llvm::MustBeExecutedContextExplorer::findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a84b80673b9748e75da40fa84cca3a630">llvm::OutlinableRegion::findCorrespondingBlockIn</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#ab0cac3cc09d07bc44ffd388ff8be5e49">llvm::MustBeExecutedContextExplorer::findForwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#af30ff2458bb283e423c1fc242a468579">findOrCreatePHIBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad600d9077d7e1eadff1334ee14f7f25a">llvm::foldBranchToCommonDest</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a7134dae528abf2cf2ef1bd1d92f9ce39">foldLogOpOfMaskedICmps_NotAllZeros_BMask_Mixed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#a0344a21f3995913a734b93bbd0d0e841">llvm::BlockAddress::get</a>, <a href="/web-llvm/docs/api/classes/llvm/addrlabelmap/#acbb53aac904b80dad6df38f882e319f3">llvm::AddrLabelMap::getAddrLabelSymbolToEmit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86loweramxtype-cpp/#a660392f54efb6a70e2b59a840ccf1728">getAllocaPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a9cf59960e7146dd283b2f23753a00c3c">llvm::memtag::getAndroidSlotPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a5a8db261ae8a0e5359c65e8e8f8c1135">llvm::TargetLoweringBase::getDefaultSafeStackPointerLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference/#abe4e816c7ba92d54465becab471317c1">llvm::BlockCoverageInference::getDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa5c238ef927795521aeb232b467a6cd1">llvm::MemoryDependenceResults::getDependency</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#afd194fd0bfdd8b288bb7f1e9585a1679">getDominatees</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/randomirbuilder-cpp/#a93819e91559afbcefbe8c8d90f0499ed">getDominators</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#aa741eaf03ea033a9a1a3b669d0321983">llvm::IRSimilarity::IRSimilarityCandidate::getEndBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a1f83b92c78b2b41b842a95f4ff5910d0">llvm::memtag::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a0c770bec150810f68fb4a4eacceec263">llvm::DbgRecord::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#aa5e73fb863b8910b7841f583487fc077">llvm::DbgRecord::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#abfc4581d38f96e5833319a3d1ad24c1c">llvm::IRSimilarity::IRSimilarityCandidate::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/trace/#aa2599e2e71d0e672d28c9d8a93b1f308">llvm::Trace::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/valueenumerator/#ac26f6dabdd4fbb3288de35fce6b62422">llvm::ValueEnumerator::getGlobalBasicBlockID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a784589f886057bdb03273b8bb07deb2b">llvm::TargetLoweringBase::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a4cb54e7d62530f9e973ff35f6301de6a">llvm::X86TargetLowering::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a2b4746e455f9041187249483e7f5e5f5">llvm::Loop::getLocStr</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/memcmpexpansion/#a36cf9f1978b6c3bce437ad288b98e1dc">anonymous{ExpandMemCmp.cpp}::MemCmpExpansion::getMemCmpExpansion</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp/#a7b98dd2ff18a320795917ace7f8010db">getModuleFromDPI</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#aa7240503037f0c0499222a41a5f22d06">llvm::MemoryDependenceResults::getNonLocalCallDependency</a>, <a href="#a0bf3a7e9bff209ef9f8d2eb194196848">getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#afba1279eafd7cf7b6ef9681b6f28283f">llvm::sandboxir::Instruction::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#ad9b5eba01208d43c3c753251be70778a">llvm::memtag::getPC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b127c37d77da045cea07e787e2d1e48">llvm::TargetLoweringBase::getSafeStackPointerLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/irsimilarity/irsimilaritycandidate/#ae22d915fa9ab51e40345773c663ebdeb">llvm::IRSimilarity::IRSimilarityCandidate::getStartBB</a>, <a href="/web-llvm/docs/api/classes/llvm/gcprojectioninst/#a6cffcfabac72ca61185ea24c1208b937">llvm::GCProjectionInst::getStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a94b383e649f60242503ff47c799fd22e">HandleByValArgumentInit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4cbd6aad6f6b93f79dc435feab77550e">HandleInlinedLandingPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a045ddd9cf89c401caf98eb3acad6b1a7">insertBoundsCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a1a4145a18b32a1bc1030bf789e370963">InsertCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a05dd87a2da7ddff8ce97716e3b479b2e">InsertSafepointPoll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#ac2547f0adabfca4600d7c16947b20ed4">InsertTrap</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add2fcd2292dd9e51480a2f43d41acfe2">llvm::invertCondition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#af471b1ff6b59d2257a9e1e301d173015">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isAssumedDead</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a28ca3a54ea9ef7dd53412258dc067de3">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfunction/#a5749980418be3808e831c1189b77f829">anonymous{AttributorAttributes.cpp}::AAIsDeadFunction::isEdgeDead</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a0fdc6cad0c749330f186d0415048e2cd">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedByInitialThreadOnly</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a6d53d8df2e0ea40eee8a7349563a9df7">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedInAlignedRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a806ec23d6f44b02ad8cf3b1e61c05495">isExplicitVecOuterLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a4d3ad60400165f1708ea8572d996abc3">isFSqrtDivToFMulLegal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2fadbd4626ccfbf3d2cabd27003d597">llvm::isInTailCallPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0581d6d5dc280ba2a39087a557050a6a">isNotUsedOrFoldableInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4603b4fac07d9342d2ea27067c81057">llvm::isPresplitCoroSuspendExitEdge</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#gaa5642c34ff5104e4c8237fad31d2dca7">LLVMInsertBasicBlockInContext</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#ga685b3eca9432cb6b80cc96dd54d025a3">LLVMInsertExistingBasicBlockAfterInsertBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#a5272e28bf5a3ca5f021f055c88adc118">llvm::BlockAddress::lookup</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a7b4a95aa47d151f0db62f60bafa792d8">memoryIsNotModifiedBetween</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertfunctionstrategy/#a51a23cfe8db3e31fdc6eeb8547df0d33">llvm::InsertFunctionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertphistrategy/#a55f9b306ebb441abea69179650c2a4ad">llvm::InsertPHIStrategy::mutate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a679d0966b3083f647af785f24936d3d9">llvm::RandomIRBuilder::newSink</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8b569b7040c15c2e2233b3064caa8f4f">llvm::RandomIRBuilder::newSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a1e5a795e237da6e01636980c98b645ab">nullifySetjmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a4839bb9ff9510a0c0bda1e41cabe4714">placeSplitBlockCarefully</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#aae23f7e6fc37b0f1bb756f938023512c">preparePlanForEpilogueVectorLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad7f49d3dc767d0f0789ffd9e332e7a49">llvm::PrepareToSplitEntryBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a6f875a89b00cf04b3d413c954e9fe915">anonymous{AsmWriter.cpp}::AssemblyWriter::printBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a732a1e33a5b12385ee96d35735356c0e">printBBName</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-delinearization-cpp-/#a5c53d773e653f349a53c8796896bfaed">anonymous{Delinearization.cpp}::printDelinearization</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineoperand-cpp/#a39e0c396e9ae881eddc29a02ebc40956">printIRBlockReference</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#ab31b894cd23f1d93468a50153a385fa1">llvm::memtag::readRegister</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#a90cb1c8c28c96b3e0abcd1dc070a7d87">anonymous{LICM.cpp}::ControlFlowHoister::registerPossiblyHoistableBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08f3f942afc0ee9115a8f9fa87e9191d">llvm::RemoveRedundantDbgInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#a1ad5c109b5218ec1d5f5fcd6390636ba">replaceConstantExprOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdaterbulk/#a60fac14032181eef9fe2f3e790ce9c28">llvm::SSAUpdaterBulk::RewriteAllUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a>, <a href="/web-llvm/docs/api/classes/anonymous-flattencfg-cpp-/flattencfgopt/#a602f2acd35dc9f79595697f2a5296541">anonymous{FlattenCFG.cpp}::FlattenCFGOpt::run</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#ab6f626d7c6ac0566eb109ca95019549f">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegionNoRecurse</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#afe210701ce0a3abfea9278d2538a6470">scanOneBB</a>, <a href="/web-llvm/docs/api/classes/llvm/blockcoverageinference/#a2cd68a41956d11d1d2647c1de065b1e0">llvm::BlockCoverageInference::shouldInstrumentBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a994d8b93d52a786748213d2cb98f1000">llvm::shouldOptimizeForSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpchain/#a6bb3a89ac6216b60c21d8815fb2fa220">anonymous{MergeICmps.cpp}::BCECmpChain::simplify</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/simplifycfgopt/#a0cadca6f494db1ccdccb2256e49cb7fe">anonymous{SimplifyCFG.cpp}::SimplifyCFGOpt::simplifyOnce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a925d8eaf1d93c7d13870ae5948c48140">sinkLoopInvariantInstructions</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-scalarizer-cpp-/#ab918ecc49624aa2ae55ec900d4919ee7">anonymous{Scalarizer.cpp}::skipPastPhiNodesAndDbg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32aaa22eb69c944393cd5a1c79fa0d35">llvm::SplitBlockAndInsertSimpleForLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#a602f4157bb9c3e355a0a9377f828a56f">llvm::SuspendCrossingInfo::SuspendCrossingInfo</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#adb1dafd461988f3d8e687eabb99e108d">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryInlineCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>, <a href="/web-llvm/docs/api/classes/llvm/addrlabelmap/#aba3d880d5b4c6f123a2c50923e78c46a">llvm::AddrLabelMap::UpdateForDeletedBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxasmprinter-cpp/#ac028d1a2a3f133861c33cd16c0addd6e">useFuncSeen</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#aadfa6a6899cb32e0b249dfe7d5ab904b">UseTlsOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a0b4c48d53ab1ddc5bf009cd4ddffdc5a">validateAndCostRequiredSelects</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a> and <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#af2c1b11e25a6289f7eca7c11acd304dc">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::~RuntimeCallInserter</a>.</p>

</div>
</div>

### getParent() {#a8418f5e52a18c1b1ab5860eb591fd325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::BasicBlock::getParent ()</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#ab7194606aa12931e96f8f5448d418ed0">Function</a>.</p>

</div>
</div>

### getPostdominatingDeoptimizeCall() {#ae8a9915f25abfe7ff5010da686e446c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallInst * BasicBlock::getPostdominatingDeoptimizeCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the call instruction calling @llvm.experimental.deoptimize that is present either in current basic block or in block that is a unique successor to current block, if such call is present.</p>


<p>Otherwise, returns null.</p>


<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a20d58a0069048b80461676a4132ad1d4">canRotateDeoptimizingLatchExit</a>.</p>

</div>
</div>

### getPostdominatingDeoptimizeCall() {#aa686e5eb0f14cc06211dd7b571736ff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * llvm::BasicBlock::getPostdominatingDeoptimizeCall ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getSinglePredecessor() {#a59fb91d1691350f7d1b8e8a114e3f2a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * BasicBlock::getSinglePredecessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the predecessor of this block if it has a single predecessor block.</p>


<p>Otherwise return a null pointer.</p>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/hardwareloops-cpp/#adb6fcf2b6da127679d3169f4474e6912">CanGenerateTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa8ec1591dd8e7639e5b5e1869b49e9b5">CanPropagatePredecessorsForPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#ad908d5abcd036d7ff7e277fda6821cf0">CanProveNotTakenFirstIteration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a36f7b9a37f452349ad02d4d7f7d33972">anonymous{LoopDistribute.cpp}::InstPartitionContainer::cloneLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/#a8547d158fd9eb8e0cb27673ac3034a1c">llvm::TileInfo::CreateTiledLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#ad7f6d6fa3db0135b61c54c14f40cd6be">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#af15e3fefdfa2f5ea86ef5b8eacfa3517">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aa55563b1c40f6c6c94622a87dd7b5dcb">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitSCEVChecks</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a6039b71ec6a83438538f637df2080cd7">llvm::JumpThreadingPass::evaluateOnPredecessorEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#aa62aa7b8aa53a4cc57ee4397a5221e64">findDominatingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a48e98416c61da7bdde42d88ea460723c">findPHIForConditionForwarding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#ad459fdaea6898de5c02c8ed651ae50c9">FindWidenableTerminatorAboveLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a98c59bcf49cb7343886e8f425d6d877b">foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a345b729df369d487a73e9e67486dde01">getDomPredecessorCondition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a5751a2dd7306ff9a59eae6c1de8925">llvm::GetIfCondition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5b2e625679f6ef442bd50c46920e6048">anonymous{MergeICmps.cpp}::getOrderedBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs/#a8fdb3ab3875b4306157d47d84e972405">llvm::objcarc::BundledRetainClaimRVs::insertAfterInvokes</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aefc772d1808d513abc142b59844cfe45">llvm::ScalarEvolution::isBasicBlockEntryGuardedByCond</a>, <a href="/web-llvm/docs/api/classes/llvm/suspendcrossinginfo/#a184a65eb9ac1cd8093ea44d3490b3e70">llvm::SuspendCrossingInfo::isDefinitionAcrossSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8b617baf7fc5914d8a245e702ea65a7d">llvm::ScalarEvolution::isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunroll-cpp/#a8ed485ff9b2526376525b8f792929a31">loadCSE</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a30207ff92cc09d50e4f6e188de0f59ed">llvm::JumpThreadingPass::maybeMergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a710878a88d68a9169313249bfd52862a">llvm::JumpThreadingPass::maybethreadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a5a5d8a7a6d46886bfb6350ed47c0f225">mergeBlocksIntoPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1f70470f7a7722fd55c58c81358107f2">mergeCleanupPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a6a58dfc629e1b208cdd7b2bd76203184">mergeConditionalStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a080bc28b084ddc6539dda7e94a300da7">llvm::JumpThreadingPass::processGuards</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac06e19670a4cb86b0c885cf67bdb1bc4">llvm::JumpThreadingPass::processImpliedCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a49e16290a862f7a6fb362564ea3a3c32">recordConditions</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af37433fe005d86f4551e44915bd97e0b">llvm::InstCombinerImpl::replacedSelectWithOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-mvetailpredication-cpp-/mvetailpredication/#a7b878614c194557b9109ce592f817861">anonymous{MVETailPredication.cpp}::MVETailPredication::runOnLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#ad016e01a6a7d6f527043e7ded55dd65b">shouldInstrumentBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/simplifycfgopt/#a0cadca6f494db1ccdccb2256e49cb7fe">anonymous{SimplifyCFG.cpp}::SimplifyCFGOpt::simplifyOnce</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>.</p>

</div>
</div>

### getSinglePredecessor() {#a5688578838361dae8ae2e61da07bbd05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BasicBlock::getSinglePredecessor ()</td>
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



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getSingleSuccessor() {#a79c007dcf9fff57e1569e778d7885b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * BasicBlock::getSingleSuccessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the successor of this block if it has a single successor.</p>


<p>Otherwise return a null pointer.</p>


<p>This method is analogous to getSinglePredecessor above.</p>


<p>Declaration at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/structs/llvm/tileinfo/#a8547d158fd9eb8e0cb27673ac3034a1c">llvm::TileInfo::CreateTiledLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a5bb62631ba6a4be0ae02f7365ee4a7d7">ensureValueAvailableInSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looppredication-cpp/#ad459fdaea6898de5c02c8ed651ae50c9">FindWidenableTerminatorAboveLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af65a1289341b6d2b3c37541e1cb55bdd">llvm::isProfitableToTransform</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/speculatequery/#aa93fb291eede52d54761819aee1c3dfc">llvm::orc::SpeculateQuery::isStraightLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74e70f818c0942a018c9c24cd5dca061">llvm::MergeBlockSuccessorsIntoGivenBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a6a58dfc629e1b208cdd7b2bd76203184">mergeConditionalStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#ac6d407975ce40c65a627e26212bf60fd">anonymous{MergeICmps.cpp}::processPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ae1f1125c20c109a1dedb0cafbb501c22">programUndefinedIfUndefOrPoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#abb3297c94836debc08248e7ae3f47582">sinkLifetimeStartMarkers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>.</p>

</div>
</div>

### getSingleSuccessor() {#a4b3f0f8155c3a807947cbd3550919929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BasicBlock::getSingleSuccessor ()</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getTerminatingDeoptimizeCall() {#a6796a84f02394ce6ebef227c866cd5eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallInst * BasicBlock::getTerminatingDeoptimizeCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the call instruction calling @llvm.experimental.deoptimize prior to the terminating return instruction of this basic block, if such a call is present.</p>


<p>Otherwise, returns null.</p>


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 331 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#a9d5c5c93a898487fabe292e69b1b3c9e">anonymous{Debugify.cpp}::findTerminatingInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15055c7e3a33b44c293df24e4ba7bc5e">llvm::IsBlockFollowedByDeoptOrUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad98f06eded5a01ee8704f7d7d9ca4c5b">tryWidenCondBranchToCondBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7d391dbabb8fc073db875548184a768d">violatesLegacyMultiExitLoopCheck</a>.</p>

</div>
</div>

### getTerminatingDeoptimizeCall() {#ab60db4e6c6df756daf688cf7ea76293c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * llvm::BasicBlock::getTerminatingDeoptimizeCall ()</td>
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



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getTerminatingMustTailCall() {#ad7038933b96247814b611635abb9686c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallInst * BasicBlock::getTerminatingMustTailCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the call instruction marked 'musttail' prior to the terminating return instruction of this basic block, if such a call is present.</p>


<p>Otherwise, returns null.</p>


<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 300 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#a9d5c5c93a898487fabe292e69b1b3c9e">anonymous{Debugify.cpp}::findTerminatingInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a7bc99de2f3874d014ce70d70c12f3b12">getInsertionRange</a> and <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>.</p>

</div>
</div>

### getTerminatingMustTailCall() {#acb5567bfc9bdf953e2d365ef7a3a54ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * llvm::BasicBlock::getTerminatingMustTailCall ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getTerminator() {#aef9e9fcf4c5dfce90276ca16d91b8e46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::sandboxir::BasicBlock::getTerminator ()</td>
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

<p>Returns the terminator instruction if the block is well formed or null if the block is not well formed.</p>

<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#ab8e0eab61769d9974aeed9345ce11baf">LLVM_READONLY</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a0f682f69a2b53113b0df4e2b9a7e3aae">anonymous{ConstraintElimination.cpp}::State::addInfoFor</a>, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>, <a href="/web-llvm/docs/api/structs/prefetch/#a63798d891eed0f2ca719b80993bfd24d">Prefetch::addInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a35dd2e0efa71641e526e898918af9ef6">addNoUndefAttrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a75514cc4632af88b58a31912c8bd9ecc">anonymous{InlineCost.cpp}::CallAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/structs/llvm/codemetrics/#a994ac02d488546e86aeb825e0ea88059">llvm::CodeMetrics::analyzeBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#aa5755510005963e0d33f000914c5489d">anonymous{HotColdSplitting.cpp}::analyzeProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/canonicalloopinfo/#a32ff799dcb39887a8d21322020f305ba">llvm::CanonicalLoopInfo::assertOK</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxprofflattening-cpp-/profileannotator/#a826579366a697467a065c5423cea8df1">anonymous{PGOCtxProfFlattening.cpp}::ProfileAnnotator::assignProfileData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a96f99bd2a31fec426c13e7adf776fe16">basicBlockCanReturn</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#a4683663d1041570f374ad7ac4ea119eb">anonymous{HotColdSplitting.cpp}::blockEndsInUnreachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/predicateinfobuilder/#aaaff3f60426ede3ce93de105f66cb581">llvm::PredicateInfoBuilder::buildPredicateInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a54c3911cf4abbcd272fa99a303823942">llvm::BranchProbabilityInfo::calculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bf41f2408094f54097744991c82336a">llvm::calculateCXXStateForAsynchEH</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8b49442c1c01ddc388c51d7599c0f876">llvm::calculateSEHStateForAsynchEH</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#a20d58a0069048b80461676a4132ad1d4">canRotateDeoptimizingLatchExit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a465bf95ad9ca82a4541555d837aec85f">llvm::canSplitLoopBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a116214243278440ab010746880a8e6e5">checkBasicSSA</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af97d9ff977792ae671987a9a95f942f2">llvm::CloneFunctionBodyInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartitioncontainer/#a36f7b9a37f452349ad02d4d7f7d33972">anonymous{LoopDistribute.cpp}::InstPartitionContainer::cloneLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-codemoverutils-cpp-/controlconditions/#a866163a9dbd27133c221fc2569333ddb">anonymous{CodeMoverUtils.cpp}::ControlConditions::collectControlConditions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a3a97fed79c86bf242b0f090e1cb2e6">llvm::colorEHFunclets</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a4ca10cc5976994ee1c01be4b019c1ee6">llvm::FunctionComparator::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#add650fe201d4951c7146442a8969cc59">ComputeNumSignBitsImpl</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gac3778bafa67cdae223698e5bba785a76">ComputePostOrders</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/branchprobabilityinfo-cpp/#ade155905429b0a259a1030f418c04ad9">computeUnlikelySuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/vpbasicblock/#a2ffeb0208ddb1c5cf8a4bfb2ef0c9008">llvm::VPBasicBlock::connectToPredecessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a1548d6cc07c1c5595817e73713d58a23">copyMustTailReturn</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aae3714d6fe11a1e8c559880caf67fbc7">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab84af206a9a08b9bf97eaadc87874c6c">llvm::OpenMPIRBuilder::createAtomicCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a8fcf014aa7d3fd2461ab2349b397b647">llvm::SPIRVMergeRegionExitTargets::createExitVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#abba5b02b3dfb44e87915fcf6af38e3fb">createFoldedExitCond</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a741f7bb1cc23d5c9d8917e1c7970c732">createInvariantCond</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a52c61b3548ffc6f5088b78dc45141354">llvm::SPIRVStructurizer::createOpSelectMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a1fb67d47830d47e72144d7456dbb7fa0">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::createTiledLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a5f7b74afe2d1d4f3cc3373cd8af2e6ad">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileDPLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a991aa40e1236f6093ee0c3d93628319c">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::createTileLoadStoreLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#aa12c0d3acb3f625ee09d2919907d4067">llvm::VPlan::createVPIRBasicBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a8ce6d27f2029316071fd8130578a2229">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::currentLimitations</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a419746e2bdc89fee0101b010a13ec0c7">detectShiftUntilBitTestIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af67eef9e8d101756a1a0164e63eb4556">dominatesMergePoint</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae046f3782a1242c97fe9fe937793fa3f">anonymous{DeadStoreElimination.cpp}::DSEState::dominatingConditionImpliesValue</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4cd89ca702a817aac3a4521dd2462a2e">llvm::DuplicateInstructionsInSplitBetween</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizermainloop/#aeeb47f904372b9e25b9f7ba606158b25">llvm::EpilogueVectorizerMainLoop::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#a72c491cdf8cf0283d87008831431f917">llvm::InnerLoopVectorizer::emitIterationCountCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#af15e3fefdfa2f5ea86ef5b8eacfa3517">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitMemRuntimeChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a141e9946f635323d4da5e8b4b3f64e44">llvm::VPFirstOrderRecurrencePHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionphirecipe/#ad481483dac767c09d773266ba8b877e5">llvm::VPReductionPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/speculatequery/#ab7315fecd53d8915efb8a2ac8f908595">llvm::orc::SpeculateQuery::findCalles</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#aa62aa7b8aa53a4cc57ee4397a5221e64">findDominatingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a9bbea577bf401c708dc854d2dad600af">findLoopComponents</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#adc183a6edc37f305ee9ca5ff0bc33a6e">FindLoopCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a2ec50ab2c78eff965caf3da71cd08be4">llvm::DominatorTree::findNearestCommonDominator</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a48e98416c61da7bdde42d88ea460723c">findPHIForConditionForwarding</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-debugify-cpp-/#a9d5c5c93a898487fabe292e69b1b3c9e">anonymous{Debugify.cpp}::findTerminatingInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a6ff25bdf0db077015fe35d4a82b4b6dc">FlattenLoopPair</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9317f2efaf85a4afc7cde58a2c0d734b">llvm::InstCombinerImpl::foldBinopWithPhiOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#aa42477bdea230fb3cc4ea230c1125941">foldExit</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aef28063eb280fec69a391dd35c51666e">llvm::InstCombinerImpl::foldFreezeIntoRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a73b18943dffc9db671d3217c90b15a4f">foldGuardedFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a98c59bcf49cb7343886e8f425d6d877b">foldICmpWithDominatingICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a1ec0b67cb3bfede0da5e10a3ef76d9eb">llvm::SPIRVMergeRegionExitTargets::gatherSuccessors</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#a48955fd76dc29a6b4391aef55ce3efd3">llvm::VPTransformState::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a089d9b5caf2479e6b87f94c73e5b1f70">getBestDestForJumpOnUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a9293c2849df988b06fecea7e1b021fee">getBranchHint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#ace82efda93a438644ce877d6975851b7">getBranchInsertPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/loop/loopbounds/#acfa250dd5ec97448681f9833e22d50cf">llvm::Loop::LoopBounds::getCanonicalPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a345b729df369d487a73e9e67486dde01">getDomPredecessorCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a5345629403124507c78e4e32c6a04b84">getEHPadFromPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a74712012450beeec949c228fd21d10a6">getExpectedExitLoopLatchBranch</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a5751a2dd7306ff9a59eae6c1de8925">llvm::GetIfCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifyindvar-cpp/#a995c9f54308d436b9046a8741b149671">getInsertPointForUses</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/funcpgoinstrumentation/#a5e10295899c921b1730c88017d1bc4d6">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#ab74216e0ce40d85e6c843637018ce553">getInstrBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a65facbdd55e486cbcef04a12de132c9c">getJumpThreadDuplicationCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#afb9fd1f991a7503fe4fd7dc16bda6f30">getKnownValueOnEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a580a6361a2bad87e6071ecc795bdae96">llvm::Loop::getLoopGuardBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/memcmpexpansion/#a36cf9f1978b6c3bce437ad288b98e1dc">anonymous{ExpandMemCmp.cpp}::MemCmpExpansion::getMemCmpExpansion</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-functionpropertiesanalysis-cpp-/#a77b2d8fec31f0ea9b4d558784f86941a">anonymous{FunctionPropertiesAnalysis.cpp}::getNumBlocksFromCond</a>, <a href="/web-llvm/docs/api/structs/llvm/regiontraits-0f5d60cddaa2a9bddfbb61dc941a8926/#a6b3f1d531ccfa41bf01f4f3ec258b5ad">llvm::RegionTraits&lt; Function &gt;::getNumSuccessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsimplifycfg-cpp/#a31aca34b2768bfd5917289a053674bd1">getOnlyLiveSuccessor</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/innerloopvectorizer/#aa83b181aa14d5afe1390faad388f91a4">llvm::InnerLoopVectorizer::getOrCreateVectorTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopnestanalysis-cpp/#a1324f8c4f6c399fbb6c4fae0404a47ca">getOuterLoopLatchCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp/#a64bd791e5e5ee7951cf2b942defd81a8">getOutliningBenefit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp/#af13aae7297d317a09ab92d3bfbff0506">getOutliningPenalty</a>, <a href="/web-llvm/docs/api/classes/vectorslice/#aef12c412e54fb31aa597199eadc0e866">VectorSlice::getSlicedVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a58bcd428c0ca38b723b8ef938868ec4a">llvm::coro::getSpillInsertionPt</a>, <a href="/web-llvm/docs/api/classes/llvm/gcprojectioninst/#a6cffcfabac72ca61185ea24c1208b937">llvm::GCProjectionInst::getStatepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#af8ebafc2930bf25dfa6887c4b5bc2c33">getStrlenWithNull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1b38a63d3be7413f335be5f2d81bb234">llvm::GetSuccessorNumber</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp/#adf65ae1a0e832dc600acebbc0c483fe8">getSuccState</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a614a737e40ceece782633b5cabbeab49">llvm::coro::BaseCloner::handleFinalSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#ad0fe28a9dccc66e85a05b9447f4141ef">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handlePHINode</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#ac2fcd61c17c94d7e9d10b24b718c812e">llvm::VPlanTransforms::handleUncountableEarlyExit</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a352cde174c12aa24afbb7e61c22853e2">llvm::InstCombinerImpl::handleUnreachableFrom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a18d5638ef4590bc32bb8c69017352c1b">hasSideeffectFreeStaticResolution</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a3a3a3183a327e1186dbe900032390ec6">hoist</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a2f46552f3c07dc30e7acc64cdab53056">hoistAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab4d6b37c7f97bad2b1f441dc3fd43e0">llvm::hoistAllInstructionsInto</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aebac730a26c607cea825366afca2d8b1">hoistBOAssociation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a062c93def88f99e93047ba86970c4eab">hoistGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a1f669cc640bda295e6c2e2b3c90babb9">hoistMinMax</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a697cde840957bbc0b2848a593c3e0d5a">hoistMulAddAssociation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5efa2c3e00054566f1baaebc766461a4">llvm::hoistRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#aabf61131f4fe5c83b4f3dccf4adb5e96">hoistSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a045ddd9cf89c401caf98eb3acad6b1a7">insertBoundsCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a9019e662ee1c0c04e06e9871650268c8">llvm::DIBuilder::insertDeclare</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprofileprober/#af77769bc44a5fe5006bbc89befd75e4b">llvm::SampleProfileProber::instrumentOneFunc</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a78cf0931abfbc70e124e7c225584b686">llvm::Attributor::isAssumedDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15055c7e3a33b44c293df24e4ba7bc5e">llvm::IsBlockFollowedByDeoptOrUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a3bed745566338e51f330ff68e39ff4a1">isChainSelectCmpBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a29da820d4c19ac64f750762012fd13ca">anonymous{IndirectCallPromotion.cpp}::isDestBBSuitableForSink</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#a19fefaa90777f772a3db9ce94e5209ab">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::isEdgeFeasible</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ae8db70add348cf4c743530e9b9f54e">llvm::isInlineViable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab2fadbd4626ccfbf3d2cabd27003d597">llvm::isInTailCallPosition</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8b617baf7fc5914d8a245e702ea65a7d">llvm::ScalarEvolution::isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#aef5a823f024815a31e9be15d48d037dc">isLoopDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a23d78b7d4dbea0ecc84dc55313ad1f25">isLoopExitTestBasedOn</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#ade3ca81f3a303345f66492c713c0e4ec">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::isLoopStructureUnderstood</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0581d6d5dc280ba2a39087a557050a6a">isNotUsedOrFoldableInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a50882a093546a573f3e879fc578f167d">isPowerOfTwoRecurrence</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaintrafnreachabilityfunction/#aa6f399598404d630b1091693ed0a6f88">anonymous{AttributorAttributes.cpp}::AAIntraFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90891ab2ec546e89f8dc771761824ef6">llvm::isSafeToMoveBefore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3eb7a9b091032d4d053727b7a578a97e">llvm::isUniformLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuunifydivergentexitnodes-cpp/#a8bff41c0d4994f55a5a6f1ab6bc4d018">isUniformlyReached</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a9f134722dec96eeaf23085a29b5da9f7">llvm::Loop::makeLoopInvariant</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a30207ff92cc09d50e4f6e188de0f59ed">llvm::JumpThreadingPass::maybeMergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a710878a88d68a9169313249bfd52862a">llvm::JumpThreadingPass::maybethreadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#aef2714d7816ffbf7f4eebf159be19d1f">anonymous{HotColdSplitting.cpp}::mayExtractBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a64307c8cbf811329320f43f90c434c08">moveBBContents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4972d73b274f1c9bb08ff314cba26522">llvm::moveInstructionsToTheEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae26e0fb4a78dc439a03ac42c4ba6e674">llvm::MemorySSAUpdater::moveToPlace</a>, <a href="/web-llvm/docs/api/classes/llvm/shuffleblockstrategy/#a3bad39b7c7fd81aa15068f082eb6f0a6">llvm::ShuffleBlockStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a6a2f2b3d9153487f51dae119c07f8461">needsLFTR</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8b569b7040c15c2e2233b3064caa8f4f">llvm::RandomIRBuilder::newSource</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#afd07d19c7174c06cd7c7415f63596839">llvm::slpvectorizer::BoUpSLP::optimizeGatherSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a8b1b5c42e2e99bb24a27219f8df7294d">OptimizeNonTrivialIFuncs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3c38fd13d9fa38356cca5ecdf7cfba23">optimizeSQRT</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdb3eec2f46233c924c30c0838a3c8fe">llvm::peelLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#aaa1d9cfaf2d4ef4eca30ce71eb8c3a89">peelToTurnInvariantLoadsDerefencebale</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a66f4dcea5cb859a1234e2b71901a1031">llvm::JumpThreadingPass::processBranchOnPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac06e19670a4cb86b0c885cf67bdb1bc4">llvm::JumpThreadingPass::processImpliedCondition</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/loopdistributeforloop/#a3c63565a36daca6f3bae8a75238ffd50">anonymous{LoopDistribute.cpp}::LoopDistributeForLoop::processLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxprofflattening-cpp-/profileannotator/#a9a58a5d6b3af1afec70ac9b8c1b2c902">anonymous{PGOCtxProfFlattening.cpp}::ProfileAnnotator::ProfileAnnotator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#af5d7aa7988108e9377f154cf6a22f02b">llvm::OutlinableRegion::reattachCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopidiomrecognition-cpp-/polynomialmultiplyrecognize/#a2d8e2d584aba003918f1d906f645df9e">anonymous{HexagonLoopIdiomRecognition.cpp}::PolynomialMultiplyRecognize::recognize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#ac177889afcc13c9ef882fd160c11e851">recordCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a73660474ea469de5320aec1e4f7c6e4c">redirectToHub</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#aa0c15073f16693ebc44c2410986cacec">llvm::MemorySSAUpdater::removeBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#ad5598e219fc0883eee8ee2ec612686d8">llvm::anonymous{SPIRVStructurizer.cpp}::replaceBranchTargets</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#a345ec4bbdfd40d9bf6166ae3bf29c5ab">llvm::SPIRVMergeRegionExitTargets::replaceBranchTargets</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#a1ad5c109b5218ec1d5f5fcd6390636ba">replaceConstantExprOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#a55f5674c6ed1c3e224388d258b79fcc5">llvm::anonymous{SPIRVStructurizer.cpp}::replaceIfBranchTargets</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/lockstepreverseiterator/#a681ac4eccb12ef854bb38bb656c1f1f5">anonymous{SimplifyCFG.cpp}::LockstepReverseIterator::reset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/materializationutils-cpp/#aba618c16a34739af0506ba1082d209a3">rewriteMaterializableInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a670232d63153cd8cd2793b3106e80661">rewriteMemOpOfSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2cadcdd1750ca8ba3197c1266052c059">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-dfajumpthreading-cpp-/dfajumpthreading/#a858489f4cff24516d6ac192f2165dce2">anonymous{DFAJumpThreading.cpp}::DFAJumpThreading::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-flattencfg-cpp-/flattencfgopt/#a602f2acd35dc9f79595697f2a5296541">anonymous{FlattenCFG.cpp}::FlattenCFGOpt::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-indvarsimplify-cpp-/indvarsimplify/#a145b6ea5ff08ca6373ed24389ca97c40">anonymous{IndVarSimplify.cpp}::IndVarSimplify::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#aa6e4c71c550683bb7d117491b717e2d1">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-siannotatecontrolflow-cpp-/siannotatecontrolflow/#a41ec313e34f80b7003873540888a35b3">anonymous{SIAnnotateControlFlow.cpp}::SIAnnotateControlFlow::run</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loopconstrainer/#af041772a16751b1c52d52ae08cd5046d">llvm::LoopConstrainer::run</a>, <a href="/web-llvm/docs/api/classes/llvm/placesafepointspass/#adcb87ee7d8b9f08bc82da9cae1c74429">llvm::PlaceSafepointsPass::runImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#ad2e77c37d75ccdfcb7a3bc4fa8d58c85">llvm::SLPVectorizerPass::runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#add9d8e7cc38ac083f42ce6873a8defdd">separateNestedLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/ssplayoutinfo/#a6e112cf20dd9147017cd475f6f6cfd09">llvm::SSPLayoutInfo::shouldEmitSDCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a45bde60377059fca310bb78e5d3a3ccb">simplifyInstructionWithPHI</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/simplifycfgopt/#a0cadca6f494db1ccdccb2256e49cb7fe">anonymous{SimplifyCFG.cpp}::SimplifyCFGOpt::simplifyOnce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afae3b747fc0c20f869df931130c534fa">llvm::spliceBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2522258b740c5c76b6f9354663773c7c">llvm::splitBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7e8bd8939aed271b684b21231da918ee">llvm::splitBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#aedc5ca2a4ef6009dc69a410d60c7eeaf">llvm::coro::anonymous{SpillUtils.cpp}::splitBeforeCatchSwitch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35593f403e6311f92924141d2fdca50c">llvm::SplitBlockAndInsertIfElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7ac00229d8c59902686f52ed061cdc80">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32aaa22eb69c944393cd5a1c79fa0d35">llvm::SplitBlockAndInsertSimpleForLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0ad8b2536df5c9c88746f489318f445c">llvm::succ_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb374724f71627f5e166661bd908d470">llvm::succ_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abaf88c05560632cfb36b6c5f4d7924a3">llvm::succ_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27000cf502dbee435a9065f33fbef4ff">llvm::succ_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a96e05005577b2873e5ef9b3c99c4e30c">swapBBContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a914ac5681f80badb866f2aee44fc509a">threadBinOpOverPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a1ec7a76fbddf5983969def6e47c0f177">threadCmpOverPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a76e12ec076e7af4be7b8b77a5d53d3fc">llvm::OpenMPIRBuilder::tileLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ad67aa9d5f2effed17239ab3fad098999">llvm::JumpThreadingPass::tryThreadEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4b167ac2fde7b3d71172817650150a6">llvm::InstCombinerImpl::tryToSinkInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ae4ca9bfe94c6cc3d952413c7907db47f">llvm::JumpThreadingPass::tryToUnfoldSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a8528dea79f0940669c4fcb751940ca94">tryUnmergingGEPsAcrossIndirectBr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a2e6301db15e4516c92e21f33761886c6">turnSelectIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/makeguardsexplicit-cpp/#ac97dd263948d6205b380c1781ebb946d">turnToExplicitForm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#ae9b9f0a9eabb6c31d895d9b3e575fd51">anonymous{HotColdSplitting.cpp}::unlikelyExecuted</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a050cc2b2d1467ffcad6a825f1141424c">unswitchAllTrivialConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae5a9dfd216e7560889e2366f34ddd9f1">updatePredecessorProfileMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a81c8a5368d02d0b52654a3efe83dec38">llvm::LoopVersioning::versionLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7d391dbabb8fc073db875548184a768d">violatesLegacyMultiExitLoopCheck</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#afa06aa56938cd078f6e40733f5406dab">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineBasicBlockBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getTerminator() {#aaf87930bfa1c4483b0d94ce7b8622a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::BasicBlock::getTerminator ()</td>
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



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getTrailingDbgRecords() {#ac9e29bea40c1d36a6e36eeefefe7c073}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker * BasicBlock::getTrailingDbgRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fetch the collection of DbgRecords that "trail" after the last instruction of this block, see <a href="#a15ee901003da006e9da907c2bf70b9ec">setTrailingDbgRecords</a>.</p>


<p>If there are none, returns nullptr.</p>


<p>Declaration at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1181 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### getUniquePredecessor() {#a74aa9daea070e2ad3394a3ec58b7316a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * BasicBlock::getUniquePredecessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the predecessor of this block if it has a unique predecessor block.</p>


<p>Otherwise return a null pointer.</p>


<p>Note that unique predecessor doesn't mean single edge, there can be multiple edges from the unique predecessor to this block (for example a switch statement with multiple cases having the same destination).</p>


<p>Declaration at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ac0eeb33419165d13b0fa5c5f6fc69505">areInnerLoopLatchPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a6080253e27bfa816dce219371e6a820c">areOuterLoopExitPHIsSupported</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a0dca3347facf58865b34df5e5df676f0">llvm::MustBeExecutedContextExplorer::findBackwardJoinPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a893c7586e2537bc37a83a57a0190f67f">findLocationForEntrySafepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a580a6361a2bad87e6071ecc795bdae96">llvm::Loop::getLoopGuardBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a508cede7bc51eb83285e5fe30d14b701">IsAcceptableTarget</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a29da820d4c19ac64f750762012fd13ca">anonymous{IndirectCallPromotion.cpp}::isDestBBSuitableForSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74e70f818c0942a018c9c24cd5dca061">llvm::MergeBlockSuccessorsIntoGivenBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae11d36d6d1f06cdf18a0333eab22f381">llvm::MemorySSAUpdater::moveAllAfterMergeBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a4225c0d5e9678855f9784efc312ed92e">normalizeForInvokeSafepoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad75372cc26ff6f641159aed90d5fc11e">reuseTableCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac5d3cfa0755b34bcbd3f2298e9fa28ed">llvm::InstCombinerImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moveautoinit-cpp/#a8f3d27d1b480f6b3c90405707be76295">runMoveAutoInit</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a0c3d91a5a6e71c114dea21819cc71382">llvm::LoopNest::skipEmptyBlockUntil</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af4b167ac2fde7b3d71172817650150a6">llvm::InstCombinerImpl::tryToSinkInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#ae710dafa20ae793ef9dcab6a5ea4ca5c">anonymous{IndirectCallPromotion.cpp}::tryToSinkInstructions</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>.</p>

</div>
</div>

### getUniquePredecessor() {#a50665af84942fe71431228a39ed198e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BasicBlock::getUniquePredecessor ()</td>
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



<p>Definition at line 421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getUniqueSuccessor() {#a57f1945911ca1e95d0f51d7c3516b529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BasicBlock * BasicBlock::getUniqueSuccessor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the successor of this block if it has a unique successor.</p>


<p>Otherwise return a null pointer.</p>


<p>This method is analogous to getUniquePredecessor above.</p>


<p>Declaration at line 446 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#ab0cac3cc09d07bc44ffd388ff8be5e49">llvm::MustBeExecutedContextExplorer::findForwardJoinPoint</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-openmpopt-cpp-/#a87ab0eadf8a08e2fcd3e07d9529b6635">anonymous{OpenMPOpt.cpp}::hasFunctionEndAsUniqueSuccessor</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/sanitizercoverage-cpp/#a82d87658bf2f69df81493401a7c6dc52">IsBackEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a15055c7e3a33b44c293df24e4ba7bc5e">llvm::IsBlockFollowedByDeoptOrUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#af5d7aa7988108e9377f154cf6a22f02b">llvm::OutlinableRegion::reattachCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/loopnest/#a0c3d91a5a6e71c114dea21819cc71382">llvm::LoopNest::skipEmptyBlockUntil</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a428f7b53e32934ae46a9aa35d3028d87">tryToMergeLandingPad</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>.</p>

</div>
</div>

### getUniqueSuccessor() {#a47f3ae1882f74b645a2075d7376232d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BasicBlock::getUniqueSuccessor ()</td>
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



<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getValueSymbolTable() {#a4fcc523128392b84e17315b83f249ba1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSymbolTable * BasicBlock::getValueSymbolTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a pointer to the symbol table if one exists.</p>

<p>Declaration at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### hasAddressTaken() {#a315f26c899f5ea8a780db4740ba95ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BasicBlock::hasAddressTaken ()</td>
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

<p>Returns true if there are any uses of this basic block other than direct branches, switches, etc.</p>


<p>to it.</p>


<p>Definition at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a75514cc4632af88b58a31912c8bd9ecc">anonymous{InlineCost.cpp}::CallAnalyzer::analyze</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#ab80e6d04b6a0305ed3b55780e7eed355">llvm::AsmPrinter::emitBasicBlockStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/addrlabelmap/#acbb53aac904b80dad6df38f882e319f3">llvm::AddrLabelMap::getAddrLabelSymbolToEmit</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5b2e625679f6ef442bd50c46920e6048">anonymous{MergeICmps.cpp}::getOrderedBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#ae6fa18c5b7272e2bdd00c26da8041358">hasAddressTakenAndUsed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a5a7fe53bda3cbce584280a177a18d5ab">isBlockValidForExtraction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ae8db70add348cf4c743530e9b9f54e">llvm::isInlineViable</a>, <a href="/web-llvm/docs/api/classes/llvm/blockaddress/#a5272e28bf5a3ca5f021f055c88adc118">llvm::BlockAddress::lookup</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#aef2714d7816ffbf7f4eebf159be19d1f">anonymous{HotColdSplitting.cpp}::mayExtractBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a> and <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>.</p>

</div>
</div>

### hasNPredecessors() {#a526630ff85b48f29ac5b4c519c6c2243}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlock::hasNPredecessors (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this block has exactly N predecessors.</p>

<p>Declaration at line 427 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 503 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a5bb62631ba6a4be0ae02f7365ee4a7d7">ensureValueAvailableInSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ac4b6f64940804c14b1e0cc4ad04fb18a">introduceTooManyPhiEntries</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryssaupdater/#ae6b63bcaa1f6638b608f911cd04341e2">llvm::MemorySSAUpdater::wireOldPredecessorsToNewImmediatePredecessor</a>.</p>

</div>
</div>

### hasNPredecessorsOrMore() {#ae020673b5ca2bae358005b8980413c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlock::hasNPredecessorsOrMore (unsigned N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this block has N predecessors or more.</p>

<p>Declaration at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a72fccc775a9d83203b8d67f98dc0a3c4">CanRedirectPredsOfEmptyBBToSucc</a>.</p>

</div>
</div>

### insertDbgRecordAfter() {#a930f97c50e2e4eddb8a6cd55a4dfd5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::insertDbgRecordAfter (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * DR, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> into a block at the position given by <span class="doxyComputerOutput">I</span>.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1079 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ac8803aa267830622708ede7b732c7ae2">DbgInserterHelper</a>.</p>

</div>
</div>

### insertDbgRecordBefore() {#a365301682c41f8a7094218176d712cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::insertDbgRecordBefore (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * DR, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> Here)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> into a block at the position given by <span class="doxyComputerOutput">Here</span>.</p>

<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1088 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ac8803aa267830622708ede7b732c7ae2">DbgInserterHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ad19c7559d6302321172436f45c771171">insertDbgVariableRecordsForPHIs</a> and <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#adb6aff41bfe64d206d563112993cfb01">llvm::DIBuilder::insertLabel</a>.</p>

</div>
</div>

### insertInto() {#a8b2a364cd110b83dc5af4e4ef54f0c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::insertInto (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBefore=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert unlinked basic block into a function.</p>


<p>Inserts an unlinked basic block into <span class="doxyComputerOutput">Parent</span>. If <span class="doxyComputerOutput">InsertBefore</span> is provided, inserts before that basic block, otherwise inserts at the end.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p><em><a href="#a1b4bf7c97cdc8159fd73d48063f0b250">getParent()</a></em> is <span class="doxyComputerOutput">nullptr</span>.</p></dd>
</dl>


<p>Declaration at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>.</p>

</div>
</div>

### instructionsWithoutDebug() {#a2069641f358ef416658a2f321ca19d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filter_iterator&lt; BasicBlock::const_iterator, std::function&lt; bool(const Instruction &amp;)&gt; &gt; &gt; BasicBlock::instructionsWithoutDebug (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a const iterator range over the instructions in the block, skipping any debug instructions.</p>


<p>Skip any pseudo operations as well if <span class="doxyComputerOutput">SkipPseudoOp</span> is true.</p>


<p>Declaration at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 250 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aee330f66887329eef3ddc7dc8ccda193">blockIsSimpleEnoughToThreadThrough</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangelegality/#a168af47de1295ee31c30d2eac4c191ed">anonymous{LoopInterchange.cpp}::LoopInterchangeLegality::canInterchangeLoops</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/speculatequery/#ab7315fecd53d8915efb8a2ac8f908595">llvm::orc::SpeculateQuery::findCalles</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31070c67db84f4caef376dcb7906c4fb">getCaseResults</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/hotcoldsplitting-cpp/#a64bd791e5e5ee7951cf2b942defd81a8">getOutliningBenefit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a8bb9afd23da56f99f3bcdb52e9c74320">isSafeToSpeculateStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>.</p>

</div>
</div>

### instructionsWithoutDebug() {#a8b2e7652c5b25f8c9bfbc4fb59fa912b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; filter_iterator&lt; BasicBlock::iterator, std::function&lt; bool(Instruction &amp;)&gt; &gt; &gt; BasicBlock::instructionsWithoutDebug (bool SkipPseudoOp=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an iterator range over the instructions in the block, skipping any debug instructions.</p>


<p>Skip and any pseudo operations as well if <span class="doxyComputerOutput">SkipPseudoOp</span> is true.</p>


<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 260 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### invalidateOrders() {#a38ae48e763a7081850f72cfe7695bcd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicBlock::invalidateOrders ()</td>
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

<p>Mark instruction ordering invalid. Done on every instruction insert.</p>

<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#a9458ac6ff40d62e47321f8681cc23d54">validateInstrOrdering</a>.</p>

</div>
</div>

### isEHPad() {#ac9c170fde1808bbd4436a0dbd6d5e755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BasicBlock::isEHPad ()</td>
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

<p>Return true if this basic block is an exception handling block.</p>

<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#a362b5e6097732cbc0d2fb555a1f73400">getFirstNonPHIIt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a7227d9ecc33b8ed7a50b0d4341448c6c">calculateCXXStateNumbers</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#aaaced3d57d8877d30048b69be2787b21">calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3fd09aad409fbbe332f6e29711d7698">llvm::calculateWasmEHInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#aab2eda4003703fcc548e36043debfafa">canSplitCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a49a9acd58935033c9716f1b45d7df68a">deleteLoopIfDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86winehstate-cpp/#a158bd2eb807ca6795d388f3a6cb6ecae">getPredState</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a508cede7bc51eb83285e5fe30d14b701">IsAcceptableTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a710878a88d68a9169313249bfd52862a">llvm::JumpThreadingPass::maybethreadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#aef2714d7816ffbf7f4eebf159be19d1f">anonymous{HotColdSplitting.cpp}::mayExtractBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/injectorirstrategy/#af80c59250b5a5e540d6eaeb458be693a">llvm::InjectorIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/structs/llvm/slpvectorizerpass/#ad2e77c37d75ccdfcb7a3bc4fa8d58c85">llvm::SLPVectorizerPass::runImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-hotcoldsplitting-cpp-/#ae9b9f0a9eabb6c31d895d9b3e575fd51">anonymous{HotColdSplitting.cpp}::unlikelyExecuted</a>.</p>

</div>
</div>

### isEntryBlock() {#a4ec05121d4b54b3691ad6203e78ff54e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlock::isEntryBlock ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this is the entry block of the containing function.</p>


<p>This method can only be used on blocks that have a parent function.</p>


<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#aa1970a96b57d122e4bb765d0f82e96e6">DbgVariableRecordsRemoveUndefDbgAssignsFromEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae3df768f340538afba57a5eaeb0ba277">llvm::SelectionDAGBuilder::isExportableFromCurrentBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affedc93ead6b25c57a7196d32ff11e89">llvm::isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a6f875a89b00cf04b3d413c954e9fe915">anonymous{AsmWriter.cpp}::AssemblyWriter::printBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a732a1e33a5b12385ee96d35735356c0e">printBBName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08f3f942afc0ee9115a8f9fa87e9191d">llvm::RemoveRedundantDbgInstrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a732f2f3b2dd163037799643ce7460547">removeRedundantDbgLocs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a579e878e02e34bf9699e3d82da2bc070">removeUndefDbgAssignsFromEntryBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4e75fd1680471e758ffbca9f8d893884">removeUndefDbgLocsFromEntryBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a972ba6a9b390c00a2c1d9a5841f79bcb">UpdateAnalysisInformation</a>.</p>

</div>
</div>

### isInstrOrderValid() {#ae4e597933a0ba6d26ec65cc1beb61eb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BasicBlock::isInstrOrderValid ()</td>
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

<p>Returns true if the Order field of child Instructions is valid.</p>

<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### isLandingPad() {#ac3a2a666b5703b8c9bda318ef18c731c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlock::isLandingPad ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this basic block is a landing pad.</p>


<p>Being a `‘landing pad`' means that the basic block is the destination of the 'unwind' edge of an invoke instruction.</p>


<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aa7e215bdd027461da0d8205cf5ef0e32">mergeCompatibleInvokes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>.</p>

</div>
</div>

### isLegalToHoistInto() {#adfbe1d6bd7544c2fd2efcdf2d348f264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool BasicBlock::isLegalToHoistInto ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if it is legal to hoist instructions into this block.</p>

<p>Declaration at line 704 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 579 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### LLVM\_DEPRECATED() {#a4e1c5961974e47ac42e9c34efa0792b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BasicBlock::LLVM_DEPRECATED ("Use iterators as instruction positions instead", "getFirstNonPHIIt")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#a05695d7068e19f1799ed15ed7523a957">getFirstNonPHI</a>, <a href="#a362b5e6097732cbc0d2fb555a1f73400">getFirstNonPHIIt</a> and <a href="#a4e1c5961974e47ac42e9c34efa0792b3">LLVM_DEPRECATED</a>.</p>


<p>Referenced by <a href="#a4e1c5961974e47ac42e9c34efa0792b3">LLVM_DEPRECATED</a>.</p>

</div>
</div>

### moveAfter() {#a507bb47fc498540c91fec0bf95c25907}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::moveAfter (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this basic block from its current function and insert it right after <span class="doxyComputerOutput">MovePos</span> in the function <span class="doxyComputerOutput">MovePos</span> lives in.</p>

<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a2e130f575ee6cbddeb0d62b295dee036">InsertStackProtectors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a4839bb9ff9510a0c0bda1e41cabe4714">placeSplitBlockCarefully</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e4870aac193f722693ae7e24aa5a2be">llvm::sortBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>.</p>

</div>
</div>

### moveBefore() {#ac1fd6437bbfce263b87f01767d950ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicBlock::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * MovePos)</td>
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

<p>Unlink this basic block from its current function and insert it into the function that <span class="doxyComputerOutput">MovePos</span> lives in, right before <span class="doxyComputerOutput">MovePos</span>.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a> and <a href="#ac1fd6437bbfce263b87f01767d950ce5">moveBefore</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a> and <a href="#ac1fd6437bbfce263b87f01767d950ce5">moveBefore</a>.</p>

</div>
</div>

### moveBefore() {#a5092f4ba1618a1cf38a1558ee642912f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### phis() {#a13da92d2694197fbcb5b95fd94e7570d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_phi_iterator &gt; llvm::BasicBlock::phis ()</td>
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

<p>Returns a range that iterates over the phis in the basic block.</p>


<p>Note that this cannot be used with basic blocks that have no terminator.</p>


<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#a13da92d2694197fbcb5b95fd94e7570d">phis</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6aa61c7462784d1c9641ee501486375">llvm::InstCombinerImpl::addDeadEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a77ce0ad30f134042ba819a49315238d8">addPHINodeEntriesForMappedBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a0375fe3378c23272b805320851744043">addPredecessorToBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a882dcfc2455d525e78a8bbf46863ace2">analyzeExitPHIsForOutputUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ad50c8a25364117c5dd799586dd5b0904">areInnerLoopExitPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#ac0eeb33419165d13b0fa5c5f6fc69505">areInnerLoopLatchPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a6080253e27bfa816dce219371e6a820c">areOuterLoopExitPHIsSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a72fccc775a9d83203b8d67f98dc0a3c4">CanRedirectPredsOfEmptyBBToSucc</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a0ac5df8f0304981180d602dacb13512c">llvm::LoopVectorizationCostModel::collectValuesToIgnore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/classes/llvm/epiloguevectorizerepilogueloop/#ad1b4c0caba0fac3a1486890cd2445040">llvm::EpilogueVectorizerEpilogueLoop::createEpilogueVectorizedLoopSkeleton</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a64ecdacbd49f696216e772782a109945">llvm::DeleteDeadPHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a49a9acd58935033c9716f1b45d7df68a">deleteLoopIfDead</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ddf07853114e72808bc2713805814f3">llvm::EliminateDuplicatePHINodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a48e98416c61da7bdde42d88ea460723c">findPHIForConditionForwarding</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#aac383495fcc8fae9bf826d4d89467928">anonymous{LowerSwitch.cpp}::FixPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#a51ff57d75f102e980e39535df6ff00bb">fixupPHINodeForNormalDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#a59b92d3bbd9b21b61a2afbb73c10c3b0">fixupPHINodeForUnwindDest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a480bd8ae64f6f3e4a9cc6e1a724b2ad0">forwardSwitchConditionToPHI</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7851d1e39cf3c6f27aa6fe911056a142">incomingValuesAreCompatible</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ac4b6f64940804c14b1e0cc4ad04fb18a">introduceTooManyPhiEntries</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#afd0535a9a9691fbeaf8a97077837bff9">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::isEqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3c81223cabf643af27adba3b3ceb680c">isExistingPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#aef5a823f024815a31e9be15d48d037dc">isLoopDead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a68d6e6643cf0af54add83ed1ab981085">isPredicatedOnPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a3aaba0277f5dd5636e099fa81c20c533">isSafeToHoistInvoke</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="#a13da92d2694197fbcb5b95fd94e7570d">phis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8e5c4577c64728c435eca5f4f7e163ab">replaceTargetsFromPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a9a1db01205f9a51a14b99e53e3068da1">rewritePHINodesForExitAndUnswitchedBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a003a854484a7b23c151bc0b3d684e5d9">rewritePHINodesForUnswitchedExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7da8333874d1ad28bd987d4e7c474e53">sinkCommonCodeFromPredecessors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad98f06eded5a01ee8704f7d7d9ca4c5b">tryWidenCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1ced98ffeb2b6991821751661b136d6">llvm::updatePhiNodes</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a0b4c48d53ab1ddc5bf009cd4ddffdc5a">validateAndCostRequiredSelects</a>.</p>

</div>
</div>

### phis() {#ae0b11faf4e99c215582c8e83b0ac5792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; BasicBlock::phi_iterator &gt; BasicBlock::phis ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### print() {#a4232efd6f56912332e8631bd828eca21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a> * AAW=nullptr, bool ShouldPreserveUseListOrder=false, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the basic block to an output stream with an optional <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a>.</p>

<p>Declaration at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 4901 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="#afc70e919c88c86159cc94cea29b6c210">getModule</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02f9563a016dafe7fbc78fcb1f76f101/#ae7114057f671ef14b2fbbb1aa29adfe5">llvm::DOTGraphTraits&lt; DOTFuncMSSAInfo * &gt;::getNodeLabel</a>.</p>

</div>
</div>

### rbegin() {#a1c2af7a9e501d399f06ca7e10eef46e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::BasicBlock::rbegin ()</td>
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



<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a990710c9124f4c4183d029f678f8c13b">findLiveSetAtInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a> and <a href="/web-llvm/docs/api/classes/anonymous-atomicexpandpass-cpp-/atomicexpandimpl/#aff2bb39d444ea5a91162a8443884b7f6">anonymous{AtomicExpandPass.cpp}::AtomicExpandImpl::run</a>.</p>

</div>
</div>

### rbegin() {#af9baac351c917e7e5f60d81341f4df0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::BasicBlock::rbegin ()</td>
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



<p>Definition at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### reinsertInstInDbgRecords() {#ac15f880505f4cbe66f407f4e42a8b8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::reinsertInstInDbgRecords (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord/#a35975cf965c120e55130f30dd377418d">DbgRecord::self_iterator</a> &gt; Pos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>In rare circumstances instructions can be speculatively removed from blocks, and then be re-inserted back into that position later.</p>


<p>When this happens in RemoveDIs debug-info mode, some special patching-up needs to occur: inserting into the middle of a sequence of dbg.value intrinsics does not have an equivalent with DbgRecords.</p>


<p>Declaration at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1108 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### removeFromParent() {#a629adad5a5d84929eac0f0b00132af1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink 'this' from the containing function, but do not delete it.</p>

<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 275 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/domtreeupdater/#aa22a66bf381f2b0a994b4e00cca5eac4">llvm::DomTreeUpdater::callbackDeleteBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>.</p>

</div>
</div>

### removePredecessor() {#afe7af0c3ec2ef1f525173acd2ea4ba60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::removePredecessor (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Pred, bool KeepOneInputPHIs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update PHI nodes in this <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> before removal of predecessor <span class="doxyComputerOutput">Pred</span>.</p>


<p>Note that this function does not actually remove the predecessor.</p>


<p>If <span class="doxyComputerOutput">KeepOneInputPHIs</span> is true then don't remove PHIs that are left with zero or one incoming values, and don't simplify PHIs with all incoming values the same.</p>


<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2b3fdb09b0789963c439d41fe91e44a1">llvm::changeToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aac69c9cf4e552a52d5065e94dc023f82">HandleInlinedEHPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4cbd6aad6f6b93f79dc435feab77550e">HandleInlinedLandingPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad9d19d00519eec89a553d376d72c9520">mergeNestedCondBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac06e19670a4cb86b0c885cf67bdb1bc4">llvm::JumpThreadingPass::processImpliedCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a5770d604e68e48d1b8f1e7aa4c89a034">anonymous{LowerSwitch.cpp}::ProcessSwitchInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3057c2b7e1e25de160497b1ef3985c2a">redirectTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a0ceff22bcbbcc85abecced9a3a395ccf">removeSwitchAfterSelectFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a3e8ca2c20b8c4c14c72c49d98f3801ed">simplifySwitchOfCmpIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a428f7b53e32934ae46a9aa35d3028d87">tryToMergeLandingPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad98f06eded5a01ee8704f7d7d9ca4c5b">tryWidenCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### rend() {#a9237251072bf6816163abc2d053212ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::BasicBlock::rend ()</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a410a078c88ab7a1e5a4ce7362adc3efa">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::eraseFromParentAndMove</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a784adc2347b72f745ff1239aef3a3c26">llvm::OpenMPIRBuilder::finalize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ccb7187d4b25577a595e8bd49d2eb2c">llvm::FindAvailableLoadedValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-atomicexpandpass-cpp-/atomicexpandimpl/#aff2bb39d444ea5a91162a8443884b7f6">anonymous{AtomicExpandPass.cpp}::AtomicExpandImpl::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>.</p>

</div>
</div>

### rend() {#a8c3fa28a28df3fb064db524034812f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::BasicBlock::rend ()</td>
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



<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### renumberInstructions() {#a1f6d0ee6e9018d68250f49b9e3001139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::renumberInstructions ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Renumber instructions and mark the ordering as valid.</p>

<p>Declaration at line 726 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 726 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### replacePhiUsesWith() {#a7349a5d6bf71f3d3344b37104dc25bf4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::replacePhiUsesWith (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update all phi nodes in this basic block to refer to basic block <span class="doxyComputerOutput">New</span> instead of basic block <span class="doxyComputerOutput">Old</span>.</p>

<p>Declaration at line 677 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>.</p>

</div>
</div>

### replaceSuccessorsPhiUsesWith() {#a089e003bb688e55b9a91ed4e7fed3678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::replaceSuccessorsPhiUsesWith (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Old, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update all phi nodes in this basic block's successors to refer to basic block <span class="doxyComputerOutput">New</span> instead of basic block <span class="doxyComputerOutput">Old</span>.</p>

<p>Declaration at line 681 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a> and <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#af5d7aa7988108e9377f154cf6a22f02b">llvm::OutlinableRegion::reattachCandidate</a>.</p>

</div>
</div>

### replaceSuccessorsPhiUsesWith() {#a51d40bb95f61f8696b3b802cb8c203e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::replaceSuccessorsPhiUsesWith (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * New)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update all phi nodes in this basic block's successors to refer to basic block <span class="doxyComputerOutput">New</span> instead of to it.</p>

<p>Declaration at line 685 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### setIsNewDbgInfoFormat() {#a4425b120dc5e5600864748818fb1d923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::setIsNewDbgInfoFormat (bool NewFlag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Ensure the block is in "old" dbg.value format (<span class="doxyComputerOutput">NewFlag</span> == false) or in the new format (<span class="doxyComputerOutput">NewFlag</span> == true), converting to the desired format if necessary.</p>

<p>Declaration at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/function/#aaab8110aafc070c83bc701b13d2260df">llvm::Function::insert</a>.</p>

</div>
</div>

### setNewDbgInfoFormatFlag() {#a4e5249c00eee461ca4d26145eaaeac8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::setNewDbgInfoFormatFlag (bool NewFlag)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### setTrailingDbgRecords() {#a15ee901003da006e9da907c2bf70b9ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::setTrailingDbgRecords (<a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/record">Record</a> that the collection of DbgRecords in <span class="doxyComputerOutput">M</span> "trails" after the last instruction of this block.</p>


<p>These are equivalent to dbg.value intrinsics that exist at the end of a basic block with no terminator (a transient state that occurs regularly).</p>


<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1177 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a98eceec46c49f571b3413d3f91e31e10">llvm::DbgMarker::removeMarker</a>.</p>

</div>
</div>

### size() {#ab9f68be0e2bcdf14f503f45edea63023}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::BasicBlock::size ()</td>
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



<p>Definition at line 482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a57d54880afa1fb74833cc7c43ad33377">analyzeAndPruneOutputBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#af714eb55aced0ac27294c881d8be6ecb">findDuplicateOutputBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31070c67db84f4caef376dcb7906c4fb">getCaseResults</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-aa60992bff446bfaa212c7392dde9918/#ade1da0b29f5e3cb310ac591da00699c3">llvm::DenseMapInfo&lt; const SwitchSuccWrapper * &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4972d73b274f1c9bb08ff314cba26522">llvm::moveInstructionsToTheEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplan-cpp/#aaa122781f91b3e8bc730b2c5b7c07a05">remapOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#a55f5674c6ed1c3e224388d258b79fcc5">llvm::anonymous{SPIRVStructurizer.cpp}::replaceIfBranchTargets</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### sizeWithoutDebug() {#a96768456ed4add9aa5b9f56cdd3f6d7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">filter_iterator&lt; BasicBlock::const_iterator, std::function&lt; bool(constInstruction &amp;)&gt; &gt;::difference_type BasicBlock::sizeWithoutDebug ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size of the basic block ignoring debug instructions.</p>

<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 270 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1b8715812b9f4dd2bd46163dd1b51128">llvm::FastISel::fastEmitBranch</a>.</p>

</div>
</div>

### splice() {#af29f89e91dfd0ae90950f0b1bf49798d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicBlock::splice (<a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * FromBB)</td>
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

<p>Transfer all instructions from <span class="doxyComputerOutput">FromBB</span> to this basic block at <span class="doxyComputerOutput">ToIt</span>.</p>

<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="#a0ed5f3ab3c2e4196ee0cffffa080c062">begin</a>, <a href="#a0b4e7bee9b8575cc7db73329f1a561bd">end</a> and <a href="#af29f89e91dfd0ae90950f0b1bf49798d">splice</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aab4d6b37c7f97bad2b1f441dc3fd43e0">llvm::hoistAllInstructionsInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a3afc8c0c69b0c55edce3be13d5b7cc32">moveBBContents</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a64307c8cbf811329320f43f90c434c08">moveBBContents</a>, <a href="#af29f89e91dfd0ae90950f0b1bf49798d">splice</a>, <a href="#a7eb640f1399f315fe3cd89e3168b98b2">splice</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### splice() {#a7eb640f1399f315fe3cd89e3168b98b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicBlock::splice (<a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * FromBB, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromIt)</td>
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

<p>Transfer one instruction from <span class="doxyComputerOutput">FromBB</span> at <span class="doxyComputerOutput">FromIt</span> to this basic block at <span class="doxyComputerOutput">ToIt</span>.</p>

<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#af29f89e91dfd0ae90950f0b1bf49798d">splice</a>.</p>

</div>
</div>

### splice() {#aec78f7040944cf02862cd8f41052979e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::splice (<a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * FromBB, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromBeginIt, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromEndIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer a range of instructions that belong to <span class="doxyComputerOutput">FromBB</span> from <span class="doxyComputerOutput">FromBeginIt</span> to <span class="doxyComputerOutput">FromEndIt</span>, to this basic block at <span class="doxyComputerOutput">ToIt</span>.</p>

<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1051 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### splitBasicBlock() {#a52c990590792c91dd20b6d45acebe359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * BasicBlock::splitBasicBlock (<a href="#a98c0a84a5dfa8bce341c829709f171e5">iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BBName="", bool Before=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split the basic block into two basic blocks at the specified instruction.</p>


<p>If <span class="doxyComputerOutput">Before</span> is true, splitBasicBlockBefore handles the block splitting. Otherwise, execution proceeds as described below.</p>


<p>Note that all instructions BEFORE the specified iterator stay as part of the original basic block, an unconditional branch is added to the original BB, and the rest of the instructions in the BB are moved to the new BB, including the old terminator. The newly formed basic block is returned. This function invalidates the specified iterator.</p>


<p>Note that this only works on well formed basic blocks (must have a terminator), and <span class="doxyComputerOutput">'I'</span> must not be the end of instruction list (which would cause a degenerate basic block to be formed, having a terminator inside of the basic block).</p>


<p>Also note that this doesn't preserve any passes. To split blocks while keeping loop information consistent, use the SplitBlock utility function.</p>


<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 599 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab84af206a9a08b9bf97eaadc87874c6c">llvm::OpenMPIRBuilder::createAtomicCompare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a19ce83f3f1fef433e2ba91a0b2a196a0">llvm::CodeExtractor::findOrCreateBlockForHoisting</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#af8ebafc2930bf25dfa6887c4b5bc2c33">getStrlenWithNull</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a614a737e40ceece782633b5cabbeab49">llvm::coro::BaseCloner::handleFinalSuspend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a045ddd9cf89c401caf98eb3acad6b1a7">insertBoundsCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="#a2bc5caaabd6841e4ab97237ebcaeb86d">splitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#aedc5ca2a4ef6009dc69a410d60c7eeaf">llvm::coro::anonymous{SpillUtils.cpp}::splitBeforeCatchSwitch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33f79ea6e1fd1b8ba93c75519b1c929c">llvm::splitBlockBefore</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a26bed2b570bc6e4d34eda3488f8430c4">SplitBlockImpl</a>.</p>

</div>
</div>

### splitBasicBlock() {#a2bc5caaabd6841e4ab97237ebcaeb86d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BasicBlock::splitBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BBName="", bool Before=false)</td>
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



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a52c990590792c91dd20b6d45acebe359">splitBasicBlock</a>.</p>

</div>
</div>

### splitBasicBlockBefore() {#a30def825db848cba7fe11baa870b978f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * BasicBlock::splitBasicBlockBefore (<a href="#a98c0a84a5dfa8bce341c829709f171e5">iterator</a> I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BBName="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Split the basic block into two basic blocks at the specified instruction and insert the new basic blocks as the predecessor of the current block.</p>


<p>This function ensures all instructions AFTER and including the specified iterator <span class="doxyComputerOutput">I</span> are part of the original basic block. All Instructions BEFORE the iterator <span class="doxyComputerOutput">I</span> are moved to the new BB and an unconditional branch is added to the new BB. The new basic block is returned.</p>


<p>Note that this only works on well formed basic blocks (must have a terminator), and <span class="doxyComputerOutput">'I'</span> must not be the end of instruction list (which would cause a degenerate basic block to be formed, having a terminator inside of the basic block). <span class="doxyComputerOutput">'I'</span> cannot be a iterator for a <a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> with multiple incoming blocks.</p>


<p>Also note that this doesn't preserve any passes. To split blocks while keeping loop information consistent, use the SplitBlockBefore utility function.</p>


<p>Declaration at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="#a370c83904cd61faa1cce22906ec5f4c0">splitBasicBlockBefore</a>.</p>

</div>
</div>

### splitBasicBlockBefore() {#a370c83904cd61faa1cce22906ec5f4c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BasicBlock::splitBasicBlockBefore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; BBName="")</td>
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



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a30def825db848cba7fe11baa870b978f">splitBasicBlockBefore</a>.</p>

</div>
</div>

### validateInstrOrdering() {#a9458ac6ff40d62e47321f8681cc23d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::validateInstrOrdering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Asserts that instruction order numbers are marked invalid, or that they are in ascending order.</p>


<p>In asserts builds, this checks the numbering.</p>


<p>This is constant time if the ordering is invalid, and linear in the number of instructions if the ordering is valid. Callers should be careful not to call this in ways that make common operations O(n^2). For example, it takes O(n) time to assign order numbers to instructions, so the order should be validated no more than once after each ordering to ensure that transforms have the same algorithmic complexity when asserts are enabled as when they are disabled.</p>


<p>In non-asserts builds, it is defined as a no-op inline function in BasicBlock.h.</p>


<p>Declaration at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 1165 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>


<p>Referenced by <a href="#a38ae48e763a7081850f72cfe7695bcd5">invalidateOrders</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### AdjustBlockAddressRefCount() {#a5a1fd63db7827caba1d32a6505ae8997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicBlock::AdjustBlockAddressRefCount (int Amt)</td>
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

<p>Increment the internal refcount of the number of BlockAddresses referencing this <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> by <span class="doxyComputerOutput">Amt</span>.</p>


<p>This is almost always 0, sometimes one possibly, but almost never 2, and inconceivably 3 or more.</p>


<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getBasicBlockBits() {#a9a645b50d89a22637c8edb57bd0dcd3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlockBits llvm::BasicBlock::getBasicBlockBits ()</td>
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

<p>Safely reinterpret the subclass data bits to a more useful form.</p>

<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getInstList() {#ad5153e86482ada896764e15fa2c229e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InstListType &amp; llvm::BasicBlock::getInstList ()</td>
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

<p>Return the underlying instruction list container.</p>


<p>This is deliberately private because we have implemented an adequate set of functions to modify the list, including <a href="#af29f89e91dfd0ae90950f0b1bf49798d">BasicBlock::splice()</a>, <a href="#a018d5142c1a4469d9296a26a59fe2783">BasicBlock::erase()</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#afcd9d2ea284c4d90541291ff9c47d332">Instruction::insertInto()</a> etc.</p>


<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### getInstList() {#ab0ac16f503d0763b23aa9ebd5fa14ac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstListType &amp; llvm::BasicBlock::getInstList ()</td>
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



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### setBasicBlockBits() {#ab12b02ce0ec7bf2ebf95135e3e924a1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicBlock::setBasicBlockBits (BasicBlockBits AsBits)</td>
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

<p>Reinterpret our subclass bits and store them back into <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</p>

<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### setParent() {#ab1d222c91a3197e01b76a5d73cb58d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::setParent (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * parent)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### setValueSubclassData() {#a10611776c6385d9bb801c66f2d0d2ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BasicBlock::setValueSubclassData (unsigned short D)</td>
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

<p>Shadow <a href="/web-llvm/docs/api/classes/llvm/value/#aae37705b598ef612f698198dc33d6f65">Value::setValueSubclassData</a> with a private forwarding method so that any future subclasses cannot accidentally use it.</p>

<p>Definition at line 791 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### spliceDebugInfo() {#adabab3e391aec9a349e44767635cf2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::spliceDebugInfo (<a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * FromBB, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromBeginIt, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromEndIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform any debug-info specific maintenence for the given splice activity.</p>


<p>In the <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> debug-info representation, debug-info is not in instructions, and so it does not automatically move from one block to another.</p>


<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 825 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### spliceDebugInfoEmptyBlock() {#a8ca70ca9ca9d95b2368c0d96f2088c2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::spliceDebugInfoEmptyBlock (<a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * FromBB, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromBeginIt, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromEndIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dedicated function for splicing debug-info: when we have an empty splice (i.e.</p>


<p>zero instructions), the caller may still intend any debug-info in between the two "positions" to be spliced.</p>


<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 770 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

### spliceDebugInfoImpl() {#a8335e14738ac93e766958f1cd92a802a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BasicBlock::spliceDebugInfoImpl (<a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> ToIt, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * FromBB, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromBeginIt, <a href="#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> FromEndIt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>, definition at line 907 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsNewDbgInfoFormat {#ab571b8358a3a8b6db1327d06bdc5e9f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BasicBlock::IsNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag recording whether or not this block stores debug-info in the form of intrinsic instructions (false) or non-instruction records (true).</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a2373ebe62ac37c5f7d838e9ca92a7f2e">removeRedundantDbgInstrsUsingBackwardScan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#aceb315f70b8f69369df84d79274ef420">removeRedundantDbgInstrsUsingForwardScan</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a579e878e02e34bf9699e3d82da2bc070">removeUndefDbgAssignsFromEntryBlock</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### InstList {#adbc3eb171dc0b6709a64e74208e9a12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstListType llvm::BasicBlock::InstList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### Number {#af506f331e4060e97b4151e3bef031303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::BasicBlock::Number = -1u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Per-function unique number.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

### Parent {#adc87bddc1d4bf05e11935e5845943505}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* llvm::BasicBlock::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a1dfb5f698e35730791c0176a7c6c4b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BasicBlock::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a18dbfcb332af7515599ee795cf462843">llvm::Value::Value</a>.</p>

</div>
</div>

### Create() {#a4a5b798214be930cf8e133c032ba0129}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::BasicBlock::Create (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Parent=nullptr, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * InsertBefore=nullptr)</td>
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

<p>Creates a new <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<p>If the Parent parameter is specified, the basic block is automatically inserted at either the end of the function (if InsertBefore is 0), or before the specified basic block.</p>


<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>


<p>Reference <a href="#a4a5b798214be930cf8e133c032ba0129">Create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lljit-cpp-/#a02c5eacc8cf66436f8d0f722263b9494">anonymous{LLJIT.cpp}::addHelperAndWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#afca73617f8390579ca48fa10bf1c8edb">assureFPCallStub</a>, <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a101a4250b1fd5a230a766de2a14cb271">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildEntryThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#ac134215053dd186eca7bdd553eabc68c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildExitThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7990af2ca325a18286d49b694c835c98">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildGuestExitThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildPatchableThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a99b699ca919e40ac78708ea425fbfa98">convertToGuardPredicates</a>, <a href="#a4a5b798214be930cf8e133c032ba0129">Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a8120984c169f2ea17e785e7c6887702a">createAndInsertBasicBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#aea6556d942d972a777204187dd1600e5">anonymous{JMCInstrumenter.cpp}::createDefaultCheckFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a2bd6903bee5451ebaffd790ccf869664">llvm::MIRParserImpl::createDummyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a826f32ce82e4b2605718fedddba8a055">CreateFailBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#a6406a80ca9230c2d3e441f6975dba745">createFPFnStub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a7ba6b711f3cab802b6e29a1595d223bb">llvm::RandomIRBuilder::createFunctionDefinition</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#a4e632566b9002891ab9f5a108f3bd803">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a083d4808926043b15fdd4acbccc863d1">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a445fa52d77040bccb16bfea111234a2e">llvm::OpenMPIRBuilder::createLoopSkeleton</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#afb5a26693a2aa4ccb54923bf6a6e86d6">anonymous{OffloadWrapper.cpp}::createRegisterFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a256980e987af753b4c497757fad18000">llvm::createSanitizerCtor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a7aa8025f73f4e06135e6ba7083ad7aab">createUnreachableSwitchDefault</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a483af07ad9cee019751803fda2e04d1e">anonymous{OffloadWrapper.cpp}::createUnregisterFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a4aacbb0606ccb384dd6803bdf975eed7">anonymous{ExpandVariadics.cpp}::ExpandVariadics::defineVariadicWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5eeb42cfad58d947c605b1e21376e0b7">llvm::emitAMDGPUPrintfCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#af30ff2458bb283e423c1fc242a468579">findOrCreatePHIBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a0c8e1730578d5e4181a2bd1502328802">llvm::SanitizerStatReport::finish</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a32adc549fbc7c20005aabb9406435ff4">anonymous{InstrOrderFile.cpp}::InstrOrderFile::generateCodeSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/controlflowhoister/#ac2231bda91f0fdd79e476cb36e48d33b">anonymous{LICM.cpp}::ControlFlowHoister::getOrCreateHoistedBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#af8ebafc2930bf25dfa6887c4b5bc2c33">getStrlenWithNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/structs/anonymous-typesanitizer-cpp-/typesanitizer/#aa8094f0b4dd7316f56198f0e4760b9b4">anonymous{TypeSanitizer.cpp}::TypeSanitizer::instrumentGlobals</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#ga87e7cb1da004cffb6650565f835a27bd">LLVMAppendBasicBlockInContext</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#ga3b0b32f2bbe9597c55efb08df4b68814">LLVMCreateBasicBlockInContext</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluebasicblock/#gaa5642c34ff5104e4c8237fad31d2dca7">LLVMInsertBasicBlockInContext</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a557d913cc365524a47e73e4a8d468ab2">lowerIntrinsicToFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a2f68fd99d1f5c6c8326be57c2963306d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/inliner-cpp/#ad4950adb47ff6ab441d457a67d66ebec">makeFunctionBodyUnreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a853bb2a9a7292ce3445eb4138fb4bc52">llvm::orc::makeStub</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0af4594038f5cb46e7a4c86713520c95">markAliveBlocks</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#a77bc86cd5c15b83afe922fa7bbfe0f11">anonymous{LowerSwitch.cpp}::NewLeafBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ae1c543456cbefe674946cdb2e237ad14">processSwitch</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#ab6f626d7c6ac0566eb109ca95019549f">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegionNoRecurse</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85ee70791795fa2ddb07694182f783b2">llvm::splitBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#a06b5d6856fd9067830ab0477c0b13f31">anonymous{UnifyFunctionExitNodes.cpp}::unifyReturnBlocks</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#adb133e739b469808feb3635786aeaa01">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::unifyReturnBlockSet</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#af51c1104ae401b16bf1787ef769b356c">anonymous{UnifyFunctionExitNodes.cpp}::unifyUnreachableBlocks</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getSublistAccess() {#ab7709ac1c84ac480a6c0565d4b0182da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstListType BasicBlock::* llvm::BasicBlock::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *)</td>
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

<p>Returns a pointer to a member of the instruction list.</p>


<p>This is private on purpose, just like <span class="doxyComputerOutput">getInstList()</span>.</p>


<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/basicblock-h">BasicBlock.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/basicblock-cpp">BasicBlock.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
