---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/abstractlatticefunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `AbstractLatticeFunction` Class Template

<p><a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction">AbstractLatticeFunction</a> - This class is implemented by the dataflow instance to specify what the lattice values are and how they handle merges etc. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class LatticeKey, class LatticeVal&gt;
class llvm::AbstractLatticeFunction&lt;LatticeKey, LatticeVal&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">llvm/Analysis/SparsePropagation.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a3630859cb3da8279f4ee4b50e6d86851">AbstractLatticeFunction</a> (LatticeVal undefVal, LatticeVal overdefinedVal, LatticeVal untrackedVal)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#abd2e72a95ce549143516d634591a3be0">~AbstractLatticeFunction</a> ()=default</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac8c706169cac63369933e4bc06012858">getUndefVal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a02ada13ec5d86d5ef19b22b784b4ffd1">getOverdefinedVal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9f907a6f73caddcf4ee0f2da89775a8d">getUntrackedVal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9b60ccf8ced2365eddf37c593f57c9ab">IsUntrackedValue</a> (LatticeKey Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsUntrackedValue - If the specified LatticeKey is obviously uninteresting to the analysis (i.e., it would always return UntrackedVal), this function can return true to avoid pointless work. <a href="#a9b60ccf8ced2365eddf37c593f57c9ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ab816519e09cacfdba6d7238354dac579">ComputeLatticeVal</a> (LatticeKey Key)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ComputeLatticeVal - Compute and return a LatticeVal corresponding to the given LatticeKey. <a href="#ab816519e09cacfdba6d7238354dac579">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ad1454aaace96d639ee345ff604efdeb7">IsSpecialCasedPHI</a> (PHINode *PN)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>IsSpecialCasedPHI - Given a PHI node, determine whether this PHI node is one that the we want to handle through ComputeInstructionState. <a href="#ad1454aaace96d639ee345ff604efdeb7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad312f76a0ca98ce02ab059d30d07f4d">MergeValues</a> (LatticeVal X, LatticeVal Y)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MergeValues - Compute and return the merge of the two specified lattice values. <a href="#aad312f76a0ca98ce02ab059d30d07f4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a78126cf5b7b84ad3538971c5ff628b7d">ComputeInstructionState</a> (Instruction &amp;I, SmallDenseMap&lt; LatticeKey, LatticeVal, 16 &gt; &amp;ChangedValues, SparseSolver&lt; LatticeKey, LatticeVal &gt; &amp;SS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>ComputeInstructionState - Compute the LatticeKeys that change as a result of executing instruction <span class="doxyComputerOutput">I</span>. <a href="#a78126cf5b7b84ad3538971c5ff628b7d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c8587148919487006b8f9ceb218fa22">PrintLatticeVal</a> (LatticeVal LV, raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PrintLatticeVal - Render the given LatticeVal to the specified stream. <a href="#a9c8587148919487006b8f9ceb218fa22">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7985e661e2a246cec7d1f8a0b4b858e0">PrintLatticeKey</a> (LatticeKey Key, raw_ostream &amp;OS)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>PrintLatticeKey - Render the given LatticeKey to the specified stream. <a href="#a7985e661e2a246cec7d1f8a0b4b858e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a90f18696b6a1b5a6c2ef41bb1affe1bc">GetValueFromLatticeVal</a> (LatticeVal LV, Type *Ty=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetValueFromLatticeVal - If the given LatticeVal is representable as an LLVM value, return it; otherwise, return nullptr. <a href="#a90f18696b6a1b5a6c2ef41bb1affe1bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae22df1c297d7563a61c20dc5a41192ae">UndefVal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a266b65b20d1c86d7bd7c5827d6fbbe62">OverdefinedVal</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class LatticeKey, class LatticeVal&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">LatticeVal</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a482f7cca53fd1ecaa33521d40da04e53">UntrackedVal</a></td>
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

<p><a href="/web-llvm/docs/api/classes/llvm/abstractlatticefunction">AbstractLatticeFunction</a> - This class is implemented by the dataflow instance to specify what the lattice values are and how they handle merges etc.</p>


<p>This gives the client the power to compute lattice values from instructions, constants, etc. The current requirement is that lattice values must be copyable. At the moment, nothing tries to avoid copying. Additionally, lattice keys must be able to be used as keys of a mapping data structure. Internally, the generic solver currently uses a <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a> to map lattice keys to lattice values. If the lattice key is a non-standard type, a specialization of <a href="/web-llvm/docs/api/structs/llvm/densemapinfo">DenseMapInfo</a> must be provided.</p>


