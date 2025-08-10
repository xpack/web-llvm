---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/irbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IRBuilder` Class Template

<p>This provides a uniform API for creating instructions and inserting them into a basic block: either at the end of a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, or at a specific iterator location in a block. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;
class llvm::IRBuilder&lt;FolderTy, InserterTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">llvm/IR/IRBuilder.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilderbase">IRBuilderBase</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common base class shared among various IRBuilders. <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/nextnodeirbuilder">NextNodeIRBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class to attach debug information of the given instruction onto new instructions inserted after. <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/nextnodeirbuilder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/instrumentationirbuilder">InstrumentationIRBuilder</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#afdcde0e677ccb2ad5b4d67a510da2972">IRBuilder</a> (LLVMContext &amp;C, FolderTy Folder, InserterTy Inserter=InserterTy(), MDNode *FPMathTag=nullptr, ArrayRef&lt; OperandBundleDef &gt; OpBundles={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a04288de84a757f2857bf1becf58fb667">IRBuilder</a> (LLVMContext &amp;C, MDNode *FPMathTag=nullptr, ArrayRef&lt; OperandBundleDef &gt; OpBundles={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae3e12d952891d67b75f5c911d8d0cf3b">IRBuilder</a> (BasicBlock *TheBB, FolderTy Folder, MDNode *FPMathTag=nullptr, ArrayRef&lt; OperandBundleDef &gt; OpBundles={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#affb3b703562007817b2f6524f7b91640">IRBuilder</a> (BasicBlock *TheBB, MDNode *FPMathTag=nullptr, ArrayRef&lt; OperandBundleDef &gt; OpBundles={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aa0c387324b2bd5b71623f26480f58cec">IRBuilder</a> (Instruction *IP, MDNode *FPMathTag=nullptr, ArrayRef&lt; OperandBundleDef &gt; OpBundles={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ae7109dbd34956afb56532463d27f795a">IRBuilder</a> (BasicBlock *TheBB, BasicBlock::iterator IP, FolderTy Folder, MDNode *FPMathTag=nullptr, ArrayRef&lt; OperandBundleDef &gt; OpBundles={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#aff654855a2909901cd84a3f7dc68a502">IRBuilder</a> (BasicBlock *TheBB, BasicBlock::iterator IP, MDNode *FPMathTag=nullptr, ArrayRef&lt; OperandBundleDef &gt; OpBundles={})</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a1d855b4f198564f1a415e8f8dae038d3">IRBuilder</a> (const IRBuilder &amp;)=delete</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Avoid copying the full <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>. <a href="#a1d855b4f198564f1a415e8f8dae038d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">InserterTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b7810474e93491ff49e693464df1800">getInserter</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> InserterTy &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeee8096cd576f21f56b74874dd61bfc2">getInserter</a> () const</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">FolderTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad44060a0026fac6410e5d0faf053de5f">Folder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt; ... &gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">InserterTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8119053277340f0f3445d199b6f2986a">Inserter</a></td>
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

<p>This provides a uniform API for creating instructions and inserting them into a basic block: either at the end of a <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, or at a specific iterator location in a block.</p>


<p>Note that the builder does not expose the full generality of LLVM instructions. For access to extra instruction properties, use the mutators (e.g. setVolatile) on the instructions after they have been created. Convenience state exists to specify fast-math flags and fp-math tags.</p>


<p>The first template argument specifies a class to use for creating constants. This defaults to creating minimally folded constants. The second template argument allows clients to specify custom insertion hooks that are called on every newly created insertion.</p>


<p>Definition at line 2705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IRBuilder() {#afdcde0e677ccb2ad5b4d67a510da2972}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, FolderTy Folder, InserterTy Inserter=InserterTy(), <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * FPMathTag=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; OpBundles={})</td>
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



<p>Definition at line 2711 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/instrumentationirbuilder/#acaa832739cdac826e2ffa713d3b4787a">llvm::InstrumentationIRBuilder::ensureDebugInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/instrumentationirbuilder/#a146c26005656a7c2a79168ab63b5b9fa">llvm::InstrumentationIRBuilder::InstrumentationIRBuilder</a>, <a href="/web-llvm/docs/api/structs/llvm/instrumentationirbuilder/#a448f037b3ebf53dbba70a9ce7a89cad4">llvm::InstrumentationIRBuilder::InstrumentationIRBuilder</a> and <a href="/web-llvm/docs/api/classes/anonymous-memorysanitizer-cpp-/nextnodeirbuilder/#a0069210926fba78c824a7a41edee915f">anonymous{MemorySanitizer.cpp}::NextNodeIRBuilder::NextNodeIRBuilder</a>.</p>

</div>
</div>

### IRBuilder() {#a04288de84a757f2857bf1becf58fb667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * FPMathTag=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; OpBundles={})</td>
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



<p>Definition at line 2717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### IRBuilder() {#ae3e12d952891d67b75f5c911d8d0cf3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * TheBB, FolderTy Folder, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * FPMathTag=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; OpBundles={})</td>
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



<p>Definition at line 2721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### IRBuilder() {#affb3b703562007817b2f6524f7b91640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * TheBB, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * FPMathTag=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; OpBundles={})</td>
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



<p>Definition at line 2730 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### IRBuilder() {#aa0c387324b2bd5b71623f26480f58cec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * IP, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * FPMathTag=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; OpBundles={})</td>
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



<p>Definition at line 2737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### IRBuilder() {#ae7109dbd34956afb56532463d27f795a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * TheBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP, FolderTy Folder, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * FPMathTag=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; OpBundles={})</td>
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



<p>Definition at line 2744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### IRBuilder() {#aff654855a2909901cd84a3f7dc68a502}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * TheBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * FPMathTag=nullptr, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#aa97c65466bdd34abda6772dd32eb5d19">OperandBundleDef</a> &gt; OpBundles={})</td>
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



<p>Definition at line 2753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### IRBuilder() {#a1d855b4f198564f1a415e8f8dae038d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::IRBuilder (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Avoid copying the full <a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>.</p>


<p>Prefer using <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/insertpointguard">InsertPointGuard</a> or <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/fastmathflagguard">FastMathFlagGuard</a> instead.</p>


<p>Definition at line 2763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getInserter() {#a8b7810474e93491ff49e693464df1800}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InserterTy &amp; llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::getInserter ()</td>
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



<p>Definition at line 2765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### getInserter() {#aeee8096cd576f21f56b74874dd61bfc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const InserterTy &amp; llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::getInserter ()</td>
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



<p>Definition at line 2766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Folder {#ad44060a0026fac6410e5d0faf053de5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FolderTy llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::Folder</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2707 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

### Inserter {#a8119053277340f0f3445d199b6f2986a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename FolderTy = ConstantFolder, typename InserterTy = IRBuilderDefaultInserter&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InserterTy llvm::IRBuilder&lt; FolderTy, InserterTy &gt;::Inserter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2708 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/irbuilder-h">IRBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
