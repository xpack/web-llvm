---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/status
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Status` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct Status { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a521e597985be481067010a6b7b40f7dc">Status</a> (unsigned NewMask, unsigned NewMode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6927b9d6af12920e80ae469aa1660491">operator==</a> (const Status &amp;S) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa92eb76e83481bf6df6ecb43ae05964d">operator!=</a> (const Status &amp;S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d238cf08ca2aca7b1ef0e8b7a4b0770">merge</a> (const Status &amp;S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedf18ee1c895e1fea6c0e7e195a5a1ca">mergeUnknown</a> (unsigned newMask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6c36013b7c84c75cc978506e306a1a4">intersect</a> (const Status &amp;S) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/status">Status</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d49768146ce886e2eb17aacd8159ca9">delta</a> (const Status &amp;S) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78cea2430649ceb585466218022bd579">isCompatible</a> (Status &amp;S)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62c91ffba279ca27ad70766196e3367c">isCombinable</a> (Status &amp;S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad278024750ac1478e4a551043df7ff65">Mask</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a> = 0</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Status() {#a693c4657472e9cd6990e401f1a26f88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status::Status ()</td>
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



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>Referenced by <a href="#a4d49768146ce886e2eb17aacd8159ca9">delta</a>, <a href="#aa6c36013b7c84c75cc978506e306a1a4">intersect</a>, <a href="#a62c91ffba279ca27ad70766196e3367c">isCombinable</a>, <a href="#a78cea2430649ceb585466218022bd579">isCompatible</a>, <a href="#a7d238cf08ca2aca7b1ef0e8b7a4b0770">merge</a>, <a href="#aedf18ee1c895e1fea6c0e7e195a5a1ca">mergeUnknown</a>, <a href="#aa92eb76e83481bf6df6ecb43ae05964d">operator!=</a> and <a href="#a6927b9d6af12920e80ae469aa1660491">operator==</a>.</p>

</div>
</div>

### Status() {#a521e597985be481067010a6b7b40f7dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status::Status (unsigned NewMask, unsigned NewMode)</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a> and <a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#aa92eb76e83481bf6df6ecb43ae05964d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Status::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/status">Status</a> &amp; S)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>Reference <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>

</div>
</div>

### operator==() {#a6927b9d6af12920e80ae469aa1660491}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Status::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/status">Status</a> &amp; S)</td>
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



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a>, <a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a> and <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### delta() {#a4d49768146ce886e2eb17aacd8159ca9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status Status::delta (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/status">Status</a> &amp; S)</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a>, <a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a> and <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#acf320f6e863d6b402e856a2c603d5ab5">anonymous{SIModeRegister.cpp}::SIModeRegister::processBlockPhase1</a>.</p>

</div>
</div>

### intersect() {#aa6c36013b7c84c75cc978506e306a1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status Status::intersect (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/status">Status</a> &amp; S)</td>
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



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a>, <a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a> and <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>

</div>
</div>

### isCombinable() {#a62c91ffba279ca27ad70766196e3367c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Status::isCombinable (<a href="/web-llvm/docs/api/structs/status">Status</a> &amp; S)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#a78cea2430649ceb585466218022bd579">isCompatible</a>, <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a> and <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#acf320f6e863d6b402e856a2c603d5ab5">anonymous{SIModeRegister.cpp}::SIModeRegister::processBlockPhase1</a>.</p>

</div>
</div>

### isCompatible() {#a78cea2430649ceb585466218022bd579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Status::isCompatible (<a href="/web-llvm/docs/api/structs/status">Status</a> &amp; S)</td>
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



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a>, <a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a> and <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>


<p>Referenced by <a href="#a62c91ffba279ca27ad70766196e3367c">isCombinable</a>.</p>

</div>
</div>

### merge() {#a7d238cf08ca2aca7b1ef0e8b7a4b0770}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status Status::merge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/status">Status</a> &amp; S)</td>
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



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a>, <a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a> and <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#acf320f6e863d6b402e856a2c603d5ab5">anonymous{SIModeRegister.cpp}::SIModeRegister::processBlockPhase1</a>.</p>

</div>
</div>

### mergeUnknown() {#aedf18ee1c895e1fea6c0e7e195a5a1ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Status Status::mergeUnknown (unsigned newMask)</td>
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



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>References <a href="#ad278024750ac1478e4a551043df7ff65">Mask</a>, <a href="#ae0d986f890ca1ef807fb7bbf99cff5bf">Mode</a> and <a href="#a693c4657472e9cd6990e401f1a26f88a">Status</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Mask {#ad278024750ac1478e4a551043df7ff65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Status::Mask = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>Referenced by <a href="#a4d49768146ce886e2eb17aacd8159ca9">delta</a>, <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#ac5cb23515382def14508d54ee39bcc5f">anonymous{SIModeRegister.cpp}::SIModeRegister::insertSetreg</a>, <a href="#aa6c36013b7c84c75cc978506e306a1a4">intersect</a>, <a href="#a62c91ffba279ca27ad70766196e3367c">isCombinable</a>, <a href="#a78cea2430649ceb585466218022bd579">isCompatible</a>, <a href="#a7d238cf08ca2aca7b1ef0e8b7a4b0770">merge</a>, <a href="#aedf18ee1c895e1fea6c0e7e195a5a1ca">mergeUnknown</a>, <a href="#a6927b9d6af12920e80ae469aa1660491">operator==</a> and <a href="#a521e597985be481067010a6b7b40f7dc">Status</a>.</p>

</div>
</div>

### Mode {#ae0d986f890ca1ef807fb7bbf99cff5bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Status::Mode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a>.</p>


<p>Referenced by <a href="#a4d49768146ce886e2eb17aacd8159ca9">delta</a>, <a href="/web-llvm/docs/api/classes/anonymous-simoderegister-cpp-/simoderegister/#ac5cb23515382def14508d54ee39bcc5f">anonymous{SIModeRegister.cpp}::SIModeRegister::insertSetreg</a>, <a href="#aa6c36013b7c84c75cc978506e306a1a4">intersect</a>, <a href="#a78cea2430649ceb585466218022bd579">isCompatible</a>, <a href="#a7d238cf08ca2aca7b1ef0e8b7a4b0770">merge</a>, <a href="#aedf18ee1c895e1fea6c0e7e195a5a1ca">mergeUnknown</a>, <a href="#a6927b9d6af12920e80ae469aa1660491">operator==</a> and <a href="#a521e597985be481067010a6b7b40f7dc">Status</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/simoderegister-cpp">SIModeRegister.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
