---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/instvisitor
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `InstVisitor` Class Template

<p>Base class for instruction visitors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SubClass, typename RetTy = void&gt;
class llvm::InstVisitor&lt;SubClass, RetTy&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">llvm/IR/InstVisitor.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for visitors over the uses of a pointer value. <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for visitors over the uses of a pointer value. <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor">PtrUseVisitor&lt;DerivedT&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for visitors over the uses of a pointer value. <a href="/web-llvm/docs/api/classes/llvm/ptrusevisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class Iterator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6352e72d11377a9c62f24434ae869bf0">visit</a> (Iterator Start, Iterator End)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac65283ef740efaf1df62007f005ae159">visit</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7fc7bda51e1ba67ee687930d54ab7625">visit</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae28ae8847a062e9113dbbc6a1db6861">visit</a> (BasicBlock &amp;BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2967814be7886dba5eef0b8173a729d8">visit</a> (Module *M)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8066337003f855a1de7cd91e256ec12">visit</a> (Function *F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa4c8b67cbdf055eb17ee775a6b3e4f4e">visit</a> (BasicBlock *BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a698c79d59fe5bd5642ee647383c1e839">visit</a> (Instruction *I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a30c7db851b91924de0e46c8d72375be9">visit</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ada43dc65752febf34c718d21983d32ce">visitModule</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a23d3f70bb5fdbf71476d26f5fd17441a">visitFunction</a> (Function &amp;F)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a47268f9ec6c20215143e8ac1f30f0cfe">visitBasicBlock</a> (BasicBlock &amp;BB)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2b9d4f06e4126f2fbbc10a71c19a9d3">visitICmpInst</a> (ICmpInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15f219103dc6b25a859d629b0f1c0917">visitFCmpInst</a> (FCmpInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab89f81b6570d21fd7eefa7b09439c149">visitAllocaInst</a> (AllocaInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8829e5fbad4f9606b5b6c0b100493c5">visitLoadInst</a> (LoadInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8f006d606ec21cb0e454912ce36d17d8">visitStoreInst</a> (StoreInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4e7bf5ec2426970bd86bcd8599e9f89c">visitAtomicCmpXchgInst</a> (AtomicCmpXchgInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa9a8ed9a3652337776d1812cf9c7059b">visitAtomicRMWInst</a> (AtomicRMWInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af738b980e998639ba3fd8d7f7893711c">visitFenceInst</a> (FenceInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aefd0a9d7224ad6eb0a24c20197c5dc53">visitGetElementPtrInst</a> (GetElementPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6b5f364cdf10081c74343b149fbc325f">visitPHINode</a> (PHINode &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2301fc6526da21ff42ecb733dfaf95d9">visitTruncInst</a> (TruncInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#afc055d8c7e9e2f430f19b2f6887d1d37">visitZExtInst</a> (ZExtInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a593a97b3a33a03397ab24c42049cb011">visitSExtInst</a> (SExtInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab7c5ff480bab1f39d52fc492194ad641">visitFPTruncInst</a> (FPTruncInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac268c92fdf2bf24b67ddbdf8e7d25a70">visitFPExtInst</a> (FPExtInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a86b8d0f19a5db86d56c0ae4050b13a50">visitFPToUIInst</a> (FPToUIInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a11c6aea9cef4bcd537d4b63a47f3540b">visitFPToSIInst</a> (FPToSIInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af332042b4c6d937cb7b58c48a64ffd97">visitUIToFPInst</a> (UIToFPInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abb8bc66ad0815944c7770346e789ec83">visitSIToFPInst</a> (SIToFPInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0cc6a72ad7d27065b1ad1c5d0b2cac21">visitPtrToIntInst</a> (PtrToIntInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a57ec53e925ab39d499405e2428fff31f">visitIntToPtrInst</a> (IntToPtrInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5b052a3578e5c55ba04a8e8e87d7d584">visitBitCastInst</a> (BitCastInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab39b720f77593cfa9c056431b6bc3714">visitAddrSpaceCastInst</a> (AddrSpaceCastInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb67eff747cfcdb17ca1079aff8ed9ca">visitSelectInst</a> (SelectInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af8f7dfddc1f55fb738f00a43270bce5e">visitVAArgInst</a> (VAArgInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a6290ef96ff3b08c0e463afef012ac9">visitExtractElementInst</a> (ExtractElementInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa3db7419445c212f612d809c7b92300b">visitInsertElementInst</a> (InsertElementInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a45623fa4891c507f3b430bcc3b2e7a90">visitShuffleVectorInst</a> (ShuffleVectorInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7b3008f24e9985fd9b427cbf65898e0a">visitExtractValueInst</a> (ExtractValueInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f8025addd1e435a612fc680fe4e65e1">visitInsertValueInst</a> (InsertValueInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a46ccc0f15a7079d10ec5ed554ed459dc">visitLandingPadInst</a> (LandingPadInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa352484fecc3e8e3e2afc97e30aee410">visitFuncletPadInst</a> (FuncletPadInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a61d3f7692decd5e4c52ff2e38f2f82b5">visitCleanupPadInst</a> (CleanupPadInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a32edf0d6349ce5d846f8471a909f5182">visitCatchPadInst</a> (CatchPadInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a092dc67ced79a88abe201ea46da32de5">visitFreezeInst</a> (FreezeInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae9f6d19db01b61de6e0ae70fdf4e1fd7">visitDbgDeclareInst</a> (DbgDeclareInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aae5e79758347bcf52f16c2c90a2b5c4c">visitDbgValueInst</a> (DbgValueInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae151028ffcbe839b57acfb3895b6f705">visitDbgVariableIntrinsic</a> (DbgVariableIntrinsic &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8d23862d4863dfc9c17eeba75baa5fe2">visitDbgLabelInst</a> (DbgLabelInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a16a6087f3368aa0f9f25b5dcc6e85688">visitDbgInfoIntrinsic</a> (DbgInfoIntrinsic &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad401dce38c15719e37382c854618dd15">visitMemSetInst</a> (MemSetInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9dbd696d10f57db2ba417aeb4deccb4">visitMemSetInlineInst</a> (MemSetInlineInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac9c2e0fa94f0314f41ff580962b31deb">visitMemSetPatternInst</a> (MemSetPatternInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1d0bcd4737de80bdaaa85e094b102d97">visitMemCpyInst</a> (MemCpyInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9ecca3f390d384ef182978a68e60be25">visitMemCpyInlineInst</a> (MemCpyInlineInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa883c5b93d6c4f4bf058abd06306a299">visitMemMoveInst</a> (MemMoveInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acaad755824bda1ce0066749c8655d3df">visitMemTransferInst</a> (MemTransferInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0e3132f8f6a1e2d04287ad74a64766f3">visitMemIntrinsic</a> (MemIntrinsic &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1b8bec4e74a7318b69a421e8df11bb41">visitVAStartInst</a> (VAStartInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7cefcc06639ac482ae979e1703a1b3fc">visitVAEndInst</a> (VAEndInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a132027e36e429b65a9a6a245f4fc8eae">visitVACopyInst</a> (VACopyInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a432d533de0923ad3b0fd6dfc22c7ebd6">visitIntrinsicInst</a> (IntrinsicInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad52d3da08557d933a3555611b0cbf33b">visitCallInst</a> (CallInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a102d96db537eef02feda77636663eafb">visitInvokeInst</a> (InvokeInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02c2e9a2433786968d7851059cb94ed5">visitCallBrInst</a> (CallBrInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6d2afefadb6a03b00d1bd6c6e6f58054">visitReturnInst</a> (ReturnInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aeb47dccb3d4b225460702b067e783d4f">visitBranchInst</a> (BranchInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5c4c1a1ece6f2adc18f686648c1947eb">visitSwitchInst</a> (SwitchInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a06182f380e2e1736e6ae593c4304cda8">visitIndirectBrInst</a> (IndirectBrInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac0683ed7b73154d4da7968c87eb30150">visitResumeInst</a> (ResumeInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a493ba72f6175aa590987ecf0d7065511">visitUnreachableInst</a> (UnreachableInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2b239b5535ce1aa2df21ec5f409f45c7">visitCleanupReturnInst</a> (CleanupReturnInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac2fea11a3959716bfb37b820c26d4f1e">visitCatchReturnInst</a> (CatchReturnInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ade28897d1282787e8a10eb5b3ab15a2d">visitCatchSwitchInst</a> (CatchSwitchInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1a1f70533fc480e3cad75489388477cc">visitTerminator</a> (Instruction &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adfea612bdc5ce7d2f5f1c08e979a152c">visitCastInst</a> (CastInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8c877135fb038567546d01c269d519ed">visitUnaryOperator</a> (UnaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab9647b10528628944657473a225932bb">visitBinaryOperator</a> (BinaryOperator &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0da94277ceb54c8aee12739104aaa2df">visitCmpInst</a> (CmpInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab199d37220dd0341361cd45229981d60">visitUnaryInstruction</a> (UnaryInstruction &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a22ae80c2045ac48274ba65b1d91d89e7">visitCallBase</a> (CallBase &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af7fc294424421c8b8e16185bd9bc7f8f">visitInstruction</a> (Instruction &amp;I)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#af121c0450f32f983e87b483c15ca2b10">delegateCallInst</a> (CallInst &amp;I)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SubClass, typename RetTy = void&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">RetTy</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9a368e6d2d74bc048a78b26cc84cc2bc">delegateCallInst</a> (Instruction &amp;I)</td>
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

<p>Base class for instruction visitors.</p>


<p><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> visitors are used when you want to perform different actions for different kinds of instructions without having to use lots of casts and a big switch statement (in your code, that is).</p>


<p>To define your own visitor, inherit from this class, specifying your new type for the 'SubClass' template parameter, and "override" visitXXX functions in your class. I say "override" because this class is defined in terms of statically resolved overloading, not virtual functions.</p>


<p>For example, here is a visitor that counts the number of malloc instructions processed:</p>


<p>/// Declare the class. Note that we derive from <a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor</a> instantiated /// with <em>our new subclasses</em> type. /// struct CountAllocaVisitor : public <a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor&lt;CountAllocaVisitor&gt;</a> { unsigned Count; CountAllocaVisitor() : <a href="/web-llvm/docs/api/namespaces/llvm/#a845e08be4b0320d66901a66b0c0e9509">Count(0)</a> {}</p>


<p>void <a href="#ab89f81b6570d21fd7eefa7b09439c149">visitAllocaInst(AllocaInst &amp;AI)</a> { ++Count; } };</p>


<p>And this class would be used like this: CountAllocaVisitor CAV; CAV.visit(function); NumAllocas = CAV.Count;</p>


<p>The defined has 'visit' methods for <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a>, and also for <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>, and <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, which recursively process all contained instructions.</p>


<p>Note that if you don't implement visitXXX for some instruction type, the visitXXX method for instruction superclass will be invoked. So if instructions are added in the future, they will be automatically supported, if you handle one of their superclasses.</p>


<p>The optional second template argument specifies the type that instruction visitation functions should return. If you specify this, you <em>MUST</em> provide an implementation of visitInstruction though!.</p>


<p>Note that this class is specifically designed as a template to avoid virtual function call overhead. Defining and using an <a href="/web-llvm/docs/api/classes/llvm/instvisitor">InstVisitor</a> is just as efficient as having your own switch statement over the instruction opcode.</p>


<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### visit() {#a6352e72d11377a9c62f24434ae869bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class Iterator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (Iterator Start, Iterator End)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a176c662ef638785a96bf45d8c269b471">llvm::findIndirectCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abeedae71cf0cc7b944516eb98738b488">llvm::findVTableAddrs</a>, <a href="/web-llvm/docs/api/classes/anonymous-instcount-cpp-/instcount/#a2f6d5d0af5c247dfbf0a42a84559ec23">anonymous{InstCount.cpp}::InstCount::InstVisitor&lt; InstCount &gt;</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a8605e39e73fa355574fd811094481af4">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a1574d36e9a8ab92a5481fa4d754a80ed">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visit</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a640527ab9d6976053dcc136f4ac23b76">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visit</a>, <a href="/web-llvm/docs/api/classes/datascalarizervisitor/#ad628515150fb7ac12fd0e45d3ef93afc">DataScalarizerVisitor::visit</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/anonymous-spillutils-cpp-/anonymous-spillutils-cpp-/allocausevisitor/#a9c6e21ecfcb258d3ec0f43046e5e5d29">llvm::coro::anonymous{SpillUtils.cpp}::anonymous{SpillUtils.cpp}::AllocaUseVisitor::visit</a>, <a href="#aae28ae8847a062e9113dbbc6a1db6861">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>, <a href="#a7fc7bda51e1ba67ee687930d54ab7625">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>, <a href="#a6352e72d11377a9c62f24434ae869bf0">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>, <a href="#ac65283ef740efaf1df62007f005ae159">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a> and <a href="/web-llvm/docs/api/structs/anonymous-nvptxlowerargs-cpp-/argusechecker/#a6d53db8820f5704f0678827ac5314fcb">anonymous{NVPTXLowerArgs.cpp}::ArgUseChecker::visitArgPtr</a>.</p>

</div>
</div>

### visit() {#ac65283ef740efaf1df62007f005ae159}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visit() {#a7fc7bda51e1ba67ee687930d54ab7625}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visit() {#aae28ae8847a062e9113dbbc6a1db6861}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
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



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visit() {#a2967814be7886dba5eef0b8173a729d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> * M)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#a2967814be7886dba5eef0b8173a729d8">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>.</p>

</div>
</div>

### visit() {#af8066337003f855a1de7cd91e256ec12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * F)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#af8066337003f855a1de7cd91e256ec12">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>.</p>

</div>
</div>

### visit() {#aa4c8b67cbdf055eb17ee775a6b3e4f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * BB)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#aa4c8b67cbdf055eb17ee775a6b3e4f4e">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>.</p>

</div>
</div>

### visit() {#a698c79d59fe5bd5642ee647383c1e839}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#a698c79d59fe5bd5642ee647383c1e839">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>.</p>

</div>
</div>

### visit() {#a30c7db851b91924de0e46c8d72375be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visit (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitAddrSpaceCastInst() {#ab39b720f77593cfa9c056431b6bc3714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitAddrSpaceCastInst (<a href="/web-llvm/docs/api/classes/llvm/addrspacecastinst">AddrSpaceCastInst</a> &amp; I)</td>
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



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitAllocaInst() {#ab89f81b6570d21fd7eefa7b09439c149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitAllocaInst (<a href="/web-llvm/docs/api/classes/llvm/allocainst">AllocaInst</a> &amp; I)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitAtomicCmpXchgInst() {#a4e7bf5ec2426970bd86bcd8599e9f89c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitAtomicCmpXchgInst (<a href="/web-llvm/docs/api/classes/llvm/atomiccmpxchginst">AtomicCmpXchgInst</a> &amp; I)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitAtomicRMWInst() {#aa9a8ed9a3652337776d1812cf9c7059b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitAtomicRMWInst (<a href="/web-llvm/docs/api/classes/llvm/atomicrmwinst">AtomicRMWInst</a> &amp; I)</td>
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



<p>Definition at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitBasicBlock() {#a47268f9ec6c20215143e8ac1f30f0cfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitBasicBlock (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB)</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#aae28ae8847a062e9113dbbc6a1db6861">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>.</p>

</div>
</div>

### visitBinaryOperator() {#ab9647b10528628944657473a225932bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitBinaryOperator (<a href="/web-llvm/docs/api/classes/llvm/binaryoperator">BinaryOperator</a> &amp; I)</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitBitCastInst() {#a5b052a3578e5c55ba04a8e8e87d7d584}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitBitCastInst (<a href="/web-llvm/docs/api/classes/llvm/bitcastinst">BitCastInst</a> &amp; I)</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitBranchInst() {#aeb47dccb3d4b225460702b067e783d4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitBranchInst (<a href="/web-llvm/docs/api/classes/llvm/branchinst">BranchInst</a> &amp; I)</td>
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



<p>Definition at line 232 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCallBase() {#a22ae80c2045ac48274ba65b1d91d89e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCallBase (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; I)</td>
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



<p>Definition at line 270 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCallBrInst() {#a02c2e9a2433786968d7851059cb94ed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCallBrInst (<a href="/web-llvm/docs/api/classes/llvm/callbrinst">CallBrInst</a> &amp; I)</td>
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



<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCallInst() {#ad52d3da08557d933a3555611b0cbf33b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCallInst (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
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



<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCastInst() {#adfea612bdc5ce7d2f5f1c08e979a152c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCastInst (<a href="/web-llvm/docs/api/classes/llvm/castinst">CastInst</a> &amp; I)</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCatchPadInst() {#a32edf0d6349ce5d846f8471a909f5182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCatchPadInst (<a href="/web-llvm/docs/api/classes/llvm/catchpadinst">CatchPadInst</a> &amp; I)</td>
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



<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCatchReturnInst() {#ac2fea11a3959716bfb37b820c26d4f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCatchReturnInst (<a href="/web-llvm/docs/api/classes/llvm/catchreturninst">CatchReturnInst</a> &amp; I)</td>
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



<p>Definition at line 250 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCatchSwitchInst() {#ade28897d1282787e8a10eb5b3ab15a2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCatchSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/catchswitchinst">CatchSwitchInst</a> &amp; I)</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCleanupPadInst() {#a61d3f7692decd5e4c52ff2e38f2f82b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCleanupPadInst (<a href="/web-llvm/docs/api/classes/llvm/cleanuppadinst">CleanupPadInst</a> &amp; I)</td>
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



<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCleanupReturnInst() {#a2b239b5535ce1aa2df21ec5f409f45c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCleanupReturnInst (<a href="/web-llvm/docs/api/classes/llvm/cleanupreturninst">CleanupReturnInst</a> &amp; I)</td>
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



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitCmpInst() {#a0da94277ceb54c8aee12739104aaa2df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitCmpInst (<a href="/web-llvm/docs/api/classes/llvm/cmpinst">CmpInst</a> &amp; I)</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitDbgDeclareInst() {#ae9f6d19db01b61de6e0ae70fdf4e1fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitDbgDeclareInst (<a href="/web-llvm/docs/api/classes/llvm/dbgdeclareinst">DbgDeclareInst</a> &amp; I)</td>
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



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitDbgInfoIntrinsic() {#a16a6087f3368aa0f9f25b5dcc6e85688}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitDbgInfoIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/dbginfointrinsic">DbgInfoIntrinsic</a> &amp; I)</td>
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



<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitDbgLabelInst() {#a8d23862d4863dfc9c17eeba75baa5fe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitDbgLabelInst (<a href="/web-llvm/docs/api/classes/llvm/dbglabelinst">DbgLabelInst</a> &amp; I)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitDbgValueInst() {#aae5e79758347bcf52f16c2c90a2b5c4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitDbgValueInst (<a href="/web-llvm/docs/api/classes/llvm/dbgvalueinst">DbgValueInst</a> &amp; I)</td>
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



<p>Definition at line 204 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitDbgVariableIntrinsic() {#ae151028ffcbe839b57acfb3895b6f705}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitDbgVariableIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic">DbgVariableIntrinsic</a> &amp; I)</td>
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



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitExtractElementInst() {#a1a6290ef96ff3b08c0e463afef012ac9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitExtractElementInst (<a href="/web-llvm/docs/api/classes/llvm/extractelementinst">ExtractElementInst</a> &amp; I)</td>
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



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitExtractValueInst() {#a7b3008f24e9985fd9b427cbf65898e0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitExtractValueInst (<a href="/web-llvm/docs/api/classes/llvm/extractvalueinst">ExtractValueInst</a> &amp; I)</td>
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



<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFCmpInst() {#a15f219103dc6b25a859d629b0f1c0917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFCmpInst (<a href="/web-llvm/docs/api/classes/llvm/fcmpinst">FCmpInst</a> &amp; I)</td>
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



<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFenceInst() {#af738b980e998639ba3fd8d7f7893711c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFenceInst (<a href="/web-llvm/docs/api/classes/llvm/fenceinst">FenceInst</a> &amp; I)</td>
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



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFPExtInst() {#ac268c92fdf2bf24b67ddbdf8e7d25a70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFPExtInst (<a href="/web-llvm/docs/api/classes/llvm/fpextinst">FPExtInst</a> &amp; I)</td>
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



<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFPToSIInst() {#a11c6aea9cef4bcd537d4b63a47f3540b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFPToSIInst (<a href="/web-llvm/docs/api/classes/llvm/fptosiinst">FPToSIInst</a> &amp; I)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFPToUIInst() {#a86b8d0f19a5db86d56c0ae4050b13a50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFPToUIInst (<a href="/web-llvm/docs/api/classes/llvm/fptouiinst">FPToUIInst</a> &amp; I)</td>
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



<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFPTruncInst() {#ab7c5ff480bab1f39d52fc492194ad641}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFPTruncInst (<a href="/web-llvm/docs/api/classes/llvm/fptruncinst">FPTruncInst</a> &amp; I)</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFreezeInst() {#a092dc67ced79a88abe201ea46da32de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFreezeInst (<a href="/web-llvm/docs/api/classes/llvm/freezeinst">FreezeInst</a> &amp; I)</td>
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



<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFuncletPadInst() {#aa352484fecc3e8e3e2afc97e30aee410}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFuncletPadInst (<a href="/web-llvm/docs/api/classes/llvm/funcletpadinst">FuncletPadInst</a> &amp; I)</td>
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



<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitFunction() {#a23d3f70bb5fdbf71476d26f5fd17441a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#a7fc7bda51e1ba67ee687930d54ab7625">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>.</p>

</div>
</div>

### visitGetElementPtrInst() {#aefd0a9d7224ad6eb0a24c20197c5dc53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitGetElementPtrInst (<a href="/web-llvm/docs/api/classes/llvm/getelementptrinst">GetElementPtrInst</a> &amp; I)</td>
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



<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitICmpInst() {#ac2b9d4f06e4126f2fbbc10a71c19a9d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitICmpInst (<a href="/web-llvm/docs/api/classes/llvm/icmpinst">ICmpInst</a> &amp; I)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitIndirectBrInst() {#a06182f380e2e1736e6ae593c4304cda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitIndirectBrInst (<a href="/web-llvm/docs/api/classes/llvm/indirectbrinst">IndirectBrInst</a> &amp; I)</td>
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



<p>Definition at line 238 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitInsertElementInst() {#aa3db7419445c212f612d809c7b92300b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitInsertElementInst (<a href="/web-llvm/docs/api/classes/llvm/insertelementinst">InsertElementInst</a> &amp; I)</td>
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



<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitInsertValueInst() {#a2f8025addd1e435a612fc680fe4e65e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitInsertValueInst (<a href="/web-llvm/docs/api/classes/llvm/insertvalueinst">InsertValueInst</a> &amp; I)</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitInstruction() {#af7fc294424421c8b8e16185bd9bc7f8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitInstruction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitIntrinsicInst() {#a432d533de0923ad3b0fd6dfc22c7ebd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitIntrinsicInst (<a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> &amp; I)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitIntToPtrInst() {#a57ec53e925ab39d499405e2428fff31f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitIntToPtrInst (<a href="/web-llvm/docs/api/classes/llvm/inttoptrinst">IntToPtrInst</a> &amp; I)</td>
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



<p>Definition at line 186 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitInvokeInst() {#a102d96db537eef02feda77636663eafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitInvokeInst (<a href="/web-llvm/docs/api/classes/llvm/invokeinst">InvokeInst</a> &amp; I)</td>
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



<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitLandingPadInst() {#a46ccc0f15a7079d10ec5ed554ed459dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitLandingPadInst (<a href="/web-llvm/docs/api/classes/llvm/landingpadinst">LandingPadInst</a> &amp; I)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitLoadInst() {#af8829e5fbad4f9606b5b6c0b100493c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitLoadInst (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> &amp; I)</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemCpyInlineInst() {#a9ecca3f390d384ef182978a68e60be25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemCpyInlineInst (<a href="/web-llvm/docs/api/classes/llvm/memcpyinlineinst">MemCpyInlineInst</a> &amp; I)</td>
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



<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemCpyInst() {#a1d0bcd4737de80bdaaa85e094b102d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemCpyInst (<a href="/web-llvm/docs/api/classes/llvm/memcpyinst">MemCpyInst</a> &amp; I)</td>
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



<p>Definition at line 214 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemIntrinsic() {#a0e3132f8f6a1e2d04287ad74a64766f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemIntrinsic (<a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> &amp; I)</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemMoveInst() {#aa883c5b93d6c4f4bf058abd06306a299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemMoveInst (<a href="/web-llvm/docs/api/classes/llvm/memmoveinst">MemMoveInst</a> &amp; I)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemSetInlineInst() {#ab9dbd696d10f57db2ba417aeb4deccb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemSetInlineInst (<a href="/web-llvm/docs/api/classes/llvm/memsetinlineinst">MemSetInlineInst</a> &amp; I)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemSetInst() {#ad401dce38c15719e37382c854618dd15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemSetInst (<a href="/web-llvm/docs/api/classes/llvm/memsetinst">MemSetInst</a> &amp; I)</td>
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



<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemSetPatternInst() {#ac9c2e0fa94f0314f41ff580962b31deb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemSetPatternInst (<a href="/web-llvm/docs/api/classes/llvm/memsetpatterninst">MemSetPatternInst</a> &amp; I)</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitMemTransferInst() {#acaad755824bda1ce0066749c8655d3df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitMemTransferInst (<a href="/web-llvm/docs/api/classes/llvm/memtransferinst">MemTransferInst</a> &amp; I)</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitModule() {#ada43dc65752febf34c718d21983d32ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
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



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#ac65283ef740efaf1df62007f005ae159">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visit</a>.</p>

</div>
</div>

### visitPHINode() {#a6b5f364cdf10081c74343b149fbc325f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitPHINode (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> &amp; I)</td>
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



<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitPtrToIntInst() {#a0cc6a72ad7d27065b1ad1c5d0b2cac21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitPtrToIntInst (<a href="/web-llvm/docs/api/classes/llvm/ptrtointinst">PtrToIntInst</a> &amp; I)</td>
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



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitResumeInst() {#ac0683ed7b73154d4da7968c87eb30150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitResumeInst (<a href="/web-llvm/docs/api/classes/llvm/resumeinst">ResumeInst</a> &amp; I)</td>
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



<p>Definition at line 241 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitReturnInst() {#a6d2afefadb6a03b00d1bd6c6e6f58054}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitReturnInst (<a href="/web-llvm/docs/api/classes/llvm/returninst">ReturnInst</a> &amp; I)</td>
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



<p>Definition at line 229 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitSelectInst() {#aeb67eff747cfcdb17ca1079aff8ed9ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitSelectInst (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> &amp; I)</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitSExtInst() {#a593a97b3a33a03397ab24c42049cb011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitSExtInst (<a href="/web-llvm/docs/api/classes/llvm/sextinst">SExtInst</a> &amp; I)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitShuffleVectorInst() {#a45623fa4891c507f3b430bcc3b2e7a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitShuffleVectorInst (<a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst">ShuffleVectorInst</a> &amp; I)</td>
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



<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitSIToFPInst() {#abb8bc66ad0815944c7770346e789ec83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitSIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/sitofpinst">SIToFPInst</a> &amp; I)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitStoreInst() {#a8f006d606ec21cb0e454912ce36d17d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitStoreInst (<a href="/web-llvm/docs/api/classes/llvm/storeinst">StoreInst</a> &amp; I)</td>
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



<p>Definition at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitSwitchInst() {#a5c4c1a1ece6f2adc18f686648c1947eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitSwitchInst (<a href="/web-llvm/docs/api/classes/llvm/switchinst">SwitchInst</a> &amp; I)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitTerminator() {#a1a1f70533fc480e3cad75489388477cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitTerminator (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 256 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>


<p>Referenced by <a href="#aeb47dccb3d4b225460702b067e783d4f">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitBranchInst</a>, <a href="#a22ae80c2045ac48274ba65b1d91d89e7">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCallBase</a>, <a href="#ac2fea11a3959716bfb37b820c26d4f1e">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCatchReturnInst</a>, <a href="#ade28897d1282787e8a10eb5b3ab15a2d">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCatchSwitchInst</a>, <a href="#a2b239b5535ce1aa2df21ec5f409f45c7">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitCleanupReturnInst</a>, <a href="#a06182f380e2e1736e6ae593c4304cda8">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitIndirectBrInst</a>, <a href="#ac0683ed7b73154d4da7968c87eb30150">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitResumeInst</a>, <a href="#a6d2afefadb6a03b00d1bd6c6e6f58054">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitReturnInst</a>, <a href="#a5c4c1a1ece6f2adc18f686648c1947eb">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitSwitchInst</a> and <a href="#a493ba72f6175aa590987ecf0d7065511">llvm::InstVisitor&lt; UnrolledInstAnalyzer, bool &gt;::visitUnreachableInst</a>.</p>

</div>
</div>

### visitTruncInst() {#a2301fc6526da21ff42ecb733dfaf95d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitTruncInst (<a href="/web-llvm/docs/api/classes/llvm/truncinst">TruncInst</a> &amp; I)</td>
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



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitUIToFPInst() {#af332042b4c6d937cb7b58c48a64ffd97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitUIToFPInst (<a href="/web-llvm/docs/api/classes/llvm/uitofpinst">UIToFPInst</a> &amp; I)</td>
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



<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitUnaryInstruction() {#ab199d37220dd0341361cd45229981d60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitUnaryInstruction (<a href="/web-llvm/docs/api/classes/llvm/unaryinstruction">UnaryInstruction</a> &amp; I)</td>
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



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitUnaryOperator() {#a8c877135fb038567546d01c269d519ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitUnaryOperator (<a href="/web-llvm/docs/api/classes/llvm/unaryoperator">UnaryOperator</a> &amp; I)</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitUnreachableInst() {#a493ba72f6175aa590987ecf0d7065511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitUnreachableInst (<a href="/web-llvm/docs/api/classes/llvm/unreachableinst">UnreachableInst</a> &amp; I)</td>
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



<p>Definition at line 244 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitVAArgInst() {#af8f7dfddc1f55fb738f00a43270bce5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitVAArgInst (<a href="/web-llvm/docs/api/classes/llvm/vaarginst">VAArgInst</a> &amp; I)</td>
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



<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitVACopyInst() {#a132027e36e429b65a9a6a245f4fc8eae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitVACopyInst (<a href="/web-llvm/docs/api/classes/llvm/vacopyinst">VACopyInst</a> &amp; I)</td>
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



<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitVAEndInst() {#a7cefcc06639ac482ae979e1703a1b3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitVAEndInst (<a href="/web-llvm/docs/api/classes/llvm/vaendinst">VAEndInst</a> &amp; I)</td>
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



<p>Definition at line 220 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitVAStartInst() {#a1b8bec4e74a7318b69a421e8df11bb41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitVAStartInst (<a href="/web-llvm/docs/api/classes/llvm/vastartinst">VAStartInst</a> &amp; I)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### visitZExtInst() {#afc055d8c7e9e2f430f19b2f6887d1d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::visitZExtInst (<a href="/web-llvm/docs/api/classes/llvm/zextinst">ZExtInst</a> &amp; I)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### delegateCallInst() {#af121c0450f32f983e87b483c15ca2b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::delegateCallInst (<a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> &amp; I)</td>
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



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

### delegateCallInst() {#a9a368e6d2d74bc048a78b26cc84cc2bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SubClass, typename RetTy = void&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RetTy llvm::InstVisitor&lt; SubClass, RetTy &gt;::delegateCallInst (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/instvisitor-h">InstVisitor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
