---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/macho/textapireader
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TextAPIReader` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MachO::TextAPIReader { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapireader-h">llvm/TextAPI/TextAPIReader.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9de070f7f4202602ae7f2c874648dbd">TextAPIReader</a> ()=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7">FileType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91cc2902b5c82e2313c928a08a54597c">canRead</a> (MemoryBufferRef InputBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine whether input can be interpreted as TAPI text file. <a href="#a91cc2902b5c82e2313c928a08a54597c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae720a98705c6ad89165018117560dc47">get</a> (MemoryBufferRef InputBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse and get an <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> that represents the full library. <a href="#ae720a98705c6ad89165018117560dc47">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 23 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapireader-h">TextAPIReader.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextAPIReader() {#ae9de070f7f4202602ae7f2c874648dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MachO::TextAPIReader::TextAPIReader ()</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapireader-h">TextAPIReader.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### canRead() {#a91cc2902b5c82e2313c928a08a54597c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; FileType &gt; TextAPIReader::canRead (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> InputBuffer)</td>
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

<p>Determine whether input can be interpreted as TAPI text file.</p>


<p>This allows one to exit early when file is not recognized as TAPI file as opposed to <span class="doxyComputerOutput">get</span> which attempts to full parse and load of library attributes.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InputBuffer</td>
<td class="doxyParamItemDescription"><p>Buffer holding contents of TAPI text file.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The file format version of TAPI text file.</p></dd>
</dl>


<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapireader-h">TextAPIReader.h</a>, definition at line 1074 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7a50e1b7d3e1ed10d92235a499b0a0322a">llvm::MachO::TBD_V1</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7aca27acf08b2ba9723e508a1671c35f8b">llvm::MachO::TBD_V2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3b3aa8ad245f6b7318bebf085418816">llvm::MachO::TBD_V3</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7abeff4de6e3db063aac951727cf4d7c2b">llvm::MachO::TBD_V4</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3f7ae54a7045f6eb81648829a1167c3">llvm::MachO::TBD_V5</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#ab9990397f97b40d5d8564e000d00174a">llvm::StringRef::trim</a>.</p>


<p>Referenced by <a href="#ae720a98705c6ad89165018117560dc47">get</a>.</p>

</div>
</div>

### get() {#ae720a98705c6ad89165018117560dc47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; InterfaceFile &gt; &gt; TextAPIReader::get (<a href="/web-llvm/docs/api/classes/llvm/memorybufferref">MemoryBufferRef</a> InputBuffer)</td>
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

<p>Parse and get an <a href="/web-llvm/docs/api/classes/llvm/macho/interfacefile">InterfaceFile</a> that represents the full library.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">InputBuffer</td>
<td class="doxyParamItemDescription"><p>Buffer holding contents of TAPI text file.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapireader-h">TextAPIReader.h</a>, definition at line 1099 of file <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a>.</p>


<p>References <a href="#a91cc2902b5c82e2313c928a08a54597c">canRead</a>, <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp/#aa9f07add63589fb3b28821d089f069a7">DiagHandler</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/input/#aa353fb192bcd1d2e0561858ad440829b">llvm::yaml::Input::error</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a7301c8fd89ad0f595f4ce4609c872704">llvm::MemoryBufferRef::getBuffer</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybufferref/#a3201ce149cba3920fc965378ceddbcb8">llvm::MemoryBufferRef::getBufferIdentifier</a>, <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a87d247041800a391e58d7e42c6286219">llvm::MachO::getInterfaceFileFromJSON</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>, <a href="/web-llvm/docs/api/structs/llvm/macho/textapicontext/#a528a941dda5e4c476cb6aeb1a0341c84">llvm::MachO::TextAPIContext::Path</a> and <a href="/web-llvm/docs/api/namespaces/llvm/macho/#a11849daa1b55a8c00390b349546112e7ab3f7ae54a7045f6eb81648829a1167c3">llvm::MachO::TBD_V5</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/object/tapiuniversal/#a8b5913e2c0b8781f9db4cd57f0f1f922">llvm::object::TapiUniversal::TapiUniversal</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/textapi/textapireader-h">TextAPIReader.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/textapi/textstub-cpp">TextStub.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
