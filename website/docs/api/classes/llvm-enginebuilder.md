---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/enginebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `EngineBuilder` Class Reference

<p>Builder class for ExecutionEngines. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::EngineBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">llvm/ExecutionEngine/ExecutionEngine.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor for <a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a>. <a href="#a20f12106f0142f5114fdfdef7bb45551">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a942eae70b5e6253100a4aa1ad843128a">EngineBuilder</a> (std::unique_ptr&lt; Module &gt; M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructor for <a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a>. <a href="#a942eae70b5e6253100a4aa1ad843128a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635a47f960dc06371007c276ca1de032">~EngineBuilder</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a960c0e2e27d0ccef2db82f261a475ef9">setEngineKind</a> (EngineKind::Kind w)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setEngineKind - Controls whether the user wants the interpreter, the JIT, or whichever engine works. <a href="#a960c0e2e27d0ccef2db82f261a475ef9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158be06e8bc0c3e9caafba69adadaaa4">setMCJITMemoryManager</a> (std::unique_ptr&lt; RTDyldMemoryManager &gt; mcjmm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setMCJITMemoryManager - Sets the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> memory manager to use. <a href="#a158be06e8bc0c3e9caafba69adadaaa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab08bd10157c574607b371f6ffc3bf78">setMemoryManager</a> (std::unique_ptr&lt; MCJITMemoryManager &gt; MM)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a498e29ffd7de3d329887c9a5fabc1ca8">setSymbolResolver</a> (std::unique_ptr&lt; LegacyJITSymbolResolver &gt; SR)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8537e02128a9b4bd244dcb08f0da1fbe">setErrorStr</a> (std::string *e)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setErrorStr - Set the error string to write to on error. <a href="#a8537e02128a9b4bd244dcb08f0da1fbe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4908930f1022471c7a7f366c94b52032">setOptLevel</a> (CodeGenOptLevel l)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setOptLevel - Set the optimization level for the JIT. <a href="#a4908930f1022471c7a7f366c94b52032">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08c232e2416c85bdc2e479bb8f77448f">setTargetOptions</a> (const TargetOptions &amp;Opts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setTargetOptions - Set the target options that the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> target is using. <a href="#a08c232e2416c85bdc2e479bb8f77448f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab19c764bd44bf595803472ef2c3123f3">setRelocationModel</a> (Reloc::Model RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setRelocationModel - Set the relocation model that the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> target is using. <a href="#ab19c764bd44bf595803472ef2c3123f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a387f51a24c0f1df5c0337ba630eb8f54">setCodeModel</a> (CodeModel::Model M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setCodeModel - Set the <a href="/web-llvm/docs/api/namespaces/llvm/codemodel">CodeModel</a> that the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> target data is using. <a href="#a387f51a24c0f1df5c0337ba630eb8f54">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b972eb34932750dfec21f44f358398">setMArch</a> (StringRef march)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setMArch - Override the architecture set by the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s triple. <a href="#a33b972eb34932750dfec21f44f358398">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb3f9f8b01e92ccf434c556cdb5afd0">setMCPU</a> (StringRef mcpu)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setMCPU - <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> a specific cpu type. <a href="#abeb3f9f8b01e92ccf434c556cdb5afd0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892d551cc875d9149c447f10caea9656">setVerifyModules</a> (bool Verify)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setVerifyModules - Set whether the JIT implementation should verify IR modules during compilation. <a href="#a892d551cc875d9149c447f10caea9656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename StringSequence&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aba74129a5e5ff15f51a03f318bfe2497">setMAttrs</a> (const StringSequence &amp;mattrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>setMAttrs - Set cpu-specific attributes. <a href="#aba74129a5e5ff15f51a03f318bfe2497">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab94775bd138477154f0839cd8ab93a9a">setEmulatedTLS</a> (bool EmulatedTLS)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69bf35545691487248c1a1d0bd45976c">selectTarget</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ef5bb146eb2c0e3a609a6a169ac4f44">selectTarget</a> (const Triple &amp;TargetTriple, StringRef MArch, StringRef MCPU, const SmallVectorImpl&lt; std::string &gt; &amp;MAttrs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>selectTarget - Pick a target either via -march or by guessing the native arch. <a href="#a7ef5bb146eb2c0e3a609a6a169ac4f44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaccaa0649b2f09dfcb7123300ccd3d19">create</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af775bc7e1e968734ced732bfceae8c57">create</a> (TargetMachine *TM)</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b095cdbd8612d70a986a86365a9aef5">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441">EngineKind::Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22a43b96b15036c5ff8c470707d20b3a">WhichEngine</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf709535c5e9561117d2bd8072c4ef4c">ErrorStr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71021c6a547feed143b10646baea353b">OptLevel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager">MCJITMemoryManager</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f036ad79acd814b6d3557dd30eac8f0">MemMgr</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver">LegacyJITSymbolResolver</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ebed678b50809807e40cd4b759aa69c">Resolver</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7935ffdfc889f9ac6844a88fe30df19">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9af8109d2897f9ab8d9f362804248ce5">RelocModel</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05402046ae5fda099ce867aced4f51af">CMModel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af061530a70e7f7962437ec53c66c4535">MArch</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a7b91ad8895c7990998aff43879fe7e">MCPU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; std::string, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69f271619b48246c1220a9b621320898">MAttrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a359f73508b403c791a59603b6fa9ad28">VerifyModules</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c366d6523ca8fa82894b5990048de67">EmulatedTLS</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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

