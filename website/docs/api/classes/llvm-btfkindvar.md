---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/btfkindvar
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BTFKindVar` Class

<p>Handle variable instances. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BTFKindVar { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3622dc9ed9f5d894e5bda083b0c0b459">BTFKindVar</a> (StringRef VarName, uint32_t TypeId, uint32_t VarInfo)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87769309e75bca2cc39178c681dae612">getSize</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#a87769309e75bca2cc39178c681dae612">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb492bbaefade0483054f80d31266472">completeType</a> (BTFDebug &amp;BDebug) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Complete <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type generation after all related DebugInfo types have been visited so their <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type id's are available for cross referece. <a href="#acb492bbaefade0483054f80d31266472">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6063d7dad9aab202661760a53b2e3ae4">emitType</a> (MCStreamer &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit types for this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#a6063d7dad9aab202661760a53b2e3ae4">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1a9e26743ff60df87353f6ae65059e9">Name</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4161ccbaf770888fdcba53e9dc410df">Info</a></td>
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

<p>Handle variable instances.</p>

<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BTFKindVar() {#a3622dc9ed9f5d894e5bda083b0c0b459}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BTFKindVar::BTFKindVar (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> VarName, uint32_t TypeId, uint32_t VarInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 400 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a0cebeba190cfb4a6959a5aab93700829">llvm::BTFTypeBase::Kind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### completeType() {#acb492bbaefade0483054f80d31266472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFKindVar::completeType (<a href="/web-llvm/docs/api/classes/llvm/btfdebug">BTFDebug</a> &amp; BDebug)</td>
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

<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 408 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a49279d4bb54b6577992d301458c6512d">llvm::BTFDebug::addString</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a>.</p>

</div>
</div>

### emitType() {#a6063d7dad9aab202661760a53b2e3ae4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFKindVar::emitType (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
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


<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 412 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af00b13d92054d7b6f7c8b4561f46685b">llvm::BTFTypeBase::emitType</a>.</p>

</div>
</div>

### getSize() {#a87769309e75bca2cc39178c681dae612}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTFKindVar::getSize ()</td>
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

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a761afb51bc258152f71a07bfa2e9e2b7">llvm::BTFTypeBase::getSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Info {#ab4161ccbaf770888fdcba53e9dc410df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTFKindVar::Info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

### Name {#af1a9e26743ff60df87353f6ae65059e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::BTFKindVar::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

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
