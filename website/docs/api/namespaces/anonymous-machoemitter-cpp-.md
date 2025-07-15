---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-machoemitter-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{MachOEmitter.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{MachOEmitter.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machoemitter-cpp-/machowriter">MachOWriter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-machoemitter-cpp-/universalwriter">UniversalWriter</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SectionType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">SectionType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a59a2e25869569d3d84f42d39d2a78baf">constructSection</a> (const MachOYAML::Section &amp;Sec)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename StructType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1226099fc7d6b8323cb56bc93b8ac79">writeLoadCommandData</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4526bc01726a48ab04a549eb59f98d82">writeLoadCommandData&lt; MachO::segment_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218333fa07659a7328c0122fa819ed74">writeLoadCommandData&lt; MachO::segment_command_64 &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda788d784e2a7f5e8f5d572edf655ed">writeLoadCommandData&lt; MachO::dylib_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1a84773761197a923a026ee5bbe2efe">writeLoadCommandData&lt; MachO::dylinker_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababe0ac58c8fd97b5843ef74a9b811b3">writeLoadCommandData&lt; MachO::rpath_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa497e0bdae18f0ff39c572c223858eca">writeLoadCommandData&lt; MachO::sub_framework_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0838db0a933117d117b50254625a792a">writeLoadCommandData&lt; MachO::sub_umbrella_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4ee18fe45b97a79627e098f6467343">writeLoadCommandData&lt; MachO::sub_client_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0cbb158e74a61c65d57598fab5a45fe">writeLoadCommandData&lt; MachO::sub_library_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0452cfab8d631ffe612b7db3ca753f3">writeLoadCommandData&lt; MachO::build_version_command &gt;</a> (MachOYAML::LoadCommand &amp;LC, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad384887e7ea0a8cb24eb9843a7eeaea3">ZeroFillBytes</a> (raw_ostream &amp;OS, size_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bcc321a63a6cafde4809bbbe835e2ed">Fill</a> (raw_ostream &amp;OS, size_t Size, uint32_t Data)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add84f157f58d2607efb42b9723c3235a">makeRelocationInfo</a> (const MachOYAML::Relocation &amp;R, bool IsLE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info">MachO::any_relocation_info</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed774ebd1348ca6144ae96c13de706c9">makeScatteredRelocationInfo</a> (const MachOYAML::Relocation &amp;R)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename NListType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46fc3f6bb1d9703770ef88e4b3d5d90b">writeNListEntry</a> (MachOYAML::NListEntry &amp;NLE, raw_ostream &amp;OS, bool IsLittleEndian)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename FatArchType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">FatArchType</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa33d56236bd375c3b794773f4a9bb2f1">constructFatArch</a> (MachOYAML::FatArch &amp;Arch)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename StructType&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11910abe491a09e338cb62f5dff69cab">writeFatArch</a> (MachOYAML::FatArch &amp;LC, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d4982689181e30f9114c6b35ec7facc">writeFatArch&lt; MachO::fat_arch &gt;</a> (MachOYAML::FatArch &amp;Arch, raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e7b80e5a81e549928ca2e08054efa8">writeFatArch&lt; MachO::fat_arch_64 &gt;</a> (MachOYAML::FatArch &amp;Arch, raw_ostream &amp;OS)</td>
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

### constructFatArch() {#aa33d56236bd375c3b794773f4a9bb2f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FatArchType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FatArchType anonymous{MachOEmitter.cpp}::constructFatArch (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch">MachOYAML::FatArch</a> &amp; Arch)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 691 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch/#a6af3d107e8c53996156ea3b8bc9390b7">llvm::MachOYAML::FatArch::align</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch/#ababfbb5092ec6615e8670ad32eea8fb7">llvm::MachOYAML::FatArch::cpusubtype</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch/#a1bd47e94d530e3e98d4ea694b2b1760e">llvm::MachOYAML::FatArch::cputype</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch/#a0c19c878c03ae8f131c81ea4df8958f6">llvm::MachOYAML::FatArch::offset</a> and <a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch/#a2d8430cd21c1d9eede148721d0d3a404">llvm::MachOYAML::FatArch::size</a>.</p>


<p>Referenced by <a href="#a5d4982689181e30f9114c6b35ec7facc">writeFatArch&lt; MachO::fat_arch &gt;</a> and <a href="#a04e7b80e5a81e549928ca2e08054efa8">writeFatArch&lt; MachO::fat_arch_64 &gt;</a>.</p>

</div>
</div>

### constructSection() {#a59a2e25869569d3d84f42d39d2a78baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SectionType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SectionType anonymous{MachOEmitter.cpp}::constructSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section">MachOYAML::Section</a> &amp; Sec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#a69b7ed316b2c7b3c07a61509f8838e01">llvm::MachOYAML::Section::addr</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#a1b033f5c91c69abbb17ea09725109846">llvm::MachOYAML::Section::align</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#af66684a8034c22111242ad52f8b24009">llvm::MachOYAML::Section::flags</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#af1b9dd9eff1c5ba49c9387f76654a4b4">llvm::MachOYAML::Section::nreloc</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#aaf188f06dff4f48dda2066aed7d2f0b3">llvm::MachOYAML::Section::offset</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#a8f635859d240afe52c7685a940967175">llvm::MachOYAML::Section::reloff</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#a7b0c1a7c90423e9043b2bd838bd0f84b">llvm::MachOYAML::Section::reserved1</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#a68c7959f7e7ff0cb61b30b0b3cfa90eb">llvm::MachOYAML::Section::reserved2</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#a73a5031e5184185583260e221df023e3">llvm::MachOYAML::Section::sectname</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#a40e71c69c8a4d9ec38d8dfedb2f7f3ed">llvm::MachOYAML::Section::segname</a> and <a href="/web-llvm/docs/api/structs/llvm/machoyaml/section/#afdc1dfefa81110478394f9c0938fccca">llvm::MachOYAML::Section::size</a>.</p>


<p>Referenced by <a href="#a4526bc01726a48ab04a549eb59f98d82">writeLoadCommandData&lt; MachO::segment_command &gt;</a> and <a href="#a218333fa07659a7328c0122fa819ed74">writeLoadCommandData&lt; MachO::segment_command_64 &gt;</a>.</p>

</div>
</div>

### Fill() {#a3bcc321a63a6cafde4809bbbe835e2ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachOEmitter.cpp}::Fill (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, size_t Size, uint32_t Data)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### makeRelocationInfo() {#add84f157f58d2607efb42b9723c3235a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::any_relocation_info anonymous{MachOEmitter.cpp}::makeRelocationInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machoyaml/relocation">MachOYAML::Relocation</a> &amp; R, bool IsLE)</td>
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



<p>Definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>

</div>
</div>

### makeScatteredRelocationInfo() {#aed774ebd1348ca6144ae96c13de706c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachO::any_relocation_info anonymous{MachOEmitter.cpp}::makeScatteredRelocationInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/machoyaml/relocation">MachOYAML::Relocation</a> &amp; R)</td>
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



<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a5155210832b813b1bb19b1830cad62b5ad528edd5b6f57022a7d7f12b5d8d55c7">llvm::MachO::R_SCATTERED</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#a2c1c46bbe4b0ef3065fe91d3e9ca806e">llvm::MachO::any_relocation_info::r_word0</a> and <a href="/web-llvm/docs/api/structs/llvm/macho/any-relocation-info/#aff97edf4109298178b12aca5621bd6ec">llvm::MachO::any_relocation_info::r_word1</a>.</p>

</div>
</div>

### writeFatArch() {#a11910abe491a09e338cb62f5dff69cab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename StructType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachOEmitter.cpp}::writeFatArch (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch">MachOYAML::FatArch</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>

</div>
</div>

### writeFatArch&lt; MachO::fat\_arch &gt;() {#a5d4982689181e30f9114c6b35ec7facc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachOEmitter.cpp}::writeFatArch&lt; MachO::fat_arch &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch">MachOYAML::FatArch</a> &amp; Arch, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="#aa33d56236bd375c3b794773f4a9bb2f1">constructFatArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### writeFatArch&lt; MachO::fat\_arch\_64 &gt;() {#a04e7b80e5a81e549928ca2e08054efa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachOEmitter.cpp}::writeFatArch&lt; MachO::fat_arch_64 &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch">MachOYAML::FatArch</a> &amp; Arch, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="#aa33d56236bd375c3b794773f4a9bb2f1">constructFatArch</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/fatarch/#ad8597b1f87407c555bad3655b0f46bf9">llvm::MachOYAML::FatArch::reserved</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### writeLoadCommandData() {#ad1226099fc7d6b8323cb56bc93b8ac79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename StructType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::build\_version\_command &gt;() {#ab0452cfab8d631ffe612b7db3ca753f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::build_version_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/build-tool-version/#a535b03ad464e5f96ec323dec8d2b5488">llvm::MachO::build_tool_version::tool</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand/#acb414009afbdf8d402b752460dce9300">llvm::MachOYAML::LoadCommand::Tools</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::dylib\_command &gt;() {#adda788d784e2a7f5e8f5d572edf655ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::dylib_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>Reference <a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::dylinker\_command &gt;() {#ae1a84773761197a923a026ee5bbe2efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::dylinker_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>Reference <a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::rpath\_command &gt;() {#ababe0ac58c8fd97b5843ef74a9b811b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::rpath_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>Reference <a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::segment\_command &gt;() {#a4526bc01726a48ab04a549eb59f98d82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::segment_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="#a59a2e25869569d3d84f42d39d2a78baf">constructSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand/#a779fd93978fe0bdbde03acf696a2e42c">llvm::MachOYAML::LoadCommand::Sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::segment\_command\_64 &gt;() {#a218333fa07659a7328c0122fa819ed74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::segment_command_64 &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="#a59a2e25869569d3d84f42d39d2a78baf">constructSection</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand/#a779fd93978fe0bdbde03acf696a2e42c">llvm::MachOYAML::LoadCommand::Sections</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::sub\_client\_command &gt;() {#a1d4ee18fe45b97a79627e098f6467343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::sub_client_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>Reference <a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::sub\_framework\_command &gt;() {#aa497e0bdae18f0ff39c572c223858eca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::sub_framework_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>Reference <a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::sub\_library\_command &gt;() {#ae0cbb158e74a61c65d57598fab5a45fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::sub_library_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>Reference <a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a>.</p>

</div>
</div>

### writeLoadCommandData&lt; MachO::sub\_umbrella\_command &gt;() {#a0838db0a933117d117b50254625a792a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::sub_umbrella_command &gt; (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>Reference <a href="#a3209e484dbc45751b9a056593f408e10">writePayloadString</a>.</p>

</div>
</div>

### writeNListEntry() {#a46fc3f6bb1d9703770ef88e4b3d5d90b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename NListType&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachOEmitter.cpp}::writeNListEntry (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/nlistentry">MachOYAML::NListEntry</a> &amp; NLE, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool IsLittleEndian)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 474 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a4ee2015697caec796e59972aadc2f9e2">llvm::sys::IsLittleEndianHost</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/nlistentry/#a909ca1f39d2b2087fcc28b6e663dd2c5">llvm::MachOYAML::NListEntry::n_desc</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/nlistentry/#a0e1d729a84d763f2c2cd71eaaf19b68a">llvm::MachOYAML::NListEntry::n_sect</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/nlistentry/#ac0985b9595f4899c5418ae84f174f033">llvm::MachOYAML::NListEntry::n_strx</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/nlistentry/#a77f85d549dd3a2e87eff124ab0dcd56a">llvm::MachOYAML::NListEntry::n_type</a>, <a href="/web-llvm/docs/api/structs/llvm/machoyaml/nlistentry/#a7fc132fc7befac1cedb1d35345ff68e7">llvm::MachOYAML::NListEntry::n_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a754466f4b36d6a2365e56663e0d9de83">llvm::MachO::swapStruct</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

### writePayloadString() {#a3209e484dbc45751b9a056593f408e10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t anonymous{MachOEmitter.cpp}::writePayloadString (<a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand">MachOYAML::LoadCommand</a> &amp; LC, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/machoyaml/loadcommand/#a01f57d006721307993542e0b1369d12c">llvm::MachOYAML::LoadCommand::Content</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>


<p>Referenced by <a href="#adda788d784e2a7f5e8f5d572edf655ed">writeLoadCommandData&lt; MachO::dylib_command &gt;</a>, <a href="#ae1a84773761197a923a026ee5bbe2efe">writeLoadCommandData&lt; MachO::dylinker_command &gt;</a>, <a href="#ababe0ac58c8fd97b5843ef74a9b811b3">writeLoadCommandData&lt; MachO::rpath_command &gt;</a>, <a href="#a1d4ee18fe45b97a79627e098f6467343">writeLoadCommandData&lt; MachO::sub_client_command &gt;</a>, <a href="#aa497e0bdae18f0ff39c572c223858eca">writeLoadCommandData&lt; MachO::sub_framework_command &gt;</a>, <a href="#ae0cbb158e74a61c65d57598fab5a45fe">writeLoadCommandData&lt; MachO::sub_library_command &gt;</a> and <a href="#a0838db0a933117d117b50254625a792a">writeLoadCommandData&lt; MachO::sub_umbrella_command &gt;</a>.</p>

</div>
</div>

### ZeroFillBytes() {#ad384887e7ea0a8cb24eb9843a7eeaea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MachOEmitter.cpp}::ZeroFillBytes (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a6e0cbc5c8568d8446c284c8538b2c9f1">llvm::raw_ostream::write</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objectyaml/machoemitter-cpp">MachOEmitter.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
