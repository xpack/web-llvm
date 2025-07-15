---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gsym/objectfiletransformer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ObjectFileTransformer` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::gsym::ObjectFileTransformer { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/objectfiletransformer-h">llvm/DebugInfo/GSYM/ObjectFileTransformer.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9940b2d9a5f2a7de1dcfcdb970bf5e51">convert</a> (const object::ObjectFile &amp;Obj, OutputAggregator &amp;Output, GsymCreator &amp;Gsym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Extract any object file data that is needed by the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>. <a href="#a9940b2d9a5f2a7de1dcfcdb970bf5e51">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/objectfiletransformer-h">ObjectFileTransformer.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### convert() {#a9940b2d9a5f2a7de1dcfcdb970bf5e51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Error ObjectFileTransformer::convert (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/object/objectfile">object::ObjectFile</a> &amp; Obj, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator">OutputAggregator</a> &amp; Output, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a> &amp; Gsym)</td>
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

<p>Extract any object file data that is needed by the <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator">GsymCreator</a>.</p>


<p>The extracted information includes the <a href="/web-llvm/docs/api/files/lib/lib/textapi/textstubcommon-h/#a847f9d797fd06f1d451476d6362a6a41">UUID</a> of the binary and converting all function symbols from any symbol tables into <a href="/web-llvm/docs/api/structs/llvm/gsym/functioninfo">FunctionInfo</a> objects.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">Obj</td>
<td class="doxyParamItemDescription"><p>The object file that contains the DWARF debug info.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Log</td>
<td class="doxyParamItemDescription"><p>The stream to log warnings and non fatal issues to. If NULL, don't log.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">Gsym</td>
<td class="doxyParamItemDescription"><p>The GSYM creator to populate with the function information from the debug info.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An error indicating any fatal issues that happen when parsing the DWARF, or <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">Error::success()</a> if all goes well.</p></dd>
</dl>


<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/objectfiletransformer-h">ObjectFileTransformer.h</a>, definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp">ObjectFileTransformer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a0255c904a2083824db32c67a98520742">llvm::gsym::GsymCreator::addFunctionInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="/web-llvm/docs/api/classes/llvm/expected/#ad26ecbb6920f4ea55f5ed4f64e52342d">llvm::Expected&lt; T &gt;::get</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#adebfdaa4b1b4fa505e9b9b8b91693704">llvm::gsym::GsymCreator::getNumFunctionInfos</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/outputaggregator/#ac1be2c7a42ac407e8eac9396768207dc">llvm::gsym::OutputAggregator::GetOS</a>, <a href="/web-llvm/docs/api/classes/llvm/object/elfsymbolref/#a8549874db03a19df5cb846d78eddf383">llvm::object::ELFSymbolRef::getSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp/#a675f0690b04eaa2c63f91d8e05c75106">getUUID</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#a22638e32cb1220ddfacd7eb1bc5dfcf5">llvm::gsym::GsymCreator::insertString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#aed7eb12c998221cb39a6a3d96e9a0e56">llvm::gsym::GsymCreator::IsValidTextAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a065ed35b75b9eeb5cca1aa73bcae7183">llvm::logAllUnhandledErrors</a>, <a href="/web-llvm/docs/api/classes/llvm/gsym/gsymcreator/#ab85ea74b3cb2aeabcf765b1892ff9d91">llvm::gsym::GsymCreator::setUUID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a10f3d955592ae2bc745f57e5b48ae115">llvm::size</a>, <a href="/web-llvm/docs/api/classes/llvm/object/symbolref/#a2ea2ecb4f81936cc379aff129e440b04a2fcf5b0171fb8526218be425765b5da1">llvm::object::SymbolRef::ST_Function</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/classes/llvm/object/objectfile/#aa22a9825f4937b28269552f5b8db4a69">llvm::object::ObjectFile::symbols</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/debuginfo/include/llvm/debuginfo/gsym/objectfiletransformer-h">ObjectFileTransformer.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/gsym/objectfiletransformer-cpp">ObjectFileTransformer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
