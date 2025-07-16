---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmccorevaluebasicblock
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The Basic Block Reference

<p>A basic block represents a single entry single exit section of code. <a href="#details">More...</a></p>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga444a4024b92a990e9ab311c336e74633">LLVMBasicBlockAsValue</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert a basic block instance to a value type. <a href="#ga444a4024b92a990e9ab311c336e74633">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga209de0bceb13179a973c6a45211617bd">LLVMBool</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gab57c996ff697ef40966432055ae47a4e">LLVMValueIsBasicBlock</a> (LLVMValueRef Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether an <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> is itself a basic block. <a href="#gab57c996ff697ef40966432055ae47a4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga339307355e5bb84d6a110139dada75c9">LLVMValueAsBasicBlock</a> (LLVMValueRef Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert an <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> to an <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> instance. <a href="#ga339307355e5bb84d6a110139dada75c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae0d2617602255bd2f490973d13e15325">LLVMGetBasicBlockName</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the string name of a basic block. <a href="#gae0d2617602255bd2f490973d13e15325">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga94bcbe957389c2c2219d6a02e72691ef">LLVMGetBasicBlockParent</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the function to which a basic block belongs. <a href="#ga94bcbe957389c2c2219d6a02e72691ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga754e45f69f4b784b658d9e379943f354">LLVMGetBasicBlockTerminator</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the terminator instruction for a basic block. <a href="#ga754e45f69f4b784b658d9e379943f354">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga767498a2a7d01498ce302e8a66da2b61">LLVMCountBasicBlocks</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the number of basic blocks in a function. <a href="#ga767498a2a7d01498ce302e8a66da2b61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga699b8756d996785085a48a703932add3">LLVMGetBasicBlocks</a> (LLVMValueRef Fn, LLVMBasicBlockRef *BasicBlocks)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain all of the basic blocks in a function. <a href="#ga699b8756d996785085a48a703932add3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga27930a1f6ef942a6d6b70a880af24f14">LLVMGetFirstBasicBlock</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the first basic block in a function. <a href="#ga27930a1f6ef942a6d6b70a880af24f14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga84bd6522485aa27bb5581aabc13493b2">LLVMGetLastBasicBlock</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the last basic block in a function. <a href="#ga84bd6522485aa27bb5581aabc13493b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga07967d9c5eb0aa3dd8c2f0a0068ae3aa">LLVMGetNextBasicBlock</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance a basic block iterator. <a href="#ga07967d9c5eb0aa3dd8c2f0a0068ae3aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf9c5b1e85d737e66cd78d49cdfdec92b">LLVMGetPreviousBasicBlock</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Go backwards in a basic block iterator. <a href="#gaf9c5b1e85d737e66cd78d49cdfdec92b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaade17b8c9f551f9779de4da8f543b131">LLVMGetEntryBasicBlock</a> (LLVMValueRef Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the basic block that corresponds to the entry point of a function. <a href="#gaade17b8c9f551f9779de4da8f543b131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga685b3eca9432cb6b80cc96dd54d025a3">LLVMInsertExistingBasicBlockAfterInsertBlock</a> (LLVMBuilderRef Builder, LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert the given basic block after the insertion point of the given builder. <a href="#ga685b3eca9432cb6b80cc96dd54d025a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga07e972a7d6bb4571f317ba0eeab51585">LLVMAppendExistingBasicBlock</a> (LLVMValueRef Fn, LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the given basic block to the basic block list of the given function. <a href="#ga07e972a7d6bb4571f317ba0eeab51585">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3b0b32f2bbe9597c55efb08df4b68814">LLVMCreateBasicBlockInContext</a> (LLVMContextRef C, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a new basic block without inserting it into a function. <a href="#ga3b0b32f2bbe9597c55efb08df4b68814">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga87e7cb1da004cffb6650565f835a27bd">LLVMAppendBasicBlockInContext</a> (LLVMContextRef C, LLVMValueRef Fn, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append a basic block to the end of a function. <a href="#ga87e7cb1da004cffb6650565f835a27bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga74f2ff28344ef72a8206b9c5925be543">LLVMAppendBasicBlock</a> (LLVMValueRef Fn, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append a basic block to the end of a function using the global context. <a href="#ga74f2ff28344ef72a8206b9c5925be543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa5642c34ff5104e4c8237fad31d2dca7">LLVMInsertBasicBlockInContext</a> (LLVMContextRef C, LLVMBasicBlockRef BB, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a basic block in a function before another basic block. <a href="#gaa5642c34ff5104e4c8237fad31d2dca7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa97a2f5faf832606c543321ea6b3fe88">LLVMInsertBasicBlock</a> (LLVMBasicBlockRef InsertBeforeBB, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a basic block in a function using the global context. <a href="#gaa97a2f5faf832606c543321ea6b3fe88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga174c942f924efd2dac593073e79f694c">LLVMDeleteBasicBlock</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a basic block from a function and delete it. <a href="#ga174c942f924efd2dac593073e79f694c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3e185c6526550e877c0bc8dd88c612d1">LLVMRemoveBasicBlockFromParent</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove a basic block from a function. <a href="#ga3e185c6526550e877c0bc8dd88c612d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga41c95b5a67bbe12b072012684f21327d">LLVMMoveBasicBlockBefore</a> (LLVMBasicBlockRef BB, LLVMBasicBlockRef MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move a basic block to before another one. <a href="#ga41c95b5a67bbe12b072012684f21327d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga77c7d5fecec83d503c6c52edd8f93779">LLVMMoveBasicBlockAfter</a> (LLVMBasicBlockRef BB, LLVMBasicBlockRef MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move a basic block to after another one. <a href="#ga77c7d5fecec83d503c6c52edd8f93779">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga9baf824cd325ad211027b23fce8a7494">LLVMGetFirstInstruction</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the first instruction in a basic block. <a href="#ga9baf824cd325ad211027b23fce8a7494">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa0bb2c95802d06bf94f4c55e61fc3477">LLVMGetLastInstruction</a> (LLVMBasicBlockRef BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Obtain the last instruction in a basic block. <a href="#gaa0bb2c95802d06bf94f4c55e61fc3477">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A basic block represents a single entry single exit section of code.</p>


