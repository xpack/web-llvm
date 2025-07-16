---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/bitfields-details/bitpatterns
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BitPatterns` Struct Template Reference

<p>A struct defining useful bit patterns for n-bits integer types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename T, unsigned Bits&gt;
struct llvm::bitfields_details::BitPatterns&lt;T, Bits&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">llvm/ADT/Bitfields.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a> = std::make_unsigned_t&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Bit patterns are forged using the equivalent <span class="doxyComputerOutput"><a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></span> type because of undefined operations over signed types (e.g. <a href="#a256d10f001d8a689a25cf658d47e73e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr unsigned</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a900dad517a613bb0a1da85fb8dd55f6d">TypeBits</a> = sizeof(<a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>) * CHAR_BIT</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af422860447e221241107decfbe91bc0f">AllZeros</a> = <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>e.g. with TypeBits == 8 and Bits == 6. <a href="#af422860447e221241107decfbe91bc0f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a3f3d4d91b7987dc71350acfa84e32b15">AllOnes</a> = ~<a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(0)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b1beef3861a9c4b13c1fe0fc0e5e6ce">Umin</a> = <a href="#af422860447e221241107decfbe91bc0f">AllZeros</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad201bab28e409edb73a495dc1223f692">Umax</a> = <a href="#a3f3d4d91b7987dc71350acfa84e32b15">AllOnes</a> &gt;&gt; (<a href="#a900dad517a613bb0a1da85fb8dd55f6d">TypeBits</a> - Bits)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac03fb7d13195746239d8386193354569">SignBitMask</a> = <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(1) &lt;&lt; (Bits - 1)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a52f22fcfeb772edcd9194328b7709336">Smax</a> = <a href="#ad201bab28e409edb73a495dc1223f692">Umax</a> &gt;&gt; 1U</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a825cb759b8b241d75306434b80b058af">Smin</a> = ~<a href="#a52f22fcfeb772edcd9194328b7709336">Smax</a></td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T, unsigned Bits&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7c04cd4b16aa18377685d6adbcf3043c">SignExtend</a> = <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(<a href="#a825cb759b8b241d75306434b80b058af">Smin</a> &lt;&lt; 1U)</td>
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

<p>A struct defining useful bit patterns for n-bits integer types.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Unsigned {#a256d10f001d8a689a25cf658d47e73e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::Unsigned =  std::make_unsigned_t&lt;T&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Bit patterns are forged using the equivalent <span class="doxyComputerOutput"><a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a></span> type because of undefined operations over signed types (e.g.</p>


<p>Bitwise shift operators). Moreover same size casting from unsigned to signed is well defined but not the other way around.</p>


<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### AllOnes {#a3f3d4d91b7987dc71350acfa84e32b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::AllOnes = ~<a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(0)</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

### AllZeros {#af422860447e221241107decfbe91bc0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::AllZeros = <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(0)</td>
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

<p>e.g. with TypeBits == 8 and Bits == 6.</p>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

### SignBitMask {#ac03fb7d13195746239d8386193354569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::SignBitMask = <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(1) &lt;&lt; (Bits - 1)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor-897e7bd5356f4fb8a328c055a16f2090/#af0644bc62ea0dec77a0e9beadca92920">llvm::bitfields_details::Compressor&lt; T, Bits, false &gt;::unpack</a>.</p>

</div>
</div>

### SignExtend {#a7c04cd4b16aa18377685d6adbcf3043c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::SignExtend = <a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>(<a href="#a825cb759b8b241d75306434b80b058af">Smin</a> &lt;&lt; 1U)</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor-897e7bd5356f4fb8a328c055a16f2090/#af0644bc62ea0dec77a0e9beadca92920">llvm::bitfields_details::Compressor&lt; T, Bits, false &gt;::unpack</a>.</p>

</div>
</div>

### Smax {#a52f22fcfeb772edcd9194328b7709336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::Smax = <a href="#ad201bab28e409edb73a495dc1223f692">Umax</a> &gt;&gt; 1U</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor-897e7bd5356f4fb8a328c055a16f2090/#a60cf06048833d8240840a03210e89baf">llvm::bitfields_details::Compressor&lt; T, Bits, false &gt;::pack</a>.</p>

</div>
</div>

### Smin {#a825cb759b8b241d75306434b80b058af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::Smin = ~<a href="#a52f22fcfeb772edcd9194328b7709336">Smax</a></td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor-897e7bd5356f4fb8a328c055a16f2090/#a60cf06048833d8240840a03210e89baf">llvm::bitfields_details::Compressor&lt; T, Bits, false &gt;::pack</a>.</p>

</div>
</div>

### TypeBits {#a900dad517a613bb0a1da85fb8dd55f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::TypeBits = sizeof(<a href="#a256d10f001d8a689a25cf658d47e73e3">Unsigned</a>) * CHAR_BIT</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

</div>
</div>

### Umax {#ad201bab28e409edb73a495dc1223f692}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::Umax = <a href="#a3f3d4d91b7987dc71350acfa84e32b15">AllOnes</a> &gt;&gt; (<a href="#a900dad517a613bb0a1da85fb8dd55f6d">TypeBits</a> - Bits)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/bitfields-details/compressor/#aca2cd0ceae369c29fdeba4e78783b6f3">llvm::bitfields_details::Compressor&lt; IntegerType, Bitfield::Bits &gt;::pack</a>.</p>

</div>
</div>

### Umin {#a8b1beef3861a9c4b13c1fe0fc0e5e6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T, unsigned Bits&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Unsigned llvm::bitfields_details::BitPatterns&lt; T, Bits &gt;::Umin = <a href="#af422860447e221241107decfbe91bc0f">AllZeros</a></td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/bitfields-h">Bitfields.h</a>.</p>

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
