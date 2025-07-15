---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/tablegen/emitter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `Emitter` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::TableGen::Emitter { ... }
</div>

## Classes Index

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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a6979b4038e161a738f9e031d925af3">FnT</a> = <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; void(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp;Records, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;OS)&gt;</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8ce24c3c1a2d743d528e1bb58731d17">ApplyCallback</a> (const RecordKeeper &amp;Records, raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply callback for any command line option registered above. <a href="#ad8ce24c3c1a2d743d528e1bb58731d17">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### FnT {#a8a6979b4038e161a738f9e031d925af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::TableGen::Emitter::FnT =  function_ref&lt;void(const RecordKeeper &amp;Records, raw_ostream &amp;OS)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### ApplyCallback() {#ad8ce24c3c1a2d743d528e1bb58731d17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::TableGen::Emitter::ApplyCallback (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/recordkeeper">RecordKeeper</a> &amp; Records, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply callback for any command line option registered above.</p>


<p>Apply callback specified on the command line.</p>


<p>Returns false is no callback was applied.</p>


<p>Returns true if no callback was applied.</p>


<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a>, definition at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp">TableGenBackend.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp/#a48b2ed3cd15847ee80711a00102b0c10">CallbackFunction</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">TableGenBackend.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp">TableGenBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
