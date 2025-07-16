---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/objectsizeopts
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ObjectSizeOpts` Struct Reference

<p>Various options to control the behavior of getObjectSize. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::ObjectSizeOpts { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">llvm/Analysis/MemoryBuiltins.h</a>"
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Mode : uint8_t { <a href="#a77eec32ab6be9e75a4b1f7cd5c4e5b8e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Controls how we handle conditional statements with unknown conditions. <a href="#a77eec32ab6be9e75a4b1f7cd5c4e5b8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a77eec32ab6be9e75a4b1f7cd5c4e5b8e">Mode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c614185ae8ad5ed7bd5ff0aa66f8242">EvalMode</a> = <a href="#a77eec32ab6be9e75a4b1f7cd5c4e5b8eadefd13f9ab5c5bd023984cbb0dac7109">Mode::ExactSizeFromOffset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>How we want to evaluate this object's size. <a href="#a0c614185ae8ad5ed7bd5ff0aa66f8242">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53a625d57d29696ca5cc6dd7a5ee94ee">RoundToAlign</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to round the result up to the alignment of allocas, byval arguments, and global variables. <a href="#a53a625d57d29696ca5cc6dd7a5ee94ee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0229c5396522e5a903a277fda4c3659c">NullIsUnknownSize</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this is true, null pointers in address space 0 will be treated as though they can't be evaluated. <a href="#a0229c5396522e5a903a277fda4c3659c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e6d4ff8dd1d58ffe5bf8ff600026ef">AA</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If set, used for more accurate evaluation. <a href="#a18e6d4ff8dd1d58ffe5bf8ff600026ef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Various options to control the behavior of getObjectSize.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Mode {#a77eec32ab6be9e75a4b1f7cd5c4e5b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ObjectSizeOpts::Mode : uint8_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Controls how we handle conditional statements with unknown conditions.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExactSizeFromOffset<a id="a77eec32ab6be9e75a4b1f7cd5c4e5b8eadefd13f9ab5c5bd023984cbb0dac7109"></a></td>
<td class="doxyEnumItemDescription">All branches must be known and have the same size, starting from the offset, to be merged</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExactUnderlyingSizeAndOffset<a id="a77eec32ab6be9e75a4b1f7cd5c4e5b8ea10113250545a1816e8c19f41c98467d2"></a></td>
<td class="doxyEnumItemDescription">All branches must be known and have the same underlying size and offset to be merged</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Min<a id="a77eec32ab6be9e75a4b1f7cd5c4e5b8ea78d811e98514cd165dda532286610fd2"></a></td>
<td class="doxyEnumItemDescription">Evaluate all branches of an unknown condition</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Max<a id="a77eec32ab6be9e75a4b1f7cd5c4e5b8ea6a061313d22e51e0f25b7cd4dc065233"></a></td>
<td class="doxyEnumItemDescription">Same as Min, except we pick the maximum size of all of the branches</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AA {#a18e6d4ff8dd1d58ffe5bf8ff600026ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AAResults* llvm::ObjectSizeOpts::AA = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If set, used for more accurate evaluation.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>.</p>

</div>
</div>

### EvalMode {#a0c614185ae8ad5ed7bd5ff0aa66f8242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Mode llvm::ObjectSizeOpts::EvalMode = <a href="#a77eec32ab6be9e75a4b1f7cd5c4e5b8eadefd13f9ab5c5bd023984cbb0dac7109">Mode::ExactSizeFromOffset</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>How we want to evaluate this object's size.</p>

<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>.</p>

</div>
</div>

### NullIsUnknownSize {#a0229c5396522e5a903a277fda4c3659c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ObjectSizeOpts::NullIsUnknownSize = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this is true, null pointers in address space 0 will be treated as though they can't be evaluated.</p>


<p>Otherwise, null is always considered to point to a 0 byte region of memory.</p>


<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aec29f5580509ec9a7592200e09b7aa27">computePointerICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a8bb1cb40cf03b28fb4fac792966ab7b2">getObjectSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/deadstoreelimination-cpp/#aa869f364a3c2e42a22fb605382eaf7c4">getPointerSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a3e49ed1824b63334071840d20aab03ba">isDereferenceableAndAlignedPointer</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a41052a5d27c665c41207f349f1a45af2">llvm::lowerObjectSizeCall</a>.</p>

</div>
</div>

### RoundToAlign {#a53a625d57d29696ca5cc6dd7a5ee94ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ObjectSizeOpts::RoundToAlign = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to round the result up to the alignment of allocas, byval arguments, and global variables.</p>

<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a0faf2520b671c3cb14b4f291c873cb88">addBoundsChecking</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#a8bb1cb40cf03b28fb4fac792966ab7b2">getObjectSize</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loads-cpp/#a3e49ed1824b63334071840d20aab03ba">isDereferenceableAndAlignedPointer</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/memorybuiltins-h">MemoryBuiltins.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
