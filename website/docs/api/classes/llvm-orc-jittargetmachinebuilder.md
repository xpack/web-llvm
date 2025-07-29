---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/jittargetmachinebuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `JITTargetMachineBuilder` Class

<p>A utility class for building TargetMachines for JITs. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::orc::JITTargetMachineBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">llvm/ExecutionEngine/Orc/JITTargetMachineBuilder.h</a>"
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28b06e61d728e42d09ee8d829fe88a18">JITTargetMachineBuilderPrinter</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a> (Triple TT)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> based on the given triple. <a href="#ad180fd040a0603fdebcc1b4cb8b002da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad851482024748222bc5538345ec2bd12">createTargetMachine</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>. <a href="#ad851482024748222bc5538345ec2bd12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae1a8efd4b4afe6411908938a204fa0b">getDefaultDataLayoutForTarget</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the default <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for the target. <a href="#aae1a8efd4b4afe6411908938a204fa0b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec5fa6165b874d31e84a16e4759147d3">setCPU</a> (std::string CPU)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the CPU string. <a href="#aec5fa6165b874d31e84a16e4759147d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b77888697357ad6e8a9fb7c566d05cb">getCPU</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the CPU string. <a href="#a1b77888697357ad6e8a9fb7c566d05cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d13d5621622a259d38614f47f131d32">setRelocationModel</a> (std::optional&lt; Reloc::Model &gt; RM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the relocation model. <a href="#a6d13d5621622a259d38614f47f131d32">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dc059c3f5b4f70a725894fb854f56ab">getRelocationModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the relocation model. <a href="#a2dc059c3f5b4f70a725894fb854f56ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73e16640e122a7b86db4219b0e3baa6">setCodeModel</a> (std::optional&lt; CodeModel::Model &gt; CM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the code model. <a href="#aa73e16640e122a7b86db4219b0e3baa6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35f1081bab7ac10ea393d067bd157c07">getCodeModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the code model. <a href="#a35f1081bab7ac10ea393d067bd157c07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fdab86b2c89eb0ef9fbbb1544f3d11">setCodeGenOptLevel</a> (CodeGenOptLevel OptLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the LLVM CodeGen optimization level. <a href="#a19fdab86b2c89eb0ef9fbbb1544f3d11">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0ec04e468a114be176c024b5f627cc3">setFeatures</a> (StringRef FeatureString)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set subtarget features. <a href="#ab0ec04e468a114be176c024b5f627cc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a542f642c8bb4285e3297fce9c9ff8a8b">addFeatures</a> (const std::vector&lt; std::string &gt; &amp;FeatureVec)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add subtarget features. <a href="#a542f642c8bb4285e3297fce9c9ff8a8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55092d36ab6356bbcae306bd67e22c53">getFeatures</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access subtarget features. <a href="#a55092d36ab6356bbcae306bd67e22c53">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d62b1db951b062cc5d11184bbadbc3">getFeatures</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access subtarget features. <a href="#ab6d62b1db951b062cc5d11184bbadbc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a49f02d0a565e36e9814dabec0a500d">setOptions</a> (TargetOptions Options)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a>. <a href="#a6a49f02d0a565e36e9814dabec0a500d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a338e5ffffcf6d17ea963d9236ce5dfd5">getOptions</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a>. <a href="#a338e5ffffcf6d17ea963d9236ce5dfd5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa49ae15f4f8bfbfadcead4456ffac69d">getOptions</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a>. <a href="#aa49ae15f4f8bfbfadcead4456ffac69d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68541e5fec498fa3931da9a1173fd1d1">getTargetTriple</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a>. <a href="#a68541e5fec498fa3931da9a1173fd1d1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c740de0b933961ed1a9f157fb9e3c6c">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Access <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a>. <a href="#a6c740de0b933961ed1a9f157fb9e3c6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af16aa3355004b93a6e4770143d8efe81">TT</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5aa13ab6efc4f80f7585372fffd7a717">CPU</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures">SubtargetFeatures</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64c6bb702e8a30966808bec7bc358048">Features</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07682dce57d84aa729ccbc46734c7836">Options</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ae88419a7812fa28071a69a54dc732d">RM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5932ff1b0e3e974c281879e73cc6fb36">CM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7beb2c4c70c768d49f8a2386f4d5fd31">OptLevel</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa67d14db111b10a6a09cb70fa5f4e084">detectHost</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> for the host system. <a href="#aa67d14db111b10a6a09cb70fa5f4e084">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A utility class for building TargetMachines for JITs.</p>

<p>Definition at line 34 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<div class="doxySectionDef">

## Friends

### JITTargetMachineBuilderPrinter {#a28b06e61d728e42d09ee8d829fe88a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilderprinter">JITTargetMachineBuilderPrinter</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 36 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#a28b06e61d728e42d09ee8d829fe88a18">JITTargetMachineBuilderPrinter</a>.</p>


