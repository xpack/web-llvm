---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/support/convertutf-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `ConvertUTF.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/convertutf-h">llvm/Support/ConvertUTF.h</a>"
#include &lt;assert.h&gt;
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc447f16673e43c25917dab90c642c4">ConvertUTF_DISABLE_WARNINGS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afacfcd89f24bd3bbf56f4f7f3b36755b">ConvertUTF_RESTORE_WARNINGS</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ab84eb26356a90f3b7b9ac7aca1edfe">UNI_SUR_HIGH_START</a>&nbsp;&nbsp;&nbsp;(UTF32)0xD800</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5481872f1061e4e2a66849802b4b81e">UNI_SUR_HIGH_END</a>&nbsp;&nbsp;&nbsp;(UTF32)0xDBFF</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23de5862375b48afcb4e3ff7b56a274d">UNI_SUR_LOW_START</a>&nbsp;&nbsp;&nbsp;(UTF32)0xDC00</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9a531ffb73be79f7089049c1b84dc59">UNI_SUR_LOW_END</a>&nbsp;&nbsp;&nbsp;(UTF32)0xDFFF</td>
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

### ConvertUTF\_DISABLE\_WARNINGS {#a7fc447f16673e43c25917dab90c642c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ConvertUTF_DISABLE_WARNINGS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/lib/lib/support/convertutf-cpp">ConvertUTF.cpp</a>.</p>

</div>
</div>

### ConvertUTF\_RESTORE\_WARNINGS {#afacfcd89f24bd3bbf56f4f7f3b36755b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ConvertUTF_RESTORE_WARNINGS</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/lib/lib/support/convertutf-cpp">ConvertUTF.cpp</a>.</p>

</div>
</div>

### UNI\_SUR\_HIGH\_END {#ae5481872f1061e4e2a66849802b4b81e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_SUR_HIGH_END&nbsp;&nbsp;&nbsp;(UTF32)0xDBFF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/support/convertutf-cpp">ConvertUTF.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acfe7abb08f321fadc531bbfcd08195b8">llvm::ConvertUTF16toUTF32</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a988452fbc9a0ba7121a951fce8a6e306">llvm::ConvertUTF16toUTF8</a>.</p>

</div>
</div>

### UNI\_SUR\_HIGH\_START {#a4ab84eb26356a90f3b7b9ac7aca1edfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_SUR_HIGH_START&nbsp;&nbsp;&nbsp;(UTF32)0xD800</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/support/convertutf-cpp">ConvertUTF.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acfe7abb08f321fadc531bbfcd08195b8">llvm::ConvertUTF16toUTF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a988452fbc9a0ba7121a951fce8a6e306">llvm::ConvertUTF16toUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82e113be2d7b15014ca0d577ee93942a">llvm::ConvertUTF32toUTF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3bf0f73ed17fc80c3253d89a3708c62">llvm::ConvertUTF32toUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adda0d47c266c2443b44d2e2af459bb2a">llvm::ConvertUTF8toUTF16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a01e0eabee8e4d41ebbc36d1f3060f94f">llvm::ConvertUTF8toUTF32Impl</a>.</p>

</div>
</div>

### UNI\_SUR\_LOW\_END {#ab9a531ffb73be79f7089049c1b84dc59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_SUR_LOW_END&nbsp;&nbsp;&nbsp;(UTF32)0xDFFF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/support/convertutf-cpp">ConvertUTF.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acfe7abb08f321fadc531bbfcd08195b8">llvm::ConvertUTF16toUTF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a988452fbc9a0ba7121a951fce8a6e306">llvm::ConvertUTF16toUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82e113be2d7b15014ca0d577ee93942a">llvm::ConvertUTF32toUTF16</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab3bf0f73ed17fc80c3253d89a3708c62">llvm::ConvertUTF32toUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adda0d47c266c2443b44d2e2af459bb2a">llvm::ConvertUTF8toUTF16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a01e0eabee8e4d41ebbc36d1f3060f94f">llvm::ConvertUTF8toUTF32Impl</a>.</p>

</div>
</div>

### UNI\_SUR\_LOW\_START {#a23de5862375b48afcb4e3ff7b56a274d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define UNI_SUR_LOW_START&nbsp;&nbsp;&nbsp;(UTF32)0xDC00</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/support/convertutf-cpp">ConvertUTF.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acfe7abb08f321fadc531bbfcd08195b8">llvm::ConvertUTF16toUTF32</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a988452fbc9a0ba7121a951fce8a6e306">llvm::ConvertUTF16toUTF8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82e113be2d7b15014ca0d577ee93942a">llvm::ConvertUTF32toUTF16</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#adda0d47c266c2443b44d2e2af459bb2a">llvm::ConvertUTF8toUTF16</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
