---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/autoinitremark
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AutoInitRemark` Struct Reference

<p>Special case for -ftrivial-auto-var-init remarks. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::AutoInitRemark { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">llvm/Transforms/Utils/MemoryOpRemark.h</a>"
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/memoryopremark">MemoryOpRemark</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc96db1676e27342e9f1ade5e46d8ea5">AutoInitRemark</a> (OptimizationRemarkEmitter &amp;ORE, StringRef RemarkPass, const DataLayout &amp;DL, const TargetLibraryInfo &amp;TLI)</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab32f9db76653d78af26d37c13778c4e6">explainSource</a> (StringRef Type) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa94fc90cfa2315eeef5dcf04458617fa">remarkName</a> (RemarkKind RK) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594">DiagnosticKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7158522b3592b9c0b3eb1e0bebc040fc">diagnosticKind</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69856189f0653d336e1f0f13076845bf">canHandle</a> (const Instruction *I)</td>
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

<p>Special case for -ftrivial-auto-var-init remarks.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">MemoryOpRemark.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AutoInitRemark() {#abc96db1676e27342e9f1ade5e46d8ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AutoInitRemark::AutoInitRemark (<a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp; ORE, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> RemarkPass, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> &amp; TLI)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">MemoryOpRemark.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#a81ab7f2ae731a7f145a1488cb84be1d8">llvm::MemoryOpRemark::DL</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#ad99cd44fdfd9049476ff35f5e7771acc">llvm::MemoryOpRemark::MemoryOpRemark</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#affc8a7a84f31d6345933fb32afca4947">llvm::MemoryOpRemark::ORE</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#aad1dbb4b1f80d87def38329defc8389d">llvm::MemoryOpRemark::RemarkPass</a> and <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#a3a261163a53fa4b58499322c20f1952d">llvm::MemoryOpRemark::TLI</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### diagnosticKind() {#a7158522b3592b9c0b3eb1e0bebc040fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagnosticKind llvm::AutoInitRemark::diagnosticKind ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">MemoryOpRemark.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a52b4ea3a21377555e9a0511d57945594a60172d67189a80dd366981444c7e6fe9">llvm::DK_OptimizationRemarkMissed</a>.</p>

</div>
</div>

### explainSource() {#ab32f9db76653d78af26d37c13778c4e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string AutoInitRemark::explainSource (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Type)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">MemoryOpRemark.h</a>, definition at line 398 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/memoryopremark-cpp">MemoryOpRemark.cpp</a>.</p>

</div>
</div>

### remarkName() {#aa94fc90cfa2315eeef5dcf04458617fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef AutoInitRemark::remarkName (<a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#a0b5f89367d77e95e191f4dba11119540">RemarkKind</a> RK)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">MemoryOpRemark.h</a>, definition at line 402 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/memoryopremark-cpp">MemoryOpRemark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#a0b5f89367d77e95e191f4dba11119540ac5867bebefae5ad9ac7e0eec418dc722">llvm::MemoryOpRemark::RK_Call</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#a0b5f89367d77e95e191f4dba11119540ad26116e0fbc3518a8b5ce42bf723fafb">llvm::MemoryOpRemark::RK_IntrinsicCall</a>, <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#a0b5f89367d77e95e191f4dba11119540aa036baa9962afbac5185a09979402c9d">llvm::MemoryOpRemark::RK_Store</a> and <a href="/web-llvm/docs/api/structs/llvm/memoryopremark/#a0b5f89367d77e95e191f4dba11119540a38c89bc3f274207c66f98f2f9f440482">llvm::MemoryOpRemark::RK_Unknown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### canHandle() {#a69856189f0653d336e1f0f13076845bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AutoInitRemark::canHandle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I)</td>
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




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true iff the instruction is understood by <a href="/web-llvm/docs/api/structs/llvm/autoinitremark">AutoInitRemark</a>.</p></dd>
</dl>


<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">MemoryOpRemark.h</a>, definition at line 388 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/memoryopremark-cpp">MemoryOpRemark.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a61d13d6824ec46c31260a4fd0997eda0">llvm::any_of</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/annotationremarks-cpp/#ac8389a31f52b01976c5813624f836d0d">tryEmitAutoInitRemark</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/utils/memoryopremark-h">MemoryOpRemark.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/memoryopremark-cpp">MemoryOpRemark.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
