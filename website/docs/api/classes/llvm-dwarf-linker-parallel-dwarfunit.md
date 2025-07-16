---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/dwarfunit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DwarfUnit` Class Reference

<p>Base class for all Dwarf units(Compile unit/Type table unit). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DwarfUnit { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinker/Parallel/DWARFLinkerUnit.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections">OutputSections</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class keeps contents and offsets to the debug sections. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit">CompileUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Stores all information related to a compile unit, be it in its original instance of the object file or its brand new cloned and generated <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> tree. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit">TypeUnit</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> Unit is used to represent an artificial compilation unit which keeps all type information. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2962714894f04021fc77f2d80d495a98">FileNamesCache</a> = <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, std::pair&lt; std::string, std::string &gt; &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Cache for file names for this unit. <a href="#a2962714894f04021fc77f2d80d495a98">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AccelType : uint8_t { <a href="/web-llvm/docs/api/groups/methods/#ga2c708209e1c0939d50f9e70bc5708491">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad367b733292adfe15b6d45c5fc4db8b2">DwarfUnit</a> (LinkingGlobalData &amp;GlobalData, unsigned ID, StringRef ClangModuleName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a920e15c58c13f072568b09e0e0f52c57">~DwarfUnit</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c73e0f59889afc189e84456b7e76df8">getUniqueID</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique id of the unit. <a href="#a1c73e0f59889afc189e84456b7e76df8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a14a749f6a0640d5bb83586f80ea7ac">getUnitSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns size of this(newly generated) compile unit. <a href="#a6a14a749f6a0640d5bb83586f80ea7ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4d5c28a1b468db516b750ace450138d">getUnitName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns this unit name. <a href="#ab4d5c28a1b468db516b750ace450138d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb30d50b24260ae45f84319d1d1825ea">getSysRoot</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the DW_AT_LLVM_sysroot of the compile unit or an empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#afb30d50b24260ae45f84319d1d1825ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a081afb78e5946e181853edeef38302">isClangModule</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if this compile unit is from Clang module. <a href="#a6a081afb78e5946e181853edeef38302">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6dcdbb6d8c273d2509c77174b821a50">getClangModuleName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return Clang module name;. <a href="#ab6dcdbb6d8c273d2509c77174b821a50">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a461c26c602014baed9de7d2c019f4f8a">getGlobalData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return global data. <a href="#a461c26c602014baed9de7d2c019f4f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adadeb3b3df0c3dfa1f8b82eb0d97d416">isInterconnectedCU</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if unit is inter-connected(it references/referenced by other unit). <a href="#adadeb3b3df0c3dfa1f8b82eb0d97d416">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e3c904a9b9278a29763744a1d9846d4">setInterconnectedCU</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mark this unit as inter-connected(it references/referenced by other unit). <a href="#a6e3c904a9b9278a29763744a1d9846d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c259a02c5568d23015e29643620acb3">assignAbbrev</a> (DIEAbbrev &amp;Abbrev)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds <span class="doxyComputerOutput">Abbrev</span> into unit`s abbreviation table. <a href="#a6c259a02c5568d23015e29643620acb3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &gt; &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebc2b7745b60e26a867ba76b835c1a95">getAbbreviations</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns abbreviations for this compile unit. <a href="#aebc2b7745b60e26a867ba76b835c1a95">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbcc691dc3aee7912fd0e6f49fb1bb8a">getOutUnitDIE</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns output unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#afbcc691dc3aee7912fd0e6f49fb1bb8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24c182dd9def83d9d63a6cce49331c0">setOutUnitDIE</a> (DIE *UnitDie)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set output unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#ad24c182dd9def83d9d63a6cce49331c0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5414c3234e9f56523af233d2628c7475">getTag</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns unit DWARF tag. <a href="#a5414c3234e9f56523af233d2628c7475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae752add53cb8c1a0bb60cd20927edc46">getDebugStrIndex</a> (const StringEntry *String)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns index(inside .debug_str_offsets) of specified string. <a href="#ae752add53cb8c1a0bb60cd20927edc46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">emitAbbreviations</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">emitDebugInfo</a> (const Triple &amp;TargetTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_info section for unit DIEs. <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#gaf5ad0e93c4f3b97d0e8d192675945746">emitDebugLine</a> (const Triple &amp;TargetTriple, const DWARFDebugLine::LineTable &amp;OutLineTable)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_line section. <a href="/web-llvm/docs/api/groups/methods/#gaf5ad0e93c4f3b97d0e8d192675945746">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">emitDebugStringOffsetSection</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_str_offsets section for current unit. <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga90690238930e2f8062b17bbea187d3b1">warn</a> (const Twine &amp;Warning)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga88ab67842e20cde2f963249cf344c2ed">error</a> (const Twine &amp;Err)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">emitPubAccelerators</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit .debug_pubnames and .debug_pubtypes for <span class="doxyComputerOutput">Unit</span>. <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/methods/#ga75da77525cf70d66af72eb9d0f4592f2">forEachAcceleratorRecord</a> (function_ref&lt; void(AccelInfo &amp;)&gt; Handler)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Enumerates accelerator data. <a href="/web-llvm/docs/api/groups/methods/#ga75da77525cf70d66af72eb9d0f4592f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec20444d01151e8ad774f0d1354067c3">emitDwarfAbbrevEntry</a> (const DIEAbbrev &amp;Abbrev, SectionDescriptor &amp;AbbrevSection)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit single abbreviation entry. <a href="#aec20444d01151e8ad774f0d1354067c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5415f7dcc45583b4bb82acb6f64c73a">emitPubAcceleratorEntry</a> (SectionDescriptor &amp;OutSection, const AccelInfo &amp;Info, std::optional&lt; uint64_t &gt; LengthOffset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit single pubnames/pubtypes accelerator entry. <a href="#aa5415f7dcc45583b4bb82acb6f64c73a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4bc76d8c13939bdfdaf0b96aa1d4f82">ID</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unique ID for the unit. <a href="#ab4bc76d8c13939bdfdaf0b96aa1d4f82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c338a607208f34a94cce92277176e35">UnitName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name of this unit. <a href="#a2c338a607208f34a94cce92277176e35">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6405b4fe980c4bdbffe7fd3732d74c18">SysRoot</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The DW_AT_LLVM_sysroot of this unit. <a href="#a6405b4fe980c4bdbffe7fd3732d74c18">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6bdec0518399f994bc436daa5ad27a3">ClangModuleName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is a Clang module, this holds the module's name. <a href="#ad6bdec0518399f994bc436daa5ad27a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac21110b8f5b380fabba7f116241336a0">UnitSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#ac94a19fc8c57bf0350fc4e9f45897828">dwarf::Tag</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72d5fcb0ae990476c91d0c3e3dcb651">UnitTag</a> = dwarf::DW_TAG_null</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>DWARF unit tag. <a href="#ad72d5fcb0ae990476c91d0c3e3dcb651">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::atomic&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace9b14713dbdd91c06da4932e2db8f92">IsInterconnectedCU</a> = {false}</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>true if current unit references_to/is_referenced by other unit. <a href="#ace9b14713dbdd91c06da4932e2db8f92">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed631a14c4d5d968368454041e3d9413">AbbreviationsSet</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> that uniques the abbreviations. <a href="#aed631a14c4d5d968368454041e3d9413">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d32c9fbda345136f12dfba14237d2fc">Abbreviations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Storage for the unique Abbreviations. <a href="#a4d32c9fbda345136f12dfba14237d2fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a523c53d66f904a426d8b60e192fb72">OutUnitDIE</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>. <a href="#a5a523c53d66f904a426d8b60e192fb72">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2962714894f04021fc77f2d80d495a98">FileNamesCache</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16cbefbd2f62758e696d04e82fc6fd1a">FileNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/indexedvaluesmap">IndexedValuesMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98241a1a7e8a7cb3c7fa4e9202a5011b">DebugStringIndexMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a string into the index inside .debug_str_offsets section. <a href="#a98241a1a7e8a7cb3c7fa4e9202a5011b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Base class for all Dwarf units(Compile unit/Type table unit).</p>

