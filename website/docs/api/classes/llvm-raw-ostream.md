---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/raw-ostream
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `raw_ostream` Class Reference

<p>This class implements an extremely fast bulk output stream that can <em>only</em> output to a stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::raw_ostream { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-goffemitter-cpp-/goffostream">GOFFOstream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-goffobjectwriter-cpp-/goffostream">GOFFOstream</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream">circular_raw_ostream</a> - A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> which <em>can</em> save its data to a circular buffer, or can pass it through directly to an underlying stream if specified with a buffer of zero. <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> - A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that wraps another one and keeps track of line and column position, allowing padding out to specific column boundaries and querying the number of lines written to the stream. <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-os-ostream">raw_os_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/raw-os-ostream">raw_os_ostream</a> - A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to an std::ostream. <a href="/web-llvm/docs/api/classes/llvm/raw-os-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream">raw_pwrite_stream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract base class for streams implementations that also support a pwrite operation. <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-sha1-ostream">raw_sha1_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that hash the content using the sha1 algorithm. <a href="/web-llvm/docs/api/classes/llvm/raw-sha1-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream">raw_string_ostream</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> that writes to an std::string. <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2a4949bc82f743fb17bd9131e7041b">uuid_t</a> = uint8_t[16]</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output a formatted <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> with dash separators. <a href="#aad2a4949bc82f743fb17bd9131e7041b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OStreamKind { <a href="#ad85a9ad7858d658c954afde33bcf3d43">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Colors { <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">BufferKind { <a href="#a8131bb2ae3e658376ab2a2f3b8d715d6">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> (bool unbuffered=false, OStreamKind K=OStreamKind::OK_OStream)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac686d47980294a15635a65dee6bcab65">raw_ostream</a> (const raw_ostream &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5231543b6b40176238cc62b982f4bdf5">~raw_ostream</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac725aaaafa45384bad3197e47c74be4c">operator=</a> (const raw_ostream &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b9992ae460e4e0fb0fa7ce054494e8">operator&lt;&lt;</a> (char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a075cb7ac15c51197e4db4100b32a9fb2">operator&lt;&lt;</a> (unsigned char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d7ad838c3518917424debc6be5ae9aa">operator&lt;&lt;</a> (signed char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaffa29e8a30c948243c84abf6b92a54">operator&lt;&lt;</a> (StringRef Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4379610669a40c09242de6f02bf715b">operator&lt;&lt;</a> (const char *Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae00dbdc15d9b90a48e1326c50a2c0bc6">operator&lt;&lt;</a> (const std::string &amp;Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a194a494c85e146be05d9e6fac49a5945">operator&lt;&lt;</a> (const std::string_view &amp;Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac88eab7965bf3a6d7c553f17e68d1513">operator&lt;&lt;</a> (const SmallVectorImpl&lt; char &gt; &amp;Str)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0e27cd90adc0b6beb89033845f9823d">operator&lt;&lt;</a> (unsigned long N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9d57be5c0397ea87d9f634929629c25">operator&lt;&lt;</a> (long N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45acd041c106c28341db5ef6c38d8125">operator&lt;&lt;</a> (unsigned long long N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acabcb5001c45027cf69ca516a38f9e77">operator&lt;&lt;</a> (long long N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8300c9b501bef90a5642fc3ef7807b0c">operator&lt;&lt;</a> (const void *P)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae161a943836d575a59a8c84534ed6dcf">operator&lt;&lt;</a> (unsigned int N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcf9b50e849ae41a25c3ac13ab1f1028">operator&lt;&lt;</a> (int N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0901ea2124ad30e3766766e20ed3a73e">operator&lt;&lt;</a> (double N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6683621f818ca79cfe58e9bc0136d12">operator&lt;&lt;</a> (Colors C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a8d18dc26984414573e1d152d89a5e2">operator&lt;&lt;</a> (const format_object_base &amp;Fmt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad72c5336e2ff27aefee791348d4e1680">operator&lt;&lt;</a> (const FormattedString &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980a91d30111be065234c1dac2f067e1">operator&lt;&lt;</a> (const FormattedNumber &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5283ab203049acfffb2dd233f816402">operator&lt;&lt;</a> (const formatv_object_base &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebda89a6230d3b4ac098b18b57c16f4b">operator&lt;&lt;</a> (const FormattedBytes &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f90ad570f71349466844ee9f2d06cd1">tell</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>tell - Return the current offset with the file. <a href="#a0f90ad570f71349466844ee9f2d06cd1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad85a9ad7858d658c954afde33bcf3d43">OStreamKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3aec1d6c89f3eed88579d13ade51ea0">get_kind</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65ed6b6a8c96b6c1dc98ba50bc1547a">reserveExtraSpace</a> (uint64_t ExtraSize)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If possible, pre-allocate <span class="doxyComputerOutput">ExtraSize</span> bytes for stream data. <a href="#ad65ed6b6a8c96b6c1dc98ba50bc1547a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6e095a40885b6ed93dcdeb112ceeab2">SetBuffered</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the stream to be buffered, with an automatically determined buffer size. <a href="#af6e095a40885b6ed93dcdeb112ceeab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a59a3dce2d7cde8c5e6ef0e3a30b375">SetBufferSize</a> (size_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the stream to be buffered, using the specified buffer size. <a href="#a1a59a3dce2d7cde8c5e6ef0e3a30b375">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d79232a41a2f24d43acb936c8522443">GetBufferSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75860636a752bc2592f6e4185e63efdc">SetUnbuffered</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the stream to be unbuffered. <a href="#a75860636a752bc2592f6e4185e63efdc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6cd89674692383208613b1e4ee560fe">GetNumBytesInBuffer</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a520bdf57dfe3e73abb53d482893f0a27">flush</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b5dd8a8b82f2818e0f4ea9699d8ae5">write_hex</a> (unsigned long long N)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output <span class="doxyComputerOutput">N</span> in hexadecimal, without any prefix or padding. <a href="#a37b5dd8a8b82f2818e0f4ea9699d8ae5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e6042cae3a8ab74080998736eabd3fa">write_uuid</a> (const uuid_t UUID)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ba2ece4b959bae02752c34b784ba087">write_escaped</a> (StringRef Str, bool UseHexEscapes=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Output <span class="doxyComputerOutput">Str</span>, turning '\', '\t', '
<br/>
', '"', and anything that doesn't satisfy llvm::isPrint into an escape sequence. <a href="#a5ba2ece4b959bae02752c34b784ba087">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a> (unsigned char C)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a581a276005e9f911c53aa145e4a01e53">write</a> (const char *Ptr, size_t Size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fdf5cdf041c8aded7e3308c1c3efacc">indent</a> (unsigned NumSpaces)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>indent - Insert 'NumSpaces' spaces. <a href="#a8fdf5cdf041c8aded7e3308c1c3efacc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06288f4d38e1d74fc7a1d10056d88373">write_zeros</a> (unsigned NumZeros)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>write_zeros - Insert 'NumZeros' nulls. <a href="#a06288f4d38e1d74fc7a1d10056d88373">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28fa4a2054d6d628fa4eea21c5262212">changeColor</a> (enum Colors Color, bool Bold=false, bool BG=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Changes the foreground color of text that will be output from this point forward. <a href="#a28fa4a2054d6d628fa4eea21c5262212">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4219e33c3cd0cc8383f615fc40254d21">resetColor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Resets the colors to terminal defaults. <a href="#a4219e33c3cd0cc8383f615fc40254d21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6095e2a0ebe961a05e2b3a7b6acbe769">reverseColor</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reverses the foreground and background colors. <a href="#a6095e2a0ebe961a05e2b3a7b6acbe769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f6a957a67e05e7355ab616619ee2608">is_displayed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if this stream is connected to a "tty" or "console" window. <a href="#a8f6a957a67e05e7355ab616619ee2608">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5c85e2158de685ed0c287a13c07ea49">has_colors</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function determines if this stream is displayed and supports colors. <a href="#ae5c85e2158de685ed0c287a13c07ea49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb9477fc02ae36079df14aa77d8789c3">enable_colors</a> (bool enable)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff9ac3b7e5094380eca385afd6023cd4">colors_enabled</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61bcdba2623dbce59a5f460650255db2">SetBuffer</a> (char *BufferStart, size_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the provided buffer as the <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> buffer. <a href="#a61bcdba2623dbce59a5f460650255db2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6799a9c00e1099623cec7e887f93eb57">preferred_buffer_size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an efficient buffer size for the underlying output mechanism. <a href="#a6799a9c00e1099623cec7e887f93eb57">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a980ad6112624b521eb2d831b39b346eb">getBufferStart</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the beginning of the current stream buffer, or 0 if the stream is unbuffered. <a href="#a980ad6112624b521eb2d831b39b346eb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff81bd777453e69313941c475ec2a848">write_impl</a> (const char *Ptr, size_t Size)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The is the piece of the class that is implemented by subclasses. <a href="#aff81bd777453e69313941c475ec2a848">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ba24fa2187fb1b7bcf1a7458db20d13">current_pos</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the current position within the stream, not counting the bytes currently in the buffer. <a href="#a7ba24fa2187fb1b7bcf1a7458db20d13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0495921bc3d6e243c1b81bd0cd5fbcc">SetBufferAndMode</a> (char *BufferStart, size_t Size, BufferKind Mode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Install the given buffer and mode. <a href="#ad0495921bc3d6e243c1b81bd0cd5fbcc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0eabc6d24e282c292b2fdc482007f2e">flush_nonempty</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flush the current buffer, which is known to be non-empty. <a href="#aa0eabc6d24e282c292b2fdc482007f2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7a586a50af93a4a0305e9be41adbdd4">copy_to_buffer</a> (const char *Ptr, size_t Size)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Copy data into the buffer. <a href="#ab7a586a50af93a4a0305e9be41adbdd4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11bb5ca6e8b421e64a19a6282e616254">prepare_colors</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute whether colors should be used and do the necessary work such as flushing. <a href="#a11bb5ca6e8b421e64a19a6282e616254">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0759e19a1af03fb90ddfac33c74c03">anchor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad85a9ad7858d658c954afde33bcf3d43">OStreamKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89b9937ca5327a89c670129e961b630">Kind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0045edfef76e8e677ae2ca6edf1d3104">OutBufStart</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The buffer is handled in such a way that the buffer is uninitialized, unbuffered, or out of space when OutBufCur &gt;= OutBufEnd. <a href="#a0045edfef76e8e677ae2ca6edf1d3104">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a090dd09f34514feed92a95eee1f278b7">OutBufEnd</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fb90e40352be6091e0344c54b3e8918">OutBufCur</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb8c9ab6da25408ba291e4815bcd03b5">ColorEnabled</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum llvm::raw_ostream::BufferKind</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a884983dc651f6edc8ee6f6194b8d94dc">BufferMode</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7fa72c34a893a70df723e8c90410864">BLACK</a> = Colors::BLACK</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7b7856e1bc7aea739f05e4d65d5276b">RED</a> = Colors::RED</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae56223ff7592f05301a6b496ae46299c">GREEN</a> = Colors::GREEN</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a026561b02ba397a040ff1e681d2fb0ae">YELLOW</a> = Colors::YELLOW</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63c9d9dc86ce5675ba81e57258408628">BLUE</a> = Colors::BLUE</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abab3a5904ddc74e76f0a8021d383866f">MAGENTA</a> = Colors::MAGENTA</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b89c1fc567cf8889baeccead5083434">CYAN</a> = Colors::CYAN</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcd12a4a8e2d561e7dd31b4c05b2053">WHITE</a> = Colors::WHITE</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1ed300c78ba04b636a61ecb147c92ce">BRIGHT_BLACK</a> = Colors::BRIGHT_BLACK</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a335509d3624637f5c80198c97f3c00">BRIGHT_RED</a> = Colors::BRIGHT_RED</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9db6917b73438040622a62595123fbc">BRIGHT_GREEN</a> = Colors::BRIGHT_GREEN</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7d521f5dc48e516c88ae329cf2ebb7e">BRIGHT_YELLOW</a> = Colors::BRIGHT_YELLOW</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35171b7d8e8bd280c9ca13cee2e342c">BRIGHT_BLUE</a> = Colors::BRIGHT_BLUE</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa87ef9bf0a5af081e8f10606cb5e8687">BRIGHT_MAGENTA</a> = Colors::BRIGHT_MAGENTA</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02a884bafdecf4c92bd7bb2ebec2b33">BRIGHT_CYAN</a> = Colors::BRIGHT_CYAN</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae493f4fdc4c0739416102c6bd5b432a7">BRIGHT_WHITE</a> = Colors::BRIGHT_WHITE</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad55e55b3692fe8ec3e8b724d3d5bade0">SAVEDCOLOR</a> = Colors::SAVEDCOLOR</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ba1327251e8c5c71480b9876c52f4e4">RESET</a> = Colors::RESET</td>
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

<p>This class implements an extremely fast bulk output stream that can <em>only</em> output to a stream.</p>


<p>It does not support seeking, reopening, rewinding, line buffered disciplines etc. It is a simple buffer that outputs a chunk at a time.</p>


<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### uuid\_t {#aad2a4949bc82f743fb17bd9131e7041b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::raw_ostream::uuid_t =  uint8_t[16]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Output a formatted <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> with dash separators.</p>

<p>Definition at line 296 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### BufferKind {#a8131bb2ae3e658376ab2a2f3b8d715d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::raw_ostream::BufferKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Unbuffered<a id="a8131bb2ae3e658376ab2a2f3b8d715d6a7b889cd81153bef60d4f3ea9038f5894"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InternalBuffer<a id="a8131bb2ae3e658376ab2a2f3b8d715d6a3cf6dfafac7305c5dda44ef38916691a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ExternalBuffer<a id="a8131bb2ae3e658376ab2a2f3b8d715d6a3a6ecebdb9754637d24b3a978b0c628f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### Colors {#a1d5efc43dd5669473ac2fe47d5aaf965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::raw_ostream::Colors </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">BLACK<a id="a1d5efc43dd5669473ac2fe47d5aaf965a08d0012388564e95c3b4a7407cf04965"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RED<a id="a1d5efc43dd5669473ac2fe47d5aaf965aa2d9547b5d3dd9f05984475f7c926da0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GREEN<a id="a1d5efc43dd5669473ac2fe47d5aaf965a9de0e5dd94e861317e74964bed179fa0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">YELLOW<a id="a1d5efc43dd5669473ac2fe47d5aaf965a8a568e5f41b7e4da88fe5c4a00aad34e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BLUE<a id="a1d5efc43dd5669473ac2fe47d5aaf965a1b3e1ee9bff86431dea6b181365ba65f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MAGENTA<a id="a1d5efc43dd5669473ac2fe47d5aaf965ac634ffea7195608364671ac52ee59a61"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CYAN<a id="a1d5efc43dd5669473ac2fe47d5aaf965a344dd8cd533280795b9db82ef0c92749"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WHITE<a id="a1d5efc43dd5669473ac2fe47d5aaf965ab5bf627e448384cf3a4c35121ca6008d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_BLACK<a id="a1d5efc43dd5669473ac2fe47d5aaf965aae7e8e8f5ddf114057b47f5f799347b1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_RED<a id="a1d5efc43dd5669473ac2fe47d5aaf965a01fd5046e2769cae7b662d3dfbb64045"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_GREEN<a id="a1d5efc43dd5669473ac2fe47d5aaf965a7ca9c0eccf9c3fa7fe85fea8404d50a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_YELLOW<a id="a1d5efc43dd5669473ac2fe47d5aaf965a2373edc9b8eb3a49710b95c6f7906434"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_BLUE<a id="a1d5efc43dd5669473ac2fe47d5aaf965ad187a715c27ec1e774325b6715f4da67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_MAGENTA<a id="a1d5efc43dd5669473ac2fe47d5aaf965acdbf2435d34544195dd18a6b31953951"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_CYAN<a id="a1d5efc43dd5669473ac2fe47d5aaf965aa74a6a719de5de03a46f89ce260fa4b7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BRIGHT_WHITE<a id="a1d5efc43dd5669473ac2fe47d5aaf965a376520e57593580aa5c7ef8cf5136946"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SAVEDCOLOR<a id="a1d5efc43dd5669473ac2fe47d5aaf965abd8a983d726207f3d1ba3ea7e2cfdf2a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RESET<a id="a1d5efc43dd5669473ac2fe47d5aaf965ab5859d8721cfdc0312b2838b9c985bc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### OStreamKind {#ad85a9ad7858d658c954afde33bcf3d43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::raw_ostream::OStreamKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">OK_OStream<a id="ad85a9ad7858d658c954afde33bcf3d43a2bdd687fb19e606203cb02f5c50bf07b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OK_FDStream<a id="ad85a9ad7858d658c954afde33bcf3d43a8dfae711fb29865c49b78c8ea1a6f782"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OK_SVecStream<a id="ad85a9ad7858d658c954afde33bcf3d43a091bc9597603430daadbc899a42f6408"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### raw\_ostream() {#a0f4b64a0f7aec0a02e7f2ff5a6552723}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_ostream::raw_ostream (bool unbuffered=false, <a href="#ad85a9ad7858d658c954afde33bcf3d43">OStreamKind</a> K=<a href="#ad85a9ad7858d658c954afde33bcf3d43a2bdd687fb19e606203cb02f5c50bf07b">OStreamKind::OK_OStream</a>)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="#ad85a9ad7858d658c954afde33bcf3d43a2bdd687fb19e606203cb02f5c50bf07b">OK_OStream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a28c28221c236cdabcd2e6553854ed278">llvm::formatted_raw_ostream::changeColor</a>, <a href="#a28fa4a2054d6d628fa4eea21c5262212">changeColor</a>, <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream/#a42664fb7b2765468ff290e0b46cbb079">llvm::circular_raw_ostream::circular_raw_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#adb8a7ef601b3598707e6ae9a6c9f6e4d">llvm::formatted_raw_ostream::formatted_raw_ostream</a>, <a href="/web-llvm/docs/api/classes/anonymous-goffemitter-cpp-/goffostream/#a9c5065f0b1869918c137eeb8b30b2ce6">anonymous{GOFFEmitter.cpp}::GOFFOstream::GOFFOstream</a>, <a href="#a8fdf5cdf041c8aded7e3308c1c3efacc">indent</a>, <a href="#a51b9992ae460e4e0fb0fa7ce054494e8">operator&lt;&lt;</a>, <a href="#ab6683621f818ca79cfe58e9bc0136d12">operator&lt;&lt;</a>, <a href="#ac4379610669a40c09242de6f02bf715b">operator&lt;&lt;</a>, <a href="#a0a8d18dc26984414573e1d152d89a5e2">operator&lt;&lt;</a>, <a href="#aebda89a6230d3b4ac098b18b57c16f4b">operator&lt;&lt;</a>, <a href="#a980a91d30111be065234c1dac2f067e1">operator&lt;&lt;</a>, <a href="#ad72c5336e2ff27aefee791348d4e1680">operator&lt;&lt;</a>, <a href="#ac5283ab203049acfffb2dd233f816402">operator&lt;&lt;</a>, <a href="#ac88eab7965bf3a6d7c553f17e68d1513">operator&lt;&lt;</a>, <a href="#ae00dbdc15d9b90a48e1326c50a2c0bc6">operator&lt;&lt;</a>, <a href="#a194a494c85e146be05d9e6fac49a5945">operator&lt;&lt;</a>, <a href="#a8300c9b501bef90a5642fc3ef7807b0c">operator&lt;&lt;</a>, <a href="#a0901ea2124ad30e3766766e20ed3a73e">operator&lt;&lt;</a>, <a href="#abcf9b50e849ae41a25c3ac13ab1f1028">operator&lt;&lt;</a>, <a href="#acabcb5001c45027cf69ca516a38f9e77">operator&lt;&lt;</a>, <a href="#ae9d57be5c0397ea87d9f634929629c25">operator&lt;&lt;</a>, <a href="#a9d7ad838c3518917424debc6be5ae9aa">operator&lt;&lt;</a>, <a href="#acaffa29e8a30c948243c84abf6b92a54">operator&lt;&lt;</a>, <a href="#a075cb7ac15c51197e4db4100b32a9fb2">operator&lt;&lt;</a>, <a href="#ae161a943836d575a59a8c84534ed6dcf">operator&lt;&lt;</a>, <a href="#a45acd041c106c28341db5ef6c38d8125">operator&lt;&lt;</a>, <a href="#aa0e27cd90adc0b6beb89033845f9823d">operator&lt;&lt;</a>, <a href="#ac725aaaafa45384bad3197e47c74be4c">operator=</a>, <a href="#ac686d47980294a15635a65dee6bcab65">raw_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#a6114ce21446653490e1d609d876b42eb">llvm::raw_pwrite_stream::raw_pwrite_stream</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a255a1144d50063acc74b8b5143697694">llvm::formatted_raw_ostream::resetColor</a>, <a href="#a4219e33c3cd0cc8383f615fc40254d21">resetColor</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#af55e6fb1fbaadb04b201cba1f302d7b9">llvm::formatted_raw_ostream::reverseColor</a>, <a href="#a6095e2a0ebe961a05e2b3a7b6acbe769">reverseColor</a>, <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream/#abc8b7debcef19eb1c6c0dd39cec3f7f6">llvm::circular_raw_ostream::setStream</a>, <a href="#a581a276005e9f911c53aa145e4a01e53">write</a>, <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>, <a href="#a5ba2ece4b959bae02752c34b784ba087">write_escaped</a>, <a href="#a37b5dd8a8b82f2818e0f4ea9699d8ae5">write_hex</a>, <a href="#a4e6042cae3a8ab74080998736eabd3fa">write_uuid</a> and <a href="#a06288f4d38e1d74fc7a1d10056d88373">write_zeros</a>.</p>

</div>
</div>

### raw\_ostream() {#ac686d47980294a15635a65dee6bcab65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::raw_ostream::raw_ostream (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~raw\_ostream() {#a5231543b6b40176238cc62b982f4bdf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::~raw_ostream ()</td>
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



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&lt;&lt;() {#a51b9992ae460e4e0fb0fa7ce054494e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (char C)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>


<p>Referenced by <a href="#ac4379610669a40c09242de6f02bf715b">operator&lt;&lt;</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a075cb7ac15c51197e4db4100b32a9fb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (unsigned char C)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a9d7ad838c3518917424debc6be5ae9aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (signed char C)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#acaffa29e8a30c948243c84abf6b92a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ac4379610669a40c09242de6f02bf715b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Str)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="#a51b9992ae460e4e0fb0fa7ce054494e8">operator&lt;&lt;</a> and <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ae00dbdc15d9b90a48e1326c50a2c0bc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; Str)</td>
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



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a194a494c85e146be05d9e6fac49a5945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string_view &amp; Str)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ac88eab7965bf3a6d7c553f17e68d1513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; char &gt; &amp; Str)</td>
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



