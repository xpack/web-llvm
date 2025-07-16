---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/elfyaml/chunk
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Chunk` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::ELFYAML::Chunk { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">llvm/ObjectYAML/ELFYAML.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/elfyaml/fill">Fill</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/elfyaml/section">Section</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable">SectionHeaderTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ChunkKind { <a href="#ab68f803d16c3c44be1e8dbe5c2c682e8">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c1018577671f4f33d78d1a89ca120bb">Chunk</a> (ChunkKind K, bool Implicit)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf3230cc0550c54d901a4d17da82e33d">~Chunk</a> ()</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab68f803d16c3c44be1e8dbe5c2c682e8">ChunkKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af45a927d4e6e944a950c59ce0ffb9aa8">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8feb13348657c415a02f1c883f8344d1">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; llvm::yaml::Hex64 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fe341ccaf982d6148f10caaddd1e6bc">Offset</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#affcca580c5ea9281ce0a63d64da262e6">IsImplicit</a></td>
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


<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ChunkKind {#ab68f803d16c3c44be1e8dbe5c2c682e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ELFYAML::Chunk::ChunkKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Dynamic<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a971fd8cc345d8bd9f92e9f7d88fdf20c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Group<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a03937134cedab9078be39a77ee3a48a0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RawContent<a id="ab68f803d16c3c44be1e8dbe5c2c682e8ac34949db9ce05a7dcfa4cf073b161233"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Relocation<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a656cac63806390344159babef82cd855"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Relr<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a1368b815a6f4afbc88e09b93a69fcbcd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoBits<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a001a9743d76a3414a16927ddb442c8ef"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Note<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a3b0649c72650c313a357338dcdfb64ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Hash<a id="ab68f803d16c3c44be1e8dbe5c2c682e8afae8a9257e154175da4193dbf6552ef6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GnuHash<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a0818f8dfc1fa249af243b38c255ef0e7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Verdef<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a0fd3a9e030bfb9eddc8243ee36676a17"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Verneed<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a3262a0e301ee30bcea6d882f79bd3aab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">StackSizes<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a805a03a14b60ab1c6526d9bd6d559e08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SymtabShndxSection<a id="ab68f803d16c3c44be1e8dbe5c2c682e8ac31bc3a98304fba16da58c4b6ae502ba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Symver<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a33e647dbf94544185c038088df801d07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ARMIndexTable<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a55df54d738ac06e842241ebbdb071e29"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MipsABIFlags<a id="ab68f803d16c3c44be1e8dbe5c2c682e8ac8bd8d1ba9cb387b17e6209427cc3921"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Addrsig<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a2160fcfc10b37d36c52983f3bf0bfd49"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LinkerOptions<a id="ab68f803d16c3c44be1e8dbe5c2c682e8ac13148621b718094b716b6c5c905ba01"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DependentLibraries<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a5b7000c075f6c8074fc47f30f57203b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallGraphProfile<a id="ab68f803d16c3c44be1e8dbe5c2c682e8af27ac6e090f8556da592cd9c01a57564"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BBAddrMap<a id="ab68f803d16c3c44be1e8dbe5c2c682e8a8d47fdaa338846273d6c25a20a616d72"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SpecialChunksStart<a id="ab68f803d16c3c44be1e8dbe5c2c682e8ae6237945411f16594fa80cbb8ff1c981"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Fill<a id="ab68f803d16c3c44be1e8dbe5c2c682e8adb3e3f51c9107e26c9bccf9a188ce2ed"></a></td>
<td class="doxyEnumItemDescription"> (= SpecialChunksStart)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SectionHeaderTable<a id="ab68f803d16c3c44be1e8dbe5c2c682e8aeb94454f132c0169a9c89a3ddb07a994"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Chunk() {#a0c1018577671f4f33d78d1a89ca120bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ELFYAML::Chunk::Chunk (<a href="#ab68f803d16c3c44be1e8dbe5c2c682e8">ChunkKind</a> K, bool Implicit)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>


<p>References <a href="#affcca580c5ea9281ce0a63d64da262e6">IsImplicit</a> and <a href="#af45a927d4e6e944a950c59ce0ffb9aa8">Kind</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/elfyaml/fill/#a8023b995b754c019a90cadbefd7635b9">llvm::ELFYAML::Fill::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a5516b80698fa447eb119ae21e2d58e66">llvm::ELFYAML::Section::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable/#a9af69a0e03ca266777911979ea4e4ebc">llvm::ELFYAML::SectionHeaderTable::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/fill/#aef7db2d9ebd09fe135c806ab345193fb">llvm::ELFYAML::Fill::Fill</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a2698c2beb5c07d3537722b2d7b0496ca">llvm::ELFYAML::Section::Section</a> and <a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable/#aab2c45fb9443501d1c6a64147411b582">llvm::ELFYAML::SectionHeaderTable::SectionHeaderTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Chunk() {#aaf3230cc0550c54d901a4d17da82e33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ELFYAML::Chunk::~Chunk ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### IsImplicit {#affcca580c5ea9281ce0a63d64da262e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ELFYAML::Chunk::IsImplicit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>


<p>Referenced by <a href="#a0c1018577671f4f33d78d1a89ca120bb">Chunk</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable/#ad30ac3bac2ea38004c2c67d98e9b156e">llvm::ELFYAML::SectionHeaderTable::getNumHeaders</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a2698c2beb5c07d3537722b2d7b0496ca">llvm::ELFYAML::Section::Section</a> and <a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable/#aab2c45fb9443501d1c6a64147411b582">llvm::ELFYAML::SectionHeaderTable::SectionHeaderTable</a>.</p>

</div>
</div>

### Kind {#af45a927d4e6e944a950c59ce0ffb9aa8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChunkKind llvm::ELFYAML::Chunk::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>


<p>Referenced by <a href="#a0c1018577671f4f33d78d1a89ca120bb">Chunk</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/addrsigsection/#af134a109a7a7c7c1c1587a3db15c053d">llvm::ELFYAML::AddrsigSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/armindextablesection/#aac1382c7de8d489a3b81c0e2fa6b9482">llvm::ELFYAML::ARMIndexTableSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/bbaddrmapsection/#a59ef66f95960160e5acf9228124e9c45">llvm::ELFYAML::BBAddrMapSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/callgraphprofilesection/#ad85ea45a7cc66fbc5caac8437326d1d5">llvm::ELFYAML::CallGraphProfileSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/dependentlibrariessection/#ae3d89d48eea84500430783e61c91c1bc">llvm::ELFYAML::DependentLibrariesSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/dynamicsection/#a047a7b9096dd6fe682de1caba6cff615">llvm::ELFYAML::DynamicSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/fill/#a8023b995b754c019a90cadbefd7635b9">llvm::ELFYAML::Fill::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/gnuhashsection/#a99e4c50a9d3ab3a7c90228c087934d76">llvm::ELFYAML::GnuHashSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/groupsection/#a244a29da6f25892426edcbbb346e43f7">llvm::ELFYAML::GroupSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/hashsection/#a8b18c9f98f0ca67f2440251896963369">llvm::ELFYAML::HashSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/linkeroptionssection/#ac1b316cff84d8d0651e8c174e7419175">llvm::ELFYAML::LinkerOptionsSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/mipsabiflags/#a53b2328626c812a787f67ed88ce18676">llvm::ELFYAML::MipsABIFlags::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/nobitssection/#a94fbaa34e49a3ee74a44f55fab30bc1b">llvm::ELFYAML::NoBitsSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/notesection/#a7c7e2e9bd13288600d01b8e43267f871">llvm::ELFYAML::NoteSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/rawcontentsection/#a55d5925c22cc13ad353a18dfc5302006">llvm::ELFYAML::RawContentSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/relocationsection/#ac80f97fdb78b5e568df9716b4c47afe2">llvm::ELFYAML::RelocationSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/relrsection/#a521801067159b38bb245aa329e311143">llvm::ELFYAML::RelrSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a5516b80698fa447eb119ae21e2d58e66">llvm::ELFYAML::Section::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/sectionheadertable/#a9af69a0e03ca266777911979ea4e4ebc">llvm::ELFYAML::SectionHeaderTable::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/stacksizessection/#a28902f68ce93271862e49de410da212f">llvm::ELFYAML::StackSizesSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/symtabshndxsection/#a4f686727ec338870af42b9a26808d5a7">llvm::ELFYAML::SymtabShndxSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/symversection/#a6d40d3a65bc6e2be25601d5c8ed87a35">llvm::ELFYAML::SymverSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/verdefsection/#a516d9a257267894a271771b22ba632f5">llvm::ELFYAML::VerdefSection::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/elfyaml/verneedsection/#ab0376712ce3e16508e948397815ddb7b">llvm::ELFYAML::VerneedSection::classof</a> and <a href="/web-llvm/docs/api/structs/llvm/elfyaml/section/#a2698c2beb5c07d3537722b2d7b0496ca">llvm::ELFYAML::Section::Section</a>.</p>

</div>
</div>

### Name {#a8feb13348657c415a02f1c883f8344d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::ELFYAML::Chunk::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/elfyaml/stacksizessection/#a5d5c6c6ee5bcba2163078936f31d221c">llvm::ELFYAML::StackSizesSection::nameMatches</a>.</p>

</div>
</div>

### Offset {#a9fe341ccaf982d6148f10caaddd1e6bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;llvm::yaml::Hex64&gt; llvm::ELFYAML::Chunk::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a589ba45a5490ef34fda7d35463e0fc7c">llvm::yaml::sectionHeaderTableMapping</a> and <a href="/web-llvm/docs/api/classes/anonymous-elfemitter-cpp-/elfstate/#ae52777d0974a0686586c0e6c8087e084">anonymous{ELFEmitter.cpp}::ELFState&lt; ELFT &gt;::writeELF</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/objectyaml/elfyaml-h">ELFYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
