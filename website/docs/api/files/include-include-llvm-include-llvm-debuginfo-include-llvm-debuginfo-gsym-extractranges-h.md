---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ExtractRanges.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/addressranges-h">llvm/ADT/AddressRanges.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/format-h">llvm/Support/Format.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/raw-ostream-h">llvm/Support/raw_ostream.h</a>"
#include &lt;stdint.h&gt;
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm">llvm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is an optimization pass for GlobalISel generic memory operations. <a href="/web-llvm/docs/api/namespaces/llvm/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/gsym">gsym</a></td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d57b52d7d017a1fbc51ade0d6b50df0">HEX8</a>(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 4)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f2782880e58ec7350a0c4c364c3f635">HEX16</a>(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 6)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9fd7a73c45fec3c647590738cef3fc9">HEX32</a>(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 10)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abedaa94d52e9958ad4a0d3790d0e4451">HEX64</a>(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 18)</td>
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

## Macro Definitions

### HEX16 {#a6f2782880e58ec7350a0c4c364c3f635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEX16(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 6)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 18 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h">ExtractRanges.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a40a7cf3120a64f2f2e563bc820b9d846">llvm::gsym::GsymReader::dump</a>.</p>

</div>
</div>

### HEX32 {#ad9fd7a73c45fec3c647590738cef3fc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEX32(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 10)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 19 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h">ExtractRanges.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a2c4724c06d85bc195e23612de85f6774">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a23b23c842771d071cfb8af8c15e38e37">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a3c4e9c1f62e2525a6bdc722d0d6607a8">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a9b9d8d22a94c1862520178099d37c76e">llvm::gsym::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a>.</p>

</div>
</div>

### HEX64 {#abedaa94d52e9958ad4a0d3790d0e4451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEX64(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 18)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h">ExtractRanges.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#af08e62850443dbd1f2003aac7845ab3b">convertFunctionLineTable</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a2c4724c06d85bc195e23612de85f6774">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymreader/#a33125921f2e76880e7ad9ab30c9dfca2">llvm::gsym::GsymReader::dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a15f42fd0953ecc13d8122847660c0e5b">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a59c17734793f3095d138e197be3a2b69">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a01f9d864a1818825ffb00bbfa4b846c6">llvm::gsym::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b117ff34b6d87ecd6b48c6f10c8e561">llvm::operator&lt;&lt;</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/dwarftransformer-cpp/#a254758a009a4c05dee5c67ee26e61529">parseInlineInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/gsym/dwarftransformer/#ac40e6efe1caf07771eb6713f41db076b">llvm::gsym::DwarfTransformer::verify</a>.</p>

</div>
</div>

### HEX8 {#a1d57b52d7d017a1fbc51ade0d6b50df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HEX8(v)&nbsp;&nbsp;&nbsp;<a href="/web-llvm/docs/api/namespaces/llvm/#a90c017a4d672e046b7e98f67edf082ec">llvm::format_hex</a>(v, 4)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 17 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/extractranges-h">ExtractRanges.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/gsym/#a15f42fd0953ecc13d8122847660c0e5b">llvm::gsym::operator&lt;&lt;</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
