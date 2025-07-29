---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/jitlink/elflinkgraphbuilder-aarch32
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ELFLinkGraphBuilder_aarch32` Class Template



## Declaration

<div class="doxyDeclaration">
template &lt;llvm::endianness DataEndianness&gt;
class llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt;DataEndianness&gt; { ... }
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4ac669fbaea224dc99a59913ca4ff653">ELFT</a> = <a href="/web-llvm/docs/api/structs/llvm/object/elftype">ELFType</a>&lt; DataEndianness, false &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0f84651cab3b85270edece6a9273198f">Base</a> = <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder">ELFLinkGraphBuilder</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/elftype">ELFT</a> &gt;</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a7f4b54292cd078518fefb02374cdc421">ELFLinkGraphBuilder_aarch32</a> (StringRef FileName, const llvm::object::ELFFile&lt; ELFT &gt; &amp;Obj, std::shared_ptr&lt; orc::SymbolStringPool &gt; SSP, Triple TT, SubtargetFeatures Features, aarch32::ArmConfig ArmCfg)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a323fe44f4de0113e72a5392d91c12ef7">makeTargetFlags</a> (const typename ELFT::Sym &amp;Sym) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/orc/#a59b5f232ad8ec6bf405ddc77c3d6d752">orc::ExecutorAddrDiff</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5091dc9dddf6224d13c63258eaaceae3">getRawOffset</a> (const typename ELFT::Sym &amp;Sym, TargetFlagsType Flags) override</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9cfc6105babf29ae53f3477979df8f07">addRelocations</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Call to derived class to handle relocations. <a href="#a9cfc6105babf29ae53f3477979df8f07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a79ead4a85c422f961ea500a79936b673">addSingleRelRelocation</a> (const typename ELFT::Rel &amp;Rel, const typename ELFT::Shdr &amp;FixupSect, Block &amp;BlockToFix)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;llvm::endianness DataEndianness&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">aarch32::ArmConfig</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab4c1565666e6c28631c29f616bc84fa6">ArmCfg</a></td>
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


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### Base {#a0f84651cab3b85270edece6a9273198f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::Base =  ELFLinkGraphBuilder&lt;ELFT&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>

</div>
</div>

### ELFT {#a4ac669fbaea224dc99a59913ca4ff653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::ELFT =  ELFType&lt;DataEndianness, false&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ELFLinkGraphBuilder\_aarch32() {#a7f4b54292cd078518fefb02374cdc421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::ELFLinkGraphBuilder_aarch32 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FileName, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/elffile">llvm::object::ELFFile</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/elftype">ELFT</a> &gt; &amp; Obj, std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpool">orc::SymbolStringPool</a> &gt; SSP, <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> Features, <a href="/web-llvm/docs/api/structs/llvm/jitlink/aarch32/armconfig">aarch32::ArmConfig</a> ArmCfg)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a4209efe05789ea6287d2499d5366763f">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFType&lt; DataEndianness, false &gt; &gt;::ELFLinkGraphBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#a973318c52fa5f0593df8f3145940c516">llvm::jitlink::getELFAArch32EdgeKindName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="/web-llvm/docs/api/classes/llvm/jitlink/elflinkgraphbuilder/#a325728a6d5c1a376a01c854a48b11476">llvm::jitlink::ELFLinkGraphBuilder&lt; ELFType&lt; DataEndianness, false &gt; &gt;::Obj</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getRawOffset() {#a5091dc9dddf6224d13c63258eaaceae3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">orc::ExecutorAddrDiff llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::getRawOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/structs/llvm/object/elftype/#adf035ef3a492b5b951fd58f0cb807ced">ELFT::Sym</a> &amp; Sym, <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/#abc9bc580a689ae42bea77b8de495a70c">TargetFlagsType</a> Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#ac9b996f8dd6ccbcdab5bad57295d9b48">llvm::object::Elf_Sym_Impl&lt; ELFT &gt;::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#accd13c4a49f5be5b3aef772ba2141948">llvm::object::Elf_Sym_Impl&lt; ELFT &gt;::getValue</a>, <a href="#a323fe44f4de0113e72a5392d91c12ef7">llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::makeTargetFlags</a> and <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a>.</p>

</div>
</div>

### makeTargetFlags() {#a323fe44f4de0113e72a5392d91c12ef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetFlagsType llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::makeTargetFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/structs/llvm/object/elftype/#adf035ef3a492b5b951fd58f0cb807ced">ELFT::Sym</a> &amp; Sym)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#ac9b996f8dd6ccbcdab5bad57295d9b48">llvm::object::Elf_Sym_Impl&lt; ELFT &gt;::getType</a>, <a href="/web-llvm/docs/api/structs/llvm/object/elf-sym-impl/#accd13c4a49f5be5b3aef772ba2141948">llvm::object::Elf_Sym_Impl&lt; ELFT &gt;::getValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/elf/#ac6fcda18e36f2c9045a88905ff3fc179a28ceebccd9f41f8a7e2359ac45c59f66">llvm::ELF::STT_FUNC</a> and <a href="/web-llvm/docs/api/namespaces/llvm/jitlink/aarch32/#a8de4fa84b421de4e842bb78158a8ba4ca8c325ed3a8f210c3206b46cf846afe9b">llvm::jitlink::aarch32::ThumbSymbol</a>.</p>


<p>Referenced by <a href="#a5091dc9dddf6224d13c63258eaaceae3">llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::getRawOffset</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addRelocations() {#a9cfc6105babf29ae53f3477979df8f07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::addRelocations ()</td>
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


<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>

</div>
</div>

### addSingleRelRelocation() {#a79ead4a85c422f961ea500a79936b673}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::addSingleRelRelocation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/structs/llvm/object/elftype/#a3df613b9d37b371f8813858611b265ed">ELFT::Rel</a> &amp; Rel, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> typename <a href="/web-llvm/docs/api/structs/llvm/object/elftype/#a8fec91d096b20c03e753e95533345ba2">ELFT::Shdr</a> &amp; FixupSect, <a href="/web-llvm/docs/api/classes/llvm/jitlink/block">Block</a> &amp; BlockToFix)</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArmCfg {#ab4c1565666e6c28631c29f616bc84fa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;llvm::endianness DataEndianness&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">aarch32::ArmConfig llvm::jitlink::ELFLinkGraphBuilder_aarch32&lt; DataEndianness &gt;::ArmCfg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/jitlink/elf-aarch32-cpp">ELF_aarch32.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
