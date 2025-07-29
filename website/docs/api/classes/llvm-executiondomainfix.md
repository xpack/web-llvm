---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/executiondomainfix
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ExecutionDomainFix` Class



## Declaration

<div class="doxyDeclaration">
class llvm::ExecutionDomainFix { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">llvm/CodeGen/ExecutionDomainFix.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass">MachineFunctionPass</a> - This class adapts the <a href="/web-llvm/docs/api/classes/llvm/functionpass">FunctionPass</a> interface to allow convenient creation of passes that operate on the <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> representation. <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armexecutiondomainfix">ARMExecutionDomainFix</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-x86targetmachine-cpp-/x86executiondomainfix">X86ExecutionDomainFix</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f50c014d318f7bd5391a8811537340">LiveRegsDVInfo</a> = std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> currently in each register, or NULL when no value is being tracked. <a href="#a29f50c014d318f7bd5391a8811537340">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2e6cc750e2f33af7e57b6be3486fea1">OutRegsInfoMap</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; LiveRegsDVInfo, 4 &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keeps domain information for all registers. <a href="#aa2e6cc750e2f33af7e57b6be3486fea1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a141030b45949448836e2a786e89ba216">ExecutionDomainFix</a> (char &amp;PassID, const TargetRegisterClass &amp;RC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a101879a381eb818b929145a3354575b8">getAnalysisUsage</a> (AnalysisUsage &amp;AU) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job. <a href="#a101879a381eb818b929145a3354575b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa90dd7f08ca467a5d6dc3215fb98ee51">runOnMachineFunction</a> (MachineFunction &amp;MF) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis. <a href="#aa90dd7f08ca467a5d6dc3215fb98ee51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties">MachineFunctionProperties</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26657d3f8a330b3b43c90710cdc98cdf">getRequiredProperties</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; int &gt;<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">::const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c67bf36c726ef85915a890ac0b64ca">regIndices</a> (unsigned Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Translate TRI register number to a list of indices into our smaller tables of interesting registers. <a href="#a24c67bf36c726ef85915a890ac0b64ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1efd873c13e7037f49bc7ca26b2e4b78">alloc</a> (int domain=-1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> allocation. <a href="#a1efd873c13e7037f49bc7ca26b2e4b78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fdf6cfe6a3994a00b5ed44acf65df63">retain</a> (DomainValue *DV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add reference to DV. <a href="#a0fdf6cfe6a3994a00b5ed44acf65df63">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d16e49bab6bec162f627047e734f83">release</a> (DomainValue *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Release a reference to DV. <a href="#af0d16e49bab6bec162f627047e734f83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96ee03ab1de2d3bf79bc76c1c640119">resolve</a> (DomainValue *&amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Follow the chain of dead DomainValues until a live <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> is reached. <a href="#ad96ee03ab1de2d3bf79bc76c1c640119">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c6f9efac38759ed27b7b3751daf72c5">setLiveReg</a> (int rx, DomainValue *DV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set LiveRegs[rx] = dv, updating reference counts. <a href="#a1c6f9efac38759ed27b7b3751daf72c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb991635b24d9344a48a3abbf8cc3283">kill</a> (int rx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kill register rx, recycle or collapse any <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a>. <a href="#afb991635b24d9344a48a3abbf8cc3283">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d238d8385deab7b4cd62450a3b2eca">force</a> (int rx, unsigned domain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Force register rx into domain. <a href="#a64d238d8385deab7b4cd62450a3b2eca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1401bd55ffdf7647dff0b5d9cbc92ed">collapse</a> (DomainValue *dv, unsigned domain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collapse open <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> into given domain. <a href="#af1401bd55ffdf7647dff0b5d9cbc92ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a400099433f030ba48a87545288e89fc6">merge</a> (DomainValue *A, DomainValue *B)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All instructions and registers in B are moved to A, and B is released. <a href="#a400099433f030ba48a87545288e89fc6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ebbcd41ae4ba16e860d985bb59c8ab">enterBasicBlock</a> (const LoopTraversal::TraversedMBBInfo &amp;TraversedMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set up LiveRegs by merging predecessor live-out values. <a href="#a73ebbcd41ae4ba16e860d985bb59c8ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07eacb5daf93153c00a71a7ee0c54684">leaveBasicBlock</a> (const LoopTraversal::TraversedMBBInfo &amp;TraversedMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update live-out values. <a href="#a07eacb5daf93153c00a71a7ee0c54684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70ebfad844448c105d6354ee046e8fd4">processBasicBlock</a> (const LoopTraversal::TraversedMBBInfo &amp;TraversedMBB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> he given basic block. <a href="#a70ebfad844448c105d6354ee046e8fd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac048d5afb6d98aef4e3f9bb3618ea0e5">visitInstr</a> (MachineInstr *)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Visit given insturcion. <a href="#ac048d5afb6d98aef4e3f9bb3618ea0e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac954eac09919ac86f73491d2fff582f9">processDefs</a> (MachineInstr *, bool Kill)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update def-ages for registers defined by MI. <a href="#ac954eac09919ac86f73491d2fff582f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53321cb004793dde847dd9ebc35d08d3">visitSoftInstr</a> (MachineInstr *, unsigned mask)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A soft instruction can be changed to work in other domains given by mask. <a href="#a53321cb004793dde847dd9ebc35d08d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4f2c26ac2dc3cd5a5190845f6ea1aa4">visitHardInstr</a> (MachineInstr *, unsigned domain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A hard instruction only works in one domain. <a href="#af4f2c26ac2dc3cd5a5190845f6ea1aa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/specificbumpptrallocator">SpecificBumpPtrAllocator</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad57efbfcc86a44fdaccebab62edd7d21">Allocator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9b26ba6e924487d496ad64d201ed9fc">Avail</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71f4c2abb1abc62912cbea8715da04e5">RC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2dde57530820d1cffd1c6bc0c950c0e">MF</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetinstrinfo">TargetInstrInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16cbffbdd7e05ab58b34968371b2515e">TII</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a213e635a34296f752d449ca546a35e0a">TRI</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; int, 1 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5f1e2fcdcf23cbfde704f60450dec4e">AliasMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a44bc02029bdc1ef8fb82007db8605e">NumRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">LiveRegsDVInfo</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc059e613d50df38d2951e91f194ff09">LiveRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">OutRegsInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f3d3735964451a6b9a3ffa2ed8f2812">MBBOutRegsInfos</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/reachingdefanalysis">ReachingDefAnalysis</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed79c45b6858f755f2931c575626b3f">RDA</a> = nullptr</td>
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


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### LiveRegsDVInfo {#a29f50c014d318f7bd5391a8811537340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ExecutionDomainFix::LiveRegsDVInfo =  std::vector&lt;DomainValue *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> currently in each register, or NULL when no value is being tracked.</p>


<p>This counts as a <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> reference.</p>


<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### OutRegsInfoMap {#aa2e6cc750e2f33af7e57b6be3486fea1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::ExecutionDomainFix::OutRegsInfoMap =  SmallVector&lt;LiveRegsDVInfo, 4&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keeps domain information for all registers.</p>


<p>Note that this is different from the usual definition notion of liveness. The CPU doesn't care whether or not we consider a register killed.</p>


<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ExecutionDomainFix() {#a141030b45949448836e2a786e89ba216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ExecutionDomainFix::ExecutionDomainFix (char &amp; PassID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> &amp; RC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a29c81d2386f4a727c6d33413807530c8">llvm::MachineFunctionPass::MachineFunctionPass</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-armtargetmachine-cpp-/armexecutiondomainfix/#ac551188827dc9a9a97f0061938b113b9">anonymous{ARMTargetMachine.cpp}::ARMExecutionDomainFix::ARMExecutionDomainFix</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86targetmachine-cpp-/x86executiondomainfix/#a8ec6526dc54d92ef45d87c845b27c869">anonymous{X86TargetMachine.cpp}::X86ExecutionDomainFix::X86ExecutionDomainFix</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAnalysisUsage() {#a101879a381eb818b929145a3354575b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::ExecutionDomainFix::getAnalysisUsage (<a href="/web-llvm/docs/api/classes/llvm/analysisusage">AnalysisUsage</a> &amp;)</td>
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

<p>getAnalysisUsage - This function should be overriden by passes that need analysis information to do their job.</p>


<p>If a pass specifies that it uses a particular analysis result to this function, it can then use the <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">getAnalysis&lt;AnalysisType&gt;()</a> function, below.</p>


<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#ae0adcccca08fb686c9ce00f9397b660c">llvm::AnalysisUsage::addRequired</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionpass/#a864fd57b4304ef933b3281d0ef85a88e">llvm::MachineFunctionPass::getAnalysisUsage</a> and <a href="/web-llvm/docs/api/classes/llvm/analysisusage/#af22b06a6a4f9df80454071685a0d6a02">llvm::AnalysisUsage::setPreservesAll</a>.</p>

</div>
</div>

### getRequiredProperties() {#a26657d3f8a330b3b43c90710cdc98cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunctionProperties llvm::ExecutionDomainFix::getRequiredProperties ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a72f7d830dd5ddb30f06d8e9639558ac3">llvm::MachineFunctionProperties::NoVRegs</a> and <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#aa7780563d7ca260d0ae67d957b56427f">llvm::MachineFunctionProperties::set</a>.</p>

</div>
</div>

### runOnMachineFunction() {#aa90dd7f08ca467a5d6dc3215fb98ee51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ExecutionDomainFix::runOnMachineFunction (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
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

<p>runOnMachineFunction - This method must be overloaded to perform the desired machine code transformation or analysis.</p>

<p>Declaration at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 413 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/classes/llvm/pass/#a4863e5e463fb79955269fbf7fbf52b80">llvm::Pass::getAnalysis</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a977ddce262de45c645be23d951066351">llvm::MachineFunction::getFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/targetsubtargetinfo/#acd858ed72f11db9444617740c3622608">llvm::TargetSubtargetInfo::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#aa22424ba23740b6a748e8d0c239b7e4c">llvm::MachineFunction::getNumBlockIDs</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a810234b6b3d223b7c74a4253fcc5ea5e">llvm::MachineFunction::getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#a3825368aca2bc1550d173660df4da6a6">llvm::MachineFunction::getSubtarget</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregaliasiterator/#ac336c049c12ead7be5b86e6d046f8ab0">llvm::MCRegAliasIterator::isValid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64advsimdscalarpass-cpp/#aacd2ab195054a3e6a74bfbb9d5d571c8">MRI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a650dea4533083a886cec9f16d80356d9a123fead50246387983ee340507115ef4">llvm::release</a>, <a href="/web-llvm/docs/api/classes/llvm/functionpass/#af9f5f511d75e16f09a5520cb9444cfa8">llvm::FunctionPass::skipFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/looptraversal/#a87cd9704fc800af5dddb87f26badfb3a">llvm::LoopTraversal::traverse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### alloc() {#a1efd873c13e7037f49bc7ca26b2e4b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomainValue * ExecutionDomainFix::alloc (int domain=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> allocation.</p>

<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### collapse() {#af1401bd55ffdf7647dff0b5d9cbc92ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::collapse (<a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> * dv, unsigned domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collapse open <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> into given domain.</p>


<p>If there are multiple registers using dv, they each get a unique collapsed <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a>.</p>


<p>Declaration at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### enterBasicBlock() {#a73ebbcd41ae4ba16e860d985bb59c8ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::enterBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/looptraversal/traversedmbbinfo">LoopTraversal::TraversedMBBInfo</a> &amp; TraversedMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set up LiveRegs by merging predecessor live-out values.</p>

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### force() {#a64d238d8385deab7b4cd62450a3b2eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::force (int rx, unsigned domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Force register rx into domain.</p>

<p>Declaration at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### kill() {#afb991635b24d9344a48a3abbf8cc3283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::kill (int rx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kill register rx, recycle or collapse any <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a>.</p>

<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### leaveBasicBlock() {#a07eacb5daf93153c00a71a7ee0c54684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::leaveBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/looptraversal/traversedmbbinfo">LoopTraversal::TraversedMBBInfo</a> &amp; TraversedMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update live-out values.</p>

<p>Declaration at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### merge() {#a400099433f030ba48a87545288e89fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ExecutionDomainFix::merge (<a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> * A, <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> * B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All instructions and registers in B are moved to A, and B is released.</p>

<p>Declaration at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### processBasicBlock() {#a70ebfad844448c105d6354ee046e8fd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::processBasicBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/looptraversal/traversedmbbinfo">LoopTraversal::TraversedMBBInfo</a> &amp; TraversedMBB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/process">Process</a> he given basic block.</p>

<p>Declaration at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### processDefs() {#ac954eac09919ac86f73491d2fff582f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::processDefs (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI, bool Kill)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Update def-ages for registers defined by MI.</p>


<p>If Kill is set, also kill off DomainValues clobbered by the defs.</p>


<p>Declaration at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### regIndices() {#a24c67bf36c726ef85915a890ac0b64ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; SmallVectorImpl&lt; int &gt;::const_iterator &gt; ExecutionDomainFix::regIndices (unsigned Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Translate TRI register number to a list of indices into our smaller tables of interesting registers.</p>

<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### release() {#af0d16e49bab6bec162f627047e734f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::release (<a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> * DV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Release a reference to DV.</p>


<p>When the last reference is released, collapse if needed.</p>


<p>Declaration at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### resolve() {#ad96ee03ab1de2d3bf79bc76c1c640119}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomainValue * ExecutionDomainFix::resolve (<a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> *&amp; DVRef)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Follow the chain of dead DomainValues until a live <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> is reached.</p>


<p>Update the referenced pointer when necessary.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### retain() {#a0fdf6cfe6a3994a00b5ed44acf65df63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DomainValue * llvm::ExecutionDomainFix::retain (<a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> * DV)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add reference to DV.</p>

<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### setLiveReg() {#a1c6f9efac38759ed27b7b3751daf72c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::setLiveReg (int rx, <a href="/web-llvm/docs/api/structs/llvm/domainvalue">DomainValue</a> * DV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set LiveRegs[rx] = dv, updating reference counts.</p>

<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### visitHardInstr() {#af4f2c26ac2dc3cd5a5190845f6ea1aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::visitHardInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * mi, unsigned domain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A hard instruction only works in one domain.</p>


<p>All input registers will be forced into that domain.</p>


<p>Declaration at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### visitInstr() {#ac048d5afb6d98aef4e3f9bb3618ea0e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ExecutionDomainFix::visitInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Visit given insturcion.</p>

<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

### visitSoftInstr() {#a53321cb004793dde847dd9ebc35d08d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ExecutionDomainFix::visitSoftInstr (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * mi, unsigned mask)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A soft instruction can be changed to work in other domains given by mask.</p>

<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AliasMap {#af5f1e2fcdcf23cbfde704f60450dec4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SmallVector&lt;int, 1&gt; &gt; llvm::ExecutionDomainFix::AliasMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### Allocator {#ad57efbfcc86a44fdaccebab62edd7d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecificBumpPtrAllocator&lt;DomainValue&gt; llvm::ExecutionDomainFix::Allocator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### Avail {#ae9b26ba6e924487d496ad64d201ed9fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;DomainValue *, 16&gt; llvm::ExecutionDomainFix::Avail</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### LiveRegs {#afc059e613d50df38d2951e91f194ff09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LiveRegsDVInfo llvm::ExecutionDomainFix::LiveRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### MBBOutRegsInfos {#a3f3d3735964451a6b9a3ffa2ed8f2812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutRegsInfoMap llvm::ExecutionDomainFix::MBBOutRegsInfos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### MF {#ae2dde57530820d1cffd1c6bc0c950c0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::ExecutionDomainFix::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### NumRegs {#a6a44bc02029bdc1ef8fb82007db8605e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::ExecutionDomainFix::NumRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### RC {#a71f4c2abb1abc62912cbea8715da04e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterClass* const llvm::ExecutionDomainFix::RC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### RDA {#a3ed79c45b6858f755f2931c575626b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ReachingDefAnalysis* llvm::ExecutionDomainFix::RDA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### TII {#a16cbffbdd7e05ab58b34968371b2515e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::ExecutionDomainFix::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

### TRI {#a213e635a34296f752d449ca546a35e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::ExecutionDomainFix::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/executiondomainfix-h">ExecutionDomainFix.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/executiondomainfix-cpp">ExecutionDomainFix.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