<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### AbstractLatticeFunction() {#a3630859cb3da8279f4ee4b50e6d86851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::AbstractLatticeFunction (LatticeVal undefVal, LatticeVal overdefinedVal, LatticeVal untrackedVal)</td>
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



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~AbstractLatticeFunction() {#abd2e72a95ce549143516d634591a3be0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::~AbstractLatticeFunction ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### ComputeInstructionState() {#a78126cf5b7b84ad3538971c5ff628b7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::ComputeInstructionState (<a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> &amp; I, <a href="/web-llvm/docs/api/classes/llvm/smalldensemap">SmallDenseMap</a>&lt; LatticeKey, LatticeVal, 16 &gt; &amp; ChangedValues, <a href="/web-llvm/docs/api/classes/llvm/sparsesolver">SparseSolver</a>&lt; LatticeKey, LatticeVal &gt; &amp; SS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>ComputeInstructionState - Compute the LatticeKeys that change as a result of executing instruction <span class="doxyComputerOutput">I</span>.</p>


<p>Their associated LatticeVals are store in <span class="doxyComputerOutput">ChangedValues</span>.</p>


<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### ComputeLatticeVal() {#ab816519e09cacfdba6d7238354dac579}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::ComputeLatticeVal (LatticeKey Key)</td>
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

<p>ComputeLatticeVal - Compute and return a LatticeVal corresponding to the given LatticeKey.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>


<p>References <a href="#a02ada13ec5d86d5ef19b22b784b4ffd1">llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::getOverdefinedVal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### getOverdefinedVal() {#a02ada13ec5d86d5ef19b22b784b4ffd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::getOverdefinedVal ()</td>
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



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>


<p>Referenced by <a href="#ab816519e09cacfdba6d7238354dac579">llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::ComputeLatticeVal</a> and <a href="#aad312f76a0ca98ce02ab059d30d07f4d">llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::MergeValues</a>.</p>

</div>
</div>

### getUndefVal() {#ac8c706169cac63369933e4bc06012858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::getUndefVal ()</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

### getUntrackedVal() {#a9f907a6f73caddcf4ee0f2da89775a8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::getUntrackedVal ()</td>
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



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

### GetValueFromLatticeVal() {#a90f18696b6a1b5a6c2ef41bb1affe1bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual Value * llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::GetValueFromLatticeVal (LatticeVal LV, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty=nullptr)</td>
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

<p>GetValueFromLatticeVal - If the given LatticeVal is representable as an LLVM value, return it; otherwise, return nullptr.</p>


<p>If a type is given, the returned value must have the same type. This function is used by the generic solver in attempting to resolve branch and switch conditions.</p>


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

### IsSpecialCasedPHI() {#ad1454aaace96d639ee345ff604efdeb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::IsSpecialCasedPHI (<a href="/web-llvm/docs/api/classes/llvm/phinode">PHINode</a> * PN)</td>
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

<p>IsSpecialCasedPHI - Given a PHI node, determine whether this PHI node is one that the we want to handle through ComputeInstructionState.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

### IsUntrackedValue() {#a9b60ccf8ced2365eddf37c593f57c9ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::IsUntrackedValue (LatticeKey Key)</td>
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

<p>IsUntrackedValue - If the specified LatticeKey is obviously uninteresting to the analysis (i.e., it would always return UntrackedVal), this function can return true to avoid pointless work.</p>

<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### MergeValues() {#aad312f76a0ca98ce02ab059d30d07f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::MergeValues (LatticeVal X, LatticeVal Y)</td>
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

<p>MergeValues - Compute and return the merge of the two specified lattice values.</p>


<p>Merging should only move one direction down the lattice to guarantee convergence (toward overdefined).</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>


<p>References <a href="#a02ada13ec5d86d5ef19b22b784b4ffd1">llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::getOverdefinedVal</a>, <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#ab60f28d7a141ac46ccc200176a1bca8b">X</a> and <a href="/web-llvm/docs/api/files/lib/lib/tablegen/tablegenbackendskeleton-cpp/#a262774d3e5186511427e5b2414a85f7f">Y</a>.</p>

</div>
</div>

### PrintLatticeKey() {#a7985e661e2a246cec7d1f8a0b4b858e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::PrintLatticeKey (LatticeKey Key, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>PrintLatticeKey - Render the given LatticeKey to the specified stream.</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### PrintLatticeVal() {#a9c8587148919487006b8f9ceb218fa22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::PrintLatticeVal (LatticeVal LV, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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

<p>PrintLatticeVal - Render the given LatticeVal to the specified stream.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### OverdefinedVal {#a266b65b20d1c86d7bd7c5827d6fbbe62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::OverdefinedVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

### UndefVal {#ae22df1c297d7563a61c20dc5a41192ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::UndefVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

### UntrackedVal {#a482f7cca53fd1ecaa33521d40da04e53}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class LatticeKey, class LatticeVal&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LatticeVal llvm::AbstractLatticeFunction&lt; LatticeKey, LatticeVal &gt;::UntrackedVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/sparsepropagation-h">SparsePropagation.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
