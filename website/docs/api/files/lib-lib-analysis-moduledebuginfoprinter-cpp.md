---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/analysis/moduledebuginfoprinter-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ModuleDebugInfoPrinter.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/moduledebuginfoprinter-h">llvm/Analysis/ModuleDebugInfoPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfo-h">llvm/IR/DebugInfo.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/pass-h">llvm/Pass.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h">llvm/Support/ErrorHandling.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf578ca2e23ec24ac92210d63747ca0">printFile</a> (raw_ostream &amp;O, StringRef Filename, StringRef Directory, unsigned Line=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a24d20274ad98afd584ab1c1de6cdfb">printModuleDebugInfo</a> (raw_ostream &amp;O, const Module *M, const DebugInfoFinder &amp;Finder)</td>
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


<div class="doxySectionDef">

## Functions

### printFile() {#acbf578ca2e23ec24ac92210d63747ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printFile (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Directory, unsigned Line=0)</td>
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



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/moduledebuginfoprinter-cpp">ModuleDebugInfoPrinter.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>.</p>


<p>Referenced by <a href="#a1a24d20274ad98afd584ab1c1de6cdfb">printModuleDebugInfo</a>.</p>

</div>
</div>

### printModuleDebugInfo() {#a1a24d20274ad98afd584ab1c1de6cdfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void printModuleDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; O, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder">DebugInfoFinder</a> &amp; Finder)</td>
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



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/moduledebuginfoprinter-cpp">ModuleDebugInfoPrinter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga8a7e29291b6e812a89dcdbb07948c0ac">llvm::dwarf::AttributeEncodingString</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder/#ae6c27c3f4b0e09a088b582df980f0238">llvm::DebugInfoFinder::compile_units</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder/#ab2dad7176b1cbfd1313807d054421084">llvm::DebugInfoFinder::global_variables</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#ga6040ef7c99341269e7c3ffe8347f72b3">llvm::dwarf::LanguageString</a>, <a href="#acbf578ca2e23ec24ac92210d63747ca0">printFile</a>, <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder/#ab46cbea3f0c8ddd0ddb33a69a7213a9a">llvm::DebugInfoFinder::subprograms</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/groups/dwarfconstantsdumping/#gaf17a843ca40c67635b127ba50ad45bdf">llvm::dwarf::TagString</a> and <a href="/web-llvm/docs/api/classes/llvm/debuginfofinder/#acd678837d688e6c676bdba6b8d12a95d">llvm::DebugInfoFinder::types</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/moduledebuginfoprinterpass/#a0c14bc5fba5000829a981ee9a17d00be">llvm::ModuleDebugInfoPrinterPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
