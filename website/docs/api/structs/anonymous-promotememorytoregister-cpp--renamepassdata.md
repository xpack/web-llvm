---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-promotememorytoregister-cpp-/renamepassdata
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RenamePassData` Struct Reference

<p>Data package used by RenamePass(). <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{PromoteMemoryToRegister.cpp}::RenamePassData { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18e5b1dbb4e7b1463315c636b916abd0">ValVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81ba17b4e41561256ed0b2a82aaac8ce">LocationVector</a> = std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/debugloc">DebugLoc</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915f29d785997f4266e64348c8a0e2b2">RenamePassData</a> (BasicBlock *B, BasicBlock *P, ValVector V, LocationVector L)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad93429799d281f5a6534821bc14fa36c">BB</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9573d1a944e1048e7fd1c0c488eced2">Pred</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a18e5b1dbb4e7b1463315c636b916abd0">ValVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add5219f842875c33a4168bf4bb6b37f5">Values</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a81ba17b4e41561256ed0b2a82aaac8ce">LocationVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18184dbfe73aeba751307ac82f0e5209">Locations</a></td>
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

<p>Data package used by RenamePass().</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LocationVector {#a81ba17b4e41561256ed0b2a82aaac8ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::LocationVector =  std::vector&lt;DebugLoc&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 287 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

### ValVector {#a18e5b1dbb4e7b1463315c636b916abd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::ValVector =  std::vector&lt;Value *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### RenamePassData() {#a915f29d785997f4266e64348c8a0e2b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::RenamePassData (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * B, <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> * P, <a href="#a18e5b1dbb4e7b1463315c636b916abd0">ValVector</a> V, <a href="#a81ba17b4e41561256ed0b2a82aaac8ce">LocationVector</a> L)</td>
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



<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#ad93429799d281f5a6534821bc14fa36c">BB</a>, <a href="#a18184dbfe73aeba751307ac82f0e5209">Locations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ab9573d1a944e1048e7fd1c0c488eced2">Pred</a> and <a href="#add5219f842875c33a4168bf4bb6b37f5">Values</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BB {#ad93429799d281f5a6534821bc14fa36c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::BB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a915f29d785997f4266e64348c8a0e2b2">RenamePassData</a> and <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>.</p>

</div>
</div>

### Locations {#a18184dbfe73aeba751307ac82f0e5209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LocationVector anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::Locations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 295 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a915f29d785997f4266e64348c8a0e2b2">RenamePassData</a> and <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>.</p>

</div>
</div>

### Pred {#ab9573d1a944e1048e7fd1c0c488eced2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BasicBlock* anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::Pred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a915f29d785997f4266e64348c8a0e2b2">RenamePassData</a> and <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>.</p>

</div>
</div>

### Values {#add5219f842875c33a4168bf4bb6b37f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValVector anonymous{PromoteMemoryToRegister.cpp}::RenamePassData::Values</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a>.</p>


<p>Referenced by <a href="#a915f29d785997f4266e64348c8a0e2b2">RenamePassData</a> and <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp">PromoteMemoryToRegister.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
