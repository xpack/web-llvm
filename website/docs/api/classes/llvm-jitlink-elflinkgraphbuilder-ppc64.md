---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/elflinkgraphbuilder-ppc64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFLinkGraphBuilder_ppc64` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;llvm::endianness Endianness&gt;
class llvm::jitlink::ELFLinkGraphBuilder_ppc64&lt;Endianness&gt; { ... }
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abdee7614d5d803923575293a3937e107">ELFT</a> = <a href="/web-llvm/docs/api/structs/llvm/object/elftype">object::ELFType</a>&lt; Endianness, <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abbe98bf9aaddeb7d34afa2cb6609602b">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder">ELFLinkGraphBuilder</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/elftype">ELFT</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a2823efdc53a37cceb5459d67ede2ecca">ELFLinkGraphBuilder_ppc64</a> (StringRef FileName, const object::ELFFile&lt; ELFT &gt; &amp;Obj, std::shared_ptr&lt; orc::SymbolStringPool &gt; SSP, Triple TT, SubtargetFeatures Features)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5f68521cdfef2e6bad44ccaf3339a376">addRelocations</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call to derived class to handle relocations. <a href="#a5f68521cdfef2e6bad44ccaf3339a376">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness Endianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2a3febca54833967a442df2a68b6e9ca">addSingleRelocation</a> (const typename ELFT::Rela &amp;Rel, const typename ELFT::Shdr &amp;FixupSection, Block &amp;BlockToFix)</td>
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


<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#abbe98bf9aaddeb7d34afa2cb6609602b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::ELFLinkGraphBuilder_ppc64&lt; Endianness &gt;::Base =  ELFLinkGraphBuilder&lt;ELFT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

### ELFT {#abdee7614d5d803923575293a3937e107}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::ELFLinkGraphBuilder_ppc64&lt; Endianness &gt;::ELFT =  object::ELFType&lt;Endianness, true&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ELFLinkGraphBuilder\_ppc64() {#a2823efdc53a37cceb5459d67ede2ecca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::ELFLinkGraphBuilder_ppc64&lt; Endianness &gt;::ELFLinkGraphBuilder_ppc64 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">object::ELFFile</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/elftype">ELFT</a> &gt; &amp; Obj, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">orc::SymbolStringPool</a> &gt; SSP, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> Features)</td>
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



<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a4209efe05789ea6287d2499d5366763f">llvm::jitlink::ELFLinkGraphBuilder&lt; object::ELFType&lt; Endianness, true &gt; &gt;::ELFLinkGraphBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; object::ELFType&lt; Endianness, true &gt; &gt;::Obj</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRelocations() {#a5f68521cdfef2e6bad44ccaf3339a376}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder_ppc64&lt; Endianness &gt;::addRelocations ()</td>
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


<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

### addSingleRelocation() {#a2a3febca54833967a442df2a68b6e9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness Endianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder_ppc64&lt; Endianness &gt;::addSingleRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/structs/llvm/object/elftype/#a651d2ec91430c2e19f00b80a3e623653">ELFT::Rela</a> &amp; Rel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/structs/llvm/object/elftype/#a8fec91d096b20c03e753e95533345ba2">ELFT::Shdr</a> &amp; FixupSection, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; BlockToFix)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-ppc64-cpp">ELF_ppc64.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
