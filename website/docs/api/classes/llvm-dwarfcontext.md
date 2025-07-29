---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFContext` Class

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> This data structure is the top level entity that deals with dwarf debug information parsing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">llvm/DebugInfo/DWARF/DWARFContext.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283632a1efaee08b12853486fe1dda07">unit_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#ab995f3f17edd24f5a4ad18631b1b810e">DWARFUnitVector::iterator_range</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1663e29c697071c8e776ed1194d45a88">compile_unit_range</a> = <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#ae643824befdeea36bcdf9e2281ee4d63">DWARFUnitVector::compile_unit_range</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a1bd77ddc9aa314df1e0452710ca00af9">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read compile units from the debug_info.dwo section (if necessary) and type units from the debug_types.dwo section (if necessary) and store them in DWOUnits. <a href="#a1bd77ddc9aa314df1e0452710ca00af9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProcessDebugRelocations { <a href="#a6fbfbccaef05e07b2b1615224d5e20bd">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c1413d062f12285c899c61c634ae216">DWARFContextState</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22e323931522ffc5496756d56ca07365">DWARFContext</a> (std::unique_ptr&lt; const DWARFObject &gt; DObj, std::string DWPName="", std::function&lt; void(Error)&gt; RecoverableErrorHandler=WithColor::defaultErrorHandler, std::function&lt; void(Error)&gt; WarningHandler=WithColor::defaultWarningHandler, bool ThreadSafe=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac80147452befdf006653b9d9a1bc000">DWARFContext</a> (DWARFContext &amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a162a5effbd02f46a038e77b2ff714280">~DWARFContext</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cd0c012d5c338f904bd4553eba14d48">operator=</a> (DWARFContext &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5ebc989c207cabcabe0e9943938ddf1">getDWARFObj</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a872194924baf250829ba1b42a0b14105">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts, std::array&lt; std::optional&lt; uint64_t &gt;, DIDT_ID_Count &gt; DumpOffsets)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a textual representation to <span class="doxyComputerOutput">OS</span>. <a href="#a872194924baf250829ba1b42a0b14105">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7a45346661002500064513fff88c8ca">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef02a65817764b3fd99c6ee3bb349f4">verify</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts={}) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a283632a1efaee08b12853486fe1dda07">unit_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac511031ed298b7bbcc65d432ffe88912">info_section_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get units from .debug_info in this context. <a href="#ac511031ed298b7bbcc65d432ffe88912">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79ccbded2a247e0888f95da54f898d2d">getNormalUnitsVector</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a283632a1efaee08b12853486fe1dda07">unit_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9582935f8e1daa71195a6c76ce4f6c20">types_section_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get units from .debug_types in this context. <a href="#a9582935f8e1daa71195a6c76ce4f6c20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1663e29c697071c8e776ed1194d45a88">compile_unit_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3505e8caa8aebc427a28a104a4eb22b2">compile_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get compile units in this context. <a href="#a3505e8caa8aebc427a28a104a4eb22b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a283632a1efaee08b12853486fe1dda07">unit_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cd858c6644228cba53bd8631155b4a2">normal_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all normal compile/type units in this context. <a href="#a8cd858c6644228cba53bd8631155b4a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a283632a1efaee08b12853486fe1dda07">unit_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ad3a87998e6044d7e0ef77cd6e7d7d">dwo_info_section_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get units from .debug_info..dwo in the DWO context. <a href="#ac9ad3a87998e6044d7e0ef77cd6e7d7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5baf936fc47d9c920546930f670c03a">getDWOUnitsVector</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583afaee9d6061308ee33315501ee898">isDWP</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true of this DWARF context is a DWP file. <a href="#a583afaee9d6061308ee33315501ee898">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a283632a1efaee08b12853486fe1dda07">unit_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86b96eacf90b70918b473cbb3eaf4b5f">dwo_types_section_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get units from .debug_types.dwo in the DWO context. <a href="#a86b96eacf90b70918b473cbb3eaf4b5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1663e29c697071c8e776ed1194d45a88">compile_unit_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78d21cccb75ee475003a2592946d2207">dwo_compile_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get compile units in the DWO context. <a href="#a78d21cccb75ee475003a2592946d2207">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a283632a1efaee08b12853486fe1dda07">unit_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8e69a65912ebaef59c5fc4fefab821d">dwo_units</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get all units in the DWO context. <a href="#ae8e69a65912ebaef59c5fc4fefab821d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e3dd722cf5f278baf1e0f4fe736b0b">getNumCompileUnits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of compile units in this context. <a href="#a12e3dd722cf5f278baf1e0f4fe736b0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2649448397bdce699c88751d0bc17926">getNumTypeUnits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of type units in this context. <a href="#a2649448397bdce699c88751d0bc17926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab515cfc8666bd778801c6423e43c20a">getNumDWOCompileUnits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of compile units in the DWO context. <a href="#aab515cfc8666bd778801c6423e43c20a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d7c3e84e2c4fb0c0d1069367bf65a9">getNumDWOTypeUnits</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of type units in the DWO context. <a href="#a51d7c3e84e2c4fb0c0d1069367bf65a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68bb642208ccb975f1e00cbc9798e171">getUnitAtIndex</a> (unsigned index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the unit at the specified index. <a href="#a68bb642208ccb975f1e00cbc9798e171">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d96b7310c2ed4e1e4b1463d007f6c78">getDWOUnitAtIndex</a> (unsigned index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the unit at the specified index for the DWO units. <a href="#a3d96b7310c2ed4e1e4b1463d007f6c78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DWARFCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa708ebd83dcbff6505a26eb5d1608c34">getDWOCompileUnitForHash</a> (uint64_t Hash)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit">DWARFTypeUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8908e32e9aa677cefe9724dca7b7a908">getTypeUnitForHash</a> (uint64_t Hash, bool IsDWO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78455d42a3c92e58121a9f629033557e">getUnitForOffset</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the DWARF unit that includes an offset (relative to .debug_info). <a href="#a78455d42a3c92e58121a9f629033557e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DWARFCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508f713c72592be1df1230572a14f0e8">getCompileUnitForOffset</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the compile unit that includes an offset (relative to .debug_info). <a href="#a508f713c72592be1df1230572a14f0e8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ec6991c453b3e1479306bae88aa678">getDIEForOffset</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> given an exact offset. <a href="#a23ec6991c453b3e1479306bae88aa678">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a374f87c13c0dc6f0060885b97996391b">getMaxVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affd548c01726d8b05c45b743461774e9">getMaxDWOVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a779225a89b840b20c5840a7d6b89b4ea">setMaxVersionIfGreater</a> (unsigned Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba71f25d7fbb9345779ce7744749a36a">getCUIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfgdbindex">DWARFGdbIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a111be77dff94b0df3d6865ef9a77f5a5">getGdbIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex">DWARFUnitIndex</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364e16e7ce9aba162ab6d0103e68c3b0">getTUIndex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d55fdec90e61153ed8c8622753f0b82">getDebugAbbrev</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed DebugAbbrev object. <a href="#a3d55fdec90e61153ed8c8622753f0b82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc">DWARFDebugLoc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a3b000efab098963dcf4b891d8c9e35">getDebugLoc</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> object. <a href="#a7a3b000efab098963dcf4b891d8c9e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fd1b33cb1101c4716be9db002bc9723">getDebugAbbrevDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed dwo abbreviations object. <a href="#a2fd1b33cb1101c4716be9db002bc9723">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges">DWARFDebugAranges</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab467319c9e8fd684eca5161fc690e991">getDebugAranges</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed DebugAranges object. <a href="#ab467319c9e8fd684eca5161fc690e991">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a65005cffe7037718ea9543bf031aa4">getDebugFrame</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed frame information object. <a href="#a0a65005cffe7037718ea9543bf031aa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugframe">DWARFDebugFrame</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb053694870211a497c486c77741b451">getEHFrame</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed eh frame information object. <a href="#abb053694870211a497c486c77741b451">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeca2673e2cbd840e515b891c62eab57">getDebugMacinfo</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed DebugMacinfo information object. <a href="#adeca2673e2cbd840e515b891c62eab57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ecc79eb8233c0a5ecd6170341325a15">getDebugMacinfoDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed DebugMacinfoDWO information object. <a href="#a7ecc79eb8233c0a5ecd6170341325a15">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f5f0a402cdcb2ac0f56509ec4ddbd6">getDebugMacro</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed DebugMacro information object. <a href="#ad6f5f0a402cdcb2ac0f56509ec4ddbd6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugmacro">DWARFDebugMacro</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5443ecff451285b6e5b9dc43ea1c4eba">getDebugMacroDWO</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to the parsed DebugMacroDWO information object. <a href="#a5443ecff451285b6e5b9dc43ea1c4eba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames">DWARFDebugNames</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50ca1c7845a72288efbd3cd803672de5">getDebugNames</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the parsed accelerator table object. <a href="#a50ca1c7845a72288efbd3cd803672de5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76dc15e7b1c31a843564c589069ae413">getAppleNames</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the parsed accelerator table object. <a href="#a76dc15e7b1c31a843564c589069ae413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75848214f4a3eb792018168954f6c332">getAppleTypes</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the parsed accelerator table object. <a href="#a75848214f4a3eb792018168954f6c332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace22354603c3a5509e0a78b33f8ce317">getAppleNamespaces</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the parsed accelerator table object. <a href="#ace22354603c3a5509e0a78b33f8ce317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable">AppleAcceleratorTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355a562fff292f07e804eebf7f6bec5e">getAppleObjC</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the parsed accelerator table object. <a href="#a355a562fff292f07e804eebf7f6bec5e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b034e23dde3985292359895c41c74f6">getLineTableForUnit</a> (DWARFUnit *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to a parsed line table corresponding to a compile unit. <a href="#a6b034e23dde3985292359895c41c74f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable">DWARFDebugLine::LineTable</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a3a19ccb58c94b848a52f73fc722599">getLineTableForUnit</a> (DWARFUnit *U, function_ref&lt; void(Error)&gt; RecoverableErrorHandler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a pointer to a parsed line table corresponding to a compile unit. <a href="#a6a3a19ccb58c94b848a52f73fc722599">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7551c5997f50616b0b2af252de2527e5">clearLineTableForUnit</a> (DWARFUnit *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb28a98e1cb61a88b54188bd9617aef">getStringExtractor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca50e17987c68fd8f46648581534bd27">getStringDWOExtractor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d05545e25a58358f62a32e4ffb5260">getLineStringExtractor</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dwarfcontext/diesforaddress">DIEsForAddress</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3b09300d5e9ca1002c2a91191aee71b">getDIEsForAddress</a> (uint64_t Address, bool CheckDWO=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the compilation unit, the function <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and lexical block <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given address where applicable. <a href="#ac3b09300d5e9ca1002c2a91191aee71b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b7b57672968438f2f310f339c39cad2">getLineInfoForAddress</a> (object::SectionedAddress Address, DILineInfoSpecifier Specifier=DILineInfoSpecifier()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaffb0ccd4471e5240cb3ce371c9589e1">getLineInfoForDataAddress</a> (object::SectionedAddress Address) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a35d153b242ca028df3d73d57dd256522">DILineInfoTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f204d9568a58fbc54ad04343452904">getLineInfoForAddressRange</a> (object::SectionedAddress Address, uint64_t Size, DILineInfoSpecifier Specifier=DILineInfoSpecifier()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/diinlininginfo">DIInliningInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a063924dae0fe080259de2f7f2d7949eb">getInliningInfoForAddress</a> (object::SectionedAddress Address, DILineInfoSpecifier Specifier=DILineInfoSpecifier()) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilocal">DILocal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3dc5679c9f87dbde396b2ef8e006bc14">getLocalsForAddress</a> (object::SectionedAddress Address) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6810400ced4f9fd81a2a0f16a6d71de7">isLittleEndian</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc70edbeef03f50f1848e0a0d5a50bd">getDWOContext</a> (StringRef AbsolutePath)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a111bc257b974cfaa4070a8707a1b34c7">getRecoverableErrorHandler</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66f6b3d43cb69feb1c0bfd1ab00d99b1">getWarningHandler</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02498f8d7c7a3c0673ec84312da599fa">getCUAddrSize</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get address size from CUs. <a href="#a02498f8d7c7a3c0673ec84312da599fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154">Triple::ArchType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10da25a01692d7f5b04afee82a84e17e">getArch</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DWARFCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a> (uint64_t Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the compile unit which contains instruction with provided address. <a href="#a000efe430c85d8454e4ff9e74acb30bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DWARFCompileUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5cda98effd5b8f70b493af97124ff6">getCompileUnitForDataAddress</a> (uint64_t Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the compile unit which contains data with the provided address. <a href="#a3a5cda98effd5b8f70b493af97124ff6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac863d17ece37a8a1e3ddc65e106148c1">getParseCUTUIndexManually</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether CU/TU should be populated manually. <a href="#ac863d17ece37a8a1e3ddc65e106148c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4181199a7150c1631ecfb33a24040795">setParseCUTUIndexManually</a> (bool PCUTU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets whether CU/TU should be populated manually. <a href="#a4181199a7150c1631ecfb33a24040795">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a971c210f18ab6ad9a8862cc1a15844b2">getDWOUnits</a> (bool Lazy=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a863de61bc6f5f6706b04458f8fbcc33b">addLocalsForDie</a> (DWARFCompileUnit *CU, DWARFDie Subprogram, DWARFDie Die, std::vector&lt; DILocal &gt; &amp;Result)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate">DWARFContextState</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016343841104f99824e512a6629c682a">State</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>All important state for a <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> that needs to be threadsafe needs to go into <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate">DWARFContextState</a>. <a href="#a016343841104f99824e512a6629c682a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e14f6ab2a1bf98ab5a74bc4128d91b4">MaxVersion</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The maximum DWARF version of all units. <a href="#a2e14f6ab2a1bf98ab5a74bc4128d91b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e070e1f349623e503e5fbb08a8d1717">RecoverableErrorHandler</a> = ...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5c992a259d5c262114a1c8552f2c102">WarningHandler</a> = <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">WithColor::defaultWarningHandler</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83d9fd7ab2148f4231317342c670686">DObj</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24aac7e47d2398ca666c98f1205797bf">ParseCUTUIndexManually</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2936fe9d2a3c04a6fcaecf7baa725964">classof</a> (const DIContext *DICtx)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d72d4e6aa9cc116ad8b493299b42fd3">getMaxSupportedVersion</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d43ca8a7b3ac8ecf59f9b4b4279e896">isSupportedVersion</a> (unsigned version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint8_t, 3 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bda1f878fc3edb9fccf6acf1ea0dd32">getSupportedAddressSizes</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae44667c99ac42386fb7f60170a90b011">isAddressSizeSupported</a> (unsigned AddressSize)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Ts&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a62e2d6aade48552d756381ef9336576a">checkAddressSizeSupported</a> (unsigned AddressSize, std::error_code EC, char const *Fmt, const Ts &amp;...Vals)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6f9fa82bb8b6a5dae98b9d9d346d913">create</a> (const object::ObjectFile &amp;Obj, ProcessDebugRelocations RelocAction=ProcessDebugRelocations::Process, const LoadedObjectInfo *L=nullptr, std::string DWPName="", std::function&lt; void(Error)&gt; RecoverableErrorHandler=WithColor::defaultErrorHandler, std::function&lt; void(Error)&gt; WarningHandler=WithColor::defaultWarningHandler, bool ThreadSafe=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6970c9ef74827330c7124d6cb66e4ac">create</a> (const StringMap&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; &amp;Sections, uint8_t AddrSize, bool isLittleEndian=sys::IsLittleEndianHost, std::function&lt; void(Error)&gt; RecoverableErrorHandler=WithColor::defaultErrorHandler, std::function&lt; void(Error)&gt; WarningHandler=WithColor::defaultWarningHandler, bool ThreadSafe=false)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> This data structure is the top level entity that deals with dwarf debug information parsing.</p>


<p>The actual data is supplied through DWARFObj.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### compile\_unit\_range {#a1663e29c697071c8e776ed1194d45a88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFContext::compile_unit_range =  DWARFUnitVector::compile_unit_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### unit\_iterator\_range {#a283632a1efaee08b12853486fe1dda07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFContext::unit_iterator_range =  DWARFUnitVector::iterator_range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a1bd77ddc9aa314df1e0452710ca00af9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read compile units from the debug_info.dwo section (if necessary) and type units from the debug_types.dwo section (if necessary) and store them in DWOUnits.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EagerParse<a id="a1bd77ddc9aa314df1e0452710ca00af9a3266c94b0b97ee9bbe3d25ed6e5cb6ee"></a></td>
<td class="doxyEnumItemDescription"> (= false)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LazyParse<a id="a1bd77ddc9aa314df1e0452710ca00af9aa14cabfca45e71ff9759970a5da20355"></a></td>
<td class="doxyEnumItemDescription"> (= true)</td>
</tr>

</table>
</dd>
</dl>


<p>If <span class="doxyComputerOutput">Lazy</span> is true, set up to parse but don't actually parse them.</p>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### ProcessDebugRelocations {#a6fbfbccaef05e07b2b1615224d5e20bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::DWARFContext::ProcessDebugRelocations </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Process<a id="a6fbfbccaef05e07b2b1615224d5e20bdab6ec7abeb6ae29cc35a4b47475e12afe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Ignore<a id="a6fbfbccaef05e07b2b1615224d5e20bdafd038fc7f319e48f3115d92bf5bdbef9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 442 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DWARFContextState {#a1c1413d062f12285c899c61c634ae216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class DWARFContextState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/withcolor/#aa125c88f5418a9e78bd9f1f20b774b08">llvm::WithColor::defaultErrorHandler</a> and <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">llvm::WithColor::defaultWarningHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFContext() {#a22e323931522ffc5496756d56ca07365}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext::DWARFContext (std::unique_ptr&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfobject">DWARFObject</a> &gt; DObj, std::string DWPName="", std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler=<a href="/web-llvm/docs/api/classes/llvm/withcolor/#aa125c88f5418a9e78bd9f1f20b774b08">WithColor::defaultErrorHandler</a>, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; WarningHandler=<a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">WithColor::defaultWarningHandler</a>, bool ThreadSafe=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 744 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dicontext/#a9f7a11b0c15fffd9a627ae4ab42063dea4fd44b2bd2d598bbeb0699356db2a3ea">llvm::DIContext::CK_DWARF</a>, <a href="/web-llvm/docs/api/classes/llvm/dicontext/#aef4a5e2014d75324cc94441c730dcb85">llvm::DIContext::DIContext</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#aac80147452befdf006653b9d9a1bc000">DWARFContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate/#a9f94073361ae730535f2c039acdaf966">llvm::DWARFContext::DWARFContextState::DWARFContextState</a> and <a href="#a6cd0c012d5c338f904bd4553eba14d48">operator=</a>.</p>

</div>
</div>

### DWARFContext() {#aac80147452befdf006653b9d9a1bc000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFContext::DWARFContext (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp;)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Reference <a href="#a22e323931522ffc5496756d56ca07365">DWARFContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DWARFContext() {#a162a5effbd02f46a038e77b2ff714280}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext::~DWARFContext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a6cd0c012d5c338f904bd4553eba14d48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext &amp; llvm::DWARFContext::operator= (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp;)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Reference <a href="#a22e323931522ffc5496756d56ca07365">DWARFContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearLineTableForUnit() {#a7551c5997f50616b0b2af252de2527e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFContext::clearLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1502 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### compile\_units() {#a3505e8caa8aebc427a28a104a4eb22b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">compile_unit_range llvm::DWARFContext::compile_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get compile units in this context.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="#ac511031ed298b7bbcc65d432ffe88912">info_section_units</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada33d5221e33153a5557787ab6c9e3bb">llvm::isCompileUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#acc33f3dabfc507904e9fdfa7b0d81b51">llvm::DWARFDebugAranges::generate</a>, <a href="#a3a5cda98effd5b8f70b493af97124ff6">getCompileUnitForDataAddress</a> and <a href="#a02498f8d7c7a3c0673ec84312da599fa">getCUAddrSize</a>.</p>

</div>
</div>

### dump() {#a872194924baf250829ba1b42a0b14105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFContext::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts, std::array&lt; std::optional&lt; uint64_t &gt;, <a href="/web-llvm/docs/api/namespaces/llvm/#ad45d6f59eed095ce40cb5cea6c5455a4a974adafaf29dcbdf8ccefc9831bc0eae">DIDT_ID_Count</a> &gt; DumpOffsets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a textual representation to <span class="doxyComputerOutput">OS</span>.</p>


<p>If any <span class="doxyComputerOutput">DumpOffsets</span> are present, dump only the record at the specified offset.</p>


<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 987 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="#a3505e8caa8aebc427a28a104a4eb22b2">compile_units</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/debugify-cpp/#a9e8fa29f7cb6a03aa586afae7591f6cc">DF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad61266803a6a149f93740d19b87c0874a0616c268f4b30224000b0e828c45f90f">llvm::DIDT_All</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad45d6f59eed095ce40cb5cea6c5455a4a974adafaf29dcbdf8ccefc9831bc0eae">llvm::DIDT_ID_Count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad61266803a6a149f93740d19b87c0874af71984bf65c8aeb6f66e9cd926401c64">llvm::DIDT_UUID</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#af989f60200414119fe05ca13a394ca61">llvm::DIDumpOptions::DisplayRawContents</a>, <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#abdb9058a51e2fb5fd61d203dcdfd551a">llvm::AppleAcceleratorTable::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev/#a771ab53db331733048f7e421a2022154">llvm::DWARFDebugAbbrev::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugarangeset/#a6b102d8acecb56fe2e599dd7724ab78b">llvm::DWARFDebugArangeSet::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#aaefcf5fb948c6d0eaba576c6919871b9">llvm::DWARFDebugLoc::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/#af509255633e1bbe144cba3330e5d945c">llvm::DWARFDebugNames::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#adfc6560d80dd2ff0053cd7ef7ba0f5f1">llvm::DWARFDebugRangeList::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfgdbindex/#a9a69ad79fdede2991a00e3874c972f10">llvm::DWARFGdbIndex::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitindex/#a8b1fff716b8c2d13ec16bf4cb315ef8c">llvm::DWARFUnitIndex::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#aad9651c88d362ae11ea69508451b3ae6">dumpAddrSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a02e544cd4394600f3a6161460f9ec689">dumpLoclistsSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a76facea967f558412cc173c8224fdd9a">dumpPubTableSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a20d3f5071a5e2993982abaea21820301">dumpRnglistsSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#afb874a51b13c3cdfa8011bbf866c3658">dumpStringOffsetsSection</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a7313b0f4c1c5a3307d0947dcbee1777d">llvm::DIDumpOptions::DumpType</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a2aab28bc62e4c45e2fee753cdeb035dc">dumpUUID</a>, <a href="#ac9ad3a87998e6044d7e0ef77cd6e7d7d">dwo_info_section_units</a>, <a href="#a86b96eacf90b70918b473cbb3eaf4b5f">dwo_types_section_units</a>, <a href="#ae8e69a65912ebaef59c5fc4fefab821d">dwo_units</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ad1056825d31bf187d0be430c51aac281">llvm::sys::path::extension</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugarangeset/#a81576979ca20731e32ff1b245df0c5f3">llvm::DWARFDebugArangeSet::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a25597c272c2c6da035416f2331dccfbd">llvm::DWARFDebugRangeList::extract</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a76dc15e7b1c31a843564c589069ae413">getAppleNames</a>, <a href="#ace22354603c3a5509e0a78b33f8ce317">getAppleNamespaces</a>, <a href="#a355a562fff292f07e804eebf7f6bec5e">getAppleObjC</a>, <a href="#a75848214f4a3eb792018168954f6c332">getAppleTypes</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a17638a9e9146a6f6feef1adb50c53d2b">llvm::DataExtractor::getCStr</a>, <a href="#a02498f8d7c7a3c0673ec84312da599fa">getCUAddrSize</a>, <a href="#aba71f25d7fbb9345779ce7744749a36a">getCUIndex</a>, <a href="#a3d55fdec90e61153ed8c8622753f0b82">getDebugAbbrev</a>, <a href="#a2fd1b33cb1101c4716be9db002bc9723">getDebugAbbrevDWO</a>, <a href="#a0a65005cffe7037718ea9543bf031aa4">getDebugFrame</a>, <a href="#a7a3b000efab098963dcf4b891d8c9e35">getDebugLoc</a>, <a href="#adeca2673e2cbd840e515b891c62eab57">getDebugMacinfo</a>, <a href="#a7ecc79eb8233c0a5ecd6170341325a15">getDebugMacinfoDWO</a>, <a href="#ad6f5f0a402cdcb2ac0f56509ec4ddbd6">getDebugMacro</a>, <a href="#a5443ecff451285b6e5b9dc43ea1c4eba">getDebugMacroDWO</a>, <a href="#a50ca1c7845a72288efbd3cd803672de5">getDebugNames</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a54935e3c42396c955484e9ca2bab9081">llvm::DWARFUnit::getDIEForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4030d97efbcfaf77b80c112cd27c4214">llvm::DWARFDie::getDwarfUnit</a>, <a href="#abb053694870211a497c486c77741b451">getEHFrame</a>, <a href="#a111be77dff94b0df3d6865ef9a77f5a5">getGdbIndex</a>, <a href="#a374f87c13c0dc6f0060885b97996391b">getMaxVersion</a>, <a href="#a12e3dd722cf5f278baf1e0f4fe736b0b">getNumCompileUnits</a>, <a href="#aab515cfc8666bd778801c6423e43c20a">getNumDWOCompileUnits</a>, <a href="#a51d7c3e84e2c4fb0c0d1069367bf65a9">getNumDWOTypeUnits</a>, <a href="#a2649448397bdce699c88751d0bc17926">getNumTypeUnits</a>, <a href="#a364e16e7ce9aba162ab6d0103e68c3b0">getTUIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ac511031ed298b7bbcc65d432ffe88912">info_section_units</a>, <a href="#a6810400ced4f9fd81a2a0f16a6d71de7">isLittleEndian</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad6c780b958be0ededd6a525ce67206bb">llvm::DataExtractor::isValidOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a4374cf34c5d58482ffae982196bd2114">llvm::Macro</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#ace64c2107df2ab7fcbf17e0b6017d9dc">llvm::DIDumpOptions::noImplicitRecursion</a>, <a href="#a8cd858c6644228cba53bd8631155b4a2">normal_units</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a37d04f96a64f8d44fb59b8ca1ab8935b">llvm::DIDumpOptions::RecoverableErrorHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="#a9582935f8e1daa71195a6c76ce4f6c20">types_section_units</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a14000245b9f0a590dec228e5f073d44f">llvm::DIDumpOptions::WarningHandler</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>


<p>Referenced by <a href="#aa7a45346661002500064513fff88c8ca">dump</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-debuginfosupport-cpp-/#a6d57a0bd16d4bddf7ab304a3b529bd0b">anonymous{DebugInfoSupport.cpp}::dumpDWARFContext</a>.</p>

</div>
</div>

### dump() {#aa7a45346661002500064513fff88c8ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFContext::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad45d6f59eed095ce40cb5cea6c5455a4a974adafaf29dcbdf8ccefc9831bc0eae">llvm::DIDT_ID_Count</a> and <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### dwo\_compile\_units() {#a78d21cccb75ee475003a2592946d2207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">compile_unit_range llvm::DWARFContext::dwo_compile_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get compile units in the DWO context.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="#ac9ad3a87998e6044d7e0ef77cd6e7d7d">dwo_info_section_units</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ada33d5221e33153a5557787ab6c9e3bb">llvm::isCompileUnit</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a898e9304cf2baf908f4e9b8e32a5f6c3">llvm::make_filter_range</a>.</p>


<p>Referenced by <a href="#aa708ebd83dcbff6505a26eb5d1608c34">getDWOCompileUnitForHash</a>.</p>

</div>
</div>

### dwo\_info\_section\_units() {#ac9ad3a87998e6044d7e0ef77cd6e7d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator_range llvm::DWARFContext::dwo_info_section_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get units from .debug_info..dwo in the DWO context.</p>

<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a200eebec447ce4a311390379f322dd86">llvm::DWARFUnitVector::getNumInfoUnits</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>, <a href="#a78d21cccb75ee475003a2592946d2207">dwo_compile_units</a> and <a href="#affd548c01726d8b05c45b743461774e9">getMaxDWOVersion</a>.</p>

</div>
</div>

### dwo\_types\_section\_units() {#a86b96eacf90b70918b473cbb3eaf4b5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator_range llvm::DWARFContext::dwo_types_section_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get units from .debug_types.dwo in the DWO context.</p>

<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a200eebec447ce4a311390379f322dd86">llvm::DWARFUnitVector::getNumInfoUnits</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### dwo\_units() {#ae8e69a65912ebaef59c5fc4fefab821d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator_range llvm::DWARFContext::dwo_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get all units in the DWO context.</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getAppleNames() {#a76dc15e7b1c31a843564c589069ae413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; DWARFContext::getAppleNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a reference to the parsed accelerator table object.</p>

<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1470 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getAppleNamespaces() {#ace22354603c3a5509e0a78b33f8ce317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; DWARFContext::getAppleNamespaces ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a reference to the parsed accelerator table object.</p>

<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1478 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getAppleObjC() {#a355a562fff292f07e804eebf7f6bec5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; DWARFContext::getAppleObjC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a reference to the parsed accelerator table object.</p>

<p>Declaration at line 343 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1482 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getAppleTypes() {#a75848214f4a3eb792018168954f6c332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AppleAcceleratorTable &amp; DWARFContext::getAppleTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a reference to the parsed accelerator table object.</p>

<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1474 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getArch() {#a10da25a01692d7f5b04afee82a84e17e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::ArchType llvm::DWARFContext::getArch ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 467 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#ade6a289b7efafc8625daf0575ad81c08">llvm::object::ObjectFile::getArch</a>, <a href="#af5ebc989c207cabcabe0e9943938ddf1">getDWARFObj</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfobject/#afa4d2332712570f07479fccee61f767e">llvm::DWARFObject::getFile</a>.</p>

</div>
</div>

### getCompileUnitForCodeAddress() {#a000efe430c85d8454e4ff9e74acb30bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFCompileUnit * DWARFContext::getCompileUnitForCodeAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the compile unit which contains instruction with provided address.</p>


<p>TODO: change input parameter from "uint64_t Address" into "SectionedAddress Address"</p>


<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1518 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#ad5bd8d6e5b48e67cdd897f650afeda9f">llvm::DWARFDebugAranges::findAddress</a>, <a href="#a508f713c72592be1df1230572a14f0e8">getCompileUnitForOffset</a> and <a href="#ab467319c9e8fd684eca5161fc690e991">getDebugAranges</a>.</p>


<p>Referenced by <a href="#ac3b09300d5e9ca1002c2a91191aee71b">getDIEsForAddress</a>, <a href="#a063924dae0fe080259de2f7f2d7949eb">getInliningInfoForAddress</a>, <a href="#a2b7b57672968438f2f310f339c39cad2">getLineInfoForAddress</a>, <a href="#a55f204d9568a58fbc54ad04343452904">getLineInfoForAddressRange</a> and <a href="#a3dc5679c9f87dbde396b2ef8e006bc14">getLocalsForAddress</a>.</p>

</div>
</div>

### getCompileUnitForDataAddress() {#a3a5cda98effd5b8f70b493af97124ff6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFCompileUnit * DWARFContext::getCompileUnitForDataAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the compile unit which contains data with the provided address.</p>


<p>Note: This is more expensive than <span class="doxyComputerOutput">getCompileUnitForAddress</span>, as if <span class="doxyComputerOutput">Address</span> isn't found in the <a href="/web-llvm/docs/api/namespaces/cu">CU</a> ranges (which is cheap), then it falls back to an expensive O(n) walk of all <a href="/web-llvm/docs/api/namespaces/cu">CU</a>'s looking for data that spans the address. TODO: change input parameter from "uint64_t Address" into "SectionedAddress Address"</p>


<p>Declaration at line 484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1523 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a3505e8caa8aebc427a28a104a4eb22b2">compile_units</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#ad5bd8d6e5b48e67cdd897f650afeda9f">llvm::DWARFDebugAranges::findAddress</a>, <a href="#a508f713c72592be1df1230572a14f0e8">getCompileUnitForOffset</a> and <a href="#ab467319c9e8fd684eca5161fc690e991">getDebugAranges</a>.</p>


<p>Referenced by <a href="#aaffb0ccd4471e5240cb3ce371c9589e1">getLineInfoForDataAddress</a>.</p>

</div>
</div>

### getCompileUnitForOffset() {#a508f713c72592be1df1230572a14f0e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFCompileUnit * DWARFContext::getCompileUnitForOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the compile unit that includes an offset (relative to .debug_info).</p>

<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1514 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a78455d42a3c92e58121a9f629033557e">getUnitForOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a> and <a href="#a3a5cda98effd5b8f70b493af97124ff6">getCompileUnitForDataAddress</a>.</p>

</div>
</div>

### getCUAddrSize() {#a02498f8d7c7a3c0673ec84312da599fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t DWARFContext::getCUAddrSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get address size from CUs.</p>


<p>TODO: refactor <a href="#a3505e8caa8aebc427a28a104a4eb22b2">compile_units()</a> to make this const.</p>


<p>Declaration at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 2469 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="#a3505e8caa8aebc427a28a104a4eb22b2">compile_units</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getCUIndex() {#aba71f25d7fbb9345779ce7744749a36a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitIndex &amp; DWARFContext::getCUIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1413 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a> and <a href="#aa708ebd83dcbff6505a26eb5d1608c34">getDWOCompileUnitForHash</a>.</p>

</div>
</div>

### getDebugAbbrev() {#a3d55fdec90e61153ed8c8622753f0b82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAbbrev * DWARFContext::getDebugAbbrev ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed DebugAbbrev object.</p>

<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1425 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugAbbrevDWO() {#a2fd1b33cb1101c4716be9db002bc9723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAbbrev * DWARFContext::getDebugAbbrevDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed dwo abbreviations object.</p>

<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1429 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugAranges() {#ab467319c9e8fd684eca5161fc690e991}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAranges * DWARFContext::getDebugAranges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed DebugAranges object.</p>

<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1437 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a> and <a href="#a3a5cda98effd5b8f70b493af97124ff6">getCompileUnitForDataAddress</a>.</p>

</div>
</div>

### getDebugFrame() {#a0a65005cffe7037718ea9543bf031aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugFrame * &gt; DWARFContext::getDebugFrame ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed frame information object.</p>

<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1441 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugLoc() {#a7a3b000efab098963dcf4b891d8c9e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugLoc * DWARFContext::getDebugLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> object.</p>

<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1433 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugMacinfo() {#adeca2673e2cbd840e515b891c62eab57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * DWARFContext::getDebugMacinfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed DebugMacinfo information object.</p>

<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1457 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugMacinfoDWO() {#a7ecc79eb8233c0a5ecd6170341325a15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * DWARFContext::getDebugMacinfoDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed DebugMacinfoDWO information object.</p>

<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1461 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugMacro() {#ad6f5f0a402cdcb2ac0f56509ec4ddbd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * DWARFContext::getDebugMacro ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed DebugMacro information object.</p>

<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1449 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugMacroDWO() {#a5443ecff451285b6e5b9dc43ea1c4eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugMacro * DWARFContext::getDebugMacroDWO ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed DebugMacroDWO information object.</p>

<p>Declaration at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1453 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDebugNames() {#a50ca1c7845a72288efbd3cd803672de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugNames &amp; DWARFContext::getDebugNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a reference to the parsed accelerator table object.</p>

<p>Declaration at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1466 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getDIEForOffset() {#a23ec6991c453b3e1479306bae88aa678}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFContext::getDIEForOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> given an exact offset.</p>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1387 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getDIEsForAddress() {#ac3b09300d5e9ca1002c2a91191aee71b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext::DIEsForAddress DWARFContext::getDIEsForAddress (uint64_t Address, bool CheckDWO=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the compilation unit, the function <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and lexical block <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the given address where applicable.</p>


<p>TODO: change input parameter from "uint64_t Address" into "SectionedAddress Address"</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] CheckDWO</td>
<td class="doxyParamItemDescription"><p>If this is false then only search for address matches in the current context's DIEs. If this is true, then each <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> that has a DWO file will have the debug info in the DWO file searched as well. This allows for lookups to succeed by searching the split DWARF debug info when using the main executable's debug info.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1546 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4030d97efbcfaf77b80c112cd27c4214">llvm::DWARFDie::getDwarfUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4608e0e7126cfbc1e51312f20041486">llvm::DWARFUnit::getSubroutineForAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/die/#aeac16c22ec5a0c13658381144c7e3439">llvm::DIE::getTag</a>.</p>

</div>
</div>

### getDWARFObj() {#af5ebc989c207cabcabe0e9943938ddf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFObject &amp; llvm::DWARFContext::getDWARFObj ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#acc33f3dabfc507904e9fdfa7b0d81b51">llvm::DWARFDebugAranges::generate</a> and <a href="#a10da25a01692d7f5b04afee82a84e17e">getArch</a>.</p>

</div>
</div>

### getDWOCompileUnitForHash() {#aa708ebd83dcbff6505a26eb5d1608c34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFCompileUnit * DWARFContext::getDWOCompileUnitForHash (uint64_t Hash)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1357 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="#a78d21cccb75ee475003a2592946d2207">dwo_compile_units</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#aba71f25d7fbb9345779ce7744749a36a">getCUIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#ae12b387e4a14699e4f1229bf9d3d0905">llvm::DWARFUnitVector::getUnitForIndexEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>

</div>
</div>

### getDWOContext() {#a9dc70edbeef03f50f1848e0a0d5a50bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt; DWARFContext &gt; DWARFContext::getDWOContext (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AbsolutePath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 434 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1894 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### getDWOUnitAtIndex() {#a3d96b7310c2ed4e1e4b1463d007f6c78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit * llvm::DWARFContext::getDWOUnitAtIndex (unsigned index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the unit at the specified index for the DWO units.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getDWOUnitsVector() {#ae5baf936fc47d9c920546930f670c03a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitVector &amp; llvm::DWARFContext::getDWOUnitsVector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getEHFrame() {#abb053694870211a497c486c77741b451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugFrame * &gt; DWARFContext::getEHFrame ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to the parsed eh frame information object.</p>

<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1445 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getGdbIndex() {#a111be77dff94b0df3d6865ef9a77f5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFGdbIndex &amp; DWARFContext::getGdbIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1421 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getInliningInfoForAddress() {#a063924dae0fe080259de2f7f2d7949eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIInliningInfo DWARFContext::getInliningInfoForAddress (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> Specifier=<a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a>())</td>
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



<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1824 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/diinlininginfo/#ab109fcfc74414ad346bf8d3c81e48397">llvm::DIInliningInfo::addFrame</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#abdd9c481889f931155cca79f72e034f4">llvm::DILineInfo::Column</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a40c4c35f717ef11a8331573d47a83a93">llvm::DILineInfo::Discriminator</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#aafbd532afdd9c251604c825b8368580d">llvm::DILineInfo::FileName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#ab8894db2d4e97b2f89e68769bea54b3b">llvm::DILineInfo::FunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a629935bec1902c4115188af1c5a6aeb3">llvm::DWARFDie::getCallerFrame</a>, <a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a9d3dccb6b4b6b618de926e3863327b49">llvm::DWARFDie::getDeclFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aa60164fdf3076c81c5c5ddce03657dc7">llvm::DWARFDie::getDeclLine</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a21d28efc861659400235ff1b387c6aa3">llvm::DWARFDebugLine::LineTable::getFileLineInfoForAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a72aff7095112320360cc07670524728e">llvm::DWARFDebugLine::LineTable::getFileNameByIndex</a>, <a href="#a6b034e23dde3985292359895c41c74f6">getLineTableForUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a48f96d333a71d8a20a5ecb501f07b16c">llvm::DWARFDie::getSubroutineName</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a69b67fe0ad4e7bfe7c66e2ae3fa9b1ab">llvm::DILineInfo::Line</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a2b086783f95057c188bc04c705faff25">llvm::DILineInfo::StartAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#aee6de87e87f24d06aadf8ad3821ab007">llvm::DILineInfo::StartFileName</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#ade557e29b505c495f4e761fdba518595">llvm::DILineInfo::StartLine</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a3fcfe121a4dc5b72106bdacb47f3ce1e">llvm::dwarf::toSectionedAddress</a>.</p>

</div>
</div>

### getLineInfoForAddress() {#a2b7b57672968438f2f310f339c39cad2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILineInfo DWARFContext::getLineInfoForAddress (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> Specifier=<a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a>())</td>
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



<p>Declaration at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1733 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a4f50f080b393ee0a2c845ddbce571ae9">getFunctionNameAndStartLineForAddress</a> and <a href="#a6b034e23dde3985292359895c41c74f6">getLineTableForUnit</a>.</p>

</div>
</div>

### getLineInfoForAddressRange() {#a55f204d9568a58fbc54ad04343452904}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILineInfoTable DWARFContext::getLineInfoForAddressRange (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address, uint64_t Size, <a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a> Specifier=<a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier">DILineInfoSpecifier</a>())</td>
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



<p>Declaration at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1769 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/structs/llvm/dilineinfo/#a1d2fecd19cf03aa8167943894af5f8c4">llvm::DILineInfo::BadString</a>, <a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a72aff7095112320360cc07670524728e">llvm::DWARFDebugLine::LineTable::getFileNameByIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a4f50f080b393ee0a2c845ddbce571ae9">getFunctionNameAndStartLineForAddress</a>, <a href="#a6b034e23dde3985292359895c41c74f6">getLineTableForUnit</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a910420e98a8f344483b3c461314898e3">llvm::DWARFDebugLine::LineTable::lookupAddressRange</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a08f2df6a1aaacec42c6ded0585a11e4d">llvm::DWARFDebugLine::LineTable::Rows</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-perfsupportplugin-cpp-/#ac931ae3a09278d920ebb024da87edf2e">anonymous{PerfSupportPlugin.cpp}::getDebugInfoRecord</a>.</p>

</div>
</div>

### getLineInfoForDataAddress() {#aaffb0ccd4471e5240cb3ce371c9589e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DILineInfo DWARFContext::getLineInfoForDataAddress (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address)</td>
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



<p>Declaration at line 393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1755 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a3a5cda98effd5b8f70b493af97124ff6">getCompileUnitForDataAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a9d3dccb6b4b6b618de926e3863327b49">llvm::DWARFDie::getDeclFile</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aa60164fdf3076c81c5c5ddce03657dc7">llvm::DWARFDie::getDeclLine</a>.</p>

</div>
</div>

### getLineStringExtractor() {#ac3d05545e25a58358f62a32e4ffb5260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor llvm::DWARFContext::getLineStringExtractor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getLineTableForUnit() {#a6b034e23dde3985292359895c41c74f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugLine::LineTable * DWARFContext::getLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to a parsed line table corresponding to a compile unit.</p>


<p>Report any parsing issues as warnings on stderr.</p>


<p>Declaration at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1487 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="#a6b034e23dde3985292359895c41c74f6">getLineTableForUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#ac9a2ecd6a14be08a7a81ef10f869aa31">llvm::gsym::CUInfo::CUInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a2af35f9fb586ccbd0416130e8b3f17aa">llvm::DWARFFormValue::getAsFile</a>, <a href="#a063924dae0fe080259de2f7f2d7949eb">getInliningInfoForAddress</a>, <a href="#a2b7b57672968438f2f310f339c39cad2">getLineInfoForAddress</a>, <a href="#a55f204d9568a58fbc54ad04343452904">getLineInfoForAddressRange</a> and <a href="#a6b034e23dde3985292359895c41c74f6">getLineTableForUnit</a>.</p>

</div>
</div>

### getLineTableForUnit() {#a6a3a19ccb58c94b848a52f73fc722599}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const DWARFDebugLine::LineTable * &gt; DWARFContext::getLineTableForUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a pointer to a parsed line table corresponding to a compile unit.</p>


<p>Report any recoverable parsing problems using the handler.</p>


<p>Declaration at line 352 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1497 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### getLocalsForAddress() {#a3dc5679c9f87dbde396b2ef8e006bc14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; DILocal &gt; DWARFContext::getLocalsForAddress (<a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> Address)</td>
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



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1721 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#a000efe430c85d8454e4ff9e74acb30bf">getCompileUnitForCodeAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ae970d60ab52d996448bb030b4a0b67bc">llvm::DWARFDie::isValid</a>.</p>

</div>
</div>

### getMaxDWOVersion() {#affd548c01726d8b05c45b743461774e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::getMaxDWOVersion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Reference <a href="#ac9ad3a87998e6044d7e0ef77cd6e7d7d">dwo_info_section_units</a>.</p>

</div>
</div>

### getMaxVersion() {#a374f87c13c0dc6f0060885b97996391b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::getMaxVersion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Reference <a href="#ac511031ed298b7bbcc65d432ffe88912">info_section_units</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getNormalUnitsVector() {#a79ccbded2a247e0888f95da54f898d2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitVector &amp; llvm::DWARFContext::getNormalUnitsVector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getNumCompileUnits() {#a12e3dd722cf5f278baf1e0f4fe736b0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::getNumCompileUnits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of compile units in this context.</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getNumDWOCompileUnits() {#aab515cfc8666bd778801c6423e43c20a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::getNumDWOCompileUnits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of compile units in the DWO context.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getNumDWOTypeUnits() {#a51d7c3e84e2c4fb0c0d1069367bf65a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::getNumDWOTypeUnits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of type units in the DWO context.</p>

<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getNumTypeUnits() {#a2649448397bdce699c88751d0bc17926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::getNumTypeUnits ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the number of type units in this context.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### getParseCUTUIndexManually() {#ac863d17ece37a8a1e3ddc65e106148c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFContext::getParseCUTUIndexManually ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether CU/TU should be populated manually.</p>


<p>TU Index populated manually only for DWARF5.</p>


<p>Definition at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getRecoverableErrorHandler() {#a111bc257b974cfaa4070a8707a1b34c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt; void(Error)&gt; llvm::DWARFContext::getRecoverableErrorHandler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 436 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#acc33f3dabfc507904e9fdfa7b0d81b51">llvm::DWARFDebugAranges::generate</a>.</p>

</div>
</div>

### getStringDWOExtractor() {#aca50e17987c68fd8f46648581534bd27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor llvm::DWARFContext::getStringDWOExtractor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getStringExtractor() {#a3eb28a98e1cb61a88b54188bd9617aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor llvm::DWARFContext::getStringExtractor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getTUIndex() {#a364e16e7ce9aba162ab6d0103e68c3b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitIndex &amp; DWARFContext::getTUIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1417 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a> and <a href="#a8908e32e9aa677cefe9724dca7b7a908">getTypeUnitForHash</a>.</p>

</div>
</div>

### getTypeUnitForHash() {#a8908e32e9aa677cefe9724dca7b7a908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFTypeUnit * DWARFContext::getTypeUnitForHash (uint64_t Hash, bool IsDWO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1346 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a5f6182886dc2f96c204299e92c1565d5">llvm::dyn_cast_or_null</a>, <a href="#a364e16e7ce9aba162ab6d0103e68c3b0">getTUIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#ae12b387e4a14699e4f1229bf9d3d0905">llvm::DWARFUnitVector::getUnitForIndexEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4bbbe4c1e38aa50239589e57e47d0eee">llvm::DWARFDie::getAttributeValueAsReferencedDie</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a107a5c45aec6fd4389339f69720a8608">llvm::DWARFDie::resolveTypeUnitReference</a>.</p>

</div>
</div>

### getUnitAtIndex() {#a68bb642208ccb975f1e00cbc9798e171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit * llvm::DWARFContext::getUnitAtIndex (unsigned index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the unit at the specified index.</p>

<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### getUnitForOffset() {#a78455d42a3c92e58121a9f629033557e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit * DWARFContext::getUnitForOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the DWARF unit that includes an offset (relative to .debug_info).</p>

<p>Declaration at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1510 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a508f713c72592be1df1230572a14f0e8">getCompileUnitForOffset</a>.</p>

</div>
</div>

### getWarningHandler() {#a66f6b3d43cb69feb1c0bfd1ab00d99b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt; void(Error)&gt; llvm::DWARFContext::getWarningHandler ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#acc33f3dabfc507904e9fdfa7b0d81b51">llvm::DWARFDebugAranges::generate</a>.</p>

</div>
</div>

### info\_section\_units() {#ac511031ed298b7bbcc65d432ffe88912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator_range llvm::DWARFContext::info_section_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get units from .debug_info in this context.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a200eebec447ce4a311390379f322dd86">llvm::DWARFUnitVector::getNumInfoUnits</a>.</p>


<p>Referenced by <a href="#a3505e8caa8aebc427a28a104a4eb22b2">compile_units</a>, <a href="#a872194924baf250829ba1b42a0b14105">dump</a> and <a href="#a374f87c13c0dc6f0060885b97996391b">getMaxVersion</a>.</p>

</div>
</div>

### isDWP() {#a583afaee9d6061308ee33315501ee898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFContext::isDWP ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true of this DWARF context is a DWP file.</p>

<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 2479 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### isLittleEndian() {#a6810400ced4f9fd81a2a0f16a6d71de7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFContext::isLittleEndian ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="#aa6970c9ef74827330c7124d6cb66e4ac">create</a>, <a href="#a872194924baf250829ba1b42a0b14105">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugaranges/#acc33f3dabfc507904e9fdfa7b0d81b51">llvm::DWARFDebugAranges::generate</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp/#a53ce6032d5574922c161935e73014e18">isVariableIndexable</a>.</p>

</div>
</div>

### normal\_units() {#a8cd858c6644228cba53bd8631155b4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator_range llvm::DWARFContext::normal_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get all normal compile/type units in this context.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### setMaxVersionIfGreater() {#a779225a89b840b20c5840a7d6b89b4ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFContext::setMaxVersionIfGreater (unsigned Version)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a689a023f54d38d41f6d952cac41ee538">llvm::Version</a>.</p>

</div>
</div>

### setParseCUTUIndexManually() {#a4181199a7150c1631ecfb33a24040795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFContext::setParseCUTUIndexManually (bool PCUTU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets whether CU/TU should be populated manually.</p>


<p>TU Index populated manually only for DWARF5.</p>


<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### types\_section\_units() {#a9582935f8e1daa71195a6c76ce4f6c20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unit_iterator_range llvm::DWARFContext::types_section_units ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get units from .debug_types in this context.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a200eebec447ce4a311390379f322dd86">llvm::DWARFUnitVector::getNumInfoUnits</a>.</p>


<p>Referenced by <a href="#a872194924baf250829ba1b42a0b14105">dump</a>.</p>

</div>
</div>

### verify() {#a7ef02a65817764b3fd99c6ee3bb349f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFContext::verify (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts={})</td>
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



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1393 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a7313b0f4c1c5a3307d0947dcbee1777d">llvm::DIDumpOptions::DumpType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a0863e40b075a475f0333b33714fb09d7">llvm::DWARFVerifier::handleAccelTables</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#af4c71e263810db89b9093317f9ffb48c">llvm::DWARFVerifier::handleDebugAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a9f68717723fce2a910828afff31f838a">llvm::DWARFVerifier::handleDebugCUIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#aa6eb6cb99b9b63fd2ad94746fe8d7c93">llvm::DWARFVerifier::handleDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#abb3d42476a9be199a131e95a1af05de9">llvm::DWARFVerifier::handleDebugLine</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a615332b0161a87347eea3360a5d51410">llvm::DWARFVerifier::handleDebugStrOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#a5cd4ba96c8f51dd40c91522ea21beea2">llvm::DWARFVerifier::handleDebugTUIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/lib/target/aarch64/disassembler/aarch64disassembler-cpp/#abdb086b34295fb7aa09493c62d798465">Success</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfverifier/#acc7f16c0553ca0c637b42907ff64b9f5">llvm::DWARFVerifier::summarize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addLocalsForDie() {#a863de61bc6f5f6706b04458f8fbcc33b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFContext::addLocalsForDie (<a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit">DWARFCompileUnit</a> * CU, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Subprogram, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die, std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/dilocal">DILocal</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1655 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

### getDWOUnits() {#a971c210f18ab6ad9a8862cc1a15844b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitVector &amp; DWARFContext::getDWOUnits (bool Lazy=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 1506 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DObj {#aa83d9fd7ab2148f4231317342c670686}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;const DWARFObject&gt; llvm::DWARFContext::DObj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### MaxVersion {#a2e14f6ab2a1bf98ab5a74bc4128d91b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::MaxVersion = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The maximum DWARF version of all units.</p>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### ParseCUTUIndexManually {#a24aac7e47d2398ca666c98f1205797bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFContext::ParseCUTUIndexManually = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### RecoverableErrorHandler {#a4e070e1f349623e503e5fbb08a8d1717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Error)&gt; llvm::DWARFContext::RecoverableErrorHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/classes/llvm/withcolor/#aa125c88f5418a9e78bd9f1f20b774b08">WithColor::defaultErrorHandler</a>
</div>
</dd>
</dl>

<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### State {#a016343841104f99824e512a6629c682a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFContextState&gt; llvm::DWARFContext::State</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>All important state for a <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> that needs to be threadsafe needs to go into <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/dwarfcontextstate">DWARFContextState</a>.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

### WarningHandler {#ad5c992a259d5c262114a1c8552f2c102}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(Error)&gt; llvm::DWARFContext::WarningHandler = <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">WithColor::defaultWarningHandler</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### checkAddressSizeSupported() {#a62e2d6aade48552d756381ef9336576a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Ts&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::DWARFContext::checkAddressSizeSupported (unsigned AddressSize, std::error_code EC, char <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Fmt, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> Ts &amp;... Vals)</td>
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



<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a1bda1f878fc3edb9fccf6acf1ea0dd32">getSupportedAddressSizes</a>, <a href="#ae44667c99ac42386fb7f60170a90b011">isAddressSizeSupported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugarangeset/#a81576979ca20731e32ff1b245df0c5f3">llvm::DWARFDebugArangeSet::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a25597c272c2c6da035416f2331dccfbd">llvm::DWARFDebugRangeList::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader/#a1a4f52d08af4f50e2e5b0f2ea73fe12f">llvm::DWARFListTableHeader::extract</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>.</p>

</div>
</div>

### classof() {#a2936fe9d2a3c04a6fcaecf7baa725964}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFContext::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicontext">DIContext</a> * DICtx)</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dicontext/#a9f7a11b0c15fffd9a627ae4ab42063dea4fd44b2bd2d598bbeb0699356db2a3ea">llvm::DIContext::CK_DWARF</a>, <a href="/web-llvm/docs/api/classes/llvm/dicontext/#aef4a5e2014d75324cc94441c730dcb85">llvm::DIContext::DIContext</a> and <a href="/web-llvm/docs/api/classes/llvm/dicontext/#ad0884480a7cb2a5bbe9f265e66444a22">llvm::DIContext::getKind</a>.</p>

</div>
</div>

### create() {#ad6f9fa82bb8b6a5dae98b9d9d346d913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; DWARFContext &gt; DWARFContext::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="#a6fbfbccaef05e07b2b1615224d5e20bd">ProcessDebugRelocations</a> RelocAction=<a href="#a6fbfbccaef05e07b2b1615224d5e20bdab6ec7abeb6ae29cc35a4b47475e12afe">ProcessDebugRelocations::Process</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loadedobjectinfo">LoadedObjectInfo</a> * L=nullptr, std::string DWPName="", std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler=<a href="/web-llvm/docs/api/classes/llvm/withcolor/#aa125c88f5418a9e78bd9f1f20b774b08">WithColor::defaultErrorHandler</a>, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; WarningHandler=<a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">WithColor::defaultWarningHandler</a>, bool ThreadSafe=false)</td>
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



<p>Declaration at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 2442 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1fbf6763e62eb4e5268f421eee37d6b1">llvm::MachO::DylibReader::accumulateSourceLocFromDSYM</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a9ecb3cb1036963ce01100bfddac5791f">llvm::orc::createDWARFContext</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofcorrelatorimpl/#a03623c93978bf24485c895a53d164368">llvm::InstrProfCorrelatorImpl&lt; IntPtrT &gt;::get</a>, <a href="/web-llvm/docs/api/classes/anonymous-dwarfcontext-cpp-/threadunsafedwarfcontextstate/#a54233894e754c548da87c0d21d69003d">anonymous{DWARFContext.cpp}::ThreadUnsafeDWARFContextState::getDWOContext</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/llvmsymbolizer/#aed363690d82a9bc955ab653a37e75090">llvm::symbolize::LLVMSymbolizer::getOrCreateModuleInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-inteljiteventlistener-cpp-/inteljiteventlistener/#a89cbcd5cb777a56db440c87f1ebffdb4">anonymous{IntelJITEventListener.cpp}::IntelJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-oprofilejiteventlistener-cpp-/oprofilejiteventlistener/#acbf9525bdd6bfe26f04d293ee1d9a7ca">anonymous{OProfileJITEventListener.cpp}::OProfileJITEventListener::notifyObjectLoaded</a>, <a href="/web-llvm/docs/api/classes/anonymous-perfjiteventlistener-cpp-/perfjiteventlistener/#a502ebf0f061782cbcfa72244fbd0ec97">anonymous{PerfJITEventListener.cpp}::PerfJITEventListener::notifyObjectLoaded</a> and <a href="/web-llvm/docs/api/classes/anonymous-debuggersupportplugin-cpp-/machodebugobjectsynthesizer/#a59a5eeccde7b8eef0833cee7b914443b">anonymous{DebuggerSupportPlugin.cpp}::MachODebugObjectSynthesizer&lt; MachOTraits &gt;::startSynthesis</a>.</p>

</div>
</div>

### create() {#aa6970c9ef74827330c7124d6cb66e4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; DWARFContext &gt; DWARFContext::create (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt; &amp; Sections, uint8_t AddrSize, bool isLittleEndian=<a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">sys::IsLittleEndianHost</a>, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; RecoverableErrorHandler=<a href="/web-llvm/docs/api/classes/llvm/withcolor/#aa125c88f5418a9e78bd9f1f20b774b08">WithColor::defaultErrorHandler</a>, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/error">Error</a>)&gt; WarningHandler=<a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0ab9ce7767ba8ad9a3cb17cd35d81a1f">WithColor::defaultWarningHandler</a>, bool ThreadSafe=false)</td>
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



<p>Declaration at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>, definition at line 2458 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a>.</p>


<p>Reference <a href="#a6810400ced4f9fd81a2a0f16a6d71de7">isLittleEndian</a>.</p>

</div>
</div>

### getMaxSupportedVersion() {#a8d72d4e6aa9cc116ad8b493299b42fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFContext::getMaxSupportedVersion ()</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a> and <a href="#a0d43ca8a7b3ac8ecf59f9b4b4279e896">isSupportedVersion</a>.</p>

</div>
</div>

### getSupportedAddressSizes() {#a1bda1f878fc3edb9fccf6acf1ea0dd32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; uint8_t, 3 &gt; llvm::DWARFContext::getSupportedAddressSizes ()</td>
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



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Referenced by <a href="#a62e2d6aade48552d756381ef9336576a">checkAddressSizeSupported</a> and <a href="#ae44667c99ac42386fb7f60170a90b011">isAddressSizeSupported</a>.</p>

</div>
</div>

### isAddressSizeSupported() {#ae44667c99ac42386fb7f60170a90b011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFContext::isAddressSizeSupported (unsigned AddressSize)</td>
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



<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>References <a href="#a1bda1f878fc3edb9fccf6acf1ea0dd32">getSupportedAddressSizes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>.</p>


<p>Referenced by <a href="#a62e2d6aade48552d756381ef9336576a">checkAddressSizeSupported</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugrangelist/rangelistentry/#aab974969801970ba1a8b9b3a0c69f5f5">llvm::DWARFDebugRangeList::RangeListEntry::isBaseAddressSelectionEntry</a>.</p>

</div>
</div>

### isSupportedVersion() {#a0d43ca8a7b3ac8ecf59f9b4b4279e896}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFContext::isSupportedVersion (unsigned version)</td>
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



<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a>.</p>


<p>Reference <a href="#a8d72d4e6aa9cc116ad8b493299b42fd3">getMaxSupportedVersion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a528edf849dcc29ea39dcbd66bcf2ba7d">llvm::DWARFUnitHeader::extract</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcontext-h">DWARFContext.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp">DWARFContext.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
