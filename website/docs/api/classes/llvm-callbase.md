---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/callbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `CallBase` Class

<p>Base class for all callable instructions (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> and <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>) Holds everything related to calling a function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::CallBase { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">llvm/IR/InstrTypes.h</a>"
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

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callbrinst">CallBrInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>CallBr instruction, tracking function calls that may not return control but instead transfer it to a third location. <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a function call, abstracting a target machine's calling convention. <a href="/web-llvm/docs/api/classes/llvm/callinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst">CoroAwaitSuspendInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This represents the llvm.coro.await.suspend.{void,bool,handle} instructions. <a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst">GCStatepointInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a gc.statepoint intrinsic call. <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Invoke instruction. <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2202e11d8597e6945b50553155da0f6c">CallInstReservedField</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; unsigned, 0, 2 &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20cd52815cac3179b0c156c0c1e32a1b">CallingConvField</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfield/element">Bitfield::Element</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a>, <a href="/web-llvm/docs/api/structs/llvm/bitfield/element/#ac97bc0b40f8f7b458e734291ef255f93">CallInstReservedField::NextBit</a>, 10, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca2f101663d054cffa9c9956f30e7ecf7d">CallingConv::MaxID</a> &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... ArgsTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a> (AttributeList const &amp;A, FunctionType *FT, ArgsTy &amp;&amp;... Args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6139303612b013feb3df0e6c5e1ad26">getConvergenceControlToken</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the convergence control token for this call, if it exists. <a href="#ad6139303612b013feb3df0e6c5e1ad26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c35bd078a268a207f607d0f57dadba">getFunctionType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba272b7337f4e135f28eeb0bcc69adbb">mutateFunctionType</a> (FunctionType *FTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b423d0aabe8aa38adbafa70bcfe441f">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">User::op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>data_operands_begin/data_operands_end - Return iterators iterating over the call / invoke argument list and bundle operands. <a href="#a3085b56a4d6537a84c58e62e535adb71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">User::const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4f7a09419cfbecd02dc93b0a922734e">data_operands_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">User::op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">User::const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a7d0271d0b5cee584dd4587ce8f570">data_operands_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">User::op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ba46d7221ffbc2c8b346d0ffb852438">data_ops</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">User::const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae626892238af2ed1a7344a2182bdd432">data_ops</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f72468f6bf9fb34cda794c49aefb65c">data_operands_empty</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc718f223186f71669ec794545a4d0ea">data_operands_size</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb1d2333537383d23ad22081752930f">isDataOperand</a> (const Use *U) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a560101563557d89f119dd261d2eb9940">isDataOperand</a> (Value::const_user_iterator UI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec61b88c722cd0e736fa93b4b599a19">getDataOperandNo</a> (Value::const_user_iterator UI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a value use iterator, return the data operand corresponding to it. <a href="#a3ec61b88c722cd0e736fa93b4b599a19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219b662245bf37ec1b2af068525c500b">getDataOperandNo</a> (const Use *U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a use for a data operand, get the data operand number that corresponds to it. <a href="#a219b662245bf37ec1b2af068525c500b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">User::op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the iterator pointing to the beginning of the argument list. <a href="#a4fb513d744ca72275932b2c7003f16f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">User::const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e55f2560cba1c3de7a6fb03b9da1cc1">arg_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">User::op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the iterator pointing to the end of the argument list. <a href="#ac0f11b96f81b2769dd23d028e3189075">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">User::const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9050deb0dfd0aaed9ff2f1df1706923">arg_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">User::op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad027ea8803d83ee19b9a2e13aec6d655">args</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Iteration adapter for range-for loops. <a href="#ad027ea8803d83ee19b9a2e13aec6d655">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">User::const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75853e55318f84e0df01706473daa624">args</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0efb2d7a831e24212063c504045d3203">arg_empty</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabd76e6a8a23a5af1ce4d3c310d88bcd">getArgOperand</a> (unsigned i) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc10b887caad109288ffceb230493a85">setArgOperand</a> (unsigned i, Value *v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1c6e6fdb0e2812d7f3b97ae16caeb44">getArgOperandUse</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Wrappers for getting the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> of a call argument. <a href="#aa1c6e6fdb0e2812d7f3b97ae16caeb44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f7ef00950294f037ed4b63aa7ebfa0b">getArgOperandUse</a> (unsigned i)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeac59c1598cb931a07550c901220bcf2">isArgOperand</a> (const Use *U) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe3eec799f786c28b6bc7b1d6e21813">isArgOperand</a> (Value::const_user_iterator UI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2be14a6cee99d5f27223178c42366f3">getArgOperandNo</a> (const Use *U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a use for a arg operand, get the arg operand number that corresponds to it. <a href="#ad2be14a6cee99d5f27223178c42366f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5a933ce70d8e5aeaa84005090a62a0">getArgOperandNo</a> (Value::const_user_iterator UI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a value use iterator, return the arg operand number corresponding to it. <a href="#a9b5a933ce70d8e5aeaa84005090a62a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ce0dcf6d29175cc7d7738ef77d1dd81">hasArgument</a> (const Value *V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this CallSite passes the given Value* as an argument to the called function. <a href="#a1ce0dcf6d29175cc7d7738ef77d1dd81">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d13199cbf4d080d3b5dcf330dad5d2c">getCalledOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8efa5432c5bf5ac4050ab6d3b27594c4">getCalledOperandUse</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56ba724ca88adebc9d7f9d0062e5f0e2">getCalledOperandUse</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the function called, or null if this is an indirect function invocation or the function signature does not match the call signature. <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574efc7d85ff014d5f15e077f3c82e6b">isIndirectCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the callsite is an indirect call. <a href="#a574efc7d85ff014d5f15e077f3c82e6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a754b47054852401f87e52805d15bdf05">isCallee</a> (Value::const_user_iterator UI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the passed iterator points to the callee operand's <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>. <a href="#a754b47054852401f87e52805d15bdf05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89338ed7a9ad9bc5cb9d771d79ebd5ba">isCallee</a> (const Use *U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> is the callee operand's <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>. <a href="#a89338ed7a9ad9bc5cb9d771d79ebd5ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afac5b39bcbb90d660f83d9b4bd8c6d95">getCaller</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper to get the caller (the parent function). <a href="#afac5b39bcbb90d660f83d9b4bd8c6d95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f7541a49e43b7bed69b5f590ed966f">getCaller</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50426b12f4acb3d9f74d0778948e9597">isMustTailCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this call site must be tail call optimized. <a href="#a50426b12f4acb3d9f74d0778948e9597">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c6594a90c163f7347396d39e094abe">isTailCall</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tests if this call site is marked as a tail call. <a href="#af2c6594a90c163f7347396d39e094abe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62778065b99372cc62cf994b967e7e8">getIntrinsicID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the intrinsic called or <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">Intrinsic::not_intrinsic</a> if the called function is not an intrinsic, or if this is an indirect call. <a href="#ac62778065b99372cc62cf994b967e7e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad70fe60b7ed052c6a74863944b518251">setCalledOperand</a> (Value *V)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee56a5257c4899bf97c5957d87a732e3">setCalledFunction</a> (Function *Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the function called, including updating the function type. <a href="#aee56a5257c4899bf97c5957d87a732e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea8b7cad8cee4202b900bd648a98bdf">setCalledFunction</a> (FunctionCallee Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the function called, including updating the function type. <a href="#a8ea8b7cad8cee4202b900bd648a98bdf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0107453b6a36d93e5a10d48cdac4d06c">setCalledFunction</a> (FunctionType *FTy, Value *Fn)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the function called, including updating to the specified function type. <a href="#a0107453b6a36d93e5a10d48cdac4d06c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ff92cec76009e859cb0c419d6e8ba5f">getCallingConv</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0851b4de29686e9c3918449b054cfada">setCallingConv</a> (CallingConv::ID CC)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a018f0394a375233d538109968b76a05a">isInlineAsm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this call is an inline asm statement. <a href="#a018f0394a375233d538109968b76a05a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042568b06f355d5c5fcd78dcfb381676">hasDescriptor</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3758e792ce9aeb9dea98f70b3d4715">getNumSubclassExtraOperands</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41fc1cf527faa2225d1c8589b08314d3">getNumSubclassExtraOperandsDynamic</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of extra operands for instructions that don't have a fixed number of extra operands. <a href="#a41fc1cf527faa2225d1c8589b08314d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a75d6fe5ffe0df5c42c2eed243726d3">hasFnAttrOnCalledFunction</a> (Attribute::AttrKind Kind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201344cbb7c2893ea88f8f1e4fa75572">hasFnAttrOnCalledFunction</a> (StringRef Kind) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AttrKind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adb7a292e6d06890882b156168d82b85c">hasFnAttrImpl</a> (AttrKind Kind) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AK&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a930cd28d366d4597913b7108fdb94868">getFnAttrOnCalledFunction</a> (AK Kind) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AK&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9cc421e50b26e4986a97db788c8db7dd">getParamAttrOnCalledFunction</a> (unsigned ArgNo, AK Kind) const</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename AttrKind&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3290146bc52003c0772c6f1ca7df2636">hasRetAttrImpl</a> (AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the return value has the given attribute. <a href="#a3290146bc52003c0772c6f1ca7df2636">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parameter attributes for callable <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacb21b50e69e3d808db0120e9a0a7b9d">FTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca631a010bfa5a055b7a07fe9e68f7e9">Create</a> (CallBase *CB, ArrayRef&lt; OperandBundleDef &gt; Bundles, InsertPosition InsertPt=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone of <span class="doxyComputerOutput">CB</span> with a different set of operand bundles and insert it before <span class="doxyComputerOutput">InsertPt</span>. <a href="#aca631a010bfa5a055b7a07fe9e68f7e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6577a1fc727a8972f1fcd8d14c70b29e">Create</a> (CallBase *CB, OperandBundleDef Bundle, InsertPosition InsertPt=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone of <span class="doxyComputerOutput">CB</span> with the operand bundle with the tag matching <span class="doxyComputerOutput">Bundle's</span> tag replaced with Bundle, and insert it before <span class="doxyComputerOutput">InsertPt</span>. <a href="#a6577a1fc727a8972f1fcd8d14c70b29e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70d8ffa4f0ffa07bd736cb74d178d917">addOperandBundle</a> (CallBase *CB, uint32_t ID, OperandBundleDef OB, InsertPosition InsertPt=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone of <span class="doxyComputerOutput">CB</span> with operand bundle <span class="doxyComputerOutput">OB</span> added. <a href="#a70d8ffa4f0ffa07bd736cb74d178d917">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad82786d29c116d0bf5131f654d51e681">removeOperandBundle</a> (CallBase *CB, uint32_t ID, InsertPosition InsertPt=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a clone of <span class="doxyComputerOutput">CB</span> with operand bundle <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span> removed. <a href="#ad82786d29c116d0bf5131f654d51e681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f751706099c68d86b273f33971bc76">classof</a> (const Instruction *I)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad608d6540a71ecab577d6e890a458209">classof</a> (const Value *V)</td>
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

## Protected Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598efe23bbf3bd82fa6b6a5588aa58b9">CalledOperandOpEndIdx</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The last operand is the called operand. <a href="#a598efe23bbf3bd82fa6b6a5588aa58b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Operand Bundle API Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49f898706ddd985e5d2673f203832578">bundle_op_iterator</a> = <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> *</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8638b163c6d6824432adf467aab267">const_bundle_op_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> *</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of operand bundles associated with this <a href="/web-llvm/docs/api/classes/llvm/user">User</a>. <a href="#a35b3798829fba58f145ea59e4214e84a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/user">User</a> has any operand bundles. <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a21e7face454c8ea6c4b9e12b506e40">getBundleOperandsStartIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of the first bundle operand in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> array. <a href="#a7a21e7face454c8ea6c4b9e12b506e40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0951bc018bd4725e28d9d05e36a1360a">getBundleOperandsEndIndex</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of the last bundle operand in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> array. <a href="#a0951bc018bd4725e28d9d05e36a1360a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2be9e255ef96b741c5680c3d66f8587">isBundleOperand</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the operand at index <span class="doxyComputerOutput">Idx</span> is a bundle operand. <a href="#ac2be9e255ef96b741c5680c3d66f8587">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a203a11487b55577e3f295af2e3e2ae2a">isOperandBundleOfType</a> (uint32_t ID, unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the operand at index <span class="doxyComputerOutput">Idx</span> is a bundle operand that has tag <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>. <a href="#a203a11487b55577e3f295af2e3e2ae2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb497a3113f10b593158ab55bfd1e1c">isBundleOperand</a> (const Use *U) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the use is a bundle operand. <a href="#a5fb497a3113f10b593158ab55bfd1e1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3533647593dde9cf45849501086c9d2">isBundleOperand</a> (Value::const_user_iterator UI) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff4a43d51265443e3d62d49395d0b585">getNumTotalBundleOperands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the total number operands (not operand bundles) used by every operand bundle in this OperandBundleUser. <a href="#aff4a43d51265443e3d62d49395d0b585">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/operandbundleuse">OperandBundleUse</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a> (unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand bundle at a specific index. <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652220e0fde7043b474f1d6a85cd0452">countOperandBundlesOfType</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of operand bundles with the tag Name attached to this instruction. <a href="#a652220e0fde7043b474f1d6a85cd0452">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa08853cdbf6877e032d15d3900088e56">countOperandBundlesOfType</a> (uint32_t ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of operand bundles with the tag <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> attached to this instruction. <a href="#aa08853cdbf6877e032d15d3900088e56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse">OperandBundleUse</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ab5f34fb7b9476d45da0102ecbfae6">getOperandBundle</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an operand bundle by name, if present. <a href="#a23ab5f34fb7b9476d45da0102ecbfae6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse">OperandBundleUse</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0de2d66512556efff4898a90ef0f041">getOperandBundle</a> (uint32_t ID) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an operand bundle by tag <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, if present. <a href="#ae0de2d66512556efff4898a90ef0f041">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19263fff7f5b3a9d22b48151fa0d85d0">getOperandBundlesAsDefs</a> (SmallVectorImpl&lt; OperandBundleDef &gt; &amp;Defs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the list of operand bundles attached to this instruction as a vector of OperandBundleDefs. <a href="#a19263fff7f5b3a9d22b48151fa0d85d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/operandbundleuse">OperandBundleUse</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa635b5961d4592b8224755579c752414">getOperandBundleForOperand</a> (unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the operand bundle for the operand at index OpIdx. <a href="#aa635b5961d4592b8224755579c752414">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada195b22ad562f2d06824c595765dd30">hasReadingOperandBundles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this operand bundle user has operand bundles that may read from the heap. <a href="#ada195b22ad562f2d06824c595765dd30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4139298dd770711bf92cf3b95ba200a">hasClobberingOperandBundles</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this operand bundle user has operand bundles that may write to the heap. <a href="#ad4139298dd770711bf92cf3b95ba200a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d230e2d456d6a6c94d272428f05395">bundleOperandHasAttr</a> (unsigned OpIdx, Attribute::AttrKind A) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the bundle operand at index <span class="doxyComputerOutput">OpIdx</span> has the attribute <span class="doxyComputerOutput">A</span>. <a href="#ac0d230e2d456d6a6c94d272428f05395">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e301518882466a796c3b890aac2e866">hasIdenticalOperandBundleSchema</a> (const CallBase &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Other</span> has the same sequence of operand bundle tags with the same number of operands on each one of them as this OperandBundleUser. <a href="#a4e301518882466a796c3b890aac2e866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2d248762d49cd9fa5443dea54c7e6f3">hasOperandBundlesOtherThan</a> (ArrayRef&lt; uint32_t &gt; IDs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this operand bundle user contains operand bundles with tags other than those specified in <span class="doxyComputerOutput">IDs</span>. <a href="#aa2d248762d49cd9fa5443dea54c7e6f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/operandbundleuse">OperandBundleUse</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6cd42ee6d8d51324f79e5e5e5d5f74">operandBundleFromBundleOpInfo</a> (const BundleOpInfo &amp;BOI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simple helper function to map a <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> to an <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse">OperandBundleUse</a>. <a href="#a1b6cd42ee6d8d51324f79e5e5e5d5f74">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a49f898706ddd985e5d2673f203832578">bundle_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the start of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser. <a href="#a09fff26473ca9a3d9d1ff51633e048c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afe8638b163c6d6824432adf467aab267">const_bundle_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d15f6b4756852ff1757a7e479fbcb96">bundle_op_info_begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the start of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser. <a href="#a6d15f6b4756852ff1757a7e479fbcb96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a49f898706ddd985e5d2673f203832578">bundle_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the end of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser. <a href="#a418564b6605d97c81db3dc3ddc4cb948">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afe8638b163c6d6824432adf467aab267">const_bundle_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeebc4ed71de27cdd341498e7030a30ee">bundle_op_info_end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the end of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser. <a href="#aeebc4ed71de27cdd341498e7030a30ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a49f898706ddd985e5d2673f203832578">bundle_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63109b37b9bc1849d98d8f787ad650d7">bundle_op_infos</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range [<span class="doxyComputerOutput">bundle_op_info_begin</span>, <span class="doxyComputerOutput">bundle_op_info_end</span>). <a href="#a63109b37b9bc1849d98d8f787ad650d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#afe8638b163c6d6824432adf467aab267">const_bundle_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a0fc4db1daa05339f90300036edeea8">bundle_op_infos</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the range [<span class="doxyComputerOutput">bundle_op_info_begin</span>, <span class="doxyComputerOutput">bundle_op_info_end</span>). <a href="#a1a0fc4db1daa05339f90300036edeea8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93f122dff654f8336680531a3898375c">populateBundleOperandInfos</a> (ArrayRef&lt; OperandBundleDef &gt; Bundles, const unsigned BeginIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate the <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances and the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector from <span class="doxyComputerOutput">Bundles</span>. <a href="#a93f122dff654f8336680531a3898375c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec62dc363b96fea41e5a7e2e627498de">hasDeoptState</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the call has deopt state bundle. <a href="#aec62dc363b96fea41e5a7e2e627498de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a> (unsigned OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> for the operand at index OpIdx. <a href="#a05315814f0e1ff39f8e753d7ac430a02">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cee61c774fe9d8b6a956984a6168ad0">getBundleOpInfoForOperand</a> (unsigned OpIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac795264d758ae8856ba1f1f74fc4acb4">CountBundleInputs</a> (ArrayRef&lt; OperandBundleDef &gt; Bundles)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the total number of values used in <span class="doxyComputerOutput">Bundles</span>. <a href="#ac795264d758ae8856ba1f1f74fc4acb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Attribute API Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attributes for this call. <a href="#ae0c55761fce39dd71617690b04385193">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da3b29e8e71b9be4645874e1721207a">setAttributes</a> (AttributeList A)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the attributes for this call. <a href="#a9da3b29e8e71b9be4645874e1721207a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82be2ba8b164fb0cf70e254f9c8a13a3">getRetAttributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the return attributes for this call. <a href="#a82be2ba8b164fb0cf70e254f9c8a13a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attributeset">AttributeSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31dce9e2b84da293213f996778355b32">getParamAttributes</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the param attributes for this call. <a href="#a31dce9e2b84da293213f996778355b32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb49554840d9c699b6b3a2a09361dbd8">tryIntersectAttributes</a> (const CallBase *Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to intersect the attributes from 'this' <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> and the 'Other' <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>. <a href="#afb49554840d9c699b6b3a2a09361dbd8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this call has the given attribute. <a href="#a2fbfe5377a984518a7c03d8558df726d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c901967b076f5c9d245000b7637822a">hasFnAttr</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this call has the given attribute. <a href="#a4c901967b076f5c9d245000b7637822a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ec1fe122d152d6c6cefbdab43a43cdc">addAttributeAtIndex</a> (unsigned i, Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the attribute to the list of attributes. <a href="#a9ec1fe122d152d6c6cefbdab43a43cdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2060ab64acfc67af974e20cbc79ca273">addAttributeAtIndex</a> (unsigned i, Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the attribute to the list of attributes. <a href="#a2060ab64acfc67af974e20cbc79ca273">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the attribute to the function. <a href="#a0f72a62efd0912aba72c6818c720023c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031e44afee1f29cd934862cebf714a88">addFnAttr</a> (Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the attribute to the function. <a href="#a031e44afee1f29cd934862cebf714a88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94f59b6921a7cd3567439b3302a5357">addRetAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the attribute to the return value. <a href="#aa94f59b6921a7cd3567439b3302a5357">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae30660fb489f8cbe69bf8650daadcdb1">addRetAttr</a> (Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the attribute to the return value. <a href="#ae30660fb489f8cbe69bf8650daadcdb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5d05ec2b9a60806746addff3f2a71a9">addParamAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the attribute to the indicated argument. <a href="#ae5d05ec2b9a60806746addff3f2a71a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433ec4bd285111f13acdc8a78be16a72">addParamAttr</a> (unsigned ArgNo, Attribute Attr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds the attribute to the indicated argument. <a href="#a433ec4bd285111f13acdc8a78be16a72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab18063e13ecbbbdea86aa54cd118b1db">removeAttributeAtIndex</a> (unsigned i, Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the list of attributes. <a href="#ab18063e13ecbbbdea86aa54cd118b1db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38dc9fea21bad23a1ca15b9c7a7ec484">removeAttributeAtIndex</a> (unsigned i, StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>removes the attribute from the list of attributes. <a href="#a38dc9fea21bad23a1ca15b9c7a7ec484">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68f6ab734f9bafb1a1b591267ef402d8">removeFnAttrs</a> (const AttributeMask &amp;AttrsToRemove)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attributes from the function. <a href="#a68f6ab734f9bafb1a1b591267ef402d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd7acfca49e931306ba40f1eb6939f67">removeFnAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attribute from the function. <a href="#acd7acfca49e931306ba40f1eb6939f67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5536ea9f061a27091a487f69565b3e">removeFnAttr</a> (StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attribute from the function. <a href="#ada5536ea9f061a27091a487f69565b3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9724a78a61a4a4d72941116c6bd7c892">removeRetAttr</a> (Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attribute from the return value. <a href="#a9724a78a61a4a4d72941116c6bd7c892">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d9fe4a8103a58d5dee8ff09e6fa2152">removeRetAttrs</a> (const AttributeMask &amp;AttrsToRemove)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attributes from the return value. <a href="#a2d9fe4a8103a58d5dee8ff09e6fa2152">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ab5d0b4d639b3f79ff3922441e0082e">removeParamAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attribute from the given argument. <a href="#a2ab5d0b4d639b3f79ff3922441e0082e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7aecdc1aa280f1c8c0aa194b3453b46">removeParamAttr</a> (unsigned ArgNo, StringRef Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attribute from the given argument. <a href="#af7aecdc1aa280f1c8c0aa194b3453b46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14f9c4f42aae35f61b404a5d21e9d88d">removeParamAttrs</a> (unsigned ArgNo, const AttributeMask &amp;AttrsToRemove)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Removes the attributes from the given argument. <a href="#a14f9c4f42aae35f61b404a5d21e9d88d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf1a2105045f7e33738b34f49b0f9f08">addDereferenceableParamAttr</a> (unsigned i, uint64_t Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the dereferenceable attribute to the list of attributes. <a href="#adf1a2105045f7e33738b34f49b0f9f08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9add940717795f05bb69603216f17254">addDereferenceableRetAttr</a> (uint64_t Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the dereferenceable attribute to the list of attributes. <a href="#a9add940717795f05bb69603216f17254">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e7b74d310c94c459b8985806192cc99">addRangeRetAttr</a> (const ConstantRange &amp;CR)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>adds the range attribute to the list of attributes. <a href="#a0e7b74d310c94c459b8985806192cc99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a330471067c17061b7c2152d75102f24a">hasRetAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the return value has the given attribute. <a href="#a330471067c17061b7c2152d75102f24a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a528035b19a094c04b880d91fedfe8b6c">hasRetAttr</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the return value has the given attribute. <a href="#a528035b19a094c04b880d91fedfe8b6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06511680b1f7b6834735343e1d5c2e7f">getRetAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the attribute for the given attribute kind for the return value. <a href="#a06511680b1f7b6834735343e1d5c2e7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether the argument or parameter has the given attribute. <a href="#a4cbb2344996abd4332716e76178ad4f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcdfbff6a28275c90eab24a36cbc4240">getAttributeAtIndex</a> (unsigned i, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the attribute of a given kind at a position. <a href="#abcdfbff6a28275c90eab24a36cbc4240">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affe34085f142d12218c875ad46b506b8">getAttributeAtIndex</a> (unsigned i, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the attribute of a given kind at a position. <a href="#affe34085f142d12218c875ad46b506b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e46a3a4bf99f8dcea9cb9efb4d977a3">getFnAttr</a> (StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the attribute of a given kind for the function. <a href="#a9e46a3a4bf99f8dcea9cb9efb4d977a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a838a60b97fcf512dbf9116b564b05f2c">getFnAttr</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the attribute of a given kind for the function. <a href="#a838a60b97fcf512dbf9116b564b05f2c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50b4d34365cf704260dd9e43796144ea">getParamAttr</a> (unsigned ArgNo, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the attribute of a given kind from a given arg. <a href="#a50b4d34365cf704260dd9e43796144ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29461b85f0f7f0d91323ff2e40de2d75">getParamAttr</a> (unsigned ArgNo, StringRef Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the attribute of a given kind from a given arg. <a href="#a29461b85f0f7f0d91323ff2e40de2d75">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a> (unsigned i, Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the data operand at index <span class="doxyComputerOutput">i</span> has the attribute <span class="doxyComputerOutput">A</span>. <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27ab264aa1e655ed42732fe0ec40d441">doesNotCapture</a> (unsigned OpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this data operand is not captured. <a href="#a27ab264aa1e655ed42732fe0ec40d441">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610f151afe638890b21bea434a26821d">isByValArgument</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this argument is passed by value. <a href="#a610f151afe638890b21bea434a26821d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f410f8b74acae583c8589e52de992fa">isInAllocaArgument</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this argument is passed in an alloca. <a href="#a2f410f8b74acae583c8589e52de992fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af18a046d00e9c3059053fb96e43f0bfd">isPassPointeeByValueArgument</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether this argument is passed by value, in an alloca, or is preallocated. <a href="#af18a046d00e9c3059053fb96e43f0bfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c09dbc5b720c1d0a74e303d0e6765bf">isPassingUndefUB</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether passing undef to this argument is undefined behavior. <a href="#a1c09dbc5b720c1d0a74e303d0e6765bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a140af9f05b67d6b2a3b7cc8513254e2f">hasInAllocaArgument</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if there are is an inalloca argument. <a href="#a140af9f05b67d6b2a3b7cc8513254e2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d989cf6c0da10e436e1e95e380e0e09">doesNotAccessMemory</a> (unsigned OpNo) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857a8c38e4856efec047cc914c25b692">onlyReadsMemory</a> (unsigned OpNo) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63dc200b9de33401dee748b417e9b329">onlyWritesMemory</a> (unsigned OpNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d457bc91b566b5fdcb785dfc8862e7">getRetAlign</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the alignment of the return value. <a href="#a16d457bc91b566b5fdcb785dfc8862e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7713a45c8983df00c3975444b94e69ae">getParamAlign</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the alignment for a call or parameter (0=unknown). <a href="#a7713a45c8983df00c3975444b94e69ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a04c74b7f139321a0b49f5249e2d57">getParamStackAlign</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1951bdad78f9a0cb364948f121d6fba4">getParamByRefType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the byref type for a call or parameter. <a href="#a1951bdad78f9a0cb364948f121d6fba4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88cc5fa65ff17e62b49dc5fb4401f813">getParamByValType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the byval type for a call or parameter. <a href="#a88cc5fa65ff17e62b49dc5fb4401f813">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e664c47c22c883baf848ad37261637c">getParamPreallocatedType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the preallocated type for a call or parameter. <a href="#a1e664c47c22c883baf848ad37261637c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b576de254a0b0c5f278538862840e76">getParamInAllocaType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the inalloca type for a call or parameter. <a href="#a2b576de254a0b0c5f278538862840e76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287b116e4b7437fc6f4a0ca5f96add85">getParamStructRetType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the sret type for a call or parameter. <a href="#a287b116e4b7437fc6f4a0ca5f96add85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d39950dcbd9e1e6dac2b66db4324d4">getParamElementType</a> (unsigned ArgNo) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the elementtype type for a parameter. <a href="#aa9d39950dcbd9e1e6dac2b66db4324d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab114d0e71d6a1db826bade5d22b0028c">getRetDereferenceableBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the number of dereferenceable bytes for a call or parameter (0=unknown). <a href="#ab114d0e71d6a1db826bade5d22b0028c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37269632d3b68130c5b7019cd795be44">getParamDereferenceableBytes</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the number of dereferenceable bytes for a call or parameter (0=unknown). <a href="#a37269632d3b68130c5b7019cd795be44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf32f4feeff0b07e12c42c614a4791c1">getRetDereferenceableOrNullBytes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the number of dereferenceable_or_null bytes for a call (0=unknown). <a href="#acf32f4feeff0b07e12c42c614a4791c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaf8a257af9e537d7cd8b05299e5090c">getParamDereferenceableOrNullBytes</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the number of dereferenceable_or_null bytes for a parameter (0=unknown). <a href="#abaf8a257af9e537d7cd8b05299e5090c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c455a4c7338c00f6d0bc9efecf9cb8">getRetNoFPClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a test mask for disallowed floating-point value classes for the return value. <a href="#a08c455a4c7338c00f6d0bc9efecf9cb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a76921eddf6329af860916f3278ef1d1d">FPClassTest</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01640692cf7fbf4574227f7899af2e71">getParamNoFPClass</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract a test mask for disallowed floating-point value classes for the parameter. <a href="#a01640692cf7fbf4574227f7899af2e71">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64b47f684944bcb9aea2c1350440cd7">getRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this return value has a range attribute, return the value range of the argument. <a href="#aa64b47f684944bcb9aea2c1350440cd7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab40deb840751b104926b1052d91e7fc">isReturnNonNull</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the return value is known to be not null. <a href="#aab40deb840751b104926b1052d91e7fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5d60fefd4d76e44095f07fd48e46096">returnDoesNotAlias</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the return value is marked with NoAlias attribute. <a href="#aa5d60fefd4d76e44095f07fd48e46096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac95847047b045e505c83450ad09c1d25">getReturnedArgOperand</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If one of the arguments has the 'returned' attribute, returns its operand value. <a href="#ac95847047b045e505c83450ad09c1d25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7cae01462379060b2dae3f960054c6f">getArgOperandWithAttribute</a> (Attribute::AttrKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If one of the arguments has the specified attribute, returns its operand value. <a href="#ac7cae01462379060b2dae3f960054c6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb374eb65dcf7cd3d1671efb2616f76">isNoBuiltin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the call should not be treated as a call to a builtin. <a href="#a1fb374eb65dcf7cd3d1671efb2616f76">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300433f583bb9e2862b84df663f43f40">isStrictFP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call requires strict floating point semantics. <a href="#a300433f583bb9e2862b84df663f43f40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57c98f6b8ffe38c7c8d75f92a82d0ee3">isNoInline</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the call should not be inlined. <a href="#a57c98f6b8ffe38c7c8d75f92a82d0ee3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac74d68c9539ee35631f7f3435e46520b">setIsNoInline</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a> (MemoryEffects ME)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16951c81e4ffebc84739c2882a030e4f">doesNotAccessMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call does not access memory. <a href="#a16951c81e4ffebc84739c2882a030e4f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2db9f3ffecc57cf9333d355927413fbf">setDoesNotAccessMemory</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5be058522f7a1076ffb760c30171b2cd">onlyReadsMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call does not access or only reads memory. <a href="#a5be058522f7a1076ffb760c30171b2cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68bd81d0004f8cc3cdcef6151677c673">setOnlyReadsMemory</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca77ab9c9b9577f6ae3d1a08d6499738">onlyWritesMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call does not access or only writes memory. <a href="#aca77ab9c9b9577f6ae3d1a08d6499738">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923df3cbec0e08cc6d2be259286c2e3c">setOnlyWritesMemory</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc6331fb2f51f3f964b8f9494ab6620e">onlyAccessesArgMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call can access memmory only using pointers based on its arguments. <a href="#adc6331fb2f51f3f964b8f9494ab6620e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fa26173a9afc96fadd278584892766">setOnlyAccessesArgMemory</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34613a108e56086f52edab637d1d55ae">onlyAccessesInaccessibleMemory</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function may only access memory that is inaccessible from the IR. <a href="#a34613a108e56086f52edab637d1d55ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a52d36d02e6e763dbff76fffc55aef">setOnlyAccessesInaccessibleMemory</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a2ce134efb83b008e2180d30451ac98">onlyAccessesInaccessibleMemOrArgMem</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the function may only access memory that is either inaccessible from the IR or pointed to by its arguments. <a href="#a7a2ce134efb83b008e2180d30451ac98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f63e188e21bf64cfa775849cd37334d">setOnlyAccessesInaccessibleMemOrArgMem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8b80c508197d6dcbe67e082426a8026">doesNotReturn</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call cannot return. <a href="#ad8b80c508197d6dcbe67e082426a8026">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a086ea083312d974694676dcde76a1e65">setDoesNotReturn</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba8528d08dec5d59a0dc66f56588b7c">doesNoCfCheck</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call should not perform indirect branch tracking. <a href="#a4ba8528d08dec5d59a0dc66f56588b7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87fae97a8c702741eca5a95748af49d">doesNotThrow</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call cannot unwind. <a href="#aa87fae97a8c702741eca5a95748af49d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b6cef2a78857b0236b1c3a2a6eb857e">setDoesNotThrow</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d9c71916a2a8d7a227d871580265ce">cannotDuplicate</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the invoke cannot be duplicated. <a href="#a30d9c71916a2a8d7a227d871580265ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab343ed4a791fff67f7ab395b08b9a1e0">setCannotDuplicate</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08daddd36adb2d47a22de9b6177c7110">cannotMerge</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call cannot be tail merged. <a href="#a08daddd36adb2d47a22de9b6177c7110">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da7de997f92fdb5d3e85f4f5b9af20e">setCannotMerge</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32c9ebab7dfd3db749d0ab5e6e58b3e">isConvergent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the invoke is convergent. <a href="#ac32c9ebab7dfd3db749d0ab5e6e58b3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbe1ad518eb726a3d9eb83a31100ce48">setConvergent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85986906dda425ba6e72a3078ffd6421">setNotConvergent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae67e9ebc8e8d1033eaf27acf4ad622c">hasStructRetAttr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if the call returns a structure through first pointer argument. <a href="#aae67e9ebc8e8d1033eaf27acf4ad622c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1646cf4edf9e4502235bf4882f12f30e">hasByValArgument</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine if any call argument is an aggregate passed by value. <a href="#a1646cf4edf9e4502235bf4882f12f30e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for all callable instructions (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> and <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a>) Holds everything related to calling a function.</p>


<p>All call-like instructions are required to use a common operand layout:</p>


<ul class="doxyList ">
<li>Zero or more arguments to the call,</li>
<li>Zero or more operand bundles with zero or more operand inputs each bundle,</li>
<li>Zero or more subclass controlled operands</li>
<li>The called function.</li>
</ul>

<p>This allows this base class to easily access the called function and the start of the arguments without knowing how many other operands a particular subclass requires. Note that accessing the end of the argument list isn't as cheap as most other operations on the base class.</p>


<p>Definition at line 1112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### CallingConvField {#a20cd52815cac3179b0c156c0c1e32a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallBase::CallingConvField = 
      Bitfield::Element&lt;CallingConv::ID, CallInstReservedField::NextBit, 10,
                        CallingConv::MaxID&gt;</td>
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



<p>Definition at line 1116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### CallInstReservedField {#a2202e11d8597e6945b50553155da0f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallBase::CallInstReservedField =  Bitfield::Element&lt;unsigned, 0, 2&gt;</td>
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



<p>Definition at line 1115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### CallBase() {#a8a6c9c1339e7a196e0ae69031426c083}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... ArgsTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallBase::CallBase (<a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; A, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FT, ArgsTy &amp;&amp;... Args)</td>
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



<p>Definition at line 1130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="#aacb21b50e69e3d808db0120e9a0a7b9d">FTy</a> and <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>


<p>Referenced by <a href="#a70d8ffa4f0ffa07bd736cb74d178d917">addOperandBundle</a>, <a href="#a4e55f2560cba1c3de7a6fb03b9da1cc1">arg_begin</a>, <a href="#af9050deb0dfd0aaed9ff2f1df1706923">arg_end</a>, <a href="#a6d15f6b4756852ff1757a7e479fbcb96">bundle_op_info_begin</a>, <a href="#aeebc4ed71de27cdd341498e7030a30ee">bundle_op_info_end</a>, <a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst/#a636686efef82d935edef1e61de135f21">llvm::CoroAwaitSuspendInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#ade4b57265c96820be0f356f6062155ee">llvm::GCStatepointInst::classof</a>, <a href="#aca631a010bfa5a055b7a07fe9e68f7e9">Create</a>, <a href="#a6577a1fc727a8972f1fcd8d14c70b29e">Create</a>, <a href="#ab4f7a09419cfbecd02dc93b0a922734e">data_operands_begin</a>, <a href="#a33a7d0271d0b5cee584dd4587ce8f570">data_operands_end</a>, <a href="#a8cee61c774fe9d8b6a956984a6168ad0">getBundleOpInfoForOperand</a>, <a href="#af4f7541a49e43b7bed69b5f590ed966f">getCaller</a>, <a href="#a4e301518882466a796c3b890aac2e866">hasIdenticalOperandBundleSchema</a>, <a href="#ad82786d29c116d0bf5131f654d51e681">removeOperandBundle</a> and <a href="#afb49554840d9c699b6b3a2a09361dbd8">tryIntersectAttributes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### arg\_begin() {#a4fb513d744ca72275932b2c7003f16f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::op_iterator llvm::CallBase::arg_begin ()</td>
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

<p>Return the iterator pointing to the beginning of the argument list.</p>

<p>Definition at line 1261 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a8dba7d21d7bbdd6652c6f596d253bb24">llvm::GCStatepointInst::actual_arg_begin</a>, <a href="#a4e55f2560cba1c3de7a6fb03b9da1cc1">arg_begin</a>, <a href="#a0efb2d7a831e24212063c504045d3203">arg_empty</a>, <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="#ad027ea8803d83ee19b9a2e13aec6d655">args</a>, <a href="#a75853e55318f84e0df01706473daa624">args</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#adb44b65867ce48eee9d2d49cbdc60333">llvm::MLInlineAdvisor::getAdviceImpl</a>, <a href="#ad2be14a6cee99d5f27223178c42366f3">getArgOperandNo</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae94615351738e4ace274b61029700da9">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a78c7e7972f2cde9531b9f9d71196cfc5">hasSameArgumentList</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#a6760a5137f8e0ec21dbd7b99e61b52ed">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="#aeac59c1598cb931a07550c901220bcf2">isArgOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a26a463481e43dd8125ceef85d495be9d">isCondRelevantToAnyCallArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6300c8f1d33302d372c953398dd5f18c">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithNamedStructOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/classes/llvm/coroendresults/#a2b013435e5e5f26c868ad7d964ce6d3c">llvm::CoroEndResults::retval_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/coroendresults/#a72c47d8929ec6bd18d04b3cbdc7357b6">llvm::CoroEndResults::retval_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendretconinst/#a13b7bb8a696134a2d6612673b691e593">llvm::CoroSuspendRetconInst::value_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/corosuspendretconinst/#a6e48f873e5fea00e4dcf9735b0b31561">llvm::CoroSuspendRetconInst::value_begin</a>.</p>

</div>
</div>

### arg\_begin() {#a4e55f2560cba1c3de7a6fb03b9da1cc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::const_op_iterator llvm::CallBase::arg_begin ()</td>
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



<p>Definition at line 1262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a> and <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>.</p>

</div>
</div>

### arg\_empty() {#a0efb2d7a831e24212063c504045d3203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::arg_empty ()</td>
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



<p>Definition at line 1283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a> and <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp/#a494dabe67c8e93868fed4e59fbd49150">computeBytesPoppedByCalleeForSRet</a>, <a href="#a140af9f05b67d6b2a3b7cc8513254e2f">hasInAllocaArgument</a> and <a href="#aae67e9ebc8e8d1033eaf27acf4ad622c">hasStructRetAttr</a>.</p>

</div>
</div>

### arg\_end() {#ac0f11b96f81b2769dd23d028e3189075}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::op_iterator llvm::CallBase::arg_end ()</td>
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

<p>Return the iterator pointing to the end of the argument list.</p>

<p>Definition at line 1267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a> and <a href="#aff4a43d51265443e3d62d49395d0b585">getNumTotalBundleOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a9affda98a42fa9eeca661518ef2f4034">llvm::GCStatepointInst::actual_arg_end</a>, <a href="#a0efb2d7a831e24212063c504045d3203">arg_empty</a>, <a href="#af9050deb0dfd0aaed9ff2f1df1706923">arg_end</a>, <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="#ad027ea8803d83ee19b9a2e13aec6d655">args</a>, <a href="#a75853e55318f84e0df01706473daa624">args</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a23b0fbe869cf4baef885aaab613ffe56">llvm::GCStatepointInst::deopt_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a2df806263f1e5d5cfbd39ada183f6fd2">llvm::GCStatepointInst::deopt_end</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a748b2e4d7bb43011fcc43c38945c7a86">llvm::GCStatepointInst::gc_live_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#abe5a441ccb5494ac458909dd7b28ecdc">llvm::GCStatepointInst::gc_live_end</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a36080372317ba912639416f07a561506">llvm::GCStatepointInst::gc_transition_args_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#af422fe78a5f773d1d6948224670d7498">llvm::GCStatepointInst::gc_transition_args_end</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#adb44b65867ce48eee9d2d49cbdc60333">llvm::MLInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/aaresults/#ae94615351738e4ace274b61029700da9">llvm::AAResults::getModRefInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a78c7e7972f2cde9531b9f9d71196cfc5">hasSameArgumentList</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#afffa0ff2e1527ab545cef33be915c656">hostParallelCallback</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#a6760a5137f8e0ec21dbd7b99e61b52ed">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="#aeac59c1598cb931a07550c901220bcf2">isArgOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a26a463481e43dd8125ceef85d495be9d">isCondRelevantToAnyCallArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a2fea5f04ff43df5b1fc0a4304b7362c2">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerCtpopToCountBits</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a6300c8f1d33302d372c953398dd5f18c">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithNamedStructOp</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/classes/llvm/coroendresults/#af60bb734c396f05441a0cccc10a5fb2b">llvm::CoroEndResults::retval_end</a>, <a href="/web-llvm/docs/api/classes/llvm/coroendresults/#ac84b676da8b22a1806f8fa783616cc97">llvm::CoroEndResults::retval_end</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendretconinst/#a5e3d77d752ab18939e5ea29e04b788bd">llvm::CoroSuspendRetconInst::value_end</a> and <a href="/web-llvm/docs/api/classes/llvm/corosuspendretconinst/#a703aa5b41880b21021116b5e5e3d974a">llvm::CoroSuspendRetconInst::value_end</a>.</p>

</div>
</div>

### arg\_end() {#af9050deb0dfd0aaed9ff2f1df1706923}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::const_op_iterator llvm::CallBase::arg_end ()</td>
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



<p>Definition at line 1272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a> and <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>.</p>

</div>
</div>

### arg\_size() {#adde2ea00dd2613ee41bfe91908e4e68e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::arg_size ()</td>
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



<p>Definition at line 1284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a> and <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a8dba7d21d7bbdd6652c6f596d253bb24">llvm::GCStatepointInst::actual_arg_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="#a433ec4bd285111f13acdc8a78be16a72">addParamAttr</a>, <a href="#ae5d05ec2b9a60806746addff3f2a71a9">addParamAttr</a>, <a href="/web-llvm/docs/api/structs/anonymous-functionattrs-cpp-/argumentusestracker/#aa35ba8c73830d12eea5dda2a41aba718">anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::captured</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a58d962e3d29a81e1cdd18243bf6c71d3">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeArgumentPointerLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasyncendinst/#a38f76f44c524e7bbe9443b7d83c1e6ea">llvm::CoroAsyncEndInst::checkWellFormed</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3f603d822817256077c95e6573f2b14a">llvm::OpenMPIRBuilder::createTeams</a>, <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>, <a href="#a27ab264aa1e655ed42732fe0ec40d441">doesNotCapture</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a7a4b1bb434f664cf880b1dd79909c61a">getAllocationSize</a>, <a href="#aabd76e6a8a23a5af1ce4d3c310d88bcd">getArgOperand</a>, <a href="#a2f7ef00950294f037ed4b63aa7ebfa0b">getArgOperandUse</a>, <a href="#aa1c6e6fdb0e2812d7f3b97ae16caeb44">getArgOperandUse</a>, <a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a00c4a5b0ef7928bc65dca7af9a5a2b37">llvm::ConstrainedFPIntrinsic::getExceptionBehavior</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#aae2d74b7aa304f8f6126f4b1e6e00dd0">llvm::CallBrInst::getIndirectDestLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#a7929a2a96611a7af6f8a0f45d823c2b3">llvm::CallBrInst::getIndirectDestLabelUse</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasyncendinst/#a027bb9d1043a71779d88816a0e22140d">llvm::CoroAsyncEndInst::getMustTailCallFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a9ba9cd066476f18d59351934de5ee48d">llvm::ConstrainedFPIntrinsic::getNonMetadataArgCount</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a338bc4206ec4d19d62a2567d60c9c36c">llvm::AArch64TTIImpl::getOrCreateResultFromMemIntrinsic</a>, <a href="#a50b4d34365cf704260dd9e43796144ea">getParamAttr</a>, <a href="#a29461b85f0f7f0d91323ff2e40de2d75">getParamAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a4fc25c0fccec261829e187a058a772a9">llvm::ConstrainedFPIntrinsic::getRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ad9e8ff17d0545b9c796d2104b2e23a56">llvm::AArch64TTIImpl::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8bb58bae0761c8591279171367a2b334">handleGuaranteedWellDefinedOps</a>, <a href="#a140af9f05b67d6b2a3b7cc8513254e2f">hasInAllocaArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#a78c7e7972f2cde9531b9f9d71196cfc5">hasSameArgumentList</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a766df1ea3c4bf3cbc8586f310562034f">isReportingError</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>, <a href="#a857a8c38e4856efec047cc914c25b692">onlyReadsMemory</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="#a2ab5d0b4d639b3f79ff3922441e0082e">removeParamAttr</a>, <a href="#af7aecdc1aa280f1c8c0aa194b3453b46">removeParamAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a1fbbf5255240485629c031aa08e41c3f">removeTriviallyEmptyRange</a>, <a href="#abc10b887caad109288ffceb230493a85">setArgOperand</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a975eb04de3ce355131f2bdc9328def27">llvm::Attributor::translateArgumentToCallSiteContent</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#abfe65728f3f9352f6b3154da7803821e">tryToSplitCallSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a554ade21fa5bda8daa3af645c00364b1">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a49a422e75fb519fc9419967ae2c3679b">upgradeAbs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad9d7a82ba140ac920458705124372cd6">upgradeAVX512MaskToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#adaf155c02ba4c5b8ec6d8d72b50e0f91">upgradeDbgIntrinsicToDbgRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#acd3fbecf680813e839ac85bf3b3a81f2">upgradeMaskedCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ae2068f406068749ea0cca3bacd6815a0">upgradePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad194379f5156fa6a9ec196923d80df3a">upgradeX86BinaryIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#abbe50b1b6428dd6884355b64360f2f29">upgradeX86ConcatShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a2e38c407c9078c144f8aa68eef3ac0ac">upgradeX86Rotate</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyoptimizereturned-cpp-/optimizereturned/#ae81d17afe649660014f0e1ca569e8bf3">anonymous{WebAssemblyOptimizeReturned.cpp}::OptimizeReturned::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ac88e3e89148ab5849fc08d1eef269a84">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitCallBase</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### args() {#ad027ea8803d83ee19b9a2e13aec6d655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; User::op_iterator &gt; llvm::CallBase::args ()</td>
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

<p>Definition at line 1277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a>, <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a8971fbe1184d7b7301a70ee23b318772">addNonNullAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a490938b206738261d5984fe958a872ad">adjustInliningThresholdUsingCallee</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a9875dff9496a8c83bc0bcf749858c45b">buildIntrinsicArgTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a2ebf7459caf9252729048bd9c5231f6c">collectEscapedLocals</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a596e8b6e6b71f454b18f982f947e5e03">doesInTreeUserNeedToExtract</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#aa883d40ffa8836538699a7974632d0a0">getCallArgsTotalAllocaSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a3bc18cb70ac72d463ce6ee68cbc00d64">llvm::objcarc::GetCallSiteClass</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad1f0755693a05c2b008e9a576c3b162b">llvm::LoopVectorizationCostModel::getVectorCallCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5abced3ab870d7abf57f2b35a02cd041">llvm::LoopVectorizationCostModel::getVectorIntrinsicCost</a>, <a href="#a1ce0dcf6d29175cc7d7738ef77d1dd81">hasArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a68d6e6643cf0af54add83ed1ab981085">isPredicatedOnPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorybehaviorcallsite/#a0451826f9ecd21f9d963cc51401b1b4d">anonymous{AttributorAttributes.cpp}::AAMemoryBehaviorCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#af31ca6130fc1fdac86bfb75b1acac4ac">markTails</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a8e6d3da10023ff90b874399d8a1d7880">setConstantInArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a4ce4b835cffc5fa4123fe82f5f39cf97">upgradeAArch64IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad9d7a82ba140ac920458705124372cd6">upgradeAVX512MaskToSelect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargaarch64helper/#a41ca0d5d12f5940de41f29cf08066e00">anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#acc81d19554e4eb245d659a89a2fd6f37">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararggenerichelper/#ab229cd82fd788028a0ff3a1f1957e7f9">anonymous{MemorySanitizer.cpp}::VarArgGenericHelper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a372b313738e7d6b96b0ef622ce60890c">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper/#af0bc023f29f779469e5e8e3f92b9db0f">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::visitCallBase</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### args() {#a75853e55318f84e0df01706473daa624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; User::const_op_iterator &gt; llvm::CallBase::args ()</td>
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



<p>Definition at line 1280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a>, <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### data\_operands\_begin() {#a3085b56a4d6537a84c58e62e535adb71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::op_iterator llvm::CallBase::data_operands_begin ()</td>
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

<p>data_operands_begin/data_operands_end - Return iterators iterating over the call / invoke argument list and bundle operands.</p>


<p>For invokes, this is the set of instruction operands except the invoke target and the two successor blocks; and for calls this is the set of instruction operands except the call target.</p>


<p>Definition at line 1213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>.</p>


<p>Referenced by <a href="#ab4f7a09419cfbecd02dc93b0a922734e">data_operands_begin</a>, <a href="#a1f72468f6bf9fb34cda794c49aefb65c">data_operands_empty</a>, <a href="#acc718f223186f71669ec794545a4d0ea">data_operands_size</a>, <a href="#a6ba46d7221ffbc2c8b346d0ffb852438">data_ops</a>, <a href="#ae626892238af2ed1a7344a2182bdd432">data_ops</a>, <a href="#a219b662245bf37ec1b2af068525c500b">getDataOperandNo</a> and <a href="#aebb1d2333537383d23ad22081752930f">isDataOperand</a>.</p>

</div>
</div>

### data\_operands\_begin() {#ab4f7a09419cfbecd02dc93b0a922734e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::const_op_iterator llvm::CallBase::data_operands_begin ()</td>
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



<p>Definition at line 1214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a> and <a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a>.</p>

</div>
</div>

### data\_operands\_empty() {#a1f72468f6bf9fb34cda794c49aefb65c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::data_operands_empty ()</td>
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



<p>Definition at line 1231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a> and <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a>.</p>

</div>
</div>

### data\_operands\_end() {#a8448c3e780b73347f00055dbbbc98a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::op_iterator llvm::CallBase::data_operands_end ()</td>
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



<p>Definition at line 1217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4a3758e792ce9aeb9dea98f70b3d4715">getNumSubclassExtraOperands</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>.</p>


<p>Referenced by <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a>, <a href="#a1f72468f6bf9fb34cda794c49aefb65c">data_operands_empty</a>, <a href="#a33a7d0271d0b5cee584dd4587ce8f570">data_operands_end</a>, <a href="#acc718f223186f71669ec794545a4d0ea">data_operands_size</a>, <a href="#a6ba46d7221ffbc2c8b346d0ffb852438">data_ops</a>, <a href="#ae626892238af2ed1a7344a2182bdd432">data_ops</a> and <a href="#aebb1d2333537383d23ad22081752930f">isDataOperand</a>.</p>

</div>
</div>

### data\_operands\_end() {#a33a7d0271d0b5cee584dd4587ce8f570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">User::const_op_iterator llvm::CallBase::data_operands_end ()</td>
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



<p>Definition at line 1222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a> and <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a>.</p>

</div>
</div>

### data\_operands\_size() {#acc718f223186f71669ec794545a4d0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::data_operands_size ()</td>
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



<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a> and <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a>.</p>

</div>
</div>

### data\_ops() {#a6ba46d7221ffbc2c8b346d0ffb852438}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; User::op_iterator &gt; llvm::CallBase::data_ops ()</td>
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



<p>Definition at line 1225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a>, <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### data\_ops() {#ae626892238af2ed1a7344a2182bdd432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; User::const_op_iterator &gt; llvm::CallBase::data_ops ()</td>
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



<p>Definition at line 1228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a>, <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a7b423d0aabe8aa38adbafa70bcfe441f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallBase::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### getArgOperand() {#aabd76e6a8a23a5af1ce4d3c310d88bcd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::CallBase::getArgOperand (unsigned i)</td>
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



<p>Definition at line 1286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae54a643a9f9d83374bb4d7d22d4662d7">AddAlignmentAssumptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a6396da6d0b65cef8693b0aedd06f31e3">llvm::SystemZTTIImpl::adjustInliningThreshold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aebd8fb1e50c14f4988226de940a067ed">annotateNonNullNoUndefBasedOnAccess</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aamemorylocationimpl/#a58d962e3d29a81e1cdd18243bf6c71d3">anonymous{AttributorAttributes.cpp}::AAMemoryLocationImpl::categorizeArgumentPointerLocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#ad696038e18d6965dc078902075026d9b">checkIfSupported</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a5af505d92ab7180dda5a7fa14fa24dfd">llvm::AnyCoroIdRetconInst::checkWellFormed</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidasyncinst/#aa384a27e0cb9e2e608147d53aa927cdd">llvm::CoroIdAsyncInst::checkWellFormed</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#ab330f042033636da90859626bc4dc542">llvm::CoroIdInst::clearPromise</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinemuldivrem-cpp/#a0adb0a856adef09fd017379f4644ba4e">convertFSqrtDivIntoFMul</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aa49cf0e393f7067f09985cec1d4b7387">convertStrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3f603d822817256077c95e6573f2b14a">llvm::OpenMPIRBuilder::createTeams</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#af3e1fd8c444e23d60cbfdfa3d0279cb4">destArrayCanBeWidened</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a133fc35b714b7fc4b5a0935c811ed37a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::emitSIMDTiling</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-expandmemcmp-cpp-/#aa507b512719f5e8d2b31c99f5534541b">anonymous{ExpandMemCmp.cpp}::expandMemCmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8148654fcf3528ef06d7a0e28b57b952">llvm::findDevirtualizableCallsForTypeCheckedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#ac1582713ab3ea01b71ad1cd559fbf4af">foldCtpopPow2Test</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac1c36177d82543f048444e40d97f16a8">llvm::funcReturnsFirstArgOfCall</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#af196b6ea9e0a63c97336480d7fe60c27">llvm::GCStatepointInst::getActualCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/coroallocaallocinst/#a24c0edabd00b4d1be4c296b6e49b8dfa">llvm::CoroAllocaAllocInst::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/coropromiseinst/#a4d8579c6558228656059605b5c1c4fb7">llvm::CoroPromiseInst::getAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/coroallocafreeinst/#ab736eca4ac9627bbafc2557485bbb051">llvm::CoroAllocaFreeInst::getAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/coroallocagetinst/#a91a82cf8289849455e2d7f5a9a8d5a1e">llvm::CoroAllocaGetInst::getAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a6557fc92152c6e431a0072d7fe76bd83">llvm::AnyCoroIdRetconInst::getAllocFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acdec81ddbe2a44db51de1226fa1ff5f0">llvm::getAllocSize</a>, <a href="/web-llvm/docs/api/classes/llvm/vaendinst/#a1bdb2d4d39f25b07fe9f291d73d40de5">llvm::VAEndInst::getArgList</a>, <a href="/web-llvm/docs/api/classes/llvm/vastartinst/#af66868b7cbd9c85e897068f3f6c5c1bc">llvm::VAStartInst::getArgList</a>, <a href="#ac7cae01462379060b2dae3f960054c6f">getArgOperandWithAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasynccontextdeallocinst/#a408cad1d4886ba53e81472a7852285d4">llvm::CoroAsyncContextDeallocInst::getAsyncContext</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#a22e75cd1b723b6fae19aebb4407f9c60">llvm::CoroSuspendAsyncInst::getAsyncContextProjectionFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasynccontextallocinst/#aec91e357f7c432ac64c479e194efd3b6">llvm::CoroAsyncContextAllocInst::getAsyncFunctionPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidasyncinst/#ab461e95beef7d14d7d648575035c5e63">llvm::CoroIdAsyncInst::getAsyncFunctionPointer</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeinst/#a17b57890f95cdbd177267fd8ec7b76c3">llvm::PseudoProbeInst::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst/#ad95956ea38c201709e4f6e230ccdebff">llvm::CoroAwaitSuspendInst::getAwaiter</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#ae33641b6538b4ab4f3aa3dad2926860f">llvm::GCRelocateInst::getBasePtrIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofmcdctvbitmapupdate/#a0f4d563ee73453c0056c66a1ccbeaaae">llvm::InstrProfMCDCTVBitmapUpdate::getBitmapIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a4c4c33f562e18b287ca4ca5b0e0eedc7">getBranchWeight</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite/#a0d0520a20214373f2e8cfd17db2d86a2">llvm::InstrProfCallsite::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendinst/#aa359a0b614626b5bfafbc095eef26e04">llvm::CoroSuspendInst::getCoroSave</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#a5678ec2adcd02082dc703831ebdee65c">llvm::CoroIdInst::getCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/corobegininst/#ac55ea7c80f2d057ece6d44ce81ac2054">llvm::CoroBeginInst::getCustomABI</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#abe0e0a10af167017af1842ba615492ab">llvm::AnyCoroIdRetconInst::getDeallocFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/gcrelocateinst/#af4362abf4fd66b2cfbd6d1b0590dbbdf">llvm::GCRelocateInst::getDerivedPtrIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/vacopyinst/#adc1e943acc2dfc31c6e79b10db8bf1a0">llvm::VACopyInst::getDest</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a00c4a5b0ef7928bc65dca7af9a5a2b37">llvm::ConstrainedFPIntrinsic::getExceptionBehavior</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeinst/#ad0fb97860a5867a93ee182af576ef45b">llvm::PseudoProbeInst::getFactor</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a7e0495e0f7d0b948c7b38f862035acbe">llvm::GCStatepointInst::getFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#af438c8da3109f9d2b1530aed2771b88e">llvm::MemoryLocation::getForSource</a>, <a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst/#a661148f67663ccb7062f61fa52acd614">llvm::CoroAwaitSuspendInst::getFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/corofreeinst/#a0dc7f14ec3e33bf5fd7e4bffe91fb981">llvm::CoroFreeInst::getFrame</a>, <a href="/web-llvm/docs/api/classes/llvm/corosubfninst/#a54a9f5b070810ccdabc867b0324f616e">llvm::CoroSubFnInst::getFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeinst/#af93ae26b85bd31e18d254eec2efd5d4d">llvm::PseudoProbeInst::getFuncGuid</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofinstbase/#ac3fea7437bee644ad742fa36f7735498">llvm::InstrProfInstBase::getHash</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a4f370e414666fd92c2ec6fdfc70eaafd">llvm::GCStatepointInst::getID</a>, <a href="/web-llvm/docs/api/classes/llvm/corobegininst/#a30b3ddd0433d254830f61bf122e5eefc">llvm::CoroBeginInst::getId</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase/#a47828ff886349450c00ffb6afd03b4f0">llvm::InstrProfCntrInstBase::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofvalueprofileinst/#a22a603b4cab18fb6057bd866ab11501d">llvm::InstrProfValueProfileInst::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/pseudoprobeinst/#a185f8aa0815d5f116eef69368f218ca0">llvm::PseudoProbeInst::getIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#a4d180adab34368b65e2a43f64c7de814">getISDForVPIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/kernelinfo/#a3ce86cd1750ba693983bdec2c5d361be">KernelInfo::getKernelEnvironementGVFromKernelInitCB</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a0fef04103987e9763468d19eb680b223">llvm::MemIntrinsicBase&lt; Derived &gt;::getLength</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#abd530ffa05240e0728bf85169dc7abcc">llvm::BinaryOpIntrinsic::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpintrinsic/#ad7ffbaac0e2e619375210475ee1080a6">llvm::CmpIntrinsic::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a673a466c3e8606df34705f6953698a10">llvm::MinMaxIntrinsic::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ae3a6cf3016819a83fe114e42db5df7f7">llvm::VPIntrinsic::getMaskParam</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofmcdctvbitmapupdate/#a0d322eb2b8f98ddf1c1440e6e0cab334">llvm::InstrProfMCDCTVBitmapUpdate::getMCDCCondBitmapAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/corobegininst/#ae89883a1c15c3e54f66479db5b03fb35">llvm::CoroBeginInst::getMem</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#acc801d404cca596b586df87ab8f19897">llvm::VPIntrinsic::getMemoryDataParam</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ad2dbe79feecaee785999f4958f39fbb0">llvm::VPIntrinsic::getMemoryPointerParam</a>, <a href="/web-llvm/docs/api/classes/llvm/coroasyncendinst/#a027bb9d1043a71779d88816a0e22140d">llvm::CoroAsyncEndInst::getMustTailCallFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#afa005fa6599ee04bd121e40a0dcdf756">llvm::CoroSuspendAsyncInst::getMustTailCallFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofinstbase/#ad6fc31f833f27dc182b882cbeceb7a5a">llvm::InstrProfInstBase::getNameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofmcdcbitmapinstbase/#a3c7aa30ce3bb0681330630b35ef01d35">llvm::InstrProfMCDCBitmapInstBase::getNumBitmapBits</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a2e0ebfdcf1d9e384aeb9c597d0d11b7c">llvm::GCStatepointInst::getNumCallArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase/#ad93cb99f29b17839f8a166d04df8ccf5">llvm::InstrProfCntrInstBase::getNumCounters</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a0f7597de18eb49e3c6b9f1a15980a46f">llvm::GCStatepointInst::getNumPatchBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a338bc4206ec4d19d62a2567d60c9c36c">llvm::AArch64TTIImpl::getOrCreateResultFromMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpcmpintrinsic/#a0848b587dc3e457693603a7d61f6bbb4">llvm::ConstrainedFPCmpIntrinsic::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/vpcmpintrinsic/#abd4835d4ce4a46f73cc1a219b7b410b4">llvm::VPCmpIntrinsic::getPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#aa17122071013697e6134f40d91c5c69d">llvm::CoroIdInst::getPromise</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a3f0278794a8d4c4711fd5d60fbb28515">llvm::AnyCoroIdRetconInst::getPrototype</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a9865b76f7e5dd72798f0b9fda5f17a57">llvm::DbgAssignIntrinsic::getRawAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#ad565da45575440ec9c4dfb5b1348ebdd">llvm::DbgAssignIntrinsic::getRawAddressExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#ae3e889eb2faa001e5488a8d64712ad86">llvm::DbgAssignIntrinsic::getRawAssignID</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a18d6accbeb5cb7b8051219b8b4ddd4f7">llvm::MemIntrinsicBase&lt; Derived &gt;::getRawDest</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicmemintrinsic/#a4596a484b5b93d0e64dd537778fa3ae8">llvm::AtomicMemIntrinsic::getRawElementSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#ae8046dbd496e42d7fc3079474e62cb02">llvm::DbgVariableIntrinsic::getRawExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/corosubfninst/#ab1bf8e23e9fb08ebfcc7de672a334f11">llvm::CoroSubFnInst::getRawIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#a9dbdb0ca9332c447a3ec6f7b3bbb2fce">llvm::CoroIdInst::getRawInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelinst/#a37e5a810d1b08405046290f99050ddc3">llvm::DbgLabelInst::getRawLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#a753c375d2c90d5f7e04af2ea99648ac3">llvm::DbgVariableIntrinsic::getRawLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#ac1e5c61ab8cebb2b9a4c7b9e20d87783">llvm::DbgVariableIntrinsic::getRawVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroendinst/#af3e03cce0a4b7d43100526fffbdad151">llvm::AnyCoroEndInst::getResults</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#aeb9fbb3057734e2753c7cf8966bd0e84">llvm::CoroSuspendAsyncInst::getResumeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryopintrinsic/#a0583d2d049d59cf53ccfd2b6f4e53c87">llvm::BinaryOpIntrinsic::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpintrinsic/#a5b6283c0d91fe831e18f7b239eb5f0cb">llvm::CmpIntrinsic::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/minmaxintrinsic/#a82ded87f3e0e5e0a0827c7494b097d1d">llvm::MinMaxIntrinsic::getRHS</a>, <a href="/web-llvm/docs/api/classes/llvm/constrainedfpintrinsic/#a4fc25c0fccec261829e187a058a772a9">llvm::ConstrainedFPIntrinsic::getRoundingMode</a>, <a href="/web-llvm/docs/api/classes/llvm/coroallocaallocinst/#a60e1555c971882d5ac4b9fb75227e644">llvm::CoroAllocaAllocInst::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/vacopyinst/#a09d5aaa284591aa190d8e0da9ea45762">llvm::VACopyInst::getSrc</a>, <a href="/web-llvm/docs/api/classes/llvm/gcprojectioninst/#a6cffcfabac72ca61185ea24c1208b937">llvm::GCProjectionInst::getStatepoint</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofincrementinst/#afe7c16bf1ea59bb69a0e02f5d80aadda">llvm::InstrProfIncrementInst::getStep</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a2b5d30c7290790abe669d2c01faa9915">llvm::AnyCoroIdRetconInst::getStorage</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a3a0e2ffc025fe9de9569095d9ac140b8">llvm::AnyCoroIdRetconInst::getStorageAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidasyncinst/#a0ffbc186a4ed0d6f9889272500784445">llvm::CoroIdAsyncInst::getStorageAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidasyncinst/#ae025aa6bb0adb37f2b51714181627bc9">llvm::CoroIdAsyncInst::getStorageArgumentIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendasyncinst/#a8bab20d5bdb174a016c6f3658331a17e">llvm::CoroSuspendAsyncInst::getStorageArgumentIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroidretconinst/#a591b908fe4707059172b0ee3cd2ed4a2">llvm::AnyCoroIdRetconInst::getStorageSize</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidasyncinst/#a4aa55b08cc5603ffda9ca544e37a24eb">llvm::CoroIdAsyncInst::getStorageSize</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofvalueprofileinst/#a35174567917e9e78ea267bbebbc58cad">llvm::InstrProfValueProfileInst::getTargetValue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#ad9e8ff17d0545b9c796d2104b2e23a56">llvm::AArch64TTIImpl::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a8de5bf4f45a9fe750de151c5532d4fec">llvm::GCNTTIImpl::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcttiimpl/#a515494cf182cfa8aec53bd6fef47a11e">llvm::PPCTTIImpl::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#ae2b19bc21d3201e045841292463888ba">llvm::SITargetLowering::getTgtMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofvalueprofileinst/#ad7f36d7c63926c49a5a58780b84fa730">llvm::InstrProfValueProfileInst::getValueKind</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a5297bb63c49e91e5959ec20b638a8a45">llvm::VPIntrinsic::getVectorLengthParam</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsic/#a03fcea967fd9cd9d3f2f83ccccd8dfa3">llvm::MemIntrinsic::getVolatileCst</a>, <a href="/web-llvm/docs/api/classes/llvm/memsetpatternintrinsic/#adcd271333526da13d073f64263b3e45e">llvm::MemSetPatternIntrinsic::getVolatileCst</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a42f1b66a51c9c74a14385ead6991e370">llvm::RISCVTTIImpl::getVPLegalizationStrategy</a>, <a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst/#afd6b128b8f20ce45f7417590b5527b09">llvm::CoroAwaitSuspendInst::getWrapperFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8bb58bae0761c8591279171367a2b334">handleGuaranteedWellDefinedOps</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#a1217110bea3dc6c47ed8fab732d092b9">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::handleParallel51</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ab61a60817533b84f369d2623e0593ec7">handleSwitchExpect</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroendinst/#aafd1766cc8a87fcbc039347b8d8c082c">llvm::AnyCoroEndInst::hasResults</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#ab0859b33717bfc3149f2b4051949b5cb">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::initialize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a2e130f575ee6cbddeb0d62b295dee036">InsertStackProtectors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a9946a89352eee5ab78f0f3fc4fc18941">instCombineSVEPTest</a>, <a href="/web-llvm/docs/api/classes/llvm/corosuspendinst/#a7692f2161f769816538e6e99c6cc52f1">llvm::CoroSuspendInst::isFinal</a>, <a href="/web-llvm/docs/api/classes/llvm/coropromiseinst/#a849918e54a1807a933a648e04d34abbc">llvm::CoroPromiseInst::isFromPromise</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#acdf2ba7931aca786fe764e4361610d3e">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::isFusionProfitable</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a045a0a6379348da2235025355734b067">isKnownNonZeroFromOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a3f1861e30cebca3c33d71a2e73de0c5b">llvm::GCNTTIImpl::isReadRegisterSourceOfDivergence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a766df1ea3c4bf3cbc8586f310562034f">isReportingError</a>, <a href="/web-llvm/docs/api/classes/llvm/gcprojectioninst/#a9977194165b85f4c1271d6a077d59e6b">llvm::GCProjectionInst::isTiedToInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/anycoroendinst/#ad120b0fb98dfee5e50709ce853aa9327">llvm::AnyCoroEndInst::isUnwind</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4275af81cdeb1801deeae02ea2a0fb3b">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerBufferStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a237ac9d59f45a0b7c18296704e005a6c">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerColumnMajorLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a4c72146be47366faa66bbe3fa93abf2a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerColumnMajorStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ad2fd6546e0f1cc42311962f4ad4b29cd">lowerExpectIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-preiselintrinsiclowering-cpp-/preiselintrinsiclowering/#a333bc33c92a4288cf0b3e4514f4cb075">anonymous{PreISelIntrinsicLowering.cpp}::PreISelIntrinsicLowering::lowerIntrinsics</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7ae0da674977e2cd46d8df703e7dbab1">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMatrixMultiplyFused</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a6d7b7ecce18021429495c1db66a025ee">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerMultiply</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a30b2570b289c65776a16666bd087c988">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerRawBufferLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a4a42541fb66ae32c0c9f8deede2cc21e">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToBindAndAnnotateHandle</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a1e07c1aec365d4862fe2edef28aeec38">llvm::IntrinsicLowering::LowerToByteSwap</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a230768916fc2abaf5fb0f563654d2cc8">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerToCreateHandle</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aadb2a52a94fd7cf1e3f1643e0f5e2934">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerTranspose</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a70502c89919d53c74320c78b78d5c282">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerTypedBufferLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ab10e6ab2669a5c752426570de655e7ce">anonymous{DXILOpLowering.cpp}::OpLowerer::lowerUpdateCounter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanoaliascallsiteargument/#af60845674c792fb83289ea7695d3807e">anonymous{AttributorAttributes.cpp}::AANoAliasCallSiteArgument::mayAliasWithArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aa6cdda5199aa68a60388dd66800ec8fd">memChrToCharCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a5c59325f9c3c1526f4439392c892fd41">optimizeCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a996275d837998b396728990f8be0ef3a">OptimizeEmptyGlobalAtExitDtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#add5616535a62c9047ccfbf84bf778663">optimizeNaN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f16f94f0247434555c3aa4d379aa9e1">optimizeSymmetricCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a0a084f86091fd327d3113e8674c54192">anonymous{ThinLTOBitcodeWriter.cpp}::promoteTypeIds</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a6341f4b0dd74acf5c862050cb99221d3">ReplaceFPIntrinsicWithCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#ac54843966305eb21541468d352728681">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceFunctionWithOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#acd162cfe23d841a49056ce6436dd2075">replacePrepare</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ae17ac9c827f3c2d2ae6ec6da46566807">replaceUnaryCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#aa026b3b9ac87614295cbdcd804c5aff1">scalarizeMaskedGather</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#af5f0cd789df078f7bab4037b7d2c988d">scalarizeMaskedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a50bc726219ab43b02215f9236e621f76">scalarizeMaskedScatter</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a7e1f78e5d63e607ceba3b4f22ae02df8">scalarizeMaskedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a1f495e2156aca2b14d6a3574fdbeab9b">scalarizeMaskedVectorHistogram</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#aa3057ac8aef166e271195a0f465d97f2">llvm::CoroIdInst::setCoroutineSelf</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a430025e146710444567fa8bd1da2d3a9">setInfoSVEStN</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a020bb3b63fcf4ec2941fd868101f8914">anonymous{InlineCost.cpp}::CallAnalyzer::simplifyIntrinsicCallIsConstant</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#acb999adbc0664256b33b94d266a8b9da">anonymous{InlineCost.cpp}::CallAnalyzer::simplifyIntrinsicCallObjectSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/stripsymbols-cpp/#a216b0f52f244182222da5b7fcbc8ca01">stripDebugDeclareImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#afed5e8a79fa550920f638708cc257bdf">llvm::JumpThreadingPass::threadGuard</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#aab62d60a2e3448ed482c13292f79c57d">unwrapMAVOp</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaicvtrackerfunction/#a8e6bda36d87255e722de98932c92fb60">anonymous{OpenMPOpt.cpp}::AAICVTrackerFunction::updateImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a49a422e75fb519fc9419967ae2c3679b">upgradeAbs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a9d9ad1173db1cee0c288f1b773baaf65">upgradeAMDGCNIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad9d7a82ba140ac920458705124372cd6">upgradeAVX512MaskToSelect</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#adaf155c02ba4c5b8ec6d8d72b50e0f91">upgradeDbgIntrinsicToDbgRecord</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#acd3fbecf680813e839ac85bf3b3a81f2">upgradeMaskedCompare</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a56cb2dd18ee973c519f699213b466ade">upgradeMaskedMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a2bb059c3ec33f54ef3e4566ad1fde6c0">upgradeMaskToInt</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad37834e4f8e16e808997aef286954fd0">upgradeNVVMIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ae2068f406068749ea0cca3bacd6815a0">upgradePMULDQ</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#abbe50b1b6428dd6884355b64360f2f29">upgradeX86ConcatShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#ad582c34ed4be8ec80d79ba87edee1d76">upgradeX86MaskedShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a2e38c407c9078c144f8aa68eef3ac0ac">upgradeX86Rotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a252d7fc6161c61ec238f1ee24e8279b3">upgradeX86vpcom</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a02b56bd888812aead982e69819ce8452">upgradeX86VPERMT2Intrinsics</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyoptimizereturned-cpp-/optimizereturned/#ae81d17afe649660014f0e1ca569e8bf3">anonymous{WebAssemblyOptimizeReturned.cpp}::OptimizeReturned::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ac88e3e89148ab5849fc08d1eef269a84">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#ab0ad299c950e0e8ad155a9d78d4fa6e2">llvm::ObjectSizeOffsetEvaluator::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgomemopsizeopt-cpp-/memopsizeopt/#a818468a3517bf84dd05ea543b25fdac5">anonymous{PGOMemOPSizeOpt.cpp}::MemOPSizeOpt::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a8369ab820502d8565628a7691353538a">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicCompareExchange</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a88cd7ba4231567153875f30c8d90b7b0">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicExchange</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a7c97c0b1f7463c3f6d909f1e95263e58">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9b2c0b28c3d1ee4253d2aae4f9172d94">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLibAtomicLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ae56e07df4a48a26b74a418f5a4616971">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicStore</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#abe25be4a6081ab8cac7639e57970ec3c">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLibAtomicStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a960e756e8b2f056fbba7baa5bdcfb769">widenDestArray</a> and <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#aa2a5199bf39360e25f40b93cd5f9468a">workshareLoopTargetCallback</a>.</p>

</div>
</div>

### getArgOperandNo() {#ad2be14a6cee99d5f27223178c42366f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getArgOperandNo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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

<p>Given a use for a arg operand, get the arg operand number that corresponds to it.</p>

<p>Definition at line 1317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#aeac59c1598cb931a07550c901220bcf2">isArgOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a490938b206738261d5984fe958a872ad">adjustInliningThresholdUsingCallee</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ab7660504ac6ac15f209047da7f39755a">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::checkUse</a>, <a href="#a9b5a933ce70d8e5aeaa84005090a62a0">getArgOperandNo</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### getArgOperandNo() {#a9b5a933ce70d8e5aeaa84005090a62a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getArgOperandNo (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> UI)</td>
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

<p>Given a value use iterator, return the arg operand number corresponding to it.</p>


<p>Iterator must actually correspond to a data operand.</p>


<p>Definition at line 1324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#ad2be14a6cee99d5f27223178c42366f3">getArgOperandNo</a>.</p>

</div>
</div>

### getArgOperandUse() {#aa1c6e6fdb0e2812d7f3b97ae16caeb44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::CallBase::getArgOperandUse (unsigned i)</td>
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

<p>Wrappers for getting the <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a></span> of a call argument.</p>

<p>Definition at line 1297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a3f3b252f63d32a9a6e05208ce26562bf">llvm::User::getOperandUse</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/irposition/#a4c17a71e75898bbc42578a1c0b94c6b6">llvm::IRPosition::callsite_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#afd4a1cbb77ab22edcbb8ed8c9f4959b9">llvm::MemIntrinsicBase&lt; Derived &gt;::getLengthUse</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#ac873f56ddec5139e63e9b5d470c13516">llvm::MemIntrinsicBase&lt; Derived &gt;::getLengthUse</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a7d1b8fd1dae8330c9de11a6a4a27eee1">llvm::MemIntrinsicBase&lt; Derived &gt;::getRawDestUse</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a0a649be29743ac0cb7f0e5e616cabe13">llvm::MemIntrinsicBase&lt; Derived &gt;::getRawDestUse</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaisdeadcallsiteargument/#a5d6050f7be56f61036d2d194ac7f66f8">anonymous{AttributorAttributes.cpp}::AAIsDeadCallSiteArgument::manifest</a>.</p>

</div>
</div>

### getArgOperandUse() {#a2f7ef00950294f037ed4b63aa7ebfa0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use &amp; llvm::CallBase::getArgOperandUse (unsigned i)</td>
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



<p>Definition at line 1301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a3f3b252f63d32a9a6e05208ce26562bf">llvm::User::getOperandUse</a>.</p>

</div>
</div>

### getCalledFunction() {#a2b1ae7cf1bafdd43d1fee4c6ad0a2913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * llvm::CallBase::getCalledFunction ()</td>
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

<p>Returns the function called, or null if this is an indirect function invocation or the function signature does not match the call signature.</p>

<p>Definition at line 1341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a8d13199cbf4d080d3b5dcf330dad5d2c">getCalledOperand</a> and <a href="#ac3c35bd078a268a207f607d0f57dadba">getFunctionType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae54a643a9f9d83374bb4d7d22d4662d7">AddAlignmentAssumptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#ae52dc32e051ded6356e4065b75d19935">addIntrinsicToSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a6396da6d0b65cef8693b0aedd06f31e3">llvm::SystemZTTIImpl::adjustInliningThreshold</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a7e0dd0687cbb3cdc252710877b323c29">callInstIsMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite/#ad13669e41527f0cb36a0f5c93cff4a21">llvm::InstrProfCallsite::canInstrumentCallsite</a>, <a href="/web-llvm/docs/api/structs/anonymous-functionattrs-cpp-/argumentusestracker/#aa35ba8c73830d12eea5dda2a41aba718">anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::captured</a>, <a href="/web-llvm/docs/api/classes/llvm/coroawaitsuspendinst/#a636686efef82d935edef1e61de135f21">llvm::CoroAwaitSuspendInst::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a4f81b9940e1869e146636dc533455929">llvm::OpenMPIRBuilder::createParallel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a43988d720b2e37fb0abe3531980dbec8">doCallSiteSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/gcrootlowering-cpp/#a755b4fb8450994d9125dbcd317bc4fc0">DoLowering</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a219e9fac05a219d48a97e03304f84613">anonymous{SampleProfile.cpp}::SampleProfileLoader::findCalleeFunctionSamples</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8148654fcf3528ef06d7a0e28b57b952">llvm::findDevirtualizableCallsForTypeCheckedLoad</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#aa9137eda03e0c2cfd6eebaa55dfdd4cc">anonymous{SampleProfile.cpp}::SampleProfileLoader::findExternalInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#af70fa833673e4ac07c323a4a94e7ba93">llvm::InlineAdvisor::getAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#adb44b65867ce48eee9d2d49cbdc60333">llvm::MLInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a83088027da72950b627f9200965fb55b">llvm::ReplayInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a92ed436b80d7666f785e46f7e9aa3e82">llvm::objcarc::GetARCInstKind</a>, <a href="#ac7cae01462379060b2dae3f960054c6f">getArgOperandWithAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ab2a358830eca13fbd32b219f5318a7d8">llvm::GCNTTIImpl::getCallerAllocaCost</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a652b7ff39d88ac67e35d0955ac906292">anonymous{OpenMPOpt.cpp}::OpenMPOpt::getCallIfRegularCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a86c7b47618d45adedaeb1fb0f920c15c">anonymous{OpenMPOpt.cpp}::OpenMPOpt::getCallIfRegularCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#aaa89f605828072564b1ef10f730a67a3">getDefaultInlineAdvice</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inlineorder-cpp-/#abe75a2a872550eb0c6cc23a2b98fa8a4">anonymous{InlineOrder.cpp}::getInlineCostWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db7e1f11fa5a274a0cffb6fc5e524be">llvm::getIntrinsicForCallSite</a>, <a href="#ac62778065b99372cc62cf994b967e7e8">getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst/#a7ff64b3625b6f9020556ed05a5f72af4">llvm::IntrinsicInst::getIntrinsicID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a130c04c64f1ad6c7bea33c1aff8160be">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a2610d24c389789284bb8c8b616ab5e43">llvm::InlineAdvisor::getMandatoryKind</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7f27e470647cae7ae9225bae804bf006">llvm::MDNode::getMergedProfMetadata</a>, <a href="#a1951bdad78f9a0cb364948f121d6fba4">getParamByRefType</a>, <a href="#a88cc5fa65ff17e62b49dc5fb4401f813">getParamByValType</a>, <a href="#a2b576de254a0b0c5f278538862840e76">getParamInAllocaType</a>, <a href="#a01640692cf7fbf4574227f7899af2e71">getParamNoFPClass</a>, <a href="#a1e664c47c22c883baf848ad37261637c">getParamPreallocatedType</a>, <a href="#a287b116e4b7437fc6f4a0ca5f96add85">getParamStructRetType</a>, <a href="#a16d457bc91b566b5fdcb785dfc8862e7">getRetAlign</a>, <a href="#a06511680b1f7b6834735343e1d5c2e7f">getRetAttr</a>, <a href="#ab114d0e71d6a1db826bade5d22b0028c">getRetDereferenceableBytes</a>, <a href="#acf32f4feeff0b07e12c42c614a4791c1">getRetDereferenceableOrNullBytes</a>, <a href="#a08c455a4c7338c00f6d0bc9efecf9cb8">getRetNoFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#ad1f0755693a05c2b008e9a576c3b162b">llvm::LoopVectorizationCostModel::getVectorCallCost</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5abced3ab870d7abf57f2b35a02cd041">llvm::LoopVectorizationCostModel::getVectorIntrinsicCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#a6ac9067dc7c125cd83855df3e480e04c">handleBrSelExpect</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4ea5b2388bd9dc7e7fc902b5bd1e35e4">HandleCallsInBlockInlinedThroughInvoke</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#aea5dd05a61257355d99f96d8d6dc9f94">handlePhiDef</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ab61a60817533b84f369d2623e0593ec7">handleSwitchExpect</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05eaff7b97d11f44f547d03244617db4">llvm::hasAssumption</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9031658af970d96ad739450ec380d86a">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#abed91fefcc041268a8f52d7db0be4fce">InstrBreaksNoFree</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#ae64bb5b78cd6a7e4568e355e6422f6f4">InstrBreaksNonConvergent</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiccostattributes/#a6760a5137f8e0ec21dbd7b99e61b52ed">llvm::IntrinsicCostAttributes::IntrinsicCostAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a46f0bc39f45a99f997c4f124c505fb50">isFunctionMallocLike</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#a87548c69480b23599d643d518412895c">isIntrinsicOrLFToBeTailCalled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadargumentelimination-cpp-/#a13fbf5cf617b7f23022dbc57577d7d39">anonymous{DeadArgumentElimination.cpp}::isMustTailCalleeAnalyzable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a9ec948ba8709fe1041a2ec4a79cb6e4b">isReturnNonNull</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#accf402c1a02e48bf0826d239322b1f85">isSMEABIRoutineCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inlinecost-cpp-/#aaa4a24113a96ba45e9dc3e45a42a5b57">anonymous{InlineCost.cpp}::isSoleCallToLocalFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae641260d79a9242ccf378d9a7949fdc3">llvm::isTLIScalarize</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-sanitizerbinarymetadata-cpp-/#aa1c12445454ce9ee3832e5b4b993b966">anonymous{SanitizerBinaryMetadata.cpp}::isUARSafeCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#af5e459bc0b4c18c5b43a208cad131437">llvm::NVPTXTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/lowerexpectintrinsic-cpp/#ad2fd6546e0f1cc42311962f4ad4b29cd">lowerExpectIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aafoldruntimecallcallsitereturned/#af1bd9d5096d40a231c52e763ca91647f">anonymous{OpenMPOpt.cpp}::AAFoldRuntimeCallCallSiteReturned::manifest</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-objcarcapelim-cpp-/#a083ed14a6ddbd8d83b33f068cd2b4470">anonymous{ObjCARCAPElim.cpp}::MayAutorelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae63427c4d8f3c1ce48401b38ed9198f1">llvm::maybeMarkSanitizerLibraryCallNoBuiltin</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#a8a43e48d75ff4289fc2674097dab5d50">modifyIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fortifiedlibcallsimplifier/#ab5f693b48590402b0109cfdca55ec335">llvm::FortifiedLibCallSimplifier::optimizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/libcallsimplifier/#a73c4a774eb638f963533b77f7124293b">llvm::LibCallSimplifier::optimizeCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f0607e63d19dd3d4fb6edcef16bc26e">optimizeDoubleFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a7f16f94f0247434555c3aa4d379aa9e1">optimizeSymmetricCall</a>, <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpinstvisitor/#a1ba56140e5d65987c0cbc692b05a795f">llvm::SCCPInstVisitor::resolvedUndef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#aff18d7e34536cf38b7a43d7c42fa743c">restoreMutatedType</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/cgprofile-cpp/#a804d6eb117c9b69c6b52f2655438e787">runCGProfilePass</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ae0683ad49b9a0ccca8bd1c97987a8cf9">llvm::IRSimilarity::IRInstructionData::setCalleeName</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#a0e5ee7a451482722a4446bdf208df9fc">shouldBeDeferred</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a463056de56ab82cc6e2c50e5ccf17626">shouldCheckArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25e327ae759c3362067beb2aad1dbfdd">llvm::shouldInline</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a518b0cf18edfb9fb05aaa530550af870">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineCandidate</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#a902b6197889c703bbe3c087f8bcf0789">anonymous{SampleProfile.cpp}::SampleProfileLoader::shouldInlineColdCallee</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineorder-cpp-/sizepriority/#a535de0218025bdcc506fc863f9bf0ed5">anonymous{InlineOrder.cpp}::SizePriority::SizePriority</a>, <a href="/web-llvm/docs/api/classes/llvm/smeattrs/#aa5e262aac758714fcbe1b579d3d37920">llvm::SMEAttrs::SMEAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae71573dba191b26eda0d5ea27b81ef62">trackInlinedStores</a>, <a href="/web-llvm/docs/api/classes/anonymous-sampleprofile-cpp-/sampleprofileloader/#adb1dafd461988f3d8e687eabb99e108d">anonymous{SampleProfile.cpp}::SampleProfileLoader::tryInlineCandidate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#a1f7cd4c14e02c076508142fbb2c1aa79">llvm::SCCPSolver::tryToReplaceWithConstant</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ab013e5e37e15eee5725a24b6a6df2416">llvm::AMDGPULibCalls::useNative</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a4abe522bf135a7628b059cf5fc0be127">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::VisitCallInst</a>, <a href="/web-llvm/docs/api/structs/anonymous-spirvregularizer-cpp-/spirvregularizer/#a3126f03fedf2204dffcef1c05dee06c2">anonymous{SPIRVRegularizer.cpp}::SPIRVRegularizer::visitCallInst</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/instructionclassification/#a6d402b84cf5af9fc205b7e554449cf93">llvm::IRSimilarity::IRInstructionMapper::InstructionClassification::visitCallInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#aee075a4b7e853e004ad694f7ef959f28">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractValueInst</a> and <a href="/web-llvm/docs/api/structs/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/exprlinearizer/#a4cf50167dfbcc11002f483718ac75556">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::ExprLinearizer::writeFnName</a>.</p>

</div>
</div>

### getCalledOperand() {#a8d13199cbf4d080d3b5dcf330dad5d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::CallBase::getCalledOperand ()</td>
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



<p>Definition at line 1334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a7ba763fe17be006dc5cb7408dd332432">canParameterizeCallOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a130fa46387c197f8e770059b89d2a4b4">llvm::Attributor::checkForAllCallees</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ab7660504ac6ac15f209047da7f39755a">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::checkUse</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a259334992127b809a034f025fc2bd13f">llvm::diagnoseDontCall</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a4b23196df4c243ce29f29f54a26cae7e">llvm::ARMTargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a687e754bf03f8d135bc899b49db74472">llvm::X86TargetLowering::ExpandInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineasmlowering-cpp-/extraflags/#a265ccdc955df6841403de15996982e3e">anonymous{InlineAsmLowering.cpp}::ExtraFlags::ExtraFlags</a>, <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f8e808593fe987a587d9259865f136">llvm::getMaybeBitcastedCallee</a>, <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8bb58bae0761c8591279171367a2b334">handleGuaranteedWellDefinedOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/functioninstrumenter/#ad8a93caaba7e38b078b14a134f5f46f8">anonymous{PGOInstrumentation.cpp}::FunctionInstrumenter::instrument</a>, <a href="#a574efc7d85ff014d5f15e077f3c82e6b">isIndirectCall</a>, <a href="#a018f0394a375233d538109968b76a05a">isInlineAsm</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac9742261cd7ee88cb99ec122fc61f5e8">llvm::SelectionDAGBuilder::LowerCallSiteWithPtrAuthBundle</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcisellowering-cpp/#aefc8b558bcaf81b735d0f6e634279aef">prepareDescriptorIndirectCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9f3928b341e4412b8b66b794896014f0">simplifySuspendPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a975eb04de3ce355131f2bdc9328def27">llvm::Attributor::translateArgumentToCallSiteContent</a>, <a href="/web-llvm/docs/api/structs/llvm/pgoindirectcallvisitor/#aba025734aa83b5cacf35c35bd572ee0e">llvm::PGOIndirectCallVisitor::tryGetVTableInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a554ade21fa5bda8daa3af645c00364b1">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanonconvergentfunction/#a7e5c9d15b3fcbb936077ce73cfb12692">anonymous{AttributorAttributes.cpp}::AANonConvergentFunction::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaundefinedbehaviorimpl/#ae455d1ecbeb7d95762d758c9aae70512">anonymous{AttributorAttributes.cpp}::AAUndefinedBehaviorImpl::updateImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84163d559062da6b736ab943644e0a16">llvm::versionCallSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a27c9f05f074b1acd44859e85c1212bc1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAsmInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getCalledOperandUse() {#a8efa5432c5bf5ac4050ab6d3b27594c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Use &amp; llvm::CallBase::getCalledOperandUse ()</td>
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



<p>Definition at line 1336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="#a89338ed7a9ad9bc5cb9d771d79ebd5ba">isCallee</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ad9f376137b3a3160390ab81821f205f6">isCalleeOperand</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#a554ade21fa5bda8daa3af645c00364b1">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::updateImpl</a>.</p>

</div>
</div>

### getCalledOperandUse() {#a56ba724ca88adebc9d7f9d0062e5f0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use &amp; llvm::CallBase::getCalledOperandUse ()</td>
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



<p>Definition at line 1337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### getCaller() {#afac5b39bcbb90d660f83d9b4bd8c6d95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * CallBase::getCaller ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper to get the caller (the parent function).</p>

<p>Declaration at line 1360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 327 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a739b30c811f1eece61b05320ddf44e5b">llvm::GlobalValue::getParent</a> and <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-parent-access/#a7e19e7508415378ad9523e0339b23e22">llvm::ilist_detail::node_parent_access&lt; ilist_node_impl&lt; ilist_detail::compute_node_options&lt; Instruction, Options... &gt;::type &gt;, ilist_detail::compute_node_options&lt; Instruction, Options... &gt;::type::parent_ty &gt;::getParent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#ae54a643a9f9d83374bb4d7d22d4662d7">AddAlignmentAssumptions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aebd8fb1e50c14f4988226de940a067ed">annotateNonNullNoUndefBasedOnAccess</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/llvm/ctxprofanalysis/#a4dd66bb1f3a24ebaf94d2f204a700e4a">llvm::CtxProfAnalysis::collectIndirectCallPromotionList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#af70fa833673e4ac07c323a4a94e7ba93">llvm::InlineAdvisor::getAdvice</a>, <a href="/web-llvm/docs/api/classes/llvm/mlinlineadvisor/#adb44b65867ce48eee9d2d49cbdc60333">llvm::MLInlineAdvisor::getAdviceImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/replayinlineadvisor/#a83088027da72950b627f9200965fb55b">llvm::ReplayInlineAdvisor::getAdviceImpl</a>, <a href="#af4f7541a49e43b7bed69b5f590ed966f">getCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineadvisor/#a14528ae0117f755bc5a74a7683c0722d">llvm::InlineAdvisor::getCallerORE</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineadvisor-cpp/#aaa89f605828072564b1ef10f730a67a3">getDefaultInlineAdvice</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-inlineorder-cpp-/#abe75a2a872550eb0c6cc23a2b98fa8a4">anonymous{InlineOrder.cpp}::getInlineCostWrapper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9031658af970d96ad739450ec380d86a">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a652ede21e988a4de569cdbc7863ea234">isColdCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/profilesummaryinfo/#aa873cdb66e593236e466fd0d452a0a82">llvm::ProfileSummaryInfo::isColdCallSite</a>, <a href="#aab40deb840751b104926b1052d91e7fc">isReturnNonNull</a>, <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/moduleinlinerpass/#ab7155781c9a6aafef322de28d9bc4c86">llvm::ModuleInlinerPass::run</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a25e327ae759c3362067beb2aad1dbfdd">llvm::shouldInline</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3219f7b717320ae52f53ccb09ad5a84">llvm::tryPromoteCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaprivatizableptrargument/#a5714820dd8c18b0cf570124cd752b8f7">anonymous{AttributorAttributes.cpp}::AAPrivatizablePtrArgument::updateImpl</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfocallsite/#aa952da5010350f12b8d601516719d22b">anonymous{OpenMPOpt.cpp}::AAKernelInfoCallSite::updateImpl</a>.</p>

</div>
</div>

### getCaller() {#af4f7541a49e43b7bed69b5f590ed966f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Function * llvm::CallBase::getCaller ()</td>
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



<p>Definition at line 1361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a> and <a href="#afac5b39bcbb90d660f83d9b4bd8c6d95">getCaller</a>.</p>

</div>
</div>

### getCallingConv() {#a3ff92cec76009e859cb0c419d6e8ba5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID llvm::CallBase::getCallingConv ()</td>
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



<p>Definition at line 1399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/instruction/#a041694a1ea45996587ef9712d9a2bb1f">llvm::Instruction::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgputargettransforminfo-cpp/#a490938b206738261d5984fe958a872ad">adjustInliningThresholdUsingCallee</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8126d22f7eb9fade7b5f423c75342d38">llvm::AMDGPU::isArgPassedInSGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a6fe2425902ca5775f3b350cfbe49cc8f">llvm::TargetLibraryInfoImpl::isCallingConvCCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a429785d5b6015aff39a7a998d9e70fa3">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a263f69437421410a39c26e0be576f028">llvm::PPCTargetLowering::supportsTailCallFor</a> and <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/instructionclassification/#a6d402b84cf5af9fc205b7e554449cf93">llvm::IRSimilarity::IRInstructionMapper::InstructionClassification::visitCallInst</a>.</p>

</div>
</div>

### getConvergenceControlToken() {#ad6139303612b013feb3df0e6c5e1ad26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::CallBase::getConvergenceControlToken ()</td>
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

<p>Return the convergence control token for this call, if it exists.</p>

<p>Definition at line 1183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a23ab5f34fb7b9476d45da0102ecbfae6">getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cacdf8ff962c6163eb5fae1f9b2fb5142a">llvm::LLVMContext::OB_convergencectrl</a>.</p>

</div>
</div>

### getDataOperandNo() {#a3ec61b88c722cd0e736fa93b4b599a19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getDataOperandNo (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> UI)</td>
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

<p>Given a value use iterator, return the data operand corresponding to it.</p>


<p>Iterator must actually correspond to a data operand.</p>


<p>Definition at line 1249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a3ec61b88c722cd0e736fa93b4b599a19">getDataOperandNo</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-functionattrs-cpp-/argumentusestracker/#aa35ba8c73830d12eea5dda2a41aba718">anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::captured</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a> and <a href="#a3ec61b88c722cd0e736fa93b4b599a19">getDataOperandNo</a>.</p>

</div>
</div>

### getDataOperandNo() {#a219b662245bf37ec1b2af068525c500b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getDataOperandNo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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

<p>Given a use for a data operand, get the data operand number that corresponds to it.</p>

<p>Definition at line 1255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a> and <a href="#aebb1d2333537383d23ad22081752930f">isDataOperand</a>.</p>

</div>
</div>

### getFunctionType() {#ac3c35bd078a268a207f607d0f57dadba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * llvm::CallBase::getFunctionType ()</td>
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



<p>Definition at line 1199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#aacb21b50e69e3d808db0120e9a0a7b9d">FTy</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#aaf2fe2b910650ab4ea0eeaca5922dce8">addVariantDeclaration</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8a8b818a539c2cbbe1a954a875c5fcec">getVectorCallCosts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aefba9af2f61452f20f4c947b4c2e5f4e">llvm::objcarc::hasAttachedCallOpBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a6fe2425902ca5775f3b350cfbe49cc8f">llvm::TargetLibraryInfoImpl::isCallingConvCCompatible</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a429785d5b6015aff39a7a998d9e70fa3">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#a03acc2b3a98139a84dbbc1b425e220d1">shouldConvertToIndirectCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a020bb3b63fcf4ec2941fd868101f8914">anonymous{InlineCost.cpp}::CallAnalyzer::simplifyIntrinsicCallIsConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargaarch64helper/#a41ca0d5d12f5940de41f29cf08066e00">anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#acc81d19554e4eb245d659a89a2fd6f37">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararggenerichelper/#ab229cd82fd788028a0ff3a1f1957e7f9">anonymous{MemorySanitizer.cpp}::VarArgGenericHelper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a372b313738e7d6b96b0ef622ce60890c">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper/#af0bc023f29f779469e5e8e3f92b9db0f">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::visitCallBase</a>.</p>

</div>
</div>

### getIntrinsicID() {#ac62778065b99372cc62cf994b967e7e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID CallBase::getIntrinsicID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the intrinsic <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the intrinsic called or <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">Intrinsic::not_intrinsic</a> if the called function is not an intrinsic, or if this is an indirect call.</p>

<p>Declaration at line 1375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a35fedf4db6d756bd82501607f93c1e79aab5fb650050f184fa7c19c26abde5226">llvm::Intrinsic::not_intrinsic</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs/#ad32a933965ba0059ff2a3a322cc8b40b">llvm::objcarc::BundledRetainClaimRVs::eraseInst</a>, <a href="#ad4139298dd770711bf92cf3b95ba200a">hasClobberingOperandBundles</a>, <a href="#ada195b22ad562f2d06824c595765dd30">hasReadingOperandBundles</a>, <a href="/web-llvm/docs/api/structs/llvm/aanosync/#a79dea56e8e62d80d48cddd4319a55380">llvm::AANoSync::isAlignedBarrier</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#a035312f0450b07253231a7a9a7153b74">isKnownIntegral</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ae47d97e1c5c07ee94c968058e19acb98">llvm::CallInst::isNonContinuableTrap</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroearly-cpp-/lowerer/#ad856ac9052abe36a0ca7e8909fd18f1b">anonymous{CoroEarly.cpp}::Lowerer::lowerEarlyIntrinsics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0947c6f5b0bdcd54aa4a8447602f8283">llvm::lowerUnaryVectorIntrinsicAsLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a98e8d1806c78a1e84fa32e50a41a8a62">llvm::InstCombinerImpl::SimplifyDemandedUseFPClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#a90bcc9afc1cc990c8790a5424a93c926">upgradeARMIntrinsicCall</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### hasArgument() {#a1ce0dcf6d29175cc7d7738ef77d1dd81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Returns true if this CallSite passes the given Value* as an argument to the called function.</p>

<p>Definition at line 1330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#ad027ea8803d83ee19b9a2e13aec6d655">args</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>

</div>
</div>

### isArgOperand() {#aeac59c1598cb931a07550c901220bcf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isArgOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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



<p>Definition at line 1306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a4fb513d744ca72275932b2c7003f16f6">arg_begin</a>, <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ab7660504ac6ac15f209047da7f39755a">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::checkUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="#ad2be14a6cee99d5f27223178c42366f3">getArgOperandNo</a> and <a href="#a8fe3eec799f786c28b6bc7b1d6e21813">isArgOperand</a>.</p>

</div>
</div>

### isArgOperand() {#a8fe3eec799f786c28b6bc7b1d6e21813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isArgOperand (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> UI)</td>
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



<p>Definition at line 1311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#aeac59c1598cb931a07550c901220bcf2">isArgOperand</a>.</p>

</div>
</div>

### isCallee() {#a754b47054852401f87e52805d15bdf05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isCallee (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> UI)</td>
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

<p>Determine whether the passed iterator points to the callee operand's <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>.</p>

<p>Definition at line 1352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a754b47054852401f87e52805d15bdf05">isCallee</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#ad449dfa0d6d2308ee93fa07b5a1e1e0a">addNoRecurseAttrsTopDown</a>, <a href="/web-llvm/docs/api/structs/anonymous-functionattrs-cpp-/argumentusestracker/#aa35ba8c73830d12eea5dda2a41aba718">anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::captured</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaglobalvalueinfofloating/#ab7660504ac6ac15f209047da7f39755a">anonymous{AttributorAttributes.cpp}::AAGlobalValueInfoFloating::checkUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a652b7ff39d88ac67e35d0955ac906292">anonymous{OpenMPOpt.cpp}::OpenMPOpt::getCallIfRegularCall</a>, <a href="#a754b47054852401f87e52805d15bdf05">isCallee</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>.</p>

</div>
</div>

### isCallee() {#a89338ed7a9ad9bc5cb9d771d79ebd5ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isCallee (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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

<p>Determine whether this <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> is the callee operand's <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>.</p>

<p>Definition at line 1357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a8efa5432c5bf5ac4050ab6d3b27594c4">getCalledOperandUse</a>.</p>

</div>
</div>

### isDataOperand() {#aebb1d2333537383d23ad22081752930f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isDataOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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



<p>Definition at line 1238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a3085b56a4d6537a84c58e62e535adb71">data_operands_begin</a> and <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a>.</p>


<p>Referenced by <a href="#a219b662245bf37ec1b2af068525c500b">getDataOperandNo</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslicerewriter/#a73e5f32465500cf4cbd002f5c1c9a025">anonymous{SROA.cpp}::AllocaSliceRewriter::InstVisitor&lt; AllocaSliceRewriter, bool &gt;</a>, <a href="#a560101563557d89f119dd261d2eb9940">isDataOperand</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>.</p>

</div>
</div>

### isDataOperand() {#a560101563557d89f119dd261d2eb9940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isDataOperand (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> UI)</td>
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



<p>Definition at line 1243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#aebb1d2333537383d23ad22081752930f">isDataOperand</a>.</p>

</div>
</div>

### isIndirectCall() {#a574efc7d85ff014d5f15e077f3c82e6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::isIndirectCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the callsite is an indirect call.</p>

<p>Declaration at line 1349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8d13199cbf4d080d3b5dcf330dad5d2c">getCalledOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="#a018f0394a375233d538109968b76a05a">isInlineAsm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite/#ad13669e41527f0cb36a0f5c93cff4a21">llvm::InstrProfCallsite::canInstrumentCallsite</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8bb58bae0761c8591279171367a2b334">handleGuaranteedWellDefinedOps</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9469fd548994812c12e4c10d42ec82a3">llvm::promoteCallWithIfThenElse</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a370b5637d8494d95fb8867b813fa71d8">anonymous{OpenMPOpt.cpp}::OpenMPOpt::registerAAsForFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#aff18d7e34536cf38b7a43d7c42fa743c">restoreMutatedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/cgprofile-cpp/#a804d6eb117c9b69c6b52f2655438e787">runCGProfilePass</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ae0683ad49b9a0ccca8bd1c97987a8cf9">llvm::IRSimilarity::IRInstructionData::setCalleeName</a>, <a href="/web-llvm/docs/api/structs/llvm/pgoindirectcallvisitor/#aba025734aa83b5cacf35c35bd572ee0e">llvm::PGOIndirectCallVisitor::tryGetVTableInstruction</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalledgescallsite/#a827970be0131200af76c14c9e1a24b15">anonymous{AttributorAttributes.cpp}::AACallEdgesCallSite::updateImpl</a> and <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructionmapper/instructionclassification/#a6d402b84cf5af9fc205b7e554449cf93">llvm::IRSimilarity::IRInstructionMapper::InstructionClassification::visitCallInst</a>.</p>

</div>
</div>

### isInlineAsm() {#a018f0394a375233d538109968b76a05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isInlineAsm ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this call is an inline asm statement.</p>

<p>Definition at line 1408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a8d13199cbf4d080d3b5dcf330dad5d2c">getCalledOperand</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite/#ad13669e41527f0cb36a0f5c93cff4a21">llvm::InstrProfCallsite::canInstrumentCallsite</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a7ba763fe17be006dc5cb7408dd332432">canParameterizeCallOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a11fb81052cf8abb712c95daa2f0344d6">llvm::GCNTTIImpl::isAlwaysUniform</a>, <a href="#a574efc7d85ff014d5f15e077f3c82e6b">isIndirectCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#aff18d7e34536cf38b7a43d7c42fa743c">restoreMutatedType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#aff43b1c529b1af47195587ca0090f7ec">shouldConvertUse</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>.</p>

</div>
</div>

### isMustTailCall() {#a50426b12f4acb3d9f74d0778948e9597}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::isMustTailCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tests if this call site must be tail call optimized.</p>


<p>Only a <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> can be tail call optimized.</p>


<p>Declaration at line 1367 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 343 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a43988d720b2e37fb0abe3531980dbec8">doCallSiteSplitting</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a7e0090207d4b1da753ad2d3bbb51fc4d">hasMustTailCallers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-deadargumentelimination-cpp-/#a13fbf5cf617b7f23022dbc57577d7d39">anonymous{DeadArgumentElimination.cpp}::isMustTailCalleeAnalyzable</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a273e9b97fc0dfec8df7cf4294d9b87fe">llvm::Attributor::isValidFunctionSignatureRewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#a45d8aec8b73256f724d9c7517306f030">llvm::LoongArchTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#af635bdefb1b223548ffe30e04acd5487">llvm::RISCVTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a19163d10ff2d0dcede586ea892c7c920">llvm::SITargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac9742261cd7ee88cb99ec122fc61f5e8">llvm::SelectionDAGBuilder::LowerCallSiteWithPtrAuthBundle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#afad0de1026bed50eff308033f7cd132b">splitCallSite</a>, <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#a1f7cd4c14e02c076508142fbb2c1aa79">llvm::SCCPSolver::tryToReplaceWithConstant</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/callpromotionutils-cpp/#aaabc735841282ccafdf43b7c165b030e">versionCallSiteWithCond</a>.</p>

</div>
</div>

### isTailCall() {#af2c6594a90c163f7347396d39e094abe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::isTailCall ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tests if this call site is marked as a tail call.</p>

<p>Declaration at line 1370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac9742261cd7ee88cb99ec122fc61f5e8">llvm::SelectionDAGBuilder::LowerCallSiteWithPtrAuthBundle</a>.</p>

</div>
</div>

### mutateFunctionType() {#aba272b7337f4e135f28eeb0bcc69adbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::mutateFunctionType (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy)</td>
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



<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aacb21b50e69e3d808db0120e9a0a7b9d">FTy</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ac0f09c2c9951158f9eecfaf7068d7b20">llvm::Value::mutateType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>.</p>

</div>
</div>

### setArgOperand() {#abc10b887caad109288ffceb230493a85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setArgOperand (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * v)</td>
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



<p>Definition at line 1291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a5fa9b8e1842b354f64c1ba6be0a4a17f">llvm::User::setOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#ab330f042033636da90859626bc4dc542">llvm::CoroIdInst::clearPromise</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroutines-cpp/#ad623ba85ece2827b2a9c853e95ee24fc">createCoroSave</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp/#adfad68845808cb6acd116e50b15bc281">despeculateCountZeros</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a0a084f86091fd327d3113e8674c54192">anonymous{ThinLTOBitcodeWriter.cpp}::promoteTypeIds</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#ae723478bb89b56b7c11d9184e627c9c5">llvm::DbgVariableIntrinsic::setArgOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcallsite/#a061fc2b03bdd87e122bc8889adee8c09">llvm::InstrProfCallsite::setCallee</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a8e6d3da10023ff90b874399d8a1d7880">setConstantInArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#aa3057ac8aef166e271195a0f465d97f2">llvm::CoroIdInst::setCoroutineSelf</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a64ab14972c2bd5c0a01eaf7242dee624">llvm::MemIntrinsicBase&lt; Derived &gt;::setDest</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicmemintrinsic/#a91ecdf20aedd95b2052709963e7c9c7b">llvm::AtomicMemIntrinsic::setElementSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcntrinstbase/#ac98dfc76a69863c13ae587fa9521c808">llvm::InstrProfCntrInstBase::setIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#a11b71b3b2f2b4d214a7eac47e628b3d2">llvm::CoroIdInst::setInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dbglabelinst/#a91ea3c7496ba4e21be7e4d1ed54b03c6">llvm::DbgLabelInst::setLabel</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a3e472e6fd83abb77745a59bccd367688">llvm::MemIntrinsicBase&lt; Derived &gt;::setLength</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a36ec592acc6de041c35f8f192d5d572d">llvm::VPIntrinsic::setMaskParam</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofinstbase/#ab097a46b048989cd238f46c7d761f44e">llvm::InstrProfInstBase::setNameValue</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#a7d6e3b2cad50a3bd88b4d298a17cef24">llvm::VPIntrinsic::setVectorLengthParam</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsic/#a5bcdeddd3338802df4c911055eefb283">llvm::MemIntrinsic::setVolatile</a>, <a href="/web-llvm/docs/api/classes/llvm/memsetpatternintrinsic/#a765a77ff3dda0862e314c67a0988dff3">llvm::MemSetPatternIntrinsic::setVolatile</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/simpleloopunswitch-cpp/#af3ac46dde637293a34d0ff7b619a656b">turnGuardIntoBranch</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a7c97c0b1f7463c3f6d909f1e95263e58">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9b2c0b28c3d1ee4253d2aae4f9172d94">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLibAtomicLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ae56e07df4a48a26b74a418f5a4616971">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLibAtomicStore</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#abe25be4a6081ab8cac7639e57970ec3c">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitLibAtomicStore</a>.</p>

</div>
</div>

### setCalledFunction() {#aee56a5257c4899bf97c5957d87a732e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setCalledFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * Fn)</td>
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

<p>Sets the function called, including updating the function type.</p>

<p>Definition at line 1380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a> and <a href="#aee56a5257c4899bf97c5957d87a732e3">setCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#a0f104a4f4a7edce928ac0aea2a3509b8">lowerFunnelShifts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="#aee56a5257c4899bf97c5957d87a732e3">setCalledFunction</a>, <a href="#a8ea8b7cad8cee4202b900bd648a98bdf">setCalledFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ab013e5e37e15eee5725a24b6a6df2416">llvm::AMDGPULibCalls::useNative</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### setCalledFunction() {#a8ea8b7cad8cee4202b900bd648a98bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setCalledFunction (<a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> Fn)</td>
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

<p>Sets the function called, including updating the function type.</p>

<p>Definition at line 1385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#ac5d8da677233fa2e1e7039508ed56e0e">llvm::FunctionCallee::getCallee</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncallee/#a6272287f036b912f12c0270607cec675">llvm::FunctionCallee::getFunctionType</a> and <a href="#aee56a5257c4899bf97c5957d87a732e3">setCalledFunction</a>.</p>

</div>
</div>

### setCalledFunction() {#a0107453b6a36d93e5a10d48cdac4d06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setCalledFunction (<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Fn)</td>
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

<p>Sets the function called, including updating to the specified function type.</p>

<p>Definition at line 1391 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aacb21b50e69e3d808db0120e9a0a7b9d">FTy</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="#ad70fe60b7ed052c6a74863944b518251">setCalledOperand</a>.</p>

</div>
</div>

### setCalledOperand() {#ad70fe60b7ed052c6a74863944b518251}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setCalledOperand (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aef572ae661cf9f5b14651ef952629c10">OptimizeAwayTrappingUsesOfValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="#a0107453b6a36d93e5a10d48cdac4d06c">setCalledFunction</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### setCallingConv() {#a0851b4de29686e9c3918449b054cfada}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setCallingConv (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC)</td>
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



<p>Definition at line 1403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#afbb5877d4ac72148b232c8fedb08bba5">llvm::Instruction::setSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7990af2ca325a18286d49b694c835c98">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildGuestExitThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a3f27dda1e68a24fab4b3ed4a9cfc0e7c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildPatchableThunk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a792b08a6322bb539ee5ce2f754588c8c">llvm::IRBuilderBase::CreateMalloc</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/structs/anonymous-partialinlining-cpp-/partialinlinerimpl/functioncloner/#a61f3d93434dc9f576826799df553ed1b">anonymous{PartialInlining.cpp}::PartialInlinerImpl::FunctionCloner::doMultiRegionFunctionOutlining</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#aa71b78b68e5077a0c0201ceb8b5cbe85">emitBinaryFloatFnCallHelper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8dbd4c4f3aebf9f810f0590d49ba1003">llvm::emitCalloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8a6b92032e49dc6da4a5c4a05771878f">llvm::emitFPutC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a689dd439a7989cc49b73cd6eb52d90dc">llvm::emitFPutS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a2a45b5fd2f1698d6fd10a06a0a38f2">llvm::emitFWrite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad8bec6d053e2c93fee21eebfffae31d0">llvm::emitHotColdNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acb10d4f78442972e711932060882cd79">llvm::emitHotColdNewAligned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1ee7adc14967589134b654d321b3561d">llvm::emitHotColdNewAlignedNoThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac6cfbf3bb83193d8447d8f7c392915cb">llvm::emitHotColdNewNoThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad721b230836c9430afd9a392db0c7c5a">llvm::emitHotColdSizeReturningNew</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf8c11d60a5385f70c3a140c03f136e4">llvm::emitHotColdSizeReturningNewAligned</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a62d6c0a5c9dd42949245eb28ab9c37c8">emitLibCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac76c99e44c5f3570a3666c9234caf222">llvm::emitMalloc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1484bdcb6b4c84ceb447270f8acca352">llvm::emitMemCpyChk</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11b84a626ef34d3ced2e131937e58ddd">llvm::emitPutChar</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8cc4358373eeb5363cd620bbdaeab">llvm::emitPutS</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a560b77762851df60ac51ca48db42058b">emitUnaryFloatFnCallHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/ompinformationcache/#a4085e5e5acca78ad7d76140bbe0f36f9">anonymous{OpenMPOpt.cpp}::OMPInformationCache::setCallingConvention</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getNumSubclassExtraOperands() {#a4a3758e792ce9aeb9dea98f70b3d4715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getNumSubclassExtraOperands ()</td>
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



<p>Definition at line 1137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a41fc1cf527faa2225d1c8589b08314d3">getNumSubclassExtraOperandsDynamic</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a8448c3e780b73347f00055dbbbc98a47">data_operands_end</a>.</p>

</div>
</div>

### getNumSubclassExtraOperandsDynamic() {#a41fc1cf527faa2225d1c8589b08314d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned CallBase::getNumSubclassExtraOperandsDynamic ()</td>
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

<p>Get the number of extra operands for instructions that don't have a fixed number of extra operands.</p>

<p>Declaration at line 1151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a>.</p>


<p>Referenced by <a href="#a4a3758e792ce9aeb9dea98f70b3d4715">getNumSubclassExtraOperands</a>.</p>

</div>
</div>

### hasDescriptor() {#a042568b06f355d5c5fcd78dcfb381676}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasDescriptor ()</td>
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



<p>Definition at line 1135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/value/#ae534948f447c9e41a6890b01a8c13f0a">llvm::Value::HasDescriptor</a>.</p>


<p>Referenced by <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a> and <a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a>.</p>

</div>
</div>

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
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a> and <a href="#a55f751706099c68d86b273f33971bc76">classof</a>.</p>

</div>
</div>

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



<p>Declaration at line 1133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getFnAttrOnCalledFunction() {#a930cd28d366d4597913b7108fdb94868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AK&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template Attribute CallBase::getFnAttrOnCalledFunction (AK Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### getParamAttrOnCalledFunction() {#a9cc421e50b26e4986a97db788c8db7dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AK&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">template Attribute CallBase::getParamAttrOnCalledFunction (unsigned ArgNo, AK Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### hasFnAttrImpl() {#adb7a292e6d06890882b156168d82b85c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AttrKind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasFnAttrImpl (AttrKind Kind)</td>
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



<p>Definition at line 2296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### hasFnAttrOnCalledFunction() {#a9a75d6fe5ffe0df5c42c2eed243726d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::hasFnAttrOnCalledFunction (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 435 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### hasFnAttrOnCalledFunction() {#a201344cbb7c2893ea88f8f1e4fa75572}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::hasFnAttrOnCalledFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>

</div>
</div>

### hasRetAttrImpl() {#a3290146bc52003c0772c6f1ca7df2636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename AttrKind&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasRetAttrImpl (AttrKind Kind)</td>
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

<p>Determine whether the return value has the given attribute.</p>


<p>Supports <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> as <span class="doxyComputerOutput">AttrKind</span> types.</p>


<p>Definition at line 2308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Attrs {#a97849e9f49e6326c0e055bc8f1ea4eec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::CallBase::Attrs</td>
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

<p>parameter attributes for callable</p>

<p>Definition at line 1126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="#a2060ab64acfc67af974e20cbc79ca273">addAttributeAtIndex</a>, <a href="#a9ec1fe122d152d6c6cefbdab43a43cdc">addAttributeAtIndex</a>, <a href="#adf1a2105045f7e33738b34f49b0f9f08">addDereferenceableParamAttr</a>, <a href="#a9add940717795f05bb69603216f17254">addDereferenceableRetAttr</a>, <a href="#a031e44afee1f29cd934862cebf714a88">addFnAttr</a>, <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>, <a href="#a433ec4bd285111f13acdc8a78be16a72">addParamAttr</a>, <a href="#ae5d05ec2b9a60806746addff3f2a71a9">addParamAttr</a>, <a href="#a0e7b74d310c94c459b8985806192cc99">addRangeRetAttr</a>, <a href="#ae30660fb489f8cbe69bf8650daadcdb1">addRetAttr</a>, <a href="#aa94f59b6921a7cd3567439b3302a5357">addRetAttr</a>, <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="#ac7cae01462379060b2dae3f960054c6f">getArgOperandWithAttribute</a>, <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a>, <a href="#a7713a45c8983df00c3975444b94e69ae">getParamAlign</a>, <a href="#a1951bdad78f9a0cb364948f121d6fba4">getParamByRefType</a>, <a href="#a88cc5fa65ff17e62b49dc5fb4401f813">getParamByValType</a>, <a href="#a37269632d3b68130c5b7019cd795be44">getParamDereferenceableBytes</a>, <a href="#abaf8a257af9e537d7cd8b05299e5090c">getParamDereferenceableOrNullBytes</a>, <a href="#aa9d39950dcbd9e1e6dac2b66db4324d4">getParamElementType</a>, <a href="#a2b576de254a0b0c5f278538862840e76">getParamInAllocaType</a>, <a href="#a01640692cf7fbf4574227f7899af2e71">getParamNoFPClass</a>, <a href="#a1e664c47c22c883baf848ad37261637c">getParamPreallocatedType</a>, <a href="#a00a04c74b7f139321a0b49f5249e2d57">getParamStackAlign</a>, <a href="#a287b116e4b7437fc6f4a0ca5f96add85">getParamStructRetType</a>, <a href="#a16d457bc91b566b5fdcb785dfc8862e7">getRetAlign</a>, <a href="#a06511680b1f7b6834735343e1d5c2e7f">getRetAttr</a>, <a href="#ab114d0e71d6a1db826bade5d22b0028c">getRetDereferenceableBytes</a>, <a href="#acf32f4feeff0b07e12c42c614a4791c1">getRetDereferenceableOrNullBytes</a>, <a href="#a08c455a4c7338c00f6d0bc9efecf9cb8">getRetNoFPClass</a>, <a href="#a1646cf4edf9e4502235bf4882f12f30e">hasByValArgument</a>, <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>, <a href="#ab18063e13ecbbbdea86aa54cd118b1db">removeAttributeAtIndex</a>, <a href="#a38dc9fea21bad23a1ca15b9c7a7ec484">removeAttributeAtIndex</a>, <a href="#acd7acfca49e931306ba40f1eb6939f67">removeFnAttr</a>, <a href="#ada5536ea9f061a27091a487f69565b3e">removeFnAttr</a>, <a href="#a68f6ab734f9bafb1a1b591267ef402d8">removeFnAttrs</a>, <a href="#a2ab5d0b4d639b3f79ff3922441e0082e">removeParamAttr</a>, <a href="#af7aecdc1aa280f1c8c0aa194b3453b46">removeParamAttr</a>, <a href="#a14f9c4f42aae35f61b404a5d21e9d88d">removeParamAttrs</a>, <a href="#a9724a78a61a4a4d72941116c6bd7c892">removeRetAttr</a>, <a href="#a2d9fe4a8103a58d5dee8ff09e6fa2152">removeRetAttrs</a>, <a href="#aa5d60fefd4d76e44095f07fd48e46096">returnDoesNotAlias</a> and <a href="#a9da3b29e8e71b9be4645874e1721207a">setAttributes</a>.</p>

</div>
</div>

### FTy {#aacb21b50e69e3d808db0120e9a0a7b9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType* llvm::CallBase::FTy</td>
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



<p>Definition at line 1127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="#ac3c35bd078a268a207f607d0f57dadba">getFunctionType</a>, <a href="#aba272b7337f4e135f28eeb0bcc69adbb">mutateFunctionType</a> and <a href="#a0107453b6a36d93e5a10d48cdac4d06c">setCalledFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addOperandBundle() {#a70d8ffa4f0ffa07bd736cb74d178d917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase * CallBase::addOperandBundle (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, uint32_t ID, <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> OB, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt=nullptr)</td>
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

<p>Create a clone of <span class="doxyComputerOutput">CB</span> with operand bundle <span class="doxyComputerOutput">OB</span> added.</p>

<p>Declaration at line 1174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 562 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="#aca631a010bfa5a055b7a07fe9e68f7e9">Create</a>, <a href="#a23ab5f34fb7b9476d45da0102ecbfae6">getOperandBundle</a>, <a href="#a19263fff7f5b3a9d22b48151fa0d85d0">getOperandBundlesAsDefs</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#abf4fabc264b52dbd503f04805135a40e">inlineRetainOrClaimRVCalls</a> and <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/runtimecallinserter/#af2c1b11e25a6289f7eca7c11acd304dc">anonymous{AddressSanitizer.cpp}::RuntimeCallInserter::~RuntimeCallInserter</a>.</p>

</div>
</div>

### classof() {#a55f751706099c68d86b273f33971bc76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 1190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#ae70f02adcd410ca9c8429fa8d7711965">Instruction</a>.</p>


<p>Referenced by <a href="#ad608d6540a71ecab577d6e890a458209">classof</a>.</p>

</div>
</div>

### classof() {#ad608d6540a71ecab577d6e890a458209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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



<p>Definition at line 1195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a55f751706099c68d86b273f33971bc76">classof</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### Create() {#aca631a010bfa5a055b7a07fe9e68f7e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase * CallBase::Create (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; Bundles, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt=nullptr)</td>
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

<p>Create a clone of <span class="doxyComputerOutput">CB</span> with a different set of operand bundles and insert it before <span class="doxyComputerOutput">InsertPt</span>.</p>


<p>The returned call instruction is identical <span class="doxyComputerOutput">CB</span> in every way except that the operand bundles for the new instruction are set to the operand bundles in <span class="doxyComputerOutput">Bundles</span>.</p>


<p>Declaration at line 1162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 301 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ad827d6e6b726bda4090423719c8a6fff">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#afd66a65191b8b1e51ce7d6aa1a726329">llvm::InvokeInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ab4e05d690df389b8b1477c90387b575f">llvm::Instruction::getOpcode</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#a70d8ffa4f0ffa07bd736cb74d178d917">addOperandBundle</a>, <a href="#a6577a1fc727a8972f1fcd8d14c70b29e">Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af939eab05ffe67221645aab1342156b2">PropagateOperandBundles</a>, <a href="#ad82786d29c116d0bf5131f654d51e681">removeOperandBundle</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>.</p>

</div>
</div>

### Create() {#a6577a1fc727a8972f1fcd8d14c70b29e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase * CallBase::Create (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> Bundle, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt=nullptr)</td>
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

<p>Create a clone of <span class="doxyComputerOutput">CB</span> with the operand bundle with the tag matching <span class="doxyComputerOutput">Bundle's</span> tag replaced with Bundle, and insert it before <span class="doxyComputerOutput">InsertPt</span>.</p>


<p>The returned call instruction is identical <span class="doxyComputerOutput">CI</span> in every way except that the specified operand bundle has been replaced.</p>


<p>Declaration at line 1170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 315 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="#aca631a010bfa5a055b7a07fe9e68f7e9">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a>, <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a> and <a href="/web-llvm/docs/api/classes/llvm/operandbundledeft/#aafd670922cb0e577561bb2aec9677683">llvm::OperandBundleDefT&lt; InputTy &gt;::getTag</a>.</p>

</div>
</div>

### removeOperandBundle() {#ad82786d29c116d0bf5131f654d51e681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase * CallBase::removeOperandBundle (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * CB, uint32_t ID, <a href="/web-llvm/docs/api/classes/llvm/insertposition">InsertPosition</a> InsertPt=nullptr)</td>
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

<p>Create a clone of <span class="doxyComputerOutput">CB</span> with operand bundle <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span> removed.</p>

<p>Declaration at line 1179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 574 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="#aca631a010bfa5a055b7a07fe9e68f7e9">Create</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a>, <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/classes/llvm/objcarc/bundledretainclaimrvs/#ad32a933965ba0059ff2a3a322cc8b40b">llvm::objcarc::BundledRetainClaimRVs::eraseInst</a>, <a href="/web-llvm/docs/api/classes/llvm/kcfipass/#a19dcb564cb3c8a4de327c6f9cabed5b3">llvm::KCFIPass::run</a> and <a href="/web-llvm/docs/api/classes/spirvstripconvergentintrinsics/#a4d2b7f7dd9786ee2f5eba35539cbd397">SPIRVStripConvergentIntrinsics::runOnFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Attributes

### CalledOperandOpEndIdx {#a598efe23bbf3bd82fa6b6a5588aa58b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::CallBase::CalledOperandOpEndIdx = -1</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The last operand is the called operand.</p>

<p>Definition at line 1124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operand Bundle API



<p>This group of methods provides the API to access and manipulate operand bundles on this call.</p>


### bundle\_op\_info\_begin {#a09fff26473ca9a3d9d1ff51633e048c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bundle_op_iterator llvm::CallBase::bundle_op_info_begin ()</td>
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

<p>Return the start of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser.</p>


<p>OperandBundleUser uses the descriptor area co-allocated with the host <a href="/web-llvm/docs/api/classes/llvm/user">User</a> to store some meta information about which operands are "normal" operands, and which ones belong to some operand bundle.</p>


<p>The layout of an operand bundle user is</p>



<pre><code>     +-----------uint32_t End-------------------------------------+
     |                                                            |
     |  +--------uint32_t Begin--------------------+              |
     |  |                                          |              |
     ^  ^                                          v              v
</code></pre>


<p>|---—|---—|-—|-—|-—|-—|-—|------—|-—|------—|-—|--— | BOI0 | BOI1 | .. | DU | U0 | U1 | .. | BOI0_U0 | .. | BOI1_U0 | .. | Un |---—|---—|-—|-—|-—|-—|-—|------—|-—|------—|-—|--— v v ^ ^ | | | | | +-----—uint32_t Begin---------—+ | | | +--------—uint32_t End--------------------------—+</p>


<p>BOI0, BOI1 ... are descriptions of operand bundles in this <a href="/web-llvm/docs/api/classes/llvm/user">User</a>'s use list. These descriptions are installed and managed by this class, and they're all instances of OperandBundleUser&lt;T&gt;::BundleOpInfo.</p>


<p>DU is an additional descriptor installed by <a href="/web-llvm/docs/api/classes/llvm/user">User</a>'s 'operator new' to keep track of the 'BOI0 ... BOIN' co-allocation. OperandBundleUser does not access or modify DU in any way, it's an implementation detail private to <a href="/web-llvm/docs/api/classes/llvm/user">User</a>.</p>


<p>The regular <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector for the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> starts at U0. The operand bundle uses are part of the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector, just like normal uses. In the diagram above, the operand bundle uses start at BOI0_U0. Each instance of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> has information about a contiguous set of uses constituting an operand bundle, and the total set of operand bundle uses themselves form a contiguous set of uses (i.e. there are no gaps between uses corresponding to individual operand bundles).</p>


<p>This class does not know the location of the set of operand bundle uses within the use list – that is decided by the <a href="/web-llvm/docs/api/classes/llvm/user">User</a> using this class via the BeginIdx argument in populateBundleOperandInfos.</p>


<p>Currently operand bundle users with hung-off operands are not supported.</p>


<p>Definition at line 2214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#a0d4a83cd78f12aa1ab452c4d94b9cb7b">llvm::User::getDescriptor</a> and <a href="#a042568b06f355d5c5fcd78dcfb381676">hasDescriptor</a>.</p>


<p>Referenced by <a href="#a63109b37b9bc1849d98d8f787ad650d7">bundle_op_infos</a>, <a href="#a1a0fc4db1daa05339f90300036edeea8">bundle_op_infos</a>, <a href="#a7a21e7face454c8ea6c4b9e12b506e40">getBundleOperandsStartIndex</a>, <a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a>, <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>, <a href="#a4e301518882466a796c3b890aac2e866">hasIdenticalOperandBundleSchema</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>.</p>

</div>
</div>

### bundle\_op\_info\_begin {#a6d15f6b4756852ff1757a7e479fbcb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_bundle_op_iterator llvm::CallBase::bundle_op_info_begin ()</td>
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

<p>Return the start of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser.</p>

<p>Definition at line 2224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>.</p>

</div>
</div>

### bundle\_op\_info\_end {#a418564b6605d97c81db3dc3ddc4cb948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bundle_op_iterator llvm::CallBase::bundle_op_info_end ()</td>
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

<p>Return the end of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser.</p>

<p>Definition at line 2231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/user/#a0d4a83cd78f12aa1ab452c4d94b9cb7b">llvm::User::getDescriptor</a> and <a href="#a042568b06f355d5c5fcd78dcfb381676">hasDescriptor</a>.</p>


<p>Referenced by <a href="#a63109b37b9bc1849d98d8f787ad650d7">bundle_op_infos</a>, <a href="#a1a0fc4db1daa05339f90300036edeea8">bundle_op_infos</a>, <a href="#a0951bc018bd4725e28d9d05e36a1360a">getBundleOperandsEndIndex</a>, <a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a>, <a href="#a4e301518882466a796c3b890aac2e866">hasIdenticalOperandBundleSchema</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>.</p>

</div>
</div>

### bundle\_op\_info\_end {#aeebc4ed71de27cdd341498e7030a30ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_bundle_op_iterator llvm::CallBase::bundle_op_info_end ()</td>
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

<p>Return the end of the list of <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances associated with this OperandBundleUser.</p>

<p>Definition at line 2241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>.</p>

</div>
</div>

### bundle\_op\_infos {#a63109b37b9bc1849d98d8f787ad650d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; bundle_op_iterator &gt; llvm::CallBase::bundle_op_infos ()</td>
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

<p>Return the range [<span class="doxyComputerOutput">bundle_op_info_begin</span>, <span class="doxyComputerOutput">bundle_op_info_end</span>).</p>

<p>Definition at line 2247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a>, <a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a> and <a href="#a93f122dff654f8336680531a3898375c">populateBundleOperandInfos</a>.</p>

</div>
</div>

### bundle\_op\_infos {#a1a0fc4db1daa05339f90300036edeea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_bundle_op_iterator &gt; llvm::CallBase::bundle_op_infos ()</td>
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

<p>Return the range [<span class="doxyComputerOutput">bundle_op_info_begin</span>, <span class="doxyComputerOutput">bundle_op_info_end</span>).</p>

<p>Definition at line 2252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a>, <a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### bundle\_op\_iterator {#a49f898706ddd985e5d2673f203832578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallBase::bundle_op_iterator =  BundleOpInfo *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### bundleOperandHasAttr {#ac0d230e2d456d6a6c94d272428f05395}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::bundleOperandHasAttr (unsigned OpIdx, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> A)</td>
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

<p>Return true if the bundle operand at index <span class="doxyComputerOutput">OpIdx</span> has the attribute <span class="doxyComputerOutput">A</span>.</p>

<p>Definition at line 2108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a> and <a href="#a1b6cd42ee6d8d51324f79e5e5e5d5f74">operandBundleFromBundleOpInfo</a>.</p>


<p>Referenced by <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>.</p>

</div>
</div>

### const\_bundle\_op\_iterator {#afe8638b163c6d6824432adf467aab267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::CallBase::const_bundle_op_iterator =  const BundleOpInfo *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### CountBundleInputs {#ac795264d758ae8856ba1f1f74fc4acb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::CountBundleInputs (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; Bundles)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the total number of values used in <span class="doxyComputerOutput">Bundles</span>.</p>

<p>Definition at line 2282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af5ab7a47bc553dfc3ee92daf969d0d7ca96b0141273eabab320119c467cdcaf17">llvm::Total</a>.</p>

</div>
</div>

### countOperandBundlesOfType {#a652220e0fde7043b474f1d6a85cd0452}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::countOperandBundlesOfType (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Return the number of operand bundles with the tag Name attached to this instruction.</p>

<p>Definition at line 2029 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> and <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>.</p>


<p>Referenced by <a href="#a23ab5f34fb7b9476d45da0102ecbfae6">getOperandBundle</a>, <a href="#ae0de2d66512556efff4898a90ef0f041">getOperandBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>.</p>

</div>
</div>

### countOperandBundlesOfType {#aa08853cdbf6877e032d15d3900088e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::countOperandBundlesOfType (uint32_t ID)</td>
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

<p>Return the number of operand bundles with the tag <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> attached to this instruction.</p>

<p>Definition at line 2040 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">llvm::Count</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> and <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>.</p>

</div>
</div>

### getBundleOperandsEndIndex {#a0951bc018bd4725e28d9d05e36a1360a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getBundleOperandsEndIndex ()</td>
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

<p>Return the index of the last bundle operand in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> array.</p>

<p>Definition at line 1980 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a>, <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#ada395c3a073fdc65e96bf018d9d0cf4f">llvm::CallBase::BundleOpInfo::End</a> and <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a>.</p>


<p>Referenced by <a href="#aff4a43d51265443e3d62d49395d0b585">getNumTotalBundleOperands</a> and <a href="#ac2be9e255ef96b741c5680c3d66f8587">isBundleOperand</a>.</p>

</div>
</div>

### getBundleOperandsStartIndex {#a7a21e7face454c8ea6c4b9e12b506e40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getBundleOperandsStartIndex ()</td>
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

<p>Return the index of the first bundle operand in the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> array.</p>

<p>Definition at line 1974 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#af823d55c0067f516522508d1a38b2992">llvm::CallBase::BundleOpInfo::Begin</a>, <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a> and <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a>.</p>


<p>Referenced by <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>, <a href="#aff4a43d51265443e3d62d49395d0b585">getNumTotalBundleOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a> and <a href="#ac2be9e255ef96b741c5680c3d66f8587">isBundleOperand</a>.</p>

</div>
</div>

### getBundleOpInfoForOperand {#a05315814f0e1ff39f8e753d7ac430a02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase::BundleOpInfo &amp; CallBase::getBundleOpInfoForOperand (unsigned OpIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> for the operand at index OpIdx.</p>


<p>It is an error to call this with an OpIdx that does not correspond to an bundle operand.</p>


<p>Declaration at line 2275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#af823d55c0067f516522508d1a38b2992">llvm::CallBase::BundleOpInfo::Begin</a>, <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a>, <a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a>, <a href="#a63109b37b9bc1849d98d8f787ad650d7">bundle_op_infos</a>, <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#ada395c3a073fdc65e96bf018d9d0cf4f">llvm::CallBase::BundleOpInfo::End</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="#ac0d230e2d456d6a6c94d272428f05395">bundleOperandHasAttr</a>, <a href="#a8cee61c774fe9d8b6a956984a6168ad0">getBundleOpInfoForOperand</a> and <a href="#aa635b5961d4592b8224755579c752414">getOperandBundleForOperand</a>.</p>

</div>
</div>

### getBundleOpInfoForOperand {#a8cee61c774fe9d8b6a956984a6168ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const BundleOpInfo &amp; llvm::CallBase::getBundleOpInfoForOperand (unsigned OpIdx)</td>
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



<p>Definition at line 2276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a> and <a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a>.</p>

</div>
</div>

### getNumOperandBundles {#a35b3798829fba58f145ea59e4214e84a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getNumOperandBundles ()</td>
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

<p>Return the number of operand bundles associated with this <a href="/web-llvm/docs/api/classes/llvm/user">User</a>.</p>

<p>Definition at line 1966 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a> and <a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ad9c2018082a0bb908947e363733b3c25">llvm::CallBrInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a9e52b82293f11aed8b26862a02fc3f54">llvm::CallInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#a307d5a58d01ab9dd06f2e3acc2ac1437">llvm::InvokeInst::cloneImpl</a>, <a href="#a652220e0fde7043b474f1d6a85cd0452">countOperandBundlesOfType</a>, <a href="#aa08853cdbf6877e032d15d3900088e56">countOperandBundlesOfType</a>, <a href="#a6577a1fc727a8972f1fcd8d14c70b29e">Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="#a23ab5f34fb7b9476d45da0102ecbfae6">getOperandBundle</a>, <a href="#ae0de2d66512556efff4898a90ef0f041">getOperandBundle</a>, <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>, <a href="#a19263fff7f5b3a9d22b48151fa0d85d0">getOperandBundlesAsDefs</a>, <a href="#a4e301518882466a796c3b890aac2e866">hasIdenticalOperandBundleSchema</a>, <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a>, <a href="#aa2d248762d49cd9fa5443dea54c7e6f3">hasOperandBundlesOtherThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="#ad82786d29c116d0bf5131f654d51e681">removeOperandBundle</a>.</p>

</div>
</div>

### getNumTotalBundleOperands {#aff4a43d51265443e3d62d49395d0b585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::CallBase::getNumTotalBundleOperands ()</td>
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

<p>Return the total number operands (not operand bundles) used by every operand bundle in this OperandBundleUser.</p>

<p>Definition at line 2010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a0951bc018bd4725e28d9d05e36a1360a">getBundleOperandsEndIndex</a>, <a href="#a7a21e7face454c8ea6c4b9e12b506e40">getBundleOperandsStartIndex</a> and <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a>.</p>


<p>Referenced by <a href="#ac0f11b96f81b2769dd23d028e3189075">arg_end</a>, <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#aae2d74b7aa304f8f6126f4b1e6e00dd0">llvm::CallBrInst::getIndirectDestLabel</a> and <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#a7929a2a96611a7af6f8a0f45d823c2b3">llvm::CallBrInst::getIndirectDestLabelUse</a>.</p>

</div>
</div>

### getOperandBundle {#a23ab5f34fb7b9476d45da0102ecbfae6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; OperandBundleUse &gt; llvm::CallBase::getOperandBundle (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Return an operand bundle by name, if present.</p>


<p>It is an error to call this for operand bundle types that may have multiple instances of them on the same instruction.</p>


<p>Definition at line 2053 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a652220e0fde7043b474f1d6a85cd0452">countOperandBundlesOfType</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> and <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>.</p>


<p>Referenced by <a href="#a70d8ffa4f0ffa07bd736cb74d178d917">addOperandBundle</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a21ea18f2c76b35d0985927f6ffebf9ba">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a7ba763fe17be006dc5cb7408dd332432">canParameterizeCallOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a23b0fbe869cf4baef885aaab613ffe56">llvm::GCStatepointInst::deopt_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a2df806263f1e5d5cfbd39ada183f6fd2">llvm::GCStatepointInst::deopt_end</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a748b2e4d7bb43011fcc43c38945c7a86">llvm::GCStatepointInst::gc_live_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#abe5a441ccb5494ac458909dd7b28ecdc">llvm::GCStatepointInst::gc_live_end</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#a36080372317ba912639416f07a561506">llvm::GCStatepointInst::gc_transition_args_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#af422fe78a5f773d1d6948224670d7498">llvm::GCStatepointInst::gc_transition_args_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aaa634580f5cb9e54209fa554bf8fb388">llvm::objcarc::getAttachedARCFunction</a>, <a href="#ad6139303612b013feb3df0e6c5e1ad26">getConvergenceControlToken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4ea5b2388bd9dc7e7fc902b5bd1e35e4">HandleCallsInBlockInlinedThroughInvoke</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aefba9af2f61452f20f4c947b4c2e5f4e">llvm::objcarc::hasAttachedCallOpBundle</a>, <a href="#aec62dc363b96fea41e5a7e2e627498de">hasDeoptState</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac9742261cd7ee88cb99ec122fc61f5e8">llvm::SelectionDAGBuilder::LowerCallSiteWithPtrAuthBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a27aee52717271be9e79135bfaab890ce">llvm::makeGuardControlFlowExplicit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a9cb75e325aabbbb2e1fdf034b2f11491">replaceUnwindCoroEnd</a> and <a href="/web-llvm/docs/api/classes/llvm/sccpsolver/#a1f7cd4c14e02c076508142fbb2c1aa79">llvm::SCCPSolver::tryToReplaceWithConstant</a>.</p>

</div>
</div>

### getOperandBundle {#ae0de2d66512556efff4898a90ef0f041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; OperandBundleUse &gt; llvm::CallBase::getOperandBundle (uint32_t ID)</td>
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

<p>Return an operand bundle by tag <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, if present.</p>


<p>It is an error to call this for operand bundle types that may have multiple instances of them on the same instruction.</p>


<p>Definition at line 2069 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a652220e0fde7043b474f1d6a85cd0452">countOperandBundlesOfType</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> and <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>.</p>

</div>
</div>

### getOperandBundleAt {#a1b38c4ecbbce4814b679f08b72b1d67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OperandBundleUse llvm::CallBase::getOperandBundleAt (unsigned Index)</td>
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

<p>Return the operand bundle at a specific index.</p>

<p>Definition at line 2022 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> and <a href="#a1b6cd42ee6d8d51324f79e5e5e5d5f74">operandBundleFromBundleOpInfo</a>.</p>


<p>Referenced by <a href="#a652220e0fde7043b474f1d6a85cd0452">countOperandBundlesOfType</a>, <a href="#aa08853cdbf6877e032d15d3900088e56">countOperandBundlesOfType</a>, <a href="#a6577a1fc727a8972f1fcd8d14c70b29e">Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/assumptioncache-cpp/#a51e2be2d1cd63e7b951c1f25c8eb182b">findAffectedValues</a>, <a href="#a23ab5f34fb7b9476d45da0102ecbfae6">getOperandBundle</a>, <a href="#ae0de2d66512556efff4898a90ef0f041">getOperandBundle</a>, <a href="#a19263fff7f5b3a9d22b48151fa0d85d0">getOperandBundlesAsDefs</a>, <a href="#aa2d248762d49cd9fa5443dea54c7e6f3">hasOperandBundlesOtherThan</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="#ad82786d29c116d0bf5131f654d51e681">removeOperandBundle</a>.</p>

</div>
</div>

### getOperandBundleForOperand {#aa635b5961d4592b8224755579c752414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OperandBundleUse llvm::CallBase::getOperandBundleForOperand (unsigned OpIdx)</td>
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

<p>Return the operand bundle for the operand at index OpIdx.</p>


<p>It is an error to call this with an OpIdx that does not correspond to an bundle operand.</p>


<p>Definition at line 2094 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a05315814f0e1ff39f8e753d7ac430a02">getBundleOpInfoForOperand</a> and <a href="#a1b6cd42ee6d8d51324f79e5e5e5d5f74">operandBundleFromBundleOpInfo</a>.</p>


<p>Referenced by <a href="#a203a11487b55577e3f295af2e3e2ae2a">isOperandBundleOfType</a>.</p>

</div>
</div>

### getOperandBundlesAsDefs {#a19263fff7f5b3a9d22b48151fa0d85d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::getOperandBundlesAsDefs (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; &amp; Defs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the list of operand bundles attached to this instruction as a vector of OperandBundleDefs.</p>


<p>This function copies the OperandBundeUse instances associated with this OperandBundleUser to a vector of OperandBundleDefs. Note: OperandBundeUses and OperandBundleDefs are non-trivially <em>different</em> representations of operand bundles (see documentation above).</p>


<p>Declaration at line 2088 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> and <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>.</p>


<p>Referenced by <a href="#a70d8ffa4f0ffa07bd736cb74d178d917">addOperandBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/classes/llvm/fortifiedlibcallsimplifier/#ab5f693b48590402b0109cfdca55ec335">llvm::FortifiedLibCallSimplifier::optimizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/libcallsimplifier/#a73c4a774eb638f963533b77f7124293b">llvm::LibCallSimplifier::optimizeCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a5b064b03163c5f9304d4b702da5fa1e4">RemovePreallocated</a>.</p>

</div>
</div>

### hasClobberingOperandBundles {#ad4139298dd770711bf92cf3b95ba200a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::hasClobberingOperandBundles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this operand bundle user has operand bundles that may write to the heap.</p>

<p>Declaration at line 2104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#ac62778065b99372cc62cf994b967e7e8">getIntrinsicID</a>, <a href="#aa2d248762d49cd9fa5443dea54c7e6f3">hasOperandBundlesOtherThan</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a">llvm::LLVMContext::OB_deopt</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca8997c6b0930e2c05209e95e7172c6cf3">llvm::LLVMContext::OB_funclet</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cadb925bc2eb2c117b3ec0b76d1e267127">llvm::LLVMContext::OB_kcfi</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cadd4d7ff61cc637f50c78417fc8e67c15">llvm::LLVMContext::OB_ptrauth</a>.</p>


<p>Referenced by <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>

</div>
</div>

### hasDeoptState {#aec62dc363b96fea41e5a7e2e627498de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasDeoptState ()</td>
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

<p>Return true if the call has deopt state bundle.</p>

<p>Definition at line 2266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a23ab5f34fb7b9476d45da0102ecbfae6">getOperandBundle</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9ca3f6df86c6efab701ade7abbc3134c25a">llvm::LLVMContext::OB_deopt</a>.</p>

</div>
</div>

### hasIdenticalOperandBundleSchema {#a4e301518882466a796c3b890aac2e866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasIdenticalOperandBundleSchema (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Other)</td>
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

<p>Return true if <span class="doxyComputerOutput">Other</span> has the same sequence of operand bundle tags with the same number of operands on each one of them as this OperandBundleUser.</p>

<p>Definition at line 2117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a09fff26473ca9a3d9d1ff51633e048c1">bundle_op_info_begin</a>, <a href="#a418564b6605d97c81db3dc3ddc4cb948">bundle_op_info_end</a>, <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### hasOperandBundles {#aecc0c27ae96638bc9d8fa4caffa92c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasOperandBundles ()</td>
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

<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/user">User</a> has any operand bundles.</p>

<p>Definition at line 1971 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-functionattrs-cpp-/argumentusestracker/#aa35ba8c73830d12eea5dda2a41aba718">anonymous{FunctionAttrs.cpp}::ArgumentUsesTracker::captured</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ad9c2018082a0bb908947e363733b3c25">llvm::CallBrInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a9e52b82293f11aed8b26862a02fc3f54">llvm::CallInst::cloneImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/invokeinst/#a307d5a58d01ab9dd06f2e3acc2ac1437">llvm::InvokeInst::cloneImpl</a>, <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>, <a href="#a0951bc018bd4725e28d9d05e36a1360a">getBundleOperandsEndIndex</a>, <a href="#a7a21e7face454c8ea6c4b9e12b506e40">getBundleOperandsStartIndex</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a652b7ff39d88ac67e35d0955ac906292">anonymous{OpenMPOpt.cpp}::OpenMPOpt::getCallIfRegularCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/openmpopt/#a86c7b47618d45adedaeb1fb0f920c15c">anonymous{OpenMPOpt.cpp}::OpenMPOpt::getCallIfRegularCall</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>, <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>, <a href="#aff4a43d51265443e3d62d49395d0b585">getNumTotalBundleOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#acb2c6a8dafac1cdf8927e67b28baab1c">getSameOpcode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="#a5fb497a3113f10b593158ab55bfd1e1c">isBundleOperand</a> and <a href="#ac2be9e255ef96b741c5680c3d66f8587">isBundleOperand</a>.</p>

</div>
</div>

### hasOperandBundlesOtherThan {#aa2d248762d49cd9fa5443dea54c7e6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasOperandBundlesOtherThan (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt; IDs)</td>
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

<p>Return true if this operand bundle user contains operand bundles with tags other than those specified in <span class="doxyComputerOutput">IDs</span>.</p>

<p>Definition at line 2127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a35b3798829fba58f145ea59e4214e84a">getNumOperandBundles</a>, <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a>, <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse/#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9">llvm::OperandBundleUse::getTagID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#ad4139298dd770711bf92cf3b95ba200a">hasClobberingOperandBundles</a>, <a href="#ada195b22ad562f2d06824c595765dd30">hasReadingOperandBundles</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#af31ca6130fc1fdac86bfb75b1acac4ac">markTails</a>.</p>

</div>
</div>

### hasReadingOperandBundles {#ada195b22ad562f2d06824c595765dd30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::hasReadingOperandBundles ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this operand bundle user has operand bundles that may read from the heap.</p>

<p>Declaration at line 2100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#ac62778065b99372cc62cf994b967e7e8">getIntrinsicID</a>, <a href="#aa2d248762d49cd9fa5443dea54c7e6f3">hasOperandBundlesOtherThan</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cadb925bc2eb2c117b3ec0b76d1e267127">llvm::LLVMContext::OB_kcfi</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cadd4d7ff61cc637f50c78417fc8e67c15">llvm::LLVMContext::OB_ptrauth</a>.</p>


<p>Referenced by <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>

</div>
</div>

### isBundleOperand {#ac2be9e255ef96b741c5680c3d66f8587}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isBundleOperand (unsigned Idx)</td>
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

<p>Return true if the operand at index <span class="doxyComputerOutput">Idx</span> is a bundle operand.</p>

<p>Definition at line 1986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a0951bc018bd4725e28d9d05e36a1360a">getBundleOperandsEndIndex</a>, <a href="#a7a21e7face454c8ea6c4b9e12b506e40">getBundleOperandsStartIndex</a> and <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a>.</p>


<p>Referenced by <a href="#a5fb497a3113f10b593158ab55bfd1e1c">isBundleOperand</a>, <a href="#ad3533647593dde9cf45849501086c9d2">isBundleOperand</a> and <a href="#a203a11487b55577e3f295af2e3e2ae2a">isOperandBundleOfType</a>.</p>

</div>
</div>

### isBundleOperand {#a5fb497a3113f10b593158ab55bfd1e1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isBundleOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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

<p>Returns true if the use is a bundle operand.</p>

<p>Definition at line 1999 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a>, <a href="#ac2be9e255ef96b741c5680c3d66f8587">isBundleOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>.</p>

</div>
</div>

### isBundleOperand {#ad3533647593dde9cf45849501086c9d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isBundleOperand (<a href="/web-llvm/docs/api/classes/llvm/value/#a146665db2d7a79fa164098370a3a34c4">Value::const_user_iterator</a> UI)</td>
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



<p>Definition at line 2004 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#ac2be9e255ef96b741c5680c3d66f8587">isBundleOperand</a>.</p>

</div>
</div>

### isOperandBundleOfType {#a203a11487b55577e3f295af2e3e2ae2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isOperandBundleOfType (uint32_t ID, unsigned Idx)</td>
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

<p>Return true if the operand at index <span class="doxyComputerOutput">Idx</span> is a bundle operand that has tag <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a></span>.</p>

<p>Definition at line 1993 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#aa635b5961d4592b8224755579c752414">getOperandBundleForOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse/#a6386ca6c50ec4ef5d9a0f13e7fe8f0c9">llvm::OperandBundleUse::getTagID</a> and <a href="#ac2be9e255ef96b741c5680c3d66f8587">isBundleOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a7ba763fe17be006dc5cb7408dd332432">canParameterizeCallOperand</a>.</p>

</div>
</div>

### operandBundleFromBundleOpInfo {#a1b6cd42ee6d8d51324f79e5e5e5d5f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OperandBundleUse llvm::CallBase::operandBundleFromBundleOpInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> &amp; BOI)</td>
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

<p>Simple helper function to map a <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> to an <a href="/web-llvm/docs/api/structs/llvm/operandbundleuse">OperandBundleUse</a>.</p>

<p>Definition at line 2159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#af823d55c0067f516522508d1a38b2992">llvm::CallBase::BundleOpInfo::Begin</a>, <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#ada395c3a073fdc65e96bf018d9d0cf4f">llvm::CallBase::BundleOpInfo::End</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a> and <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo/#a6aa7df1351e95051b1565a3df18dacb0">llvm::CallBase::BundleOpInfo::Tag</a>.</p>


<p>Referenced by <a href="#ac0d230e2d456d6a6c94d272428f05395">bundleOperandHasAttr</a>, <a href="#a1b38c4ecbbce4814b679f08b72b1d67f">getOperandBundleAt</a> and <a href="#aa635b5961d4592b8224755579c752414">getOperandBundleForOperand</a>.</p>

</div>
</div>

### populateBundleOperandInfos {#a93f122dff654f8336680531a3898375c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBase::op_iterator CallBase::populateBundleOperandInfos (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; Bundles, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned BeginIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate the <a href="/web-llvm/docs/api/structs/llvm/callbase/bundleopinfo">BundleOpInfo</a> instances and the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; vector from <span class="doxyComputerOutput">Bundles</span>.</p>


<p>Return the <a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">op_iterator</a> pointing to the <a href="/web-llvm/docs/api/classes/llvm/use">Use</a>&amp; one past the last last bundle operand use.</p>


<p>Each <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a></span> instance is tracked by a OperandBundleInfo instance allocated in this <a href="/web-llvm/docs/api/classes/llvm/user">User</a>'s descriptor.</p>


<p>Declaration at line 2262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 490 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="#a63109b37b9bc1849d98d8f787ad650d7">bundle_op_infos</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a> and <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#aa142c8c536b95dd8e8a243cb67b57a80">llvm::LLVMContext::pImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Attribute API



<p>These methods access and modify attributes on this call (including looking through to the attributes on the called function when necessary).</p>


### addAttributeAtIndex {#a9ec1fe122d152d6c6cefbdab43a43cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>adds the attribute to the list of attributes.</p>

<p>Definition at line 1464 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### addAttributeAtIndex {#a2060ab64acfc67af974e20cbc79ca273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
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

<p>adds the attribute to the list of attributes.</p>

<p>Definition at line 1469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### addDereferenceableParamAttr {#adf1a2105045f7e33738b34f49b0f9f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addDereferenceableParamAttr (unsigned i, uint64_t Bytes)</td>
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

<p>adds the dereferenceable attribute to the list of attributes.</p>

<p>Definition at line 1558 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### addDereferenceableRetAttr {#a9add940717795f05bb69603216f17254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addDereferenceableRetAttr (uint64_t Bytes)</td>
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

<p>adds the dereferenceable attribute to the list of attributes.</p>

<p>Definition at line 1563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### addFnAttr {#a0f72a62efd0912aba72c6818c720023c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Adds the attribute to the function.</p>

<p>Definition at line 1474 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memoryprofileinfo-cpp/#ade3d002f2a3c1617aacaddf25e561833">addAllocTypeAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/structs/llvm/attributor/#a45f6cbf770c1d990014838ceb300e936">llvm::Attributor::createShallowWrapper</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae63427c4d8f3c1ce48401b38ed9198f1">llvm::maybeMarkSanitizerLibraryCallNoBuiltin</a>, <a href="#ab343ed4a791fff67f7ab395b08b9a1e0">setCannotDuplicate</a>, <a href="#a6da7de997f92fdb5d3e85f4f5b9af20e">setCannotMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a5c27eeded5a29d83fe4cf5a8d19de645">llvm::CallInst::setCanReturnTwice</a>, <a href="#adbe1ad518eb726a3d9eb83a31100ce48">setConvergent</a>, <a href="#a086ea083312d974694676dcde76a1e65">setDoesNotReturn</a>, <a href="#a0b6cef2a78857b0236b1c3a2a6eb857e">setDoesNotThrow</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a444e3e622a00db2be6dcaf46cef996f5">llvm::setInlineRemark</a>, <a href="#ac74d68c9539ee35631f7f3435e46520b">setIsNoInline</a>, <a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a> and <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a9ad2ee389fa99a4c02f610183530735c">llvm::VFABI::setVectorVariantNames</a>.</p>

</div>
</div>

### addFnAttr {#a031e44afee1f29cd934862cebf714a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
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

<p>Adds the attribute to the function.</p>

<p>Definition at line 1479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### addParamAttr {#ae5d05ec2b9a60806746addff3f2a71a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Adds the attribute to the indicated argument.</p>

<p>Definition at line 1494 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#abb18e068cfa4ee49c6cc19a2ea5278d9">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::addConditionalCallbacksIfEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a8971fbe1184d7b7301a70ee23b318772">addNonNullAttribute</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ac04b6d4e5d3715d33fee0cf6c80a15c8">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::addReachesFunctionCallbacksIfEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aebd8fb1e50c14f4988226de940a067ed">annotateNonNullNoUndefBasedOnAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ac3e775626bfa565297feec5807947efc">llvm::IRBuilderBase::CreateElementUnorderedAtomicMemMove</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/irbuilder-cpp/#a35929b5ae2c67d8c86640518636092ae">CreateGCStatepointCallCommon</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a2001dcf6278f9e7e10b895d060d15abb">llvm::IRBuilderBase::CreateMaskedCompressStore</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad878957c30eb65983e09b60edb0e1a1b">llvm::IRBuilderBase::CreateMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aeac445a66283c4e567ebd390c058e39d">llvm::IRBuilderBase::CreatePreserveArrayAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a4804fd7127d8e249a628e93d6b8b3f2a">llvm::IRBuilderBase::CreatePreserveStructAccessIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a19f9814e01d7c1d3167216cba953eab2">llvm::IRBuilderBase::CreateThreadLocalAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a8631130c37aa54ae6c9127abc5fe392a">llvm::AArch64TargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#ab439771b84f342c37a8823fb2f797642">llvm::ARMTargetLowering::emitLoadLinked</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadevlrecipe/#a16471f19bad1ca5212ccbd52c21b8b54">llvm::VPWidenLoadEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenstoreevlrecipe/#a1c719942d2fa4ca51fe66c92b9ab834c">llvm::VPWidenStoreEVLRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a74b80978e3ab87994e9361f4bbc767dd">llvm::RISCVTargetLowering::lowerInterleavedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#ab33d2ce475c619c3e4412b33aac3b5bb">llvm::RISCVTargetLowering::lowerInterleavedStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/preiselintrinsiclowering-cpp/#aa5369c9d1c15e1c2fe5106461ae89334">lowerObjCCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a2a6b95606a7aa4afbc8a38114dd8da82">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::materializeOneCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a3e1cfc51d4ab9b192f09e050b24e410b">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a4ab0f2c30ee83d6377488de9a1f089e9">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a00c704ed1965bd5d0348f156a8e33506">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::storeOrigin</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a95a9e06abc2fb2a674a398adf05671f2">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCmpInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#ab1f923b66b5437b4912f28e87b6076ff">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitLoadInst</a> and <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a8f85dad5b58e981324eab559a5be4e87">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitStoreInst</a>.</p>

</div>
</div>

### addParamAttr {#a433ec4bd285111f13acdc8a78be16a72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
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

<p>Adds the attribute to the indicated argument.</p>

<p>Definition at line 1500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### addRangeRetAttr {#a0e7b74d310c94c459b8985806192cc99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addRangeRetAttr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; CR)</td>
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

<p>adds the range attribute to the list of attributes.</p>

<p>Definition at line 1568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#ab99310a04afb6c28186b1a6428eb75b0">hoistConditionalLoadsStores</a>.</p>

</div>
</div>

### addRetAttr {#aa94f59b6921a7cd3567439b3302a5357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Adds the attribute to the return value.</p>

<p>Definition at line 1484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a19f9814e01d7c1d3167216cba953eab2">llvm::IRBuilderBase::CreateThreadLocalAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerkernelarguments-cpp/#a804c9545f28631dc405eccad6d7234a7">lowerKernelArguments</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### addRetAttr {#ae30660fb489f8cbe69bf8650daadcdb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::addRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute">Attribute</a> Attr)</td>
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

<p>Adds the attribute to the return value.</p>

<p>Definition at line 1489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### cannotDuplicate {#a30d9c71916a2a8d7a227d871580265ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::cannotDuplicate ()</td>
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

<p>Determine if the invoke cannot be duplicated.</p>

<p>Definition at line 1929 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#aab2eda4003703fcc548e36043debfafa">canSplitCallSite</a>.</p>

</div>
</div>

### cannotMerge {#a08daddd36adb2d47a22de9b6177c7110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::cannotMerge ()</td>
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

<p>Determine if the call cannot be tail merged.</p>

<p>Definition at line 1933 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>

</div>
</div>

### dataOperandHasImpliedAttr {#a590b8b0d5d2ae53eeb6f290d7395c71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::dataOperandHasImpliedAttr (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Return true if the data operand at index <span class="doxyComputerOutput">i</span> has the attribute <span class="doxyComputerOutput">A</span>.</p>


<p>Data operands include call arguments and values used in operand bundles, but does not include the callee operand.</p>


<p>The index <span class="doxyComputerOutput">i</span> is interpreted as</p>


<p><span class="doxyComputerOutput">i</span> in [0, arg_size) -&gt; argument number (<span class="doxyComputerOutput">i</span>) <span class="doxyComputerOutput">i</span> in [arg_size, data_operand_size) -&gt; bundle operand at index (<span class="doxyComputerOutput">i</span>) in the operand list.</p>


<p>Definition at line 1649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ac0d230e2d456d6a6c94d272428f05395">bundleOperandHasAttr</a>, <a href="#a7a21e7face454c8ea6c4b9e12b506e40">getBundleOperandsStartIndex</a>, <a href="#aff4a43d51265443e3d62d49395d0b585">getNumTotalBundleOperands</a>, <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a> and <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="#a2d989cf6c0da10e436e1e95e380e0e09">doesNotAccessMemory</a>, <a href="#a27ab264aa1e655ed42732fe0ec40d441">doesNotCapture</a>, <a href="#a857a8c38e4856efec047cc914c25b692">onlyReadsMemory</a> and <a href="#a63dc200b9de33401dee748b417e9b329">onlyWritesMemory</a>.</p>

</div>
</div>

### doesNoCfCheck {#a4ba8528d08dec5d59a0dc66f56588b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::doesNoCfCheck ()</td>
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

<p>Determine if the call should not perform indirect branch tracking.</p>

<p>Definition at line 1922 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>

</div>
</div>

### doesNotAccessMemory {#a2d989cf6c0da10e436e1e95e380e0e09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::doesNotAccessMemory (unsigned OpNo)</td>
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



<p>Definition at line 1715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ad633d6152693e0c1dd402507ac156289">isTrigLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp/#af31ca6130fc1fdac86bfb75b1acac4ac">markTails</a> and <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaexecutiondomainfunction/#a53429c521770c95bf0380a74711dd451">anonymous{OpenMPOpt.cpp}::AAExecutionDomainFunction::updateImpl</a>.</p>

</div>
</div>

### doesNotAccessMemory {#a16951c81e4ffebc84739c2882a030e4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::doesNotAccessMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the call does not access memory.</p>


<p>Determine if the function does not access memory.</p>


<p>Declaration at line 1891 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a513f55e474dba6d6c2507997e9920b6d">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::doesNotAccessMemory</a> and <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>.</p>

</div>
</div>

### doesNotCapture {#a27ab264aa1e655ed42732fe0ec40d441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::doesNotCapture (unsigned OpNo)</td>
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

<p>Determine whether this data operand is not captured.</p>

<p>Definition at line 1669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a> and <a href="#a610f151afe638890b21bea434a26821d">isByValArgument</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslicerewriter/#a73e5f32465500cf4cbd002f5c1c9a025">anonymous{SROA.cpp}::AllocaSliceRewriter::InstVisitor&lt; AllocaSliceRewriter, bool &gt;</a> and <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#ac88e3e89148ab5849fc08d1eef269a84">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visitCallBase</a>.</p>

</div>
</div>

### doesNotReturn {#ad8b80c508197d6dcbe67e082426a8026}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::doesNotReturn ()</td>
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

<p>Determine if the call cannot return.</p>

<p>Definition at line 1918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>

</div>
</div>

### doesNotThrow {#aa87fae97a8c702741eca5a95748af49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::doesNotThrow ()</td>
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

<p>Determine if the call cannot unwind.</p>

<p>Definition at line 1925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a4ea5b2388bd9dc7e7fc902b5bd1e35e4">HandleCallsInBlockInlinedThroughInvoke</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#abbd47852a13b73290f4625f20c9018d8">isRemovableWrite</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#ad633d6152693e0c1dd402507ac156289">isTrigLibCall</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getArgOperandWithAttribute {#ac7cae01462379060b2dae3f960054c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * CallBase::getArgOperandWithAttribute (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If one of the arguments has the specified attribute, returns its operand value.</p>


<p>Otherwise, return nullptr.</p>


<p>Declaration at line 1871 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#af5dcb6d3da4b30a7d21c9fb39bbf1a68a503c0b646ea0b3868c0c8380fdc688b8">llvm::AttributeList::FirstArgIndex</a>, <a href="#aabd76e6a8a23a5af1ce4d3c310d88bcd">getArgOperand</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab9cb77a3069c227792d6bade6faff422">llvm::getFreedOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4ff10451ba01dc08fc0d38983c6743b7">llvm::getReallocatedOperand</a>, <a href="#ac95847047b045e505c83450ad09c1d25">getReturnedArgOperand</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-deadstoreelimination-cpp-/#a4f3e2c0f6369d8d9bd65a1f7c16f2f52">anonymous{DeadStoreElimination.cpp}::hasInitializesAttr</a>.</p>

</div>
</div>

### getAttributeAtIndex {#abcdfbff6a28275c90eab24a36cbc4240}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::CallBase::getAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Get the attribute of a given kind at a position.</p>

<p>Definition at line 1595 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributelist/#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">llvm::AttributeList::getAttributeAtIndex</a> and <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a>.</p>

</div>
</div>

### getAttributeAtIndex {#affe34085f142d12218c875ad46b506b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::CallBase::getAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Get the attribute of a given kind at a position.</p>

<p>Definition at line 1600 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attributelist/#aa13d8e07ad2d8a1e2cbc5e8baa5d4c60">llvm::AttributeList::getAttributeAtIndex</a> and <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a>.</p>

</div>
</div>

### getAttributes {#ae0c55761fce39dd71617690b04385193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeList llvm::CallBase::getAttributes ()</td>
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

<p>Return the attributes for this call.</p>

<p>Definition at line 1417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1481db7804704b4beb48e8c2ad4c94b2">llvm::changeToInvokeAndSplitBasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/callbrinst/#ac56dc4e7c9b62727513a77d85a3dc243">llvm::CallBrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a1f815573461be87717cbb7a4ce30f875">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a720b783746c2f472ba1a810c8a3fe600">expandAtan2Intrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#ab26ebd710695202964347075355c501d">expandExpIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a8be283da675a1b678e17fd283f14945c">expandLogIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a7e60b335a21054740045b2f77975841f">expandPowIntrinsic</a>, <a href="#abcdfbff6a28275c90eab24a36cbc4240">getAttributeAtIndex</a>, <a href="#affe34085f142d12218c875ad46b506b8">getAttributeAtIndex</a>, <a href="#a838a60b97fcf512dbf9116b564b05f2c">getFnAttr</a>, <a href="#a9e46a3a4bf99f8dcea9cb9efb4d977a3">getFnAttr</a>, <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>, <a href="#a50b4d34365cf704260dd9e43796144ea">getParamAttr</a>, <a href="#a29461b85f0f7f0d91323ff2e40de2d75">getParamAttr</a>, <a href="#a31dce9e2b84da293213f996778355b32">getParamAttributes</a>, <a href="#a82be2ba8b164fb0cf70e254f9c8a13a3">getRetAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a5c59325f9c3c1526f4439392c892fd41">optimizeCallInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4e385793d373a822cffdeaa9ee8f3e19">RemoveAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/smeattrs/#aa5e262aac758714fcbe1b579d3d37920">llvm::SMEAttrs::SMEAttrs</a>, <a href="#afb49554840d9c699b6b3a2a09361dbd8">tryIntersectAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### getFnAttr {#a9e46a3a4bf99f8dcea9cb9efb4d977a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::CallBase::getFnAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Get the attribute of a given kind for the function.</p>

<p>Definition at line 1605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a90024ee48918b2167a4c9409750d4148">llvm::AttributeList::getFnAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/memorybuiltins-cpp/#a7a4b1bb434f664cf880b1dd79909c61a">getAllocationSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a657d70881481b03f8b3b38838f3a7c39">llvm::getAssumptions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a24380444e7b6b5af3e742282c87d4219">llvm::getStringFnAttrAsInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05eaff7b97d11f44f547d03244617db4">llvm::hasAssumption</a>.</p>

</div>
</div>

### getFnAttr {#a838a60b97fcf512dbf9116b564b05f2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::CallBase::getFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Get the attribute of a given kind for the function.</p>

<p>Definition at line 1613 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a90024ee48918b2167a4c9409750d4148">llvm::AttributeList::getFnAttr</a>.</p>

</div>
</div>

### getMemoryEffects {#a0af057818885e78ae73169231c243b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemoryEffects CallBase::getMemoryEffects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1887 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 607 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a>, <a href="#a8d13199cbf4d080d3b5dcf330dad5d2c">getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/attributelist/#afb984e3fb006d09d90fcc934789cfbd8">llvm::AttributeList::getMemoryEffects</a>, <a href="#ad4139298dd770711bf92cf3b95ba200a">hasClobberingOperandBundles</a>, <a href="#aecc0c27ae96638bc9d8fa4caffa92c31">hasOperandBundles</a>, <a href="#ada195b22ad562f2d06824c595765dd30">hasReadingOperandBundles</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a0dc1a3456bce25673dff8dce6f240a8f">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::readOnly</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a9e3dc568b5f51e03441c9c44b618f337">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::writeOnly</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="#a16951c81e4ffebc84739c2882a030e4f">doesNotAccessMemory</a>, <a href="#adc6331fb2f51f3f964b8f9494ab6620e">onlyAccessesArgMemory</a>, <a href="#a7a2ce134efb83b008e2180d30451ac98">onlyAccessesInaccessibleMemOrArgMem</a>, <a href="#a34613a108e56086f52edab637d1d55ae">onlyAccessesInaccessibleMemory</a>, <a href="#a5be058522f7a1076ffb760c30171b2cd">onlyReadsMemory</a>, <a href="#aca77ab9c9b9577f6ae3d1a08d6499738">onlyWritesMemory</a>, <a href="#a19fa26173a9afc96fadd278584892766">setOnlyAccessesArgMemory</a>, <a href="#a1f63e188e21bf64cfa775849cd37334d">setOnlyAccessesInaccessibleMemOrArgMem</a>, <a href="#ac9a52d36d02e6e763dbff76fffc55aef">setOnlyAccessesInaccessibleMemory</a>, <a href="#a68bd81d0004f8cc3cdcef6151677c673">setOnlyReadsMemory</a> and <a href="#a923df3cbec0e08cc6d2be259286c2e3c">setOnlyWritesMemory</a>.</p>

</div>
</div>

### getParamAlign {#a7713a45c8983df00c3975444b94e69ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::CallBase::getParamAlign (unsigned ArgNo)</td>
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

<p>Extract the alignment for a call or parameter (0=unknown).</p>

<p>Definition at line 1748 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#ac03b57021568dcc4d9a685c40011ff09">llvm::MemIntrinsicBase&lt; Derived &gt;::getDestAlign</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a6fa466783177c427903cc7d61ea79f57">llvm::MemIntrinsicBase&lt; Derived &gt;::getDestAlignment</a>, <a href="/web-llvm/docs/api/classes/llvm/vpintrinsic/#ae3a0c2dd2caff6d81180f9724a6d369e">llvm::VPIntrinsic::getPointerAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a237ac9d59f45a0b7c18296704e005a6c">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerColumnMajorLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a4c72146be47366faa66bbe3fa93abf2a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerColumnMajorStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a93ae09e320f176a41ae347e5f1dcd714">scalarizeMaskedCompressStore</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a372b313738e7d6b96b0ef622ce60890c">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::visitCallBase</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>.</p>

</div>
</div>

### getParamAttr {#a50b4d34365cf704260dd9e43796144ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::CallBase::getParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Get the attribute of a given kind from a given arg.</p>

<p>Definition at line 1621 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a4bd6dadb077a5c3503a74b8c5850a805">llvm::AttributeList::getParamAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a> and <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>.</p>

</div>
</div>

### getParamAttr {#a29461b85f0f7f0d91323ff2e40de2d75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::CallBase::getParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Get the attribute of a given kind from a given arg.</p>

<p>Definition at line 1630 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a4bd6dadb077a5c3503a74b8c5850a805">llvm::AttributeList::getParamAttr</a>.</p>

</div>
</div>

### getParamAttributes {#a31dce9e2b84da293213f996778355b32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet llvm::CallBase::getParamAttributes (unsigned ArgNo)</td>
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

<p>Return the param attributes for this call.</p>

<p>Definition at line 1428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#ada7a173c40ca7ac048a4b7099ceb71c0">llvm::AttributeList::getParamAttrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>.</p>

</div>
</div>

### getParamByRefType {#a1951bdad78f9a0cb364948f121d6fba4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CallBase::getParamByRefType (unsigned ArgNo)</td>
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

<p>Extract the byref type for a call or parameter.</p>

<p>Definition at line 1757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>.</p>

</div>
</div>

### getParamByValType {#a88cc5fa65ff17e62b49dc5fb4401f813}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CallBase::getParamByValType (unsigned ArgNo)</td>
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

<p>Extract the byval type for a call or parameter.</p>

<p>Definition at line 1766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#acc81d19554e4eb245d659a89a2fd6f37">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a372b313738e7d6b96b0ef622ce60890c">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::visitCallBase</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>.</p>

</div>
</div>

### getParamDereferenceableBytes {#a37269632d3b68130c5b7019cd795be44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallBase::getParamDereferenceableBytes (unsigned i)</td>
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

<p>Extract the number of dereferenceable bytes for a call or parameter (0=unknown).</p>

<p>Definition at line 1819 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>.</p>

</div>
</div>

### getParamDereferenceableOrNullBytes {#abaf8a257af9e537d7cd8b05299e5090c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallBase::getParamDereferenceableOrNullBytes (unsigned i)</td>
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

<p>Extract the number of dereferenceable_or_null bytes for a parameter (0=unknown).</p>

<p>Definition at line 1837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>.</p>

</div>
</div>

### getParamElementType {#aa9d39950dcbd9e1e6dac2b66db4324d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CallBase::getParamElementType (unsigned ArgNo)</td>
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

<p>Extract the elementtype type for a parameter.</p>


<p>Note that elementtype() can only be applied to call arguments, not function declaration parameters.</p>


<p>Definition at line 1804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gcstatepointinst/#addf5e64879884d57feb90917960dc288">llvm::GCStatepointInst::getActualReturnType</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a27c9f05f074b1acd44859e85c1212bc1">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitAsmInstruction</a>.</p>

</div>
</div>

### getParamInAllocaType {#a2b576de254a0b0c5f278538862840e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CallBase::getParamInAllocaType (unsigned ArgNo)</td>
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

<p>Extract the inalloca type for a call or parameter.</p>

<p>Definition at line 1784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>

</div>
</div>

### getParamNoFPClass {#a01640692cf7fbf4574227f7899af2e71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest CallBase::getParamNoFPClass (unsigned i)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a test mask for disallowed floating-point value classes for the parameter.</p>

<p>Declaration at line 1847 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 370 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>

</div>
</div>

### getParamPreallocatedType {#a1e664c47c22c883baf848ad37261637c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CallBase::getParamPreallocatedType (unsigned ArgNo)</td>
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

<p>Extract the preallocated type for a call or parameter.</p>

<p>Definition at line 1775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>

</div>
</div>

### getParamStackAlign {#a00a04c74b7f139321a0b49f5249e2d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::CallBase::getParamStackAlign (unsigned ArgNo)</td>
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



<p>Definition at line 1752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>

</div>
</div>

### getParamStructRetType {#a287b116e4b7437fc6f4a0ca5f96add85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::CallBase::getParamStructRetType (unsigned ArgNo)</td>
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

<p>Extract the sret type for a call or parameter.</p>

<p>Definition at line 1793 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>

</div>
</div>

### getRange {#aa64b47f684944bcb9aea2c1350440cd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; CallBase::getRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this return value has a range attribute, return the value range of the argument.</p>


<p>Otherwise, std::nullopt is returned.</p>


<p>Declaration at line 1851 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 378 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attribute/#a10eb642c38648a5edb4a6bc7ce217a17">llvm::Attribute::getRange</a>, <a href="#a06511680b1f7b6834735343e1d5c2e7f">getRetAttr</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a7e0764cee9d3754f276a61e53da1c2b4">IdentifyValidPoisonGeneratingAttributes</a>.</p>

</div>
</div>

### getRetAlign {#a16d457bc91b566b5fdcb785dfc8862e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::CallBase::getRetAlign ()</td>
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

<p>Extract the alignment of the return value.</p>

<p>Definition at line 1739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a7e0764cee9d3754f276a61e53da1c2b4">IdentifyValidPoisonGeneratingAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaheaptostackfunction/#a7d3aee2fc33ae5d5ffe0085711f601bf">anonymous{AttributorAttributes.cpp}::AAHeapToStackFunction::manifest</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### getRetAttr {#a06511680b1f7b6834735343e1d5c2e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Attribute llvm::CallBase::getRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Return the attribute for the given attribute kind for the return value.</p>

<p>Definition at line 1580 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343af2bbdf9f72c085adc4d0404e370f0f4c">llvm::Attribute</a>, <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/ir/attributes-cpp/#a50b54203d53a07641d04250d2a7f039da19331ed2fb57db290a26f2869bae2f45">RetAttr</a>.</p>


<p>Referenced by <a href="#aa64b47f684944bcb9aea2c1350440cd7">getRange</a>.</p>

</div>
</div>

### getRetAttributes {#a82be2ba8b164fb0cf70e254f9c8a13a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AttributeSet llvm::CallBase::getRetAttributes ()</td>
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

<p>Return the return attributes for this call.</p>

<p>Definition at line 1423 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/attributelist/#a5604157867b3d226260f6388b987e49a">llvm::AttributeList::getRetAttrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>.</p>

</div>
</div>

### getRetDereferenceableBytes {#ab114d0e71d6a1db826bade5d22b0028c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallBase::getRetDereferenceableBytes ()</td>
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

<p>Extract the number of dereferenceable bytes for a call or parameter (0=unknown).</p>

<p>Definition at line 1810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a006ce5c0c5ec18c589454f270a335a3c">IdentifyValidUBGeneratingAttributes</a> and <a href="#aab40deb840751b104926b1052d91e7fc">isReturnNonNull</a>.</p>

</div>
</div>

### getRetDereferenceableOrNullBytes {#acf32f4feeff0b07e12c42c614a4791c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::CallBase::getRetDereferenceableOrNullBytes ()</td>
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

<p>Extract the number of dereferenceable_or_null bytes for a call (0=unknown).</p>

<p>Definition at line 1825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a006ce5c0c5ec18c589454f270a335a3c">IdentifyValidUBGeneratingAttributes</a>.</p>

</div>
</div>

### getRetNoFPClass {#a08c455a4c7338c00f6d0bc9efecf9cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FPClassTest CallBase::getRetNoFPClass ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract a test mask for disallowed floating-point value classes for the return value.</p>

<p>Declaration at line 1843 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 362 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>.</p>

</div>
</div>

### getReturnedArgOperand {#ac95847047b045e505c83450ad09c1d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::CallBase::getReturnedArgOperand ()</td>
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

<p>If one of the arguments has the 'returned' attribute, returns its operand value.</p>


<p>Otherwise, return nullptr.</p>


<p>Definition at line 1865 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#ac7cae01462379060b2dae3f960054c6f">getArgOperandWithAttribute</a>.</p>

</div>
</div>

### hasByValArgument {#a1646cf4edf9e4502235bf4882f12f30e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasByValArgument ()</td>
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

<p>Determine if any call argument is an aggregate passed by value.</p>

<p>Definition at line 1952 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>

</div>
</div>

### hasFnAttr {#a2fbfe5377a984518a7c03d8558df726d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Determine whether this call has the given attribute.</p>


<p>If it does not then determine if the called function has the attribute, but only if the attribute is allowed for the call.</p>


<p>Definition at line 1451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a30d9c71916a2a8d7a227d871580265ce">cannotDuplicate</a>, <a href="#a08daddd36adb2d47a22de9b6177c7110">cannotMerge</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#a8efd271074231871996d10f15a0b8752">llvm::CallInst::canReturnTwice</a>, <a href="#a4ba8528d08dec5d59a0dc66f56588b7c">doesNoCfCheck</a>, <a href="#ad8b80c508197d6dcbe67e082426a8026">doesNotReturn</a>, <a href="#aa87fae97a8c702741eca5a95748af49d">doesNotThrow</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#abed91fefcc041268a8f52d7db0be4fce">InstrBreaksNoFree</a>, <a href="#ac32c9ebab7dfd3db749d0ab5e6e58b3e">isConvergent</a>, <a href="#a57c98f6b8ffe38c7c8d75f92a82d0ee3">isNoInline</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ae47d97e1c5c07ee94c968058e19acb98">llvm::CallInst::isNonContinuableTrap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adffe8dd96d1c957f04909ca9c2cd79ba">llvm::isSafeToMoveBefore</a>, <a href="#a300433f583bb9e2862b84df663f43f40">isStrictFP</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aae4a4706a2a2568c38bd04b1354eafb4">llvm::SITargetLowering::passSpecialInputs</a>.</p>

</div>
</div>

### hasFnAttr {#a4c901967b076f5c9d245000b7637822a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasFnAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Determine whether this call has the given attribute.</p>


<p>If it does not then determine if the called function has the attribute, but only if the attribute is allowed for the call.</p>


<p>Definition at line 1460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### hasInAllocaArgument {#a140af9f05b67d6b2a3b7cc8513254e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasInAllocaArgument ()</td>
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

<p>Determine if there are is an inalloca argument.</p>


<p>Only the last argument can have the inalloca attribute.</p>


<p>Definition at line 1709 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a0efb2d7a831e24212063c504045d3203">arg_empty</a>, <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a> and <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>.</p>

</div>
</div>

### hasRetAttr {#a330471067c17061b7c2152d75102f24a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Determine whether the return value has the given attribute.</p>

<p>Definition at line 1573 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a8843a51d7d6aaf2e81c17ae86f86d3f6">AddReturnAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a7e0764cee9d3754f276a61e53da1c2b4">IdentifyValidPoisonGeneratingAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#a006ce5c0c5ec18c589454f270a335a3c">IdentifyValidUBGeneratingAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a46f0bc39f45a99f997c4f124c505fb50">isFunctionMallocLike</a>, <a href="#aab40deb840751b104926b1052d91e7fc">isReturnNonNull</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### hasRetAttr {#a528035b19a094c04b880d91fedfe8b6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasRetAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Determine whether the return value has the given attribute.</p>

<p>Definition at line 1577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>

</div>
</div>

### hasStructRetAttr {#aae67e9ebc8e8d1033eaf27acf4ad622c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::hasStructRetAttr ()</td>
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

<p>Determine if the call returns a structure through first pointer argument.</p>

<p>Definition at line 1943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a0efb2d7a831e24212063c504045d3203">arg_empty</a> and <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>

</div>
</div>

### isByValArgument {#a610f151afe638890b21bea434a26821d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isByValArgument (unsigned ArgNo)</td>
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

<p>Determine whether this argument is passed by value.</p>

<p>Definition at line 1679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>


<p>Referenced by <a href="#a27ab264aa1e655ed42732fe0ec40d441">doesNotCapture</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="#a857a8c38e4856efec047cc914c25b692">onlyReadsMemory</a>.</p>

</div>
</div>

### isConvergent {#ac32c9ebab7dfd3db749d0ab5e6e58b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isConvergent ()</td>
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

<p>Determine if the invoke is convergent.</p>

<p>Definition at line 1937 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#aab2eda4003703fcc548e36043debfafa">canSplitCallSite</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlineasmlowering-cpp-/extraflags/#a265ccdc955df6841403de15996982e3e">anonymous{InlineAsmLowering.cpp}::ExtraFlags::ExtraFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/earlycse-cpp/#ad4cae6fe0d617016d48331d85dffa4c8">hashCallInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#ae64bb5b78cd6a7e4568e355e6422f6f4">InstrBreaksNonConvergent</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#a2b4653fa0c302d9cbe4e7839d711e76a">llvm::SelectionDAGBuilder::LowerCallTo</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aanosyncimpl/#a671a7ae35e26ce8b5b12340ec2c712a6">anonymous{AttributorAttributes.cpp}::AANoSyncImpl::updateImpl</a>.</p>

</div>
</div>

### isInAllocaArgument {#a2f410f8b74acae583c8589e52de992fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isInAllocaArgument (unsigned ArgNo)</td>
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

<p>Determine whether this argument is passed in an alloca.</p>

<p>Definition at line 1684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>

</div>
</div>

### isNoBuiltin {#a1fb374eb65dcf7cd3d1671efb2616f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isNoBuiltin ()</td>
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

<p>Return true if the call should not be treated as a call to a builtin.</p>

<p>Definition at line 1875 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/injecttlimappings-cpp/#a8bde7bea5a6d6a50fd5b6d03d746e05b">addMappingsFromTLI</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo/#a130c04c64f1ad6c7bea33c1aff8160be">llvm::TargetLibraryInfo::getLibFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8a8b818a539c2cbbe1a954a875c5fcec">getVectorCallCosts</a>, <a href="/web-llvm/docs/api/classes/llvm/libcallsimplifier/#a73c4a774eb638f963533b77f7124293b">llvm::LibCallSimplifier::optimizeCall</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a> and <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#ab013e5e37e15eee5725a24b6a6df2416">llvm::AMDGPULibCalls::useNative</a>.</p>

</div>
</div>

### isNoInline {#a57c98f6b8ffe38c7c8d75f92a82d0ee3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isNoInline ()</td>
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

<p>Return true if the call should not be inlined.</p>

<p>Definition at line 1884 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>

</div>
</div>

### isPassingUndefUB {#a1c09dbc5b720c1d0a74e303d0e6765bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isPassingUndefUB (unsigned ArgNo)</td>
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

<p>Determine whether passing undef to this argument is undefined behavior.</p>


<p>If passing undef to this argument is UB, passing poison is UB as well because poison is more undefined than undef.</p>


<p>Definition at line 1699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>

</div>
</div>

### isPassPointeeByValueArgument {#af18a046d00e9c3059053fb96e43f0bfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isPassPointeeByValueArgument (unsigned ArgNo)</td>
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

<p>Determine whether this argument is passed by value, in an alloca, or is preallocated.</p>

<p>Definition at line 1690 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a4cbb2344996abd4332716e76178ad4f4">paramHasAttr</a>.</p>

</div>
</div>

### isReturnNonNull {#aab40deb840751b104926b1052d91e7fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::isReturnNonNull ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the return value is known to be not null.</p>


<p>This may be because it has the nonnull attribute, or because at least one byte is dereferenceable and the pointer is in addrspace(0).</p>


<p>Declaration at line 1856 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#afac5b39bcbb90d660f83d9b4bd8c6d95">getCaller</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a21b1f2d0effa0506f01cb146823de6a2">llvm::getPointerAddressSpace</a>, <a href="#ab114d0e71d6a1db826bade5d22b0028c">getRetDereferenceableBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#a330471067c17061b7c2152d75102f24a">hasRetAttr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a7b03ed78a8e299bde6d26a8793cd4e06">llvm::NullPointerIsDefined</a>.</p>

</div>
</div>

### isStrictFP {#a300433f583bb9e2862b84df663f43f40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::isStrictFP ()</td>
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

<p>Determine if the call requires strict floating point semantics.</p>

<p>Definition at line 1881 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a2fbfe5377a984518a7c03d8558df726d">hasFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>.</p>

</div>
</div>

### onlyAccessesArgMemory {#adc6331fb2f51f3f964b8f9494ab6620e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::onlyAccessesArgMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the call can access memmory only using pointers based on its arguments.</p>

<p>Declaration at line 1904 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a8bc927c80d7734e7e0baef13efd08bc5">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesArgPointees</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>.</p>

</div>
</div>

### onlyAccessesInaccessibleMemOrArgMem {#a7a2ce134efb83b008e2180d30451ac98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::onlyAccessesInaccessibleMemOrArgMem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the function may only access memory that is either inaccessible from the IR or pointed to by its arguments.</p>

<p>Declaration at line 1914 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#afe3bf77a36d10551139f91d68bb00c4d">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesInaccessibleOrArgMem</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>.</p>

</div>
</div>

### onlyAccessesInaccessibleMemory {#a34613a108e56086f52edab637d1d55ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::onlyAccessesInaccessibleMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the function may only access memory that is inaccessible from the IR.</p>

<p>Declaration at line 1909 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 661 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a636d669d76e435e9d71cdc417c89a30c">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyAccessesInaccessibleMem</a>.</p>

</div>
</div>

### onlyReadsMemory {#a857a8c38e4856efec047cc914c25b692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::onlyReadsMemory (unsigned OpNo)</td>
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



<p>Definition at line 1721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a> and <a href="#a610f151afe638890b21bea434a26821d">isByValArgument</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-tailrecursionelimination-cpp-/allocaderivedvaluetracker/#a6019b1c94104110144aa402a98d7076f">anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker::callUsesLocalStack</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/callvalue/#abf2170fc4c00058df8ef27562be3fb39">anonymous{EarlyCSE.cpp}::CallValue::canHandle</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/functionattrs-cpp/#a11e85bd0636c06273039d95814064fd1">determinePointerAccessAttrs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#a3bc18cb70ac72d463ce6ee68cbc00d64">llvm::objcarc::GetCallSiteClass</a>, <a href="/web-llvm/docs/api/classes/llvm/memorylocation/#a4904e476c0d296b50491f629f7de59c3">llvm::MemoryLocation::getForDest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9db7e1f11fa5a274a0cffb6fc5e524be">llvm::getIntrinsicForCallSite</a>, <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/valuetable/#a0f202a9387b6d7a60044c0ea986e7cb4">anonymous{GVNSink.cpp}::ValueTable::getMemoryUseOrder</a> and <a href="/web-llvm/docs/api/classes/anonymous-sroa-cpp-/allocaslicerewriter/#a73e5f32465500cf4cbd002f5c1c9a025">anonymous{SROA.cpp}::AllocaSliceRewriter::InstVisitor&lt; AllocaSliceRewriter, bool &gt;</a>.</p>

</div>
</div>

### onlyReadsMemory {#a5be058522f7a1076ffb760c30171b2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::onlyReadsMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the call does not access or only reads memory.</p>


<p>Determine if the function does not access or only reads memory.</p>


<p>Declaration at line 1895 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a8c57cabc627d282678d407f79da2b6e7">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyReadsMemory</a>.</p>

</div>
</div>

### onlyWritesMemory {#a63dc200b9de33401dee748b417e9b329}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::onlyWritesMemory (unsigned OpNo)</td>
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



<p>Definition at line 1733 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>.</p>

</div>
</div>

### onlyWritesMemory {#aca77ab9c9b9577f6ae3d1a08d6499738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::onlyWritesMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine if the call does not access or only writes memory.</p>


<p>Determine if the function does not access or only writes memory.</p>


<p>Declaration at line 1899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a0fc7f721f42a2177d9d6d94972a5cde5">llvm::MemoryEffectsBase&lt; LocationEnum &gt;::onlyWritesMemory</a>.</p>

</div>
</div>

### paramHasAttr {#a4cbb2344996abd4332716e76178ad4f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool CallBase::paramHasAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determine whether the argument or parameter has the given attribute.</p>

<p>Declaration at line 1592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 409 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">getCalledFunction</a>, <a href="#ad4139298dd770711bf92cf3b95ba200a">hasClobberingOperandBundles</a> and <a href="#ada195b22ad562f2d06824c595765dd30">hasReadingOperandBundles</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#aa35af336fee32786b6551e23d5b55fcf">AddAliasScopeMetadata</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#af1986bc1d2d700807f4c8ef167bf6fdd">AddParamAndFnBasicAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#aebd8fb1e50c14f4988226de940a067ed">annotateNonNullNoUndefBasedOnAccess</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp/#a494dabe67c8e93868fed4e59fbd49150">computeBytesPoppedByCalleeForSRet</a>, <a href="#a590b8b0d5d2ae53eeb6f290d7395c71c">dataOperandHasImpliedAttr</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#ae58d526e759487737de52702abf2b7c5">anonymous{DeadStoreElimination.cpp}::DSEState::getInitializesArgMemLoc</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper/#a7d1221047aae479ec27a751236ae95e6">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::getShadowExtension</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a8bb58bae0761c8591279171367a2b334">handleGuaranteedWellDefinedOps</a>, <a href="#a140af9f05b67d6b2a3b7cc8513254e2f">hasInAllocaArgument</a>, <a href="#aae67e9ebc8e8d1033eaf27acf4ad622c">hasStructRetAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a8126d22f7eb9fade7b5f423c75342d38">llvm::AMDGPU::isArgPassedInSGPR</a>, <a href="#a610f151afe638890b21bea434a26821d">isByValArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a26a463481e43dd8125ceef85d495be9d">isCondRelevantToAnyCallArgument</a>, <a href="#a2f410f8b74acae583c8589e52de992fa">isInAllocaArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="#a1c09dbc5b720c1d0a74e303d0e6765bf">isPassingUndefUB</a>, <a href="#af18a046d00e9c3059053fb96e43f0bfd">isPassPointeeByValueArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#acc81d19554e4eb245d659a89a2fd6f37">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a372b313738e7d6b96b0ef622ce60890c">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper/#af0bc023f29f779469e5e8e3f92b9db0f">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::visitCallBase</a> and <a href="/web-llvm/docs/api/classes/anonymous-webassemblyoptimizereturned-cpp-/optimizereturned/#ae81d17afe649660014f0e1ca569e8bf3">anonymous{WebAssemblyOptimizeReturned.cpp}::OptimizeReturned::visitCallBase</a>.</p>

</div>
</div>

### removeAttributeAtIndex {#ab18063e13ecbbbdea86aa54cd118b1db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>removes the attribute from the list of attributes.</p>

<p>Definition at line 1506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### removeAttributeAtIndex {#a38dc9fea21bad23a1ca15b9c7a7ec484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeAttributeAtIndex (unsigned i, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>removes the attribute from the list of attributes.</p>

<p>Definition at line 1511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### removeFnAttr {#acd7acfca49e931306ba40f1eb6939f67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeFnAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Removes the attribute from the function.</p>

<p>Definition at line 1521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a> and <a href="#a85986906dda425ba6e72a3078ffd6421">setNotConvergent</a>.</p>

</div>
</div>

### removeFnAttr {#ada5536ea9f061a27091a487f69565b3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeFnAttr (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Removes the attribute from the function.</p>

<p>Definition at line 1526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### removeFnAttrs {#a68f6ab734f9bafb1a1b591267ef402d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeFnAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
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

<p>Removes the attributes from the function.</p>

<p>Definition at line 1516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### removeParamAttr {#a2ab5d0b4d639b3f79ff3922441e0082e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Removes the attribute from the given argument.</p>

<p>Definition at line 1541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a67acb174a712823e6cf5e5b03bed3fdf">annotateDereferenceableBytes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a53602f27c06fcab4b6b5d552984a5ad7">promoteArguments</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/callsitesplitting-cpp/#a8e6d3da10023ff90b874399d8a1d7880">setConstantInArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a3e1cfc51d4ab9b192f09e050b24e410b">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a> and <a href="/web-llvm/docs/api/classes/llvm/memintrinsicbase/#a4ab0f2c30ee83d6377488de9a1f089e9">llvm::MemIntrinsicBase&lt; Derived &gt;::setDestAlignment</a>.</p>

</div>
</div>

### removeParamAttr {#af7aecdc1aa280f1c8c0aa194b3453b46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeParamAttr (unsigned ArgNo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
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

<p>Removes the attribute from the given argument.</p>

<p>Definition at line 1547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#adde2ea00dd2613ee41bfe91908e4e68e">arg_size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### removeParamAttrs {#a14f9c4f42aae35f61b404a5d21e9d88d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeParamAttrs (unsigned ArgNo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
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

<p>Removes the attributes from the given argument.</p>

<p>Definition at line 1553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>.</p>

</div>
</div>

### removeRetAttr {#a9724a78a61a4a4d72941116c6bd7c892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeRetAttr (<a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60e">Attribute::AttrKind</a> Kind)</td>
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

<p>Removes the attribute from the return value.</p>

<p>Definition at line 1531 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>

</div>
</div>

### removeRetAttrs {#a2d9fe4a8103a58d5dee8ff09e6fa2152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::removeRetAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/attributemask">AttributeMask</a> &amp; AttrsToRemove)</td>
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

<p>Removes the attributes from the return value.</p>

<p>Definition at line 1536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>.</p>

</div>
</div>

### returnDoesNotAlias {#aa5d60fefd4d76e44095f07fd48e46096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::returnDoesNotAlias ()</td>
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

<p>Determine if the return value is marked with NoAlias attribute.</p>

<p>Definition at line 1859 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>

</div>
</div>

### setAttributes {#a9da3b29e8e71b9be4645874e1721207a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setAttributes (<a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> A)</td>
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

<p>Set the attributes for this call.</p>

<p>Definition at line 1420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a> and <a href="#a97849e9f49e6326c0e055bc8f1ea4eec">Attrs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c3ae5ad4be121cbb1bc87e871b679da">llvm::createCallMatchingInvoke</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#aa71b78b68e5077a0c0201ceb8b5cbe85">emitBinaryFloatFnCallHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a560b77762851df60ac51ca48db42058b">emitUnaryFloatFnCallHelper</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilintrinsicexpansion-cpp/#a720b783746c2f472ba1a810c8a3fe600">expandAtan2Intrinsic</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a423393b3ce94c7230d81a41881918ccd">mergeAttributesAndFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#a1e38dc7f1aecace87c3977df3d96e680">processCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#aff4f43a1b558e2a63b2bc597665c7990">processCallSite</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a90c1755a8480ebc1dcc4f05d56271b00">llvm::promoteCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4e385793d373a822cffdeaa9ee8f3e19">RemoveAttribute</a>, <a href="#afb49554840d9c699b6b3a2a09361dbd8">tryIntersectAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#a87ed771bf8f375c44d2c5451328d4637">tryToMoveFreeBeforeNullTest</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### setCannotDuplicate {#ab343ed4a791fff67f7ab395b08b9a1e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setCannotDuplicate ()</td>
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



<p>Definition at line 1930 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroearly-cpp-/lowerer/#ad856ac9052abe36a0ca7e8909fd18f1b">anonymous{CoroEarly.cpp}::Lowerer::lowerEarlyIntrinsics</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroearly-cpp/#a0af71aee449ca1e2e4a0e3c280d8a791">setCannotDuplicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3f67233011e3c2264e7806412baa1595">setDXILAttributes</a>.</p>

</div>
</div>

### setCannotMerge {#a6da7de997f92fdb5d3e85f4f5b9af20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setCannotMerge ()</td>
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



<p>Definition at line 1934 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9f4e542bdcac1a2ab15b6e55991f07c8">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::insertWarningFn</a>.</p>

</div>
</div>

### setConvergent {#adbe1ad518eb726a3d9eb83a31100ce48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setConvergent ()</td>
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



<p>Definition at line 1938 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>.</p>

</div>
</div>

### setDoesNotAccessMemory {#a2db9f3ffecc57cf9333d355927413fbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::setDoesNotAccessMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1892 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 630 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#af04065f3c729719471689b08089942f3">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::none</a> and <a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3f67233011e3c2264e7806412baa1595">setDXILAttributes</a>.</p>

</div>
</div>

### setDoesNotReturn {#a086ea083312d974694676dcde76a1e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setDoesNotReturn ()</td>
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



<p>Definition at line 1919 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3f67233011e3c2264e7806412baa1595">setDXILAttributes</a>.</p>

</div>
</div>

### setDoesNotThrow {#a0b6cef2a78857b0236b1c3a2a6eb857e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setDoesNotThrow ()</td>
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



<p>Definition at line 1926 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afa2581e2e1ac6959cd02e28062a7c1d5">llvm::InstCombinerImpl::visitCallInst</a>.</p>

</div>
</div>

### setIsNoInline {#ac74d68c9539ee35631f7f3435e46520b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setIsNoInline ()</td>
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



<p>Definition at line 1885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/inlinerpass/#a78e09cea341cfdf58869920175c52d82">llvm::InlinerPass::run</a>.</p>

</div>
</div>

### setMemoryEffects {#aecb5289d51bac327bc2f7f5a2d0ad5c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::setMemoryEffects (<a href="/web-llvm/docs/api/namespaces/llvm/#a44ad2b29af9ebe3d12a99843a7594757">MemoryEffects</a> ME)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1888 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 622 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0f72a62efd0912aba72c6818c720023c">addFnAttr</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/attribute/#adaf42001b3cc4c8c631902cbb48106d5">llvm::Attribute::getWithMemoryEffects</a>.</p>


<p>Referenced by <a href="#a2db9f3ffecc57cf9333d355927413fbf">setDoesNotAccessMemory</a>, <a href="#a19fa26173a9afc96fadd278584892766">setOnlyAccessesArgMemory</a>, <a href="#a1f63e188e21bf64cfa775849cd37334d">setOnlyAccessesInaccessibleMemOrArgMem</a>, <a href="#ac9a52d36d02e6e763dbff76fffc55aef">setOnlyAccessesInaccessibleMemory</a>, <a href="#a68bd81d0004f8cc3cdcef6151677c673">setOnlyReadsMemory</a> and <a href="#a923df3cbec0e08cc6d2be259286c2e3c">setOnlyWritesMemory</a>.</p>

</div>
</div>

### setNotConvergent {#a85986906dda425ba6e72a3078ffd6421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::CallBase::setNotConvergent ()</td>
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



<p>Definition at line 1939 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>Reference <a href="#acd7acfca49e931306ba40f1eb6939f67">removeFnAttr</a>.</p>

</div>
</div>

### setOnlyAccessesArgMemory {#a19fa26173a9afc96fadd278584892766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::setOnlyAccessesArgMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1905 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5288b2ba178703d9e1f24a5d3708f594">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::argMemOnly</a>, <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a> and <a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a>.</p>

</div>
</div>

### setOnlyAccessesInaccessibleMemOrArgMem {#a1f63e188e21bf64cfa775849cd37334d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::setOnlyAccessesInaccessibleMemOrArgMem ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 673 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#ad341f584befc40ff0aefca99682baf7c">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleOrArgMemOnly</a> and <a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a>.</p>

</div>
</div>

### setOnlyAccessesInaccessibleMemory {#ac9a52d36d02e6e763dbff76fffc55aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::setOnlyAccessesInaccessibleMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1910 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a5cba4a49c183c6c2f6168be64f04a7b9">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::inaccessibleMemOnly</a> and <a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a>.</p>

</div>
</div>

### setOnlyReadsMemory {#a68bd81d0004f8cc3cdcef6151677c673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::setOnlyReadsMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1896 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 638 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a0dc1a3456bce25673dff8dce6f240a8f">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::readOnly</a> and <a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3f67233011e3c2264e7806412baa1595">setDXILAttributes</a>.</p>

</div>
</div>

### setOnlyWritesMemory {#a923df3cbec0e08cc6d2be259286c2e3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallBase::setOnlyWritesMemory ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1900 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>, definition at line 646 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a>.</p>


<p>References <a href="#a0af057818885e78ae73169231c243b2a">getMemoryEffects</a>, <a href="#aecb5289d51bac327bc2f7f5a2d0ad5c3">setMemoryEffects</a> and <a href="/web-llvm/docs/api/classes/llvm/memoryeffectsbase/#a9e3dc568b5f51e03441c9c44b618f337">llvm::MemoryEffectsBase&lt; IRMemLocation &gt;::writeOnly</a>.</p>

</div>
</div>

### tryIntersectAttributes {#afb49554840d9c699b6b3a2a09361dbd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallBase::tryIntersectAttributes (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> * Other)</td>
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

<p>Try to intersect the attributes from 'this' <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> and the 'Other' <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a>.</p>


<p>Sets the intersected attributes to 'this' and return true if successful. Doesn't modify 'this' and returns false if unsuccessful.</p>


<p>Definition at line 1436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a>.</p>


<p>References <a href="#a8a6c9c1339e7a196e0ae69031426c083">CallBase</a>, <a href="#ae0c55761fce39dd71617690b04385193">getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#ab3fc0225d8aaf8434026c3573f961f2c">llvm::Value::getContext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a> and <a href="#a9da3b29e8e71b9be4645874e1721207a">setAttributes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#acc8066950deec241b4fafe0700ff5f2c">mergeCompatibleInvokesImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instrtypes-h">InstrTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp">Instructions.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
