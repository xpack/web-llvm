---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/debuginfoperpass
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DebugInfoPerPass` Struct Reference

<p>Used to track the Debug Info Metadata information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct DebugInfoPerPass { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">llvm/Transforms/Utils/Debugify.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a4b96511d25a6961a44edfbfbf7868ba4">DebugFnMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf923996a54e0206a5fb9e665ed0a17">DIFunctions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a73236f7f4b807ff6fbbb80d8783beb91">DebugInstMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c856759d515a856df4294aa8a60ccc1">DILocations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a837564d2ec7dc9b49a534242135e1997">WeakInstValueMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a233bc305852872d1f2731483f853e">InstToDelete</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h/#a88f4c7f22c84b7c35e08b9a633ce258d">DebugVarMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e1b06ef29af916f5cefad78589036aa">DIVariables</a></td>
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

<p>Used to track the Debug Info Metadata information.</p>

<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### DIFunctions {#a5bf923996a54e0206a5fb9e665ed0a17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugFnMap DebugInfoPerPass::DIFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>.</p>

</div>
</div>

### DILocations {#a4c856759d515a856df4294aa8a60ccc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugInstMap DebugInfoPerPass::DILocations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>.</p>

</div>
</div>

### DIVariables {#a9e1b06ef29af916f5cefad78589036aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DebugVarMap DebugInfoPerPass::DIVariables</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>.</p>

</div>
</div>

### InstToDelete {#af6a233bc305852872d1f2731483f853e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WeakInstValueMap DebugInfoPerPass::InstToDelete</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b1daaa72630852c5b859e1410e69a55">llvm::checkDebugInfoMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e556eb90cea56b01be517fbf549fd84">llvm::collectDebugInfoMetadata</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/debugify-h">Debugify.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
