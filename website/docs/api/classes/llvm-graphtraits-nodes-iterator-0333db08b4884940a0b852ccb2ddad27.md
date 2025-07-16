---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/graphtraits/nodes-iterator-0333db08b4884940a0b852ccb2ddad27
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `nodes_iterator` Class Template Reference

<p>For the node iterator we just need to turn the <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a7ceeff5a65c10abe289db52446ac088a">TreeEntry</a> iterator into a TreeEntry* iterator so that it dereferences to <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a55cdb660a488b62f949a57dc65f5296e">NodeRef</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GraphTraits::nodes_iterator&lt;BoUpSLP * &gt;::nodes_iterator { ... }
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806960b67d3d0cca6c663f8a80330c76">ItTy</a> = <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a9eae7ba1448d9866beca95a042de2e11">ContainerTy::iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4742270efd4962f67118785836da65">nodes_iterator</a> (const ItTy &amp;It2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a55cdb660a488b62f949a57dc65f5296e">NodeRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c96b270649e7b4bb961a85c9a03852c">operator*</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/graphtraits/nodes-iterator-0333db08b4884940a0b852ccb2ddad27">nodes_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110d907b8accd61d00d8a4b2354fc16e">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c02c6d639d41ef827da13f8acf10f4">operator!=</a> (const nodes_iterator &amp;N2) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ItTy</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7769cd0025c1115f27f7671f08a8e6f6">It</a></td>
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

<p>For the node iterator we just need to turn the <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a7ceeff5a65c10abe289db52446ac088a">TreeEntry</a> iterator into a TreeEntry* iterator so that it dereferences to <a href="/web-llvm/docs/api/structs/llvm/graphtraits-860e5f7a11c435b145d274344a0415db/#a55cdb660a488b62f949a57dc65f5296e">NodeRef</a>.</p>

<p>Definition at line 4467 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### ItTy {#a806960b67d3d0cca6c663f8a80330c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::GraphTraits&lt; BoUpSLP * &gt;::nodes_iterator::ItTy =  ContainerTy::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4468 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### nodes\_iterator() {#a4c4742270efd4962f67118785836da65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GraphTraits&lt; BoUpSLP * &gt;::nodes_iterator::nodes_iterator (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ItTy &amp; It2)</td>
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



<p>Definition at line 4472 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Referenced by <a href="#ae8c02c6d639d41ef827da13f8acf10f4">operator!=</a> and <a href="#a110d907b8accd61d00d8a4b2354fc16e">operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#ae8c02c6d639d41ef827da13f8acf10f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GraphTraits&lt; BoUpSLP * &gt;::nodes_iterator::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/graphtraits/nodes-iterator-0333db08b4884940a0b852ccb2ddad27">nodes_iterator</a> &amp; N2)</td>
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



<p>Definition at line 4478 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="#a4c4742270efd4962f67118785836da65">nodes_iterator</a>.</p>

</div>
</div>

### operator\*() {#a7c96b270649e7b4bb961a85c9a03852c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NodeRef llvm::GraphTraits&lt; BoUpSLP * &gt;::nodes_iterator::operator* ()</td>
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



<p>Definition at line 4473 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

### operator++() {#a110d907b8accd61d00d8a4b2354fc16e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">nodes_iterator llvm::GraphTraits&lt; BoUpSLP * &gt;::nodes_iterator::operator++ ()</td>
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



<p>Definition at line 4474 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>


<p>Reference <a href="#a4c4742270efd4962f67118785836da65">nodes_iterator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### It {#a7769cd0025c1115f27f7671f08a8e6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ItTy llvm::GraphTraits&lt; BoUpSLP * &gt;::nodes_iterator::It</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 4469 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp">SLPVectorizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
