---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysis-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ProvenanceAnalysis.h` File Reference

<p>This file declares a special form of Alias Analysis called <span class="doxyComputerOutput">Provenance / Analysis''. </span> <a href="#details">More...</a></p>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/densemap-h">llvm/ADT/DenseMap.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/passmanager-h">llvm/IR/PassManager.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/valuehandle-h">llvm/IR/ValueHandle.h</a>"
#include &lt;utility&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/provenanceanalysis">ProvenanceAnalysis</a></td>
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

<p>This file declares a special form of Alias Analysis called <span class="doxyComputerOutput">Provenance / Analysis''. </span></p>


<p>The word provenance'' refers to the history of the ownership / of an object. Thus `‘Provenance Analysis`' is an analysis which attempts to / use various techniques to determine if locally / / WARNING: This file knows about certain library functions. It recognizes them / by name, and hardwires knowledge of their semantics. / / WARNING: This file knows about how certain Objective-C library functions are / used. Naive LLVM IR transformations which would otherwise be / behavior-preserving may break these assumptions.</p>


<p>===-------------------------------------------------------------------—===//</p>


<p>namespace llvm {</p>


<p>class AAResults; class PHINode; class SelectInst; class Value;</p>


<p>namespace objcarc {</p>


<p>/ This is similar to BasicAliasAnalysis, and it uses many of the same / techniques, except it uses special ObjC-specific reasoning about pointer / relationships. / / In this context <span class="doxyComputerOutput">Provenance'' is defined as the history of an object's / ownership. Thus </span>Provenance Analysis'' is defined by using the notion of / an `‘independent provenance source`' of a pointer to determine whether or not two pointers have the same provenance source and thus could potentially be related.</p>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
