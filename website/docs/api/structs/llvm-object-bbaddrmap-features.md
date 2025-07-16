---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/object/bbaddrmap/features
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Features` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::object::BBAddrMap::Features { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">llvm/Object/ELFTypes.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3277d6e3f793f75749a3e8e35a3e61e6">operator==</a> (const Features &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef7bccc1db668aa9abb930f178a18b72">hasPGOAnalysis</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaeb4229fc1216616fe0908396f99162">hasPGOAnalysisBBData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670079ad2ab670f54d7489b902c853ac">encode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcce893abd5c350d05392295509ad360">FuncEntryCount</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24efbea1211f48f81b01b2605459f264">BBFreq</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a650eb6981dfff7bc28bc72a8bf98596f">BrProb</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fe191b46a8e47bba3f14b26f6167f28">MultiBBRange</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64366ab8032082e6fa7133e94a294013">OmitBBEntries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features">Features</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5237f92a42dcf07815d67e912fb9c9">decode</a> (uint8_t Val)</td>
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


<p>Definition at line 828 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a3277d6e3f793f75749a3e8e35a3e61e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/object/bbaddrmap/features">Features</a> &amp; Other)</td>
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



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>References <a href="#a24efbea1211f48f81b01b2605459f264">BBFreq</a>, <a href="#a650eb6981dfff7bc28bc72a8bf98596f">BrProb</a>, <a href="#abcce893abd5c350d05392295509ad360">FuncEntryCount</a>, <a href="#a4fe191b46a8e47bba3f14b26f6167f28">MultiBBRange</a>, <a href="#a64366ab8032082e6fa7133e94a294013">OmitBBEntries</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### encode() {#a670079ad2ab670f54d7489b902c853ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::object::BBAddrMap::Features::encode ()</td>
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



<p>Definition at line 840 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>References <a href="#a24efbea1211f48f81b01b2605459f264">BBFreq</a>, <a href="#a650eb6981dfff7bc28bc72a8bf98596f">BrProb</a>, <a href="#abcce893abd5c350d05392295509ad360">FuncEntryCount</a>, <a href="#a4fe191b46a8e47bba3f14b26f6167f28">MultiBBRange</a> and <a href="#a64366ab8032082e6fa7133e94a294013">OmitBBEntries</a>.</p>


<p>Referenced by <a href="#ada5237f92a42dcf07815d67e912fb9c9">decode</a>.</p>

</div>
</div>

### hasPGOAnalysis() {#aef7bccc1db668aa9abb930f178a18b72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::hasPGOAnalysis ()</td>
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



<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>References <a href="#a24efbea1211f48f81b01b2605459f264">BBFreq</a>, <a href="#a650eb6981dfff7bc28bc72a8bf98596f">BrProb</a> and <a href="#abcce893abd5c350d05392295509ad360">FuncEntryCount</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>.</p>

</div>
</div>

### hasPGOAnalysisBBData() {#abaeb4229fc1216616fe0908396f99162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::hasPGOAnalysisBBData ()</td>
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



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>References <a href="#a24efbea1211f48f81b01b2605459f264">BBFreq</a> and <a href="#a650eb6981dfff7bc28bc72a8bf98596f">BrProb</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BBFreq {#a24efbea1211f48f81b01b2605459f264}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::BBFreq</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#a670079ad2ab670f54d7489b902c853ac">encode</a>, <a href="#aef7bccc1db668aa9abb930f178a18b72">hasPGOAnalysis</a>, <a href="#abaeb4229fc1216616fe0908396f99162">hasPGOAnalysisBBData</a> and <a href="#a3277d6e3f793f75749a3e8e35a3e61e6">operator==</a>.</p>

</div>
</div>

### BrProb {#a650eb6981dfff7bc28bc72a8bf98596f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::BrProb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#a670079ad2ab670f54d7489b902c853ac">encode</a>, <a href="#aef7bccc1db668aa9abb930f178a18b72">hasPGOAnalysis</a>, <a href="#abaeb4229fc1216616fe0908396f99162">hasPGOAnalysisBBData</a> and <a href="#a3277d6e3f793f75749a3e8e35a3e61e6">operator==</a>.</p>

</div>
</div>

### FuncEntryCount {#abcce893abd5c350d05392295509ad360}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::FuncEntryCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#a670079ad2ab670f54d7489b902c853ac">encode</a>, <a href="#aef7bccc1db668aa9abb930f178a18b72">hasPGOAnalysis</a> and <a href="#a3277d6e3f793f75749a3e8e35a3e61e6">operator==</a>.</p>

</div>
</div>

### MultiBBRange {#a4fe191b46a8e47bba3f14b26f6167f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::MultiBBRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#a670079ad2ab670f54d7489b902c853ac">encode</a> and <a href="#a3277d6e3f793f75749a3e8e35a3e61e6">operator==</a>.</p>

</div>
</div>

### OmitBBEntries {#a64366ab8032082e6fa7133e94a294013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::BBAddrMap::Features::OmitBBEntries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>, <a href="#a670079ad2ab670f54d7489b902c853ac">encode</a> and <a href="#a3277d6e3f793f75749a3e8e35a3e61e6">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decode() {#ada5237f92a42dcf07815d67e912fb9c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Features &gt; llvm::object::BBAddrMap::Features::decode (uint8_t Val)</td>
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



<p>Definition at line 850 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="#a670079ad2ab670f54d7489b902c853ac">encode</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/elf-cpp/#ab230da2e143b2070f404fea9287e4ed9">decodeBBAddrMapImpl</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/elftypes-h">ELFTypes.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