<p>Basic blocks contain a list of instructions which form the body of the block.</p>


<p>Basic blocks belong to functions. They have the type of label.</p>


<p>Basic blocks are themselves values. However, the C API models them as <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock">llvm::BasicBlock</a></p></dd>
</dl>


<div class="doxySectionDef">

## Functions

### LLVMAppendBasicBlock() {#ga74f2ff28344ef72a8206b9c5925be543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMAppendBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append a basic block to the end of a function using the global context.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create()</a></p></dd>
</dl>


<p>Declaration at line 3469 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2867 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="#ga87e7cb1da004cffb6650565f835a27bd">LLVMAppendBasicBlockInContext</a> and <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga0055cde9a9b2497b332d639d8844a810">LLVMGetGlobalContext</a>.</p>

</div>
</div>

### LLVMAppendBasicBlockInContext() {#ga87e7cb1da004cffb6650565f835a27bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMAppendBasicBlockInContext (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> C, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append a basic block to the end of a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create()</a></p></dd>
</dl>


<p>Declaration at line 3459 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2861 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>


<p>Referenced by <a href="#ga74f2ff28344ef72a8206b9c5925be543">LLVMAppendBasicBlock</a>.</p>

</div>
</div>

### LLVMAppendExistingBasicBlock() {#ga07e972a7d6bb4571f317ba0eeab51585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMAppendExistingBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Append the given basic block to the basic block list of the given function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a319c1a7cbadd9e30ae93fe737aafcdad">llvm::Function::BasicBlockListType::push_back()</a></p></dd>
</dl>


