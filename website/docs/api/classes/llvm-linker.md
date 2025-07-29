---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/linker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Linker` Class

<p>This class provides the core functionality of linking in LLVM. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Linker { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">llvm/Linker/Linker.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Flags { <a href="#a355e72d5c66c2cd4dd386466d8529e8f">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56c10a0bc69aa90244ef1e9a16afd8c">Linker</a> (Module &amp;M)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a864cc4d71e0234e9f8d786f8716804">linkInModule</a> (std::unique_ptr&lt; Module &gt; Src, unsigned Flags=Flags::None, std::function&lt; void(Module &amp;, const StringSet&lt;&gt; &amp;)&gt; InternalizeCallback={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Link <span class="doxyComputerOutput">Src</span> into the composite. <a href="#a5a864cc4d71e0234e9f8d786f8716804">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irmover">IRMover</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f34e20c78dade3665405aaffd1186bd">Mover</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e11e8404db974fa400748b888ea49d">linkModules</a> (Module &amp;Dest, std::unique_ptr&lt; Module &gt; Src, unsigned Flags=Flags::None, std::function&lt; void(Module &amp;, const StringSet&lt;&gt; &amp;)&gt; InternalizeCallback={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function links two modules together, with the resulting Dest module modified to be the composite of the two input modules. <a href="#a72e11e8404db974fa400748b888ea49d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class provides the core functionality of linking in LLVM.</p>


<p>It keeps a pointer to the merged module so far. It doesn't take ownership of the module since it is assumed that the user of this class will want to do something with it after the linking.</p>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">Linker.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Flags {#a355e72d5c66c2cd4dd386466d8529e8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Linker::Flags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">None<a id="a355e72d5c66c2cd4dd386466d8529e8fa063ce462fbdba434772c3d043c4d8c7c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OverrideFromSrc<a id="a355e72d5c66c2cd4dd386466d8529e8fa0d6c6444920bff00301b3d07715296be"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LinkOnlyNeeded<a id="a355e72d5c66c2cd4dd386466d8529e8fa99c4f9a71a7a6d9b781af547adb9bc8f"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">Linker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Linker() {#ad56c10a0bc69aa90244ef1e9a16afd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Linker::Linker (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">Linker.h</a>, definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>


<p>Referenced by <a href="#a72e11e8404db974fa400748b888ea49d">linkModules</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### linkInModule() {#a5a864cc4d71e0234e9f8d786f8716804}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Linker::linkInModule (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; Src, unsigned Flags=<a href="#a355e72d5c66c2cd4dd386466d8529e8fa063ce462fbdba434772c3d043c4d8c7c">Flags::None</a>, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; &amp;)&gt; InternalizeCallback={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Link <span class="doxyComputerOutput">Src</span> into the composite.</p>


<p>Passing OverrideSymbols as true will have symbols from Src shadow those in the Dest.</p>


<p>Passing InternalizeCallback will have the linker call the function with the new module and a list of global value names to be internalized by the callback.</p>


<p>Returns true on error.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">Linker.h</a>, definition at line 623 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Mover {#a4f34e20c78dade3665405aaffd1186bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRMover llvm::Linker::Mover</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">Linker.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### linkModules() {#a72e11e8404db974fa400748b888ea49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Linker::linkModules (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; Dest, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; Src, unsigned Flags=<a href="#a355e72d5c66c2cd4dd386466d8529e8fa063ce462fbdba434772c3d043c4d8c7c">Flags::None</a>, std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a>&lt;&gt; &amp;)&gt; InternalizeCallback={})</td>
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

<p>This function links two modules together, with the resulting Dest module modified to be the composite of the two input modules.</p>


<p>If an error occurs, true is returned and ErrorMsg (if not null) is set to indicate the problem. Upon failure, the Dest module could be in a modified state, and shouldn't be relied on to be consistent.</p>


<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">Linker.h</a>, definition at line 640 of file <a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a>.</p>


<p>Reference <a href="#ad56c10a0bc69aa90244ef1e9a16afd8c">Linker</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccorelinker/#gae18bee20a3140da8a2b2ebb8edcf4bed">LLVMLinkModules2</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/linker/linker-h">Linker.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/linker/linkmodules-cpp">LinkModules.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
