---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/targetregisterclass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TargetRegisterClass` Class



## Declaration

<div class="doxyDeclaration">
class llvm::TargetRegisterClass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">llvm/CodeGen/TargetRegisterInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54bad443892b02e3fc9ebd886e4e0110">iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc4e9a74fe208e78ff5260dded00a286">const_iterator</a> = <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> *</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a8b65536822d50171455a6baa81da7">getID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the register class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number. <a href="#a32a8b65536822d50171455a6baa81da7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a54bad443892b02e3fc9ebd886e4e0110">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae39f39f7451b8556a479efc27ad2a149">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>begin/end - Return all of the registers in this class. <a href="#ae39f39f7451b8556a479efc27ad2a149">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a54bad443892b02e3fc9ebd886e4e0110">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a881bc79908403b2d42dc1c4377e5cbb6">end</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a140a96e49ab5e53e99c3233291d98eb4">getNumRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of registers in this class. <a href="#a140a96e49ab5e53e99c3233291d98eb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a208148ec39e21c8c4591ad914e318dc9">getRegisters</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4cd0fd35859157ba99c4206679d3824">getRegister</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the specified register in the class. <a href="#ad4cd0fd35859157ba99c4206679d3824">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b6974966381f08079722f2258a0039">contains</a> (Register Reg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified register is included in this register class. <a href="#a60b6974966381f08079722f2258a0039">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0ccc3903ae5fedb32c51eb99d479ca">contains</a> (Register Reg1, Register Reg2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if both registers are in this class. <a href="#aca0ccc3903ae5fedb32c51eb99d479ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad81039a93caf12aa52e19c054223cd13">getCopyCost</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the cost of copying a value between two registers in this class. <a href="#ad81039a93caf12aa52e19c054223cd13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68b1cbd38847abc3e56eca6df316d5a1">isAllocatable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this register class may be used to create virtual registers. <a href="#a68b1cbd38847abc3e56eca6df316d5a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215a0b6b7d08f14e4710f35abf89f43c">isBaseClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this register class has a defined BaseClassOrder. <a href="#a215a0b6b7d08f14e4710f35abf89f43c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5870d927668bd2f44e70afa77ffdd4">hasSubClass</a> (const TargetRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> is a proper sub-class of this <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a>. <a href="#a9a5870d927668bd2f44e70afa77ffdd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ea8ce186fc4a70ad542e74d015d84ed">hasSubClassEq</a> (const TargetRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if RC is a sub-class of or equal to this class. <a href="#a8ea8ce186fc4a70ad542e74d015d84ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75138bd1bc4e6051fde2290ee928d12">hasSuperClass</a> (const TargetRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> is a proper super-class of this <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a>. <a href="#ac75138bd1bc4e6051fde2290ee928d12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee1c3236731101b249f6eeffd8cd7ba">hasSuperClassEq</a> (const TargetRegisterClass *RC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if RC is a super-class of or equal to this class. <a href="#abee1c3236731101b249f6eeffd8cd7ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf5c67f9a17117f6971d4341ef5018bf">getSubClassMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a bit vector of subclasses, including this one. <a href="#acf5c67f9a17117f6971d4341ef5018bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed851e5969d93eb6c2ea438566f7a10">getSuperRegIndices</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a 0-terminated list of sub-register indices that project some super-register class into this register class. <a href="#a2ed851e5969d93eb6c2ea438566f7a10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0cdee375c69ef697e465bb73f9c1db3">superclasses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a list of super-classes. <a href="#ab0cdee375c69ef697e465bb73f9c1db3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace997e272fac89816c54b98c69b118ee">isASubClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> is a subset class of at least one other <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a>. <a href="#ace997e272fac89816c54b98c69b118ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf6359290d600a6fbc13f6370dc45ba">getRawAllocationOrder</a> (const MachineFunction &amp;MF) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the preferred order for allocating registers from this register class in MF. <a href="#afbf6359290d600a6fbc13f6370dc45ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4b4e4e2660b0fcd4f92c1d35c29d1c0">getLaneMask</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the combination of all lane masks of register in this class. <a href="#ac4b4e4e2660b0fcd4f92c1d35c29d1c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcregisterclass">MCRegisterClass</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af73df27bcdf64385e1752f65741552fd">SubClassMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5d7f9c9e61be17dae283679fa67121a">SuperRegIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/lanebitmask">LaneBitmask</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0363c6cc08fe464f66f9e53239bb35e3">LaneMask</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad33e9f6afa3710617ba9cc7396209f4b">AllocationPriority</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Classes with a higher priority value are assigned first by register allocators using a greedy heuristic. <a href="#ad33e9f6afa3710617ba9cc7396209f4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d429efd1c7b47b6045ae08a72acfe4c">GlobalPriority</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc1ce48e42ab86c1419314bef07f00b">TSFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Configurable target specific flags. <a href="#a1cc1ce48e42ab86c1419314bef07f00b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f091eb46b984dbf525c6ac041f6af95">HasDisjunctSubRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the class supports two (or more) disjunct subregister indices. <a href="#a5f091eb46b984dbf525c6ac041f6af95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf30ddf5feeccddcf0e890fc9022ec4d">CoveredBySubRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether a combination of subregisters can cover every register in the class. <a href="#abf30ddf5feeccddcf0e890fc9022ec4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af33111ec1e4102ec047b72d21e5a674e">SuperClasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae53d97bc140470998e83df37d913a9b5">SuperClassesSize</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aad72cfbb210808985a9dc19f4e5d8542">MCPhysReg</a> &gt;(*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e33895453deb02809a3219a325c2312">OrderFunc</a>)(const MachineFunction &)</td>
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


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#abc4e9a74fe208e78ff5260dded00a286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetRegisterClass::const_iterator =  const MCPhysReg *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### iterator {#a54bad443892b02e3fc9ebd886e4e0110}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TargetRegisterClass::iterator =  const MCPhysReg *</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#ae39f39f7451b8556a479efc27ad2a149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::TargetRegisterClass::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>begin/end - Return all of the registers in this class.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a8688cc0d4d5620a54a1d45bd3087de1f">allocateSGPR32InputImpl</a>, <a href="#a208148ec39e21c8c4591ad914e318dc9">getRegisters</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa2b5a0a0f6bf1b5480337a01257df8b6">getRegistersForValue</a>.</p>

</div>
</div>

### contains() {#a60b6974966381f08079722f2258a0039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::contains (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified register is included in this register class.</p>


<p>This does not include virtual registers.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>References <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#aaf08c51751e9ec671a84a92af1daab99">addHints</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac9cfa172b885cad0eba3d7c9527568ad">llvm::MachineFunction::addLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a848f5b2d82a5d809fe4785b96e6bdb95">canFoldCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcinstrinfo/#aedcc57df983cf17bab675fab4233ac7d">llvm::PPCInstrInfo::ClobbersPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/virtregauxinfo/#a01fce66601f12ad1b3bd219ff02c3426">llvm::VirtRegAuxInfo::copyHint</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a6f318a4b1d38e66b324c0748304e60de">llvm::ARMBaseRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armframelowering-cpp/#a1a011d7a55ad214720e5e6765df6cf9d">estimateRSStackSizeLimit</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a96e06941b1694e3eb5cfd4efb2d69b59">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::foldOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a2666dab43798128db9f7c436090e2d64">llvm::R600InstrInfo::getIndirectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#a27574b6eff0c19ab7525347e22c22c27">llvm::M68kRegisterInfo::getMatchingMegaReg</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#a97c8d0c6028ffa258758bd49f68f2e28">llvm::M68kRegisterInfo::getMaximalPhysRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a69a2253decaa6ee31ae96ec6e0b3de13">llvm::AArch64RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#a7a7237cd5cb35f9159b32a96f4b14541">llvm::X86TargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a32193820add51ccf1ce4a89b83ea3cc8">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::IsRegInClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a37bd9fe42c1706827b1ae359aeb84c7e">llvm::rewriteT2FrameIndex</a>, <a href="/web-llvm/docs/api/classes/anonymous-loongarchdeadregisterdefinitions-cpp-/loongarchdeadregisterdefinitions/#a045d88b2cc0eb3d853b24e0f6a5904b2">anonymous{LoongArchDeadRegisterDefinitions.cpp}::LoongArchDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-riscvdeadregisterdefinitions-cpp-/riscvdeadregisterdefinitions/#ac2ca3a8531c6bdb17cc3908e3fbf10c4">anonymous{RISCVDeadRegisterDefinitions.cpp}::RISCVDeadRegisterDefinitions::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a>, <a href="/web-llvm/docs/api/structs/anonymous-armlowoverheadloops-cpp-/lowoverheadloop/#ad8272d1e2af6d68d30fbd619283a68c5">anonymous{ARMLowOverheadLoops.cpp}::LowOverheadLoop::ValidateLiveOuts</a> and <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#ab92b353cd5e64914fd35af38bb31e61b">llvm::SIInstrInfo::verifyInstruction</a>.</p>

</div>
</div>

### contains() {#aca0ccc3903ae5fedb32c51eb99d479ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::contains (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg1, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> Reg2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if both registers are in this class.</p>

<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/register/#a49effcc0d9e7a321043ade70145d11f6">llvm::Register::asMCReg</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#affdbf5b92ed7e01352e2f39466efbe21">llvm::Register::isPhysical</a> and <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>

</div>
</div>

### end() {#a881bc79908403b2d42dc1c4377e5cbb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::TargetRegisterClass::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp/#a43762e6a22fd0e7b98b8115946fc87b6">getRegistersForValue</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagbuilder-cpp/#aa2b5a0a0f6bf1b5480337a01257df8b6">getRegistersForValue</a>.</p>

</div>
</div>

### getCopyCost() {#ad81039a93caf12aa52e19c054223cd13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::TargetRegisterClass::getCopyCost ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the cost of copying a value between two registers in this class.</p>


<p>A negative number means the register class is very expensive to copy e.g. status flag register classes.</p>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagsdnodes-cpp/#a7d574da13bc65b93810a42059eada04f">CheckForPhysRegDependency</a> and <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a0e8adf21ba4a3e746edcd3b9cf9c5d14">llvm::SITargetLowering::checkForPhysRegDependency</a>.</p>

</div>
</div>

### getID() {#a32a8b65536822d50171455a6baa81da7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetRegisterClass::getID ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the register class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> number.</p>

<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/regsforvalue/#a73e723a22ad556552ca99f7e7a90a780">llvm::RegsForValue::AddInlineAsmOperands</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a82ef22a357f6b3f17e77b598df0ca45f">llvm::HexagonEvaluator::composeWithSubRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/registerbank/#aa0393eeb48bb9235b4fc40b19ebb52f1">llvm::RegisterBank::covers</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a878a2b864e18e3d074d75b426ea7912d">llvm::HexagonFrameLowering::determineCalleeSaves</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a639a1e437b7586350b87cae4556342c2">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::dumpRegPressure</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa5ee374b5dd8bd37ca7876c4bfb24bbf">llvm::SITargetLowering::finalizeLowering</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#afb719bff41b5688bcd0e39208d11677f">llvm::HexagonRegisterInfo::getCallerSavedRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/webassembly/#a401b0a43069b4766865e9e83de7deb16">llvm::WebAssembly::getCopyOpcodeForRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/scheduledagrrlist-cpp/#a75eb4d99ebf26777f16034567505166b">GetCostForDef</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a8e3ebf47bfdde7c6ce8235ca71190e1b">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getFinalVRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8528b1c4543692486b82ac9012c1617b">llvm::HexagonRegisterInfo::getHexagonSubRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a7d9301f2db70078a258c683a1046f569">llvm::ARMBaseRegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerbankinfo/#a764ae29d6f969d21006942e066524217">llvm::AArch64RegisterBankInfo::getRegBankFromRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterbankinfo/#a5a6ede71870e0137cd31b2bde6d6e4ba">llvm::PPCRegisterBankInfo::getRegBankFromRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvregisterbankinfo/#a94d762edf9ac2168b4ab17b05f23e074">llvm::SPIRVRegisterBankInfo::getRegBankFromRegClass</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#acc8a2c40a5d623bd8c7c28e93eda91d3">llvm::AMDGPU::getRegBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a852a4600d4487849a5c8e3d08ca3fddd">llvm::TargetRegisterInfo::getRegClassInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a686453b777e5e7540ba688dc84fd4733">llvm::AArch64RegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#afe522c5b4605ba12fa3167e7959b6645">llvm::ARMBaseRegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsregisterinfo/#a456c98e104fefc660add08150cc6c794">llvm::MipsRegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#ab0d7ef2c34f8283a7ae1891dbe6a9321">llvm::PPCRegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#aa7dbd22ec4e0cc058f8290a8b98cacc6">llvm::SIRegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a9808d4e58aafe6a0fd4d14673ee4c4e0">llvm::X86RegisterInfo::getRegPressureLimit</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/hexagonbitsimplify/#a645204801c7cc2848635065d0331dffd">anonymous{HexagonBitSimplify.cpp}::HexagonBitSimplify::getSubregMask</a>, <a href="#a8ea8ce186fc4a70ad542e74d015d84ed">hasSubClassEq</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonpeephole-cpp/#a75858997548ce7f9cc07ce26843356c6">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a597d9711362d4d496b01d4cf2df66009">llvm::X86RegisterInfo::isTileRegisterClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/mvetpandvptoptimisationspass-cpp/#ab527804ff82cb87d1229cbec56e95778">IsWritingToVCCR</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasmlowering/#a1c9cd272afbe2a9aaca46369f9e61b79">llvm::InlineAsmLowering::lowerInlineAsm</a>, <a href="/web-llvm/docs/api/structs/llvm/hexagonevaluator/#a26c72fb657ffaea1a961279c6d3a80fb">llvm::HexagonEvaluator::mask</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonbitsimplify-cpp-/bitsimplification/#a7ae2252105ba3f43b639d6648a219a85">anonymous{HexagonBitSimplify.cpp}::BitSimplification::processBlock</a>, <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a39e19835bf722b3340acfce2e69f6c08">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::RegReductionPQBase</a>, <a href="/web-llvm/docs/api/classes/llvm/resourcepriorityqueue/#a0ad9cbe1a5bd1eb9d026fc0e91fab117">llvm::ResourcePriorityQueue::scheduledNode</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpudagtodagisel/#a4e1374fde17218f949e94ee57e18dc2c">llvm::AMDGPUDAGToDAGISel::Select</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64iseldagtodag-cpp-/aarch64dagtodagisel/#a2d3135a3679a9bf0460e25b9d03f9298">anonymous{AArch64ISelDAGToDAG.cpp}::AArch64DAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppciseldagtodag-cpp-/ppcdagtodagisel/#a6182598aaa3c33b0c1e4eb1f7b1ce870">anonymous{PPCISelDAGToDAG.cpp}::PPCDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a541773af1ff4cbdfa6782d6d45e42d78">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::SelectInlineAsmMemoryOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a472cefd8107362b99710b1e58174b7a0">llvm::AArch64RegisterInfo::shouldCoalesce</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8a7cb54f8347286b106be184c8c125e1">llvm::HexagonRegisterInfo::shouldCoalesce</a> and <a href="/web-llvm/docs/api/classes/anonymous-scheduledagrrlist-cpp-/regreductionpqbase/#a94317da8cf8f9c0cfd21c1af6c9ed449">anonymous{ScheduleDAGRRList.cpp}::RegReductionPQBase::unscheduledNode</a>.</p>

</div>
</div>

### getLaneMask() {#ac4b4e4e2660b0fcd4f92c1d35c29d1c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LaneBitmask llvm::TargetRegisterClass::getLaneMask ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the combination of all lane masks of register in this class.</p>


<p>The lane masks of the registers are the combination of all lane masks of their subregisters. Returns 1 if there are no subregisters.</p>


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#a0363c6cc08fe464f66f9e53239bb35e3">LaneMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a643ff7dd8c287dd58e75cbe79556e74c">llvm::ScheduleDAGInstrs::getLaneMaskForMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#ab7e720f69b70ef3973d672936a9fa0ec">llvm::MachineRegisterInfo::getMaxLaneMaskForVReg</a>.</p>

</div>
</div>

### getNumRegs() {#a140a96e49ab5e53e99c3233291d98eb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::TargetRegisterClass::getNumRegs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of registers in this class.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo/#afbb05388c505418c42219ea66ada4cc5">llvm::RegisterClassInfo::computePSetLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineregisterinfo-cpp/#afdf1630cc583964ae0b965eb5ec72797">constrainRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a2666dab43798128db9f7c436090e2d64">llvm::R600InstrInfo::getIndirectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#a97c8d0c6028ffa258758bd49f68f2e28">llvm::M68kRegisterInfo::getMaximalPhysRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#aafb84ed6261a1ce9b994d8542f5fd83a">llvm::M68kRegisterInfo::getRegisterOrder</a>, <a href="#a208148ec39e21c8c4591ad914e318dc9">getRegisters</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86pretileconfig-cpp-/x86pretileconfig/#a5d1d05840235d52ee7fb4b0ce9a63b76">anonymous{X86PreTileConfig.cpp}::X86PreTileConfig::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>.</p>

</div>
</div>

### getRawAllocationOrder() {#afbf6359290d600a6fbc13f6370dc45ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; llvm::TargetRegisterClass::getRawAllocationOrder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the preferred order for allocating registers from this register class in MF.</p>


<p>The raw order comes directly from the .td file and may include reserved registers that are not allocatable. <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> allocators should also make sure to allocate callee-saved registers only after all the volatiles are used. The <a href="/web-llvm/docs/api/classes/llvm/registerclassinfo">RegisterClassInfo</a> class provides filtered allocation orders with callee-saved registers moved to the end.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> argument can be used to tune the allocatable registers based on the characteristics of the function, subtarget, or other criteria.</p>


<p>By default, this method returns all registers in the class.</p>


<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>References <a href="#a208148ec39e21c8c4591ad914e318dc9">getRegisters</a> and <a href="#a7e33895453deb02809a3219a325c2312">OrderFunc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#a5e3d92b49e8116d3df7c9264615e2d2d">getAllocatableSetForRC</a> and <a href="/web-llvm/docs/api/classes/llvm/regscavenger/#a62d08c8303092539ecb1fde389108e7a">llvm::RegScavenger::scavengeRegisterBackwards</a>.</p>

</div>
</div>

### getRegister() {#ad4cd0fd35859157ba99c4206679d3824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::TargetRegisterClass::getRegister (unsigned i)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the specified register in the class.</p>

<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/r600instrinfo/#a2666dab43798128db9f7c436090e2d64">llvm::R600InstrInfo::getIndirectIndexBegin</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a5f39e10469c6e4a18135aed5e76cddf5">llvm::SITargetLowering::getRegForInlineAsmConstraint</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#aafb84ed6261a1ce9b994d8542f5fd83a">llvm::M68kRegisterInfo::getRegisterOrder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a66436eae766ca32356bb075ec31ac449">llvm::tryFoldSPUpdateIntoPushPop</a>.</p>

</div>
</div>

### getRegisters() {#a208148ec39e21c8c4591ad914e318dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt; llvm::TargetRegisterClass::getRegisters ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#ae39f39f7451b8556a479efc27ad2a149">begin</a> and <a href="#a140a96e49ab5e53e99c3233291d98eb4">getNumRegs</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/simachinefunctioninfo/#a592045324d9ab5a208ce36932f3a7c2d">llvm::SIMachineFunctionInfo::allocateVGPRSpillToAGPR</a>, <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a1558554539a5b133b8e361c0517e9fb1">llvm::RegAllocBase::getErrorAssignment</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a7435cc0e3ba036d3183793e46cdee546">llvm::SIRegisterInfo::getNumUsedPhysRegs</a> and <a href="#afbf6359290d600a6fbc13f6370dc45ba">getRawAllocationOrder</a>.</p>

</div>
</div>

### getSubClassMask() {#acf5c67f9a17117f6971d4341ef5018bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t * llvm::TargetRegisterClass::getSubClassMask ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a bit vector of subclasses, including this one.</p>


<p>The vector is indexed by class IDs.</p>


<p>To use it, consider the returned array as a chunk of memory that contains an array of bits of size NumRegClasses. Each 32-bit chunk contains a bitset of the <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> of the subclasses in big-endian style. I.e., the representation of the memory from left to right at the bit level looks like: [31 30 ... 1 0] [ 63 62 ... 33 32] ... [ XXX NumRegClasses NumRegClasses - 1 ... ] Where the number represents the class <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and XXX bits that should be ignored.</p>


<p>See the implementation of hasSubClassEq for an example of how it can be used.</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#af73df27bcdf64385e1752f65741552fd">SubClassMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a91c8fd7879e62b4a76d8c23ecef7ef23">llvm::TargetRegisterInfo::getAllocatableClass</a>.</p>

</div>
</div>

### getSuperRegIndices() {#a2ed851e5969d93eb6c2ea438566f7a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t * llvm::TargetRegisterClass::getSuperRegIndices ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a 0-terminated list of sub-register indices that project some super-register class into this register class.</p>


<p>The list has an entry for each Idx such that:</p>


<p>There exists SuperRC where: For all Reg in SuperRC: this-&gt;contains(Reg:Idx)</p>


<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab5d7f9c9e61be17dae283679fa67121a">SuperRegIndices</a>.</p>

</div>
</div>

### hasSubClass() {#a9a5870d927668bd2f44e70afa77ffdd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::hasSubClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> is a proper sub-class of this <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a>.</p>

<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#a8ea8ce186fc4a70ad542e74d015d84ed">hasSubClassEq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#ac2edf0373e31245fe6691d49c4274f2e">getCommonMinimalPhysRegClass</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#a97c8d0c6028ffa258758bd49f68f2e28">llvm::M68kRegisterInfo::getMaximalPhysRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#a3d384230ab441fc0da0f899122f07b4e">getMinimalPhysRegClass</a> and <a href="#ac75138bd1bc4e6051fde2290ee928d12">hasSuperClass</a>.</p>

</div>
</div>

### hasSubClassEq() {#a8ea8ce186fc4a70ad542e74d015d84ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::hasSubClassEq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if RC is a sub-class of or equal to this class.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>References <a href="#a32a8b65536822d50171455a6baa81da7">getID</a> and <a href="#af73df27bcdf64385e1752f65741552fd">SubClassMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac9cfa172b885cad0eba3d7c9527568ad">llvm::MachineFunction::addLiveIn</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetinstrinfo-cpp/#a848f5b2d82a5d809fe4785b96e6bdb95">canFoldCopy</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a0e83ecd12d46c80703ce5d3ef34ead33">llvm::SIRegisterInfo::getCompatibleSubRegClass</a>, <a href="#a9a5870d927668bd2f44e70afa77ffdd4">hasSubClass</a>, <a href="#abee1c3236731101b249f6eeffd8cd7ba">hasSuperClassEq</a>, <a href="/web-llvm/docs/api/structs/anonymous-ppcvsxcopy-cpp-/ppcvsxcopy/#a32193820add51ccf1ce4a89b83ea3cc8">anonymous{PPCVSXCopy.cpp}::PPCVSXCopy::IsRegInClass</a>, <a href="/web-llvm/docs/api/classes/anonymous-sifoldoperands-cpp-/sifoldoperandsimpl/#a17772fd1beeccd740ec6412abad098f9">anonymous{SIFoldOperands.cpp}::SIFoldOperandsImpl::tryFoldPhiAGPR</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#a77dea00ee37a964ad5edf6072fb35071">UpdateOperandRegClass</a> and <a href="/web-llvm/docs/api/classes/llvm/registerbank/#a29b158112720b57e5aa9898944c69330">llvm::RegisterBank::verify</a>.</p>

</div>
</div>

### hasSuperClass() {#ac75138bd1bc4e6051fde2290ee928d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::hasSuperClass (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> is a proper super-class of this <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a>.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#a9a5870d927668bd2f44e70afa77ffdd4">hasSubClass</a>.</p>

</div>
</div>

### hasSuperClassEq() {#abee1c3236731101b249f6eeffd8cd7ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::hasSuperClassEq (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if RC is a super-class of or equal to this class.</p>

<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#a8ea8ce186fc4a70ad542e74d015d84ed">hasSubClassEq</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#a10b62cdcfa9a6e59de1c621f7aae8747">llvm::AArch64InstrInfo::emitLdStWithAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#aba962e46a3ab42206182058420cb876f">llvm::SIInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a811049dc54f4a8053c0b34c8fa470a99">isFRClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0ae9685e0bfae51cfb048c3a2da8a06f">isGRClass</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#abecccbf97c3a9d0be384e6c639fcf2dc">llvm::SIInstrInfo::isLegalRegOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a2adf69ba524926c5454f5d259c1c4dac">llvm::SIRegisterInfo::isProperlyAlignedRC</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a67e06f2d863f883613cc60086eb26493">isVKClass</a>, <a href="/web-llvm/docs/api/classes/llvm/thumb1instrinfo/#a1eeb397bafd16951ce8898c83f21c5e4">llvm::Thumb1InstrInfo::loadRegFromStackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/siinstrinfo/#a9fac55ed154a25a20608a5f71dc833c0">llvm::SIInstrInfo::materializeImmediate</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#ade724427f9c92b975072767cdcfd45ec">llvm::SystemZRegisterInfo::shouldCoalesce</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#aa1da2564961dc226cc06c5c95d9a603d">llvm::X86RegisterInfo::shouldRewriteCopySrc</a> and <a href="/web-llvm/docs/api/structs/anonymous-machineverifier-cpp-/machineverifier/#a16957e467c8bf1aa4c3c8614d7315709">anonymous{MachineVerifier.cpp}::MachineVerifier::visitMachineOperand</a>.</p>

</div>
</div>

### isAllocatable() {#a68b1cbd38847abc3e56eca6df316d5a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::isAllocatable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this register class may be used to create virtual registers.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a5c77792a06583e0fe7a0379ad94a2809">llvm::MachineRegisterInfo::createVirtualRegister</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#a91c8fd7879e62b4a76d8c23ecef7ef23">llvm::TargetRegisterInfo::getAllocatableClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetregisterinfo-cpp/#a5e3d92b49e8116d3df7c9264615e2d2d">getAllocatableSetForRC</a> and <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a965a15cef77a97f0e17f9f26fd5be53e">llvm::MachineRegisterInfo::setRegClass</a>.</p>

</div>
</div>

### isASubClass() {#ace997e272fac89816c54b98c69b118ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::isASubClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> is a subset class of at least one other <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a>.</p>

<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#af33111ec1e4102ec047b72d21e5a674e">SuperClasses</a>.</p>

</div>
</div>

### isBaseClass() {#a215a0b6b7d08f14e4710f35abf89f43c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TargetRegisterClass::isBaseClass ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this register class has a defined BaseClassOrder.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Reference <a href="#ab67affb87d0ac718bdda5ebe40a7327d">MC</a>.</p>

</div>
</div>

### superclasses() {#ab0cdee375c69ef697e465bb73f9c1db3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; unsigned &gt; llvm::TargetRegisterClass::superclasses ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a list of super-classes.</p>


<p>The classes are ordered by <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> which is also a topological ordering from large to small classes. The list does NOT include the current class.</p>


<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#af33111ec1e4102ec047b72d21e5a674e">SuperClasses</a> and <a href="#ae53d97bc140470998e83df37d913a9b5">SuperClassesSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hexagonregisterinfo/#a8528b1c4543692486b82ac9012c1617b">llvm::HexagonRegisterInfo::getHexagonSubRegIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a7d9301f2db70078a258c683a1046f569">llvm::ARMBaseRegisterInfo::getLargestLegalSuperClass</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#aef6a94b763376e95e861f14451a12d5b">llvm::PPCRegisterInfo::getLargestLegalSuperClass</a> and <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a842441ec6290263363da4edef875b5c5">llvm::X86RegisterInfo::getLargestLegalSuperClass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocationPriority {#ad33e9f6afa3710617ba9cc7396209f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::TargetRegisterClass::AllocationPriority</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Classes with a higher priority value are assigned first by register allocators using a greedy heuristic.</p>


<p>The value is in the range [0,31].</p>


<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### CoveredBySubRegs {#abf30ddf5feeccddcf0e890fc9022ec4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::TargetRegisterClass::CoveredBySubRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether a combination of subregisters can cover every register in the class.</p>


<p>See also the CoveredBySubRegs description in Target.td.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/deadlanedetector/#a0507a9e0fb3ad8b5cbe21a6f19c8714c">llvm::DeadLaneDetector::transferUsedLanes</a>.</p>

</div>
</div>

### GlobalPriority {#a9d429efd1c7b47b6045ae08a72acfe4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::TargetRegisterClass::GlobalPriority</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>

</div>
</div>

### HasDisjunctSubRegs {#a5f091eb46b984dbf525c6ac041f6af95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const bool llvm::TargetRegisterClass::HasDisjunctSubRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether the class supports two (or more) disjunct subregister indices.</p>

<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scheduledaginstrs/#a643ff7dd8c287dd58e75cbe79556e74c">llvm::ScheduleDAGInstrs::getLaneMaskForMO</a> and <a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo/#a7f2602cf77af82396115293302557ee0">llvm::MachineRegisterInfo::shouldTrackSubRegLiveness</a>.</p>

</div>
</div>

### LaneMask {#a0363c6cc08fe464f66f9e53239bb35e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const LaneBitmask llvm::TargetRegisterClass::LaneMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ac4b4e4e2660b0fcd4f92c1d35c29d1c0">getLaneMask</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/physicalregisterinfo/#ab895a9e549543404ea829bb14f6162c1">llvm::rdf::PhysicalRegisterInfo::mapTo</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/copypropagation/#ab5cc393f3a921f0a6fe0505561a80e23">llvm::rdf::CopyPropagation::run</a> and <a href="/web-llvm/docs/api/classes/llvm/deadlanedetector/#a0507a9e0fb3ad8b5cbe21a6f19c8714c">llvm::DeadLaneDetector::transferUsedLanes</a>.</p>

</div>
</div>

### MC {#ab67affb87d0ac718bdda5ebe40a7327d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCRegisterClass* llvm::TargetRegisterClass::MC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ae39f39f7451b8556a479efc27ad2a149">begin</a>, <a href="#a60b6974966381f08079722f2258a0039">contains</a>, <a href="#aca0ccc3903ae5fedb32c51eb99d479ca">contains</a>, <a href="#a881bc79908403b2d42dc1c4377e5cbb6">end</a>, <a href="#ad81039a93caf12aa52e19c054223cd13">getCopyCost</a>, <a href="#a32a8b65536822d50171455a6baa81da7">getID</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#aa5aad3f9195b1fd331f449ce9a709da2">llvm::TargetRegisterInfo::getMatchingSuperReg</a>, <a href="#a140a96e49ab5e53e99c3233291d98eb4">getNumRegs</a>, <a href="#ad4cd0fd35859157ba99c4206679d3824">getRegister</a>, <a href="#a68b1cbd38847abc3e56eca6df316d5a1">isAllocatable</a>, <a href="#a215a0b6b7d08f14e4710f35abf89f43c">isBaseClass</a> and <a href="/web-llvm/docs/api/classes/anonymous-gcnpreraoptimizations-cpp-/gcnpreraoptimizations/#a579b1d5abab1d9f7ada407f49d3a56a1">anonymous{GCNPreRAOptimizations.cpp}::GCNPreRAOptimizations::runOnMachineFunction</a>.</p>

</div>
</div>

### OrderFunc {#a7e33895453deb02809a3219a325c2312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; MCPhysReg &gt;(* llvm::TargetRegisterClass::OrderFunc) (const MachineFunction &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#afbf6359290d600a6fbc13f6370dc45ba">getRawAllocationOrder</a>.</p>

</div>
</div>

### SubClassMask {#af73df27bcdf64385e1752f65741552fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t* llvm::TargetRegisterClass::SubClassMask</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#acf5c67f9a17117f6971d4341ef5018bf">getSubClassMask</a> and <a href="#a8ea8ce186fc4a70ad542e74d015d84ed">hasSubClassEq</a>.</p>

</div>
</div>

### SuperClasses {#af33111ec1e4102ec047b72d21e5a674e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned* llvm::TargetRegisterClass::SuperClasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ace997e272fac89816c54b98c69b118ee">isASubClass</a> and <a href="#ab0cdee375c69ef697e465bb73f9c1db3">superclasses</a>.</p>

</div>
</div>

### SuperClassesSize {#ae53d97bc140470998e83df37d913a9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t llvm::TargetRegisterClass::SuperClassesSize</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#ab0cdee375c69ef697e465bb73f9c1db3">superclasses</a>.</p>

</div>
</div>

### SuperRegIndices {#ab5d7f9c9e61be17dae283679fa67121a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint16_t* llvm::TargetRegisterClass::SuperRegIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="#a2ed851e5969d93eb6c2ea438566f7a10">getSuperRegIndices</a>.</p>

</div>
</div>

### TSFlags {#a1cc1ce48e42ab86c1419314bef07f00b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t llvm::TargetRegisterClass::TSFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Configurable target specific flags.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvinstrinfo/#a436965f98f9e4301e33096c32ed6dbd2">llvm::RISCVInstrInfo::copyPhysRegVector</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#af3b7e264a1a447b652821dae53bb1993">llvm::SIRegisterInfo::getRegClassAlignmentNumBits</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae24a21441afe482d6119ffa30efc33c1">llvm::SIRegisterInfo::getSubRegAlignmentNumBits</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae1364aa9eb8390d678c037be69450deb">llvm::SIRegisterInfo::hasAGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#ae2b17b04c6d4d3b578c7ba3497652df4">llvm::SIRegisterInfo::hasSGPRs</a>, <a href="/web-llvm/docs/api/classes/llvm/siregisterinfo/#a8cb8776ee5f539fe6391a6d521af25f1">llvm::SIRegisterInfo::hasVGPRs</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a6b0e6be6a451881260fcd7f29b7fb4fc">llvm::RISCVRegisterInfo::isRVVRegClass</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvvloptimizer-cpp/#aa7416d4f582d65182fdc05986c346f95">isVectorRegClass</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#a332bd6d18c6843b98cd5638ed6516bf1">llvm::RISCVRegisterInfo::isVRNRegClass</a> and <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#acbb4c61a970c46bace27495c19538ac5">llvm::RISCVRegisterInfo::isVRRegClass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/targetregisterinfo-h">TargetRegisterInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
