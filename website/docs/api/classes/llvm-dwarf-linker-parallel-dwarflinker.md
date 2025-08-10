---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dwarf-linker/parallel/dwarflinker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DWARFLinker` Class



## Declaration

<div class="doxyDeclaration">
class llvm::dwarf_linker::parallel::DWARFLinker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/parallel/dwarflinker-h">llvm/DWARFLinker/Parallel/DWARFLinker.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase">DWARFLinkerBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base interface for <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/classic/dwarflinker">DWARFLinker</a> implementations. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl">DWARFLinkerImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class links debug info. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a7f0737ec70ef10abee719dd612fbe3">~DWARFLinker</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496b5d31b33d7423bc5c28fd29d57a94">setOutputDWARFHandler</a> (const Triple &amp;TargetTriple, SectionHandlerTy SectionHandler)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set output DWARF handler. <a href="#a496b5d31b33d7423bc5c28fd29d57a94">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinker">DWARFLinker</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85bcc9515e3fea62b968dcfffe6a402">createLinker</a> (MessageHandlerTy ErrorHandler, MessageHandlerTy WarningHandler)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates dwarf linker instance. <a href="#af85bcc9515e3fea62b968dcfffe6a402">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/parallel/dwarflinker-h">DWARFLinker.h</a>.</p>


<div class="doxySectionDef">

## Public Destructor

### \~DWARFLinker() {#a4a7f0737ec70ef10abee719dd612fbe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::dwarf_linker::parallel::DWARFLinker::~DWARFLinker ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/parallel/dwarflinker-h">DWARFLinker.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp/#a170a641ca785d873866fb901dfcb7591">ErrorHandler</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setOutputDWARFHandler() {#a496b5d31b33d7423bc5c28fd29d57a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::dwarf_linker::parallel::DWARFLinker::setOutputDWARFHandler (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/parallel/#a6f049fdf3c9f69b0817f13b00ce1140a">SectionHandlerTy</a> SectionHandler)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set output DWARF handler.</p>


<p>Result of linking DWARF is set of sections containing final debug info. <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a5c06ee4a3b2d38bf3fc825fc74580383">DWARFLinkerBase::link()</a> pass generated sections using specified <span class="doxyComputerOutput">SectionHandler</span>.</p>


<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/parallel/dwarflinker-h">DWARFLinker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### createLinker() {#af85bcc9515e3fea62b968dcfffe6a402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; DWARFLinker &gt; DWARFLinker::createLinker (<a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> ErrorHandler, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/dwarflinkerbase/#a6171d1affe838c4595f5bc1306ca5749">MessageHandlerTy</a> WarningHandler)</td>
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

<p>Creates dwarf linker instance.</p>

<p>Declaration at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/parallel/dwarflinker-h">DWARFLinker.h</a>, definition at line 17 of file <a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinker-cpp">DWARFLinker.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/errorhandling-cpp/#a170a641ca785d873866fb901dfcb7591">ErrorHandler</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/dwarflinker/include/llvm/dwarflinker/parallel/dwarflinker-h">DWARFLinker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/dwarflinker/lib/dwarflinker/parallel/dwarflinker-cpp">DWARFLinker.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
