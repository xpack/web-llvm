---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-winexception-cpp-/invokestatechange
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `InvokeStateChange` Struct



## Declaration

<div class="doxyDeclaration">
struct anonymous{WinException.cpp}::InvokeStateChange { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f8e28d92f4cd6a583e8f77a4f6a71c">PreviousEndLabel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EH Label immediately after the last invoke in the previous state, or nullptr if the previous state was the null state. <a href="#a29f8e28d92f4cd6a583e8f77a4f6a71c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d65e8e7a055c989c981ef92b0c7734">NewStartLabel</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>EH label immediately before the first invoke in the new state, or nullptr if the new state is the null state. <a href="#a88d65e8e7a055c989c981ef92b0c7734">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b68f809046daead62cbdc2b2367b5d8">NewState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>State of the invoke following NewStartLabel, or NullState to indicate the presence of calls which may unwind to caller. <a href="#a0b68f809046daead62cbdc2b2367b5d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### NewStartLabel {#a88d65e8e7a055c989c981ef92b0c7734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* anonymous{WinException.cpp}::InvokeStateChange::NewStartLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EH label immediately before the first invoke in the new state, or nullptr if the new state is the null state.</p>

<p>Definition at line 381 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### NewState {#a0b68f809046daead62cbdc2b2367b5d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int anonymous{WinException.cpp}::InvokeStateChange::NewState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>State of the invoke following NewStartLabel, or NullState to indicate the presence of calls which may unwind to caller.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

### PreviousEndLabel {#a29f8e28d92f4cd6a583e8f77a4f6a71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const MCSymbol* anonymous{WinException.cpp}::InvokeStateChange::PreviousEndLabel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>EH Label immediately after the last invoke in the previous state, or nullptr if the previous state was the null state.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/asmprinter/winexception-cpp">WinException.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
