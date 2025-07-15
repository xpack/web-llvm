---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/dilineinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DILineInfo` Struct Reference

<p>A format-neutral container for source line information. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::DILineInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">llvm/DebugInfo/DIContext.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a> (const DILineInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a413313c492e3c86ec9bb8c0a04461a5f">operator!=</a> (const DILineInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a> (const DILineInfo &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abff3fd22afe2a89a97b618abfc728cf5">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a230d231177001096a632a982631dd4dd">dump</a> (raw_ostream &amp;OS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafbd532afdd9c251604c825b8368580d">FileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8894db2d4e97b2f89e68769bea54b3b">FunctionName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee6de87e87f24d06aadf8ad3821ab007">StartFileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1ab4aaa7a2c43e131246c266c496986">Source</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1055d89c22f9257f93e137bc42ab3b1">LineSource</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b67fe0ad4e7bfe7c66e2ae3fa9b1ab">Line</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdd9c481889f931155cca79f72e034f4">Column</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade557e29b505c495f4e761fdba518595">StartLine</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b086783f95057c188bc04c705faff25">StartAddress</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c4c35f717ef11a8331573d47a83a93">Discriminator</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2093e947aabba30c6a82adaa288a602c">IsApproximateLine</a> = false</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a519f3c4eea5a21cce1242995f27f13e9">ApproxString</a> = "(approximate)"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2fecd19cf03aa8167943894af5f8c4">BadString</a> = "&lt;invalid&gt;"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bdc0174f72b0cb5ce38132c702bb00a">Addr2LineBadString</a> = "??"</td>
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

<p>A format-neutral container for source line information.</p>

<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DILineInfo() {#ac9a52eebd7b2776ee70e2921e93ebca1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DILineInfo::DILineInfo ()</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#a1d2fecd19cf03aa8167943894af5f8c4">BadString</a>, <a href="#aafbd532afdd9c251604c825b8368580d">FileName</a>, <a href="#ab8894db2d4e97b2f89e68769bea54b3b">FunctionName</a> and <a href="#aee6de87e87f24d06aadf8ad3821ab007">StartFileName</a>.</p>


<p>Referenced by <a href="#abff3fd22afe2a89a97b618abfc728cf5">operator bool</a>, <a href="#a413313c492e3c86ec9bb8c0a04461a5f">operator!=</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a> and <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#abff3fd22afe2a89a97b618abfc728cf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DILineInfo::operator bool ()</td>
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



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Reference <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a>.</p>

</div>
</div>

### operator!=() {#a413313c492e3c86ec9bb8c0a04461a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILineInfo::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &amp; RHS)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator&lt;() {#ae122160c39dbf431f86aecb81ad10704}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILineInfo::operator&lt; (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &amp; RHS)</td>
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



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#abdd9c481889f931155cca79f72e034f4">Column</a>, <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a>, <a href="#a40c4c35f717ef11a8331573d47a83a93">Discriminator</a>, <a href="#aafbd532afdd9c251604c825b8368580d">FileName</a>, <a href="#ab8894db2d4e97b2f89e68769bea54b3b">FunctionName</a>, <a href="#a69b67fe0ad4e7bfe7c66e2ae3fa9b1ab">Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aee6de87e87f24d06aadf8ad3821ab007">StartFileName</a> and <a href="#ade557e29b505c495f4e761fdba518595">StartLine</a>.</p>

</div>
</div>

### operator==() {#a9cc1f32f25f95d4e16a9e734e8bb377d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILineInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/dilineinfo">DILineInfo</a> &amp; RHS)</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#abdd9c481889f931155cca79f72e034f4">Column</a>, <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a>, <a href="#a40c4c35f717ef11a8331573d47a83a93">Discriminator</a>, <a href="#aafbd532afdd9c251604c825b8368580d">FileName</a>, <a href="#ab8894db2d4e97b2f89e68769bea54b3b">FunctionName</a>, <a href="#a69b67fe0ad4e7bfe7c66e2ae3fa9b1ab">Line</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>, <a href="#aee6de87e87f24d06aadf8ad3821ab007">StartFileName</a> and <a href="#ade557e29b505c495f4e761fdba518595">StartLine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a230d231177001096a632a982631dd4dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DILineInfo::dump (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>References <a href="#a1d2fecd19cf03aa8167943894af5f8c4">BadString</a>, <a href="#abdd9c481889f931155cca79f72e034f4">Column</a>, <a href="#aafbd532afdd9c251604c825b8368580d">FileName</a>, <a href="#ab8894db2d4e97b2f89e68769bea54b3b">FunctionName</a>, <a href="#a69b67fe0ad4e7bfe7c66e2ae3fa9b1ab">Line</a>, <a href="#aee6de87e87f24d06aadf8ad3821ab007">StartFileName</a> and <a href="#ade557e29b505c495f4e761fdba518595">StartLine</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Column {#abdd9c481889f931155cca79f72e034f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DILineInfo::Column = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#a230d231177001096a632a982631dd4dd">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#a9690eb35ff7a9e7476c1f08ebe174e27">llvm::pdb::PDBContext::getInliningInfoForAddress</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a>, <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### Discriminator {#a40c4c35f717ef11a8331573d47a83a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DILineInfo::Discriminator = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a>, <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### FileName {#aafbd532afdd9c251604c825b8368580d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DILineInfo::FileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a>, <a href="#a230d231177001096a632a982631dd4dd">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#a9690eb35ff7a9e7476c1f08ebe174e27">llvm::pdb::PDBContext::getInliningInfoForAddress</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a>, <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/jsonprinter/#a808d66d93b73e4fdd1e409c9ba48671b">llvm::symbolize::JSONPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### FunctionName {#ab8894db2d4e97b2f89e68769bea54b3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DILineInfo::FunctionName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a>, <a href="#a230d231177001096a632a982631dd4dd">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#a9690eb35ff7a9e7476c1f08ebe174e27">llvm::pdb::PDBContext::getInliningInfoForAddress</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a>, <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### IsApproximateLine {#a2093e947aabba30c6a82adaa288a602c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::DILineInfo::IsApproximateLine = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### Line {#a69b67fe0ad4e7bfe7c66e2ae3fa9b1ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DILineInfo::Line = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#a230d231177001096a632a982631dd4dd">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/pdb/pdbcontext/#a9690eb35ff7a9e7476c1f08ebe174e27">llvm::pdb::PDBContext::getInliningInfoForAddress</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a>, <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/jsonprinter/#a808d66d93b73e4fdd1e409c9ba48671b">llvm::symbolize::JSONPrinter::print</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### LineSource {#af1055d89c22f9257f93e137bc42ab3b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::DILineInfo::LineSource</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

### Source {#aa1ab4aaa7a2c43e131246c266c496986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;StringRef&gt; llvm::DILineInfo::Source</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symbolize/jsonprinter/#a808d66d93b73e4fdd1e409c9ba48671b">llvm::symbolize::JSONPrinter::print</a>.</p>

</div>
</div>

### StartAddress {#a2b086783f95057c188bc04c705faff25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::DILineInfo::StartAddress</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### StartFileName {#aee6de87e87f24d06aadf8ad3821ab007}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::DILineInfo::StartFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a>, <a href="#a230d231177001096a632a982631dd4dd">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a>, <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

### StartLine {#ade557e29b505c495f4e761fdba518595}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::DILineInfo::StartLine = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#a230d231177001096a632a982631dd4dd">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a063924dae0fe080259de2f7f2d7949eb">llvm::DWARFContext::getInliningInfoForAddress</a>, <a href="#ae122160c39dbf431f86aecb81ad10704">operator&lt;</a>, <a href="#a9cc1f32f25f95d4e16a9e734e8bb377d">operator==</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### Addr2LineBadString {#a4bdc0174f72b0cb5ce38132c702bb00a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::DILineInfo::Addr2LineBadString = "??"</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#affd94f6421b8ea9074813cb07edf9af1">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a7f435370eac27a8d71d7ec885910bf0b">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#abf95e7e26e59bb529cc62cbf06285524">llvm::symbolize::PlainPrinterBase::print</a> and <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#ab2c186a58dd705d72e7c689355080b01">llvm::symbolize::PlainPrinterBase::printFunctionName</a>.</p>

</div>
</div>

### ApproxString {#a519f3c4eea5a21cce1242995f27f13e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::DILineInfo::ApproxString = "(approximate)"</td>
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



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>

</div>
</div>

### BadString {#a1d2fecd19cf03aa8167943894af5f8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* const llvm::DILineInfo::BadString = "&lt;invalid&gt;"</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a>.</p>


<p>Referenced by <a href="#ac9a52eebd7b2776ee70e2921e93ebca1">DILineInfo</a>, <a href="#a230d231177001096a632a982631dd4dd">dump</a>, <a href="/web-llvm/docs/api/classes/llvm/dwarfcontext/#a55f204d9568a58fbc54ad04343452904">llvm::DWARFContext::getLineInfoForAddressRange</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/jsonprinter/#a172e06333c63683404e516e6f5cabdf9">llvm::symbolize::JSONPrinter::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#affd94f6421b8ea9074813cb07edf9af1">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#a7f435370eac27a8d71d7ec885910bf0b">llvm::symbolize::PlainPrinterBase::print</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/plainprinterbase/#ab2c186a58dd705d72e7c689355080b01">llvm::symbolize::PlainPrinterBase::printFunctionName</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#a218915a5f9c3f5f93eb5b91d64b86bef">llvm::symbolize::SymbolizableObjectFile::symbolizeCode</a>, <a href="/web-llvm/docs/api/classes/llvm/symbolize/symbolizableobjectfile/#af579f0af68a8e23690bd1e3ef3ed2b0e">llvm::symbolize::SymbolizableObjectFile::symbolizeInlinedCode</a> and <a href="/web-llvm/docs/api/namespaces/llvm/symbolize/#add9bc2a455dcdc69f83ff0c32445cb1f">llvm::symbolize::toJSON</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/dicontext-h">DIContext.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
