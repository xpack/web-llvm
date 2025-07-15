---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarftypeunit-1
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFTypeUnit` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DWARFTypeUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">llvm/DebugInfo/DWARF/DWARFTypeUnit.h</a>"
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb745ae665bf53d8d2536c01f385acb">DWARFTypeUnit</a> (DWARFContext &amp;Context, const DWARFSection &amp;Section, const DWARFUnitHeader &amp;Header, const DWARFDebugAbbrev *DA, const DWARFSection *RS, const DWARFSection *LocSection, StringRef SS, const DWARFSection &amp;SOS, const DWARFSection *AOS, const DWARFSection &amp;LS, bool LE, bool IsDWO, const DWARFUnitVector &amp;UnitVector)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc22be0c6b0ce38d53fd0b4683bb6fec">getTypeHash</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618cd83987813c41dca4cdb74b2b0f1a">getTypeOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c2344d084d7463ac5940022292d5775">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts={}) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af854109f380b6c8b357945d3fa290522">classof</a> (const DWARFUnit *U)</td>
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


<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">DWARFTypeUnit.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DWARFTypeUnit() {#abcb745ae665bf53d8d2536c01f385acb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFTypeUnit::DWARFTypeUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; Section, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader">DWARFUnitHeader</a> &amp; Header, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> * DA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * RS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * LocSection, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; SOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * AOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; LS, bool LE, bool IsDWO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp; UnitVector)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">DWARFTypeUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">llvm::DWARFUnit::DWARFUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a9c2344d084d7463ac5940022292d5775}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFTypeUnit::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts={})</td>
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



<p>Declaration at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">DWARFTypeUnit.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarftypeunit-cpp">DWARFTypeUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaad973adc80fce80cd7fb76d263240436">llvm::dwarf::FormatString</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a535b9e1cc27192f7a16a1459333b859c">llvm::DWARFUnit::getAbbreviations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a95728db13d817152e70779b446728bfc">llvm::DWARFUnit::getAbbrOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">llvm::DWARFUnit::getAddressByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a54935e3c42396c955484e9ca2bab9081">llvm::DWARFUnit::getDIEForOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7830b1eb40f6264e196c3329a42cc342">llvm::DWARFUnit::getFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a23ed28928941964f658de8e78d8fc997">llvm::DWARFUnit::getLength</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a834590fd64e02e844dd117b380ab819b">llvm::DWARFDie::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae206bea6a70cddb7db54917fa04d8537">llvm::DWARFUnit::getNextUnitOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af52bec8bfd6fcde07ecb8d04e495b8a0">llvm::DWARFUnit::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#adc22be0c6b0ce38d53fd0b4683bb6fec">getTypeHash</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a618cd83987813c41dca4cdb74b2b0f1a">getTypeOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">llvm::DWARFUnit::getUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2084980f131a34248e09f10228625e78">llvm::DWARFUnit::getUnitType</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8579cbbdc6613b150050d23fcc8fc539">llvm::DWARFUnit::getVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870ad26b007baa81cc3cd38d8d6c93e6df42">llvm::ShortName</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a9e2b48707bbce67c70aea64d3b1d1634">llvm::DIDumpOptions::SummarizeTypes</a> and <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gae092dcf5f7e688a2a2213fe052374bf2">llvm::dwarf::UnitTypeString</a>.</p>

</div>
</div>

### getTypeHash() {#adc22be0c6b0ce38d53fd0b4683bb6fec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFTypeUnit::getTypeHash ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">DWARFTypeUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a525cad0eda581481dd10ec944237a5ec">llvm::DWARFUnit::getHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a7b8ac285c44bf370974cf4ce02134fcb">llvm::DWARFUnitHeader::getTypeHash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">dump</a>.</p>

</div>
</div>

### getTypeOffset() {#a618cd83987813c41dca4cdb74b2b0f1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFTypeUnit::getTypeOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">DWARFTypeUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a525cad0eda581481dd10ec944237a5ec">llvm::DWARFUnit::getHeader</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a945cdf61db1305c4679beb3a285671dd">llvm::DWARFUnitHeader::getTypeOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">dump</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#af854109f380b6c8b357945d3fa290522}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFTypeUnit::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * U)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">DWARFTypeUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">llvm::DWARFUnit::DWARFUnit</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarftypeunit-h">DWARFTypeUnit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarftypeunit-cpp">DWARFTypeUnit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
