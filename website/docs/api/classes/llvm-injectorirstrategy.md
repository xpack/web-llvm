---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/injectorirstrategy
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `InjectorIRStrategy` Class Reference

<p>Strategy that injects operations into the function. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::InjectorIRStrategy { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">llvm/FuzzMutate/IRMutator.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irmutationstrategy">IRMutationStrategy</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for describing how to mutate a module. <a href="/web-llvm/docs/api/classes/llvm/irmutationstrategy/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe981ff634aeceec82ac1dffd1753bea">InjectorIRStrategy</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7b2cd8387654fa847253e0213ce93c1">InjectorIRStrategy</a> (std::vector&lt; fuzzerop::OpDescriptor &gt; &amp;&amp;Operations)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7024bfc9fd530d6cc7cb693d31e598">getWeight</a> (size_t CurrentSize, size_t MaxSize, uint64_t CurrentWeight) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a weight to bias towards choosing this strategy for a mutation. <a href="#a1c7024bfc9fd530d6cc7cb693d31e598">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b097f9a6f96a44ea8b3327278846ff">mutate</a> (Function &amp;F, RandomIRBuilder &amp;IB) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22c46265af5b3e456243d03b635ae9bd">mutate</a> (BasicBlock &amp;BB, RandomIRBuilder &amp;IB) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af80c59250b5a5e540d6eaeb458be693a">mutate</a> (Module &amp;M, RandomIRBuilder &amp;IB)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249b695824fd4f98a12b0be986fe7150">mutate</a> (Instruction &amp;I, RandomIRBuilder &amp;IB)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">fuzzerop::OpDescriptor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adda0eee1a80f9288159dde7467542d68">chooseOperation</a> (Value *Src, RandomIRBuilder &amp;IB)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">fuzzerop::OpDescriptor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf33db5be239fd37a3d44694cb3b6941">Operations</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">fuzzerop::OpDescriptor</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0528fc09ee5324d528b7378b6ec78beb">getDefaultOps</a> ()</td>
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

<p>Strategy that injects operations into the function.</p>

<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### InjectorIRStrategy() {#afe981ff634aeceec82ac1dffd1753bea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InjectorIRStrategy::InjectorIRStrategy ()</td>
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



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>


<p>Reference <a href="#a0528fc09ee5324d528b7378b6ec78beb">getDefaultOps</a>.</p>

</div>
</div>

### InjectorIRStrategy() {#aa7b2cd8387654fa847253e0213ce93c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InjectorIRStrategy::InjectorIRStrategy (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">fuzzerop::OpDescriptor</a> &gt; &amp;&amp; Operations)</td>
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



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getWeight() {#a1c7024bfc9fd530d6cc7cb693d31e598}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::InjectorIRStrategy::getWeight (size_t CurrentSize, size_t MaxSize, uint64_t CurrentWeight)</td>
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

<p>Provide a weight to bias towards choosing this strategy for a mutation.</p>


<p>The value of the weight is arbitrary, but a good default is "the number of
distinct ways in which this strategy can mutate a unit". This can also be used to prefer strategies that shrink the overall size of the result when we start getting close to <span class="doxyComputerOutput">MaxSize</span>.</p>


<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>

</div>
</div>

### mutate() {#a26b097f9a6f96a44ea8b3327278846ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InjectorIRStrategy::mutate (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder">RandomIRBuilder</a> &amp; IB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>, definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a740b270dfd80a81a0765fb1d31930828">eliminateDeadCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/classes/llvm/irmutationstrategy/#af80c59250b5a5e540d6eaeb458be693a">llvm::IRMutationStrategy::mutate</a>.</p>

</div>
</div>

### mutate() {#a22c46265af5b3e456243d03b635ae9bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InjectorIRStrategy::mutate (<a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a> &amp; BB, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder">RandomIRBuilder</a> &amp; IB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp/#a7bc99de2f3874d014ce70d70c12f3b12">getInsertionRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#af2a9add76255a5e6dc09b1a5f9505f21">llvm::uniform</a>.</p>

</div>
</div>

### mutate() {#af80c59250b5a5e540d6eaeb458be693a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IRMutationStrategy::mutate (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder">RandomIRBuilder</a> &amp; IB)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Mutators for each IR unit. By default these forward to a contained instance of the next smaller unit.</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>, definition at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/basicblock/#ac9c170fde1808bbd4436a0dbd6d5e755">llvm::BasicBlock::isEHPad</a>.</p>

</div>
</div>

### mutate() {#a249b695824fd4f98a12b0be986fe7150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::IRMutationStrategy::mutate (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder">RandomIRBuilder</a> &amp; IB)</td>
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



<p>Definition at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### chooseOperation() {#adda0eee1a80f9288159dde7467542d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; fuzzerop::OpDescriptor &gt; InjectorIRStrategy::chooseOperation (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Src, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder">RandomIRBuilder</a> &amp; IB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>, definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Operations {#aaf33db5be239fd37a3d44694cb3b6941}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;fuzzerop::OpDescriptor&gt; llvm::InjectorIRStrategy::Operations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getDefaultOps() {#a0528fc09ee5324d528b7378b6ec78beb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; fuzzerop::OpDescriptor &gt; InjectorIRStrategy::getDefaultOps ()</td>
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



<p>Declaration at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a>, definition at line 96 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5a19c6aa42a42c2dc4d2aa51be8ab4c2">llvm::describeFuzzerAggregateOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac951769e67885a6a884fbec5c68c6930">llvm::describeFuzzerControlFlowOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab61cdcba81cc44be5d4fdff8c5172f1d">llvm::describeFuzzerFloatOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0854017d2b520df10302ff14d350a584">llvm::describeFuzzerIntOps</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acfd13abfd4cb8422e8db63a0e668f69a">llvm::describeFuzzerPointerOps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a85805fd963bb88590cfb345568b72d50">llvm::describeFuzzerVectorOps</a>.</p>


<p>Referenced by <a href="#afe981ff634aeceec82ac1dffd1753bea">InjectorIRStrategy</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/irmutator-h">IRMutator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/irmutator-cpp">IRMutator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
