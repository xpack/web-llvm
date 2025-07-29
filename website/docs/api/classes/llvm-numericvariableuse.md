---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/numericvariableuse
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `NumericVariableUse` Class

<p>Class representing the use of a numeric variable in the AST of an expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::NumericVariableUse { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheck/FileCheckImpl.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class representing the AST of a given expression. <a href="/web-llvm/docs/api/classes/llvm/expressionast/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2611f4acd9964a1879c8e2f45de349c2">NumericVariableUse</a> (StringRef Name, NumericVariable *Variable)</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a996950cd8ad96696ec5a27c8acef86">eval</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/expressionformat">ExpressionFormat</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5370b4f5f85e5dbd565ad75576f896a4">getImplicitFormat</a> (const SourceMgr &amp;SM) const override</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad646900e6980144d48c217c2e8fe64de">Variable</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to the class instance for the variable this use is about. <a href="#ad646900e6980144d48c217c2e8fe64de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class representing the use of a numeric variable in the AST of an expression.</p>

<p>Definition at line 280 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### NumericVariableUse() {#a2611f4acd9964a1879c8e2f45de349c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::NumericVariableUse::NumericVariableUse (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/numericvariable">NumericVariable</a> * Variable)</td>
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



<p>Definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/expressionast/#a4daa42d0e673e7617033a465eb547fd7">llvm::ExpressionAST::ExpressionAST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### eval() {#a2a996950cd8ad96696ec5a27c8acef86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; APInt &gt; NumericVariableUse::eval ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the value of the variable referenced by this instance.</p></dd>
</dl>


<p>Declaration at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 195 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/expressionast/#a7e88ea518049c603e70bc9f4ff763006">llvm::ExpressionAST::getExpressionStr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9999bd897fc8a1648bd69b36fee2d357">llvm::make_error</a>.</p>

</div>
</div>

### getImplicitFormat() {#a5370b4f5f85e5dbd565ad75576f896a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExpressionFormat &gt; llvm::NumericVariableUse::getImplicitFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>implicit format of this numeric variable.</p></dd>
</dl>


<p>Definition at line 293 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Variable {#ad646900e6980144d48c217c2e8fe64de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NumericVariable* llvm::NumericVariableUse::Variable</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to the class instance for the variable this use is about.</p>

<p>Definition at line 283 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
