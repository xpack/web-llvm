---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/architectureset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ArchitectureSet` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::ArchitectureSet { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">llvm/TextAPI/ArchitectureSet.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33ab805f5438911ed1715ce48770c3b9">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/arch-iterator">arch_iterator</a>&lt; ArchSetType &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad96f22583acebae0223b931e853f45b4">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset/arch-iterator">arch_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArchSetType &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71ee248e0f745cbca34274eea1deb008">ArchSetType</a> = uint32_t</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a059528c4309f5eca68630455c9609cea">ArchitectureSet</a> (ArchSetType Raw)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2a719d9b757db09497fe21e0086121">ArchitectureSet</a> (Architecture Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fff93011d31d541bee7ea83db26f9e">ArchitectureSet</a> (const std::vector&lt; Architecture &gt; &amp;Archs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa74394642228bcc6085fa694a25090cc">operator&amp;</a> (const ArchitectureSet &amp;o)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9fb0ab2f929b888eb8453d77137bc0">operator|</a> (const ArchitectureSet &amp;o)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace82dba6c30cf706d5a14f065f4fbd2f">operator|=</a> (const ArchitectureSet &amp;o)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa96c325cfbc8c3a99511fd3984137085">operator|=</a> (const Architecture &amp;Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7205bd1cde4ad9b85a9d40ccea7ba92a">operator==</a> (const ArchitectureSet &amp;o) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9515bea0ef5f9c6f1bee5e44318006ca">operator!=</a> (const ArchitectureSet &amp;o) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3f7136edbbd48123675df97f1ccfe4a">operator&lt;</a> (const ArchitectureSet &amp;o) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad0d7b6967bcc3abaf68ce92592ae4a6">operator std::string</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f2c541a506e6b0cf801e7d1103d5d6a">operator std::vector&lt; Architecture &gt;</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90c084869398bd78ffcc075d52f0efc5">set</a> (Architecture Arch)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b1ed15dfe8e9873fdaccc198bb816f">clear</a> (Architecture Arch)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76b67e4256ae13907721adbb0762ab78">has</a> (Architecture Arch) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93801a3e0055a049cfd51bbb389ee8d2">contains</a> (ArchitectureSet Archs) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abee887b22c8f99f36a1e5c246b6ff8c8">count</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee1b8038a612cd0e8aa65b3e9f5999da">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">ArchSetType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bc11cab0d6501b39f16f632d30a0437">rawValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0dcd9160ac84c61caa4c5b4497f9fe4">hasX86</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a33ab805f5438911ed1715ce48770c3b9">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac41eea11388e27ec261668471f8729ba">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a33ab805f5438911ed1715ce48770c3b9">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2fc2e8c2a67bf071850f215c34ef32d">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad96f22583acebae0223b931e853f45b4">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a913daba393e21bf5c41fa779116adc3e">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad96f22583acebae0223b931e853f45b4">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56df561875043288046ecddba8ff760c">end</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4ed73aeb19e39514c17dc1b28bad982">print</a> (raw_ostream &amp;OS) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">ArchSetType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1878d88091cac3611694d6af11129b37">ArchSet</a> {0}</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a93b211f78eb5c97ccc38db119ded83">All</a> ()</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> ArchSetType</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a363d8e30356ac12a5aa38cfd720788e7">EndIndexVal</a> = ...</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#ad96f22583acebae0223b931e853f45b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::ArchitectureSet::const_iterator =  arch_iterator&lt;const ArchSetType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

### iterator {#a33ab805f5438911ed1715ce48770c3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::ArchitectureSet::iterator =  arch_iterator&lt;ArchSetType&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Typedefs

### ArchSetType {#a71ee248e0f745cbca34274eea1deb008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::MachO::ArchitectureSet::ArchSetType =  uint32_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ArchitectureSet() {#a6bb196e09fe072c4bdc34adfc63b42bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ArchitectureSet::ArchitectureSet ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Referenced by <a href="#a0a93b211f78eb5c97ccc38db119ded83">All</a>, <a href="#abc2a719d9b757db09497fe21e0086121">ArchitectureSet</a>, <a href="#ac6fff93011d31d541bee7ea83db26f9e">ArchitectureSet</a>, <a href="#a61b1ed15dfe8e9873fdaccc198bb816f">clear</a>, <a href="#a93801a3e0055a049cfd51bbb389ee8d2">contains</a>, <a href="#a9515bea0ef5f9c6f1bee5e44318006ca">operator!=</a>, <a href="#aa74394642228bcc6085fa694a25090cc">operator&amp;</a>, <a href="#ae3f7136edbbd48123675df97f1ccfe4a">operator&lt;</a>, <a href="#a7205bd1cde4ad9b85a9d40ccea7ba92a">operator==</a>, <a href="#adf9fb0ab2f929b888eb8453d77137bc0">operator|</a>, <a href="#aa96c325cfbc8c3a99511fd3984137085">operator|=</a> and <a href="#ace82dba6c30cf706d5a14f065f4fbd2f">operator|=</a>.</p>

</div>
</div>

### ArchitectureSet() {#a059528c4309f5eca68630455c9609cea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ArchitectureSet::ArchitectureSet (ArchSetType Raw)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

### ArchitectureSet() {#abc2a719d9b757db09497fe21e0086121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ArchitectureSet::ArchitectureSet (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>References <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a> and <a href="#a90c084869398bd78ffcc075d52f0efc5">set</a>.</p>

</div>
</div>

### ArchitectureSet() {#ac6fff93011d31d541bee7ea83db26f9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ArchitectureSet::ArchitectureSet (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> &gt; &amp; Archs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>, definition at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/architectureset-cpp">ArchitectureSet.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397a3a18faffa4e9a399fd8bb06731321c83">llvm::MachO::AK_unknown</a>, <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a> and <a href="#a90c084869398bd78ffcc075d52f0efc5">set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator std::string() {#aad0d7b6967bcc3abaf68ce92592ae4a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ArchitectureSet::operator std::string ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>, definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/architectureset-cpp">ArchitectureSet.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab1772fd431decccb7926d484ea223db7">llvm::count</a>, <a href="#aee1b8038a612cd0e8aa65b3e9f5999da">empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a2a0395d53f0485827bc5782c0b64a4e8">llvm::MachO::getArchitectureName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

### operator std::vector&lt; Architecture &gt;() {#a7f2c541a506e6b0cf801e7d1103d5d6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::ArchitectureSet::operator std::vector&lt; Architecture &gt; ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>, definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/architectureset-cpp">ArchitectureSet.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397a3a18faffa4e9a399fd8bb06731321c83">llvm::MachO::AK_unknown</a>.</p>

</div>
</div>

### operator!=() {#a9515bea0ef5f9c6f1bee5e44318006ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ArchitectureSet::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp; o)</td>
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



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>

</div>
</div>

### operator&amp;() {#aa74394642228bcc6085fa694a25090cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet llvm::MachO::ArchitectureSet::operator&amp; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp; o)</td>
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



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>

</div>
</div>

### operator&lt;() {#ae3f7136edbbd48123675df97f1ccfe4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ArchitectureSet::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp; o)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>

</div>
</div>

### operator==() {#a7205bd1cde4ad9b85a9d40ccea7ba92a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ArchitectureSet::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp; o)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>

</div>
</div>

### operator|() {#adf9fb0ab2f929b888eb8453d77137bc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet llvm::MachO::ArchitectureSet::operator| (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp; o)</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>

</div>
</div>

### operator|=() {#ace82dba6c30cf706d5a14f065f4fbd2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet &amp; llvm::MachO::ArchitectureSet::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> &amp; o)</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>

</div>
</div>

### operator|=() {#aa96c325cfbc8c3a99511fd3984137085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet &amp; llvm::MachO::ArchitectureSet::operator|= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> &amp; Arch)</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>References <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a> and <a href="#a90c084869398bd78ffcc075d52f0efc5">set</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#ac41eea11388e27ec261668471f8729ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachO::ArchitectureSet::begin ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

### begin() {#a913daba393e21bf5c41fa779116adc3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachO::ArchitectureSet::begin ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

### clear() {#a61b1ed15dfe8e9873fdaccc198bb816f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet llvm::MachO::ArchitectureSet::clear (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>

</div>
</div>

### contains() {#a93801a3e0055a049cfd51bbb389ee8d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ArchitectureSet::contains (<a href="/web-llvm/docs/api/classes/llvm/macho/architectureset">ArchitectureSet</a> Archs)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a39b8dba7bccde15f5e47e50ba5156c1d">llvm::MachO::Symbol::hasArchitecture</a>.</p>

</div>
</div>

### count() {#abee887b22c8f99f36a1e5c246b6ff8c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::MachO::ArchitectureSet::count ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>, definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/architectureset-cpp">ArchitectureSet.cpp</a>.</p>

</div>
</div>

### empty() {#aee1b8038a612cd0e8aa65b3e9f5999da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ArchitectureSet::empty ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Referenced by <a href="#aad0d7b6967bcc3abaf68ce92592ae4a6">operator std::string</a>.</p>

</div>
</div>

### end() {#aa2fc2e8c2a67bf071850f215c34ef32d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::MachO::ArchitectureSet::end ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

### end() {#a56df561875043288046ecddba8ff760c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::MachO::ArchitectureSet::end ()</td>
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



<p>Definition at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

### has() {#a76b67e4256ae13907721adbb0762ab78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ArchitectureSet::has (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
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



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Referenced by <a href="#ac0dcd9160ac84c61caa4c5b4497f9fe4">hasX86</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/dylibreader/#a1d593efec1083a71925949203aaf6d31">llvm::MachO::DylibReader::readFile</a>, <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile/#a0c83b0802e079f9409f0fd4a18a8a3bf">llvm::MachO::InterfaceFile::targets</a> and <a href="/web-llvm/docs/api/classes/llvm/macho/symbol/#a4ae31734e36e7d641b8f0645f18c792f">llvm::MachO::Symbol::targets</a>.</p>

</div>
</div>

### hasX86() {#ac0dcd9160ac84c61caa4c5b4497f9fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MachO::ArchitectureSet::hasX86 ()</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a76b67e4256ae13907721adbb0762ab78">has</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/textapi/lib/textapi/binaryreader/dylibreader-cpp/#ab42803a7054d1210223d0e72ec575d22">constructTriples</a>.</p>

</div>
</div>

### print() {#ae4ed73aeb19e39514c17dc1b28bad982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::ArchitectureSet::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 163 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/architectureset-cpp">ArchitectureSet.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/macho/#ae8c8b2312cafa12606d53f5748ff0396">llvm::MachO::operator&lt;&lt;</a>.</p>

</div>
</div>

### rawValue() {#a3bc11cab0d6501b39f16f632d30a0437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchSetType llvm::MachO::ArchitectureSet::rawValue ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

### set() {#a90c084869398bd78ffcc075d52f0efc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MachO::ArchitectureSet::set (<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397">Architecture</a> Arch)</td>
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



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a70477e3fc02b7dbfd59604af47d88397a3a18faffa4e9a399fd8bb06731321c83">llvm::MachO::AK_unknown</a>.</p>


<p>Referenced by <a href="#abc2a719d9b757db09497fe21e0086121">ArchitectureSet</a>, <a href="#ac6fff93011d31d541bee7ea83db26f9e">ArchitectureSet</a> and <a href="#aa96c325cfbc8c3a99511fd3984137085">operator|=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ArchSet {#a1878d88091cac3611694d6af11129b37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchSetType llvm::MachO::ArchitectureSet::ArchSet {0}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### All() {#a0a93b211f78eb5c97ccc38db119ded83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchitectureSet llvm::MachO::ArchitectureSet::All ()</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>


<p>Reference <a href="#a6bb196e09fe072c4bdc34adfc63b42bd">ArchitectureSet</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile/#a310e207bf104197229a0a5789e294389">llvm::MachO::InterfaceFile::remove</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### EndIndexVal {#a363d8e30356ac12a5aa38cfd720788e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ArchSetType llvm::MachO::ArchitectureSet::EndIndexVal</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      std::numeric_limits&lt;ArchSetType&gt;<a href="/web-llvm/docs/api/namespaces/llvm/#a003389e30c9b0ec678f95bad1f3dbc4a">::max</a>()
</div>
</dd>
</dl>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/architectureset-h">ArchitectureSet.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/architectureset-cpp">ArchitectureSet.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
