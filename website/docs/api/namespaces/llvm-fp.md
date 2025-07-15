---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/fp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `fp` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::fp { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ExceptionBehavior : uint8_t { <a href="#a51c5e09b2604faec548aef87bd482630">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Exception behavior used for floating point operations. <a href="#a51c5e09b2604faec548aef87bd482630">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Enumerations

### ExceptionBehavior {#a51c5e09b2604faec548aef87bd482630}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::fp::ExceptionBehavior : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Exception behavior used for floating point operations.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ebIgnore<a id="a51c5e09b2604faec548aef87bd482630ad8009e7c0ce2967115e856052243ac62"></a></td>
<td class="doxyEnumItemDescription">This corresponds to "fpexcept.ignore"</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ebMayTrap<a id="a51c5e09b2604faec548aef87bd482630ac0971b3e4cf010afada5a9673a705e48"></a></td>
<td class="doxyEnumItemDescription">This corresponds to "fpexcept.maytrap"</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ebStrict<a id="a51c5e09b2604faec548aef87bd482630a5dfc3e95e600e911e26874be1f27dba7"></a></td>
<td class="doxyEnumItemDescription">This corresponds to "fpexcept.strict"</td>
</tr>

</table>
</dd>
</dl>


<p>Each of these values correspond to some metadata argument value of a constrained floating point intrinsic. See the LLVM Language Reference Manual for details.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fpenv-h">FPEnv.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/fpenv-h">FPEnv.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
