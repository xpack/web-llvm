---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/inlineinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InlineInfo` Struct

<p>Inline information stores the name of the inline function along with an array of address ranges. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::InlineInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">llvm/DebugInfo/GSYM/InlineInfo.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b13e2daed67ab714dcc5138fd07d600">InlineArray</a> = std::vector&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20b089b7dd2fd022435d492a9ddeab36">InlineInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5334ef65a442bb11580a5a4779555253">operator&lt;</a> (const InlineInfo &amp;RHS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compare <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects. <a href="#a5334ef65a442bb11580a5a4779555253">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06cc4c294f4958c7302cf9a7a20b630">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b32cc36bb90f453ecbf6c7f5fe1cde2">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="#a6b13e2daed67ab714dcc5138fd07d600">InlineArray</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ddf4ca5eba1a243b409b9afe1a9a6e0">getInlineStack</a> (uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup an address in the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object. <a href="#a6ddf4ca5eba1a243b409b9afe1a9a6e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942b72b4d473fa049b9e5f4fc1fce789">encode</a> (FileWriter &amp;O, uint64_t BaseAddr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode this <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream. <a href="#a942b72b4d473fa049b9e5f4fc1fce789">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af36254c514e0067df9e218d445271def">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>String table offset in the string table. <a href="#af36254c514e0067df9e218d445271def">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7dc376fcf6081633e4944a717040be46">CallFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>1 based file index in the file table. <a href="#a7dc376fcf6081633e4944a717040be46">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac42ae93d420307f9cf934d78c0ad661d">CallLine</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Source line number. <a href="#ac42ae93d420307f9cf934d78c0ad661d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55c9eb4dff498093824304e525a9017a">Ranges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53d934eaa717abd9781a703afed2b3b2">Children</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f764edf4bf576f4e243188eb8fa5e0c">lookup</a> (const GsymReader &amp;GR, DataExtractor &amp;Data, uint64_t BaseAddr, uint64_t Addr, SourceLocations &amp;SrcLocs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup a single address within the inline info data. <a href="#a6f764edf4bf576f4e243188eb8fa5e0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae59cf2adb8c2fb547e64f51ee921aa56">decode</a> (DataExtractor &amp;Data, uint64_t BaseAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object from a binary data stream. <a href="#ae59cf2adb8c2fb547e64f51ee921aa56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Inline information stores the name of the inline function along with an array of address ranges.</p>


<p>It also stores the call file and call line that called this inline function. This allows us to unwind inline call stacks back to the inline or concrete function that called this function. Inlined functions contained in this function are stored in the "Children" variable. All address ranges must be sorted and all address ranges of all children must be contained in the ranges of this function. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> clients that encode information will need to ensure the ranges are all contined correctly or lookups could fail. Add ranges in these objects must be contained in the top level <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> address ranges as well.</p>


<p>ENCODING</p>


<p>When saved to disk, the inline info encodes all ranges to be relative to a parent address range. This will be the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address if the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> is directly contained in a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>, or a the start address of the containing parent <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a>'s first "Ranges" member. This allows address ranges to be efficiently encoded using ULEB128 encodings as we encode the offset and size of each range instead of full addresses. This also makes any encoded addresses easy to relocate as we just need to relocate the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address.</p>


<ul class="doxyList ">
<li>The <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> member "Ranges" is encoded using an appropriate base address as described above.</li>
<li>UINT8 boolean value that specifies if the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object has children.</li>
<li>UINT32 string table offset that points to the name of the inline function.</li>
<li>ULEB128 integer that specifies the file of the call site that called this function.</li>
<li>ULEB128 integer that specifies the source line of the call site that called this function.</li>
<li>if this object has children, enocode each child <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> using the the first address range's start address as the base address.</li>
</ul>

<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### InlineArray {#a6b13e2daed67ab714dcc5138fd07d600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::gsym::InlineInfo::InlineArray =  std::vector&lt;const InlineInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### InlineInfo() {#a20b089b7dd2fd022435d492a9ddeab36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::InlineInfo::InlineInfo ()</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>References <a href="#a7dc376fcf6081633e4944a717040be46">CallFile</a>, <a href="#ac42ae93d420307f9cf934d78c0ad661d">CallLine</a> and <a href="#af36254c514e0067df9e218d445271def">Name</a>.</p>


<p>Referenced by <a href="#a5334ef65a442bb11580a5a4779555253">operator&lt;</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;() {#a5334ef65a442bb11580a5a4779555253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compare <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects.</p>


<p>When comparing <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects the item with the most inline functions wins. If we have two <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects that both have the same address range and both have valid <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects, we want the one with the most inline functions to win so we save the most information possible to the GSYM file. We have seen cases where LTO messes up the inline function information for the same address range, so this helps ensure we get the most descriptive information we can for an address range.</p>


<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>, definition at line 274 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#ad937528fd3e0fc9de4dc3ebf05567c72">GetTotalNumChildren</a> and <a href="#a20b089b7dd2fd022435d492a9ddeab36">InlineInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#ab06cc4c294f4958c7302cf9a7a20b630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::InlineInfo::clear ()</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>References <a href="#a7dc376fcf6081633e4944a717040be46">CallFile</a>, <a href="#ac42ae93d420307f9cf934d78c0ad661d">CallLine</a>, <a href="#a53d934eaa717abd9781a703afed2b3b2">Children</a>, <a href="#af36254c514e0067df9e218d445271def">Name</a> and <a href="#a55c9eb4dff498093824304e525a9017a">Ranges</a>.</p>

</div>
</div>

### encode() {#a942b72b4d473fa049b9e5f4fc1fce789}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error InlineInfo::encode (<a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; O, uint64_t BaseAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode this <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The binary stream to write the data to at the current file position.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when encoding all address ranges. This will be the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address if this object is directly contained in a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object, or the start address of the first address range in an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object of this object is a child of another <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure or the encoding process.</p></dd>
</dl>


<p>Declaration at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="#a7dc376fcf6081633e4944a717040be46">CallFile</a>, <a href="#ac42ae93d420307f9cf934d78c0ad661d">CallLine</a>, <a href="#a53d934eaa717abd9781a703afed2b3b2">Children</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a1457a01526b6335c882eccf768d2359b">llvm::gsym::encodeRanges</a>, <a href="#a8b32cc36bb90f453ecbf6c7f5fe1cde2">isValid</a>, <a href="#af36254c514e0067df9e218d445271def">Name</a>, <a href="#a55c9eb4dff498093824304e525a9017a">Ranges</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

### getInlineStack() {#a6ddf4ca5eba1a243b409b9afe1a9a6e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; InlineInfo::InlineArray &gt; InlineInfo::getInlineStack (uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lookup an address in the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object.</p>


<p>This function is used to symbolicate an inline call stack and can turn one address in the program into one or more inline call stacks and have the stack trace show the original call site from non-inlined code.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>the address to lookup</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>optional vector of <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> objects that describe the inline call stack for a given address, false otherwise.</p></dd>
</dl>


<p>Declaration at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="#a6ddf4ca5eba1a243b409b9afe1a9a6e0">getInlineStack</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a8fc3ed6ceeeace8a7eb5804423cd30bc">getInlineStackHelper</a>.</p>


<p>Referenced by <a href="#a6ddf4ca5eba1a243b409b9afe1a9a6e0">getInlineStack</a>.</p>

</div>
</div>

### isValid() {#a8b32cc36bb90f453ecbf6c7f5fe1cde2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::InlineInfo::isValid ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>Reference <a href="#a55c9eb4dff498093824304e525a9017a">Ranges</a>.</p>


<p>Referenced by <a href="#a942b72b4d473fa049b9e5f4fc1fce789">encode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CallFile {#a7dc376fcf6081633e4944a717040be46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::InlineInfo::CallFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>1 based file index in the file table.</p>

<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>Referenced by <a href="#ab06cc4c294f4958c7302cf9a7a20b630">clear</a>, <a href="#a942b72b4d473fa049b9e5f4fc1fce789">encode</a> and <a href="#a20b089b7dd2fd022435d492a9ddeab36">InlineInfo</a>.</p>

</div>
</div>

### CallLine {#ac42ae93d420307f9cf934d78c0ad661d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::InlineInfo::CallLine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Source line number.</p>

<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>Referenced by <a href="#ab06cc4c294f4958c7302cf9a7a20b630">clear</a>, <a href="#a942b72b4d473fa049b9e5f4fc1fce789">encode</a> and <a href="#a20b089b7dd2fd022435d492a9ddeab36">InlineInfo</a>.</p>

</div>
</div>

### Children {#a53d934eaa717abd9781a703afed2b3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;InlineInfo&gt; llvm::gsym::InlineInfo::Children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>Referenced by <a href="#ab06cc4c294f4958c7302cf9a7a20b630">clear</a>, <a href="#a942b72b4d473fa049b9e5f4fc1fce789">encode</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### Name {#af36254c514e0067df9e218d445271def}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::InlineInfo::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>String table offset in the string table.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>Referenced by <a href="#ab06cc4c294f4958c7302cf9a7a20b630">clear</a>, <a href="#a942b72b4d473fa049b9e5f4fc1fce789">encode</a> and <a href="#a20b089b7dd2fd022435d492a9ddeab36">InlineInfo</a>.</p>

</div>
</div>

### Ranges {#a55c9eb4dff498093824304e525a9017a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressRanges llvm::gsym::InlineInfo::Ranges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>.</p>


<p>Referenced by <a href="#ab06cc4c294f4958c7302cf9a7a20b630">clear</a>, <a href="#a942b72b4d473fa049b9e5f4fc1fce789">encode</a>, <a href="#a8b32cc36bb90f453ecbf6c7f5fe1cde2">isValid</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decode() {#ae59cf2adb8c2fb547e64f51ee921aa56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; InlineInfo &gt; InlineInfo::decode (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t BaseAddr)</td>
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

<p>Decode an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object from a binary data stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when decoding all address ranges. This will be the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address if this object is directly contained in a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object, or the start address of the first address range in an <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object of this object is a child of another <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> or an error describing the issue that was encountered during decoding.</p></dd>
</dl>


<p>Declaration at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>, definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aea38a34c36c8f1cb37754bd3bd336053">llvm::gsym::FunctionInfo::decode</a>.</p>

</div>
</div>

### lookup() {#a6f764edf4bf576f4e243188eb8fa5e0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error InlineInfo::lookup (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> &amp; GR, <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t BaseAddr, uint64_t Addr, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#af56cdce2bbbfcdafb057bce7c90bf419">SourceLocations</a> &amp; SrcLocs)</td>
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

<p>Lookup a single address within the inline info data.</p>


<p>Clients have the option to decode an entire <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object (using <a href="#ae59cf2adb8c2fb547e64f51ee921aa56">InlineInfo::decode()</a> ) or just find the matching inline info using this function. The benefit of using this function is that only the information needed for the lookup will be extracted, other info can be skipped and parsing can stop as soon as the deepest match is found. This allows symbolication tools to be fast and efficient and avoid allocation costs when doing lookups.</p>


<p>This function will augment the <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#af56cdce2bbbfcdafb057bce7c90bf419">SourceLocations</a> array <em>SrcLocs</em> with any inline information that pertains to <em>Addr</em>. If no inline information exists for <em>Addr</em>, then <em>SrcLocs</em> will be left untouched. If there is inline information for <em>Addr</em>, then <em>SrcLocs</em> will be modifiied to contain the deepest most inline function's <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation">SourceLocation</a> at index zero in the array and proceed up the concrete function source file and line at the end of the array.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">GR</td>
<td class="doxyParamItemDescription"><p>The GSYM reader that contains the string and file table that will be used to fill in the source locations.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The base address to use when decoding the line table. This will be the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address and will be used to decode the correct addresses for the inline information.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>The address to lookup.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcLocs</td>
<td class="doxyParamItemDescription"><p>The inline source locations that matches <em>Addr</em>. This array must be initialized with the matching line entry from the line table upon entry. The name of the concrete function must be supplied since it will get pushed to the last <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation">SourceLocation</a> entry and the inline information will fill in the source file and line from the inline information.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error if the inline information is corrupt, or <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a> for all other cases, even when no information is added to <em>SrcLocs</em>.</p></dd>
</dl>


<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a>, definition at line 159 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="#a6f764edf4bf576f4e243188eb8fa5e0c">lookup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a> and <a href="#a6f764edf4bf576f4e243188eb8fa5e0c">lookup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/inlineinfo-h">InlineInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp">InlineInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
