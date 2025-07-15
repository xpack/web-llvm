---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/asmparser/parser-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `Parser.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/parser-h">llvm/AsmParser/Parser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/asmparser/llparser-h">llvm/AsmParser/LLParser.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/modulesummaryindex-h">llvm/IR/ModuleSummaryIndex.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/sourcemgr-h">llvm/Support/SourceMgr.h</a>"
#include &lt;system_error&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982f596dc670886cba9172ea00cb7a48">parseAssemblyInto</a> (MemoryBufferRef F, Module *M, ModuleSummaryIndex *Index, SMDiagnostic &amp;Err, SlotMapping *Slots, bool UpgradeDebugInfo, DataLayoutCallbackTy DataLayoutCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/parsedmoduleandindex">ParsedModuleAndIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12b5d43626934ce6993c5731098740e9">parseAssemblyWithIndex</a> (MemoryBufferRef F, SMDiagnostic &amp;Err, LLVMContext &amp;Context, SlotMapping *Slots, bool UpgradeDebugInfo, DataLayoutCallbackTy DataLayoutCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/parsedmoduleandindex">ParsedModuleAndIndex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff85bfef450fa1ae5ee06c97367f94e4">parseAssemblyFileWithIndex</a> (StringRef Filename, SMDiagnostic &amp;Err, LLVMContext &amp;Context, SlotMapping *Slots, bool UpgradeDebugInfo, DataLayoutCallbackTy DataLayoutCallback)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f2868a82e652c99a57c4dd99683af87">parseSummaryIndexAssemblyInto</a> (MemoryBufferRef F, ModuleSummaryIndex &amp;Index, SMDiagnostic &amp;Err)</td>
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

### parseAssemblyFileWithIndex() {#aff85bfef450fa1ae5ee06c97367f94e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParsedModuleAndIndex parseAssemblyFileWithIndex (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots, bool UpgradeDebugInfo, <a href="/web-llvm/docs/api/namespaces/llvm/#aa50ec5faa5aae091f99b0f840f58a379">DataLayoutCallbackTy</a> DataLayoutCallback)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp">Parser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#a346262ff27e71aff626fe6548ef8a777adaf658d40b0b4eb15c0350864c87c2b8">llvm::SourceMgr::DK_Error</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a7903f14c3b4fb5b4f9f9fa8b4ee0b4eb">llvm::ErrorOr&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1041a5a70dd1b5246ecb39f46a70a2f">llvm::parseAssemblyWithIndex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c29183c5faa7f5a352807af8aca268">llvm::UpgradeDebugInfo</a>.</p>

</div>
</div>

### parseAssemblyInto() {#a982f596dc670886cba9172ea00cb7a48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseAssemblyInto (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> F, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * Index, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Err, <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots, bool UpgradeDebugInfo, <a href="/web-llvm/docs/api/namespaces/llvm/#aa50ec5faa5aae091f99b0f840f58a379">DataLayoutCallbackTy</a> DataLayoutCallback)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp">Parser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#afe70aa1105a855036bdeb6426cac27db">llvm::SourceMgr::AddNewSourceBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/llparser/#aeabb9a69009bc6019e909b931db71937">llvm::LLParser::Run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c29183c5faa7f5a352807af8aca268">llvm::UpgradeDebugInfo</a>.</p>

</div>
</div>

### parseAssemblyWithIndex() {#a12b5d43626934ce6993c5731098740e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParsedModuleAndIndex parseAssemblyWithIndex (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> F, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Err, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context, <a href="/web-llvm/docs/api/structs/llvm/slotmapping">SlotMapping</a> * Slots, bool UpgradeDebugInfo, <a href="/web-llvm/docs/api/namespaces/llvm/#aa50ec5faa5aae091f99b0f840f58a379">DataLayoutCallbackTy</a> DataLayoutCallback)</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp">Parser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab372f737009f5f2e40d28dbc9066313e">llvm::parseAssemblyInto</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad3c29183c5faa7f5a352807af8aca268">llvm::UpgradeDebugInfo</a>.</p>

</div>
</div>

### parseSummaryIndexAssemblyInto() {#a3f2868a82e652c99a57c4dd99683af87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool parseSummaryIndexAssemblyInto (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> F, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic">SMDiagnostic</a> &amp; Err)</td>
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



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/asmparser/parser-cpp">Parser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sourcemgr/#afe70aa1105a855036bdeb6426cac27db">llvm::SourceMgr::AddNewSourceBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a> and <a href="/web-llvm/docs/api/classes/llvm/llparser/#aeabb9a69009bc6019e909b931db71937">llvm::LLParser::Run</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#af36afc49ebf4c466393ee9e5bff963e8">llvm::parseSummaryIndexAssembly</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
