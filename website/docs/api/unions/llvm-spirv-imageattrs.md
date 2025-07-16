---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/unions/llvm/spirv/imageattrs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - union

---

<div class="doxyPage">

# The `ImageAttrs` Union Reference



## Declaration

<div class="doxyDeclaration">
union llvm::SPIRV::ImageAttrs { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvduplicatestracker-h">Target/SPIRV/SPIRVDuplicatesTracker.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade454e0e3dc3a278c72cdb8e11dd5d08">ImageAttrs</a> (unsigned Dim, unsigned Depth, unsigned Arrayed, unsigned MS, unsigned Sampled, unsigned ImageFormat, unsigned AQ=0)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct { ... }</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a083d3597629f8545c21ee7f872745afa">Flags</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24da72a56b5038d25e95ec176b9c8cdc">Val</a></td>
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


<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvduplicatestracker-h">SPIRVDuplicatesTracker.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ImageAttrs() {#ade454e0e3dc3a278c72cdb8e11dd5d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SPIRV::ImageAttrs::ImageAttrs (unsigned Dim, unsigned Depth, unsigned Arrayed, unsigned MS, unsigned Sampled, unsigned ImageFormat, unsigned AQ=0)</td>
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



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvduplicatestracker-h">SPIRVDuplicatesTracker.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a083d3597629f8545c21ee7f872745afa">Flags</a> and <a href="#a24da72a56b5038d25e95ec176b9c8cdc">Val</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a083d3597629f8545c21ee7f872745afa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">struct llvm::SPIRV::ImageAttrs::BitFlags llvm::SPIRV::ImageAttrs::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvduplicatestracker-h">SPIRVDuplicatesTracker.h</a>.</p>


<p>Referenced by <a href="#ade454e0e3dc3a278c72cdb8e11dd5d08">ImageAttrs</a>.</p>

</div>
</div>

### Val {#a24da72a56b5038d25e95ec176b9c8cdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SPIRV::ImageAttrs::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvduplicatestracker-h">SPIRVDuplicatesTracker.h</a>.</p>


<p>Referenced by <a href="#ade454e0e3dc3a278c72cdb8e11dd5d08">ImageAttrs</a> and <a href="/web-llvm/docs/api/namespaces/llvm/spirv/#aeb5e4e41c7dda3b942168ed881fa1d13">llvm::SPIRV::make_descr_sampled_image</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this union was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvduplicatestracker-h">SPIRVDuplicatesTracker.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
