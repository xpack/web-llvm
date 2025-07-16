---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instruction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Instruction` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::Instruction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">llvm/IR/Instruction.h</a>"
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user">User</a></td>
</tr>
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction that atomically checks whether a specified value is in a memory location, and, if it is, stores a new value there. <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>an instruction that atomically reads a memory location, combines it with another value, and then stores the result back. <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Conditional or Unconditional Branch instruction. <a href="/web-llvm/docs/api/classes/llvm/branchinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for all callable instructions (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> and <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>) Holds everything related to calling a function. <a href="/web-llvm/docs/api/classes/llvm/callbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/catchreturninst">CatchReturnInst</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/catchswitchinst">CatchSwitchInst</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst">CleanupReturnInst</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class is the base class for the comparison instructions. <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction extracts a single (scalar) element from a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> value. <a href="/web-llvm/docs/api/classes/llvm/extractelementinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fenceinst">FenceInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction for ordering other memory operations. <a href="/web-llvm/docs/api/classes/llvm/fenceinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>an instruction for type-safe pointer arithmetic to access elements of arrays and structs <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indirectbrinst">IndirectBrInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Indirect Branch <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction inserts a single (scalar) element into a <a href="/web-llvm/docs/api/classes/llvm/vectortype">VectorType</a> value. <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction inserts a struct field of array element value into an aggregate value. <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/landingpadinst">LandingPadInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The landingpad instruction holds all of the information necessary to generate correct exception handling. <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/resumeinst">ResumeInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resume the propagation of an exception. <a href="/web-llvm/docs/api/classes/llvm/resumeinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a value (possibly void), from a function. <a href="/web-llvm/docs/api/classes/llvm/returninst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents the LLVM 'select' instruction. <a href="/web-llvm/docs/api/classes/llvm/selectinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This instruction constructs a fixed permutation of two input vectors. <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An instruction for storing to memory. <a href="/web-llvm/docs/api/classes/llvm/storeinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiway switch. <a href="/web-llvm/docs/api/classes/llvm/switchinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unaryinstruction">UnaryInstruction</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/unreachableinst">UnreachableInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function has undefined behavior. <a href="/web-llvm/docs/api/classes/llvm/unreachableinst/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8523456fa135c84e55314de2108f76a">InstListType</a> = <a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-iterator-bits">ilist_iterator_bits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; &gt;</td>
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

## Protected Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acba4015ba8311eac7812dac3086e1b64">OpaqueField</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; uint16_t, 0, 15 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Offset&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a04f5e8259cfe79c39de8db8dd73747cb">AlignmentBitfieldElementT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; unsigned, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>, 6, <a href="/web-llvm/docs/api/classes/llvm/value/#ab5941ebb386c8b46a569d1d8dbfe0c8c">Value::MaxAlignmentExponent</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Offset&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5575a4d18b30d5812be34d337378bf01">BoolBitfieldElementT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; bool, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>, 1 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;unsigned Offset&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ff5195448fd2558e384c94cb605cbaa">AtomicOrderingBitfieldElementT</a> = typename <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">Offset</a>, 3, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7af447f5c03508de4d88e340390ba7c78f">AtomicOrdering::LAST</a> &gt;</td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16ea7f71473a88bd59ffa615ab4c6fe0">HasMetadataField</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; bool, 15, 1 &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperationEquivalenceFlags { <a href="#aa7d8c7b3481309b28659543d1efdb41d">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>When checking for operation equivalence (using isSameOperationAs) it is sometimes useful to ignore certain attributes. <a href="#aa7d8c7b3481309b28659543d1efdb41d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">TermOps { <a href="#ac9422ce2b7c1a541da2e14f637cb4c10">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">UnaryOps { <a href="#af9f57a32b08304fea642871735717f24">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BinaryOps { <a href="#ac26154a24f393f523c87cc5f8239f36c">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MemoryOps { <a href="#a0a89b738faa92ee71304cbc8d9229633">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CastOps { <a href="#afa0b2fa29ba074f2b6ec9ac11163f2d9">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FuncletPadOps { <a href="#a40bc45469579b3adf3e4eb9383ec025f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OtherOps { <a href="#a92db6d5865b9492ef8eeedad41235d0a">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a1c602c4fb0faa383cdd33bdaee7c58">SymbolTableListTraits&lt; Instruction, ilist_iterator_bits&lt; true &gt;, ilist_parent&lt; BasicBlock &gt; &gt;</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Various leaf nodes. <a href="#af10fa975001cd000bc6aaa88267d970f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a> (const Instruction &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37bc1006b02fd1e93dfd862976fb2d35">Instruction</a> (Type *Ty, unsigned iType, AllocInfo AllocInfo, InsertPosition InsertBefore=nullptr)</td>
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

## Protected Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26eb634480beff1ad7a20235c11f521d">~Instruction</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5253ec4f437838a8729fcf3d4f840bb2">operator=</a> (const Instruction &amp;)=delete</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c5f771f232bbd4cf6ec230bd78f9174">dropUnknownNonDebugMetadata</a> (ArrayRef&lt; unsigned &gt; KnownIDs={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop all unknown metadata except for debug locations. <a href="#a9c5f771f232bbd4cf6ec230bd78f9174">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c89a7c3adbeaf3cc5d02a41401801fb">cloneDebugInfoFrom</a> (const Instruction *From, std::optional&lt; simple_ilist&lt; DbgRecord &gt;::iterator &gt; FromHere=std::nullopt, bool InsertAtHead=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Clone any debug-info attached to <span class="doxyComputerOutput">From</span> onto this instruction. <a href="#a2c89a7c3adbeaf3cc5d02a41401801fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;::iterator &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a431be97c0e4d03f713d927197cdcfff0">getDbgRecordRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a range over the DbgRecords attached to this instruction. <a href="#a431be97c0e4d03f713d927197cdcfff0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99db073c46dd0de2c530c64baf77cb7">getDbgReinsertionPosition</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator to the position of the "Next" <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> after this instruction, or std::nullopt. <a href="#ad99db073c46dd0de2c530c64baf77cb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe42f1bdb9f76c2a852dea0238408f99">hasDbgRecords</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if any DbgRecords are attached to this instruction. <a href="#afe42f1bdb9f76c2a852dea0238408f99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998c60b1d33c7964e9fa7f6be1393b06">adoptDbgRecords</a> (BasicBlock *BB, InstListType::iterator It, bool InsertAtHead)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transfer any DbgRecords on the position <span class="doxyComputerOutput">It</span> onto this instruction, by simply adopting the sequence of DbgRecords (which is efficient) if possible, by merging two sequences otherwise. <a href="#a998c60b1d33c7964e9fa7f6be1393b06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0129d256feb019adf09cd86b32ce91">dropDbgRecords</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase any DbgRecords attached to this instruction. <a href="#aef0129d256feb019adf09cd86b32ce91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71583800b3bd19509d34cb223bef0aab">dropOneDbgRecord</a> (DbgRecord *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase a single <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> <span class="doxyComputerOutput">I</span> that is attached to this instruction. <a href="#a71583800b3bd19509d34cb223bef0aab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf73620764d7168629631e3681499f4f">handleMarkerRemoval</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Handle the debug-info implications of this instruction being removed. <a href="#acf73620764d7168629631e3681499f4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6609528bd67d5506a9bf9a2cce2d6f58">user_back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specialize the methods defined in <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, as we know that an instruction can only be used by other instructions. <a href="#a6609528bd67d5506a9bf9a2cce2d6f58">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c799bce3238ef2d8b7b2da3e03745d6">user_back</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba3a5be6c0e9b9e8a525de055836733">getModule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the module owning the function this instruction belongs to or nullptr it the function does not have a module. <a href="#a4ba3a5be6c0e9b9e8a525de055836733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57dc99c7685e4c2fa6c27ba7e9d26d87">getModule</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a66ebb3aa12757479a3c88de77d78f8">getFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function this instruction belongs to. <a href="#a6a66ebb3aa12757479a3c88de77d78f8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37fa134791b478ff5564bbb05255ca94">getFunction</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af65afd02332c4f21c2fab7d217d6600f">getDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the data layout of the module this instruction belongs to. <a href="#af65afd02332c4f21c2fab7d217d6600f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fd53f63d349dc8a7c5fc0cdd7a94c8d">removeFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing basic block, but does not delete it. <a href="#a0fd53f63d349dc8a7c5fc0cdd7a94c8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601ee49a4c4e0babf29bd1cf09036570">eraseFromParent</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method unlinks 'this' from the containing basic block and deletes it. <a href="#a601ee49a4c4e0babf29bd1cf09036570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482498a1c760122fd33c7fc8190dd277">insertBefore</a> (Instruction *InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unlinked instruction into a basic block immediately before the specified instruction. <a href="#a482498a1c760122fd33c7fc8190dd277">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf2824185d7a1f3a86683efb7e525e9">insertBefore</a> (InstListType::iterator InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unlinked instruction into a basic block immediately before the specified position. <a href="#a5bf2824185d7a1f3a86683efb7e525e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af09e4096de244d2fb345891328714a63">insertAfter</a> (Instruction *InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unlinked instruction into a basic block immediately after the specified instruction. <a href="#af09e4096de244d2fb345891328714a63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6347142480e7de8e6e26fb8f291e47f0">insertAfter</a> (InstListType::iterator InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert an unlinked instruction into a basic block immediately after the specified position. <a href="#a6347142480e7de8e6e26fb8f291e47f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd9d2ea284c4d90541291ff9c47d332">insertInto</a> (BasicBlock *ParentBB, InstListType::iterator It)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts an unlinked instruction into <span class="doxyComputerOutput">ParentBB</span> at position <span class="doxyComputerOutput">It</span> and returns the iterator of the inserted instruction. <a href="#afcd9d2ea284c4d90541291ff9c47d332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299df85ca0809906003361ccdf1d7bd2">insertBefore</a> (BasicBlock &amp;BB, InstListType::iterator InsertPos)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67d1f3a518964d80a109bb3d9d5cf1e">moveBefore</a> (Instruction *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right before MovePos. <a href="#af67d1f3a518964d80a109bb3d9d5cf1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56d0f00463a6a160af0a6966cc5ed885">moveBefore</a> (InstListType::iterator InsertPos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right before MovePos. <a href="#a56d0f00463a6a160af0a6966cc5ed885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c2accff1fc7b0c4fc5ab15915573af">moveBeforePreserving</a> (InstListType::iterator MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a <a href="#af67d1f3a518964d80a109bb3d9d5cf1e">moveBefore</a> operation, while signalling that the caller intends to preserve the original ordering of instructions. <a href="#ae3c2accff1fc7b0c4fc5ab15915573af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af53129f70dd4f0dae21bb5099ebecedc">moveBeforePreserving</a> (BasicBlock &amp;BB, InstListType::iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a <a href="#af67d1f3a518964d80a109bb3d9d5cf1e">moveBefore</a> operation, while signalling that the caller intends to preserve the original ordering of instructions. <a href="#af53129f70dd4f0dae21bb5099ebecedc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28c50733b8b3ed88997ca245cd0d6a3b">moveBeforePreserving</a> (Instruction *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a <a href="#af67d1f3a518964d80a109bb3d9d5cf1e">moveBefore</a> operation, while signalling that the caller intends to preserve the original ordering of instructions. <a href="#a28c50733b8b3ed88997ca245cd0d6a3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a850566850f6c034f3d39773112b0427b">moveBefore</a> (BasicBlock &amp;BB, InstListType::iterator I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this instruction and insert into BB before I. <a href="#a850566850f6c034f3d39773112b0427b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54507f01d7d06127068ee0663233511d">moveAfter</a> (Instruction *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right after MovePos. <a href="#a54507f01d7d06127068ee0663233511d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6189d19092044a37414c05526874a06">moveAfter</a> (InstListType::iterator MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right after MovePos. <a href="#ae6189d19092044a37414c05526874a06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2c07ffbd0e823cbd49ec9873c724961">moveAfterPreserving</a> (Instruction *MovePos)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="#ae3c2accff1fc7b0c4fc5ab15915573af">moveBeforePreserving</a> . <a href="#ab2c07ffbd0e823cbd49ec9873c724961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784097fca76abad9e815cf1692de79c4">comesBefore</a> (const Instruction *Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an instruction Other in the same basic block as this instruction, return true if this instruction comes before Other. <a href="#a784097fca76abad9e815cf1692de79c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2b97a10a92351d0df82c9759ad1ee07">getInsertionPointAfterDef</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the first insertion point at which the result of this instruction is defined. <a href="#ad2b97a10a92351d0df82c9759ad1ee07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e05d690df389b8b1477c90387b575f">getOpcode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a member of one of the enums like Instruction::Add. <a href="#ab4e05d690df389b8b1477c90387b575f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9affd129d19aae669647eb0d1c91f793">getOpcodeName</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7653277511df1034148a37520a585bb5">isTerminator</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6249022aded13ad98775c11881bc117">isUnaryOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c88132322ca3f46f242f7c023a57010">isBinaryOp</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c2825ab53adf1bf8c9fa19ec89d986">isIntDivRem</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f25788548135c3b2bee0f5d37becd77">isFPDivRem</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5984d6827f6e6922bed00bf03ba9552">isShift</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27997849d8982bf226891024fd68daee">isCast</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70c1f2d69b2ea2f6d7e83bb17bb9ba0a">isFuncletPad</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb56ab491984549c6f734b0f5b4f925">isSpecialTerminator</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a7168411751df6f6bc19cf5f3724d1">isOnlyUserOfAnyOperand</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>It checks if this instruction is the only user of at least one of its operands. <a href="#a42a7168411751df6f6bc19cf5f3724d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadb443634ecdb8f3e6aa001e6d436122">isLogicalShift</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is a logical shift left or a logical shift right. <a href="#aadb443634ecdb8f3e6aa001e6d436122">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ef1466270a3df7919d1f6111447997e">isArithmeticShift</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is an arithmetic shift right. <a href="#a1ef1466270a3df7919d1f6111447997e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3376e3bd632ad72252638ae43295ce4">isBitwiseLogicOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this is and/or/xor. <a href="#ac3376e3bd632ad72252638ae43295ce4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565f546ad95bd3a9bbe9a1e5040803f0">hasMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has any metadata attached to it. <a href="#a565f546ad95bd3a9bbe9a1e5040803f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0d082032f91d90c9978c66286f8dbfd">hasNonDebugLocLoopMetadata</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54867ca5f252be2c60176e14e7240391">hasMetadataOtherThanDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has metadata attached to it other than a debug location. <a href="#a54867ca5f252be2c60176e14e7240391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18993ec84b78442c34fefdd6d3b3f693">hasMetadata</a> (unsigned KindID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has the given type of metadata attached. <a href="#a18993ec84b78442c34fefdd6d3b3f693">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ce9747bfbb053cf7ac18abbe4a1006">hasMetadata</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has the given type of metadata attached. <a href="#a23ce9747bfbb053cf7ac18abbe4a1006">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c09737e146b2d816c911a047ac67ba4">getMetadata</a> (unsigned KindID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of given kind attached to this <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#a6c09737e146b2d816c911a047ac67ba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd004fda4b063f84d19f53ca2f058cd">getMetadata</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the metadata of given kind attached to this <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#aacd004fda4b063f84d19f53ca2f058cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad11fd49455cd391b69667d5bcbc5df1">getAllMetadata</a> (SmallVectorImpl&lt; std::pair&lt; unsigned, MDNode * &gt; &gt; &amp;MDs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all metadata attached to this <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#aad11fd49455cd391b69667d5bcbc5df1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab025fe91d5f5c6ff951cb7e1f5c2bf64">getAllMetadataOtherThanDebugLoc</a> (SmallVectorImpl&lt; std::pair&lt; unsigned, MDNode * &gt; &gt; &amp;MDs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This does the same thing as getAllMetadata, except that it filters out the debug location. <a href="#ab025fe91d5f5c6ff951cb7e1f5c2bf64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a> (unsigned KindID, MDNode *Node)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the metadata of the specified kind to the specified node. <a href="#a9247a212ea89acc9573fa7e7f557eaba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a695a53ce0b9f537880373b4ea1824a6b">setMetadata</a> (StringRef Kind, MDNode *Node)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec6eaa1e49f48c178e0ab9c030b5971e">copyMetadata</a> (const Instruction &amp;SrcInst, ArrayRef&lt; unsigned &gt; WL=ArrayRef&lt; unsigned &gt;())</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy metadata from <span class="doxyComputerOutput">SrcInst</span> to this instruction. <a href="#aec6eaa1e49f48c178e0ab9c030b5971e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5b08506925637f8addbc11e2190dde6">eraseMetadataIf</a> (function_ref&lt; bool(unsigned, MDNode *)&gt; Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Erase all metadata that matches the predicate. <a href="#af5b08506925637f8addbc11e2190dde6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e324daba99cb1d67713a562f9a778d2">swapProfMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the instruction has "branch_weights" MD_prof metadata and the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> has three operands (including name string), swap the order of the metadata. <a href="#a6e324daba99cb1d67713a562f9a778d2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6762e9e611c29b13a5c94bf8488fe798">addAnnotationMetadata</a> (StringRef Annotation)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an !annotation metadata node with <span class="doxyComputerOutput">Annotation</span> to this instruction. <a href="#a6762e9e611c29b13a5c94bf8488fe798">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a7c63edb94ce4fab2a5bb34dbf6079a">addAnnotationMetadata</a> (SmallVector&lt; StringRef &gt; Annotations)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds an !annotation metadata node with an array of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a></span> as a tuple to this instruction. <a href="#a9a7c63edb94ce4fab2a5bb34dbf6079a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade703948f2fdabdc65868bdf42d3141">getAAMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> metadata for this instruction. <a href="#aade703948f2fdabdc65868bdf42d3141">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dd9b6c5bb93e01393c47dbe60f8b23f">setAAMetadata</a> (const AAMDNodes &amp;N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> metadata on this instruction from the <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> structure. <a href="#a4dd9b6c5bb93e01393c47dbe60f8b23f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959c782ed643a36be7d7264e379025d1">setNoSanitizeMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the nosanitize metadata on this instruction. <a href="#a959c782ed643a36be7d7264e379025d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d5735829e1f043630dd403f01d4219">extractProfTotalWeight</a> (uint64_t &amp;TotalVal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve total raw weight values of a branch. <a href="#a51d5735829e1f043630dd403f01d4219">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8f5bf5cc06f696b52c709677df00fbf">setDebugLoc</a> (DebugLoc Loc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the debug location information for this instruction. <a href="#ae8f5bf5cc06f696b52c709677df00fbf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8faae4ff9e7434a1d226d03d15dcd2">getDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the debug location for this node as a <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>. <a href="#a4b8faae4ff9e7434a1d226d03d15dcd2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00fe6a3df205f2bb5b21ac4ef7a2dca1">getStableDebugLoc</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fetch the debug location for this node, unless this is a debug intrinsic, in which case fetch the debug location of the next non-debug node. <a href="#a00fe6a3df205f2bb5b21ac4ef7a2dca1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c03b71c79206ec41270dc3788183e0d">setHasNoUnsignedWrap</a> (bool b=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the nuw flag on this instruction, which must be an operator which supports this flag. <a href="#a0c03b71c79206ec41270dc3788183e0d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4166b451a572b1e5d3fea7250af53653">setHasNoSignedWrap</a> (bool b=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the nsw flag on this instruction, which must be an operator which supports this flag. <a href="#a4166b451a572b1e5d3fea7250af53653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01940f561517355e394911c203bcedf">setIsExact</a> (bool b=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the exact flag on this instruction, which must be an operator which supports this flag. <a href="#ac01940f561517355e394911c203bcedf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75e5beda8f609473a08473e574511de8">setNonNeg</a> (bool b=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the nneg flag on this instruction, which must be a zext instruction. <a href="#a75e5beda8f609473a08473e574511de8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100c666f9253331dd1d166a863248326">hasNoUnsignedWrap</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the no unsigned wrap flag is set. <a href="#a100c666f9253331dd1d166a863248326">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350f4fdc01c770b5cf6a8be2624ae3e5">hasNoSignedWrap</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the no signed wrap flag is set. <a href="#a350f4fdc01c770b5cf6a8be2624ae3e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87716cd594c6fcb3861a4044e7b594db">hasNonNeg</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the the nneg flag is set. <a href="#a87716cd594c6fcb3861a4044e7b594db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d57cfab4f6b4461e8ddddaeb2a28128">hasPoisonGeneratingFlags</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this operator has flags which may cause this instruction to evaluate to poison despite having non-poison inputs. <a href="#a8d57cfab4f6b4461e8ddddaeb2a28128">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4613def4002aa69721553e567ca4187">dropPoisonGeneratingFlags</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drops flags that may cause this instruction to evaluate to poison despite having non-poison inputs. <a href="#ad4613def4002aa69721553e567ca4187">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59c6449e1b577942315f4365ab5aa89">hasPoisonGeneratingMetadata</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has poison-generating metadata. <a href="#ae59c6449e1b577942315f4365ab5aa89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2736cd830f7195cee466b7199217461">dropPoisonGeneratingMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drops metadata that may generate poison. <a href="#ac2736cd830f7195cee466b7199217461">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ecc41326c89789bcdbd9c9a0295bde7">hasPoisonGeneratingReturnAttributes</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has poison-generating attribute. <a href="#a2ecc41326c89789bcdbd9c9a0295bde7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dcbbcb6c022f6f2c8b46a3e0a4821b5">dropPoisonGeneratingReturnAttributes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drops return attributes that may generate poison. <a href="#a5dcbbcb6c022f6f2c8b46a3e0a4821b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8374600731c31968debc9eb3de4c37bc">hasPoisonGeneratingAnnotations</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has poison-generating flags, return attributes or metadata. <a href="#a8374600731c31968debc9eb3de4c37bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98ad976ff75d19b336e5315a2fdef8c5">dropPoisonGeneratingAnnotations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drops flags, return attributes and metadata that may generate poison. <a href="#a98ad976ff75d19b336e5315a2fdef8c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad73fe7caaafbee5d307aaef54b5f6ea7">dropUBImplyingAttrsAndUnknownMetadata</a> (ArrayRef&lt; unsigned &gt; KnownIDs={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function drops non-debug unknown metadata (through dropUnknownNonDebugMetadata). <a href="#ad73fe7caaafbee5d307aaef54b5f6ea7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cdb2c2c02ea6d97b993be4c2bd099e6">dropUBImplyingAttrsAndMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop any attributes or metadata that can cause immediate undefined behavior. <a href="#a7cdb2c2c02ea6d97b993be4c2bd099e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689a03df5b4ae094d6a3a1bd13dac574">isExact</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the exact flag is set. <a href="#a689a03df5b4ae094d6a3a1bd13dac574">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecf2ba7921a07e6b24434554e02c8106">setFast</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear all fast-math-flags on this instruction, which must be an operator which supports this flag. <a href="#aecf2ba7921a07e6b24434554e02c8106">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5ee2f5097a11b4f6fc135a1d147de4">setHasAllowReassoc</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the reassociation flag on this instruction, which must be an operator which supports this flag. <a href="#a5b5ee2f5097a11b4f6fc135a1d147de4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef005763ae33d1f581c7809d7de1a4c">setHasNoNaNs</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the no-nans flag on this instruction, which must be an operator which supports this flag. <a href="#a4ef005763ae33d1f581c7809d7de1a4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94eaf07edb6829da0be0e8681375ac4e">setHasNoInfs</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the no-infs flag on this instruction, which must be an operator which supports this flag. <a href="#a94eaf07edb6829da0be0e8681375ac4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d07a2504f0f592823ee21311099249">setHasNoSignedZeros</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the no-signed-zeros flag on this instruction, which must be an operator which supports this flag. <a href="#a27d07a2504f0f592823ee21311099249">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdb7b321e4ed4c3d80f4fa5fdc2c4a48">setHasAllowReciprocal</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the allow-reciprocal flag on this instruction, which must be an operator which supports this flag. <a href="#acdb7b321e4ed4c3d80f4fa5fdc2c4a48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ea5d2b89cd3be3e0f07b97c466fe341">setHasAllowContract</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the allow-contract flag on this instruction, which must be an operator which supports this flag. <a href="#a3ea5d2b89cd3be3e0f07b97c466fe341">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542bbbf2a886b74cd2407c216ae06106">setHasApproxFunc</a> (bool B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear the approximate-math-functions flag on this instruction, which must be an operator which supports this flag. <a href="#a542bbbf2a886b74cd2407c216ae06106">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ca8aa62fa8b3fe5bc0e8fbe5d8b8b7a">setFastMathFlags</a> (FastMathFlags FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for setting multiple fast-math flags on this instruction, which must be an operator which supports these flags. <a href="#a5ca8aa62fa8b3fe5bc0e8fbe5d8b8b7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a7664d83746bcda035bddeb773eaae">copyFastMathFlags</a> (FastMathFlags FMF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for transferring all fast-math flag values to this instruction, which must be an operator which supports these flags. <a href="#a24a7664d83746bcda035bddeb773eaae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60311aae406df2143c650f3bce27e036">isFast</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether all fast-math-flags are set. <a href="#a60311aae406df2143c650f3bce27e036">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed565a1dfd056c37a481581db8cdbedd">hasAllowReassoc</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the allow-reassociation flag is set. <a href="#aed565a1dfd056c37a481581db8cdbedd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4bb13ba43d71cfe58184ab1bb4abd1">hasNoNaNs</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the no-NaNs flag is set. <a href="#a0d4bb13ba43d71cfe58184ab1bb4abd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10d8839494fe8385aa1ddbca6f801d79">hasNoInfs</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the no-infs flag is set. <a href="#a10d8839494fe8385aa1ddbca6f801d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c8498183c5bce88fb4f651ee4169611">hasNoSignedZeros</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the no-signed-zeros flag is set. <a href="#a2c8498183c5bce88fb4f651ee4169611">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76908359b5b01e49efdd43d1d6e08c21">hasAllowReciprocal</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the allow-reciprocal flag is set. <a href="#a76908359b5b01e49efdd43d1d6e08c21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf69200e2ae35a69c5eeecd4c0ee4d1c">hasAllowContract</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the allow-contract flag is set. <a href="#adf69200e2ae35a69c5eeecd4c0ee4d1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa11ca53210de69609754994339179e10">hasApproxFunc</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the approximate-math-functions flag is set. <a href="#aa11ca53210de69609754994339179e10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a167f91db810097d281b1ed627f4575">getFastMathFlags</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience function for getting all the fast-math flags, which must be an operator which supports these flags. <a href="#a9a167f91db810097d281b1ed627f4575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab637365777e388d026ec0a7b404fd5f9">copyFastMathFlags</a> (const Instruction *I)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy I's fast-math flags. <a href="#ab637365777e388d026ec0a7b404fd5f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e6d2896c39a84cfa6c47f34cdc584ff">copyIRFlags</a> (const Value *V, bool IncludeWrapFlags=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience method to copy supported exact, fast-math, and (optionally) wrapping flags from V to this instruction. <a href="#a3e6d2896c39a84cfa6c47f34cdc584ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ea9acbe7fd20332ea6ccdb0183d6395">andIRFlags</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Logical 'and' of any supported wrapping, exact, and fast-math flags of V and this instruction. <a href="#a4ea9acbe7fd20332ea6ccdb0183d6395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae88ca601f663c55cafa95cf742076aad">applyMergedLocation</a> (DILocation *LocA, DILocation *LocB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge 2 debug locations and apply it to the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>. <a href="#ae88ca601f663c55cafa95cf742076aad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2bf20cca6e2a10783f868d80a7c0400">updateLocationAfterHoist</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Updates the debug location given that the instruction has been hoisted from a block to a predecessor of that block. <a href="#ae2bf20cca6e2a10783f868d80a7c0400">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4576d69ed1543b06e5c41eb43b630bf1">dropLocation</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Drop the instruction's debug location. <a href="#a4576d69ed1543b06e5c41eb43b630bf1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2711d3bc7c6c769a8f34c7fc3937169d">mergeDIAssignID</a> (ArrayRef&lt; const Instruction * &gt; SourceInstructions)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Merge the <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> metadata from this instruction and those attached to instructions in <span class="doxyComputerOutput">SourceInstructions</span>. <a href="#a2711d3bc7c6c769a8f34c7fc3937169d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f0027b9d05b27206b1882976fce9038">isAssociative</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is associative: <a href="#a4f0027b9d05b27206b1882976fce9038">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55743bd32282bf6f87aeb49237b1fb68">isCommutative</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is commutative: <a href="#a55743bd32282bf6f87aeb49237b1fb68">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba4ff92fbdb591fb2a1090dbda31691">isIdempotent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is idempotent: <a href="#aeba4ff92fbdb591fb2a1090dbda31691">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a902c3b08cb9808fddc542ff284c28edb">isNilpotent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is nilpotent: <a href="#a902c3b08cb9808fddc542ff284c28edb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383175f96316074965ad115706bd49d7">mayWriteToMemory</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction may modify memory. <a href="#a383175f96316074965ad115706bd49d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9149819221d66953ac6c2938b87f0136">mayReadFromMemory</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction may read memory. <a href="#a9149819221d66953ac6c2938b87f0136">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d77b9d450543e86acb394ff6dda6b53">mayReadOrWriteMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction may read or write memory. <a href="#a2d77b9d450543e86acb394ff6dda6b53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57efb022f2ee2e19e4cdf582f4d27f2d">isAtomic</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has an <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> of unordered or higher. <a href="#a57efb022f2ee2e19e4cdf582f4d27f2d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7e43783656ce7aae69f3da31509ff88">hasAtomicLoad</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this atomic instruction loads from memory. <a href="#ab7e43783656ce7aae69f3da31509ff88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a409415e274680c5d72d3272a1cee3d95">hasAtomicStore</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this atomic instruction stores to memory. <a href="#a409415e274680c5d72d3272a1cee3d95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92599976668e8eec0d73b986ad3e7732">isVolatile</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction has a volatile memory access. <a href="#a92599976668e8eec0d73b986ad3e7732">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a765d7abba7daa905e301027dd2fd1086">getAccessType</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type this instruction accesses in memory, if any. <a href="#a765d7abba7daa905e301027dd2fd1086">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0501e3b4084693092efc0be8b02c1b6b">mayThrow</a> (bool IncludePhaseOneUnwind=false) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction may throw an exception. <a href="#a0501e3b4084693092efc0be8b02c1b6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aced8559a5380b3759af251428f024c02">isFenceLike</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this instruction behaves like a memory fence: it can load or store to memory location without being given a memory location. <a href="#aced8559a5380b3759af251428f024c02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ea260be710ac7b61309534308da3147">mayHaveSideEffects</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction may have side effects. <a href="#a6ea260be710ac7b61309534308da3147">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af92eae2af65e24114a8767cc10c8795e">isSafeToRemove</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction can be removed if the result is unused. <a href="#af92eae2af65e24114a8767cc10c8795e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa03e017ef451ba2f6f504b0d40c2da2e">willReturn</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction will return (unwinding is considered as a form of returning control flow here). <a href="#aa03e017ef451ba2f6f504b0d40c2da2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d3d315f678bc76e43b27d18e5d72829">isEHPad</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a variety of EH-block. <a href="#a5d3d315f678bc76e43b27d18e5d72829">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a185bafe1e8f07def76a3bac154a23e7a">isLifetimeStartOrEnd</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a llvm.lifetime.start or llvm.lifetime.end marker. <a href="#a185bafe1e8f07def76a3bac154a23e7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda9304aaf3716109938d9479b2d2dbc">isLaunderOrStripInvariantGroup</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a llvm.launder.invariant.group or llvm.strip.invariant.group. <a href="#adda9304aaf3716109938d9479b2d2dbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a323444895ce923a737f0a7af82a30f54">isDebugOrPseudoInst</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the instruction is a <a href="/web-llvm/docs/api/classes/llvm/dbginfointrinsic">DbgInfoIntrinsic</a> or <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeinst">PseudoProbeInst</a>. <a href="#a323444895ce923a737f0a7af82a30f54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bd28adea418a08cec78b72413d9d45">getNextNonDebugInstruction</a> (bool SkipPseudoOp=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the next non-debug instruction in the same basic block as 'this', or nullptr if no such instruction exists. <a href="#a91bd28adea418a08cec78b72413d9d45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475658532adbdbbba2c62d48e9b8d1f1">getNextNonDebugInstruction</a> (bool SkipPseudoOp=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512494b857b0644c1f722531e3ee5495">getPrevNonDebugInstruction</a> (bool SkipPseudoOp=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pointer to the previous non-debug instruction in the same basic block as 'this', or nullptr if no such instruction exists. <a href="#a512494b857b0644c1f722531e3ee5495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a880c796a9f81d3a377a3a8886ec88f62">getPrevNonDebugInstruction</a> (bool SkipPseudoOp=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a4d51e372293abe5e5f6dac133e80a6">clone</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a copy of 'this' instruction that is identical in all ways except the following: <a href="#a0a4d51e372293abe5e5f6dac133e80a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad848bd0184fc7bcb7b71e19248f08f34">isIdenticalTo</a> (const Instruction *I) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified instruction is exactly identical to the current one. <a href="#ad848bd0184fc7bcb7b71e19248f08f34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602468cf8d0763769b6b39ece1117ad7">isIdenticalToWhenDefined</a> (const Instruction *I, bool IntersectAttrs=false) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is like isIdenticalTo, except that it ignores the SubclassOptionalData flags, which may specify conditions under which the instruction's result is undefined. <a href="#a602468cf8d0763769b6b39ece1117ad7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25175390eaee0646bcb8b30990ab723b">isSameOperationAs</a> (const Instruction *I, unsigned flags=0) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if the specified instruction executes the same operation as the current one. <a href="#a25175390eaee0646bcb8b30990ab723b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a566048bdbd8bade381b6a52ed0244621">hasSameSpecialState</a> (const Instruction *I2, bool IgnoreAlignment=false, bool IntersectAttrs=false) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if the speficied instruction has the same "special" characteristics as the current one. <a href="#a566048bdbd8bade381b6a52ed0244621">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91dbffd0cc6b209fd2bfe9a0236d779c">isUsedOutsideOfBlock</a> (const BasicBlock *BB) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if there are any uses of this instruction in blocks other than the specified block. <a href="#a91dbffd0cc6b209fd2bfe9a0236d779c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3287172f2d13af086e6d66364e8c6de3">getNumSuccessors</a> () const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of successors that this instruction has. <a href="#a3287172f2d13af086e6d66364e8c6de3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e5d2e18c81baaeec7dadc81a0dea993">getSuccessor</a> (unsigned Idx) const LLVM_READONLY</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the specified successor. This instruction must be a terminator. <a href="#a6e5d2e18c81baaeec7dadc81a0dea993">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae959364e4640ac025bbc046d3d7c7e61">setSuccessor</a> (unsigned Idx, BasicBlock *BB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the specified successor to point at the provided block. <a href="#ae959364e4640ac025bbc046d3d7c7e61">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657e5d1f0907b46daf10219e2b9b5ae5">replaceSuccessorWith</a> (BasicBlock *OldBB, BasicBlock *NewBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Replace specified successor OldBB to point at the provided block. <a href="#a657e5d1f0907b46daf10219e2b9b5ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BitfieldElement&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">BitfieldElement::Type</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a041694a1ea45996587ef9712d9a2bb1f">getSubclassData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename BitfieldElement&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afbb5877d4ac72148b232c8fedb08bba5">setSubclassData</a> (typename BitfieldElement::Type Value)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e6b3a00101e8c0ae0c083a127e9f4d3">moveBeforeImpl</a> (BasicBlock &amp;BB, InstListType::iterator I, bool Preserve)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>RemoveDIs project: all other moves implemented with this method, centralising debug-info updates into one place. <a href="#a3e6b3a00101e8c0ae0c083a127e9f4d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c885f9a985e24c4132d4760868a527a">getMetadataImpl</a> (StringRef Kind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469fa5988ead0e34ab6cd440965468ec">getAllMetadataImpl</a> (SmallVectorImpl&lt; std::pair&lt; unsigned, MDNode * &gt; &gt; &amp;) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade9bf913d64dd33b0f46cbb63f7190ff">updateDIAssignIDMapping</a> (DIAssignID *ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> ID-to-Instruction(s) mapping. <a href="#ade9bf913d64dd33b0f46cbb63f7190ff">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0ab6cff2d4e000a85e3b295fb4743cc">setValueSubclassData</a> (unsigned short D)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8e7c93bf65b664f74ea285f203bb82">getSubclassDataFromValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1f8cd591829a6701818590ee806306a">cloneImpl</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a copy of this instruction. <a href="#ab1f8cd591829a6701818590ee806306a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dbgmarker">DbgMarker</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0172245e9f9a9097b5d403ab70348bdd">DebugMarker</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optional marker recording the position for debugging information that takes effect immediately before this instruction. <a href="#a0172245e9f9a9097b5d403ab70348bdd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7d7ab3746e87db585dc63d6b42112d">DbgLoc</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b66fa88bd0391e5ce77fc93ba7e9022">Order</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Relative order of this instruction in its parent basic block. <a href="#a8b66fa88bd0391e5ce77fc93ba7e9022">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5695ce86ca3854c8b1ad5020c3aa71ee">getOpcodeName</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1cfb64ba31b4b2eb24b5bb0f4a03b3">isTerminator</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3506fee8672213803272ce81e15eb43">isUnaryOp</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19a7026c9bfca302daa96fff1445910a">isBinaryOp</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea89163a72302081fba69821b3a5bf13">isIntDivRem</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a257920a1e7211884082cc6e599f4bd7f">isFPDivRem</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345db67ae3444fc10db37ff34cf4166e">isShift</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the Opcode is one of the shift instructions. <a href="#a345db67ae3444fc10db37ff34cf4166e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0036d2d7b30f510927731ba7a4f4b9">isBitwiseLogicOp</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the Opcode is and/or/xor. <a href="#a2d0036d2d7b30f510927731ba7a4f4b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47e931b4753c5d32baf9a2f8de1e2d92">isCast</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the Opcode is one of the <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> instructions. <a href="#a47e931b4753c5d32baf9a2f8de1e2d92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1d8db0294e807c6834618d54d2fb6bc">isFuncletPad</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the Opcode is one of the <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a> instructions. <a href="#ab1d8db0294e807c6834618d54d2fb6bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c1f1a7ac43254d4242048c2a92d6734">isSpecialTerminator</a> (unsigned Opcode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the Opcode is a "special" terminator that does more than branch to a successor (e.g. <a href="#a3c1f1a7ac43254d4242048c2a92d6734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58c0f69b2d18b94c651b13d8e7fd9ebc">isAssociative</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48dd504e040ba9c89e802af96c78dd25">isCommutative</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6761fd11adc4d27f569d339c3c0c8c40">isIdempotent</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8528558d235e86bddc040ae8580746b">isNilpotent</a> (unsigned Opcode)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644afe0cf8a4816171b3384098325dc2">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a644afe0cf8a4816171b3384098325dc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InstListType {#af8523456fa135c84e55314de2108f76a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Instruction::InstListType =  SymbolTableList&lt;Instruction, ilist_iterator_bits&lt;true&gt;,
                                       ilist_parent&lt;BasicBlock&gt;&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Typedefs

### AlignmentBitfieldElementT {#a04f5e8259cfe79c39de8db8dd73747cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Offset&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Instruction::AlignmentBitfieldElementT = 
      typename Bitfield::Element&lt;unsigned, Offset, 6,
                                 Value::MaxAlignmentExponent&gt;</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### AtomicOrderingBitfieldElementT {#a1ff5195448fd2558e384c94cb605cbaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Offset&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Instruction::AtomicOrderingBitfieldElementT = 
      typename Bitfield::Element&lt;AtomicOrdering, Offset, 3,
                                 AtomicOrdering::LAST&gt;</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### BoolBitfieldElementT {#a5575a4d18b30d5812be34d337378bf01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;unsigned Offset&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Instruction::BoolBitfieldElementT =  typename Bitfield::Element&lt;bool, Offset, 1&gt;</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### OpaqueField {#acba4015ba8311eac7812dac3086e1b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Instruction::OpaqueField =  Bitfield::Element&lt;uint16_t, 0, 15&gt;</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### HasMetadataField {#a16ea7f71473a88bd59ffa615ab4c6fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Instruction::HasMetadataField =  Bitfield::Element&lt;bool, 15, 1&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### BinaryOps {#ac26154a24f393f523c87cc5f8239f36c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::BinaryOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1008 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### CastOps {#afa0b2fa29ba074f2b6ec9ac11163f2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::CastOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### FuncletPadOps {#a40bc45469579b3adf3e4eb9383ec025f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::FuncletPadOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### MemoryOps {#a0a89b738faa92ee71304cbc8d9229633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::MemoryOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### OperationEquivalenceFlags {#aa7d8c7b3481309b28659543d1efdb41d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::OperationEquivalenceFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>When checking for operation equivalence (using isSameOperationAs) it is sometimes useful to ignore certain attributes.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CompareIgnoringAlignment<a id="aa7d8c7b3481309b28659543d1efdb41da78bdb3b677bd78b8f1f0f680f59a049b"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for equivalence ignoring load/store alignment (= 1 &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CompareUsingScalarTypes<a id="aa7d8c7b3481309b28659543d1efdb41da9160004f266e276236ea4be972957d3b"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for equivalence treating a type and a vector of that type as equivalent (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CompareUsingIntersectedAttrs<a id="aa7d8c7b3481309b28659543d1efdb41dacf591df2f648de38effb4c1a274d0d37"></a></td>
<td class="doxyEnumItemDescription"><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for equivalence with intersected callbase attrs (= 1 &lt;&lt; 2)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 935 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### OtherOps {#a92db6d5865b9492ef8eeedad41235d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::OtherOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### TermOps {#ac9422ce2b7c1a541da2e14f637cb4c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::TermOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### UnaryOps {#af9f57a32b08304fea642871735717f24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Instruction::UnaryOps </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### BasicBlock {#af10fa975001cd000bc6aaa88267d970f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Various leaf nodes.</p>

<p>Definition at line 1046 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#aae37705b598ef612f698198dc33d6f65">llvm::Value::setValueSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a62abc2475d09c01d583ba24a487898fd">llvm::SwitchInst::addCase</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a08b418bd465a9f2ff316beb04005f6d7">llvm::IndirectBrInst::addDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a4b1438bbee79540a0cca9a2c018b71ec">llvm::CatchSwitchInst::addHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a089cccb6f231efee72abc76d0f9c695f">llvm::PHINode::addIncoming</a>, <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a33901f0ae7fea18fad9358970e01eeb3">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/catchreturninst/#a5e0c4c9869440d0696fded059fff12dc">llvm::CatchReturnInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#acf9b80aee9ba7ec6b77416f8e5227e88">llvm::CatchSwitchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst/#a7e19664720f1c4693b788b018d08758c">llvm::CleanupReturnInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a5dd1c25db7fcd941f528cbac851ffb29">llvm::ReturnInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a3c1416226bed5e92acb74aebe8e20f5a">llvm::SwitchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a7e0388218a0b4d2e1e5f210e0fbb1e86">llvm::SwitchInst::findCaseDest</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae9562b96f6f3fa41bd36538c080035ee">llvm::PHINode::getBasicBlockIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a0943fb5f399be0ac6ffbe8c977b619c8">llvm::SwitchInst::getDefaultDest</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a1a53ee48e5f0d2aff838d12c367feb5b">llvm::IndirectBrInst::getDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#ada301efababba67a120e8438b98ad95a">llvm::IndirectBrInst::getDestination</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae7e053d6c8abe52081095ae208263ee9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ac53e1aabdf64e91b8b325bcac250d8a9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a00af260cbec025b19b160364642715b9">llvm::PHINode::getIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ab2db7609ec72b1af2f91d47e40dc3722">llvm::PHINode::getIncomingValueForBlock</a>, <a href="#a5695ce86ca3854c8b1ad5020c3aa71ee">getOpcodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#aa05da2b94b366573d1651d5b163c521e">llvm::BranchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/catchreturninst/#a3b70ee8cd586e2f8c5521ef92aefe59a">llvm::CatchReturnInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#ab67f867e4c275996050a92cc4853819e">llvm::CatchSwitchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#a8cc0c502b60875a5b8086c6e029a56c8">llvm::IndirectBrInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a30f79d54afada3c9005d24ab8743a9d6">llvm::SwitchInst::getSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#ab04dbc468ae6f1e7ff304ec5ba903b66">llvm::CatchSwitchInst::getUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst/#a28752dcdba8534d4e32018a7a2bb289b">llvm::CleanupReturnInst::getUnwindDest</a>, <a href="#a0d4bb13ba43d71cfe58184ab1bb4abd1">hasNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a12a188073b910647564952c1ca195386">llvm::PHINode::isComplete</a>, <a href="/web-llvm/docs/api/structs/llvm/branchinst/const-succ-op-iterator/#aa691808657df000cfd3b1a57d6bae596">llvm::BranchInst::const_succ_op_iterator::operator*</a>, <a href="/web-llvm/docs/api/structs/llvm/branchinst/succ-op-iterator/#acf0f5afce748bb9d80d444c56e8d060a">llvm::BranchInst::succ_op_iterator::operator*</a>, <a href="/web-llvm/docs/api/structs/llvm/indirectbrinst/const-succ-op-iterator/#a9dc8eddbe983d5cd48ce391d51468c19">llvm::IndirectBrInst::const_succ_op_iterator::operator*</a>, <a href="/web-llvm/docs/api/structs/llvm/indirectbrinst/succ-op-iterator/#a496f0b758073512d3517e563f549b842">llvm::IndirectBrInst::succ_op_iterator::operator*</a>, <a href="/web-llvm/docs/api/structs/llvm/branchinst/const-succ-op-iterator/#a146ff71cdde95657d8d72f37bfa7aa2b">llvm::BranchInst::const_succ_op_iterator::operator-&gt;</a>, <a href="/web-llvm/docs/api/structs/llvm/branchinst/succ-op-iterator/#a3e09c581609b801edc5cf527f6b26080">llvm::BranchInst::succ_op_iterator::operator-&gt;</a>, <a href="/web-llvm/docs/api/structs/llvm/indirectbrinst/const-succ-op-iterator/#af80097fea1d76abcd38ed815e09fe456">llvm::IndirectBrInst::const_succ_op_iterator::operator-&gt;</a>, <a href="/web-llvm/docs/api/structs/llvm/indirectbrinst/succ-op-iterator/#aca6c9d817fec96309a6fef178cafab65">llvm::IndirectBrInst::succ_op_iterator::operator-&gt;</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ad3b3f752c51597971949a3930b480ea8">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ae6c98d2f865894d646b95e8af8176a5d">llvm::PHINode::replaceIncomingBlockWith</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#aa22bdae1cee3c836f2b4cf8307fc7598">llvm::SwitchInst::setDefaultDest</a>, <a href="#a94eaf07edb6829da0be0e8681375ac4e">setHasNoInfs</a>, <a href="#a4ef005763ae33d1f581c7809d7de1a4c">setHasNoNaNs</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5ba57877c55dfdbe6e3bbfdacd9ef8c1">llvm::PHINode::setIncomingBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a506bcfb6f92a2184453e1fa9655f62a1">llvm::PHINode::setIncomingValueForBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#adc5e7f9c460c68455e826783d77f9a99">llvm::BranchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/catchreturninst/#a3e0707b38e81b1795e39958eba9b31d2">llvm::CatchReturnInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a6f874c755633c971f75b47cba784955e">llvm::CatchSwitchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/indirectbrinst/#add548a093823a9bc99babe5e2f9282f3">llvm::IndirectBrInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/casehandle/#ade327bd05bcf154647ea34eed5ddf354">llvm::SwitchInst::CaseHandle::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/switchinst/#a7fc7899c254935205ca29b6bd7baa926">llvm::SwitchInst::setSuccessor</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a03f8f04a7ac9266f16326fb7ba5786d3">llvm::CatchSwitchInst::setUnwindDest</a> and <a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst/#a57a0a04813b78f6dd148c72b6ad57c09">llvm::CleanupReturnInst::setUnwindDest</a>.</p>

</div>
</div>

### SymbolTableListTraits&lt; Instruction, ilist\_iterator\_bits&lt; true &gt;, ilist\_parent&lt; BasicBlock &gt; &gt; {#a4a1c602c4fb0faa383cdd33bdaee7c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, <a href="/web-llvm/docs/api/structs/llvm/ilist-iterator-bits">ilist_iterator_bits</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;, <a href="/web-llvm/docs/api/structs/llvm/ilist-parent">ilist_parent</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Instruction() {#ae70f02adcd410ca9c8429fa8d7711965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Instruction::Instruction (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a24a5f30f3d82fa2f32115ef1df689c07">llvm::CmpInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/unaryinstruction/#a4d95e06fbc70703540033570dd7fe03a">llvm::UnaryInstruction::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ae65337bd76ece9e7b1d20cf665bfa742">llvm::CmpInst::CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a6d0ee639690d0fa59e6c9e0af5adc5c2">llvm::CmpInst::CreateWithCopiedFlags</a>, <a href="#a37fa134791b478ff5564bbb05255ca94">getFunction</a>, <a href="#a57dc99c7685e4c2fa6c27ba7e9d26d87">getModule</a>, <a href="#a475658532adbdbbba2c62d48e9b8d1f1">getNextNonDebugInstruction</a>, <a href="#a880c796a9f81d3a377a3a8886ec88f62">getPrevNonDebugInstruction</a>, <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>, <a href="#a2711d3bc7c6c769a8f34c7fc3937169d">mergeDIAssignID</a>, <a href="#ae6189d19092044a37414c05526874a06">moveAfter</a>, <a href="#a5253ec4f437838a8729fcf3d4f840bb2">operator=</a>, <a href="/web-llvm/docs/api/classes/llvm/unaryinstruction/#ad93ca9b74c44e7d8c00c72405e51262d">llvm::UnaryInstruction::UnaryInstruction</a>, <a href="#a6609528bd67d5506a9bf9a2cce2d6f58">user_back</a> and <a href="#a9c799bce3238ef2d8b7b2da3e03745d6">user_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### Instruction() {#a37bc1006b02fd1e93dfd862976fb2d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction::Instruction (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, unsigned iType, <a href="/web-llvm/docs/api/structs/llvm/user/allocinfo">AllocInfo</a> AllocInfo, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertBefore=nullptr)</td>
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



<p>Declaration at line 1082 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Destructor

### \~Instruction() {#a26eb634480beff1ad7a20235c11f521d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction::~Instruction ()</td>
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



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a5253ec4f437838a8729fcf3d4f840bb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction &amp; llvm::Instruction::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp;)</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### dropUnknownNonDebugMetadata() {#a9c5f771f232bbd4cf6ec230bd78f9174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropUnknownNonDebugMetadata (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; KnownIDs={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop all unknown metadata except for debug locations.</p>


<p>Passes are required to drop metadata they don't understand. This is a convenience method for passes to do so. dropUBImplyingAttrsAndUnknownMetadata should be used instead of this API if the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> being modified is a call.</p>


<p>Declaration at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1633 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#a2a98f19750ba941ce791b75ca6d77e48">llvm::SmallSet&lt; T, N, C &gt;::count</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab1198eef44b311a7984cfc8fc97fac6d">llvm::Value::eraseMetadataIf</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1f496e54accb2cbe919fb456cb703f1a">llvm::Value::hasMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a> and <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#ac96558c87ecbcc96f020a0efcaade750">llvm::gvn::AvailableValue::MaterializeAdjustedValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addAnnotationMetadata() {#a6762e9e611c29b13a5c94bf8488fe798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::addAnnotationMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Annotation)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an !annotation metadata node with <span class="doxyComputerOutput">Annotation</span> to this instruction.</p>


<p>If this instruction already has !annotation metadata, append <span class="doxyComputerOutput">Annotation</span> to the existing node.</p>


<p>Declaration at line 487 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1732 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a7939b917f71d9664707d8ec51da88418">llvm::MDBuilder::createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a6c09737e146b2d816c911a047ac67ba4">getMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a>.</p>

</div>
</div>

### addAnnotationMetadata() {#a9a7c63edb94ce4fab2a5bb34dbf6079a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::addAnnotationMetadata (<a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; Annotations)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds an !annotation metadata node with an array of <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/annotations">Annotations</a></span> as a tuple to this instruction.</p>


<p>If this instruction already has !annotation metadata, append the tuple to the existing node.</p>


<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1702 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#a7939b917f71d9664707d8ec51da88418">llvm::MDBuilder::createString</a>, <a href="/web-llvm/docs/api/classes/llvm/mdtuple/#aad2e50b107c264353f4de80e03f9f754">llvm::MDTuple::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a6c09737e146b2d816c911a047ac67ba4">getMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a72f80871b9f46788c255158fbab96879">llvm::User::Op</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a>.</p>

</div>
</div>

### adoptDbgRecords() {#a998c60b1d33c7964e9fa7f6be1393b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::adoptDbgRecords (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> It, bool InsertAtHead)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transfer any DbgRecords on the position <span class="doxyComputerOutput">It</span> onto this instruction, by simply adopting the sequence of DbgRecords (which is efficient) if possible, by merging two sequences otherwise.</p>

<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### andIRFlags() {#a4ea9acbe7fd20332ea6ccdb0183d6395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::andIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Logical 'and' of any supported wrapping, exact, and fast-math flags of V and this instruction.</p>

<p>Declaration at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>.</p>

</div>
</div>

### applyMergedLocation() {#ae88ca601f663c55cafa95cf742076aad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::applyMergedLocation (<a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * LocA, <a href="/web-llvm/docs/api/classes/llvm/dilocation">DILocation</a> * LocB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge 2 debug locations and apply it to the <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>


<p>If the instruction is a CallIns, we need to traverse the inline chain to find the common scope. This is not efficient for N-way merging as each time you merge 2 iterations, you need to rebuild the hashmap to find the common scope. However, we still choose this API because: 1) Simplicity: it takes 2 locations instead of a list of locations. 2) In worst case, it increases the complexity from O(N*I) to O(2*N*I), where N is # of Instructions to merge, and I is the maximum level of inline stack. So it is still linear. 3) Merging of call instructions should be extremely rare in real applications, thus the N-way merging should be in code path. The <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> attached to this instruction will be overwritten by the merged <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>


<p>Declaration at line 694 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dilocation/#a78cc51c415c7e64b5efe2c8458fbd35a">llvm::DILocation::getMergedLocation</a> and <a href="#ae8f5bf5cc06f696b52c709677df00fbf">setDebugLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6c837ffd3a1932f53de13120ad1551a">llvm::InstCombinerImpl::PHIArgMergedDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a957b517efddeb68617e18ffef3b64683">updateForIncomingValueLocation</a>.</p>

</div>
</div>

### clone() {#a0a4d51e372293abe5e5f6dac133e80a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * Instruction::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a copy of 'this' instruction that is identical in all ways except the following:</p>


<ul class="doxyList ">
<li>The instruction has no parent</li>
<li>The instruction has no name</li>
</ul>

<p>Declaration at line 919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1361 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#abb509fb245e8c6b6331b5dec01e80ac7">llvm::AtomicCmpXchgInst::getSuccessOrdering</a> and <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a557a8b9c426a3c8d192775c18e848ca4">llvm::AtomicCmpXchgInst::setSuccessOrdering</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a0adb0a856adef09fd017379f4644ba4e">convertFSqrtDivIntoFMul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#a5289777e58accae64ebded1a95e4c8b0">anonymous{MergeICmps.cpp}::mergeComparisons</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a23239d94380595765d9caf8bae661d7a">replaceGEPIdxWithZero</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/storefatptrsasintsvisitor/#a77976478ff4af840d8dc298cd7bb1b65">anonymous{AMDGPULowerBufferFatPointers.cpp}::StoreFatPtrsAsIntsVisitor::visitLoadInst</a>.</p>

</div>
</div>

### cloneDebugInfoFrom() {#a2c89a7c3adbeaf3cc5d02a41401801fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; DbgRecord::self_iterator &gt; Instruction::cloneDebugInfoFrom (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * From, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/simple-ilist">simple_ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> &gt;<a href="/web-llvm/docs/api/classes/llvm/iplist">::iterator</a> &gt; FromHere=std::nullopt, bool InsertAtHead=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Clone any debug-info attached to <span class="doxyComputerOutput">From</span> onto this instruction.</p>


<p>Used to copy debugging information from one block to another, when copying entire blocks.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debugprograminstruction-h">DebugProgramInstruction.h</a> , because the ordering of DbgRecords is still important, fine grain control of which <a href="/web-llvm/docs/api/namespaces/llvm/#a7e3e687ddfdcbacd404bcf17b917dd88">instructions</a> are moved and where they go is necessary. <span class="doxyComputerOutput">From</span> The instruction to <a href="#a0a4d51e372293abe5e5f6dac133e80a6">clone</a> debug-info from. <span class="doxyComputerOutput">from_here</span> Optional <a href="/web-llvm/docs/api/classes/llvm/iplist">iterator</a> to limit DbgRecords cloned to be a range from from_here to end(). <span class="doxyComputerOutput">InsertAtHead</span> Whether the cloned DbgRecords should be placed <a href="/web-llvm/docs/api/namespaces/llvm/at">at</a> the end or the beginning of existing DbgRecords attached to this.</p></dd>
</dl>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A range over the newly cloned DbgRecords.</p></dd>
</dl>


<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#adf69200e2ae35a69c5eeecd4c0ee4d1c">hasAllowContract</a>, <a href="#a3ea5d2b89cd3be3e0f07b97c466fe341">setHasAllowContract</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a44f91224211f7d2538f311f9a916264d">llvm::JumpThreadingPass::cloneInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a3e0a718e94aeee6a4eab13eea47664da">llvm::BasicBlock::Instruction::cloneDebugInfoFrom</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>.</p>

</div>
</div>

### comesBefore() {#a784097fca76abad9e815cf1692de79c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::comesBefore (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an instruction Other in the same basic block as this instruction, return true if this instruction comes before Other.</p>


<p>In this worst case, this takes linear time in the number of instructions in the block. The results are cached, so in common cases when the block remains unmodified, it takes constant time.</p>


<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpblock/#a851916c7b9610597c4339a0d74f8e449">anonymous{MergeICmps.cpp}::BCECmpBlock::canSinkBCECmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codemoverutils-cpp/#a8b9a912d352e6ed808f954f1b40a4b58">domTreeLevelBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="/web-llvm/docs/api/classes/llvm/instructionprecedencetracking/#adeff4bfc41e787e8074a500fe3f2fbb7">llvm::InstructionPrecedenceTracking::isPreceededBySpecialInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f7c11444c9e7d7c1036ae1f049f4cee">llvm::isValidAssumeForContext</a>, <a href="#ae6189d19092044a37414c05526874a06">moveAfter</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#ae31219d422e76099c3c5dfaa2c7171cb">anonymous{LoadStoreVectorizer.cpp}::reorder</a>.</p>

</div>
</div>

### copyFastMathFlags() {#a24a7664d83746bcda035bddeb773eaae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::copyFastMathFlags (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience function for transferring all fast-math flag values to this instruction, which must be an operator which supports these flags.</p>


<p>See LangRef.html for the meaning of these flags.</p>


<p>Declaration at line 639 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 606 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a9b0aeaa55a33109c212ca71908c51131">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::expandDivRem24Impl</a>, <a href="#ad99db073c46dd0de2c530c64baf77cb7">getDbgReinsertionPosition</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>.</p>

</div>
</div>

### copyFastMathFlags() {#ab637365777e388d026ec0a7b404fd5f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::copyFastMathFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy I's fast-math flags.</p>

<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 656 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>

</div>
</div>

### copyIRFlags() {#a3e6d2896c39a84cfa6c47f34cdc584ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::copyIRFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, bool IncludeWrapFlags=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience method to copy supported exact, fast-math, and (optionally) wrapping flags from V to this instruction.</p>

<p>Declaration at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#ac0292e8b8cfe9cfc5ecd1684f841955b">llvm::FuncletPadInst::getParentPad</a> and <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst/#a86170a400cd0f64650a497310d18eda2">llvm::FuncletPadInst::setParentPad</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#ae65337bd76ece9e7b1d20cf665bfa742">llvm::CmpInst::CmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#ac80f39cdc458ec63d7ff5f7490498230">llvm::BinaryOperator::CreateWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a6d0ee639690d0fa59e6c9e0af5adc5c2">llvm::CmpInst::CreateWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/unaryoperator/#a507eb6210c8a0ba429226156e43745a1">llvm::UnaryOperator::CreateWithCopiedFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### copyMetadata() {#aec6eaa1e49f48c178e0ab9c030b5971e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::copyMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; SrcInst, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; WL=<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy metadata from <span class="doxyComputerOutput">SrcInst</span> to this instruction.</p>


<p><span class="doxyComputerOutput">WL</span>, if not empty, specifies the list of meta data that needs to be copied. If <span class="doxyComputerOutput">WL</span> is empty, all meta data will be copied.</p>


<p>Declaration at line 464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1342 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a9267cf9acba995fd1b10ae1015d048c8">llvm::breakLoopBackedge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a09d8760fa31a7b8739acf71a4d2ac9d9">llvm::SelectInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a22e193e6a0495abb240bbb128af58cfc">llvm::IRBuilderBase::CreateCondBr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#ac80824cf7bdae0e18c7032eb8ce5214c">instCombineSVELD1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a6139b54e783a57871c92c1ac67e4be6e">instCombineSVEST1</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a557f3c41bf651bbd713f9220c59f0b1a">llvm::InstCombinerImpl::SimplifyAnyMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### dropDbgRecords() {#aef0129d256feb019adf09cd86b32ce91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropDbgRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase any DbgRecords attached to this instruction.</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/fenceinst/#a4d53f38a249b595b74ebe5c838377574">llvm::FenceInst::setSyncScopeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>.</p>

</div>
</div>

### dropLocation() {#a4576d69ed1543b06e5c41eb43b630bf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropLocation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop the instruction's debug location.</p>


<p>This does not guarantee removal of the !dbg source location attachment, as it must set a line 0 location with scope information attached on call instructions. To guarantee removal of the !dbg attachment, use the <a href="#ae8f5bf5cc06f696b52c709677df00fbf">setDebugLoc()</a> API. Note: it is undefined behavior to call this on an instruction not currently inserted into a function.</p>


<p>Declaration at line 708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a4b8faae4ff9e7434a1d226d03d15dcd2">getDebugLoc</a>, <a href="#a6a66ebb3aa12757479a3c88de77d78f8">getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d834f9897d15e3a6349063b5d637cd8">llvm::Function::getSubprogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a04df6c03772f85899d30bdcd06cbcd06">llvm::IntrinsicInst::mayLowerToFunctionCall</a> and <a href="#ae8f5bf5cc06f696b52c709677df00fbf">setDebugLoc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="#ae2bf20cca6e2a10783f868d80a7c0400">updateLocationAfterHoist</a>.</p>

</div>
</div>

### dropOneDbgRecord() {#a71583800b3bd19509d34cb223bef0aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropOneDbgRecord (<a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase a single <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> <span class="doxyComputerOutput">I</span> that is attached to this instruction.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 330 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### dropPoisonGeneratingAnnotations() {#a98ad976ff75d19b336e5315a2fdef8c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Instruction::dropPoisonGeneratingAnnotations ()</td>
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

<p>Drops flags, return attributes and metadata that may generate poison.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#ad4613def4002aa69721553e567ca4187">dropPoisonGeneratingFlags</a>, <a href="#ac2736cd830f7195cee466b7199217461">dropPoisonGeneratingMetadata</a> and <a href="#a5dcbbcb6c022f6f2c8b46a3e0a4821b5">dropPoisonGeneratingReturnAttributes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/bdce-cpp/#a54ab652f375db02ea7894a5f9a512d15">clearAssumptionsOfUsers</a>.</p>

</div>
</div>

### dropPoisonGeneratingFlags() {#ad4613def4002aa69721553e567ca4187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropPoisonGeneratingFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drops flags that may cause this instruction to evaluate to poison despite having non-poison inputs.</p>

<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="#a98ad976ff75d19b336e5315a2fdef8c5">dropPoisonGeneratingAnnotations</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ad2bfc3e2f7b1661868517e662ac7496c">optimizeBranch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a85d5ffd7db412c30d2e0dd46df6cf854">llvm::patchReplacementInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-canonicalizefreezeinloops-cpp-/canonicalizefreezeinloopsimpl/#aff534de0962628bba1821ef3c0821308">anonymous{CanonicalizeFreezeInLoops.cpp}::CanonicalizeFreezeInLoopsImpl::run</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a41c00c458f7416c93927bc2f332b3898">simplifyAssocCastAssoc</a>.</p>

</div>
</div>

### dropPoisonGeneratingMetadata() {#ac2736cd830f7195cee466b7199217461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropPoisonGeneratingMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drops metadata that may generate poison.</p>

<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a98ad976ff75d19b336e5315a2fdef8c5">dropPoisonGeneratingAnnotations</a>.</p>

</div>
</div>

### dropPoisonGeneratingReturnAttributes() {#a5dcbbcb6c022f6f2c8b46a3e0a4821b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropPoisonGeneratingReturnAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drops return attributes that may generate poison.</p>

<p>Declaration at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a330bbaf89b90196df6960be4724513c6">llvm::sandboxir::Type::LLVMTy</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a>.</p>


<p>Referenced by <a href="#a98ad976ff75d19b336e5315a2fdef8c5">dropPoisonGeneratingAnnotations</a>.</p>

</div>
</div>

### dropUBImplyingAttrsAndMetadata() {#a7cdb2c2c02ea6d97b993be4c2bd099e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropUBImplyingAttrsAndMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Drop any attributes or metadata that can cause immediate undefined behavior.</p>


<p>Retain other attributes/metadata on a best-effort basis. This should be used when speculating instructions.</p>


<p>Declaration at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 547 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a7b9a62f04a493cc8b8dadc64100578f8">foldOperationIntoSelectOperand</a>.</p>

</div>
</div>

### dropUBImplyingAttrsAndUnknownMetadata() {#ad73fe7caaafbee5d307aaef54b5f6ea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::dropUBImplyingAttrsAndUnknownMetadata (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt; KnownIDs={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function drops non-debug unknown metadata (through dropUnknownNonDebugMetadata).</p>


<p>For calls, it also drops parameter and return attributes that can cause undefined behaviour. Both of these should be done by passes which move instructions in IR.</p>


<p>Declaration at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### eraseFromParent() {#a601ee49a4c4e0babf29bd1cf09036570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator Instruction::eraseFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing basic block and deletes it.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an iterator pointing to the element after the erased one</p></dd>
</dl>


<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a492be44ddc8ccbf85c4ef650b6111868">llvm::LanaiInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-bpfirpeephole-cpp-/#a53d0de9bfb4d1d767e13293ec3bd9192">anonymous{BPFIRPeephole.cpp}::BPFIRPeepholeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#afbd7f8e7654d71a5771a4eaa8b622bd2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#aae3714d6fe11a1e8c559880caf67fbc7">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::create</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab84af206a9a08b9bf97eaadc87874c6c">llvm::OpenMPIRBuilder::createAtomicCompare</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a70356a38271d388e7c4b477cef0d7b2c">llvm::OpenMPIRBuilder::createCopyinClauseBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a28eff59d4446b7289de152d575bf3cd0">createMemMoveLoopKnownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#af1d16783f6f4b4d20427e93da6dd606f">createMemMoveLoopUnknownSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowermemintrinsics-cpp/#a6472f2a2e040373d958419bde7523539">createMemSetLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a5aade91cf963bd6be461be24ff3a284c">createTblForTrunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-rewritestatepointsforgc-cpp-/deferredreplacement/#a22b51efbb28485b0a26d255371306bcb">anonymous{RewriteStatepointsForGC.cpp}::DeferredReplacement::doReplacement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9d8f1df2d7125f8c7dc1af46433b3e70">llvm::dropDebugUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a52f9ebe90c5295cbd67350376bd57eb3">dropTypeTests</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac14ea98bd0e870e467ae0ddc75a9fa87">llvm::JumpThreadingPass::duplicateCondBranchOnPHIIntoPred</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#ab160dae4712e451dfdf248b1d9d78e10">anonymous{DeadStoreElimination.cpp}::eliminateDeadStores</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-guardwidening-cpp-/#a6d418914e8b20f42ccd313fd4f1f2585">anonymous{GuardWidening.cpp}::eliminateGuard</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a98b55a0d95b3926151545101e4f2aef9">llvm::OpenMPIRBuilder::emitCancelationCheckImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7b46fe24407e1a38fdf96093359165c1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::eraseFromParentAndRemoveFromShapeMap</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs/#ad32a933965ba0059ff2a3a322cc8b40b">llvm::objcarc::BundledRetainClaimRVs::eraseInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#af4e05bf48a81b884e707efa650560fbf">llvm::objcarc::EraseInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aa9dd0c9b2a49c91d814102c1d0c7b09d">eraseTerminatorAndDCECond</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08d3e8ce57fb65481a42b256d26c264d">llvm::expandDivision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cfb58d48c02daaaa8ee7e924e9fb36">llvm::expandDivisionUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6c6db1ba2b3654c01ec2363b2bc34ce4">llvm::expandDivisionUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a105cf64e7a2027cc32f43526f2e3df53">expandIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#aa507b512719f5e8d2b31c99f5534541b">anonymous{ExpandMemCmp.cpp}::expandMemCmp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0154d60f04a5d8549b44635852557f0">llvm::expandRemainder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a090725add53936fcebc89f58fc9a7da1">llvm::expandRemainderUpTo32Bits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27da54a97fcba955457048148b1fef99">llvm::expandRemainderUpTo64Bits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumptabletoswitch-cpp/#ab930da454be280eb307c612727543eb6">expandToSwitch</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a897212b76b4c9ae35b9489244d21f2a4">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a766195c3e47268a4ff4b48372acbd4dd">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#afffd4df1bba5cd5416f615e919a8fa66">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a8688fe7e12511bba710a19b4aaf027a1">llvm::RandomIRBuilder::findOrCreateSource</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#a80a071231d638f7bf7976f9eb6478a4f">findPHIToPartitionLoops</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a4e1612deb487473177dba9b03302386c">foldMemChr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#af950841a4443ffb7aff66ae75fee8442">foldURemOfLoopIncrement</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#adcbc4d7e8bf9926797b48a2b3603e3a4">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::forwardResume</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/integerdivision-cpp/#ae01a605dfa5a83e767612e4124bb6e57">generateUnsignedDivisionCode</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#af8ebafc2930bf25dfa6887c4b5bc2c33">getStrlenWithNull</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a2c1978d516a0154dd7f006e502ab4cfa">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::handleDynamicAllocaCall</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a614a737e40ceece782633b5cabbeab49">llvm::coro::BaseCloner::handleFinalSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aa8f270ce4d001ee9e7839aa11c607931">injectPendingInvariantConditions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a045ddd9cf89c401caf98eb3acad6b1a7">insertBoundsCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac306f2130698421f64f8a139faf38675">llvm::lowerAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4275af81cdeb1801deeae02ea2a0fb3b">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerBufferStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ad2fd6546e0f1cc42311962f4ad4b29cd">lowerExpectIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loweratomicpass-cpp/#a71a9a2cc77be9409f284b570894f16d2">LowerFenceInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a818d0dbc281d144e0f02a0a75c7af1ee">llvm::SITargetLowering::lowerIdempotentRMWIntoFencedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#a79f47e97963f500c113eb9bfee2e5b47">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileDP</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxintrinsics-cpp-/x86loweramxintrinsics/#aabc37fb487455e5268d389333bc5c890">anonymous{X86LowerAMXIntrinsics.cpp}::X86LowerAMXIntrinsics::lowerTileLoadStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ab10e6ab2669a5c752426570de655e7ce">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerUpdateCounter</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1f70470f7a7722fd55c58c81358107f2">mergeCleanupPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-objcarcapelim-cpp-/#a50b0a789cfd1294b6998186af696abf1">anonymous{ObjCARCAPElim.cpp}::OptimizeBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a996275d837998b396728990f8be0ef3a">OptimizeEmptyGlobalAtExitDtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a071cd98d76a1c63f215ad16388bfdfe2">llvm::JumpThreadingPass::processBranchOnXOR</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aaa116d55b70fa3716c4ee6f0eb3488d8">processCmpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a6d4d9e7eb49fd2f51ffcb0596b37c596">processMinMaxIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a580f44370be222c0b2be5a2a7fa3f048">processSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#af5d7aa7988108e9377f154cf6a22f02b">llvm::OutlinableRegion::reattachCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ad2390aa51b816a018aed94e4d354745a">llvm::LanaiInstrInfo::removeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#aa2ead3ae2cc059f459be46ce71ef20a5">removeCoroEndsFromRampFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a82f896385cac84a2e477159ad31ace74">removeIntrinsicUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#a4601f3a29dbb6d4ea9da7f4dd26e2ae7">removeMarkerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#af04adca83664ebd947723470c4da58aa">removeUndefIntroducingPredecessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a7e2cad7ab18db9a3c940afc609c223dc">replaceCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab289568caaa6647ee577a06e6e12499a">replaceCoroEnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a8543371395854bee27033b8e24836cb0">replaceFrameSizeAndAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-spirvstructurizer-cpp-/#a55f5674c6ed1c3e224388d258b79fcc5">llvm::anonymous{SPIRVStructurizer.cpp}::replaceIfBranchTargets</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandvectorpredication-cpp/#a56afeeb4fb49342e6cbde202cacabdfc">replaceOperation</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#ad39fccc0304ca0ff35a57687380ca595">anonymous{CodeGenPrepare.cpp}::SimplificationTracker::ReplacePhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#acd162cfe23d841a49056ce6436dd2075">replacePrepare</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a87b0b481058d1def42e0b3a6564ed93d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceSplitDoubleCallUsages</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb5b48f89efd60ea799bb09abc1971ba">llvm::rewriteLoopExitValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/indirectbrexpandpass-cpp/#a241c916e6342b5f14a7492f1b91cc715">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#ae78c54dce6798892e47ca90660f9a8f6">RunTermFold</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ad54a3c6c671e583284ff935bfde3368c">simplifyOneLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9f3928b341e4412b8b66b794896014f0">simplifySuspendPoint</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#aedc5ca2a4ef6009dc69a410d60c7eeaf">llvm::coro::anonymous{SpillUtils.cpp}::splitBeforeCatchSwitch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32aaa22eb69c944393cd5a1c79fa0d35">llvm::SplitBlockAndInsertSimpleForLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a216b0f52f244182222da5b7fcbc8ca01">stripDebugDeclareImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#a5ca29e57ad15a06f70b6676ec2665f34">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::transformAMXCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a428f7b53e32934ae46a9aa35d3028d87">tryToMergeLandingPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67474fe1bb82a093f3ad2e9ad2d7f7c4">llvm::TryToSimplifyUncondBranchFromEmptyBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/makeguardsexplicit-cpp/#ac97dd263948d6205b380c1781ebb946d">turnToExplicitForm</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dfajumpthreading-cpp-/#a37fd6f31f78116956f457b105ab4513c">anonymous{DFAJumpThreading.cpp}::unfold</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af78eb969de6e17fe20fa8834d3e9c9aa">llvm::UnrollLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a81c8a5368d02d0b52654a3efe83dec38">llvm::LoopVersioning::versionLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a29df0cec2acb067cfcb09eeeb726c7db">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyreftypemem2local-cpp-/webassemblyreftypemem2local/#a9ad64c3f2f8f51ff7edc41ed024e022b">anonymous{WebAssemblyRefTypeMem2Local.cpp}::WebAssemblyRefTypeMem2Local::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a32bd3fc6040488f54b8fb322216218a5">DataScalarizerVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/storefatptrsasintsvisitor/#a77976478ff4af840d8dc298cd7bb1b65">anonymous{AMDGPULowerBufferFatPointers.cpp}::StoreFatPtrsAsIntsVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a9a06c7811f1ea67a51787ab0de806b5a">llvm::ObjectSizeOffsetEvaluator::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae42afee90ff90eb3b8fa78ad91d8858b">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitSqrt</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### eraseMetadataIf() {#af5b08506925637f8addbc11e2190dde6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::eraseMetadataIf (<a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(unsigned, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *)&gt; Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Erase all metadata that matches the predicate.</p>

<p>Declaration at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1626 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#ab1198eef44b311a7984cfc8fc97fac6d">llvm::Value::eraseMetadataIf</a>.</p>

</div>
</div>

### extractProfTotalWeight() {#a51d5735829e1f043630dd403f01d4219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::extractProfTotalWeight (uint64_t &amp; TotalVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve total raw weight values of a branch.</p>


<p>Returns true on success with profile total weights filled in. Returns false if no metadata was found.</p>


<p>Declaration at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1788 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ab4e05d690df389b8b1477c90387b575f">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a> and <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>.</p>

</div>
</div>

### getAAMetadata() {#aade703948f2fdabdc65868bdf42d3141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAMDNodes Instruction::getAAMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> metadata for this instruction.</p>

<p>Declaration at line 494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1750 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a1f496e54accb2cbe919fb456cb703f1a">llvm::Value::hasMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontextimpl/#a6577bf24ddcb2a2cd401ee3e4704527a">llvm::LLVMContextImpl::ValueMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a8f64e8576d57bb362e730214c7e6fae9">foldLoadsRecursive</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a6c1bd5fd8ec3eeb7320cd9d457b0f164">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46d61c561714322cb42bd3db9f1609fa">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1a5189be752e56bf8343fd72f45720ee">mergeConditionalStoreToAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>.</p>

</div>
</div>

### getAccessType() {#a765d7abba7daa905e301027dd2fd1086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Instruction::getAccessType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the type this instruction accesses in memory, if any.</p>

<p>Declaration at line 817 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1100 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7f4680b383ce7138bc2c12de282b14b4">getAccessType</a>.</p>

</div>
</div>

### getAllMetadata() {#aad11fd49455cd391b69667d5bcbc5df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Instruction::getAllMetadata (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &gt; &amp; MDs)</td>
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

<p>Get all metadata attached to this <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>


<p>The first element of each pair returned is the KindID, the second element is the metadata value. This list is returned sorted by the KindID.</p>


<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#a565f546ad95bd3a9bbe9a1e5040803f0">hasMetadata</a>.</p>

</div>
</div>

### getAllMetadataOtherThanDebugLoc() {#ab025fe91d5f5c6ff951cb7e1f5c2bf64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Instruction::getAllMetadataOtherThanDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &gt; &amp; MDs)</td>
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

<p>This does the same thing as getAllMetadata, except that it filters out the debug location.</p>

<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a3d200b1568f70b28ae0eb9bec58d6690">llvm::Value::getAllMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a>.</p>

</div>
</div>

### getDataLayout() {#af65afd02332c4f21c2fab7d217d6600f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; Instruction::getDataLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the data layout of the module this instruction belongs to.</p>


<p>Requires the instruction to have a parent module.</p>


<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae54a643a9f9d83374bb4d7d22d4662d7">AddAlignmentAssumptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a452155536772ef01d3c028f7284ecd2b">llvm::coro::anonymous{SpillUtils.cpp}::collectFrameAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7524dbb403a24e9e73d4bca80baa768d">llvm::JumpThreadingPass::computeValueKnownInPredecessorsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#aa88371693bc18186386b04e8c45a30e4">llvm::VPlanTransforms::createInterleaveGroups</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#af05ad96486c97ea7158a65507aaee0ef">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::createReplacementValues</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a1f1f1359a986d8e4d1b107ae4c524a32">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInMemoryIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afcb58333497c40468d7889705a5d0b03">foldSelectICmpAnd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac83b2f6d1a223c7b4ac9eb3783ee1465">foldSelectWithConstOpToBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a6c1bd5fd8ec3eeb7320cd9d457b0f164">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a46d61c561714322cb42bd3db9f1609fa">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a18e5a3f1d71ba10a624f2a8e5121cf1f">llvm::MemoryLocation::get</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a8a8741af2dcfc3312679330e1069c734">anonymous{AddressSanitizer.cpp}::AddressSanitizer::getAllocaSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#a892fff96fbddc1bc777dd9b3ca02b116">llvm::memtag::getAllocaSizeInBytes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acdec81ddbe2a44db51de1226fa1ff5f0">llvm::getAllocSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a11d6de2bddc669af3e9b358e46e38e9e">getAtomicOpSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a48ac978d44f5d426d300a400142708b5">getAtomicOpSize</a>, <a href="/web-llvm/docs/api/classes/llvm/demandedbits/#a34469f29a61b3bcb61f8e2a9af25be65">llvm::DemandedBits::getDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a5fe252ea76c22a7e9bed5af0446d4fdb">getGEPInductionOperand</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-stacksafetyanalysis-cpp-/#a9cd19dcbd2a7e975097b8bd795ac1a98">anonymous{StackSafetyAnalysis.cpp}::getStaticAllocaSizeRange</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aeba325403d8d6430ee4a41b2cea631f5">llvm::isDereferenceableAndAlignedInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a3e874f5073fd59211348a2ea23e9d0ce">llvm::GCNTTIImpl::isInlineAsmSourceOfDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a831a5dec04e512d616fccb6e1f474e79">isLoadInvariantInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a88b0909bfe0684c1c286237dd9985ce9">lookThroughCastConst</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ad190bc43c7fc8555debc7228fc5364b9">llvm::ARMTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a1321465508b2b54862b90ca404386e06">shortenAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9e745a45e9d5aa38916ad1fabf333403">llvm::SITargetLowering::shouldExpandAtomicCmpXchgInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae71573dba191b26eda0d5ea27b81ef62">trackInlinedStores</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a0bdd0669ab7b82ba709bfedcb751dcc3">valueCoversEntireFragment</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-mergeicmps-cpp-/#aaa39273101436002f3e3bd16293327be">anonymous{MergeICmps.cpp}::visitICmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a180c318fe2fe1f2f7d4f4ca4dccfd2f1">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntToPtrInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a57aff0646c7151c4158d839c386332cc">visitIVCast</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aa9a049f0da67dd58d8854ac1de525ac7">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a5b6ac7240be29b8a3a611a734a45d4a6">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitPtrToIntInst</a>.</p>

</div>
</div>

### getDbgRecordRange() {#a431be97c0e4d03f713d927197cdcfff0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; simple_ilist&lt; DbgRecord &gt;::iterator &gt; llvm::Instruction::getDbgRecordRange ()</td>
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

<p>Return a range over the DbgRecords attached to this instruction.</p>

<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a0172245e9f9a9097b5d403ab70348bdd">DebugMarker</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8bca4688ad9d211ceeaba65271a9fbfa">llvm::getDbgRecordRange</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3bc23a6f4df3d833013de35759651112">llvm::remapDebugVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/memtag/stackinfobuilder/#a2a198373b43abedb70ae454c1111cdc8">llvm::memtag::StackInfoBuilder::visit</a>.</p>

</div>
</div>

### getDbgReinsertionPosition() {#ad99db073c46dd0de2c530c64baf77cb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DbgRecord::self_iterator &gt; Instruction::getDbgReinsertionPosition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an iterator to the position of the "Next" <a href="/web-llvm/docs/api/classes/llvm/dbgrecord">DbgRecord</a> after this instruction, or std::nullopt.</p>


<p>This is the position to pass to <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ac15f880505f4cbe66f407f4e42a8b8b6">BasicBlock::reinsertInstInDbgRecords</a> when re-inserting an instruction.</p>


<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="#a24a7664d83746bcda035bddeb773eaae">copyFastMathFlags</a>.</p>

</div>
</div>

### getDebugLoc() {#a4b8faae4ff9e7434a1d226d03d15dcd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; llvm::Instruction::getDebugLoc ()</td>
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

<p>Return the debug location for this node as a <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a>.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-machinedebugify-cpp-/#aa828309ad55f30355cd07c12017a2263">anonymous{MachineDebugify.cpp}::applyDebugifyMetadataToMachineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a420bedce165a865417db21cdc88307cb">BreakUpSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#ad696038e18d6965dc078902075026d9b">checkIfSupported</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sampleprofileprobe-cpp/#aba5d19de3041eb7a532c035bbb898d3f">computeCallStackHash</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a0775987674a0fc922481db1966a5fdf5">llvm::VPRecipeBuilder::createEdgeMask</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuprintfruntimebinding-cpp/#a0ed7b2c2e7da5af8cafe5996248e4889">diagnoseInvalidFormatString</a>, <a href="#a4576d69ed1543b06e5c41eb43b630bf1">dropLocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7b3e8a01dfede6141c79e012a44ec9e4">llvm::extractProbe</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9eff8d0da220bd73f164b1aeef7af20">llvm::extractProbeFromDiscriminator</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a219e9fac05a219d48a97e03304f84613">anonymous{SampleProfile.cpp}::SampleProfileLoader::findCalleeFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a2c88d6b3f033c87b7304db47133a930e">anonymous{SampleProfile.cpp}::SampleProfileLoader::findFunctionSamples</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#abf8457f6ea82a821ee3fb08dae6246d9">anonymous{SampleProfile.cpp}::SampleProfileLoader::findIndirectCallFunctionSamples</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a2ed4f37fbda15a9c05f333fde59e9fbb">fixupLineNumbers</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a36b7410be1f86b52970bb1381904e282">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::foldBinOpIntoSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a83088027da72950b627f9200965fb55b">llvm::ReplayInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/assignmenttrackinganalysis-cpp/#a4514f516df040b468e552a28163b3747">getAggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a30791b6c651e6313b0aab3f01da9d57b">getAggregateVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#af9a5eace41510a920670a82474022c7a">llvm::SampleContextTracker::getCalleeContextSamplesFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a87ef919ea907189c22b74f604a645b40">llvm::getDebugValueLoc</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa583009e488330c099a4ab23e2536d2f">anonymous{SampleProfile.cpp}::SampleProfileLoader::getInstWeight</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuswlowerlds-cpp-/#ad29b8e5faa8d8977329b9bbc73867612">anonymous{AMDGPUSwLowerLDS.cpp}::getOrCreateDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#aaf95913e52851622a35765cc28adf643">getOrCreateDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a94b383e649f60242503ff47c799fd22e">HandleByValArgumentInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aab4d6b37c7f97bad2b1f441dc3fd43e0">llvm::hoistAllInstructionsInto</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a5a020f0ab461a1f6e3b87aff314bd040">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ab994e75dc5cae892a87ae9a86d4b767a">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af414e22c02fcc9ff3ce2d81ee8d3cfcb">llvm::AMDGPU::instrumentAddressImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/nextnodeirbuilder/#a0069210926fba78c824a7a41edee915f">anonymous{MemorySanitizer.cpp}::NextNodeIRBuilder::NextNodeIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a9ace593776041510de450a2eccc56eeb">operandWithNewAddressSpaceOrCreatePoison</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6c837ffd3a1932f53de13120ad1551a">llvm::InstCombinerImpl::PHIArgMergedDebugLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ad47460e620c33c83309f749ea8f34c6b">processSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#ace24fe825742577e78df32f725ad7b26">processSIToFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a75f37a01df1919449e22c14ec860d8b1">processSRem</a>, <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>, <a href="/web-llvm/docs/api/classes/anonymous-looploadelimination-cpp-/loadeliminationforloop/#acc9ee85c11fa2173c85a1ba82797d9fb">anonymous{LoopLoadElimination.cpp}::LoadEliminationForLoop::propagateStoredValueToLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6feadb2c8399ea3ed92085701f618b51">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a645f6e970e94d7ca51922b3932338f51">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumeratorOrZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8a96c9b1143670a73852464de9950e8e">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceSRemWithURem</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irtranslator/#a2fa3a523a1812aeda17891575f852ce9">llvm::IRTranslator::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ab30094b924bc7333b5bf134d7985ca18">llvm::FastISel::selectOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#adb1dafd461988f3d8e687eabb99e108d">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a957b517efddeb68617e18ffef3b64683">updateForIncomingValueLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a4d1d15c0a00a9b9391977c8f482e0428">updateScopeLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#adaf155c02ba4c5b8ec6d8d72b50e0f91">upgradeDbgIntrinsicToDbgRecord</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslicerewriter/#ad5e4a813f4c680afb71906bfbf32d01a">anonymous{SROA.cpp}::AllocaSliceRewriter::visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#ae534b46b7607eb604ddd8c66baa8d2d1">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitFDiv</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a8369ab820502d8565628a7691353538a">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicCompareExchange</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a7c97c0b1f7463c3f6d909f1e95263e58">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getFastMathFlags() {#a9a167f91db810097d281b1ed627f4575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags Instruction::getFastMathFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience function for getting all the fast-math flags, which must be an operator which supports these flags.</p>


<p>See LangRef.html for the meaning of these flags.</p>


<p>Declaration at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 651 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a720b783746c2f472ba1a810c8a3fe600">expandAtan2Intrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#af5dffe23851d819cc3ed8126fdf8a42f">foldAddSubSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac633a4c4d399457c76640f7dea5ebcd7">llvm::InstCombinerImpl::foldFMulReassoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a4d180adab34368b65e2a43f64c7de814">getISDForVPIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandvectorpredication-cpp-/#a59db4883933b9a437c397b1db4d32c91">anonymous{ExpandVectorPredication.cpp}::getNeutralReductionElement</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf62ca503c047621e9b9047c548f231f">llvm::matchDecomposedSelectPattern</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe/#aee1dbc25df0d2b70bd4eb984cd3be380">llvm::VPReductionEVLRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a52161486f40f867a8767dc3fef77ee9d">llvm::VPReductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>.</p>

</div>
</div>

### getFunction() {#a6a66ebb3aa12757479a3c88de77d78f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * Instruction::getFunction ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the function this instruction belongs to.</p>


<p>Note: it is undefined behavior to call this on an instruction not currently inserted into a function.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a65edce9c8505e3d3b9c0d90794458288">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAccessedPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopunrollpass-cpp/#a76ff59dafad74689cfe1966b0ed9fa3c">analyzeLoopUnrollCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/callvalue/#abf2170fc4c00058df8ef27562be3fb39">anonymous{EarlyCSE.cpp}::CallValue::canHandle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a495e0c2946cb54155fefdf25d2cf8454">canSimplifyNullLoadOrGEP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24ff4e69025be7564b19025b93cac8d9">canTransformToMemCmp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ab7660504ac6ac15f209047da7f39755a">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::checkUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanocaptureimpl/#a9e78a16876b18d86097c67afa39bc090">anonymous{AttributorAttributes.cpp}::AANoCaptureImpl::checkUse</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a28ddcf99fafe235217356e423dcdd084">anonymous{ConstantFolding.cpp}::constantFoldCanonicalize</a>, <a href="#a4576d69ed1543b06e5c41eb43b630bf1">dropLocation</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa59c4ae8c95bb222039942e9ba995c3e">llvm::expandAtomicRMWToCmpXchg</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#aa507b512719f5e8d2b31c99f5534541b">anonymous{ExpandMemCmp.cpp}::expandMemCmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#afffd4df1bba5cd5416f615e919a8fa66">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a790e9b70f12899a4cb2aefd33826ee7d">llvm::AArch64TargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/typemetadatautils-cpp/#a64702c7c3e6913b9076666d4e071b35d">findCallsAtConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfoimpl/#a7dcc7e60c55b76d16688ee3b04f804e4">anonymous{AttributorAttributes.cpp}::AAPointerInfoImpl::forallInterferingAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#ad15d45b871d3111e8da4f9b394d7c83f">forwardStoredOnceStore</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af59c587eddc75748a1e201369cd3dbac">llvm::InstCombinerImpl::freezeOtherUses</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a83088027da72950b627f9200965fb55b">llvm::ReplayInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/constantfolding-cpp/#af3c8f5caa60e75e0b9aaad6e11a88722">getInstrDenormalMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#aac5cfc936b6963f4e848982328d39e8e">getSubprogramOrNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae2ebbbbc990e3d932da5d0d0ea255f42">HandleByValArgument</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapotentialvaluesfloating/#a9dfa7d879ffc886a8014f1c9714ec166">anonymous{AttributorAttributes.cpp}::AAPotentialValuesFloating::handleCmp</a>, <a href="/web-llvm/docs/api/classes/anonymous-complexdeinterleavingpass-cpp-/complexdeinterleavinggraph/#a257b23cbc3b86d61dc953bad7beeaa5b">anonymous{ComplexDeinterleavingPass.cpp}::ComplexDeinterleavingGraph::identifyNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#ae3b43649c18ab9e63c1be61b93dd7031">insertLifetimeMarkersSurroundingCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#af0885df5b78cc732639a9d52a87d040e">insertSpills</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a100024af963f34d2ddd84c345a0caea9">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::instructionCanReach</a>, <a href="/web-llvm/docs/api/structs/llvm/instrumentationirbuilder/#a448f037b3ebf53dbba70a9ce7a89cad4">llvm::InstrumentationIRBuilder::InstrumentationIRBuilder</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5ee07316c71711c956769e3dd902079e">isAtomicRMWLegalXChgTy</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadfloating/#a64ffcd16d1457fc57339e15655b68627">anonymous{AttributorAttributes.cpp}::AAIsDeadFloating::isDeadFence</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#ad96e48bda36fb8540a3973cee993c5b3">isKnownNonZeroFromAssume</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a94e5917e7d2f3648965d7c69deb17ae6">llvm::isKnownToBeAPowerOfTwo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a86026627b644e50527898aad0747b3e5">IsOperandAMemoryOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#adc52b79e64dcac96ea901cbfab1ccc52">llvm::AA::isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aainterfnreachabilityfunction/#a6c50862efd6adb69da166ddce9dc912c">anonymous{AttributorAttributes.cpp}::AAInterFnReachabilityFunction::isReachableImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#a1ec1a38ef077070bf9d3760ddbbcfe24">llvm::AA::isValidAtPosition</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl/#ade252ec650f1f043ccf664b66c038d38">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isValidCtxInstructionForOutsideAnalysis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac963dddf8453fc717992d3ce36a27d8b">llvm::lowerAtomicRMWInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a665e880cc41e9fd97416741590e2e0d0">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::manifest</a>, <a href="#a2711d3bc7c6c769a8f34c7fc3937169d">mergeDIAssignID</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfo/#aee580d948709366b6a676f8b48460137">llvm::LoopInfo::movementPreservesLCSSAForm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/structs/llvm/alignmentfromassumptionspass/#a42ba71cba0e3d5e1b4e5395fd080016d">llvm::AlignmentFromAssumptionsPass::processAssumption</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9469fd548994812c12e4c10d42ec82a3">llvm::promoteCallWithIfThenElse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroelide-cpp/#a5d9225a91194b62b22073916440c9f23">removeTailCallAttribute</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6feadb2c8399ea3ed92085701f618b51">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#aa3057ac8aef166e271195a0f465d97f2">llvm::CoroIdInst::setCoroutineSelf</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a874edeab85418837bb65d4d2ec4c5d0b">llvm::SITargetLowering::shouldExpandAtomicRMWInIR</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a3ef524444504c738f1da4b4fb0b5a238">simplifyInstructionWithOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a761b3c02cd196cb5f6fb019bcd86866e">llvm::OutlinableRegion::splitCandidate</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#ae65b4ddecd3ffe58677c92f5ac0d26d8">suppressSpeculativeLoadForSanitizers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a1ae624f5747718933b1dabc6a03689aa">tryToOptimizeStoreOfAllocationToGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8b0688ee292d40a24ba7117b39d426bd">llvm::InstCombinerImpl::visitReturnInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a43a1d060dacb05eb645cf91ea86d7bd3">llvm::InstCombinerImpl::visitTrunc</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### getFunction() {#a37fa134791b478ff5564bbb05255ca94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::Instruction::getFunction ()</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>

</div>
</div>

### getInsertionPointAfterDef() {#ad2b97a10a92351d0df82c9759ad1ee07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; BasicBlock::iterator &gt; Instruction::getInsertionPointAfterDef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the first insertion point at which the result of this instruction is defined.</p>


<p>This is <em>not</em> the directly following instruction in a number of cases, e.g. phi nodes or terminators that return values. This function may return null if the insertion after the definition is not possible, e.g. due to a catchswitch terminator.</p>


<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="#ae6189d19092044a37414c05526874a06">moveAfter</a>.</p>

</div>
</div>

### getMetadata() {#a6c09737e146b2d816c911a047ac67ba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::Instruction::getMetadata (unsigned KindID)</td>
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

<p>Get the metadata of given kind attached to this <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>


<p>If the metadata is not found then return null.</p>


<p>Definition at line 426 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#aef569d822dbf572ae71954d6831ce8a9">llvm::Value::getMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="#a9a7c63edb94ce4fab2a5bb34dbf6079a">addAnnotationMetadata</a>, <a href="#a6762e9e611c29b13a5c94bf8488fe798">addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a5da1dcc92515b7cdd28ce936d6488964">llvm::LoopVersioning::annotateInstWithNoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a3c142cb2c6d5ca1e5f142d4062839944">combineMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a125e2946cdcc7555d8f5c383681d7097">convertMetadataToAssumes</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ae465cfd07a3ac2e84847e670d92ae8ad">llvm::DbgVariableRecord::createLinkedDVRAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvstructurizer/#a52c61b3548ffc6f5088b78dc45141354">llvm::SPIRVStructurizer::createOpSelectMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a3cd8a9205d8cc6d024b6e6344a72aca0">llvm::IRBuilderBase::CreateSelectFMF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a259334992127b809a034f025fc2bd13f">llvm::diagnoseDontCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp/#a9b051a25ba281897b4dc62df58312b7e">emitDbgAssign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a92fe4b2aa97a12f4a947e5ce99f05b15">foldTwoEntryPHINode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#af30af67184fc4c122edfcdd3a405d28a">llvm::at::getAssignmentMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ad3e63520dcd2b8f8aa1b2e66e734a575">getBranchWeights</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#aa992dd7420a71df6149dd3437c949245">llvm::at::getDVRAssignmentMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#aa116214bf0f5cf6201935447b27334e8">getFromRangeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#afbcd78588d5235f99698b5c30f591382">llvm::Loop::getLoopID</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7f27e470647cae7ae9225bae804bf006">llvm::MDNode::getMergedProfMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/scopednoaliasaaresult/#afc3838a129ca64f34b13c9227c967e98">llvm::ScopedNoAliasAAResult::getModRefInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/typebasedaaresult/#a121ec6b783769a5612f6cc225a2838b2">llvm::TypeBasedAAResult::getModRefInfo</a>, <a href="#a23ce9747bfbb053cf7ac18abbe4a1006">hasMetadata</a>, <a href="#a18993ec84b78442c34fefdd6d3b3f693">hasMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/structurizecfg-cpp/#ad1d9e6fe4974ee0754beaf3d7756bf20">hasOnlyUniformBranches</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#afdbe575a191d9f3b5b6cef8212745dc0">anonymous{LICM.cpp}::LoopPromoter::insertStoresInLoopExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51d22a1ed809d7cb1c1eb46c820c8226">llvm::intersectAccessGroups</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a08cd264874d8deee9a2bdda9b9461e29">isProfitableToSpeculate</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d5216a94e3d3c5aced721cc4f25dc7e">llvm::mayHaveValueProfileOfKind</a>, <a href="#a2711d3bc7c6c769a8f34c7fc3937169d">mergeDIAssignID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a74b8b820b4b2d53dd53ba32821887473">PropagateCallSiteMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a380713e3d0da9090dbc68193076703b7">propagateMemProfHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a81fe0543b342a120ede7c69eeed77729">propagateMemProfMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a1c4994ac805321b7fa03617dff656ad8">shouldFoldCondBranchesToCommonDestination</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a40f7c70fc970f25f1c32e8b2c28662ec">SimplifyCondBranchToCondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#ab10b653a914cecca232400be7a563633">translateBranchMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#abf86ae2ede168d53dec70f0b0cb9d9b5">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a070509ca4afed69062174feb05ef7022">anonymous{InlineCost.cpp}::CallAnalyzer::visitBranchInst</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>.</p>

</div>
</div>

### getMetadata() {#aacd004fda4b063f84d19f53ca2f058cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * llvm::Instruction::getMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Get the metadata of given kind attached to this <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>.</p>


<p>If the metadata is not found then return null.</p>


<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#a565f546ad95bd3a9bbe9a1e5040803f0">hasMetadata</a>.</p>

</div>
</div>

### getModule() {#a4ba3a5be6c0e9b9e8a525de055836733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Module * Instruction::getModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the module owning the function this instruction belongs to or nullptr it the function does not have a module.</p>


<p>Note: this is undefined behavior if the instruction does not have a parent, or the parent basic block does not have a parent function.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a65edce9c8505e3d3b9c0d90794458288">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAccessedPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aebae63f31076e8c0dfe153c45a730497">addAssumeNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a855f472cab89fb74cbc7075b164d78f0">llvm::buildAssumeFromKnowledge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#ad623ba85ece2827b2a9c853e95ee24fc">createCoroSave</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a6afb7e7298c87508bd965772db54ec19">llvm::LoongArchTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a241b3032c605e4faafb173c3adf15105">llvm::RISCVTargetLowering::emitMaskedAtomicRMWIntrinsic</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a62f9944dba24143c8954964d7dff45b8">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToFPCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#aa231edc47a3993eaf9c7aa2bb324e2f5">foldSelectFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a1bf4aeb6f1b186d451eb7f2536b76c2e">foldSelectToCopysign</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a777bef8b513df8776aec8f3cf9ce066b">llvm::InstCombinerImpl::foldVectorSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a3296ab5af4e3c77a57810f97ab19e088">llvm::LazyValueInfo::getPredicateAt</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#ad10df0e6ccca0fc951b845e3a007e385">llvm::LazyValueInfo::getPredicateAt</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofincrementinst/#afe7c16bf1ea59bb69a0e02f5d80aadda">llvm::InstrProfIncrementInst::getStep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/dibuilder/#a5a6937fcd639ac78a93b48ab6624e957">llvm::DIBuilder::insertDbgAssign</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a6fe2425902ca5775f3b350cfbe49cc8f">llvm::TargetLibraryInfoImpl::isCallingConvCCompatible</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6cbcd096f254563525e65e58557ed901">llvm::AArch64TargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/libcallsimplifier/#a73c4a774eb638f963533b77f7124293b">llvm::LibCallSimplifier::optimizeCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9784a018b2dd6a85ee8a70f5f5ab3d02">llvm::replaceAllDbgUsesWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a08f16f302c998119c978d7ce93b4c569">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::tagAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aadcf41a9f704494210a217eb089678b3">tryToReplaceWithGEPBuiltin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ab013e5e37e15eee5725a24b6a6df2416">llvm::AMDGPULibCalls::useNative</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a89ab5eaec7693029761c8d0b3ded3b00">llvm::InstCombinerImpl::visitBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7eb1707b3b9ea994955ac9d230535261">llvm::InstCombinerImpl::visitFPTrunc</a>.</p>

</div>
</div>

### getModule() {#a57dc99c7685e4c2fa6c27ba7e9d26d87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module * llvm::Instruction::getModule ()</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>

</div>
</div>

### getNextNonDebugInstruction() {#a91bd28adea418a08cec78b72413d9d45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * Instruction::getNextNonDebugInstruction (bool SkipPseudoOp=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pointer to the next non-debug instruction in the same basic block as 'this', or nullptr if no such instruction exists.</p>


<p>Skip any pseudo operations if <span class="doxyComputerOutput">SkipPseudoOp</span> is true.</p>


<p>Declaration at line 896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1226 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a0050ea5bb47a2b75ed9e8239bcd469a6">findStoresToUninstrumentedArgAllocas</a>, <a href="#a475658532adbdbbba2c62d48e9b8d1f1">getNextNonDebugInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a6d53d8df2e0ea40eee8a7349563a9df7">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedInAlignedRegion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributor-cpp/#a365173e63bd73b3ee58033678429636e">isPotentiallyReachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a>, <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a761b3c02cd196cb5f6fb019bcd86866e">llvm::OutlinableRegion::splitCandidate</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a4d1d15c0a00a9b9391977c8f482e0428">updateScopeLine</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a85e25362e2d9d1222397368e9ba7f9ce">llvm::InstCombinerImpl::visitFenceInst</a>.</p>

</div>
</div>

### getNextNonDebugInstruction() {#a475658532adbdbbba2c62d48e9b8d1f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::Instruction::getNextNonDebugInstruction (bool SkipPseudoOp=false)</td>
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



<p>Definition at line 897 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a91bd28adea418a08cec78b72413d9d45">getNextNonDebugInstruction</a> and <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>

</div>
</div>

### getNumSuccessors() {#a3287172f2d13af086e6d66364e8c6de3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Instruction::getNumSuccessors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of successors that this instruction has.</p>


<p>The instruction must be a terminator.</p>


<p>Declaration at line 973 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1272 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#aefa60bfe67b4721c395ce966ac73b439">llvm::AtomicRMWInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a5d1f392e4e23933104dbc6f0a5e78497">llvm::AtomicRMWInst::setOrdering</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-vplanhcfgbuilder-cpp-/plaincfgbuilder/#a43fb01f4c8f7fbffd8a1cec9ed5b04ab">anonymous{VPlanHCFGBuilder.cpp}::PlainCFGBuilder::buildPlainCFG</a>, <a href="/web-llvm/docs/api/classes/llvm/branchprobabilityinfo/#a54c3911cf4abbcd272fa99a303823942">llvm::BranchProbabilityInfo::calculate</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a4ca10cc5976994ee1c01be4b019c1ee6">llvm::FunctionComparator::compare</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a089d9b5caf2479e6b87f94c73e5b1f70">getBestDestForJumpOnUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a9293c2849df988b06fecea7e1b021fee">getBranchHint</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d/#a02f466eae018c75689a0189cb5f29524">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/funcpgoinstrumentation/#a5e10295899c921b1730c88017d1bc4d6">anonymous{PGOInstrumentation.cpp}::FuncPGOInstrumentation&lt; Edge, BBInfo &gt;::getInstrBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/gcovprofiling-cpp/#ab74216e0ce40d85e6c843637018ce553">getInstrBB</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a1bcb8bb92d8385a81a07659c6e1ec6fc">llvm::MustBeExecutedContextExplorer::getMustBeExecutedNextInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/regiontraits-0f5d60cddaa2a9bddfbb61dc941a8926/#a6b3f1d531ccfa41bf01f4f3ec258b5ad">llvm::RegionTraits&lt; Function &gt;::getNumSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d6efe0db0843950c3cfff2cdbdac41e">llvm::isCriticalEdge</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a29da820d4c19ac64f750762012fd13ca">anonymous{IndirectCallPromotion.cpp}::isDestBBSuitableForSink</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#a19fefaa90777f772a3db9ce94e5209ab">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::isEdgeFeasible</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a30207ff92cc09d50e4f6e188de0f59ed">llvm::JumpThreadingPass::maybeMergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#a1ad5c109b5218ec1d5f5fcd6390636ba">replaceConstantExprOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/pgousefunc/#a693592fa7e2d0950e30d14f38c333f9b">anonymous{PGOInstrumentation.cpp}::PGOUseFunc::setBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/pgoinstrumentation-cpp/#a80d168922933443e08f865909fe33799">skipPGOUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abcdf593678862fd49e4ece5829b1bb00">llvm::SplitAllCriticalEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6aad9a57bb45319be236a2c47cf23a5e">llvm::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf83581f514774264d616eef5706cf6e">llvm::SplitEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>.</p>

</div>
</div>

### getOpcode() {#ab4e05d690df389b8b1477c90387b575f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Instruction::getOpcode ()</td>
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

<p>Returns a member of one of the enums like Instruction::Add.</p>

<p>Definition at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#ab4e05d690df389b8b1477c90387b575f">getOpcode</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a4a6ca5a5b87bd84231be9d8dbec46c1a">llvm::Value::getValueID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#a492be44ddc8ccbf85c4ef650b6111868">llvm::LanaiInstrInfo::analyzeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/phitransaddr-cpp/#a2c64eb39d5bdd73f8ac9d47338931ce8">canPHITrans</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aad8311debca961aeee16791414f9efa1">llvm::SCEVExpander::canReuseFlagsFromOriginalIVInc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp/#ac79b06c4793c56d8155eb7c18aafa1d3">checkIfSafeAddSequence</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#aee57a451f8dea6781fa17e7728ee78b5">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneArithmeticIVUser</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a7ee5e663199f460b53a80855073e21bd">anonymous{SimplifyIndVar.cpp}::WidenIV::cloneIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ad59bafaeacd51c2b1e6251488039d29a">llvm::VPInterleaveRecipe::computeCost</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a52d249cc9856fb556e92d5a1b03e5e80">llvm::InstCombinerImpl::convertOrOfShiftsToFunnelShift</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#aca631a010bfa5a055b7a07fe9e68f7e9">llvm::CallBase::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a48f061a53492f73dc9d82812f4350b44">detectPopcountIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a3a0cafd820690b73a6169ab519d77d2a">detectShiftUntilLessThanIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a596e8b6e6b71f454b18f982f947e5e03">doesInTreeUserNeedToExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a46482b2bd77de78d901bfa2fd727ba0e">expandFPToI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a0f218e3451638c34910744dedf0b71ac">expandIToFP</a>, <a href="#a51d5735829e1f043630dd403f01d4219">extractProfTotalWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a6914b95d1fcf7a5aca24fe82bf4100c2">llvm::RISCVTargetLowering::fallBackToDAGISel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aa5aa7648807905cd7b63153812029fe2">findDemandedEltsBySingleUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/breakcriticaledges-cpp/#aa8ede4d4de2237a9b4f534d1be96ac75">findIBRPredecessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a568e85197421e091a259bf80e19c6765">foldFPtoI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3d58c11c9787c2764e5f11bb127ced00">llvm::InstCombinerImpl::foldICmpInstWithConstantNotInt</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7c9fd9f2dba79c2289639f72457fcea1">llvm::InstCombinerImpl::foldICmpUsingBoolRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a657815d57170937e7e75bee5ecf235ce">llvm::InstCombinerImpl::foldMultiplicationOverflowCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4df124d92129ffa8748086388a420b73">llvm::InstCombinerImpl::foldPHIArgBinOpIntoPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab6b30eb5a835fd225bcd74248fa65693">llvm::InstCombinerImpl::foldSelectExtConst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#aaf025e558f9fe2914e3f8c52e046fb21">foldShiftIntoShiftInAnotherHandOfAndInICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineandorxor-cpp/#a1f569ebf4402ad560d7c147f688ac05a">foldSignedTruncationCheck</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa72b51b8f455c8a622bb6f8cc9c14860">llvm::InstCombinerImpl::foldVariableSignZeroExtensionOfVariableHighBitExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/lazyvalueinfo-cpp/#aa116214bf0f5cf6201935447b27334e8">getFromRangeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa52ac704c30d37ea926b7e186f4fac83">getHashValueImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aece02adc8e4cc74296bfe410eabe287b">llvm::SCEVExpander::getIVIncOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#ab8fbf8890afc93e88d19a28877c13fad">getLoopPhiForCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4a3758e792ce9aeb9dea98f70b3d4715">llvm::CallBase::getNumSubclassExtraOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a41fc1cf527faa2225d1c8589b08314d3">llvm::CallBase::getNumSubclassExtraOperandsDynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a31bf07f3f61525486633bc1d0bbaf029">llvm::BinaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#a3685b2128d8e6917000e4adc3b266ff6">llvm::CastInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#af4abe8e5b55577f35032131a6264fe4f">llvm::CmpInst::getOpcode</a>, <a href="#ab4e05d690df389b8b1477c90387b575f">getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a20b0d117b1a9fa6392ffb1b71708516f">llvm::SelectInst::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/unaryoperator/#a7cece7ddf076c1dccc81f743e3b7bd36">llvm::UnaryOperator::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#ae7d7b2b9276de8b34c99bb97d25e9063">llvm::VPReplicateRecipe::getOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#af61b31a99c1e58b1760492d2a7a1ba9c">llvm::MemoryLocation::getOrNone</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#ad4cae6fe0d617016d48331d85dffa4c8">hashCallInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-structuralhash-cpp-/structuralhashimpl/#ac2717c2132c268d29f71c5c86cc40971">anonymous{StructuralHash.cpp}::StructuralHashImpl::hashInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#afb636ad432c97f9178ff3f966e93d819">isAlternateInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa60423084fe7d27af0ffbba889cbdf1a">isEqualImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ae61f1ffec3d05496e5372922373338c2">llvm::AArch64TTIImpl::isExtPartOfAvgExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a710fc966df72f9cae9f17ec7eb76f5e8">llvm::SystemZTTIImpl::isFoldableLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7ac21134b2aaca2a7d55f6ff9d92f5b2">isHighCostExpansion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64loadstoreoptimizer-cpp/#a9e9873c963a7609d913c3420a97c0595">isMatchingStore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a2bfff40c1bfc02a21a5ed0b64a99f8a2">llvm::AArch64TTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a0eee77cb45ab15bd00718f8801a3fc53">llvm::ARMTTIImpl::isProfitableToSinkOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#aca87c42e8556b7f2e73454d63efa87f2">isPromotedInstructionLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a9ec948ba8709fe1041a2ec4a79cb6e4b">isReturnNonNull</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8601ff0320b6e29a13a2194200853425">llvm::isSafeToSpeculativelyExecute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#ad762896b80c211f6d9cacfe6f8438732">matchExpandedRem</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsos16-cpp/#a75fb8890302f439ba8724a8e986b62ba">needsFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a1080880d0ca078dceb9d3c8923576ae1">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::preferToKeepConstantsAttached</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/lanaiinstrinfo/#ad2390aa51b816a018aed94e4d354745a">llvm::LanaiInstrInfo::removeBranch</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#ae31219d422e76099c3c5dfaa2c7171cb">anonymous{LoadStoreVectorizer.cpp}::reorder</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a16096e55b9292113f13073fa2343b9c7">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceFloatIVWithIntegerIV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-hexagonoptimizeszextends-cpp-/hexagonoptimizeszextends/#a4240fc0963676b19a8cbf8448a599700">anonymous{HexagonOptimizeSZextends.cpp}::HexagonOptimizeSZextends::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86avoidstoreforwardingblocks-cpp-/x86avoidsfbpass/#a42cae0fd23182f6d2b4d4368a4ec21c3">anonymous{X86AvoidStoreForwardingBlocks.cpp}::X86AvoidSFBPass::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/vectorpromotehelper/#aa46482c59b5d71b890df4cfaada1e6c7">anonymous{CodeGenPrepare.cpp}::VectorPromoteHelper::shouldPromote</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/vprecipebuilder/#a760fb390c24b907500c0a181fada9590">llvm::VPRecipeBuilder::tryToCreateWidenRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a86b0437dceb8e39c8185dc7def325011">llvm::InstCombinerImpl::visitFCmpInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae31c50e938b95587c87aed0f133b1346">llvm::InstCombinerImpl::visitICmpInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#acd093283d4e8d1301859f0a98a157680">anonymous{SimplifyIndVar.cpp}::WidenIV::widenWithVariantUse</a>.</p>

</div>
</div>

### getOpcodeName() {#a9affd129d19aae669647eb0d1c91f793}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::Instruction::getOpcodeName ()</td>
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



<p>Definition at line 312 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a9affd129d19aae669647eb0d1c91f793">getOpcodeName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#af718a7db460e96f14b7c380d841cbcd8">checkInstructions</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationplanner/#aa216c2cbc8d9610dc20db065aca671d3">llvm::LoopVectorizationPlanner::emitInvalidCostRemarks</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a1217df326ed753111e60d3eaef272ded">llvm::VPWidenRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/anonymous-bitcodereader-cpp-/bitcodeconstant/#a0e3d0af51673a8539916c28f12481da3">anonymous{BitcodeReader.cpp}::BitcodeConstant::getOpcodeName</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a5e221a49375ad8a8470607f2007784f4">llvm::ConstantExpr::getOpcodeName</a>, <a href="#a9affd129d19aae669647eb0d1c91f793">getOpcodeName</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hvxidioms/#aef05d2673ec790b5724976bfdac1790c">anonymous{HexagonVectorCombine.cpp}::HvxIdioms::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aca839409ad4f4fb66241f6b97da6674f">llvm::VPInstruction::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vppartialreductionrecipe/#a547b8cb4c97345c9b9f78fbcd4b4da89">llvm::VPPartialReductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionevlrecipe/#aee1dbc25df0d2b70bd4eb984cd3be380">llvm::VPReductionEVLRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreductionrecipe/#a52161486f40f867a8767dc3fef77ee9d">llvm::VPReductionRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a202af2dd775be9a857e92e8ca6190b4f">llvm::VPReplicateRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpscalarcastrecipe/#a344cb72b5808ac915cbb3ca2ab53d6e1">llvm::VPScalarCastRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencastrecipe/#a30fd23ee3def3f12fad8496e85755c2a">llvm::VPWidenCastRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a64949951a81f6c67ecbd51ad90374828">llvm::VPWidenEVLRecipe::print</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenrecipe/#a5ad4e4df14b5a3c6905892a8f4bcb580">llvm::VPWidenRecipe::print</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a035830591fff503ea933e8c88c84f3f8">PrintOps</a>.</p>

</div>
</div>

### getPrevNonDebugInstruction() {#a512494b857b0644c1f722531e3ee5495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * Instruction::getPrevNonDebugInstruction (bool SkipPseudoOp=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pointer to the previous non-debug instruction in the same basic block as 'this', or nullptr if no such instruction exists.</p>


<p>Skip any pseudo operations if <span class="doxyComputerOutput">SkipPseudoOp</span> is true.</p>


<p>Declaration at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1234 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp/#aa62aa7b8aa53a4cc57ee4397a5221e64">findDominatingValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a2e130f575ee6cbddeb0d62b295dee036">InsertStackProtectors</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a6d53d8df2e0ea40eee8a7349563a9df7">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::isExecutedInAlignedRegion</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a85e25362e2d9d1222397368e9ba7f9ce">llvm::InstCombinerImpl::visitFenceInst</a>.</p>

</div>
</div>

### getPrevNonDebugInstruction() {#a880c796a9f81d3a377a3a8886ec88f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::Instruction::getPrevNonDebugInstruction (bool SkipPseudoOp=false)</td>
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



<p>Definition at line 908 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>

</div>
</div>

### getStableDebugLoc() {#a00fe6a3df205f2bb5b21ac4ef7a2dca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugLoc &amp; Instruction::getStableDebugLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fetch the debug location for this node, unless this is a debug intrinsic, in which case fetch the debug location of the next non-debug node.</p>

<p>Declaration at line 515 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1241 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/branchinst/#a33be833bacd8efc3079465530cd10cea">llvm::sandboxir::BranchInst::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a72f80871b9f46788c255158fbab96879">llvm::User::Op</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>.</p>

</div>
</div>

### getSuccessor() {#a6e5d2e18c81baaeec7dadc81a0dea993}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * Instruction::getSuccessor (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the specified successor. This instruction must be a terminator.</p>

<p>Declaration at line 976 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1284 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a4ca10cc5976994ee1c01be4b019c1ee6">llvm::FunctionComparator::compare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a9bbea577bf401c708dc854d2dad600af">findLoopComponents</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/jumpthreading-cpp/#a089d9b5caf2479e6b87f94c73e5b1f70">getBestDestForJumpOnUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppciseldagtodag-cpp/#a9293c2849df988b06fecea7e1b021fee">getBranchHint</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-55c8cb82503f51812ad190e425a6fd3d/#a02f466eae018c75689a0189cb5f29524">llvm::DOTGraphTraits&lt; DOTFuncInfo * &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a1bcb8bb92d8385a81a07659c6e1ec6fc">llvm::MustBeExecutedContextExplorer::getMustBeExecutedNextInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a0cb597b1f0cffe907fa834e9a95fe719">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ababcf5a1223c36cb7c547c5b34c6416c">llvm::isCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver/#a19fefaa90777f772a3db9ce94e5209ab">llvm::SparseSolver&lt; LatticeKey, LatticeVal, KeyInfo &gt;::isEdgeFeasible</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/partiallyinlinelibcalls-cpp/#a3c38fd13d9fa38356cca5ecdf7cfba23">optimizeSQRT</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxprofflattening-cpp-/profileannotator/#a9a58a5d6b3af1afec70ac9b8c1b2c902">anonymous{PGOCtxProfFlattening.cpp}::ProfileAnnotator::ProfileAnnotator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#ac177889afcc13c9ef882fd160c11e851">recordCondition</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6aad9a57bb45319be236a2c47cf23a5e">llvm::SplitCriticalEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae45123597a5abb30853572614c1b2d4b">llvm::UnrollAndJamLoop</a>.</p>

</div>
</div>

### handleMarkerRemoval() {#acf73620764d7168629631e3681499f4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::handleMarkerRemoval ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Handle the debug-info implications of this instruction being removed.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> attached DbgRecords need to "fall" down onto the next instruction.</p>


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### hasAllowContract() {#adf69200e2ae35a69c5eeecd4c0ee4d1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasAllowContract ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the allow-contract flag is set.</p>

<p>Declaration at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="#a2c89a7c3adbeaf3cc5d02a41401801fb">cloneDebugInfoFrom</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae8b00d72cfbbf3ef02315ae6a0ecc418">llvm::GCNTTIImpl::getArithmeticInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### hasAllowReassoc() {#aed565a1dfd056c37a481581db8cdbedd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasAllowReassoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the allow-reassociation flag is set.</p>

<p>Declaration at line 645 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac85e7a1e0b7405c705c25cf188176c97">llvm::CallBrInst::getDefaultDest</a> and <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#a87ba68a2226ee11773d7b130c59d56d6">llvm::CallBrInst::setDefaultDest</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a4d3ad60400165f1708ea8572d996abc3">isFSqrtDivToFMulLegal</a>, <a href="#af53129f70dd4f0dae21bb5099ebecedc">moveBeforePreserving</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### hasAllowReciprocal() {#a76908359b5b01e49efdd43d1d6e08c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasAllowReciprocal ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the allow-reciprocal flag is set.</p>

<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a44d5479ec7293c1fcedeecd359f5d6dd">llvm::IRBuilderBase::CreateLandingPad</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/type/#a330bbaf89b90196df6960be4724513c6">llvm::sandboxir::Type::LLVMTy</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### hasApproxFunc() {#aa11ca53210de69609754994339179e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasApproxFunc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the approximate-math-functions flag is set.</p>

<p>Declaration at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a97bc0afbd46cc7b3539e1cba861ac350">llvm::LandingPadInst::setCleanup</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae8b00d72cfbbf3ef02315ae6a0ecc418">llvm::GCNTTIImpl::getArithmeticInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### hasAtomicLoad() {#ab7e43783656ce7aae69f3da31509ff88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasAtomicLoad ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this atomic instruction loads from memory.</p>

<p>Declaration at line 808 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a1c68a6f0cdbdeb8a431791ad286109a0">llvm::PPCTargetLowering::emitTrailingFence</a>.</p>

</div>
</div>

### hasAtomicStore() {#a409415e274680c5d72d3272a1cee3d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasAtomicStore ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this atomic instruction stores to memory.</p>

<p>Declaration at line 811 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1058 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a74d56dd1a8531d108c9b4883bfff61a6">llvm::CatchSwitchInst::getParentPad</a> and <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a892d35100f9c5c657d7fe1b4a8e5a990">llvm::CatchSwitchInst::setParentPad</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#afa79830ec972611f4c1d1f8e23266aa4">llvm::ARMTargetLowering::emitLeadingFence</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#aef73d1676a91c6929bba3d512881548b">llvm::TargetLoweringBase::emitLeadingFence</a> and <a href="/web-llvm/docs/api/classes/llvm/vetargetlowering/#a4eeea76dbedbbfc27c6ef0becf8bd543">llvm::VETargetLowering::emitLeadingFence</a>.</p>

</div>
</div>

### hasDbgRecords() {#afe42f1bdb9f76c2a852dea0238408f99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasDbgRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if any DbgRecords are attached to this instruction.</p>

<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### hasMetadata() {#a565f546ad95bd3a9bbe9a1e5040803f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::hasMetadata ()</td>
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

<p>Return true if this instruction has any metadata attached to it.</p>

<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a1f496e54accb2cbe919fb456cb703f1a">llvm::Value::hasMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#aef9fe930d99fc1baf2a6ae99a59df09e">atomicIgnoresDenormalModeOrFPModeIsFTZ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/anonymous-spillutils-cpp-/#a452155536772ef01d3c028f7284ecd2b">llvm::coro::anonymous{SpillUtils.cpp}::collectFrameAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a125e2946cdcc7555d8f5c383681d7097">convertMetadataToAssumes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="#aad11fd49455cd391b69667d5bcbc5df1">getAllMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a81ed5939e93e21552b452f5f82a73a38">llvm::MemoryDependenceResults::getInvariantGroupPointerDependency</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a76e90df9d2b35d9174077de99d909165">llvm::TargetLoweringBase::getLoadMemOperandFlags</a>, <a href="#aacd004fda4b063f84d19f53ca2f058cd">getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a4ee4255870ff1c70530958a72fc246dd">globalMemoryFPAtomicIsLegal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a5a020f0ab461a1f6e3b87aff314bd040">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a489ae04c136c4b088d849d7d6dc20965">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a508cede7bc51eb83285e5fe30d14b701">IsAcceptableTarget</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#accd9b4c07df33541bf14a4e2a01fb35b">anonymous{LoadStoreVectorizer.cpp}::isInvariantLoad</a>, <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue/#ac96558c87ecbcc96f020a0efcaade750">llvm::gvn::AvailableValue::MaterializeAdjustedValue</a>, <a href="#a695a53ce0b9f537880373b4ea1824a6b">setMetadata</a>, <a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#afbf6d60618e520079ded1612a2941fbe">updateMemprofMetadata</a>.</p>

</div>
</div>

### hasMetadata() {#a18993ec84b78442c34fefdd6d3b3f693}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::hasMetadata (unsigned KindID)</td>
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

<p>Return true if this instruction has the given type of metadata attached.</p>

<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#a6c09737e146b2d816c911a047ac67ba4">getMetadata</a>.</p>

</div>
</div>

### hasMetadata() {#a23ce9747bfbb053cf7ac18abbe4a1006}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::hasMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Return true if this instruction has the given type of metadata attached.</p>

<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="#a6c09737e146b2d816c911a047ac67ba4">getMetadata</a>.</p>

</div>
</div>

### hasMetadataOtherThanDebugLoc() {#a54867ca5f252be2c60176e14e7240391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::hasMetadataOtherThanDebugLoc ()</td>
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

<p>Return true if this instruction has metadata attached to it other than a debug location.</p>

<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#a1f496e54accb2cbe919fb456cb703f1a">llvm::Value::hasMetadata</a>.</p>

</div>
</div>

### hasNoInfs() {#a10d8839494fe8385aa1ddbca6f801d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasNoInfs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the no-infs flag is set.</p>

<p>Declaration at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 626 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a0397bc5569b1651e9f2e3e4faf2ade34">foldFCmpReciprocalAndZero</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a4d3ad60400165f1708ea8572d996abc3">isFSqrtDivToFMulLegal</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### hasNoNaNs() {#a0d4bb13ba43d71cfe58184ab1bb4abd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasNoNaNs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the no-NaNs flag is set.</p>

<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#a7d8e394c4b08a57bfcd68ce2df9b3545">llvm::CallBrInst::getIndirectDest</a> and <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#aadfc344e04297626c4705d33e8de8fde">llvm::CallBrInst::setIndirectDest</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#a48239fe2dd570dc10b58a6a89ce6dd72">foldFCmpFSubIntoFCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a340e06a462ce241e992ce74943f82a97">llvm::CmpInst::isEquivalence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a4d3ad60400165f1708ea8572d996abc3">isFSqrtDivToFMulLegal</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### hasNonDebugLocLoopMetadata() {#aa0d082032f91d90c9978c66286f8dbfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasNonDebugLocLoopMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### hasNonNeg() {#a87716cd594c6fcb3861a4044e7b594db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasNonNeg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the the nneg flag is set.</p>

<p>Declaration at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4d45f96f90c7ddd805c6bae2949077de">llvm::InstCombinerImpl::visitUIToFP</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### hasNoSignedWrap() {#a350f4fdc01c770b5cf6a8be2624ae3e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasNoSignedWrap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the no signed wrap flag is set.</p>

<p>Declaration at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a8efa56ca3bfdd8c715939f9e0b24ccda">buildNew</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp/#a043b2c098b442537523ecb6a194c7ec4">checkNoWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a39e315cb89b7144083895c083cc958e0">llvm::InstCombinerImpl::foldICmpSubConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a991fdcb0635a1c2dd11f56d504d18bad">foldMulShl1</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aaa54a171521e00d29d7f61f33f3269d4">isNonZeroRecurrence</a>, <a href="#a54507f01d7d06127068ee0663233511d">moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a34007246c68dde9443b1afc2a5b59318">setLimitsForBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>.</p>

</div>
</div>

### hasNoSignedZeros() {#a2c8498183c5bce88fb4f651ee4169611}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasNoSignedZeros ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the no-signed-zeros flag is set.</p>

<p>Declaration at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 631 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a4d3ad60400165f1708ea8572d996abc3">isFSqrtDivToFMulLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a75fa36408fed5acf91329505b3419196">simplifySelectWithFCmp</a>.</p>

</div>
</div>

### hasNoUnsignedWrap() {#a100c666f9253331dd1d166a863248326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasNoUnsignedWrap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the no unsigned wrap flag is set.</p>

<p>Declaration at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a8efa56ca3bfdd8c715939f9e0b24ccda">buildNew</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loadstorevectorizer-cpp/#a043b2c098b442537523ecb6a194c7ec4">checkNoWrapFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab329d363cb73927378483de592986282">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#abe15d83fb0501730bbfe840143cedc08">llvm::InstCombinerImpl::foldICmpShlConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a39e315cb89b7144083895c083cc958e0">llvm::InstCombinerImpl::foldICmpSubConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aaa54a171521e00d29d7f61f33f3269d4">isNonZeroRecurrence</a>, <a href="#a28c50733b8b3ed88997ca245cd0d6a3b">moveBeforePreserving</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a93a6fd2ea0b1d80347d4d5eff6462428">llvm::InstCombinerImpl::simplifyShrShlDemandedBits</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a> and <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a39eadf98e4773739cd4e7b4befee6fb5">anonymous{SimplifyIndVar.cpp}::WidenIV::widenIVUse</a>.</p>

</div>
</div>

### hasPoisonGeneratingAnnotations() {#a8374600731c31968debc9eb3de4c37bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::hasPoisonGeneratingAnnotations ()</td>
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

<p>Return true if this instruction has poison-generating flags, return attributes or metadata.</p>

<p>Definition at line 564 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a8374600731c31968debc9eb3de4c37bc">hasPoisonGeneratingAnnotations</a>, <a href="#a8d57cfab4f6b4461e8ddddaeb2a28128">hasPoisonGeneratingFlags</a>, <a href="#ae59c6449e1b577942315f4365ab5aa89">hasPoisonGeneratingMetadata</a> and <a href="#a2ecc41326c89789bcdbd9c9a0295bde7">hasPoisonGeneratingReturnAttributes</a>.</p>


<p>Referenced by <a href="#a8374600731c31968debc9eb3de4c37bc">hasPoisonGeneratingAnnotations</a>.</p>

</div>
</div>

### hasPoisonGeneratingFlags() {#a8d57cfab4f6b4461e8ddddaeb2a28128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasPoisonGeneratingFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this operator has flags which may cause this instruction to evaluate to poison despite having non-poison inputs.</p>

<p>Declaration at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 422 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a> and <a href="#a8374600731c31968debc9eb3de4c37bc">hasPoisonGeneratingAnnotations</a>.</p>

</div>
</div>

### hasPoisonGeneratingMetadata() {#ae59c6449e1b577942315f4365ab5aa89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasPoisonGeneratingMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction has poison-generating metadata.</p>

<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="#a8374600731c31968debc9eb3de4c37bc">hasPoisonGeneratingAnnotations</a>.</p>

</div>
</div>

### hasPoisonGeneratingReturnAttributes() {#a2ecc41326c89789bcdbd9c9a0295bde7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasPoisonGeneratingReturnAttributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction has poison-generating attribute.</p>

<p>Declaration at line 557 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>


<p>Referenced by <a href="#a8374600731c31968debc9eb3de4c37bc">hasPoisonGeneratingAnnotations</a>.</p>

</div>
</div>

### hasSameSpecialState() {#a566048bdbd8bade381b6a52ed0244621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::hasSameSpecialState (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I2, bool IgnoreAlignment=false, bool IntersectAttrs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function determines if the speficied instruction has the same "special" characteristics as the current one.</p>


<p>This must be kept in sync with <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aa359aa2850f74fbc9dbdb4650c13f4cf">FunctionComparator::cmpOperations</a> in <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp">lib/Transforms/IPO/MergeFunctions.cpp</a>.</p>


<p>This means that opcode specific details are the same. As a common example, if we are comparing loads, then hasSameSpecialState would compare the alignments (among other things).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specific instruction has the same opcde specific characteristics as the current one. Determine if one instruction has the same state as another.</p></dd>
</dl>


<p>Declaration at line 963 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### insertAfter() {#af09e4096de244d2fb345891328714a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::insertAfter (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an unlinked instruction into a basic block immediately after the specified instruction.</p>

<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 111 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aebae63f31076e8c0dfe153c45a730497">addAssumeNonNull</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a5a43b0bc7c25aaaa14cf3d79d7f13c78">DbgInserterHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ab98b1b6868b494dafb8501b53ce9b672">llvm::BasicBlock::Instruction::insertAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a9ff8c2039984eaa49dcaabc27d62ab89">llvm::BasicBlock::Instruction::insertAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a>.</p>

</div>
</div>

### insertAfter() {#a6347142480e7de8e6e26fb8f291e47f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::insertAfter (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an unlinked instruction into a basic block immediately after the specified position.</p>

<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### insertBefore() {#a482498a1c760122fd33c7fc8190dd277}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::insertBefore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an unlinked instruction into a basic block immediately before the specified instruction.</p>


<p>Deprecated in favour of the iterator-accepting flavour. Iterators at the start of a block such as <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">BasicBlock::getFirstNonPHIIt</a> must be passed into insertBefore without unwrapping/rewrapping. For all other positions, call getIterator to fetch the instruction iterator.</p>


<p>Declaration at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 99 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a2b3fdb09b0789963c439d41fe91e44a1">llvm::changeToCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa1c8d384f90fc9d69d7fcdf920138cf2">llvm::CloneBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a25f0b41add9507b8eafadfbc4a090d6c">cloneInstructionInExitBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad399adefaffab058aa56567aa1b59df9">llvm::DbgVariableRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa650642c90f81466c2cd062e00ab152b">llvm::createPHIsForSplitLoopExit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a5a43b0bc7c25aaaa14cf3d79d7f13c78">DbgInserterHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a017054a3231506db436fdd9e8ae20ca0">llvm::expandUser</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a556a77d9b9acf322358b2c4131986b13">findOrCreatePHIInBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinefunction-cpp-/landingpadinlininginfo/#a232bc3cdcfa2bab0574af9b47ff90c41">anonymous{InlineFunction.cpp}::LandingPadInliningInfo::getInnerResumeDest</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae2ebbbbc990e3d932da5d0d0ea255f42">HandleByValArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#ae3b43649c18ab9e63c1be61b93dd7031">insertLifetimeMarkersSurroundingCall</a>, <a href="/web-llvm/docs/api/classes/llvm/bpfcoresharedinfo/#adee485b8d8a010d18877f5f41286b079">llvm::BPFCoreSharedInfo::insertPassThrough</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/controlheightreduction-cpp/#a071886a7b42adae6a171e653e04bd216">insertTrivialPHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a3e35e2d0faac57d69f8ff3dab5b627fe">llvm::BasicBlock::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a193396bde318d1df3007eeb0a9afb296">llvm::BasicBlock::Instruction::insertBefore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#aa41b5e7a1b162b70c1b4ce419b0c0f25">anonymous{AttributorAttributes.cpp}::makeChange</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopinterchange-cpp/#a76f2308b91faa139968810fd02d26891">moveLCSSAPhis</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a642ec4238f02650fc1e70d5b4ac8d844">movePHIValuesToInsertedBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a759daba99f9b665ac7274d0dfe70ce09">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::normalizeReturnBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a948aaf9d2ae438b3e2369223f55ec841">rematerializeChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#a1ad5c109b5218ec1d5f5fcd6390636ba">replaceConstantExprOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad87f4b76b6846d029880d6b9012a7e69">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/materializationutils-cpp/#aba618c16a34739af0506ba1082d209a3">rewriteMaterializableInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a5a93b5fcf433128b2fd9d563792eb4cd">rewritePHIs</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a24a3e4aad4cb2fdde7ce294a531cd52a">sinkCmpExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopsink-cpp/#a89374dd34ed723e45309afa9ac10eb83">sinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a502009030bffff8a6992f4e4eb9380f5">llvm::SplitIndirectBrCriticalEdges</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfpreservestaticoffset-cpp/#aadcf41a9f704494210a217eb089678b3">tryToReplaceWithGEPBuiltin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a9498339e26b296572a463a1300bf1a13">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a7c94d0952ba1d6986f0e78b62c303074">DataScalarizerVisitor::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#ab71463de9bdf222f2f8fab162151e5c5">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitStoreInst</a> and <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#a42a4cfbd5d57ef0af5a3f332d4fba28b">DataScalarizerVisitor::visitStoreInst</a>.</p>

</div>
</div>

### insertBefore() {#a5bf2824185d7a1f3a86683efb7e525e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::insertBefore (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert an unlinked instruction into a basic block immediately before the specified position.</p>


<p>Insert an unlinked instruction into a basic block immediately before the specified instruction.</p>


<p>Declaration at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### insertBefore() {#a299df85ca0809906003361ccdf1d7bd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::insertBefore (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### insertInto() {#afcd9d2ea284c4d90541291ff9c47d332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock::iterator Instruction::insertInto (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * ParentBB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> It)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts an unlinked instruction into <span class="doxyComputerOutput">ParentBB</span> at position <span class="doxyComputerOutput">It</span> and returns the iterator of the inserted instruction.</p>

<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0eaf12b7854445670a7b0af3fe87b86c">buildPartialInvariantUnswitchConditionalBranch</a>, <a href="/web-llvm/docs/api/structs/anonymous-clonefunction-cpp-/pruningfunctioncloner/#a80ad3b35cf775718eb472f8810e73092">anonymous{CloneFunction.cpp}::PruningFunctionCloner::CloneBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2e4b18daaf5f20f1ade3a9f66b86d843">llvm::FoldReturnIntoUncondBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-lowerswitch-cpp-/#ab9fe9fd51104da9e7faa88a213b74b9b">anonymous{LowerSwitch.cpp}::SwitchConvert</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-unifyfunctionexitnodes-cpp-/#a06b5d6856fd9067830ab0477c0b13f31">anonymous{UnifyFunctionExitNodes.cpp}::unifyReturnBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>.</p>

</div>
</div>

### isArithmeticShift() {#a1ef1466270a3df7919d1f6111447997e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isArithmeticShift ()</td>
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

<p>Return true if this is an arithmetic shift right.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>.</p>

</div>
</div>

### isAssociative() {#a4f0027b9d05b27206b1882976fce9038}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isAssociative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is associative:</p>


<p>Associative operators satisfy: x op (y op z) === (x op y) op z</p>


<p>In LLVM, the Add, Mul, And, Or, and Xor operators are associative.</p>


<p>Declaration at line 742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1248 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="#a58c0f69b2d18b94c651b13d8e7fd9ebc">isAssociative</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>.</p>

</div>
</div>

### isAtomic() {#a57efb022f2ee2e19e4cdf582f4d27f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isAtomic ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction has an <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7">AtomicOrdering</a> of unordered or higher.</p>

<p>Declaration at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1031 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad7586c4efa39c8f9162c7608ff9a57cf">llvm::InstCombinerImpl::combineLoadToNewType</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a0cb38e302133457f235fdcc6723abeac">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computeFromLI</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa8a186c50cdf60ac11ae1d0b884d468d">llvm::InstCombinerImpl::foldPHIArgLoadIntoPHI</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a1806b14f4d7a63958af99758745046e2">anonymous{DeadStoreElimination.cpp}::DSEState::isDSEBarrier</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#aeb534c1a0391ce24551c226a582099a7">llvm::LoadInst::isSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a70f38e046a2d6f8d9b40e092eda2c919">llvm::StoreInst::isSimple</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a>.</p>

</div>
</div>

### isBinaryOp() {#a5c88132322ca3f46f242f7c023a57010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isBinaryOp ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a5c88132322ca3f46f242f7c023a57010">isBinaryOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ae23c0a0a029dcfece9ccade74a1e1536">llvm::ConstantRange::binaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aae18513a5879b25cf5cdcada561fff10">canCreateUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryconstantexpr/#aa957380578437c766c99d5ef3f897f24">llvm::BinaryConstantExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a004ecf8ed4165883d4dfa06716dd72c9">llvm::VPInstruction::computeCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a964455f36837281d37f2a44e2fcb4cca">llvm::ConstantFoldBinaryOpOperands</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1934978a43ce45ca0ec7b837e31d4ebc">llvm::ConstantFoldFPInstOperands</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ae6e1699b7b98eaaf080f652b08792b9f">anonymous{ConstantFolding.cpp}::ConstantFoldInstOperandsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/constantexprkeytype/#aa8c34547ab7763be1fe5bbb78f90b7f7">llvm::ConstantExprKeyType::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9dbe907d689ccc2fbf23d5a5ef2f8ed7">llvm::IRBuilderBase::CreateNAryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#aee759d5807e7eb77e631717da4461426">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredication</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a3eba8b3e2e38c997d14bc2ee850be29a">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInBinaryOperator</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a2153c46ea6d560ce96b6ad7e822d2c70">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationInReduction</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ab00c6dc5086df2a37cd2e78715968861">llvm::ConstantExpr::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae9c2f00a962cb8e0316cf3548a5d8029">llvm::ConstantExpr::getBinOpIdentity</a>, <a href="#a5c88132322ca3f46f242f7c023a57010">isBinaryOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ae94b0d68e3880f919a56af17f7c40a73">isConstExprSupported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vputils/#a002a77cdbc23293b8f7a8458ffd0f905">llvm::vputils::isUniformAfterVectorization</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#ace208c0bd1d845fe49f319be6a954764">llvm::ConstantRange::makeGuaranteedNoWrapRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#accc830d2b6d4d03922cf5e6a238ae9c1">llvm::VPInstruction::onlyFirstLaneUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#aa0b84f190dbf600165d9b79f4cf51d6c">llvm::VPInstruction::onlyFirstPartUsed</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinstruction/#a7f10a1f949eaa66f6daa0940c33ac26e">llvm::VPInstruction::opcodeMayReadOrWriteFromMemory</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a87d22942f8d1a8b5e8eb92072b6dfc8b">llvm::ConstantRange::overflowingBinaryOp</a> and <a href="/web-llvm/docs/api/classes/anonymous-vectorcombine-cpp-/vectorcombine/#a72026c9724b6de144a788bfb35de1642">anonymous{VectorCombine.cpp}::VectorCombine::run</a>.</p>

</div>
</div>

### isBitwiseLogicOp() {#ac3376e3bd632ad72252638ae43295ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isBitwiseLogicOp ()</td>
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

<p>Return true if this is and/or/xor.</p>

<p>Definition at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a2d0036d2d7b30f510927731ba7a4f4b9">isBitwiseLogicOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/patternmatch/is-bitwiselogic-op/#ae36efaefa9672297e1a422a8a9717491">llvm::PatternMatch::is_bitwiselogic_op::isOpType</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a9f7798eb98807e7ce804788b339a6978">rightDistributesOverLeft</a>.</p>

</div>
</div>

### isCast() {#a27997849d8982bf226891024fd68daee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isCast ()</td>
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



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a27997849d8982bf226891024fd68daee">isCast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/castconstantexpr/#a436d3235f8d3bf568a415b286df2e38c">llvm::CastConstantExpr::classof</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8bf77c90e2fb57af4d4d4aab084f7052">llvm::ConstantFoldCastOperand</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ae6e1699b7b98eaaf080f652b08792b9f">anonymous{ConstantFolding.cpp}::ConstantFoldInstOperandsImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/constantexprkeytype/#aa8c34547ab7763be1fe5bbb78f90b7f7">llvm::ConstantExprKeyType::create</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvectorpredication-cpp-/cachingvpexpander/#a5cd88dbe6fb8f2ddbd621296ca4ebd5f">anonymous{ExpandVectorPredication.cpp}::CachingVPExpander::expandPredicationToCastIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#a08c03a4228af93098afb6ab60e7283f6">foldConstantCastPair</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a49b69843927f7cd96d866768b3aec92b">llvm::ConstantExpr::getCast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a2c9fe4fbe6ac4c180d6d2547c05d33c9">llvm::ConstantExpr::isCast</a>, <a href="#a27997849d8982bf226891024fd68daee">isCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/bitcode/lib/bitcode/reader/bitcodereader-cpp/#ae94b0d68e3880f919a56af17f7c40a73">isConstExprSupported</a> and <a href="/web-llvm/docs/api/classes/llvm/vpcastintrinsic/#aa2c13077e5a0bbf474c5ba56fdd4bd36">llvm::VPCastIntrinsic::isVPCast</a>.</p>

</div>
</div>

### isCommutative() {#a55743bd32282bf6f87aeb49237b1fb68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isCommutative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is commutative:</p>


<p>Commutative operators satisfy: (x op y) === (y op x)</p>


<p>In LLVM, these are the commutative operators, plus SetEQ and SetNE, when applied to any type.</p>


<p>Declaration at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1265 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a34f1aa991a80c9618af5d4e84aafcb9c">llvm::AtomicRMWInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a361ca9304555f6c2e0dd2b3188439b33">llvm::AtomicRMWInst::setVolatile</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/recurrencedescriptor/#ae3b1b80ef450d6706f42f3a929e51ce5">llvm::RecurrenceDescriptor::AddReductionVar</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#ac1907ee7981a0a84ec5ec9584555cb68">areCommutative</a>, <a href="/web-llvm/docs/api/structs/anonymous-interleavedloadcombinepass-cpp-/vectorinfo/#a2088d6a1f9882689fbea2dff8f09494c">anonymous{InterleavedLoadCombinePass.cpp}::VectorInfo::computePolynomialBinOp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a6d9999d61310781a41074a967e885f12">expandBinOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a15df887e1ad05e6c22a7c2e6492bde2d">foldOrCommuteConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#a917f93b85c9b8cfe9ad68ba6d49966ba">foldSelectBinOpIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae9c2f00a962cb8e0316cf3548a5d8029">llvm::ConstantExpr::getBinOpIdentity</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a77912b33da00edf1cb4143f66890519b">llvm::RISCVTTIImpl::getIntImmCostInst</a>, <a href="#a48dd504e040ba9c89e802af96c78dd25">isCommutative</a>, <a href="/web-llvm/docs/api/classes/llvm/overflowingbinaryoperator/#ac1d9c85b70921425cbab71eec4d7c46c">llvm::OverflowingBinaryOperator::isCommutative</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvgatherscatterlowering-cpp/#a851c8b3252c6423ce124dc872f07f07d">matchStridedStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a9f7798eb98807e7ce804788b339a6978">rightDistributesOverLeft</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a8863b1b71b53dbab1dd0bd7933ddb3cf">simplifyAssociativeBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a80cc7c4bd4a37fc13e9765fd3a31dbfe">llvm::BinaryOperator::swapOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ab952034edc23ad21ab312e0baaea0d7e">tryFactorization</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a90fcdfa591c9bd0cf511f2803198b355">llvm::InstCombinerImpl::visitShl</a>.</p>

</div>
</div>

### isDebugOrPseudoInst() {#a323444895ce923a737f0a7af82a30f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isDebugOrPseudoInst ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is a <a href="/web-llvm/docs/api/classes/llvm/dbginfointrinsic">DbgInfoIntrinsic</a> or <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeinst">PseudoProbeInst</a>.</p>

<p>Declaration at line 890 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1221 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3b303a16e5a77e48c8e724c52a3abbff">llvm::findAvailablePtrLoadStore</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-indirectcallpromotion-cpp-/#a29da820d4c19ac64f750762012fd13ca">anonymous{IndirectCallPromotion.cpp}::isDestBBSuitableForSink</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a7a59feca56f2ecfe5c74d6c04b0c45c7">ProcessBlock</a>.</p>

</div>
</div>

### isEHPad() {#a5d3d315f678bc76e43b27d18e5d72829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isEHPad ()</td>
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

<p>Return true if the instruction is a variety of EH-block.</p>

<p>Definition at line 869 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a5d3d315f678bc76e43b27d18e5d72829">isEHPad</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a833a6084a93d5900e8bdd493b37bbbc7">llvm::ehAwareSplitEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/winehprepare-cpp/#a5345629403124507c78e4e32c6a04b84">getEHPadFromPredecessor</a>, <a href="#a5d3d315f678bc76e43b27d18e5d72829">isEHPad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a5e126bad06b6fa7c75f524f304deb7b0">isSafeToMove</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a3cc8a3a2506bf528398d0aef0850f31a">SinkCast</a>.</p>

</div>
</div>

### isExact() {#a689a03df5b4ae094d6a3a1bd13dac574}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isExact ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the exact flag is set.</p>

<p>Declaration at line 589 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 557 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a8efa56ca3bfdd8c715939f9e0b24ccda">buildNew</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a664aaf46532d6ebeed0dfeb704308d33">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a36ef4128d8b08242e337bcbed0dce3c8">llvm::InstCombinerImpl::foldICmpBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a78aa741a7874614a21b66826ffe6e5ce">llvm::InstCombinerImpl::foldICmpBinOpEqualityWithConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8efbb860a56c4deccffeca4d2963fb70">llvm::InstCombinerImpl::foldICmpDivConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a037006a1d44974a6840403beb4febd30">llvm::InstCombinerImpl::foldICmpShrConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a12f6125cdd608cb0459585ddb68ead53">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::foldIVUser</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad3f7f3eaea6d34ab9ade1af54174f5a2">llvm::InstCombinerImpl::FoldShiftByConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#aaa54a171521e00d29d7f61f33f3269d4">isNonZeroRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aae58203af8c9b9d7e5551badc9094d90">processAShr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aad984958be92d8e57544ae979a2a897e">processSDiv</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8ff215a6e938a8df32c29c99bc126603">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenRightShift</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a>.</p>

</div>
</div>

### isFast() {#a60311aae406df2143c650f3bce27e036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isFast ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether all fast-math-flags are set.</p>

<p>Declaration at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/libcallsimplifier/#a73c4a774eb638f963533b77f7124293b">llvm::LibCallSimplifier::optimizeCall</a>.</p>

</div>
</div>

### isFenceLike() {#aced8559a5380b3759af251428f024c02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isFenceLike ()</td>
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

<p>Return true if this instruction behaves like a memory fence: it can load or store to memory location without being given a memory location.</p>

<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#aced8559a5380b3759af251428f024c02">isFenceLike</a>.</p>


<p>Referenced by <a href="#aced8559a5380b3759af251428f024c02">isFenceLike</a>.</p>

</div>
</div>

### isFPDivRem() {#a9f25788548135c3b2bee0f5d37becd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isFPDivRem ()</td>
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



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a9f25788548135c3b2bee0f5d37becd77">isFPDivRem</a>.</p>


<p>Referenced by <a href="#a9f25788548135c3b2bee0f5d37becd77">isFPDivRem</a>.</p>

</div>
</div>

### isFuncletPad() {#a70c1f2d69b2ea2f6d7e83bb17bb9ba0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isFuncletPad ()</td>
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



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a70c1f2d69b2ea2f6d7e83bb17bb9ba0a">isFuncletPad</a>.</p>


<p>Referenced by <a href="#a70c1f2d69b2ea2f6d7e83bb17bb9ba0a">isFuncletPad</a>.</p>

</div>
</div>

### isIdempotent() {#aeba4ff92fbdb591fb2a1090dbda31691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isIdempotent ()</td>
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

<p>Return true if the instruction is idempotent:</p>


<p>Idempotent operators satisfy: x op x === x</p>


<p>In LLVM, the And and Or operators are idempotent.</p>


<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#aeba4ff92fbdb591fb2a1090dbda31691">isIdempotent</a>.</p>


<p>Referenced by <a href="#aeba4ff92fbdb591fb2a1090dbda31691">isIdempotent</a>.</p>

</div>
</div>

### isIdenticalTo() {#ad848bd0184fc7bcb7b71e19248f08f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isIdenticalTo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified instruction is exactly identical to the current one.</p>


<p>This means that all operands match and any extra information (e.g. load is volatile) agree.</p>


<p>Declaration at line 924 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 914 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a73ef5ac7d0abd594af4c190baa6515a5">anonymous{DeadStoreElimination.cpp}::DSEState::eliminateRedundantStoresOfExistingValues</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#a842f13add9ede73561cdbad22101b255">anonymous{SLPVectorizer.cpp}::HorizontalReduction::getRdxKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a428f7b53e32934ae46a9aa35d3028d87">tryToMergeLandingPad</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a85e25362e2d9d1222397368e9ba7f9ce">llvm::InstCombinerImpl::visitFenceInst</a>.</p>

</div>
</div>

### isIdenticalToWhenDefined() {#a602468cf8d0763769b6b39ece1117ad7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isIdenticalToWhenDefined (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, bool IntersectAttrs=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is like isIdenticalTo, except that it ignores the SubclassOptionalData flags, which may specify conditions under which the instruction's result is undefined.</p>

<p>Declaration at line 930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#aa5133cfd6ce1419c7162cd0d7ba39ea9">EliminateDuplicatePHINodesNaiveImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#aa60423084fe7d27af0ffbba889cbdf1a">isEqualImpl</a>.</p>

</div>
</div>

### isIntDivRem() {#af9c2825ab53adf1bf8c9fa19ec89d986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isIntDivRem ()</td>
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



<p>Definition at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#af9c2825ab53adf1bf8c9fa19ec89d986">isIntDivRem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#ac83b2f6d1a223c7b4ac9eb3783ee1465">foldSelectWithConstOpToBinOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a81425fa662eac9cc9cd5d21f1c66695e">generateKeySubkey</a>, <a href="#af9c2825ab53adf1bf8c9fa19ec89d986">isIntDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8f3292dcaad99569501ace7909f2ccf0">isValidForAlternation</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a62e2ba967b974d6e68931532ab1aa4e8">llvm::InstCombinerImpl::visitSelectInst</a>.</p>

</div>
</div>

### isLaunderOrStripInvariantGroup() {#adda9304aaf3716109938d9479b2d2dbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isLaunderOrStripInvariantGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is a llvm.launder.invariant.group or llvm.strip.invariant.group.</p>

<p>Declaration at line 887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### isLifetimeStartOrEnd() {#a185bafe1e8f07def76a3bac154a23e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isLifetimeStartOrEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction is a llvm.lifetime.start or llvm.lifetime.end marker.</p>

<p>Declaration at line 883 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1204 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>.</p>

</div>
</div>

### isLogicalShift() {#aadb443634ecdb8f3e6aa001e6d436122}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isLogicalShift ()</td>
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

<p>Return true if this is a logical shift left or a logical shift right.</p>

<p>Definition at line 354 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#aaba35705ce5c614a4b4d1a6ed6e8bb57">canEvaluateShiftedShift</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#af31783f53ca1f5cd62dc80d2729530b0">canShiftBinOpWithConstantRHS</a>.</p>

</div>
</div>

### isNilpotent() {#a902c3b08cb9808fddc542ff284c28edb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isNilpotent ()</td>
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

<p>Return true if the instruction is nilpotent:</p>


<p>Nilpotent operators satisfy: x op x === Id,</p>


<p>where Id is the identity for the operator, i.e. a constant such that x op Id === x and Id op x === x for all x.</p>


<p>In LLVM, the Xor operator is nilpotent.</p>


<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a902c3b08cb9808fddc542ff284c28edb">isNilpotent</a>.</p>


<p>Referenced by <a href="#a902c3b08cb9808fddc542ff284c28edb">isNilpotent</a>.</p>

</div>
</div>

### isOnlyUserOfAnyOperand() {#a42a7168411751df6f6bc19cf5f3724d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isOnlyUserOfAnyOperand ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>It checks if this instruction is the only user of at least one of its operands.</p>

<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 375 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### isSafeToRemove() {#af92eae2af65e24114a8767cc10c8795e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isSafeToRemove ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction can be removed if the result is unused.</p>


<p>When constant folding some instructions cannot be removed even if their results are unused. Specifically terminator instructions and calls that may have side effects cannot be removed without semantically changing the generated program.</p>


<p>Declaration at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1189 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### isSameOperationAs() {#a25175390eaee0646bcb8b30990ab723b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isSameOperationAs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, unsigned flags=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function determines if the specified instruction executes the same operation as the current one.</p>


<p>This means that the opcodes, type, operand types and any other factors affecting the operation must be the same. This is similar to isIdenticalTo except the operands themselves don't have to be identical.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the specified instruction is the same operation as the current one. Determine if one instruction is the same operation as another.</p></dd>
</dl>


<p>Declaration at line 953 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>.</p>

</div>
</div>

### isShift() {#ac5984d6827f6e6922bed00bf03ba9552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isShift ()</td>
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



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#ac5984d6827f6e6922bed00bf03ba9552">isShift</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7ff0d8853961745bbe8afef66fab99dc">detectShiftUntilZeroIdiom</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab60c98e34bf6a4b6b599ab93a3f12b06">llvm::InstCombinerImpl::foldICmpAndShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3b73df3a995af9ca26c9d024c957c45a">llvm::InstCombinerImpl::foldSelectShuffle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a2c05df65ce7ce7ec1d78348be2452e8d">foldSelectShuffleWith1Binop</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a949d5831f77e0c9dc7d3509911cf92f2">llvm::ARMTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/structs/llvm/patternmatch/is-shift-op/#a8e6596f63b346038761f21d9313a1fe0">llvm::PatternMatch::is_shift_op::isOpType</a>, <a href="#ac5984d6827f6e6922bed00bf03ba9552">isShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a9f7798eb98807e7ce804788b339a6978">rightDistributesOverLeft</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>.</p>

</div>
</div>

### isSpecialTerminator() {#afcb56ab491984549c6f734b0f5b4f925}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isSpecialTerminator ()</td>
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



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#afcb56ab491984549c6f734b0f5b4f925">isSpecialTerminator</a>.</p>


<p>Referenced by <a href="#afcb56ab491984549c6f734b0f5b4f925">isSpecialTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a30207ff92cc09d50e4f6e188de0f59ed">llvm::JumpThreadingPass::maybeMergeBasicBlockIntoOnlyPred</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a>.</p>

</div>
</div>

### isTerminator() {#a7653277511df1034148a37520a585bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isTerminator ()</td>
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



<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#a7653277511df1034148a37520a585bb5">isTerminator</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a0e686f0d790f0fd925a036c4cb50199b">CalculateUnswitchCostMultiplier</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a893c7586e2537bc37a83a57a0190f67f">findLocationForEntrySafepoint</a>, <a href="/web-llvm/docs/api/structs/llvm/mustbeexecutedcontextexplorer/#a1bcb8bb92d8385a81a07659c6e1ec6fc">llvm::MustBeExecutedContextExplorer::getMustBeExecutedNextInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-attributorattributes-cpp-/#a0cb597b1f0cffe907fa834e9a95fe719">anonymous{AttributorAttributes.cpp}::identifyAliveSuccessors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2d6efe0db0843950c3cfff2cdbdac41e">llvm::isCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#abbd47852a13b73290f4625f20c9018d8">isRemovableWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a5e126bad06b6fa7c75f524f304deb7b0">isSafeToMove</a>, <a href="#a7653277511df1034148a37520a585bb5">isTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a4082748189dc3460ea7130cd8d7790b5">llvm::MemoryDependenceResults::removeInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/outlinableregion/#a761b3c02cd196cb5f6fb019bcd86866e">llvm::OutlinableRegion::splitCandidate</a>.</p>

</div>
</div>

### isUnaryOp() {#ae6249022aded13ad98775c11881bc117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isUnaryOp ()</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplanslp-cpp/#a06b4f19004df11b338ccc7e73bf47ab4">getOpcode</a> and <a href="#ae6249022aded13ad98775c11881bc117">isUnaryOp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#ae6e1699b7b98eaaf080f652b08792b9f">anonymous{ConstantFolding.cpp}::ConstantFoldInstOperandsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2c4fe17695dd008139cd08a7d460744e">llvm::ConstantFoldUnaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6810c4cb05b49909862249d3b3afa2af">llvm::ConstantFoldUnaryOpOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/vplantransforms-cpp/#ad0faf4b8ff1cf3306958d056dcb2fde2">createEVLRecipe</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9dbe907d689ccc2fbf23d5a5ef2f8ed7">llvm::IRBuilderBase::CreateNAryOp</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenevlrecipe/#a703a08e4f8a8f64b8be733d194070cd1">llvm::VPWidenEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5e36553611d3def8cf698c722239718f">llvm::isSafeToSpeculativelyExecuteWithOpcode</a> and <a href="#ae6249022aded13ad98775c11881bc117">isUnaryOp</a>.</p>

</div>
</div>

### isUsedOutsideOfBlock() {#a91dbffd0cc6b209fd2bfe9a0236d779c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isUsedOutsideOfBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if there are any uses of this instruction in blocks other than the specified block.</p>


<p>Note that PHI nodes are considered to evaluate their operands in the corresponding predecessor block.</p>


<p>Declaration at line 969 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>.</p>

</div>
</div>

### isVolatile() {#a92599976668e8eec0d73b986ad3e7732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::isVolatile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction has a volatile memory access.</p>

<p>Declaration at line 814 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1070 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#ab04dbc468ae6f1e7ff304ec5ba903b66">llvm::CatchSwitchInst::getUnwindDest</a> and <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#a03f8f04a7ac9266f16326fb7ba5786d3">llvm::CatchSwitchInst::setUnwindDest</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ad71302bd643143c32b34b01104c2e364">llvm::expandAtomicMemCpyAsLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#ab46fb372d99dc0562d09cfdcd041d5ab">llvm::MemoryDependenceResults::getNonLocalPointerDependency</a> and <a href="/web-llvm/docs/api/classes/llvm/memorydependenceresults/#a10168569b54ede5f3a15b05463db9495">llvm::MemoryDependenceResults::getSimplePointerDependencyFrom</a>.</p>

</div>
</div>

### mayHaveSideEffects() {#a6ea260be710ac7b61309534308da3147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::mayHaveSideEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction may have side effects.</p>


<p>Side effects are:</p>


<ul class="doxyList ">
<li>Writing to memory.</li>
<li>Unwinding.</li>
<li>Not returning (e.g. an infinite loop).</li>
</ul>

<p>Note that this does not consider malloc and alloca to have side effects because the newly allocated memory is completely invisible to instructions which don't use the returned value. For cases where this matters, isSafeToSpeculativelyExecute may be more appropriate.</p>


<p>Declaration at line 854 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1185 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#aa66946de804eaf8ee4f4fb6b781dc989">llvm::sandboxir::Instruction::Opc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#a60fb2a009661b4da106f7ae49f8df93a">canMoveAboveCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a0f31e8ea7a0fea18c2df924e7d6e8de8">hasHardUserWithinLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#aab37469c4748a495736ad163ac54e776">isSafePHIToSpeculate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a> and <a href="/web-llvm/docs/api/classes/anonymous-loopinterchange-cpp-/loopinterchangetransform/#aebda974c30b92d0f6ffca66705d27f35">anonymous{LoopInterchange.cpp}::LoopInterchangeTransform::transform</a>.</p>

</div>
</div>

### mayReadFromMemory() {#a9149819221d66953ac6c2938b87f0136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::mayReadFromMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction may read memory.</p>

<p>Declaration at line 796 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 991 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0b9027fe8e7ff91d9d6ee565fbdb3db4">anonymous{DeadStoreElimination.cpp}::DSEState::getDomMemoryDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a3fd364675c871bdf0a532d46bab77e3d">GetLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a508cede7bc51eb83285e5fe30d14b701">IsAcceptableTarget</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a7a3a865fee609f58bb1a914b69afe20f">anonymous{DeadStoreElimination.cpp}::DSEState::isReadClobber</a> and <a href="#a2d77b9d450543e86acb394ff6dda6b53">mayReadOrWriteMemory</a>.</p>

</div>
</div>

### mayReadOrWriteMemory() {#a2d77b9d450543e86acb394ff6dda6b53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::mayReadOrWriteMemory ()</td>
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

<p>Return true if this instruction may read or write memory.</p>

<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a9149819221d66953ac6c2938b87f0136">mayReadFromMemory</a>, <a href="#a2d77b9d450543e86acb394ff6dda6b53">mayReadOrWriteMemory</a> and <a href="#a383175f96316074965ad115706bd49d7">mayWriteToMemory</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aliassettracker/#a5f720c5ed38312535b0080ccba56a53b">llvm::AliasSetTracker::addUnknown</a>, <a href="/web-llvm/docs/api/classes/llvm/aliasset/#accc010962179e64afb02e0340b40ce8b">llvm::AliasSet::aliasesUnknownInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a51d22a1ed809d7cb1c1eb46c820c8226">llvm::intersectAccessGroups</a>, <a href="#a2d77b9d450543e86acb394ff6dda6b53">mayReadOrWriteMemory</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorfloating/#a31f2a80a770f0aa93c1fab42e9d41407">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorFloating::updateImpl</a>.</p>

</div>
</div>

### mayThrow() {#a0501e3b4084693092efc0be8b02c1b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::mayThrow (bool IncludePhaseOneUnwind=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction may throw an exception.</p>


<p>If IncludePhaseOneUnwind is set, this will also include cases where phase one unwinding may unwind past this frame due to skipping of cleanup landingpads.</p>


<p>Declaration at line 824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1158 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#a0b8426b10dd0013c86e790af7ff415b8">anonymous{DeadStoreElimination.cpp}::canSkipDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a0b9027fe8e7ff91d9d6ee565fbdb3db4">anonymous{DeadStoreElimination.cpp}::DSEState::getDomMemoryDef</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a1806b14f4d7a63958af99758745046e2">anonymous{DeadStoreElimination.cpp}::DSEState::isDSEBarrier</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a5e126bad06b6fa7c75f524f304deb7b0">isSafeToMove</a>.</p>

</div>
</div>

### mayWriteToMemory() {#a383175f96316074965ad115706bd49d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::mayWriteToMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this instruction may modify memory.</p>

<p>Declaration at line 793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1011 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-mergeicmps-cpp-/bcecmpblock/#a851916c7b9610597c4339a0d74f8e449">anonymous{MergeICmps.cpp}::BCECmpBlock::canSinkBCECmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3b303a16e5a77e48c8e724c52a3abbff">llvm::findAvailablePtrLoadStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a9d0e45d07c65ef73adf90a69ca3ebedf">findInitTrampolineFromBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorydependenceanalysis-cpp/#a3fd364675c871bdf0a532d46bab77e3d">GetLocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#ab0859b33717bfc3149f2b4051949b5cb">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a3544d6fc5a304b516d34fb76461b345e">anonymous{DeadStoreElimination.cpp}::DSEState::isCompleteOverwrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a5e126bad06b6fa7c75f524f304deb7b0">isSafeToMove</a>, <a href="#a2d77b9d450543e86acb394ff6dda6b53">mayReadOrWriteMemory</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aapointerinfofloating/#a538f824ece3cdc520673941e39f16cf6">anonymous{AttributorAttributes.cpp}::AAPointerInfoFloating::updateImpl</a>.</p>

</div>
</div>

### mergeDIAssignID() {#a2711d3bc7c6c769a8f34c7fc3937169d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::mergeDIAssignID (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; SourceInstructions)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Merge the <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> metadata from this instruction and those attached to instructions in <span class="doxyComputerOutput">SourceInstructions</span>.</p>


<p>This process performs a RAUW on the <a href="/web-llvm/docs/api/classes/llvm/metadataasvalue">MetadataAsValue</a> uses of the merged <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> nodes. Not every instruction in <span class="doxyComputerOutput">SourceInstructions</span> needs to have <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> metadata. If none of them do then nothing happens. If this instruction does not have a <a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> attachment but at least one in <span class="doxyComputerOutput">SourceInstructions</span> does then the merged one will be attached to it. However, instructions without attachments in <span class="doxyComputerOutput">SourceInstructions</span> are not modified.</p>


<p>Declaration at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#a6a66ebb3aa12757479a3c88de77d78f8">getFunction</a>, <a href="#a6c09737e146b2d816c911a047ac67ba4">getMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/at/#aea377383f26585e0da2e86da8e4dfe53">llvm::at::RAUW</a> and <a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#afdbe575a191d9f3b5b6cef8212745dc0">anonymous{LICM.cpp}::LoopPromoter::insertStoresInLoopExitBlocks</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>.</p>

</div>
</div>

### moveAfter() {#a54507f01d7d06127068ee0663233511d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveAfter (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right after MovePos.</p>

<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a350f4fdc01c770b5cf6a8be2624ae3e5">hasNoSignedWrap</a> and <a href="#a4166b451a572b1e5d3fea7250af53653">setHasNoSignedWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="#ae6189d19092044a37414c05526874a06">moveAfter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab8b1a901ef225bb4a12ca046d13f4b45">rewriteDebugUsers</a> and <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>.</p>

</div>
</div>

### moveAfter() {#ae6189d19092044a37414c05526874a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Instruction::moveAfter (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right after MovePos.</p>

<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a784097fca76abad9e815cf1692de79c4">comesBefore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="#ad2b97a10a92351d0df82c9759ad1ee07">getInsertionPointAfterDef</a>, <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>, <a href="#a54507f01d7d06127068ee0663233511d">moveAfter</a>, <a href="#ab2c07ffbd0e823cbd49ec9873c724961">moveAfterPreserving</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### moveAfterPreserving() {#ab2c07ffbd0e823cbd49ec9873c724961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveAfterPreserving (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>See <a href="#ae3c2accff1fc7b0c4fc5ab15915573af">moveBeforePreserving</a> .</p>

<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>


<p>Referenced by <a href="#ae6189d19092044a37414c05526874a06">moveAfter</a>.</p>

</div>
</div>

### moveBefore() {#af67d1f3a518964d80a109bb3d9d5cf1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right before MovePos.</p>


<p>Deprecated in favour of the iterator-accepting flavour. Iterators at the start of a block such as <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a362b5e6097732cbc0d2fb555a1f73400">BasicBlock::getFirstNonPHIIt</a> must be passed into moveBefore without unwrapping/rewrapping. For all other positions, call getIterator to fetch the instruction iterator.</p>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#ad80b94848142a7c633976aff96d4c408">llvm::VPlan::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#ac0645a37d60eb4946b1b73c517a96544">llvm::CodeExtractor::extractCodeRegion</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af59c587eddc75748a1e201369cd3dbac">llvm::InstCombinerImpl::freezeOtherUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86loweramxtype-cpp-/x86loweramxcast/#ae812aaa917422c3c4b067cda1b1d7019">anonymous{X86LowerAMXType.cpp}::X86LowerAMXCast::optimizeAMXCastFromPhi</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#ad2bfc3e2f7b1661868517e662ac7496c">optimizeBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-loadstorevectorizer-cpp-/#ae31219d422e76099c3c5dfaa2c7171cb">anonymous{LoadStoreVectorizer.cpp}::reorder</a>, <a href="/web-llvm/docs/api/classes/anonymous-nvptxallocahoisting-cpp-/nvptxallocahoisting/#a3e0401219219142d6d4aa7cb0859afc7">anonymous{NVPTXAllocaHoisting.cpp}::NVPTXAllocaHoisting::runOnFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a63f2a772f8b7a673be8aa85f4ea406d7">llvm::setWidenableBranchCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a9364799319bac519aa565ec882986e6d">simplifyRelocatesOffABase</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#afa4c018bf923954bfd4ce5b6bf15b68b">SinkInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#abf69483b802f1e342399912142341c60">sinkLastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#aa725413bc28036ce9c795a24503f654b">llvm::coro::sinkSpillUsesAfterCoroBegin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af99540103c8717d41b490fc2a1acad5c">llvm::InstCombinerImpl::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a27f63a779f3bcae1f300371e33227bed">llvm::widenWidenableBranch</a>.</p>

</div>
</div>

### moveBefore() {#a56d0f00463a6a160af0a6966cc5ed885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> InsertPos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this instruction from its current basic block and insert it into the basic block that MovePos lives in, right before MovePos.</p>

<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### moveBefore() {#a850566850f6c034f3d39773112b0427b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveBefore (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unlink this instruction and insert into BB before I.</p>


<dl class="doxySectionUser">
<dt>Precondition</dt>
<dd><p>I is a valid iterator into BB.</p></dd>
</dl>


<p>Declaration at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

### moveBeforePreserving() {#ae3c2accff1fc7b0c4fc5ab15915573af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveBeforePreserving (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a <a href="#af67d1f3a518964d80a109bb3d9d5cf1e">moveBefore</a> operation, while signalling that the caller intends to preserve the original ordering of instructions.</p>


<p>This implicitly means that any adjacent debug-info should move with this instruction.</p>


<p>Declaration at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa76a2cf19b821f320ab439d5659ef4b9">llvm::MergeBlockIntoPredecessor</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a6e4c46869d9d198562f7b8628814e407">raiseUserConstantDataAllocasToEntryBlock</a>.</p>

</div>
</div>

### moveBeforePreserving() {#af53129f70dd4f0dae21bb5099ebecedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveBeforePreserving (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> I)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a <a href="#af67d1f3a518964d80a109bb3d9d5cf1e">moveBefore</a> operation, while signalling that the caller intends to preserve the original ordering of instructions.</p>


<p>This implicitly means that any adjacent debug-info should move with this instruction.</p>


<p>Declaration at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#aed565a1dfd056c37a481581db8cdbedd">hasAllowReassoc</a> and <a href="#a5b5ee2f5097a11b4f6fc135a1d147de4">setHasAllowReassoc</a>.</p>

</div>
</div>

### moveBeforePreserving() {#a28c50733b8b3ed88997ca245cd0d6a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveBeforePreserving (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * MovePos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a <a href="#af67d1f3a518964d80a109bb3d9d5cf1e">moveBefore</a> operation, while signalling that the caller intends to preserve the original ordering of instructions.</p>


<p>This implicitly means that any adjacent debug-info should move with this instruction.</p>


<p>Deprecated in favour of the iterator-accepting flavour of moveBeforePreserving, as all insertions should be at iterator positions.</p>


<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a100c666f9253331dd1d166a863248326">hasNoUnsignedWrap</a> and <a href="#a0c03b71c79206ec41270dc3788183e0d">setHasNoUnsignedWrap</a>.</p>

</div>
</div>

### removeFromParent() {#a0fd53f63d349dc8a7c5fc0cdd7a94c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::removeFromParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method unlinks 'this' from the containing basic block, but does not delete it.</p>

<p>Declaration at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a5a43b0bc7c25aaaa14cf3d79d7f13c78">DbgInserterHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#adf0b3634500370e379ded8d75a72e791">llvm::InstCombinerImpl::matchBSwapOrBitReverse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ab9fcdedd3580f924cf782f155b549a22">rewritePHIsForCleanupPad</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a7f1482a3531f0a99f5481d84bae6127e">llvm::JumpThreadingPass::unfoldSelectInstr</a>.</p>

</div>
</div>

### replaceSuccessorWith() {#a657e5d1f0907b46daf10219e2b9b5ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::replaceSuccessorWith (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * OldBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * NewBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Replace specified successor OldBB to point at the provided block.</p>


<p>This instruction must be a terminator.</p>


<p>Declaration at line 984 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1308 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a198849b6cd6aa24831fb54477ee69dca">llvm::AtomicCmpXchgInst::setSyncScopeID</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-loopvectorize-cpp-/generatedrtchecks/#af15e3fefdfa2f5ea86ef5b8eacfa3517">anonymous{LoopVectorize.cpp}::GeneratedRTChecks::emitMemRuntimeChecks</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>.</p>

</div>
</div>

### setAAMetadata() {#a4dd9b6c5bb93e01393c47dbe60f8b23f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setAAMetadata (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> metadata on this instruction from the <a href="/web-llvm/docs/api/structs/llvm/aamdnodes">AAMDNodes</a> structure.</p>

<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1764 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/aggressiveinstcombine/aggressiveinstcombine-cpp/#a5a43eda4795549e941b4bacafdb956bb">foldConsecutiveLoads</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#afdbe575a191d9f3b5b6cef8212745dc0">anonymous{LICM.cpp}::LoopPromoter::insertStoresInLoopExitBlocks</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ace8766b97ac54db2bec8c29e4016f3f6">speculateSelectInstLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#acce887569ed105b612c33053a3264608">unpackStoreToAggregate</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a679f36556ace611ccc56580cb497973a">llvm::InstCombinerImpl::visitExtractValueInst</a>.</p>

</div>
</div>

### setDebugLoc() {#ae8f5bf5cc06f696b52c709677df00fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Instruction::setDebugLoc (<a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> Loc)</td>
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

<p>Set the debug location information for this instruction.</p>

<p>Definition at line 508 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ac04b6d4e5d3715d33fee0cf6c80a15c8">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::addReachesFunctionCallbacksIfEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#a19cc77dc725d4cbbf994e5db311e3c97">applyFirstDebugLoc</a>, <a href="#ae88ca601f663c55cafa95cf742076aad">applyMergedLocation</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aea49493e2ae224d30cda2b3235d180b0">buildClonedLoopBlocks</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a2a8aa905f11fdce2fbbfd8e695d282b5">cloneInstructionsIntoPredecessorBlockAndUpdateSSAUses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#ad399adefaffab058aa56567aa1b59df9">llvm::DbgVariableRecord::createDebugIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a30a82385a4d14528fdc9819501044523">createFFSIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a7891243700b67217e42c82bb4224eb0c">createPopcntIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a5e53eb62d81882a5586764e2a9378a49">DoFlattenLoopPair</a>, <a href="#a4576d69ed1543b06e5c41eb43b630bf1">dropLocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad8629a06eaa190b10f442dd35c1df09a">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSaturatingIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenintorfpinductionrecipe/#a98d8cca54a99e8b64eb406f898565323">llvm::VPWidenIntOrFpInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidenpointerinductionrecipe/#ac53a5d033ba641288b6e15344d880186">llvm::VPWidenPointerInductionRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codeextractor-cpp/#aa1461454928a2518e7f3eea698b3a1da">fixupDebugInfoPostExtraction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ac0fb2da7eaa616e8ef8a8f52b981334b">foldCondBranchOnValueKnownInPredecessorImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2fc50d227d302eb98914f04bcc6634e1">llvm::InstCombinerImpl::foldOpIntoPhi</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#aaffd2ef85a5bde3351bbc659c18c1ebe">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::forceSingleThreadPerWorkgroupHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a94b383e649f60242503ff47c799fd22e">HandleByValArgumentInit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ad822c761168baefbdcd6c0d9fd928a6d">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::insertInstructionGuardsHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#afdbe575a191d9f3b5b6cef8212745dc0">anonymous{LICM.cpp}::LoopPromoter::insertStoresInLoopExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af414e22c02fcc9ff3ce2d81ee8d3cfcb">llvm::AMDGPU::instrumentAddressImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a790c96adef17241b1ba4dbf475c3e57e">LowerNegateToMultiply</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9d9df487d54cc5567b4e0b1c8e0120a8">llvm::InstCombinerImpl::mergeStoreIntoSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/divrempairs-cpp/#a6e3883483a49e3be2520667d933b25f8">optimizeDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a2c05548feac70b16d31caf0cfb225714">OptimizeExtractBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simplifycfgpass-cpp/#aec97a6e447a45c9027b71a487f5732ec">performBlockTailMerging</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6c837ffd3a1932f53de13120ad1551a">llvm::InstCombinerImpl::PHIArgMergedDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#abbc2deb942b00a9d0d19a6613e374168">llvm::JumpThreadingPass::processBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#ac06e19670a4cb86b0c885cf67bdb1bc4">llvm::JumpThreadingPass::processImpliedCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a96191c096e61f77ea0a6771263bdb5e1">llvm::JumpThreadingPass::processThreadableEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#ab1e7a17f7727ff9a32ffc2a1efdb7bcc">llvm::SCCPSolver::removeNonFeasibleEdges</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a83cbd0aa1465957c50eaea8374875b27">llvm::removeUnwindEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a96b5bd50d8e96b4c76ffc26508ce774d">replaceArgumentUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerconstantintrinsics-cpp/#aa39118ddf6c73ece724a5c5e93d0db1e">replaceConditionalBranchesOnConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a645f6e970e94d7ca51922b3932338f51">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::replaceRemWithNumeratorOrZero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#ad87f4b76b6846d029880d6b9012a7e69">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#a14553297713bc2c6012758ee13a2b917">llvm::coro::salvageDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4fb32c986b105bb7a53700e5988aab6e">llvm::setProbeDistributionFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0049977ff1075a98e9f512bbf4d181a6">sinkAndCmp0Expression</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a24a3e4aad4cb2fdde7ce294a531cd52a">sinkCmpExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a0327169186859791aafa580e4fb547e2">SinkShiftAndTruncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#ae2c617685e87af2501e3d53323f91df7">SplitLandingPadPredecessorsImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#a97cbd12fcf61e3cf7db640c3661e66df">tryToShorten</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#af1fb897c419e6a5080ecf54baf13f169">llvm::JumpThreadingPass::tryToUnfoldSelectInCurrBB</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#a6a082aa2e05f44f7dab89e2ff8c582ff">unswitchTrivialBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aadf6036e1d19c8ba91242af6ec48d40b">unswitchTrivialSwitch</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a957b517efddeb68617e18ffef3b64683">updateForIncomingValueLocation</a>.</p>

</div>
</div>

### setFast() {#aecf2ba7921a07e6b24434554e02c8106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setFast (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear all fast-math-flags on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 594 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 561 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### setFastMathFlags() {#a5ca8aa62fa8b3fe5bc0e8fbe5d8b8b7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setFastMathFlags (<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> FMF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience function for setting multiple fast-math flags on this instruction, which must be an operator which supports these flags.</p>


<p>See LangRef.html for the meaning of these flags.</p>


<p>Declaration at line 634 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a4b946333b7fb96fec126f22534cf3794">CreateAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a3621b702ef72b987959cdd7242c13d47">CreateMul</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a73ecec9fc9254930ac757b1e30a9a4e1">llvm::BinaryOperator::CreateWithFMF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#af5dffe23851d819cc3ed8126fdf8a42f">foldAddSubSelect</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bd29d381405675f36964e4a5382dae4">llvm::InstCombinerImpl::foldSelectOpOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineselect-cpp/#afdc0c60200d744fe53a7f48e3f7e4bb0">foldSelectWithFCmpToFabs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#aabcb01976dc50b78faed7491a6d43042">foldShuffleOfUnaryOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a225d5b1dcc0015e743f1dbbf348a9c36">llvm::InstCombinerImpl::SimplifyAssociativeOrCommutative</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a>.</p>

</div>
</div>

### setHasAllowContract() {#a3ea5d2b89cd3be3e0f07b97c466fe341}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasAllowContract (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the allow-contract flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="#a2c89a7c3adbeaf3cc5d02a41401801fb">cloneDebugInfoFrom</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### setHasAllowReassoc() {#a5b5ee2f5097a11b4f6fc135a1d147de4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasAllowReassoc (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the reassociation flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 599 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 566 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="#af53129f70dd4f0dae21bb5099ebecedc">moveBeforePreserving</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### setHasAllowReciprocal() {#acdb7b321e4ed4c3d80f4fa5fdc2c4a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasAllowReciprocal (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the allow-reciprocal flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 619 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### setHasApproxFunc() {#a542bbbf2a886b74cd2407c216ae06106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasApproxFunc (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the approximate-math-functions flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 629 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### setHasNoInfs() {#a94eaf07edb6829da0be0e8681375ac4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasNoInfs (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the no-infs flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 609 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### setHasNoNaNs() {#a4ef005763ae33d1f581c7809d7de1a4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasNoNaNs (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the no-nans flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 571 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a> and <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>.</p>

</div>
</div>

### setHasNoSignedWrap() {#a4166b451a572b1e5d3fea7250af53653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasNoSignedWrap (bool b=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the nsw flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 523 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#aea4ea86573aa983a20bb9af1019fd0f5">llvm::BinaryOperator::CreateNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a3555c92374939e341c136f73c9354d86">llvm::BinaryOperator::CreateNSW</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad8629a06eaa190b10f442dd35c1df09a">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSaturatingIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a9fc15c7f338806b191bd2977f4be2513">foldIntrinsicUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aa3255071e8195c43058f7e265c54677f">llvm::SCEVExpander::hoistIVInc</a>, <a href="#a54507f01d7d06127068ee0663233511d">moveAfter</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a177f4d30b9356e0bc4a5dc176e825cb2">simplifyIRemMulShl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad6315ffed3396dd69c53e1e51cfcd9f6">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenOverflowingOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### setHasNoSignedZeros() {#a27d07a2504f0f592823ee21311099249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasNoSignedZeros (bool B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the no-signed-zeros flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineaddsub-cpp/#a27bba7d498620b1d330d2ef77362f04f">foldFNegIntoConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a9eeb1caaa920e692849cb94d64b7d66f">llvm::InstCombinerImpl::foldSelectIntoOp</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af616ac59efde7c61f6e8ff8bd80d2027">llvm::InstCombinerImpl::visitFNeg</a>.</p>

</div>
</div>

### setHasNoUnsignedWrap() {#a0c03b71c79206ec41270dc3788183e0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setHasNoUnsignedWrap (bool b=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the nuw flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 519 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#abb40063a5c7439f459f7f143e706b7ee">llvm::BinaryOperator::CreateNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8fbbce94455a0a2b51e1db3daf2faa2a">llvm::BinaryOperator::CreateNUW</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a5a706e35559bb3deb6e92a8ac4bfe1e8">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad8629a06eaa190b10f442dd35c1df09a">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateSaturatingIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac38a3c2794db0ecc70c9bb7106f1e1bf">llvm::InstCombinerImpl::foldAddWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#ac6169fee4cf2c33a0c3abb46628bfefc">foldCttzCtlz</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a9fc15c7f338806b191bd2977f4be2513">foldIntrinsicUsingDistributiveLaws</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aa3255071e8195c43058f7e265c54677f">llvm::SCEVExpander::hoistIVInc</a>, <a href="#a28c50733b8b3ed88997ca245cd0d6a3b">moveBeforePreserving</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#ac89087c7d7dc7ce68b17d57237c170c8">NegateValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a177f4d30b9356e0bc4a5dc176e825cb2">simplifyIRemMulShl</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#ad6315ffed3396dd69c53e1e51cfcd9f6">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenOverflowingOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a01ed915fb2acf9fd660ca752edeec0db">llvm::InstCombinerImpl::visitMul</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a606601489498c1ba41f25e77eb2dd0cf">llvm::InstCombinerImpl::visitSub</a>.</p>

</div>
</div>

### setIsExact() {#ac01940f561517355e394911c203bcedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setIsExact (bool b=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the exact flag on this instruction, which must be an operator which supports this flag.</p>


<p>See LangRef.html for the meaning of this flag.</p>


<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8d5176ac30d2d151700b01a9f3451131">llvm::InstCombinerImpl::commonIDivTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aa831d259fa5719e16927b5f4877988db">llvm::InstCombinerImpl::commonShiftTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a83f8671569d1c9271896f8bb4b1be5e9">llvm::BinaryOperator::CreateExact</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a75232ba08deca2d4237adb5780fe2198">llvm::BinaryOperator::CreateExact</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineshifts-cpp/#a04e846746dd1839f88b9a39847f5d643">foldShiftedShift</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#af9fc0080b4accc0b19bfbbc624701e30">llvm::ConstantExpr::getAsInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/instmodificationirstrategy/#abd12a5e2bbbe4379385128cc1a481463">llvm::InstModificationIRStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4b2e9167fd714396a473ee5493c1350b">llvm::InstCombinerImpl::reassociateShiftAmtsOfTwoSameDirectionShifts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4bb2cbb88b57c9a126549efe2134d1cb">llvm::InstCombinerImpl::SimplifyDemandedUseBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a8ff215a6e938a8df32c29c99bc126603">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::strengthenRightShift</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a612d91fe0858006abe73d7b62821da0c">llvm::InstCombinerImpl::visitAShr</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#af12904244ec179b265540ed1fb8c6615">llvm::InstCombinerImpl::visitSDiv</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a1cdbee2aa0ed532c8d9e91a00cc91f37">llvm::InstCombinerImpl::visitUDiv</a>.</p>

</div>
</div>

### setMetadata() {#a9247a212ea89acc9573fa7e7f557eaba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setMetadata (unsigned KindID, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the metadata of the specified kind to the specified node.</p>


<p>This updates or replaces metadata if already present, or removes it if <a href="/web-llvm/docs/api/classes/node">Node</a> is null.</p>


<p>Declaration at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1679 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e627c32543ca70720c4270a8b11da3f">llvm::cast_or_null</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a>, <a href="#a565f546ad95bd3a9bbe9a1e5040803f0">hasMetadata</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a338590123630c357df6340c38d066572">llvm::Value::setMetadata</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="#a9a7c63edb94ce4fab2a5bb34dbf6079a">addAnnotationMetadata</a>, <a href="#a6762e9e611c29b13a5c94bf8488fe798">addAnnotationMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#ac36177cea684b1e36fdbc92d692f69d0">addBasicBlockMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/loopversioning/#a5da1dcc92515b7cdd28ce936d6488964">llvm::LoopVersioning::annotateInstWithNoAlias</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a521a0263cd32258d251908a3b8ab2f78">llvm::annotateValueSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/classes/llvm/memprof/callstacktrie/#ab9f10c4267af88a1bd143a7260d2ac8f">llvm::memprof::CallStackTrie::buildAndAttachMIBMetadata</a>, <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a00d35e1397cf2210fd30e1993c1eaab9">combineStoreToNewValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a152d8c380cc937c9dceb402ceec943b6">llvm::ConstantFoldTerminator</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#ae9315c94e4cd695aceef039966a2beba">copyMetadataForAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2f8e44f52bb2b2c5d2273eccec70faae">llvm::copyMetadataForLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab057ca6ed74ccfa73d1a0d2cf15b2300">llvm::copyNonnullMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadb1772c1026a517d15c771ceb6a91ca">llvm::copyRangeMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0097c4a6c82120f14b29ec4e3fb8abb8">llvm::IRBuilderBase::CreateElementUnorderedAtomicMemCpy</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac3e775626bfa565297feec5807947efc">llvm::IRBuilderBase::CreateElementUnorderedAtomicMemMove</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a28b3cd753cf67eba6720294e776739b9">llvm::IRBuilderBase::CreateElementUnorderedAtomicMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a87415932de9b5f1e2b693d96ad8790e6">llvm::IRBuilderBase::CreateMemSet</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#adb8c63ccc6e3dffe894c9934435fa01c">llvm::IRBuilderBase::CreateMemSetInline</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a650efd24c2b5011ed33bc980e62b0d61">llvm::IRBuilderBase::CreateMemTransferInst</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeac445a66283c4e567ebd390c058e39d">llvm::IRBuilderBase::CreatePreserveArrayAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4804fd7127d8e249a628e93d6b8b3f2a">llvm::IRBuilderBase::CreatePreserveStructAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aab968563d4e62085875f57273828523d">llvm::IRBuilderBase::CreatePreserveUnionAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#acf512f516130aaabdd835c48140c9e5c">anonymous{SampleProfile.cpp}::SampleProfileLoader::generateMDProfMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a5a020f0ab461a1f6e3b87aff314bd040">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#abf39bad779191e6a85e053be5111c399">insertNewDbgInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-licm-cpp-/looppromoter/#afdbe575a191d9f3b5b6cef8212745dc0">anonymous{LICM.cpp}::LoopPromoter::insertStoresInLoopExitBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopsimplify-cpp/#ae72984cd3577f73b7880883b12808a8c">insertUniqueBackedgeBlock</a>, <a href="#a2711d3bc7c6c769a8f34c7fc3937169d">mergeDIAssignID</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a0346c3f86c714b9ae84f5566a95e90ac">migrateDebugInfo</a>, <a href="/web-llvm/docs/api/classes/metadataloader/metadataloaderimpl/#a4a81e1117a068de8d409b76e45c3e494">llvm::MetadataLoader::MetadataLoaderImpl::parseMetadataAttachment</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a31a4e5663521fd6944605496cbc32bbb">performBranchToCommonDestFolding</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a380713e3d0da9090dbc68193076703b7">propagateMemProfHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a48a6deb3e714d54e75caadcf84b0ca76">llvm::propagateMetadata</a>, <a href="#a4dd9b6c5bb93e01393c47dbe60f8b23f">setAAMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a08c7dd6c9db484e7609dc95fca6cc55e">llvm::setIrrLoopHeaderMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad7cd933f586fc0c66656a4751ac069f">llvm::setLoopEstimatedTripCount</a>, <a href="#a695a53ce0b9f537880373b4ea1824a6b">setMetadata</a>, <a href="#a959c782ed643a36be7d7264e379025d1">setNoSanitizeMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae3e39244e3fac45ac81d2096353f2b38">llvm::InstCombinerImpl::SimplifyAnyMemTransfer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac950ae90e1bea2697f515628f7704b2a">llvm::SplitBlockAndInsertIfThenElse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxiltranslatemetadata-cpp/#ab10b653a914cecca232400be7a563633">translateBranchMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#aae4261fb86bc9023c3383785afa66b9a">unswitchNontrivialInvariants</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-autoupgrade-cpp-/amdgpuunsafefpatomicsupgradevisitor/#aa5a373065be6eabfcc9eeb46018af87c">anonymous{AutoUpgrade.cpp}::AMDGPUUnsafeFPAtomicsUpgradeVisitor::visitAtomicRMWInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-amdgpulatecodegenprepare-cpp-/amdgpulatecodegenprepare/#ac006d6756149a16407027bc971cedab0">anonymous{AMDGPULateCodeGenPrepare.cpp}::AMDGPULateCodeGenPrepare::visitLoadInst</a>.</p>

</div>
</div>

### setMetadata() {#a695a53ce0b9f537880373b4ea1824a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1612 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="#a565f546ad95bd3a9bbe9a1e5040803f0">hasMetadata</a> and <a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a>.</p>

</div>
</div>

### setNonNeg() {#a75e5beda8f609473a08473e574511de8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setNonNeg (bool b=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear the nneg flag on this instruction, which must be a zext instruction.</p>

<p>Declaration at line 531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ae573064e881a6a5e07f9904117a9102e">llvm::refineInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2043c82134190abe45de829d07042606">llvm::replaceSignedInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a4d45f96f90c7ddd805c6bae2949077de">llvm::InstCombinerImpl::visitUIToFP</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### setNoSanitizeMetadata() {#a959c782ed643a36be7d7264e379025d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setNoSanitizeMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the nosanitize metadata on this instruction.</p>

<p>Declaration at line 500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1771 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a> and <a href="#a9247a212ea89acc9573fa7e7f557eaba">setMetadata</a>.</p>

</div>
</div>

### setSuccessor() {#ae959364e4640ac025bbc046d3d7c7e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::setSuccessor (unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the specified successor to point at the provided block.</p>


<p>This instruction must be a terminator.</p>


<p>Declaration at line 980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1296 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab2a2c89b21cf14b2c729a898006cb438">llvm::IRBuilderBase::CreateAtomicRMW</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypes/#gga17a137327ed1a49585a00c585313ec18a23c6e83673e9129aabab472592b272eb">LLVMAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a72f80871b9f46788c255158fbab96879">llvm::User::Op</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a399d7b7e2e6aec8e1ad80d3d73b7b1c8">CloneLoopBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a8478b291f8a10892334ba0bcf6a18528">cloneLoopBlocks</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a16d5e17e2ce1be5012b2d00ab6d6669a">llvm::createMemCpyLoopKnownSize</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandmemcmp-cpp-/memcmpexpansion/#a36cf9f1978b6c3bce437ad288b98e1dc">anonymous{ExpandMemCmp.cpp}::MemCmpExpansion::getMemCmpExpansion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ab89e1812569bb89edf9e25c3582913">llvm::SplitKnownCriticalEdge</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afe4c82c6f42e62e67ce856488751517d">llvm::JumpThreadingPass::threadEdge</a> and <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#accef1dd983ed3831858fe41c90fcc214">llvm::JumpThreadingPass::threadThroughTwoBasicBlocks</a>.</p>

</div>
</div>

### swapProfMetadata() {#a6e324daba99cb1d67713a562f9a778d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::swapProfMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the instruction has "branch_weights" MD_prof metadata and the <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> has three operands (including name string), swap the order of the metadata.</p>

<p>Declaration at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1319 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a6550fe5bd437c1c3c6e237d726e36b90">llvm::BranchInst::swapSuccessors</a>.</p>

</div>
</div>

### updateLocationAfterHoist() {#ae2bf20cca6e2a10783f868d80a7c0400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::updateLocationAfterHoist ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Updates the debug location given that the instruction has been hoisted from a block to a predecessor of that block.</p>


<p>Note: it is undefined behavior to call this on an instruction not currently inserted into a function.</p>


<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 982 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a>.</p>


<p>Reference <a href="#a4576d69ed1543b06e5c41eb43b630bf1">dropLocation</a>.</p>

</div>
</div>

### user\_back() {#a6609528bd67d5506a9bf9a2cce2d6f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * llvm::Instruction::user_back ()</td>
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

<p>Specialize the methods defined in <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>, as we know that an instruction can only be used by other instructions.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aab1473644ffe7926032a4e01ed4bad78">llvm::InstCombinerImpl::foldIntegerTypedPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a949d5831f77e0c9dc7d3509911cf92f2">llvm::ARMTTIImpl::getArithmeticInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#ae83866ca1a903e74fd6b66c1fec0d528">llvm::ARMTTIImpl::getCmpSelInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a4e307866e6d65e87d1e6884b0d13306c">llvm::LoopVectorizationCostModel::getReductionPatternCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a0581d6d5dc280ba2a39087a557050a6a">isNotUsedOrFoldableInLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a801d960feba2403acf8dbd07ee3f34b6">replaceExtractElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a19d2abc5a580be68aa7751c0e1ce7263">ShouldBreakUpSubtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a53e9a46c5489f12eb459b3ecce3db181">shouldExpandCmpArithRMWInIR</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#a80f5f1399bc814c650325a6c41e350e2">speculatePHINodeLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a5a81ca548cc88df15a58aed766bdd890">llvm::FastISel::tryToFoldLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2a5120238e6845643a37d5a4675a5342">llvm::InstCombinerImpl::visitSExt</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a2175862566372c3684fe4f7bf62e3143">llvm::InstCombinerImpl::visitZExt</a>.</p>

</div>
</div>

### user\_back() {#a9c799bce3238ef2d8b7b2da3e03745d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Instruction * llvm::Instruction::user_back ()</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a>.</p>

</div>
</div>

### willReturn() {#aa03e017ef451ba2f6f504b0d40c2da2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Instruction::willReturn ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the instruction will return (unwinding is considered as a form of returning control flow here).</p>

<p>Declaration at line 866 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1194 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#abbd47852a13b73290f4625f20c9018d8">isRemovableWrite</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sink-cpp/#a5e126bad06b6fa7c75f524f304deb7b0">isSafeToMove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getSubclassData() {#a041694a1ea45996587ef9712d9a2bb1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BitfieldElement&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BitfieldElement::Type llvm::Instruction::getSubclassData ()</td>
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



<p>Definition at line 1063 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitfield/#a3cd3d6331b8a3ea50db05696debf2075">llvm::Bitfield::get</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfield/#a706db80c3026ce5f7761347054eca6ae">llvm::Bitfield::isOverlapping</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a42438d0a43720a6571c9138224481754">llvm::AllocaInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a86d413c1d3a59e65cd9fe1c67ea12b0a">llvm::AtomicCmpXchgInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a0b5bee42a0652f7f46ec24c924e610d7">llvm::AtomicRMWInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#af51c113a039c82f6870df5dc9666b5e3">llvm::LoadInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a3b47950858d6ed72efd1010a35b81caa">llvm::StoreInst::getAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a3ff92cec76009e859cb0c419d6e8ba5f">llvm::CallBase::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a514c327438f006bc3fe66da51943b5cb">llvm::AtomicCmpXchgInst::getFailureOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a99fd4ef84981d6a2774c14c741b5ed65">llvm::AtomicRMWInst::getOperation</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#aefa60bfe67b4721c395ce966ac73b439">llvm::AtomicRMWInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/fenceinst/#abd9ff637c66279c825f9dd00ceff10f9">llvm::FenceInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a93603fe0d4168b92a901f06015ecb2e7">llvm::LoadInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#a0aa920e83c0d914fb05917bae65fd038">llvm::StoreInst::getOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#aa7414ba9f658ff1287d22a4b8fe81bcb">llvm::CmpInst::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#abb509fb245e8c6b6331b5dec01e80ac7">llvm::AtomicCmpXchgInst::getSuccessOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a8f907245246e05c0220934144c013aee">llvm::CallInst::getTailCallKind</a>, <a href="/web-llvm/docs/api/classes/llvm/catchswitchinst/#ac1a99c39ccf8cb184c24814059bda018">llvm::CatchSwitchInst::hasUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst/#a8b05c2709e71c04c66dd2da306413ec0">llvm::CleanupReturnInst::hasUnwindDest</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a0966e2f38f20609a643b5d5e3da8bae5">llvm::LandingPadInst::isCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a3016b467a9ecb5506956f7d029509db5">llvm::AllocaInst::isSwiftError</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#a9bb98c4ac4cf77f5782e5e41f2c6f38a">llvm::AllocaInst::isUsedWithInAlloca</a>, <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a248ee22702ba698e7704486bcdfed852">llvm::AtomicCmpXchgInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst/#a34f1aa991a80c9618af5d4e84aafcb9c">llvm::AtomicRMWInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/loadinst/#a2eccc19f9061eeb7ad1e30e21f76034d">llvm::LoadInst::isVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/storeinst/#ae3098a2ed52ddc6b853a3006ea646b7e">llvm::StoreInst::isVolatile</a> and <a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst/#a91b66c93e687bd0ea2d74a896c09408b">llvm::AtomicCmpXchgInst::isWeak</a>.</p>

</div>
</div>

### setSubclassData() {#afbb5877d4ac72148b232c8fedb08bba5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename BitfieldElement&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Instruction::setSubclassData (typename BitfieldElement::Type Value)</td>
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



<p>Definition at line 1072 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/bitfield/#a706db80c3026ce5f7761347054eca6ae">llvm::Bitfield::isOverlapping</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfield/#aac5c44667e3b3ebe2ed424dbd12a35d5">llvm::Bitfield::set</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/landingpadinst/#a97bc0afbd46cc7b3539e1cba861ac350">llvm::LandingPadInst::setCleanup</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a126a12b67fa620ad28ec0c919ca7a3e8">llvm::CmpInst::setPredicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### cloneImpl() {#ab1f8cd591829a6701818590ee806306a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * Instruction::cloneImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a copy of this instruction.</p>

<p>Declaration at line 1087 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1315 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### getAllMetadataImpl() {#a469fa5988ead0e34ab6cd440965468ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::getAllMetadataImpl (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::pair&lt; unsigned, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * &gt; &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 725 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1776 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### getMetadataImpl() {#a7c885f9a985e24c4132d4760868a527a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * Instruction::getMetadataImpl (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 723 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1618 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

### getSubclassDataFromValue() {#a0f8e7c93bf65b664f74ea285f203bb82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::Instruction::getSubclassDataFromValue ()</td>
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



<p>Definition at line 1054 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### moveBeforeImpl() {#a3e6b3a00101e8c0ae0c083a127e9f4d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::moveBeforeImpl (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">InstListType::iterator</a> I, bool Preserve)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>RemoveDIs project: all other moves implemented with this method, centralising debug-info updates into one place.</p>

<p>Declaration at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### setValueSubclassData() {#ac0ab6cff2d4e000a85e3b295fb4743cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Instruction::setValueSubclassData (unsigned short D)</td>
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



<p>Definition at line 1050 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### updateDIAssignIDMapping() {#ade9bf913d64dd33b0f46cbb63f7190ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Instruction::updateDIAssignIDMapping (<a href="/web-llvm/docs/api/classes/llvm/diassignid">DIAssignID</a> * ID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> ID-to-Instruction(s) mapping.</p>


<p>If <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span> is nullptr then clear the mapping for this instruction.</p>


<p>Declaration at line 729 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 1648 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### DebugMarker {#a0172245e9f9a9097b5d403ab70348bdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbgMarker* llvm::Instruction::DebugMarker = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optional marker recording the position for debugging information that takes effect immediately before this instruction.</p>


<p>Null unless there is debugging information present.</p>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Referenced by <a href="#a431be97c0e4d03f713d927197cdcfff0">getDbgRecordRange</a> and <a href="/web-llvm/docs/api/classes/llvm/dbgmarker/#a98eceec46c49f571b3413d3f91e31e10">llvm::DbgMarker::removeMarker</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DbgLoc {#aec7d7ab3746e87db585dc63d6b42112d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugLoc llvm::Instruction::DbgLoc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### Order {#a8b66fa88bd0391e5ce77fc93ba7e9022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::Instruction::Order = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Relative order of this instruction in its parent basic block.</p>


<p>Used for O(1) local dominance checks between instructions.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a644afe0cf8a4816171b3384098325dc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 987 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="#a644afe0cf8a4816171b3384098325dc2">classof</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>.</p>


<p>Referenced by <a href="#a644afe0cf8a4816171b3384098325dc2">classof</a>.</p>

</div>
</div>

### getOpcodeName() {#a5695ce86ca3854c8b1ad5020c3aa71ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * Instruction::getOpcodeName (unsigned Opcode)</td>
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



<p>Declaration at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>, definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="#af10fa975001cd000bc6aaa88267d970f">BasicBlock</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5cff1b957d4c020c106da5126e6304d3">llvm::IRBuilderBase::CreateCleanupRet</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/instruction/#a034571bc982742eb2cb2d135dee93eb2">llvm::sandboxir::Instruction::setInsertPos</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### isAssociative() {#a58c0f69b2d18b94c651b13d8e7fd9ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isAssociative (unsigned Opcode)</td>
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



<p>Definition at line 743 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="#a4f0027b9d05b27206b1882976fce9038">isAssociative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>

</div>
</div>

### isBinaryOp() {#a19a7026c9bfca302daa96fff1445910a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isBinaryOp (unsigned Opcode)</td>
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



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isBitwiseLogicOp() {#a2d0036d2d7b30f510927731ba7a4f4b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isBitwiseLogicOp (unsigned Opcode)</td>
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

<p>Determine if the Opcode is and/or/xor.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a295de4cfe04f8cf0dee3bc16c78e5f13">llvm::InstCombinerImpl::foldBinOpShiftWithShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a6556e45ee27ad333bf33eda6b1f04b8a">foldBitCastBitwiseLogic</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#ac7754c95309ff1784b1e47b0001deeee">getBinOpsForFactorization</a>, <a href="#ac3376e3bd632ad72252638ae43295ce4">isBitwiseLogicOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a41c00c458f7416c93927bc2f332b3898">simplifyAssocCastAssoc</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ab8c09431e3ba6ccd88dfa4a32c2127be">simplifyLogicOfAddSub</a>.</p>

</div>
</div>

### isCast() {#a47e931b4753c5d32baf9a2f8de1e2d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isCast (unsigned Opcode)</td>
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

<p>Determine if the Opcode is one of the <a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> instructions.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isCommutative() {#a48dd504e040ba9c89e802af96c78dd25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isCommutative (unsigned Opcode)</td>
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



<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaec211f7c20af43e742bf2570c3cb84f9">llvm::Add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eaf552e181879ad14956985859308d77d9">llvm::FAdd</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eab48b2a9934af7a531cfd7236ded9d50e">llvm::FMul</a>, <a href="#a55743bd32282bf6f87aeb49237b1fb68">isCommutative</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>

</div>
</div>

### isFPDivRem() {#a257920a1e7211884082cc6e599f4bd7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isFPDivRem (unsigned Opcode)</td>
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



<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isFuncletPad() {#ab1d8db0294e807c6834618d54d2fb6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isFuncletPad (unsigned Opcode)</td>
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

<p>Determine if the Opcode is one of the <a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a> instructions.</p>

<p>Definition at line 379 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isIdempotent() {#a6761fd11adc4d27f569d339c3c0c8c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isIdempotent (unsigned Opcode)</td>
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



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830eac33315685a0cba3ce53be378b3c7874b">llvm::And</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea3a2d5fe857d8f9541136a124c2edec6c">llvm::Or</a>.</p>

</div>
</div>

### isIntDivRem() {#aea89163a72302081fba69821b3a5bf13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isIntDivRem (unsigned Opcode)</td>
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



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isNilpotent() {#ab8528558d235e86bddc040ae8580746b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isNilpotent (unsigned Opcode)</td>
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



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea76feb79109026728a20736a8c6504548">llvm::Xor</a>.</p>

</div>
</div>

### isShift() {#a345db67ae3444fc10db37ff34cf4166e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isShift (unsigned Opcode)</td>
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

<p>Determine if the Opcode is one of the shift instructions.</p>

<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isSpecialTerminator() {#a3c1f1a7ac43254d4242048c2a92d6734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isSpecialTerminator (unsigned Opcode)</td>
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

<p>Returns true if the Opcode is a "special" terminator that does more than branch to a successor (e.g.</p>


<p>have a side effect or return a value).</p>


<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isTerminator() {#aca1cfb64ba31b4b2eb24b5bb0f4a03b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isTerminator (unsigned Opcode)</td>
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



<p>Definition at line 329 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

### isUnaryOp() {#ab3506fee8672213803272ce81e15eb43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Instruction::isUnaryOp (unsigned Opcode)</td>
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



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instruction-h">Instruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfo-cpp">DebugInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/metadata-cpp">Metadata.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
