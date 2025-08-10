---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-constraintelimination-cpp-/factorcheck
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `FactOrCheck` Struct

<p>Represents either. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct anonymous{ConstraintElimination.cpp}::FactOrCheck { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EntryTy { <a href="#a7653cd668efd9f6300fe86fe5e844c91">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a> (EntryTy Ty, DomTreeNode *DTN, Instruction *Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3eb590fecba7420b015c73fecc72c74c">FactOrCheck</a> (DomTreeNode *DTN, Use *U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d096bf023aaad6c33d917a7032e9426">FactOrCheck</a> (DomTreeNode *DTN, CmpPredicate Pred, Value *Op0, Value *Op1, ConditionTy Precond={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a087c3fe48cccf8c8d0951f0494cacd">isCheck</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e202848f80528468595631c140a3f74">getContextInst</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5631f0e67807e31b7d8fb5a11f714207">getInstructionToSimplify</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a045a89a7d77f957580136d0f8853cf72">isConditionFact</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ba25ee0f263df095a3cd649be785cde">Inst</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/use">Use</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30898b192175d10b9bdeee6dfc3c1aa6">U</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/conditionty">ConditionTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87667f0f616441f6c08f37536bdf775d">Cond</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union anonymous_namespace{ConstraintElimination.cpp}<a href="#ab48424dc299fd03c99469003301a7bd7">::FactOrCheck</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac344c85746235ca04851881729aa2ad9"></a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/conditionty">ConditionTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfd349c1144307768a88e7005eaeb7f1">DoesHold</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A pre-condition that must hold for the current fact to be added to the system. <a href="#acfd349c1144307768a88e7005eaeb7f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa62906df8962041bec97cb180e33302">NumIn</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeafeb583d0b4768c89348db1e11114be">NumOut</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7653cd668efd9f6300fe86fe5e844c91">EntryTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34a1c00e8418093b0da2c6e03e5dad09">Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/factorcheck">FactOrCheck</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50dd66f4b9fd44ba084bd90753f4cd90">getConditionFact</a> (DomTreeNode *DTN, CmpPredicate Pred, Value *Op0, Value *Op1, ConditionTy Precond={})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/factorcheck">FactOrCheck</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9974e4a78ef76b40bcf4cecb76be1dad">getInstFact</a> (DomTreeNode *DTN, Instruction *Inst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/factorcheck">FactOrCheck</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34f9221f7e746879dd09a80a9ea4841">getCheck</a> (DomTreeNode *DTN, Use *U)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/factorcheck">FactOrCheck</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace832dc792e7ab1b3fab181da9a726c5">getCheck</a> (DomTreeNode *DTN, CallInst *CI)</td>
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

<p>Represents either.</p>


<ul class="doxyList ">
<li>a condition that holds on entry to a block (=condition fact)</li>
<li>an assume (=assume fact)</li>
<li>a use of a compare instruction to simplify. It also tracks the Dominator DFS in and out numbers for each entry.</li>
</ul>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### EntryTy {#a7653cd668efd9f6300fe86fe5e844c91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class anonymous{ConstraintElimination.cpp}::FactOrCheck::EntryTy </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ConditionFact<a id="a7653cd668efd9f6300fe86fe5e844c91a8266fc2e0454774a0d5ca4063408fa8d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InstFact<a id="a7653cd668efd9f6300fe86fe5e844c91a82d19cb36488a04e75e23e6cfc9e269f"></a></td>
<td class="doxyEnumItemDescription">A condition that holds on entry to a block</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InstCheck<a id="a7653cd668efd9f6300fe86fe5e844c91a164b7be34d50670587782248b5cf5180"></a></td>
<td class="doxyEnumItemDescription">A fact that holds after Inst executed (e.g</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UseCheck<a id="a7653cd668efd9f6300fe86fe5e844c91abddd8986cc5f7b02abfecedff00aa664"></a></td>
<td class="doxyEnumItemDescription">An instruction to simplify (e.g</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FactOrCheck() {#ab48424dc299fd03c99469003301a7bd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ConstraintElimination.cpp}::FactOrCheck::FactOrCheck (<a href="#a7653cd668efd9f6300fe86fe5e844c91">EntryTy</a> Ty, <a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * DTN, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#a4ba25ee0f263df095a3cd649be785cde">Inst</a>, <a href="#aaa62906df8962041bec97cb180e33302">NumIn</a>, <a href="#aeafeb583d0b4768c89348db1e11114be">NumOut</a> and <a href="#a34a1c00e8418093b0da2c6e03e5dad09">Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a61e2de2c4987a7fdaf09251933714262">eliminateConstraints</a>, <a href="#ace832dc792e7ab1b3fab181da9a726c5">getCheck</a>, <a href="#ae34f9221f7e746879dd09a80a9ea4841">getCheck</a>, <a href="#a50dd66f4b9fd44ba084bd90753f4cd90">getConditionFact</a> and <a href="#a9974e4a78ef76b40bcf4cecb76be1dad">getInstFact</a>.</p>

</div>
</div>

### FactOrCheck() {#a3eb590fecba7420b015c73fecc72c74c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ConstraintElimination.cpp}::FactOrCheck::FactOrCheck (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * DTN, <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#aaa62906df8962041bec97cb180e33302">NumIn</a>, <a href="#aeafeb583d0b4768c89348db1e11114be">NumOut</a>, <a href="#a34a1c00e8418093b0da2c6e03e5dad09">Ty</a>, <a href="#a30898b192175d10b9bdeee6dfc3c1aa6">U</a> and <a href="#a7653cd668efd9f6300fe86fe5e844c91abddd8986cc5f7b02abfecedff00aa664">UseCheck</a>.</p>

</div>
</div>

### FactOrCheck() {#a8d096bf023aaad6c33d917a7032e9426}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{ConstraintElimination.cpp}::FactOrCheck::FactOrCheck (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * DTN, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/conditionty">ConditionTy</a> Precond={})</td>
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



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getContextInst() {#a0e202848f80528468595631c140a3f74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{ConstraintElimination.cpp}::FactOrCheck::getContextInst ()</td>
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



<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a26cc8732cd251afc0ef7f6f666cb1274">getContextInstForUse</a>, <a href="#a4ba25ee0f263df095a3cd649be785cde">Inst</a>, <a href="#a045a89a7d77f957580136d0f8853cf72">isConditionFact</a>, <a href="#a34a1c00e8418093b0da2c6e03e5dad09">Ty</a>, <a href="#a30898b192175d10b9bdeee6dfc3c1aa6">U</a> and <a href="#a7653cd668efd9f6300fe86fe5e844c91abddd8986cc5f7b02abfecedff00aa664">UseCheck</a>.</p>

</div>
</div>

### getInstructionToSimplify() {#a5631f0e67807e31b7d8fb5a11f714207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * anonymous{ConstraintElimination.cpp}::FactOrCheck::getInstructionToSimplify ()</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a4ba25ee0f263df095a3cd649be785cde">Inst</a>, <a href="#a7653cd668efd9f6300fe86fe5e844c91a164b7be34d50670587782248b5cf5180">InstCheck</a>, <a href="#a6a087c3fe48cccf8c8d0951f0494cacd">isCheck</a>, <a href="#a34a1c00e8418093b0da2c6e03e5dad09">Ty</a> and <a href="#a30898b192175d10b9bdeee6dfc3c1aa6">U</a>.</p>

</div>
</div>

### isCheck() {#a6a087c3fe48cccf8c8d0951f0494cacd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ConstraintElimination.cpp}::FactOrCheck::isCheck ()</td>
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



<p>Definition at line 160 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#a7653cd668efd9f6300fe86fe5e844c91a164b7be34d50670587782248b5cf5180">InstCheck</a>, <a href="#a34a1c00e8418093b0da2c6e03e5dad09">Ty</a> and <a href="#a7653cd668efd9f6300fe86fe5e844c91abddd8986cc5f7b02abfecedff00aa664">UseCheck</a>.</p>


<p>Referenced by <a href="#a5631f0e67807e31b7d8fb5a11f714207">getInstructionToSimplify</a>.</p>

</div>
</div>

### isConditionFact() {#a045a89a7d77f957580136d0f8853cf72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{ConstraintElimination.cpp}::FactOrCheck::isConditionFact ()</td>
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



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#a7653cd668efd9f6300fe86fe5e844c91a8266fc2e0454774a0d5ca4063408fa8d">ConditionFact</a> and <a href="#a34a1c00e8418093b0da2c6e03e5dad09">Ty</a>.</p>


<p>Referenced by <a href="#a0e202848f80528468595631c140a3f74">getContextInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

###  {#ac344c85746235ca04851881729aa2ad9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">union anonymous{ConstraintElimination.cpp}::FactOrCheck anonymous{ConstraintElimination.cpp}::FactOrCheck</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>

</div>
</div>

### Cond {#a87667f0f616441f6c08f37536bdf775d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConditionTy anonymous{ConstraintElimination.cpp}::FactOrCheck::Cond</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>

</div>
</div>

### DoesHold {#acfd349c1144307768a88e7005eaeb7f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConditionTy anonymous{ConstraintElimination.cpp}::FactOrCheck::DoesHold</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A pre-condition that must hold for the current fact to be added to the system.</p>

<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>

</div>
</div>

### Inst {#a4ba25ee0f263df095a3cd649be785cde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction* anonymous{ConstraintElimination.cpp}::FactOrCheck::Inst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a>, <a href="#a0e202848f80528468595631c140a3f74">getContextInst</a>, <a href="#a9974e4a78ef76b40bcf4cecb76be1dad">getInstFact</a> and <a href="#a5631f0e67807e31b7d8fb5a11f714207">getInstructionToSimplify</a>.</p>

</div>
</div>

### NumIn {#aaa62906df8962041bec97cb180e33302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ConstraintElimination.cpp}::FactOrCheck::NumIn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a3eb590fecba7420b015c73fecc72c74c">FactOrCheck</a> and <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a>.</p>

</div>
</div>

### NumOut {#aeafeb583d0b4768c89348db1e11114be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned anonymous{ConstraintElimination.cpp}::FactOrCheck::NumOut</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a3eb590fecba7420b015c73fecc72c74c">FactOrCheck</a> and <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a>.</p>

</div>
</div>

### Ty {#a34a1c00e8418093b0da2c6e03e5dad09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryTy anonymous{ConstraintElimination.cpp}::FactOrCheck::Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a3eb590fecba7420b015c73fecc72c74c">FactOrCheck</a>, <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a>, <a href="#a0e202848f80528468595631c140a3f74">getContextInst</a>, <a href="#a5631f0e67807e31b7d8fb5a11f714207">getInstructionToSimplify</a>, <a href="#a6a087c3fe48cccf8c8d0951f0494cacd">isCheck</a> and <a href="#a045a89a7d77f957580136d0f8853cf72">isConditionFact</a>.</p>

</div>
</div>

### U {#a30898b192175d10b9bdeee6dfc3c1aa6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Use* anonymous{ConstraintElimination.cpp}::FactOrCheck::U</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 117 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Referenced by <a href="#a3eb590fecba7420b015c73fecc72c74c">FactOrCheck</a>, <a href="#ae34f9221f7e746879dd09a80a9ea4841">getCheck</a>, <a href="#a0e202848f80528468595631c140a3f74">getContextInst</a> and <a href="#a5631f0e67807e31b7d8fb5a11f714207">getInstructionToSimplify</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getCheck() {#ae34f9221f7e746879dd09a80a9ea4841}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FactOrCheck anonymous{ConstraintElimination.cpp}::FactOrCheck::getCheck (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * DTN, <a href="/web-llvm/docs/api/classes/llvm/use">Use</a> * U)</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a> and <a href="#a30898b192175d10b9bdeee6dfc3c1aa6">U</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a0f682f69a2b53113b0df4e2b9a7e3aae">anonymous{ConstraintElimination.cpp}::State::addInfoFor</a>.</p>

</div>
</div>

### getCheck() {#ace832dc792e7ab1b3fab181da9a726c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FactOrCheck anonymous{ConstraintElimination.cpp}::FactOrCheck::getCheck (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * DTN, <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * CI)</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a> and <a href="#a7653cd668efd9f6300fe86fe5e844c91a164b7be34d50670587782248b5cf5180">InstCheck</a>.</p>

</div>
</div>

### getConditionFact() {#a50dd66f4b9fd44ba084bd90753f4cd90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FactOrCheck anonymous{ConstraintElimination.cpp}::FactOrCheck::getConditionFact (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * DTN, <a href="/web-llvm/docs/api/classes/llvm/cmppredicate">CmpPredicate</a> Pred, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op0, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Op1, <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/conditionty">ConditionTy</a> Precond={})</td>
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



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>Reference <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a0f682f69a2b53113b0df4e2b9a7e3aae">anonymous{ConstraintElimination.cpp}::State::addInfoFor</a> and <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a77dccdccff30d1cf89c684cf37cd85d8">anonymous{ConstraintElimination.cpp}::State::addInfoForInductions</a>.</p>

</div>
</div>

### getInstFact() {#a9974e4a78ef76b40bcf4cecb76be1dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FactOrCheck anonymous{ConstraintElimination.cpp}::FactOrCheck::getInstFact (<a href="/web-llvm/docs/api/namespaces/llvm/#a58b9df85470fc4e2a8066ff6a62e5a34">DomTreeNode</a> * DTN, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * Inst)</td>
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



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a>.</p>


<p>References <a href="#ab48424dc299fd03c99469003301a7bd7">FactOrCheck</a>, <a href="#a4ba25ee0f263df095a3cd649be785cde">Inst</a> and <a href="#a7653cd668efd9f6300fe86fe5e844c91a82d19cb36488a04e75e23e6cfc9e269f">InstFact</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-constraintelimination-cpp-/state/#a0f682f69a2b53113b0df4e2b9a7e3aae">anonymous{ConstraintElimination.cpp}::State::addInfoFor</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp">ConstraintElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
