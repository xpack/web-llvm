---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/tablegen/emitter/optclass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OptClass` Class Template Reference

<p>Convienence wrapper around <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt">Opt</a></span> that registers <span class="doxyComputerOutput">EmitterClass::run</span> as the callback. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class EmitterC&gt;
class llvm::TableGen::Emitter::OptClass&lt;EmitterC&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">llvm/TableGen/TableGenBackend.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt">Opt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creating an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt">Opt</a></span> object registers the command line option <span class="doxyComputerOutput">Name</span> with <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> backend and associates the callback <span class="doxyComputerOutput">CB</span> with that option. <a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class EmitterC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a8b4cc1e34d3d03f6841103ac5f847f5e">OptClass</a> (StringRef Name, StringRef Desc)</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class EmitterC&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a8b446a3a2900c44fc6dfd12b4318fc">run</a> (const RecordKeeper &amp;RK, raw_ostream &amp;OS)</td>
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

<p>Convienence wrapper around <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt">Opt</a></span> that registers <span class="doxyComputerOutput">EmitterClass::run</span> as the callback.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### OptClass() {#a8b4cc1e34d3d03f6841103ac5f847f5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class EmitterC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::TableGen::Emitter::OptClass&lt; EmitterC &gt;::OptClass (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Desc)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt/#a9987489a9dc651e9c1f98a440fe4a3e0">llvm::TableGen::Emitter::Opt::Opt</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### run() {#a7a8b446a3a2900c44fc6dfd12b4318fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class EmitterC&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::TableGen::Emitter::OptClass&lt; EmitterC &gt;::run (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; RK, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
