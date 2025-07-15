---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/registermcreginfofn
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterMCRegInfoFn` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/registermcreginfofn">RegisterMCRegInfoFn</a> - Helper template for registering a target register info implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegisterMCRegInfoFn { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab40c8c3bf3b761518a7db459786d7f60">RegisterMCRegInfoFn</a> (Target &amp;T, Target::MCRegInfoCtorFnTy Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcreginfofn">RegisterMCRegInfoFn</a> - Helper template for registering a target register info implementation.</p>


<p>This invokes the specified function to do the construction. Usage:</p>


<p>extern "C" void LLVMInitializeFooTarget() { extern <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> TheFooTarget; <a href="/web-llvm/docs/api/structs/llvm/registermcreginfofn">RegisterMCRegInfoFn</a> <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X(TheFooTarget, TheFunction)</a>; }</p>


<p>Definition at line 1200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterMCRegInfoFn() {#ab40c8c3bf3b761518a7db459786d7f60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterMCRegInfoFn::RegisterMCRegInfoFn (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a75a0ab6413b8ed39da567eeb7810f9f1">Target::MCRegInfoCtorFnTy</a> Fn)</td>
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



<p>Definition at line 1201 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a0be8ffbacd90d86a1c1f27a032e2265e">llvm::TargetRegistry::RegisterMCRegInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
