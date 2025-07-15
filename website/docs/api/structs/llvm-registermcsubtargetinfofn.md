---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/registermcsubtargetinfofn
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `RegisterMCSubtargetInfoFn` Struct Reference

<p><a href="/web-llvm/docs/api/structs/llvm/registermcsubtargetinfofn">RegisterMCSubtargetInfoFn</a> - Helper template for registering a target subtarget info implementation. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::RegisterMCSubtargetInfoFn { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">llvm/MC/TargetRegistry.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9c8f6069533f9e9497f8d08017178c5">RegisterMCSubtargetInfoFn</a> (Target &amp;T, Target::MCSubtargetInfoCtorFnTy Fn)</td>
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

<p><a href="/web-llvm/docs/api/structs/llvm/registermcsubtargetinfofn">RegisterMCSubtargetInfoFn</a> - Helper template for registering a target subtarget info implementation.</p>


<p>This invokes the specified function to do the construction. Usage:</p>


<p>extern "C" void LLVMInitializeFooTarget() { extern <a href="/web-llvm/docs/api/classes/llvm/target">Target</a> TheFooTarget; <a href="/web-llvm/docs/api/structs/llvm/registermcsubtargetinfofn">RegisterMCSubtargetInfoFn</a> <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X(TheFooTarget, TheFunction)</a>; }</p>


<p>Definition at line 1234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RegisterMCSubtargetInfoFn() {#af9c8f6069533f9e9497f8d08017178c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::RegisterMCSubtargetInfoFn::RegisterMCSubtargetInfoFn (<a href="/web-llvm/docs/api/classes/llvm/target">Target</a> &amp; T, <a href="/web-llvm/docs/api/classes/llvm/target/#a1056bfbe7e8c7721ae6cce94313350e3">Target::MCSubtargetInfoCtorFnTy</a> Fn)</td>
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



<p>Definition at line 1235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/mc/targetregistry-h">TargetRegistry.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a469331cb6070bffd3354391877547014">llvm::TargetRegistry::RegisterMCSubtargetInfo</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

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
