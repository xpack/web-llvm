---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/printable
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Printable` Class

<p>Simple wrapper around std::function&lt;void(raw_ostream&amp;)&gt;. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Printable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/printable-h">llvm/Support/Printable.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a249eb6b998536519ef6f7e363931e4d0">Printable</a> (std::function&lt; void(raw_ostream &amp;OS)&gt; Print)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;OS)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c71fd195a3144750d9faab2736a48fa">Print</a></td>
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

<p>Simple wrapper around std::function&lt;void(raw_ostream&amp;)&gt;.</p>


<p>This class is useful to construct print helpers for <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a>.</p>


<p>Example: <a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a> printRegister(unsigned Register) { return <a href="/web-llvm/docs/api/classes/llvm/printable">Printable</a>([<a href="/web-llvm/docs/api/classes/llvm/register">Register</a>](<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;OS) { OS &lt;&lt; getRegisterName(Register); }); } ... OS &lt;&lt; printRegister(Register); ...</p>


<p>Implementation note: Ideally this would just be a typedef, but doing so leads to operator &lt;&lt; being ambiguous as function has matching constructors in some STL versions. I have seen the problem on gcc 4.6 libstdc++ and microsoft STL.</p>


<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/printable-h">Printable.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Printable() {#a249eb6b998536519ef6f7e363931e4d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::Printable::Printable (std::function&lt; void(<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp;OS)&gt; Print)</td>
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



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/printable-h">Printable.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abfc9c7ecf70f66901e439f7c04ef3dbb">llvm::move</a> and <a href="#a2c71fd195a3144750d9faab2736a48fa">Print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Print {#a2c71fd195a3144750d9faab2736a48fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;void(raw_ostream &amp;OS)&gt; llvm::Printable::Print</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/printable-h">Printable.h</a>.</p>


<p>Referenced by <a href="#a249eb6b998536519ef6f7e363931e4d0">Printable</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/printable-h">Printable.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
