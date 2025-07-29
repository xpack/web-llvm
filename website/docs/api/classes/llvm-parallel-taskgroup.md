---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/parallel/taskgroup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TaskGroup` Class



## Declaration

<div class="doxyDeclaration">
class llvm::parallel::TaskGroup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">llvm/Support/Parallel.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383436e232e602a67d0f17c76a97057e">TaskGroup</a> ()</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fcdb4a971f8751ed7e3ea6150fdd0fb">~TaskGroup</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f936d7e589b0615fccac0a4c0cb8d97">spawn</a> (std::function&lt; void()&gt; f)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18480d77fc6939382cda718bb765e73c">sync</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73d6cfbb62c4f5841a20e4586ba692fc">isParallel</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/parallel/detail/latch">detail::Latch</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e3717c374ef23c8a0ecefb21fa1b6b">L</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accb2d35afbe37510785ef81bdf756490">Parallel</a></td>
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


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TaskGroup() {#a383436e232e602a67d0f17c76a97057e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::parallel::TaskGroup::TaskGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/support/parallel-cpp">Parallel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/parallel/#a68f04a4e2c26fa6b9cd7517dced50729">llvm::parallel::strategy</a> and <a href="#a383436e232e602a67d0f17c76a97057e">TaskGroup</a>.</p>


<p>Referenced by <a href="#a383436e232e602a67d0f17c76a97057e">TaskGroup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TaskGroup() {#a1fcdb4a971f8751ed7e3ea6150fdd0fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::parallel::TaskGroup::~TaskGroup ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/support/parallel-cpp">Parallel.cpp</a>.</p>


<p>Reference <a href="#a1fcdb4a971f8751ed7e3ea6150fdd0fb">~TaskGroup</a>.</p>


<p>Referenced by <a href="#a1fcdb4a971f8751ed7e3ea6150fdd0fb">~TaskGroup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isParallel() {#a73d6cfbb62c4f5841a20e4586ba692fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::parallel::TaskGroup::isParallel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>.</p>

</div>
</div>

### spawn() {#a5f936d7e589b0615fccac0a4c0cb8d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::parallel::TaskGroup::spawn (std::function&lt; void()&gt; f)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/support/parallel-cpp">Parallel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a5f936d7e589b0615fccac0a4c0cb8d97">spawn</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a41d82740af65d76898c3580c88ef460a">llvm::dwarf_linker::parallel::DWARFLinkerImpl::assignOffsets</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/typeunit/#aafd0fac7574417fa923ca2bce4b9b85c">llvm::dwarf_linker::parallel::TypeUnit::createDIETree</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#ac8c9b6d8ca3948e29ec1511b6037cdcf">llvm::dwarf_linker::parallel::DWARFLinkerImpl::emitCommonSectionsAndWriteCompileUnitsToTheOutput</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarflinkerimpl/#a42302ab883ef8ec7e51b00701d626ce4">llvm::dwarf_linker::parallel::DWARFLinkerImpl::link</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ad06d8aa0d7980827ad6f0a8543657f73">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::link</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aca37fe9da8af401451f8bb3c8241f83d">llvm::parallelFor</a> and <a href="#a5f936d7e589b0615fccac0a4c0cb8d97">spawn</a>.</p>

</div>
</div>

### sync() {#a18480d77fc6939382cda718bb765e73c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::parallel::TaskGroup::sync ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### L {#aa7e3717c374ef23c8a0ecefb21fa1b6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">detail::Latch llvm::parallel::TaskGroup::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>.</p>

</div>
</div>

### Parallel {#accb2d35afbe37510785ef81bdf756490}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::parallel::TaskGroup::Parallel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/parallel-h">Parallel.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/parallel-cpp">Parallel.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
