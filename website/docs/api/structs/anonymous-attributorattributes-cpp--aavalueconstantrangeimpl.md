---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangeimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AAValueConstantRangeImpl` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl { ... }
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange">AAValueConstantRange</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An abstract interface for range value analysis. <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaargumentfromcallsitearguments">AAArgumentFromCallSiteArguments&lt;AAType, BaseType, StateType, BridgeCallBaseContext, IRAttributeKind&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for generic deduction: call site argument -&gt; argument position. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaargumentfromcallsitearguments/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite">AACalleeToCallSite&lt;AAType, BaseType, StateType, IntroduceCallBaseContext, IRAttributeKind&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for generic replication: function returned -&gt; cs returned. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aacalleetocallsite/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aareturnedfromreturnedvalues">AAReturnedFromReturnedValues&lt;AAType, BaseType, StateType, PropagateCallBaseContext, IRAttributeKind, RecurseForSelectAndPHI&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper class for generic deduction: return value -&gt; returned position. <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aareturnedfromreturnedvalues/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating">AAValueConstantRangeFloating</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefunction">AAValueConstantRangeFunction</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf41e0f6f3fd5b1279318d750cea829">StateType</a> = <a href="/web-llvm/docs/api/structs/llvm/integerrangestate">IntegerRangeState</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abda461bd0cc87d90f77c50f2fa15ac60">AAValueConstantRangeImpl</a> (const IRPosition &amp;IRP, Attributor &amp;A)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a9160e61aee9e51514937e1cd8b2f0">initialize</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a63f1f9078e9f43f6ac08ac9e1e9b4a41">AbstractAttribute::initialize</a>(..). <a href="#a98a9160e61aee9e51514937e1cd8b2f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b5568e59f33b74c9b10462295c0ecb6">getAsStr</a> (Attributor *A) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>. <a href="#a5b5568e59f33b74c9b10462295c0ecb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b1acdea3aaa8e166e24b51e22def764">getSCEV</a> (Attributor &amp;A, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to get a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expr for the associated value at program point <span class="doxyComputerOutput">I</span>. <a href="#a0b1acdea3aaa8e166e24b51e22def764">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa917f47e75cf32ee8a1abf71f2ebde01">getConstantRangeFromSCEV</a> (Attributor &amp;A, const Instruction *I=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to get a range from <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the associated value at program point <span class="doxyComputerOutput">I</span>. <a href="#aa917f47e75cf32ee8a1abf71f2ebde01">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5a45de2ff151caaae105b2aa429f35b">getConstantRangeFromLVI</a> (Attributor &amp;A, const Instruction *CtxI=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to get a range from LVI for the associated value at program point <span class="doxyComputerOutput">I</span>. <a href="#aa5a45de2ff151caaae105b2aa429f35b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade252ec650f1f043ccf664b66c038d38">isValidCtxInstructionForOutsideAnalysis</a> (Attributor &amp;A, const Instruction *CtxI, bool AllowAACtxI) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">CtxI</span> is valid for querying outside analyses. <a href="#ade252ec650f1f043ccf664b66c038d38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d362ce614123852df0f345317c6c957">getKnownConstantRange</a> (Attributor &amp;A, const Instruction *CtxI=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#afd6f3ec72df277e48fc3a9edb095b3cb">AAValueConstantRange::getKnownConstantRange</a>(..). <a href="#a6d362ce614123852df0f345317c6c957">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad39b005f46b9ffb7cc54942161210656">getAssumedConstantRange</a> (Attributor &amp;A, const Instruction *CtxI=nullptr) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a2411004443b9be61cdecbf43554f2c4d">AAValueConstantRange::getAssumedConstantRange</a>(..). <a href="#ad39b005f46b9ffb7cc54942161210656">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3">ChangeStatus</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12fa48f6f87955f0d3b9a0912669ef38">manifest</a> (Attributor &amp;A) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a1405b111f812f19e71bbe4286484ef54">AbstractAttribute::manifest()</a> <a href="#a12fa48f6f87955f0d3b9a0912669ef38">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fee7c9d5fe48b2dfbeefbd6ff1b0910">getMDNodeForConstantRange</a> (Type *Ty, LLVMContext &amp;Ctx, const ConstantRange &amp;AssumedConstantRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to create <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for range metadata. <a href="#a7fee7c9d5fe48b2dfbeefbd6ff1b0910">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a745987cc07ad13e3d1b5e07ea6d8e78f">isBetterRange</a> (const ConstantRange &amp;Assumed, MDNode *KnownRanges)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if <span class="doxyComputerOutput">Assumed</span> is included in <span class="doxyComputerOutput">KnownRanges</span>. <a href="#a745987cc07ad13e3d1b5e07ea6d8e78f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a679c2e4baff0b3b8eff40752f5a3e222">setRangeMetadataIfisBetterRange</a> (Instruction *I, const ConstantRange &amp;AssumedConstantRange)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to set range metadata. <a href="#a679c2e4baff0b3b8eff40752f5a3e222">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 8995 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### StateType {#aadf41e0f6f3fd5b1279318d750cea829}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::StateType =  IntegerRangeState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 8996 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### AAValueConstantRangeImpl() {#abda461bd0cc87d90f77c50f2fa15ac60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::AAValueConstantRangeImpl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/irposition">IRPosition</a> &amp; IRP, <a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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



<p>Definition at line 8997 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a7e85dae54d01cf0410db2477b07152d9">llvm::AAValueConstantRange::AAValueConstantRange</a> and <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#aa72ab70aeb5fda68592b723813e77ff6">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::AAValueConstantRangeFloating</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefunction/#adeb011853f9337a4798fd032873441e5">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFunction::AAValueConstantRangeFunction</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAsStr() {#a5b5568e59f33b74c9b10462295c0ecb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getAsStr (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> * A)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#ab46cf8c2872fdda027ddc8691afbf498">AbstractAttribute::getAsStr()</a>.</p>

<p>Definition at line 9015 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#ac3c5924f36fc704b6a1f12211c897113">llvm::IntegerRangeState::getAssumed</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a> and <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#aaf5d2b73a9ab6a5f6c038ccc3b87621e">llvm::IntegerRangeState::getKnown</a>.</p>

</div>
</div>

### getAssumedConstantRange() {#ad39b005f46b9ffb7cc54942161210656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getAssumedConstantRange (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#a2411004443b9be61cdecbf43554f2c4d">AAValueConstantRange::getAssumedConstantRange</a>(..).</p>

<p>Definition at line 9131 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#ac3c5924f36fc704b6a1f12211c897113">llvm::IntegerRangeState::getAssumed</a>, <a href="#aa5a45de2ff151caaae105b2aa429f35b">getConstantRangeFromLVI</a>, <a href="#aa917f47e75cf32ee8a1abf71f2ebde01">getConstantRangeFromSCEV</a> and <a href="#ade252ec650f1f043ccf664b66c038d38">isValidCtxInstructionForOutsideAnalysis</a>.</p>


<p>Referenced by <a href="#a12fa48f6f87955f0d3b9a0912669ef38">manifest</a>.</p>

</div>
</div>

### getConstantRangeFromLVI() {#aa5a45de2ff151caaae105b2aa429f35b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromLVI (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
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

<p>Helper function to get a range from LVI for the associated value at program point <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 9070 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/lazyvalueinfo/#a250c3d5c704c7c596ec914c18c40fbc2">llvm::LazyValueInfo::getConstantRange</a> and <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#ade656897ef13aaa480677e37a4fcfa43">llvm::IntegerRangeState::getWorstState</a>.</p>


<p>Referenced by <a href="#ad39b005f46b9ffb7cc54942161210656">getAssumedConstantRange</a>, <a href="#a6d362ce614123852df0f345317c6c957">getKnownConstantRange</a> and <a href="#a98a9160e61aee9e51514937e1cd8b2f0">initialize</a>.</p>

</div>
</div>

### getConstantRangeFromSCEV() {#aa917f47e75cf32ee8a1abf71f2ebde01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getConstantRangeFromSCEV (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
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

<p>Helper function to get a range from <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> for the associated value at program point <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 9051 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a2cb59ea8f9e8543986d40c48acfd24a3">getBitWidth</a>, <a href="#a0b1acdea3aaa8e166e24b51e22def764">getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a7593d52f91ebe342de9fa72846ebe755">llvm::ScalarEvolution::getUnsignedRange</a>, <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#ade656897ef13aaa480677e37a4fcfa43">llvm::IntegerRangeState::getWorstState</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#ad39b005f46b9ffb7cc54942161210656">getAssumedConstantRange</a>, <a href="#a6d362ce614123852df0f345317c6c957">getKnownConstantRange</a> and <a href="#a98a9160e61aee9e51514937e1cd8b2f0">initialize</a>.</p>

</div>
</div>

### getKnownConstantRange() {#a6d362ce614123852df0f345317c6c957}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstantRange anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getKnownConstantRange (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI=nullptr)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/aavalueconstantrange/#afd6f3ec72df277e48fc3a9edb095b3cb">AAValueConstantRange::getKnownConstantRange</a>(..).</p>

<p>Definition at line 9118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="#aa5a45de2ff151caaae105b2aa429f35b">getConstantRangeFromLVI</a>, <a href="#aa917f47e75cf32ee8a1abf71f2ebde01">getConstantRangeFromSCEV</a>, <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#aaf5d2b73a9ab6a5f6c038ccc3b87621e">llvm::IntegerRangeState::getKnown</a> and <a href="#ade252ec650f1f043ccf664b66c038d38">isValidCtxInstructionForOutsideAnalysis</a>.</p>

</div>
</div>

### getSCEV() {#a0b1acdea3aaa8e166e24b51e22def764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getSCEV (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I=nullptr)</td>
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

<p>Helper function to get a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expr for the associated value at program point <span class="doxyComputerOutput">I</span>.</p>

<p>Definition at line 9028 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#afa339f4513a2704e8e2dadb6a92faab3">llvm::IRPosition::getAnchorScope</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a30bd18ac905eacf3601bc6a553a9ff49">llvm::ScalarEvolution::getSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a21d6ee82eed29080d911dbb548a8bb68">llvm::ScalarEvolution::getSCEVAtScope</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#aa917f47e75cf32ee8a1abf71f2ebde01">getConstantRangeFromSCEV</a>.</p>

</div>
</div>

### initialize() {#a98a9160e61aee9e51514937e1cd8b2f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::initialize (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a63f1f9078e9f43f6ac08ac9e1e9b4a41">AbstractAttribute::initialize</a>(..).</p>

<p>Definition at line 9001 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="#aa5a45de2ff151caaae105b2aa429f35b">getConstantRangeFromLVI</a>, <a href="#aa917f47e75cf32ee8a1abf71f2ebde01">getConstantRangeFromSCEV</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a5cdc54db452dfdce67b7f0713f822f71">llvm::IRPosition::getCtxI</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#af5135f33d24ea71544db77941dab1e38">llvm::AbstractAttribute::getIRPosition</a>, <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#aa13036717a5ffd3ae9b9d717f981978e">llvm::IntegerRangeState::indicatePessimisticFixpoint</a> and <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#aba968663106abb1b267a4a8673b89f55">llvm::IntegerRangeState::intersectKnown</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangecallsitereturned/#adea35464b5cc6628399f3a058c28bb0b">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeCallSiteReturned::initialize</a> and <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavalueconstantrangefloating/#a2b827c74bf3fdb8d906b3eeb0e1e5f8f">anonymous{AttributorAttributes.cpp}::AAValueConstantRangeFloating::initialize</a>.</p>

</div>
</div>

### isValidCtxInstructionForOutsideAnalysis() {#ade252ec650f1f043ccf664b66c038d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isValidCtxInstructionForOutsideAnalysis (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * CtxI, bool AllowAACtxI)</td>
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

<p>Return true if <span class="doxyComputerOutput">CtxI</span> is valid for querying outside analyses.</p>


<p>This basically makes sure we do not ask intra-procedural analysis about a context in the wrong function or a context that violates dominance assumptions they might have. The <span class="doxyComputerOutput">AllowAACtxI</span> flag indicates if the original context of this <a href="/web-llvm/docs/api/namespaces/llvm/aa">AA</a> is OK or should be considered invalid.</p>


<p>Definition at line 9091 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/classes/llvm/dominatortree/#a5c69311e8d44898dac36a155c3d8691d">llvm::DominatorTree::dominates</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/informationcache/#af887d734d176f82b42528b55c0bdc4f7">llvm::InformationCache::getAnalysisResultForFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a5cdc54db452dfdce67b7f0713f822f71">llvm::IRPosition::getCtxI</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a6a66ebb3aa12757479a3c88de77d78f8">llvm::Instruction::getFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="/web-llvm/docs/api/namespaces/llvm/aa/#ad7be59b8a3d5e2faf55b21c42ed07a63">llvm::AA::isValidInScope</a>.</p>


<p>Referenced by <a href="#ad39b005f46b9ffb7cc54942161210656">getAssumedConstantRange</a> and <a href="#a6d362ce614123852df0f345317c6c957">getKnownConstantRange</a>.</p>

</div>
</div>

### manifest() {#a12fa48f6f87955f0d3b9a0912669ef38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ChangeStatus anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::manifest (<a href="/web-llvm/docs/api/structs/llvm/attributor">Attributor</a> &amp; A)</td>
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

<p>See <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a1405b111f812f19e71bbe4286484ef54">AbstractAttribute::manifest()</a></p>

<p>Definition at line 9200 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/abstractattribute/#a05f3b3169e1f6a561b0c38f0150b3867">llvm::AbstractAttribute::Attributor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3ae6b94e58bfd13b21bc786578d9f8ba4a">llvm::CHANGED</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a96130007e2acc25ee2ed2dd8f08f3e18">llvm::IRPosition::getAssociatedValue</a>, <a href="#ad39b005f46b9ffb7cc54942161210656">getAssumedConstantRange</a>, <a href="/web-llvm/docs/api/structs/llvm/irposition/#a5cdc54db452dfdce67b7f0713f822f71">llvm::IRPosition::getCtxI</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a4f6242fab5145c424cee29230fefe746">llvm::ConstantRange::isFullSet</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a91cf2c952ea87d701fe608fe4aaabfe4">llvm::ConstantRange::isSingleElement</a>, <a href="#a679c2e4baff0b3b8eff40752f5a3e222">setRangeMetadataIfisBetterRange</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acd850975ae5042cacb64a9d0ea4715f3a46335765005ff44b1fe1e38e5d2ddfcc">llvm::UNCHANGED</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getMDNodeForConstantRange() {#a7fee7c9d5fe48b2dfbeefbd6ff1b0910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MDNode * anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::getMDNodeForConstantRange (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; AssumedConstantRange)</td>
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

<p>Helper function to create <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> for range metadata.</p>

<p>Definition at line 9148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a23f4339e49343721146062b10c144052">llvm::ConstantRange::getLower</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#aa1955c426e1ff66455b4bb6657ee995d">llvm::ConstantRange::getUpper</a>.</p>


<p>Referenced by <a href="#a679c2e4baff0b3b8eff40752f5a3e222">setRangeMetadataIfisBetterRange</a>.</p>

</div>
</div>

### isBetterRange() {#a745987cc07ad13e3d1b5e07ea6d8e78f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::isBetterRange (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; Assumed, <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * KnownRanges)</td>
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

<p>Return true if <span class="doxyComputerOutput">Assumed</span> is included in <span class="doxyComputerOutput">KnownRanges</span>.</p>

<p>Definition at line 9158 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#a4386fbf0609524525ddb030f243ce4a1">llvm::IntegerRangeState::Assumed</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mdconst/#ad938857d6c6603847adf3a8cbe403d17">llvm::mdconst::extract</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#aa4068e37ec583962685e3567dc102ae5">llvm::MDNode::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a42409838a49255a3770da1469872f20b">llvm::MDNode::getOperand</a>, <a href="/web-llvm/docs/api/structs/llvm/integerrangestate/#a807fb347d0feef5f839837e6d3dc5dbc">llvm::IntegerRangeState::Known</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>.</p>


<p>Referenced by <a href="#a679c2e4baff0b3b8eff40752f5a3e222">setRangeMetadataIfisBetterRange</a>.</p>

</div>
</div>

### setRangeMetadataIfisBetterRange() {#a679c2e4baff0b3b8eff40752f5a3e222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AttributorAttributes.cpp}::AAValueConstantRangeImpl::setRangeMetadataIfisBetterRange (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * I, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &amp; AssumedConstantRange)</td>
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

<p>Helper function to set range metadata.</p>

<p>Definition at line 9185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a>.</p>


<p>References <a href="#a7fee7c9d5fe48b2dfbeefbd6ff1b0910">getMDNodeForConstantRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a745987cc07ad13e3d1b5e07ea6d8e78f">isBetterRange</a> and <a href="/web-llvm/docs/api/classes/llvm/constantrange/#a5bd6d98b4a7ecc1dcdc571e4352fcc52">llvm::ConstantRange::isEmptySet</a>.</p>


<p>Referenced by <a href="#a12fa48f6f87955f0d3b9a0912669ef38">manifest</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/attributorattributes-cpp">AttributorAttributes.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
