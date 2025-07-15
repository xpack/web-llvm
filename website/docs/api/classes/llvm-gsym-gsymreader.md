---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/gsymreader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GsymReader` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> is used to read GSYM data from a file or buffer. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::gsym::GsymReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">llvm/DebugInfo/GSYM/GsymReader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfb8ec46232ad9d3b2b2d8a3d2b8f6cf">GsymReader</a> (GsymReader &amp;&amp;RHS)</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8396b98fae621a66af7cd9009728e0a9">GsymReader</a> (std::unique_ptr&lt; MemoryBuffer &gt; Buffer)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6de836822f59f466c4ba2e5af57284e1">~GsymReader</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/header">Header</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e7d9a0bf21c853ef7f5efb1219e4721">getHeader</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access the GSYM header. <a href="#a8e7d9a0bf21c853ef7f5efb1219e4721">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891f5398a526e0de9d2b5006559ef594">getFunctionInfo</a> (uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the full function info for an address. <a href="#a891f5398a526e0de9d2b5006559ef594">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae699d115f9699264b670c60d4f57d394">getFunctionInfoAtIndex</a> (uint64_t AddrIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the full function info given an address index. <a href="#ae699d115f9699264b670c60d4f57d394">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5768ee08d5c7c9b431387ce9b03a6e9">lookup</a> (uint64_t Addr, std::optional&lt; DataExtractor &gt; *MergedFuncsData=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup an address in the a GSYM. <a href="#ad5768ee08d5c7c9b431387ce9b03a6e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afab544245beb837bd2fd89c12e060c3f">lookupAll</a> (uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup all merged functions for a given address. <a href="#afab544245beb837bd2fd89c12e060c3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65ec9133639d066dcf6843b1fc3ae79c">getString</a> (uint32_t Offset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a string from the string table. <a href="#a65ec9133639d066dcf6843b1fc3ae79c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25ce2405debe5fa88ce06de770ce4bf0">getFile</a> (uint32_t Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the a file entry for the suppplied file index. <a href="#a25ce2405debe5fa88ce06de770ce4bf0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c4724c06d85bc195e23612de85f6774">dump</a> (raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the entire Gsym data contained in this object. <a href="#a2c4724c06d85bc195e23612de85f6774">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a000318afaccf51b9e411d4890c4a1231">dump</a> (raw_ostream &amp;OS, const FunctionInfo &amp;FI, uint32_t Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object. <a href="#a000318afaccf51b9e411d4890c4a1231">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e9110bbf8007555e8e6b1135609d4d7">dump</a> (raw_ostream &amp;OS, const MergedFunctionsInfo &amp;MFI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object. <a href="#a4e9110bbf8007555e8e6b1135609d4d7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40a7cf3120a64f2f2e563bc820b9d846">dump</a> (raw_ostream &amp;OS, const CallSiteInfo &amp;CSI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object. <a href="#a40a7cf3120a64f2f2e563bc820b9d846">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba0602c835ed2f449b723d5bf57d2eda">dump</a> (raw_ostream &amp;OS, const CallSiteInfoCollection &amp;CSIC, uint32_t Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection">CallSiteInfoCollection</a> object. <a href="#aba0602c835ed2f449b723d5bf57d2eda">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33125921f2e76880e7ad9ab30c9dfca2">dump</a> (raw_ostream &amp;OS, const LineTable &amp;LT, uint32_t Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object. <a href="#a33125921f2e76880e7ad9ab30c9dfca2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60b4742db7fd8558ba9138277c44bf22">dump</a> (raw_ostream &amp;OS, const InlineInfo &amp;II, uint32_t Indent=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object. <a href="#a60b4742db7fd8558ba9138277c44bf22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0c87bb82a7b90da0291671f18e9f8cd">dump</a> (raw_ostream &amp;OS, std::optional&lt; FileEntry &gt; FE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> object. <a href="#ac0c87bb82a7b90da0291671f18e9f8cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35ec8760c2d3f45a812020c7e19f25da">getNumAddresses</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the number of addresses in this Gsym file. <a href="#a35ec8760c2d3f45a812020c7e19f25da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a462b4c7171102d060094e578596c23c2">getAddress</a> (size_t Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets an address from the address table. <a href="#a462b4c7171102d060094e578596c23c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a572a0897fc07913ec396452f99efa704">getAddrOffsets</a> () const -&gt; <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; T &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an appropriate address info offsets array. <a href="#a572a0897fc07913ec396452f99efa704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a938be134329f4243053d957980a79724">addressForIndex</a> (size_t Index) const -&gt; std::optional&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an appropriate address from the address table. <a href="#a938be134329f4243053d957980a79724">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afe6e63cc76f08a5400707ae311ca1cfd">getAddressOffsetIndex</a> (const uint64_t AddrOffset) const -&gt; std::optional&lt; uint64_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup an address offset in the AddrOffsets table. <a href="#afe6e63cc76f08a5400707ae311ca1cfd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9572a95e4bc84fe4b9d8294cd81d30d">getAddressIndex</a> (const uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an address, find the address index. <a href="#ab9572a95e4bc84fe4b9d8294cd81d30d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fcb3aee09b8523cef4a80c620f87366">getAddressInfoOffset</a> (size_t Index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an address index, get the offset for the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>. <a href="#a4fcb3aee09b8523cef4a80c620f87366">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dataextractor">llvm::DataExtractor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15b2b0c7e2abba2d3e36989685d800f">getFunctionInfoDataForAddress</a> (uint64_t Addr, uint64_t &amp;FuncStartAddr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an address, find the correct function info data and function address. <a href="#af15b2b0c7e2abba2d3e36989685d800f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dataextractor">llvm::DataExtractor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa167494fa5d265faa5315612cd3d37fe">getFunctionInfoDataAtIndex</a> (uint64_t AddrIdx, uint64_t &amp;FuncStartAddr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the function data and address given an address index. <a href="#aa167494fa5d265faa5315612cd3d37fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac84c32841bd9b8176df41f9afff85c4a">parse</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acad5db4c26dab79d637ad82335033cc8">MemBuffer</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a555e6db794ee577eef1925e500873978">GsymBytes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8d12edac5b9fc6cf17ab94d7aa6732d">Endian</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/header">Header</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac748c9eb8e6533296efd0cd3e5853670">Hdr</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a324ca1de3325ad321555708b6efd9552">AddrOffsets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6828d3ba2ebf768bdc468f08f533bae1">AddrInfoOffsets</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55f4ce39eb9fbdb97ea4adc39bd8a44f">Files</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/gsym/stringtable">StringTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b3522d26e6a48eb0c25aa56743fc88">StrTab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; SwappedData &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab670812ee49d3c5217d14a2a99544252">Swap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc6f8b4a312834f3683fa1a90bda0ed">openFile</a> (StringRef Path)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> from a file on disk. <a href="#a3cc6f8b4a312834f3683fa1a90bda0ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2040abae29e3f6423e313d74955aa1c">copyBuffer</a> (StringRef Bytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> from a buffer. <a href="#ad2040abae29e3f6423e313d74955aa1c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">llvm::gsym::GsymReader</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1ce9ad5cf608cfe2cad31ba38cf22f">create</a> (std::unique_ptr&lt; MemoryBuffer &gt; &amp;MemBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a GSYM from a memory buffer. <a href="#ada1ce9ad5cf608cfe2cad31ba38cf22f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> is used to read GSYM data from a file or buffer.</p>


<p>This class is optimized for very quick lookups when the endianness matches the host system. The <a href="/web-llvm/docs/api/structs/llvm/gsym/header">Header</a>, address table, address info offsets, and file table is designed to be mmap'ed as read only into memory and used without any parsing needed. If the endianness doesn't match, we swap these objects and tables into GsymReader::SwappedData and then point our header and ArrayRefs to this swapped internal data.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> objects must use one of the static functions to create an instance: GsymReader::openFile(...) and GsymReader::copyBuffer(...).</p>


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GsymReader() {#acfb8ec46232ad9d3b2b2d8a3d2b8f6cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GsymReader::GsymReader (<a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> &amp;&amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### GsymReader() {#a8396b98fae621a66af7cd9009728e0a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GsymReader::GsymReader (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; Buffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GsymReader() {#a6de836822f59f466c4ba2e5af57284e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GsymReader::~GsymReader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a2c4724c06d85bc195e23612de85f6774}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the entire Gsym data contained in this object.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 383 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>, <a href="#a462b4c7171102d060094e578596c23c2">getAddress</a>, <a href="#a25ce2405debe5fa88ce06de770ce4bf0">getFile</a>, <a href="#ae699d115f9699264b670c60d4f57d394">getFunctionInfoAtIndex</a>, <a href="#a8e7d9a0bf21c853ef7f5efb1219e4721">getHeader</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#ad9fd7a73c45fec3c647590738cef3fc9">HEX32</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#abedaa94d52e9958ad4a0d3790d0e4451">HEX64</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#ae56c0257076bd0b9c1a4f42671eb03f0">llvm::gsym::Header::NumAddresses</a>.</p>


<p>Referenced by <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>, <a href="#aba0602c835ed2f449b723d5bf57d2eda">dump</a>, <a href="#a000318afaccf51b9e411d4890c4a1231">dump</a>, <a href="#a60b4742db7fd8558ba9138277c44bf22">dump</a>, <a href="#a33125921f2e76880e7ad9ab30c9dfca2">dump</a> and <a href="#a4e9110bbf8007555e8e6b1135609d4d7">dump</a>.</p>

</div>
</div>

### dump() {#a000318afaccf51b9e411d4890c4a1231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &amp; FI, uint32_t Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object.</p>


<p>This function will convert any string table indexes and file indexes into human readable format.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FI</td>
<td class="doxyParamItemDescription"><p>The object to dump.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Indent</td>
<td class="doxyParamItemDescription"><p>The indentation as number of spaces. Used when dumping as an item within <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 438 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a43fc767894ca96f7054ed1308b52ac0f">llvm::gsym::FunctionInfo::CallSites</a>, <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>, <a href="#a65ec9133639d066dcf6843b1fc3ae79c">getString</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a03451bd54bbf81c015e178fea619ca5f">llvm::gsym::FunctionInfo::Inline</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a03611a5afc9cc137c5d0550d9e0a06f1">llvm::gsym::FunctionInfo::MergedFunctions</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aa80935f98fcef212e4a50f81732eb645">llvm::gsym::FunctionInfo::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aca03bd4694755ceb052d01df2cc3af82">llvm::gsym::FunctionInfo::OptLineTable</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a102aa70a223f40f43c99d916bc69a603">llvm::gsym::FunctionInfo::Range</a>.</p>

</div>
</div>

### dump() {#a4e9110bbf8007555e8e6b1135609d4d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> &amp; MFI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object.</p>


<p>This function will dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> object - basically by dumping the contained <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects with indentation.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MFI</td>
<td class="doxyParamItemDescription"><p>The object to dump.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#ae75acbb7c5b01b67f75181b26cfe11a6">llvm::gsym::MergedFunctionsInfo::MergedFunctions</a>.</p>

</div>
</div>

### dump() {#a40a7cf3120a64f2f2e563bc820b9d846}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> &amp; CSI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object.</p>


<p>This function will output the details of a <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object in a human-readable format.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CSI</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> object to dump.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 463 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo/#aced76967548a86d559ae0b349755c0f7ae0cc01e472339cb43229324899820e47">llvm::gsym::CallSiteInfo::ExternalCall</a>, <a href="#a65ec9133639d066dcf6843b1fc3ae79c">getString</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#a6f2782880e58ec7350a0c4c364c3f635">HEX16</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo/#aced76967548a86d559ae0b349755c0f7a6df5bef433fbaea29a0f93375ffebc36">llvm::gsym::CallSiteInfo::InternalCall</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo/#a04c72564fa58d17a8082073d5efcf101">llvm::gsym::CallSiteInfo::MatchRegex</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo/#aced76967548a86d559ae0b349755c0f7a1e0e4b3343db783006649575e4a9b7ef">llvm::gsym::CallSiteInfo::None</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo/#a26c0bff4e03d1b8593ffd2590c20efcb">llvm::gsym::CallSiteInfo::ReturnOffset</a>.</p>

</div>
</div>

### dump() {#aba0602c835ed2f449b723d5bf57d2eda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection">CallSiteInfoCollection</a> &amp; CSIC, uint32_t Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection">CallSiteInfoCollection</a> object.</p>


<p>This function will iterate over a collection of <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> objects and dump each one.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">CSIC</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection">CallSiteInfoCollection</a> object to dump.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Indent</td>
<td class="doxyParamItemDescription"><p>The indentation as number of spaces. Used when dumping as an item from within <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection/#a3d5d409c866a7de92877f77cb8f638de">llvm::gsym::CallSiteInfoCollection::CallSites</a>, <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>

</div>
</div>

### dump() {#a33125921f2e76880e7ad9ab30c9dfca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> &amp; LT, uint32_t Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> object.</p>


<p>This function will convert any string table indexes and file indexes into human readable format.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">LT</td>
<td class="doxyParamItemDescription"><p>The object to dump.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Indent</td>
<td class="doxyParamItemDescription"><p>The indentation as number of spaces. Used when dumping as an item from within <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>, <a href="#a25ce2405debe5fa88ce06de770ce4bf0">getFile</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h/#abedaa94d52e9958ad4a0d3790d0e4451">HEX64</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>

</div>
</div>

### dump() {#a60b4742db7fd8558ba9138277c44bf22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &amp; II, uint32_t Indent=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> object.</p>


<p>This function will convert any string table indexes and file indexes into human readable format.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">II</td>
<td class="doxyParamItemDescription"><p>The object to dump.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Indent</td>
<td class="doxyParamItemDescription"><p>The indentation as number of spaces. Used for recurive dumping.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 252 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>, <a href="#a25ce2405debe5fa88ce06de770ce4bf0">getFile</a>, <a href="#a65ec9133639d066dcf6843b1fc3ae79c">getString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>

</div>
</div>

### dump() {#ac0c87bb82a7b90da0291671f18e9f8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymReader::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> &gt; FE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump a <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> object.</p>


<p>This function will convert any string table indexes into human readable format.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>The output stream to dump to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FE</td>
<td class="doxyParamItemDescription"><p>The object to dump.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 537 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="#a65ec9133639d066dcf6843b1fc3ae79c">getString</a>.</p>

</div>
</div>

### getAddress() {#a462b4c7171102d060094e578596c23c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; GsymReader::getAddress (size_t Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets an address from the address table.</p>


<p>Addresses are stored as offsets frrom the <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#af3a0fa4fd0587b1bcb2e1979bbe3c747">gsym::Header::BaseAddress</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Index</td>
<td class="doxyParamItemDescription"><p>A index into the address table.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A resolved virtual address for adddress in the address table or std::nullopt if Index is out of bounds.</p></dd>
</dl>


<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>Reference <a href="#a938be134329f4243053d957980a79724">addressForIndex</a>.</p>


<p>Referenced by <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a> and <a href="#aa167494fa5d265faa5315612cd3d37fe">getFunctionInfoDataAtIndex</a>.</p>

</div>
</div>

### getFile() {#a25ce2405debe5fa88ce06de770ce4bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; FileEntry &gt; llvm::gsym::GsymReader::getFile (uint32_t Index)</td>
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

<p>Get the a file entry for the suppplied file index.</p>


<p>Used to convert any file indexes in the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> data back into files. This function can be used for iteration, but is more commonly used for random access when doing lookups.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Index</td>
<td class="doxyParamItemDescription"><p>An index into the file table.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An optional FileInfo that will be valid if the file index is valid, or std::nullopt if the file index is out of bounds,</p></dd>
</dl>


<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<p>Referenced by <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>, <a href="#a60b4742db7fd8558ba9138277c44bf22">dump</a>, <a href="#a33125921f2e76880e7ad9ab30c9dfca2">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>

</div>
</div>

### getFunctionInfo() {#a891f5398a526e0de9d2b5006559ef594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; FunctionInfo &gt; GsymReader::getFunctionInfo (uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the full function info for an address.</p>


<p>This should be called when a client will store a copy of the complete <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> for a given address. For one off lookups, use the <a href="#ad5768ee08d5c7c9b431387ce9b03a6e9">lookup()</a> function below.</p>


<p>Symbolication server processes might want to parse the entire function info for a given address and cache it if the process stays around to service many symbolication addresses, like for parsing profiling information.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>A virtual address from the orignal object file to lookup.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> that contains the function info object or an error object that indicates reason for failing to lookup the address.</p></dd>
</dl>


<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aea38a34c36c8f1cb37754bd3bd336053">llvm::gsym::FunctionInfo::decode</a> and <a href="#af15b2b0c7e2abba2d3e36989685d800f">getFunctionInfoDataForAddress</a>.</p>

</div>
</div>

### getFunctionInfoAtIndex() {#ae699d115f9699264b670c60d4f57d394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; FunctionInfo &gt; GsymReader::getFunctionInfoAtIndex (uint64_t AddrIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the full function info given an address index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AddrIdx</td>
<td class="doxyParamItemDescription"><p>A address index for an address in the address table.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> that contains the function info object or an error object that indicates reason for failing get the function info object.</p></dd>
</dl>


<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 329 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#aea38a34c36c8f1cb37754bd3bd336053">llvm::gsym::FunctionInfo::decode</a> and <a href="#aa167494fa5d265faa5315612cd3d37fe">getFunctionInfoDataAtIndex</a>.</p>


<p>Referenced by <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>.</p>

</div>
</div>

### getHeader() {#a8e7d9a0bf21c853ef7f5efb1219e4721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Header &amp; GsymReader::getHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Access the GSYM header.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A native endian version of the GSYM header.</p></dd>
</dl>


<p>Declaration at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>


<p>Referenced by <a href="#a2c4724c06d85bc195e23612de85f6774">dump</a>.</p>

</div>
</div>

### getNumAddresses() {#a35ec8760c2d3f45a812020c7e19f25da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::GsymReader::getNumAddresses ()</td>
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

<p>Get the number of addresses in this Gsym file.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<p>Referenced by <a href="#aa167494fa5d265faa5315612cd3d37fe">getFunctionInfoDataAtIndex</a> and <a href="#af15b2b0c7e2abba2d3e36989685d800f">getFunctionInfoDataForAddress</a>.</p>

</div>
</div>

### getString() {#a65ec9133639d066dcf6843b1fc3ae79c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::gsym::GsymReader::getString (uint32_t Offset)</td>
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

<p>Get a string from the string table.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The string table offset for the string to retrieve.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The string from the strin table.</p></dd>
</dl>


<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a40a7cf3120a64f2f2e563bc820b9d846">dump</a>, <a href="#a000318afaccf51b9e411d4890c4a1231">dump</a>, <a href="#a60b4742db7fd8558ba9138277c44bf22">dump</a>, <a href="#ac0c87bb82a7b90da0291671f18e9f8cd">dump</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/inlineinfo-cpp/#a5db99f4b7f8744e0b1c8b50dba8ec5a2">lookup</a>.</p>

</div>
</div>

### lookup() {#ad5768ee08d5c7c9b431387ce9b03a6e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; LookupResult &gt; GsymReader::lookup (uint64_t Addr, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &gt; * MergedFuncsData=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lookup an address in the a GSYM.</p>


<p>Lookup just the information needed for a specific address <em>Addr</em>. This function is faster that calling <a href="#a891f5398a526e0de9d2b5006559ef594">getFunctionInfo()</a> as it will only return information that pertains to <em>Addr</em> and allows the parsing to skip any extra information encoded for other addresses. For example the line table parsing can stop when a matching <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry">LineEntry</a> has been fouhnd, and the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> can stop parsing early once a match has been found and also skip information that doesn't match. This avoids memory allocations and is much faster for lookups.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>A virtual address from the orignal object file to lookup.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">MergedFuncsData</td>
<td class="doxyParamItemDescription"><p>A pointer to an optional <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> that, if non-null, will be set to the raw data of the MergedFunctionInfo, if present.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a> that contains only the information needed for the current address, or an error object that indicates reason for failing to lookup the address.</p></dd>
</dl>


<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="#af15b2b0c7e2abba2d3e36989685d800f">getFunctionInfoDataForAddress</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>.</p>


<p>Referenced by <a href="#afab544245beb837bd2fd89c12e060c3f">lookupAll</a>.</p>

</div>
</div>

### lookupAll() {#afab544245beb837bd2fd89c12e060c3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::vector&lt; LookupResult &gt; &gt; GsymReader::lookupAll (uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Lookup all merged functions for a given address.</p>


<p>This function performs a lookup for the specified address and then retrieves additional LookupResults from any merged functions associated with the primary <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>The address to lookup.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A vector of <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a> objects, where the first element is the primary result, followed by results for any merged functions</p></dd>
</dl>


<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#a494857c857bfb2ff33cc151c34c200d1">llvm::gsym::MergedFunctionsInfo::getFuncsDataExtractors</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a5d896568c18192e090d13f4831e4abb1">llvm::gsym::FunctionInfo::lookup</a>, <a href="#ad5768ee08d5c7c9b431387ce9b03a6e9">lookup</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/aliasanalysis-cpp/#a7e344cff0feadf0b02223fee63cc7475">Results</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### addressForIndex() {#a938be134329f4243053d957980a79724}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::gsym::GsymReader::addressForIndex (size_t Index)</td>
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

<p>Get an appropriate address from the address table.</p>


<p>The address table in the GSYM file is stored as array of 1, 2, 4 or 8 byte address offsets from the The <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#af3a0fa4fd0587b1bcb2e1979bbe3c747">gsym::Header::BaseAddress</a>. The table is stored internally as a array of bytes that are in the correct endianness. In order to extract an address from the address table we must access the address offset using the correct size and then add it to the BaseAddress in the header.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Index</td>
<td class="doxyParamItemDescription"><p>An index into the AddrOffsets array.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An virtual address that matches the original object file for the address as the specified index, or std::nullopt if Index is out of bounds.</p></dd>
</dl>


<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<p>References <a href="#a572a0897fc07913ec396452f99efa704">getAddrOffsets</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a462b4c7171102d060094e578596c23c2">getAddress</a>.</p>

</div>
</div>

### getAddressIndex() {#ab9572a95e4bc84fe4b9d8294cd81d30d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint64_t &gt; GsymReader::getAddressIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t Addr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an address, find the address index.</p>


<p>Binary search the address table and find the matching address index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>A virtual address that matches the original object file to lookup.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An index into the address table. This index can be used to extract the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> data's offset from the AddrInfoOffsets array. Returns an error if the address isn't in the GSYM with details of why.</p></dd>
</dl>


<p>Declaration at line 375 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="#afe6e63cc76f08a5400707ae311ca1cfd">getAddressOffsetIndex</a>.</p>


<p>Referenced by <a href="#af15b2b0c7e2abba2d3e36989685d800f">getFunctionInfoDataForAddress</a>.</p>

</div>
</div>

### getAddressInfoOffset() {#a4fcb3aee09b8523cef4a80c620f87366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; GsymReader::getAddressInfoOffset (size_t Index)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an address index, get the offset for the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>.</p>


<p>Looking up an address is done by finding the corresponding address index for the address. This index is then used to get the offset of the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> data that we will decode using this function.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Index</td>
<td class="doxyParamItemDescription"><p>An index into the address table.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An optional GSYM data offset for the offset of the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> that needs to be decoded.</p></dd>
</dl>


<p>Declaration at line 386 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>

</div>
</div>

### getAddressOffsetIndex() {#afe6e63cc76f08a5400707ae311ca1cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::gsym::GsymReader::getAddressOffsetIndex (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t AddrOffset)</td>
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

<p>Lookup an address offset in the AddrOffsets table.</p>


<p>Given an address offset, look it up using a binary search of the AddrOffsets table.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AddrOffset</td>
<td class="doxyParamItemDescription"><p>An address offset, that has already been computed by subtracting the <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#af3a0fa4fd0587b1bcb2e1979bbe3c747">gsym::Header::BaseAddress</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The matching address offset index. This index will be used to extract the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> data's offset from the AddrInfoOffsets array.</p></dd>
</dl>


<p>Definition at line 326 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a> and <a href="#a572a0897fc07913ec396452f99efa704">getAddrOffsets</a>.</p>


<p>Referenced by <a href="#ab9572a95e4bc84fe4b9d8294cd81d30d">getAddressIndex</a>.</p>

</div>
</div>

### getAddrOffsets() {#a572a0897fc07913ec396452f99efa704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; T &gt; llvm::gsym::GsymReader::getAddrOffsets ()</td>
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

<p>Get an appropriate address info offsets array.</p>


<p>The address table in the GSYM file is stored as array of 1, 2, 4 or 8 byte offsets from the The <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#af3a0fa4fd0587b1bcb2e1979bbe3c747">gsym::Header::BaseAddress</a>. The table is stored internally as a array of bytes that are in the correct endianness. When we access this table we must get an array that matches those sizes. This templatized helper function is used when accessing address offsets in the AddrOffsets member variable.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a> of an appropriate address offset size.</p></dd>
</dl>


<p>Definition at line 291 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a938be134329f4243053d957980a79724">addressForIndex</a> and <a href="#afe6e63cc76f08a5400707ae311ca1cfd">getAddressOffsetIndex</a>.</p>

</div>
</div>

### getFunctionInfoDataAtIndex() {#aa167494fa5d265faa5315612cd3d37fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; DataExtractor &gt; GsymReader::getFunctionInfoDataAtIndex (uint64_t AddrIdx, uint64_t &amp; FuncStartAddr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the function data and address given an address index.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">AddrIdx</td>
<td class="doxyParamItemDescription"><p>A address index from the address table.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> that contains the function info object or an error object that indicates reason for failing to lookup the address.</p></dd>
</dl>


<p>Declaration at line 418 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 299 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbad861877da56b8b4ceb35c8cbfdf65bb4">llvm::big</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="#a462b4c7171102d060094e578596c23c2">getAddress</a>, <a href="#a35ec8760c2d3f45a812020c7e19f25da">getNumAddresses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dbaaae6635e044ac56046b2893a529b5114">llvm::little</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a25f1fd81f2132805676c82ab8ae0c109">llvm::StringRef::substr</a>.</p>


<p>Referenced by <a href="#ae699d115f9699264b670c60d4f57d394">getFunctionInfoAtIndex</a> and <a href="#af15b2b0c7e2abba2d3e36989685d800f">getFunctionInfoDataForAddress</a>.</p>

</div>
</div>

### getFunctionInfoDataForAddress() {#af15b2b0c7e2abba2d3e36989685d800f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; DataExtractor &gt; GsymReader::getFunctionInfoDataForAddress (uint64_t Addr, uint64_t &amp; FuncStartAddr)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an address, find the correct function info data and function address.</p>


<p>Binary search the address table and find the matching address info and make sure that the function info contains the address. GSYM allows functions to overlap, and the most debug info is contained in the first entries due to the sorting when GSYM files are created. We can have multiple function info that start at the same address only if their address range doesn't match. So find the first entry that matches <em>Addr</em> and iterate forward until we find one that contains the address.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] Addr</td>
<td class="doxyParamItemDescription"><p>A virtual address that matches the original object file to lookup.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] FuncStartAddr</td>
<td class="doxyParamItemDescription"><p>A virtual address that is the base address of the function that is used for decoding the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An valid data extractor on success, or an error if we fail to find the address in a function info or corrrectly decode the data</p></dd>
</dl>


<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/value-cpp/#a34433c37334a1cde3d58cde3099257dd">contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#ab9572a95e4bc84fe4b9d8294cd81d30d">getAddressIndex</a>, <a href="#aa167494fa5d265faa5315612cd3d37fe">getFunctionInfoDataAtIndex</a>, <a href="#a35ec8760c2d3f45a812020c7e19f25da">getNumAddresses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a891f5398a526e0de9d2b5006559ef594">getFunctionInfo</a> and <a href="#ad5768ee08d5c7c9b431387ce9b03a6e9">lookup</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### parse() {#ac84c32841bd9b8176df41f9afff85c4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error GsymReader::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AddrInfoOffsets {#a6828d3ba2ebf768bdc468f08f533bae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint32_t&gt; llvm::gsym::GsymReader::AddrInfoOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 53 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### AddrOffsets {#a324ca1de3325ad321555708b6efd9552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;uint8_t&gt; llvm::gsym::GsymReader::AddrOffsets</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### Endian {#af8d12edac5b9fc6cf17ab94d7aa6732d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::endianness llvm::gsym::GsymReader::Endian</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### Files {#a55f4ce39eb9fbdb97ea4adc39bd8a44f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt;FileEntry&gt; llvm::gsym::GsymReader::Files</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### GsymBytes {#a555e6db794ee577eef1925e500873978}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::gsym::GsymReader::GsymBytes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### Hdr {#ac748c9eb8e6533296efd0cd3e5853670}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Header* llvm::gsym::GsymReader::Hdr = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### MemBuffer {#acad5db4c26dab79d637ad82335033cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::gsym::GsymReader::MemBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### StrTab {#aa2b3522d26e6a48eb0c25aa56743fc88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTable llvm::gsym::GsymReader::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

### Swap {#ab670812ee49d3c5217d14a2a99544252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SwappedData&gt; llvm::gsym::GsymReader::Swap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### copyBuffer() {#ad2040abae29e3f6423e313d74955aa1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; GsymReader &gt; GsymReader::copyBuffer (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Bytes)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> from a buffer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bytes</td>
<td class="doxyParamItemDescription"><p>A set of bytes that will be copied and owned by the returned object on success.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> that contains the object or an error object that indicates reason for failing to read the GSYM.</p></dd>
</dl>


<p>Declaration at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="#ada1ce9ad5cf608cfe2cad31ba38cf22f">create</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a>.</p>

</div>
</div>

### openFile() {#a3cc6f8b4a312834f3683fa1a90bda0ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; GsymReader &gt; GsymReader::openFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path)</td>
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

<p>Construct a <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> from a file on disk.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path</td>
<td class="doxyParamItemDescription"><p>The file path the GSYM file to read.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> that contains the object or an error object that indicates reason for failing to read the GSYM.</p></dd>
</dl>


<p>Declaration at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>References <a href="#ada1ce9ad5cf608cfe2cad31ba38cf22f">create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a7903f14c3b4fb5b4f9f9fa8b4ee0b4eb">llvm::ErrorOr&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a> and <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a9c54e2428ad0163441789c281ca42ee4">llvm::MemoryBuffer::getFileOrSTDIN</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ac40e6efe1caf07771eb6713f41db076b">llvm::gsym::DwarfTransformer::verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Static Functions

### create() {#ada1ce9ad5cf608cfe2cad31ba38cf22f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; llvm::gsym::GsymReader &gt; GsymReader::create (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; &amp; MemBuffer)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a GSYM from a memory buffer.</p>


<p>Called by both <a href="#a3cc6f8b4a312834f3683fa1a90bda0ed">openFile()</a> and <a href="#ad2040abae29e3f6423e313d74955aa1c">copyBuffer()</a>, this function does all of the work of parsing the GSYM file and returning an error.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">MemBuffer</td>
<td class="doxyParamItemDescription"><p>A memory buffer that will transfer ownership into the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> that contains the object or an error object that indicates reason for failing to read the GSYM.</p></dd>
</dl>


<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a>, definition at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>.</p>


<p>Referenced by <a href="#ad2040abae29e3f6423e313d74955aa1c">copyBuffer</a> and <a href="#a3cc6f8b4a312834f3683fa1a90bda0ed">openFile</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymreader-h">GsymReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymreader-cpp">GsymReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
