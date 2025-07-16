---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/virtregmap
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VirtRegMap` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::VirtRegMap { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">llvm/CodeGen/VirtRegMap.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69fa879a33a59f14ca440c7ec9669a38">VirtRegMap</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9017e7efa287f0d78d5072d2a26e9913">VirtRegMap</a> (const VirtRegMap &amp;)=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8479febdfe5f9093009aecb7d0fae952">VirtRegMap</a> (VirtRegMap &amp;&amp;)=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf00a08991767e88031193592a29ab85">operator=</a> (const VirtRegMap &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a06f2509b5f901646c6498e9a0e8d4f">init</a> (MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7619711af4bb95253dea3e0783400f26">getMachineFunction</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b03bffeedbff2a86dfe427fd90c1465">getRegInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo">TargetRegisterInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb16c0664049f377c9ff542829013a75">getTargetRegInfo</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d5afab2fece1568139a0c2784f0e481">grow</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab28bf4ffd3e2223dab0527c9d7e18288">hasPhys</a> (Register virtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns true if the specified virtual register is mapped to a physical register <a href="#ab28bf4ffd3e2223dab0527c9d7e18288">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a785a4e2daf4e5bf3f0836adbc4fb7e65">getPhys</a> (Register virtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the physical register mapped to the specified virtual register <a href="#a785a4e2daf4e5bf3f0836adbc4fb7e65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7483a2fa0354b8fa3298ab99f41ce0d4">assignVirt2Phys</a> (Register virtReg, MCRegister physReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>creates a mapping for the specified virtual register to the specified physical register <a href="#a7483a2fa0354b8fa3298ab99f41ce0d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0653b6b211a32dda8152d3177e11aa4">isShapeMapEmpty</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d1e9b1a4148131fa20946943f7b1449">hasShape</a> (Register virtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/shapet">ShapeT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bdec6932a16e4d542bd8773fcb50acb">getShape</a> (Register virtReg) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac75c4794d822351e963610133d4dc701">assignVirt2Shape</a> (Register virtReg, ShapeT shape)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d25688d9c61100ba6a5dea48771ecde">clearVirt</a> (Register virtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clears the specified virtual register's, physical register mapping <a href="#a2d25688d9c61100ba6a5dea48771ecde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ab2e8cafc507db705e2eeae719ae5c">clearAllVirt</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clears all virtual to physical register mappings <a href="#a35ab2e8cafc507db705e2eeae719ae5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af3414dbf16e5eb1b862c7cf35ed83c">hasPreferredPhys</a> (Register VirtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns true if VirtReg is assigned to its preferred physreg. <a href="#a4af3414dbf16e5eb1b862c7cf35ed83c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a103071c94c9a366fd2d96f5953871dde">hasKnownPreference</a> (Register VirtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns true if VirtReg has a known preferred register. <a href="#a103071c94c9a366fd2d96f5953871dde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b7b231e8677fb4c83572d6f4bedaa1">setIsSplitFromReg</a> (Register virtReg, Register SReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>records virtReg is a split live interval from SReg. <a href="#a37b7b231e8677fb4c83572d6f4bedaa1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582c4d764e37313a1bc6dff1a727e752">getPreSplitReg</a> (Register virtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the live interval virtReg is split from. <a href="#a582c4d764e37313a1bc6dff1a727e752">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d88862090bbf71af421aacae8f12866">getOriginal</a> (Register VirtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getOriginal - Return the original virtual register that VirtReg descends from through splitting. <a href="#a4d88862090bbf71af421aacae8f12866">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0df6033e4012261f7531e62274cf99c">isAssignedReg</a> (Register virtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns true if the specified virtual register is not mapped to a stack slot or rematerialized. <a href="#ad0df6033e4012261f7531e62274cf99c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32846fd2d98022e7b336962f85411a42">getStackSlot</a> (Register virtReg) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns the stack slot mapped to the specified virtual register <a href="#a32846fd2d98022e7b336962f85411a42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae60b2416ed4d106a241c6874c1992d">assignVirt2StackSlot</a> (Register virtReg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>create a mapping for the specifed virtual register to the next available stack slot <a href="#a1ae60b2416ed4d106a241c6874c1992d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9636d75b520f38c5860a95791331c8">assignVirt2StackSlot</a> (Register virtReg, int SS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>create a mapping for the specified virtual register to the specified stack slot <a href="#aff9636d75b520f38c5860a95791331c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa4b2ab2c4e30ebbb80c8384dc9ddd3">print</a> (raw_ostream &amp;OS, const Module *M=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570cc2ad4630f9e1adf4576e36507449">dump</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52608652809dc40da1201f892fb8a3e2">createSpillSlot</a> (const TargetRegisterClass *RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>createSpillSlot - Allocate a spill slot for RC from MFI. <a href="#a52608652809dc40da1201f892fb8a3e2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineregisterinfo">MachineRegisterInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a835c8be6a08721f11b0f0bfa93486af5">MRI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e6a853f888cc11e0124b767dc4ae1b">TII</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac280e5ca437a716279a2854979b1e2e1">TRI</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f0b2088961d71501e812a59ee31d9eb">MF</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a490f5b16e0234a997c467f91d377b09d">Virt2PhysMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virt2PhysMap - This is a virtual to physical register mapping. <a href="#a490f5b16e0234a997c467f91d377b09d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; int, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1684e154e59fbd59d0c7ac7291ecf5c">Virt2StackSlotMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virt2StackSlotMap - This is virtual register to stack slot mapping. <a href="#ab1684e154e59fbd59d0c7ac7291ecf5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/indexedmap">IndexedMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/structs/llvm/virtreg2indexfunctor">VirtReg2IndexFunctor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4805378b31b0716a1aea9b44ecaa32">Virt2SplitMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virt2SplitMap - This is virtual register to splitted virtual register mapping. <a href="#adf4805378b31b0716a1aea9b44ecaa32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, <a href="/web-llvm/docs/api/classes/llvm/shapet">ShapeT</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7400fd988e94da51a93c7d7685cad13b">Virt2ShapeMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Virt2ShapeMap - For <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> AMX register whose register is bound shape information. <a href="#a7400fd988e94da51a93c7d7685cad13b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2e99ae080aa934d64b0ff504dab0158">NO_STACK_SLOT</a> = INT_MAX</td>
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


<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### VirtRegMap() {#a69fa879a33a59f14ca440c7ec9669a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VirtRegMap::VirtRegMap ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Reference <a href="#ad2e99ae080aa934d64b0ff504dab0158">NO_STACK_SLOT</a>.</p>


<p>Referenced by <a href="#adf00a08991767e88031193592a29ab85">operator=</a>, <a href="#a9017e7efa287f0d78d5072d2a26e9913">VirtRegMap</a> and <a href="#a8479febdfe5f9093009aecb7d0fae952">VirtRegMap</a>.</p>

</div>
</div>

### VirtRegMap() {#a9017e7efa287f0d78d5072d2a26e9913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VirtRegMap::VirtRegMap (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Reference <a href="#a69fa879a33a59f14ca440c7ec9669a38">VirtRegMap</a>.</p>

</div>
</div>

### VirtRegMap() {#a8479febdfe5f9093009aecb7d0fae952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::VirtRegMap::VirtRegMap (<a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Reference <a href="#a69fa879a33a59f14ca440c7ec9669a38">VirtRegMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#adf00a08991767e88031193592a29ab85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VirtRegMap &amp; llvm::VirtRegMap::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/virtregmap">VirtRegMap</a> &amp;)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Reference <a href="#a69fa879a33a59f14ca440c7ec9669a38">VirtRegMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignVirt2Phys() {#a7483a2fa0354b8fa3298ab99f41ce0d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VirtRegMap::assignVirt2Phys (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg, <a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> physReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>creates a mapping for the specified virtual register to the specified physical register</p>

<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunctionproperties/#ad85237c6c667e4713efe8921e9c32ac1a84c7a981b331eae0f00669f3775ab3ca">llvm::MachineFunctionProperties::FailedRegAlloc</a>, <a href="#a5b03bffeedbff2a86dfe427fd90c1465">getRegInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mcregister/#adab6a6e130a565c2cb11ef465fac90e7">llvm::MCRegister::isPhysical</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>

</div>
</div>

### assignVirt2Shape() {#ac75c4794d822351e963610133d4dc701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VirtRegMap::assignVirt2Shape (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg, <a href="/web-llvm/docs/api/classes/llvm/shapet">ShapeT</a> shape)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86registerinfo-cpp/#aec0d8323ad306042f2eef8a2c5978162">getTileShape</a>.</p>

</div>
</div>

### assignVirt2StackSlot() {#a1ae60b2416ed4d106a241c6874c1992d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VirtRegMap::assignVirt2StackSlot (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>create a mapping for the specifed virtual register to the next available stack slot</p>

<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="#ad2e99ae080aa934d64b0ff504dab0158">NO_STACK_SLOT</a>.</p>

</div>
</div>

### assignVirt2StackSlot() {#aff9636d75b520f38c5860a95791331c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VirtRegMap::assignVirt2StackSlot (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg, int SS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>create a mapping for the specified virtual register to the specified stack slot</p>

<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="#ad2e99ae080aa934d64b0ff504dab0158">NO_STACK_SLOT</a>.</p>

</div>
</div>

### clearAllVirt() {#a35ab2e8cafc507db705e2eeae719ae5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VirtRegMap::clearAllVirt ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clears all virtual to physical register mappings</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Reference <a href="#a8d5afab2fece1568139a0c2784f0e481">grow</a>.</p>

</div>
</div>

### clearVirt() {#a2d25688d9c61100ba6a5dea48771ecde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VirtRegMap::clearVirt (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clears the specified virtual register's, physical register mapping</p>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>

</div>
</div>

### dump() {#a570cc2ad4630f9e1adf4576e36507449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void VirtRegMap::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#a7fa4b2ab2c4e30ebbb80c8384dc9ddd3">print</a>.</p>

</div>
</div>

### getMachineFunction() {#a7619711af4bb95253dea3e0783400f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction &amp; llvm::VirtRegMap::getMachineFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a1d17986988f0819f29d78d1be8555c9e">llvm::AllocationOrder::create</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#a38c76eebc11caaa9225a4bfe146585a6">anonymous{LiveDebugVariables.cpp}::UserValue::emitDebugValues</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a2e9547b9bc56b02aad18e54488c8059b">llvm::RegAllocBase::init</a>.</p>

</div>
</div>

### getOriginal() {#a4d88862090bbf71af421aacae8f12866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::VirtRegMap::getOriginal (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getOriginal - Return the original virtual register that VirtReg descends from through splitting.</p>


<p>A register that was not created by splitting is its own original. This operation is idempotent.</p>


<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Reference <a href="#a582c4d764e37313a1bc6dff1a727e752">getPreSplitReg</a>.</p>

</div>
</div>

### getPhys() {#a785a4e2daf4e5bf3f0836adbc4fb7e65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCRegister llvm::VirtRegMap::getPhys (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns the physical register mapped to the specified virtual register</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveintervals/#a6e3886e9084257e74b5db4a8951d36e0">llvm::LiveIntervals::addKillFlags</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/regallocgreedy-cpp/#a6e87024d7fe817808e0288f6b213d40c">assignedRegPartiallyOverlaps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86tileconfig-cpp/#af9d05205b22b79b40070ddc105679c7c">collectVirtRegShapes</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#abe5a79d15b373804c482e1905df927ff">llvm::LiveDebugVariables::LDVImpl::emitDebugValues</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzinstrinfo/#af3524773747ed9e90b586d5e6752e1c2">llvm::SystemZInstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#a6825b86f34e17792a882f599423f5485">getRC32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a69a2253decaa6ee31ae96ec6e0b3de13">llvm::AArch64RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a77b81cc14aafd09d0e380b123cd06d51">llvm::ARMBaseRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#ad490ad7663a07141538a6f4049299550">llvm::RISCVRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a31e904f48ac2baf80f9222c49059ef63">llvm::SystemZRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/targetregisterinfo/#afc99d2835eb4b8cde9e81db9abca597c">llvm::TargetRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>, <a href="#ab28bf4ffd3e2223dab0527c9d7e18288">hasPhys</a>, <a href="#a4af3414dbf16e5eb1b862c7cf35ed83c">hasPreferredPhys</a> and <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a>.</p>

</div>
</div>

### getPreSplitReg() {#a582c4d764e37313a1bc6dff1a727e752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::VirtRegMap::getPreSplitReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns the live interval virtReg is split from.</p>

<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="#a4d88862090bbf71af421aacae8f12866">getOriginal</a>.</p>

</div>
</div>

### getRegInfo() {#a5b03bffeedbff2a86dfe427fd90c1465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo &amp; llvm::VirtRegMap::getRegInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="#a7483a2fa0354b8fa3298ab99f41ce0d4">assignVirt2Phys</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a2e9547b9bc56b02aad18e54488c8059b">llvm::RegAllocBase::init</a>.</p>

</div>
</div>

### getShape() {#a5bdec6932a16e4d542bd8773fcb50acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShapeT llvm::VirtRegMap::getShape (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86tileconfig-cpp/#af9d05205b22b79b40070ddc105679c7c">collectVirtRegShapes</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86registerinfo-cpp/#aec0d8323ad306042f2eef8a2c5978162">getTileShape</a> and <a href="#a37b7b231e8677fb4c83572d6f4bedaa1">setIsSplitFromReg</a>.</p>

</div>
</div>

### getStackSlot() {#a32846fd2d98022e7b336962f85411a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VirtRegMap::getStackSlot (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns the stack slot mapped to the specified virtual register</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#abe5a79d15b373804c482e1905df927ff">llvm::LiveDebugVariables::LDVImpl::emitDebugValues</a>, <a href="#ad0df6033e4012261f7531e62274cf99c">isAssignedReg</a> and <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a>.</p>

</div>
</div>

### getTargetRegInfo() {#adb16c0664049f377c9ff542829013a75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo &amp; llvm::VirtRegMap::getTargetRegInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/allocationorder/#a1d17986988f0819f29d78d1be8555c9e">llvm::AllocationOrder::create</a> and <a href="/web-llvm/docs/api/classes/llvm/regallocbase/#a2e9547b9bc56b02aad18e54488c8059b">llvm::RegAllocBase::init</a>.</p>

</div>
</div>

### grow() {#a8d5afab2fece1568139a0c2784f0e481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VirtRegMap::grow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>Referenced by <a href="#a35ab2e8cafc507db705e2eeae719ae5c">clearAllVirt</a>.</p>

</div>
</div>

### hasKnownPreference() {#a103071c94c9a366fd2d96f5953871dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VirtRegMap::hasKnownPreference (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns true if VirtReg has a known preferred register.</p>


<p>This returns false if VirtReg has a preference that is a virtual register that hasn't been assigned yet.</p>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 121 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>Reference <a href="#ab28bf4ffd3e2223dab0527c9d7e18288">hasPhys</a>.</p>

</div>
</div>

### hasPhys() {#ab28bf4ffd3e2223dab0527c9d7e18288}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VirtRegMap::hasPhys (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns true if the specified virtual register is mapped to a physical register</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>References <a href="#a785a4e2daf4e5bf3f0836adbc4fb7e65">getPhys</a> and <a href="/web-llvm/docs/api/classes/llvm/mcregister/#a127e2906913fb89109f3e86397a559ad">llvm::MCRegister::isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#abe5a79d15b373804c482e1905df927ff">llvm::LiveDebugVariables::LDVImpl::emitDebugValues</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzregisterinfo-cpp/#a6825b86f34e17792a882f599423f5485">getRC32</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a69a2253decaa6ee31ae96ec6e0b3de13">llvm::AArch64RegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/armbaseregisterinfo/#a77b81cc14aafd09d0e380b123cd06d51">llvm::ARMBaseRegisterInfo::getRegAllocationHints</a>, <a href="/web-llvm/docs/api/classes/llvm/ppcregisterinfo/#a09a1c19b999c807cb52c21541a2c7de4">llvm::PPCRegisterInfo::getRegAllocationHints</a>, <a href="#a103071c94c9a366fd2d96f5953871dde">hasKnownPreference</a> and <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a>.</p>

</div>
</div>

### hasPreferredPhys() {#a4af3414dbf16e5eb1b862c7cf35ed83c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VirtRegMap::hasPreferredPhys (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> VirtReg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns true if VirtReg is assigned to its preferred physreg.</p>

<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>References <a href="#a785a4e2daf4e5bf3f0836adbc4fb7e65">getPhys</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#a7407603b3efcdc8d4c2b76697be34528">llvm::Register::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/register/#ab203bbcbc320180b1da9e9a92ee0c784">llvm::Register::isVirtual</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/mem2reg-cpp/#a6fde3eb6ca09ddf2fd76432176d817bb">Register</a>.</p>

</div>
</div>

### hasShape() {#a3d1e9b1a4148131fa20946943f7b1449}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VirtRegMap::hasShape (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86registerinfo-cpp/#aec0d8323ad306042f2eef8a2c5978162">getTileShape</a> and <a href="#a37b7b231e8677fb4c83572d6f4bedaa1">setIsSplitFromReg</a>.</p>

</div>
</div>

### init() {#a1a06f2509b5f901646c6498e9a0e8d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VirtRegMap::init (<a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/liveregmatrix/#ac1907c90bcd96c06c880601406ce946c">llvm::LiveRegMatrix::init</a> and <a href="/web-llvm/docs/api/classes/llvm/virtregmapanalysis/#a01f5f291c2aa5b0c076173adeb2dbd3a">llvm::VirtRegMapAnalysis::run</a>.</p>

</div>
</div>

### isAssignedReg() {#ad0df6033e4012261f7531e62274cf99c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VirtRegMap::isAssignedReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>returns true if the specified virtual register is not mapped to a stack slot or rematerialized.</p>

<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>References <a href="#a32846fd2d98022e7b336962f85411a42">getStackSlot</a> and <a href="#ad2e99ae080aa934d64b0ff504dab0158">NO_STACK_SLOT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#abe5a79d15b373804c482e1905df927ff">llvm::LiveDebugVariables::LDVImpl::emitDebugValues</a> and <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a>.</p>

</div>
</div>

### isShapeMapEmpty() {#af0653b6b211a32dda8152d3177e11aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VirtRegMap::isShapeMapEmpty ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-x86tileconfig-cpp-/x86tileconfig/#a963813efe9cac5e7b68def8df1713456">anonymous{X86TileConfig.cpp}::X86TileConfig::runOnMachineFunction</a>.</p>

</div>
</div>

### print() {#a7fa4b2ab2c4e30ebbb80c8384dc9ddd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VirtRegMap::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/register/#a1979c563289f871907832e419889f979">llvm::Register::index2VirtReg</a>, <a href="#ad2e99ae080aa934d64b0ff504dab0158">NO_STACK_SLOT</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af085ea923a328b9fa6a1975f1a4ff987">llvm::printReg</a>.</p>


<p>Referenced by <a href="#a570cc2ad4630f9e1adf4576e36507449">dump</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a071a500925a47bb844a0ad854252821c">llvm::operator&lt;&lt;</a>.</p>

</div>
</div>

### setIsSplitFromReg() {#a37b7b231e8677fb4c83572d6f4bedaa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VirtRegMap::setIsSplitFromReg (<a href="/web-llvm/docs/api/classes/llvm/register">Register</a> virtReg, <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> SReg)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>records virtReg is a split live interval from SReg.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>References <a href="#a5bdec6932a16e4d542bd8773fcb50acb">getShape</a> and <a href="#a3d1e9b1a4148131fa20946943f7b1449">hasShape</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createSpillSlot() {#a52608652809dc40da1201f892fb8a3e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned VirtRegMap::createSpillSlot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetregisterclass">TargetRegisterClass</a> * RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>createSpillSlot - Allocate a spill slot for RC from MFI.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MF {#a7f0b2088961d71501e812a59ee31d9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction* llvm::VirtRegMap::MF = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

### MRI {#a835c8be6a08721f11b0f0bfa93486af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineRegisterInfo* llvm::VirtRegMap::MRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

### TII {#a12e6a853f888cc11e0124b767dc4ae1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetInstrInfo* llvm::VirtRegMap::TII = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

### TRI {#ac280e5ca437a716279a2854979b1e2e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetRegisterInfo* llvm::VirtRegMap::TRI = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

### Virt2PhysMap {#a490f5b16e0234a997c467f91d377b09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;MCRegister, VirtReg2IndexFunctor&gt; llvm::VirtRegMap::Virt2PhysMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virt2PhysMap - This is a virtual to physical register mapping.</p>


<p>Each virtual register is required to have an entry in it; even spilled virtual registers (the register mapped to a spilled register is the temporary used to load it from the stack).</p>


<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

### Virt2ShapeMap {#a7400fd988e94da51a93c7d7685cad13b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;Register, ShapeT&gt; llvm::VirtRegMap::Virt2ShapeMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virt2ShapeMap - For <a href="/web-llvm/docs/api/namespaces/llvm/x86">X86</a> AMX register whose register is bound shape information.</p>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

### Virt2SplitMap {#adf4805378b31b0716a1aea9b44ecaa32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;Register, VirtReg2IndexFunctor&gt; llvm::VirtRegMap::Virt2SplitMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virt2SplitMap - This is virtual register to splitted virtual register mapping.</p>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

### Virt2StackSlotMap {#ab1684e154e59fbd59d0c7ac7291ecf5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedMap&lt;int, VirtReg2IndexFunctor&gt; llvm::VirtRegMap::Virt2StackSlotMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Virt2StackSlotMap - This is virtual register to stack slot mapping.</p>


<p>Each spilled virtual register has an entry in it which corresponds to the stack slot this register is spilled at.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### NO\_STACK\_SLOT {#ad2e99ae080aa934d64b0ff504dab0158}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::VirtRegMap::NO_STACK_SLOT = INT_MAX</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a>.</p>


<p>Referenced by <a href="#a1ae60b2416ed4d106a241c6874c1992d">assignVirt2StackSlot</a>, <a href="#aff9636d75b520f38c5860a95791331c8">assignVirt2StackSlot</a>, <a href="/web-llvm/docs/api/classes/llvm/livedebugvariables/ldvimpl/#abe5a79d15b373804c482e1905df927ff">llvm::LiveDebugVariables::LDVImpl::emitDebugValues</a>, <a href="#ad0df6033e4012261f7531e62274cf99c">isAssignedReg</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinespiller-cpp-/hoistspillhelper/#ad395a85b9e11855611ae547a3d332b8f">anonymous{InlineSpiller.cpp}::HoistSpillHelper::LRE_DidCloneVirtReg</a>, <a href="#a7fa4b2ab2c4e30ebbb80c8384dc9ddd3">print</a>, <a href="/web-llvm/docs/api/classes/anonymous-livedebugvariables-cpp-/uservalue/#aa3921084f5ef700564dcb83801124551">anonymous{LiveDebugVariables.cpp}::UserValue::rewriteLocations</a> and <a href="#a69fa879a33a59f14ca440c7ec9669a38">VirtRegMap</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/virtregmap-h">VirtRegMap.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp">VirtRegMap.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
