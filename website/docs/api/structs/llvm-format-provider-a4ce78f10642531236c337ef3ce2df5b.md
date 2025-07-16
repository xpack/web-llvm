---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/format-provider-a4ce78f10642531236c337ef3ce2df5b
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `format_provider` Struct Template Reference

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for type <span class="doxyComputerOutput">bool</span> <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::format_provider&lt;bool&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">llvm/Support/FormatProviders.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90b73d26259241c3400bb39fe8e4cad3">format</a> (const bool &amp;B, llvm::raw_ostream &amp;Stream, StringRef Style)</td>
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

<p>Implementation of <a href="/web-llvm/docs/api/structs/llvm/format-provider">format_provider&lt;T&gt;</a> for type <span class="doxyComputerOutput">bool</span></p>


<p>The options string of a boolean type has the grammar:</p>


<p>bool_options :: "" | "Y" | "y" | "D" | "d" | "T" | "t"</p>


<hr/>


## | C | Meaning | {#autotoc_md48}


<p>| Y | YES / NO | | y | yes / no | | D / d | Integer 0 or 1 | | T | TRUE / FALSE | | t | true / false |</p>


## | (empty) | Equivalent to 't' | {#autotoc_md49}


<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### format() {#a90b73d26259241c3400bb39fe8e4cad3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::format_provider&lt; bool &gt;::format (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool &amp; B, <a href="/web-llvm/docs/api/classes/llvm/raw-ostream">llvm::raw_ostream</a> &amp; Stream, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Style)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/formatproviders-h">FormatProviders.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
