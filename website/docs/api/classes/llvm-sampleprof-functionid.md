---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sampleprof/functionid
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FunctionId` Class Reference

<p>This class represents a function that is read from a sample profile. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::sampleprof::FunctionId { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">llvm/ProfileData/FunctionId.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e7ef8c33c2dfc11808482f459e9718e">operator&lt;&lt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f6de9c348192cc721a47820a5887b9">FunctionId</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00a95f6c10a5942e4d8d38ec5df0550a">FunctionId</a> (StringRef Str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a00a95f6c10a5942e4d8d38ec5df0550a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5787b4f24749152c65ae0ac28481d6c0">FunctionId</a> (uint64_t HashCode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor from a hash code. <a href="#a5787b4f24749152c65ae0ac28481d6c0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9256740671ebe9569db9be4859249e43">equals</a> (const FunctionId &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for equality. <a href="#a9256740671ebe9569db9be4859249e43">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88477c2cef22acd843d1e9891c26c67c">compare</a> (const FunctionId &amp;Other) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Total order comparison. <a href="#a88477c2cef22acd843d1e9891c26c67c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac33ae101b77f66bd6b558c770a6256bc">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert to a string, usually for output purpose. <a href="#ac33ae101b77f66bd6b558c770a6256bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36a977f1e2f4b4b0fca324a11d3e3313">stringRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convert to <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>. <a href="#a36a977f1e2f4b4b0fca324a11d3e3313">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c097d6625bd9e8132f391309e787943">getHashCode</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get hash code of this object. <a href="#a5c097d6625bd9e8132f391309e787943">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6fbd8851c1e7809544abaf1fae75a0">empty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a760c909c653e18da72d03609610ab2e5">isStringRef</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this object represents a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, or a hash code. <a href="#a760c909c653e18da72d03609610ab2e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a666b07a201ea29594a7a295465ce9380">Data</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12d120796b7ace4d8082140341d55343">LengthOrHashCode</a> = 0</td>
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

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c8d6264ba738941d9d2020aa879550">compareMemory</a> (const char *Lhs, const char *Rhs, uint64_t Length)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> to memcmp to handle hash code representation. <a href="#af3c8d6264ba738941d9d2020aa879550">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents a function that is read from a sample profile.</p>


<p>It comes with two forms: a string or a hash code. The latter form is the 64-bit <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> of the function name for efficient storage supported by ExtBinary profile format, and when reading the profile, this class can represent it without converting it to a string first. When representing a hash code, we utilize the LengthOrHashCode field to store it, and Name is set to null. When representing a string, it is same as <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator&lt;&lt; {#a7e7ef8c33c2dfc11808482f459e9718e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; Obj</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>Reference <a href="#a72f6de9c348192cc721a47820a5887b9">FunctionId</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FunctionId() {#a72f6de9c348192cc721a47820a5887b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::FunctionId::FunctionId ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>Referenced by <a href="#a88477c2cef22acd843d1e9891c26c67c">compare</a>, <a href="#a9256740671ebe9569db9be4859249e43">equals</a> and <a href="#a7e7ef8c33c2dfc11808482f459e9718e">operator&lt;&lt;</a>.</p>

</div>
</div>

### FunctionId() {#a00a95f6c10a5942e4d8d38ec5df0550a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::FunctionId::FunctionId (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor from a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>.</p>

</div>
</div>

### FunctionId() {#a5787b4f24749152c65ae0ac28481d6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sampleprof::FunctionId::FunctionId (uint64_t HashCode)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor from a hash code.</p>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compare() {#a88477c2cef22acd843d1e9891c26c67c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sampleprof::FunctionId::compare (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; Other)</td>
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

<p>Total order comparison.</p>


<p>If both <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> are <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, this is the same as <a href="/web-llvm/docs/api/classes/llvm/stringref/#ae0c6424784f132b91eb387a3ee0b57c9">StringRef::compare</a>. If one of them is <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, it is considered greater than the hash code <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a>. Otherwise this is the the same as comparing their int values.</p>


<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>References <a href="#a72f6de9c348192cc721a47820a5887b9">FunctionId</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### empty() {#a8f6fbd8851c1e7809544abaf1fae75a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionId::empty ()</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/contexttrienode/#ab05fd0aa0f2a966006e4b4bd448617e7">llvm::ContextTrieNode::getChildContext</a> and <a href="/web-llvm/docs/api/classes/llvm/samplecontexttracker/#a03cbc7841d2552fcd7639666975fa13c">llvm::SampleContextTracker::promoteMergeContextSamplesTree</a>.</p>

</div>
</div>

### equals() {#a9256740671ebe9569db9be4859249e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionId::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> &amp; Other)</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> for equality.</p>


<p>Similar to StringRef::equals, but will also cover for the case where one or both are hash codes. Comparing their int values are sufficient. A hash code <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> is considered not equal to a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionid">FunctionId</a> regardless of actual contents.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>References <a href="#a72f6de9c348192cc721a47820a5887b9">FunctionId</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### getHashCode() {#a5c097d6625bd9e8132f391309e787943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionId::getHashCode ()</td>
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

<p>Get hash code of this object.</p>


<p>Returns this object's hash code if it is already representing one, otherwise returns the <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> of its string content. Note that it is not the same as std::hash because we want to keep the consistency that the same sample profile function in string form or <a href="/web-llvm/docs/api/classes/llvm/md5">MD5</a> form has the same hash code.</p>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#afb077bf8dc20e4016e83042d3f784d32">llvm::sampleprof::FunctionSamples::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/samplecontext/#aa974f8c265b1f6334ffd5df3507371f3">llvm::sampleprof::SampleContext::getHashCode</a>, <a href="/web-llvm/docs/api/structs/llvm/densemapinfo-9d88b1da97f443eb327dce9e3460d07c/#ae6cdc1b489f722a1f25cdd8da4c870cb">llvm::DenseMapInfo&lt; sampleprof::FunctionId, void &gt;::getHashValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#ae45c2dc36b1f12d52356dd557bcf02eb">llvm::sampleprof::hash_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a8e89e6935aaf48cde9d60fd12a3dae0f">llvm::sampleprof::MD5Hash</a>, <a href="/web-llvm/docs/api/structs/std/hash-ec5350b77c06d74bcb90f84edf6d0a1c/#a19585ecc01dca67677608064e7b3e743">std::hash&lt; llvm::sampleprof::FunctionId &gt;::operator()</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a> and <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderbinary/#a08a6c4a1c3536fa7e594a3151e0773f9">llvm::sampleprof::SampleProfileReaderBinary::readNameTable</a>.</p>

</div>
</div>

### isStringRef() {#a760c909c653e18da72d03609610ab2e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sampleprof::FunctionId::isStringRef ()</td>
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

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if this object represents a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, or a hash code.</p>

<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>

</div>
</div>

### str() {#ac33ae101b77f66bd6b558c770a6256bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::sampleprof::FunctionId::str ()</td>
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

<p>Convert to a string, usually for output purpose.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> caution on return value's lifetime when converting to <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/profiledata/sampleprofreader-cpp/#a3f66983ff782c5a6bc67a19058c7ea6b">dumpFunctionProfileJson</a>.</p>

</div>
</div>

### stringRef() {#a36a977f1e2f4b4b0fca324a11d3e3313}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::sampleprof::FunctionId::stringRef ()</td>
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

<p>Convert to <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>.</p>


<p>This is only allowed when it is known this object is representing a <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>, not a hash code. Calling this function on a hash code is considered an error.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sampleprof/sampleprofilereaderextbinarybase/#a873e0df967c1a3a622ee9e25c1a6fa00">llvm::sampleprof::SampleProfileReaderExtBinaryBase::readFuncProfiles</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Data {#a666b07a201ea29594a7a295465ce9380}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* llvm::sampleprof::FunctionId::Data = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>

</div>
</div>

### LengthOrHashCode {#a12d120796b7ace4d8082140341d55343}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::sampleprof::FunctionId::LengthOrHashCode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### compareMemory() {#af3c8d6264ba738941d9d2020aa879550}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sampleprof::FunctionId::compareMemory (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Lhs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Rhs, uint64_t Length)</td>
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

<p><a href="/web-llvm/docs/api/structs/extension">Extension</a> to memcmp to handle hash code representation.</p>


<p>If both are hash values, Lhs and Rhs are both null, function returns 0 (and needs an extra comparison using getIntValue). If only one is hash code, it is considered less than the <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> one. Otherwise perform normal string comparison.</p>


<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/functionid-h">FunctionId.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
