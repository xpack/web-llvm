---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/hashbuilderbase
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `HashBuilderBase` Class Template

<p>Declares the hasher member, and functions forwarding directly to the hasher. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename HasherT&gt;
class llvm::HashBuilderBase&lt;HasherT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">llvm/Support/HashBuilder.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder&lt;HasherT, Endianness&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to help hash various types through a hasher type. <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hashbuilder">HashBuilder&lt;HasherT, Endianness&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interface to help hash various types through a hasher type. <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT_ = HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#add737579036caa6a21beb68d14df904e">HashResultTy</a> = decltype(std::declval&lt; HasherT_ &amp; &gt;().<a href="#a6e5cbc4cd359a97743ffbfa4abc13d73">final</a>())</td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abc0798b909ab86d9724d67362a53946e">HashBuilderBase</a> (HasherT &amp;Hasher)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgTypes&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ad5183c886f14f268b267e1cc5a5f4ba9">HashBuilderBase</a> (ArgTypes &amp;&amp;...Args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">HasherT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7295afb2f132e1ad53f38a61fb2aff3">getHasher</a> ()</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae3ff56a4d35e4dd4630e8abdb80d1bb9">update</a> (ArrayRef&lt; uint8_t &gt; Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forward to <span class="doxyComputerOutput">HasherT::update(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;)</span>. <a href="#ae3ff56a4d35e4dd4630e8abdb80d1bb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a87b3f72e3be3c8f17f2f42ade0341b0a">update</a> (StringRef Data)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forward to <span class="doxyComputerOutput">HasherT::update(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;)</span>. <a href="#a87b3f72e3be3c8f17f2f42ade0341b0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT_ = HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6e5cbc4cd359a97743ffbfa4abc13d73">final</a> () -&gt; <a href="#add737579036caa6a21beb68d14df904e">HashResultTy</a>&lt; HasherT_ &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forward to <span class="doxyComputerOutput">HasherT::final()</span> if available. <a href="#a6e5cbc4cd359a97743ffbfa4abc13d73">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT_ = HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad2f567a2782a06b3116aed7e92047fd">result</a> () -&gt; <a href="#add737579036caa6a21beb68d14df904e">HashResultTy</a>&lt; HasherT_ &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Forward to <span class="doxyComputerOutput">HasherT::result()</span> if available. <a href="#aad2f567a2782a06b3116aed7e92047fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">std::optional&lt; HasherT &gt;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa01e782b1ba341a33a706266a90864f1">OptionalHasher</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename HasherT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">HasherT &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7db8207fcdb94b3fc8e91bc87abf1e05">Hasher</a></td>
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

<p>Declares the hasher member, and functions forwarding directly to the hasher.</p>

<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### HashResultTy {#add737579036caa6a21beb68d14df904e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT_ = HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::HashBuilderBase&lt; HasherT &gt;::HashResultTy =  decltype(std::declval&lt;HasherT_ &amp;&gt;().final())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### HashBuilderBase() {#abc0798b909ab86d9724d67362a53946e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HashBuilderBase&lt; HasherT &gt;::HashBuilderBase (HasherT &amp; Hasher)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#af8733fcc0780d8e7f05a7428721159ec">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::HashBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#a3790ea10d4f6d2364d6b1fb2bddfbf4e">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::HashBuilder</a>.</p>

</div>
</div>

### HashBuilderBase() {#ad5183c886f14f268b267e1cc5a5f4ba9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgTypes&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::HashBuilderBase&lt; HasherT &gt;::HashBuilderBase (ArgTypes &amp;&amp;... Args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### final() {#a6e5cbc4cd359a97743ffbfa4abc13d73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT_ = HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashResultTy&lt; HasherT_ &gt; llvm::HashBuilderBase&lt; HasherT &gt;::final ()</td>
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

<p>Forward to <span class="doxyComputerOutput">HasherT::final()</span> if available.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Reference <a href="#af7295afb2f132e1ad53f38a61fb2aff3">llvm::HashBuilderBase&lt; HasherT &gt;::getHasher</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a22834e90a038045330c1385f188104f5">computeFullStackId</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/memprofiler-cpp/#a59956a56d1a2c15842922d6c2ba8de18">computeStackId</a>.</p>

</div>
</div>

### getHasher() {#af7295afb2f132e1ad53f38a61fb2aff3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HasherT &amp; llvm::HashBuilderBase&lt; HasherT &gt;::getHasher ()</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Referenced by <a href="#a6e5cbc4cd359a97743ffbfa4abc13d73">llvm::HashBuilderBase&lt; HasherT &gt;::final</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a4b5ed3aee26b7c67700b5e0fbc4d2f">llvm::hash_value</a>, <a href="#aad2f567a2782a06b3116aed7e92047fd">llvm::HashBuilderBase&lt; HasherT &gt;::result</a> and <a href="#ae3ff56a4d35e4dd4630e8abdb80d1bb9">llvm::HashBuilderBase&lt; HasherT &gt;::update</a>.</p>

</div>
</div>

### result() {#aad2f567a2782a06b3116aed7e92047fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT_ = HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HashResultTy&lt; HasherT_ &gt; llvm::HashBuilderBase&lt; HasherT &gt;::result ()</td>
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

<p>Forward to <span class="doxyComputerOutput">HasherT::result()</span> if available.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>Reference <a href="#af7295afb2f132e1ad53f38a61fb2aff3">llvm::HashBuilderBase&lt; HasherT &gt;::getHasher</a>.</p>

</div>
</div>

### update() {#ae3ff56a4d35e4dd4630e8abdb80d1bb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HashBuilderBase&lt; HasherT &gt;::update (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; Data)</td>
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

<p>Forward to <span class="doxyComputerOutput">HasherT::update(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;)</span>.</p>


<p>This may not take the size of <span class="doxyComputerOutput">Data</span> into account. Users of this function should pay attention to respect endianness contraints.</p>


<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#af7295afb2f132e1ad53f38a61fb2aff3">llvm::HashBuilderBase&lt; HasherT &gt;::getHasher</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#a8e8f681c61a2745facd1cb55855fe402">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>, <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#a1815b02e7fafbe2f603c7893bd131666">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::add</a>, <a href="/web-llvm/docs/api/classes/llvm/hashbuilder/#a2f0e0694a40550ad8156ff89999df152">llvm::HashBuilder&lt; hashbuilder_detail::HashCodeHasher, llvm::endianness::native &gt;::adjustForEndiannessAndAdd</a> and <a href="#a87b3f72e3be3c8f17f2f42ade0341b0a">llvm::HashBuilderBase&lt; HasherT &gt;::update</a>.</p>

</div>
</div>

### update() {#a87b3f72e3be3c8f17f2f42ade0341b0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::HashBuilderBase&lt; HasherT &gt;::update (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data)</td>
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

<p>Forward to <span class="doxyComputerOutput">HasherT::update(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt;uint8_t&gt;)</span>.</p>


<p>This may not take the size of <span class="doxyComputerOutput">Data</span> into account. Users of this function should pay attention to respect endianness contraints.</p>


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="#ae3ff56a4d35e4dd4630e8abdb80d1bb9">llvm::HashBuilderBase&lt; HasherT &gt;::update</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Hasher {#a7db8207fcdb94b3fc8e91bc87abf1e05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HasherT&amp; llvm::HashBuilderBase&lt; HasherT &gt;::Hasher</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

### OptionalHasher {#aa01e782b1ba341a33a706266a90864f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename HasherT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;HasherT&gt; llvm::HashBuilderBase&lt; HasherT &gt;::OptionalHasher</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/hashbuilder-h">HashBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
