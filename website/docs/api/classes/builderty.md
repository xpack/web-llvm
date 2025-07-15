---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/builderty
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `BuilderTy` Class Reference



## Declaration

<div class="doxyDeclaration">
class BuilderTy { ... }
</div>

## Base class

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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8f04bf2341322b164db120058b87384">BuilderTy</a> (BasicBlock *TheBB, BasicBlock::iterator IP, TargetFolder Folder)</td>
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


<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp">BoundsChecking.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BuilderTy() {#aa8f04bf2341322b164db120058b87384}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BuilderTy::BuilderTy (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * TheBB, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a98c0a84a5dfa8bce341c829709f171e5">BasicBlock::iterator</a> IP, <a href="/web-llvm/docs/api/classes/llvm/targetfolder">TargetFolder</a> Folder)</td>
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



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp">BoundsChecking.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/irbuilder/#afdcde0e677ccb2ad5b4d67a510da2972">llvm::IRBuilder&lt; TargetFolder &gt;::IRBuilder</a> and <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17d41b5b0a5db696fd1aa34fc65c7a86">llvm::IRBuilderBase::SetNoSanitizeMetadata</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp">BoundsChecking.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
