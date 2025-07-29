---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `DWARFAcceleratorTable.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/dwarf/dwarfacceleratortable-h">llvm/DebugInfo/DWARF/DWARFAcceleratorTable.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/smallvector-h">llvm/ADT/SmallVector.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h">llvm/Support/Compiler.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/djb-h">llvm/Support/DJB.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errc-h">llvm/Support/Errc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatvariadic-h">llvm/Support/FormatVariadic.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/scopedprinter-h">llvm/Support/ScopedPrinter.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;cstddef&gt;
#include &lt;cstdint&gt;
#include &lt;utility&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/anonymous-dwarfacceleratortable-cpp-">anonymous{DWARFAcceleratorTable.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dwarfacceleratortable-cpp-/atom">Atom</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static Atom</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa975c3a1b5eb8ee021c8746cdd7de4fb">formatAtom</a> (unsigned Atom)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/attributeencoding">DWARFDebugNames::AttributeEncoding</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08271baaab8cea7a5e80e82308b2126d">sentinelAttrEnc</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aed031578039adc6374053233f53d6f">isSentinel</a> (const DWARFDebugNames::AttributeEncoding &amp;AE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev">DWARFDebugNames::Abbrev</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4810918df89d6c80317ce0fa14274de2">sentinelAbbrev</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c40a9a69d7ac0c214942f5f494e58ab">isSentinel</a> (const DWARFDebugNames::Abbrev &amp;Abbr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87eb92367f1bfb31f1e6d8301f37b0d8">isObjCSelector</a> (StringRef Name)</td>
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


<div class="doxySectionDef">

## Functions

### formatAtom() {#aa975c3a1b5eb8ee021c8746cdd7de4fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Atom formatAtom (unsigned Atom)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/appleacceleratortable/#abdb9058a51e2fb5fd61d203dcdfd551a">llvm::AppleAcceleratorTable::dump</a>.</p>

</div>
</div>

### isObjCSelector() {#a87eb92367f1bfb31f1e6d8301f37b0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isObjCSelector (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1076 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac52de24a1dd7695de94261e6ab8bb457">llvm::getObjCNamesIfSelector</a>.</p>

</div>
</div>

### isSentinel() {#a1aed031578039adc6374053233f53d6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSentinel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/attributeencoding">DWARFDebugNames::AttributeEncoding</a> &amp; AE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 491 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="#a08271baaab8cea7a5e80e82308b2126d">sentinelAttrEnc</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/callvalue/#ac96e19b3c68d14bc252bc64c994f11a1">anonymous{EarlyCSE.cpp}::CallValue::CallValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#ab880924a451b73edfe368d53c3d8631c">EliminateDuplicatePHINodesSetBasedImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugnames/nameindex/#acce40431959421046e6a001a951e8dd9">llvm::DWARFDebugNames::NameIndex::extract</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/gepvalue/#aabd5d3090025319d0196467ebcc1ade4">anonymous{EarlyCSE.cpp}::GEPValue::GEPValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/gepvalue/#a81bd8f32d23fd8b1d7a0c08d5f43769e">anonymous{EarlyCSE.cpp}::GEPValue::GEPValue</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-detail/node-base-prevnext-091d3899ff95c2824901f23dd4df29e2/#ab3339037cf31b6bdd8e0ad7fa157fad4">llvm::ilist_detail::node_base_prevnext&lt; NodeBase, true &gt;::isKnownSentinel</a> and <a href="/web-llvm/docs/api/structs/anonymous-earlycse-cpp-/simplevalue/#a5553b6a4d73374b6dc3f63328958f23a">anonymous{EarlyCSE.cpp}::SimpleValue::SimpleValue</a>.</p>

</div>
</div>

### isSentinel() {#a9c40a9a69d7ac0c214942f5f494e58ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isSentinel (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev">DWARFDebugNames::Abbrev</a> &amp; Abbr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 499 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugnames/abbrev/#a1ba909a75265c4eb2ba13528777002cb">llvm::DWARFDebugNames::Abbrev::Code</a>.</p>

</div>
</div>

### sentinelAbbrev() {#a4810918df89d6c80317ce0fa14274de2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DWARFDebugNames::Abbrev sentinelAbbrev ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>

</div>
</div>

### sentinelAttrEnc() {#a08271baaab8cea7a5e80e82308b2126d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">constexpr DWARFDebugNames::AttributeEncoding sentinelAttrEnc ()</td>
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



<p>Definition at line 487 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfacceleratortable-cpp">DWARFAcceleratorTable.cpp</a>.</p>


<p>Referenced by <a href="#a1aed031578039adc6374053233f53d6f">isSentinel</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
