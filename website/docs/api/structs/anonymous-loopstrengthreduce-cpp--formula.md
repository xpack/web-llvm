---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-loopstrengthreduce-cpp-/formula
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Formula` Struct Reference

<p>This class holds information that describes a formula for computing satisfying a use. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{LoopStrengthReduce.cpp}::Formula { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e104e7ceecb5b2eddfc08e66e925c09">initialMatch</a> (const SCEV *S, Loop *L, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Incorporate loop-variant parts of S into this <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a>, attempting to keep all loop-invariant and loop-computable values in a single base register. <a href="#a5e104e7ceecb5b2eddfc08e66e925c09">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a315b16382757c50cd6c367fb26e1b15b">isCanonical</a> (const Loop &amp;L) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check whether or not this formula satisfies the canonical representation. <a href="#a315b16382757c50cd6c367fb26e1b15b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef242a2293780c65ed1974184bc17193">canonicalize</a> (const Loop &amp;L)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper method to morph a formula into its canonical representation. <a href="#aef242a2293780c65ed1974184bc17193">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad02fff210996fa6f08b890aabf0f10ca">unscale</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get rid of the scale in the formula. <a href="#ad02fff210996fa6f08b890aabf0f10ca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fab594af348068066d23af810379fff">hasZeroEnd</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a326e8d43b798acbc2b57c0ed8573b492">getNumRegs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the total number of register operands used by this formula. <a href="#a326e8d43b798acbc2b57c0ed8573b492">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ee5737cd553c4eec111f7fbf9894f37">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the type of this formula, if it has one, or null otherwise. <a href="#a2ee5737cd553c4eec111f7fbf9894f37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ae8c31aeebb77960343a102ce36adcb">deleteBaseReg</a> (const SCEV *&amp;S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Delete the given base reg from the BaseRegs list. <a href="#a3ae8c31aeebb77960343a102ce36adcb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7984ece4636cc86706ac5bdfefe3bc6d">referencesReg</a> (const SCEV *S) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test if this formula references the given register. <a href="#a7984ece4636cc86706ac5bdfefe3bc6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98e7bf1bb1d9378c9867e4168a7bfa89">hasRegsUsedByUsesOtherThan</a> (size_t LUIdx, const RegUseTracker &amp;RegUses) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this formula uses registers which are used by uses other than the use with the given index. <a href="#a98e7bf1bb1d9378c9867e4168a7bfa89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a376acc2ec7fd1a216d5ec9fb9f04c99a">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49a86e7759b7ea04a2a99995e9dc11b5">BaseGV</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Global base address used for complex addressing. <a href="#a49a86e7759b7ea04a2a99995e9dc11b5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fd970b2e850c6b038ec1c331132f152">BaseOffset</a> = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a393faf261b99c7234b6d7d97dbdbd5e0">Immediate::getZero</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base offset for complex addressing. <a href="#a7fd970b2e850c6b038ec1c331132f152">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dd38ab56c263b0c9684cb7ad90a17b8">HasBaseReg</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether any complex addressing has a base register. <a href="#a5dd38ab56c263b0c9684cb7ad90a17b8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa82546abf6797d53c3c4ba478ac27c48">Scale</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The scale of any complex addressing. <a href="#aa82546abf6797d53c3c4ba478ac27c48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The list of "base" registers for this use. <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The 'scaled' register for this use. <a href="#a10f8f397229c512b481d8067dc0111db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate">Immediate</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e25533d4ccb07257ed404f527196b3">UnfoldedOffset</a> = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a393faf261b99c7234b6d7d97dbdbd5e0">Immediate::getZero</a>()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An additional constant offset which added near the use. <a href="#a12e25533d4ccb07257ed404f527196b3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class holds information that describes a formula for computing satisfying a use.</p>


<p>It may include broken-out immediates and scaled registers.</p>


<p>Definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Formula() {#a0d4735864020dc6d7bef7067c9a16a3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{LoopStrengthReduce.cpp}::Formula::Formula ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 513 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#aef242a2293780c65ed1974184bc17193">canonicalize</a>, <a href="#a3ae8c31aeebb77960343a102ce36adcb">deleteBaseReg</a>, <a href="#a326e8d43b798acbc2b57c0ed8573b492">getNumRegs</a>, <a href="#a98e7bf1bb1d9378c9867e4168a7bfa89">hasRegsUsedByUsesOtherThan</a>, <a href="#a2fab594af348068066d23af810379fff">hasZeroEnd</a>, <a href="#a5e104e7ceecb5b2eddfc08e66e925c09">initialMatch</a>, <a href="#a7984ece4636cc86706ac5bdfefe3bc6d">referencesReg</a> and <a href="#ad02fff210996fa6f08b890aabf0f10ca">unscale</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### canonicalize() {#aef242a2293780c65ed1974184bc17193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Formula::canonicalize (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Helper method to morph a formula into its canonical representation.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">Formula::BaseRegs</a>. Every formula having more than one base register, must <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a> the <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a> field. Otherwise, we would have to do special cases everywhere in LSR to treat reg1 + reg2 + ... the same way as reg1 + 1*reg2 + ... On the other hand, 1*reg should be canonicalized into reg.</p></dd>
</dl>


<p>Definition at line 519 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1fb9d2e9aea7544f9453aa3e2df38109">containsAddRecDependentOnLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp/#a97d418be7ec7fc90283cc2fee34599ce">isCanonical</a>, <a href="#aa82546abf6797d53c3c4ba478ac27c48">Scale</a>, <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a> and <a href="#a5e104e7ceecb5b2eddfc08e66e925c09">initialMatch</a>.</p>

</div>
</div>

### deleteBaseReg() {#a3ae8c31aeebb77960343a102ce36adcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Formula::deleteBaseReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *&amp; S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Delete the given base reg from the BaseRegs list.</p>

<p>Definition at line 528 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a>.</p>

</div>
</div>

### dump() {#a376acc2ec7fd1a216d5ec9fb9f04c99a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void Formula::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 535 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>

</div>
</div>

### getNumRegs() {#a326e8d43b798acbc2b57c0ed8573b492}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t Formula::getNumRegs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the total number of register operands used by this formula.</p>


<p>This does not include register uses implied by non-constant addrec strides.</p>


<p>Definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a> and <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a>.</p>

</div>
</div>

### getType() {#a2ee5737cd553c4eec111f7fbf9894f37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * Formula::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the type of this formula, if it has one, or null otherwise.</p>


<p>This type is meaningless except for the bit size.</p>


<p>Definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#a49a86e7759b7ea04a2a99995e9dc11b5">BaseGV</a>, <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a> and <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a>.</p>

</div>
</div>

### hasRegsUsedByUsesOtherThan() {#a98e7bf1bb1d9378c9867e4168a7bfa89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Formula::hasRegsUsedByUsesOtherThan (size_t LUIdx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker">RegUseTracker</a> &amp; RegUses)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test whether this formula uses registers which are used by uses other than the use with the given index.</p>

<p>Definition at line 531 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/regusetracker/#a048ddb994fd2688e1940fe34f7d706f8">anonymous{LoopStrengthReduce.cpp}::RegUseTracker::isRegUsedByUsesOtherThan</a> and <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a>.</p>

</div>
</div>

### hasZeroEnd() {#a2fab594af348068066d23af810379fff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Formula::hasZeroEnd ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 523 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#a7fd970b2e850c6b038ec1c331132f152">BaseOffset</a>, <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a> and <a href="#a12e25533d4ccb07257ed404f527196b3">UnfoldedOffset</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a>.</p>

</div>
</div>

### initialMatch() {#a5e104e7ceecb5b2eddfc08e66e925c09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Formula::initialMatch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * L, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Incorporate loop-variant parts of S into this <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula">Formula</a>, attempting to keep all loop-invariant and loop-computable values in a single base register.</p>

<p>Definition at line 515 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="#aef242a2293780c65ed1974184bc17193">canonicalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="#a5dd38ab56c263b0c9684cb7ad90a17b8">HasBaseReg</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#a4541962f9c18aacceb7243520eb15e1f">llvm::SCEV::isZero</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a>.</p>

</div>
</div>

### isCanonical() {#a315b16382757c50cd6c367fb26e1b15b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Formula::isCanonical (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Check whether or not this formula satisfies the canonical representation.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">Formula::BaseRegs</a>.</p></dd>
</dl>


<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a1fb9d2e9aea7544f9453aa3e2df38109">containsAddRecDependentOnLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a>, <a href="#aa82546abf6797d53c3c4ba478ac27c48">Scale</a> and <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a>.</p>

</div>
</div>

### print() {#ab6da05c123f7ca65ecc1163ebf739f01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Formula::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#a49a86e7759b7ea04a2a99995e9dc11b5">BaseGV</a>, <a href="#a7fd970b2e850c6b038ec1c331132f152">BaseOffset</a>, <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="#a5dd38ab56c263b0c9684cb7ad90a17b8">HasBaseReg</a>, <a href="#aa82546abf6797d53c3c4ba478ac27c48">Scale</a>, <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a> and <a href="#a12e25533d4ccb07257ed404f527196b3">UnfoldedOffset</a>.</p>

</div>
</div>

### referencesReg() {#a7984ece4636cc86706ac5bdfefe3bc6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Formula::referencesReg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Test if this formula references the given register.</p>

<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a> and <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a>.</p>

</div>
</div>

### unscale() {#ad02fff210996fa6f08b890aabf0f10ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Formula::unscale ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get rid of the scale in the formula.</p>


<p>In other words, this method morphes reg1 + 1*reg2 into reg1 + reg2.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if it was possible to get rid of the scale, false otherwise.</p></dd>
</dl>



:::info
<p>After this operation the formula may not be in the canonical form.</p>
:::


<p>Definition at line 521 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>References <a href="#ad1246f472c53ef21f95da9e3f6b3f3c2">BaseRegs</a>, <a href="#aa82546abf6797d53c3c4ba478ac27c48">Scale</a> and <a href="#a10f8f397229c512b481d8067dc0111db">ScaledReg</a>.</p>


<p>Referenced by <a href="#a0d4735864020dc6d7bef7067c9a16a3d">Formula</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### BaseGV {#a49a86e7759b7ea04a2a99995e9dc11b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue* anonymous{LoopStrengthReduce.cpp}::Formula::BaseGV = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Global base address used for complex addressing.</p>

<p>Definition at line 477 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a2ee5737cd553c4eec111f7fbf9894f37">getType</a> and <a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a>.</p>

</div>
</div>

### BaseOffset {#a7fd970b2e850c6b038ec1c331132f152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Immediate anonymous{LoopStrengthReduce.cpp}::Formula::BaseOffset = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a393faf261b99c7234b6d7d97dbdbd5e0">Immediate::getZero</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Base offset for complex addressing.</p>

<p>Definition at line 480 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a2fab594af348068066d23af810379fff">hasZeroEnd</a> and <a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a>.</p>

</div>
</div>

### BaseRegs {#ad1246f472c53ef21f95da9e3f6b3f3c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const SCEV *, 4&gt; anonymous{LoopStrengthReduce.cpp}::Formula::BaseRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The list of "base" registers for this use.</p>


<p>When this is non-empty. The canonical representation of a formula is</p>


<ol class="doxyList" type="1">
<li>BaseRegs.size &gt; 1 implies ScaledReg != NULL and</li>
<li>ScaledReg != NULL implies Scale != 1 || !BaseRegs.empty().</li>
<li>The reg containing recurrent expr related with currect loop in the formula should be put in the ScaledReg. #1 enforces that the scaled register is always used when at least two registers are needed by the formula: e.g., reg1 + reg2 is reg1 + 1 * reg2. #2 enforces that 1 * reg is reg. #3 ensures invariant regs with respect to current loop can be combined together in LSR codegen. This invariant can be temporarily broken while building a formula. However, every formula inserted into the <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsrinstance">LSRInstance</a> must be in canonical form.</li>
</ol>

<p>Definition at line 502 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#aef242a2293780c65ed1974184bc17193">canonicalize</a>, <a href="#a3ae8c31aeebb77960343a102ce36adcb">deleteBaseReg</a>, <a href="#a326e8d43b798acbc2b57c0ed8573b492">getNumRegs</a>, <a href="#a2ee5737cd553c4eec111f7fbf9894f37">getType</a>, <a href="#a98e7bf1bb1d9378c9867e4168a7bfa89">hasRegsUsedByUsesOtherThan</a>, <a href="#a2fab594af348068066d23af810379fff">hasZeroEnd</a>, <a href="#a5e104e7ceecb5b2eddfc08e66e925c09">initialMatch</a>, <a href="#a315b16382757c50cd6c367fb26e1b15b">isCanonical</a>, <a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a>, <a href="#a7984ece4636cc86706ac5bdfefe3bc6d">referencesReg</a> and <a href="#ad02fff210996fa6f08b890aabf0f10ca">unscale</a>.</p>

</div>
</div>

### HasBaseReg {#a5dd38ab56c263b0c9684cb7ad90a17b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{LoopStrengthReduce.cpp}::Formula::HasBaseReg = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Whether any complex addressing has a base register.</p>

<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a5e104e7ceecb5b2eddfc08e66e925c09">initialMatch</a> and <a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a>.</p>

</div>
</div>

### Scale {#aa82546abf6797d53c3c4ba478ac27c48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int64_t anonymous{LoopStrengthReduce.cpp}::Formula::Scale = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The scale of any complex addressing.</p>

<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#aef242a2293780c65ed1974184bc17193">canonicalize</a>, <a href="#a315b16382757c50cd6c367fb26e1b15b">isCanonical</a>, <a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a> and <a href="#ad02fff210996fa6f08b890aabf0f10ca">unscale</a>.</p>

</div>
</div>

### ScaledReg {#a10f8f397229c512b481d8067dc0111db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* anonymous{LoopStrengthReduce.cpp}::Formula::ScaledReg = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The 'scaled' register for this use.</p>


<p>This should be non-null when Scale is not zero.</p>


<p>Definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#aef242a2293780c65ed1974184bc17193">canonicalize</a>, <a href="#a326e8d43b798acbc2b57c0ed8573b492">getNumRegs</a>, <a href="#a2ee5737cd553c4eec111f7fbf9894f37">getType</a>, <a href="#a98e7bf1bb1d9378c9867e4168a7bfa89">hasRegsUsedByUsesOtherThan</a>, <a href="#a2fab594af348068066d23af810379fff">hasZeroEnd</a>, <a href="#a315b16382757c50cd6c367fb26e1b15b">isCanonical</a>, <a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a>, <a href="#a7984ece4636cc86706ac5bdfefe3bc6d">referencesReg</a> and <a href="#ad02fff210996fa6f08b890aabf0f10ca">unscale</a>.</p>

</div>
</div>

### UnfoldedOffset {#a12e25533d4ccb07257ed404f527196b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Immediate anonymous{LoopStrengthReduce.cpp}::Formula::UnfoldedOffset = <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a393faf261b99c7234b6d7d97dbdbd5e0">Immediate::getZero</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>An additional constant offset which added near the use.</p>


<p>This requires a temporary register, but the offset itself can live in an add immediate field rather than a register.</p>


<p>Definition at line 511 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a>.</p>


<p>Referenced by <a href="#a2fab594af348068066d23af810379fff">hasZeroEnd</a> and <a href="#ab6da05c123f7ca65ecc1163ebf739f01">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp">LoopStrengthReduce.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
