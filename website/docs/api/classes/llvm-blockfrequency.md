---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/blockfrequency
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BlockFrequency` Class



## Declaration

<div class="doxyDeclaration">
class llvm::BlockFrequency { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">llvm/Support/BlockFrequency.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47363ce48aa19a8c8777a9c31b53455c">BlockFrequency</a> (uint64_t Freq)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3d21db88053efddb1fab40325f88fe3">operator*=</a> (BranchProbability Prob)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiplies with a branch probability. <a href="#af3d21db88053efddb1fab40325f88fe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab81f3ce1ca68468d20391910b841a78b">operator*</a> (BranchProbability Prob) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af724ffc512f3dc4374e71297186cf191">operator/=</a> (BranchProbability Prob)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Divide by a non-zero branch probability using saturating arithmetic. <a href="#af724ffc512f3dc4374e71297186cf191">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35b52f21370e519580f95513178e682c">operator/</a> (BranchProbability Prob) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa55796fd8534453c4c51b41dc3a7a141">operator+=</a> (BlockFrequency Freq)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds another block frequency using saturating arithmetic. <a href="#aa55796fd8534453c4c51b41dc3a7a141">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d7120f536d08b969face2fe5c2903ec">operator+</a> (BlockFrequency Freq) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601aeacb8db7c0f532cf4f1257d5a9f6">operator-=</a> (BlockFrequency Freq)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Subtracts another block frequency using saturating arithmetic. <a href="#a601aeacb8db7c0f532cf4f1257d5a9f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af50b7f1e179829de7498cd63e935df17">operator-</a> (BlockFrequency Freq) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf0b10bfee4d6b4dd8d8a34920149bfa">operator&gt;&gt;=</a> (const unsigned count)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Shift block frequency to the right by count digits saturating to 1. <a href="#acf0b10bfee4d6b4dd8d8a34920149bfa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90111bb1a750b506cf8df8e1c362cc01">operator&lt;</a> (BlockFrequency RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a47c3a4e4ec42188cb74e9e16556bd">operator&lt;=</a> (BlockFrequency RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1687c1d23eee4a938707609e813e6f8">operator&gt;</a> (BlockFrequency RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3edade2ca18b2814b137650d8ca16aef">operator&gt;=</a> (BlockFrequency RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c7e5115a09bf6bea2dad337f6d3b79">operator==</a> (BlockFrequency RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07bfbb3f9fa8bb2995538f88190628a6">operator!=</a> (BlockFrequency RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e9ed6b20c2503f66f1fd0725297aedc">getFrequency</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the frequency as a fixpoint number scaled by the entry frequency. <a href="#a8e9ed6b20c2503f66f1fd0725297aedc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a822c8d45c2ef32b52c93ea433f7c4659">mul</a> (uint64_t Factor) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiplies frequency with <span class="doxyComputerOutput">Factor</span>. Returns <span class="doxyComputerOutput">nullopt</span> in case of overflow. <a href="#a822c8d45c2ef32b52c93ea433f7c4659">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a439f9adf5c1d87310f3732ffaeff4445">Frequency</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd2a8de4fde83093df0cc2415db2312">max</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the maximum possible frequency, the saturation value. <a href="#a5bd2a8de4fde83093df0cc2415db2312">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BlockFrequency() {#ae7f6692748a6f136c949352de096a4cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BlockFrequency::BlockFrequency ()</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>Referenced by <a href="#a5bd2a8de4fde83093df0cc2415db2312">max</a>, <a href="#a822c8d45c2ef32b52c93ea433f7c4659">mul</a>, <a href="#a07bfbb3f9fa8bb2995538f88190628a6">operator!=</a>, <a href="#ab81f3ce1ca68468d20391910b841a78b">operator*</a>, <a href="#af3d21db88053efddb1fab40325f88fe3">operator*=</a>, <a href="#a1d7120f536d08b969face2fe5c2903ec">operator+</a>, <a href="#aa55796fd8534453c4c51b41dc3a7a141">operator+=</a>, <a href="#af50b7f1e179829de7498cd63e935df17">operator-</a>, <a href="#a601aeacb8db7c0f532cf4f1257d5a9f6">operator-=</a>, <a href="#a35b52f21370e519580f95513178e682c">operator/</a>, <a href="#af724ffc512f3dc4374e71297186cf191">operator/=</a>, <a href="#a90111bb1a750b506cf8df8e1c362cc01">operator&lt;</a>, <a href="#ac2a47c3a4e4ec42188cb74e9e16556bd">operator&lt;=</a>, <a href="#aa3c7e5115a09bf6bea2dad337f6d3b79">operator==</a>, <a href="#ac1687c1d23eee4a938707609e813e6f8">operator&gt;</a>, <a href="#a3edade2ca18b2814b137650d8ca16aef">operator&gt;=</a> and <a href="#acf0b10bfee4d6b4dd8d8a34920149bfa">operator&gt;&gt;=</a>.</p>

</div>
</div>

### BlockFrequency() {#a47363ce48aa19a8c8777a9c31b53455c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BlockFrequency::BlockFrequency (uint64_t Freq)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-() {#af50b7f1e179829de7498cd63e935df17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::BlockFrequency::operator- (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>Reference <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a>.</p>

</div>
</div>

### operator-=() {#a601aeacb8db7c0f532cf4f1257d5a9f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency &amp; llvm::BlockFrequency::operator-= (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq)</td>
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

<p>Subtracts another block frequency using saturating arithmetic.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>Reference <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a>.</p>

</div>
</div>

### operator!=() {#a07bfbb3f9fa8bb2995538f88190628a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequency::operator!= (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> RHS)</td>
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



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator\*() {#ab81f3ce1ca68468d20391910b841a78b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency BlockFrequency::operator* (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/support/blockfrequency-cpp">BlockFrequency.cpp</a>.</p>


<p>Reference <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a>.</p>

</div>
</div>

### operator\*=() {#af3d21db88053efddb1fab40325f88fe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency &amp; BlockFrequency::operator*= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiplies with a branch probability.</p>


<p>The computation will never overflow.</p>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>, definition at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/support/blockfrequency-cpp">BlockFrequency.cpp</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a9ccfc22b308af94572ad6843ecc21055">llvm::BranchProbability::scale</a>.</p>

</div>
</div>

### operator/() {#a35b52f21370e519580f95513178e682c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency BlockFrequency::operator/ (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/support/blockfrequency-cpp">BlockFrequency.cpp</a>.</p>


<p>Reference <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a>.</p>

</div>
</div>

### operator/=() {#af724ffc512f3dc4374e71297186cf191}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency &amp; BlockFrequency::operator/= (<a href="/web-llvm/docs/api/classes/llvm/branchprobability">BranchProbability</a> Prob)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Divide by a non-zero branch probability using saturating arithmetic.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/support/blockfrequency-cpp">BlockFrequency.cpp</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/classes/llvm/branchprobability/#a654bfa34e440912fecad8a6bd989d992">llvm::BranchProbability::scaleByInverse</a>.</p>

</div>
</div>

### operator+() {#a1d7120f536d08b969face2fe5c2903ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::BlockFrequency::operator+ (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>Reference <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a>.</p>

</div>
</div>

### operator+=() {#aa55796fd8534453c4c51b41dc3a7a141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency &amp; llvm::BlockFrequency::operator+= (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> Freq)</td>
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

<p>Adds another block frequency using saturating arithmetic.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/passes/standardinstrumentations-cpp/#a6f1bbcae7288f05872dcfe811d0388baa9060587edeb01a63e3d3edc959678d1e">Before</a>, <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>

</div>
</div>

### operator&lt;() {#a90111bb1a750b506cf8df8e1c362cc01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequency::operator&lt; (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> RHS)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;=() {#ac2a47c3a4e4ec42188cb74e9e16556bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequency::operator&lt;= (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> RHS)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#aa3c7e5115a09bf6bea2dad337f6d3b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequency::operator== (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> RHS)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;() {#ac1687c1d23eee4a938707609e813e6f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequency::operator&gt; (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> RHS)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;=() {#a3edade2ca18b2814b137650d8ca16aef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BlockFrequency::operator&gt;= (<a href="/web-llvm/docs/api/classes/llvm/blockfrequency">BlockFrequency</a> RHS)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&gt;&gt;=() {#acf0b10bfee4d6b4dd8d8a34920149bfa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency &amp; llvm::BlockFrequency::operator&gt;&gt;= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned count)</td>
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

<p>Shift block frequency to the right by count digits saturating to 1.</p>

<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFrequency() {#a8e9ed6b20c2503f66f1fd0725297aedc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BlockFrequency::getFrequency ()</td>
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

<p>Returns the frequency as a fixpoint number scaled by the entry frequency.</p>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonloopalign-cpp-/hexagonloopalign/#a49530a2f7101146544b49c809bc2e035">anonymous{HexagonLoopAlign.cpp}::HexagonLoopAlign::attemptToBalignSmallLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#a5f32c10b46f4e956f21552b0984ae68f">llvm::AsmPrinter::emitBBAddrMapSection</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/instrinsertpoint/#acfe02f412f4221fbb6a31ca758ac297e">llvm::RegBankSelect::InstrInsertPoint::frequency</a>, <a href="/web-llvm/docs/api/classes/llvm/regbankselect/mbbinsertpoint/#a93a33c37cd1f7261b08ca7a90062c3fd">llvm::RegBankSelect::MBBInsertPoint::frequency</a>, <a href="/web-llvm/docs/api/classes/llvm/machineblockfrequencyinfo/#a9be2cffeaf9bda65c4c49eeebaa5458f">llvm::MachineBlockFrequencyInfo::getBlockFreqRelativeToEntryBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#ac2c46c98ef08efa11fd207209dabba62">llvm::BlockFrequencyInfoImplBase::getProfileCountFromFreq</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4d074876aec87f462a07b2999827758">llvm::printRelativeBlockFreq</a>, <a href="/web-llvm/docs/api/classes/anonymous-machineblockplacement-cpp-/machineblockplacementstats/#a8305613a915321631b70e8f26e2d55d6">anonymous{MachineBlockPlacement.cpp}::MachineBlockPlacementStats::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfoimplbase/#a88624bc3c370c84a05d0f891b8b0793e">llvm::BlockFrequencyInfoImplBase::setBlockFreq</a> and <a href="/web-llvm/docs/api/classes/llvm/blockfrequencyinfo/#a79d23612ec0c59f4c30ccfabfc2b312c">llvm::BlockFrequencyInfo::setBlockFreqAndScale</a>.</p>

</div>
</div>

### mul() {#a822c8d45c2ef32b52c93ea433f7c4659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; BlockFrequency &gt; BlockFrequency::mul (uint64_t Factor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiplies frequency with <span class="doxyComputerOutput">Factor</span>. Returns <span class="doxyComputerOutput">nullopt</span> in case of overflow.</p>

<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>, definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/support/blockfrequency-cpp">BlockFrequency.cpp</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa6c35ac16c3c23e443f27a025d7a1597">llvm::SaturatingMultiply</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Frequency {#a439f9adf5c1d87310f3732ffaeff4445}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::BlockFrequency::Frequency</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### max() {#a5bd2a8de4fde83093df0cc2415db2312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockFrequency llvm::BlockFrequency::max ()</td>
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

<p>Returns the maximum possible frequency, the saturation value.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a>.</p>


<p>References <a href="#ae7f6692748a6f136c949352de096a4cd">BlockFrequency</a> and <a href="/web-llvm/docs/api/files/include/include/llvm-c/datatypes-h/#a30654b4b67d97c42ca3f9b6052dda916">UINT64_MAX</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/spillplacement/node/#a03bf04c760f4e0dc8f8673a6dbbc1f37">llvm::SpillPlacement::Node::addBias</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/blockfrequency-h">BlockFrequency.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/blockfrequency-cpp">BlockFrequency.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
