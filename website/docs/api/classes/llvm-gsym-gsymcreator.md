---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/gsymcreator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `GsymCreator` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> is used to emit GSYM data to a stand alone file or section within a file. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::gsym::GsymCreator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">llvm/DebugInfo/GSYM/GsymCreator.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af85ae9f6e8c014d57c9b61519dcadcbd">GsymCreator</a> (bool Quiet=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c4f8122cf59952849b4d8184df118dc">save</a> (StringRef Path, llvm::endianness ByteOrder, std::optional&lt; uint64_t &gt; SegmentSize=std::nullopt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save a GSYM file to a stand alone file. <a href="#a5c4f8122cf59952849b4d8184df118dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ede3510dd3c4a79112fd4ff9048e04b">encode</a> (FileWriter &amp;O) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode a GSYM into the file writer stream at the current position. <a href="#a9ede3510dd3c4a79112fd4ff9048e04b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22638e32cb1220ddfacd7eb1bc5dfcf5">insertString</a> (StringRef S, bool Copy=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a string into the GSYM string table. <a href="#a22638e32cb1220ddfacd7eb1bc5dfcf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9614258b67dc42d2f0708464bddc96dd">getString</a> (uint32_t Offset)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve a string from the GSYM string table given its offset. <a href="#a9614258b67dc42d2f0708464bddc96dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9372d27c9fb107c96a7b241848d05ed">insertFile</a> (StringRef Path, sys::path::Style Style=sys::path::Style::native)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert a file into this GSYM creator. <a href="#ac9372d27c9fb107c96a7b241848d05ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0255c904a2083824db32c67a98520742">addFunctionInfo</a> (FunctionInfo &amp;&amp;FI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a function info to this GSYM creator. <a href="#a0255c904a2083824db32c67a98520742">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e3037da68715a480cd7b1996f5737a8">loadCallSitesFromYAML</a> (StringRef YAMLFile)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Load call site information from a YAML file. <a href="#a9e3037da68715a480cd7b1996f5737a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ff8f5a82defa914ab5037231e289055">prepareMergedFunctions</a> (OutputAggregator &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Organize merged <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s. <a href="#a7ff8f5a82defa914ab5037231e289055">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdaa5c17b22848e0de64e78984c8d07c">finalize</a> (OutputAggregator &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Finalize the data in the GSYM creator prior to saving the data out. <a href="#abdaa5c17b22848e0de64e78984c8d07c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab85ea74b3cb2aeabcf765b1892ff9d91">setUUID</a> (llvm::ArrayRef&lt; uint8_t &gt; UUIDBytes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> value. <a href="#ab85ea74b3cb2aeabcf765b1892ff9d91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af56844c4beded9856bac60a414e9e998">forEachFunctionInfo</a> (std::function&lt; bool(FunctionInfo &amp;)&gt; const &amp;Callback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Thread safe iteration over all function infos. <a href="#af56844c4beded9856bac60a414e9e998">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4030597c6be78b2eb79b02a4d827e1">forEachFunctionInfo</a> (std::function&lt; bool(const FunctionInfo &amp;)&gt; const &amp;Callback) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Thread safe const iteration over all function infos. <a href="#a5e4030597c6be78b2eb79b02a4d827e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adebfdaa4b1b4fa505e9b9b8b91693704">getNumFunctionInfos</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the current number of <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects contained in this object. <a href="#adebfdaa4b1b4fa505e9b9b8b91693704">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c47f7d5f05e3c9778d24ad91e5e7c7">SetValidTextRanges</a> (AddressRanges &amp;TextRanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set valid .text address ranges that all functions must be contained in. <a href="#ac3c47f7d5f05e3c9778d24ad91e5e7c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ef9c30d1566dd46fc54265f960ed1e4">GetValidTextRanges</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the valid text ranges. <a href="#a3ef9c30d1566dd46fc54265f960ed1e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed7eb12c998221cb39a6a3d96e9a0e56">IsValidTextAddress</a> (uint64_t Addr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an address is a valid code address. <a href="#aed7eb12c998221cb39a6a3d96e9a0e56">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a20d5b08d026255dd9f7f7473cfe89b">setBaseAddress</a> (uint64_t Addr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the base address to use for the GSYM file. <a href="#a3a20d5b08d026255dd9f7f7473cfe89b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf2698c4afe7c309bcae39e29649586b">isQuiet</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether the transformation should be quiet, i.e. not output warnings. <a href="#aaf2698c4afe7c309bcae39e29649586b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a00b6c05d78359948c41de0ee1f20a4">createSegment</a> (uint64_t SegmentSize, size_t &amp;FuncIdx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a segmented GSYM creator starting with function info index <em>FuncIdx</em>. <a href="#a5a00b6c05d78359948c41de0ee1f20a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91dba24214a5f73e6905051a606f2456">getFirstFunctionAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the first function start address. <a href="#a91dba24214a5f73e6905051a606f2456">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcabc5c0ba02a9d4fa852a1b3ffbe653">getLastFunctionAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the last function address. <a href="#abcabc5c0ba02a9d4fa852a1b3ffbe653">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea6e7922d95ba749dc5b28502865be1a">getBaseAddress</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the base address to use for this GSYM file. <a href="#aea6e7922d95ba749dc5b28502865be1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec7f87095214d476f4c125e835bcc542">getAddressOffsetSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of an address offset in the address offset table. <a href="#aec7f87095214d476f4c125e835bcc542">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab79b32a605ddd551d253675b502501d9">getMaxAddressOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the maximum address offset for the current address offset size. <a href="#ab79b32a605ddd551d253675b502501d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184a8738d7e06598e2b134fbe8de1db5">calculateHeaderAndTableSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Calculate the byte size of the GSYM header and tables sizes. <a href="#a184a8738d7e06598e2b134fbe8de1db5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23d03be9f14030b4c9c15d3af3828eb9">copyFunctionInfo</a> (const GsymCreator &amp;SrcGC, size_t FuncInfoIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> from the <em>SrcGC</em> GSYM creator into this creator. <a href="#a23d03be9f14030b4c9c15d3af3828eb9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af34f501dde106b375256acc90dbd4722">copyString</a> (const GsymCreator &amp;SrcGC, uint32_t StrOff)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a string from <em>SrcGC</em> into this object. <a href="#af34f501dde106b375256acc90dbd4722">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4ed17972f32e1e1c433dfab2f9b3234">copyFile</a> (const GsymCreator &amp;SrcGC, uint32_t FileIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy a file from <em>SrcGC</em> into this object. <a href="#ac4ed17972f32e1e1c433dfab2f9b3234">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa16f9ffdff258d3535649550fb07f2bd">insertFileEntry</a> (FileEntry FE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inserts a <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> into the file table. <a href="#aa16f9ffdff258d3535649550fb07f2bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110e3e5b5679107f83e06d0f20396bab">fixupInlineInfo</a> (const GsymCreator &amp;SrcGC, InlineInfo &amp;II)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fixup any string and file references by updating any file indexes and strings offsets in the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> parameter. <a href="#a110e3e5b5679107f83e06d0f20396bab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a275c1ae3dda520ae8831fea5fefd346b">saveSegments</a> (StringRef Path, llvm::endianness ByteOrder, uint64_t SegmentSize) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Save this GSYM file into segments that are roughly <em>SegmentSize</em> in size. <a href="#a275c1ae3dda520ae8831fea5fefd346b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad94f4001e614cf2e16b880a974f6f5cf">setIsSegment</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Let this creator know that this is a segment of another <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>. <a href="#ad94f4001e614cf2e16b880a974f6f5cf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2a3052a487317850c3aaa8eb27cc56">Mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a16f49bae614c3976349a1ff08b803f">Funcs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringtablebuilder">StringTableBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6da00e5dd1b290512db1b4e4b47ddc2b">StrTab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringset">StringSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a8689714862f3de5b1dd31bd22ed446">StringStorage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">llvm::gsym::FileEntry</a>, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86b0a15e3307f6176548130886919b4b">FileEntryToIndex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; uint64_t, <a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref">CachedHashStringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d272dc332c48251f3a30ef31589eb5">StringOffsetMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">llvm::gsym::FileEntry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12c2a779adebc0ebde5f392805329ac0">Files</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; uint8_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88af2aa58192684bbf3ab31ba1ef63c7">UUID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e4bda0571853dabfa136714abb880d">ValidTextRanges</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dfc2665bf21ffe0f3b0fee2748e3c8d">BaseAddress</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1112fe4df5ef2743964805fdb454f573">IsSegment</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3befc4512b386daee2cc9e4c6be89f25">Finalized</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7866fcd54b3f2ff23de3313735dfd2e">Quiet</a></td>
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

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> is used to emit GSYM data to a stand alone file or section within a file.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> is designed to be used in 3 stages:</p>


<ul class="doxyList ">
<li>Create <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects and add them</li>
<li>Finalize the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> object</li>
<li>Save to file or section</li>
</ul>

<p>The first stage involves creating <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects from another source of information like compiler debug info metadata, DWARF or Breakpad files. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> strings in the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> or contained information, like <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> or <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> objects, should get the string table offsets by calling GsymCreator::insertString(...). <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> file indexes that are needed should be obtained by calling GsymCreator::insertFile(...). All of the function calls in <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> are thread safe. This allows multiple threads to create and add <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects while parsing debug information.</p>


<p>Once all of the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects have been added, the GsymCreator::finalize(...) must be called prior to saving. This function will sort the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects, finalize the string table, and do any other passes on the information needed to prepare the information to be saved.</p>


<p>Once the object has been finalized, it can be saved to a file or section.</p>


<p>ENCODING</p>


<p>GSYM files are designed to be memory mapped into a process as shared, read only data, and used as is.</p>


<p>The GSYM file format when in a stand alone file consists of:</p>


<ul class="doxyList ">
<li><a href="/web-llvm/docs/api/structs/llvm/gsym/header">Header</a></li>
<li>Address Table</li>
<li><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Info Offsets</li>
<li>File Table</li>
<li>String Table</li>
<li><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Info Data</li>
</ul>

<p>HEADER</p>


<p>The header is fully described in "llvm/DebugInfo/GSYM/Header.h".</p>


<p>ADDRESS TABLE</p>


<p>The address table immediately follows the header in the file and consists of <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#ae56c0257076bd0b9c1a4f42671eb03f0">Header.NumAddresses</a> address offsets. These offsets are sorted and can be binary searched for efficient lookups. Addresses in the address table are stored as offsets from a 64 bit base address found in <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#af3a0fa4fd0587b1bcb2e1979bbe3c747">Header.BaseAddress</a>. This allows the address table to contain 8, 16, or 32 offsets. This allows the address table to not require full 64 bit addresses for each address. The resulting GSYM size is smaller and causes fewer pages to be touched during address lookups when the address table is smaller. The size of the address offsets in the address table is specified in the header in <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a34f83b8e1b9a91f2e306a9d0df969a5b">Header.AddrOffSize</a>. The first offset in the address table is aligned to <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a34f83b8e1b9a91f2e306a9d0df969a5b">Header.AddrOffSize</a> alignment to ensure efficient access when loaded into memory.</p>


<p>FUNCTION INFO OFFSETS TABLE</p>


<p>The function info offsets table immediately follows the address table and consists of <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#ae56c0257076bd0b9c1a4f42671eb03f0">Header.NumAddresses</a> 32 bit file offsets: one for each address in the address table. This data is aligned to a 4 byte boundary. The offsets in this table are the relative offsets from the start offset of the GSYM header and point to the function info data for each address in the address table. Keeping this data separate from the address table helps to reduce the number of pages that are touched when address lookups occur on a GSYM file.</p>


<p>FILE TABLE</p>


<p>The file table immediately follows the function info offsets table. The encoding of the FileTable is:</p>


<p>struct FileTable { uint32_t Count; <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> Files[]; };</p>


<p>The file table starts with a 32 bit count of the number of files that are used in all of the function info, followed by that number of <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> structures. The file table is aligned to a 4 byte boundary, Each file in the file table is represented with a <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> structure. See "llvm/DebugInfo/GSYM/FileEntry.h" for details.</p>


<p>STRING TABLE</p>


<p>The string table follows the file table in stand alone GSYM files and contains all strings for everything contained in the GSYM file. <a href="/web-llvm/docs/api/classes/llvm/any">Any</a> string data should be added to the string table and any references to strings inside GSYM information must be stored as 32 bit string table offsets into this string table. The string table always starts with an empty string at offset zero and is followed by any strings needed by the GSYM information. The start of the string table is not aligned to any boundary.</p>


<p>FUNCTION INFO DATA</p>


<p>The function info data is the payload that contains information about the address that is being looked up. It contains all of the encoded <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects. Each encoded <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s data is pointed to by an entry in the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> Info Offsets Table. For details on the exact encoding of <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects, see "llvm/DebugInfo/GSYM/FunctionInfo.h".</p>


<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GsymCreator() {#af85ae9f6e8c014d57c9b61519dcadcbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GsymCreator::GsymCreator (bool Quiet=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 295 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>Reference <a href="#ac9372d27c9fb107c96a7b241848d05ed">insertFile</a>.</p>


<p>Referenced by <a href="#a5a00b6c05d78359948c41de0ee1f20a4">createSegment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFunctionInfo() {#a0255c904a2083824db32c67a98520742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymCreator::addFunctionInfo (<a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &amp;&amp; FI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a function info to this GSYM creator.</p>


<p>All information in the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object must use the GsymCreator::insertString(...) function when creating string table offsets for names and other strings.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FI</td>
<td class="doxyParamItemDescription"><p>The function info object to emplace into our functions list.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 363 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>.</p>

</div>
</div>

### createSegment() {#a5a00b6c05d78359948c41de0ee1f20a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; std::unique_ptr&lt; GsymCreator &gt; &gt; GsymCreator::createSegment (uint64_t SegmentSize, size_t &amp; FuncIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a segmented GSYM creator starting with function info index <em>FuncIdx</em>.</p>


<p>This function will create a <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> object that will encode into roughly <em>SegmentSize</em> bytes and return it. It is used by the private saveSegments(...) function and also is used by the GSYM unit tests to test segmenting of GSYM files. The returned <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> can be finalized and encoded.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] SegmentSize</td>
<td class="doxyParamItemDescription"><p>The size in bytes to roughly segment the GSYM file into.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] FuncIdx</td>
<td class="doxyParamItemDescription"><p>The index of the first function info to encode into the returned <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>. This index will be updated so it can be used in subsequent calls to this function to allow more segments to be created.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An expected unique pointer to a <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> or an error. The returned unique pointer can be NULL if there are no more functions to encode.</p></dd>
</dl>


<p>Declaration at line 488 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a> and <a href="#af85ae9f6e8c014d57c9b61519dcadcbd">GsymCreator</a>.</p>

</div>
</div>

### encode() {#a9ede3510dd3c4a79112fd4ff9048e04b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error GsymCreator::encode (<a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; O)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode a GSYM into the file writer stream at the current position.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The stream to save the binary data to</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure of the save.</p></dd>
</dl>


<p>Declaration at line 318 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a34f83b8e1b9a91f2e306a9d0df969a5b">llvm::gsym::Header::AddrOffSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#af3a0fa4fd0587b1bcb2e1979bbe3c747">llvm::gsym::Header::BaseAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a976c8e49991502be5186b73cdd2d3589">llvm::gsym::Header::encode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a75a03ed9f8e173b2e923681761f4a3ca">llvm::gsym::GSYM_MAGIC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a7feb3a53720bdec8d221e5ccc76d8e94">llvm::gsym::GSYM_VERSION</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a47ef9e8af3bae7caacb43b16108d03a1">llvm::gsym::Header::Magic</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#ae56c0257076bd0b9c1a4f42671eb03f0">llvm::gsym::Header::NumAddresses</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/amdhsakerneldescriptor-h/#a276e8a32e0bbf024aadd9420b8f2d3b3">offsetof</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a9f8bfadcb63e2bec5eb4e2f897e1c8f8">llvm::gsym::Header::StrtabOffset</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#aaf7da00d25cd0b1ec0e7105d1f15fcaf">llvm::gsym::Header::StrtabSize</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#aa843b4319bce6f5a623cf632db244399">llvm::gsym::Header::UUID</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#ae25e8b83cd8416417a33dd9267cbf4ce">llvm::gsym::Header::UUIDSize</a> and <a href="/web-llvm/docs/api/structs/llvm/gsym/header/#a05be47ccf18c7b121da8d5e2e00c4007">llvm::gsym::Header::Version</a>.</p>


<p>Referenced by <a href="#a5c4f8122cf59952849b4d8184df118dc">save</a>.</p>

</div>
</div>

### finalize() {#abdaa5c17b22848e0de64e78984c8d07c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error GsymCreator::finalize (<a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Finalize the data in the GSYM creator prior to saving the data out.</p>


<p>Finalize must be called after all <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects have been added and before <a href="#a5c4f8122cf59952849b4d8184df118dc">GsymCreator::save()</a> is called.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Output stream to report duplicate function infos, overlapping function infos, and function infos that were merged or removed.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure of the finalize.</p></dd>
</dl>


<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 241 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/addressrange/#accce80061bb85f65b4223c49d91216a0">llvm::AddressRange::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a4e97135bd7730c4555dea03637855e03">llvm::gsym::FunctionInfo::hasRichInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrange/#a978098dc4eb29f90b3e9cbbf09d2c42a">llvm::AddressRange::intersects</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a102aa70a223f40f43c99d916bc69a603">llvm::gsym::FunctionInfo::Range</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a34bd74317e3f04bfc4318c2d1a470877">Range</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#a051eee638f618d1ebe54f433350b7c1d">llvm::gsym::OutputAggregator::Report</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrange/#afe148fdaacb37330c6cfb734abbf610a">llvm::AddressRange::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrange/#a37ab39927de3ceda2cd6766243b516b9">llvm::AddressRange::start</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### forEachFunctionInfo() {#af56844c4beded9856bac60a414e9e998}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymCreator::forEachFunctionInfo (std::function&lt; bool(<a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &amp;)&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Callback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Thread safe iteration over all function infos.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Callback</td>
<td class="doxyParamItemDescription"><p>A callback function that will get called with each <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>. If the callback returns false, stop iterating.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 401 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### forEachFunctionInfo() {#a5e4030597c6be78b2eb79b02a4d827e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymCreator::forEachFunctionInfo (std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &amp;)&gt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> &amp; Callback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Thread safe const iteration over all function infos.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Callback</td>
<td class="doxyParamItemDescription"><p>A callback function that will get called with each <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>. If the callback returns false, stop iterating.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 410 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### getNumFunctionInfos() {#adebfdaa4b1b4fa505e9b9b8b91693704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t GsymCreator::getNumFunctionInfos ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the current number of <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects contained in this object.</p>

<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>.</p>

</div>
</div>

### getString() {#a9614258b67dc42d2f0708464bddc96dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef GsymCreator::getString (uint32_t Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Retrieve a string from the GSYM string table given its offset.</p>


<p>The offset is assumed to be a valid offset into the string table. otherwise an assert will be triggered.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Offset</td>
<td class="doxyParamItemDescription"><p>The offset of the string to retrieve, previously returned by insertString.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The string at the given offset in the string table.</p></dd>
</dl>


<p>Declaration at line 340 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### GetValidTextRanges() {#a3ef9c30d1566dd46fc54265f960ed1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; AddressRanges &gt; llvm::gsym::GsymCreator::GetValidTextRanges ()</td>
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

<p>Get the valid text ranges.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### insertFile() {#ac9372d27c9fb107c96a7b241848d05ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t GsymCreator::insertFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49f">sys::path::Style</a> Style=<a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a58cfd8a47c0ef96db27b451c2d6ec49fa8e5f3adee38c8fccc13c1f3be0143796">sys::path::Style::native</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a file into this GSYM creator.</p>


<p>Inserts a file by adding a <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> into the "Files" member variable if the file has not already been added. The file path is split into directory and filename which are both added to the string table. This allows paths to be stored efficiently by reusing the directories that are common between multiple files.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path</td>
<td class="doxyParamItemDescription"><p>The path to the file to insert.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Style</td>
<td class="doxyParamItemDescription"><p>The path style for the "Path" parameter.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The unique file index for the inserted file.</p></dd>
</dl>


<p>Declaration at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sampleprof/#a702f69807459cc25db5754a5f179d3fcaf6fbeb8fa9f451468611536b00878d41">llvm::sampleprof::Base</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#aa56d25bb5127dd7a5831c25764f76cbe">llvm::sys::path::filename</a>, <a href="#a22638e32cb1220ddfacd7eb1bc5dfcf5">insertString</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/path/#a5326427c87607b2364a1fcdf13fa0eea">llvm::sys::path::parent_path</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/cuinfo/#a44c3e2e1f1513822fef926de568c244f">llvm::gsym::CUInfo::DWARFToGSYMFileIndex</a> and <a href="#af85ae9f6e8c014d57c9b61519dcadcbd">GsymCreator</a>.</p>

</div>
</div>

### insertString() {#a22638e32cb1220ddfacd7eb1bc5dfcf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t GsymCreator::insertString (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> S, bool Copy=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Insert a string into the GSYM string table.</p>


<p>All strings used by GSYM files must be uniqued by adding them to this string pool and using the returned offset for any string values.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">S</td>
<td class="doxyParamItemDescription"><p>The string to insert into the string table.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Copy</td>
<td class="doxyParamItemDescription"><p>If true, then make a backing copy of the string. If false, the string is owned by another object that will stay around long enough for the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> to save the GSYM file.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The unique 32 bit offset into the string table.</p></dd>
</dl>


<p>Declaration at line 330 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 363 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a> and <a href="/web-llvm/docs/api/classes/llvm/cachedhashstringref/#acbd41293942524a54c002b089d2f5c6f">llvm::CachedHashStringRef::hash</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#aa755805a8a835eba37c76377d871d3b0">getQualifiedNameIndex</a> and <a href="#ac9372d27c9fb107c96a7b241848d05ed">insertFile</a>.</p>

</div>
</div>

### isQuiet() {#aaf2698c4afe7c309bcae39e29649586b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::GsymCreator::isQuiet ()</td>
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

<p>Whether the transformation should be quiet, i.e. not output warnings.</p>

<p>Definition at line 466 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### IsValidTextAddress() {#aed7eb12c998221cb39a6a3d96e9a0e56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GsymCreator::IsValidTextAddress (uint64_t Addr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if an address is a valid code address.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/any">Any</a> functions whose addresses do not exist within these function bounds will not be converted into the final GSYM. This allows the object file to figure out the valid file address ranges of all the code sections and ensure we don't add invalid functions to the final output. Many linkers have issues when dead stripping functions from DWARF debug info where they set the DW_AT_low_pc to zero, but newer DWARF has the DW_AT_high_pc as an offset from the DW_AT_low_pc and these size attributes have no relocations that can be applied. This results in DWARF where many functions have an DW_AT_low_pc of zero and a valid offset size for DW_AT_high_pc. If we extract all valid ranges from an object file that are marked with executable permissions, we can properly ensure that these functions are removed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>An address to check.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>True if the address is in the valid text ranges or if no valid text ranges have been set, false otherwise.</p></dd>
</dl>


<p>Declaration at line 448 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>.</p>

</div>
</div>

### loadCallSitesFromYAML() {#a9e3037da68715a480cd7b1996f5737a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error GsymCreator::loadCallSitesFromYAML (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> YAMLFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Load call site information from a YAML file.</p>


<p>This function reads call site information from a specified YAML file and adds it to the GSYM data.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">YAMLFile</td>
<td class="doxyParamItemDescription"><p>The path to the YAML file containing call site information.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 372 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/gsym/callsiteinfoloader/#af96a5f4033bb285a8570b073578aceb1">llvm::gsym::CallSiteInfoLoader::loadYAML</a>.</p>

</div>
</div>

### prepareMergedFunctions() {#a7ff8f5a82defa914ab5037231e289055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymCreator::prepareMergedFunctions (<a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Organize merged <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s.</p>


<p>This method processes the list of function infos (Funcs) to identify and group functions with overlapping address ranges.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Out</td>
<td class="doxyParamItemDescription"><p>Output stream to report information about how merged <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s were handled.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a03611a5afc9cc137c5d0550d9e0a06f1">llvm::gsym::FunctionInfo::MergedFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea13e6f453fc178a85f4f96cef6fbfe02c">MergedFunctionsInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo/#a102aa70a223f40f43c99d916bc69a603">llvm::gsym::FunctionInfo::Range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a076f93c387f454f0db13d4bc7d4e7f9c">llvm::stable_sort</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>

</div>
</div>

### save() {#a5c4f8122cf59952849b4d8184df118dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error GsymCreator::save (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> ByteOrder, std::optional&lt; uint64_t &gt; SegmentSize=std::nullopt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Save a GSYM file to a stand alone file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path</td>
<td class="doxyParamItemDescription"><p>The file path to save the GSYM file to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteOrder</td>
<td class="doxyParamItemDescription"><p>The endianness to use when saving the file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SegmentSize</td>
<td class="doxyParamItemDescription"><p>The size in bytes to segment the GSYM file into. If this option is set this function will create N segments that are all around <em>SegmentSize</em> bytes in size. This allows a very large GSYM file to be broken up into shards. Each GSYM file will have its own file table, and string table that only have the files and strings needed for the shared. If this argument has no value, a single GSYM file that contains all function information will be created.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates success or failure of the save.</p></dd>
</dl>


<p>Declaration at line 311 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 68 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>


<p>References <a href="#a9ede3510dd3c4a79112fd4ff9048e04b">encode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>.</p>

</div>
</div>

### setBaseAddress() {#a3a20d5b08d026255dd9f7f7473cfe89b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::GsymCreator::setBaseAddress (uint64_t Addr)</td>
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

<p>Set the base address to use for the GSYM file.</p>


<p>Setting the base address to use for the GSYM file. Object files typically get loaded from a base address when the OS loads them into memory. Using GSYM files for symbolication becomes easier if the base address in the GSYM header is the same address as it allows addresses to be easily slid and allows symbolication without needing to find the original base address in the original object file.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>The address to use as the base address of the GSYM file when it is saved to disk.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### setUUID() {#ab85ea74b3cb2aeabcf765b1892ff9d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::GsymCreator::setUUID (<a href="/web-llvm/docs/api/classes/llvm/arrayref">llvm::ArrayRef</a>&lt; uint8_t &gt; UUIDBytes)</td>
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

<p>Set the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> value.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">UUIDBytes</td>
<td class="doxyParamItemDescription"><p>The new <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> bytes.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/objectfiletransformer/#a9940b2d9a5f2a7de1dcfcdb970bf5e51">llvm::gsym::ObjectFileTransformer::convert</a>.</p>

</div>
</div>

### SetValidTextRanges() {#ac3c47f7d5f05e3c9778d24ad91e5e7c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::GsymCreator::SetValidTextRanges (<a href="/web-llvm/docs/api/classes/llvm/addressranges">AddressRanges</a> &amp; TextRanges)</td>
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

<p>Set valid .text address ranges that all functions must be contained in.</p>

<p>Definition at line 420 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### calculateHeaderAndTableSize() {#a184a8738d7e06598e2b134fbe8de1db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t GsymCreator::calculateHeaderAndTableSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Calculate the byte size of the GSYM header and tables sizes.</p>


<p>This function will calculate the exact size in bytes of the encocded GSYM for the following items:</p>


<ul class="doxyList ">
<li>The GSYM header</li>
<li>The Address offset table</li>
<li>The Address info offset table</li>
<li>The file table</li>
<li>The string table</li>
</ul>

<p>This is used to help split GSYM files into segments.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>Size in bytes the GSYM header and tables.</p></dd>
</dl>


<p>Declaration at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### copyFile() {#ac4ed17972f32e1e1c433dfab2f9b3234}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t GsymCreator::copyFile (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; SrcGC, uint32_t FileIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy a file from <em>SrcGC</em> into this object.</p>


<p>Copy a file from <em>SrcGC</em> by file index into this GSYM creator. Files consist of two string table entries, one for the directory and one for the filename, this function will copy any needed strings ensure the file is uniqued within this object. If a file already exists in this GSYM creator the uniqued index will be returned, else the stirngs will be copied and the new file index will be returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcGC</td>
<td class="doxyParamItemDescription"><p>The source gsym creator to copy from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FileIdx</td>
<td class="doxyParamItemDescription"><p>The 1 based file table index within <em>SrcGC</em> to copy. A file index of zero will always return zero as the zero is a reserved file index that means no file.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The new file index of the file within this object.</p></dd>
</dl>


<p>Declaration at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### copyFunctionInfo() {#a23d03be9f14030b4c9c15d3af3828eb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t GsymCreator::copyFunctionInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; SrcGC, size_t FuncInfoIdx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> from the <em>SrcGC</em> GSYM creator into this creator.</p>


<p>Copy the function info and only the needed files and strings and add a converted <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> into this object. This is used to segment GSYM files into separate files while only transferring the files and strings that are needed from <em>SrcGC</em>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcGC</td>
<td class="doxyParamItemDescription"><p>The source gsym creator to copy from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncInfoIdx</td>
<td class="doxyParamItemDescription"><p>The function info index within <em>SrcGC</em> to copy.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The number of bytes it will take to encode the function info in this <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>. This helps calculate the size of the current GSYM segment file.</p></dd>
</dl>


<p>Declaration at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 507 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### copyString() {#af34f501dde106b375256acc90dbd4722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t GsymCreator::copyString (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; SrcGC, uint32_t StrOff)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy a string from <em>SrcGC</em> into this object.</p>


<p>Copy a string from <em>SrcGC</em> by string table offset into this GSYM creator. If a string has already been copied, the uniqued string table offset will be returned, otherwise the string will be copied and a unique offset will be returned.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcGC</td>
<td class="doxyParamItemDescription"><p>The source gsym creator to copy from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">StrOff</td>
<td class="doxyParamItemDescription"><p>The string table offset from <em>SrcGC</em> to copy.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The new string table offset of the string within this object.</p></dd>
</dl>


<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 356 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### fixupInlineInfo() {#a110e3e5b5679107f83e06d0f20396bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GsymCreator::fixupInlineInfo (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; SrcGC, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &amp; II)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fixup any string and file references by updating any file indexes and strings offsets in the <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> parameter.</p>


<p>When copying <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> entries, we can simply make a copy of the object and then fixup the files and strings for efficiency.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">SrcGC</td>
<td class="doxyParamItemDescription"><p>The source gsym creator to copy from.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">II</td>
<td class="doxyParamItemDescription"><p>The inline info that contains file indexes and string offsets that come from <em>SrcGC</em>. The entries will be updated by coping any files and strings over into this object.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### getAddressOffsetSize() {#aec7f87095214d476f4c125e835bcc542}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t GsymCreator::getAddressOffsetSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the size of an address offset in the address offset table.</p>


<p>GSYM files store offsets from the base address in the address offset table and we store the size of the address offsets in the GSYM header. This function will calculate the size in bytes of these address offsets based on the current contents of the GSYM file.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The size in byets of the address offsets.</p></dd>
</dl>


<p>Declaration at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 466 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### getBaseAddress() {#aea6e7922d95ba749dc5b28502865be1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; GsymCreator::getBaseAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the base address to use for this GSYM file.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The base address to put into the header and to use when creating the address offset table or std::nullpt if there are no valid function infos or if the base address wasn't specified.</p></dd>
</dl>


<p>Declaration at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### getFirstFunctionAddress() {#a91dba24214a5f73e6905051a606f2456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; GsymCreator::getFirstFunctionAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the first function start address.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The start address of the first <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> or std::nullopt if there are no function infos.</p></dd>
</dl>


<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### getLastFunctionAddress() {#abcabc5c0ba02a9d4fa852a1b3ffbe653}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; GsymCreator::getLastFunctionAddress ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the last function address.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The start address of the last <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> or std::nullopt if there are no function infos.</p></dd>
</dl>


<p>Declaration at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 440 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### getMaxAddressOffset() {#ab79b32a605ddd551d253675b502501d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t GsymCreator::getMaxAddressOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the maximum address offset for the current address offset size.</p>


<p>This is used when creating the address offset table to ensure we have values that are in range so we don't end up truncating address offsets when creating GSYM files as the code evolves.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The maximum address offset value that will be encoded into a GSYM file.</p></dd>
</dl>


<p>Declaration at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### insertFileEntry() {#aa16f9ffdff258d3535649550fb07f2bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t GsymCreator::insertFileEntry (<a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> FE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inserts a <a href="/web-llvm/docs/api/structs/llvm/gsym/fileentry">FileEntry</a> into the file table.</p>


<p>This is used to insert a file entry in a thread safe way into this object.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FE</td>
<td class="doxyParamItemDescription"><p>A file entry object that contains valid string table offsets from this object already.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### saveSegments() {#a275c1ae3dda520ae8831fea5fefd346b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error GsymCreator::saveSegments (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Path, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000db">llvm::endianness</a> ByteOrder, uint64_t SegmentSize)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Save this GSYM file into segments that are roughly <em>SegmentSize</em> in size.</p>


<p>When segemented GSYM files are saved to disk, they will use <em>Path</em> as a prefix and then have the first function info address appended to the path when each segment is saved. Each segmented GSYM file has a only the strings and files that are needed to save the function infos that are in each segment. These smaller files are easy to compress and download separately and allow for efficient lookups with very large GSYM files and segmenting them allows servers to download only the segments that are needed.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Path</td>
<td class="doxyParamItemDescription"><p>The path prefix to use when saving the GSYM files.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ByteOrder</td>
<td class="doxyParamItemDescription"><p>The endianness to use when saving the file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SegmentSize</td>
<td class="doxyParamItemDescription"><p>The size in bytes to segment the GSYM file into.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>, definition at line 541 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a>.</p>

</div>
</div>

### setIsSegment() {#ad94f4001e614cf2e16b880a974f6f5cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::GsymCreator::setIsSegment ()</td>
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

<p>Let this creator know that this is a segment of another <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>.</p>


<p>When we have a segment, we know that function infos will be added in ascending address range order without having to be finalized. We also don't need to sort and unique entries during the finalize function call.</p>


<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BaseAddress {#a4dfc2665bf21ffe0f3b0fee2748e3c8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::gsym::GsymCreator::BaseAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### FileEntryToIndex {#a86b0a15e3307f6176548130886919b4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;llvm::gsym::FileEntry, uint32_t&gt; llvm::gsym::GsymCreator::FileEntryToIndex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### Files {#a12c2a779adebc0ebde5f392805329ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;llvm::gsym::FileEntry&gt; llvm::gsym::GsymCreator::Files</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### Finalized {#a3befc4512b386daee2cc9e4c6be89f25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::GsymCreator::Finalized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### Funcs {#a9a16f49bae614c3976349a1ff08b803f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FunctionInfo&gt; llvm::gsym::GsymCreator::Funcs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### IsSegment {#a1112fe4df5ef2743964805fdb454f573}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::GsymCreator::IsSegment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### Mutex {#a5b2a3052a487317850c3aaa8eb27cc56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex llvm::gsym::GsymCreator::Mutex</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### Quiet {#af7866fcd54b3f2ff23de3313735dfd2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::GsymCreator::Quiet</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### StringOffsetMap {#aa9d272dc332c48251f3a30ef31589eb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;uint64_t, CachedHashStringRef&gt; llvm::gsym::GsymCreator::StringOffsetMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### StringStorage {#a4a8689714862f3de5b1dd31bd22ed446}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringSet llvm::gsym::GsymCreator::StringStorage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### StrTab {#a6da00e5dd1b290512db1b4e4b47ddc2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringTableBuilder llvm::gsym::GsymCreator::StrTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### UUID {#a88af2aa58192684bbf3ab31ba1ef63c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;uint8_t&gt; llvm::gsym::GsymCreator::UUID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

### ValidTextRanges {#a93e4bda0571853dabfa136714abb880d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;AddressRanges&gt; llvm::gsym::GsymCreator::ValidTextRanges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/gsymcreator-h">GsymCreator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/gsymcreator-cpp">GsymCreator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
