---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/deltatree
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DeltaTree` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> - a multiway search tree (BTree) structure with some fancy features. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DeltaTree { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">llvm/ADT/DeltaTree.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93581c8e7d30de46117cc3e07a0af01d">DeltaTree</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71158ee3b58ca404fbbe5c7e96d30c4b">DeltaTree</a> (const DeltaTree &amp;RHS)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf2c383983f61525048221dc5218c8a0">~DeltaTree</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d79f8161fd4c4dbeb435534e56a2fc1">operator=</a> (const DeltaTree &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d2add1ca152069aa7cd796d3e7c552e">getDeltaAt</a> (unsigned FileIndex) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getDeltaAt - Return the accumulated delta at the specified file offset. <a href="#a9d2add1ca152069aa7cd796d3e7c552e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65b2200df7c029fc766e3486c6629ae5">AddDelta</a> (unsigned FileIndex, int Delta)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AddDelta - When a change is made that shifts around the text buffer, this method is used to record that info. <a href="#a65b2200df7c029fc766e3486c6629ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad401b622a1f23da5ca0404d5a7133c7d">Root</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> - a multiway search tree (BTree) structure with some fancy features.</p>


<p>B-Trees are generally more memory and cache efficient than binary trees, because they store multiple keys/values in each node. This implements a key/value mapping from index to delta, and allows fast lookup on index. However, an added (important) bonus is that it can also efficiently tell us the full accumulated delta for a specific file offset as well, without traversing the whole tree.</p>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DeltaTree() {#a93581c8e7d30de46117cc3e07a0af01d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaTree::DeltaTree ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Referenced by <a href="#a71158ee3b58ca404fbbe5c7e96d30c4b">DeltaTree</a> and <a href="#a5d79f8161fd4c4dbeb435534e56a2fc1">operator=</a>.</p>

</div>
</div>

### DeltaTree() {#a71158ee3b58ca404fbbe5c7e96d30c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaTree::DeltaTree (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>, definition at line 390 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a93581c8e7d30de46117cc3e07a0af01d">DeltaTree</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DeltaTree() {#abf2c383983f61525048221dc5218c8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaTree::~DeltaTree ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>, definition at line 397 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a5d79f8161fd4c4dbeb435534e56a2fc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DeltaTree &amp; llvm::DeltaTree::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>.</p>


<p>Reference <a href="#a93581c8e7d30de46117cc3e07a0af01d">DeltaTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AddDelta() {#a65b2200df7c029fc766e3486c6629ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DeltaTree::AddDelta (unsigned FileIndex, int Delta)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AddDelta - When a change is made that shifts around the text buffer, this method is used to record that info.</p>


<p>It inserts a delta of 'Delta' into the current <a href="/web-llvm/docs/api/classes/llvm/deltatree">DeltaTree</a> at offset FileIndex.</p>


<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a>.</p>

</div>
</div>

### getDeltaAt() {#a9d2add1ca152069aa7cd796d3e7c552e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DeltaTree::getDeltaAt (unsigned FileIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getDeltaAt - Return the accumulated delta at the specified file offset.</p>


<p>This includes all insertions or delections that occurred <em>before</em> the specified file index.</p>


<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp/#ab590661425ca60ca82edfdb4cf22233d">getRoot</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Root {#ad401b622a1f23da5ca0404d5a7133c7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void* llvm::DeltaTree::Root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/deltatree-h">DeltaTree.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/deltatree-cpp">DeltaTree.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
