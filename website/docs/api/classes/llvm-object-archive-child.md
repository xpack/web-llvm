---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/archive/child
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Child` Class



## Declaration

<div class="doxyDeclaration">
class llvm::object::Archive::Child { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9537162135cca043a3b82f0df2816ed7">Child</a> (const Archive *Parent, const char *Start, Error *Err)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5edeef2b11493696c58676b48291fd32">Child</a> (const Archive *Parent, StringRef Data, uint16_t StartOfFile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3f3b3abfbc09ae94e9469b5875f3943">Child</a> (const Child &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc44f31712a5c98532f1b8acf49218b3">Child</a> (Child &amp;&amp;C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13536751052c3b3cab6ef09803fc603">operator=</a> (Child &amp;&amp;C) noexcept</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a587b2803cc38fa645cef1af5cff24d37">operator=</a> (const Child &amp;C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b0a7624e9e8209f9bef0f5e227b6eaf">operator==</a> (const Child &amp;other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac89b2f5f9a092793db6d9b5692fdcd08">getParent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a137ad5829c3f2470a0da63800c59385e">getNext</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3acd0fa308c00ead51dc16b4d46604bc">getName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ece0b78ccffb215a68d44b94b46e2f">getFullName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f5f4cc94a06322f5be047c398bc5e34">getRawName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a52f2c3fdd7f80c1991d8c7079489efff">sys::TimePoint</a>&lt; std::chrono::seconds &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abea74633b8c0af7cb53addc66ce55ec1">getLastModified</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1065e08cfcfc167515f06a8d397e40c1">getRawLastModified</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f4f1c730ddfa9b53bed05548b656fa">getUID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5cbd281cdf1331330da601c219e452e9">getGID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#ac56b6ec1078927bdd9b65f7ba8fbda82">sys::fs::perms</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8e1ab8fcc1aa249d1c6a01a263ef303">getAccessMode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470c8d3fb44a1233ee5fe50fd5ce0304">getSize</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3125cc2c2f3101a53e90173312fc4554">getRawSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03bfd76bddfe1a42326e93dc3c131c8c">getBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309631f432f58bf4c6f171b73330512f">getChildOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9f4321493aa94a53f9e3770a11a93c">getDataOffset</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fa0bfbc8489a0b3472e2dd834e03c80">getMemoryBufferRef</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/binary">Binary</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e08f334d391b4c5c327739f3e460465">getAsBinary</a> (LLVMContext *Context=nullptr) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a240d2598d6b251f95aa0d68657ece3c0">isThinMember</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a212dc0a4d2da50c9300f418ae9017c4b">Archive</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">friend</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcfe95d361dd817f614a9bd4ef5e4a58">AbstractArchiveMemberHeader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d94f63a838183dc5bc5fc9da2244e6e">Parent</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/object/abstractarchivememberheader">AbstractArchiveMemberHeader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f8e54bc6f82d97ade6ff81ff2a1f9b">Header</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5334d6b6d8171c9ee8fb27c64ffb063c">Data</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Includes header but not padding byte. <a href="#a5334d6b6d8171c9ee8fb27c64ffb063c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2f268933c4afca40dc1c5a735b54b3b">StartOfFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset from Data to the start of the file. <a href="#ac2f268933c4afca40dc1c5a735b54b3b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Child() {#a9537162135cca043a3b82f0df2816ed7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::Child::Child (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> * Parent, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Start, <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> * Err)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 467 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a1881146f2dcc2ca57c9c5f77f938db9d">llvm::StringRef::getAsInteger</a>, <a href="#a6f5f4cc94a06322f5be047c398bc5e34">getRawName</a>, <a href="#a3125cc2c2f3101a53e90173312fc4554">getRawSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a0a831e9d8a13d29158e9607b50e46b9b">llvm::object::Archive::isThin</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#ab288378fa8bfa0678dd25e36b5198a87a1ce3ba6f0ac952cb8105e17115093810">llvm::object::Archive::K_AIXBIG</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/xcoff/#a9a03aac7419558e56bd606aeab244118">llvm::XCOFF::NameSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#acc44f31712a5c98532f1b8acf49218b3">Child</a>, <a href="#ad3f3b3abfbc09ae94e9469b5875f3943">Child</a>, <a href="#a137ad5829c3f2470a0da63800c59385e">getNext</a>, <a href="#aa13536751052c3b3cab6ef09803fc603">operator=</a>, <a href="#a587b2803cc38fa645cef1af5cff24d37">operator=</a> and <a href="#a1b0a7624e9e8209f9bef0f5e227b6eaf">operator==</a>.</p>

</div>
</div>

### Child() {#a5edeef2b11493696c58676b48291fd32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Archive::Child::Child (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> * Parent, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Data, uint16_t StartOfFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>

</div>
</div>

### Child() {#ad3f3b3abfbc09ae94e9469b5875f3943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::Archive::Child::Child (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp; C)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a>.</p>

</div>
</div>

### Child() {#acc44f31712a5c98532f1b8acf49218b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::Archive::Child::Child (<a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp;&amp; C)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aa13536751052c3b3cab6ef09803fc603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Child &amp; llvm::object::Archive::Child::operator= (<a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp;&amp; C)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a>.</p>

</div>
</div>

### operator=() {#a587b2803cc38fa645cef1af5cff24d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Child &amp; llvm::object::Archive::Child::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp; C)</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a>.</p>

</div>
</div>

### operator==() {#a1b0a7624e9e8209f9bef0f5e227b6eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::object::Archive::Child::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive/child">Child</a> &amp; other)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a> and <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAccessMode() {#ab8e1ab8fcc1aa249d1c6a01a263ef303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; sys::fs::perms &gt; llvm::object::Archive::Child::getAccessMode ()</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>.</p>

</div>
</div>

### getAsBinary() {#a7e08f334d391b4c5c327739f3e460465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Binary &gt; &gt; Archive::Child::getAsBinary (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> * Context=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/object/#aebd3886db896c46327320cfd1ccc808c">llvm::object::createBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/object/binary/#ac0322f1809be8f6f88af125c1956c9a1">llvm::object::Binary::getMemoryBufferRef</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getBuffer() {#a03bfd76bddfe1a42326e93dc3c131c8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; Archive::Child::getBuffer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 572 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="#a22ece0b78ccffb215a68d44b94b46e2f">getFullName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xtensa/lib/target/xtensa/mctargetdesc/xtensaasmbackend-cpp/#a13a0babfc55adc9b798c39e65ec9e8a3">getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a0a831e9d8a13d29158e9607b50e46b9b">llvm::object::Archive::isThin</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a7fa0bfbc8489a0b3472e2dd834e03c80">getMemoryBufferRef</a>.</p>

</div>
</div>

### getChildOffset() {#a309631f432f58bf4c6f171b73330512f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t Archive::Child::getChildOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 625 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>Referenced by <a href="#a6e9f4321493aa94a53f9e3770a11a93c">getDataOffset</a>.</p>

</div>
</div>

### getDataOffset() {#a6e9f4321493aa94a53f9e3770a11a93c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::object::Archive::Child::getDataOffset ()</td>
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



<p>Definition at line 249 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="#a309631f432f58bf4c6f171b73330512f">getChildOffset</a>.</p>

</div>
</div>

### getFullName() {#a22ece0b78ccffb215a68d44b94b46e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::string &gt; Archive::Child::getFullName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 554 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#acb80894344c78dacf8d5ff8c23be697d">llvm::sys::path::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#ac35ec1dacb408d4c65d55249c0e02474">llvm::sys::path::is_absolute</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archive/#a0a831e9d8a13d29158e9607b50e46b9b">llvm::object::Archive::isThin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a03bfd76bddfe1a42326e93dc3c131c8c">getBuffer</a>.</p>

</div>
</div>

### getGID() {#a5cbd281cdf1331330da601c219e452e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; llvm::object::Archive::Child::getGID ()</td>
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



<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>.</p>

</div>
</div>

### getLastModified() {#abea74633b8c0af7cb53addc66ce55ec1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; sys::TimePoint&lt; std::chrono::seconds &gt; &gt; llvm::object::Archive::Child::getLastModified ()</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>.</p>

</div>
</div>

### getMemoryBufferRef() {#a7fa0bfbc8489a0b3472e2dd834e03c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; MemoryBufferRef &gt; Archive::Child::getMemoryBufferRef ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 645 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a03bfd76bddfe1a42326e93dc3c131c8c">getBuffer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>.</p>

</div>
</div>

### getName() {#a3acd0fa308c00ead51dc16b4d46604bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; Archive::Child::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 632 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a3125cc2c2f3101a53e90173312fc4554">getRawSize</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getNext() {#a137ad5829c3f2470a0da63800c59385e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; Archive::Child &gt; Archive::Child::getNext ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/objcarc/provenanceanalysisevaluator-cpp/#a2ee79648e8bce3ddbb26358ff10e3e82">getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#a8160a3004ff47f73b842d7030269ff3d">malformedError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getParent() {#ac89b2f5f9a092793db6d9b5692fdcd08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Archive * llvm::object::Archive::Child::getParent ()</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getRawLastModified() {#a1065e08cfcfc167515f06a8d397e40c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::Child::getRawLastModified ()</td>
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



<p>Definition at line 231 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getRawName() {#a6f5f4cc94a06322f5be047c398bc5e34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; StringRef &gt; llvm::object::Archive::Child::getRawName ()</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a>.</p>

</div>
</div>

### getRawSize() {#a3125cc2c2f3101a53e90173312fc4554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; Archive::Child::getRawSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size in the archive header for this member.</p></dd>
</dl>


<p>Declaration at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 548 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>Referenced by <a href="#a9537162135cca043a3b82f0df2816ed7">Child</a> and <a href="#a3acd0fa308c00ead51dc16b4d46604bc">getName</a>.</p>

</div>
</div>

### getSize() {#a470c8d3fb44a1233ee5fe50fd5ce0304}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; Archive::Child::getSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the size of the archive member without the header or padding.</p></dd>
</dl>


<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>

</div>
</div>

### getUID() {#a91f4f1c730ddfa9b53bed05548b656fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; llvm::object::Archive::Child::getUID ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/newarchivemember/#aadff13fd008345361aa920977e0c9e32">llvm::NewArchiveMember::getOldMember</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### isThinMember() {#a240d2598d6b251f95aa0d68657ece3c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; bool &gt; Archive::Child::isThinMember ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 552 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AbstractArchiveMemberHeader {#abcfe95d361dd817f614a9bd4ef5e4a58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::object::Archive::Child::AbstractArchiveMemberHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### Archive {#a212dc0a4d2da50c9300f418ae9017c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend llvm::object::Archive::Child::Archive</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### Data {#a5334d6b6d8171c9ee8fb27c64ffb063c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::object::Archive::Child::Data</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Includes header but not padding byte.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### Header {#a20f8e54bc6f82d97ade6ff81ff2a1f9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;AbstractArchiveMemberHeader&gt; llvm::object::Archive::Child::Header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### Parent {#a6d94f63a838183dc5bc5fc9da2244e6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Archive* llvm::object::Archive::Child::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### StartOfFile {#ac2f268933c4afca40dc1c5a735b54b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t llvm::object::Archive::Child::StartOfFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset from Data to the start of the file.</p>

<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

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
