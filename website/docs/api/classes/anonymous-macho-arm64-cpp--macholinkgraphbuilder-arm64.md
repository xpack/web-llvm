---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-macho-arm64-cpp-/macholinkgraphbuilder-arm64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MachOLinkGraphBuilder_arm64` Class



## Declaration

<div class="doxyDeclaration">
class anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64 { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23fd211d08e2f8680edc75cbd3fefc87">PairRelocInfo</a> = std::tuple&lt; Edge::Kind, <a href="/web-llvm/docs/api/classes/llvm/jitlink/symbol">Symbol</a> *, uint64_t &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MachOARM64RelocationKind : Edge::Kind { <a href="#af871bd19bc58ebd11f078b75eb1154d6">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29a349bf83d4092aaeb36e2af537784">MachOLinkGraphBuilder_arm64</a> (const object::MachOObjectFile &amp;Obj, std::shared_ptr&lt; orc::SymbolStringPool &gt; SSP, SubtargetFeatures Features)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981c7e310f715cd369d64b92295f0429">parsePairRelocation</a> (Block &amp;BlockToFix, Edge::Kind SubtractorKind, const MachO::relocation_info &amp;SubRI, orc::ExecutorAddr FixupAddress, const char *FixupContent, object::relocation_iterator &amp;UnsignedRelItr, object::relocation_iterator &amp;RelEnd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89b5eecb3b69024d9731d967476aaac7">addRelocations</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55574a2d1dc6f41d6085691493e983e0">getMachOARM64RelocationKindName</a> (Edge::Kind R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the string name of the given <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> arm64 edge kind. <a href="#a55574a2d1dc6f41d6085691493e983e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7610de3dd2ffbfc679dee89ae9e43af">NumSymbols</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f1d09e1ac25ee6090de86eeffb3536">getObjectTriple</a> (const object::MachOObjectFile &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; MachOARM64RelocationKind &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29c7cb8097bbafeb0c66686bac531fd9">getRelocationKind</a> (const MachO::relocation_info &amp;RI)</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### PairRelocInfo {#a23fd211d08e2f8680edc75cbd3fefc87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::PairRelocInfo =  std::tuple&lt;Edge::Kind, Symbol *, uint64_t&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### MachOARM64RelocationKind {#af871bd19bc58ebd11f078b75eb1154d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::MachOARM64RelocationKind : Edge::Kind</td>
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
<td class="doxyEnumItemName">MachOBranch26<a id="af871bd19bc58ebd11f078b75eb1154d6a54a46186dcd5b1e0556813b3b7917432"></a></td>
<td class="doxyEnumItemDescription"> (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointer32<a id="af871bd19bc58ebd11f078b75eb1154d6a7b8f22d2ad44a04a177e1a01bda9fe98"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointer64<a id="af871bd19bc58ebd11f078b75eb1154d6a2b0d5c0798d7f665aa78458223e579f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointer64Anon<a id="af871bd19bc58ebd11f078b75eb1154d6ac40209c8006d9aed9d12665b7096e534"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointer64Authenticated<a id="af871bd19bc58ebd11f078b75eb1154d6ad936783402cd2149bf3e7afc5e1269df"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPage21<a id="af871bd19bc58ebd11f078b75eb1154d6adda29c11fc6b32abab9cfb0b1ec78733"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPageOffset12<a id="af871bd19bc58ebd11f078b75eb1154d6a99a258b6760183e08299dc05c4867205"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOGOTPage21<a id="af871bd19bc58ebd11f078b75eb1154d6a040df291ceb0d6cab1a6a00d093ec0c2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOGOTPageOffset12<a id="af871bd19bc58ebd11f078b75eb1154d6a1e7763250eed1b72aab19c33f45f288c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOTLVPage21<a id="af871bd19bc58ebd11f078b75eb1154d6ac11e6bf8c27f0dd0e7d7d6b8e7648404"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOTLVPageOffset12<a id="af871bd19bc58ebd11f078b75eb1154d6a9e5c66b4e09a2baf398b06985da8fbee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPointerToGOT<a id="af871bd19bc58ebd11f078b75eb1154d6a620dd9814476793a0d75787b35c57d9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOPairedAddend<a id="af871bd19bc58ebd11f078b75eb1154d6a453efb43266a2493390f0ae93ded2d30"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachOLDRLiteral19<a id="af871bd19bc58ebd11f078b75eb1154d6aa372b8da33b94c643b8389ed4864a151"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachODelta32<a id="af871bd19bc58ebd11f078b75eb1154d6a3b47553d14b5522011519c96704c61c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachODelta64<a id="af871bd19bc58ebd11f078b75eb1154d6a92e3f5b3b5bfeb0d1d316e7f1c24031d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachONegDelta32<a id="af871bd19bc58ebd11f078b75eb1154d6ad93e613f871b3f3d26dbe130a40c9197"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MachONegDelta64<a id="af871bd19bc58ebd11f078b75eb1154d6a81c622e3d36e20bb359c3de7ec547b52"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MachOLinkGraphBuilder\_arm64() {#aa29a349bf83d4092aaeb36e2af537784}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::MachOLinkGraphBuilder_arm64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">object::MachOObjectFile</a> &amp; Obj, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">orc::SymbolStringPool</a> &gt; SSP, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> Features)</td>
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



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/macholinkgraphbuilder/#a858d2c17dbc7a1306b127b648693a4a8">llvm::jitlink::MachOLinkGraphBuilder::MachOLinkGraphBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRelocations() {#a89b5eecb3b69024d9731d967476aaac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::addRelocations ()</td>
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



<p>Definition at line 252 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

### getMachOARM64RelocationKindName() {#a55574a2d1dc6f41d6085691493e983e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::getMachOARM64RelocationKindName (Edge::Kind R)</td>
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

<p>Return the string name of the given <a href="/web-llvm/docs/api/namespaces/llvm/macho">MachO</a> arm64 edge kind.</p>

<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

### parsePairRelocation() {#a981c7e310f715cd369d64b92295f0429}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; PairRelocInfo &gt; anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::parsePairRelocation (<a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; BlockToFix, Edge::Kind SubtractorKind, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info">MachO::relocation_info</a> &amp; SubRI, <a href="/web-llvm/docs/api/classes/llvm/orc/executoraddr">orc::ExecutorAddr</a> FixupAddress, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * FixupContent, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">object::relocation_iterator</a> &amp; UnsignedRelItr, <a href="/web-llvm/docs/api/namespaces/llvm/object/#acc360db994cbcc482937196bf406df98">object::relocation_iterator</a> &amp; RelEnd)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### NumSymbols {#ae7610de3dd2ffbfc679dee89ae9e43af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::NumSymbols = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getObjectTriple() {#aa8f1d09e1ac25ee6090de86eeffb3536}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::getObjectTriple (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/machoobjectfile">object::MachOObjectFile</a> &amp; Obj)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

### getRelocationKind() {#a29c7cb8097bbafeb0c66686bac531fd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MachOARM64RelocationKind &gt; anonymous{MachO_arm64.cpp}::MachOLinkGraphBuilder_arm64::getRelocationKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/macho/relocation-info">MachO::relocation_info</a> &amp; RI)</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/macho-arm64-cpp">MachO_arm64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
