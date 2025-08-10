---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-elf-aarch64-cpp-/elflinkgraphbuilder-aarch64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFLinkGraphBuilder_aarch64` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;typename ELFT&gt;
class anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt;ELFT&gt; { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder">ELFLinkGraphBuilder&lt;ELFT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/jitlink/linkgraph">LinkGraph</a> building code that's specific to the given ELFT, but common across all architectures. <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top">ELFAArch64RelocationKind : Edge::Kind { <a href="#aa8c35855070be656b8b8e9060689207b">...</a> }</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab07fca3cb5c79b4000e48e4d3585aef7">ELFLinkGraphBuilder_aarch64</a> (StringRef FileName, const object::ELFFile&lt; ELFT &gt; &amp;Obj, std::shared_ptr&lt; orc::SymbolStringPool &gt; SSP, Triple TT, SubtargetFeatures Features)</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a58f8ee3e1e7e7f7279c10d6f530617c3">addRelocations</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call to derived class to handle relocations. <a href="#a58f8ee3e1e7e7f7279c10d6f530617c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab5673223dcb9530884c7370b76d8780f">addSingleRelocation</a> (const typename ELFT::Rela &amp;Rel, const typename ELFT::Shdr &amp;FixupSect, Block &amp;BlockToFix)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afa85874c8fbb272dfd001c8f66166e16">getELFAArch64RelocationKindName</a> (Edge::Kind R)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the string name of the given <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> edge kind. <a href="#afa85874c8fbb272dfd001c8f66166e16">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ELFT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a958cdb5b47eeb3f179a647c7183e2c10">getRelocationKind</a> (const uint32_t Type) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; ELFAArch64RelocationKind &gt;</td>
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


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ELFAArch64RelocationKind {#aa8c35855070be656b8b8e9060689207b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64::ELFAArch64RelocationKind : Edge::Kind</td>
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
<td class="doxyEnumItemName">ELFCall26<a id="aa8c35855070be656b8b8e9060689207ba37481081137e58628ba86db9030b08f2"></a></td>
<td class="doxyEnumItemDescription"> (= Edge::FirstRelocation)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLdrLo19<a id="aa8c35855070be656b8b8e9060689207ba605cf7fdadf72af796b028e92cbc50e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFAdrLo21<a id="aa8c35855070be656b8b8e9060689207ba6e99d7b59e0aea16aed7f0b05fda3be8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFAdrPage21<a id="aa8c35855070be656b8b8e9060689207babe54e7aee3b22c3c34d27086832c6e01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFAddAbs12<a id="aa8c35855070be656b8b8e9060689207baf3af4b5ce4ffa1b3d9263a335d4ebfca"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLdSt8Abs12<a id="aa8c35855070be656b8b8e9060689207baf2a810271027bc74ba9397e86645ae87"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLdSt16Abs12<a id="aa8c35855070be656b8b8e9060689207ba34b97014f26a0f1474133f9d18482d07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLdSt32Abs12<a id="aa8c35855070be656b8b8e9060689207ba9bf14965cc3120351527c8042eedec86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLdSt64Abs12<a id="aa8c35855070be656b8b8e9060689207ba4f88c68b6d16e137ee59c8d4a61aa8ac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLdSt128Abs12<a id="aa8c35855070be656b8b8e9060689207ba288411c604d147242424f23b126674c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFMovwAbsG0<a id="aa8c35855070be656b8b8e9060689207ba100edcdb25975dc2300a287635ee4f6c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFMovwAbsG1<a id="aa8c35855070be656b8b8e9060689207bac75b40141231eb42b2acbf4e9a2a3bcb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFMovwAbsG2<a id="aa8c35855070be656b8b8e9060689207baaeaad7537600bba8ec921a375d4b9df3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFMovwAbsG3<a id="aa8c35855070be656b8b8e9060689207ba29bd7bd72760cb293b072e4acdc7278f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFTstBr14<a id="aa8c35855070be656b8b8e9060689207ba5bd944bfc13353de5ad5115eedff0d2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFCondBr19<a id="aa8c35855070be656b8b8e9060689207bab8e421747f14c19e89bcac70452c7934"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFAbs32<a id="aa8c35855070be656b8b8e9060689207ba5e0ed94d8c70005e8f75fac951ac1c0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFAbs64<a id="aa8c35855070be656b8b8e9060689207babad4aa5e81beb9c66bae9c0b303d2ab0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFPrel32<a id="aa8c35855070be656b8b8e9060689207baf30d31c204f1382154895e753ac49224"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFPrel64<a id="aa8c35855070be656b8b8e9060689207baec5431069a9aef90ede5898a3e6b209a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFAdrGOTPage21<a id="aa8c35855070be656b8b8e9060689207bab17aa6901b000cb33bd1db0ff9507fb9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLd64GOTLo12<a id="aa8c35855070be656b8b8e9060689207ba9ed98ecb3db4cacd9c90c4923f0a0a9d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFLd64GOTPAGELo15<a id="aa8c35855070be656b8b8e9060689207bad42a49105ab2617b8291d08b330eb833"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFTLSDescAdrPage21<a id="aa8c35855070be656b8b8e9060689207ba171545768e90478334fa3ad757cca8f3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFTLSDescAddLo12<a id="aa8c35855070be656b8b8e9060689207bae9206c17b58d35e615412aa2c11f5384"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFTLSDescLd64Lo12<a id="aa8c35855070be656b8b8e9060689207ba8ab0ccfa3185f1095542813369f188b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELFTLSDescCall<a id="aa8c35855070be656b8b8e9060689207baab8228509ec1691237309d20443fa6a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ELFLinkGraphBuilder\_aarch64() {#ab07fca3cb5c79b4000e48e4d3585aef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt; ELFT &gt;::ELFLinkGraphBuilder_aarch64 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">object::ELFFile</a>&lt; ELFT &gt; &amp; Obj, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">orc::SymbolStringPool</a> &gt; SSP, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> Features)</td>
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



<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a4209efe05789ea6287d2499d5366763f">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::ELFLinkGraphBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFT &gt;::Obj</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRelocations() {#a58f8ee3e1e7e7f7279c10d6f530617c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt; ELFT &gt;::addRelocations ()</td>
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

<p>Call to derived class to handle relocations.</p>


<p>These require architecture specific knowledge to map to JITLink edge kinds.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a>.</p>

</div>
</div>

### addSingleRelocation() {#ab5673223dcb9530884c7370b76d8780f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt; ELFT &gt;::addSingleRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Rela &amp; Rel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename ELFT::Shdr &amp; FixupSect, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; BlockToFix)</td>
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



<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a>.</p>

</div>
</div>

### getELFAArch64RelocationKindName() {#afa85874c8fbb272dfd001c8f66166e16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt; ELFT &gt;::getELFAArch64RelocationKindName (Edge::Kind R)</td>
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

<p>Return the string name of the given <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch64">aarch64</a> edge kind.</p>

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### getRelocationKind() {#a958cdb5b47eeb3f179a647c7183e2c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ELFT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ELFAArch64RelocationKind &gt; anonymous{ELF_aarch64.cpp}::ELFLinkGraphBuilder_aarch64&lt; ELFT &gt;::getRelocationKind (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t Type)</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch64-cpp">ELF_aarch64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
