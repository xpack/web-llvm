---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/binaryoperation
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `BinaryOperation` Class

<p>Class representing a single binary operation in the AST of an expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::BinaryOperation { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a154484290a87bced44deeb38931127d4">BinaryOperation</a> (StringRef ExpressionStr, binop_eval_t EvalBinop, std::unique_ptr&lt; ExpressionAST &gt; LeftOp, std::unique_ptr&lt; ExpressionAST &gt; RightOp)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae881b7ad9c843880674599dbe5d85dd9">eval</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Evaluates the value of the binary operation represented by this AST, using EvalBinop on the result of recursively evaluating the operands. <a href="#ae881b7ad9c843880674599dbe5d85dd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/expressionformat">ExpressionFormat</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d9325add2b388eebc0420cf6a0fdb4">getImplicitFormat</a> (const SourceMgr &amp;SM) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadf8975cc3370af67454e3ba5b867333">LeftOperand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Left operand. <a href="#aadf8975cc3370af67454e3ba5b867333">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22f168c5c6fb0152b4891c0e69ec723b">RightOperand</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Right operand. <a href="#a22f168c5c6fb0152b4891c0e69ec723b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6555f12ac0d974429e146c133c780449">binop_eval_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5750c3eaf0ad9927e4ec13b252296d8">EvalBinop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pointer to function that can evaluate this binary operation. <a href="#ae5750c3eaf0ad9927e4ec13b252296d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class representing a single binary operation in the AST of an expression.</p>

<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BinaryOperation() {#a154484290a87bced44deeb38931127d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BinaryOperation::BinaryOperation (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ExpressionStr, <a href="/web-llvm/docs/api/namespaces/llvm/#a6555f12ac0d974429e146c133c780449">binop_eval_t</a> EvalBinop, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt; LeftOp, std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/expressionast">ExpressionAST</a> &gt; RightOp)</td>
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



<p>Definition at line 314 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/expressionast/#a4daa42d0e673e7617033a465eb547fd7">llvm::ExpressionAST::ExpressionAST</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### eval() {#ae881b7ad9c843880674599dbe5d85dd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; APInt &gt; BinaryOperation::eval ()</td>
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

<p>Evaluates the value of the binary operation represented by this AST, using EvalBinop on the result of recursively evaluating the operands.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the expression value or an error if an undefined numeric variable is used in one of the operands.</p></dd>
</dl>


<p>Declaration at line 326 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 203 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp/#af1eb91b7a599d7ef03c2282a78e99466">nextAPIntBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aca8fce65eb69a82aa10a635e2e79877a">llvm::APInt::sext</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

### getImplicitFormat() {#a24d9325add2b388eebc0420cf6a0fdb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; ExpressionFormat &gt; BinaryOperation::getImplicitFormat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sourcemgr">SourceMgr</a> &amp; SM)</td>
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
<dd><p>the implicit format of this AST, if any, a diagnostic against <span class="doxyComputerOutput">SM</span> if the implicit formats of the AST's components conflict, or no format if the AST has no implicit format (e.g. AST is made of a single literal).</p></dd>
</dl>


<p>Declaration at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>, definition at line 242 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheck-cpp">FileCheck.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/errordiagnostic/#afd2d10db0e8822de9860636d612a13af">llvm::ErrorDiagnostic::get</a>, <a href="/web-llvm/docs/api/classes/llvm/expressionast/#a7e88ea518049c603e70bc9f4ff763006">llvm::ExpressionAST::getExpressionStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a71210b99d2ef87236d8505c1771a7ab1">llvm::joinErrors</a>, <a href="/web-llvm/docs/api/structs/llvm/expressionformat/#a8aa1badb3ecc62f86172f9f85928fb61aa305d2e7bbf7ddc98728fa844c9e210e">llvm::ExpressionFormat::NoFormat</a>, <a href="/web-llvm/docs/api/classes/llvm/error/#a4dfd0813c3d0e0a30439b5a3e9196b59">llvm::Error::success</a> and <a href="/web-llvm/docs/api/classes/llvm/expected/#a94789df4ebd03dc008e8adebaa66ac1f">llvm::Expected&lt; T &gt;::takeError</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EvalBinop {#ae5750c3eaf0ad9927e4ec13b252296d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">binop_eval_t llvm::BinaryOperation::EvalBinop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pointer to function that can evaluate this binary operation.</p>

<p>Definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### LeftOperand {#aadf8975cc3370af67454e3ba5b867333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ExpressionAST&gt; llvm::BinaryOperation::LeftOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Left operand.</p>

<p>Definition at line 305 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

</div>
</div>

### RightOperand {#a22f168c5c6fb0152b4891c0e69ec723b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ExpressionAST&gt; llvm::BinaryOperation::RightOperand</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Right operand.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/lib/lib/filecheck/filecheckimpl-h">FileCheckImpl.h</a>.</p>

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
