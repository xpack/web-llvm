---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/object/abstractarchivememberheader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `AbstractArchiveMemberHeader` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::object::AbstractArchiveMemberHeader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">llvm/Object/Archive.h</a>"
</div>

## Derived Classes

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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f1345bc28f2fd55b5ef2717d251ceea">Archive</a></td>
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

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bac2ef0cc0bd5c20ce70ac89a70af60">AbstractArchiveMemberHeader</a> (const Archive *Parent)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83f3320c7c3d3221585b245b56d6b709">~AbstractArchiveMemberHeader</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac211b5f5bad964d43f0d9a921a71ff8a">clone</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ea9052f8bafbfe05ad3ce10d5cfad40">getRawName</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name without looking up long names. <a href="#a9ea9052f8bafbfe05ad3ce10d5cfad40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1109f242efcfa02638cf1219c526430">getRawAccessMode</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6af5815082421e20334d3056a8f30f1">getRawLastModified</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ce100a3cd607c81704a9379ff3fdac7">getRawUID</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1380bcda3c428785e8897ce3ee62faf8">getRawGID</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73dd2f342d8dbbf4a1145fc8c8798de">getName</a> (uint64_t Size) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the name looking up long names. <a href="#ae73dd2f342d8dbbf4a1145fc8c8798de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c2bd00482dac52bfad8287c63b7411b">getSize</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3cae5601471f6b6ce12a153183ee8b">getOffset</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9adb0ce9bfd58fca90fbb43216f90831">getNextChildLoc</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get next file member location. <a href="#a9adb0ce9bfd58fca90fbb43216f90831">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff98a518b7c7627d36961b36d5ac86f">isThin</a> () const =0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b041d7f0753dfc105eec7d7a34d5bed">getAccessMode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0994633a7dc598ab379d4dcfa99bb17">getLastModified</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a366b06f6bd50440e9b1c85f537aec7ec">getUID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8601675aad561f5f3467eb4a49c95794">getGID</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4caad5ca5c2fa6738463aaf53c8e798">getSizeOf</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the size in bytes of the format-defined member header of the concrete archive type. <a href="#aa4caad5ca5c2fa6738463aaf53c8e798">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0215baac13e6c4d987e67335d81dc29b">Parent</a></td>
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


