---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/sandboxir/callbrinst
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallBrInst` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::sandboxir::CallBrInst { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">llvm/SandboxIR/Instruction.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbase">CallBase</a></td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b8a956b26759a069f734a4c05098f7">CallBrInst</a> (llvm::Instruction *I, Context &amp;Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a2458ac81cb773c5f611902e443dba72a">Context::createCallBrInst()</a>. <a href="#a98b8a956b26759a069f734a4c05098f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60afd77ed9c48a0109fdcfbe607a72d9">getNumIndirectDests</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16051f2944e19b0677756fa6a33cb114">getIndirectDestLabel</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03e31b2a1e5a8deac89f0d539d7c8402">getIndirectDestLabelUse</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d0032ec292a7ce49c40429f25169ab4">getDefaultDest</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac31ddbf08d7b91e02a3c1e1174e375ba">getIndirectDest</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf7ddcb05ac186b8103046cdfc33c92d">getIndirectDests</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdfa4eb1abdb113270c1056c1d408e37">setDefaultDest</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5429a3e17e312e51080e56c3c90c9fa4">setIndirectDest</a> (unsigned Idx, BasicBlock *BB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bc461b29a52f3892c820753f2ca408a">getSuccessor</a> (unsigned Idx) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef6fe81d8d3f1375fd42f4e8a9cdbc75">getNumSuccessors</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/sandboxir/callbrinst">CallBrInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a069a75c5c01de3e8de423d71e219ec3c">create</a> (FunctionType *FTy, Value *Func, BasicBlock *DefaultDest, ArrayRef&lt; BasicBlock * &gt; IndirectDests, ArrayRef&lt; Value * &gt; Args, InsertPosition Pos, Context &amp;Ctx, const Twine &amp;NameStr="")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ac3693ee11b25a5b88de34b6ce0322e">classof</a> (const Value *From)</td>
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


<p>Definition at line 1475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Context {#ac26c806e60ca4a0547680edb68f6e39b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a60f87746e4945fda7ea3d5a983c9b62c">llvm::sandboxir::BasicBlock</a>, <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>.</p>


<p>Referenced by <a href="#ac26c806e60ca4a0547680edb68f6e39b">Context</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### CallBrInst() {#a98b8a956b26759a069f734a4c05098f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::sandboxir::CallBrInst::CallBrInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">llvm::Instruction</a> * I, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx)</td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/sandboxir/use">Use</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a2458ac81cb773c5f611902e443dba72a">Context::createCallBrInst()</a>.</p>


<p>Don't call the constructor directly.</p>


<p>Definition at line 1478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getDefaultDest() {#a5d0032ec292a7ce49c40429f25169ab4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::sandboxir::CallBrInst::getDefaultDest ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1497 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 600 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a60f87746e4945fda7ea3d5a983c9b62c">llvm::sandboxir::BasicBlock</a>.</p>

</div>
</div>

### getIndirectDest() {#ac31ddbf08d7b91e02a3c1e1174e375ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::sandboxir::CallBrInst::getIndirectDest (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a60f87746e4945fda7ea3d5a983c9b62c">llvm::sandboxir::BasicBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>

</div>
</div>

### getIndirectDestLabel() {#a16051f2944e19b0677756fa6a33cb114}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::CallBrInst::getIndirectDestLabel (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1495 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="#a16051f2944e19b0677756fa6a33cb114">getIndirectDestLabel</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="#a16051f2944e19b0677756fa6a33cb114">getIndirectDestLabel</a>.</p>

</div>
</div>

### getIndirectDestLabelUse() {#a03e31b2a1e5a8deac89f0d539d7c8402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::sandboxir::CallBrInst::getIndirectDestLabelUse (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a4705ee51ec0da1ba978f2353d2c47f27">llvm::sandboxir::Value::Ctx</a>, <a href="#a03e31b2a1e5a8deac89f0d539d7c8402">getIndirectDestLabelUse</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>


<p>Referenced by <a href="#a03e31b2a1e5a8deac89f0d539d7c8402">getIndirectDestLabelUse</a>.</p>

</div>
</div>

### getIndirectDests() {#acf7ddcb05ac186b8103046cdfc33c92d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SmallVector&lt; BasicBlock *, 16 &gt; llvm::sandboxir::CallBrInst::getIndirectDests ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1499 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

### getNumIndirectDests() {#a60afd77ed9c48a0109fdcfbe607a72d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::CallBrInst::getNumIndirectDests ()</td>
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



<p>Definition at line 1492 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getNumSuccessors() {#aef6fe81d8d3f1375fd42f4e8a9cdbc75}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::sandboxir::CallBrInst::getNumSuccessors ()</td>
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



<p>Definition at line 1503 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a> and <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a0c4530f3c64d8c2eafac20fb87105d8a">llvm::sandboxir::Value::Val</a>.</p>

</div>
</div>

### getSuccessor() {#a2bc461b29a52f3892c820753f2ca408a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock * llvm::sandboxir::CallBrInst::getSuccessor (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1502 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 629 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a60f87746e4945fda7ea3d5a983c9b62c">llvm::sandboxir::BasicBlock</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>.</p>

</div>
</div>

### setDefaultDest() {#afdfa4eb1abdb113270c1056c1d408e37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::CallBrInst::setDefaultDest (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1500 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/sandboxir/#a60f87746e4945fda7ea3d5a983c9b62c">llvm::sandboxir::BasicBlock</a>.</p>

</div>
</div>

### setIndirectDest() {#a5429a3e17e312e51080e56c3c90c9fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::sandboxir::CallBrInst::setIndirectDest (unsigned Idx, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1501 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 621 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a3ac3693ee11b25a5b88de34b6ce0322e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::sandboxir::CallBrInst::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * From)</td>
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



<p>Definition at line 1489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value/#a27b9af008c6420f3340805e50297f9fb">llvm::sandboxir::Value::getSubclassID</a>.</p>

</div>
</div>

### create() {#a069a75c5c01de3e8de423d71e219ec3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallBrInst * llvm::sandboxir::CallBrInst::create (<a href="/web-llvm/docs/api/classes/llvm/sandboxir/functiontype">FunctionType</a> * FTy, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * Func, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * DefaultDest, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * &gt; IndirectDests, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/sandboxir/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/insertposition">InsertPosition</a> Pos, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context">Context</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; NameStr="")</td>
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



<p>Declaration at line 1484 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a>, definition at line 570 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/sandboxir/instruction-h">Instruction.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/instruction-cpp">Instruction.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
