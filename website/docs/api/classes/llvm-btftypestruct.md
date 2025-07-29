---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/btftypestruct
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BTFTypeStruct` Class

<p>Handle struct/union type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BTFTypeStruct { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">Target/BPF/BTFDebug.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/btftypebase">BTFTypeBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The base class for <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type generation. <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acae1d74827462d1e7483422994e8fe29">BTFTypeStruct</a> (const DICompositeType *STy, bool IsStruct, bool HasBitField, uint32_t NumMembers)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represent either a struct or a union. <a href="#acae1d74827462d1e7483422994e8fe29">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0f298767e922c2e9e34ad99991ecb19">getSize</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#ac0f298767e922c2e9e34ad99991ecb19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9bd52649a7141c0bc1bae5f0a9e8f06">completeType</a> (BTFDebug &amp;BDebug) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Complete <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type generation after all related DebugInfo types have been visited so their <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type id's are available for cross referece. <a href="#ad9bd52649a7141c0bc1bae5f0a9e8f06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a261288152d81e6ee565d7c68d175624e">emitType</a> (MCStreamer &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit types for this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#a261288152d81e6ee565d7c68d175624e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4de39f4af6e9d464c501a660769a1b">getName</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed5d21cc1990aecc34afa95aa0bf981e">STy</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab236e14bed01d30b7f2ccca04661e780">HasBitField</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; struct <a href="/web-llvm/docs/api/structs/llvm/btf/btfmember">BTF::BTFMember</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2f76befb90dce7fc2108710f34019f">Members</a></td>
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

<p>Handle struct/union type.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BTFTypeStruct() {#acae1d74827462d1e7483422994e8fe29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BTFTypeStruct::BTFTypeStruct (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * STy, bool IsStruct, bool HasBitField, uint32_t NumMembers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Represent either a struct or a union.</p>

<p>Declaration at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a0cebeba190cfb4a6959a5aab93700829">llvm::BTFTypeBase::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af531da13c9fd67de1bfbf782eb04b7c7">llvm::BTFTypeBase::roundupToBytes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### completeType() {#ad9bd52649a7141c0bc1bae5f0a9e8f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFTypeStruct::completeType (<a href="/web-llvm/docs/api/classes/llvm/btfdebug">BTFDebug</a> &amp; BDebug)</td>
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

<p>Complete <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type generation after all related DebugInfo types have been visited so their <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type id's are available for cross referece.</p>

<p>Declaration at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a49279d4bb54b6577992d301458c6512d">llvm::BTFDebug::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a901f5c847e07433c2b9977e1a8567454">llvm::BTFDebug::getTypeId</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a9d62bd0b4b094cf0f35d47cc024ed1bf">llvm::BTFTypeBase::IsCompleted</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/btfmember/#a0ffcd706611ea780a90179deaa4ff57b">llvm::BTF::BTFMember::NameOff</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/btfmember/#a2acadf022d68b4e7905efcadfbfd3444">llvm::BTF::BTFMember::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp/#ad40a6e28ad9b5134d8985bc9889fec4d">tryRemoveAtomicType</a> and <a href="/web-llvm/docs/api/structs/llvm/btf/btfmember/#ad51708ec32be9d7307732b6d308f06cc">llvm::BTF::BTFMember::Type</a>.</p>

</div>
</div>

### emitType() {#a261288152d81e6ee565d7c68d175624e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFTypeStruct::emitType (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
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

<p>Emit types for this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry.</p>


<p>Emit a <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> common type.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 323 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af00b13d92054d7b6f7c8b4561f46685b">llvm::BTFTypeBase::emitType</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getName() {#afb4de39f4af6e9d464c501a660769a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string BTFTypeStruct::getName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>

</div>
</div>

### getSize() {#ac0f298767e922c2e9e34ad99991ecb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTFTypeStruct::getSize ()</td>
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

<p>Get the size of this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry.</p>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/btf/#ac469d636ea54a1eb9da4c1f633a4496ca3663f67af63c0c12b250f0a116272dea">llvm::BTF::BTFMemberSize</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a761afb51bc258152f71a07bfa2e9e2b7">llvm::BTFTypeBase::getSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### HasBitField {#ab236e14bed01d30b7f2ccca04661e780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::BTFTypeStruct::HasBitField</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

### Members {#a5e2f76befb90dce7fc2108710f34019f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;struct BTF::BTFMember&gt; llvm::BTFTypeStruct::Members</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

### STy {#aed5d21cc1990aecc34afa95aa0bf981e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DICompositeType* llvm::BTFTypeStruct::STy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
