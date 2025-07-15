---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/codegenopt
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `CodeGenOpt` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::CodeGenOpt { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f32c8cbe9e69d7926b20fcf456281b7">getLevel</a> (int OL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <span class="doxyComputerOutput">Level</span> identified by the integer <span class="doxyComputerOutput">OL</span>. <a href="#a6f32c8cbe9e69d7926b20fcf456281b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc31ff64de59cc3caccf959912140759">parseLevel</a> (char C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput">C</span> as a single digit integer and get matching <span class="doxyComputerOutput">CodeGenLevel</span>. <a href="#acc31ff64de59cc3caccf959912140759">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### getLevel() {#a6f32c8cbe9e69d7926b20fcf456281b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CodeGenOptLevel &gt; llvm::CodeGenOpt::getLevel (int OL)</td>
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

<p>Get the <span class="doxyComputerOutput">Level</span> identified by the integer <span class="doxyComputerOutput">OL</span>.</p>


<p>Returns std::nullopt if <span class="doxyComputerOutput">OL</span> is invalid.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a>.</p>


<p>Referenced by <a href="#acc31ff64de59cc3caccf959912140759">parseLevel</a> and <a href="/web-llvm/docs/api/structs/llvm/ltocodegenerator/#a57d11ddd6ea999809e6670e52a6219cb">llvm::LTOCodeGenerator::setOptLevel</a>.</p>

</div>
</div>

### parseLevel() {#acc31ff64de59cc3caccf959912140759}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CodeGenOptLevel &gt; llvm::CodeGenOpt::parseLevel (char C)</td>
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

<p>Parse <span class="doxyComputerOutput">C</span> as a single digit integer and get matching <span class="doxyComputerOutput">CodeGenLevel</span>.</p>


<p>Returns std::nullopt if the input is not a valid optimization level.</p>


<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a6f32c8cbe9e69d7926b20fcf456281b7">getLevel</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab3e1cccbbbb64f0a0ae8546c703e9b81">llvm::SPIRVTranslateModule</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
