---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/legacylegalizeactions
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `LegacyLegalizeActions` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::LegacyLegalizeActions { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">LegacyLegalizeAction : std::uint8_t { <a href="#ad25716c86372dafbf624b34891685078">...</a> }</td>
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

### LegacyLegalizeAction {#ad25716c86372dafbf624b34891685078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::LegacyLegalizeActions::LegacyLegalizeAction : std::uint8_t</td>
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
<td class="doxyEnumItemName">Legal<a id="ad25716c86372dafbf624b34891685078a2d949fba71eeb09f438bde429c97f73b"></a></td>
<td class="doxyEnumItemDescription">The operation is expected to be selectable directly by the target, and no transformation is necessary</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NarrowScalar<a id="ad25716c86372dafbf624b34891685078a5449e96e0fbabdf17da10f550e73fef7"></a></td>
<td class="doxyEnumItemDescription">The operation should be synthesized from multiple instructions acting on a narrower scalar base-type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WidenScalar<a id="ad25716c86372dafbf624b34891685078af024bf463bed5cbd23fd03a1499b4b48"></a></td>
<td class="doxyEnumItemDescription">The operation should be implemented in terms of a wider scalar base-type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FewerElements<a id="ad25716c86372dafbf624b34891685078a4f494c23358a431c763a6dc593381c78"></a></td>
<td class="doxyEnumItemDescription">The (vector) operation should be implemented by splitting it into sub-vectors where the operation is legal</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MoreElements<a id="ad25716c86372dafbf624b34891685078a2c6b35e9cd746d28ac9625e5f1694539"></a></td>
<td class="doxyEnumItemDescription">The (vector) operation should be implemented by widening the input vector and ignoring the lanes added by doing so</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bitcast<a id="ad25716c86372dafbf624b34891685078a031174d0f974cf1041a9cadb84f0dcbf"></a></td>
<td class="doxyEnumItemDescription">Perform the operation on a different, but equivalently sized type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Lower<a id="ad25716c86372dafbf624b34891685078a70d6bbaf9c336f6503bed0cee8421b29"></a></td>
<td class="doxyEnumItemDescription">The operation itself must be expressed in terms of simpler actions on this target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Libcall<a id="ad25716c86372dafbf624b34891685078af57e86597132ffdc2f10aa179c8d522b"></a></td>
<td class="doxyEnumItemDescription">The operation should be implemented as a call to some kind of runtime support library</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Custom<a id="ad25716c86372dafbf624b34891685078a77dcc0b01e20bc9215e0ce22d81aca98"></a></td>
<td class="doxyEnumItemDescription">The target wants to do something special with this combination of operand and type</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unsupported<a id="ad25716c86372dafbf624b34891685078a5118e62994caf312467b5e5539a9e39b"></a></td>
<td class="doxyEnumItemDescription">This operation is completely unsupported on the target</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NotFound<a id="ad25716c86372dafbf624b34891685078aa2a0de09ad7131649f5caf2ca1093396"></a></td>
<td class="doxyEnumItemDescription">Sentinel value for when no action was found in the specified table</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/legacylegalizerinfo-h">LegacyLegalizerInfo.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
