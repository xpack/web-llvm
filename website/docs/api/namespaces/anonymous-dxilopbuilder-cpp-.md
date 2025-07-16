---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/anonymous-dxilopbuilder-cpp-
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `anonymous{DXILOpBuilder.cpp}` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace anonymous{DXILOpBuilder.cpp} { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilopbuilder-cpp-/version">Version</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-dxilopbuilder-cpp-/opoverload">OpOverload</a></td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OverloadKind : uint16_t { <a href="#a3fe8fcf1f03e5da864eb86be303a3216">...</a> }</td>
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

### OverloadKind {#a3fe8fcf1f03e5da864eb86be303a3216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum anonymous{DXILOpBuilder.cpp}::OverloadKind : uint16_t</td>
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
<td class="doxyEnumItemName">UNDEFINED<a id="a3fe8fcf1f03e5da864eb86be303a3216a9045349aadd51459c6dbe4f3b1c43217"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VOID<a id="a3fe8fcf1f03e5da864eb86be303a3216a024a9a32ecf675c926c758581f6bf9bd"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HALF<a id="a3fe8fcf1f03e5da864eb86be303a3216a7335e3c4796125b052339203e9bee87c"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FLOAT<a id="a3fe8fcf1f03e5da864eb86be303a3216a0cb2f05d3d3bae54de28f97a63bc7609"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DOUBLE<a id="a3fe8fcf1f03e5da864eb86be303a3216a2101ebdffa84e38fb11a5cb6b68b04d9"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I1<a id="a3fe8fcf1f03e5da864eb86be303a3216a0bfbc695c285082c59ed77069aafbfae"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I8<a id="a3fe8fcf1f03e5da864eb86be303a3216ac383fd0eb699cf3a30312ec776eebaa2"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I16<a id="a3fe8fcf1f03e5da864eb86be303a3216a5526adc82ddfe412c99755949207ecf0"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I32<a id="a3fe8fcf1f03e5da864eb86be303a3216a1f0bcb70cad1532c77dd33155ac68acc"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">I64<a id="a3fe8fcf1f03e5da864eb86be303a3216a22de29aa2be8f8e321df4e69eded5d07"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UserDefineType<a id="a3fe8fcf1f03e5da864eb86be303a3216acf3f514bb7a7f97c8c6bc38334ffb02f"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ObjectType<a id="a3fe8fcf1f03e5da864eb86be303a3216a1955f73644e78a3ffadcf645300a22c2"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
