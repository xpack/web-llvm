---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/forcefunctionattrspass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `ForceFunctionAttrsPass` Struct

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> which forces specific function attributes into the IR, primarily as a debugging tool. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ForceFunctionAttrsPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/forcefunctionattrs-h">llvm/Transforms/IPO/ForceFunctionAttrs.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/passinfomixin">PassInfoMixin&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A CRTP mix-in to automatically provide informational APIs needed for passes. <a href="/web-llvm/docs/api/structs/llvm/passinfomixin/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">PreservedAnalyses</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87517a35ede072d09d6c9889584780d5">run</a> (Module &amp;M, ModuleAnalysisManager &amp;)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/pass">Pass</a> which forces specific function attributes into the IR, primarily as a debugging tool.</p>

<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/forcefunctionattrs-h">ForceFunctionAttrs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### run() {#a87517a35ede072d09d6c9889584780d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreservedAnalyses ForceFunctionAttrsPass::run (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/namespaces/llvm/#af9c9208365fd9ce11392b4d79485e259">ModuleAnalysisManager</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/forcefunctionattrs-h">ForceFunctionAttrs.h</a>, definition at line 89 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attribute/#aa1d1daaf72feb4d1ecb59df592bdc3d7">llvm::Attribute::canUseAsFnAttr</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp/#ad56611176a728e6cb83b0e80c23bc4e4">CSVFilePath</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp/#a447453362ec26907f4116a81d6ac91f1">forceAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a0c53a4c5456480dc377772d5d2f4f832">llvm::Attribute::getAttrKindFromName</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a0f68098734d6d3b451aacf5b38a67131">llvm::MemoryBuffer::getMemBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp/#a89aaadc138883ed68b018666234257c9">hasForceAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a82ec15858b975dea72110e176c6e840e">llvm::line_iterator::is_at_end</a>, <a href="/web-llvm/docs/api/classes/llvm/line-iterator/#a51eb9a429555dd682d9b265cff7f869f">llvm::line_iterator::line_number</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/forcefunctionattrs-h">ForceFunctionAttrs.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
