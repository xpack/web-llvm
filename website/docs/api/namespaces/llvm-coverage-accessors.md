---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/coverage/accessors
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `accessors` Namespace Reference

<p>This namespace defines accessors shared by different versions of coverage mapping records. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::coverage::accessors { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae52b19d4c976e143b7a6d3d2f7d029a3">getFuncHash</a> (const FuncRecordTy *Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the structural hash associated with the function. <a href="#ae52b19d4c976e143b7a6d3d2f7d029a3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a91db0b9fe0c605dd32a2e7b96929c25e">getDataSize</a> (const FuncRecordTy *Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the coverage map data size for the function. <a href="#a91db0b9fe0c605dd32a2e7b96929c25e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1de033f4f2e853a4bc81cd3079e72419">getFuncNameRef</a> (const FuncRecordTy *Record)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the function lookup key. The value is considered opaque. <a href="#a1de033f4f2e853a4bc81cd3079e72419">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab6161a32808a77777e006ca358dac0b2">getFuncNameViaRef</a> (const FuncRecordTy *Record, InstrProfSymtab &amp;ProfileNames, StringRef &amp;FuncName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the PGO name of the function. <a href="#ab6161a32808a77777e006ca358dac0b2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d48afd0873f94aa71c31eca795a3cbd">getCoverageMappingOutOfLine</a> (const FuncRecordTy *Record, const char *MappingBuf)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Read coverage mapping out-of-line, from <span class="doxyComputerOutput">MappingBuf</span>. <a href="#a8d48afd0873f94aa71c31eca795a3cbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">auto </td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acd13adc5d04d1d7ce3c82b88f7f8ae60">advanceByOneOutOfLine</a> (const FuncRecordTy *Record, const char *MappingBuf) -&gt; std::pair&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordTy * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advance to the next out-of-line coverage mapping and its associated function record. <a href="#acd13adc5d04d1d7ce3c82b88f7f8ae60">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This namespace defines accessors shared by different versions of coverage mapping records.</p>

<div class="doxySectionDef">

## Functions

### advanceByOneOutOfLine() {#acd13adc5d04d1d7ce3c82b88f7f8ae60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; const char *, const FuncRecordTy * &gt; llvm::coverage::accessors::advanceByOneOutOfLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordTy * Record, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * MappingBuf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Advance to the next out-of-line coverage mapping and its associated function record.</p>

<p>Definition at line 1236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="#a91db0b9fe0c605dd32a2e7b96929c25e">getDataSize</a>.</p>

</div>
</div>

### getCoverageMappingOutOfLine() {#a8d48afd0873f94aa71c31eca795a3cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::coverage::accessors::getCoverageMappingOutOfLine (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordTy * Record, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * MappingBuf)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Read coverage mapping out-of-line, from <span class="doxyComputerOutput">MappingBuf</span>.</p>


<p>This is used when the coverage mapping is attached to the file header, instead of to the function record.</p>


<p>Definition at line 1227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="#a91db0b9fe0c605dd32a2e7b96929c25e">getDataSize</a>.</p>

</div>
</div>

### getDataSize() {#a91db0b9fe0c605dd32a2e7b96929c25e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::accessors::getDataSize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordTy * Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the coverage map data size for the function.</p>

<p>Definition at line 1203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>.</p>


<p>Referenced by <a href="#acd13adc5d04d1d7ce3c82b88f7f8ae60">advanceByOneOutOfLine</a> and <a href="#a8d48afd0873f94aa71c31eca795a3cbd">getCoverageMappingOutOfLine</a>.</p>

</div>
</div>

### getFuncHash() {#ae52b19d4c976e143b7a6d3d2f7d029a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::accessors::getFuncHash (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordTy * Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the structural hash associated with the function.</p>

<p>Definition at line 1197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>.</p>

</div>
</div>

### getFuncNameRef() {#a1de033f4f2e853a4bc81cd3079e72419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::coverage::accessors::getFuncNameRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordTy * Record)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the function lookup key. The value is considered opaque.</p>

<p>Definition at line 1209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/support/endian/#a108ca68c609b3e8c00918a68d26905fa">llvm::support::endian::byte_swap</a>.</p>


<p>Referenced by <a href="#ab6161a32808a77777e006ca358dac0b2">getFuncNameViaRef</a>.</p>

</div>
</div>

### getFuncNameViaRef() {#ab6161a32808a77777e006ca358dac0b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class FuncRecordTy, llvm::endianness Endian&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::coverage::accessors::getFuncNameViaRef (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> FuncRecordTy * Record, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab">InstrProfSymtab</a> &amp; ProfileNames, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &amp; FuncName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the PGO name of the function.</p>


<p>Used for formats in which the name is a hash.</p>


<p>Definition at line 1216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<p>References <a href="#a1de033f4f2e853a4bc81cd3079e72419">getFuncNameRef</a>, <a href="/web-llvm/docs/api/classes/llvm/instrprofsymtab/#a4368b520bb5883d23d6c2c59bf129b5a">llvm::InstrProfSymtab::getFuncOrVarName</a> and <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
