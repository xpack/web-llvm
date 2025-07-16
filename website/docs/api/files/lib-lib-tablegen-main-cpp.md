---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/tablegen/main-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Main.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/main-h">llvm/TableGen/Main.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tglexer-h">TGLexer.h</a>"
#include "<a href="/web-llvm/docs/api/files/lib/lib/tablegen/tgparser-h">TGParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/stringref-h">llvm/ADT/StringRef.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/twine-h">llvm/ADT/Twine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/erroror-h">llvm/Support/ErrorOr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/filesystem-h">llvm/Support/FileSystem.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smloc-h">llvm/Support/SMLoc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/tooloutputfile-h">llvm/Support/ToolOutputFile.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/error-h">llvm/TableGen/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/record-h">llvm/TableGen/Record.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tgtimer-h">llvm/TableGen/TGTimer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/tablegen/tablegenbackend-h">llvm/TableGen/TableGenBackend.h</a>"
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;system_error&gt;
#include &lt;utility&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1491396cfef16b592355c5ba7fca450">reportError</a> (const char *ProgName, Twine Msg)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cdb223afb9f4268a3716aaac56826bd">createDependencyFile</a> (const TGParser &amp;Parser, const char *argv0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a dependency file for <span class="doxyComputerOutput">-d</span> option. <a href="#a5cdb223afb9f4268a3716aaac56826bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a896200b9a8add6ca7edf3034cb031fea">OutputFilename</a>("o", cl::desc("Output filename"), cl::value_desc("filename"), cl::init("-"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c646cbf04903c936329264a31f2e674">DependFilename</a>("d", cl::desc("Dependency filename"), cl::value_desc("filename"), cl::init(""))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa0fa37480ba9aa590065846d7ccb1d2">InputFilename</a>(cl::Positional, cl::desc("<input file>"), cl::init("-"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14127d1d9dc8491608c83fd7ac07e04f">IncludeDirs</a>("I", cl::desc("Directory of include files"), cl::value_desc("directory"), cl::Prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8a174d41326dfaa51c8aa97b343c2ef">MacroNames</a>("D", cl::desc("Name of the macro to be defined"), cl::value_desc("macro name"), cl::Prefix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c1afd7d4f140c7ac201372b094f2be">WriteIfChanged</a>("write-if-changed", cl::desc("Only write output if it changed"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b75b0717f23e260cedcf20b72e15c55">TimePhases</a>("time-phases", cl::desc("Time phases of parser and backend"))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a034b08d8b50b5fbc801c672cdf3ac6a5">NoWarnOnUnusedTemplateArgs</a>("no-warn-on-unused-template-args", cl::desc("Disable unused template argument warnings."))</td>
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

### createDependencyFile() {#a5cdb223afb9f4268a3716aaac56826bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int createDependencyFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/tgparser">TGParser</a> &amp; Parser, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * argv0)</td>
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

<p>Create a dependency file for <span class="doxyComputerOutput">-d</span> option.</p>


<p>This functionality is really only for the benefit of the build system. It is similar to GCC's <span class="doxyComputerOutput">-M*</span> family of options.</p>


<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>References <a href="#a7c646cbf04903c936329264a31f2e674">DependFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/tgparser/#a58685cdd792796ad7d316a781ebd7089">llvm::TGParser::getDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile/#a736bcda698a82e4ae3a92310d706868d">llvm::ToolOutputFile::keep</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a6118bd1b7164f1f8f02470a5cb6a538b">llvm::sys::fs::OF_Text</a>, <a href="/web-llvm/docs/api/classes/llvm/tooloutputfile/#afd739434d6e7e26f93a9e87c23e4e7a3">llvm::ToolOutputFile::os</a>, <a href="#a896200b9a8add6ca7edf3034cb031fea">OutputFilename</a> and <a href="#af1491396cfef16b592355c5ba7fca450">reportError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### reportError() {#af1491396cfef16b592355c5ba7fca450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int reportError (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * ProgName, <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> Msg)</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>.</p>


<p>Referenced by <a href="#a5cdb223afb9f4268a3716aaac56826bd">createDependencyFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### DependFilename {#a7c646cbf04903c936329264a31f2e674}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; DependFilename("d", cl::desc("Dependency filename"), cl::value_desc("filename"), cl::init(""))</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="#a5cdb223afb9f4268a3716aaac56826bd">createDependencyFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### IncludeDirs {#a14127d1d9dc8491608c83fd7ac07e04f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; IncludeDirs("I", cl::desc("Directory of include files"), cl::value_desc("directory"), cl::Prefix)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### InputFilename {#aaa0fa37480ba9aa590065846d7ccb1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; InputFilename(cl::Positional, cl::desc("&lt;input file&gt;"), cl::init("-"))</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/elf/elfobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/macho/machoobjcopy-cpp/#aa40e91285159d4c13a609b1810b19485">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/wasm/#ab4c167a5e231ccb60ec1eb5552ca233b">llvm::objcopy::wasm::dumpSectionToFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### MacroNames {#ae8a174d41326dfaa51c8aa97b343c2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; MacroNames("D", cl::desc("Name of the macro to be defined"), cl::value_desc("macro name"), cl::Prefix)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### NoWarnOnUnusedTemplateArgs {#a034b08d8b50b5fbc801c672cdf3ac6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; NoWarnOnUnusedTemplateArgs("no-warn-on-unused-template-args", cl::desc("Disable unused template argument warnings."))</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### OutputFilename {#a896200b9a8add6ca7edf3034cb031fea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; OutputFilename("o", cl::desc("Output filename"), cl::value_desc("filename"), cl::init("-"))</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/filepermissionsapplier/#a958cd3b9790b98d062b8e5fb5ebc32e6">llvm::FilePermissionsApplier::apply</a>, <a href="#a5cdb223afb9f4268a3716aaac56826bd">createDependencyFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a09515ea8784bdea8e0e866799bb38409">llvm::CreateInfoOutputFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2ac93a817bcb1ef2549c8e737866b7a3">llvm::DisplayGraph</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af1ad9f56998b03b32a1066b574125126">llvm::EmitImportsFiles</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aaf0263a348d44245abd76df0d07af9ea">llvm::AsmPrinter::emitStackUsage</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### TimePhases {#a8b75b0717f23e260cedcf20b72e15c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; TimePhases("time-phases", cl::desc("Time phases of parser and backend"))</td>
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



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>.</p>

</div>
</div>

### WriteIfChanged {#a62c1afd7d4f140c7ac201372b094f2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; bool &gt; WriteIfChanged("write-if-changed", cl::desc("Only write output if it changed"))</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp">Main.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a969d49f2536556ecd3442e9a8279fe15">llvm::TableGenMain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a97f8c83dd15571db29c576450a8264e2">llvm::ifs::writeBinaryStub</a> and <a href="/web-llvm/docs/api/namespaces/llvm/ifs/#a101c2836638ffc1c34e2e502ad68d0da">llvm::ifs::writeELFBinaryToFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
