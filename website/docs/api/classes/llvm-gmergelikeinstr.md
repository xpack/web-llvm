---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gmergelikeinstr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GMergeLikeInstr` Class

<p>Represents G_BUILD_VECTOR, G_CONCAT_VECTORS or G_MERGE_VALUES. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::GMergeLikeInstr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">llvm/CodeGen/GlobalISel/GenericMachineInstrs.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr">GenericMachineInstr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A base class for all GenericMachineInstrs. <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gbuildvector">GBuildVector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a G_BUILD_VECTOR. <a href="/web-llvm/docs/api/classes/llvm/gbuildvector/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gbuildvectortrunc">GBuildVectorTrunc</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a G_BUILD_VECTOR_TRUNC. <a href="/web-llvm/docs/api/classes/llvm/gbuildvectortrunc/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gconcatvectors">GConcatVectors</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a G_CONCAT_VECTORS. <a href="/web-llvm/docs/api/classes/llvm/gconcatvectors/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gmerge">GMerge</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Represents a G_MERGE_VALUES. <a href="/web-llvm/docs/api/classes/llvm/gmerge/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90d314382626dec7379b4d2ec02b7a4b">getNumSources</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of source registers. <a href="#a90d314382626dec7379b4d2ec02b7a4b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226d638a0e8ab52846285f8a24e3c9f5">getSourceReg</a> (unsigned I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the I'th source register. <a href="#a226d638a0e8ab52846285f8a24e3c9f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8f7f0aa074adacc159ea23179fa801b">classof</a> (const MachineInstr *MI)</td>
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

<p>Represents G_BUILD_VECTOR, G_CONCAT_VECTORS or G_MERGE_VALUES.</p>


<p>All these have the common property of generating a single value from multiple sources.</p>


<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### getNumSources() {#a90d314382626dec7379b4d2ec02b7a4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GMergeLikeInstr::getNumSources ()</td>
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

<p>Returns the number of source registers.</p>

<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/machineinstr/#a432824f0975bb863478bf4ef3a5df258">llvm::MachineInstr::getNumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a19cd4e56c457ed0e004225064806cbcb">llvm::isConstantOrConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a3b0f315e261e572d6f0b357e4404ca42">isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#ae88fdd4a40851c70c1f04282174034c2">llvm::CombinerHelper::matchCastOfBuildVector</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a853bef7f992c449e98913ebad50666a2">shiftAmountKnownInRange</a>.</p>

</div>
</div>

### getSourceReg() {#a226d638a0e8ab52846285f8a24e3c9f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::GMergeLikeInstr::getSourceReg (unsigned I)</td>
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

<p>Returns the I'th source register.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/genericmachineinstr/#a2cdf10ff4f5fb865c6a669331aeb5846">llvm::GenericMachineInstr::getReg</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a19cd4e56c457ed0e004225064806cbcb">llvm::isConstantOrConstantVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a3b0f315e261e572d6f0b357e4404ca42">isGuaranteedNotToBeUndefOrPoison</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#af7bcd2506b90a78c86a2ac061132783f">llvm::CombinerHelper::matchExtractVectorElementWithBuildVector</a>, <a href="/web-llvm/docs/api/classes/llvm/combinerhelper/#a2a97e27cc61249c732f88ca2b63ce73f">llvm::CombinerHelper::matchExtractVectorElementWithBuildVectorTrunc</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/utils-cpp/#a853bef7f992c449e98913ebad50666a2">shiftAmountKnownInRange</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#ad8f7f0aa074adacc159ea23179fa801b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GMergeLikeInstr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> * MI)</td>
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



<p>Definition at line 271 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/genericmachineinstrs-h">GenericMachineInstrs.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
