---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarfdie
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFDie` Class Reference

<p>Utility class that carries the DWARF compile/type unit and the debug info entry in an object. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DWARFDie { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">llvm/DebugInfo/DWARF/DWARFDie.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a652a8c8f9e1d6fe9889aa451f290c65b">DWARFFormValue</a> = <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">llvm::DWARFFormValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a> ()=default</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a190323ddcb644bbeeae80c6c498c799f">DWARFDie</a> (DWARFUnit *Unit, const DWARFDebugInfoEntry *D)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad12709d83cc62353d47c5bbb059f1ebe">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41fc5e2ca3d059c98029728b2677be44">getDebugInfoEntry</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4030d97efbcfaf77b80c112cd27c4214">getDwarfUnit</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfabbreviationdeclaration">DWARFAbbreviationDeclaration</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">getAbbreviationDeclarationPtr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the abbreviation declaration for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">getOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the absolute offset into the debug info or types section. <a href="#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac07a6d11b09b4e2c92e9609b6843e9ea">getTag</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49bee858d2b063e9cfe14ae41903f3b9">hasChildren</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8db424aa6577ea2c055ee823549f3d">isNULL</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true for a valid <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that terminates a sibling chain. <a href="#acd8db424aa6577ea2c055ee823549f3d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b616e747d955b94fe3ee589a9c1003">isSubprogramDIE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represents a subprogram (not inlined). <a href="#a63b616e747d955b94fe3ee589a9c1003">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cb799dc32cfff9bf946923f4775550b">isSubroutineDIE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represents a subprogram or an inlined subroutine. <a href="#a5cb799dc32cfff9bf946923f4775550b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fa3d574c395e0628051860fc9be0463">getParent</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the parent of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object. <a href="#a2fa3d574c395e0628051860fc9be0463">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a597b29132ac81f9ba70af9d6fb52cc45">getSibling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the sibling of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object. <a href="#a597b29132ac81f9ba70af9d6fb52cc45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87dc06a48727e53f283cf3b6484302bc">getPreviousSibling</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the previous sibling of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object. <a href="#a87dc06a48727e53f283cf3b6484302bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eecd422d9c6bd6653dd3492367d3aa3">getFirstChild</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the first child of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object. <a href="#a9eecd422d9c6bd6653dd3492367d3aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8523c1cf66285db2aa7d5f21cf86d001">getLastChild</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the last child of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object. <a href="#a8523c1cf66285db2aa7d5f21cf86d001">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a> (raw_ostream &amp;OS, unsigned indent=0, DIDumpOptions DumpOpts=DIDumpOptions()) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and all of its attributes to the supplied stream. <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61d3b80309ad8e1497b9decb9b16c9f5">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenience zero-argument overload for debugging. <a href="#a61d3b80309ad8e1497b9decb9b16c9f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a652a8c8f9e1d6fe9889aa451f290c65b">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a> (dwarf::Attribute Attr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the specified attribute from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a315f90678bfa85d85d71a9dd12d5457a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a652a8c8f9e1d6fe9889aa451f290c65b">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2631f26350dc3818a78b34b448d777">find</a> (ArrayRef&lt; dwarf::Attribute &gt; Attrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the first value of any attribute in Attrs from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a0d2631f26350dc3818a78b34b448d777">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a652a8c8f9e1d6fe9889aa451f290c65b">DWARFFormValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63fa5eea47d71eee71631388500cc8e5">findRecursively</a> (ArrayRef&lt; dwarf::Attribute &gt; Attrs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the first value of any attribute in Attrs from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and recurse into any DW_AT_specification or DW_AT_abstract_origin referenced DIEs. <a href="#a63fa5eea47d71eee71631388500cc8e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2343cb0aab23f03ea5e28ea535894dd1">getAttributeValueAsReferencedDie</a> (dwarf::Attribute Attr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the specified attribute from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> as the referenced <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a2343cb0aab23f03ea5e28ea535894dd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bbbe4c1e38aa50239589e57e47d0eee">getAttributeValueAsReferencedDie</a> (const DWARFFormValue &amp;V) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a107a5c45aec6fd4389339f69720a8608">resolveTypeUnitReference</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e41a18c9f51cedd4178dc02be89e918">resolveReferencedType</a> (dwarf::Attribute Attr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4cc1e18f2073a11bda5d0cc37cb7e12">resolveReferencedType</a> (const DWARFFormValue &amp;V) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48523a7732959ffeffcdbfaaf5e1578">getRangesBaseAttribute</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract the range base attribute from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> as absolute section offset. <a href="#ac48523a7732959ffeffcdbfaaf5e1578">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11debcb2a343bba0cb48f2bbae5e47c7">getLocBaseAttribute</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a8f3e9af7915e4b0b10f9e17de63ca">getHighPC</a> (uint64_t LowPC) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the DW_AT_high_pc attribute value as an address. <a href="#a75a8f3e9af7915e4b0b10f9e17de63ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608a08ce1fda97817fddbc8b82b0b622">getLowAndHighPC</a> (uint64_t &amp;LowPC, uint64_t &amp;HighPC, uint64_t &amp;SectionIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves DW_AT_low_pc and DW_AT_high_pc from <a href="/web-llvm/docs/api/namespaces/cu">CU</a>. <a href="#a608a08ce1fda97817fddbc8b82b0b622">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#af7b7409cf7c2a265eb671b0023fb9ebf">DWARFAddressRangesVector</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1eac3980947a504ac089ba80976debda">getAddressRanges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the address ranges for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a1eac3980947a504ac089ba80976debda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d3f031c8cae763003080ab17c8ea24">addressRangeContainsAddress</a> (const uint64_t Address) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7ecc2f5b797f131f8932034e32d77c3">getLanguage</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac17a520cef18422636f0fbdd13061acf">getLocations</a> (dwarf::Attribute Attr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f96d333a71d8a20a5ecb501f07b16c">getSubroutineName</a> (DINameKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represents a subprogram (or inlined subroutine), returns its mangled name (or short name, if mangled is missing). <a href="#a48f96d333a71d8a20a5ecb501f07b16c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a834590fd64e02e844dd117b380ab819b">getName</a> (DINameKind Kind) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> name resolving DW_AT_specification or DW_AT_abstract_origin references if necessary. <a href="#a834590fd64e02e844dd117b380ab819b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0095e307c6632ded142272356d210e76">getFullName</a> (raw_string_ostream &amp;, std::string *OriginalFullName=nullptr) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a183b9a712f7e4beb9b21671ce343c960">getShortName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> short name resolving DW_AT_specification or DW_AT_abstract_origin references if necessary. <a href="#a183b9a712f7e4beb9b21671ce343c960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0e347575bcc3e0fd9caa27e1edfadef">getLinkageName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> linkage name resolving DW_AT_specification or DW_AT_abstract_origin references if necessary. <a href="#ac0e347575bcc3e0fd9caa27e1edfadef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60164fdf3076c81c5c5ddce03657dc7">getDeclLine</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the declaration line (start line) for a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, assuming it specifies a subprogram. <a href="#aa60164fdf3076c81c5c5ddce03657dc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d3dccb6b4b6b618de926e3863327b49">getDeclFile</a> (DILineInfoSpecifier::FileLineInfoKind Kind) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629935bec1902c4115188af1c5a6aeb3">getCallerFrame</a> (uint32_t &amp;CallFile, uint32_t &amp;CallLine, uint32_t &amp;CallColumn, uint32_t &amp;CallDiscriminator) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves values of DW_AT_call_file, DW_AT_call_line and DW_AT_call_column from <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (or zeroes if they are missing). <a href="#a629935bec1902c4115188af1c5a6aeb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/attribute-iterator">attribute_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebfc0d0a2a6ce5273bef574e0b018fda">attributes</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an iterator range to all attributes in the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> only. <a href="#aebfc0d0a2a6ce5273bef574e0b018fda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a778b64ccbeb836841eb9b35bbe91e3c8">getTypeSize</a> (uint64_t PointerSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the type size (in bytes) for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a778b64ccbeb836841eb9b35bbe91e3c8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie/iterator">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956b9b7191bfe0703399bf6bf2538016">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfdie/iterator">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d55a09bfdc79ab47ae45890102e2f6c">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::reverse_iterator&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/iterator">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202ebee994e49307c789e43b1d3dcd01">rbegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::reverse_iterator&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/iterator">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc3fb758b3d08b11e728b3df67788b5">rend</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/iterator">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fa7cbc55eb0808d9fc434ef3efb5bca">children</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6297c71f451a8b9fc960b3a9ed482047">U</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1206baf8b74176b0563a8223b86421ed">Die</a> = nullptr</td>
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

<p>Utility class that carries the DWARF compile/type unit and the debug info entry in an object.</p>


<p>When accessing information from a debug info entry we always need to DWARF compile/type unit in order to extract the info correctly as some information is relative to the compile/type unit. Prior to this class the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> and the <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> was passed around separately and there was the possibility for error if the wrong <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> was used to extract a unit relative offset. This class helps to ensure that this doesn't happen and also simplifies the attribute extraction calls by not having to specify the <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> for each call.</p>


<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### DWARFFormValue {#a652a8c8f9e1d6fe9889aa451f290c65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::DWARFDie::DWARFFormValue =  llvm::DWARFFormValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFDie() {#a8d8e0bb75600c92e2c135918ce4a82b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDie::DWARFDie ()</td>
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



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/attribute-iterator/#a2490c902cfb844522cd43c29fdc3f80e">llvm::DWARFDie::attribute_iterator::attribute_iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/attribute-iterator/#a9680f78c02dbc8d42ac84767e7e30e31">llvm::DWARFDie::attribute_iterator::attribute_iterator</a>, <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="#a63fa5eea47d71eee71631388500cc8e5">findRecursively</a>, <a href="#a4bbbe4c1e38aa50239589e57e47d0eee">getAttributeValueAsReferencedDie</a>, <a href="#a2343cb0aab23f03ea5e28ea535894dd1">getAttributeValueAsReferencedDie</a>, <a href="#a9eecd422d9c6bd6653dd3492367d3aa3">getFirstChild</a>, <a href="#a8523c1cf66285db2aa7d5f21cf86d001">getLastChild</a>, <a href="#a2fa3d574c395e0628051860fc9be0463">getParent</a>, <a href="#a87dc06a48727e53f283cf3b6484302bc">getPreviousSibling</a>, <a href="#a597b29132ac81f9ba70af9d6fb52cc45">getSibling</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/iterator/#a57a897fc4cf07011e2474af5fd580f87">llvm::DWARFDie::iterator::iterator</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/iterator/#ad7935c33e41ea869c18ae7b923c5be81">llvm::DWARFDie::iterator::operator*</a>, <a href="#ab4cc1e18f2073a11bda5d0cc37cb7e12">resolveReferencedType</a>, <a href="#a7e41a18c9f51cedd4178dc02be89e918">resolveReferencedType</a> and <a href="#a107a5c45aec6fd4389339f69720a8608">resolveTypeUnitReference</a>.</p>

</div>
</div>

### DWARFDie() {#a190323ddcb644bbeeae80c6c498c799f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDie::DWARFDie (<a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a> * Unit, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dwarfdebuginfoentry">DWARFDebugInfoEntry</a> * D)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#ad12709d83cc62353d47c5bbb059f1ebe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DWARFDie::operator bool ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addressRangeContainsAddress() {#a63d3f031c8cae763003080ab17c8ea24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDie::addressRangeContainsAddress (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Address)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a> and <a href="#a1eac3980947a504ac089ba80976debda">getAddressRanges</a>.</p>

</div>
</div>

### attributes() {#aebfc0d0a2a6ce5273bef574e0b018fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; DWARFDie::attribute_iterator &gt; DWARFDie::attributes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get an iterator range to all attributes in the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> only.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an iterator range for the attributes of the current <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></dd>
</dl>


<p>Declaration at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 684 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>.</p>

</div>
</div>

### begin() {#a956b9b7191bfe0703399bf6bf2538016}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie::iterator llvm::DWARFDie::begin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="#a9eecd422d9c6bd6653dd3492367d3aa3">getFirstChild</a>.</p>


<p>Referenced by <a href="#a1fa7cbc55eb0808d9fc434ef3efb5bca">children</a> and <a href="#aedc3fb758b3d08b11e728b3df67788b5">rend</a>.</p>

</div>
</div>

### children() {#a1fa7cbc55eb0808d9fc434ef3efb5bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; DWARFDie::iterator &gt; llvm::DWARFDie::children ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>References <a href="#a956b9b7191bfe0703399bf6bf2538016">begin</a>, <a href="#a3d55a09bfdc79ab47ae45890102e2f6c">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a814ac0131e04e8e9e7a715d8029ea010">hasInlineInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a02b44f93159b4b08e7998a4fb4d7705f">llvm::verifyKeepChain</a>.</p>

</div>
</div>

### dump() {#aff52b4e2a5b1e91ab933fbd3ad52bba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDie::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned indent=0, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a> DumpOpts=<a href="/web-llvm/docs/api/structs/llvm/didumpoptions">DIDumpOptions</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and all of its attributes to the supplied stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>the stream to use for output.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">indent</td>
<td class="doxyParamItemDescription"><p>the number of characters to indent each line that is output.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="#aebfc0d0a2a6ce5273bef574e0b018fda">attributes</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#ae396b319b15cbecf51ec8dc4ee2719b0">llvm::DIDumpOptions::ChildRecurseDepth</a>, <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a50bceafadc9172f69d322e3f2eb1ad3f">dumpParentChain</a>, <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a986df42e8d99e128c31168ef61b02f5a">llvm::WithColor::get</a>, <a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">getAbbreviationDeclarationPtr</a>, <a href="#a9eecd422d9c6bd6653dd3492367d3aa3">getFirstChild</a>, <a href="#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">getOffset</a>, <a href="#a2fa3d574c395e0628051860fc9be0463">getParent</a>, <a href="#a597b29132ac81f9ba70af9d6fb52cc45">getSibling</a>, <a href="#ac07a6d11b09b4e2c92e9609b6843e9ea">getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#a6f2f68613d44758a66e49320fb075a02">llvm::DataExtractor::getULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/dataextractor/#ad6c780b958be0ededd6a525ce67206bb">llvm::DataExtractor::isValidOffset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a828913b4a1930e52edc8f9d696d0e560">llvm::DIDumpOptions::ShowAddresses</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#a63c9abd316790e49de7546ac58b9e37b">llvm::DIDumpOptions::ShowChildren</a>, <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#af55119555e8e6db24b4441fdef5ead40">llvm::DIDumpOptions::ShowParents</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a> and <a href="/web-llvm/docs/api/structs/llvm/didumpoptions/#add6a33649e764a95f041d7b8358a019e">llvm::DIDumpOptions::Verbose</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#ad09cae3468f14c61f3ca7af906462dab">llvm::DWARFCompileUnit::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a50bceafadc9172f69d322e3f2eb1ad3f">dumpParentChain</a>.</p>

</div>
</div>

### dump() {#a61d3b80309ad8e1497b9decb9b16c9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void DWARFDie::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenience zero-argument overload for debugging.</p>

<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a61d3b80309ad8e1497b9decb9b16c9f5">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>


<p>Referenced by <a href="#a61d3b80309ad8e1497b9decb9b16c9f5">dump</a>.</p>

</div>
</div>

### end() {#a3d55a09bfdc79ab47ae45890102e2f6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie::iterator llvm::DWARFDie::end ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="#a8523c1cf66285db2aa7d5f21cf86d001">getLastChild</a>.</p>


<p>Referenced by <a href="#a1fa7cbc55eb0808d9fc434ef3efb5bca">children</a> and <a href="#a202ebee994e49307c789e43b1d3dcd01">rbegin</a>.</p>

</div>
</div>

### find() {#a315f90678bfa85d85d71a9dd12d5457a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; DWARFDie::find (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the specified attribute from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Extract an attribute value from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> only. This call doesn't look for the attribute value in any DW_AT_specification or DW_AT_abstract_origin referenced DIEs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attr</td>
<td class="doxyParamItemDescription"><p>the attribute to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an optional <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> that will have the form value if the attribute was successfully extracted.</p></dd>
</dl>


<p>Declaration at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 249 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">getAbbreviationDeclarationPtr</a>, <a href="#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">getOffset</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#aab5e3c8afd376c7fedfcd02a86d31540">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugMacro</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#ac9a2ecd6a14be08a7a81ef10f869aa31">llvm::gsym::CUInfo::CUInfo</a>, <a href="#a1eac3980947a504ac089ba80976debda">getAddressRanges</a>, <a href="#a2343cb0aab23f03ea5e28ea535894dd1">getAttributeValueAsReferencedDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae800ac93781be66c955244212aaa9e85">llvm::DWARFUnit::getBaseAddress</a>, <a href="#a629935bec1902c4115188af1c5a6aeb3">getCallerFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp/#a2d1a5a9de231e51210688bc228887c4c">getDwoId</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8aeafac87842fc748625b83753887067">llvm::getDwoId</a>, <a href="#a75a8f3e9af7915e4b0b10f9e17de63ca">getHighPC</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="#ac17a520cef18422636f0fbdd13061acf">getLocations</a>, <a href="#a11debcb2a343bba0cb48f2bbae5e47c7">getLocBaseAttribute</a>, <a href="#a608a08ce1fda97817fddbc8b82b0b622">getLowAndHighPC</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerimpl-cpp/#aa348ebfb62b7adcd56d333e15c064e9a">getPCMFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a58c8277a8af9d4c7d299c82c95b39668">llvm::getPCMFile</a>, <a href="#ac48523a7732959ffeffcdbfaaf5e1578">getRangesBaseAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp/#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a62ed34db5672583fcefb9c152e2dad01">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::isClangModuleRef</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a21dc5ae67ffaf38250ef5b5d377b5358">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::loadClangModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>, <a href="#a107a5c45aec6fd4389339f69720a8608">resolveTypeUnitReference</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#aca2d3ebfb1896c7f85f76bcb6dea8b81">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::save</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a29eb6e9604006a962c4d3dc91c6b5c0f">llvm::DWARFUnit::tryExtractDIEsIfNeeded</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a931cfa6e58e63d6d65fa10e8ce2e18ff">llvm::updatePruning</a>.</p>

</div>
</div>

### find() {#a0d2631f26350dc3818a78b34b448d777}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; DWARFDie::find (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> &gt; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the first value of any attribute in Attrs from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Extract the first attribute that matches from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> only. This call doesn't look for the attribute value in any DW_AT_specification or DW_AT_abstract_origin referenced DIEs. The attributes will be searched linearly in the order they are specified within Attrs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attrs</td>
<td class="doxyParamItemDescription"><p>an array of DWARF attribute to look for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an optional that has a valid <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> for the first matching attribute in Attrs, or std::nullopt if none of the attributes in Attrs exist in this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></dd>
</dl>


<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">getAbbreviationDeclarationPtr</a>, <a href="#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">getOffset</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>

</div>
</div>

### findRecursively() {#a63fa5eea47d71eee71631388500cc8e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; DWARFFormValue &gt; DWARFDie::findRecursively (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> &gt; Attrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the first value of any attribute in Attrs from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> and recurse into any DW_AT_specification or DW_AT_abstract_origin referenced DIEs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attrs</td>
<td class="doxyParamItemDescription"><p>an array of DWARF attribute to look for.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an optional that has a valid <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue">DWARFFormValue</a> for the first matching attribute in Attrs, or std::nullopt if none of the attributes in Attrs exist in this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> or in any DW_AT_specification or DW_AT_abstract_origin DIEs.</p></dd>
</dl>


<p>Declaration at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a6a9f043784cf87001c84980afa76da82">D</a>, <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/smallset/#afcadfef2cf37c3e6dbdbc9cd7bea50a0">llvm::SmallSet&lt; T, N, C &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="#a9d3dccb6b4b6b618de926e3863327b49">getDeclFile</a>, <a href="#aa60164fdf3076c81c5c5ddce03657dc7">getDeclLine</a>, <a href="#ac0e347575bcc3e0fd9caa27e1edfadef">getLinkageName</a>, <a href="#a183b9a712f7e4beb9b21671ce343c960">getShortName</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### getAbbreviationDeclarationPtr() {#a8ccacda3a5cf1a17d4012fdfc8b51e96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFAbbreviationDeclaration * llvm::DWARFDie::getAbbreviationDeclarationPtr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the abbreviation declaration for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the abbreviation declaration or NULL for null tags.</p></dd>
</dl>


<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="#a0d2631f26350dc3818a78b34b448d777">find</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a>, <a href="#ac07a6d11b09b4e2c92e9609b6843e9ea">getTag</a> and <a href="#acd8db424aa6577ea2c055ee823549f3d">isNULL</a>.</p>

</div>
</div>

### getAddressRanges() {#a1eac3980947a504ac089ba80976debda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFAddressRangesVector &gt; DWARFDie::getAddressRanges ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the address ranges for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Get the hi/low PC range if both attributes are available or exrtracts the non-contiguous address ranges from the DW_AT_ranges attribute.</p>


<p>Extracts the range information from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> only. This call doesn't look for the range in any DW_AT_specification or DW_AT_abstract_origin DIEs.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a address range vector that might be empty if no address range information is available.</p></dd>
</dl>


<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a>, <a href="#a608a08ce1fda97817fddbc8b82b0b622">getLowAndHighPC</a> and <a href="#acd8db424aa6577ea2c055ee823549f3d">isNULL</a>.</p>


<p>Referenced by <a href="#a63d3f031c8cae763003080ab17c8ea24">addressRangeContainsAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ae8fdb8ecb676db124d905f7db91d25e7">llvm::DWARFUnit::collectAddressRanges</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afcf7af3468ead1789473fd544662751a">llvm::DWARFUnit::updateAddressDieMap</a>.</p>

</div>
</div>

### getAttributeValueAsReferencedDie() {#a2343cb0aab23f03ea5e28ea535894dd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::getAttributeValueAsReferencedDie (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the specified attribute from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> as the referenced <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<p>Regardless of the reference type, return the correct <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if the attribute exists. The returned <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> object might be from another <a href="/web-llvm/docs/api/classes/llvm/dwarfunit">DWARFUnit</a>, but that is all encapsulated in the new <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> object.</p>


<p>Extract an attribute value from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> only. This call doesn't look for the attribute value in any DW_AT_specification or DW_AT_abstract_origin referenced DIEs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Attr</td>
<td class="doxyParamItemDescription"><p>the attribute to extract.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a valid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if the attribute exists, or an invalid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> object if it doesn't.</p></dd>
</dl>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a> and <a href="#a2343cb0aab23f03ea5e28ea535894dd1">getAttributeValueAsReferencedDie</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="#a2343cb0aab23f03ea5e28ea535894dd1">getAttributeValueAsReferencedDie</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#ae805ed41c31e2492528701718a34276a">GetParentDeclContextDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a>, <a href="#ab4cc1e18f2073a11bda5d0cc37cb7e12">resolveReferencedType</a>, <a href="#a7e41a18c9f51cedd4178dc02be89e918">resolveReferencedType</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">llvm::DWARFUnit::updateVariableDieMap</a>.</p>

</div>
</div>

### getAttributeValueAsReferencedDie() {#a4bbbe4c1e38aa50239589e57e47d0eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::getAttributeValueAsReferencedDie (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a652a8c8f9e1d6fe9889aa451f290c65b">DWARFFormValue</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 312 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2f4b745612c1f38ddeeb42af9a4df2d8">llvm::DWARFUnit::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a54935e3c42396c955484e9ca2bab9081">llvm::DWARFUnit::getDIEForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a8908e32e9aa677cefe9724dca7b7a908">llvm::DWARFContext::getTypeUnitForHash</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunitvector/#a887387b3f904d16301c7dae667aaa42b">llvm::DWARFUnitVector::getUnitForOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ab0b215242a5a89784e1358645ecacdf3">llvm::DWARFUnit::getUnitVector</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getCallerFrame() {#a629935bec1902c4115188af1c5a6aeb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDie::getCallerFrame (uint32_t &amp; CallFile, uint32_t &amp; CallLine, uint32_t &amp; CallColumn, uint32_t &amp; CallDiscriminator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves values of DW_AT_call_file, DW_AT_call_line and DW_AT_call_column from <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> (or zeroes if they are missing).</p>


<p>This function looks for DW_AT_call attributes in this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> only, it will not resolve the attribute values in any DW_AT_specification or DW_AT_abstract_origin DIEs.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">CallFile</td>
<td class="doxyParamItemDescription"><p>filled in with non-zero if successful, zero if there is no DW_AT_call_file attribute in this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CallLine</td>
<td class="doxyParamItemDescription"><p>filled in with non-zero if successful, zero if there is no DW_AT_call_line attribute in this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CallColumn</td>
<td class="doxyParamItemDescription"><p>filled in with non-zero if successful, zero if there is no DW_AT_call_column attribute in this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CallDiscriminator</td>
<td class="doxyParamItemDescription"><p>filled in with non-zero if successful, zero if there is no DW_AT_GNU_discriminator attribute in this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 501 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>.</p>

</div>
</div>

### getDebugInfoEntry() {#a41fc5e2ca3d059c98029728b2677be44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry * llvm::DWARFDie::getDebugInfoEntry ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>.</p>

</div>
</div>

### getDeclFile() {#a9d3dccb6b4b6b618de926e3863327b49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string DWARFDie::getDeclFile (<a href="/web-llvm/docs/api/structs/llvm/dilineinfospecifier/#a4d01b170267924ab4225e3c93ad666c3">DILineInfoSpecifier::FileLineInfoKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>Reference <a href="#a63fa5eea47d71eee71631388500cc8e5">findRecursively</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#aaffb0ccd4471e5240cb3ce371c9589e1">llvm::DWARFContext::getLineInfoForDataAddress</a>.</p>

</div>
</div>

### getDeclLine() {#aa60164fdf3076c81c5c5ddce03657dc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t DWARFDie::getDeclLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the declaration line (start line) for a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, assuming it specifies a subprogram.</p>


<p>This may be fetched from specification or abstract origin for this subprogram by resolving DW_AT_sepcification or DW_AT_abstract_origin references if necessary.</p>


<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a63fa5eea47d71eee71631388500cc8e5">findRecursively</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ae150cb3561ce0a2979ed60d29301eef7">llvm::dwarf::toUnsigned</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#aaffb0ccd4471e5240cb3ce371c9589e1">llvm::DWARFContext::getLineInfoForDataAddress</a>.</p>

</div>
</div>

### getDwarfUnit() {#a4030d97efbcfaf77b80c112cd27c4214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit * llvm::DWARFDie::getDwarfUnit ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#ac3b09300d5e9ca1002c2a91191aee71b">llvm::DWARFContext::getDIEsForAddress</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp/#a53ce6032d5574922c161935e73014e18">isVariableIndexable</a>.</p>

</div>
</div>

### getFirstChild() {#a9eecd422d9c6bd6653dd3492367d3aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::getFirstChild ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the first child of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a valid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if this object has children or an invalid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if it doesn't.</p></dd>
</dl>


<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a9eecd422d9c6bd6653dd3492367d3aa3">getFirstChild</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="#a956b9b7191bfe0703399bf6bf2538016">begin</a>, <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="#a9eecd422d9c6bd6653dd3492367d3aa3">getFirstChild</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afcf7af3468ead1789473fd544662751a">llvm::DWARFUnit::updateAddressDieMap</a>.</p>

</div>
</div>

### getFullName() {#a0095e307c6632ded142272356d210e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DWARFDie::getFullName (<a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a> &amp; OS, std::string * OriginalFullName=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae64c48fcdefcf075717364cfa4201a18">llvm::dumpTypeUnqualifiedName</a>, <a href="#a183b9a712f7e4beb9b21671ce343c960">getShortName</a> and <a href="#ac07a6d11b09b4e2c92e9609b6843e9ea">getTag</a>.</p>

</div>
</div>

### getHighPC() {#a75a8f3e9af7915e4b0b10f9e17de63ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDie::getHighPC (uint64_t LowPC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the DW_AT_high_pc attribute value as an address.</p>


<p>In DWARF version 4 and later the high PC can be encoded as an offset from the DW_AT_low_pc. This function takes care of extracting the value as an address or offset and adds it to the low PC if needed and returns the value as an optional in case the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> doesn't have a DW_AT_high_pc attribute.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">LowPC</td>
<td class="doxyParamItemDescription"><p>the low PC that might be needed to calculate the high PC.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>an optional address value for the attribute.</p></dd>
</dl>


<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8e02bbea14c70bab55fbc1384e1472d9add7bf230fde8d4836917806aff6a6b27">llvm::Address</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ad31a7a9cab8288e009f13cfabc5afc13">llvm::dwarf::computeTombstoneAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a58762abf82ba4b9f2f46d3b89070d6c1">DenseMapInfo&lt; LocallyHashedType &gt;::Tombstone</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a608a08ce1fda97817fddbc8b82b0b622">getLowAndHighPC</a>.</p>

</div>
</div>

### getLanguage() {#ad7ecc2f5b797f131f8932034e32d77c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDie::getLanguage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 416 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>Reference <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>

</div>
</div>

### getLastChild() {#a8523c1cf66285db2aa7d5f21cf86d001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::getLastChild ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the last child of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a valid null <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if this object has children or an invalid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if it doesn't.</p></dd>
</dl>


<p>Declaration at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a8523c1cf66285db2aa7d5f21cf86d001">getLastChild</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="#a3d55a09bfdc79ab47ae45890102e2f6c">end</a> and <a href="#a8523c1cf66285db2aa7d5f21cf86d001">getLastChild</a>.</p>

</div>
</div>

### getLinkageName() {#ac0e347575bcc3e0fd9caa27e1edfadef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DWARFDie::getLinkageName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> linkage name resolving DW_AT_specification or DW_AT_abstract_origin references if necessary.</p>


<p>Returns null if no name is found.</p>


<p>Declaration at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a63fa5eea47d71eee71631388500cc8e5">findRecursively</a>, <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>.</p>


<p>Referenced by <a href="#a834590fd64e02e844dd117b380ab819b">getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#aca2d3ebfb1896c7f85f76bcb6dea8b81">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::save</a>.</p>

</div>
</div>

### getLocations() {#ac17a520cef18422636f0fbdd13061acf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DWARFLocationExpressionsVector &gt; DWARFDie::getLocations (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 426 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga3022f1d3f256e296d351404c6041d776">llvm::dwarf::AttributeString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga4863132f9f3dd24b6df4cfc6c9cfb676">llvm::dwarf::FormEncodingString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a886094eaed7ce32029ea52a641142b88">llvm::to_vector</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfverifier-cpp/#a53ce6032d5574922c161935e73014e18">isVariableIndexable</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">llvm::DWARFUnit::updateVariableDieMap</a>.</p>

</div>
</div>

### getLocBaseAttribute() {#a11debcb2a343bba0cb48f2bbae5e47c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDie::getLocBaseAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a966c7097853fffeaf2746f5d58861f36">llvm::dwarf::toSectionOffset</a>.</p>

</div>
</div>

### getLowAndHighPC() {#a608a08ce1fda97817fddbc8b82b0b622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDie::getLowAndHighPC (uint64_t &amp; LowPC, uint64_t &amp; HighPC, uint64_t &amp; SectionIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieves DW_AT_low_pc and DW_AT_high_pc from <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p>


<p>Returns true if both attributes are present.</p>


<p>Declaration at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a>, <a href="#a75a8f3e9af7915e4b0b10f9e17de63ca">getHighPC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a3fcfe121a4dc5b72106bdacb47f3ce1e">llvm::dwarf::toSectionedAddress</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a> and <a href="#a1eac3980947a504ac089ba80976debda">getAddressRanges</a>.</p>

</div>
</div>

### getName() {#a834590fd64e02e844dd117b380ab819b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DWARFDie::getName (<a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870">DINameKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> name resolving DW_AT_specification or DW_AT_abstract_origin references if necessary.</p>


<p>For the LinkageName case it additionaly searches for ShortName if LinkageName is not found. Returns null if no name is found.</p>


<p>Declaration at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#ac0e347575bcc3e0fd9caa27e1edfadef">getLinkageName</a>, <a href="#a183b9a712f7e4beb9b21671ce343c960">getShortName</a>, <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a2af11f5ae6e00ebf5aff0bfd071ba5b3">llvm::LinkageName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarftypeunit/#a9c2344d084d7463ac5940022292d5775">llvm::DWARFTypeUnit::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a>, <a href="#a48f96d333a71d8a20a5ecb501f07b16c">getSubroutineName</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp/#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a>.</p>

</div>
</div>

### getOffset() {#a14abe929fe7e3d9a46c3ad1d8a1eb2fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DWARFDie::getOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the absolute offset into the debug info or types section.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> offset or -1U if invalid.</p></dd>
</dl>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="#a0d2631f26350dc3818a78b34b448d777">find</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### getParent() {#a2fa3d574c395e0628051860fc9be0463}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::getParent ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the parent of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a valid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if this object has a parent or an invalid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if it doesn't.</p></dd>
</dl>


<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 654 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a2fa3d574c395e0628051860fc9be0463">getParent</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a50bceafadc9172f69d322e3f2eb1ad3f">dumpParentChain</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a86af5dc1ea8da3e443ba72fcf0f9caf5">llvm::DWARFUnit::getInlinedChainForAddress</a>, <a href="#a2fa3d574c395e0628051860fc9be0463">getParent</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#ae805ed41c31e2492528701718a34276a">GetParentDeclContextDIE</a> and <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp/#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a>.</p>

</div>
</div>

### getPreviousSibling() {#a87dc06a48727e53f283cf3b6484302bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::getPreviousSibling ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the previous sibling of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a valid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if this object has a sibling or an invalid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if it doesn't.</p></dd>
</dl>


<p>Declaration at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a87dc06a48727e53f283cf3b6484302bc">getPreviousSibling</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="#a87dc06a48727e53f283cf3b6484302bc">getPreviousSibling</a>.</p>

</div>
</div>

### getRangesBaseAttribute() {#ac48523a7732959ffeffcdbfaaf5e1578}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDie::getRangesBaseAttribute ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Extract the range base attribute from this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> as absolute section offset.</p>


<p>This is a utility function that checks for either the DW_AT_rnglists_base or DW_AT_GNU_ranges_base attribute.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>anm optional absolute section offset value for the attribute.</p></dd>
</dl>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 346 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a966c7097853fffeaf2746f5d58861f36">llvm::dwarf::toSectionOffset</a>.</p>

</div>
</div>

### getShortName() {#a183b9a712f7e4beb9b21671ce343c960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DWARFDie::getShortName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> short name resolving DW_AT_specification or DW_AT_abstract_origin references if necessary.</p>


<p>Returns null if no name is found.</p>


<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 473 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a63fa5eea47d71eee71631388500cc8e5">findRecursively</a>, <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a39a67e6dc97585d609932dc2fb04a377">llvm::dwarf::toString</a>.</p>


<p>Referenced by <a href="#a0095e307c6632ded142272356d210e76">getFullName</a>, <a href="#a834590fd64e02e844dd117b380ab819b">getName</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/acceleratorrecordssaver/#aca2d3ebfb1896c7f85f76bcb6dea8b81">llvm::dwarf_linker::parallel::AcceleratorRecordsSaver::save</a>.</p>

</div>
</div>

### getSibling() {#a597b29132ac81f9ba70af9d6fb52cc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::getSibling ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the sibling of this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> object.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a valid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if this object has a sibling or an invalid <a href="/web-llvm/docs/api/classes/llvm/dwarfdie">DWARFDie</a> instance if it doesn't.</p></dd>
</dl>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a597b29132ac81f9ba70af9d6fb52cc45">getSibling</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>


<p>Referenced by <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="#a597b29132ac81f9ba70af9d6fb52cc45">getSibling</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afcf7af3468ead1789473fd544662751a">llvm::DWARFUnit::updateAddressDieMap</a>.</p>

</div>
</div>

### getSubroutineName() {#a48f96d333a71d8a20a5ecb501f07b16c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * DWARFDie::getSubroutineName (<a href="/web-llvm/docs/api/namespaces/llvm/#aad87d874f7944b5838f7881938d18870">DINameKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If a <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represents a subprogram (or inlined subroutine), returns its mangled name (or short name, if mangled is missing).</p>


<p>This name may be fetched from specification or abstract origin for this subprogram. Returns null if no name is found.</p>


<p>Declaration at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a834590fd64e02e844dd117b380ab819b">getName</a> and <a href="#a5cb799dc32cfff9bf946923f4775550b">isSubroutineDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>.</p>

</div>
</div>

### getTag() {#ac07a6d11b09b4e2c92e9609b6843e9ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::DWARFDie::getTag ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">getAbbreviationDeclarationPtr</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac7f4306c508478ca81791cbccef212fb">llvm::analyzeContextInfo</a>, <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="#a0095e307c6632ded142272356d210e76">getFullName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a86af5dc1ea8da3e443ba72fcf0f9caf5">llvm::DWARFUnit::getInlinedChainForAddress</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#ae805ed41c31e2492528701718a34276a">GetParentDeclContextDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp/#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a814ac0131e04e8e9e7a715d8029ea010">hasInlineInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acc6108333e358848db3db11c51d105ef">llvm::isODRCanonicalCandidate</a>, <a href="#a63b616e747d955b94fe3ee589a9c1003">isSubprogramDIE</a>, <a href="#a5cb799dc32cfff9bf946923f4775550b">isSubroutineDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa6fc3382b3caf1e509384c91f5457db7">llvm::updateChildIncompleteness</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a931cfa6e58e63d6d65fa10e8ce2e18ff">llvm::updatePruning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f460e86ae0cf56bd21fd50ef7f5e2b6">llvm::updateRefIncompleteness</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">llvm::DWARFUnit::updateVariableDieMap</a>.</p>

</div>
</div>

### getTypeSize() {#a778b64ccbeb836841eb9b35bbe91e3c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DWARFDie::getTypeSize (uint64_t PointerSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the type size (in bytes) for this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">PointerSize</td>
<td class="doxyParamItemDescription"><p>the pointer size of the containing <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>if this is a type <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>, or this <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> contains a DW_AT_type, returns the size of the type.</p></dd>
</dl>


<p>Declaration at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#accf3be3ee4da66e202a85c57bc4135a4">getTypeSizeImpl</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#ac360b4709027f4534efa4a4671140ccb">llvm::DWARFUnit::updateVariableDieMap</a>.</p>

</div>
</div>

### hasChildren() {#a49bee858d2b063e9cfe14ae41903f3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDie::hasChildren ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#ae970d60ab52d996448bb030b4a0b67bc">isValid</a>.</p>

</div>
</div>

### isNULL() {#acd8db424aa6577ea2c055ee823549f3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDie::isNULL ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true for a valid <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> that terminates a sibling chain.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">getAbbreviationDeclarationPtr</a>.</p>


<p>Referenced by <a href="#a1eac3980947a504ac089ba80976debda">getAddressRanges</a>.</p>

</div>
</div>

### isSubprogramDIE() {#a63b616e747d955b94fe3ee589a9c1003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDie::isSubprogramDIE ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represents a subprogram (not inlined).</p>

<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>Reference <a href="#ac07a6d11b09b4e2c92e9609b6843e9ea">getTag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a86af5dc1ea8da3e443ba72fcf0f9caf5">llvm::DWARFUnit::getInlinedChainForAddress</a>.</p>

</div>
</div>

### isSubroutineDIE() {#a5cb799dc32cfff9bf946923f4775550b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DWARFDie::isSubroutineDIE ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> represents a subprogram or an inlined subroutine.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#ac07a6d11b09b4e2c92e9609b6843e9ea">getTag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343ac101058e7ea21bbbf2a5ac893088e90b">llvm::Tag</a>.</p>


<p>Referenced by <a href="#a48f96d333a71d8a20a5ecb501f07b16c">getSubroutineName</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#afcf7af3468ead1789473fd544662751a">llvm::DWARFUnit::updateAddressDieMap</a>.</p>

</div>
</div>

### isValid() {#ae970d60ab52d996448bb030b4a0b67bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DWARFDie::isValid ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a>, <a href="/web-llvm/docs/api/classes/llvm/logicalview/lvdwarfreader/#abf565023d8f6916f29adcd9ac264400e">llvm::logicalview::LVDWARFReader::createScopes</a>, <a href="#aff52b4e2a5b1e91ab933fbd3ad52bba0">dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="#a0d2631f26350dc3818a78b34b448d777">find</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a>, <a href="#a8ccacda3a5cf1a17d4012fdfc8b51e96">getAbbreviationDeclarationPtr</a>, <a href="#a9eecd422d9c6bd6653dd3492367d3aa3">getFirstChild</a>, <a href="#ad7ecc2f5b797f131f8932034e32d77c3">getLanguage</a>, <a href="#a8523c1cf66285db2aa7d5f21cf86d001">getLastChild</a>, <a href="#ac0e347575bcc3e0fd9caa27e1edfadef">getLinkageName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a3dc5679c9f87dbde396b2ef8e006bc14">llvm::DWARFContext::getLocalsForAddress</a>, <a href="#a834590fd64e02e844dd117b380ab819b">getName</a>, <a href="#a14abe929fe7e3d9a46c3ad1d8a1eb2fd">getOffset</a>, <a href="#a2fa3d574c395e0628051860fc9be0463">getParent</a>, <a href="#a87dc06a48727e53f283cf3b6484302bc">getPreviousSibling</a>, <a href="#a183b9a712f7e4beb9b21671ce343c960">getShortName</a>, <a href="#a597b29132ac81f9ba70af9d6fb52cc45">getSibling</a>, <a href="#a49bee858d2b063e9cfe14ae41903f3b9">hasChildren</a>, <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/acceleratorrecordssaver-cpp/#a9301753b7bb43fbe58a0c9ea05711537">hashFullyQualifiedName</a>, <a href="#ad12709d83cc62353d47c5bbb059f1ebe">operator bool</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dependencytracker/#a066fd5533813e5df6d52cb59fc8afd4e">llvm::dwarf_linker::parallel::DependencyTracker::verifyKeepChain</a>.</p>

</div>
</div>

### rbegin() {#a202ebee994e49307c789e43b1d3dcd01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::reverse_iterator&lt; DWARFDie::iterator &gt; llvm::DWARFDie::rbegin ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 299 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="#a3d55a09bfdc79ab47ae45890102e2f6c">end</a>.</p>

</div>
</div>

### rend() {#aedc3fb758b3d08b11e728b3df67788b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::reverse_iterator&lt; DWARFDie::iterator &gt; llvm::DWARFDie::rend ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 300 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>


<p>Reference <a href="#a956b9b7191bfe0703399bf6bf2538016">begin</a>.</p>

</div>
</div>

### resolveReferencedType() {#a7e41a18c9f51cedd4178dc02be89e918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::resolveReferencedType (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a1424c28b6a65587442fbd9d87726c2c7">dwarf::Attribute</a> Attr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 339 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a2343cb0aab23f03ea5e28ea535894dd1">getAttributeValueAsReferencedDie</a> and <a href="#a107a5c45aec6fd4389339f69720a8608">resolveTypeUnitReference</a>.</p>

</div>
</div>

### resolveReferencedType() {#ab4cc1e18f2073a11bda5d0cc37cb7e12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::resolveReferencedType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a652a8c8f9e1d6fe9889aa451f290c65b">DWARFFormValue</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 342 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a2343cb0aab23f03ea5e28ea535894dd1">getAttributeValueAsReferencedDie</a> and <a href="#a107a5c45aec6fd4389339f69720a8608">resolveTypeUnitReference</a>.</p>

</div>
</div>

### resolveTypeUnitReference() {#a107a5c45aec6fd4389339f69720a8608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDie DWARFDie::resolveTypeUnitReference ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>, definition at line 328 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a>.</p>


<p>References <a href="#a8d8e0bb75600c92e2c135918ce4a82b9">DWARFDie</a>, <a href="#a315f90678bfa85d85d71a9dd12d5457a">find</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfunit/#a2f4b745612c1f38ddeeb42af9a4df2d8">llvm::DWARFUnit::getContext</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a8908e32e9aa677cefe9724dca7b7a908">llvm::DWARFContext::getTypeUnitForHash</a>.</p>


<p>Referenced by <a href="#ab4cc1e18f2073a11bda5d0cc37cb7e12">resolveReferencedType</a> and <a href="#a7e41a18c9f51cedd4178dc02be89e918">resolveReferencedType</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Die {#a1206baf8b74176b0563a8223b86421ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DWARFDebugInfoEntry* llvm::DWARFDie::Die = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>

</div>
</div>

### U {#a6297c71f451a8b9fc960b3a9ed482047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFUnit* llvm::DWARFDie::U = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfdie-h">DWARFDie.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp">DWARFDie.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
