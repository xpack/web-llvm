---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bitfields-details/impl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Impl` Struct Template Reference

<p><a href="/web-llvm/docs/api/structs/llvm/bitfields-details/impl">Impl</a> is where Bifield description and Storage are put together to interact with values. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename Bitfield, typename StorageType&gt;
struct llvm::bitfields_details::Impl&lt;Bitfield, StorageType&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">llvm/ADT/Bitfields.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade04c491df24f9f2cd9428791ec8fa02">IntegerType</a> = typename Bitfield::IntegerType</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a523737220bd74cbfd78269dd6799f248">C</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor">Compressor</a>&lt; <a href="#ade04c491df24f9f2cd9428791ec8fa02">IntegerType</a>, Bitfield::Bits &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a236c4ed813b37d6d7935c15fb4198918">BP</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/bitpatterns">BitPatterns</a>&lt; StorageType, Bitfield::Bits &gt;</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70396106a4515186e3aefe39af98cc9e">update</a> (StorageType &amp;Packed, IntegerType UserValue)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks <span class="doxyComputerOutput">UserValue</span> is within bounds and packs it between <span class="doxyComputerOutput">FirstBit</span> and <span class="doxyComputerOutput">LastBit</span> of <span class="doxyComputerOutput">Packed</span> leaving the rest unchanged. <a href="#a70396106a4515186e3aefe39af98cc9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static <a href="#ade04c491df24f9f2cd9428791ec8fa02">IntegerType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1ebd6dc7953c014f87a95163874d0291">extract</a> (StorageType Packed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interprets bits between <span class="doxyComputerOutput">FirstBit</span> and <span class="doxyComputerOutput">LastBit</span> of <span class="doxyComputerOutput">Packed</span> as an<span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></span>. <a href="#a1ebd6dc7953c014f87a95163874d0291">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static StorageType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9035aebdbd8127174cc3dca7514a09bd">test</a> (StorageType Packed)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Interprets bits between <span class="doxyComputerOutput">FirstBit</span> and <span class="doxyComputerOutput">LastBit</span> of <span class="doxyComputerOutput">Packed</span> as an<span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></span>. <a href="#a9035aebdbd8127174cc3dca7514a09bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a09ef2fa7a205bb1b5fe40f433f9fbd4d">StorageBits</a> = sizeof(StorageType) * CHAR_BIT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename Bitfield, typename StorageType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr StorageType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad4ab1ed7f6d3975d42cd0a9f7ddcf219">Mask</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/bitpatterns/#ad201bab28e409edb73a495dc1223f692">BP::Umax</a> &lt;&lt; Bitfield::Shift</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/bitfields-details/impl">Impl</a> is where Bifield description and Storage are put together to interact with values.</p>

<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BP {#a236c4ed813b37d6d7935c15fb4198918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::BP =  BitPatterns&lt;StorageType, Bitfield::Bits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

### C {#a523737220bd74cbfd78269dd6799f248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::C =  Compressor&lt;IntegerType, Bitfield::Bits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

### IntegerType {#ade04c491df24f9f2cd9428791ec8fa02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::IntegerType =  typename Bitfield::IntegerType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### extract() {#a1ebd6dc7953c014f87a95163874d0291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::extract (StorageType Packed)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interprets bits between <span class="doxyComputerOutput">FirstBit</span> and <span class="doxyComputerOutput">LastBit</span> of <span class="doxyComputerOutput">Packed</span> as an<span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></span>.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>References <a href="#ad4ab1ed7f6d3975d42cd0a9f7ddcf219">llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::Mask</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor/#ae31ff7880e8cf9d72bd53746d971bf06">llvm::bitfields_details::Compressor&lt; IntegerType, Bitfield::Bits &gt;::unpack</a>.</p>

</div>
</div>

### test() {#a9035aebdbd8127174cc3dca7514a09bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StorageType llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::test (StorageType Packed)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Interprets bits between <span class="doxyComputerOutput">FirstBit</span> and <span class="doxyComputerOutput">LastBit</span> of <span class="doxyComputerOutput">Packed</span> as an<span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a></span>.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Reference <a href="#ad4ab1ed7f6d3975d42cd0a9f7ddcf219">llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::Mask</a>.</p>

</div>
</div>

### update() {#a70396106a4515186e3aefe39af98cc9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::update (StorageType &amp; Packed, <a href="#ade04c491df24f9f2cd9428791ec8fa02">IntegerType</a> UserValue)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks <span class="doxyComputerOutput">UserValue</span> is within bounds and packs it between <span class="doxyComputerOutput">FirstBit</span> and <span class="doxyComputerOutput">LastBit</span> of <span class="doxyComputerOutput">Packed</span> leaving the rest unchanged.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>References <a href="#ad4ab1ed7f6d3975d42cd0a9f7ddcf219">llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::Mask</a> and <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor/#aca2cd0ceae369c29fdeba4e78783b6f3">llvm::bitfields_details::Compressor&lt; IntegerType, Bitfield::Bits &gt;::pack</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Mask {#ad4ab1ed7f6d3975d42cd0a9f7ddcf219}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StorageType llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::Mask = <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/bitpatterns/#ad201bab28e409edb73a495dc1223f692">BP::Umax</a> &lt;&lt; Bitfield::Shift</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="#a1ebd6dc7953c014f87a95163874d0291">llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::extract</a>, <a href="#a9035aebdbd8127174cc3dca7514a09bd">llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::test</a> and <a href="#a70396106a4515186e3aefe39af98cc9e">llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::update</a>.</p>

</div>
</div>

### StorageBits {#a09ef2fa7a205bb1b5fe40f433f9fbd4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename Bitfield, typename StorageType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::bitfields_details::Impl&lt; Bitfield, StorageType &gt;::StorageBits = sizeof(StorageType) * CHAR_BIT</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
