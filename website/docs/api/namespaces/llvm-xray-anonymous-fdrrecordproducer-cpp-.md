---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/xray/anonymous-fdrrecordproducer-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{FDRRecordProducer.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::xray::anonymous{FDRRecordProducer.cpp} { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MetadataRecordKinds : uint8_t { <a href="#a8d8729424e3a97e3cf5e424d657f47a2">...</a> }</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/xray/record">Record</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb0faf0b2173034ffd84646967053164">metadataRecordType</a> (const XRayFileHeader &amp;Header, uint8_t T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66e772e63664a0f50ebed0f1e2b5772a">isMetadataIntroducer</a> (uint8_t FirstByte)</td>
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

## Enumerations

### MetadataRecordKinds {#a8d8729424e3a97e3cf5e424d657f47a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::xray::anonymous{FDRRecordProducer.cpp}::MetadataRecordKinds : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NewBufferKind<a id="a8d8729424e3a97e3cf5e424d657f47a2ad6915c990eab89ac697239609d2681e0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfBufferKind<a id="a8d8729424e3a97e3cf5e424d657f47a2a09b4623558aea6918f2eae8d8dfbfc8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NewCPUIdKind<a id="a8d8729424e3a97e3cf5e424d657f47a2ae57b13a163b038f8fea0cdc4540f815d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TSCWrapKind<a id="a8d8729424e3a97e3cf5e424d657f47a2a97d6b707d068e544d74a7ac12f072c19"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WalltimeMarkerKind<a id="a8d8729424e3a97e3cf5e424d657f47a2a5838de9bb352b8a4d4a8395f429c6ed9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CustomEventMarkerKind<a id="a8d8729424e3a97e3cf5e424d657f47a2a17ea535932659e9af75617433da4586a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallArgumentKind<a id="a8d8729424e3a97e3cf5e424d657f47a2ab552fd655211ac5302aa5678bd3cf8e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BufferExtentsKind<a id="a8d8729424e3a97e3cf5e424d657f47a2a558bc1c058aeb618802d5dc29795fbd1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TypedEventMarkerKind<a id="a8d8729424e3a97e3cf5e424d657f47a2a9a3f9cab3392536494d16b0e067cee5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PidKind<a id="a8d8729424e3a97e3cf5e424d657f47a2a8ee33e1743b07b672aadc7f045560fa4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EnumEndMarker<a id="a8d8729424e3a97e3cf5e424d657f47a2a39ab437c8750f7c57d2313b5b2e4da1f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/fdrrecordproducer-cpp">FDRRecordProducer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### isMetadataIntroducer() {#a66e772e63664a0f50ebed0f1e2b5772a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::xray::anonymous{FDRRecordProducer.cpp}::isMetadataIntroducer (uint8_t FirstByte)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/fdrrecordproducer-cpp">FDRRecordProducer.cpp</a>.</p>


<p>Reference <a href="#a66e772e63664a0f50ebed0f1e2b5772a">isMetadataIntroducer</a>.</p>


<p>Referenced by <a href="#a66e772e63664a0f50ebed0f1e2b5772a">isMetadataIntroducer</a>.</p>

</div>
</div>

### metadataRecordType() {#aeb0faf0b2173034ffd84646967053164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; Record &gt; &gt; llvm::xray::anonymous{FDRRecordProducer.cpp}::metadataRecordType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/xray/xrayfileheader">XRayFileHeader</a> &amp; Header, uint8_t T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/xray/fdrrecordproducer-cpp">FDRRecordProducer.cpp</a>.</p>


<p>References <a href="#a8d8729424e3a97e3cf5e424d657f47a2a558bc1c058aeb618802d5dc29795fbd1">BufferExtentsKind</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2ab552fd655211ac5302aa5678bd3cf8e8">CallArgumentKind</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2a17ea535932659e9af75617433da4586a">CustomEventMarkerKind</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2a09b4623558aea6918f2eae8d8dfbfc8d">EndOfBufferKind</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2a39ab437c8750f7c57d2313b5b2e4da1f">EnumEndMarker</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#aeb0faf0b2173034ffd84646967053164">metadataRecordType</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2ad6915c990eab89ac697239609d2681e0">NewBufferKind</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2ae57b13a163b038f8fea0cdc4540f815d">NewCPUIdKind</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2a8ee33e1743b07b672aadc7f045560fa4">PidKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2a97d6b707d068e544d74a7ac12f072c19">TSCWrapKind</a>, <a href="#a8d8729424e3a97e3cf5e424d657f47a2a9a3f9cab3392536494d16b0e067cee5e">TypedEventMarkerKind</a> and <a href="#a8d8729424e3a97e3cf5e424d657f47a2a5838de9bb352b8a4d4a8395f429c6ed9">WalltimeMarkerKind</a>.</p>


<p>Referenced by <a href="#aeb0faf0b2173034ffd84646967053164">metadataRecordType</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/xray/fdrrecordproducer-cpp">FDRRecordProducer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
