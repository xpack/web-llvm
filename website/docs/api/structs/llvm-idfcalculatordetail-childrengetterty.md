---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/idfcalculatordetail/childrengetterty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ChildrenGetterTy` Struct Template Reference

<p>Generic utility class used for getting the children of a basic block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class NodeTy, bool IsPostDom&gt;
struct llvm::IDFCalculatorDetail::ChildrenGetterTy&lt;NodeTy, IsPostDom&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">llvm/Support/GenericIteratedDominanceFrontier.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3113fc68c6730a4814882980981a7e75">NodeRef</a> = typename <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; NodeTy * &gt;::NodeRef</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a23849eec5be1b92d976433bb29f8c908">ChildIteratorType</a> = typename <a href="/web-llvm/docs/api/structs/llvm/graphtraits">GraphTraits</a>&lt; NodeTy * &gt;::ChildIteratorType</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a149e26492071b21a56a21d80d868b2e5">range</a> = <a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a23849eec5be1b92d976433bb29f8c908">ChildIteratorType</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class NodeTy, bool IsPostDom&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a149e26492071b21a56a21d80d868b2e5">range</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f1b15474259d49fb4668ce85d797ab8">get</a> (const NodeRef &amp;N)</td>
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

<p>Generic utility class used for getting the children of a basic block.</p>


<p>May be specialized if, for example, one wouldn't like to return nullpointer successors.</p>


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### ChildIteratorType {#a23849eec5be1b92d976433bb29f8c908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IDFCalculatorDetail::ChildrenGetterTy&lt; NodeTy, IsPostDom &gt;::ChildIteratorType =  typename GraphTraits&lt;NodeTy *&gt;::ChildIteratorType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### NodeRef {#a3113fc68c6730a4814882980981a7e75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IDFCalculatorDetail::ChildrenGetterTy&lt; NodeTy, IsPostDom &gt;::NodeRef =  typename GraphTraits&lt;NodeTy *&gt;::NodeRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

### range {#a149e26492071b21a56a21d80d868b2e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::IDFCalculatorDetail::ChildrenGetterTy&lt; NodeTy, IsPostDom &gt;::range =  iterator_range&lt;ChildIteratorType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#a5f1b15474259d49fb4668ce85d797ab8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class NodeTy, bool IsPostDom&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChildrenGetterTy&lt; NodeTy, IsPostDom &gt;::range llvm::IDFCalculatorDetail::ChildrenGetterTy&lt; NodeTy, IsPostDom &gt;::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a3113fc68c6730a4814882980981a7e75">NodeRef</a> &amp; N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acc2e6a2001a5f102f18060a53520e82b">llvm::children</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/genericiterateddominancefrontier-h">GenericIteratedDominanceFrontier.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
