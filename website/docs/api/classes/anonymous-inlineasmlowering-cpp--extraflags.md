---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-inlineasmlowering-cpp-/extraflags
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ExtraFlags` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{InlineAsmLowering.cpp}::ExtraFlags { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a265ccdc955df6841403de15996982e3e">ExtraFlags</a> (const CallBase &amp;CB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f9400f16ef11b5ae4f82337370657d5">update</a> (const TargetLowering::AsmOperandInfo &amp;OpInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6936bcc3e53e0e6f74e144c5e262814">get</a> () const</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add2b0ab3881987da1829461403465e11">Flags</a> = 0</td>
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


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExtraFlags() {#a265ccdc955df6841403de15996982e3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{InlineAsmLowering.cpp}::ExtraFlags::ExtraFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370abff974c258dde829c1c6b6f32667be3a">llvm::InlineAsm::Extra_AsmDialect</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a68a61079919e61d3af1002124c2f1ff9">llvm::InlineAsm::Extra_HasSideEffects</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ada6152484586a08fa711d4b0d44c87e5">llvm::InlineAsm::Extra_IsAlignStack</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370a9921f5d5868939f49675e7fe34d1be70">llvm::InlineAsm::Extra_IsConvergent</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac32c9ebab7dfd3db749d0ab5e6e58b3e">llvm::CallBase::isConvergent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### get() {#ad6936bcc3e53e0e6f74e144c5e262814}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineAsmLowering.cpp}::ExtraFlags::get ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>

</div>
</div>

### update() {#a5f9400f16ef11b5ae4f82337370657d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{InlineAsmLowering.cpp}::ExtraFlags::update (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> TargetLowering::AsmOperandInfo &amp; OpInfo)</td>
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



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116a420d729d2e7d056ec884c094ccdc4467">llvm::TargetLowering::C_Memory</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlowering/#a0b0176781cd4fd9f45cc739f1d007116abc9c279d343d2f957ab51b37ff39e88e">llvm::TargetLowering::C_Other</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370aa21b27c3cc4550dcd3ff599dbe76d0c3">llvm::InlineAsm::Extra_MayLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#af263df97504e0800bba5e552246b7370ab01e1dce8dabbbb3d14ed5f34c366008">llvm::InlineAsm::Extra_MayStore</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34adf39e7f7e158f2ccacae6d4446197322">llvm::InlineAsm::isClobber</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6">llvm::InlineAsm::isInput</a> and <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f">llvm::InlineAsm::isOutput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Flags {#add2b0ab3881987da1829461403465e11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{InlineAsmLowering.cpp}::ExtraFlags::Flags = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/inlineasmlowering-cpp">InlineAsmLowering.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