<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Archive {#a4f1345bc28f2fd55b5ef2717d251ceea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="#a4f1345bc28f2fd55b5ef2717d251ceea">Archive</a>.</p>


<p>Referenced by <a href="#a5bac2ef0cc0bd5c20ce70ac89a70af60">AbstractArchiveMemberHeader</a>, <a href="#a4f1345bc28f2fd55b5ef2717d251ceea">Archive</a> and <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a672e18a663388332797a2573fa7c09e8">llvm::object::CommonArchiveMemberHeader&lt; T &gt;::CommonArchiveMemberHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Constructors

### AbstractArchiveMemberHeader() {#a5bac2ef0cc0bd5c20ce70ac89a70af60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::object::AbstractArchiveMemberHeader::AbstractArchiveMemberHeader (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/archive">Archive</a> * Parent)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>References <a href="#a4f1345bc28f2fd55b5ef2717d251ceea">Archive</a> and <a href="#a0215baac13e6c4d987e67335d81dc29b">Parent</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a672e18a663388332797a2573fa7c09e8">llvm::object::CommonArchiveMemberHeader&lt; T &gt;::CommonArchiveMemberHeader</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AbstractArchiveMemberHeader() {#a83f3320c7c3d3221585b245b56d6b709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::object::AbstractArchiveMemberHeader::~AbstractArchiveMemberHeader ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clone() {#ac211b5f5bad964d43f0d9a921a71ff8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; AbstractArchiveMemberHeader &gt; llvm::object::AbstractArchiveMemberHeader::clone ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getAccessMode() {#a5b041d7f0753dfc105eec7d7a34d5bed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; sys::fs::perms &gt; AbstractArchiveMemberHeader::getAccessMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 384 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#ad146f206f099fa725c05238ccdccc333">getArchiveMemberOctField</a>, <a href="#ac1109f242efcfa02638cf1219c526430">getRawAccessMode</a>, <a href="#a0215baac13e6c4d987e67335d81dc29b">Parent</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getGID() {#a8601675aad561f5f3467eb4a49c95794}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; AbstractArchiveMemberHeader::getGID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="#a1380bcda3c428785e8897ce3ee62faf8">getRawGID</a> and <a href="#a0215baac13e6c4d987e67335d81dc29b">Parent</a>.</p>

</div>
</div>

### getLastModified() {#aa0994633a7dc598ab379d4dcfa99bb17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; sys::TimePoint&lt; std::chrono::seconds &gt; &gt; AbstractArchiveMemberHeader::getLastModified ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 393 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="#ae6af5815082421e20334d3056a8f30f1">getRawLastModified</a>, <a href="#a0215baac13e6c4d987e67335d81dc29b">Parent</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a7e0c6b3661b9c9f048aaef620463f1bc">llvm::sys::toTimePoint</a>.</p>

</div>
</div>

### getName() {#ae73dd2f342d8dbbf4a1145fc8c8798de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; StringRef &gt; llvm::object::AbstractArchiveMemberHeader::getName (uint64_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name looking up long names.</p>

<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a>.</p>

</div>
</div>

### getNextChildLoc() {#a9adb0ce9bfd58fca90fbb43216f90831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; const char * &gt; llvm::object::AbstractArchiveMemberHeader::getNextChildLoc ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get next file member location.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getOffset() {#a8e3cae5601471f6b6ce12a153183ee8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::AbstractArchiveMemberHeader::getOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#ad146f206f099fa725c05238ccdccc333">getArchiveMemberOctField</a>.</p>

</div>
</div>

### getRawAccessMode() {#ac1109f242efcfa02638cf1219c526430}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::object::AbstractArchiveMemberHeader::getRawAccessMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a5b041d7f0753dfc105eec7d7a34d5bed">getAccessMode</a>.</p>

</div>
</div>

### getRawGID() {#a1380bcda3c428785e8897ce3ee62faf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::object::AbstractArchiveMemberHeader::getRawGID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a8601675aad561f5f3467eb4a49c95794">getGID</a>.</p>

</div>
</div>

### getRawLastModified() {#ae6af5815082421e20334d3056a8f30f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::object::AbstractArchiveMemberHeader::getRawLastModified ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#aa0994633a7dc598ab379d4dcfa99bb17">getLastModified</a>.</p>

</div>
</div>

### getRawName() {#a9ea9052f8bafbfe05ad3ce10d5cfad40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; StringRef &gt; llvm::object::AbstractArchiveMemberHeader::getRawName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the name without looking up long names.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getRawUID() {#a2ce100a3cd607c81704a9379ff3fdac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual StringRef llvm::object::AbstractArchiveMemberHeader::getRawUID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a366b06f6bd50440e9b1c85f537aec7ec">getUID</a>.</p>

</div>
</div>

### getSize() {#a4c2bd00482dac52bfad8287c63b7411b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; uint64_t &gt; llvm::object::AbstractArchiveMemberHeader::getSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getSizeOf() {#aa4caad5ca5c2fa6738463aaf53c8e798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::object::AbstractArchiveMemberHeader::getSizeOf ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the size in bytes of the format-defined member header of the concrete archive type.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

### getUID() {#a366b06f6bd50440e9b1c85f537aec7ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; unsigned &gt; AbstractArchiveMemberHeader::getUID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp">Archive.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af0b0d5a3c44e6c8bf449fcbd3cc1224b">getArchiveMemberDecField</a>, <a href="#a2ce100a3cd607c81704a9379ff3fdac7">getRawUID</a> and <a href="#a0215baac13e6c4d987e67335d81dc29b">Parent</a>.</p>

</div>
</div>

### isThin() {#a9ff98a518b7c7627d36961b36d5ac86f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Expected&lt; bool &gt; llvm::object::AbstractArchiveMemberHeader::isThin ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Parent {#a0215baac13e6c4d987e67335d81dc29b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Archive* llvm::object::AbstractArchiveMemberHeader::Parent</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/object/archive-h">Archive.h</a>.</p>


<p>Referenced by <a href="#a5bac2ef0cc0bd5c20ce70ac89a70af60">AbstractArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#ae54b3190e013b4c17e9dd0e82fb8ec2e">llvm::object::BigArchiveMemberHeader::BigArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a672e18a663388332797a2573fa7c09e8">llvm::object::CommonArchiveMemberHeader&lt; T &gt;::CommonArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archive-cpp/#af194271b77c030b86d1f22f523e7f048">createMemberHeaderParseError</a>, <a href="#a5b041d7f0753dfc105eec7d7a34d5bed">getAccessMode</a>, <a href="#a8601675aad561f5f3467eb4a49c95794">getGID</a>, <a href="#aa0994633a7dc598ab379d4dcfa99bb17">getLastModified</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#ae1d86083ac823979ed30663f9d87118d">llvm::object::ArchiveMemberHeader::getNextChildLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a5ac0ddcf418dd66efde6cb208755629f">llvm::object::BigArchiveMemberHeader::getNextChildLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#adfe40bee08ac4f93c61808e0aa9e3308">llvm::object::BigArchiveMemberHeader::getNextOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/commonarchivememberheader/#a6f0d33d445775adb00017f7c7e49d230">llvm::object::CommonArchiveMemberHeader&lt; T &gt;::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a990a2cc1b018140f8dde6e1a8ad42182">llvm::object::ArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a1dee83379cd715e24ccdec554331a3cf">llvm::object::BigArchiveMemberHeader::getRawName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#aa12e214fe9eef659a3935afbac7b05fb">llvm::object::BigArchiveMemberHeader::getRawNameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#ace1855f7759a2a9be5299cdecc51c477">llvm::object::ArchiveMemberHeader::getSize</a>, <a href="/web-llvm/docs/api/classes/llvm/object/bigarchivememberheader/#a19fbab288c38cba1ba49b9093ce87995">llvm::object::BigArchiveMemberHeader::getSize</a>, <a href="#a366b06f6bd50440e9b1c85f537aec7ec">getUID</a> and <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#aa954ca2029479568fc22ecd2c427c4a2">llvm::object::ArchiveMemberHeader::isThin</a>.</p>

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