<p>Builder class for ExecutionEngines.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> this by stack-allocating a builder, chaining the various set* methods, and terminating it with a .<a href="#aaccaa0649b2f09dfcb7123300ccd3d19">create()</a> call.</p>


<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### EngineBuilder() {#a20f12106f0142f5114fdfdef7bb45551}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder::EngineBuilder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default constructor for <a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a>.</p>

<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 469 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>


<p>Referenced by <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>, <a href="#a387f51a24c0f1df5c0337ba630eb8f54">setCodeModel</a>, <a href="#a960c0e2e27d0ccef2db82f261a475ef9">setEngineKind</a>, <a href="#a8537e02128a9b4bd244dcb08f0da1fbe">setErrorStr</a>, <a href="#a33b972eb34932750dfec21f44f358398">setMArch</a>, <a href="#aba74129a5e5ff15f51a03f318bfe2497">setMAttrs</a>, <a href="#a158be06e8bc0c3e9caafba69adadaaa4">setMCJITMemoryManager</a>, <a href="#abeb3f9f8b01e92ccf434c556cdb5afd0">setMCPU</a>, <a href="#a4908930f1022471c7a7f366c94b52032">setOptLevel</a>, <a href="#ab19c764bd44bf595803472ef2c3123f3">setRelocationModel</a>, <a href="#a08c232e2416c85bdc2e479bb8f77448f">setTargetOptions</a> and <a href="#a892d551cc875d9149c447f10caea9656">setVerifyModules</a>.</p>

</div>
</div>

### EngineBuilder() {#a942eae70b5e6253100a4aa1ad843128a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder::EngineBuilder (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &gt; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructor for <a href="/web-llvm/docs/api/classes/llvm/enginebuilder">EngineBuilder</a>.</p>

