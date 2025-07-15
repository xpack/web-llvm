---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/lto/config
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Config` Struct Reference

<p><a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> configuration. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::lto::Config { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">llvm/LTO/Config.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ac2a2331097ef0392e387a01a0844ec">ModuleHookFn</a> = std::function&lt; bool(unsigned Task, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The following callbacks deal with tasks, which normally represent the entire optimization and code generation pipeline for what will become a single native object file. <a href="#a2ac2a2331097ef0392e387a01a0844ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfaa4b815344424627948d3bff41ad5b">CombinedIndexHookFn</a> = std::function&lt; bool( <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp;Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a3af0428ec6e48cb2f05c199b7b9f7e07">GlobalValue::GUID</a> &gt; &amp;GUIDPreservedSymbols)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A combined index hook is called after all per-module indexes have been combined (ThinLTO-specific). <a href="#adfaa4b815344424627948d3bff41ad5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VisScheme { <a href="#a6df1c201fe73a270f67a7c153c42c0be">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a> (std::string OutputFileName, bool UseInputModulePath=false, const DenseSet&lt; StringRef &gt; &amp;SaveTempsArgs={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is a convenience function that configures this <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> object to write temporary files named after the given OutputFileName for each of the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> phases to disk. <a href="#a4395f06e55f4b727fe0b685074821644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787c0462fab83a3c31d543240378fe78">CPU</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2df4a4590f315d98041339341d9e469">Options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a1e8e55e81b4c203d49bbbd0bce8a51">MAttrs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a602290924408156b5beb6e7cd6f8f4ab">MllvmArgs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addd6c05e7f9781702cd583680b21da07">PassPlugins</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/legacy/passmanager">legacy::PassManager</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534b265d050d27ea55a86b1a473b9515">PreCodeGenPassesHook</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>For adding passes that run right before codegen. <a href="#a534b265d050d27ea55a86b1a473b9515">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae561eb0b1d21dcefd1c59988684fe403">RelocModel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">Reloc::PIC_</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a143b2765089504057036d723110b48">CodeModel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6783034dde920cf6c0187877581c72ce">CGOptLevel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af31b6979bcc0505621c4d905ec5c6a2a">CGFileType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260a95aca07e95d9459c1bb31f4e7f9fda10">CodeGenFileType::ObjectFile</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad583f6a59d2c6c9debe64279846d7123">OptLevel</a> = 2</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647ccc8efe422fa8ac5d5242ccf8bbdb">VerifyEach</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59454d5a628381f0c1ce63819aa25b25">DisableVerify</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af662fcf728cd50f9a546a5a3ba7c1961">Freestanding</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Flag to indicate that the optimizer should not assume builtins are present on the target. <a href="#af662fcf728cd50f9a546a5a3ba7c1961">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55bf412b26277e61d0a5e6f8ccd10985">CodeGenOnly</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Disable entirely the optimizer, including importing for ThinLTO. <a href="#a55bf412b26277e61d0a5e6f8ccd10985">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05157b80afde0ee192d5be6978c5dba">RunCSIRInstr</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Run PGO context sensitive IR instrumentation. <a href="#ac05157b80afde0ee192d5be6978c5dba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb2fc95c3f63546728703c4e587e46cc">PGOWarnMismatch</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Turn on/off the warning about a hash mismatch in the PGO profile data. <a href="#aeb2fc95c3f63546728703c4e587e46cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a130b60c6ba64af6fe241affbafdcf1ba">HasWholeProgramVisibility</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Asserts whether we can assume whole program visibility during the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> link. <a href="#a130b60c6ba64af6fe241affbafdcf1ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a142b2de143644a1ca51d28a0fd6d5a05">ValidateAllVtablesHaveTypeInfos</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We're validating that all native vtables have corresponding type infos. <a href="#a142b2de143644a1ca51d28a0fd6d5a05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa24c924121088ad5844c88699344a7d3">AllVtablesHaveTypeInfos</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If all native vtables have corresponding type infos, allow usage of RTTI to block devirtualization on types used in native files. <a href="#aa24c924121088ad5844c88699344a7d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77d6eab1341b63721ae4ea07cbf4cc7a">AlwaysEmitRegularLTOObj</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Always emit a Regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> object even when it is empty because no Regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> modules were linked. <a href="#a77d6eab1341b63721ae4ea07cbf4cc7a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed3ed67f7ab274e3d086aa3488a3093">KeepSymbolNameCopies</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If true, the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> instance creates copies of the symbol names for <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#ada5eca1803d5afcb1005ea05ffc62636">LTO::run</a>. <a href="#a1ed3ed67f7ab274e3d086aa3488a3093">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6df1c201fe73a270f67a7c153c42c0be">VisScheme</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a901ca2ceffdd3815fd527e0d994ea4a0">VisibilityScheme</a> = <a href="#a6df1c201fe73a270f67a7c153c42c0beab75f3c598a19a49547d5fa7456d64e1a">FromPrevailing</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Allows non-imported definitions to get the potentially more constraining visibility from the prevailing definition. <a href="#a901ca2ceffdd3815fd527e0d994ea4a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe426c024bc5082714ea582cd739210e">OptPipeline</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this field is set, the set of passes run in the middle-end optimizer will be the one specified by the string. <a href="#abe426c024bc5082714ea582cd739210e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c0096e74a84beee8fa9676008520c87">AAPipeline</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99a4165a613772f6ae3b807c4e361a36">OverrideTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setting this field will replace target triples in input files with this triple. <a href="#a99a4165a613772f6ae3b807c4e361a36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7230a2bd41c69c49110f5000222515d4">DefaultTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Setting this field will replace unspecified target triples in input files with this triple. <a href="#a7230a2bd41c69c49110f5000222515d4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adffa7a90c82e1d7aa0aead0e6f74786b">CSIRProfile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Context Sensitive PGO profile path. <a href="#adffa7a90c82e1d7aa0aead0e6f74786b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1d4183a0d4ae2e704610be044010b0">SampleProfile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sample PGO profile path. <a href="#afd1d4183a0d4ae2e704610be044010b0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9dc5e1dacdffb8158529596000b3b411">ProfileRemapping</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Name remapping file for profile data. <a href="#a9dc5e1dacdffb8158529596000b3b411">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c554b4240d5088684a7ab7637749d93">DwoDir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The directory to store .dwo files. <a href="#a7c554b4240d5088684a7ab7637749d93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4f390c0f5cbd46df4734ccd229f36ec">SplitDwarfFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The name for the split debug info file used for the DW_AT_[GNU_]dwo_name attribute in the skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a>. <a href="#aa4f390c0f5cbd46df4734ccd229f36ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd13a77ae60a12f2f22018c0b7bd719">SplitDwarfOutput</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The path to write a .dwo file to. <a href="#aacd13a77ae60a12f2f22018c0b7bd719">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5add25ae56d0b0c8c3486115a6f825">RemarksFilename</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimization remarks file path. <a href="#a7f5add25ae56d0b0c8c3486115a6f825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6be094bc919f0a88daf638a87f35ed2">RemarksPasses</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Optimization remarks pass filter. <a href="#ab6be094bc919f0a88daf638a87f35ed2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad722bd2d07c784bdf48e98d88a25b214">RemarksWithHotness</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to emit optimization remarks with hotness informations. <a href="#ad722bd2d07c784bdf48e98d88a25b214">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fb18e2c1449a48f3ce809e398c8496c">RemarksHotnessThreshold</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The minimum hotness value a diagnostic needs in order to be included in optimization diagnostics. <a href="#a3fb18e2c1449a48f3ce809e398c8496c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc99ed0043add37ba2764446dbe225e">RemarksFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The format used for serializing remarks (default: YAML). <a href="#afdc99ed0043add37ba2764446dbe225e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e7d3a91d656d9f1d3c374429f883166">DebugPassManager</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether to emit the pass manager debuggging informations. <a href="#a2e7d3a91d656d9f1d3c374429f883166">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a482472b6897cbf42c20bcb04d2e879d0">StatsFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Statistics output file path. <a href="#a482472b6897cbf42c20bcb04d2e879d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61bae81cc9f92b3a346515bfb107fe3c">ThinLTOModulesToCompile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Specific thinLTO modules to compile. <a href="#a61bae81cc9f92b3a346515bfb107fe3c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf60658a6fcb26aeb35654d64e81d7d">TimeTraceEnabled</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Time trace enabled. <a href="#aadf60658a6fcb26aeb35654d64e81d7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad529c2f007e8133b4a8582d5963923aa">TimeTraceGranularity</a> = 500</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Time trace granularity. <a href="#ad529c2f007e8133b4a8582d5963923aa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae82637c19542651480df96b56531c3e0">ShouldDiscardValueNames</a> = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a1d9ed2529f1248d760979b7b53a64394">DiagnosticHandlerFunction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bb4ceaedab73c92426a241147cdabba">DiagHandler</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a345a10e4235f0a90822f39c3cbe56ae8">AddFSDiscriminator</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add FSAFDO discriminators. <a href="#a345a10e4235f0a90822f39c3cbe56ae8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a719ecf03772af7ca6a1a7cc1bc43c65b">ResolutionFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this field is set, <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> will write input file paths and symbol resolutions here in llvm-lto2 command line flag format. <a href="#a719ecf03772af7ca6a1a7cc1bc43c65b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pipelinetuningoptions">PipelineTuningOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c489480556941aaffb99ac11d530ceb">PTO</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Tunable parameters for passes in the default pipelines. <a href="#a6c489480556941aaffb99ac11d530ceb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ac2a2331097ef0392e387a01a0844ec">ModuleHookFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a496d67358c7f1e3a328e3ba2cda26268">PreOptModuleHook</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This module hook is called after linking (regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a>) or loading (ThinLTO) the module, before modifying it. <a href="#a496d67358c7f1e3a328e3ba2cda26268">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ac2a2331097ef0392e387a01a0844ec">ModuleHookFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929cce8a073bdcefff79d854deedb7ed">PostPromoteModuleHook</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook is called after promoting any internal functions (ThinLTO-specific). <a href="#a929cce8a073bdcefff79d854deedb7ed">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ac2a2331097ef0392e387a01a0844ec">ModuleHookFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace0039edf4791c66d2eb99dab50fe8f9">PostInternalizeModuleHook</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook is called after internalizing the module. <a href="#ace0039edf4791c66d2eb99dab50fe8f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ac2a2331097ef0392e387a01a0844ec">ModuleHookFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5f3c0f8fbd4bf85381e96cc672beb13">PostImportModuleHook</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This hook is called after importing from other modules (ThinLTO-specific). <a href="#ad5f3c0f8fbd4bf85381e96cc672beb13">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ac2a2331097ef0392e387a01a0844ec">ModuleHookFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab380a759b3e8d32fc59b8f88b52fe198">PostOptModuleHook</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This module hook is called after optimization is complete. <a href="#ab380a759b3e8d32fc59b8f88b52fe198">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2ac2a2331097ef0392e387a01a0844ec">ModuleHookFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae36f72183fdb505c21cc4ca6bd48a860">PreCodeGenModuleHook</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This module hook is called before code generation. <a href="#ae36f72183fdb505c21cc4ca6bd48a860">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adfaa4b815344424627948d3bff41ad5b">CombinedIndexHookFn</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49ab8afb39328f912dd54a942fbdc5c1">CombinedIndexHook</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> configuration.</p>


<p>A linker can configure <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> by setting fields in this data structure and passing it to the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">lto::LTO</a> constructor.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### CombinedIndexHookFn {#adfaa4b815344424627948d3bff41ad5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::lto::Config::CombinedIndexHookFn =  std::function&lt;bool(
      const ModuleSummaryIndex &amp;Index,
      const DenseSet&lt;GlobalValue::GUID&gt; &amp;GUIDPreservedSymbols)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A combined index hook is called after all per-module indexes have been combined (ThinLTO-specific).</p>


<p>It can be used to implement -save-temps for the combined index.</p>


<p>If this function returns false, any further processing for ThinLTO tasks is aborted.</p>


<p>It is called regardless of whether the backend is in-process, although it is not called from individual backend processes.</p>


<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### ModuleHookFn {#a2ac2a2331097ef0392e387a01a0844ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::lto::Config::ModuleHookFn =  std::function&lt;bool(unsigned Task, const Module &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The following callbacks deal with tasks, which normally represent the entire optimization and code generation pipeline for what will become a single native object file.</p>


<p>Each task has a unique identifier between 0 and getMaxTasks()-1, which is supplied to the callback via the Task parameter. A task represents the entire pipeline for ThinLTO and regular (non-parallel) <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a>, but a parallel code generation task will be split into N tasks before code generation, where N is the parallelism level.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> may decide to stop processing a task at any time, for example if the module is empty or if a module hook (see below) returns false. For this reason, the client should not expect to receive exactly getMaxTasks() native object files. A module hook may be used by a linker to perform actions during the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> pipeline. For example, a linker may use this function to implement -save-temps. If this function returns false, any further processing for that task is aborted.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> hooks must be thread safe with respect to the linker's internal data structures. A module hook will never be called concurrently from multiple threads with the same task <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a>, or the same module.</p>


<p>Note that in out-of-process backend scenarios, none of the hooks will be called for ThinLTO tasks.</p>


<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### VisScheme {#a6df1c201fe73a270f67a7c153c42c0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::lto::Config::VisScheme </td>
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
<td class="doxyEnumItemName">FromPrevailing<a id="a6df1c201fe73a270f67a7c153c42c0beab75f3c598a19a49547d5fa7456d64e1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELF<a id="a6df1c201fe73a270f67a7c153c42c0bea89d9995963600df8c6854372881cbbb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addSaveTemps() {#a4395f06e55f4b727fe0b685074821644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error Config::addSaveTemps (std::string OutputFileName, bool UseInputModulePath=false, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/denseset">DenseSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; SaveTempsArgs={})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This is a convenience function that configures this <a href="/web-llvm/docs/api/structs/llvm/lto/config">Config</a> object to write temporary files named after the given OutputFileName for each of the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> phases to disk.</p>


<p>A client can use this function to implement -save-temps.</p>


<p>FIXME: Temporary files derived from ThinLTO backends are currently named after the input file name, rather than the output file name, when UseInputModulePath is set to true.</p>


<p>Specifically, it (1) sets each of the above module hooks and the combined index hook to a function that calls the hook function (if any) that was present in the appropriate field when the addSaveTemps function was called, and writes the module to a bitcode file with a name prefixed by the given output file name, and (2) creates a resolution file whose name is prefixed by the given output file name and sets ResolutionFile to its file handle.</p>


<p>SaveTempsArgs can be specified to select which temps to save. If SaveTempsArgs is not provided, all temps are saved.</p>


<p>Declaration at line 280 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a>.</p>


<p>References <a href="#a49ab8afb39328f912dd54a942fbdc5c1">CombinedIndexHook</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#ad409c2de8502b94c8a0b1193307c63b6">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/detail/densesetimpl/#a9a3c9d867ff6bde97841c2b7983f5c70">llvm::detail::DenseSetImpl&lt; ValueT, MapTy, ValueInfoT &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a6118bd1b7164f1f8f02470a5cb6a538b">llvm::sys::fs::OF_Text</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a>, <a href="#ad5f3c0f8fbd4bf85381e96cc672beb13">PostImportModuleHook</a>, <a href="#ace0039edf4791c66d2eb99dab50fe8f9">PostInternalizeModuleHook</a>, <a href="#ab380a759b3e8d32fc59b8f88b52fe198">PostOptModuleHook</a>, <a href="#a929cce8a073bdcefff79d854deedb7ed">PostPromoteModuleHook</a>, <a href="#ae36f72183fdb505c21cc4ca6bd48a860">PreCodeGenModuleHook</a>, <a href="#a496d67358c7f1e3a328e3ba2cda26268">PreOptModuleHook</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a041e682560afc980462e5ca47deb1f24">reportOpenError</a>, <a href="#a719ecf03772af7ca6a1a7cc1bc43c65b">ResolutionFile</a>, <a href="#ae82637c19542651480df96b56531c3e0">ShouldDiscardValueNames</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a41972fe6f3fab862543b7b835a714f9b">llvm::utostr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a199eb3a521b35ac20b20b7460bf2dabb">llvm::WriteBitcodeToFile</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AAPipeline {#a4c0096e74a84beee8fa9676008520c87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::AAPipeline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### AddFSDiscriminator {#a345a10e4235f0a90822f39c3cbe56ae8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::AddFSDiscriminator = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add FSAFDO discriminators.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### AllVtablesHaveTypeInfos {#aa24c924121088ad5844c88699344a7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::AllVtablesHaveTypeInfos = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If all native vtables have corresponding type infos, allow usage of RTTI to block devirtualization on types used in native files.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### AlwaysEmitRegularLTOObj {#a77d6eab1341b63721ae4ea07cbf4cc7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::AlwaysEmitRegularLTOObj = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Always emit a Regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> object even when it is empty because no Regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> modules were linked.</p>


<p>This option is useful for some build system which want to know a priori all possible output files.</p>


<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### CGFileType {#af31b6979bcc0505621c4d905ec5c6a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenFileType llvm::lto::Config::CGFileType = <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260a95aca07e95d9459c1bb31f4e7f9fda10">CodeGenFileType::ObjectFile</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>.</p>

</div>
</div>

### CGOptLevel {#a6783034dde920cf6c0187877581c72ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::lto::Config::CGOptLevel = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### CodeGenOnly {#a55bf412b26277e61d0a5e6f8ccd10985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::CodeGenOnly = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Disable entirely the optimizer, including importing for ThinLTO.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### CodeModel {#a4a143b2765089504057036d723110b48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CodeModel::Model&gt; llvm::lto::Config::CodeModel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a>.</p>

</div>
</div>

### CombinedIndexHook {#a49ab8afb39328f912dd54a942fbdc5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CombinedIndexHookFn llvm::lto::Config::CombinedIndexHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a>.</p>

</div>
</div>

### CPU {#a787c0462fab83a3c31d543240378fe78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::CPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### CSIRProfile {#adffa7a90c82e1d7aa0aead0e6f74786b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::CSIRProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Context Sensitive PGO profile path.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### DebugPassManager {#a2e7d3a91d656d9f1d3c374429f883166}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::DebugPassManager = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to emit the pass manager debuggging informations.</p>

<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### DefaultTriple {#a7230a2bd41c69c49110f5000222515d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::DefaultTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Setting this field will replace unspecified target triples in input files with this triple.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>.</p>

</div>
</div>

### DiagHandler {#a0bb4ceaedab73c92426a241147cdabba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticHandlerFunction llvm::lto::Config::DiagHandler</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### DisableVerify {#a59454d5a628381f0c1ce63819aa25b25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::DisableVerify = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### DwoDir {#a7c554b4240d5088684a7ab7637749d93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::DwoDir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The directory to store .dwo files.</p>

<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>.</p>

</div>
</div>

### Freestanding {#af662fcf728cd50f9a546a5a3ba7c1961}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::Freestanding = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Flag to indicate that the optimizer should not assume builtins are present on the target.</p>

<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### HasWholeProgramVisibility {#a130b60c6ba64af6fe241affbafdcf1ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::HasWholeProgramVisibility = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Asserts whether we can assume whole program visibility during the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> link.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### KeepSymbolNameCopies {#a1ed3ed67f7ab274e3d086aa3488a3093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::KeepSymbolNameCopies = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If true, the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> instance creates copies of the symbol names for <a href="/web-llvm/docs/api/classes/llvm/lto/lto/#ada5eca1803d5afcb1005ea05ffc62636">LTO::run</a>.</p>


<p>The lld linker uses string saver to keep symbol names alive and doesn't need to create copies, so it can set this field to false.</p>


<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### MAttrs {#a5a1e8e55e81b4c203d49bbbd0bce8a51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::lto::Config::MAttrs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### MllvmArgs {#a602290924408156b5beb6e7cd6f8f4ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::lto::Config::MllvmArgs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>.</p>

</div>
</div>

### Options {#aa2df4a4590f315d98041339341d9e469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetOptions llvm::lto::Config::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### OptLevel {#ad583f6a59d2c6c9debe64279846d7123}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::Config::OptLevel = 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae3dc87f8d2d7b79aa7da2d3224f3f63d">llvm::lto::opt</a>.</p>

</div>
</div>

### OptPipeline {#abe426c024bc5082714ea582cd739210e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::OptPipeline</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this field is set, the set of passes run in the middle-end optimizer will be the one specified by the string.</p>


<p>Only works with the new pass manager as the old one doesn't have this ability.</p>


<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### OverrideTriple {#a99a4165a613772f6ae3b807c4e361a36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::OverrideTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Setting this field will replace target triples in input files with this triple.</p>

<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>.</p>

</div>
</div>

### PassPlugins {#addd6c05e7f9781702cd583680b21da07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::lto::Config::PassPlugins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### PGOWarnMismatch {#aeb2fc95c3f63546728703c4e587e46cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::PGOWarnMismatch = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Turn on/off the warning about a hash mismatch in the PGO profile data.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### PostImportModuleHook {#ad5f3c0f8fbd4bf85381e96cc672beb13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleHookFn llvm::lto::Config::PostImportModuleHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This hook is called after importing from other modules (ThinLTO-specific).</p>

<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### PostInternalizeModuleHook {#ace0039edf4791c66d2eb99dab50fe8f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleHookFn llvm::lto::Config::PostInternalizeModuleHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This hook is called after internalizing the module.</p>

<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### PostOptModuleHook {#ab380a759b3e8d32fc59b8f88b52fe198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleHookFn llvm::lto::Config::PostOptModuleHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This module hook is called after optimization is complete.</p>

<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae3dc87f8d2d7b79aa7da2d3224f3f63d">llvm::lto::opt</a>.</p>

</div>
</div>

### PostPromoteModuleHook {#a929cce8a073bdcefff79d854deedb7ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleHookFn llvm::lto::Config::PostPromoteModuleHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This hook is called after promoting any internal functions (ThinLTO-specific).</p>

<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### PreCodeGenModuleHook {#ae36f72183fdb505c21cc4ca6bd48a860}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleHookFn llvm::lto::Config::PreCodeGenModuleHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This module hook is called before code generation.</p>


<p>It is similar to the PostOptModuleHook, but for parallel code generation it is called after splitting the module.</p>


<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>.</p>

</div>
</div>

### PreCodeGenPassesHook {#a534b265d050d27ea55a86b1a473b9515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(legacy::PassManager &amp;)&gt; llvm::lto::Config::PreCodeGenPassesHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>For adding passes that run right before codegen.</p>

<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>.</p>

</div>
</div>

### PreOptModuleHook {#a496d67358c7f1e3a328e3ba2cda26268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleHookFn llvm::lto::Config::PreOptModuleHook</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This module hook is called after linking (regular <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a>) or loading (ThinLTO) the module, before modifying it.</p>

<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### ProfileRemapping {#a9dc5e1dacdffb8158529596000b3b411}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::ProfileRemapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Name remapping file for profile data.</p>

<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### PTO {#a6c489480556941aaffb99ac11d530ceb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PipelineTuningOptions llvm::lto::Config::PTO</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Tunable parameters for passes in the default pipelines.</p>

<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### RelocModel {#ae561eb0b1d21dcefd1c59988684fe403}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Reloc::Model&gt; llvm::lto::Config::RelocModel = <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568adc2075e13a68142b26e05ac08bbfc320">Reloc::PIC_</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a020a49618af317a9da7a8193a54338e5">createTargetMachine</a> and <a href="/web-llvm/docs/api/classes/anonymous-thinltocodegenerator-cpp-/modulecacheentry/#aea61f7d56840b1a92477a55f4a526de0">anonymous{ThinLTOCodeGenerator.cpp}::ModuleCacheEntry::ModuleCacheEntry</a>.</p>

</div>
</div>

### RemarksFilename {#a7f5add25ae56d0b0c8c3486115a6f825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::RemarksFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimization remarks file path.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### RemarksFormat {#afdc99ed0043add37ba2764446dbe225e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::RemarksFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The format used for serializing remarks (default: YAML).</p>

<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### RemarksHotnessThreshold {#a3fb18e2c1449a48f3ce809e398c8496c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;uint64_t&gt; llvm::lto::Config::RemarksHotnessThreshold = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The minimum hotness value a diagnostic needs in order to be included in optimization diagnostics.</p>


<p>The threshold is an Optional value, which maps to one of the 3 states:</p>


<ol class="doxyList" type="1">
<li>0 =&gt; threshold disabled. All emarks will be printed.</li>
<li>positive int =&gt; manual threshold by user. Remarks with hotness exceed threshold will be printed.</li>
<li>None =&gt; 'auto' threshold by user. The actual value is not available at command line, but will be synced with hotness threhold from profile summary during compilation.</li>
</ol>

<p>If threshold option is not specified, it is disabled by default.</p>


<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### RemarksPasses {#ab6be094bc919f0a88daf638a87f35ed2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::RemarksPasses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Optimization remarks pass filter.</p>

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### RemarksWithHotness {#ad722bd2d07c784bdf48e98d88a25b214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::RemarksWithHotness = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether to emit optimization remarks with hotness informations.</p>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">llvm::lto::thinBackend</a>.</p>

</div>
</div>

### ResolutionFile {#a719ecf03772af7ca6a1a7cc1bc43c65b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;raw_ostream&gt; llvm::lto::Config::ResolutionFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this field is set, <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> will write input file paths and symbol resolutions here in llvm-lto2 command line flag format.</p>


<p>This can be used for testing and for running the <a href="/web-llvm/docs/api/classes/llvm/lto/lto">LTO</a> pipeline outside of the linker with llvm-lto2.</p>


<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a>.</p>

</div>
</div>

### RunCSIRInstr {#ac05157b80afde0ee192d5be6978c5dba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::RunCSIRInstr = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Run PGO context sensitive IR instrumentation.</p>

<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### SampleProfile {#afd1d4183a0d4ae2e704610be044010b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::SampleProfile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sample PGO profile path.</p>

<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acded9a0ef045f4502147ee746817bbd9">llvm::computeLTOCacheKey</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### ShouldDiscardValueNames {#ae82637c19542651480df96b56531c3e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::ShouldDiscardValueNames = <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="#a4395f06e55f4b727fe0b685074821644">addSaveTemps</a>.</p>

</div>
</div>

### SplitDwarfFile {#aa4f390c0f5cbd46df4734ccd229f36ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::SplitDwarfFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The name for the split debug info file used for the DW_AT_[GNU_]dwo_name attribute in the skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p>


<p>This should generally only be used when running an individual backend directly via <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend()</a>, as otherwise all objects would use the same .dwo file. Not used as output path.</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>.</p>

</div>
</div>

### SplitDwarfOutput {#aacd13a77ae60a12f2f22018c0b7bd719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::SplitDwarfOutput</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The path to write a .dwo file to.</p>


<p>This should generally only be used when running an individual backend directly via <a href="/web-llvm/docs/api/namespaces/llvm/lto/#ae6ff75e89240b2f2c01d3be088ca6014">thinBackend()</a>, as otherwise all .dwo files will be written to the same path. Not used in skeleton <a href="/web-llvm/docs/api/namespaces/cu">CU</a>.</p>


<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#a889b75e55af23f854f7f597b0e912b98">codegen</a>.</p>

</div>
</div>

### StatsFile {#a482472b6897cbf42c20bcb04d2e879d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::lto::Config::StatsFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Statistics output file path.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### ThinLTOModulesToCompile {#a61bae81cc9f92b3a346515bfb107fe3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;std::string&gt; llvm::lto::Config::ThinLTOModulesToCompile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Specific thinLTO modules to compile.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### TimeTraceEnabled {#aadf60658a6fcb26aeb35654d64e81d7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::TimeTraceEnabled = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Time trace enabled.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### TimeTraceGranularity {#ad529c2f007e8133b4a8582d5963923aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::lto::Config::TimeTraceGranularity = 500</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Time trace granularity.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### ValidateAllVtablesHaveTypeInfos {#a142b2de143644a1ca51d28a0fd6d5a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::ValidateAllVtablesHaveTypeInfos = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We're validating that all native vtables have corresponding type infos.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

### VerifyEach {#a647ccc8efe422fa8ac5d5242ccf8bbdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::lto::Config::VerifyEach = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp/#af5d1d807d38250523b2335cec221c2f1">runNewPMPasses</a>.</p>

</div>
</div>

### VisibilityScheme {#a901ca2ceffdd3815fd527e0d994ea4a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VisScheme llvm::lto::Config::VisibilityScheme = <a href="#a6df1c201fe73a270f67a7c153c42c0beab75f3c598a19a49547d5fa7456d64e1a">FromPrevailing</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Allows non-imported definitions to get the potentially more constraining visibility from the prevailing definition.</p>


<p>FromPrevailing is the default because it works for many binary formats. <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> can use the more optimized '<a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a>' scheme.</p>


<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/lto/config-h">Config.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/lto/ltobackend-cpp">LTOBackend.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
