---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/btftypeenum64
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BTFTypeEnum64` Class Reference

<p>Handle 64-bit enumerate type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BTFTypeEnum64 { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61c4802e13f50a1aa650f80be13ea05b">BTFTypeEnum64</a> (const DICompositeType *ETy, uint32_t NumValues, bool IsSigned)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0899edee9843906cf78081c84f8c1817">getSize</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the size of this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#a0899edee9843906cf78081c84f8c1817">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a66e96c6d116c0673d0cf1486fd418f">completeType</a> (BTFDebug &amp;BDebug) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Complete <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type generation after all related DebugInfo types have been visited so their <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type id's are available for cross referece. <a href="#a3a66e96c6d116c0673d0cf1486fd418f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeeff33f4503f3e3724197047123252d1">emitType</a> (MCStreamer &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit types for this <a href="/web-llvm/docs/api/namespaces/llvm/btf">BTF</a> type entry. <a href="#aeeff33f4503f3e3724197047123252d1">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabe37bf637b113adef9363eda953ae5a">ETy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; struct <a href="/web-llvm/docs/api/structs/llvm/btf/btfenum64">BTF::BTFEnum64</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2c2219d4e3ad2deb9682c1c541746f">EnumValues</a></td>
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

<p>Handle 64-bit enumerate type.</p>

<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BTFTypeEnum64() {#a61c4802e13f50a1aa650f80be13ea05b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BTFTypeEnum64::BTFTypeEnum64 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/dicompositetype">DICompositeType</a> * ETy, uint32_t NumValues, bool IsSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a0cebeba190cfb4a6959a5aab93700829">llvm::BTFTypeBase::Kind</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af531da13c9fd67de1bfbf782eb04b7c7">llvm::BTFTypeBase::roundupToBytes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### completeType() {#a3a66e96c6d116c0673d0cf1486fd418f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFTypeEnum64::completeType (<a href="/web-llvm/docs/api/classes/llvm/btfdebug">BTFDebug</a> &amp; BDebug)</td>
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

<p>Declaration at line 231 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/btfdebug/#a49279d4bb54b6577992d301458c6512d">llvm::BTFDebug::addString</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a5f85d1b9106ebceb66b457049ba1f666">llvm::BTFTypeBase::BTFType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a9d62bd0b4b094cf0f35d47cc024ed1bf">llvm::BTFTypeBase::IsCompleted</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/btfenum64/#a164fa1bd400af420941a9ff1d7498ae0">llvm::BTF::BTFEnum64::NameOff</a>, <a href="/web-llvm/docs/api/structs/llvm/btf/btfenum64/#a19618460d15c5c385326972c6dcf0178">llvm::BTF::BTFEnum64::Val_Hi32</a> and <a href="/web-llvm/docs/api/structs/llvm/btf/btfenum64/#a35f4d3b5a3aa055eaeb1a183e3296d01">llvm::BTF::BTFEnum64::Val_Lo32</a>.</p>

</div>
</div>

### emitType() {#aeeff33f4503f3e3724197047123252d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void BTFTypeEnum64::emitType (<a href="/web-llvm/docs/api/classes/llvm/mcstreamer">MCStreamer</a> &amp; OS)</td>
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


<p>Declaration at line 232 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>, definition at line 247 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-cpp">BTFDebug.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#a64eafd6bed9f342e423e74a93223135c">llvm::MCStreamer::AddComment</a>, <a href="/web-llvm/docs/api/classes/llvm/mcstreamer/#acc3817979bc871dba942b87773da1cc0">llvm::MCStreamer::emitInt32</a>, <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#af00b13d92054d7b6f7c8b4561f46685b">llvm::BTFTypeBase::emitType</a> and <a href="/web-llvm/docs/api/classes/llvm/twine/#acaa1b3e2d07a6c9d2d7030c7dc7ec6a7">llvm::Twine::utohexstr</a>.</p>

</div>
</div>

### getSize() {#a0899edee9843906cf78081c84f8c1817}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t llvm::BTFTypeEnum64::getSize ()</td>
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

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/btf/#ac469d636ea54a1eb9da4c1f633a4496ca0c9f8e5e4ae813fac59083717851ce07">llvm::BTF::BTFEnum64Size</a> and <a href="/web-llvm/docs/api/classes/llvm/btftypebase/#a761afb51bc258152f71a07bfa2e9e2b7">llvm::BTFTypeBase::getSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EnumValues {#a8f2c2219d4e3ad2deb9682c1c541746f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;struct BTF::BTFEnum64&gt; llvm::BTFTypeEnum64::EnumValues</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

</div>
</div>

### ETy {#aabe37bf637b113adef9363eda953ae5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DICompositeType* llvm::BTFTypeEnum64::ETy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/btfdebug-h">BTFDebug.h</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
