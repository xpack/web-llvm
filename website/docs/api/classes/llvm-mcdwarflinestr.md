---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mcdwarflinestr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MCDwarfLineStr` Class Reference

<p>Manage the .debug_line_str section contents, if we use it. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::MCDwarfLineStr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">llvm/MC/MCDwarf.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b8cb2b434353c5d0957495b0582cce6">MCDwarfLineStr</a> (MCContext &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct an instance that can emit .debug_line_str (for use in a normal v5 line table). <a href="#a4b8cb2b434353c5d0957495b0582cce6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021df1c95a6ab0401ba875c929054a07">getSaver</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad325ab6e610eb8bd1f59534515561fdc">emitRef</a> (MCStreamer *MCOS, StringRef Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit a reference to the string. <a href="#ad325ab6e610eb8bd1f59534515561fdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1578026c1ceb637e4b37023412f971ac">emitSection</a> (MCStreamer *MCOS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit the .debug_line_str section if appropriate. <a href="#a1578026c1ceb637e4b37023412f971ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 0 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d40dcd5c8c0c12f4036fe07992cce51">getFinalizedData</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns finalized section. <a href="#a4d40dcd5c8c0c12f4036fe07992cce51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ca2f172998b53bd6458753acd65492">addString</a> (StringRef Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds path <span class="doxyComputerOutput">Path</span> to the line string. <a href="#ad3ca2f172998b53bd6458753acd65492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8e084fd45fff812da2a1db509e6ff70">Alloc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringsaver">StringSaver</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4a5256c10c32a92651c42b49028940">Saver</a> {Alloc}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac23e254325d8eaa223a618ac1ec15c03">LineStrLabel</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a454d48beb8586361981559e6d07a8173">LineStrings</a> {<a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aafa19fdcc19d034fbc975465426a59188">StringTableBuilder::DWARF</a>}</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c038fafc18571becd3e699b6bd2e04">UseRelocs</a> = false</td>
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

<p>Manage the .debug_line_str section contents, if we use it.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MCDwarfLineStr() {#a4b8cb2b434353c5d0957495b0582cce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCDwarfLineStr::MCDwarfLineStr (<a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct an instance that can emit .debug_line_str (for use in a normal v5 line table).</p>

<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsection/#ac690da7fe3ddf1862812d82c36a02766">llvm::MCSection::getBeginSymbol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addString() {#ad3ca2f172998b53bd6458753acd65492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t MCDwarfLineStr::addString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds path <span class="doxyComputerOutput">Path</span> to the line string.</p>


<p>Returns offset in the .debug_line_str section.</p>


<p>Declaration at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Referenced by <a href="#ad325ab6e610eb8bd1f59534515561fdc">emitRef</a>.</p>

</div>
</div>

### emitRef() {#ad325ab6e610eb8bd1f59534515561fdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDwarfLineStr::emitRef (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit a reference to the string.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="#ad3ca2f172998b53bd6458753acd65492">addString</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a714de05372be0237bac97ad800dd2b52">llvm::MCStreamer::emitCOFFSecRel32</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a971830cc1546210be8cc86fa568be8d0">llvm::MCStreamer::emitIntValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a7833630c617e5943c0a41755f5d4bdcf">llvm::MCStreamer::emitValue</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#ae871de84d03670534d73ae7448b6b6d9">llvm::MCContext::getDwarfFormat</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#aa234436b20c856bcf616330ffcad6939">llvm::dwarf::getDwarfOffsetByteSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp/#ad484999912240f5615d60831473902cd">makeStartPlusIntExpr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### emitSection() {#a1578026c1ceb637e4b37023412f971ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MCDwarfLineStr::emitSection (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> * MCOS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit the .debug_line_str section if appropriate.</p>

<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a1d73c2da2d5410a07113b9f24c640c12">llvm::MCStreamer::emitBinaryData</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a61c979932b890df773ce75013b76708b">llvm::MCStreamer::getContext</a>, <a href="/web-llvm/docs/api/classes/llvm/mcobjectfileinfo/#a5e2906ef9fe9b6b1bef3e104b1519cd0">llvm::MCObjectFileInfo::getDwarfLineStrSection</a>, <a href="#a4d40dcd5c8c0c12f4036fe07992cce51">getFinalizedData</a>, <a href="/web-llvm/docs/api/classes/llvm/mccontext/#a01d6d82d18a5da901c50a546932c4264">llvm::MCContext::getObjectFileInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#ac4f84451dc4abc997c960d484953b1d2">llvm::MCStreamer::switchSection</a>.</p>

</div>
</div>

### getFinalizedData() {#a4d40dcd5c8c0c12f4036fe07992cce51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt; 0 &gt; MCDwarfLineStr::getFinalizedData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns finalized section.</p>

<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>, definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>.</p>


<p>Referenced by <a href="#a1578026c1ceb637e4b37023412f971ac">emitSection</a>.</p>

</div>
</div>

### getSaver() {#a021df1c95a6ab0401ba875c929054a07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSaver &amp; llvm::MCDwarfLineStr::getSaver ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Alloc {#ac8e084fd45fff812da2a1db509e6ff70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BumpPtrAllocator llvm::MCDwarfLineStr::Alloc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### LineStrings {#a454d48beb8586361981559e6d07a8173}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder llvm::MCDwarfLineStr::LineStrings {<a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder/#a58c8b5f09afd8827aed05c9a1804e73aafa19fdcc19d034fbc975465426a59188">StringTableBuilder::DWARF</a>}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### LineStrLabel {#ac23e254325d8eaa223a618ac1ec15c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::MCDwarfLineStr::LineStrLabel = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### Saver {#a7f4a5256c10c32a92651c42b49028940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSaver llvm::MCDwarfLineStr::Saver {Alloc}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

### UseRelocs {#ac4c038fafc18571becd3e699b6bd2e04}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MCDwarfLineStr::UseRelocs = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/mcdwarf-h">MCDwarf.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/mc/mcdwarf-cpp">MCDwarf.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
