---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/archivememberheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ArchiveMemberHeader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::ArchiveMemberHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader">CommonArchiveMemberHeader&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0906254a905f4d1c0a68dd54c3eb65e8">ArchiveMemberHeader</a> (const Archive *Parent, const char *RawHeaderPtr, uint64_t Size, Error *Err)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader">AbstractArchiveMemberHeader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38428db2247ba834aa62f7dbbe73a64e">clone</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a990a2cc1b018140f8dde6e1a8ad42182">getRawName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name without looking up long names. <a href="#a990a2cc1b018140f8dde6e1a8ad42182">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940c0b94e9bb9dfdb69961d456b47b60">getName</a> (uint64_t Size) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name looking up long names. <a href="#a940c0b94e9bb9dfdb69961d456b47b60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace1855f7759a2a9be5299cdecc51c477">getSize</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d86083ac823979ed30663f9d87118d">getNextChildLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get next file member location. <a href="#ae1d86083ac823979ed30663f9d87118d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa954ca2029479568fc22ecd2c427c4a2">isThin</a> () const override</td>
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


<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ArchiveMemberHeader() {#a0906254a905f4d1c0a68dd54c3eb65e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArchiveMemberHeader::ArchiveMemberHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RawHeaderPtr, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a672e18a663388332797a2573fa7c09e8">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::CommonArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a940c0b94e9bb9dfdb69961d456b47b60">getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a6924fc0f14382098122afbc64ea239e8">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::getSizeOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a38428db2247ba834aa62f7dbbe73a64e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AbstractArchiveMemberHeader &gt; llvm::object::ArchiveMemberHeader::clone ()</td>
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



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getName() {#a940c0b94e9bb9dfdb69961d456b47b60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; ArchiveMemberHeader::getName (uint64_t Size)</td>
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

<p>Get the name looking up long names.</p>

<p>Declaration at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a520bdf57dfe3e73abb53d482893f0a27">llvm::raw_ostream::flush</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a990a2cc1b018140f8dde6e1a8ad42182">getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a6924fc0f14382098122afbc64ea239e8">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::getSizeOf</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a63a070d89ebf9a74c22a38ec25719ae7">llvm::object::Archive::K_GNU</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87af59b87258f3f4e04b99d21c79bdd7c20">llvm::object::Archive::K_GNU64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a9b52404a8d2877d3b32ebb5d1f5c72ff">llvm::StringRef::rtrim</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a5ba2ece4b959bae02752c34b784ba087">llvm::raw_ostream::write_escaped</a>.</p>


<p>Referenced by <a href="#a0906254a905f4d1c0a68dd54c3eb65e8">ArchiveMemberHeader</a>.</p>

</div>
</div>

### getNextChildLoc() {#ae1d86083ac823979ed30663f9d87118d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const char * &gt; ArchiveMemberHeader::getNextChildLoc ()</td>
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

<p>Get next file member location.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#ace1855f7759a2a9be5299cdecc51c477">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a6924fc0f14382098122afbc64ea239e8">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::getSizeOf</a>, <a href="#aa954ca2029479568fc22ecd2c427c4a2">isThin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getRawName() {#a990a2cc1b018140f8dde6e1a8ad42182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; ArchiveMemberHeader::getRawName ()</td>
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

<p>Get the name without looking up long names.</p>

<p>Declaration at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 154 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aab312a8386488873bac2eddfc67c22be">llvm::StringRef::find</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a769a0d23f23121590187fb224cfa650f">llvm::object::Archive::K_BSD</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87ad2085dbd9869a86d285bec7525920d8a">llvm::object::Archive::K_DARWIN64</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#ad0f54a163ac500b144590640c6f1eb6b">llvm::StringRef::npos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>.</p>


<p>Referenced by <a href="#a940c0b94e9bb9dfdb69961d456b47b60">getName</a> and <a href="#aa954ca2029479568fc22ecd2c427c4a2">isThin</a>.</p>

</div>
</div>

### getSize() {#ace1855f7759a2a9be5299cdecc51c477}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; ArchiveMemberHeader::getSize ()</td>
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



<p>Declaration at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; UnixArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a> and <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>.</p>


<p>Referenced by <a href="#ae1d86083ac823979ed30663f9d87118d">getNextChildLoc</a>.</p>

</div>
</div>

### isThin() {#aa954ca2029479568fc22ecd2c427c4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; ArchiveMemberHeader::isThin ()</td>
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



<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a990a2cc1b018140f8dde6e1a8ad42182">getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#ae1d86083ac823979ed30663f9d87118d">getNextChildLoc</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
