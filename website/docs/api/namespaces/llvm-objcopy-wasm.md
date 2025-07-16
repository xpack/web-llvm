---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/objcopy/wasm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `wasm` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::objcopy::wasm { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object">Object</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader">Reader</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/writer">Writer</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5bbb8d6140f5e75d6f431344571c49">SectionPred</a> = std::function&lt; bool(<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> &amp;Sec)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6098aac8d9341369e7479af43f3d1c2">executeObjcopyOnBinary</a> (const CommonConfig &amp;Config, const WasmConfig &amp;, object::WasmObjectFile &amp;In, raw_ostream &amp;Out)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Apply the transformations described by <span class="doxyComputerOutput">Config</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/objcopy/wasmconfig">WasmConfig</a></span> to <span class="doxyComputerOutput">In</span> and writes the result into <span class="doxyComputerOutput">Out</span>. <a href="#ae6098aac8d9341369e7479af43f3d1c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dba745db7f48a6b368292275bf556c8">isDebugSection</a> (const Section &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad82fa2803c170f1ec4d650cf675ac11e">isLinkerSection</a> (const Section &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c7c565e25c8198f7dd825a62574961">isNameSection</a> (const Section &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08369588257f45ac9b845eda6e4352b3">isCommentSection</a> (const Section &amp;Sec)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4c167a5e231ccb60ec1eb5552ca233b">dumpSectionToFile</a> (StringRef SecName, StringRef Filename, StringRef InputFilename, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a128c16fdb808e0e243d89ae57ed3717d">removeSections</a> (const CommonConfig &amp;Config, Object &amp;Obj)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42dbc5cc7c04f8d8738edf9699d75654">handleArgs</a> (const CommonConfig &amp;Config, Object &amp;Obj)</td>
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

## Typedefs

### SectionPred {#aef5bbb8d6140f5e75d6f431344571c49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::objcopy::wasm::SectionPred =  std::function&lt;bool(const Section &amp;Sec)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### dumpSectionToFile() {#ab4c167a5e231ccb60ec1eb5552ca233b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::wasm::dumpSectionToFile (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> SecName, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Filename, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InputFilename, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#a5b75640e3f42d0e0b592221f25ef0b66">llvm::objcopy::wasm::Section::Contents</a>, <a href="/web-llvm/docs/api/classes/llvm/fileoutputbuffer/#a3a10ce8cad8fee5d6a4c55270866aa05">llvm::FileOutputBuffer::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a7ca5197533a9c1fb8a2bd30587fcec6b">llvm::ArrayRef&lt; T &gt;::end</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/main-cpp/#aaa0fa37480ba9aa590065846d7ccb1d2">InputFilename</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59739a4f15fb2ec57a6b7fcfe938546bae55d43eabeefe5a8271b4a3c898bd18f">llvm::invalid_argument</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#aec9545d1fbb019d82321902c588dbe75">llvm::objcopy::wasm::Section::Name</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object/#a16c713d625e7e58397151ee1b7b25c11">llvm::objcopy::wasm::Object::Sections</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a223dd14e7d12bc5cea01889b972a98b2">llvm::StringRef::str</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>


<p>Referenced by <a href="#a42dbc5cc7c04f8d8738edf9699d75654">handleArgs</a>.</p>

</div>
</div>

### executeObjcopyOnBinary() {#ae6098aac8d9341369e7479af43f3d1c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::wasm::executeObjcopyOnBinary (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasmconfig">WasmConfig</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/object/wasmobjectfile">object::WasmObjectFile</a> &amp; In, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; Out)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Apply the transformations described by <span class="doxyComputerOutput">Config</span> and <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/structs/llvm/objcopy/wasmconfig">WasmConfig</a></span> to <span class="doxyComputerOutput">In</span> and writes the result into <span class="doxyComputerOutput">Out</span>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>any <a href="/web-llvm/docs/api/classes/llvm/error">Error</a> encountered whilst performing the operation.</p></dd>
</dl>


<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/reader/#a51514a556b4bbc63df0eabeec60c031f">llvm::objcopy::wasm::Reader::create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0f4ffaa2f15fc8f612a233e3b45510c0">llvm::createFileError</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="#a42dbc5cc7c04f8d8738edf9699d75654">handleArgs</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a24e1ca7d92cbc2a42152ac37dbc0e7ad">llvm::objcopy::CommonConfig::InputFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a8a04952cef062450e2bd671d5e4b3c0c">llvm::objcopy::CommonConfig::OutputFilename</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a> and <a href="/web-llvm/docs/api/classes/llvm/objcopy/wasm/writer/#a0c6b0217a29520ff740cb32952eac94f">llvm::objcopy::wasm::Writer::write</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/objcopy/#af45b538ed42f9864350e9c38c168333e">llvm::objcopy::executeObjcopyOnBinary</a>.</p>

</div>
</div>

### handleArgs() {#a42dbc5cc7c04f8d8738edf9699d75654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error llvm::objcopy::wasm::handleArgs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a935828d3516e07952f9982eedb0af62f">llvm::objcopy::CommonConfig::AddSection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object/#ae8b896e0f60be77a397633e4bbeee362">llvm::objcopy::wasm::Object::addSectionWithOwnedContents</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#a5b75640e3f42d0e0b592221f25ef0b66">llvm::objcopy::wasm::Section::Contents</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a42cc07e96293a65eb61cf4ce8a489b41">llvm::objcopy::CommonConfig::DumpSection</a>, <a href="#ab4c167a5e231ccb60ec1eb5552ca233b">dumpSectionToFile</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#a32d2c9ba9019e6e41605c60acd06bd09">llvm::MemoryBuffer::getMemBufferCopy</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a24e1ca7d92cbc2a42152ac37dbc0e7ad">llvm::objcopy::CommonConfig::InputFilename</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#aec9545d1fbb019d82321902c588dbe75">llvm::objcopy::wasm::Section::Name</a>, <a href="#a128c16fdb808e0e243d89ae57ed3717d">removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a641257caac84236fba46e30aa91f6c7a">llvm::objcopy::NewSectionInfo::SectionData</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/newsectioninfo/#a05c34cfa6560e1e8b1aa9a540d5505e3">llvm::objcopy::NewSectionInfo::SectionName</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#a0f6248ef8ae89023e9b794f67f618fd3">llvm::objcopy::wasm::Section::SectionType</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/namespaces/llvm/wasm/#a5223078a36e47d8683316af75b2f33aaa685069a810d109e09f4af7d2d115a8cd">llvm::wasm::WASM_SEC_CUSTOM</a>.</p>


<p>Referenced by <a href="#ae6098aac8d9341369e7479af43f3d1c2">executeObjcopyOnBinary</a>.</p>

</div>
</div>

### isCommentSection() {#a08369588257f45ac9b845eda6e4352b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::wasm::isCommentSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> &amp; Sec)</td>
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



<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#aec9545d1fbb019d82321902c588dbe75">llvm::objcopy::wasm::Section::Name</a>.</p>


<p>Referenced by <a href="#a128c16fdb808e0e243d89ae57ed3717d">removeSections</a>.</p>

</div>
</div>

### isDebugSection() {#a4dba745db7f48a6b368292275bf556c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::wasm::isDebugSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> &amp; Sec)</td>
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



<p>Definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#aec9545d1fbb019d82321902c588dbe75">llvm::objcopy::wasm::Section::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a128c16fdb808e0e243d89ae57ed3717d">removeSections</a>.</p>

</div>
</div>

### isLinkerSection() {#ad82fa2803c170f1ec4d650cf675ac11e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::wasm::isLinkerSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> &amp; Sec)</td>
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



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#aec9545d1fbb019d82321902c588dbe75">llvm::objcopy::wasm::Section::Name</a> and <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2cd8968ff703aaeb395dcd63f6805ff1">llvm::StringRef::starts_with</a>.</p>


<p>Referenced by <a href="#a128c16fdb808e0e243d89ae57ed3717d">removeSections</a>.</p>

</div>
</div>

### isNameSection() {#ac3c7c565e25c8198f7dd825a62574961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::objcopy::wasm::isNameSection (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section">Section</a> &amp; Sec)</td>
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



<p>Definition at line 32 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/section/#aec9545d1fbb019d82321902c588dbe75">llvm::objcopy::wasm::Section::Name</a>.</p>


<p>Referenced by <a href="#a128c16fdb808e0e243d89ae57ed3717d">removeSections</a>.</p>

</div>
</div>

### removeSections() {#a128c16fdb808e0e243d89ae57ed3717d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::objcopy::wasm::removeSections (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig">CommonConfig</a> &amp; Config, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object">Object</a> &amp; Obj)</td>
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



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#ae37fd1e51553e31998f280b07d853e77">llvm::objcopy::NameMatcher::empty</a>, <a href="#a08369588257f45ac9b845eda6e4352b3">isCommentSection</a>, <a href="#a4dba745db7f48a6b368292275bf556c8">isDebugSection</a>, <a href="#ad82fa2803c170f1ec4d650cf675ac11e">isLinkerSection</a>, <a href="#ac3c7c565e25c8198f7dd825a62574961">isNameSection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abebf9b7925c5e3587702549e836500ff">llvm::objcopy::CommonConfig::KeepSection</a>, <a href="/web-llvm/docs/api/classes/llvm/objcopy/namematcher/#a8fe6d6e80304c85e35c03066ae1bcfa9">llvm::objcopy::NameMatcher::matches</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a44946f210492495ee1add2b497ddc31a">llvm::objcopy::CommonConfig::OnlyKeepDebug</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#aba256fcc9763c4d144e805e67f6790f9">llvm::objcopy::CommonConfig::OnlySection</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/wasm/object/#af9ff1730158f82c9b5c99b3947740404">llvm::objcopy::wasm::Object::removeSections</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#a9d5713c258905f31b34b13b07086b7c7">llvm::objcopy::CommonConfig::StripAll</a>, <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#abadfb5107f778ad8d81df7893db2c25e">llvm::objcopy::CommonConfig::StripDebug</a> and <a href="/web-llvm/docs/api/structs/llvm/objcopy/commonconfig/#addbcdc27b0e6e19fba3ec20ef5de05d9">llvm::objcopy::CommonConfig::ToRemove</a>.</p>


<p>Referenced by <a href="#a42dbc5cc7c04f8d8738edf9699d75654">handleArgs</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/objcopy/lib/objcopy/wasm/wasmobjcopy-cpp">WasmObjcopy.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
