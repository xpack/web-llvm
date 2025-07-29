---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/btftypefloat
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BTFTypeFloat` Class

<p>Handle binary floating point type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BTFTypeFloat { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6bd8e2f62122a7d8a483c52c07a8e63">BTFTypeFloat</a> (uint32_t SizeInBits, StringRef TypeName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd7f4cfa99246fbe1e0d9a887f89daf">completeType</a> (BTFDebug &amp;BDebug) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Complete <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type generation after all related DebugInfo types have been visited so their <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type id's are available for cross referece. <a href="#a9fd7f4cfa99246fbe1e0d9a887f89daf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9ff206fa41f512414fdc4f2be121089">Name</a></td>
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

<p>Handle binary floating point type.</p>

<p>Definition at line 201 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BTFTypeFloat() {#ab6bd8e2f62122a7d8a483c52c07a8e63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BTFTypeFloat::BTFTypeFloat (uint32_t SizeInBits, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TypeName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 439 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a0cebeba190cfb4a6959a5aab93700829">llvm::BTFTypeBase::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af531da13c9fd67de1bfbf782eb04b7c7">llvm::BTFTypeBase::roundupToBytes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### completeType() {#a9fd7f4cfa99246fbe1e0d9a887f89daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFTypeFloat::completeType (<a href="/web-llvm/docs/api/classes/llvm/btfdebug">BTFDebug</a> &amp; BDebug)</td>
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

<p>Declaration at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a49279d4bb54b6577992d301458c6512d">llvm::BTFDebug::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a9d62bd0b4b094cf0f35d47cc024ed1bf">llvm::BTFTypeBase::IsCompleted</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Name {#ad9ff206fa41f512414fdc4f2be121089}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BTFTypeFloat::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

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
