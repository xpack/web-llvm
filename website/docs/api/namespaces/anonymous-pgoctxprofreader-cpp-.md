---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-pgoctxprofreader-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{PGOCtxProfReader.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{PGOCtxProfReader.cpp} { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbbd2ec36cbfb0867c1747b2c445fe41">toYaml</a> (yaml::Output &amp;Out, const PGOCtxProfContext &amp;Ctx)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a857d77a5beee71976041ebb6050964df">toYaml</a> (yaml::Output &amp;Out, const PGOCtxProfContext::CallTargetMapTy &amp;CallTargets)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a692f874e5ade7c6b3c0dcb244870bcb3">toYaml</a> (yaml::Output &amp;Out, const PGOCtxProfContext::CallsiteMapTy &amp;Callsites)</td>
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

### toYaml() {#adbbd2ec36cbfb0867c1747b2c445fe41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOCtxProfReader.cpp}::toYaml (<a href="/web-llvm/docs/api/classes/llvm/yaml/output">yaml::Output</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofcontext">PGOCtxProfContext</a> &amp; Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofreader-cpp">PGOCtxProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a0293085d139f190d6ffbc579a199ab2b">llvm::yaml::Output::beginFlowSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#aa2b5df9bd0a5a0a39a74892fc946659b">llvm::yaml::Output::beginMapping</a>, <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a39431a54202ce59d2b45f6bbe73060bc">llvm::yaml::Output::endFlowSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#af01bc248be6d9742bb115947318227cf">llvm::yaml::Output::endMapping</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0acb957607a78494ea70db887d1463437c">llvm::Guid</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#aaeb82b6c5b0d20bc1576c94401029702">llvm::yaml::Output::postflightFlowElement</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#af1e24b96c83a1383627fbe73e2e19aaf">llvm::yaml::Output::postflightKey</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#afb01a81c95887d95e546fd514a10b554">llvm::yaml::Output::preflightFlowElement</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#aa696b67a5ffa6c74c1fca3dc7b31ab7a">llvm::yaml::Output::preflightKey</a>, <a href="#adbbd2ec36cbfb0867c1747b2c445fe41">toYaml</a> and <a href="/web-llvm/docs/api/namespaces/llvm/yaml/#a315c7135a7dd2656de0c8bdb497c5116">llvm::yaml::yamlize</a>.</p>


<p>Referenced by <a href="#adbbd2ec36cbfb0867c1747b2c445fe41">toYaml</a>, <a href="#a692f874e5ade7c6b3c0dcb244870bcb3">toYaml</a> and <a href="#a857d77a5beee71976041ebb6050964df">toYaml</a>.</p>

</div>
</div>

### toYaml() {#a857d77a5beee71976041ebb6050964df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOCtxProfReader.cpp}::toYaml (<a href="/web-llvm/docs/api/classes/llvm/yaml/output">yaml::Output</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofcontext/#afe49915d2374d86f45b65d4bbc8f7208">PGOCtxProfContext::CallTargetMapTy</a> &amp; CallTargets)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofreader-cpp">PGOCtxProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/lib/target/hexagon/mctargetdesc/hexagonmccodeemitter-cpp/#ae4dfd7b0d66121016d6466d2ff10e8ba">_</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#adde9c3fc450771029f34a619f65e65b7">llvm::yaml::Output::beginSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#acf4afa1205c69d3ef49a2fbb1161db6d">llvm::yaml::Output::endSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a3c768e4ecf23529edbb8601b95f72d50">llvm::yaml::Output::postflightElement</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#ac1466a7db8fbbbe149c573d5a90c1a9e">llvm::yaml::Output::preflightElement</a> and <a href="#adbbd2ec36cbfb0867c1747b2c445fe41">toYaml</a>.</p>

</div>
</div>

### toYaml() {#a692f874e5ade7c6b3c0dcb244870bcb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{PGOCtxProfReader.cpp}::toYaml (<a href="/web-llvm/docs/api/classes/llvm/yaml/output">yaml::Output</a> &amp; Out, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pgoctxprofcontext/#a9cb043dbc57db0649037709a60529e16">PGOCtxProfContext::CallsiteMapTy</a> &amp; Callsites)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofreader-cpp">PGOCtxProfReader.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a0293085d139f190d6ffbc579a199ab2b">llvm::yaml::Output::beginFlowSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#adde9c3fc450771029f34a619f65e65b7">llvm::yaml::Output::beginSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a39431a54202ce59d2b45f6bbe73060bc">llvm::yaml::Output::endFlowSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#acf4afa1205c69d3ef49a2fbb1161db6d">llvm::yaml::Output::endSequence</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f02feabe2798347395e53d18da48f96">llvm::make_first_range</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab4e6de707bff0fe8081c4da0711bba07">llvm::max_element</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#a3c768e4ecf23529edbb8601b95f72d50">llvm::yaml::Output::postflightElement</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/output/#ac1466a7db8fbbbe149c573d5a90c1a9e">llvm::yaml::Output::preflightElement</a> and <a href="#adbbd2ec36cbfb0867c1747b2c445fe41">toYaml</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/pgoctxprofreader-cpp">PGOCtxProfReader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