<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#aa0e27cd90adc0b6beb89033845f9823d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (unsigned long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bf1d985e33127a9930a309cfdfdb093">llvm::write_integer</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ae9d57be5c0397ea87d9f634929629c25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 274 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 130 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bf1d985e33127a9930a309cfdfdb093">llvm::write_integer</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a45acd041c106c28341db5ef6c38d8125}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (unsigned long long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 135 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bf1d985e33127a9930a309cfdfdb093">llvm::write_integer</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#acabcb5001c45027cf69ca516a38f9e77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (long long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 276 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 140 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bf1d985e33127a9930a309cfdfdb093">llvm::write_integer</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a8300c9b501bef90a5642fc3ef7807b0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> void * P)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 277 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0aff4b514f126214ab6ab5ab9ecd249cd6">llvm::PrefixLower</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aedb7c876c118bfb3b40eb756db6f9">llvm::write_hex</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ae161a943836d575a59a8c84534ed6dcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (unsigned int N)</td>
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



<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#abcf9b50e849ae41a25c3ac13ab1f1028}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; llvm::raw_ostream::operator&lt;&lt; (int N)</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a0901ea2124ad30e3766766e20ed3a73e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (double N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a403260df3a211e47e65f35fbfd9bee8faf5ccb8d51ca38e2f3329955fc0149cd4">llvm::Exponent</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abadfa6a189135012fde92b57982b2ce2">llvm::write_double</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ab6683621f818ca79cfe58e9bc0136d12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (<a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a> C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 293 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a28fa4a2054d6d628fa4eea21c5262212">changeColor</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="#a1d5efc43dd5669473ac2fe47d5aaf965ab5859d8721cfdc0312b2838b9c985bc1">RESET</a> and <a href="#a4219e33c3cd0cc8383f615fc40254d21">resetColor</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a0a8d18dc26984414573e1d152d89a5e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/format-object-base">format_object_base</a> &amp; Fmt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 307 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/format-object-base/#a5b6aaf8cbdc3d3660bef42e1556908f1">llvm::format_object_base::print</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ad72c5336e2ff27aefee791348d4e1680}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/formattedstring">FormattedString</a> &amp; FS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 310 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 353 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="#a8fdf5cdf041c8aded7e3308c1c3efacc">indent</a>, <a href="/web-llvm/docs/api/classes/llvm/formattedstring/#a3cf16524a65f4bdfbcbb608b8fd87725a3dc39d17c7fa3ae14c44b1d19d4f70f4">llvm::FormattedString::JustifyCenter</a>, <a href="/web-llvm/docs/api/classes/llvm/formattedstring/#a3cf16524a65f4bdfbcbb608b8fd87725a1eb15418063202b1d1c26b6d5f4a7833">llvm::FormattedString::JustifyLeft</a>, <a href="/web-llvm/docs/api/classes/llvm/formattedstring/#a3cf16524a65f4bdfbcbb608b8fd87725aef35f4c8ca4f4fd5c1cc68618f3deb8c">llvm::FormattedString::JustifyNone</a>, <a href="/web-llvm/docs/api/classes/llvm/formattedstring/#a3cf16524a65f4bdfbcbb608b8fd87725a9ffe6369d59900ade00509c0df864887">llvm::FormattedString::JustifyRight</a> and <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#a980a91d30111be065234c1dac2f067e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/formattednumber">FormattedNumber</a> &amp; FN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 379 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="#a8fdf5cdf041c8aded7e3308c1c3efacc">indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af83da56920f4f1059b02e07966f9fccfaa0faef0851b4294c06f2b94bb1cb2044">llvm::Integer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0aff4b514f126214ab6ab5ab9ecd249cd6">llvm::PrefixLower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a3cc854288a88eeb0ef88c4fc91ee69c6">llvm::PrefixUpper</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aedb7c876c118bfb3b40eb756db6f9">llvm::write_hex</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5bf1d985e33127a9930a309cfdfdb093">llvm::write_integer</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#ac5283ab203049acfffb2dd233f816402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base">formatv_object_base</a> &amp; Obj)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 316 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 348 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#a1909dc6f7823cf0b4c30885197406471">llvm::formatv_object_base::format</a> and <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>