<p>Referenced by <a href="#a28b06e61d728e42d09ee8d829fe88a18">JITTargetMachineBuilderPrinter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### JITTargetMachineBuilder() {#ad180fd040a0603fdebcc1b4cb8b002da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::orc::JITTargetMachineBuilder::JITTargetMachineBuilder (<a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a> TT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> based on the given triple.</p>


<p>Note: <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> is default-constructed, then EmulatedTLS is set to true. If EmulatedTLS is not required, these values should be reset before calling createTargetMachine.</p>


<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>, definition at line 18 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jittargetmachinebuilder-cpp">JITTargetMachineBuilder.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>


<p>Referenced by <a href="#a542f642c8bb4285e3297fce9c9ff8a8b">addFeatures</a>, <a href="#aa67d14db111b10a6a09cb70fa5f4e084">detectHost</a>, <a href="#a19fdab86b2c89eb0ef9fbbb1544f3d11">setCodeGenOptLevel</a>, <a href="#aa73e16640e122a7b86db4219b0e3baa6">setCodeModel</a>, <a href="#aec5fa6165b874d31e84a16e4759147d3">setCPU</a>, <a href="#ab0ec04e468a114be176c024b5f627cc3">setFeatures</a>, <a href="#a6a49f02d0a565e36e9814dabec0a500d">setOptions</a> and <a href="#a6d13d5621622a259d38614f47f131d32">setRelocationModel</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFeatures() {#a542f642c8bb4285e3297fce9c9ff8a8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetMachineBuilder &amp; llvm::orc::JITTargetMachineBuilder::addFeatures (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::vector&lt; std::string &gt; &amp; FeatureVec)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add subtarget features.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>, definition at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jittargetmachinebuilder-cpp">JITTargetMachineBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a>.</p>

</div>
</div>

### createTargetMachine() {#ad851482024748222bc5538345ec2bd12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; TargetMachine &gt; &gt; llvm::orc::JITTargetMachineBuilder::createTargetMachine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a>.</p>


<p>This operation will fail if the requested target is not registered, in which case see <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/targetselect-h">llvm/Support/TargetSelect.h</a>. To JIT IR the <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> and the target's <a href="/web-llvm/docs/api/classes/llvm/asmprinter">AsmPrinter</a> must both be registered. To JIT assembly (including inline and module level assembly) the target's AsmParser must also be registered.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jittargetmachinebuilder-cpp">JITTargetMachineBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/orc/lljit/#a7e3e5170bf4d4fa25f1b53e1a5925589">llvm::orc::LLJIT::createCompileFunction</a> and <a href="#aae1a8efd4b4afe6411908938a204fa0b">getDefaultDataLayoutForTarget</a>.</p>

</div>
</div>

### getCodeModel() {#a35f1081bab7ac10ea393d067bd157c07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; CodeModel::Model &gt; &amp; llvm::orc::JITTargetMachineBuilder::getCodeModel ()</td>
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

<p>Get the code model.</p>

<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### getCPU() {#a1b77888697357ad6e8a9fb7c566d05cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::orc::JITTargetMachineBuilder::getCPU ()</td>
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

<p>Returns the CPU string.</p>

<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### getDefaultDataLayoutForTarget() {#aae1a8efd4b4afe6411908938a204fa0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; DataLayout &gt; llvm::orc::JITTargetMachineBuilder::getDefaultDataLayoutForTarget ()</td>
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

<p>Get the default <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> for the target.</p>


<p>Note: This is reasonably expensive, as it creates a temporary <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> instance under the hood. It is only suitable for use during JIT setup.</p>


<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#ad851482024748222bc5538345ec2bd12">createTargetMachine</a>.</p>

</div>
</div>

### getFeatures() {#a55092d36ab6356bbcae306bd67e22c53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubtargetFeatures &amp; llvm::orc::JITTargetMachineBuilder::getFeatures ()</td>
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

<p>Access subtarget features.</p>

<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Referenced by <a href="#aa67d14db111b10a6a09cb70fa5f4e084">detectHost</a>.</p>

</div>
</div>

### getFeatures() {#ab6d62b1db951b062cc5d11184bbadbc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SubtargetFeatures &amp; llvm::orc::JITTargetMachineBuilder::getFeatures ()</td>
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

<p>Access subtarget features.</p>

<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### getOptions() {#a338e5ffffcf6d17ea963d9236ce5dfd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetOptions &amp; llvm::orc::JITTargetMachineBuilder::getOptions ()</td>
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

<p>Access <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a>.</p>

<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### getOptions() {#aa49ae15f4f8bfbfadcead4456ffac69d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TargetOptions &amp; llvm::orc::JITTargetMachineBuilder::getOptions ()</td>
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

<p>Access <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a>.</p>

<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### getRelocationModel() {#a2dc059c3f5b4f70a725894fb854f56ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::optional&lt; Reloc::Model &gt; &amp; llvm::orc::JITTargetMachineBuilder::getRelocationModel ()</td>
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

<p>Get the relocation model.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### getTargetTriple() {#a68541e5fec498fa3931da9a1173fd1d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple &amp; llvm::orc::JITTargetMachineBuilder::getTargetTriple ()</td>
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

<p>Access <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a>.</p>

<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### getTargetTriple() {#a6c740de0b933961ed1a9f157fb9e3c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Triple &amp; llvm::orc::JITTargetMachineBuilder::getTargetTriple ()</td>
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

<p>Access <a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a>.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### setCodeGenOptLevel() {#a19fdab86b2c89eb0ef9fbbb1544f3d11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetMachineBuilder &amp; llvm::orc::JITTargetMachineBuilder::setCodeGenOptLevel (<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel)</td>
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

<p>Set the LLVM CodeGen optimization level.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a>.</p>

</div>
</div>

### setCodeModel() {#aa73e16640e122a7b86db4219b0e3baa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetMachineBuilder &amp; llvm::orc::JITTargetMachineBuilder::setCodeModel (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt; CM)</td>
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

<p>Set the code model.</p>

<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a>.</p>

</div>
</div>

### setCPU() {#aec5fa6165b874d31e84a16e4759147d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetMachineBuilder &amp; llvm::orc::JITTargetMachineBuilder::setCPU (std::string CPU)</td>
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

<p>Set the CPU string.</p>

<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a>.</p>


<p>Referenced by <a href="#aa67d14db111b10a6a09cb70fa5f4e084">detectHost</a>.</p>

</div>
</div>

### setFeatures() {#ab0ec04e468a114be176c024b5f627cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetMachineBuilder &amp; llvm::orc::JITTargetMachineBuilder::setFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FeatureString)</td>
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

<p>Set subtarget features.</p>

<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a>.</p>

</div>
</div>

### setOptions() {#a6a49f02d0a565e36e9814dabec0a500d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetMachineBuilder &amp; llvm::orc::JITTargetMachineBuilder::setOptions (<a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> Options)</td>
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

<p>Set <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a>.</p>


<p>Note: This operation will overwrite any previously configured options, including EmulatedTLS and UseInitArray which the <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> sets by default. Clients are responsible for re-enabling these overwritten options.</p>


<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a>.</p>

</div>
</div>

### setRelocationModel() {#a6d13d5621622a259d38614f47f131d32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">JITTargetMachineBuilder &amp; llvm::orc::JITTargetMachineBuilder::setRelocationModel (std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt; RM)</td>
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

<p>Set the relocation model.</p>

<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>


<p>Reference <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CM {#a5932ff1b0e3e974c281879e73cc6fb36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;CodeModel::Model&gt; llvm::orc::JITTargetMachineBuilder::CM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### CPU {#a5aa13ab6efc4f80f7585372fffd7a717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::orc::JITTargetMachineBuilder::CPU</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### Features {#a64c6bb702e8a30966808bec7bc358048}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubtargetFeatures llvm::orc::JITTargetMachineBuilder::Features</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### Options {#a07682dce57d84aa729ccbc46734c7836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetOptions llvm::orc::JITTargetMachineBuilder::Options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### OptLevel {#a7beb2c4c70c768d49f8a2386f4d5fd31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenOptLevel llvm::orc::JITTargetMachineBuilder::OptLevel = <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### RM {#a1ae88419a7812fa28071a69a54dc732d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;Reloc::Model&gt; llvm::orc::JITTargetMachineBuilder::RM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

### TT {#af16aa3355004b93a6e4770143d8efe81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple llvm::orc::JITTargetMachineBuilder::TT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### detectHost() {#aa67d14db111b10a6a09cb70fa5f4e084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; JITTargetMachineBuilder &gt; llvm::orc::JITTargetMachineBuilder::detectHost ()</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/orc/jittargetmachinebuilder">JITTargetMachineBuilder</a> for the host system.</p>


<p>Note: <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> is default-constructed, then EmulatedTLS is set to true. If EmulatedTLS is not required, these values should be reset before calling createTargetMachine.</p>


<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a>, definition at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jittargetmachinebuilder-cpp">JITTargetMachineBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#af579a881fa0a6fe785ecf91fcc9ccaaa">llvm::SubtargetFeatures::AddFeature</a>, <a href="#a55092d36ab6356bbcae306bd67e22c53">getFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2e3453665d04910c970e81e6c2fc2f98">llvm::sys::getHostCPUFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2e8cdc0e591685c9156af3d0d4fdae06">llvm::sys::getHostCPUName</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#aab375071f641a086c0d7067635ccd3dc">llvm::sys::getProcessTriple</a>, <a href="#ad180fd040a0603fdebcc1b4cb8b002da">JITTargetMachineBuilder</a> and <a href="#aec5fa6165b874d31e84a16e4759147d3">setCPU</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga5718550d7bc69420aef9830b23a1bec7">LLVMOrcJITTargetMachineBuilderDetectHost</a> and <a href="/web-llvm/docs/api/classes/llvm/orc/lljitbuilderstate/#a18ff6139760982f4640e0ea26da81ba4">llvm::orc::LLJITBuilderState::prepareForConstruction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/jittargetmachinebuilder-h">JITTargetMachineBuilder.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/jittargetmachinebuilder-cpp">JITTargetMachineBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
