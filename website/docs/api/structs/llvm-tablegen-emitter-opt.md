---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/tablegen/emitter/opt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Opt` Struct

<p>Creating an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt">Opt</a></span> object registers the command line option <span class="doxyComputerOutput">Name</span> with <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> backend and associates the callback <span class="doxyComputerOutput">CB</span> with that option. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::TableGen::Emitter::Opt { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">llvm/TableGen/TableGenBackend.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/tablegen/emitter/optclass">OptClass&lt;EmitterC&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convienence wrapper around <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt">Opt</a></span> that registers <span class="doxyComputerOutput">EmitterClass::run</span> as the callback. <a href="/web-llvm/docs/api/classes/llvm/tablegen/emitter/optclass/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9987489a9dc651e9c1f98a440fe4a3e0">Opt</a> (StringRef Name, FnT CB, StringRef Desc, bool ByDefault=false)</td>
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

<p>Creating an <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/tablegen/emitter/opt">Opt</a></span> object registers the command line option <span class="doxyComputerOutput">Name</span> with <a href="/web-llvm/docs/api/namespaces/llvm/tablegen">TableGen</a> backend and associates the callback <span class="doxyComputerOutput">CB</span> with that option.</p>


<p>If <span class="doxyComputerOutput">ByDefault</span> is true, then that callback is applied by default if no command line option was specified.</p>


<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Opt() {#a9987489a9dc651e9c1f98a440fe4a3e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Opt::Opt (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/namespaces/llvm/tablegen/emitter/#a8a6979b4038e161a738f9e031d925af3">FnT</a> CB, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Desc, bool ByDefault=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a>, definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp">TableGenBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp/#a48b2ed3cd15847ee80711a00102b0c10">CallbackFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/tablegen/emitter/optclass/#a8b4cc1e34d3d03f6841103ac5f847f5e">llvm::TableGen::Emitter::OptClass&lt; EmitterC &gt;::OptClass</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp">TableGenBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
