---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lto/lto/globalresolution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `GlobalResolution` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::lto::LTO::GlobalResolution { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> : unsigned { <a href="#aaf59b2c09d9b9431171fb30573dbe14f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Special partition numbers. <a href="#aaf59b2c09d9b9431171fb30573dbe14f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4087f59537491f4741a8e8c1d95af38e">isPrevailingIRSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if module contains the prevailing definition and symbol is an IR symbol. <a href="#a4087f59537491f4741a8e8c1d95af38e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac6e1786b323c3fbad712257114ffe60">IRName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The unmangled name of the global. <a href="#aac6e1786b323c3fbad712257114ffe60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa4fe95b1096d2dee7f6bbdd13a47b1">VisibleOutsideSummary</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track if the symbol is visible outside of a module with a summary (i.e. <a href="#a0fa4fe95b1096d2dee7f6bbdd13a47b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a24043bdb317439fc7f40e12c12e7d3">ExportDynamic</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The symbol was exported dynamically, and therefore could be referenced by a shared library not visible to the linker. <a href="#a0a24043bdb317439fc7f40e12c12e7d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae628c508a460a9aa092ebe17f08867fe">UnnamedAddr</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef352e815d55f53ae1d04a86eb181430">Prevailing</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if module contains the prevailing definition. <a href="#aef352e815d55f53ae1d04a86eb181430">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fb7283c89b4c6aaa60ca90af64cf740">Partition</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">Unknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This field keeps track of the partition number of this global. <a href="#a9fb7283c89b4c6aaa60ca90af64cf740">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#aaf59b2c09d9b9431171fb30573dbe14f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Special partition numbers.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="aaf59b2c09d9b9431171fb30573dbe14fa686e5842b7b1b1dfeebf32fef6a8f1fa"></a></td>
<td class="doxyEnumItemDescription">A partition number has not yet been assigned to this global (= -1u)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">External<a id="aaf59b2c09d9b9431171fb30573dbe14faa0ce2610e65d5867ed61f08f1b9426ce"></a></td>
<td class="doxyEnumItemDescription">This global is either used by more than one partition or has an external reference, and therefore cannot be internalized (= -2u)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegularLTO<a id="aaf59b2c09d9b9431171fb30573dbe14fa5da9d53de0139cf88e20284b7f4b2e5c"></a></td>
<td class="doxyEnumItemDescription">The RegularLTO partition (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isPrevailingIRSymbol() {#a4087f59537491f4741a8e8c1d95af38e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::LTO::GlobalResolution::isPrevailingIRSymbol ()</td>
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

<p>Returns true if module contains the prevailing definition and symbol is an IR symbol.</p>


<p>For example when module-level inline asm block is used, symbol can be prevailing in module but have no IR name.</p>


<p>Definition at line 459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### ExportDynamic {#a0a24043bdb317439fc7f40e12c12e7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::LTO::GlobalResolution::ExportDynamic = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The symbol was exported dynamically, and therefore could be referenced by a shared library not visible to the linker.</p>

<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### IRName {#aac6e1786b323c3fbad712257114ffe60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::LTO::GlobalResolution::IRName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The unmangled name of the global.</p>

<p>Definition at line 440 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### Partition {#a9fb7283c89b4c6aaa60ca90af64cf740}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::LTO::GlobalResolution::Partition = <a href="/web-llvm/docs/api/namespaces/llvm/#a0ba893e7dc00f439ef557e79f12e899fa88183b946cc5f0e8c96b2e66e1c74a7e">Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This field keeps track of the partition number of this global.</p>


<p>The regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> object is partition 0, while each ThinLTO object has its own partition number from 1 onwards.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> global that is defined or used by more than one partition, or that is referenced externally, may not be internalized.</p>


<p>Partitions generally have a one-to-one correspondence with tasks, except that we use partition 0 for all parallel <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> code generation partitions. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> partitioning of the combined <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> object is done internally by the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> backend.</p>


<p>Definition at line 472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### Prevailing {#aef352e815d55f53ae1d04a86eb181430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::LTO::GlobalResolution::Prevailing = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if module contains the prevailing definition.</p>

<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### UnnamedAddr {#ae628c508a460a9aa092ebe17f08867fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::LTO::GlobalResolution::UnnamedAddr = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

### VisibleOutsideSummary {#a0fa4fe95b1096d2dee7f6bbdd13a47b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::LTO::GlobalResolution::VisibleOutsideSummary = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track if the symbol is visible outside of a module with a summary (i.e.</p>


<p>in either a regular object or a regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> module without a summary).</p>


<p>Definition at line 445 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/lto-h">LTO.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
