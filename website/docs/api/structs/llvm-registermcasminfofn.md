---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/registermcasminfofn
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterMCAsmInfoFn` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/registermcasminfofn">RegisterMCAsmInfoFn</a> - Helper template for registering a target assembly info implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegisterMCAsmInfoFn { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3aa42e560a3b036302e3a0e20a4db6c5">RegisterMCAsmInfoFn</a> (Target &amp;T, Target::MCAsmInfoCtorFnTy Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcasminfofn">RegisterMCAsmInfoFn</a> - Helper template for registering a target assembly info implementation.</p>


<p>This invokes the specified function to do the construction. Usage:</p>


<p>extern "C" void LLVMInitializeFooTarget() { extern <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> TheFooTarget; <a href="/web-llvm/docs/api/structs/llvm/registermcasminfofn">RegisterMCAsmInfoFn</a> <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X(TheFooTarget, TheFunction)</a>; }</p>


<p>Definition at line 1070 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterMCAsmInfoFn() {#a3aa42e560a3b036302e3a0e20a4db6c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterMCAsmInfoFn::RegisterMCAsmInfoFn (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a0a7cbba18b8a0911bea364fd3f3451d5">Target::MCAsmInfoCtorFnTy</a> Fn)</td>
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



<p>Definition at line 1071 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a3af2448a3eae2807437e612c2334b58a">llvm::TargetRegistry::RegisterMCAsmInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