</div>
</div>

### operator&lt;&lt;() {#aebda89a6230d3b4ac098b18b57c16f4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::operator&lt;&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/formattedbytes">FormattedBytes</a> &amp; FB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a8fdf5cdf041c8aded7e3308c1c3efacc">indent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a238ef12f09938dac4efe5ca56dc125d9">llvm::Log2_64_Ceil</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aedb7c876c118bfb3b40eb756db6f9">llvm::write_hex</a>.</p>

</div>
</div>

### operator=() {#ac725aaaafa45384bad3197e47c74be4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_ostream::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### changeColor() {#a28fa4a2054d6d628fa4eea21c5262212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::changeColor (enum <a href="#a1d5efc43dd5669473ac2fe47d5aaf965">Colors</a> Color, bool Bold=false, bool BG=false)</td>
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

<p>Changes the foreground color of text that will be output from this point forward.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Color</td>
<td class="doxyParamItemDescription"><p>ANSI color to use, the special SAVEDCOLOR can be used to change only the bold attribute, and keep colors untouched</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Bold</td>
<td class="doxyParamItemDescription"><p>bold/brighter text, default false</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">BG</td>
<td class="doxyParamItemDescription"><p>if true change the background, default: change foreground</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>itself so it can be used within &lt;&lt; invocations</p></dd>
</dl>


<p>Declaration at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 520 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a5f838fbf3e04fdf7763b38ae5c499bbe">llvm::sys::Process::OutputBold</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#a17881ed9155bdf983b849c4c69c365b0">llvm::sys::Process::OutputColor</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="#ad55e55b3692fe8ec3e8b724d3d5bade0">SAVEDCOLOR</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a28c28221c236cdabcd2e6553854ed278">llvm::formatted_raw_ostream::changeColor</a> and <a href="#ab6683621f818ca79cfe58e9bc0136d12">operator&lt;&lt;</a>.</p>

</div>
</div>

### colors\_enabled() {#aff9ac3b7e5094380eca385afd6023cd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_ostream::colors_enabled ()</td>
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



<p>Definition at line 357 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a28c28221c236cdabcd2e6553854ed278">llvm::formatted_raw_ostream::changeColor</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a255a1144d50063acc74b8b5143697694">llvm::formatted_raw_ostream::resetColor</a> and <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#af55e6fb1fbaadb04b201cba1f302d7b9">llvm::formatted_raw_ostream::reverseColor</a>.</p>

</div>
</div>

### enable\_colors() {#abb9477fc02ae36079df14aa77d8789c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::raw_ostream::enable_colors (bool enable)</td>
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



<p>Definition at line 355 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcdisassembler/#ga4ab4dad1fdcb9e651fa60f6059ab09b4">LLVMDisasmInstruction</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a8006c8875484467031d61b1e671cfede">llvm::raw_fd_ostream::raw_fd_ostream</a>.</p>

</div>
</div>

