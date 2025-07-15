---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm/include/llvm/support/convertutf-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ConvertUTF.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cstddef&gt;
#include &lt;string&gt;
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

</table>

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b240b95a93f71535c03f5e26d7dbe1">UNI_REPLACEMENT_CHAR</a>&nbsp;&nbsp;&nbsp;(UTF32)0x0000FFFD</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc71280d09832f0fb6c6b83fbf043140">UNI_MAX_BMP</a>&nbsp;&nbsp;&nbsp;(UTF32)0x0000FFFF</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d0ea77d1231214ba0893e846d7fcaf">UNI_MAX_UTF16</a>&nbsp;&nbsp;&nbsp;(UTF32)0x0010FFFF</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26c4390ae1463df1e6075ea585ed79a3">UNI_MAX_UTF32</a>&nbsp;&nbsp;&nbsp;(UTF32)0x7FFFFFFF</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a2f50a1ca513613316ffd384dd1bfb">UNI_MAX_LEGAL_UTF32</a>&nbsp;&nbsp;&nbsp;(UTF32)0x0010FFFF</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd41ea1a2b55429f9d18653a02a4bd98">UNI_MAX_UTF8_BYTES_PER_CODE_POINT</a>&nbsp;&nbsp;&nbsp;4</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04ebcc9bd96acb50f34a94772fa4dbb">UNI_UTF16_BYTE_ORDER_MARK_NATIVE</a>&nbsp;&nbsp;&nbsp;65279</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa1dc32abb594acac67dee02a7f67a76">UNI_UTF16_BYTE_ORDER_MARK_SWAPPED</a>&nbsp;&nbsp;&nbsp;65534</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab89338d7545b70780f999fe6f125df66">UNI_UTF32_BYTE_ORDER_MARK_NATIVE</a>&nbsp;&nbsp;&nbsp;65279</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a5948638e705e5f827751d8f0ee1720">UNI_UTF32_BYTE_ORDER_MARK_SWAPPED</a>&nbsp;&nbsp;&nbsp;4294836224</td>
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

### UNI\_MAX\_BMP {#adc71280d09832f0fb6c6b83fbf043140}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_MAX_BMP&nbsp;&nbsp;&nbsp;(UTF32)0x0000FFFF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a82e113be2d7b15014ca0d577ee93942a">llvm::ConvertUTF32toUTF16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adda0d47c266c2443b44d2e2af459bb2a">llvm::ConvertUTF8toUTF16</a>.</p>

</div>
</div>

### UNI\_MAX\_LEGAL\_UTF32 {#a98a2f50a1ca513613316ffd384dd1bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_MAX_LEGAL_UTF32&nbsp;&nbsp;&nbsp;(UTF32)0x0010FFFF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a82e113be2d7b15014ca0d577ee93942a">llvm::ConvertUTF32toUTF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3bf0f73ed17fc80c3253d89a3708c62">llvm::ConvertUTF32toUTF8</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a01e0eabee8e4d41ebbc36d1f3060f94f">llvm::ConvertUTF8toUTF32Impl</a>.</p>

</div>
</div>

### UNI\_MAX\_UTF16 {#a69d0ea77d1231214ba0893e846d7fcaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_MAX_UTF16&nbsp;&nbsp;&nbsp;(UTF32)0x0010FFFF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#adda0d47c266c2443b44d2e2af459bb2a">llvm::ConvertUTF8toUTF16</a>.</p>

</div>
</div>

### UNI\_MAX\_UTF32 {#a26c4390ae1463df1e6075ea585ed79a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_MAX_UTF32&nbsp;&nbsp;&nbsp;(UTF32)0x7FFFFFFF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>

</div>
</div>

### UNI\_MAX\_UTF8\_BYTES\_PER\_CODE\_POINT {#abd41ea1a2b55429f9d18653a02a4bd98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_MAX_UTF8_BYTES_PER_CODE_POINT&nbsp;&nbsp;&nbsp;4</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d4ce88555d804615c0cd225d9fcb6">llvm::convertUTF32ToUTF8String</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a632e8458ae307eeaa12c092cb27c689f">llvm::convertWideToUTF8</a>.</p>

</div>
</div>

### UNI\_REPLACEMENT\_CHAR {#a44b240b95a93f71535c03f5e26d7dbe1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_REPLACEMENT_CHAR&nbsp;&nbsp;&nbsp;(UTF32)0x0000FFFD</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a988452fbc9a0ba7121a951fce8a6e306">llvm::ConvertUTF16toUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82e113be2d7b15014ca0d577ee93942a">llvm::ConvertUTF32toUTF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3bf0f73ed17fc80c3253d89a3708c62">llvm::ConvertUTF32toUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adda0d47c266c2443b44d2e2af459bb2a">llvm::ConvertUTF8toUTF16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a01e0eabee8e4d41ebbc36d1f3060f94f">llvm::ConvertUTF8toUTF32Impl</a>.</p>

</div>
</div>

### UNI\_UTF16\_BYTE\_ORDER\_MARK\_NATIVE {#af04ebcc9bd96acb50f34a94772fa4dbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_UTF16_BYTE_ORDER_MARK_NATIVE&nbsp;&nbsp;&nbsp;65279</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>.</p>

</div>
</div>

### UNI\_UTF16\_BYTE\_ORDER\_MARK\_SWAPPED {#afa1dc32abb594acac67dee02a7f67a76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_UTF16_BYTE_ORDER_MARK_SWAPPED&nbsp;&nbsp;&nbsp;65534</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/object/#ad367577ea33bb6c474e53aee35df3b37">llvm::object::convertUTF16LEToUTF8String</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a8059c040f5af7b4554015074e49f5cd2">llvm::convertUTF16ToUTF8String</a>.</p>

</div>
</div>

### UNI\_UTF32\_BYTE\_ORDER\_MARK\_NATIVE {#ab89338d7545b70780f999fe6f125df66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_UTF32_BYTE_ORDER_MARK_NATIVE&nbsp;&nbsp;&nbsp;65279</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d4ce88555d804615c0cd225d9fcb6">llvm::convertUTF32ToUTF8String</a>.</p>

</div>
</div>

### UNI\_UTF32\_BYTE\_ORDER\_MARK\_SWAPPED {#a2a5948638e705e5f827751d8f0ee1720}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_UTF32_BYTE_ORDER_MARK_SWAPPED&nbsp;&nbsp;&nbsp;4294836224</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">ConvertUTF.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aa39d4ce88555d804615c0cd225d9fcb6">llvm::convertUTF32ToUTF8String</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
