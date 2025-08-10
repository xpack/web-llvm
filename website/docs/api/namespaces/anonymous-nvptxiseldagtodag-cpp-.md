---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-nvptxiseldagtodag-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `anonymous{NVPTXISelDAGToDAG.cpp}` Namespace



## Definition

<div class="doxyDefinition">
namespace anonymous{NVPTXISelDAGToDAG.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-nvptxiseldagtodag-cpp-/operationorderings">OperationOrderings</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-nvptxiseldagtodag-cpp-/operationorderings">OperationOrderings</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b394d4c4aa365db793d44aa627bec7a">getOperationOrderings</a> (MemSDNode *N, const NVPTXSubtarget *Subtarget)</td>
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

### getOperationOrderings() {#a4b394d4c4aa365db793d44aa627bec7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OperationOrderings anonymous{NVPTXISelDAGToDAG.cpp}::getOperationOrderings (<a href="/web-llvm/docs/api/classes/llvm/memsdnode">MemSDNode</a> * N, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/nvptxsubtarget">NVPTXSubtarget</a> * Subtarget)</td>
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



<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a993ca650a85e8e69b8f7eaa4809c4862">llvm::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a049c4a51b6abaec68a318a3167fffab0">llvm::NVPTX::Acquire</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a960fbd067612ca87e16d5dfdb12fe40a">llvm::AcquireRelease</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a78523d34068fb7d8996627878dd5ba19">llvm::NVPTX::Const</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a653cce37b80c03eebe7a00520a8eabb6">llvm::formatv</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86aa39dce0fae417c281c73ce59bf74f23d">llvm::NVPTX::Generic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp/#a0ab9f5d7a4da7c32c7047da3d08c0f22">getCodeAddrSpace</a>, <a href="#a4b394d4c4aa365db793d44aa627bec7a">getOperationOrderings</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a1db64802d3774048124b6d35acbb48b8">llvm::NVPTX::Global</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxsubtarget/#aef2c7b33bb315753d2d59da497aa2a1a">llvm::NVPTXSubtarget::hasMemoryOrdering</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxsubtarget/#ab53d4c5c6623a1a8426aef6129ca2f32">llvm::NVPTXSubtarget::hasRelaxedMMIO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86afa222eeb9d903482895b95ece2b983b7">llvm::NVPTX::Local</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a14194d0b2e6c6680067975517cd58eac">llvm::Monotonic</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a56a57d29a3f9dda8671b4d6490a94b08">llvm::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a8392068ab98bc624c0f367e662639412">llvm::NVPTX::NotAtomic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a2f6244cb6b1966052e52af35d910cf8d">llvm::NVPTX::Param</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a1897d7bdf307cfe860a93305d7b53f2d">llvm::NVPTX::Relaxed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01a00c1ec0cc5d8e908c81e0f31af1aac13">llvm::NVPTX::RelaxedMMIO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ab8e7b465df7c5979dc731d06e84ce2cf">llvm::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01ac9b2103fef41f5e9b1d44dc5beb90f81">llvm::NVPTX::Release</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7ae3b0fa849dbd758b450f98fcfde936a2">llvm::SequentiallyConsistent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01ad9751ec400c96e6c2b104cc6c9859a71">llvm::NVPTX::SequentiallyConsistent</a>, <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#a33cca915c8026e43ecc98a96089a6b86a54c619e65d06a9f19b7bb89cef76b1a9">llvm::NVPTX::Shared</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a473a7928f2af5c01022800db638773">llvm::toIRString</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9bccbe67aaab722783ca4e7c504aaaa7a288d468c5e0969f26a310773eda65603">llvm::Unordered</a> and <a href="/web-llvm/docs/api/namespaces/llvm/nvptx/#adcf87377f3df8d9008825b7fc46f4f01abccad5ae872ddb0c9b447c03602e8eab">llvm::NVPTX::Volatile</a>.</p>


<p>Referenced by <a href="#a4b394d4c4aa365db793d44aa627bec7a">getOperationOrderings</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxiseldagtodag-cpp">NVPTXISelDAGToDAG.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
