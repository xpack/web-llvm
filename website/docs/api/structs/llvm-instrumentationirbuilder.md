---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/instrumentationirbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InstrumentationIRBuilder` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::InstrumentationIRBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">llvm/Transforms/Utils/Instrumentation.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder&lt;FolderTy, InserterTy&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This provides a uniform API for creating instructions and inserting them into a basic block: either at the end of a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, or at a specific iterator location in a block. <a href="/web-llvm/docs/api/classes/llvm/irbuilder/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a448f037b3ebf53dbba70a9ce7a89cad4">InstrumentationIRBuilder</a> (Instruction *IP)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146c26005656a7c2a79168ab63b5b9fa">InstrumentationIRBuilder</a> (BasicBlock *BB, BasicBlock::iterator It)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaa832739cdac826e2ffa713d3b4787a">ensureDebugInfo</a> (IRBuilder&lt;&gt; &amp;IRB, const Function &amp;F)</td>
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


<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">Instrumentation.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InstrumentationIRBuilder() {#a448f037b3ebf53dbba70a9ce7a89cad4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrumentationIRBuilder::InstrumentationIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IP)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">Instrumentation.h</a>.</p>


<p>References <a href="#acaa832739cdac826e2ffa713d3b4787a">ensureDebugInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilder/#afdcde0e677ccb2ad5b4d67a510da2972">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder</a>.</p>

</div>
</div>

### InstrumentationIRBuilder() {#a146c26005656a7c2a79168ab63b5b9fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InstrumentationIRBuilder::InstrumentationIRBuilder (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> It)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">Instrumentation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a03e7efde4d4b8c00e4d8431329383236">llvm::IRBuilderBase::BB</a>, <a href="#acaa832739cdac826e2ffa713d3b4787a">ensureDebugInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilder/#afdcde0e677ccb2ad5b4d67a510da2972">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### ensureDebugInfo() {#acaa832739cdac826e2ffa713d3b4787a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstrumentationIRBuilder::ensureDebugInfo (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">Instrumentation.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a90a3242eeb2a7d1afbb5ab5bc5bfb20d">llvm::IRBuilderBase::getCurrentDebugLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilder/#afdcde0e677ccb2ad5b4d67a510da2972">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a63fc74646456a3bed261512f21efe29c">llvm::IRBuilderBase::SetCurrentDebugLocation</a>.</p>


<p>Referenced by <a href="#a146c26005656a7c2a79168ab63b5b9fa">InstrumentationIRBuilder</a>, <a href="#a448f037b3ebf53dbba70a9ce7a89cad4">InstrumentationIRBuilder</a> and <a href="/web-llvm/docs/api/structs/anonymous-threadsanitizer-cpp-/threadsanitizer/#a41fe353d57c56ba3f43b66143ff436b0">anonymous{ThreadSanitizer.cpp}::ThreadSanitizer::sanitizeFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/instrumentation-h">Instrumentation.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
