---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/user
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `User` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user">sandboxir::User</a> has operands. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::User { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">llvm/SandboxIR/User.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A SandboxIR <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> has users. This is the base class. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant">Constant</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user">sandboxir::User</a> with operands, opcode and linked with previous/next instructions in an instruction list. <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/operator">Operator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a899e62d7db86984354bbdaa96067f91e">op_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operanduseiterator">OperandUseIterator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb7da57c57a24be71816721887dc455">const_op_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operanduseiterator">OperandUseIterator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea441faf71d458b974c3add03e0fd179">op_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a899e62d7db86984354bbdaa96067f91e">op_iterator</a> &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc18fd33516ae7ad56c8f337fc90cc0d">const_op_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a3fb7da57c57a24be71816721887dc455">const_op_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a834efd0135e81675280d5ba828d263">OperandUseIterator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64f0b50a2c1ec72bf69dbde8bd85f0c5">Use::getOperandNo</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed798e20a38c7c32351becc11f61f755">User</a> (ClassID ID, llvm::Value *V, Context &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a899e62d7db86984354bbdaa96067f91e">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00acedbe40caf585acae6bf934765a72">op_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a899e62d7db86984354bbdaa96067f91e">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1b0b449637bb3ff8c08cd4287d5395">op_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fb7da57c57a24be71816721887dc455">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac93570e69f7d66e536562edccfcfa8ed">op_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3fb7da57c57a24be71816721887dc455">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4d629ecf1980b70211cb29a8be430a">op_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aea441faf71d458b974c3add03e0fd179">op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cce4d02fda40af0a08b56b03f2b1ce2">operands</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acc18fd33516ae7ad56c8f337fc90cc0d">const_op_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e9d08dd6bf19d1cc7add6dc9d90d4c">operands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d0f6b7220d01d4fe9ecefd3c296a02d">getOperand</a> (unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb9166dd8e540f8c9e6efad7e9cccba0">getOperandUse</a> (unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the operand edge for <span class="doxyComputerOutput">OpIdx</span>. <a href="#acb9166dd8e540f8c9e6efad7e9cccba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac600a3ffce54e05ca28e586af7a04831">getNumOperands</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54abb07f9d20e6d5344ce647621f85a8">setOperand</a> (unsigned OperandIdx, Value *Operand)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a710a597d6f0560bb7e05ea54512520">replaceUsesOfWith</a> (Value *FromV, Value *ToV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replaces any operands that match <span class="doxyComputerOutput">FromV</span> with <span class="doxyComputerOutput">ToV</span>. <a href="#a7a710a597d6f0560bb7e05ea54512520">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67250c676fe2b5ab6619b31d80b5dd5c">verify</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should crash if there is something wrong with the instruction. <a href="#a67250c676fe2b5ab6619b31d80b5dd5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa54928bdcbec1bc934abc9dc7e72445e">dumpCommonHeader</a> (raw_ostream &amp;OS) const final</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb825aba82b13c419b578def1dbc3e3">dumpOS</a> (raw_ostream &amp;OS) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8014de6610ee432b675e3819e011acb2">getOperandUseDefault</a> (unsigned OpIdx, bool Verify) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> edge that corresponds to <span class="doxyComputerOutput">OpIdx</span>. <a href="#a8014de6610ee432b675e3819e011acb2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa469c4f23b78900ac9135b3417819f31">getOperandUseInternal</a> (unsigned OpIdx, bool Verify) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> for the <span class="doxyComputerOutput">OpIdx'th</span> operand. <a href="#aa469c4f23b78900ac9135b3417819f31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a0e1f0647903c551dc3ea6333ab6fc3">getUseOperandNoDefault</a> (const Use &amp;Use) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The default implementation works only for single-LLVMIR-instruction Users and only if they match exactly the LLVM instruction. <a href="#a2a0e1f0647903c551dc3ea6333ab6fc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1edb73baa990149e09d9405f596163a3">getUseOperandNo</a> (const Use &amp;Use) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>\Returns the operand index of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></span>. <a href="#a1edb73baa990149e09d9405f596163a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02ef62e9b637f2ccdc108a83ad983fc">swapOperandsInternal</a> (unsigned OpIdxA, unsigned OpIdxB)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29a530f0bf7efe84cbba172fac79970d">verifyUserOfLLVMUse</a> (const llvm::Use &amp;Use) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980a2cfe3503510dad80d58a1bf46367">classof</a> (const Value *From)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For isa/dyn_cast. <a href="#a980a2cfe3503510dad80d58a1bf46367">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/sandboxir/user">sandboxir::User</a> has operands.</p>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_op\_iterator {#a3fb7da57c57a24be71816721887dc455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::User::const_op_iterator =  OperandUseIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>

</div>
</div>

### const\_op\_range {#acc18fd33516ae7ad56c8f337fc90cc0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::User::const_op_range =  iterator_range&lt;const_op_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>

</div>
</div>

### op\_iterator {#a899e62d7db86984354bbdaa96067f91e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::User::op_iterator =  OperandUseIterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>

</div>
</div>

### op\_range {#aea441faf71d458b974c3add03e0fd179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sandboxir::User::op_range =  iterator_range&lt;op_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### OperandUseIterator {#a1a834efd0135e81675280d5ba828d263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operanduseiterator">OperandUseIterator</a></td>
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


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>Reference <a href="#a1a834efd0135e81675280d5ba828d263">OperandUseIterator</a>.</p>


<p>Referenced by <a href="#a1a834efd0135e81675280d5ba828d263">OperandUseIterator</a>.</p>

</div>
</div>

### Use::getOperandNo {#a64f0b50a2c1ec72bf69dbde8bd85f0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend unsigned</td>
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


<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### User() {#aed798e20a38c7c32351becc11f61f755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::User::User (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#afa2029c46b6caf94a7d05ceb0dbcefe9">ClassID</a> ID, <a href="/web-llvm/docs/api/classes/llvm/value">llvm::Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#ac26c806e60ca4a0547680edb68f6e39b">llvm::sandboxir::Value::Context</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a73b563c1c2654e2f9b3756f38e276284">llvm::sandboxir::Value::Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#aa5e4bdc915437f18466d1d9d1a490f19">llvm::sandboxir::Constant::Constant</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#a79434ebb02d4852eb1e8ca58342c1724">llvm::sandboxir::Constant::Constant</a>, <a href="#a8014de6610ee432b675e3819e011acb2">getOperandUseDefault</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#ac1049fd9695f66ca0bcd91e542f0ed8d">llvm::sandboxir::Instruction::Instruction</a>, <a href="#ac93570e69f7d66e536562edccfcfa8ed">op_begin</a> and <a href="#a2c4d629ecf1980b70211cb29a8be430a">op_end</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dumpCommonHeader() {#aa54928bdcbec1bc934abc9dc7e72445e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::User::dumpCommonHeader (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a1565aa2d231b44e393af53deb7de04c2">llvm::sandboxir::Value::dumpCommonHeader</a>.</p>

</div>
</div>

### dumpOS() {#a0fb825aba82b13c419b578def1dbc3e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::User::dumpOS (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>

</div>
</div>

### getNumOperands() {#ac600a3ffce54e05ca28e586af7a04831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::sandboxir::User::getNumOperands ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/user/#a0d4a83cd78f12aa1ab452c4d94b9cb7b">llvm::User::getDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a4404158bef08e9ee3c0690a359792bc7">llvm::sandboxir::CatchSwitchInst::getNumSuccessors</a>, <a href="#a8014de6610ee432b675e3819e011acb2">getOperandUseDefault</a>, <a href="#add1b0b449637bb3ff8c08cd4287d5395">op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#adb65b7728328242af02bba662ee8e7d7">llvm::sandboxir::PHINode::replaceIncomingBlockWith</a> and <a href="#ab02ef62e9b637f2ccdc108a83ad983fc">swapOperandsInternal</a>.</p>

</div>
</div>

### getOperand() {#a1d0f6b7220d01d4fe9ecefd3c296a02d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::User::getOperand (unsigned OpIdx)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use/#ae8e7baeb75c96786957fe74a468ee8c7">llvm::sandboxir::Use::get</a>, <a href="#acb9166dd8e540f8c9e6efad7e9cccba0">getOperandUse</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a73b563c1c2654e2f9b3756f38e276284">llvm::sandboxir::Value::Value</a>.</p>

</div>
</div>

### getOperandUse() {#acb9166dd8e540f8c9e6efad7e9cccba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use llvm::sandboxir::User::getOperandUse (unsigned OpIdx)</td>
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

<p>\Returns the operand edge for <span class="doxyComputerOutput">OpIdx</span>.</p>


<p>NOTE: This should also work for OpIdx == <a href="#ac600a3ffce54e05ca28e586af7a04831">getNumOperands()</a>, which is used for <a href="#add1b0b449637bb3ff8c08cd4287d5395">op_end()</a>.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="#aa469c4f23b78900ac9135b3417819f31">getOperandUseInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a7b479862be57f4448b155a225b5972ac">llvm::sandboxir::Value::Use</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/shufflevectorinst/#a3e70e997a39fb055c1bfab8f994be745">llvm::sandboxir::ShuffleVectorInst::commute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a37fadc2db10bd3cd2057afbfb8eb3a50">llvm::sandboxir::CallBase::getArgOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#abfbd72a1e2ff7e05724e0938a412628d">llvm::sandboxir::CallBase::getArgOperandUse</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a0d4a83cd78f12aa1ab452c4d94b9cb7b">llvm::User::getDescriptor</a>, <a href="#a1d0f6b7220d01d4fe9ecefd3c296a02d">getOperand</a>, <a href="#a54abb07f9d20e6d5344ce647621f85a8">setOperand</a>, <a href="#ab02ef62e9b637f2ccdc108a83ad983fc">swapOperandsInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#a462041a4b8235d7b12124fca65b8640c">llvm::sandboxir::SelectInst::swapValues</a>.</p>

</div>
</div>

### op\_begin() {#a00acedbe40caf585acae6bf934765a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual op_iterator llvm::sandboxir::User::op_begin ()</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aa469c4f23b78900ac9135b3417819f31">getOperandUseInternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a1d9f9b39dcf9a3e15bfc27a310ac7185">llvm::sandboxir::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#ab426319e6835171df33446fd0c0de8eb">llvm::sandboxir::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#ac628b553ddf5e80f619cb67450aafe43">llvm::sandboxir::CallBase::data_operands_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a57f89d7b128f61512d8b9d321efdd7db">llvm::sandboxir::CallBase::data_operands_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#a5337873da2a75ae20dcc0648c250567d">llvm::sandboxir::CallBase::data_operands_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a85dc121c1e4bdee01555ff2113b68e3c">llvm::sandboxir::CatchSwitchInst::handler_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a123fde854ba4fa4bfffc760cd6a3f8c9">llvm::sandboxir::CatchSwitchInst::handler_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a3199791b2661ee161cee8784dbf69912">llvm::sandboxir::GetElementPtrInst::idx_begin</a>, <a href="#ac93570e69f7d66e536562edccfcfa8ed">op_begin</a>, <a href="#a5cce4d02fda40af0a08b56b03f2b1ce2">operands</a> and <a href="#a92e9d08dd6bf19d1cc7add6dc9d90d4c">operands</a>.</p>

</div>
</div>

### op\_begin() {#ac93570e69f7d66e536562edccfcfa8ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const_op_iterator llvm::sandboxir::User::op_begin ()</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="#a00acedbe40caf585acae6bf934765a72">op_begin</a> and <a href="#aed798e20a38c7c32351becc11f61f755">User</a>.</p>

</div>
</div>

### op\_end() {#add1b0b449637bb3ff8c08cd4287d5395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual op_iterator llvm::sandboxir::User::op_end ()</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac600a3ffce54e05ca28e586af7a04831">getNumOperands</a>, <a href="#aa469c4f23b78900ac9135b3417819f31">getOperandUseInternal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ad7fce600e545aed41462687cd1012965">llvm::sandboxir::CatchSwitchInst::handler_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#a141117bae680c97f0b262e88cf488ccf">llvm::sandboxir::CatchSwitchInst::handler_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/getelementptrinst/#a6e1a26ff4579584e38c58102dfc9d00f">llvm::sandboxir::GetElementPtrInst::idx_end</a>, <a href="#a2c4d629ecf1980b70211cb29a8be430a">op_end</a>, <a href="#a5cce4d02fda40af0a08b56b03f2b1ce2">operands</a> and <a href="#a92e9d08dd6bf19d1cc7add6dc9d90d4c">operands</a>.</p>

</div>
</div>

### op\_end() {#a2c4d629ecf1980b70211cb29a8be430a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual const_op_iterator llvm::sandboxir::User::op_end ()</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="#add1b0b449637bb3ff8c08cd4287d5395">op_end</a> and <a href="#aed798e20a38c7c32351becc11f61f755">User</a>.</p>

</div>
</div>

### operands() {#a5cce4d02fda40af0a08b56b03f2b1ce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_range llvm::sandboxir::User::operands ()</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a00acedbe40caf585acae6bf934765a72">op_begin</a> and <a href="#add1b0b449637bb3ff8c08cd4287d5395">op_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#ad687bdb3aaba6148ae1ec27a7ff1d097">llvm::sandboxir::PHINode::incoming_values</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/phinode/#a2ca40c8247d91c4c374eef9d7e8466e8">llvm::sandboxir::PHINode::incoming_values</a>.</p>

</div>
</div>

### operands() {#a92e9d08dd6bf19d1cc7add6dc9d90d4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_range llvm::sandboxir::User::operands ()</td>
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



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a00acedbe40caf585acae6bf934765a72">op_begin</a> and <a href="#add1b0b449637bb3ff8c08cd4287d5395">op_end</a>.</p>

</div>
</div>

### replaceUsesOfWith() {#a7a710a597d6f0560bb7e05ea54512520}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::User::replaceUsesOfWith (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * FromV, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * ToV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replaces any operands that match <span class="doxyComputerOutput">FromV</span> with <span class="doxyComputerOutput">ToV</span>.</p>


<p>Returns whether any operands were replaced.</p>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a73b563c1c2654e2f9b3756f38e276284">llvm::sandboxir::Value::Value</a>.</p>

</div>
</div>

### setOperand() {#a54abb07f9d20e6d5344ce647621f85a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::User::setOperand (unsigned OperandIdx, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * Operand)</td>
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



<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="#acb9166dd8e540f8c9e6efad7e9cccba0">getOperandUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a73b563c1c2654e2f9b3756f38e276284">llvm::sandboxir::Value::Value</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase/#ad0164d1ab126c51b8595a9ca34e908c7">llvm::sandboxir::CallBase::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a6683c9e3dc16c9d38d1d543a8e15e271">llvm::sandboxir::BranchInst::setCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#a88d168508c17f766c80c0cdf43a89706">llvm::sandboxir::SelectInst::setCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#afae8754bf6d6132ac0cd3acec32985aa">llvm::sandboxir::SelectInst::setFalseValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/invokeinst/#a5aa271ca1ee63dcbc399cf9dcb392d08">llvm::sandboxir::InvokeInst::setNormalDest</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a1c1a35937b89e6b44dadde42df430048">llvm::sandboxir::BranchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/catchswitchinst/#ae180dc5e7860bbf271f786584fce279d">llvm::sandboxir::CatchSwitchInst::setSuccessor</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/selectinst/#a5f9926afd52097966d954b8d0cebec2e">llvm::sandboxir::SelectInst::setTrueValue</a>.</p>

</div>
</div>

### verify() {#a67250c676fe2b5ab6619b31d80b5dd5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::User::verify ()</td>
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

<p>Should crash if there is something wrong with the instruction.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getOperandUseDefault() {#a8014de6610ee432b675e3819e011acb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use llvm::sandboxir::User::getOperandUseDefault (unsigned OpIdx, bool Verify)</td>
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

<p>\Returns the <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> edge that corresponds to <span class="doxyComputerOutput">OpIdx</span>.</p>


<p>Note: This is the default implementation that works for instructions that match the underlying LLVM instruction. All others should use a different implementation.</p>


<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="#ac600a3ffce54e05ca28e586af7a04831">getNumOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a7b479862be57f4448b155a225b5972ac">llvm::sandboxir::Value::Use</a>, <a href="#aed798e20a38c7c32351becc11f61f755">User</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#afbda7524d17168713343950a44657d70">llvm::sandboxir::Constant::getOperandUseInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#a212c05932ca0d1ac0e87b008542aeaa9">llvm::sandboxir::GlobalObject::getOperandUseInternal</a>.</p>

</div>
</div>

### getOperandUseInternal() {#aa469c4f23b78900ac9135b3417819f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Use llvm::sandboxir::User::getOperandUseInternal (unsigned OpIdx, bool Verify)</td>
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

<p>\Returns the <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> for the <span class="doxyComputerOutput">OpIdx'th</span> operand.</p>


<p>This is virtual to allow instructions to deviate from the LLVM IR operands, which is a requirement for sandboxir Instructions that consist of more than one LLVM <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction">Instruction</a>.</p>


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a7b479862be57f4448b155a225b5972ac">llvm::sandboxir::Value::Use</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a>.</p>


<p>Referenced by <a href="#acb9166dd8e540f8c9e6efad7e9cccba0">getOperandUse</a>, <a href="#a00acedbe40caf585acae6bf934765a72">op_begin</a>, <a href="#add1b0b449637bb3ff8c08cd4287d5395">op_end</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operanduseiterator/#ae20a68943264151156296ee8f5a2d25d">llvm::sandboxir::OperandUseIterator::operator+</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/operanduseiterator/#aa46d6a2faaa49dfea1ee6de34cd7b77f">llvm::sandboxir::OperandUseIterator::operator-</a>.</p>

</div>
</div>

### getUseOperandNo() {#a1edb73baa990149e09d9405f596163a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual unsigned llvm::sandboxir::User::getUseOperandNo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> &amp; Use)</td>
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

<p>\Returns the operand index of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a></span>.</p>

<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a7b479862be57f4448b155a225b5972ac">llvm::sandboxir::Value::Use</a>.</p>

</div>
</div>

### getUseOperandNoDefault() {#a2a0e1f0647903c551dc3ea6333ab6fc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::User::getUseOperandNoDefault (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> &amp; Use)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The default implementation works only for single-LLVMIR-instruction Users and only if they match exactly the LLVM instruction.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a7b479862be57f4448b155a225b5972ac">llvm::sandboxir::Value::Use</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/constant/#acf8bb0ca0cc851077b8786fb146c2726">llvm::sandboxir::Constant::getUseOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/globalobject/#add0f588d2e0fa1ede779224b1b98966c">llvm::sandboxir::GlobalObject::getUseOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/nocfivalue/#abcb5c922fba6380c0cc75f1192a8ea43">llvm::sandboxir::NoCFIValue::getUseOperandNo</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/singlellvminstructionimpl/#ade5140b1e37f53fab2641c423dcbbd36">llvm::sandboxir::SingleLLVMInstructionImpl&lt; LLVMT &gt;::getUseOperandNo</a>.</p>

</div>
</div>

### swapOperandsInternal() {#ab02ef62e9b637f2ccdc108a83ad983fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::User::swapOperandsInternal (unsigned OpIdxA, unsigned OpIdxB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac600a3ffce54e05ca28e586af7a04831">getNumOperands</a> and <a href="#acb9166dd8e540f8c9e6efad7e9cccba0">getOperandUse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/binaryoperator/#a1c454f1eb02b39275ab2ca598fafc1c2">llvm::sandboxir::BinaryOperator::swapOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#aaf3075b9b8aaece57ac893df01a25ff3">llvm::sandboxir::BranchInst::swapSuccessors</a>.</p>

</div>
</div>

### verifyUserOfLLVMUse() {#a29a530f0bf7efe84cbba172fac79970d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::User::verifyUserOfLLVMUse (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">llvm::Use</a> &amp; Use)</td>
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



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a7b479862be57f4448b155a225b5972ac">llvm::sandboxir::Value::Use</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a980a2cfe3503510dad80d58a1bf46367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::User::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * From)</td>
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

<p>For isa/dyn_cast.</p>

<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a27b9af008c6420f3340805e50297f9fb">llvm::sandboxir::Value::getSubclassID</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a73b563c1c2654e2f9b3756f38e276284">llvm::sandboxir::Value::Value</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/user-h">User.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/user-cpp">User.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
