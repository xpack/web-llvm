---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ForceFunctionAttrs.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/ipo/forcefunctionattrs-h">llvm/Transforms/IPO/ForceFunctionAttrs.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/function-h">llvm/IR/Function.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/commandline-h">llvm/Support/CommandLine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h">llvm/Support/Debug.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/lineiterator-h">llvm/Support/LineIterator.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/memorybuffer-h">llvm/Support/MemoryBuffer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a447453362ec26907f4116a81d6ac91f1">forceAttributes</a> (Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If F has any forced attributes given on the command line, add them. <a href="#a447453362ec26907f4116a81d6ac91f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89aaadc138883ed68b018666234257c9">hasForceAttributes</a> ()</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/cl/list">cl::list</a>&lt; <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#ae2b0d0345572d6718e219aa76d1d54edab45cffe084dd3d20d928bee85e7b0f21">std::string</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998cacac480f8acfb935b027f332a917">ForceAttributes</a>("force-attribute", cl::Hidden, cl::desc("Add an attribute to a function. This can be a " "pair of 'function-name:attribute-name', to apply an attribute to a " "specific function. For " "example -force-attribute=foo:noinline. Specifying only an attribute " "will apply the attribute to every function in the module. This " "option can be specified multiple times."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a6343433a018bf45ceae1f0b7d4466">ForceRemoveAttributes</a>("force-remove-attribute", cl::Hidden, cl::desc("Remove an attribute from a function. This can be a " "pair of 'function-name:attribute-name' to remove an attribute " "from a specific function. For " "example -force-remove-attribute=foo:noinline. Specifying only an " "attribute will remove the attribute from all functions in the " "module. This " "option can be specified multiple times."))</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56611176a728e6cb83b0e80c23bc4e4">CSVFilePath</a>("forceattrs-csv-path", cl::Hidden, cl::desc("Path to CSV file containing lines of function names and attributes to " "add to them in the form of `f1,attr1` or `f2,attr2=str`."))</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>&nbsp;&nbsp;&nbsp;"forceattrs"</td>
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

### forceAttributes() {#a447453362ec26907f4116a81d6ac91f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void forceAttributes (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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

<p>If F has any forced attributes given on the command line, add them.</p>


<p>If F has any forced remove attributes given on the command line, remove them. When both force and force-remove are given to a function, the latter takes precedence.</p>


<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attribute/#aa1d1daaf72feb4d1ecb59df592bdc3d7">llvm::Attribute::canUseAsFnAttr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="#a998cacac480f8acfb935b027f332a917">ForceAttributes</a>, <a href="#ab1a6343433a018bf45ceae1f0b7d4466">ForceRemoveAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a0c53a4c5456480dc377772d5d2f4f832">llvm::Attribute::getAttrKindFromName</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#aab7ee4b8fd1d3e7e4cea87868855e60ea5e58e419b1c9e35d6131976412fd8f0c">llvm::Attribute::None</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a0320b2a5a6d440bf4479a02e78cf5ca7">llvm::StringRef::split</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>.</p>

</div>
</div>

### hasForceAttributes() {#a89aaadc138883ed68b018666234257c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool hasForceAttributes ()</td>
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



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a>.</p>


<p>References <a href="#a998cacac480f8acfb935b027f332a917">ForceAttributes</a> and <a href="#ab1a6343433a018bf45ceae1f0b7d4466">ForceRemoveAttributes</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### CSVFilePath {#ad56611176a728e6cb83b0e80c23bc4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::opt&lt; std::string &gt; CSVFilePath("forceattrs-csv-path", cl::Hidden, cl::desc( "Path to CSV file containing lines of function names and attributes to " "add to them in the form of `f1,attr1` or `f2,attr2=str`."))</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/forcefunctionattrspass/#a87517a35ede072d09d6c9889584780d5">llvm::ForceFunctionAttrsPass::run</a>.</p>

</div>
</div>

### ForceAttributes {#a998cacac480f8acfb935b027f332a917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; ForceAttributes("force-attribute", cl::Hidden, cl::desc( "Add an attribute to a function. This can be a " "pair of 'function-name:attribute-name', to apply an attribute to a " "specific function. For " "example -force-attribute=foo:noinline. Specifying only an attribute " "will apply the attribute to every function in the module. This " "option can be specified multiple times."))</td>
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



<p>Definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a447453362ec26907f4116a81d6ac91f1">forceAttributes</a> and <a href="#a89aaadc138883ed68b018666234257c9">hasForceAttributes</a>.</p>

</div>
</div>

### ForceRemoveAttributes {#ab1a6343433a018bf45ceae1f0b7d4466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">cl::list&lt; std::string &gt; ForceRemoveAttributes("force-remove-attribute", cl::Hidden, cl::desc("Remove an attribute from a function. This can be a " "pair of 'function-name:attribute-name' to remove an attribute " "from a specific function. For " "example -force-remove-attribute=foo:noinline. Specifying only an " "attribute will remove the attribute from all functions in the " "module. This " "option can be specified multiple times."))</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a>.</p>


<p>Referenced by <a href="#a447453362ec26907f4116a81d6ac91f1">forceAttributes</a> and <a href="#a89aaadc138883ed68b018666234257c9">hasForceAttributes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DEBUG\_TYPE {#ad78e062f62e0d6e453941fb4ca843e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DEBUG_TYPE&nbsp;&nbsp;&nbsp;"forceattrs"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/forcefunctionattrs-cpp">ForceFunctionAttrs.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
