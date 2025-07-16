---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/zerocallusedregs
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `ZeroCallUsedRegs` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::ZeroCallUsedRegs { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ZeroCallUsedRegsKind : unsigned int { <a href="#af03f9c4ce466646943e50f317397cec0">...</a> }</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf42edc9fd7799c3df53103cbb16bde9">ONLY_USED</a> = 1U &lt;&lt; 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7992c63b4ae3ee7b2dd3906f9d3c302e">ONLY_GPR</a> = 1U &lt;&lt; 2</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5526e6aff0c01a52f69ea64772a8b50">ONLY_ARG</a> = 1U &lt;&lt; 3</td>
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

### ZeroCallUsedRegsKind {#af03f9c4ce466646943e50f317397cec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::ZeroCallUsedRegs::ZeroCallUsedRegsKind : unsigned int</td>
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
<td class="doxyEnumItemName">Skip<a id="af03f9c4ce466646943e50f317397cec0a72ef2b9b6965d078e3c7f95487a82d1c"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UsedGPRArg<a id="af03f9c4ce466646943e50f317397cec0a10b3b11234c3484fd40d935810c976d9"></a></td>
<td class="doxyEnumItemDescription"> (= ONLY_USED | ONLY_GPR | ONLY_ARG)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UsedGPR<a id="af03f9c4ce466646943e50f317397cec0a8843d86cb89f4fc7f81ea906ee936de5"></a></td>
<td class="doxyEnumItemDescription"> (= ONLY_USED | ONLY_GPR)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UsedArg<a id="af03f9c4ce466646943e50f317397cec0acb5e51f2df3a0397e5909475e70b52e1"></a></td>
<td class="doxyEnumItemDescription"> (= ONLY_USED | ONLY_ARG)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Used<a id="af03f9c4ce466646943e50f317397cec0a019d1ca7d50cc54b995f60d456435e87"></a></td>
<td class="doxyEnumItemDescription"> (= ONLY_USED)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllGPRArg<a id="af03f9c4ce466646943e50f317397cec0a6a88e6b065bde1744fb858e368a9cb6f"></a></td>
<td class="doxyEnumItemDescription"> (= ONLY_GPR | ONLY_ARG)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllGPR<a id="af03f9c4ce466646943e50f317397cec0a2602a5b1063650a0b028b7ce5c800be0"></a></td>
<td class="doxyEnumItemDescription"> (= ONLY_GPR)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AllArg<a id="af03f9c4ce466646943e50f317397cec0a96a2965a74546d1d432bc28cdaaacec8"></a></td>
<td class="doxyEnumItemDescription"> (= ONLY_ARG)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">All<a id="af03f9c4ce466646943e50f317397cec0ab1c94ca2fbc3e78fc30069c8d0f01680"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### ONLY\_ARG {#af5526e6aff0c01a52f69ea64772a8b50}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::ZeroCallUsedRegs::ONLY_ARG = 1U &lt;&lt; 3</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a>.</p>

</div>
</div>

### ONLY\_GPR {#a7992c63b4ae3ee7b2dd3906f9d3c302e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::ZeroCallUsedRegs::ONLY_GPR = 1U &lt;&lt; 2</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a>.</p>

</div>
</div>

### ONLY\_USED {#adf42edc9fd7799c3df53103cbb16bde9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned llvm::ZeroCallUsedRegs::ONLY_USED = 1U &lt;&lt; 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/codegen-h">CodeGen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