### flush() {#a520bdf57dfe3e73abb53d482893f0a27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_ostream::flush ()</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-irsymtab-cpp-/builder/#a15ad3b408efc55e12e201e1cd1dfbc45">anonymous{IRSymtab.cpp}::Builder::addSymbol</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a293545f9b5864a8e1b33e57becbc5b3a">llvm::raw_fd_ostream::close</a>, <a href="/web-llvm/docs/api/classes/anonymous-fileoutputbuffer-cpp-/inmemorybuffer/#aa633fcd4ff4b9eb332ba7f26d090c10a">anonymous{FileOutputBuffer.cpp}::InMemoryBuffer::commit</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a5be3fea922116aa226fc27bde3419182">computeStringTable</a>, <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#ae8bbdd648bb050563755e846cdf43932">llvm::LTOCodeGenerator::DiagnosticHandler</a>, <a href="/web-llvm/docs/api/classes/llvm/importedfunctionsinliningstatistics/#a776e5ef304e07acc5bbbf585443459a4">llvm::ImportedFunctionsInliningStatistics::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a1514e3ae4b6c55b9394b3271c4f06a6f">llvm::pdb::PDBSymbol::dumpChildStats</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbsymbol/#a8bdbb44382f06651fe82fe060de7fd99">llvm::pdb::PDBSymbol::dumpProperties</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/lib/mc/mcdisassembler/disassembler-cpp/#a0e50dc982f01eab3eeb5eef624e25f03">emitComments</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a1bf0b70372e2ca4b1e9540e9c4f8aa41">emitDebugSectionImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilecoff/#a88c088e4fb14a140785c69f3af654b55">llvm::TargetLoweringObjectFileCOFF::emitLinkerDirectives</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4b27e8ffe711b0dcbc16b19671d5edc">llvm::emitLinkerFlagsForGlobalCOFF</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41e273066032e223f6423e84ff4a0249">llvm::format</a>, <a href="/web-llvm/docs/api/classes/anonymous-standardinstrumentations-cpp-/dotcfgdiffdisplaygraph/#af15f59a940b7e5ce205f671241664985">anonymous{StandardInstrumentations.cpp}::DotCfgDiffDisplayGraph::generateDotFile</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a493e72ce53ee16d92489ba67d7ce2bb0">llvm::Attribute::getAsString</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machineblockplacement-cpp/#a8f9ee7f9ffc036496a8663335da175fa">getBlockName</a>, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#ac3fd4c945029b6ece24a347676056f86">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getEdgeAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/refscc/#ac30dc61a31f34e7359336fa637104bfb">llvm::LazyCallGraph::RefSCC::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/lazycallgraph/scc/#abac122ed462169c3afbf43309644b415">llvm::LazyCallGraph::SCC::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/structs/llvm/bfidotgraphtraitsbase/#a1c78d4d6544b97f0fb4219ec8a99c54b">llvm::BFIDOTGraphTraitsBase&lt; BlockFrequencyInfo, BranchProbabilityInfo &gt;::getNodeAttributes</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkparser-cpp/#ab579a679ef1379aa93f97bca62dedd1c">handleDiagnostic</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4ea2d791b0cb2b452a1d9ccfaf181712">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::IsSameAsFreshTree</a>, <a href="/web-llvm/docs/api/groups/llvmccorecontext/#ga4aaf10ddcd079155b0845d9e19987917">LLVMGetDiagInfoDescription</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluegeneral/#gaae8965c52ac55f5e8d5b58fccbea9c2a">LLVMPrintDbgRecordToString</a>, <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gae0d61246e5b4f768588aef14e124a96b">LLVMPrintModuleToString</a>, <a href="/web-llvm/docs/api/groups/llvmccoretype/#ga8dc1081c3c9a3928fccedb59a41d319e">LLVMPrintTypeToString</a>, <a href="/web-llvm/docs/api/groups/llvmccorevaluegeneral/#gaf8b442b67e59615cadfb43f4f54b237e">LLVMPrintValueToString</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/targetmachinec-cpp/#a380dad8a77bc823770e1488a704ae8ca">LLVMTargetMachineEmit</a>, <a href="/web-llvm/docs/api/groups/llvmctarget/#ga8d5be4abc46b15b48cebc50bdbcf219b">LLVMTargetMachineEmitToFile</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfounsupported/#a12864403c3efdae1dac8ca322dedf9ba">llvm::DiagnosticInfoUnsupported::print</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4956c1072998f3de28fb64a8979fcbf5">llvm::PrintStatistics</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aec1a19ebf309a206257e212c33f045a1">llvm::PrintStatisticsJSON</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#af1491396cfef16b592355c5ba7fca450">reportError</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a041e682560afc980462e5ca47deb1f24">reportOpenError</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/mircanonicalizerpass-cpp/#a10ae65e3c5a7ffa45ad8a1ba47c98b5a">rescheduleLexographically</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a9e2a27de71f137279ac47e6edd4abc47">llvm::raw_fd_ostream::seek</a>, <a href="#a1a59a3dce2d7cde8c5e6ef0e3a30b375">SetBufferSize</a>, <a href="#a75860636a752bc2592f6e4185e63efdc">SetUnbuffered</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-sha1-ostream/#ae97bc497cdd81ca9063def3bda77a40f">llvm::raw_sha1_ostream::sha1</a>, <a href="/web-llvm/docs/api/classes/llvm/formatv-object-base/#aaaf577b5205c929de4042770a32a9517">llvm::formatv_object_base::str</a>, <a href="/web-llvm/docs/api/classes/llvm/unittest/tempfile/#a2277a37b366e2d68164f1ab32bb26dca">llvm::unittest::TempFile::TempFile</a>, <a href="/web-llvm/docs/api/classes/llvm/peelingmoduloscheduleexpander/#ae67a99405a40814d2261e31f11fe7a38">llvm::PeelingModuloScheduleExpander::validateAgainstModuloScheduleExpander</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aba197972422fd98e9318e22f0419e0a8">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyDFSNumbers</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4714e88fbf38f2aaf7fd427dfb17a3a0">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::VerifyLevels</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeeca9e1d5c151829946fa95f9b9b30c7">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyParentProperty</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a4bed97020476a2d93eb433776597d3de">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyReachability</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#aeff699bd020f8620eb57bc0ffd9ce847">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifyRoots</a>, <a href="/web-llvm/docs/api/structs/llvm/domtreebuilder/semincainfo/#a647a59b37db18cd302d604f723ba2ec4">llvm::DomTreeBuilder::SemiNCAInfo&lt; DomTreeT &gt;::verifySiblingProperty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae80a7e9590f1bec7c0ca3b271e88a735">llvm::writeArchiveToStream</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a80a1017cd2662da510365c7ee41a782a">llvm::writeToOutput</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/lto-cpp/#a2b96fb8bf782a1b498a82682ab8e74c9">writeToResolutionFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmemitter-cpp-/wasmwriter/#acaacefba415b1f85febb359665476b2b">anonymous{WasmEmitter.cpp}::WasmWriter::writeWasm</a>, <a href="/web-llvm/docs/api/classes/llvm/circular-raw-ostream/#a0d4db71785e433a2a0aa7a37fbcacf5f">llvm::circular_raw_ostream::~circular_raw_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a0eb361f836554627ef51810e0d3646c6">llvm::formatted_raw_ostream::~formatted_raw_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-fd-ostream/#a77063e0754fec7f06f3cdfa9e9bb5c1b">llvm::raw_fd_ostream::~raw_fd_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-null-ostream/#ac80527780279cb74bd7e155c405014f2">llvm::raw_null_ostream::~raw_null_ostream</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-os-ostream/#a992b8b8c66644c69b6bd51011a255bb2">llvm::raw_os_ostream::~raw_os_ostream</a>.</p>

</div>
</div>

### get\_kind() {#af3aec1d6c89f3eed88579d13ade51ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OStreamKind llvm::raw_ostream::get_kind ()</td>
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



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-fd-stream/#ac10c45dc61a1a5df36766b16d1f8e9b9">llvm::raw_fd_stream::classof</a>.</p>

</div>
</div>

### GetBufferSize() {#a2d79232a41a2f24d43acb936c8522443}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::raw_ostream::GetBufferSize ()</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="#a6799a9c00e1099623cec7e887f93eb57">preferred_buffer_size</a>.</p>

</div>
</div>

### GetNumBytesInBuffer() {#ad6cd89674692383208613b1e4ee560fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::raw_ostream::GetNumBytesInBuffer ()</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a65290bab4b83149e403bf48709658bd1">llvm::formatted_raw_ostream::getColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a88de341253439019e912f01fcd55c45b">llvm::formatted_raw_ostream::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a1fc7f913807a21ba5a42df7cc2d2e748">llvm::formatted_raw_ostream::PadToColumn</a> and <a href="#a0f90ad570f71349466844ee9f2d06cd1">tell</a>.</p>

</div>
</div>

### has\_colors() {#ae5c85e2158de685ed0c287a13c07ea49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::raw_ostream::has_colors ()</td>
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

<p>This function determines if this stream is displayed and supports colors.</p>


<p>The result is unaffected by calls to enable_color().</p>


<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="#a8f6a957a67e05e7355ab616619ee2608">is_displayed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/support/withcolor-cpp/#a217ca6e38806a2d0ea3712d69c0b06f6">DefaultAutoDetectFunction</a>.</p>

</div>
</div>

### indent() {#a8fdf5cdf041c8aded7e3308c1c3efacc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::indent (unsigned NumSpaces)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>indent - Insert 'NumSpaces' spaces.</p>

