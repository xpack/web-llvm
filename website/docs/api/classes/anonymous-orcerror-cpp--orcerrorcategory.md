---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-orcerror-cpp-/orcerrorcategory
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `OrcErrorCategory` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{OrcError.cpp}::OrcErrorCategory { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::error_category</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1a33e3f64922e5023b78134a4cc60eb">name</a> () const noexcept override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a732776a254369f8cb27f8b661854d94e">message</a> (int condition) const override</td>
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


<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcerror-cpp">OrcError.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### message() {#a732776a254369f8cb27f8b661854d94e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous{OrcError.cpp}::OrcErrorCategory::message (int condition)</td>
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



<p>Definition at line 30 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcerror-cpp">OrcError.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a3c7a3debdc594fa39ee86b3d4c5d3bea">llvm::orc::DuplicateDefinition</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9aaef2ea5850b12e7cddc1f4a55201e832">llvm::orc::JITSymbolNotFound</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9ab5ea62e5272ec6fc807c54b3d23b27d7">llvm::orc::MissingSymbolDefinitions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a1129a818c9d693ec0420ec0102f182a1">llvm::orc::RemoteAllocatorDoesNotExist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9ab86ba6d4a6eea12ea7cd33a379182d99">llvm::orc::RemoteAllocatorIdAlreadyInUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9aacda0870eae3bf8a988c31e8e2b99810">llvm::orc::RemoteIndirectStubsOwnerDoesNotExist</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9aea9d5333b542d9b799d2ef5cda4e1a3c">llvm::orc::RemoteIndirectStubsOwnerIdAlreadyInUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a7fc0ded8d4d5f06591033d64e7a71038">llvm::orc::RemoteMProtectAddrUnrecognized</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a1b5ed3737cd80e283f367fb58daeff01">llvm::orc::RPCConnectionClosed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a320b7102df8e58164bbc442019093227">llvm::orc::RPCCouldNotNegotiateFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9ab34a1bdc4a622d03ebcb86674dd011b4">llvm::orc::RPCResponseAbandoned</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9ae50a21d5a3fa1908cd75f253ce1d557b">llvm::orc::UnexpectedRPCCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a7aaf4df089b90dc6518982710f7ab1cc">llvm::orc::UnexpectedRPCResponse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9acc1dada5386d1d6091d1ebe9d02ef562">llvm::orc::UnexpectedSymbolDefinitions</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a5ff829bc3f475331da4e1e09d4b11fd7">llvm::orc::UnknownErrorCodeFromRemote</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9a9cdc93dde9ad70aa22e0c4ed2a096d8f">llvm::orc::UnknownORCError</a> and <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a2ac00a1daeb719e880429ee3a1a2cec9aa492b440879c3dcf5819ac4aac49ea2a">llvm::orc::UnknownResourceHandle</a>.</p>

</div>
</div>

### name() {#ac1a33e3f64922e5023b78134a4cc60eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * anonymous{OrcError.cpp}::OrcErrorCategory::name ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel noexcept">noexcept</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcerror-cpp">OrcError.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/lib/executionengine/orc/shared/orcerror-cpp">OrcError.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
