---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/btfkinddatasec
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BTFKindDataSec` Class Reference

<p>Handle data sections. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BTFKindDataSec { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a870def4ca867756cff187bdb769e63ab">BTFKindDataSec</a> (AsmPrinter *AsmPrt, std::string SecName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b62f47699939b78cee6424833d6524">getSize</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#aa9b62f47699939b78cee6424833d6524">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a830e2589b35081531b0091b3024125a3">addDataSecEntry</a> (uint32_t Id, const MCSymbol *Sym, uint32_t Size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32e8a0836c4aa7b30a2af1335946950">getName</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43ab4cf2d2a062e925abe185ca028c21">completeType</a> (BTFDebug &amp;BDebug) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Complete <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type generation after all related DebugInfo types have been visited so their <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type id's are available for cross referece. <a href="#a43ab4cf2d2a062e925abe185ca028c21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41b5cfee68732eaed66ef41d9d1a7884">emitType</a> (MCStreamer &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit types for this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#a41b5cfee68732eaed66ef41d9d1a7884">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bebe12b7c6cab48aefce9bb595011df">Asm</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89db2690cfcd11c8ae6a02199d27f3f5">Name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::tuple&lt; uint32_t, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *, uint32_t &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade48fa10a5df34434abd1d196b3ede13">Vars</a></td>
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

<p>Handle data sections.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BTFKindDataSec() {#a870def4ca867756cff187bdb769e63ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BTFKindDataSec::BTFKindDataSec (<a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> * AsmPrt, std::string SecName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 417 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a0cebeba190cfb4a6959a5aab93700829">llvm::BTFTypeBase::Kind</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDataSecEntry() {#a830e2589b35081531b0091b3024125a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::BTFKindDataSec::addDataSecEntry (uint32_t Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Sym, uint32_t Size)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#ad14737e420354b4c281c2c467f18d7f6">llvm::BTFTypeBase::Id</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### completeType() {#a43ab4cf2d2a062e925abe185ca028c21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFKindDataSec::completeType (<a href="/web-llvm/docs/api/classes/llvm/btfdebug">BTFDebug</a> &amp; BDebug)</td>
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

<p>Declaration at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 424 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a49279d4bb54b6577992d301458c6512d">llvm::BTFDebug::addString</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a>.</p>

</div>
</div>

### emitType() {#a41b5cfee68732eaed66ef41d9d1a7884}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFKindDataSec::emitType (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
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


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 429 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af00b13d92054d7b6f7c8b4561f46685b">llvm::BTFTypeBase::emitType</a>.</p>

</div>
</div>

### getName() {#ab32e8a0836c4aa7b30a2af1335946950}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::BTFKindDataSec::getName ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

### getSize() {#aa9b62f47699939b78cee6424833d6524}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTFKindDataSec::getSize ()</td>
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

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/btf/#ac469d636ea54a1eb9da4c1f633a4496cacab2d7bfdf05721a0926f1720349c48c">llvm::BTF::BTFDataSecVarSize</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a761afb51bc258152f71a07bfa2e9e2b7">llvm::BTFTypeBase::getSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Asm {#a0bebe12b7c6cab48aefce9bb595011df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsmPrinter* llvm::BTFKindDataSec::Asm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

### Name {#a89db2690cfcd11c8ae6a02199d27f3f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::BTFKindDataSec::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

### Vars {#ade48fa10a5df34434abd1d196b3ede13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::tuple&lt;uint32_t, const MCSymbol *, uint32_t&gt; &gt; llvm::BTFKindDataSec::Vars</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

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