<p>Declaration at line 322 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp/#a63cbeb84490a2634b82648f8028202eb">write_padding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a0182cdf55f9bfbdd904e3f5e6802316a">llvm::IndexedReference::computeRefCost</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/cfiprogram/#a34dd8791e1ec288901de49e463950e57">llvm::dwarf::CFIProgram::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf/unwindrow/#a059c7ec610310aaef931a57658b9ee98">llvm::dwarf::UnwindRow::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdie/#aff52b4e2a5b1e91ab933fbd3ad52bba0">llvm::DWARFDie::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#aba0602c835ed2f449b723d5bf57d2eda">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a000318afaccf51b9e411d4890c4a1231">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a60b4742db7fd8558ba9138277c44bf22">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a33125921f2e76880e7ad9ab30c9dfca2">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/lexicalscope/#aa6c3d87456bbee468f6fd51bf8163dfe">llvm::LexicalScope::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/ipdbsourcefile/#aa3dd3b2aab501748e355e42bc8dd7224">llvm::pdb::IPDBSourceFile::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/seedbundle/#ad4df5511d40840b3d310d92bfbe6806d">llvm::sandboxir::SeedBundle::dump</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#a0acd4c91ee5645013bd3ac2e45e90dba">dumpAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a119c7591f5a3c513ebda9f69414f786c">llvm::sandboxir::Value::dumpCommonFooter</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarflocationtable/#aec9a11e9a2e87414bb67f6aaa342a570">llvm::DWARFLocationTable::dumpLocationList</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#ad9526a1ce54457f4cef4a593ad1e99ea">DumpNodes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#a8b40b63522fe1b491ba458feec392ea6">DumpNodesr</a>, <a href="/web-llvm/docs/api/classes/anonymous-callgraphsccpass-cpp-/cgpassmanager/#a4efbb82e436e90c66cc02d1630c0c528">anonymous{CallGraphSCCPass.cpp}::CGPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/anonymous-legacypassmanager-cpp-/mppassmanager/#a7c9d902501ce3b0da29040e896cc4a9e">anonymous{LegacyPassManager.cpp}::MPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/fppassmanager/#aad38713efe44fd73c9bc1da06c0a6ca2">llvm::FPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/lppassmanager/#a65a4ed6b290a5d717266585050528047">llvm::LPPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/classes/llvm/rgpassmanager/#a3b0d682de606b00fcd4c6de1748496af">llvm::RGPassManager::dumpPassStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdie-cpp/#ade69f55e99e7ef15fbbb7468ac74b557">dumpRanges</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloc/#a11cbb190f63755889353aaef746ba05a">llvm::DWARFDebugLoc::dumpRawEntry</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfdebugloclists/#aaa38af193e8749bb5d9b945b405e933e">llvm::DWARFDebugLoclists::dumpRawEntry</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a28e0e7c7f7920e3608fea13ec3e4394e">llvm::pdb::dumpSymbolField</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#aebe60f61f4fe8956834c561bfb8a75e8">llvm::pdb::dumpSymbolIdField</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/row/#ac3f903d6b8cf4b48c2f1c72dabfbee38">llvm::DWARFDebugLine::Row::dumpTableHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobe/#a4fbe96db8448f1711fd51c4f4601c063">llvm::MCPseudoProbe::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/mcpseudoprobeinlinetree/#a803da0fccbb98b7ceaf9240f55fa69b6">llvm::MCPseudoProbeInlineTree::emit</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a5a05fbafdbe696de6c83937542acc38e">emitBasicBlockLoopComments</a>, <a href="/web-llvm/docs/api/classes/llvm/support/detail/padadapter/#a89033b9b3dde0ee3bd5c5343aee0d639">llvm::support::detail::PadAdapter&lt; T &gt;::format</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a68b97d806d8c2e58e42e7038bc6d45b8">llvm::IndexedReference::hasSpacialReuse</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#a62ed34db5672583fcefb9c152e2dad01">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::isClangModuleRef</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#a5f11ba76fd5bf10519e057da7c9a84b2">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a01f9d864a1818825ffb00bbfa4b846c6">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a198dd514b6fcada5bd79b308d0124fbe">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6a03e75881c56744e1c23234b716ad01">llvm::operator&lt;&lt;</a>, <a href="#aebda89a6230d3b4ac098b18b57c16f4b">operator&lt;&lt;</a>, <a href="#a980a91d30111be065234c1dac2f067e1">operator&lt;&lt;</a>, <a href="#ad72c5336e2ff27aefee791348d4e1680">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a1fc7f913807a21ba5a42df7cc2d2e748">llvm::formatted_raw_ostream::PadToColumn</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfdebugline/linetable/#a49eb2522e1fc6988c75f9936c3061bb6">llvm::DWARFDebugLine::LineTable::parse</a>, <a href="/web-llvm/docs/api/classes/llvm/loopaccessinfo/#a8acfde41662b7ec9d592d905da1dbb22">llvm::LoopAccessInfo::print</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a5b3fe20235340fb3bbf3ff86ec172d73">llvm::LoopBase&lt; BlockT, LoopT &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock/#a5a4302f4590a281bb84e08b30c80591c">llvm::MachineBasicBlock::print</a>, <a href="/web-llvm/docs/api/structs/llvm/memorydepchecker/dependence/#a8169d805ee357d7dc129683171b02a7f">llvm::MemoryDepChecker::Dependence::print</a>, <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a84e9b8947377b33bf66815f86269e6ce">llvm::PredicatedScalarEvolution::print</a>, <a href="/web-llvm/docs/api/classes/llvm/regionbase/#aed7eee2aa41a7b67f3cfc9a6bc1f991a">llvm::RegionBase&lt; Tr &gt;::print</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a616cdd740bc8d7ccbed42ce872ca86c4">llvm::RuntimePointerChecking::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sampleprof/functionsamples/#adca18b92b535ad86d151efc86442027d">llvm::sampleprof::FunctionSamples::print</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/memdgnode/#a98726d4d9fcff82e7518d14b2e6b111a">llvm::sandboxir::MemDGNode::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcomparepredicate/#ada4c07a2a91d420224b61eab10de7889">llvm::SCEVComparePredicate::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a42276b9ddf5e782e18683908a626466a">llvm::SCEVWrapPredicate::print</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/vloperands/#ae8d07324e150cf3266d4013f6d3f0b06">llvm::slpvectorizer::BoUpSLP::VLOperands::print</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyexception/#a0c81702b40d9a9c4959074ba7387ce6e">llvm::WebAssemblyException::print</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#a3e60690517dfc1dd58b48cbbc1e0657f">llvm::RuntimePointerChecking::printChecks</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a8e071196c041b94cb39ea3ff6a5aa654">PrintChildLoopComment</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#acae182b4c4d76e0489cde49f97f4be7f">llvm::cl::Option::printEnumValHelpStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/riscvisainfo-cpp/#a9eeb6ab7ee4a2fd19e22f671d7ce32b2">PrintExtension</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/generic-parser-base/#a7c44bc839272e942aa1a7c622eb9affb">llvm::cl::generic_parser_base::printGenericOptionDiff</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/opttable-cpp/#af57814310114de54a058984c486a21a2">PrintHelpOptionList</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/option/#adbafb62d9a5896bf0485dea594d111bb">llvm::cl::Option::printHelpStr</a>, <a href="/web-llvm/docs/api/classes/llvm/cl/basic-parser-impl/#ae26435a44ff77679505607b1c62d056a">llvm::cl::basic_parser_impl::printOptionName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a9e656ca6880429c47f777ef0d06ac030">PrintParentLoopComment</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#aa0dea2adf7c230e9226a20ecc348464e">llvm::TargetRegistry::printRegisteredTargetsForVersion</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/selectiondagdumper-cpp/#adfc37ceb937f230dbfdbda000e383090">printrWithDepthHelper</a>, <a href="/web-llvm/docs/api/classes/anonymous-commandline-cpp-/helpprinter/#a7f3edd58dd488ae30a1cfa617a24168e">anonymous{CommandLine.cpp}::HelpPrinter::printSubCommands</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvisainfo/#ac192fe2b2eb30e2900fb5a9277432f72">llvm::RISCVISAInfo::printSupportedExtensions</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a>.</p>

</div>
</div>

### is\_displayed() {#a8f6a957a67e05e7355ab616619ee2608}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::raw_ostream::is_displayed ()</td>
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

<p>This function determines if this stream is connected to a "tty" or "console" window.</p>


<p>That is, the output would be displayed to the user rather than being put on a pipe or stored in a file.</p>


<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab7c147006432b03872f87ddd298d80e3">llvm::CheckBitcodeOutputToConsole</a> and <a href="#ae5c85e2158de685ed0c287a13c07ea49">has_colors</a>.</p>

</div>
</div>

### reserveExtraSpace() {#ad65ed6b6a8c96b6c1dc98ba50bc1547a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::raw_ostream::reserveExtraSpace (uint64_t ExtraSize)</td>
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

<p>If possible, pre-allocate <span class="doxyComputerOutput">ExtraSize</span> bytes for stream data.</p>


<p>i.e. it extends internal buffers to keep additional ExtraSize bytes. So that the stream could keep at least <a href="#a0f90ad570f71349466844ee9f2d06cd1">tell()</a> + ExtraSize bytes without re-allocations. <a href="#ad65ed6b6a8c96b6c1dc98ba50bc1547a">reserveExtraSpace()</a> does not change the size/data of the stream.</p>


<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### resetColor() {#a4219e33c3cd0cc8383f615fc40254d21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::resetColor ()</td>
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

<p>Resets the colors to terminal defaults.</p>


<p>Call this when you are done outputting colored text, or before program exit.</p>


<p>Declaration at line 339 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 533 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/process/#add81bb27661c8bce42dee6b4b5828e83">llvm::sys::Process::ResetColor</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>


<p>Referenced by <a href="#ab6683621f818ca79cfe58e9bc0136d12">operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a255a1144d50063acc74b8b5143697694">llvm::formatted_raw_ostream::resetColor</a>.</p>

</div>
</div>

### reverseColor() {#a6095e2a0ebe961a05e2b3a7b6acbe769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::reverseColor ()</td>
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

<p>Reverses the foreground and background colors.</p>

<p>Declaration at line 342 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/sys/process/#aad9fc0056cabdeff2e16f13ec879688f">llvm::sys::Process::OutputReverse</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#af55e6fb1fbaadb04b201cba1f302d7b9">llvm::formatted_raw_ostream::reverseColor</a>.</p>

</div>
</div>

### SetBuffered() {#af6e095a40885b6ed93dcdeb112ceeab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_ostream::SetBuffered ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the stream to be buffered, with an automatically determined buffer size.</p>

<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="#a6799a9c00e1099623cec7e887f93eb57">preferred_buffer_size</a>, <a href="#a1a59a3dce2d7cde8c5e6ef0e3a30b375">SetBufferSize</a>, <a href="#a75860636a752bc2592f6e4185e63efdc">SetUnbuffered</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="#a581a276005e9f911c53aa145e4a01e53">write</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### SetBufferSize() {#a1a59a3dce2d7cde8c5e6ef0e3a30b375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_ostream::SetBufferSize (size_t Size)</td>
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

<p>Set the stream to be buffered, using the specified buffer size.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>References <a href="#a520bdf57dfe3e73abb53d482893f0a27">flush</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-goffemitter-cpp-/goffostream/#a9c5065f0b1869918c137eeb8b30b2ce6">anonymous{GOFFEmitter.cpp}::GOFFOstream::GOFFOstream</a> and <a href="#af6e095a40885b6ed93dcdeb112ceeab2">SetBuffered</a>.</p>

</div>
</div>

### SetUnbuffered() {#a75860636a752bc2592f6e4185e63efdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_ostream::SetUnbuffered ()</td>
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

<p>Set the stream to be unbuffered.</p>


<p>When unbuffered, the stream will flush after every write. This routine will also flush the buffer immediately when the stream is being set to unbuffered.</p>


<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="#a520bdf57dfe3e73abb53d482893f0a27">flush</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#ac1532c60ac358982e83c080469611061">llvm::raw_string_ostream::raw_string_ostream</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#ac5de2c3f4305e6a5f5a6076e5f60c7d7">llvm::raw_svector_ostream::raw_svector_ostream</a> and <a href="#af6e095a40885b6ed93dcdeb112ceeab2">SetBuffered</a>.</p>

</div>
</div>

### tell() {#a0f90ad570f71349466844ee9f2d06cd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::raw_ostream::tell ()</td>
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

