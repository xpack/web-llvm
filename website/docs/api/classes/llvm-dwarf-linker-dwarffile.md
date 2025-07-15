---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/dwarffile
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DWARFFile` Class Reference

<p>This class represents DWARF information for source file and it's address map. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::DWARFFile { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">llvm/DWARFLinker/DWARFFile.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7051a3bbd56f92c0696bc18765ca4bee">UnloadCallbackTy</a> = std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="#ab9a62394ba9282bbcfce9bce71e4ada9">FileName</a>)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d429f936c45567b926e289bfc8c9b5">DWARFFile</a> (StringRef Name, std::unique_ptr&lt; DWARFContext &gt; Dwarf, std::unique_ptr&lt; AddressesMap &gt; Addresses, UnloadCallbackTy UnloadFunc=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a558003f2fe3f9ae866f84c04b70d1d">unload</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unloads object file and corresponding <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap">AddressesMap</a> and Dwarf Context. <a href="#a8a558003f2fe3f9ae866f84c04b70d1d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a62394ba9282bbcfce9bce71e4ada9">FileName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Object file name. <a href="#ab9a62394ba9282bbcfce9bce71e4ada9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd324456c487528eeb69587a4e3aa2cb">Dwarf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source DWARF information. <a href="#afd324456c487528eeb69587a4e3aa2cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap">AddressesMap</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3feabbe6734f4e6fa2b0bc7d9917cb2f">Addresses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helpful address information(list of valid address ranges, relocations). <a href="#a3feabbe6734f4e6fa2b0bc7d9917cb2f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7051a3bbd56f92c0696bc18765ca4bee">UnloadCallbackTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45a423a86ad424a69069c21d79718d5f">UnloadFunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback to the module keeping object file to unload. <a href="#a45a423a86ad424a69069c21d79718d5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents DWARF information for source file and it's address map.</p>


<p>May be used asynchroniously for reading.</p>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### UnloadCallbackTy {#a7051a3bbd56f92c0696bc18765ca4bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::dwarf_linker::DWARFFile::UnloadCallbackTy =  std::function&lt;void(StringRef FileName)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DWARFFile() {#ad7d429f936c45567b926e289bfc8c9b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dwarf_linker::DWARFFile::DWARFFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext">DWARFContext</a> &gt; Dwarf, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap">AddressesMap</a> &gt; Addresses, <a href="#a7051a3bbd56f92c0696bc18765ca4bee">UnloadCallbackTy</a> UnloadFunc=nullptr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>


<p>References <a href="#a3feabbe6734f4e6fa2b0bc7d9917cb2f">Addresses</a>, <a href="#afd324456c487528eeb69587a4e3aa2cb">Dwarf</a>, <a href="#ab9a62394ba9282bbcfce9bce71e4ada9">FileName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a45a423a86ad424a69069c21d79718d5f">UnloadFunc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### unload() {#a8a558003f2fe3f9ae866f84c04b70d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::dwarf_linker::DWARFFile::unload ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unloads object file and corresponding <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/addressesmap">AddressesMap</a> and Dwarf Context.</p>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>


<p>References <a href="#a3feabbe6734f4e6fa2b0bc7d9917cb2f">Addresses</a>, <a href="#afd324456c487528eeb69587a4e3aa2cb">Dwarf</a>, <a href="#ab9a62394ba9282bbcfce9bce71e4ada9">FileName</a> and <a href="#a45a423a86ad424a69069c21d79718d5f">UnloadFunc</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Addresses {#a3feabbe6734f4e6fa2b0bc7d9917cb2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AddressesMap&gt; llvm::dwarf_linker::DWARFFile::Addresses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helpful address information(list of valid address ranges, relocations).</p>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>


<p>Referenced by <a href="#ad7d429f936c45567b926e289bfc8c9b5">DWARFFile</a> and <a href="#a8a558003f2fe3f9ae866f84c04b70d1d">unload</a>.</p>

</div>
</div>

### Dwarf {#afd324456c487528eeb69587a4e3aa2cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DWARFContext&gt; llvm::dwarf_linker::DWARFFile::Dwarf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source DWARF information.</p>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/compileunit/#a5d779ebf8d97beda3616fa4d7997e355">llvm::dwarf_linker::parallel::CompileUnit::cloneAndEmitLineTable</a>, <a href="#ad7d429f936c45567b926e289bfc8c9b5">DWARFFile</a> and <a href="#a8a558003f2fe3f9ae866f84c04b70d1d">unload</a>.</p>

</div>
</div>

### FileName {#ab9a62394ba9282bbcfce9bce71e4ada9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::dwarf_linker::DWARFFile::FileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Object file name.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>


<p>Referenced by <a href="#ad7d429f936c45567b926e289bfc8c9b5">DWARFFile</a> and <a href="#a8a558003f2fe3f9ae866f84c04b70d1d">unload</a>.</p>

</div>
</div>

### UnloadFunc {#a45a423a86ad424a69069c21d79718d5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UnloadCallbackTy llvm::dwarf_linker::DWARFFile::UnloadFunc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Callback to the module keeping object file to unload.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a>.</p>


<p>Referenced by <a href="#ad7d429f936c45567b926e289bfc8c9b5">DWARFFile</a> and <a href="#a8a558003f2fe3f9ae866f84c04b70d1d">unload</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/dwarffile-h">DWARFFile.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
