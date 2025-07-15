---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-codelayout-cpp-/mergednodest
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MergedNodesT` Struct Reference

<p>A wrapper around three concatenated vectors (chains) of nodes; it is used to avoid extra instantiation of the vectors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{CodeLayout.cpp}::MergedNodesT { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d2c3cd8495ebf14693cbf159e16e7a0">MergedNodesT</a> (NodeIter Begin1, NodeIter End1, NodeIter Begin2=EmptyList.begin(), NodeIter End2=EmptyList.end(), NodeIter Begin3=EmptyList.begin(), NodeIter End3=EmptyList.end())</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename F&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0700cd8ca492e6d6b189920d4f8200d9">forEach</a> (const F &amp;Func) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a697f0c99b6a0c9b2657611adacf3a8c7">getNodes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/anonymous-codelayout-cpp-/nodet">NodeT</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a746b822c18d71b154bc3c2b4e105df09">getFirstNode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3523bac4cf776c7e6b75a57c23644a18">Begin1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e44bb26dbc4cf8750061874f5e37be3">End1</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6b8749318d0446854c10e2820113c98">Begin2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760e9197c4b48f374144c96a74b98688">End2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e2abdd0c5e2a0da067b8a9c4a3e83b">Begin3</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64085373f1ea1bd9e1e34ea530961d3a">End3</a></td>
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

<p>A wrapper around three concatenated vectors (chains) of nodes; it is used to avoid extra instantiation of the vectors.</p>

<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MergedNodesT() {#a8d2c3cd8495ebf14693cbf159e16e7a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{CodeLayout.cpp}::MergedNodesT::MergedNodesT (<a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a> Begin1, <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a> End1, <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a> Begin2=EmptyList.begin(), <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a> End2=EmptyList.end(), <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a> Begin3=EmptyList.begin(), <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#ada0856182ddb592b34f37da3f4dc1eb5">NodeIter</a> End3=EmptyList.end())</td>
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



<p>Definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#adba7008c22659d027ed7e2987a9e4be2">anonymous{CodeLayout.cpp}::EmptyList</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-codelayout-cpp-/#a800ced24f890a965660badbbd70800d2">anonymous{CodeLayout.cpp}::mergeNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### forEach() {#a0700cd8ca492e6d6b189920d4f8200d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename F&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeLayout.cpp}::MergedNodesT::forEach (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> &amp; Func)</td>
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



<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>.</p>

</div>
</div>

### getFirstNode() {#a746b822c18d71b154bc3c2b4e105df09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NodeT * anonymous{CodeLayout.cpp}::MergedNodesT::getFirstNode ()</td>
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



<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### getNodes() {#a697f0c99b6a0c9b2657611adacf3a8c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; NodeT * &gt; anonymous{CodeLayout.cpp}::MergedNodesT::getNodes ()</td>
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



<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Begin1 {#a3523bac4cf776c7e6b75a57c23644a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIter anonymous{CodeLayout.cpp}::MergedNodesT::Begin1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### Begin2 {#ae6b8749318d0446854c10e2820113c98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIter anonymous{CodeLayout.cpp}::MergedNodesT::Begin2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### Begin3 {#a23e2abdd0c5e2a0da067b8a9c4a3e83b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIter anonymous{CodeLayout.cpp}::MergedNodesT::Begin3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 532 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### End1 {#a7e44bb26dbc4cf8750061874f5e37be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIter anonymous{CodeLayout.cpp}::MergedNodesT::End1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 529 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### End2 {#a760e9197c4b48f374144c96a74b98688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIter anonymous{CodeLayout.cpp}::MergedNodesT::End2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

### End3 {#a64085373f1ea1bd9e1e34ea530961d3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeIter anonymous{CodeLayout.cpp}::MergedNodesT::End3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/codelayout-cpp">CodeLayout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