<p>tell - Return the current offset with the file.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="#ad6cd89674692383208613b1e4ee560fe">GetNumBytesInBuffer</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarf-linker/parallel/dwarflinkerimpl/linkcontext/#ac4560fb1d6b91d4ba6edb7e907573c1e">llvm::dwarf_linker::parallel::DWARFLinkerImpl::LinkContext::cloneAndEmitDebugFrame</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a98ad0137a31b38aa7b278f7cc52c4f3e">computeMemberData</a>, <a href="/web-llvm/docs/api/classes/llvm/ondiskchainedhashtablegenerator/#a9c8d5a30bca2110b979dbe64063ee93d">llvm::OnDiskChainedHashTableGenerator&lt; Info &gt;::Emit</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/debuglinesectionemitter/#a81feed7a90b5abc9e58b574e7da2a360">llvm::dwarf_linker::parallel::DebugLineSectionEmitter::emit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a258100c512356fe24a12a14fc7ad9d78">llvm::DWARFYAML::emitDebugRanges</a>, <a href="/web-llvm/docs/api/groups/methods/#ga579ac60d76c4a3b6ca084238591d4437">llvm::dwarf_linker::parallel::DwarfUnit::emitDebugStringOffsetSection</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarf-linker/parallel/dwarfunit/#aa5415f7dcc45583b4bb82acb6f64c73a">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAcceleratorEntry</a>, <a href="/web-llvm/docs/api/groups/methods/#ga80d3884d82a541f6f1b11931db9fc5fb">llvm::dwarf_linker::parallel::DwarfUnit::emitPubAccelerators</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a1f4394e4fc8872fa8f2a5baca5b3cc4b">getSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/tarwriter-cpp/#a498738d65e5a3c57d210f97b7a475d54">pad</a>, <a href="/web-llvm/docs/api/classes/llvm/cgdataostream/#a1d951f57be86b30e864740019b41f0f2">llvm::CGDataOStream::patch</a>, <a href="/web-llvm/docs/api/classes/llvm/profostream/#a52299b07451a31e9fc5a62e305d5fe21">llvm::ProfOStream::patch</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackend-cpp/#a5f10e2bc9876065234ead6b2a02f8af5">printLine</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#af7cc3cea867e3070fd25ab0d14abb814">printWithSpacePadding</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-pwrite-stream/#a9a004bff5f9c00b2ede3a52c93c665c2">llvm::raw_pwrite_stream::pwrite</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-string-ostream/#ab6404e90b84bda345a98539075706232">llvm::raw_string_ostream::reserveExtraSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/raw-svector-ostream/#a94bec39d1b2d114ce2a7f131314c2254">llvm::raw_svector_ostream::reserveExtraSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/testingformatwriter/#af47bcd2c269bb9099d476b455b4dc5ed">llvm::coverage::TestingFormatWriter::write</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a9d1c89a919275d8aa033388862d7771e">writeDWARFExpression</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a6ae6757140194100cc316df00b97773f">writeFragment</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a58ac83b81cafa1a8062aaf24af05346d">writeListEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-machoemitter-cpp-/machowriter/#a613e65e4ab9eafc574abffdbe4c1063a">anonymous{MachOEmitter.cpp}::MachOWriter::writeMachO</a>, <a href="/web-llvm/docs/api/classes/anonymous-machoemitter-cpp-/universalwriter/#a3e3da0c5ca6b6afd845ca7417bb1034e">anonymous{MachOEmitter.cpp}::UniversalWriter::writeMachO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcassembler/#a2a301492f7142fbc3744cc1c5a86f5ec">llvm::MCAssembler::writeSectionData</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a8980c8408e5daa10c78c4a577ebaa527">writeSymbolTableHeader</a> and <a href="/web-llvm/docs/api/classes/anonymous-minidumpemitter-cpp-/bloballocator/#a6fa75f337ed8bdb565ad78234f20c1d9">anonymous{MinidumpEmitter.cpp}::BlobAllocator::writeTo</a>.</p>

</div>
</div>

### write() {#a6e0cbc5c8568d8446c284c8538b2c9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::write (unsigned char C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="#af6e095a40885b6ed93dcdeb112ceeab2">SetBuffered</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>


<p>Referenced by <a href="#a28fa4a2054d6d628fa4eea21c5262212">changeColor</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#aeade4a99cac29eaa9bf39f2729f8d75f">llvm::InstrProfRecordWriterTrait::EmitData</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a81600054c53c8bfe10547514c330a547">llvm::DWARFYAML::emitDebugAbbrev</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#a0aca0c593a4951ced7f067663729871a">llvm::DWARFYAML::emitDebugInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ae91e1699c9c07514f5381a7d882f2ef0">llvm::DWARFYAML::emitDebugLine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#ad1f7f7a8ed653ac5d4c9cf22992767ea">llvm::DWARFYAML::emitDebugNames</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dwarfemitter-cpp-/#a95b9cd710db1ece98dc23d86c22bdb5b">anonymous{DWARFEmitter.cpp}::emitDebugNamesHeader</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarfyaml/#aac6c1a9a865304388a58f18a55a4a8f7">llvm::DWARFYAML::emitDebugStr</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a232c76d4c06ded6c02597dfae877aca3">emitExternalFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a23875c46eead910ec10551d31420a75d">emitFileEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinterinlineasm-cpp/#a362579106cd14231f459ca8c00af60ca">EmitInlineAsmStr</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofrecordwritertrait/#ad6f07481b72e3568320b1a68fe1d320d">llvm::InstrProfRecordWriterTrait::EmitKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a6c011cb80a79745aa876f8e3efb35975">emitMagic</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmprinter-cpp-/ppcaixasmprinter/#a3275b7a3457510661d5af13a82bb48ca">anonymous{PPCAsmPrinter.cpp}::PPCAIXAsmPrinter::emitModuleCommandLines</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#aa371f7d58f8c4b09db71516e37bf45f4">emitPubSection</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#a381769de0e2dcfdc39d00d50ec961c66">emitStrTab</a>, <a href="/web-llvm/docs/api/files/lib/lib/remarks/yamlremarkserializer-cpp/#accf8f848dfab29077924750f922e320d">emitVersion</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a3bcc321a63a6cafde4809bbbe835e2ed">anonymous{MachOEmitter.cpp}::Fill</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/bitstreamremarkserializerhelper/#ae2ee2b1ce9ba0bb78d12f335d4c98164">llvm::remarks::BitstreamRemarkSerializerHelper::flushToStream</a>, <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data/#a63440c1553c8b023f90126cc142e8724">llvm::DWARFYAML::Data::getAbbrevTableContentByIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dumpobjects/#aa0dc48bd5c7938d84780ec3e63378a13">llvm::orc::DumpObjects::operator()</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-goffemitter-cpp-/#aef416bbc7f2a09ab58b27d0468ad514a">anonymous{GOFFEmitter.cpp}::operator&lt;&lt;</a>, <a href="#a51b9992ae460e4e0fb0fa7ce054494e8">operator&lt;&lt;</a>, <a href="#a0a8d18dc26984414573e1d152d89a5e2">operator&lt;&lt;</a>, <a href="#ac88eab7965bf3a6d7c553f17e68d1513">operator&lt;&lt;</a>, <a href="#ae00dbdc15d9b90a48e1326c50a2c0bc6">operator&lt;&lt;</a>, <a href="#a194a494c85e146be05d9e6fac49a5945">operator&lt;&lt;</a>, <a href="#a9d7ad838c3518917424debc6be5ae9aa">operator&lt;&lt;</a>, <a href="#acaffa29e8a30c948243c84abf6b92a54">operator&lt;&lt;</a>, <a href="#a075cb7ac15c51197e4db4100b32a9fb2">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a9f1e7fc31749b7af6e259adf5d1c95ec">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a72da78454e254c8fe7398f8ceba5ed88">operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofilewriter/#a9e14ee9078852ac00c52462c0110b2f6">llvm::PGOCtxProfileWriter::PGOCtxProfileWriter</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aea934139e960daaca81f19ee42fefb9a">printBigArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a52904074f52a694e289a93b1634553c3">printBSDMemberHeader</a>, <a href="#a4219e33c3cd0cc8383f615fc40254d21">resetColor</a>, <a href="#a6095e2a0ebe961a05e2b3a7b6acbe769">reverseColor</a>, <a href="/web-llvm/docs/api/structs/llvm/remarks/stringtable/#a78e58ea3fcbfd1e8b4a5921c850507a0">llvm::remarks::StringTable::serialize</a>, <a href="/web-llvm/docs/api/classes/llvm/coverage/testingformatwriter/#af47bcd2c269bb9099d476b455b4dc5ed">llvm::coverage::TestingFormatWriter::write</a>, <a href="/web-llvm/docs/api/structs/llvm/mcdxbc/psvruntimeinfo/#a8ce05943db5cfcb56bbff62909a08e9c">llvm::mcdxbc::PSVRuntimeInfo::write</a>, <a href="/web-llvm/docs/api/classes/llvm/mcdxbc/signature/#a608616d2779ddc0d1ca2669b17119ba2">llvm::mcdxbc::Signature::write</a>, <a href="#a581a276005e9f911c53aa145e4a01e53">write</a>, <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a9dbd69fb838179adf11cb50b3d029cda">llvm::support::endian::write</a>, <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a0d40b2f1e459508b598037aca1a32cfc">llvm::support::endian::write_array</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aedb7c876c118bfb3b40eb756db6f9">llvm::write_hex</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp/#a63cbeb84490a2634b82648f8028202eb">write_padding</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8462d4d5c5381616faaacedd724215f4">write_unsigned_impl</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/elfemitter-cpp/#a241b7950718c3fe88ea2248850b7b928">writeArrayData</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref/#afc171c69b8c4ca66beae66513b4b1ab4">llvm::yaml::BinaryRef::writeAsBinary</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/binaryref/#aede9f099940022e899f2594cbc744916">llvm::yaml::BinaryRef::writeAsHex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#abe6559672807a3455fb24c680ac42dc6">writeDIE</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a27a0ea7c31356a5938a3fe32e8eb3103">writeDWARFLists</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a0096360a382602b21e0e980fb8069d52">llvm::dxil::WriteDXILToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a9ffd2185084f74a9992ea31cc78c4ddb">writeECSymbols</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a8e1598cefbf424412afe2ea557d7a27a">writeExtendedOpcode</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a5d4982689181e30f9114c6b35ec7facc">anonymous{MachOEmitter.cpp}::writeFatArch&lt; MachO::fat_arch &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a04e7b80e5a81e549928ca2e08054efa8">anonymous{MachOEmitter.cpp}::writeFatArch&lt; MachO::fat_arch_64 &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/mc/mcassembler-cpp/#a6ae6757140194100cc316df00b97773f">writeFragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a7d09dee266df5fb62a8791100b24c5a6">writeInteger</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a563a2cfcb7521ea43f914110e6336fc4">writeListEntry</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#ab0452cfab8d631ffe612b7db3ca753f3">anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::build_version_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a4526bc01726a48ab04a549eb59f98d82">anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::segment_command &gt;</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a218333fa07659a7328c0122fa819ed74">anonymous{MachOEmitter.cpp}::writeLoadCommandData&lt; MachO::segment_command_64 &gt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a749770911c6d0f9c6b687d28a5ea9d7d">writeLoadConfig</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a46fc3f6bb1d9703770ef88e4b3d5d90b">anonymous{MachOEmitter.cpp}::writeNListEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#a888a52044bc3005ea4bddd5f280a9dac">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-lanaiasmbackend-cpp-/lanaiasmbackend/#a15d84d8230e102bb29eeea2c4b3433ef">anonymous{LanaiAsmBackend.cpp}::LanaiAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-msp430asmbackend-cpp-/msp430asmbackend/#a40111db0a5919e2df31fd0f8cb333cc1">anonymous{MSP430AsmBackend.cpp}::MSP430AsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#ac8f8a80943df09baa1ccdb938e453639">anonymous{X86AsmBackend.cpp}::X86AsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/armasmbackend/#acfcc9bf39d2207d4e4e96c88903728fc">llvm::ARMAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#aacb87d7c3bf496454f2d5015c35fc92b">llvm::LoongArchAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a7e4421566f19358913fa09d91a089989">llvm::RISCVAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/xtensamcasmbackend/#a93cd076ae4068b7dc9cd7473bf4293dd">llvm::XtensaMCAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#a3209e484dbc45751b9a056593f408e10">anonymous{MachOEmitter.cpp}::writePayloadString</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a5b06dd328e277cc107d21a8ee4266e04">writeSymbolMap</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#a59c3a1cc637af30e381ff9222aa75c5f">writeSymbolTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a33564097625c6a9b619c60a71343c058">llvm::writeThinLinkBitcodeToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmemitter-cpp/#a199d700abdda200a3c69b29aba3be984">writeUint32</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmemitter-cpp/#ae902e3aa4f0a43e5771dd72e5c1d7b9e">writeUint64</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/wasmemitter-cpp/#ad6696f7a932d23d2f898e7e01dfafc00">writeUint8</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>, <a href="/web-llvm/docs/api/classes/anonymous-wasmemitter-cpp-/wasmwriter/#acaacefba415b1f85febb359665476b2b">anonymous{WasmEmitter.cpp}::WasmWriter::writeWasm</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/nativeformatting-cpp/#a8dd06742877ada9717169e974f5f5de2">writeWithCommas</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#ace523ea68fd49787987759de81452913">llvm::yaml::yaml2archive</a>, <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a960217c66ca1fa6c96ec78eba269b580">llvm::yaml::yaml2offload</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-machoemitter-cpp-/#ad384887e7ea0a8cb24eb9843a7eeaea3">anonymous{MachOEmitter.cpp}::ZeroFillBytes</a> and <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/dwarfemitter-cpp/#a1cb7e677ef1f781489e3e391caf5af2f">ZeroFillBytes</a>.</p>