<p>Declaration at line 3443 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2856 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMBasicBlockAsValue() {#ga444a4024b92a990e9ab311c336e74633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMBasicBlockAsValue (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert a basic block instance to a value type.</p>

<p>Declaration at line 3340 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2773 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMCountBasicBlocks() {#ga767498a2a7d01498ce302e8a66da2b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned LLVMCountBasicBlocks (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the number of basic blocks in a function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Fn</td>
<td class="doxyParamItemDescription"><p>Function value to operate on.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 3381 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2797 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMCreateBasicBlockInContext() {#ga3b0b32f2bbe9597c55efb08df4b68814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMCreateBasicBlockInContext (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a new basic block without inserting it into a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create()</a></p></dd>
</dl>


<p>Declaration at line 3451 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2843 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMDeleteBasicBlock() {#ga174c942f924efd2dac593073e79f694c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMDeleteBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a basic block from a function and delete it.</p>


<p>This deletes the basic block from its containing function and deletes the basic block itself.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4c464ef563b721bcb04c8a998c30cabd">llvm::BasicBlock::eraseFromParent()</a></p></dd>
</dl>


<p>Declaration at line 3499 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2883 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetBasicBlockName() {#gae0d2617602255bd2f490973d13e15325}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMGetBasicBlockName (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the string name of a basic block.</p>

<p>Declaration at line 3355 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2785 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMGetBasicBlockParent() {#ga94bcbe957389c2c2219d6a02e72691ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetBasicBlockParent (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the function to which a basic block belongs.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a8418f5e52a18c1b1ab5860eb591fd325">llvm::BasicBlock::getParent()</a></p></dd>
</dl>


<p>Declaration at line 3362 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2789 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a1b8850f1ed44c12bc3501175a71c251c">getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetBasicBlocks() {#ga699b8756d996785085a48a703932add3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMGetBasicBlocks (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> * BasicBlocks)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain all of the basic blocks in a function.</p>


<p>This operates on a function value. The BasicBlocks parameter is a pointer to a pre-allocated array of <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> of at least <a href="#ga767498a2a7d01498ce302e8a66da2b61">LLVMCountBasicBlocks()</a> in length. This array is populated with <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> instances.</p>


<p>Declaration at line 3391 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2801 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetBasicBlockTerminator() {#ga754e45f69f4b784b658d9e379943f354}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetBasicBlockTerminator (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the terminator instruction for a basic block.</p>


<p>If the basic block does not have a terminator (it is not well-formed if it doesn't), then NULL is returned.</p>


<p>The returned <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> corresponds to an <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a>.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#aaf87930bfa1c4483b0d94ce7b8622a91">llvm::BasicBlock::getTerminator()</a></p></dd>
</dl>


<p>Declaration at line 3374 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2793 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetEntryBasicBlock() {#gaade17b8c9f551f9779de4da8f543b131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMGetEntryBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the basic block that corresponds to the entry point of a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a0da3ad33bda3df0fa6c10d91d3815626">llvm::Function::getEntryBlock()</a></p></dd>
</dl>


<p>Declaration at line 3426 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2807 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetFirstBasicBlock() {#ga27930a1f6ef942a6d6b70a880af24f14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMGetFirstBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the first basic block in a function.</p>


<p>The returned basic block can be used as an iterator. You will likely eventually call into <a href="#ga07967d9c5eb0aa3dd8c2f0a0068ae3aa">LLVMGetNextBasicBlock()</a> with it.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#a88a5e60837674780a9d812d661897ac5">llvm::Function::begin()</a></p></dd>
</dl>


<p>Declaration at line 3401 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2811 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetFirstInstruction() {#ga9baf824cd325ad211027b23fce8a7494}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetFirstInstruction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the first instruction in a basic block.</p>


<p>The returned <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> corresponds to a <a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> instance.</p>


<p>Declaration at line 3531 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2905 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetLastBasicBlock() {#ga84bd6522485aa27bb5581aabc13493b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMGetLastBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Fn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the last basic block in a function.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/function/#ae4ca2261b8b901e415fda7feac5051ea">llvm::Function::end()</a></p></dd>
</dl>


<p>Declaration at line 3408 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2819 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetLastInstruction() {#gaa0bb2c95802d06bf94f4c55e61fc3477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMValueRef LLVMGetLastInstruction (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Obtain the last instruction in a basic block.</p>


<p>The returned <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> corresponds to an LLVM:Instruction.</p>


<p>Declaration at line 3538 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2913 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetNextBasicBlock() {#ga07967d9c5eb0aa3dd8c2f0a0068ae3aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMGetNextBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance a basic block iterator.</p>

<p>Declaration at line 3413 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2827 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMGetPreviousBasicBlock() {#gaf9c5b1e85d737e66cd78d49cdfdec92b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMGetPreviousBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Go backwards in a basic block iterator.</p>

<p>Declaration at line 3418 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2835 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMInsertBasicBlock() {#gaa97a2f5faf832606c543321ea6b3fe88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMInsertBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> InsertBeforeBB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a basic block in a function using the global context.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create()</a></p></dd>
</dl>


<p>Declaration at line 3488 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2878 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga0055cde9a9b2497b332d639d8844a810">LLVMGetGlobalContext</a> and <a href="#gaa5642c34ff5104e4c8237fad31d2dca7">LLVMInsertBasicBlockInContext</a>.</p>

</div>
</div>

### LLVMInsertBasicBlockInContext() {#gaa5642c34ff5104e4c8237fad31d2dca7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMInsertBasicBlockInContext (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9c43e01525516ff6b4feab5166c5b1da">LLVMContextRef</a> C, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a basic block in a function before another basic block.</p>


<p>The function to add to is determined by the function of the passed basic block.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create()</a></p></dd>
</dl>


<p>Declaration at line 3479 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2871 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>


<p>Referenced by <a href="#gaa97a2f5faf832606c543321ea6b3fe88">LLVMInsertBasicBlock</a>.</p>

</div>
</div>

### LLVMInsertExistingBasicBlockAfterInsertBlock() {#ga685b3eca9432cb6b80cc96dd54d025a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMInsertExistingBasicBlockAfterInsertBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab13eecdec39366f9974f865d68011775">LLVMBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert the given basic block after the insertion point of the given builder.</p>


<p>The insertion point must be valid.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#aabf8d16970751590d6087ea1a0241694">llvm::Function::BasicBlockListType::insertAfter()</a></p></dd>
</dl>


<p>Declaration at line 3435 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2848 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a80069e261aca5e34cffcc2ef67cfa29b">llvm::BasicBlock::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#aaab8110aafc070c83bc701b13d2260df">llvm::Function::insert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMMoveBasicBlockAfter() {#ga77c7d5fecec83d503c6c52edd8f93779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMMoveBasicBlockAfter (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move a basic block to after another one.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a507bb47fc498540c91fec0bf95c25907">llvm::BasicBlock::moveAfter()</a></p></dd>
</dl>


<p>Declaration at line 3523 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2895 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMMoveBasicBlockBefore() {#ga41c95b5a67bbe12b072012684f21327d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMMoveBasicBlockBefore (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move a basic block to before another one.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#ac1fd6437bbfce263b87f01767d950ce5">llvm::BasicBlock::moveBefore()</a></p></dd>
</dl>


<p>Declaration at line 3516 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2891 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMRemoveBasicBlockFromParent() {#ga3e185c6526550e877c0bc8dd88c612d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMRemoveBasicBlockFromParent (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove a basic block from a function.</p>


<p>This deletes the basic block from its containing function but keep the basic block alive.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a3be34ea0f6bb2f1c928e200c4a8fa5ef">llvm::BasicBlock::removeFromParent()</a></p></dd>
</dl>


<p>Declaration at line 3509 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2887 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMValueAsBasicBlock() {#ga339307355e5bb84d6a110139dada75c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBasicBlockRef LLVMValueAsBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convert an <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> to an <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#gab57bd16a0147aad5c492a0d97e0df8a9">LLVMBasicBlockRef</a> instance.</p>

<p>Declaration at line 3350 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2781 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMValueIsBasicBlock() {#gab57c996ff697ef40966432055ae47a4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMBool LLVMValueIsBasicBlock (<a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether an <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga113ce952344691b8304a43a314f8be17">LLVMValueRef</a> is itself a basic block.</p>

<p>Declaration at line 3345 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/core-h">Core.h</a>, definition at line 2777 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/core-cpp">Core.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
