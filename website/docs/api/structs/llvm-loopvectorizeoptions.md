---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/loopvectorizeoptions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `LoopVectorizeOptions` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::LoopVectorizeOptions { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">llvm/Transforms/Vectorize/LoopVectorize.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6783f8be2f000616bf0c2c34cae65ad0">LoopVectorizeOptions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The current defaults when creating the pass with no arguments are: EnableLoopInterleaving = true and EnableLoopVectorization = true. <a href="#a6783f8be2f000616bf0c2c34cae65ad0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c26328cd96546a50d896e9bfa6953d7">LoopVectorizeOptions</a> (bool InterleaveOnlyWhenForced, bool VectorizeOnlyWhenForced)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopvectorizeoptions">LoopVectorizeOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5393e0c3e4331c12efc4ec4f91096cd5">setInterleaveOnlyWhenForced</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/loopvectorizeoptions">LoopVectorizeOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e069859198ff7a4972b1c2af8d4674e">setVectorizeOnlyWhenForced</a> (bool Value)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ffc347deee18f567b88ce71101d45d">InterleaveOnlyWhenForced</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, consider all loops for interleaving. <a href="#ac6ffc347deee18f567b88ce71101d45d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac73f29a1b055929ead9221ab91e1dd10">VectorizeOnlyWhenForced</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If false, consider all loops for vectorization. <a href="#ac73f29a1b055929ead9221ab91e1dd10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LoopVectorizeOptions() {#a6783f8be2f000616bf0c2c34cae65ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopVectorizeOptions::LoopVectorizeOptions ()</td>
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

<p>The current defaults when creating the pass with no arguments are: EnableLoopInterleaving = true and EnableLoopVectorization = true.</p>


<p>This means that interleaving default is consistent with the <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a> flag, while vectorization is not. FIXME: The default for EnableLoopVectorization in the <a href="/web-llvm/docs/api/classes/llvm/cl/opt">cl::opt</a> should be set to true, and the corresponding change to account for this be made in opt.cpp. The initializations below will become: InterleaveOnlyWhenForced(!EnableLoopInterleaving) VectorizeOnlyWhenForced(!EnableLoopVectorization).</p>


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>References <a href="#ac6ffc347deee18f567b88ce71101d45d">InterleaveOnlyWhenForced</a> and <a href="#ac73f29a1b055929ead9221ab91e1dd10">VectorizeOnlyWhenForced</a>.</p>


<p>Referenced by <a href="#a5393e0c3e4331c12efc4ec4f91096cd5">setInterleaveOnlyWhenForced</a> and <a href="#a3e069859198ff7a4972b1c2af8d4674e">setVectorizeOnlyWhenForced</a>.</p>

</div>
</div>

### LoopVectorizeOptions() {#a2c26328cd96546a50d896e9bfa6953d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::LoopVectorizeOptions::LoopVectorizeOptions (bool InterleaveOnlyWhenForced, bool VectorizeOnlyWhenForced)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>References <a href="#ac6ffc347deee18f567b88ce71101d45d">InterleaveOnlyWhenForced</a> and <a href="#ac73f29a1b055929ead9221ab91e1dd10">VectorizeOnlyWhenForced</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setInterleaveOnlyWhenForced() {#a5393e0c3e4331c12efc4ec4f91096cd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizeOptions &amp; llvm::LoopVectorizeOptions::setInterleaveOnlyWhenForced (bool Value)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>References <a href="#ac6ffc347deee18f567b88ce71101d45d">InterleaveOnlyWhenForced</a> and <a href="#a6783f8be2f000616bf0c2c34cae65ad0">LoopVectorizeOptions</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a0bf1de19ee39f1ce18df8c0b5e42a1c2">anonymous{PassBuilder.cpp}::parseLoopVectorizeOptions</a>.</p>

</div>
</div>

### setVectorizeOnlyWhenForced() {#a3e069859198ff7a4972b1c2af8d4674e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoopVectorizeOptions &amp; llvm::LoopVectorizeOptions::setVectorizeOnlyWhenForced (bool Value)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>References <a href="#a6783f8be2f000616bf0c2c34cae65ad0">LoopVectorizeOptions</a> and <a href="#ac73f29a1b055929ead9221ab91e1dd10">VectorizeOnlyWhenForced</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-passbuilder-cpp-/#a0bf1de19ee39f1ce18df8c0b5e42a1c2">anonymous{PassBuilder.cpp}::parseLoopVectorizeOptions</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### InterleaveOnlyWhenForced {#ac6ffc347deee18f567b88ce71101d45d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizeOptions::InterleaveOnlyWhenForced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, consider all loops for interleaving.</p>


<p>If true, only loops that explicitly request interleaving are considered.</p>


<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a6783f8be2f000616bf0c2c34cae65ad0">LoopVectorizeOptions</a>, <a href="#a2c26328cd96546a50d896e9bfa6953d7">LoopVectorizeOptions</a> and <a href="#a5393e0c3e4331c12efc4ec4f91096cd5">setInterleaveOnlyWhenForced</a>.</p>

</div>
</div>

### VectorizeOnlyWhenForced {#ac73f29a1b055929ead9221ab91e1dd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::LoopVectorizeOptions::VectorizeOnlyWhenForced</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If false, consider all loops for vectorization.</p>


<p>If true, only loops that explicitly request vectorization are considered.</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a>.</p>


<p>Referenced by <a href="#a6783f8be2f000616bf0c2c34cae65ad0">LoopVectorizeOptions</a>, <a href="#a2c26328cd96546a50d896e9bfa6953d7">LoopVectorizeOptions</a> and <a href="#a3e069859198ff7a4972b1c2af8d4674e">setVectorizeOnlyWhenForced</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/vectorize/loopvectorize-h">LoopVectorize.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