</div>
</div>

### write() {#a581a276005e9f911c53aa145e4a01e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::write (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 304 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 245 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#a104cae72182bec0ab951e3faea6ce509">LLVM_UNLIKELY</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>, <a href="#af6e095a40885b6ed93dcdeb112ceeab2">SetBuffered</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="#a6e0cbc5c8568d8446c284c8538b2c9f1">write</a>.</p>

</div>
</div>

### write\_escaped() {#a5ba2ece4b959bae02752c34b784ba087}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::write_escaped (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, bool UseHexEscapes=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Output <span class="doxyComputerOutput">Str</span>, turning '\', '\t', '
<br/>
', '"', and anything that doesn't satisfy llvm::isPrint into an escape sequence.</p>

<p>Declaration at line 301 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Reference <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a0906254a905f4d1c0a68dd54c3eb65e8">llvm::object::ArchiveMemberHeader::ArchiveMemberHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/asmtoken/#a9e8e74c88aca8715d0c131ce35b75387">llvm::AsmToken::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a872194924baf250829ba1b42a0b14105">llvm::DWARFContext::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfformvalue/#abccb4aa356ed1bf8bae692df185a885a">llvm::DWARFFormValue::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/stringtooffsettable/#a1878d931b7c5cb9a938690f5a73d75a2">llvm::StringToOffsetTable::EmitStringTableDef</a>, <a href="/web-llvm/docs/api/classes/llvm/object/archivememberheader/#a940c0b94e9bb9dfdb69961d456b47b60">llvm::object::ArchiveMemberHeader::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/prettystacktraceprogram/#a837a5955004fdc8af71f6d30fbdfa862">llvm::PrettyStackTraceProgram::print</a>, <a href="/web-llvm/docs/api/classes/llvm/pattern/#a3a4e8a88439506522a2a0f3850802d3f">llvm::Pattern::printSubstitutions</a>, <a href="/web-llvm/docs/api/classes/anonymous-machinecfgprinter-cpp-/machinecfgprinter/#acaeae56f20830134ab1bcad4eda8ec16">anonymous{MachineCFGPrinter.cpp}::MachineCFGPrinter::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcexternalsymbolizer/#a932da00ce99b1018afdbc02579239ff1">llvm::MCExternalSymbolizer::tryAddingPcLoadReferenceComment</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64externalsymbolizer/#aadc518cf2b179163c8eca58f17e333b2">llvm::AArch64ExternalSymbolizer::tryAddingSymbolicOperand</a>.</p>

</div>
</div>

### write\_hex() {#a37b5dd8a8b82f2818e0f4ea9699d8ae5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::write_hex (unsigned long long N)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Output <span class="doxyComputerOutput">N</span> in hexadecimal, without any prefix or padding.</p>

<p>Declaration at line 290 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ab1aedb7c876c118bfb3b40eb756db6f9">llvm::write_hex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-hexagonasmbackend-cpp-/hexagonasmbackend/#acb84e0118cb55bac7f2f1b46ccc6ff3d">anonymous{HexagonAsmBackend.cpp}::HexagonAsmBackend::applyFixup</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfdebugframe-cpp/#a0e25fc51f7806df57464873f1323c074">dumpDataAux</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arc/lib/target/arc/mctargetdesc/arcinstprinter-cpp/#a0092f28dd2ee076c70d4c225678dc6ce">printExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/lib/target/mips/mctargetdesc/mipstargetstreamer-cpp/#a55848527bdd075e070314c22f1250a29">printHex32</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonshuffler/#a572425344ad3846264384af43858a5e1">llvm::HexagonShuffler::shuffle</a> and <a href="/web-llvm/docs/api/classes/llvm/instrprofwriter/#a764569b7bb113502ca90fca3c07fa816">llvm::InstrProfWriter::writeRecordInText</a>.</p>

</div>
</div>

### write\_uuid() {#a4e6042cae3a8ab74080998736eabd3fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::write_uuid (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aad2a4949bc82f743fb17bd9131e7041b">uuid_t</a> UUID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 158 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a> and <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/dwarf/dwarfcontext-cpp/#a2aab28bc62e4c45e2fee753cdeb035dc">dumpUUID</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/scalartraits-a4f0c68a7a5b628e681fe71e26204a68/#a4e8da63936a6b179c9ae510cc242773e">llvm::yaml::ScalarTraits&lt; uuid_t &gt;::output</a>.</p>

</div>
</div>

### write\_zeros() {#a06288f4d38e1d74fc7a1d10056d88373}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream &amp; raw_ostream::write_zeros (unsigned NumZeros)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>write_zeros - Insert 'NumZeros' nulls.</p>

<p>Declaration at line 325 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>References <a href="#a0f4b64a0f7aec0a02e7f2ff5a6552723">raw_ostream</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp/#a63cbeb84490a2634b82648f8028202eb">write_padding</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/dwarfyaml/data/#a63440c1553c8b023f90126cc142e8724">llvm::DWARFYAML::Data::getAbbrevTableContentByIndex</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-goffemitter-cpp-/#a9a5ae41342b1ed85eee45fafb4a93557">anonymous{GOFFEmitter.cpp}::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#a09963de4b3b90f89cf9f9b6f154af6bd">llvm::LoongArchAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvasmbackend/#a056a7266fa88806c3f88ab217fac6e4e">llvm::RISCVAsmBackend::relaxDwarfLineAddr</a>, <a href="/web-llvm/docs/api/classes/llvm/object/offloadbinary/#a56f47c8dc5df749b09ecdabc977e01c7">llvm::object::OffloadBinary::write</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#ab42bb96f4eedf10f2f2437b807a77f8b">writeCOFF</a>, <a href="/web-llvm/docs/api/files/lib/lib/objectyaml/coffemitter-cpp/#a749770911c6d0f9c6b687d28a5ea9d7d">writeLoadConfig</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64asmbackend-cpp-/aarch64asmbackend/#a888a52044bc3005ea4bddd5f280a9dac">anonymous{AArch64AsmBackend.cpp}::AArch64AsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuasmbackend-cpp-/amdgpuasmbackend/#ae6be0530b11fb45dd1d82160fee76e76">anonymous{AMDGPUAsmBackend.cpp}::AMDGPUAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-ppcasmbackend-cpp-/ppcasmbackend/#a7fd7dd3a3c502259ea39a750c70edb94">anonymous{PPCAsmBackend.cpp}::PPCAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/anonymous-sparcasmbackend-cpp-/sparcasmbackend/#a6d313bf87ed584a309f9c5c0ec366fe8">anonymous{SparcAsmBackend.cpp}::SparcAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/avrasmbackend/#a8adb83bb8a3474a9261a804c2798ee94">llvm::AVRAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyasmbackend/#af8c0b495532ba9e071763edc19516f31">llvm::CSKYAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchasmbackend/#aacb87d7c3bf496454f2d5015c35fc92b">llvm::LoongArchAsmBackend::writeNopData</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsasmbackend/#a88b2f08af754834c45de4e5017a11a19">llvm::MipsAsmBackend::writeNopData</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/machouniversalwriter-cpp/#a9f26efe564d8f7f1afb5f3033156d58d">writeUniversalArchsToStream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### getBufferStart() {#a980ad6112624b521eb2d831b39b346eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::raw_ostream::getBufferStart ()</td>
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

