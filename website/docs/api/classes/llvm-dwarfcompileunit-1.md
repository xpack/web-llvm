---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfcompileunit-1
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFCompileUnit` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DWARFCompileUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">llvm/DebugInfo/DWARF/DWARFCompileUnit.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit-1">DWARFUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda0e7f6d7bf42526da3171eea79f92f">DWARFCompileUnit</a> (DWARFContext &amp;Context, const DWARFSection &amp;Section, const DWARFUnitHeader &amp;Header, const DWARFDebugAbbrev *DA, const DWARFSection *RS, const DWARFSection *LocSection, StringRef SS, const DWARFSection &amp;SOS, const DWARFSection *AOS, const DWARFSection &amp;LS, bool LE, bool IsDWO, const DWARFUnitVector &amp;UnitVector)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d1077ea3b7d5af71f1734d4e2cb687e">~DWARFCompileUnit</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VTable anchor. <a href="#a6d1077ea3b7d5af71f1734d4e2cb687e">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09cae3468f14c61f3ca7af906462dab">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump this compile unit to <span class="doxyComputerOutput">OS</span>. <a href="#ad09cae3468f14c61f3ca7af906462dab">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb978c8a6ce86f509e73a66e5bf7d811">classof</a> (const DWARFUnit *U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enable LLVM-style RTTI. <a href="#acb978c8a6ce86f509e73a66e5bf7d811">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">DWARFCompileUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFCompileUnit() {#afda0e7f6d7bf42526da3171eea79f92f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFCompileUnit::DWARFCompileUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; Section, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader">DWARFUnitHeader</a> &amp; Header, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> * DA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * RS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * LocSection, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; SOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * AOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; LS, bool LE, bool IsDWO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp; UnitVector)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">DWARFCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">llvm::DWARFUnit::DWARFUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DWARFCompileUnit() {#a6d1077ea3b7d5af71f1734d4e2cb687e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFCompileUnit::~DWARFCompileUnit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>VTable anchor.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">DWARFCompileUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#ad09cae3468f14c61f3ca7af906462dab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFCompileUnit::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts)</td>
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

<p>Dump this compile unit to <span class="doxyComputerOutput">OS</span>.</p>

<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">DWARFCompileUnit.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcompileunit-cpp">DWARFCompileUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a98519e1abf24139b0964cc8a33e7993a">llvm::DIDumpOptions::DumpNonSkeleton</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaad973adc80fce80cd7fb76d263240436">llvm::dwarf::FormatString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a535b9e1cc27192f7a16a1459333b859c">llvm::DWARFUnit::getAbbreviations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a95728db13d817152e70779b446728bfc">llvm::DWARFUnit::getAbbrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">llvm::DWARFUnit::getAddressByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0515d7981dbdf5c5031a5512368a03c4">llvm::DWARFUnit::getDWOId</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7830b1eb40f6264e196c3329a42cc342">llvm::DWARFUnit::getFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a23ed28928941964f658de8e78d8fc997">llvm::DWARFUnit::getLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae206bea6a70cddb7db54917fa04d8537">llvm::DWARFUnit::getNextUnitOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1b28f531b56fac2a5bdedea66750519b">llvm::DWARFUnit::getNonSkeletonUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af52bec8bfd6fcde07ecb8d04e495b8a0">llvm::DWARFUnit::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">llvm::DWARFUnit::getUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2084980f131a34248e09f10228625e78">llvm::DWARFUnit::getUnitType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8579cbbdc6613b150050d23fcc8fc539">llvm::DWARFUnit::getVersion</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a9e2b48707bbce67c70aea64d3b1d1634">llvm::DIDumpOptions::SummarizeTypes</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gae092dcf5f7e688a2a2213fe052374bf2">llvm::dwarf::UnitTypeString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#acb978c8a6ce86f509e73a66e5bf7d811}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFCompileUnit::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
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

<p>Enable LLVM-style RTTI.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">DWARFCompileUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">llvm::DWARFUnit::DWARFUnit</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfcompileunit-h">DWARFCompileUnit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcompileunit-cpp">DWARFCompileUnit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
