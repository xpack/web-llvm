---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/stackoffset
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `StackOffset` Class Reference

<p><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> holds a fixed and a scalable offset in bytes. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::StackOffset { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">llvm/Support/TypeSize.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1180b456475627c52a88d9950168733">StackOffset</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac524864f698f71aab0bb6565425f20">StackOffset</a> (int64_t Fixed, int64_t Scalable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1217b85b9a15f96784482b0d492fc209">operator+</a> (const StackOffset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ba0bf822d8fb8951e145b9e696a2f4">operator-</a> (const StackOffset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af07e2a30a69b2adb04d3744d67dfb51e">operator+=</a> (const StackOffset &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa18279e4ecdff775bb7bc397bbaf37ec">operator-=</a> (const StackOffset &amp;RHS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4636273b20556e15827e5837b34f32f4">operator-</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a754cfd4a2abded1fff0d1c11a8da7c01">operator==</a> (const StackOffset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46eb1b1f5dbb37866bb2daed97f02242">operator!=</a> (const StackOffset &amp;RHS) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75a4bd0a207a0f670fca719de92ab0d2">operator bool</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0775e5fb52ac148f4d06e7eedb34e94e">getFixed</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the fixed component of the stack. <a href="#a0775e5fb52ac148f4d06e7eedb34e94e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bb61639d8566c8d12f66c562d948bef">getScalable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the scalable component of the stack. <a href="#a3bb61639d8566c8d12f66c562d948bef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca939b844489c19a123c81d630acb97">Fixed</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e8885f04beed44296b10faa1782b8e8">Scalable</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb11e994c5580c80bbb0951eb05f9c80">getFixed</a> (int64_t Fixed)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac92bd14c26009fdfdc00576604da950f">getScalable</a> (int64_t Scalable)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab735eb6b844f1b683d12013a083b4e2">get</a> (int64_t Fixed, int64_t Scalable)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> holds a fixed and a scalable offset in bytes.</p>

<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### StackOffset() {#ac1180b456475627c52a88d9950168733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StackOffset::StackOffset ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### StackOffset() {#adac524864f698f71aab0bb6565425f20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StackOffset::StackOffset (int64_t Fixed, int64_t Scalable)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator bool() {#a75a4bd0a207a0f670fca719de92ab0d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::StackOffset::operator bool ()</td>
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



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

### operator-() {#a64ba0bf822d8fb8951e145b9e696a2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset llvm::StackOffset::operator- (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp; RHS)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator-() {#a4636273b20556e15827e5837b34f32f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset llvm::StackOffset::operator- ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

### operator-=() {#aa18279e4ecdff775bb7bc397bbaf37ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset &amp; llvm::StackOffset::operator-= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp; RHS)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator!=() {#a46eb1b1f5dbb37866bb2daed97f02242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StackOffset::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp; RHS)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+() {#a1217b85b9a15f96784482b0d492fc209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset llvm::StackOffset::operator+ (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp; RHS)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator+=() {#af07e2a30a69b2adb04d3744d67dfb51e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset &amp; llvm::StackOffset::operator+= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp; RHS)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### operator==() {#a754cfd4a2abded1fff0d1c11a8da7c01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::StackOffset::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stackoffset">StackOffset</a> &amp; RHS)</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getFixed() {#a0775e5fb52ac148f4d06e7eedb34e94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::StackOffset::getFixed ()</td>
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

<p>Returns the fixed component of the stack.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#aa4909014e5875c7b2d1cd6fdd7ab7e89">llvm::RISCVRegisterInfo::adjustReg</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#aa24149b04083669797095c1473b14f3a">llvm::AArch64RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/loongarchregisterinfo/#a14277e449886ad06b196b805fad006ec">llvm::LoongArchRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#afea15e305a01decf5c19eb0ccedc38a1">llvm::RISCVRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/asmprinter-cpp/#a0207059cc31ba2a73d1d7bc1ce62663f">emitDebugValueComment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c6206e8d8fd98ecca8ac2c785ee9491">llvm::emitFrameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#abc7410daace72818d9ce654814a67892">getFPOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/armframelowering/#a0d5a207d110955367d9418022a41b8c5">llvm::ARMFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/cskyframelowering/#a317f0fab04ed40f94b6d80d68370fe43">llvm::CSKYFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonframelowering/#a75d48c8917ed2a09d85cf46fcda67002">llvm::HexagonFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchframelowering/#a0f71a92dc6f774b7059d9490a29d52ad">llvm::LoongArchFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kframelowering/#a7a7d0ca18a51d0d4829fb467deed15e9">llvm::M68kFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/mipsseframelowering/#a46adda2adcecd14a8c1ef28661069805">llvm::MipsSEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxframelowering/#acafaf5b04f0664b35c2b2c3d83f2de27">llvm::NVPTXFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/r600framelowering/#a7829220a3eab94d3ec786598ab48da83">llvm::R600FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/siframelowering/#a1d2fa221d761f2dbaeb65823e305b8d7">llvm::SIFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/sparcframelowering/#ac3af49ca4a1c47f7c01abaae4e8092bf">llvm::SparcFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a95fac1598df11a84e80e2da098dbe4b3">llvm::SystemZELFFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#af88a8f2328543f94aea3ba85d954fafa">llvm::TargetFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/veframelowering/#a77083d402f6deba15f8ccf39ffff370e">llvm::VEFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a84fbe17f451c957c67de546c98f2b79b">llvm::X86FrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a454562a019aeae43ffd6a8ce7f894ed3">llvm::AArch64FrameLowering::getFrameIndexReferenceFromSP</a>, <a href="/web-llvm/docs/api/classes/llvm/targetframelowering/#adea691938e0e44353858c07a39a5d0a6">llvm::TargetFrameLowering::getFrameIndexReferenceFromSP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ad6591055c1ba6d0a1033510f7a4eab65">llvm::AArch64FrameLowering::getFrameIndexReferencePreferSP</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a79ebbed1ceecae3f74214e33fc8c533f">llvm::X86FrameLowering::getFrameIndexReferenceSP</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a492547015f6f9aaf93099d70b32e8d9a">llvm::AArch64FrameLowering::getNonLocalFrameIndexReference</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/#a15018e8dce8929d06d5b0e67b3ac424b">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::getStackOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#abfe6f4589d25ac776ff98f1ac68518a6">getStackOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a7b0d5c1915330faa3a19839c10ccfd2f">llvm::AArch64RegisterInfo::isFrameOffsetLegal</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64registerinfo/#a825b9cf5093b700f2b37cf4b7555af66">llvm::AArch64RegisterInfo::resolveFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acbe69ef233b07b4362366dcfc380abca">llvm::rewriteAArch64FrameIndex</a>.</p>

</div>
</div>

### getScalable() {#a3bb61639d8566c8d12f66c562d948bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::StackOffset::getScalable ()</td>
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

<p>Returns the scalable component of the stack.</p>

<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c6206e8d8fd98ecca8ac2c785ee9491">llvm::emitFrameOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64instrinfo-cpp/#aea02c3c9f298ea50ec11bb7c8201525a">emitFrameOffsetAdj</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a7a40dfef81dda9948bcafa33022d0fb5">getSVEStackSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Fixed {#a8ca939b844489c19a123c81d630acb97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::StackOffset::Fixed = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

### Scalable {#a1e8885f04beed44296b10faa1782b8e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t llvm::StackOffset::Scalable = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#aab735eb6b844f1b683d12013a083b4e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset llvm::StackOffset::get (int64_t Fixed, int64_t Scalable)</td>
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



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a27a80b2fc0f8820ecab9d99312bb4607">llvm::AArch64FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/structs/llvm/riscvregisterinfo/#afea15e305a01decf5c19eb0ccedc38a1">llvm::RISCVRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a9258a9f50df17d6b3c064af9bf06c2bf">llvm::RISCVFrameLowering::getFrameIndexReference</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a454562a019aeae43ffd6a8ce7f894ed3">llvm::AArch64FrameLowering::getFrameIndexReferenceFromSP</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a3cbf7279944dc2f0f99a6896501277f9">getScalingFactorCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18dec717578f39bfcff50e325c2d27c5">llvm::isAArch64FrameOffsetLegal</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>.</p>

</div>
</div>

### getFixed() {#aeb11e994c5580c80bbb0951eb05f9c80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset llvm::StackOffset::getFixed (int64_t Fixed)</td>
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



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a5d69df780f835d45386962290fc32210">llvm::RISCVFrameLowering::allocateStack</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64framelowering-cpp/#a73f427af3525340f74d7e85b984b82d6">convertCalleeSaveRestoreToSPPrePostIncDec</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a27a80b2fc0f8820ecab9d99312bb4607">llvm::AArch64FrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aeac33945153d277b7244196a35084006">llvm::RISCVFrameLowering::eliminateCallFramePseudoInstr</a>, <a href="/web-llvm/docs/api/classes/llvm/m68kregisterinfo/#abf7147087fcf4414651e62ff5de5234e">llvm::M68kRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/structs/llvm/systemzregisterinfo/#a1e101bcf68a4448908d194d220029861">llvm::SystemZRegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#a2e94eaf8bec0e356a92dc822d30de554">llvm::X86RegisterInfo::eliminateFrameIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c6206e8d8fd98ecca8ac2c785ee9491">llvm::emitFrameOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a566df1a4bd19d5e175f1d38c4a487f91">llvm::AArch64FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzelfframelowering/#a734b1c5c857eaef57158e8ceefb5b5ce">llvm::SystemZELFFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0899ff53f18fd319b08cd613b140f969">llvm::AArch64TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6bab4676a9047479dd222ae4d6e9dff0">llvm::ARMTTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a7caed3bceadafb0aaa8416b84ddb9c87">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a8e4802ac97daf25e8dce4187a513e236">llvm::TargetTransformInfoImplBase::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4c06fd8823711b9a3a748faaeea2c40c">llvm::X86TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#a94d2a07e589c43e48e5b591dd520760e">llvm::AArch64FrameLowering::getSEHFrameIndexOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#acd3876e593314b23ed0679279ee31dfe">llvm::X86FrameLowering::getWin64EHFrameIndexRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18dec717578f39bfcff50e325c2d27c5">llvm::isAArch64FrameOffsetLegal</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a809a73866dcd66caa79e94530e339fb1">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::operator&lt;</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64instrinfo/#ab9deb47df6ac29c81422ae6b4bfd924d">llvm::AArch64InstrInfo::probedStackAlloc</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a> and <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#a535388ac574e0f8d844662d315997b3d">llvm::X86FrameLowering::restoreWin32EHStackPointers</a>.</p>

</div>
</div>

### getScalable() {#ac92bd14c26009fdfdc00576604da950f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StackOffset llvm::StackOffset::getScalable (int64_t Scalable)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#aa3348fc65e993db75e0c3c050c561018">llvm::AArch64FrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#aa587d71d9d14ad035e31b99fc0c90802">llvm::RISCVFrameLowering::emitEpilogue</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvframelowering/#a131316d63f21b59d27d82ae95b91bfc7">llvm::RISCVFrameLowering::emitPrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a0899ff53f18fd319b08cd613b140f969">llvm::AArch64TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a6bab4676a9047479dd222ae4d6e9dff0">llvm::ARMTTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a7caed3bceadafb0aaa8416b84ddb9c87">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a8e4802ac97daf25e8dce4187a513e236">llvm::TargetTransformInfoImplBase::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a4c06fd8823711b9a3a748faaeea2c40c">llvm::X86TTIImpl::getScalingFactorCost</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a18dec717578f39bfcff50e325c2d27c5">llvm::isAArch64FrameOffsetLegal</a>, <a href="/web-llvm/docs/api/structs/anonymous-stackframelayoutanalysispass-cpp-/stackframelayoutanalysispass/slotdata/#a809a73866dcd66caa79e94530e339fb1">anonymous{StackFrameLayoutAnalysisPass.cpp}::StackFrameLayoutAnalysisPass::SlotData::operator&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/aarch64framelowering/#ac8934ae6c8b97148ebb1db39bd978b03">llvm::AArch64FrameLowering::resolveFrameOffsetReference</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/typesize-h">TypeSize.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
