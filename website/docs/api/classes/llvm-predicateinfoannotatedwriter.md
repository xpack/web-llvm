---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/predicateinfoannotatedwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PredicateInfoAnnotatedWriter` Class Reference

<p>An assembly annotator class to print <a href="/web-llvm/docs/api/classes/llvm/predicateinfo">PredicateInfo</a> information in comments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PredicateInfoAnnotatedWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd561f24f0d69b8b7986d295d5bcd086">PredicateInfo</a></td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a417c0441817b2064068857248609c2b2">PredicateInfoAnnotatedWriter</a> (const PredicateInfo *M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d7c3d2ed52d6f55c6c82f59a8cd137">emitBasicBlockStartAnnot</a> (const BasicBlock *BB, formatted_raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitBasicBlockStartAnnot - This may be implemented to emit a string right after the basic block label, but before the first instruction in the block. <a href="#ad7d7c3d2ed52d6f55c6c82f59a8cd137">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84fe7c49603300369fa9dbf87ac1449d">emitInstructionAnnot</a> (const Instruction *I, formatted_raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>emitInstructionAnnot - This may be implemented to emit a string right before an instruction is emitted. <a href="#a84fe7c49603300369fa9dbf87ac1449d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/predicateinfo">PredicateInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68fb8df6870775c71fec091cee4edfc8">PredInfo</a></td>
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

<p>An assembly annotator class to print <a href="/web-llvm/docs/api/classes/llvm/predicateinfo">PredicateInfo</a> information in comments.</p>

<p>Definition at line 855 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<div class="doxySectionDef">

## Friends

### PredicateInfo {#acd561f24f0d69b8b7986d295d5bcd086}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/predicateinfo">PredicateInfo</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 856 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<p>Reference <a href="#acd561f24f0d69b8b7986d295d5bcd086">PredicateInfo</a>.</p>


<p>Referenced by <a href="#acd561f24f0d69b8b7986d295d5bcd086">PredicateInfo</a> and <a href="#a417c0441817b2064068857248609c2b2">PredicateInfoAnnotatedWriter</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PredicateInfoAnnotatedWriter() {#a417c0441817b2064068857248609c2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PredicateInfoAnnotatedWriter::PredicateInfoAnnotatedWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/predicateinfo">PredicateInfo</a> * M)</td>
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



<p>Definition at line 860 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<p>Reference <a href="#acd561f24f0d69b8b7986d295d5bcd086">PredicateInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### emitBasicBlockStartAnnot() {#ad7d7c3d2ed52d6f55c6c82f59a8cd137}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PredicateInfoAnnotatedWriter::emitBasicBlockStartAnnot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>emitBasicBlockStartAnnot - This may be implemented to emit a string right after the basic block label, but before the first instruction in the block.</p>

<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>

</div>
</div>

### emitInstructionAnnot() {#a84fe7c49603300369fa9dbf87ac1449d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::PredicateInfoAnnotatedWriter::emitInstructionAnnot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>emitInstructionAnnot - This may be implemented to emit a string right before an instruction is emitted.</p>

<p>Definition at line 865 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#afd1501c49c84f3addfd108c2484f5674">PB</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### PredInfo {#a68fb8df6870775c71fec091cee4edfc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const PredicateInfo* llvm::PredicateInfoAnnotatedWriter::PredInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/predicateinfo-cpp">PredicateInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
