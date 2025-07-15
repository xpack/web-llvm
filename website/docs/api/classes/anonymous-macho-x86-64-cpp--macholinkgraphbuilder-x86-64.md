---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-macho-x86-64-cpp-/macholinkgraphbuilder-x86-64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `MachOLinkGraphBuilder_x86_64` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{MachO_x86_64.cpp}::MachOLinkGraphBuilder_x86_64 { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/macholinkgraphbuilder">MachOLinkGraphBuilder</a></td>
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeda192c8acc9402c36fc3f217c241f75">PairRelocInfo</a> = std::tuple&lt; Edge::Kind, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> *, uint64_t &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MachONormalizedRelocationType : unsigned { <a href="#a67c4388121129567ffef4cf49e45c526">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad569a429fb4f5a808a850747c4c4d1fa">MachOLinkGraphBuilder_x86_64</a> (const object::MachOObjectFile &amp;Obj, std::shared_ptr&lt; orc::SymbolStringPool &gt; SSP, SubtargetFeatures Features)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; PairRelocInfo &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a478368514b0ef3c1fbb7ea32c5d72ac7">parsePairRelocation</a> (Block &amp;BlockToFix, MachONormalizedRelocationType SubtractorKind, const MachO::relocation_info &amp;SubRI, orc::ExecutorAddr FixupAddress, const char *FixupContent, object::relocation_iterator &amp;UnsignedRelItr, object::relocation_iterator &amp;RelEnd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac53cfd9995ef6d3dbf7657744a8ad908">addRelocations</a> () override</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; MachONormalizedRelocationType &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e1e666507d68a2f4ff57559f952fd10">getRelocKind</a> (const MachO::relocation_info &amp;RI)</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### PairRelocInfo {#aeda192c8acc9402c36fc3f217c241f75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachO_x86_64.cpp}::MachOLinkGraphBuilder_x86_64::PairRelocInfo =  std::tuple&lt;Edge::Kind, Symbol *, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### MachONormalizedRelocationType {#a67c4388121129567ffef4cf49e45c526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MachO_x86_64.cpp}::MachOLinkGraphBuilder_x86_64::MachONormalizedRelocationType : unsigned</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOBranch32<a id="a67c4388121129567ffef4cf49e45c526a652c9eecaf7849f082140d5283a0ee04"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointer32<a id="a67c4388121129567ffef4cf49e45c526af526a2eac93faef8ab1aa8a21954e274"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointer64<a id="a67c4388121129567ffef4cf49e45c526abdb975b86adb479dd035ce4df670ef1b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointer64Anon<a id="a67c4388121129567ffef4cf49e45c526a21772a3001bdd65170c9cbc2a328ab17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32<a id="a67c4388121129567ffef4cf49e45c526a1bf7e682facd692ea8a6725784f0ff51"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32Minus1<a id="a67c4388121129567ffef4cf49e45c526a2f56ec8c360c3b8e4d1ae0e57347a086"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32Minus2<a id="a67c4388121129567ffef4cf49e45c526a3f90ffa1c5d497b50ad5f76acd1d19c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32Minus4<a id="a67c4388121129567ffef4cf49e45c526a19381187cc0d8f5763712a1fb325d025"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32Anon<a id="a67c4388121129567ffef4cf49e45c526a4fa7dbb3a3e3c5c999826673387a71dc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32Minus1Anon<a id="a67c4388121129567ffef4cf49e45c526a1d735936ae601f6d94a000f4e719f25d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32Minus2Anon<a id="a67c4388121129567ffef4cf49e45c526a6e9f4c7bfb2f67e3dea3d1e4ed62e4c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32Minus4Anon<a id="a67c4388121129567ffef4cf49e45c526a345a7c924ba9be7958b3664e2790eb50"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32GOTLoad<a id="a67c4388121129567ffef4cf49e45c526a82247524dc1e4bf43d75749ba759352b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32GOT<a id="a67c4388121129567ffef4cf49e45c526a5970d46f33b3312ba4f70bcbadfa4274"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPCRel32TLV<a id="a67c4388121129567ffef4cf49e45c526a81e276cf5e98e0686448f7bfcbb1d256"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOSubtractor32<a id="a67c4388121129567ffef4cf49e45c526a462f4b25469914472504a6de215c3540"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOSubtractor64<a id="a67c4388121129567ffef4cf49e45c526a6a0babaf3d48df898fd535841009f9cc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachOLinkGraphBuilder\_x86\_64() {#ad569a429fb4f5a808a850747c4c4d1fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachO_x86_64.cpp}::MachOLinkGraphBuilder_x86_64::MachOLinkGraphBuilder_x86_64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">object::MachOObjectFile</a> &amp; Obj, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">orc::SymbolStringPool</a> &gt; SSP, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> Features)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/macholinkgraphbuilder/#a858d2c17dbc7a1306b127b648693a4a8">llvm::jitlink::MachOLinkGraphBuilder::MachOLinkGraphBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRelocations() {#ac53cfd9995ef6d3dbf7657744a8ad908}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{MachO_x86_64.cpp}::MachOLinkGraphBuilder_x86_64::addRelocations ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>

</div>
</div>

### parsePairRelocation() {#a478368514b0ef3c1fbb7ea32c5d72ac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; PairRelocInfo &gt; anonymous{MachO_x86_64.cpp}::MachOLinkGraphBuilder_x86_64::parsePairRelocation (<a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; BlockToFix, MachONormalizedRelocationType SubtractorKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info">MachO::relocation_info</a> &amp; SubRI, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> FixupAddress, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FixupContent, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">object::relocation_iterator</a> &amp; UnsignedRelItr, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">object::relocation_iterator</a> &amp; RelEnd)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getRelocKind() {#a7e1e666507d68a2f4ff57559f952fd10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachONormalizedRelocationType &gt; anonymous{MachO_x86_64.cpp}::MachOLinkGraphBuilder_x86_64::getRelocKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info">MachO::relocation_info</a> &amp; RI)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-x86-64-cpp">MachO_x86_64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
