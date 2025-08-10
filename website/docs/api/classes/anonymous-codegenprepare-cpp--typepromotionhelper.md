---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-codegenprepare-cpp-/typepromotionhelper
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TypePromotionHelper` Class

<p>Hepler class to perform type promotion. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{CodeGenPrepare.cpp}::TypePromotionHelper { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada40299269e8b441bab738dc14ad0c1e">Action</a> = <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *(*)(<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *Ext, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp;TPT, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp;PromotedInsts, unsigned &amp;CreatedInstsCost, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; *Exts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; *Truncs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for the utility function that promotes the operand of Ext. <a href="#ada40299269e8b441bab738dc14ad0c1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ada40299269e8b441bab738dc14ad0c1e">Action</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6df9b95e8bacacbad0035f25c46d2581">getAction</a> (Instruction *Ext, const SetOfInstrs &amp;InsertedInsts, const TargetLowering &amp;TLI, const InstrToOrigTy &amp;PromotedInsts)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a sign/zero extend instruction <span class="doxyComputerOutput">Ext</span>, return the appropriate action to promote the operand of <span class="doxyComputerOutput">Ext</span> instead of using Ext. <a href="#a6df9b95e8bacacbad0035f25c46d2581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f521500ee39e89561edaebfbd8e8543">addPromotedInst</a> (InstrToOrigTy &amp;PromotedInsts, Instruction *ExtOpnd, bool IsSExt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to add a promoted instruction <span class="doxyComputerOutput">ExtOpnd</span> to <span class="doxyComputerOutput">PromotedInsts</span> and record the type of extension we have seen. <a href="#a0f521500ee39e89561edaebfbd8e8543">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad884fa0c7a928beebcc76107aab8e760">getOrigType</a> (const InstrToOrigTy &amp;PromotedInsts, Instruction *Opnd, bool IsSExt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to query the original type of instruction <span class="doxyComputerOutput">Opnd</span> with a matched extension type. <a href="#ad884fa0c7a928beebcc76107aab8e760">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bff60d6d38eca058313256cbb4fd09f">canGetThrough</a> (const Instruction *Inst, Type *ConsideredExtType, const InstrToOrigTy &amp;PromotedInsts, bool IsSExt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to check whether or not a sign or zero extension of <span class="doxyComputerOutput">Inst</span> with <span class="doxyComputerOutput">ConsideredExtType</span> can be moved through <span class="doxyComputerOutput">Inst</span> by either using the operands of <span class="doxyComputerOutput">Inst</span> or promoting <span class="doxyComputerOutput">Inst</span>. <a href="#a4bff60d6d38eca058313256cbb4fd09f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8cc7db7a82ae835d602c63de830b80d">shouldExtOperand</a> (const Instruction *Inst, int OpIdx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to determine if <span class="doxyComputerOutput">OpIdx</span> should be promoted when promoting <span class="doxyComputerOutput">Inst</span>. <a href="#af8cc7db7a82ae835d602c63de830b80d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95bae4c5ef7d726b41b169b09fd466b1">promoteOperandForTruncAndAnyExt</a> (Instruction *Ext, TypePromotionTransaction &amp;TPT, InstrToOrigTy &amp;PromotedInsts, unsigned &amp;CreatedInstsCost, SmallVectorImpl&lt; Instruction * &gt; *Exts, SmallVectorImpl&lt; Instruction * &gt; *Truncs, const TargetLowering &amp;TLI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to promote the operand of <span class="doxyComputerOutput">Ext</span> when this operand is a promotable trunc or sext or zext. <a href="#a95bae4c5ef7d726b41b169b09fd466b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fd96f1dbfee53b31e81c3ca68b484a5">promoteOperandForOther</a> (Instruction *Ext, TypePromotionTransaction &amp;TPT, InstrToOrigTy &amp;PromotedInsts, unsigned &amp;CreatedInstsCost, SmallVectorImpl&lt; Instruction * &gt; *Exts, SmallVectorImpl&lt; Instruction * &gt; *Truncs, const TargetLowering &amp;TLI, bool IsSExt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Utility function to promote the operand of <span class="doxyComputerOutput">Ext</span> when this operand is promotable and is not a supported trunc or sext. <a href="#a9fd96f1dbfee53b31e81c3ca68b484a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4da5476cd05880c16670ba43094a798">signExtendOperandForOther</a> (Instruction *Ext, TypePromotionTransaction &amp;TPT, InstrToOrigTy &amp;PromotedInsts, unsigned &amp;CreatedInstsCost, SmallVectorImpl&lt; Instruction * &gt; *Exts, SmallVectorImpl&lt; Instruction * &gt; *Truncs, const TargetLowering &amp;TLI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af121a9cbf73371b1eb78fd1a6b0ba03d">zeroExtendOperandForOther</a> (Instruction *Ext, TypePromotionTransaction &amp;TPT, InstrToOrigTy &amp;PromotedInsts, unsigned &amp;CreatedInstsCost, SmallVectorImpl&lt; Instruction * &gt; *Exts, SmallVectorImpl&lt; Instruction * &gt; *Truncs, const TargetLowering &amp;TLI)</td>
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

<p>Hepler class to perform type promotion.</p>

<p>Definition at line 4669 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Action {#ada40299269e8b441bab738dc14ad0c1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::Action =  Value *(*)(Instruction *Ext, TypePromotionTransaction &amp;TPT,
                            InstrToOrigTy &amp;PromotedInsts,
                            unsigned &amp;CreatedInstsCost,
                            SmallVectorImpl&lt;Instruction *&gt; *Exts,
                            SmallVectorImpl&lt;Instruction *&gt; *Truncs,
                            const TargetLowering &amp;TLI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> for the utility function that promotes the operand of Ext.</p>

<p>Definition at line 4777 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getAction() {#a6df9b95e8bacacbad0035f25c46d2581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypePromotionHelper::Action TypePromotionHelper::getAction (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Ext, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#af2dad33e47a12a0b01b11d97d390f7ee">SetOfInstrs</a> &amp; InsertedInsts, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts)</td>
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

<p>Given a sign/zero extend instruction <span class="doxyComputerOutput">Ext</span>, return the appropriate action to promote the operand of <span class="doxyComputerOutput">Ext</span> instead of using Ext.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>NULL if no promotable action is possible with the current sign extension. <span class="doxyComputerOutput">InsertedInsts</span> keeps track of all the instructions inserted by the other <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a> optimizations. This information is important because we do not want to promote these instructions as <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/codegenprepare">CodeGenPrepare</a> will reinsert them later. Thus creating an infinite loop: create/remove. <span class="doxyComputerOutput">PromotedInsts</span> maps the instructions to their type before promotion.</p></dd>
</dl>


<p>Definition at line 4793 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a1f475b0df44ebd7169e720fa1bf9169e">llvm::SmallPtrSetImpl&lt; PtrType &gt;::count</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a6f992bc4ca89f1b5f0b34f5b29978c31">llvm::TargetLoweringBase::isTruncateFree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Functions

### addPromotedInst() {#a0f521500ee39e89561edaebfbd8e8543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::addPromotedInst (<a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * ExtOpnd, bool IsSExt)</td>
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

<p>Utility function to add a promoted instruction <span class="doxyComputerOutput">ExtOpnd</span> to <span class="doxyComputerOutput">PromotedInsts</span> and record the type of extension we have seen.</p>

<p>Definition at line 4672 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### canGetThrough() {#a4bff60d6d38eca058313256cbb4fd09f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TypePromotionHelper::canGetThrough (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ConsideredExtType, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, bool IsSExt)</td>
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

<p>Utility function to check whether or not a sign or zero extension of <span class="doxyComputerOutput">Inst</span> with <span class="doxyComputerOutput">ConsideredExtType</span> can be moved through <span class="doxyComputerOutput">Inst</span> by either using the operands of <span class="doxyComputerOutput">Inst</span> or promoting <span class="doxyComputerOutput">Inst</span>.</p>


<p>The type of the extension is defined by <span class="doxyComputerOutput">IsSExt</span>. In other words, check if: ext (Ty Inst opnd1 opnd2 ... opndN) to ConsideredExtType. #1 Promotion applies: ConsideredExtType Inst (ext opnd1 to ConsideredExtType, ...). #2 Operand reuses: ext opnd1 to ConsideredExtType. <span class="doxyComputerOutput">PromotedInsts</span> maps the instructions to their type before promotion.</p>


<p>Definition at line 4714 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### getOrigType() {#ad884fa0c7a928beebcc76107aab8e760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Type * anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::getOrigType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Opnd, bool IsSExt)</td>
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

<p>Utility function to query the original type of instruction <span class="doxyComputerOutput">Opnd</span> with a matched extension type.</p>


<p>If the extension doesn't match, we cannot use the information we had on the original type. BothExtension doesn't match any extension type.</p>


<p>Definition at line 4694 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### promoteOperandForOther() {#a9fd96f1dbfee53b31e81c3ca68b484a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * TypePromotionHelper::promoteOperandForOther (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Ext, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, unsigned &amp; CreatedInstsCost, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Exts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Truncs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI, bool IsSExt)</td>
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

<p>Utility function to promote the operand of <span class="doxyComputerOutput">Ext</span> when this operand is promotable and is not a supported trunc or sext.</p>


<p><span class="doxyComputerOutput">PromotedInsts</span> maps the instructions to their type before promotion. <span class="doxyComputerOutput">CreatedInstsCost</span>[out] contains the cost of all the instructions created to promote the operand of Ext. Newly added extensions are inserted in <span class="doxyComputerOutput">Exts</span>. Newly added truncates are inserted in <span class="doxyComputerOutput">Truncs</span>. Should never be called directly.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The promoted value which is used instead of Ext.</p></dd>
</dl>


<p>Definition at line 4747 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### promoteOperandForTruncAndAnyExt() {#a95bae4c5ef7d726b41b169b09fd466b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * TypePromotionHelper::promoteOperandForTruncAndAnyExt (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Ext, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, unsigned &amp; CreatedInstsCost, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Exts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Truncs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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

<p>Utility function to promote the operand of <span class="doxyComputerOutput">Ext</span> when this operand is a promotable trunc or sext or zext.</p>


<p><span class="doxyComputerOutput">PromotedInsts</span> maps the instructions to their type before promotion. <span class="doxyComputerOutput">CreatedInstsCost</span>[out] contains the cost of all instructions created to promote the operand of Ext. Newly added extensions are inserted in <span class="doxyComputerOutput">Exts</span>. Newly added truncates are inserted in <span class="doxyComputerOutput">Truncs</span>. Should never be called directly.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>The promoted value which is used instead of Ext.</p></dd>
</dl>


<p>Definition at line 4732 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### shouldExtOperand() {#af8cc7db7a82ae835d602c63de830b80d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::shouldExtOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst, int OpIdx)</td>
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

<p>Utility function to determine if <span class="doxyComputerOutput">OpIdx</span> should be promoted when promoting <span class="doxyComputerOutput">Inst</span>.</p>

<p>Definition at line 4719 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### signExtendOperandForOther() {#ae4da5476cd05880c16670ba43094a798}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::signExtendOperandForOther (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Ext, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, unsigned &amp; CreatedInstsCost, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Exts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Truncs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>promoteOperandForOther.</p></dd>
</dl>


<p>Definition at line 4756 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

### zeroExtendOperandForOther() {#af121a9cbf73371b1eb78fd1a6b0ba03d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * anonymous{CodeGenPrepare.cpp}::TypePromotionHelper::zeroExtendOperandForOther (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Ext, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/typepromotiontransaction">TypePromotionTransaction</a> &amp; TPT, <a href="/web-llvm/docs/api/namespaces/anonymous-codegenprepare-cpp-/#a71622f7f81af67784beaf8b1420aa76d">InstrToOrigTy</a> &amp; PromotedInsts, unsigned &amp; CreatedInstsCost, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Exts, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * &gt; * Truncs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlowering">TargetLowering</a> &amp; TLI)</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p>promoteOperandForOther.</p></dd>
</dl>


<p>Definition at line 4766 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/codegenprepare-cpp">CodeGenPrepare.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
