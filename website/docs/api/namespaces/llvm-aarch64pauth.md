---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/aarch64pauth
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `AArch64PAuth` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::AArch64PAuth { ... }
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4ee5c509a18d1b04fd6be73f6d0d9b1">None</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Variants of check performed on an authenticated pointer. <a href="#ad4ee5c509a18d1b04fd6be73f6d0d9b1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84f299c794c2b52d77fce8c7f7e3b0ea">DummyLoad</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Perform a load to a temporary register. <a href="#a84f299c794c2b52d77fce8c7f7e3b0ea">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Variables

### DummyLoad {#a84f299c794c2b52d77fce8c7f7e3b0ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AArch64PAuth::DummyLoad</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Perform a load to a temporary register.</p>

<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a>.</p>

</div>
</div>

### None {#ad4ee5c509a18d1b04fd6be73f6d0d9b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::AArch64PAuth::None</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Variants of check performed on an authenticated pointer.</p>


<p>In cases such as authenticating the LR value when performing a tail call or when re-signing a signed pointer with a different signing schema, a failed authentication may not generate an exception on its own and may create an authentication or signing oracle if not checked explicitly.</p>


<p>A number of check methods modify control flow in a similar way by rewriting the code</p>


<p><span class="doxyComputerOutput"> &lt;authenticate LR&gt; &lt;more instructions&gt; </span></p>


<p>as follows:</p>


<p>``` &lt;authenticate LR&gt; &lt;method-specific checker&gt; on_fail: brk <span class="doxyComputerOutput"> on_success: &lt;more instructions&gt;</span></p>


<p><span class="doxyComputerOutput"> ``` enum class AuthCheckMethod { Do not check the value at all </span></p>


<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64pointerauth-h">AArch64PointerAuth.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
