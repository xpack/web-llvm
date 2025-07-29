---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pdb/dbistream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DbiStream` Class



## Declaration

<div class="doxyDeclaration">
class llvm::pdb::DbiStream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">llvm/DebugInfo/PDB/Native/DbiStream.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ff385d39f9ca4b059715f2fbd72cd9">DbiStreamBuilder</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6167c0af6fa7cc91fb9e063806571cdc">DbiStream</a> (std::unique_ptr&lt; BinaryStream &gt; Stream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add51cea7825b9aa5a1368d799489142b">~DbiStream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f720d4ce41d82acda3ab73ee832ca34">reload</a> (PDBFile *Pdb)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a9d89da1d1c09b15fbb63c9c4495c73ad">PdbRaw_DbiVer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c4666e620e0ef37f4e6a5492daab26d">getDbiVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4280ff2b5d6024636bd4cee7f6c96182">getAge</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab70af67262ca01498664f253f56f6402">getPublicSymbolStreamIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a614d2cb7b56ffe9974673d877a518254">getGlobalSymbolStreamIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48f49cc804b7bd8386bc3ac959e482cc">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48d7d70e53ff2a4e06e9aa2b15fa99be">isIncrementallyLinked</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf34d1fe56e00d03d40cda1d86167e20">hasCTypes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a525b36c5372a039c1c07f08c83b3a0c2">isStripped</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80378ba4eee550822faf30d6a81d775f">getBuildNumber</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fbac1324fb4625e0d2b38c7318ebb84">getBuildMajorVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956e097e73327be9c5e4b75fdacfa030">getBuildMinorVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a3f57849f84f69794f6fcc34346928">getPdbDllRbld</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaeef7d69914fedb152819436d854dc9e">getPdbDllVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3312664e914bb377b8343db25047f71">getSymRecordStreamIndex</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1928545fad40360ae644901d7308cbeb">PDB_Machine</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25b67219b7075c2ffa3c3b0d94bffb48">getMachineType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/pdb/dbistreamheader">DbiStreamHeader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d125dd60aebfb8542af66a32a79d2ec">getHeader</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6a82e232c500f82e4a2e8f531b27ad9">getSectionContributionData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2099197beb11e004516ace9f433343f1">getSecMapSubstreamData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc4afccd56ede125e9a4f219da45895">getModiSubstreamData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3948ccb80f6dd803548d56fa0163a6af">getFileInfoSubstreamData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aa352b7cacee2cb5b29937b40857209">getTypeServerMapSubstreamData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8b47a135c584ad11ccb9036a8f9c76">getECSubstreamData</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b6db64c73f202e22852fdd96359ee99">getDebugStreamIndex</a> (DbgHeaderType Type) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If the given stream type is present, returns its stream index. <a href="#a9b6db64c73f202e22852fdd96359ee99">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pdb/dbimodulelist">DbiModuleList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef594440d9d920a9cbf050d24b0493f">modules</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">object::coff_section</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60f47eaf382a1bb984566c18cac330bc">getSectionHeaders</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe22dc011c6740945272609f69e59197">hasOldFpoRecords</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/fpodata">object::FpoData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa638af99fd296bbd5de6db7f12ae9f18">getOldFpoRecords</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d132deb16ebe55f3993219dff0a7cc0">hasNewFpoRecords</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref">codeview::DebugFrameDataSubsectionRef</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a11416a7c33728a3cb95cc1a2e3ae09">getNewFpoRecords</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pdb/secmapentry">SecMapEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67fc502882ac99a5c1a11c7eea9bdee">getSectionMap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40e41bad0c0e6b36ee231fe7d7177521">visitSectionContributions</a> (ISectionContribVisitor &amp;Visitor) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc4bc9a3f883ff0bd08647ac00e9f35">getECName</a> (uint32_t NI) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a696e90292eecca1e54ebe48fc0184a">initializeSectionContributionData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b83a4d5b74b589547828d5dbda78e82">initializeSectionHeadersData</a> (PDBFile *Pdb)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f83a7c73f5589f6a79d3b14bb79d4e">initializeSectionMapData</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8c83cadd9b620f28580fa331b74e618">initializeOldFpoRecords</a> (PDBFile *Pdb)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17ac5a172f5ac9149dafdf3c0bb8d805">initializeNewFpoRecords</a> (PDBFile *Pdb)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">msf::MappedBlockStream</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac03a3f439281383a4384c5c01352b646">createIndexedStreamForHeaderType</a> (PDBFile *Pdb, DbgHeaderType Type) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990755930ac459d2a8caedb0d97d9f9f">Stream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/pdbstringtable">PDBStringTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62dde4500a003030fa162cb900d2958a">ECNames</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd45f76eac1d40c20a8d463a0b375e67">SecContrSubstream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66d0ad1b134957cc645fc7537b724ad6">SecMapSubstream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae433714447f0b55f0f3afbfc3026378c">ModiSubstream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4165b732e03fda6484c33be3fd0323">FileInfoSubstream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a983a0e69a61dad0de4d48fcfddb675e3">TypeServerMapSubstream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/binarysubstreamref">BinarySubstreamRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fbdcd4f5544e8803481c89ded9c2bc1">ECSubstream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pdb/dbimodulelist">DbiModuleList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac740e49ddda50f747c86778775a76b5d">Modules</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/support/#a4e29b3df92632c930b82161555c3b8d6">support::ulittle16_t</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5adf54e9958314ba48830d7e1f35643">DbgStreams</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae225e561af00d197a94010952d536a8b">PdbRaw_DbiSecContribVer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995b5d677a667f5b726facaaebde3118">SectionContribVersion</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pdb/sectioncontrib">SectionContrib</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a113359a027a143c1dc5caa14a3306c42">SectionContribs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pdb/sectioncontrib2">SectionContrib2</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e85efb1c7c3d01eff9e473d35e28b0">SectionContribs2</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pdb/secmapentry">SecMapEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a507bd4d1d92135da9269ba3d9c7481fc">SectionMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">msf::MappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44c11cf215311801910a8ae959aab9a4">SectionHeaderStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/coff-section">object::coff_section</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a365114678e8815ac7ae9fbf0a874c9d4">SectionHeaders</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">msf::MappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65fa0d94fb6a6d3a2542487ca81fcc9f">OldFpoStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fixedstreamarray">FixedStreamArray</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/object/fpodata">object::FpoData</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5007bb73a6046b03ef699b7959571947">OldFpoRecords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/msf/mappedblockstream">msf::MappedBlockStream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9198efe3dc727c588c11e61a809afb">NewFpoStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/codeview/debugframedatasubsectionref">codeview::DebugFrameDataSubsectionRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9df1c79c2f53e2cb86e98c9ab1890153">NewFpoRecords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/pdb/dbistreamheader">DbiStreamHeader</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a923754d365ba9f5b3d6e377206a201fb">Header</a></td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>


<div class="doxySectionDef">

## Friends

### DbiStreamBuilder {#ab7ff385d39f9ca4b059715f2fbd72cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/pdb/dbistreambuilder">DbiStreamBuilder</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>


<p>Reference <a href="#ab7ff385d39f9ca4b059715f2fbd72cd9">DbiStreamBuilder</a>.</p>


<p>Referenced by <a href="#ab7ff385d39f9ca4b059715f2fbd72cd9">DbiStreamBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DbiStream() {#a6167c0af6fa7cc91fb9e063806571cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbiStream::DbiStream (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/binarystream">BinaryStream</a> &gt; Stream)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DbiStream() {#add51cea7825b9aa5a1368d799489142b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbiStream::~DbiStream ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAge() {#a4280ff2b5d6024636bd4cee7f6c96182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DbiStream::getAge ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getBuildMajorVersion() {#a5fbac1324fb4625e0d2b38c7318ebb84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DbiStream::getBuildMajorVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/pdb/dbibuildno/#a65141d899c90b92961a249bc288a3bd7">llvm::pdb::DbiBuildNo::BuildMajorMask</a> and <a href="/web-llvm/docs/api/structs/llvm/pdb/dbibuildno/#a2d5ecb5a9cd54f1a55ee2d2eaf6846f8">llvm::pdb::DbiBuildNo::BuildMajorShift</a>.</p>

</div>
</div>

### getBuildMinorVersion() {#a956e097e73327be9c5e4b75fdacfa030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DbiStream::getBuildMinorVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 181 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/pdb/dbibuildno/#a87e7ab03bf11c9c6a4490a6db221efb4">llvm::pdb::DbiBuildNo::BuildMinorMask</a> and <a href="/web-llvm/docs/api/structs/llvm/pdb/dbibuildno/#ae6450e62c612ad05b0484a939b787674">llvm::pdb::DbiBuildNo::BuildMinorShift</a>.</p>

</div>
</div>

### getBuildNumber() {#a80378ba4eee550822faf30d6a81d775f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DbiStream::getBuildNumber ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getDbiVersion() {#a4c4666e620e0ef37f4e6a5492daab26d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PdbRaw_DbiVer DbiStream::getDbiVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getDebugStreamIndex() {#a9b6db64c73f202e22852fdd96359ee99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DbiStream::getDebugStreamIndex (<a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a81a0fae24e6bdfe240da4249a8da5978">DbgHeaderType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If the given stream type is present, returns its stream index.</p>


<p>If it is not present, returns InvalidStreamIndex.</p>


<p>Declaration at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 376 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a0a7a9a9849fa2f1e5dec7a99ba9530da">llvm::pdb::kInvalidStreamIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a952cb7401a07c49e2879fbfc92f0dc2caa1fa27779242b4902f7ae3bdd5c6d508">llvm::pdb::Type</a>.</p>

</div>
</div>

### getECName() {#a1cc4bc9a3f883ff0bd08647ac00e9f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; DbiStream::getECName (uint32_t NI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getECSubstreamData() {#abc8b47a135c584ad11ccb9036a8f9c76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef DbiStream::getECSubstreamData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getFileInfoSubstreamData() {#a3948ccb80f6dd803548d56fa0163a6af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef DbiStream::getFileInfoSubstreamData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getFlags() {#a48f49cc804b7bd8386bc3ac959e482cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DbiStream::getFlags ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getGlobalSymbolStreamIndex() {#a614d2cb7b56ffe9974673d877a518254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DbiStream::getGlobalSymbolStreamIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getHeader() {#a7d125dd60aebfb8542af66a32a79d2ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DbiStreamHeader * llvm::pdb::DbiStream::getHeader ()</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### getMachineType() {#a25b67219b7075c2ffa3c3b0d94bffb48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDB_Machine DbiStream::getMachineType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 194 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#a2e16e55de32fe349f3e8242166918205">Machine</a>.</p>

</div>
</div>

### getModiSubstreamData() {#a7bc4afccd56ede125e9a4f219da45895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef DbiStream::getModiSubstreamData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getNewFpoRecords() {#a8a11416a7c33728a3cb95cc1a2e3ae09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DebugFrameDataSubsectionRef &amp; DbiStream::getNewFpoRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 211 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getOldFpoRecords() {#aa638af99fd296bbd5de6db7f12ae9f18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt; object::FpoData &gt; DbiStream::getOldFpoRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getPdbDllRbld() {#ae2a3f57849f84f69794f6fcc34346928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DbiStream::getPdbDllRbld ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 186 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getPdbDllVersion() {#aaeef7d69914fedb152819436d854dc9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DbiStream::getPdbDllVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getPublicSymbolStreamIndex() {#ab70af67262ca01498664f253f56f6402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t DbiStream::getPublicSymbolStreamIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getSecMapSubstreamData() {#a2099197beb11e004516ace9f433343f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef DbiStream::getSecMapSubstreamData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getSectionContributionData() {#af6a82e232c500f82e4a2e8f531b27ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef DbiStream::getSectionContributionData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getSectionHeaders() {#a60f47eaf382a1bb984566c18cac330bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt; object::coff_section &gt; DbiStream::getSectionHeaders ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getSectionMap() {#af67fc502882ac99a5c1a11c7eea9bdee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt; SecMapEntry &gt; DbiStream::getSectionMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getSymRecordStreamIndex() {#ab3312664e914bb377b8343db25047f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DbiStream::getSymRecordStreamIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 190 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### getTypeServerMapSubstreamData() {#a7aa352b7cacee2cb5b29937b40857209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef DbiStream::getTypeServerMapSubstreamData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 357 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### hasCTypes() {#acf34d1fe56e00d03d40cda1d86167e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DbiStream::hasCTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/pdb/dbiflags/#a9e36d80fe59f6aaa651f2bd68fe2f345">llvm::pdb::DbiFlags::FlagHasCTypesMask</a>.</p>

</div>
</div>

### hasNewFpoRecords() {#a5d132deb16ebe55f3993219dff0a7cc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DbiStream::hasNewFpoRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### hasOldFpoRecords() {#afe22dc011c6740945272609f69e59197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DbiStream::hasOldFpoRecords ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### isIncrementallyLinked() {#a48d7d70e53ff2a4e06e9aa2b15fa99be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DbiStream::isIncrementallyLinked ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 162 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/pdb/dbiflags/#a117c4b4235ca4046c53fbb4eb594e5f8">llvm::pdb::DbiFlags::FlagIncrementalMask</a>.</p>

</div>
</div>

### isStripped() {#a525b36c5372a039c1c07f08c83b3a0c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DbiStream::isStripped ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/pdb/dbiflags/#ae1d275dd7e047341a13332256c231d19">llvm::pdb::DbiFlags::FlagStrippedMask</a>.</p>

</div>
</div>

### modules() {#a7ef594440d9d920a9cbf050d24b0493f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DbiModuleList &amp; DbiStream::modules ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a4ea0a9908bf44e213edb07fb04ab0240">llvm::pdb::getModuleDebugStream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#af1896eb50b6f562b62e975912f7e146c">llvm::pdb::getModuleDebugStream</a>.</p>

</div>
</div>

### reload() {#a6f720d4ce41d82acda3ab73ee832ca34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DbiStream::reload (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> * Pdb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 50 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a81b49f753bf7db44da6cf4b0fc59b76e">llvm::BinaryStreamReader::bytesRemaining</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a573bcbbea76b4d72b33de1e392cc14aea8c4fdeb9f0256322a364cd1347a6ffd6">llvm::pdb::corrupt_file</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a2e1cbb0e2bd7a35ed99c31853dc45374a3fd6b696867d70225deda7868308679b">llvm::codeview::EC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a573bcbbea76b4d72b33de1e392cc14aea42ca91a8fe91a5b02e36a30dd17355e7">llvm::pdb::feature_unsupported</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#af483a6f5695bfa37be36c56ad2f175b6ab693cea68a050d89a00c376652df1c5e">llvm::codeview::Pdb</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a9d89da1d1c09b15fbb63c9c4495c73ada42ab070cbc19b59670096fe59b55f3fe">llvm::pdb::PdbDbiV70</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#ab88a8b3835c1028f8fd6c2b23f396d30">llvm::BinaryStreamReader::readArray</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a07e25e055f92f545f94821c4a3cbded8">llvm::BinaryStreamReader::readObject</a>, <a href="/web-llvm/docs/api/classes/llvm/binarystreamreader/#a520983e8f7f744a446b4b6501d6ccb03">llvm::BinaryStreamReader::readSubstream</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### visitSectionContributions() {#a40e41bad0c0e6b36ee231fe7d7177521}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DbiStream::visitSectionContributions (<a href="/web-llvm/docs/api/classes/llvm/pdb/isectioncontribvisitor">ISectionContribVisitor</a> &amp; Visitor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae225e561af00d197a94010952d536a8ba6cf96f596d3629bb03ae180a52aabc8e">llvm::pdb::DbiSecContribV2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae225e561af00d197a94010952d536a8ba3c20f691ca79ecef5c928453bca77605">llvm::pdb::DbiSecContribVer60</a> and <a href="/web-llvm/docs/api/classes/llvm/pdb/isectioncontribvisitor/#a895119a5ce53fe129103d3503ee06319">llvm::pdb::ISectionContribVisitor::visit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createIndexedStreamForHeaderType() {#ac03a3f439281383a4384c5c01352b646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; msf::MappedBlockStream &gt; &gt; DbiStream::createIndexedStreamForHeaderType (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> * Pdb, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a81a0fae24e6bdfe240da4249a8da5978">DbgHeaderType</a> Type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### initializeNewFpoRecords() {#a17ac5a172f5ac9149dafdf3c0bb8d805}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DbiStream::initializeNewFpoRecords (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> * Pdb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 306 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### initializeOldFpoRecords() {#ae8c83cadd9b620f28580fa331b74e618}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DbiStream::initializeOldFpoRecords (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> * Pdb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### initializeSectionContributionData() {#a6a696e90292eecca1e54ebe48fc0184a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DbiStream::initializeSectionContributionData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 238 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### initializeSectionHeadersData() {#a9b83a4d5b74b589547828d5dbda78e82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DbiStream::initializeSectionHeadersData (<a href="/web-llvm/docs/api/classes/llvm/pdb/pdbfile">PDBFile</a> * Pdb)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

### initializeSectionMapData() {#a55f83a7c73f5589f6a79d3b14bb79d4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error DbiStream::initializeSectionMapData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DbgStreams {#ac5adf54e9958314ba48830d7e1f35643}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt;support::ulittle16_t&gt; llvm::pdb::DbiStream::DbgStreams</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### ECNames {#a62dde4500a003030fa162cb900d2958a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PDBStringTable llvm::pdb::DbiStream::ECNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### ECSubstream {#a3fbdcd4f5544e8803481c89ded9c2bc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::pdb::DbiStream::ECSubstream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### FileInfoSubstream {#afd4165b732e03fda6484c33be3fd0323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::pdb::DbiStream::FileInfoSubstream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### Header {#a923754d365ba9f5b3d6e377206a201fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DbiStreamHeader* llvm::pdb::DbiStream::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### ModiSubstream {#ae433714447f0b55f0f3afbfc3026378c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::pdb::DbiStream::ModiSubstream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### Modules {#ac740e49ddda50f747c86778775a76b5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DbiModuleList llvm::pdb::DbiStream::Modules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### NewFpoRecords {#a9df1c79c2f53e2cb86e98c9ab1890153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">codeview::DebugFrameDataSubsectionRef llvm::pdb::DbiStream::NewFpoRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### NewFpoStream {#afe9198efe3dc727c588c11e61a809afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;msf::MappedBlockStream&gt; llvm::pdb::DbiStream::NewFpoStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### OldFpoRecords {#a5007bb73a6046b03ef699b7959571947}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt;object::FpoData&gt; llvm::pdb::DbiStream::OldFpoRecords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### OldFpoStream {#a65fa0d94fb6a6d3a2542487ca81fcc9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;msf::MappedBlockStream&gt; llvm::pdb::DbiStream::OldFpoStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SecContrSubstream {#acd45f76eac1d40c20a8d463a0b375e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::pdb::DbiStream::SecContrSubstream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SecMapSubstream {#a66d0ad1b134957cc645fc7537b724ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::pdb::DbiStream::SecMapSubstream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SectionContribs {#a113359a027a143c1dc5caa14a3306c42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt;SectionContrib&gt; llvm::pdb::DbiStream::SectionContribs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SectionContribs2 {#a57e85efb1c7c3d01eff9e473d35e28b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt;SectionContrib2&gt; llvm::pdb::DbiStream::SectionContribs2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SectionContribVersion {#a995b5d677a667f5b726facaaebde3118}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PdbRaw_DbiSecContribVer llvm::pdb::DbiStream::SectionContribVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
      <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ae225e561af00d197a94010952d536a8ba3c20f691ca79ecef5c928453bca77605">PdbRaw_DbiSecContribVer::DbiSecContribVer60</a>
</div>
</dd>
</dl>

<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SectionHeaders {#a365114678e8815ac7ae9fbf0a874c9d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt;object::coff_section&gt; llvm::pdb::DbiStream::SectionHeaders</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SectionHeaderStream {#a44c11cf215311801910a8ae959aab9a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;msf::MappedBlockStream&gt; llvm::pdb::DbiStream::SectionHeaderStream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### SectionMap {#a507bd4d1d92135da9269ba3d9c7481fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FixedStreamArray&lt;SecMapEntry&gt; llvm::pdb::DbiStream::SectionMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### Stream {#a990755930ac459d2a8caedb0d97d9f9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;BinaryStream&gt; llvm::pdb::DbiStream::Stream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

### TypeServerMapSubstream {#a983a0e69a61dad0de4d48fcfddb675e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BinarySubstreamRef llvm::pdb::DbiStream::TypeServerMapSubstream</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/dbistream-h">DbiStream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/dbistream-cpp">DbiStream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
