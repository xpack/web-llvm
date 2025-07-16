---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfunit-1
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFUnit` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::DWARFUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">llvm/DebugInfo/DWARF/DWARFUnit.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit-1">DWARFCompileUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit-1">DWARFTypeUnit</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94206113c22ed86bdba16fb99d1c1976">die_iterator_range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> &gt;::iterator &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4eac03e9bd7411e28763651863ef34">DWARFUnit</a> (DWARFContext &amp;Context, const DWARFSection &amp;Section, const DWARFUnitHeader &amp;Header, const DWARFDebugAbbrev *DA, const DWARFSection *RS, const DWARFSection *LocSection, StringRef SS, const DWARFSection &amp;SOS, const DWARFSection *AOS, const DWARFSection &amp;LS, bool LE, bool IsDWO, const DWARFUnitVector &amp;UnitVector)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d0357e44ae99196d6e5a8bcdbfe0977">~DWARFUnit</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac94ea7123c4e4c7c8a1522b862ce552">isLittleEndian</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd5def6886f14df2575567385872bd04">isDWOUnit</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4b745612c1f38ddeeb42af9a4df2d8">getContext</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38f3338ec2a656ffa9ecdbe1992f79d1">getInfoSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af52bec8bfd6fcde07ecb8d04e495b8a0">getOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf/formparams">dwarf::FormParams</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff9ec61643dc22b123715b1ca6a2997">getFormParams</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8579cbbdc6613b150050d23fcc8fc539">getVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27b542dc4852075a40029e6d8d6c764c">getRefAddrByteSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad20e7d5049432cf9e6f7371cc5de6a42">getDwarfOffsetByteSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a061c014d0992c2c47203ab0d53911215">getHeaderSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size in bytes of the parsed unit header. <a href="#a061c014d0992c2c47203ab0d53911215">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23ed28928941964f658de8e78d8fc997">getLength</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8">dwarf::DwarfFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7830b1eb40f6264e196c3329a42cc342">getFormat</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2084980f131a34248e09f10228625e78">getUnitType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af095eaf82934314628b28695068f1a43">isTypeUnit</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95728db13d817152e70779b446728bfc">getAbbrOffset</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae206bea6a70cddb7db54917fa04d8537">getNextUnitOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0eff9bf79f4a6046f709219c6bfc05a">getLineSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1e6c792249b0f4eb1f0d1e3a82c4242">getStringSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc43925b07ed2e19699bda5e49ea4838">getStringOffsetSection</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3527777482c78013e87fa81ad534921e">setSkeletonUnit</a> (DWARFUnit *SU)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb2a6b70dfb07aceb67d788bbf2d7174">getLinkedUnit</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475680697010e75853d3de26b25a7010">setAddrOffsetSection</a> (const DWARFSection *AOS, uint64_t Base)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3699f74be932a3c9e7a7624f02dd8def">getAddrOffsetSectionBase</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a954ccacf225fe012bd76695406c8f4ec">getIndexedAddressOffset</a> (uint64_t Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns offset to the indexed address value inside .debug_addr section. <a href="#a954ccacf225fe012bd76695406c8f4ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcf7af3468ead1789473fd544662751a">updateAddressDieMap</a> (DWARFDie Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively update address to Die map. <a href="#afcf7af3468ead1789473fd544662751a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac360b4709027f4534efa4a4671140ccb">updateVariableDieMap</a> (DWARFDie Die)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Recursively update address to variable Die map. <a href="#ac360b4709027f4534efa4a4671140ccb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b1795b25520fc21034191b03a195b6f">setRangesSection</a> (const DWARFSection *RS, uint64_t Base)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49202f39135b78136444c464cc52e2f5">getLocSectionBase</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9e4e9bb8aca24972f98c4874621bc18">getAddrOffsetSectionItem</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa052142780ad350aef0886c2dbbce7cd">getStringOffsetSectionItem</a> (uint32_t Index) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fdbaae0aa17efabff658831b7c097e8">getDebugInfoExtractor</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29197561ea0758bd952ee855cfafc97a">getStringExtractor</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarflocationtable">DWARFLocationTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c4aa15672adef294b8b6b7c749fd5b5">getLocationTable</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd07b57ab552b82dbbcd795a9c865a4">extractRangeList</a> (uint64_t RangeListOffset, DWARFDebugRangeList &amp;RangeList) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the range list referenced by this compile unit from the .debug_ranges section. <a href="#a9fd07b57ab552b82dbbcd795a9c865a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59ceaf24fba4056aa49e73e33b6a121c">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/stroffsetscontributiondescriptor">StrOffsetsContributionDescriptor</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8842efba37e6e9a30817463c53efa7f">getStringOffsetsTableContribution</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b9442804156cf58ee5d7bd49d4655f8">getDwarfStringOffsetsByteSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a703a75ea31e6a8b397d183b4f6b45d77">getStringOffsetsBase</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a855c2ba52367432d0108492c9b694d90">getAbbreviationsOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclarationset">DWARFAbbreviationDeclarationSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a535b9e1cc27192f7a16a1459333b859c">getAbbreviations</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae800ac93781be66c955244212aaa9e85">getBaseAddress</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a> (bool ExtractUnitDIEOnly=true)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b28f531b56fac2a5bdedea66750519b">getNonSkeletonUnitDIE</a> (bool ExtractUnitDIEOnly=true, StringRef DWOAlternativeLocation={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a610e091c42196cd8bdddce77b7a407e4">getCompilationDir</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0515d7981dbdf5c5031a5512368a03c4">getDWOId</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483218ec45b305b47c7505fa93858969">setDWOId</a> (uint64_t NewID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac462c25594ad9731410df38ff635fb7">findRnglistFromOffset</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector of address ranges resulting from a (possibly encoded) range list starting at a given offset in the appropriate ranges section. <a href="#aac462c25594ad9731410df38ff635fb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8a6f07aa775bd31d5e913f5867af78f">findRnglistFromIndex</a> (uint32_t Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a vector of address ranges retrieved from an encoded range list whose offset is found via a table lookup given an index (DWARF v5 and later). <a href="#ad8a6f07aa775bd31d5e913f5867af78f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29e8a80bfafc6bb58673eacdec89453b">getRnglistOffset</a> (uint32_t Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a rangelist's offset based on an index. <a href="#a29e8a80bfafc6bb58673eacdec89453b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f2cc73e87e1f1a949943a14e14bea4a">getLoclistOffset</a> (uint32_t Index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8fdb8ecb676db124d905f7db91d25e7">collectAddressRanges</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#afc9a8659aea188ea36273a12a45b5929">DWARFLocationExpressionsVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab8397ea715fe1132418fcad480386db">findLoclistFromOffset</a> (uint64_t Offset)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4608e0e7126cfbc1e51312f20041486">getSubroutineForAddress</a> (uint64_t Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns subprogram <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with address range encompassing the provided address. <a href="#ac4608e0e7126cfbc1e51312f20041486">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35662c11ae2356969e328d8115b9d8b2">getVariableForAddress</a> (uint64_t Address)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the address provided. <a href="#a35662c11ae2356969e328d8115b9d8b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86af5dc1ea8da3e443ba72fcf0f9caf5">getInlinedChainForAddress</a> (uint64_t Address, SmallVectorImpl&lt; DWARFDie &gt; &amp;InlinedChain)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getInlinedChainForAddress - fetches inlined chain for a given address. <a href="#a86af5dc1ea8da3e443ba72fcf0f9caf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0b215242a5a89784e1358645ecacdf3">getUnitVector</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> containing this unit. <a href="#ab0b215242a5a89784e1358645ecacdf3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec6a9263e9ba2e5f5045f091731aabc">getNumDIEs</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of DIEs in the unit. <a href="#a0ec6a9263e9ba2e5f5045f091731aabc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6302b02a9f4f9b4837762e44aec89ca3">getDIEIndex</a> (const DWARFDie &amp;D) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector. <a href="#a6302b02a9f4f9b4837762e44aec89ca3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a9ceb07aa8fdeac193c7644be84765">getDIEAtIndex</a> (unsigned Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object at the given index <span class="doxyComputerOutput">Index</span>. <a href="#af1a9ceb07aa8fdeac193c7644be84765">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5655ffd4b682c468befc6e9387d14184">getParent</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2872e5c09f7d6579b324312e8f5f5c6f">getSibling</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07fe3c7b82d0c759f3178527d5c1fa11">getPreviousSibling</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1978540fd6d361e95ff39e0a3f79c4cd">getFirstChild</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63e2dce9605eb71e53e8a5c22dfd713">getLastChild</a> (const DWARFDebugInfoEntry *Die)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54935e3c42396c955484e9ca2bab9081">getDIEForOffset</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object for a given offset <span class="doxyComputerOutput">Offset</span> inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector. <a href="#a54935e3c42396c955484e9ca2bab9081">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a811bebdebe4a92be5bab22a83979dff4">getDIEIndexForOffset</a> (uint64_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index for a given offset <span class="doxyComputerOutput">Offset</span> inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector. <a href="#a811bebdebe4a92be5bab22a83979dff4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae01b486b3131a24d6d9bd0fe146490">getLineTableOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">die_iterator_range</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75d824c5a4838425e2787dde95e47ec">dies</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab09fee6fe726ad640d0b83da558a5ac4">dump</a> (raw_ostream &amp;OS, DIDumpOptions DumpOpts)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29eb6e9604006a962c4d3dc91c6b5c0f">tryExtractDIEsIfNeeded</a> (bool CUDieOnly)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa19e6ee8bd7aee2cdb0877d7e07a5926">getDIEIndex</a> (const DWARFDebugInfoEntry *Die) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of a <span class="doxyComputerOutput">Die</span> entry inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector. <a href="#aa19e6ee8bd7aee2cdb0877d7e07a5926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031e0d9bcb2f5af51da179fc3d2c0165">getDebugInfoEntry</a> (unsigned Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> for the specified index <span class="doxyComputerOutput">Index</span>. <a href="#a031e0d9bcb2f5af51da179fc3d2c0165">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1790d029c849d8cce4869ff39b6b7396">getParentEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a042cc638efbb7ab4559890854afd5179">getSiblingEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2775409266704ae5ffe40b1588a104">getPreviousSiblingEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace915cc7890f9756905f9be5f4ce4f17">getFirstChildEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4662b7516c2006390c013710c6bb3f3">getLastChildEntry</a> (const DWARFDebugInfoEntry *Die) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader">DWARFUnitHeader</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525cad0eda581481dd10ec944237a5ec">getHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/stroffsetscontributiondescriptor">StrOffsetsContributionDescriptor</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b6d5f1979457082b8c187b9f80eb70e">determineStringOffsetsTableContribution</a> (DWARFDataExtractor &amp;DA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the unit's contribution to the string offsets table and determine its length and form. <a href="#a7b6d5f1979457082b8c187b9f80eb70e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/stroffsetscontributiondescriptor">StrOffsetsContributionDescriptor</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a6a6c25f3b3fe3bda5f9cb23892dc0a">determineStringOffsetsTableContributionDWO</a> (DWARFDataExtractor &amp;DA)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find the unit's contribution to the string offsets table and determine its length and form. <a href="#a0a6a6c25f3b3fe3bda5f9cb23892dc0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb44ea55e1d7c1226f184558959e617">getDebugInfoSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Size in bytes of the .debug_info data associated with this compile unit. <a href="#a5cb44ea55e1d7c1226f184558959e617">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33044c09b6c7ca222be8b2ef51f81b28">extractDIEsIfNeeded</a> (bool CUDieOnly)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>extractDIEsIfNeeded - Parses a compile unit and indexes its DIEs if it hasn't already been done <a href="#a33044c09b6c7ca222be8b2ef51f81b28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aede10a43c27380e11ed969deaf6f9ae5">extractDIEsToVector</a> (bool AppendCUDie, bool AppendNonCUDIEs, std::vector&lt; DWARFDebugInfoEntry &gt; &amp;DIEs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>extractDIEsToVector - Appends all parsed DIEs to a vector. <a href="#aede10a43c27380e11ed969deaf6f9ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69bfb213d16a5c63cf2e12abd059612f">clearDIEs</a> (bool KeepCUDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>clearDIEs - Clear parsed DIEs to keep memory usage low. <a href="#a69bfb213d16a5c63cf2e12abd059612f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85899837795e4c1e7be60092635bb72">parseDWO</a> (StringRef AlternativeLocation={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>parseDWO - Parses .dwo file for current compile unit. <a href="#af85899837795e4c1e7be60092635bb72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2659f11f97300e9cce7cc18f59e772cc">Context</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36026ab2ca306386873da62bb4c246b9">InfoSection</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Section containing this <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a>. <a href="#a36026ab2ca306386873da62bb4c246b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader">DWARFUnitHeader</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af68e1ca2e95cc0697c534503c6d73d90">Header</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d6e03f2a868a1de8be0576c4c48159e">Abbrev</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1491cf4dff88a0191a012738624d127a">RangeSection</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3adecf28ef5dccc12e2ef98a98f7b16b">RangeSectionBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e5246a3c791446c13734d768cca596a">LocSectionBase</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarflocationtable">DWARFLocationTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4446c8c9f17b9d39f7bc95f66a25ba25">LocTable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Location table of this unit. <a href="#a4446c8c9f17b9d39f7bc95f66a25ba25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae9ea0ab09bcaf22a75f27ccad831248">LineSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af477d88d0ee6722e5c132710615e35ad">StringSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cde1832df9c2f836f29590bc5fe6c03">StringOffsetSection</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5c4aa8398a4407b43afa3aca5ce0e0f">AddrOffsetSection</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade562540dc20b758c172cc46546aa7f5">SU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c0aea80887951a6fa706671cd214fd">AddrOffsetSectionBase</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce0b47d3f0923a31cf3190f285a8804">IsLittleEndian</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5ab6b4d9d73d3c630586736416ed491">IsDWO</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe733d247273b64c1fc70ba6190ec51c">UnitVector</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/stroffsetscontributiondescriptor">StrOffsetsContributionDescriptor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afce7dd529678138a3bb2e4e605ff4a7c">StringOffsetsTableContribution</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Start, length, and DWARF format of the unit's contribution to the string offsets table (DWARF v5). <a href="#afce7dd529678138a3bb2e4e605ff4a7c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclarationset">DWARFAbbreviationDeclarationSet</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6e9540249fbfb20ff20c683a1b28265">Abbrevs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/object/sectionedaddress">object::SectionedAddress</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b8ecda1c740272947ef7738e904bb8">BaseAddr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdecc8920a8e734da4e17b1eef958c87">DieArray</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The compile unit debug information entry items. <a href="#acdecc8920a8e734da4e17b1eef958c87">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint64_t, std::pair&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8fa4a7fb014f904ca9168f68e1d088a">AddrDieMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from range's start address to end address and corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#aa8fa4a7fb014f904ca9168f68e1d088a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; uint64_t, std::pair&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ba7b5833ccffd8f9eda1997948ea6b">VariableDieMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Map from the location (interpreted DW_AT_location) of a DW_TAG_variable, to the end address and the corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a41ba7b5833ccffd8f9eda1997948ea6b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09cf845eb9d0421f302a2d7ed268f470">RootsParsedForVariables</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab59acfcd22d3772711d851cf9ffb0222">DWO</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addff610c46acd6341bd0fe70dc0f5705">isMatchingUnitTypeAndTag</a> (uint8_t UnitType, dwarf::Tag Tag)</td>
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


<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### die\_iterator\_range {#a94206113c22ed86bdba16fb99d1c1976}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFUnit::die_iterator_range = 
      iterator_range&lt;std::vector&lt;DWARFDebugInfoEntry&gt;::iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFUnit() {#a7a4eac03e9bd7411e28763651863ef34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit::DWARFUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &amp; Context, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; Section, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader">DWARFUnitHeader</a> &amp; Header, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugabbrev">DWARFDebugAbbrev</a> * DA, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * RS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * LocSection, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; SOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * AOS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> &amp; LS, bool LE, bool IsDWO, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> &amp; UnitVector)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a59ceaf24fba4056aa49e73e33b6a121c">clear</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#acb978c8a6ce86f509e73a66e5bf7d811">llvm::DWARFCompileUnit::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#af854109f380b6c8b357945d3fa290522">llvm::DWARFTypeUnit::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#afda0e7f6d7bf42526da3171eea79f92f">llvm::DWARFCompileUnit::DWARFCompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#abcb745ae665bf53d8d2536c01f385acb">llvm::DWARFTypeUnit::DWARFTypeUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4662b7516c2006390c013710c6bb3f3">getLastChildEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aeb2a6b70dfb07aceb67d788bbf2d7174">getLinkedUnit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3527777482c78013e87fa81ad534921e">setSkeletonUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DWARFUnit() {#a2d0357e44ae99196d6e5a8bcdbfe0977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit::~DWARFUnit ()</td>
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



<p>Definition at line 315 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a59ceaf24fba4056aa49e73e33b6a121c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFUnit::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 402 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2c8b9ba6422c57fd4edb9b5771b650d2">llvm::dwarf_linker::parallel::CompileUnit::cleanupDataAfterClonning</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">DWARFUnit</a>.</p>

</div>
</div>

### collectAddressRanges() {#ae8fdb8ecb676db124d905f7db91d25e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFAddressRangesVector &gt; DWARFUnit::collectAddressRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a1eac3980947a504ac089ba80976debda">llvm::DWARFDie::getAddressRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a>.</p>

</div>
</div>

### dies() {#aa75d824c5a4838425e2787dde95e47ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">die_iterator_range llvm::DWARFUnit::dies ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 560 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### dump() {#ab09fee6fe726ad640d0b83da558a5ac4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::DWARFUnit::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 565 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### extractRangeList() {#a9fd07b57ab552b82dbbcd795a9c865a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFUnit::extractRangeList (uint64_t RangeListOffset, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist">DWARFDebugRangeList</a> &amp; RangeList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the range list referenced by this compile unit from the .debug_ranges section.</p>


<p>If the extraction is unsuccessful, an error is returned. Successful extraction requires that the compile unit has already been extracted.</p>


<p>Declaration at line 400 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a25597c272c2c6da035416f2331dccfbd">llvm::DWARFDebugRangeList::extract</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aac462c25594ad9731410df38ff635fb7">findRnglistFromOffset</a>.</p>

</div>
</div>

### findLoclistFromOffset() {#aab8397ea715fe1132418fcad480386db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFLocationExpressionsVector &gt; DWARFUnit::findLoclistFromOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae9e4e9bb8aca24972f98c4874621bc18">getAddrOffsetSectionItem</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae800ac93781be66c955244212aaa9e85">getBaseAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0c4aa15672adef294b8b6b7c749fd5b5">getLocationTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarflocationtable/#acc05bf27e333c6e86262cbe80d95914f">llvm::DWARFLocationTable::visitAbsoluteLocationList</a>.</p>

</div>
</div>

### findRnglistFromIndex() {#ad8a6f07aa775bd31d5e913f5867af78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFAddressRangesVector &gt; DWARFUnit::findRnglistFromIndex (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a vector of address ranges retrieved from an encoded range list whose offset is found via a table lookup given an index (DWARF v5 and later).</p>

<p>Declaration at line 471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aac462c25594ad9731410df38ff635fb7">findRnglistFromOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29e8a80bfafc6bb58673eacdec89453b">getRnglistOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### findRnglistFromOffset() {#aac462c25594ad9731410df38ff635fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFAddressRangesVector &gt; DWARFUnit::findRnglistFromOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a vector of address ranges resulting from a (possibly encoded) range list starting at a given offset in the appropriate ranges section.</p>

<p>Declaration at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 667 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a9fd07b57ab552b82dbbcd795a9c865a4">extractRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttablebase/#a9f56b95c6429c26fbddd56ac096c50ec">llvm::DWARFListTableBase&lt; DWARFListType &gt;::findList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugrangelist/#a988c616ede2f0e4cf1c8c4f5faa554c8">llvm::DWARFDebugRangeList::getAbsoluteRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae800ac93781be66c955244212aaa9e85">getBaseAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8579cbbdc6613b150050d23fcc8fc539">getVersion</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad8a6f07aa775bd31d5e913f5867af78f">findRnglistFromIndex</a>.</p>

</div>
</div>

### getAbbreviations() {#a535b9e1cc27192f7a16a1459333b859c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFAbbreviationDeclarationSet * DWARFUnit::getAbbreviations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1054 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a855c2ba52367432d0108492c9b694d90">getAbbreviationsOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>.</p>

</div>
</div>

### getAbbreviationsOffset() {#a855c2ba52367432d0108492c9b694d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::getAbbreviationsOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a535b9e1cc27192f7a16a1459333b859c">getAbbreviations</a>.</p>

</div>
</div>

### getAbbrOffset() {#a95728db13d817152e70779b446728bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::getAbbrOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>.</p>

</div>
</div>

### getAddressByteSize() {#a320ab482b7d34c3c336762fb0678c44d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFUnit::getAddressByteSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a9fd07b57ab552b82dbbcd795a9c865a4">extractRangeList</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae9e4e9bb8aca24972f98c4874621bc18">getAddrOffsetSectionItem</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1fdbaae0aa17efabff658831b7c097e8">getDebugInfoExtractor</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a954ccacf225fe012bd76695406c8f4ec">getIndexedAddressOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29e8a80bfafc6bb58673eacdec89453b">getRnglistOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">tryExtractDIEsIfNeeded</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">updateVariableDieMap</a>.</p>

</div>
</div>

### getAddrOffsetSectionBase() {#a3699f74be932a3c9e7a7624f02dd8def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARFUnit::getAddrOffsetSectionBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a954ccacf225fe012bd76695406c8f4ec">getIndexedAddressOffset</a>.</p>

</div>
</div>

### getAddrOffsetSectionItem() {#ae9e4e9bb8aca24972f98c4874621bc18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; object::SectionedAddress &gt; DWARFUnit::getAddrOffsetSectionItem (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a88027543aef5a9bc0d82bc5e5e3506c3">llvm::hasSingleElement</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aab8397ea715fe1132418fcad480386db">findLoclistFromOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">updateVariableDieMap</a>.</p>

</div>
</div>

### getBaseAddress() {#ae800ac93781be66c955244212aaa9e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; object::SectionedAddress &gt; DWARFUnit::getBaseAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1068 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a3fcfe121a4dc5b72106bdacb47f3ce1e">llvm::dwarf::toSectionedAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aab8397ea715fe1132418fcad480386db">findLoclistFromOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aac462c25594ad9731410df38ff635fb7">findRnglistFromOffset</a>.</p>

</div>
</div>

### getCompilationDir() {#a610e091c42196cd8bdddce77b7a407e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DWARFUnit::getCompilationDir ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 457 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a2af35f9fb586ccbd0416130e8b3f17aa">llvm::DWARFFormValue::getAsFile</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>.</p>

</div>
</div>

### getContext() {#a2f4b745612c1f38ddeeb42af9a4df2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext &amp; llvm::DWARFUnit::getContext ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#a2af35f9fb586ccbd0416130e8b3f17aa">llvm::DWARFFormValue::getAsFile</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4bbbe4c1e38aa50239589e57e47d0eee">llvm::DWARFDie::getAttributeValueAsReferencedDie</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a107a5c45aec6fd4389339f69720a8608">llvm::DWARFDie::resolveTypeUnitReference</a>.</p>

</div>
</div>

### getDebugInfoExtractor() {#a1fdbaae0aa17efabff658831b7c097e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDataExtractor DWARFUnit::getDebugInfoExtractor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a>.</p>

</div>
</div>

### getDIEAtIndex() {#af1a9ceb07aa8fdeac193c7644be84765}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::DWARFUnit::getDIEAtIndex (unsigned Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object at the given index <span class="doxyComputerOutput">Index</span>.</p>

<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a031e0d9bcb2f5af51da179fc3d2c0165">getDebugInfoEntry</a>.</p>

</div>
</div>

### getDIEForOffset() {#a54935e3c42396c955484e9ca2bab9081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::DWARFUnit::getDIEForOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object for a given offset <span class="doxyComputerOutput">Offset</span> inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector.</p>

<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a811bebdebe4a92be5bab22a83979dff4">getDIEIndexForOffset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4bbbe4c1e38aa50239589e57e47d0eee">llvm::DWARFDie::getAttributeValueAsReferencedDie</a>.</p>

</div>
</div>

### getDIEIndex() {#a6302b02a9f4f9b4837762e44aec89ca3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFUnit::getDIEIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &amp; D)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the index of a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector.</p>


<p>It is illegal to call this method with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that hasn't be created by this unit. In other word, it's illegal to call this method on a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that isn't accessible by following children/sibling links starting from this unit's <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE()</a>.</p>


<p>Definition at line 516 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa19e6ee8bd7aee2cdb0877d7e07a5926">getDIEIndex</a>.</p>

</div>
</div>

### getDIEIndexForOffset() {#a811bebdebe4a92be5bab22a83979dff4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint32_t &gt; llvm::DWARFUnit::getDIEIndexForOffset (uint64_t Offset)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> index for a given offset <span class="doxyComputerOutput">Offset</span> inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector.</p>

<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/die/#ac44e64e0d814099105dde610b11c9914">llvm::DIE::getOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a327a399b9f6ef414a29ddeffba934d26">llvm::partition_point</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a54935e3c42396c955484e9ca2bab9081">getDIEForOffset</a>.</p>

</div>
</div>

### getDwarfOffsetByteSize() {#ad20e7d5049432cf9e6f7371cc5de6a42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFUnit::getDwarfOffsetByteSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getDwarfStringOffsetsByteSize() {#a4b9442804156cf58ee5d7bd49d4655f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFUnit::getDwarfStringOffsetsByteSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 410 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa052142780ad350aef0886c2dbbce7cd">getStringOffsetSectionItem</a>.</p>

</div>
</div>

### getDWOId() {#a0515d7981dbdf5c5031a5512368a03c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARFUnit::getDWOId ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunitheader/#a019949cbf97d8e8564132ed0fbef8d76">llvm::DWARFUnitHeader::getDWOId</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a525cad0eda581481dd10ec944237a5ec">getHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>.</p>

</div>
</div>

### getFirstChild() {#a1978540fd6d361e95ff39e0a3f79c4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFUnit::getFirstChild (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 528 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 984 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ace915cc7890f9756905f9be5f4ce4f17">getFirstChildEntry</a>.</p>

</div>
</div>

### getFormat() {#a7830b1eb40f6264e196c3329a42cc342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::DwarfFormat llvm::DWARFUnit::getFormat ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5f2cc73e87e1f1a949943a14e14bea4a">getLoclistOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29e8a80bfafc6bb58673eacdec89453b">getRnglistOffset</a>.</p>

</div>
</div>

### getFormParams() {#a0ff9ec61643dc22b123715b1ca6a2997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const dwarf::FormParams &amp; llvm::DWARFUnit::getFormParams ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getHeaderSize() {#a061c014d0992c2c47203ab0d53911215}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFUnit::getHeaderSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size in bytes of the parsed unit header.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getIndexedAddressOffset() {#a954ccacf225fe012bd76695406c8f4ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::DWARFUnit::getIndexedAddressOffset (uint64_t Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns offset to the indexed address value inside .debug_addr section.</p>

<p>Definition at line 361 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a3699f74be932a3c9e7a7624f02dd8def">getAddrOffsetSectionBase</a>.</p>

</div>
</div>

### getInfoSection() {#a38f3338ec2a656ffa9ecdbe1992f79d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection &amp; llvm::DWARFUnit::getInfoSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getInlinedChainForAddress() {#a86af5dc1ea8da3e443ba72fcf0f9caf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFUnit::getInlinedChainForAddress (uint64_t Address, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> &gt; &amp; InlinedChain)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getInlinedChainForAddress - fetches inlined chain for a given address.</p>


<p>Returns empty chain if there is no subprogram containing address. The chain is valid as long as parsed compile unit DIEs are not cleared.</p>


<p>Declaration at line 497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2fa3d574c395e0628051860fc9be0463">llvm::DWARFDie::getParent</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4608e0e7126cfbc1e51312f20041486">getSubroutineForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac07a6d11b09b4e2c92e9609b6843e9ea">llvm::DWARFDie::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a63b616e747d955b94fe3ee589a9c1003">llvm::DWARFDie::isSubprogramDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getLastChild() {#af63e2dce9605eb71e53e8a5c22dfd713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFUnit::getLastChild (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1009 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4662b7516c2006390c013710c6bb3f3">getLastChildEntry</a>.</p>

</div>
</div>

### getLength() {#a23ed28928941964f658de8e78d8fc997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::getLength ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>.</p>

</div>
</div>

### getLineSection() {#ac0eff9bf79f4a6046f709219c6bfc05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection &amp; llvm::DWARFUnit::getLineSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getLineTableOffset() {#a6ae01b486b3131a24d6d9bd0fe146490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFUnit::getLineTableOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getLinkedUnit() {#aeb2a6b70dfb07aceb67d788bbf2d7174}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit * llvm::DWARFUnit::getLinkedUnit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">DWARFUnit</a>.</p>

</div>
</div>

### getLocationTable() {#a0c4aa15672adef294b8b6b7c749fd5b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFLocationTable &amp; llvm::DWARFUnit::getLocationTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aab8397ea715fe1132418fcad480386db">findLoclistFromOffset</a>.</p>

</div>
</div>

### getLoclistOffset() {#a5f2cc73e87e1f1a949943a14e14bea4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFUnit::getLoclistOffset (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1219 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7830b1eb40f6264e196c3329a42cc342">getFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader/#a3c1d6e1effdc93963e12868a6c193d49">llvm::DWARFListTableHeader::getOffsetEntry</a>.</p>

</div>
</div>

### getLocSectionBase() {#a49202f39135b78136444c464cc52e2f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::getLocSectionBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getNextUnitOffset() {#ae206bea6a70cddb7db54917fa04d8537}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::getNextUnitOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>.</p>

</div>
</div>

### getNonSkeletonUnitDIE() {#a1b28f531b56fac2a5bdedea66750519b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::DWARFUnit::getNonSkeletonUnitDIE (bool ExtractUnitDIEOnly=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> DWOAlternativeLocation={})</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>.</p>

</div>
</div>

### getNumDIEs() {#a0ec6a9263e9ba2e5f5045f091731aabc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DWARFUnit::getNumDIEs ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of DIEs in the unit.</p>


<p>Parses the unit if necessary.</p>


<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getOffset() {#af52bec8bfd6fcde07ecb8d04e495b8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::getOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ae40361c138fe76519f53bc8366a281c7">llvm::dwarf_linker::parallel::CompileUnit::resolveDIEReference</a>.</p>

</div>
</div>

### getParent() {#a5655ffd4b682c468befc6e9387d14184}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFUnit::getParent (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 525 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1790d029c849d8cce4869ff39b6b7396">getParentEntry</a>.</p>

</div>
</div>

### getPreviousSibling() {#a07fe3c7b82d0c759f3178527d5c1fa11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFUnit::getPreviousSibling (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 527 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aaf2775409266704ae5ffe40b1588a104">getPreviousSiblingEntry</a>.</p>

</div>
</div>

### getRefAddrByteSize() {#a27b542dc4852075a40029e6d8d6c764c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFUnit::getRefAddrByteSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 327 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getRnglistOffset() {#a29e8a80bfafc6bb58673eacdec89453b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFUnit::getRnglistOffset (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a rangelist's offset based on an index.</p>


<p>The index designates an entry in the rangelist table's offset array and is supplied by DW_FORM_rnglistx.</p>


<p>Declaration at line 476 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7830b1eb40f6264e196c3329a42cc342">getFormat</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader/#a3c1d6e1effdc93963e12868a6c193d49">llvm::DWARFListTableHeader::getOffsetEntry</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ad8a6f07aa775bd31d5e913f5867af78f">findRnglistFromIndex</a>.</p>

</div>
</div>

### getSibling() {#a2872e5c09f7d6579b324312e8f5f5c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFUnit::getSibling (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 526 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 923 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a042cc638efbb7ab4559890854afd5179">getSiblingEntry</a>.</p>

</div>
</div>

### getStringExtractor() {#a29197561ea0758bd952ee855cfafc97a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataExtractor llvm::DWARFUnit::getStringExtractor ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 390 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getStringOffsetsBase() {#a703a75ea31e6a8b397d183b4f6b45d77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::getStringOffsetsBase ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa052142780ad350aef0886c2dbbce7cd">getStringOffsetSectionItem</a>.</p>

</div>
</div>

### getStringOffsetSection() {#abc43925b07ed2e19699bda5e49ea4838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection &amp; llvm::DWARFUnit::getStringOffsetSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getStringOffsetSectionItem() {#aa052142780ad350aef0886c2dbbce7cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; DWARFUnit::getStringOffsetSectionItem (uint32_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a4b9442804156cf58ee5d7bd49d4655f8">getDwarfStringOffsetsByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a703a75ea31e6a8b397d183b4f6b45d77">getStringOffsetsBase</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getStringOffsetsTableContribution() {#ae8842efba37e6e9a30817463c53efa7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; StrOffsetsContributionDescriptor &gt; &amp; llvm::DWARFUnit::getStringOffsetsTableContribution ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getStringSection() {#ac1e6c792249b0f4eb1f0d1e3a82c4242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DWARFUnit::getStringSection ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### getSubroutineForAddress() {#ac4608e0e7126cfbc1e51312f20041486}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFUnit::getSubroutineForAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns subprogram <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> with address range encompassing the provided address.</p>


<p>The pointer is alive as long as parsed compile unit DIEs are not cleared.</p>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 763 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afcf7af3468ead1789473fd544662751a">updateAddressDieMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ac3b09300d5e9ca1002c2a91191aee71b">llvm::DWARFContext::getDIEsForAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a86af5dc1ea8da3e443ba72fcf0f9caf5">getInlinedChainForAddress</a>.</p>

</div>
</div>

### getUnitDIE() {#a2b5f2734488f7b1b52e982683675df24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie llvm::DWARFUnit::getUnitDIE (bool ExtractUnitDIEOnly=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae8fdb8ecb676db124d905f7db91d25e7">collectAddressRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7b6d5f1979457082b8c187b9f80eb70e">determineStringOffsetsTableContribution</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae800ac93781be66c955244212aaa9e85">getBaseAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a610e091c42196cd8bdddce77b7a407e4">getCompilationDir</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#a640543dfd6a85c0f9910ecf22faca02c">llvm::dwarf_linker::classic::CompileUnit::getLanguage</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4662b7516c2006390c013710c6bb3f3">getLastChildEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4608e0e7126cfbc1e51312f20041486">getSubroutineForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#a6d3d35230825470499dc48f866facb9a">llvm::dwarf_linker::classic::CompileUnit::getSysRoot</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a35662c11ae2356969e328d8115b9d8b2">getVariableForAddress</a>.</p>

</div>
</div>

### getUnitType() {#a2084980f131a34248e09f10228625e78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::DWARFUnit::getUnitType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>.</p>

</div>
</div>

### getUnitVector() {#ab0b215242a5a89784e1358645ecacdf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitVector &amp; llvm::DWARFUnit::getUnitVector ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector">DWARFUnitVector</a> containing this unit.</p>

<p>Definition at line 501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a4bbbe4c1e38aa50239589e57e47d0eee">llvm::DWARFDie::getAttributeValueAsReferencedDie</a>.</p>

</div>
</div>

### getVariableForAddress() {#a35662c11ae2356969e328d8115b9d8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFUnit::getVariableForAddress (uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns variable <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> for the address provided.</p>


<p>The pointer is alive as long as parsed compile unit DIEs are not cleared.</p>


<p>Declaration at line 492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 851 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">updateVariableDieMap</a>.</p>

</div>
</div>

### getVersion() {#a8579cbbdc6613b150050d23fcc8fc539}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::DWARFUnit::getVersion ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0a6a6c25f3b3fe3bda5f9cb23892dc0a">determineStringOffsetsTableContributionDWO</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aac462c25594ad9731410df38ff635fb7">findRnglistFromOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">tryExtractDIEsIfNeeded</a>.</p>

</div>
</div>

### isDWOUnit() {#afd5def6886f14df2575567385872bd04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFUnit::isDWOUnit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ab014307b03ade42770de6ed2f827630b">llvm::gsym::DwarfTransformer::convert</a> and <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>.</p>

</div>
</div>

### isLittleEndian() {#aac94ea7123c4e4c7c8a1522b862ce552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFUnit::isLittleEndian ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">updateVariableDieMap</a>.</p>

</div>
</div>

### isTypeUnit() {#af095eaf82934314628b28695068f1a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFUnit::isTypeUnit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### setAddrOffsetSection() {#a475680697010e75853d3de26b25a7010}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFUnit::setAddrOffsetSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * AOS, uint64_t Base)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>.</p>

</div>
</div>

### setDWOId() {#a483218ec45b305b47c7505fa93858969}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFUnit::setDWOId (uint64_t NewID)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### setRangesSection() {#a4b1795b25520fc21034191b03a195b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFUnit::setRangesSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfsection">DWARFSection</a> * RS, uint64_t Base)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">tryExtractDIEsIfNeeded</a>.</p>

</div>
</div>

### setSkeletonUnit() {#a3527777482c78013e87fa81ad534921e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DWARFUnit::setSkeletonUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * SU)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">DWARFUnit</a>.</p>

</div>
</div>

### tryExtractDIEsIfNeeded() {#a29eb6e9604006a962c4d3dc91c6b5c0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DWARFUnit::tryExtractDIEsIfNeeded (bool CUDieOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 567 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7b6d5f1979457082b8c187b9f80eb70e">determineStringOffsetsTableContribution</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0a6a6c25f3b3fe3bda5f9cb23892dc0a">determineStringOffsetsTableContributionDWO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a52d529efd96454b48642563c5f78e242a3c17e61a3717834d08557468dd5dd721">llvm::DW_SECT_EXT_LOC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a315f90678bfa85d85d71a9dd12d5457a">llvm::DWARFDie::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflisttableheader/#a1374388723b168fd14a77c5188d4a7db">llvm::DWARFListTableHeader::getHeaderSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8579cbbdc6613b150050d23fcc8fc539">getVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a4b1795b25520fc21034191b03a195b6f">setRangesSection</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a966c7097853fffeaf2746f5d58861f36">llvm::dwarf::toSectionOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad06d74e24faba91639ef782ef7291c3d">llvm::toString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>

</div>
</div>

### updateAddressDieMap() {#afcf7af3468ead1789473fd544662751a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFUnit::updateAddressDieMap (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively update address to Die map.</p>

<p>Declaration at line 370 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 732 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a1eac3980947a504ac089ba80976debda">llvm::DWARFDie::getAddressRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a9eecd422d9c6bd6653dd3492367d3aa3">llvm::DWARFDie::getFirstChild</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a597b29132ac81f9ba70af9d6fb52cc45">llvm::DWARFDie::getSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a5cb799dc32cfff9bf946923f4775550b">llvm::DWARFDie::isSubroutineDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afcf7af3468ead1789473fd544662751a">updateAddressDieMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac4608e0e7126cfbc1e51312f20041486">getSubroutineForAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afcf7af3468ead1789473fd544662751a">updateAddressDieMap</a>.</p>

</div>
</div>

### updateVariableDieMap() {#ac360b4709027f4534efa4a4671140ccb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFUnit::updateVariableDieMap (<a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> Die)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Recursively update address to variable Die map.</p>

<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#aaaa906e7447d4fa5b6b5adf6fefdb1c3">llvm::DWARFExpression::begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfexpression/#a249b4ed19ed8ab2457457d9e1317c710">llvm::DWARFExpression::end</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a320ab482b7d34c3c336762fb0678c44d">getAddressByteSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae9e4e9bb8aca24972f98c4874621bc18">getAddrOffsetSectionItem</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a2343cb0aab23f03ea5e28ea535894dd1">llvm::DWARFDie::getAttributeValueAsReferencedDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac17a520cef18422636f0fbdd13061acf">llvm::DWARFDie::getLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#ac07a6d11b09b4e2c92e9609b6843e9ea">llvm::DWARFDie::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#a778b64ccbeb836841eb9b35bbe91e3c8">llvm::DWARFDie::getTypeSize</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aac94ea7123c4e4c7c8a1522b862ce552">isLittleEndian</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a72f3beb3e0825cf70183d525cfe4be31">llvm::dwarf::isType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">updateVariableDieMap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a35662c11ae2356969e328d8115b9d8b2">getVariableForAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">updateVariableDieMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### determineStringOffsetsTableContribution() {#a7b6d5f1979457082b8c187b9f80eb70e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; StrOffsetsContributionDescriptor &gt; &gt; DWARFUnit::determineStringOffsetsTableContribution (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; DA)</td>
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

<p>Find the unit's contribution to the string offsets table and determine its length and form.</p>


<p>The given offset is expected to be derived from the unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>'s DW_AT_str_offsets_base attribute.</p>


<p>Declaration at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1159 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a086e9fbdb06276db7753101a08a63adf">llvm::find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp/#af8f3fb13a2f0b9729047f529665fc751">parseDWARFStringOffsetsTableHeader</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a966c7097853fffeaf2746f5d58861f36">llvm::dwarf::toSectionOffset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">tryExtractDIEsIfNeeded</a>.</p>

</div>
</div>

### determineStringOffsetsTableContributionDWO() {#a0a6a6c25f3b3fe3bda5f9cb23892dc0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::optional&lt; StrOffsetsContributionDescriptor &gt; &gt; DWARFUnit::determineStringOffsetsTableContributionDWO (<a href="/web-llvm/docs/api/classes/llvm/dwarfdataextractor">DWARFDataExtractor</a> &amp; DA)</td>
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

<p>Find the unit's contribution to the string offsets table and determine its length and form.</p>


<p>The given offset is expected to be 0 in a dwo file or, in a dwp file, the start of the unit's contribution to the string offsets table section (as determined by the index table).</p>


<p>Declaration at line 305 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1172 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a79a43a947d26afb3f2a388f2f7a3a8c8a63265bb5719678b401b0abd0ed5ddd76">llvm::dwarf::DWARF32</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a8579cbbdc6613b150050d23fcc8fc539">getVersion</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp/#af8f3fb13a2f0b9729047f529665fc751">parseDWARFStringOffsetsTableHeader</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">tryExtractDIEsIfNeeded</a>.</p>

</div>
</div>

### getDebugInfoEntry() {#a031e0d9bcb2f5af51da179fc3d2c0165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * llvm::DWARFUnit::getDebugInfoEntry (unsigned Index)</td>
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

<p>Return <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> for the specified index <span class="doxyComputerOutput">Index</span>.</p>

<p>Definition at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af1a9ceb07aa8fdeac193c7644be84765">getDIEAtIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1790d029c849d8cce4869ff39b6b7396">getParentEntry</a>.</p>

</div>
</div>

### getDIEIndex() {#aa19e6ee8bd7aee2cdb0877d7e07a5926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DWARFUnit::getDIEIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
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

<p>Return the index of a <span class="doxyComputerOutput">Die</span> entry inside the unit's <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> vector.</p>


<p>It is illegal to call this method with a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that hasn't be created by this unit. In other word, it's illegal to call this method on a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that isn't accessible by following children/sibling links starting from this unit's <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE()</a>.</p>


<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a6302b02a9f4f9b4837762e44aec89ca3">getDIEIndex</a>, <a href="/web-llvm/docs/api/groups/group/#ga67e10343676779815d39ecb9f3494161">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#ga46715474259d177dfee3f64cb84060b9">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#gaebaf347b4df991192eb43b3f5ec6982d">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#ga4d4950c415f9a38bf821dc4fac3d1fa3">llvm::dwarf_linker::parallel::CompileUnit::getDIEInfo</a>, <a href="/web-llvm/docs/api/groups/group/#ga24d254de081807f2007f1791d41dbcc2">llvm::dwarf_linker::parallel::CompileUnit::getDieOutOffset</a>, <a href="/web-llvm/docs/api/groups/group/#ga78fda22e9740aea1e9dad0b83f09b667">llvm::dwarf_linker::parallel::CompileUnit::getDieTypeEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ace915cc7890f9756905f9be5f4ce4f17">getFirstChildEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/compileunit/#a54bfcabd5abd73941b6f69aa1937ae5a">llvm::dwarf_linker::classic::CompileUnit::getInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab4662b7516c2006390c013710c6bb3f3">getLastChildEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aaf2775409266704ae5ffe40b1588a104">getPreviousSiblingEntry</a>, <a href="/web-llvm/docs/api/groups/group/#gaa4bca7959b19725916051fad326d8ddf">llvm::dwarf_linker::parallel::CompileUnit::setDieTypeEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/declcontext/#ae30b2bbf9086ea752acb7a645fc6e688">llvm::dwarf_linker::classic::DeclContext::setLastSeenDIE</a>.</p>

</div>
</div>

### getFirstChildEntry() {#ace915cc7890f9756905f9be5f4ce4f17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * DWARFUnit::getFirstChildEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
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



<p>Declaration at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 992 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa19e6ee8bd7aee2cdb0877d7e07a5926">getDIEIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#ac862abc22413dd0a1fe6bdf6b9cb26a6">llvm::DWARFDebugInfoEntry::hasChildren</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a1978540fd6d361e95ff39e0a3f79c4cd">getFirstChild</a>.</p>

</div>
</div>

### getHeader() {#a525cad0eda581481dd10ec944237a5ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitHeader &amp; llvm::DWARFUnit::getHeader ()</td>
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



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a0515d7981dbdf5c5031a5512368a03c4">getDWOId</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#adc22be0c6b0ce38d53fd0b4683bb6fec">llvm::DWARFTypeUnit::getTypeHash</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a618cd83987813c41dca4cdb74b2b0f1a">llvm::DWARFTypeUnit::getTypeOffset</a>.</p>

</div>
</div>

### getLastChildEntry() {#ab4662b7516c2006390c013710c6bb3f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * DWARFUnit::getLastChildEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
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



<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a7a4eac03e9bd7411e28763651863ef34">DWARFUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa19e6ee8bd7aee2cdb0877d7e07a5926">getDIEIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a6987befdd1df06ab5e76eed81056cac2">llvm::DWARFDebugInfoEntry::getSiblingIdx</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsparsing/#ga5e36554e194e99d7da32c35d16ba453a">llvm::dwarf::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2b5f2734488f7b1b52e982683675df24">getUnitDIE</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#ac862abc22413dd0a1fe6bdf6b9cb26a6">llvm::DWARFDebugInfoEntry::hasChildren</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#af63e2dce9605eb71e53e8a5c22dfd713">getLastChild</a>.</p>

</div>
</div>

### getParentEntry() {#a1790d029c849d8cce4869ff39b6b7396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * DWARFUnit::getParentEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
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



<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 909 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a031e0d9bcb2f5af51da179fc3d2c0165">getDebugInfoEntry</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#ab9761bc1cfe0e7e41b91d4e590df92e4">llvm::DWARFDebugInfoEntry::getParentIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a5655ffd4b682c468befc6e9387d14184">getParent</a>.</p>

</div>
</div>

### getPreviousSiblingEntry() {#aaf2775409266704ae5ffe40b1588a104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * DWARFUnit::getPreviousSiblingEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
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



<p>Declaration at line 286 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#aa19e6ee8bd7aee2cdb0877d7e07a5926">getDIEIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#ab9761bc1cfe0e7e41b91d4e590df92e4">llvm::DWARFDebugInfoEntry::getParentIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a07fe3c7b82d0c759f3178527d5c1fa11">getPreviousSibling</a>.</p>

</div>
</div>

### getSiblingEntry() {#a042cc638efbb7ab4559890854afd5179}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * DWARFUnit::getSiblingEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * Die)</td>
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



<p>Declaration at line 284 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 931 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry/#a6987befdd1df06ab5e76eed81056cac2">llvm::DWARFDebugInfoEntry::getSiblingIdx</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2872e5c09f7d6579b324312e8f5f5c6f">getSibling</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### clearDIEs() {#a69bfb213d16a5c63cf2e12abd059612f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFUnit::clearDIEs (bool KeepCUDie)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>clearDIEs - Clear parsed DIEs to keep memory usage low.</p>

<p>Declaration at line 585 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>

</div>
</div>

### extractDIEsIfNeeded() {#a33044c09b6c7ca222be8b2ef51f81b28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFUnit::extractDIEsIfNeeded (bool CUDieOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>extractDIEsIfNeeded - Parses a compile unit and indexes its DIEs if it hasn't already been done</p>

<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 493 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>

</div>
</div>

### extractDIEsToVector() {#aede10a43c27380e11ed969deaf6f9ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFUnit::extractDIEsToVector (bool AppendCUDie, bool AppendNonCUDIEs, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> &gt; &amp; DIEs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>extractDIEsToVector - Appends all parsed DIEs to a vector.</p>

<p>Declaration at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 405 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>

</div>
</div>

### getDebugInfoSize() {#a5cb44ea55e1d7c1226f184558959e617}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::DWARFUnit::getDebugInfoSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Size in bytes of the .debug_info data associated with this compile unit.</p>

<p>Definition at line 571 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### parseDWO() {#af85899837795e4c1e7be60092635bb72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFUnit::parseDWO (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> AlternativeLocation={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>parseDWO - Parses .dwo file for current compile unit.</p>


<p>Returns true if it was actually constructed. The <span class="doxyComputerOutput">AlternativeLocation</span> specifies an alternative location to get the DWARF context for the DWO object; this is the case when it has been moved from its original location.</p>


<p>Declaration at line 592 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>, definition at line 603 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Abbrev {#a9d6e03f2a868a1de8be0576c4c48159e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugAbbrev* llvm::DWARFUnit::Abbrev</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### Abbrevs {#ac6e9540249fbfb20ff20c683a1b28265}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFAbbreviationDeclarationSet* llvm::DWARFUnit::Abbrevs</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### AddrDieMap {#aa8fa4a7fb014f904ca9168f68e1d088a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint64_t, std::pair&lt;uint64_t, DWARFDie&gt; &gt; llvm::DWARFUnit::AddrDieMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from range's start address to end address and corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/intervalmap">IntervalMap</a> does not support range removal, as a result, we use the std::map::upper_bound for address range lookup.</p>


<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### AddrOffsetSection {#af5c4aa8398a4407b43afa3aca5ce0e0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection* llvm::DWARFUnit::AddrOffsetSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### AddrOffsetSectionBase {#a12c0aea80887951a6fa706671cd214fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::DWARFUnit::AddrOffsetSectionBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### BaseAddr {#a92b8ecda1c740272947ef7738e904bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;object::SectionedAddress&gt; llvm::DWARFUnit::BaseAddr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### Context {#a2659f11f97300e9cce7cc18f59e772cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFContext&amp; llvm::DWARFUnit::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### DieArray {#acdecc8920a8e734da4e17b1eef958c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DWARFDebugInfoEntry&gt; llvm::DWARFUnit::DieArray</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The compile unit debug information entry items.</p>

<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### DWO {#ab59acfcd22d3772711d851cf9ffb0222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;DWARFUnit&gt; llvm::DWARFUnit::DWO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### Header {#af68e1ca2e95cc0697c534503c6d73d90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnitHeader llvm::DWARFUnit::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### InfoSection {#a36026ab2ca306386873da62bb4c246b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection&amp; llvm::DWARFUnit::InfoSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Section containing this <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a>.</p>

<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### IsDWO {#ac5ab6b4d9d73d3c630586736416ed491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFUnit::IsDWO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### IsLittleEndian {#afce0b47d3f0923a31cf3190f285a8804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFUnit::IsLittleEndian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### LineSection {#aae9ea0ab09bcaf22a75f27ccad831248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection&amp; llvm::DWARFUnit::LineSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### LocSectionBase {#a8e5246a3c791446c13734d768cca596a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::LocSectionBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### LocTable {#a4446c8c9f17b9d39f7bc95f66a25ba25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFLocationTable&gt; llvm::DWARFUnit::LocTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Location table of this unit.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### RangeSection {#a1491cf4dff88a0191a012738624d127a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection* llvm::DWARFUnit::RangeSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### RangeSectionBase {#a3adecf28ef5dccc12e2ef98a98f7b16b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFUnit::RangeSectionBase</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### RootsParsedForVariables {#a09cf845eb9d0421f302a2d7ed268f470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseSet&lt;uint64_t&gt; llvm::DWARFUnit::RootsParsedForVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### StringOffsetSection {#a0cde1832df9c2f836f29590bc5fe6c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFSection&amp; llvm::DWARFUnit::StringOffsetSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### StringOffsetsTableContribution {#afce7dd529678138a3bb2e4e605ff4a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StrOffsetsContributionDescriptor&gt; llvm::DWARFUnit::StringOffsetsTableContribution</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Start, length, and DWARF format of the unit's contribution to the string offsets table (DWARF v5).</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### StringSection {#af477d88d0ee6722e5c132710615e35ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::DWARFUnit::StringSection</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### SU {#ade562540dc20b758c172cc46546aa7f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit* llvm::DWARFUnit::SU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### UnitVector {#abe733d247273b64c1fc70ba6190ec51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFUnitVector&amp; llvm::DWARFUnit::UnitVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

### VariableDieMap {#a41ba7b5833ccffd8f9eda1997948ea6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;uint64_t, std::pair&lt;uint64_t, DWARFDie&gt; &gt; llvm::DWARFUnit::VariableDieMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Map from the location (interpreted DW_AT_location) of a DW_TAG_variable, to the end address and the corresponding <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isMatchingUnitTypeAndTag() {#addff610c46acd6341bd0fe70dc0f5705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFUnit::isMatchingUnitTypeAndTag (uint8_t UnitType, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a> Tag)</td>
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



<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a439f48d703b146ae8f586464c53a98c4">llvm::dwarf::isUnitType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfunit-h">DWARFUnit.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfunit-cpp">DWARFUnit.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
