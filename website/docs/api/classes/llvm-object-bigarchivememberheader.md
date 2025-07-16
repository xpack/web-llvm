---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/bigarchivememberheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BigArchiveMemberHeader` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::BigArchiveMemberHeader { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae54b3190e013b4c17e9dd0e82fb8ec2e">BigArchiveMemberHeader</a> (Archive const *Parent, const char *RawHeaderPtr, uint64_t Size, Error *Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d0da9ed9aaccf83e7218decb0de0d74">clone</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dee83379cd715e24ccdec554331a3cf">getRawName</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name without looking up long names. <a href="#a1dee83379cd715e24ccdec554331a3cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa12e214fe9eef659a3935afbac7b05fb">getRawNameSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67ae2591ee5b082cdc8517169e663e38">getName</a> (uint64_t Size) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name looking up long names. <a href="#a67ae2591ee5b082cdc8517169e663e38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fbab288c38cba1ba49b9093ce87995">getSize</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ac0ddcf418dd66efde6cb208755629f">getNextChildLoc</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get next file member location. <a href="#a5ac0ddcf418dd66efde6cb208755629f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfe40bee08ac4f93c61808e0aa9e3308">getNextOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37c2e031a736a383be8c66f292700f83">isThin</a> () const override</td>
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


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BigArchiveMemberHeader() {#ae54b3190e013b4c17e9dd0e82fb8ec2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BigArchiveMemberHeader::BigArchiveMemberHeader (<a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * RawHeaderPtr, uint64_t Size, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a672e18a663388332797a2573fa7c09e8">llvm::object::CommonArchiveMemberHeader&lt; BigArMemHdrType &gt;::CommonArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a6924fc0f14382098122afbc64ea239e8">llvm::object::CommonArchiveMemberHeader&lt; BigArMemHdrType &gt;::getSizeOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#a4d0da9ed9aaccf83e7218decb0de0d74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; AbstractArchiveMemberHeader &gt; llvm::object::BigArchiveMemberHeader::clone ()</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getName() {#a67ae2591ee5b082cdc8517169e663e38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; BigArchiveMemberHeader::getName (uint64_t Size)</td>
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

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 352 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="#a1dee83379cd715e24ccdec554331a3cf">getRawName</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### getNextChildLoc() {#a5ac0ddcf418dd66efde6cb208755629f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; const char * &gt; BigArchiveMemberHeader::getNextChildLoc ()</td>
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

<p>Declaration at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#adfe40bee08ac4f93c61808e0aa9e3308">getNextOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a6f0d33d445775adb00017f7c7e49d230">llvm::object::CommonArchiveMemberHeader&lt; BigArMemHdrType &gt;::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getNextOffset() {#adfe40bee08ac4f93c61808e0aa9e3308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; BigArchiveMemberHeader::getNextOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; BigArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a> and <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>.</p>


<p>Referenced by <a href="#a5ac0ddcf418dd66efde6cb208755629f">getNextChildLoc</a>.</p>

</div>
</div>

### getRawName() {#a1dee83379cd715e24ccdec554331a3cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; BigArchiveMemberHeader::getRawName ()</td>
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

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; BigArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#aca439bf65258d9d8d057812938b617c5">llvm::StringRef::ends_with</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a67ae2591ee5b082cdc8517169e663e38">getName</a>.</p>

</div>
</div>

### getRawNameSize() {#aa12e214fe9eef659a3935afbac7b05fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; BigArchiveMemberHeader::getRawNameSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; BigArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a> and <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a>.</p>


<p>Referenced by <a href="#a19fbab288c38cba1ba49b9093ce87995">getSize</a>.</p>

</div>
</div>

### getSize() {#a19fbab288c38cba1ba49b9093ce87995}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; BigArchiveMemberHeader::getSize ()</td>
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



<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 361 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#afdfe45995438fba3926e33853fc9c1e6">llvm::object::CommonArchiveMemberHeader&lt; BigArMemHdrType &gt;::ArMemHdr</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a896c0342b10ed46345456bd263e5a7ae">getFieldRawString</a>, <a href="#aa12e214fe9eef659a3935afbac7b05fb">getRawNameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader/#a0215baac13e6c4d987e67335d81dc29b">llvm::object::AbstractArchiveMemberHeader::Parent</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### isThin() {#a37c2e031a736a383be8c66f292700f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; llvm::object::BigArchiveMemberHeader::isThin ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

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
