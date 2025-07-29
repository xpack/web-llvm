---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/textapiwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TextAPIWriter` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::TextAPIWriter { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapiwriter-h">llvm/TextAPI/TextAPIWriter.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4413b74028f8abc4aabbeced753627a">TextAPIWriter</a> ()=delete</td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c38bdeed4b96c01ab6e3f3368998030">writeToStream</a> (raw_ostream &amp;OS, const InterfaceFile &amp;File, const FileType FileKind=FileType::Invalid, bool Compact=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Write TAPI text file contents into stream. <a href="#a8c38bdeed4b96c01ab6e3f3368998030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afb9c049d0f17fe4036dbe6654d4ea2">parseFileType</a> (const StringRef FT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get TAPI <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a> from the input string. <a href="#a9afb9c049d0f17fe4036dbe6654d4ea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapiwriter-h">TextAPIWriter.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextAPIWriter() {#ac4413b74028f8abc4aabbeced753627a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::TextAPIWriter::TextAPIWriter ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapiwriter-h">TextAPIWriter.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">llvm::MachO::Invalid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### parseFileType() {#a9afb9c049d0f17fe4036dbe6654d4ea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileType llvm::MachO::TextAPIWriter::parseFileType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FT)</td>
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

<p>Get TAPI <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a> from the input string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FT</td>
<td class="doxyParamItemDescription"><p>String of input to map to <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a>.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapiwriter-h">TextAPIWriter.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a3de12858bdbbd0b3da179d508ff2be75">llvm::StringSwitch&lt; T, R &gt;::Case</a>, <a href="/web-llvm/docs/api/classes/llvm/stringswitch/#a7f0e82e8a818ca43926fceb49be81661">llvm::StringSwitch&lt; T, R &gt;::Default</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">llvm::MachO::Invalid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a50e1b7d3e1ed10d92235a499b0a0322a">llvm::MachO::TBD_V1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7aca27acf08b2ba9723e508a1671c35f8b">llvm::MachO::TBD_V2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3b3aa8ad245f6b7318bebf085418816">llvm::MachO::TBD_V3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7abeff4de6e3db063aac951727cf4d7c2b">llvm::MachO::TBD_V4</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3f7ae54a7045f6eb81648829a1167c3">llvm::MachO::TBD_V5</a>.</p>

</div>
</div>

### writeToStream() {#a8c38bdeed4b96c01ab6e3f3368998030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error TextAPIWriter::writeToStream (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &amp; File, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a> FileKind=<a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">FileType::Invalid</a>, bool Compact=false)</td>
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

<p>Write TAPI text file contents into stream.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">OS</td>
<td class="doxyParamItemDescription"><p>Stream to write to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">File</td>
<td class="doxyParamItemDescription"><p>Library attributes to write as text file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">FileKind</td>
<td class="doxyParamItemDescription"><p>File format to write text file as. If not specified, it will read from File.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Compact</td>
<td class="doxyParamItemDescription"><p>Whether to limit whitespace in text file.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapiwriter-h">TextAPIWriter.h</a>, definition at line 1137 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a48d53340ae80e1c1862548611e92c864">llvm::MachO::Invalid</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/textapicontext/#a528a941dda5e4c476cb6aeb1a0341c84">llvm::MachO::TextAPIContext::Path</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a3ff667d4f1513749fb128a62577a9b21">llvm::MachO::serializeInterfaceFileToJSON</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3f7ae54a7045f6eb81648829a1167c3">llvm::MachO::TBD_V5</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapiwriter-h">TextAPIWriter.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