<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<div class="doxySectionDef">

## Protected Member Typedefs

### FileNamesCache {#a2962714894f04021fc77f2d80d495a98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::parallel::DwarfUnit::FileNamesCache = 
      DenseMap&lt;uint64_t, std::pair&lt;std::string, std::string&gt;&gt;</td>
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

<p>Cache for file names for this unit.</p>

<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DwarfUnit() {#ad367b733292adfe15b6d45c5fc4db8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::parallel::DwarfUnit::DwarfUnit (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/linkingglobaldata">LinkingGlobalData</a> &amp; GlobalData, unsigned ID, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ClangModuleName)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>References <a href="#ad6bdec0518399f994bc436daa5ad27a3">ClangModuleName</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>, <a href="#ab4bc76d8c13939bdfdaf0b96aa1d4f82">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0f3129c5b81b6f215d2ac67d576f6c5f">llvm::dwarf_linker::parallel::OutputSections::OutputSections</a> and <a href="#a5a523c53d66f904a426d8b60e192fb72">OutUnitDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/outputunitvariantptr/#a399cf4b87dddd19fbb568833d2799b8a">llvm::dwarf_linker::parallel::CompileUnit::OutputUnitVariantPtr::operator-&gt;</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DwarfUnit() {#a920e15c58c13f072568b09e0e0f52c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::dwarf_linker::parallel::DwarfUnit::~DwarfUnit ()</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### assignAbbrev() {#a6c259a02c5568d23015e29643620acb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::assignAbbrev (<a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &amp; Abbrev)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds <span class="doxyComputerOutput">Abbrev</span> into unit`s abbreviation table.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>References <a href="#a4d32c9fbda345136f12dfba14237d2fc">Abbreviations</a>, <a href="#aed631a14c4d5d968368454041e3d9413">AbbreviationsSet</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a980e1da01a830de10ab45bbd1c1c4d1c">llvm::DIEAbbrev::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a2618aa0a10d4d37dfa2ac6b501f3d5a6">llvm::DIEAbbrev::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#ac848b9d4f06bdebb6afcb5a2d98a4099">llvm::DIEAbbrev::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#af44687d5face91653e5e63e9343b8d7b">llvm::DIEAbbrev::hasChildren</a>, <a href="#ab4bc76d8c13939bdfdaf0b96aa1d4f82">ID</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#af069b02ba0f553e53d79932413de7375">llvm::DIEAbbrev::Profile</a> and <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#ac8ed225191cf81190ec6ffd5325594b5">llvm::DIEAbbrev::setNumber</a>.</p>

</div>
</div>

### getAbbreviations() {#aebc2b7745b60e26a867ba76b835c1a95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; std::unique_ptr&lt; DIEAbbrev &gt; &gt; &amp; llvm::dwarf_linker::parallel::DwarfUnit::getAbbreviations ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns abbreviations for this compile unit.</p>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#a4d32c9fbda345136f12dfba14237d2fc">Abbreviations</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">emitAbbreviations</a>.</p>

</div>
</div>

### getClangModuleName() {#ab6dcdbb6d8c273d2509c77174b821a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::dwarf_linker::parallel::DwarfUnit::getClangModuleName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return Clang module name;.</p>

<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#ad6bdec0518399f994bc436daa5ad27a3">ClangModuleName</a>.</p>

</div>
</div>

### getDebugStrIndex() {#ae752add53cb8c1a0bb60cd20927edc46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::dwarf_linker::parallel::DwarfUnit::getDebugStrIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a0b0094f2370abd91cc57b6d5476a599b">StringEntry</a> * String)</td>
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

<p>Returns index(inside .debug_str_offsets) of specified string.</p>

<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>References <a href="#a98241a1a7e8a7cb3c7fa4e9202a5011b">DebugStringIndexMap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac226f3d2b9ca090171a8e0a8cb92c343a27118326006d3829667a400ad23d5d98">llvm::String</a>.</p>

</div>
</div>

### getGlobalData() {#a461c26c602014baed9de7d2c019f4f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkingGlobalData &amp; llvm::dwarf_linker::parallel::DwarfUnit::getGlobalData ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return global data.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a0ff0b6f2677a5d00534c3cc841b72598">llvm::dwarf_linker::parallel::OutputSections::GlobalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b155dc5f7f9374eb06f7277da633577">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugLocations</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a67e7cb91f1de318011b4ad8f6453fa7a">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitRanges</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0b5afda9f8291e7c2433262c8dc8c167">llvm::dwarf_linker::parallel::CompileUnit::cloneDieAttrExpression</a>.</p>

</div>
</div>

### getOutUnitDIE() {#afbcc691dc3aee7912fd0e6f49fb1bb8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE * llvm::dwarf_linker::parallel::DwarfUnit::getOutUnitDIE ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns output unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#a5a523c53d66f904a426d8b60e192fb72">OutUnitDIE</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#aab5e3c8afd376c7fedfcd02a86d31540">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitDebugMacro</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">emitDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a2de70543d073c4a85bf44c845b7305e9">llvm::dwarf_linker::parallel::TypeUnit::finishCloningAndEmit</a>.</p>

</div>
</div>

### getSysRoot() {#afb30d50b24260ae45f84319d1d1825ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::dwarf_linker::parallel::DwarfUnit::getSysRoot ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the DW_AT_LLVM_sysroot of the compile unit or an empty <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#a6405b4fe980c4bdbffe7fd3732d74c18">SysRoot</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>.</p>

</div>
</div>

### getTag() {#a5414c3234e9f56523af233d2628c7475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::dwarf_linker::parallel::DwarfUnit::getTag ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns unit DWARF tag.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#ad72d5fcb0ae990476c91d0c3e3dcb651">UnitTag</a>.</p>

</div>
</div>

### getUniqueID() {#a1c73e0f59889afc189e84456b7e76df8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::parallel::DwarfUnit::getUniqueID ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unique id of the unit.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#ab4bc76d8c13939bdfdaf0b96aa1d4f82">ID</a>.</p>

</div>
</div>

### getUnitName() {#ab4d5c28a1b468db516b750ace450138d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::dwarf_linker::parallel::DwarfUnit::getUnitName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns this unit name.</p>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#a2c338a607208f34a94cce92277176e35">UnitName</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>, <a href="/web-llvm/docs/api/groups/methods/#gab0417bf315aa0a768f1a33d55209135a">llvm::dwarf_linker::parallel::CompileUnit::error</a>, <a href="/web-llvm/docs/api/groups/methods/#ga067b49dc851a8db06344fa2b594cb6bb">llvm::dwarf_linker::parallel::CompileUnit::error</a>, <a href="/web-llvm/docs/api/groups/methods/#ga88ab67842e20cde2f963249cf344c2ed">error</a>, <a href="/web-llvm/docs/api/groups/methods/#gae294385bb587a12499b98215ae8e7745">llvm::dwarf_linker::parallel::CompileUnit::warn</a>, <a href="/web-llvm/docs/api/groups/methods/#ga8b2f2eefb63daf2e6f322e1e90228a2e">llvm::dwarf_linker::parallel::CompileUnit::warn</a>, <a href="/web-llvm/docs/api/groups/methods/#ga654eee00b3eed07a03d37b22391d18e2">llvm::dwarf_linker::parallel::CompileUnit::warn</a> and <a href="/web-llvm/docs/api/groups/methods/#ga90690238930e2f8062b17bbea187d3b1">warn</a>.</p>

</div>
</div>

### getUnitSize() {#a6a14a749f6a0640d5bb83586f80ea7ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DwarfUnit::getUnitSize ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns size of this(newly generated) compile unit.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#ac21110b8f5b380fabba7f116241336a0">UnitSize</a>.</p>


<p>Referenced by <a href="#aa5415f7dcc45583b4bb82acb6f64c73a">emitPubAcceleratorEntry</a>.</p>

</div>
</div>

### isClangModule() {#a6a081afb78e5946e181853edeef38302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DwarfUnit::isClangModule ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if this compile unit is from Clang module.</p>

<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#ad6bdec0518399f994bc436daa5ad27a3">ClangModuleName</a>.</p>

</div>
</div>

### isInterconnectedCU() {#adadeb3b3df0c3dfa1f8b82eb0d97d416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::dwarf_linker::parallel::DwarfUnit::isInterconnectedCU ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if unit is inter-connected(it references/referenced by other unit).</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#ace9b14713dbdd91c06da4932e2db8f92">IsInterconnectedCU</a>.</p>

</div>
</div>

### setInterconnectedCU() {#a6e3c904a9b9278a29763744a1d9846d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DwarfUnit::setInterconnectedCU ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mark this unit as inter-connected(it references/referenced by other unit).</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Reference <a href="#ace9b14713dbdd91c06da4932e2db8f92">IsInterconnectedCU</a>.</p>

</div>
</div>

### setOutUnitDIE() {#ad24c182dd9def83d9d63a6cce49331c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::parallel::DwarfUnit::setOutUnitDIE (<a href="/web-llvm/docs/api/classes/llvm/die">DIE</a> * UnitDie)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set output unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a7e3b66f8d958f065300cf5ddda43f715">llvm::dwarf_linker::parallel::OutputSections::getDebugInfoHeaderSize</a>, <a href="#a5a523c53d66f904a426d8b60e192fb72">OutUnitDIE</a>, <a href="#ac21110b8f5b380fabba7f116241336a0">UnitSize</a> and <a href="#ad72d5fcb0ae990476c91d0c3e3dcb651">UnitTag</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#ab33a7e6fdc362895e1b739081c1286ba">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmit</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### emitDwarfAbbrevEntry() {#aec20444d01151e8ad774f0d1354067c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DwarfUnit::emitDwarfAbbrevEntry (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dieabbrev">DIEAbbrev</a> &amp; Abbrev, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; AbbrevSection)</td>
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

<p>Emit single abbreviation entry.</p>

<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 59 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac21006e81ffbbc79e8e51e44f7878053">llvm::encodeSLEB128</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad0f8c0e82cde3bb0849fc59e3510f05a">llvm::encodeULEB128</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a980e1da01a830de10ab45bbd1c1c4d1c">llvm::DIEAbbrev::getData</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#a2618aa0a10d4d37dfa2ac6b501f3d5a6">llvm::DIEAbbrev::getNumber</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#ac848b9d4f06bdebb6afcb5a2d98a4099">llvm::DIEAbbrev::getTag</a>, <a href="/web-llvm/docs/api/classes/llvm/dieabbrev/#af44687d5face91653e5e63e9343b8d7b">llvm::DIEAbbrev::hasChildren</a> and <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#ga9b4dbcbc740191455c092e2edd8afa51">emitAbbreviations</a>.</p>

</div>
</div>

### emitPubAcceleratorEntry() {#aa5415f7dcc45583b4bb82acb6f64c73a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; DwarfUnit::emitPubAcceleratorEntry (<a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor">SectionDescriptor</a> &amp; OutSection, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarfunit/accelinfo">AccelInfo</a> &amp; Info, std::optional&lt; uint64_t &gt; LengthOffset)</td>
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

<p>Emit single pubnames/pubtypes accelerator entry.</p>


<p>Emit the pubnames or pubtypes section contribution for <span class="doxyComputerOutput">Unit</span> into <span class="doxyComputerOutput">Sec</span>.</p>


<p>The data is provided in <span class="doxyComputerOutput">Info</span>.</p>


<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24af6f6931771db95a6bffec131b856bd50">llvm::dwarf_linker::DebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#af37a255a9a1f06e51c27b3a5a5c7baf4a266db61014198b69171b91ffe44444ff">llvm::dwarf::DW_PUBNAMES_VERSION</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a5fdd30c106c85cd071977c5062eeed69">llvm::dwarf_linker::parallel::SectionDescriptor::emitInplaceString</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a4954fa6faa9509d506fcedc034eb02c8">llvm::dwarf_linker::parallel::SectionDescriptor::emitIntVal</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a2b514ad5d75b2375ee443a0338d694e8">llvm::dwarf_linker::parallel::SectionDescriptor::emitOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#a33ecefa9aec7bce5d08e92138ae1be08">llvm::dwarf_linker::parallel::OutputSections::getFormParams</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/outputsections/#ab6597212694001f13f816944c69bb0b2">llvm::dwarf_linker::parallel::OutputSections::getOrCreateSectionDescriptor</a>, <a href="#a6a14a749f6a0640d5bb83586f80ea7ac">getUnitSize</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/sectiondescriptor/#a01de9af3f8e9b5ca39f42089c9a0e8ce">llvm::dwarf_linker::parallel::SectionDescriptor::OS</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a0f90ad570f71349466844ee9f2d06cd1">llvm::raw_ostream::tell</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">emitPubAccelerators</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### Abbreviations {#a4d32c9fbda345136f12dfba14237d2fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::unique_ptr&lt;DIEAbbrev&gt; &gt; llvm::dwarf_linker::parallel::DwarfUnit::Abbreviations</td>
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

<p>Storage for the unique Abbreviations.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#a6c259a02c5568d23015e29643620acb3">assignAbbrev</a>, <a href="#aebc2b7745b60e26a867ba76b835c1a95">getAbbreviations</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0dec660c088023646b612c8aafc8966d">llvm::dwarf_linker::parallel::CompileUnit::maybeResetToLoadedStage</a>.</p>

</div>
</div>

### AbbreviationsSet {#aed631a14c4d5d968368454041e3d9413}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSet&lt;DIEAbbrev&gt; llvm::dwarf_linker::parallel::DwarfUnit::AbbreviationsSet</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/foldingset">FoldingSet</a> that uniques the abbreviations.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#a6c259a02c5568d23015e29643620acb3">assignAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2c8b9ba6422c57fd4edb9b5771b650d2">llvm::dwarf_linker::parallel::CompileUnit::cleanupDataAfterClonning</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0dec660c088023646b612c8aafc8966d">llvm::dwarf_linker::parallel::CompileUnit::maybeResetToLoadedStage</a>.</p>

</div>
</div>

### ClangModuleName {#ad6bdec0518399f994bc436daa5ad27a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::dwarf_linker::parallel::DwarfUnit::ClangModuleName</td>
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

<p>If this is a Clang module, this holds the module's name.</p>

<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="#ad367b733292adfe15b6d45c5fc4db8b2">DwarfUnit</a>, <a href="#ab6dcdbb6d8c273d2509c77174b821a50">getClangModuleName</a> and <a href="#a6a081afb78e5946e181853edeef38302">isClangModule</a>.</p>

</div>
</div>

### DebugStringIndexMap {#a98241a1a7e8a7cb3c7fa4e9202a5011b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IndexedValuesMap&lt;const StringEntry *&gt; llvm::dwarf_linker::parallel::DwarfUnit::DebugStringIndexMap</td>
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

<p>Maps a string into the index inside .debug_str_offsets section.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">emitDebugStringOffsetSection</a>, <a href="#ae752add53cb8c1a0bb60cd20927edc46">getDebugStrIndex</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#a8797c2bd69a6364a695cf7f88e3f5c11">llvm::dwarf_linker::parallel::TypeUnit::getDebugStrIndex</a>.</p>

</div>
</div>

### FileNames {#a16cbefbd2f62758e696d04e82fc6fd1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileNamesCache llvm::dwarf_linker::parallel::DwarfUnit::FileNames</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a2c8b9ba6422c57fd4edb9b5771b650d2">llvm::dwarf_linker::parallel::CompileUnit::cleanupDataAfterClonning</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a53949973d752a1d918687b758424714a">llvm::dwarf_linker::parallel::CompileUnit::getDirAndFilenameFromLineTable</a>.</p>

</div>
</div>

### ID {#ab4bc76d8c13939bdfdaf0b96aa1d4f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::dwarf_linker::parallel::DwarfUnit::ID = 0</td>
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

<p>Unique ID for the unit.</p>

<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#a6c259a02c5568d23015e29643620acb3">assignAbbrev</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="#ad367b733292adfe15b6d45c5fc4db8b2">DwarfUnit</a>, <a href="#a1c73e0f59889afc189e84456b7e76df8">getUniqueID</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>.</p>

</div>
</div>

### IsInterconnectedCU {#ace9b14713dbdd91c06da4932e2db8f92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic&lt;bool&gt; llvm::dwarf_linker::parallel::DwarfUnit::IsInterconnectedCU = {false}</td>
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

<p>true if current unit references_to/is_referenced by other unit.</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#adadeb3b3df0c3dfa1f8b82eb0d97d416">isInterconnectedCU</a> and <a href="#a6e3c904a9b9278a29763744a1d9846d4">setInterconnectedCU</a>.</p>

</div>
</div>

### OutUnitDIE {#a5a523c53d66f904a426d8b60e192fb72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DIE* llvm::dwarf_linker::parallel::DwarfUnit::OutUnitDIE = nullptr</td>
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

<p>Output unit <a href="/web-llvm/docs/api/classes/llvm/die">DIE</a>.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#ad367b733292adfe15b6d45c5fc4db8b2">DwarfUnit</a>, <a href="/web-llvm/docs/api/groups/methods/#ga4353067d272bae6ec1a934e5ea39f924">emitDebugInfo</a>, <a href="#afbcc691dc3aee7912fd0e6f49fb1bb8a">getOutUnitDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a0dec660c088023646b612c8aafc8966d">llvm::dwarf_linker::parallel::CompileUnit::maybeResetToLoadedStage</a> and <a href="#ad24c182dd9def83d9d63a6cce49331c0">setOutUnitDIE</a>.</p>

</div>
</div>

### SysRoot {#a6405b4fe980c4bdbffe7fd3732d74c18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::dwarf_linker::parallel::DwarfUnit::SysRoot</td>
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

<p>The DW_AT_LLVM_sysroot of this unit.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a188e713b7044fc7477fa27c6f4efc662">llvm::dwarf_linker::parallel::CompileUnit::analyzeImportedModule</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a> and <a href="#afb30d50b24260ae45f84319d1d1825ea">getSysRoot</a>.</p>

</div>
</div>

### UnitName {#a2c338a607208f34a94cce92277176e35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::dwarf_linker::parallel::DwarfUnit::UnitName</td>
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

<p>The name of this unit.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a26a4de20c065ba21d3af3b8f2fc2bb50">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#abe722b66707f8b5e4aaa19a24810480f">llvm::dwarf_linker::parallel::CompileUnit::CompileUnit</a>, <a href="#ab4d5c28a1b468db516b750ace450138d">getUnitName</a> and <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#af7ec06f047bb304a65a2c02f3bb13063">llvm::dwarf_linker::parallel::TypeUnit::TypeUnit</a>.</p>

</div>
</div>

### UnitSize {#ac21110b8f5b380fabba7f116241336a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::dwarf_linker::parallel::DwarfUnit::UnitSize = 0</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#a6a14a749f6a0640d5bb83586f80ea7ac">getUnitSize</a> and <a href="#ad24c182dd9def83d9d63a6cce49331c0">setOutUnitDIE</a>.</p>

</div>
</div>

### UnitTag {#ad72d5fcb0ae990476c91d0c3e3dcb651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">dwarf::Tag llvm::dwarf_linker::parallel::DwarfUnit::UnitTag = dwarf::DW_TAG_null</td>
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

<p>DWARF unit tag.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a>.</p>


<p>Referenced by <a href="#a5414c3234e9f56523af233d2628c7475">getTag</a> and <a href="#ad24c182dd9def83d9d63a6cce49331c0">setOutUnitDIE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-cpp">DWARFLinkerUnit.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinkerunit-h">DWARFLinkerUnit.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
