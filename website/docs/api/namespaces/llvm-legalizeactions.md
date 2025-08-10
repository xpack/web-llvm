---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/legalizeactions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `LegalizeActions` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::LegalizeActions { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LegalizeAction : std::uint8_t { <a href="#a834a0e3032e20fe88a0c931e8f246654">...</a> }</td>
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


<div class="doxySectionDef">

## Enumerations

### LegalizeAction {#a834a0e3032e20fe88a0c931e8f246654}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LegalizeActions::LegalizeAction : std::uint8_t</td>
</tr>
</table>
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
<td class="doxyEnumItemName">Legal<a id="a834a0e3032e20fe88a0c931e8f246654a167074ba3b742859ff5dbe464381e107"></a></td>
<td class="doxyEnumItemDescription">The operation is expected to be selectable directly by the target, and no transformation is necessary</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NarrowScalar<a id="a834a0e3032e20fe88a0c931e8f246654ad0868c394d6503253b0d29c7e383e78b"></a></td>
<td class="doxyEnumItemDescription">The operation should be synthesized from multiple instructions acting on a narrower scalar base-type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WidenScalar<a id="a834a0e3032e20fe88a0c931e8f246654aad899913ed8431ad4b1c81f717f7a909"></a></td>
<td class="doxyEnumItemDescription">The operation should be implemented in terms of a wider scalar base-type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FewerElements<a id="a834a0e3032e20fe88a0c931e8f246654a123b973f813232425a88cae2ef685a5a"></a></td>
<td class="doxyEnumItemDescription">The (vector) operation should be implemented by splitting it into sub-vectors where the operation is legal</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MoreElements<a id="a834a0e3032e20fe88a0c931e8f246654af7c712e88ef2300e4bc43089d1cdf3e5"></a></td>
<td class="doxyEnumItemDescription">The (vector) operation should be implemented by widening the input vector and ignoring the lanes added by doing so</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bitcast<a id="a834a0e3032e20fe88a0c931e8f246654ac37bb600575f12795f12c117b2d86740"></a></td>
<td class="doxyEnumItemDescription">Perform the operation on a different, but equivalently sized type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lower<a id="a834a0e3032e20fe88a0c931e8f246654a5ff0dbefe0555c538e207b9ee20e26cf"></a></td>
<td class="doxyEnumItemDescription">The operation itself must be expressed in terms of simpler actions on this target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Libcall<a id="a834a0e3032e20fe88a0c931e8f246654a1e5ed9cc15d3744694855efcdf0b948e"></a></td>
<td class="doxyEnumItemDescription">The operation should be implemented as a call to some kind of runtime support library</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Custom<a id="a834a0e3032e20fe88a0c931e8f246654adbc4d3a46a3d7a515b5458a671394536"></a></td>
<td class="doxyEnumItemDescription">The target wants to do something special with this combination of operand and type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unsupported<a id="a834a0e3032e20fe88a0c931e8f246654a47383e4f532d33bd4f45d182896d7c17"></a></td>
<td class="doxyEnumItemDescription">This operation is completely unsupported on the target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotFound<a id="a834a0e3032e20fe88a0c931e8f246654af5708ed7587123419f3518dd98bbbfd5"></a></td>
<td class="doxyEnumItemDescription">Sentinel value for when no action was found in the specified table</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UseLegacyRules<a id="a834a0e3032e20fe88a0c931e8f246654a89cd916cb7d51db4ce46c592c2bf913b"></a></td>
<td class="doxyEnumItemDescription">Fall back onto the old rules</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legalizerinfo-h">LegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
