---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/sys/unicode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `unicode` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::sys::unicode { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sys/unicode/loosematchingresult">LooseMatchingResult</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sys/unicode/matchforcodepointname">MatchForCodepointName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node">Node</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/sys/unicode/generatednamesdata">GeneratedNamesData</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71a6fc64f3d617a205c8f34db2ff2c1a">BufferType</a> = <a href="/web-llvm/docs/api/classes/llvm/smallstring">SmallString</a>&lt; 64 &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ColumnWidthErrors { <a href="#a054c217b1f8d738318a766e35b31063e">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd3e84c33222ee387cf6a03d1a77400">isPrintable</a> (int UCS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines if a character is likely to be displayed correctly on the terminal. <a href="#abdd3e84c33222ee387cf6a03d1a77400">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd4aa0bae0775960e05e796db4139755">isFormatting</a> (int UCS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Unicode code points of the Cf category are considered formatting characters. <a href="#abd4aa0bae0775960e05e796db4139755">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5eb094d229e45fc3cee677f5fc824e2a">columnWidthUTF8</a> (StringRef Text)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the number of positions the UTF8-encoded <span class="doxyComputerOutput">Text</span> is likely to occupy when output on a terminal ("character width"). <a href="#a5eb094d229e45fc3cee677f5fc824e2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3578a101e495ed08245b568a1e02174a">foldCharSimple</a> (int C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fold input unicode character according the Simple unicode case folding rules. <a href="#a3578a101e495ed08245b568a1e02174a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; char32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4975b1c3f5b90e3270e59ee3b3e34999">nameToCodepointStrict</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps the name or the alias of a Unicode character to its associated codepoints. <a href="#a4975b1c3f5b90e3270e59ee3b3e34999">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/loosematchingresult">LooseMatchingResult</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d0d10bb4158631314f59a7865eb1c62">nameToCodepointLooseMatching</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/matchforcodepointname">MatchForCodepointName</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e10ba09dea9d13b485ec2a68efb4f98">nearestMatchesForCodepointName</a> (StringRef Pattern, std::size_t MaxMatchesCount)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1dd06eeeda61a605655a2fab90dd6c4">charWidth</a> (int UCS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the number of positions a character is likely to occupy when output on a terminal ("character width"). <a href="#aa1dd06eeeda61a605655a2fab90dd6c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a469fba4df824222417d066bbec9a1fb5">isprintableascii</a> (char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node">Node</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67818bf1586984762d35986330c4129b">createRoot</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node">Node</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1595de063cd60f1beb94ab845204e496">readNode</a> (uint32_t Offset, const Node *Parent=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263bac5d85adb87956f47116b8fd5b2a">startsWith</a> (StringRef Name, StringRef Needle, bool Strict, std::size_t &amp;Consummed, char &amp;PreviousCharInName, bool IsPrefix=false)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::tuple&lt; <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node">Node</a>, bool, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb0122730c8d41728ac1213b0bef71c1">compareNode</a> (uint32_t Offset, StringRef Name, bool Strict, char PreviousCharInName, BufferType &amp;Buffer, const Node *Parent=nullptr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::tuple&lt; <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node">Node</a>, bool, uint32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a433d541c93dc9584366ef45a39b27ef2">compareNode</a> (uint32_t Offset, StringRef Name, bool Strict, BufferType &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf9183145a865f67edbedc0b24767fd1">findSyllable</a> (StringRef Name, bool Strict, char &amp;PreviousInName, int &amp;Pos, int Column)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; char32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a> (StringRef Name, bool Strict, BufferType &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; char32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae507b357fbb69fc2cb019831c4d66dd8">nameToGeneratedCodePoint</a> (StringRef Name, bool Strict, BufferType &amp;Buffer)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; char32_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad08f0dd526b3f602ccb0f0d39832ae08">nameToCodepoint</a> (StringRef Name, bool Strict, BufferType &amp;Buffer)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56be6a91b21a2c87e2a892feaafbb5b">UnicodeNameToCodepointDict</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint8_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26b63e047af075f66f62cfc5c68bbf1">UnicodeNameToCodepointIndex</a> = <a href="#a269dcd773d0d47d82b03308f35edcedb">UnicodeNameToCodepointIndex_</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a762a9920553a2a43f09cb37ac5bccf">UnicodeNameToCodepointIndexSize</a> = 242258</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a250725ca9390c4a4206f153d57debabe">UnicodeNameToCodepointLargestNameSize</a> = 74</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a736c33ad03787045b50857d685ab1e72">HangulSyllables</a>[][3] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56aadf48006c8538ac3e9fc3bf220b9">SBase</a> = 0xAC00</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fda06c0bf8c01df9eb8a6774c19732a">LCount</a> = 19</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a953904b870805e1b6729dfc171733361">VCount</a> = 21</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1903a9794d4cb8724f7d69a17d7ca374">TCount</a> = 28</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/generatednamesdata">GeneratedNamesData</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd085f169f51596ec70557ac137af39d">GeneratedNamesDataTable</a>[] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a269dcd773d0d47d82b03308f35edcedb">UnicodeNameToCodepointIndex_</a>[242258]</td>
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


<div class="doxySectionDef">

## Typedefs

### BufferType {#a71a6fc64f3d617a205c8f34db2ff2c1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::sys::unicode::BufferType =  SmallString&lt;64&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### ColumnWidthErrors {#a054c217b1f8d738318a766e35b31063e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::sys::unicode::ColumnWidthErrors </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ErrorInvalidUTF8<a id="a054c217b1f8d738318a766e35b31063ea32cdc26114f4a19ca509d53eea14c2e9"></a></td>
<td class="doxyEnumItemDescription"> (= -2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ErrorNonPrintableCharacter<a id="a054c217b1f8d738318a766e35b31063eae08389c6cf8c7bc89ef7406ac6f95f2d"></a></td>
<td class="doxyEnumItemDescription"> (= -1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicode-h">Unicode.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### charWidth() {#aa1dd06eeeda61a605655a2fab90dd6c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sys::unicode::charWidth (int UCS)</td>
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

<p>Gets the number of positions a character is likely to occupy when output on a terminal ("character width").</p>


<p>This depends on the implementation of the terminal, and there's no standard definition of character width. The implementation defines it in a way that is expected to be compatible with a generic Unicode-capable terminal.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>Character width:</p>


<ul class="doxyList ">
<li>ErrorNonPrintableCharacter (-1) for non-printable characters (as identified by isPrintable);</li>
<li>0 for non-spacing and enclosing combining marks;</li>
<li>2 for CJK characters excluding halfwidth forms;</li>
<li>1 for all remaining characters.</li>
</ul>
</dd>
</dl>


<p>Definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicode-cpp">Unicode.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/unicodecharset/#a2920c37bba86099cb7bd7718c6288fac">llvm::sys::UnicodeCharSet::contains</a>, <a href="#a054c217b1f8d738318a766e35b31063eae08389c6cf8c7bc89ef7406ac6f95f2d">ErrorNonPrintableCharacter</a> and <a href="#abdd3e84c33222ee387cf6a03d1a77400">isPrintable</a>.</p>


<p>Referenced by <a href="#a5eb094d229e45fc3cee677f5fc824e2a">columnWidthUTF8</a>.</p>

</div>
</div>

### columnWidthUTF8() {#a5eb094d229e45fc3cee677f5fc824e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sys::unicode::columnWidthUTF8 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets the number of positions the UTF8-encoded <span class="doxyComputerOutput">Text</span> is likely to occupy when output on a terminal ("character width").</p>


<p>This depends on the implementation of the terminal, and there's no standard definition of character width.</p>


<p>The implementation defines it in a way that is expected to be compatible with a generic Unicode-capable terminal.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>Character width:</p>


<ul class="doxyList ">
<li>ErrorNonPrintableCharacter (-1) if <span class="doxyComputerOutput">Text</span> contains non-printable characters (as identified by isPrintable);</li>
<li>0 for each non-spacing and enclosing combining mark;</li>
<li>2 for each CJK character excluding halfwidth forms;</li>
<li>1 for each of the remaining characters.</li>
</ul>
</dd>
</dl>


<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicode-cpp">Unicode.cpp</a>.</p>


<p>References <a href="#aa1dd06eeeda61a605655a2fab90dd6c4">charWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5ebaabfc0ad9d49185970237f7f6e022a97cffaef83484846653a9bcef497fb42">llvm::conversionOK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a218cf13cccdc56183b8a38c4603b2e69">llvm::ConvertUTF8toUTF32</a>, <a href="#a054c217b1f8d738318a766e35b31063ea32cdc26114f4a19ca509d53eea14c2e9">ErrorInvalidUTF8</a>, <a href="#a054c217b1f8d738318a766e35b31063eae08389c6cf8c7bc89ef7406ac6f95f2d">ErrorNonPrintableCharacter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a32e798e98caac5726958f91abbb5a98f">llvm::getNumBytesForUTF8</a>, <a href="#a469fba4df824222417d066bbec9a1fb5">isprintableascii</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878af6d9f1c7b49b7601fae6a545002a6763">llvm::Length</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5e95c0244958f5a0e6198a966d8be81ca9214370b1333822e7b0c6fbfdd1c1de7">llvm::strictConversion</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/sys/locale/#a5ae394643b3722606e9daf0ca8157f52">llvm::sys::locale::columnWidth</a>.</p>

</div>
</div>

### compareNode() {#acb0122730c8d41728ac1213b0bef71c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Node, bool, uint32_t &gt; llvm::sys::unicode::compareNode (uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Strict, char PreviousCharInName, <a href="#a71a6fc64f3d617a205c8f34db2ff2c1a">BufferType</a> &amp; Buffer, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node">Node</a> * Parent=nullptr)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#acb0122730c8d41728ac1213b0bef71c1">compareNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a1595de063cd60f1beb94ab845204e496">readNode</a> and <a href="#a263bac5d85adb87956f47116b8fd5b2a">startsWith</a>.</p>


<p>Referenced by <a href="#a433d541c93dc9584366ef45a39b27ef2">compareNode</a>, <a href="#acb0122730c8d41728ac1213b0bef71c1">compareNode</a> and <a href="#ad08f0dd526b3f602ccb0f0d39832ae08">nameToCodepoint</a>.</p>

</div>
</div>

### compareNode() {#a433d541c93dc9584366ef45a39b27ef2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::tuple&lt; Node, bool, uint32_t &gt; llvm::sys::unicode::compareNode (uint32_t Offset, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Strict, <a href="#a71a6fc64f3d617a205c8f34db2ff2c1a">BufferType</a> &amp; Buffer)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="#acb0122730c8d41728ac1213b0bef71c1">compareNode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### createRoot() {#a67818bf1586984762d35986330c4129b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node llvm::sys::unicode::createRoot ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>.</p>


<p>Referenced by <a href="#a4e10ba09dea9d13b485ec2a68efb4f98">nearestMatchesForCodepointName</a> and <a href="#a1595de063cd60f1beb94ab845204e496">readNode</a>.</p>

</div>
</div>

### findSyllable() {#abf9183145a865f67edbedc0b24767fd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::size_t llvm::sys::unicode::findSyllable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Strict, char &amp; PreviousInName, int &amp; Pos, int Column)</td>
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



<p>Definition at line 259 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a736c33ad03787045b50857d685ab1e72">HangulSyllables</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a8fda06c0bf8c01df9eb8a6774c19732a">LCount</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>, <a href="#a263bac5d85adb87956f47116b8fd5b2a">startsWith</a>, <a href="#a1903a9794d4cb8724f7d69a17d7ca374">TCount</a> and <a href="#a953904b870805e1b6729dfc171733361">VCount</a>.</p>


<p>Referenced by <a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a>.</p>

</div>
</div>

### foldCharSimple() {#a3578a101e495ed08245b568a1e02174a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::sys::unicode::foldCharSimple (int C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fold input unicode character according the Simple unicode case folding rules.</p>

<p>Declaration at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicode-h">Unicode.h</a>, definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodecasefold-cpp">UnicodeCaseFold.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/djb-cpp/#a6e269ab1206e9a9013394d788df1dfd9">foldCharDwarf</a>.</p>

</div>
</div>

### isFormatting() {#abd4aa0bae0775960e05e796db4139755}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::unicode::isFormatting (int UCS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Unicode code points of the Cf category are considered formatting characters.</p>

<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicode-cpp">Unicode.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ab7530cd22b8952cb41774507dd40c6f3a520d0db389f362bf79ef56ca0af3dcab">llvm::Format</a>.</p>

</div>
</div>

### isPrintable() {#abdd3e84c33222ee387cf6a03d1a77400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::unicode::isPrintable (int UCS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines if a character is likely to be displayed correctly on the terminal.</p>


<p>Unicode code points of the categories L, M, N, P, S and Zs are considered printable.</p>


<p>Exact implementation would have to depend on the specific terminal, so we define the semantic that should be suitable for generic case of a terminal capable to output Unicode characters.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a> codepoints are those in the categories L, M, N, P, S and Zs</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the character is considered printable.</p></dd>
</dl>


<p>In addition, U+00AD SOFT HYPHEN is also considered printable, as it's actually displayed on most terminals.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the character is considered printable.</p></dd>
</dl>


<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicode-cpp">Unicode.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sys/unicodecharset/#a2920c37bba86099cb7bd7718c6288fac">llvm::sys::UnicodeCharSet::contains</a>.</p>


<p>Referenced by <a href="#aa1dd06eeeda61a605655a2fab90dd6c4">charWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#aefed9cb3f107aee0cff4d325c7d689ae">llvm::yaml::escape</a> and <a href="/web-llvm/docs/api/namespaces/llvm/sys/locale/#ad17f6a9a55a75115ee7099f6c615b336">llvm::sys::locale::isPrint</a>.</p>

</div>
</div>

### isprintableascii() {#a469fba4df824222417d066bbec9a1fb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::unicode::isprintableascii (char c)</td>
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



<p>Definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicode-cpp">Unicode.cpp</a>.</p>


<p>Referenced by <a href="#a5eb094d229e45fc3cee677f5fc824e2a">columnWidthUTF8</a>.</p>

</div>
</div>

### nameToCodepoint() {#ad08f0dd526b3f602ccb0f0d39832ae08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; char32_t &gt; llvm::sys::unicode::nameToCodepoint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Strict, <a href="#a71a6fc64f3d617a205c8f34db2ff2c1a">BufferType</a> &amp; Buffer)</td>
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



<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#acb0122730c8d41728ac1213b0bef71c1">compareNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="#ae507b357fbb69fc2cb019831c4d66dd8">nameToGeneratedCodePoint</a> and <a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a>.</p>


<p>Referenced by <a href="#a8d0d10bb4158631314f59a7865eb1c62">nameToCodepointLooseMatching</a> and <a href="#a4975b1c3f5b90e3270e59ee3b3e34999">nameToCodepointStrict</a>.</p>

</div>
</div>

### nameToCodepointLooseMatching() {#a8d0d10bb4158631314f59a7865eb1c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; LooseMatchingResult &gt; llvm::sys::unicode::nameToCodepointLooseMatching (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Reference <a href="#ad08f0dd526b3f602ccb0f0d39832ae08">nameToCodepoint</a>.</p>

</div>
</div>

### nameToCodepointStrict() {#a4975b1c3f5b90e3270e59ee3b3e34999}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; char32_t &gt; llvm::sys::unicode::nameToCodepointStrict (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps the name or the alias of a Unicode character to its associated codepoints.</p>


<p>The names and aliases are derived from UnicodeData.txt and NameAliases.txt For compatibility with the semantics of named character escape sequences in C++, this mapping does an exact match sensitive to casing and spacing.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The codepoint of the corresponding character, if any.</p></dd>
</dl>


<p>Definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Reference <a href="#ad08f0dd526b3f602ccb0f0d39832ae08">nameToCodepoint</a>.</p>

</div>
</div>

### nameToGeneratedCodePoint() {#ae507b357fbb69fc2cb019831c4d66dd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; char32_t &gt; llvm::sys::unicode::nameToGeneratedCodePoint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Strict, <a href="#a71a6fc64f3d617a205c8f34db2ff2c1a">BufferType</a> &amp; Buffer)</td>
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



<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#abd085f169f51596ec70557ac137af39d">GeneratedNamesDataTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aceda0d316aed2b818b731917d21b88bc">llvm::getAsUnsignedInteger</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfab2ee912b91d69b435159c7c3f6df7f5f">llvm::Number</a> and <a href="#a263bac5d85adb87956f47116b8fd5b2a">startsWith</a>.</p>


<p>Referenced by <a href="#ad08f0dd526b3f602ccb0f0d39832ae08">nameToCodepoint</a>.</p>

</div>
</div>

### nameToHangulCodePoint() {#a9496c295025807ea2778038622f3ba2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; char32_t &gt; llvm::sys::unicode::nameToHangulCodePoint (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Strict, <a href="#a71a6fc64f3d617a205c8f34db2ff2c1a">BufferType</a> &amp; Buffer)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#aac0ea55010b7b1a301e65a0baea057aa">llvm::SmallVectorImpl&lt; T &gt;::clear</a>, <a href="#abf9183145a865f67edbedc0b24767fd1">findSyllable</a>, <a href="#a736c33ad03787045b50857d685ab1e72">HangulSyllables</a>, <a href="#ae56aadf48006c8538ac3e9fc3bf220b9">SBase</a>, <a href="#a263bac5d85adb87956f47116b8fd5b2a">startsWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a1903a9794d4cb8724f7d69a17d7ca374">TCount</a> and <a href="#a953904b870805e1b6729dfc171733361">VCount</a>.</p>


<p>Referenced by <a href="#ad08f0dd526b3f602ccb0f0d39832ae08">nameToCodepoint</a>.</p>

</div>
</div>

### nearestMatchesForCodepointName() {#a4e10ba09dea9d13b485ec2a68efb4f98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt; MatchForCodepointName &gt; llvm::sys::unicode::nearestMatchesForCodepointName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Pattern, std::size_t MaxMatchesCount)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a67818bf1586984762d35986330c4129b">createRoot</a>, <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/matchforcodepointname/#aa5afff707ec91bbfe0430d6ab1703cec">llvm::sys::unicode::MatchForCodepointName::Distance</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a075e34e98605d0e7c289763a104869ac">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::end</a>, <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node/#a49c7c7cf7d7086c3469e4d7ee2486f32">llvm::sys::unicode::Node::fullName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a94d23373106467003722f7d6c17b1528">llvm::SmallVectorImpl&lt; T &gt;::insert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#acc1c483f4b4ee2f17bb6643a3b353609">LLVM_ATTRIBUTE_UNUSED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa81eb67f09ee4944eaeeddbc54c0c0de">llvm::lower_bound</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/matchforcodepointname/#abfa236a8272e38625ec4b248869c0b49">llvm::sys::unicode::MatchForCodepointName::Name</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolutionnormalization-cpp/#afd925d64a119671c81c42f09b7507534a4f6bc3e35432a7e20c757280be0d1f6b">Normalize</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#ad97688dfe9cd802e2a0691cbe620218a">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::pop_back</a>, <a href="#a1595de063cd60f1beb94ab845204e496">readNode</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a499ea32ca1b8d16cedfe01d1e5b08f29">llvm::SmallVectorImpl&lt; T &gt;::reserve</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="#a250725ca9390c4a4206f153d57debabe">UnicodeNameToCodepointLargestNameSize</a>.</p>

</div>
</div>

### readNode() {#a1595de063cd60f1beb94ab845204e496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node llvm::sys::unicode::readNode (uint32_t Offset, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/sys/unicode/node">Node</a> * Parent=nullptr)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="#a67818bf1586984762d35986330c4129b">createRoot</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ae42219072d798876e6b08e6b78614ff6">H</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79e64ef30db46c5331dc31759ebd8b9d">llvm::HasValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="#ae56be6a91b21a2c87e2a892feaafbb5b">UnicodeNameToCodepointDict</a>, <a href="#aa26b63e047af075f66f62cfc5c68bbf1">UnicodeNameToCodepointIndex</a> and <a href="#a5a762a9920553a2a43f09cb37ac5bccf">UnicodeNameToCodepointIndexSize</a>.</p>


<p>Referenced by <a href="#acb0122730c8d41728ac1213b0bef71c1">compareNode</a> and <a href="#a4e10ba09dea9d13b485ec2a68efb4f98">nearestMatchesForCodepointName</a>.</p>

</div>
</div>

### startsWith() {#a263bac5d85adb87956f47116b8fd5b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sys::unicode::startsWith (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Needle, bool Strict, std::size_t &amp; Consummed, char &amp; PreviousCharInName, bool IsPrefix=false)</td>
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



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armlowoverheadloops-cpp/#aee9acb24ef4f057644a7cf7217922eaa">Ignore</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a5db9240c74644c67759dd0f901fc3c7d">llvm::StringRef::size</a>.</p>


<p>Referenced by <a href="#acb0122730c8d41728ac1213b0bef71c1">compareNode</a>, <a href="#abf9183145a865f67edbedc0b24767fd1">findSyllable</a>, <a href="#ae507b357fbb69fc2cb019831c4d66dd8">nameToGeneratedCodePoint</a> and <a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### GeneratedNamesDataTable {#abd085f169f51596ec70557ac137af39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GeneratedNamesData llvm::sys::unicode::GeneratedNamesDataTable[]</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    {"CJK UNIFIED IDEOGRAPH-", 0x3400, 0x4DBF},
    {"CJK UNIFIED IDEOGRAPH-", 0x4E00, 0x9FFF},
    {"CJK UNIFIED IDEOGRAPH-", 0x20000, 0x2A6DF},
    {"CJK UNIFIED IDEOGRAPH-", 0x2A700, 0x2B739},
    {"CJK UNIFIED IDEOGRAPH-", 0x2B740, 0x2B81D},
    {"CJK UNIFIED IDEOGRAPH-", 0x2B820, 0x2CEA1},
    {"CJK UNIFIED IDEOGRAPH-", 0x2CEB0, 0x2EBE0},
    {"CJK UNIFIED IDEOGRAPH-", 0x2EBF0, 0x2EE5D},
    {"CJK UNIFIED IDEOGRAPH-", 0x30000, 0x3134A},
    {"CJK UNIFIED IDEOGRAPH-", 0x31350, 0x323AF},
    {"TANGUT IDEOGRAPH-", 0x17000, 0x187F7},
    {"TANGUT IDEOGRAPH-", 0x18D00, 0x18D08},
    {"KHITAN SMALL SCRIPT CHARACTER-", 0x18B00, 0x18CD5},
    {"NUSHU CHARACTER-", 0x1B170, 0x1B2FB},
    {"CJK COMPATIBILITY IDEOGRAPH-", 0xF900, 0xFA6D},
    {"CJK COMPATIBILITY IDEOGRAPH-", 0xFA70, 0xFAD9},
    {"CJK COMPATIBILITY IDEOGRAPH-", 0x2F800, 0x2FA1D},
}
</div>
</dd>
</dl>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Referenced by <a href="#ae507b357fbb69fc2cb019831c4d66dd8">nameToGeneratedCodePoint</a>.</p>

</div>
</div>

### HangulSyllables {#a736c33ad03787045b50857d685ab1e72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::sys::unicode::HangulSyllables[][3]</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">= {
    { "G",  "A",   ""   },
    { "GG", "AE",  "G"  },
    { "N",  "YA",  "GG" },
    { "D",  "YAE", "GS" },
    { "DD", "EO",  "N", },
    { "R",  "E",   "NJ" },
    { "M",  "YEO", "NH" },
    { "B",  "YE",  "D"  },
    { "BB", "O",   "L"  },
    { "S",  "WA",  "LG" },
    { "SS", "WAE", "LM" },
    { "",   "OE",  "LB" },
    { "J",  "YO",  "LS" },
    { "JJ", "U",   "LT" },
    { "C",  "WEO", "LP" },
    { "K",  "WE",  "LH" },
    { "T",  "WI",  "M"  },
    { "P",  "YU",  "B"  },
    { "H",  "EU",  "BS" },
    { 0,    "YI",  "S"  },
    { 0,    "I",   "SS" },
    { 0,    0,     "NG" },
    { 0,    0,     "J"  },
    { 0,    0,     "C"  },
    { 0,    0,     "K"  },
    { 0,    0,     "T"  },
    { 0,    0,     "P"  },
    { 0,    0,     "H"  }
    }
</div>
</dd>
</dl>

<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Referenced by <a href="#abf9183145a865f67edbedc0b24767fd1">findSyllable</a> and <a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a>.</p>

</div>
</div>

### LCount {#a8fda06c0bf8c01df9eb8a6774c19732a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::sys::unicode::LCount = 19</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 255 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Referenced by <a href="#abf9183145a865f67edbedc0b24767fd1">findSyllable</a>.</p>

</div>
</div>

### SBase {#ae56aadf48006c8538ac3e9fc3bf220b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char32_t llvm::sys::unicode::SBase = 0xAC00</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Referenced by <a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a>.</p>

</div>
</div>

### TCount {#a1903a9794d4cb8724f7d69a17d7ca374}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::sys::unicode::TCount = 28</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Referenced by <a href="#abf9183145a865f67edbedc0b24767fd1">findSyllable</a> and <a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a>.</p>

</div>
</div>

### UnicodeNameToCodepointDict {#ae56be6a91b21a2c87e2a892feaafbb5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::sys::unicode::UnicodeNameToCodepointDict</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepointgenerated-cpp">UnicodeNameToCodepointGenerated.cpp</a>.</p>


<p>Referenced by <a href="#a1595de063cd60f1beb94ab845204e496">readNode</a>.</p>

</div>
</div>

### UnicodeNameToCodepointIndex {#aa26b63e047af075f66f62cfc5c68bbf1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint8_t * llvm::sys::unicode::UnicodeNameToCodepointIndex = <a href="#a269dcd773d0d47d82b03308f35edcedb">UnicodeNameToCodepointIndex_</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21172 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepointgenerated-cpp">UnicodeNameToCodepointGenerated.cpp</a>.</p>


<p>Referenced by <a href="#a1595de063cd60f1beb94ab845204e496">readNode</a>.</p>

</div>
</div>

### UnicodeNameToCodepointIndex\_ {#a269dcd773d0d47d82b03308f35edcedb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t llvm::sys::unicode::UnicodeNameToCodepointIndex_[242258]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 982 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepointgenerated-cpp">UnicodeNameToCodepointGenerated.cpp</a>.</p>

</div>
</div>

### UnicodeNameToCodepointIndexSize {#a5a762a9920553a2a43f09cb37ac5bccf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::size_t llvm::sys::unicode::UnicodeNameToCodepointIndexSize = 242258</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21173 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepointgenerated-cpp">UnicodeNameToCodepointGenerated.cpp</a>.</p>


<p>Referenced by <a href="#a1595de063cd60f1beb94ab845204e496">readNode</a>.</p>

</div>
</div>

### UnicodeNameToCodepointLargestNameSize {#a250725ca9390c4a4206f153d57debabe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::size_t llvm::sys::unicode::UnicodeNameToCodepointLargestNameSize = 74</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 21174 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepointgenerated-cpp">UnicodeNameToCodepointGenerated.cpp</a>.</p>


<p>Referenced by <a href="#a4e10ba09dea9d13b485ec2a68efb4f98">nearestMatchesForCodepointName</a>.</p>

</div>
</div>

### VCount {#a953904b870805e1b6729dfc171733361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t llvm::sys::unicode::VCount = 21</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a>.</p>


<p>Referenced by <a href="#abf9183145a865f67edbedc0b24767fd1">findSyllable</a> and <a href="#a9496c295025807ea2778038622f3ba2e">nameToHangulCodePoint</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/unicode-h">Unicode.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/unicode-cpp">Unicode.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/unicodecasefold-cpp">UnicodeCaseFold.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepoint-cpp">UnicodeNameToCodepoint.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/unicodenametocodepointgenerated-cpp">UnicodeNameToCodepointGenerated.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