<p>Return the beginning of the current stream buffer, or 0 if the stream is unbuffered.</p>

<p>Definition at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a65290bab4b83149e403bf48709658bd1">llvm::formatted_raw_ostream::getColumn</a>, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a88de341253439019e912f01fcd55c45b">llvm::formatted_raw_ostream::getLine</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/dumpobjects/#aa0dc48bd5c7938d84780ec3e63378a13">llvm::orc::DumpObjects::operator()</a> and <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream/#a1fc7f913807a21ba5a42df7cc2d2e748">llvm::formatted_raw_ostream::PadToColumn</a>.</p>

</div>
</div>

### preferred\_buffer\_size() {#a6799a9c00e1099623cec7e887f93eb57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t raw_ostream::preferred_buffer_size ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an efficient buffer size for the underlying output mechanism.</p>

<p>Declaration at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>


<p>Referenced by <a href="#a2d79232a41a2f24d43acb936c8522443">GetBufferSize</a> and <a href="#af6e095a40885b6ed93dcdeb112ceeab2">SetBuffered</a>.</p>

</div>
</div>

### SetBuffer() {#a61bcdba2623dbce59a5f460650255db2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::raw_ostream::SetBuffer (char * BufferStart, size_t Size)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> the provided buffer as the <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> buffer.</p>


<p>This is intended for use only by subclasses which can arrange for the output to go directly into the desired output buffer, instead of being copied on each flush.</p>


<p>Definition at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-goffobjectwriter-cpp-/goffostream/#a0b6e28c2930d28e768447c416643c38a">anonymous{GOFFObjectWriter.cpp}::GOFFOstream::GOFFOstream</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### anchor() {#add0759e19a1af03fb90ddfac33c74c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_ostream::anchor ()</td>
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



<p>Declaration at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 551 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### copy\_to\_buffer() {#ab7a586a50af93a4a0305e9be41adbdd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_ostream::copy_to_buffer (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Copy data into the buffer.</p>


<p>Size must not be greater than the number of unused bytes in the buffer.</p>


<p>Declaration at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 288 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### current\_pos() {#a7ba24fa2187fb1b7bcf1a7458db20d13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual uint64_t llvm::raw_ostream::current_pos ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the current position within the stream, not counting the bytes currently in the buffer.</p>

<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### flush\_nonempty() {#aa0eabc6d24e282c292b2fdc482007f2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_ostream::flush_nonempty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flush the current buffer, which is known to be non-empty.</p>


<p>This outputs the currently buffered data and resets the buffer to empty.</p>


<p>Declaration at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 218 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### prepare\_colors() {#a11bb5ca6e8b421e64a19a6282e616254}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool raw_ostream::prepare_colors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute whether colors should be used and do the necessary work such as flushing.</p>


<p>The result is affected by calls to enable_color().</p>


<p>Declaration at line 415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 504 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### SetBufferAndMode() {#ad0495921bc3d6e243c1b81bd0cd5fbcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void raw_ostream::SetBufferAndMode (char * BufferStart, size_t Size, BufferKind Mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Install the given buffer and mode.</p>

<p>Declaration at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>, definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a>.</p>

</div>
</div>

### write\_impl() {#aff81bd777453e69313941c475ec2a848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::raw_ostream::write_impl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Ptr, size_t Size)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The is the piece of the class that is implemented by subclasses.</p>


<p>This writes the <span class="doxyComputerOutput">Size</span> bytes starting at <span class="doxyComputerOutput">Ptr</span> to the underlying stream.</p>


<p>This function is guaranteed to only be called at a point at which it is safe for the subclass to install a new buffer via SetBuffer.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Ptr</td>
<td class="doxyParamItemDescription"><p>The start of the data to be written. For buffered streams this is guaranteed to be the start of the buffer.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Size</td>
<td class="doxyParamItemDescription"><p>The number of bytes to be written.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Invariant</dt>
<dd><p>{ Size &gt; 0 }</p></dd>
</dl>


<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BufferMode {#a884983dc651f6edc8ee6f6194b8d94dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::raw_ostream::BufferKind llvm::raw_ostream::BufferMode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### ColorEnabled {#aeb8c9ab6da25408ba291e4815bcd03b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::raw_ostream::ColorEnabled = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### Kind {#aa89b9937ca5327a89c670129e961b630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OStreamKind llvm::raw_ostream::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### OutBufCur {#a0fb90e40352be6091e0344c54b3e8918}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::raw_ostream::OutBufCur</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### OutBufEnd {#a090dd09f34514feed92a95eee1f278b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * llvm::raw_ostream::OutBufEnd</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### OutBufStart {#a0045edfef76e8e677ae2ca6edf1d3104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char* llvm::raw_ostream::OutBufStart</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The buffer is handled in such a way that the buffer is uninitialized, unbuffered, or out of space when OutBufCur &gt;= OutBufEnd.</p>


<p>Thus a single comparison suffices to determine if we need to take the slow path to write a single character.</p>


<p>The buffer is in one of three states:</p>


<ol class="doxyList" type="1">
<li>Unbuffered (BufferMode == Unbuffered)</li>
</ol>

<ol class="doxyList" type="1">
<li>Uninitialized (BufferMode != Unbuffered &amp;&amp; OutBufStart == 0).</li>
<li>Buffered (BufferMode != Unbuffered &amp;&amp; OutBufStart != 0 &amp;&amp; OutBufEnd - OutBufStart &gt;= 1).</li>
</ol>

<p>If buffered, then the <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> owns the buffer if (BufferMode == InternalBuffer); otherwise the buffer has been set via SetBuffer and is managed by the subclass.</p>


<p>If a subclass installs an external buffer using SetBuffer then it can wait for a</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>write_impl() call to handle the <a href="/web-llvm/docs/api/files/lib/lib/codegen/staticdatasplitter-cpp/#ad2fefd8832b4b1ea3dbb1f621063bbff">data</a> which has been put into this buffer.</p></dd>
</dl>


<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### BLACK {#ad7fa72c34a893a70df723e8c90410864}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::BLACK = Colors::BLACK</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0b7d62735f94b418859340f4949299bf">llvm::WithColor::WithColor</a>.</p>

</div>
</div>

### BLUE {#a63c9d9dc86ce5675ba81e57258408628}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::BLUE = Colors::BLUE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0b7d62735f94b418859340f4949299bf">llvm::WithColor::WithColor</a>.</p>

</div>
</div>

### BRIGHT\_BLACK {#ae1ed300c78ba04b636a61ecb147c92ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_BLACK = Colors::BRIGHT_BLACK</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### BRIGHT\_BLUE {#af35171b7d8e8bd280c9ca13cee2e342c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_BLUE = Colors::BRIGHT_BLUE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### BRIGHT\_CYAN {#ad02a884bafdecf4c92bd7bb2ebec2b33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_CYAN = Colors::BRIGHT_CYAN</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### BRIGHT\_GREEN {#ae9db6917b73438040622a62595123fbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_GREEN = Colors::BRIGHT_GREEN</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### BRIGHT\_MAGENTA {#aa87ef9bf0a5af081e8f10606cb5e8687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_MAGENTA = Colors::BRIGHT_MAGENTA</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### BRIGHT\_RED {#a1a335509d3624637f5c80198c97f3c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_RED = Colors::BRIGHT_RED</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### BRIGHT\_WHITE {#ae493f4fdc4c0739416102c6bd5b432a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_WHITE = Colors::BRIGHT_WHITE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### BRIGHT\_YELLOW {#ac7d521f5dc48e516c88ae329cf2ebb7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Colors llvm::raw_ostream::BRIGHT_YELLOW = Colors::BRIGHT_YELLOW</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### CYAN {#a1b89c1fc567cf8889baeccead5083434}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::CYAN = Colors::CYAN</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0b7d62735f94b418859340f4949299bf">llvm::WithColor::WithColor</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/withmarkup/#a7b81786db9cbd784cdcd4f76bd42faee">llvm::MCInstPrinter::WithMarkup::WithMarkup</a>.</p>

</div>
</div>

### GREEN {#ae56223ff7592f05301a6b496ae46299c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::GREEN = Colors::GREEN</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a>, <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0b7d62735f94b418859340f4949299bf">llvm::WithColor::WithColor</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/withmarkup/#a7b81786db9cbd784cdcd4f76bd42faee">llvm::MCInstPrinter::WithMarkup::WithMarkup</a>.</p>

</div>
</div>

### MAGENTA {#abab3a5904ddc74e76f0a8021d383866f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::MAGENTA = Colors::MAGENTA</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0b7d62735f94b418859340f4949299bf">llvm::WithColor::WithColor</a>.</p>

</div>
</div>

### RED {#ae7b7856e1bc7aea739f05e4d65d5276b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::RED = Colors::RED</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0b7d62735f94b418859340f4949299bf">llvm::WithColor::WithColor</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/withmarkup/#a7b81786db9cbd784cdcd4f76bd42faee">llvm::MCInstPrinter::WithMarkup::WithMarkup</a>.</p>

</div>
</div>

### RESET {#a9ba1327251e8c5c71480b9876c52f4e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::RESET = Colors::RESET</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### SAVEDCOLOR {#ad55e55b3692fe8ec3e8b724d3d5bade0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::SAVEDCOLOR = Colors::SAVEDCOLOR</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="#a28fa4a2054d6d628fa4eea21c5262212">changeColor</a>, <a href="/web-llvm/docs/api/classes/llvm/smdiagnostic/#a0653e9bbc6598528d50ec97cad565b74">llvm::SMDiagnostic::print</a> and <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a49d88ad31bfdaa61d47dd7720c083823">llvm::WithColor::WithColor</a>.</p>

</div>
</div>

### WHITE {#afdcd12a4a8e2d561e7dd31b4c05b2053}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::WHITE = Colors::WHITE</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>

</div>
</div>

### YELLOW {#a026561b02ba397a040ff1e681d2fb0ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">raw_ostream::Colors raw_ostream::YELLOW = Colors::YELLOW</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/withcolor/#a0b7d62735f94b418859340f4949299bf">llvm::WithColor::WithColor</a> and <a href="/web-llvm/docs/api/classes/llvm/mcinstprinter/withmarkup/#a7b81786db9cbd784cdcd4f76bd42faee">llvm::MCInstPrinter::WithMarkup::WithMarkup</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">raw_ostream.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/raw-ostream-cpp">raw_ostream.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
