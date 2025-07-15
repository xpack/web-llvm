---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/rdf/funcnode
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `FuncNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::rdf::FuncNode { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">llvm/CodeGen/RDFGraph.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/rdf/codenode">CodeNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0123488d523150e7f7f0a109d248481a">getCode</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d0ffbd3083be7cd886e1714817492c8">findBlock</a> (const MachineBasicBlock *BB, const DataFlowGraph &amp;G) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/rdf/#a24b78e828e0547ee3eac4ac5b7089d35">Block</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9295f6b6829636049842aad2b53ae0e">getEntryBlock</a> (const DataFlowGraph &amp;G)</td>
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


<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### findBlock() {#a9d0ffbd3083be7cd886e1714817492c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block llvm::rdf::FuncNode::findBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinebasicblock">MachineBasicBlock</a> * BB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 568 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/rdf/nodeaddr/#a150c10db309dcfa7a1093dc0c698d663">llvm::rdf::NodeAddr&lt; T &gt;::Addr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/structs/llvm/rdf/blocknode/#ac31264a23924e7566514128d8b64b9a9">llvm::rdf::BlockNode::getCode</a> and <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#a0d9ff571e6ceb5df2eb4d8a4d3011245">llvm::rdf::CodeNode::members_if</a>.</p>


<p>Referenced by <a href="#ab9295f6b6829636049842aad2b53ae0e">getEntryBlock</a>.</p>

</div>
</div>

### getCode() {#a0123488d523150e7f7f0a109d248481a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFunction * llvm::rdf::FuncNode::getCode ()</td>
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



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/structs/llvm/rdf/codenode/#afa2a593357e2580338d13e86b553f6c2">llvm::rdf::CodeNode::getCode</a>.</p>


<p>Referenced by <a href="#ab9295f6b6829636049842aad2b53ae0e">getEntryBlock</a>.</p>

</div>
</div>

### getEntryBlock() {#ab9295f6b6829636049842aad2b53ae0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Block llvm::rdf::FuncNode::getEntryBlock (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/rdf/dataflowgraph">DataFlowGraph</a> &amp; G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a>, definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a>.</p>


<p>References <a href="#a9d0ffbd3083be7cd886e1714817492c8">findBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#ac8ca28de0f4dcee651340e7ef0c45233">llvm::MachineFunction::front</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a> and <a href="#a0123488d523150e7f7f0a109d248481a">getCode</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/rdfgraph-h">RDFGraph.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/rdfgraph-cpp">RDFGraph.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
