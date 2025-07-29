---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/switchinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SwitchInst` Class

<p>Multiway switch. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SwitchInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">llvm/IR/Instructions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8176744ccd6a0ecd10728669e722b939">ConstCaseHandle</a> = <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl">CaseHandleImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a> = <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl">CaseIteratorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandle">CaseHandle</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2053d4ea2a08ab0fa9e873a1457b847c">ConstCaseIt</a> = <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl">CaseIteratorImpl</a>&lt; <a href="#a8176744ccd6a0ecd10728669e722b939">ConstCaseHandle</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87273cb892a8182f137567e6b631695e">Instruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0445cf60f889d4f69a29e68b2b1a2936">SwitchInst</a> (const SwitchInst &amp;SI)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9344efa85aaf15e7e89c768bac6a69b">SwitchInst</a> (Value *Value, BasicBlock *Default, unsigned NumCases, InsertPosition InsertBefore)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new switch instruction, specifying a value to switch on and a default destination. <a href="#af9344efa85aaf15e7e89c768bac6a69b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7348a81e01cb72a7cf05841bb2df6c21">operator delete</a> (void *Ptr)</td>
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

## Private Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59a95c4a823699029018bca5975d141">operator new</a> (size_t S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e97994f5718f301ab6da3ede42c590">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide fast operand accessors. <a href="#a36e97994f5718f301ab6da3ede42c590">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8214051c768ea9d437cac4b6d50c56">getCondition</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f1c68131a864a29455ce86c1d571b2">setCondition</a> (Value *V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0943fb5f399be0ac6ffbe8c977b619c8">getDefaultDest</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521c4f0cf16380c2dae3502ee3502283">defaultDestUndefined</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the default branch must result in immediate undefined behavior, false otherwise. <a href="#a521c4f0cf16380c2dae3502ee3502283">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa22bdae1cee3c836f2b4cf8307fc7598">setDefaultDest</a> (BasicBlock *DefaultCase)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab009e4ea0d53969a9f6fb36e3da14517">getNumCases</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of 'cases' in this switch instruction, excluding the default case. <a href="#ab009e4ea0d53969a9f6fb36e3da14517">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae69c15ce940c41719cb96209e113a26e">case_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a read/write iterator that points to the first case in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>. <a href="#ae69c15ce940c41719cb96209e113a26e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2053d4ea2a08ab0fa9e873a1457b847c">ConstCaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e476ce1e4324b10ab353baf6da3c187">case_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a read-only iterator that points to the first case in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>. <a href="#a4e476ce1e4324b10ab353baf6da3c187">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a read/write iterator that points one past the last in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>. <a href="#a219f2a3514d904d05dc8003a4ee5d291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2053d4ea2a08ab0fa9e873a1457b847c">ConstCaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa4d2e46b7920aaa3a472cde8a5b38c7">case_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a read-only iterator that points one past the last in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>. <a href="#afa4d2e46b7920aaa3a472cde8a5b38c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef781db858f88845051c0f2d7310ab07">cases</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteration adapter for range-for loops. <a href="#aef781db858f88845051c0f2d7310ab07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a2053d4ea2a08ab0fa9e873a1457b847c">ConstCaseIt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55d2e34cc55c7f31a3513dbc198464a7">cases</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> iteration adapter for range-for loops. <a href="#a55d2e34cc55c7f31a3513dbc198464a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96a201f56500af4dd70b4169f140cb4c">case_default</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns an iterator that points to the default case. <a href="#a96a201f56500af4dd70b4169f140cb4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2053d4ea2a08ab0fa9e873a1457b847c">ConstCaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae436e4ec6f53b7de4d34d3b4d0daf1a6">case_default</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3a1537c850f63ce48bcf45694cde73f">findCaseValue</a> (const ConstantInt *C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Search all of the case values for the specified constant. <a href="#ad3a1537c850f63ce48bcf45694cde73f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2053d4ea2a08ab0fa9e873a1457b847c">ConstCaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311f214290e59361aa8481f858970609">findCaseValue</a> (const ConstantInt *C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e0388218a0b4d2e1e5f210e0fbb1e86">findCaseDest</a> (BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finds the unique case value for a given successor. <a href="#a7e0388218a0b4d2e1e5f210e0fbb1e86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62abc2475d09c01d583ba24a487898fd">addCase</a> (ConstantInt *OnVal, BasicBlock *Dest)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an entry to the switch instruction. <a href="#a62abc2475d09c01d583ba24a487898fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8bc09200ccc3617a5cb37e0d2f23ff">removeCase</a> (CaseIt I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method removes the specified case and its successor from the switch instruction. <a href="#aff8bc09200ccc3617a5cb37e0d2f23ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90d8c814f871c58dbda5dccce5c4110e">getNumSuccessors</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f79d54afada3c9005d24ab8743a9d6">getSuccessor</a> (unsigned idx) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc7899c254935205ca29b6bd7baa926">setSuccessor</a> (unsigned idx, BasicBlock *NewSucc)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23a180bb0cc12def1647389e47281c73">cloneImpl</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669631af5ffe1ed8e9c36a52cc8a26a5">init</a> (Value *Value, BasicBlock *Default, unsigned NumReserved)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd06990b7a8e6f79dfd75f40e538b827">growOperands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>growOperands - grow operands - This grows the operand list in response to a push_back style of operation. <a href="#afd06990b7a8e6f79dfd75f40e538b827">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a667e1456dfd73b2452a054b3820b814b">ReservedSpace</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1416226bed5e92acb74aebe8e20f5a">Create</a> (Value *Value, BasicBlock *Default, unsigned NumCases, InsertPosition InsertBefore=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8ab9b80609fc4686f1b42ecdfc5e210">classof</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b0490d0473556dd80309af75ce9c01e">classof</a> (const Value *V)</td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e595ea56b22d7c3289e8df608b635d1">DefaultPseudoIndex</a> = static_cast&lt;unsigned&gt;(~0L-1)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/user/hungoffoperandsallocmarker">HungOffOperandsAllocMarker</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80c4a6353da2b60dc15a1f6c6aa37e2">AllocMarker</a> {}</td>
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

<p>Multiway switch.</p>

<p>Definition at line 3154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CaseIt {#a723af715edeaedc8ed1048f8c235ce9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SwitchInst::CaseIt =  CaseIteratorImpl&lt;CaseHandle&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### ConstCaseHandle {#a8176744ccd6a0ecd10728669e722b939}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SwitchInst::ConstCaseHandle = 
      CaseHandleImpl&lt;const SwitchInst, const ConstantInt, const BasicBlock&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### ConstCaseIt {#a2053d4ea2a08ab0fa9e873a1457b847c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::SwitchInst::ConstCaseIt =  CaseIteratorImpl&lt;ConstCaseHandle&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### Instruction {#a87273cb892a8182f137567e6b631695e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a></td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a23a180bb0cc12def1647389e47281c73">cloneImpl</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#ae8ab9b80609fc4686f1b42ecdfc5e210">classof</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### SwitchInst() {#a0445cf60f889d4f69a29e68b2b1a2936}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwitchInst::SwitchInst (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3996 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### SwitchInst() {#af9344efa85aaf15e7e89c768bac6a69b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwitchInst::SwitchInst (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Value, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Default, unsigned NumCases, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new switch instruction, specifying a value to switch on and a default destination.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> ctor - Create a new switch instruction, specifying a value to switch on and a default destination.</p>


<p>The number of additional cases can be specified here to make memory allocation more efficient. This constructor can also auto-insert before another instruction.</p>


<p>The number of additional cases can be specified here to make memory allocation more efficient. This constructor can also autoinsert before another instruction.</p>


<p>Declaration at line 3169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3989 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator delete() {#a7348a81e01cb72a7cf05841bb2df6c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwitchInst::operator delete (void * Ptr)</td>
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



<p>Definition at line 3185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Operators

### operator new() {#ae59a95c4a823699029018bca5975d141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * llvm::SwitchInst::operator new (size_t S)</td>
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



<p>Definition at line 3173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCase() {#a62abc2475d09c01d583ba24a487898fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwitchInst::addCase (<a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * OnVal, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Dest)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an entry to the switch instruction.</p>


<p>addCase - Add an entry to the switch instruction...</p>


<p>Note: This action invalidates <a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end()</a>. Old <a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end()</a> iterator will point to the added case.</p>


<p>Declaration at line 3460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4011 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#ab009e4ea0d53969a9f6fb36e3da14517">getNumCases</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a715e8009737f71c4b3d2ea7d2abc33c4">llvm::User::setNumHungOffUseOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandle/#ade327bd05bcf154647ea34eed5ddf354">llvm::SwitchInst::CaseHandle::setSuccessor</a> and <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandle/#ab20138a23cdfbc6a42f6341e55b78005">llvm::SwitchInst::CaseHandle::setValue</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#af36172c1f538b7305b44760997d5a3c2">llvm::OpenMPIRBuilder::createSections</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a> and <a href="/web-llvm/docs/api/classes/llvm/spirvmergeregionexittargets/#ab6f626d7c6ac0566eb109ca95019549f">llvm::SPIRVMergeRegionExitTargets::runOnConvergenceRegionNoRecurse</a>.</p>

</div>
</div>

### case\_begin() {#ae69c15ce940c41719cb96209e113a26e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseIt llvm::SwitchInst::case_begin ()</td>
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

<p>Returns a read/write iterator that points to the first case in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>.</p>

<p>Definition at line 3373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#aef781db858f88845051c0f2d7310ab07">cases</a> and <a href="#a55d2e34cc55c7f31a3513dbc198464a7">cases</a>.</p>

</div>
</div>

### case\_begin() {#a4e476ce1e4324b10ab353baf6da3c187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstCaseIt llvm::SwitchInst::case_begin ()</td>
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

<p>Returns a read-only iterator that points to the first case in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>.</p>

<p>Definition at line 3379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### case\_default() {#a96a201f56500af4dd70b4169f140cb4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseIt llvm::SwitchInst::case_default ()</td>
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

<p>Returns an iterator that points to the default case.</p>


<p>Note: this iterator allows to resolve successor only. Attempt to resolve case value causes an assertion. Also note, that increment and decrement also causes an assertion and makes iterator invalid.</p>


<p>Definition at line 3410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#a5e595ea56b22d7c3289e8df608b635d1">DefaultPseudoIndex</a>.</p>


<p>Referenced by <a href="#a311f214290e59361aa8481f858970609">findCaseValue</a>.</p>

</div>
</div>

### case\_default() {#ae436e4ec6f53b7de4d34d3b4d0daf1a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstCaseIt llvm::SwitchInst::case_default ()</td>
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



<p>Definition at line 3413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#a5e595ea56b22d7c3289e8df608b635d1">DefaultPseudoIndex</a>.</p>

</div>
</div>

### case\_end() {#a219f2a3514d904d05dc8003a4ee5d291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseIt llvm::SwitchInst::case_end ()</td>
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

<p>Returns a read/write iterator that points one past the last in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>.</p>

<p>Definition at line 3385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#ab009e4ea0d53969a9f6fb36e3da14517">getNumCases</a>.</p>


<p>Referenced by <a href="#aef781db858f88845051c0f2d7310ab07">cases</a>, <a href="#a55d2e34cc55c7f31a3513dbc198464a7">cases</a> and <a href="#a311f214290e59361aa8481f858970609">findCaseValue</a>.</p>

</div>
</div>

### case\_end() {#afa4d2e46b7920aaa3a472cde8a5b38c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstCaseIt llvm::SwitchInst::case_end ()</td>
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

<p>Returns a read-only iterator that points one past the last in the <a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a>.</p>

<p>Definition at line 3391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="#ab009e4ea0d53969a9f6fb36e3da14517">getNumCases</a>.</p>

</div>
</div>

### cases() {#aef781db858f88845051c0f2d7310ab07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; CaseIt &gt; llvm::SwitchInst::cases ()</td>
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

<p>Iteration adapter for range-for loops.</p>

<p>Definition at line 3396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#ae69c15ce940c41719cb96209e113a26e">case_begin</a>, <a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a7e0388218a0b4d2e1e5f210e0fbb1e86">findCaseDest</a>, <a href="#a311f214290e59361aa8481f858970609">findCaseValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### cases() {#a55d2e34cc55c7f31a3513dbc198464a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; ConstCaseIt &gt; llvm::SwitchInst::cases ()</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> iteration adapter for range-for loops.</p>

<p>Definition at line 3401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#ae69c15ce940c41719cb96209e113a26e">case_begin</a>, <a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a36e97994f5718f301ab6da3ede42c590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SwitchInst::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide fast operand accessors.</p>

<p>Definition at line 3345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

### defaultDestUndefined() {#a521c4f0cf16380c2dae3502ee3502283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwitchInst::defaultDestUndefined ()</td>
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

<p>Returns true if the default branch must result in immediate undefined behavior, false otherwise.</p>

<p>Definition at line 3357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="#a0943fb5f399be0ac6ffbe8c977b619c8">getDefaultDest</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### findCaseDest() {#a7e0388218a0b4d2e1e5f210e0fbb1e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantInt * llvm::SwitchInst::findCaseDest (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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

<p>Finds the unique case value for a given successor.</p>


<p>Returns null if the successor is not found, not unique, or is the default case.</p>


<p>Definition at line 3438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#aef781db858f88845051c0f2d7310ab07">cases</a> and <a href="#a0943fb5f399be0ac6ffbe8c977b619c8">getDefaultDest</a>.</p>

</div>
</div>

### findCaseValue() {#ad3a1537c850f63ce48bcf45694cde73f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CaseIt llvm::SwitchInst::findCaseValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * C)</td>
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

<p>Search all of the case values for the specified constant.</p>


<p>If it is explicitly handled, return the case iterator of it, otherwise return default case iterator to indicate that it is handled by the default handler.</p>


<p>Definition at line 3421 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#ad3a1537c850f63ce48bcf45694cde73f">findCaseValue</a>.</p>


<p>Referenced by <a href="#ad3a1537c850f63ce48bcf45694cde73f">findCaseValue</a>.</p>

</div>
</div>

### findCaseValue() {#a311f214290e59361aa8481f858970609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstCaseIt llvm::SwitchInst::findCaseValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantint">ConstantInt</a> * C)</td>
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



<p>Definition at line 3426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a96a201f56500af4dd70b4169f140cb4c">case_default</a>, <a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end</a>, <a href="#aef781db858f88845051c0f2d7310ab07">cases</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#ad2b4cf1b26b0b142b243bcdcf300eafa">llvm::SwitchInst::CaseHandleImpl&lt; SwitchInstT, ConstantIntT, BasicBlockT &gt;::getCaseValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getCondition() {#add8214051c768ea9d437cac4b6d50c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::SwitchInst::getCondition ()</td>
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



<p>Definition at line 3348 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a79a12e82100c16946dd61381bf59e262">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitSwitchInst</a>.</p>

</div>
</div>

### getDefaultDest() {#a0943fb5f399be0ac6ffbe8c977b619c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::SwitchInst::getDefaultDest ()</td>
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



<p>Definition at line 3351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="#a521c4f0cf16380c2dae3502ee3502283">defaultDestUndefined</a>, <a href="#a7e0388218a0b4d2e1e5f210e0fbb1e86">findCaseDest</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>.</p>

</div>
</div>

### getNumCases() {#ab009e4ea0d53969a9f6fb36e3da14517}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwitchInst::getNumCases ()</td>
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

<p>Return the number of 'cases' in this switch instruction, excluding the default case.</p>

<p>Definition at line 3367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="#a62abc2475d09c01d583ba24a487898fd">addCase</a>, <a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end</a>, <a href="#afa4d2e46b7920aaa3a472cde8a5b38c7">case_end</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#aa832438a6843b75f7d0ef2cc563153f6">llvm::SwitchInst::CaseHandleImpl&lt; const SwitchInst, const ConstantInt, const BasicBlock &gt;::getCaseSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#ad2b4cf1b26b0b142b243bcdcf300eafa">llvm::SwitchInst::CaseHandleImpl&lt; const SwitchInst, const ConstantInt, const BasicBlock &gt;::getCaseValue</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#a80c8a3151e9ef04b1595e222bdfe1cf9">llvm::SwitchInst::CaseHandleImpl&lt; const SwitchInst, const ConstantInt, const BasicBlock &gt;::getSuccessorIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandle/#ab20138a23cdfbc6a42f6341e55b78005">llvm::SwitchInst::CaseHandle::setValue</a>.</p>

</div>
</div>

### getNumSuccessors() {#a90d8c814f871c58dbda5dccce5c4110e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwitchInst::getNumSuccessors ()</td>
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



<p>Definition at line 3471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl/#ae5a39d260adc65f8646df2830a66e262">llvm::SwitchInst::CaseIteratorImpl&lt; CaseHandle &gt;::fromSuccessorIndex</a>, <a href="#a30f79d54afada3c9005d24ab8743a9d6">getSuccessor</a> and <a href="#a7fc7899c254935205ca29b6bd7baa926">setSuccessor</a>.</p>

</div>
</div>

### getSuccessor() {#a30f79d54afada3c9005d24ab8743a9d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::SwitchInst::getSuccessor (unsigned idx)</td>
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



<p>Definition at line 3472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a90d8c814f871c58dbda5dccce5c4110e">getNumSuccessors</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

### removeCase() {#aff8bc09200ccc3617a5cb37e0d2f23ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwitchInst::CaseIt SwitchInst::removeCase (<a href="#a723af715edeaedc8ed1048f8c235ce9e">CaseIt</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method removes the specified case and its successor from the switch instruction.</p>


<p>removeCase - This method removes the specified case and its successor from the switch instruction.</p>


<p>Note that this operation may reorder the remaining cases at index idx and above. Note: This action invalidates iterators for all cases following the one removed, including the <a href="#a219f2a3514d904d05dc8003a4ee5d291">case_end()</a> iterator. It returns an iterator for the next case.</p>


<p>Declaration at line 3469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4026 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a024c7e10ce431a93ffdb4e5e6401e0be">llvm::User::getOperandList</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/use/#a40360b4fa7b8e6920a68e5a8a0814f1f">llvm::Use::set</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a715e8009737f71c4b3d2ea7d2abc33c4">llvm::User::setNumHungOffUseOperands</a>.</p>

</div>
</div>

### setCondition() {#a48f1c68131a864a29455ce86c1d571b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwitchInst::setCondition (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 3349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>

</div>
</div>

### setDefaultDest() {#aa22bdae1cee3c836f2b4cf8307fc7598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwitchInst::setDefaultDest (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * DefaultCase)</td>
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



<p>Definition at line 3361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0ee1f18526ee78ef18612b6a86dc16fc">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAllocas</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

### setSuccessor() {#a7fc7899c254935205ca29b6bd7baa926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::SwitchInst::setSuccessor (unsigned idx, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewSucc)</td>
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



<p>Definition at line 3476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a>, <a href="#a90d8c814f871c58dbda5dccce5c4110e">getNumSuccessors</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### cloneImpl() {#a23a180bb0cc12def1647389e47281c73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwitchInst * SwitchInst::cloneImpl ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4426 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Referenced by <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### growOperands() {#afd06990b7a8e6f79dfd75f40e538b827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwitchInst::growOperands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>growOperands - grow operands - This grows the operand list in response to a push_back style of operation.</p>


<p>This grows the number of ops by 3 times.</p>


<p>Declaration at line 3176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 4051 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### init() {#a669631af5ffe1ed8e9c36a52cc8a26a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SwitchInst::init (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Value, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Default, unsigned NumReserved)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 3175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>, definition at line 3975 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ReservedSpace {#a667e1456dfd73b2452a054b3820b814b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SwitchInst::ReservedSpace</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ae8ab9b80609fc4686f1b42ecdfc5e210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwitchInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 3482 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#a87273cb892a8182f137567e6b631695e">Instruction</a>.</p>


<p>Referenced by <a href="#a8b0490d0473556dd80309af75ce9c01e">classof</a>.</p>

</div>
</div>

### classof() {#a8b0490d0473556dd80309af75ce9c01e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SwitchInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 3485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ae8ab9b80609fc4686f1b42ecdfc5e210">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### Create() {#a3c1416226bed5e92acb74aebe8e20f5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwitchInst * llvm::SwitchInst::Create (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Value, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * Default, unsigned NumCases, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Definition at line 3338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/instruction/#af10fa975001cd000bc6aaa88267d970f">llvm::Instruction::BasicBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a8b123015de85b2f41b0deda2aeaad9d3">llvm::IRBuilderBase::CreateSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#ae86fef7fc5831c2514bff95bdf784d09">createSwitchStatement</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### DefaultPseudoIndex {#a5e595ea56b22d7c3289e8df608b635d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::SwitchInst::DefaultPseudoIndex = static_cast&lt;unsigned&gt;(~0L-1)</td>
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



<p>Definition at line 3188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>


<p>Referenced by <a href="#a96a201f56500af4dd70b4169f140cb4c">case_default</a>, <a href="#ae436e4ec6f53b7de4d34d3b4d0daf1a6">case_default</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/caseiteratorimpl/#ae5a39d260adc65f8646df2830a66e262">llvm::SwitchInst::CaseIteratorImpl&lt; CaseHandle &gt;::fromSuccessorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#aa832438a6843b75f7d0ef2cc563153f6">llvm::SwitchInst::CaseHandleImpl&lt; const SwitchInst, const ConstantInt, const BasicBlock &gt;::getCaseSuccessor</a> and <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandleimpl/#a80c8a3151e9ef04b1595e222bdfe1cf9">llvm::SwitchInst::CaseHandleImpl&lt; const SwitchInst, const ConstantInt, const BasicBlock &gt;::getSuccessorIndex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### AllocMarker {#aa80c4a6353da2b60dc15a1f6c6aa37e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HungOffOperandsAllocMarker llvm::SwitchInst::AllocMarker {}</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 3155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instructions-h">Instructions.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
