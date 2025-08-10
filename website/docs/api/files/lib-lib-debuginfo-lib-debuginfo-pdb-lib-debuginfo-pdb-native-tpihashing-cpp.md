---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# `TpiHashing.cpp` File



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/tpihashing-h">llvm/DebugInfo/PDB/Native/TpiHashing.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/codeview/typedeserializer-h">llvm/DebugInfo/CodeView/TypeDeserializer.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/pdb/include/llvm/debuginfo/pdb/native/hash-h">llvm/DebugInfo/PDB/Native/Hash.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/crc-h">llvm/Support/CRC.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af534c7154b2cde114629d65108069095">isAnonymous</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af90a30ef58dfd685ecb7f85db1fc7ed0">getHashForUdt</a> (const TagRecord &amp;Rec, ArrayRef&lt; uint8_t &gt; FullRecord)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a70d89e90b3449d03c7ca937d76fbdda0">getHashForUdt</a> (const CVType &amp;Rec) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af798249882e2b294e8eb95506cfce700">getTagRecordHashForUdt</a> (const CVType &amp;Rec) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/pdb/tagrecordhash">TagRecordHash</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa8fd1bec1979ec6fb2e1d7063569c620">getSourceLineHash</a> (const CVType &amp;Rec) -&gt; <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; uint32_t &gt;</td>
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

## Functions

### getHashForUdt() {#af90a30ef58dfd685ecb7f85db1fc7ed0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t getHashForUdt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/codeview/tagrecord">TagRecord</a> &amp; Rec, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint8_t &gt; FullRecord)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp">TpiHashing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa7e37f2aff533091462989c02c0cac8a1">llvm::codeview::ForwardReference</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/tagrecord/#a70d494508697280429a70e6b54e90564">llvm::codeview::TagRecord::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/tagrecord/#a1ae1be6e6d0d96125297733a3cfb222a">llvm::codeview::TagRecord::getOptions</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/tagrecord/#ab3ecf47bdb500f15d02088ae17279b8b">llvm::codeview::TagRecord::getUniqueName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a70e7a3749d35a58e1620b36a1a4183c1">llvm::pdb::hashBufferV8</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1737ab2b5a4c39b8eb3fcbd2e47abb65">llvm::pdb::hashStringV1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa1d847ff214177f9339928f7be873cd38">llvm::codeview::HasUniqueName</a>, <a href="#af534c7154b2cde114629d65108069095">isAnonymous</a> and <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa423f62fd0413b98ab4dd487ec060e628">llvm::codeview::Scoped</a>.</p>


<p>Referenced by <a href="#a70d89e90b3449d03c7ca937d76fbdda0">getHashForUdt</a>, <a href="#af798249882e2b294e8eb95506cfce700">getTagRecordHashForUdt</a> and <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a69bf231aca848ed614fb954ea4d65ff2">llvm::pdb::hashTypeRecord</a>.</p>

</div>
</div>

### getHashForUdt() {#a70d89e90b3449d03c7ca937d76fbdda0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; getHashForUdt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Rec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp">TpiHashing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aa5ac0ccd261c6bd6e07e1b288952fe33">llvm::codeview::CVRecord&lt; Kind &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="#af90a30ef58dfd685ecb7f85db1fc7ed0">getHashForUdt</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getSourceLineHash() {#aa8fd1bec1979ec6fb2e1d7063569c620}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; uint32_t &gt; getSourceLineHash (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Rec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp">TpiHashing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1737ab2b5a4c39b8eb3fcbd2e47abb65">llvm::pdb::hashStringV1</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a4f05956d010455624c13f5eb2217bc8b">llvm::support::endian::write32le</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a69bf231aca848ed614fb954ea4d65ff2">llvm::pdb::hashTypeRecord</a>.</p>

</div>
</div>

### getTagRecordHashForUdt() {#af798249882e2b294e8eb95506cfce700}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; TagRecordHash &gt; getTagRecordHashForUdt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a238eda31f74c0f0f3224f71b50b7d165">CVType</a> &amp; Rec)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp">TpiHashing.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/codeview/cvrecord/#aa5ac0ccd261c6bd6e07e1b288952fe33">llvm::codeview::CVRecord&lt; Kind &gt;::data</a>, <a href="/web-llvm/docs/api/classes/llvm/codeview/typedeserializer/#ad2afe9d87179bb184fd5f477db6e8509">llvm::codeview::TypeDeserializer::deserializeAs</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa7e37f2aff533091462989c02c0cac8a1">llvm::codeview::ForwardReference</a>, <a href="#af90a30ef58dfd685ecb7f85db1fc7ed0">getHashForUdt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#a1737ab2b5a4c39b8eb3fcbd2e47abb65">llvm::pdb::hashStringV1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codeview/#a4e60e0c351f13aade28b451480c44e5aa423f62fd0413b98ab4dd487ec060e628">llvm::codeview::Scoped</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/pdb/#ac4ae17008fa3248cf4065352bdf7e029">llvm::pdb::hashTagRecord</a>.</p>

</div>
</div>

### isAnonymous() {#af534c7154b2cde114629d65108069095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAnonymous (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/pdb/lib/debuginfo/pdb/native/tpihashing-cpp">TpiHashing.cpp</a>.</p>


<p>Referenced by <a href="#af90a30ef58dfd685ecb7f85db1fc7ed0">getHashForUdt</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
