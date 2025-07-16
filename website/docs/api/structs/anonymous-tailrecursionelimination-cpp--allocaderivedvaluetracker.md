---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-tailrecursionelimination-cpp-/allocaderivedvaluetracker
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `AllocaDerivedValueTracker` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf48fa3a2373efca5ac054e8bff29b20">walk</a> (Value *Root)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6019b1c94104110144aa402a98d7076f">callUsesLocalStack</a> (CallBase &amp;CB, bool IsNocapture)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3d7ebbc3e201f27baa546848afa78b1">AllocaUsers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *, 32 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a404cc612471698c6dc7b24b5fe6fac">EscapePoints</a></td>
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


<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp">TailRecursionElimination.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### callUsesLocalStack() {#a6019b1c94104110144aa402a98d7076f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker::callUsesLocalStack (<a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CB, bool IsNocapture)</td>
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



<p>Definition at line 171 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp">TailRecursionElimination.cpp</a>.</p>


<p>References <a href="#ac3d7ebbc3e201f27baa546848afa78b1">AllocaUsers</a>, <a href="#a2a404cc612471698c6dc7b24b5fe6fac">EscapePoints</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a857a8c38e4856efec047cc914c25b692">llvm::CallBase::onlyReadsMemory</a>.</p>


<p>Referenced by <a href="#adf48fa3a2373efca5ac054e8bff29b20">walk</a>.</p>

</div>
</div>

### walk() {#adf48fa3a2373efca5ac054e8bff29b20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker::walk (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Root)</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp">TailRecursionElimination.cpp</a>.</p>


<p>References <a href="#a6019b1c94104110144aa402a98d7076f">callUsesLocalStack</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="#a2a404cc612471698c6dc7b24b5fe6fac">EscapePoints</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/smallptrsetimpl/#a9d834ae3da8c62c2b668dada51335eb0">llvm::SmallPtrSetImpl&lt; PtrType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a0c8ffe664a36e30d49c84d0aded2fe08">llvm::SmallVectorImpl&lt; T &gt;::pop_back_val</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AllocaUsers {#ac3d7ebbc3e201f27baa546848afa78b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 32&gt; anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker::AllocaUsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp">TailRecursionElimination.cpp</a>.</p>


<p>Referenced by <a href="#a6019b1c94104110144aa402a98d7076f">callUsesLocalStack</a>.</p>

</div>
</div>

### EscapePoints {#a2a404cc612471698c6dc7b24b5fe6fac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;Instruction *, 32&gt; anonymous{TailRecursionElimination.cpp}::AllocaDerivedValueTracker::EscapePoints</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp">TailRecursionElimination.cpp</a>.</p>


<p>Referenced by <a href="#a6019b1c94104110144aa402a98d7076f">callUsesLocalStack</a> and <a href="#adf48fa3a2373efca5ac054e8bff29b20">walk</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/tailrecursionelimination-cpp">TailRecursionElimination.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