<p>Declaration at line 556 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 471 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ae58c751054b01f206f9b9e34e461d25fa7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~EngineBuilder() {#a635a47f960dc06371007c276ca1de032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder::~EngineBuilder ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 559 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### create() {#aaccaa0649b2f09dfcb7123300ccd3d19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine * llvm::EngineBuilder::create ()</td>
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



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>References <a href="#aaccaa0649b2f09dfcb7123300ccd3d19">create</a> and <a href="#a69bf35545691487248c1a1d0bd45976c">selectTarget</a>.</p>


<p>Referenced by <a href="#aaccaa0649b2f09dfcb7123300ccd3d19">create</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga6f420f2ade2b50519ec53fd459a8f267">LLVMCreateExecutionEngineForModule</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaf1bf484a8108f125ccdb6ab37e317541">LLVMCreateInterpreterForModule</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga34adfbd03647338dab2a1eb687bed23f">LLVMCreateJITCompilerForModule</a> and <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### create() {#af775bc7e1e968734ced732bfceae8c57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExecutionEngine * EngineBuilder::create (<a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> * TM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a6947cede6cdd00042e82b3597606a515">llvm::ExecutionEngine::InterpCtor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441acbd7ec5d01190e525d2f938b169b9a81">llvm::EngineKind::Interpreter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441a41413991d9e4a8c017e9d83f8446d875">llvm::EngineKind::JIT</a>, <a href="/web-llvm/docs/api/classes/llvm/sys/dynamiclibrary/#a53d32d3b3baefdec31d3d94b0586d437">llvm::sys::DynamicLibrary::LoadLibraryPermanently</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a6ce88aa01ae7cf17c22e69718cff7299">llvm::ExecutionEngine::MCJITCtor</a> and <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a05f6219fb693e81805662dd4bb42e6e9">llvm::ExecutionEngine::setVerifyModules</a>.</p>

</div>
</div>

### selectTarget() {#a69bf35545691487248c1a1d0bd45976c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine * EngineBuilder::selectTarget ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 648 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/targetselect-cpp">TargetSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441acbd7ec5d01190e525d2f938b169b9a81">llvm::EngineKind::Interpreter</a> and <a href="#a69bf35545691487248c1a1d0bd45976c">selectTarget</a>.</p>


<p>Referenced by <a href="#aaccaa0649b2f09dfcb7123300ccd3d19">create</a> and <a href="#a69bf35545691487248c1a1d0bd45976c">selectTarget</a>.</p>

</div>
</div>

### selectTarget() {#a7ef5bb146eb2c0e3a609a6a169ac4f44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetMachine * EngineBuilder::selectTarget (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp; TargetTriple, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MArch, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> MCPU, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; std::string &gt; &amp; MAttrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>selectTarget - Pick a target either via -march or by guessing the native arch.</p>


<p>Add any CPU features specified via -mcpu or -mattr.</p>


<p>Declaration at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/targetselect-cpp">TargetSelect.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#af579a881fa0a6fe785ecf91fcc9ccaaa">llvm::SubtargetFeatures::AddFeature</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a97b31e68ba164458a37e49e7d1053fc1">llvm::Target::createTargetMachine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a5d5efe3bb966ce825560b2e6dd46f8ec">llvm::Triple::getArchTypeForLLVMName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#aaa9679917091c7e93f866894599f923e">llvm::SubtargetFeatures::getString</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7bc9985614536143e793244dfb66028c">llvm::Triple::getTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#af70f4019638c4a7cccaaad403c25c048">llvm::Triple::setArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a58ffeec08324cdbd301158e5ef874cc3">llvm::Triple::setTriple</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#ad1ae7fa8c7edcabe75a0fef8b6b91b98">llvm::TargetRegistry::targets</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a5b44ea359fcb23c7b1bfdc029979614c">llvm::Triple::UnknownArch</a>.</p>

</div>
</div>

### setCodeModel() {#a387f51a24c0f1df5c0337ba630eb8f54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setCodeModel (<a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> M)</td>
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

<p>setCodeModel - Set the <a href="/web-llvm/docs/api/namespaces/llvm/codemodel">CodeModel</a> that the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> target data is using.</p>


<p>Defaults to target specific default "CodeModel::JITDefault".</p>


<p>Definition at line 612 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### setEmulatedTLS() {#ab94775bd138477154f0839cd8ab93a9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::EngineBuilder::setEmulatedTLS (bool EmulatedTLS)</td>
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



<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### setEngineKind() {#a960c0e2e27d0ccef2db82f261a475ef9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setEngineKind (<a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#a9df47239a42cd9621ac26d9ecbd57441">EngineKind::Kind</a> w)</td>
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

<p>setEngineKind - Controls whether the user wants the interpreter, the JIT, or whichever engine works.</p>


<p>This option defaults to <a href="/web-llvm/docs/api/namespaces/llvm/enginekind/#abb7d2ddf5905447f9b10f887bfe6d27d">EngineKind::Either</a>.</p>


<p>Definition at line 563 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga6f420f2ade2b50519ec53fd459a8f267">LLVMCreateExecutionEngineForModule</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaf1bf484a8108f125ccdb6ab37e317541">LLVMCreateInterpreterForModule</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga34adfbd03647338dab2a1eb687bed23f">LLVMCreateJITCompilerForModule</a> and <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### setErrorStr() {#a8537e02128a9b4bd244dcb08f0da1fbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setErrorStr (std::string * e)</td>
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

<p>setErrorStr - Set the error string to write to on error.</p>


<p>This option defaults to NULL.</p>


<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga6f420f2ade2b50519ec53fd459a8f267">LLVMCreateExecutionEngineForModule</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaf1bf484a8108f125ccdb6ab37e317541">LLVMCreateInterpreterForModule</a>, <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga34adfbd03647338dab2a1eb687bed23f">LLVMCreateJITCompilerForModule</a> and <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### setMArch() {#a33b972eb34932750dfec21f44f358398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setMArch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> march)</td>
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

<p>setMArch - Override the architecture set by the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s triple.</p>

<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a> and <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>

</div>
</div>

### setMAttrs() {#aba74129a5e5ff15f51a03f318bfe2497}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename StringSequence&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setMAttrs (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> StringSequence &amp; mattrs)</td>
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

<p>setMAttrs - Set cpu-specific attributes.</p>

<p>Definition at line 638 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>

</div>
</div>

### setMCJITMemoryManager() {#a158be06e8bc0c3e9caafba69adadaaa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; EngineBuilder::setMCJITMemoryManager (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/rtdyldmemorymanager">RTDyldMemoryManager</a> &gt; mcjmm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>setMCJITMemoryManager - Sets the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> memory manager to use.</p>


<p>This allows clients to customize their memory allocation policies for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>. This is only appropriate for the <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a>; setting this and configuring the builder to create anything other than <a href="/web-llvm/docs/api/classes/llvm/mcjit">MCJIT</a> will cause a runtime error. If <a href="#aaccaa0649b2f09dfcb7123300ccd3d19">create()</a> is called and is successful, the created engine takes ownership of the memory manager. This option defaults to NULL.</p>


<p>Declaration at line 574 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 485 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### setMCPU() {#abeb3f9f8b01e92ccf434c556cdb5afd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setMCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> mcpu)</td>
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

<p>setMCPU - <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> a specific cpu type.</p>

<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/stringref/#a46f643f1eb1939362c7dd79361bcbd0e">llvm::StringRef::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a996c7ca3dd6843ba5d55a7c217770270">llvm::StringRef::end</a> and <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>

</div>
</div>

### setMemoryManager() {#aab08bd10157c574607b371f6ffc3bf78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; EngineBuilder::setMemoryManager (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/mcjitmemorymanager">MCJITMemoryManager</a> &gt; MM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 577 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 494 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

### setOptLevel() {#a4908930f1022471c7a7f366c94b52032}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setOptLevel (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> l)</td>
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

<p>setOptLevel - Set the optimization level for the JIT.</p>


<p>This option defaults to <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a>.</p>


<p>Definition at line 590 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#ga34adfbd03647338dab2a1eb687bed23f">LLVMCreateJITCompilerForModule</a> and <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### setRelocationModel() {#ab19c764bd44bf595803472ef2c3123f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setRelocationModel (<a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> RM)</td>
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

<p>setRelocationModel - Set the relocation model that the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> target is using.</p>


<p>Defaults to target specific default "Reloc::Default".</p>


<p>Definition at line 604 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>

</div>
</div>

### setSymbolResolver() {#a498e29ffd7de3d329887c9a5fabc1ca8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; EngineBuilder::setSymbolResolver (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/legacyjitsymbolresolver">LegacyJITSymbolResolver</a> &gt; SR)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 579 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>, definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a>.</p>

</div>
</div>

### setTargetOptions() {#a08c232e2416c85bdc2e479bb8f77448f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setTargetOptions (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp; Opts)</td>
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

<p>setTargetOptions - Set the target options that the <a href="/web-llvm/docs/api/classes/llvm/executionengine">ExecutionEngine</a> target is using.</p>


<p>Defaults to TargetOptions().</p>


<p>Definition at line 597 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>Reference <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengine/#gaa97dff3ed910ce2e0fc7c96b50b1c897">LLVMCreateMCJITCompilerForModule</a>.</p>

</div>
</div>

### setVerifyModules() {#a892d551cc875d9149c447f10caea9656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineBuilder &amp; llvm::EngineBuilder::setVerifyModules (bool Verify)</td>
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

<p>setVerifyModules - Set whether the JIT implementation should verify IR modules during compilation.</p>

<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>


<p>References <a href="#a20f12106f0142f5114fdfdef7bb45551">EngineBuilder</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/powerpc/ppcctrloopsverify-cpp/#a345bd69760b9ee32b3f49d4fc04120fb">Verify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CMModel {#a05402046ae5fda099ce867aced4f51af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CodeModel::Model&gt; llvm::EngineBuilder::CMModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### EmulatedTLS {#a2c366d6523ca8fa82894b5990048de67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EngineBuilder::EmulatedTLS = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### ErrorStr {#aaf709535c5e9561117d2bd8072c4ef4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string* llvm::EngineBuilder::ErrorStr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### M {#a0b095cdbd8612d70a986a86365a9aef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Module&gt; llvm::EngineBuilder::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 536 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### MArch {#af061530a70e7f7962437ec53c66c4535}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::EngineBuilder::MArch</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 545 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### MAttrs {#a69f271619b48246c1220a9b621320898}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;std::string, 4&gt; llvm::EngineBuilder::MAttrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### MCPU {#a1a7b91ad8895c7990998aff43879fe7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::EngineBuilder::MCPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### MemMgr {#a5f036ad79acd814b6d3557dd30eac8f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;MCJITMemoryManager&gt; llvm::EngineBuilder::MemMgr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 540 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### Options {#ae7935ffdfc889f9ac6844a88fe30df19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetOptions llvm::EngineBuilder::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### OptLevel {#a71021c6a547feed143b10646baea353b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::EngineBuilder::OptLevel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 539 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### RelocModel {#a9af8109d2897f9ab8d9f362804248ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Reloc::Model&gt; llvm::EngineBuilder::RelocModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### Resolver {#a5ebed678b50809807e40cd4b759aa69c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;LegacyJITSymbolResolver&gt; llvm::EngineBuilder::Resolver</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 541 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### VerifyModules {#a359f73508b403c791a59603b6fa9ad28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::EngineBuilder::VerifyModules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

### WhichEngine {#a22a43b96b15036c5ff8c470707d20b3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EngineKind::Kind llvm::EngineBuilder::WhichEngine</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/executionengine-h">ExecutionEngine.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/executionengine-cpp">ExecutionEngine.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/targetselect-cpp">TargetSelect.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
