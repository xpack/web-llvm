---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/orc/shared/trivialspssequenceserialization
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `TrivialSPSSequenceSerialization` Class Template

<p>Specialize this to implement 'trivial' sequence serialization for a concrete sequence type. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;typename SPSElementTagT, typename ConcreteSequenceT&gt;
class llvm::orc::shared::TrivialSPSSequenceSerialization&lt;SPSElementTagT, ConcreteSequenceT&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">llvm/ExecutionEngine/Orc/Shared/SimplePackedSerialization.h</a>"
</div>

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename SPSElementTagT, typename ConcreteSequenceT&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static constexpr bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6a3aca563eb40fe731b809e2ffc4a49d">available</a> = false</td>
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

<p>Specialize this to implement 'trivial' sequence serialization for a concrete sequence type.</p>


<p>Trivial sequence serialization uses the sequence's 'size' member to get the length of the sequence, and uses a range-based for loop to iterate over the elements.</p>


<p>Specializing this template class means that you do not need to provide a specialization of <a href="/web-llvm/docs/api/classes/llvm/orc/shared/spsserializationtraits">SPSSerializationTraits</a> for your type.</p>


<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>


<div class="doxySectionDef">

## Public Static Attributes

### available {#a6a3aca563eb40fe731b809e2ffc4a49d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename SPSElementTagT, typename ConcreteSequenceT&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::orc::shared::TrivialSPSSequenceSerialization&lt; SPSElementTagT, ConcreteSequenceT &gt;::available = false</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/executionengine/include/llvm/executionengine/orc/include/llvm/executionengine/orc/shared/simplepackedserialization-h">SimplePackedSerialization.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
