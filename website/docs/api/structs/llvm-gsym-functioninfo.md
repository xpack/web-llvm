---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gsym/functioninfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FunctionInfo` Struct Reference

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> information in GSYM files encodes information for one contiguous address range. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::gsym::FunctionInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">llvm/DebugInfo/GSYM/FunctionInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcf53d0ab35bb53a0ca5d71fb6c79b71">FunctionInfo</a> (uint64_t Addr=0, uint64_t Size=0, uint32_t N=0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e97135bd7730c4555dea03637855e03">hasRichInfo</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query if a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> has rich debug info. <a href="#a4e97135bd7730c4555dea03637855e03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43805f0959f25f9637f816f36fe806f1">isValid</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Query if a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object is valid. <a href="#a43805f0959f25f9637f816f36fe806f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6deec968e0067bd7e7cd91892043097">encode</a> (FileWriter &amp;O, bool NoPadding=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode this object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream. <a href="#ab6deec968e0067bd7e7cd91892043097">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9542e71642930ba15c6f0f7788d8c654">cacheEncoding</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Encode this function info into the internal byte cache and return the size in bytes. <a href="#a9542e71642930ba15c6f0f7788d8c654">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b158428fe205ce8c6f34d1ccd78f1fb">startAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce61ffd4f47c4faabccb79d5c70a252">endAddress</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5965d701dc0010fd1a664b306c42dab5">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a184cc70241907604e8d360f32ae2ebc6">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/addressrange">AddressRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102aa70a223f40f43c99d916bc69a603">Range</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80935f98fcef212e4a50f81732eb645">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>String table offset in the string table. <a href="#aa80935f98fcef212e4a50f81732eb645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable">LineTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca03bd4694755ceb052d01df2cc3af82">OptLineTable</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03451bd54bbf81c015e178fea619ca5f">Inline</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03611a5afc9cc137c5d0550d9e0a06f1">MergedFunctions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection">CallSiteInfoCollection</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43fc767894ca96f7054ed1308b52ac0f">CallSites</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0172b7940ace197b2d098a303f8a945">EncodingCache</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If we encode a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> during segmenting so we know its size, we can cache that encoding here so we don't need to re-encode it when saving the GSYM file. <a href="#ac0172b7940ace197b2d098a303f8a945">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a> (DataExtractor &amp;Data, uint64_t BaseAddr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Decode an object from a binary data stream. <a href="#aea38a34c36c8f1cb37754bd3bd336053">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">llvm::Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d896568c18192e090d13f4831e4abb1">lookup</a> (DataExtractor &amp;Data, const GsymReader &amp;GR, uint64_t FuncAddr, uint64_t Addr, std::optional&lt; DataExtractor &gt; *MergedFuncsData=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Lookup an address within a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object's data stream. <a href="#a5d896568c18192e090d13f4831e4abb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> information in GSYM files encodes information for one contiguous address range.</p>


<p>If a function has discontiguous address ranges, they will need to be encoded using multiple <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects.</p>


<p>ENCODING</p>


<p>The function information gets the function start address as an argument to the FunctionInfo::decode(...) function. This information is calculated from the GSYM header and an address offset from the GSYM address offsets table. The encoded <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> information must be aligned to a 4 byte boundary.</p>


<p>The encoded data for a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> starts with fixed data that all function info objects have:</p>


<p>ENCODING NAME DESCRIPTION ========= =========== ==================================================== uint32_t Size The size in bytes of this function. uint32_t Name The string table offset of the function name.</p>


<p>The optional data in a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object follows this fixed information and consists of a stream of tuples that consist of:</p>


<p>ENCODING NAME DESCRIPTION ========= =========== ==================================================== uint32_t <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5ee">InfoType</a> An "InfoType" enumeration that describes the type of optional data that is encoded. uint32_t InfoLength The size in bytes of the encoded data that immediately follows this length if this value is greater than zero. uint8_t[] InfoData Encoded bytes that represent the data for the "InfoType". These bytes are only present if "InfoLength" is greater than zero.</p>


<p>The "InfoType" is an enumeration:</p>


<p>enum <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5ee">InfoType</a> { EndOfList = 0u, LineTableInfo = 1u, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo">InlineInfo</a> = 2u, <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo">MergedFunctionsInfo</a> = 3u, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfo">CallSiteInfo</a> = 4u };</p>


<p>This stream of tuples is terminated by a "InfoType" whose value is InfoType::EndOfList and a zero for "InfoLength". This signifies the end of the optional information list. This format allows us to add new optional information data to a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object over time and allows older clients to still parse the format and skip over any data that they don't understand or want to parse.</p>


<p>So the function information encoding essentially looks like:</p>


<p>struct { uint32_t Size; uint32_t Name; struct { uint32_t <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5ee">InfoType</a>; uint32_t InfoLength; uint8_t InfoData[InfoLength]; }[N]; }</p>


<p>Where "N" is the number of tuples.</p>


<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### FunctionInfo() {#adcf53d0ab35bb53a0ca5d71fb6c79b71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::gsym::FunctionInfo::FunctionInfo (uint64_t Addr=0, uint64_t Size=0, uint32_t N=0)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#aa80935f98fcef212e4a50f81732eb645">Name</a>, <a href="#a102aa70a223f40f43c99d916bc69a603">Range</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### cacheEncoding() {#a9542e71642930ba15c6f0f7788d8c654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t FunctionInfo::cacheEncoding ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode this function info into the internal byte cache and return the size in bytes.</p>


<p>When segmenting GSYM files we need to know how big each <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> will encode into so we can generate segments of the right size. We don't want to have to encode a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> twice, so we can cache the encoded bytes and re-use then when calling FunctionInfo::encode(...).</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The size in bytes of the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> if it were to be encoded into a byte stream.</p></dd>
</dl>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp">FunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>, <a href="#ac0172b7940ace197b2d098a303f8a945">EncodingCache</a>, <a href="#a43805f0959f25f9637f816f36fe806f1">isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a>.</p>

</div>
</div>

### clear() {#a184cc70241907604e8d360f32ae2ebc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::gsym::FunctionInfo::clear ()</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>References <a href="#a03451bd54bbf81c015e178fea619ca5f">Inline</a>, <a href="#aa80935f98fcef212e4a50f81732eb645">Name</a>, <a href="#aca03bd4694755ceb052d01df2cc3af82">OptLineTable</a> and <a href="#a102aa70a223f40f43c99d916bc69a603">Range</a>.</p>

</div>
</div>

### encode() {#ab6deec968e0067bd7e7cd91892043097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; uint64_t &gt; FunctionInfo::encode (<a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> &amp; O, bool NoPadding=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Encode this object into <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter">FileWriter</a> stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">O</td>
<td class="doxyParamItemDescription"><p>The binary stream to write the data to at the current file position.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">NoPadding</td>
<td class="doxyParamItemDescription"><p>Directly write the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> data, without any padding By default, <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> will be 4-byte aligned by padding with 0's at the start. This is OK since the function will return the offset of actual data in the stream. However when writing <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s as a stream, the padding will break the decoding of the data - since the offset where the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> starts is not kept in this scenario.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error object that indicates failure or the offset of the function info that was successfully written into the stream.</p></dd>
</dl>


<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>, definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp">FunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a4c1707b6e1ef8dd2cad56c0ec486e205">llvm::gsym::FileWriter::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeaa494eb85f92e884f7e730d15a4dec9c7">CallSiteInfo</a>, <a href="#a43fc767894ca96f7054ed1308b52ac0f">CallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#ac0172b7940ace197b2d098a303f8a945">EncodingCache</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea3d516faa526d601aa8b16c176189f1a6">EndOfList</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a23334fee66fedcc03e7c74ed4295611c">llvm::gsym::FileWriter::fixup32</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#aded943536fd3590c1c6b3ccb1dc7bbe2">llvm::gsym::FileWriter::getByteOrder</a>, <a href="#a03451bd54bbf81c015e178fea619ca5f">Inline</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeac1775aaace95748849e1216a09f028fc">InlineInfo</a>, <a href="#a43805f0959f25f9637f816f36fe806f1">isValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeadfcbc49fc99e4c3832ed815adc425447">LineTableInfo</a>, <a href="#a03611a5afc9cc137c5d0550d9e0a06f1">MergedFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea13e6f453fc178a85f4f96cef6fbfe02c">MergedFunctionsInfo</a>, <a href="#aa80935f98fcef212e4a50f81732eb645">Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1e26e57357947b25e392fd18ab000dba8e5f3adee38c8fccc13c1f3be0143796">llvm::native</a>, <a href="#aca03bd4694755ceb052d01df2cc3af82">OptLineTable</a>, <a href="#a102aa70a223f40f43c99d916bc69a603">Range</a>, <a href="#a5965d701dc0010fd1a664b306c42dab5">size</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a1462db57acbef343fec398bfbf85391a">llvm::gsym::FileWriter::tell</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#abf2098b5e04292cab5f72108ed12e1bd">llvm::gsym::FileWriter::writeData</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/filewriter/#a766e343d0ff12c414ffa59f35c1f562d">llvm::gsym::FileWriter::writeU32</a>.</p>


<p>Referenced by <a href="#a9542e71642930ba15c6f0f7788d8c654">cacheEncoding</a>.</p>

</div>
</div>

### endAddress() {#a0ce61ffd4f47c4faabccb79d5c70a252}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::FunctionInfo::endAddress ()</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Reference <a href="#a102aa70a223f40f43c99d916bc69a603">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>.</p>

</div>
</div>

### hasRichInfo() {#a4e97135bd7730c4555dea03637855e03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::FunctionInfo::hasRichInfo ()</td>
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

<p>Query if a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> has rich debug info.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A bool that indicates if this object has something else than range and name. When converting information from a symbol table and from debug info, we might end up with multiple <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects for the same range and we need to be able to tell which one is the better object to use.</p></dd>
</dl>


<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>References <a href="#a43fc767894ca96f7054ed1308b52ac0f">CallSites</a>, <a href="#a03451bd54bbf81c015e178fea619ca5f">Inline</a> and <a href="#aca03bd4694755ceb052d01df2cc3af82">OptLineTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#abdaa5c17b22848e0de64e78984c8d07c">llvm::gsym::GsymCreator::finalize</a>.</p>

</div>
</div>

### isValid() {#a43805f0959f25f9637f816f36fe806f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gsym::FunctionInfo::isValid ()</td>
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

<p>Query if a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object is valid.</p>


<p>Address and size can be zero and there can be no line entries for a symbol so the only indication this entry is valid is if the name is not zero. This can happen when extracting information from symbol tables that do not encode symbol sizes. In that case only the address and name will be filled in.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A boolean indicating if this <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> is valid.</p></dd>
</dl>


<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Reference <a href="#aa80935f98fcef212e4a50f81732eb645">Name</a>.</p>


<p>Referenced by <a href="#a9542e71642930ba15c6f0f7788d8c654">cacheEncoding</a> and <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>.</p>

</div>
</div>

### size() {#a5965d701dc0010fd1a664b306c42dab5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::FunctionInfo::size ()</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Reference <a href="#a102aa70a223f40f43c99d916bc69a603">Range</a>.</p>


<p>Referenced by <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ac40e6efe1caf07771eb6713f41db076b">llvm::gsym::DwarfTransformer::verify</a>.</p>

</div>
</div>

### startAddress() {#a0b158428fe205ce8c6f34d1ccd78f1fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::gsym::FunctionInfo::startAddress ()</td>
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



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Reference <a href="#a102aa70a223f40f43c99d916bc69a603">Range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### CallSites {#a43fc767894ca96f7054ed1308b52ac0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CallSiteInfoCollection&gt; llvm::gsym::FunctionInfo::CallSites</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Referenced by <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a000318afaccf51b9e411d4890c4a1231">llvm::gsym::GsymReader::dump</a>, <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>, <a href="#a4e97135bd7730c4555dea03637855e03">hasRichInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a23b23c842771d071cfb8af8c15e38e37">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### EncodingCache {#ac0172b7940ace197b2d098a303f8a945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallString&lt;32&gt; llvm::gsym::FunctionInfo::EncodingCache</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If we encode a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> during segmenting so we know its size, we can cache that encoding here so we don't need to re-encode it when saving the GSYM file.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Referenced by <a href="#a9542e71642930ba15c6f0f7788d8c654">cacheEncoding</a> and <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>.</p>

</div>
</div>

### Inline {#a03451bd54bbf81c015e178fea619ca5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;InlineInfo&gt; llvm::gsym::FunctionInfo::Inline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Referenced by <a href="#a184cc70241907604e8d360f32ae2ebc6">clear</a>, <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a000318afaccf51b9e411d4890c4a1231">llvm::gsym::GsymReader::dump</a>, <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>, <a href="#a4e97135bd7730c4555dea03637855e03">hasRichInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a23b23c842771d071cfb8af8c15e38e37">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### MergedFunctions {#a03611a5afc9cc137c5d0550d9e0a06f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;MergedFunctionsInfo&gt; llvm::gsym::FunctionInfo::MergedFunctions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Referenced by <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a000318afaccf51b9e411d4890c4a1231">llvm::gsym::GsymReader::dump</a>, <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a7ff8f5a82defa914ab5037231e289055">llvm::gsym::GsymCreator::prepareMergedFunctions</a>.</p>

</div>
</div>

### Name {#aa80935f98fcef212e4a50f81732eb645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::gsym::FunctionInfo::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>String table offset in the string table.</p>

<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Referenced by <a href="#a184cc70241907604e8d360f32ae2ebc6">clear</a>, <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a000318afaccf51b9e411d4890c4a1231">llvm::gsym::GsymReader::dump</a>, <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>, <a href="#adcf53d0ab35bb53a0ca5d71fb6c79b71">FunctionInfo</a>, <a href="#a43805f0959f25f9637f816f36fe806f1">isValid</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a23b23c842771d071cfb8af8c15e38e37">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### OptLineTable {#aca03bd4694755ceb052d01df2cc3af82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;LineTable&gt; llvm::gsym::FunctionInfo::OptLineTable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Referenced by <a href="#a184cc70241907604e8d360f32ae2ebc6">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a000318afaccf51b9e411d4890c4a1231">llvm::gsym::GsymReader::dump</a>, <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>, <a href="#a4e97135bd7730c4555dea03637855e03">hasRichInfo</a> and <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a23b23c842771d071cfb8af8c15e38e37">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

### Range {#a102aa70a223f40f43c99d916bc69a603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AddressRange llvm::gsym::FunctionInfo::Range</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>.</p>


<p>Referenced by <a href="#a184cc70241907604e8d360f32ae2ebc6">clear</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a000318afaccf51b9e411d4890c4a1231">llvm::gsym::GsymReader::dump</a>, <a href="#ab6deec968e0067bd7e7cd91892043097">encode</a>, <a href="#a0ce61ffd4f47c4faabccb79d5c70a252">endAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#abdaa5c17b22848e0de64e78984c8d07c">llvm::gsym::GsymCreator::finalize</a>, <a href="#adcf53d0ab35bb53a0ca5d71fb6c79b71">FunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a23b23c842771d071cfb8af8c15e38e37">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a7ff8f5a82defa914ab5037231e289055">llvm::gsym::GsymCreator::prepareMergedFunctions</a>, <a href="#a5965d701dc0010fd1a664b306c42dab5">size</a> and <a href="#a0b158428fe205ce8c6f34d1ccd78f1fb">startAddress</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### decode() {#aea38a34c36c8f1cb37754bd3bd336053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; FunctionInfo &gt; FunctionInfo::decode (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, uint64_t BaseAddr)</td>
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

<p>Decode an object from a binary data stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BaseAddr</td>
<td class="doxyParamItemDescription"><p>The <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s start address and will be used as the base address when decoding any contained information like the line table and the inline info.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> or an error describing the issue that was encountered during decoding.</p></dd>
</dl>


<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>, definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp">FunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeaa494eb85f92e884f7e730d15a4dec9c7">CallSiteInfo</a>, <a href="#a43fc767894ca96f7054ed1308b52ac0f">CallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection/#ade8c3030c7854f2dce476b50e2102815">llvm::gsym::CallSiteInfoCollection::decode</a>, <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#ae59cf2adb8c2fb547e64f51ee921aa56">llvm::gsym::InlineInfo::decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a45c433311387761ffb00f0aea6be6675">llvm::gsym::LineTable::decode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#a3f8f8f0e7e46eb22afffe9c8c5dbe50e">llvm::gsym::MergedFunctionsInfo::decode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea3d516faa526d601aa8b16c176189f1a6">EndOfList</a>, <a href="#adcf53d0ab35bb53a0ca5d71fb6c79b71">FunctionInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a>, <a href="#a03451bd54bbf81c015e178fea619ca5f">Inline</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeac1775aaace95748849e1216a09f028fc">InlineInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeadfcbc49fc99e4c3832ed815adc425447">LineTableInfo</a>, <a href="#a03611a5afc9cc137c5d0550d9e0a06f1">MergedFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea13e6f453fc178a85f4f96cef6fbfe02c">MergedFunctionsInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#aa80935f98fcef212e4a50f81732eb645">Name</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#aca03bd4694755ceb052d01df2cc3af82">OptLineTable</a> and <a href="#a102aa70a223f40f43c99d916bc69a603">Range</a>.</p>


<p>Referenced by <a href="#aea38a34c36c8f1cb37754bd3bd336053">decode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/mergedfunctionsinfo/#a3f8f8f0e7e46eb22afffe9c8c5dbe50e">llvm::gsym::MergedFunctionsInfo::decode</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a891f5398a526e0de9d2b5006559ef594">llvm::gsym::GsymReader::getFunctionInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#ae699d115f9699264b670c60d4f57d394">llvm::gsym::GsymReader::getFunctionInfoAtIndex</a>.</p>

</div>
</div>

### lookup() {#a5d896568c18192e090d13f4831e4abb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Expected&lt; LookupResult &gt; FunctionInfo::lookup (<a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &amp; Data, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a> &amp; GR, uint64_t FuncAddr, uint64_t Addr, std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/dataextractor">DataExtractor</a> &gt; * MergedFuncsData=nullptr)</td>
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

<p>Lookup an address within a <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object's data stream.</p>


<p>Instead of decoding an entire <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> object when doing lookups, we can decode only the information we need from the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a>'s data for the specific address. The lookup result information is returned as a <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Data</td>
<td class="doxyParamItemDescription"><p>The binary stream to read the data from. This object must have the data for the object starting at offset zero. The data can contain more data than needed.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">GR</td>
<td class="doxyParamItemDescription"><p>The GSYM reader that contains the string and file table that will be used to fill in information in the returned result.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FuncAddr</td>
<td class="doxyParamItemDescription"><p>The function start address decoded from the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader">GsymReader</a>.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Addr</td>
<td class="doxyParamItemDescription"><p>The address to lookup.</p></td>
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
<dd><p>An <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult">LookupResult</a> or an error describing the issue that was encountered during decoding. An error should only be returned if the address is not contained in the <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> or if the data is corrupted.</p></dd>
</dl>


<p>Declaration at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a>, definition at line 239 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp">FunctionInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a05bfc8d6292b7916993f0f2a32307c88">llvm::gsym::SourceLocation::Base</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a5e530bef09b9dc59f44888c60bdd82a0">llvm::gsym::LookupResult::CallSiteFuncRegex</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeaa494eb85f92e884f7e730d15a4dec9c7">CallSiteInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrange/#accce80061bb85f65b4223c49d91216a0">llvm::AddressRange::contains</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa20539e89704d20b98b97e9c3feac934">llvm::Data</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/callsiteinfocollection/#ade8c3030c7854f2dce476b50e2102815">llvm::gsym::CallSiteInfoCollection::decode</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a9c40347d10af7c2cefe3d77e8487f4b7">llvm::gsym::SourceLocation::Dir</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a233737223c9a3dba810df5b91bc91d1fabbb9957d8adae962b153273c16bce571">llvm::Done</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea3d516faa526d601aa8b16c176189f1a6">EndOfList</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry/#a193c4a1af11b83092b6db93d02219b1e">llvm::gsym::LineEntry::File</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a75d91d0e18eade33e855b488992f550e">llvm::gsym::LookupResult::FuncName</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a5aea1cf15f8a7f3f908ac755883139f3">llvm::gsym::LookupResult::FuncRange</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a25ce2405debe5fa88ce06de770ce4bf0">llvm::gsym::GsymReader::getFile</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a65ec9133639d066dcf6843b1fc3ae79c">llvm::gsym::GsymReader::getString</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeac1775aaace95748849e1216a09f028fc">InlineInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armsubtarget-cpp/#a6f57985fa144303082fa7517a52e6db9">IT</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lineentry/#a7648b354c70ebeac2fa9001116b84d11">llvm::gsym::LineEntry::Line</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a158cfb1f977ca6fa5202d0925b97197b">llvm::gsym::SourceLocation::Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eeadfcbc49fc99e4c3832ed815adc425447">LineTableInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a8b0145407164f660bd71c3189087006f">llvm::gsym::LookupResult::Locations</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/inlineinfo/#a6f764edf4bf576f4e243188eb8fa5e0c">llvm::gsym::InlineInfo::lookup</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/linetable/#a9bca453dce01051bae3751cbb4d14fef">llvm::gsym::LineTable::lookup</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/lookupresult/#a2c2d38a017ea83399938350483968ae1">llvm::gsym::LookupResult::LookupAddr</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp/#a3e1eb307ada3e1ef3a115f4c734aa5eea13e6f453fc178a85f4f96cef6fbfe02c">MergedFunctionsInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#acc0de9bcc407c170aff5069c335bb961">llvm::gsym::SourceLocation::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/gsym/sourcelocation/#a5ac9d3eb9c18ab3a8da5b084d034c158">llvm::gsym::SourceLocation::Offset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/classes/llvm/addressrange/#afe148fdaacb37330c6cfb734abbf610a">llvm::AddressRange::size</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#ad5768ee08d5c7c9b431387ce9b03a6e9">llvm::gsym::GsymReader::lookup</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#afab544245beb837bd2fd89c12e060c3f">llvm::gsym::GsymReader::lookupAll</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/functioninfo-h">FunctionInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/functioninfo-cpp">FunctionInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
