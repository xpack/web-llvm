---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/dumpobjects
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DumpObjects` Class Reference

<p>A function object that can be used as an <a href="/web-llvm/docs/api/classes/llvm/orc/objecttransformlayer">ObjectTransformLayer</a> transform to dump object files to disk at a specified path. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::DumpObjects { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">llvm/ExecutionEngine/Orc/DebugUtils.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcdecffed69334cfd8fc517836656751">DumpObjects</a> (std::string DumpDir="", std::string IdentifierOverride="")</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/dumpobjects">DumpObjects</a> transform that will dump objects to disk. <a href="#afcdecffed69334cfd8fc517836656751">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0dc48bd5c7938d84780ec3e63378a13">operator()</a> (std::unique_ptr&lt; MemoryBuffer &gt; Obj)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dumps the given buffer to disk. <a href="#aa0dc48bd5c7938d84780ec3e63378a13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65bd7cb92351275601f2a7e0d2a5ae1">getBufferIdentifier</a> (MemoryBuffer &amp;B)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d6d2beb7800f26c8ee31b8052805c45">DumpDir</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc0e40c13366e7fcf7bd67031571c360">IdentifierOverride</a></td>
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

<p>A function object that can be used as an <a href="/web-llvm/docs/api/classes/llvm/orc/objecttransformlayer">ObjectTransformLayer</a> transform to dump object files to disk at a specified path.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">DebugUtils.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DumpObjects() {#afcdecffed69334cfd8fc517836656751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::DumpObjects::DumpObjects (std::string DumpDir="", std::string IdentifierOverride="")</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/orc/dumpobjects">DumpObjects</a> transform that will dump objects to disk.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">DumpDir</td>
<td class="doxyParamItemDescription"><p>specifies the path to write dumped objects to. DumpDir may be empty, in which case files will be dumped to the working directory. If DumpDir is non-empty then any trailing separators will be discarded.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">IdentifierOverride</td>
<td class="doxyParamItemDescription"><p>specifies a file name stem to use when dumping objects. If empty, each <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a>'s identifier will be used (with a .o suffix added if not already present). If an identifier override is supplied it will be used instead (since all buffers will use the same identifier, the resulting files will be named &lt;ident&gt;.o, &lt;ident&gt;.2.o, &lt;ident&gt;.3.o, and so on). IdentifierOverride should not contain an extension, as a .o suffix will be added by <a href="/web-llvm/docs/api/classes/llvm/orc/dumpobjects">DumpObjects</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">DebugUtils.h</a>, definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aecbfb983627865ec98e96179df881e37">llvm::sys::path::is_separator</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator()() {#aa0dc48bd5c7938d84780ec3e63378a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; MemoryBuffer &gt; &gt; llvm::orc::DumpObjects::operator() (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dumps the given buffer to disk.</p>

<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">DebugUtils.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a645a607ffcccb12f16a5736db991e7d9">llvm::sys::fs::exists</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a980ad6112624b521eb2d831b39b346eb">llvm::raw_ostream::getBufferStart</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getBufferIdentifier() {#ad65bd7cb92351275601f2a7e0d2a5ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::orc::DumpObjects::getBufferIdentifier (<a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">DebugUtils.h</a>, definition at line 344 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DumpDir {#a1d6d2beb7800f26c8ee31b8052805c45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::DumpObjects::DumpDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">DebugUtils.h</a>.</p>

</div>
</div>

### IdentifierOverride {#acc0e40c13366e7fcf7bd67031571c360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::DumpObjects::IdentifierOverride</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">DebugUtils.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/debugutils-h">DebugUtils.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/debugutils-cpp">DebugUtils.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
