---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/scalartraits-82dfc8fdcf1a7d905277eea83929c8be
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ScalarTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::ScalarTraits&lt;memprof::GUIDHex64&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">llvm/ProfileData/MemProfYAML.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995256070fdeb9a242e5170738c637a1">output</a> (const memprof::GUIDHex64 &amp;Val, void *, raw_ostream &amp;Out)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e0953b3d0f992087e7c16fd37e61437">input</a> (StringRef Scalar, void *, memprof::GUIDHex64 &amp;Val)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757">QuotingType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07efe3c848f6974a15d7004bc6341249">mustQuote</a> (StringRef)</td>
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


<p>Definition at line 29 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### input() {#a0e0953b3d0f992087e7c16fd37e61437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::ScalarTraits&lt; memprof::GUIDHex64 &gt;::input (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Scalar, void *, memprof::GUIDHex64 &amp; Val)</td>
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



<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0d10fe510ced2849a8074fe81e5d04ce">llvm::all_of</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/structs/llvm/memprof/indexedmemprofrecord/#ace5015b378d124a205da5a1eaf98061e">llvm::memprof::IndexedMemProfRecord::getGUID</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a388c981224806a01d8de4172d5322d3daf60357a8d17e45793298323f1b372a74">llvm::yaml::Scalar</a>.</p>

</div>
</div>

### mustQuote() {#a07efe3c848f6974a15d7004bc6341249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QuotingType llvm::yaml::ScalarTraits&lt; memprof::GUIDHex64 &gt;::mustQuote (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a>)</td>
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



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a2e9b09c50b4fff3bad8cba23daef8757a6adf97f83acf6453d4a6a4b1070f3754">llvm::yaml::None</a>.</p>

</div>
</div>

### output() {#a995256070fdeb9a242e5170738c637a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::ScalarTraits&lt; memprof::GUIDHex64 &gt;::output (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> memprof::GUIDHex64 &amp; Val, void *, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a939bc2108d47080767f0c06ba56caec7">llvm::format</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/memprofyaml-h">MemProfYAML.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
