---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bitfields-details/compressor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `Compressor` Struct Template

<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor">Compressor</a></span> is used to manipulate the bits of a (possibly signed) integer type so it can be packed and unpacked into a <span class="doxyComputerOutput">bits</span> sized integer, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor">Compressor</a></span> is specialized on signed-ness so no runtime cost is incurred. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, unsigned Bits, bool = std::is_unsigned&lt;T&gt;::value&gt;
struct llvm::bitfields_details::Compressor&lt;T, Bits, bool&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">llvm/ADT/Bitfields.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits, bool = std::is_unsigned&lt;T&gt;::value&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa250caaebf754b022cdc9cc3473b3651">BP</a> = <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/bitpatterns">BitPatterns</a>&lt; T, Bits &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits, bool = std::is_unsigned&lt;T&gt;::value&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aca2cd0ceae369c29fdeba4e78783b6f3">pack</a> (T UserValue, T UserMaxValue)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits, bool = std::is_unsigned&lt;T&gt;::value&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static T</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae31ff7880e8cf9d72bd53746d971bf06">unpack</a> (T StorageValue)</td>
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

<p><span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor">Compressor</a></span> is used to manipulate the bits of a (possibly signed) integer type so it can be packed and unpacked into a <span class="doxyComputerOutput">bits</span> sized integer, <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor">Compressor</a></span> is specialized on signed-ness so no runtime cost is incurred.</p>


<p>The <span class="doxyComputerOutput">pack</span> method also checks that the passed in <span class="doxyComputerOutput">UserValue</span> is valid.</p>


<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### BP {#aa250caaebf754b022cdc9cc3473b3651}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits, bool = std::is_unsigned&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bitfields_details::Compressor&lt; T, Bits, bool &gt;::BP =  BitPatterns&lt;T, Bits&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### pack() {#aca2cd0ceae369c29fdeba4e78783b6f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits, bool = std::is_unsigned&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::bitfields_details::Compressor&lt; T, Bits, bool &gt;::pack (T UserValue, T UserMaxValue)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

### unpack() {#ae31ff7880e8cf9d72bd53746d971bf06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits, bool = std::is_unsigned&lt;T&gt;::value&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">T llvm::bitfields_details::Compressor&lt; T, Bits, bool &gt;::unpack (T StorageValue)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
