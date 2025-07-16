---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/coverage/counterexpressionbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CounterExpressionBuilder` Class Reference

<p>A <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> expression builder is used to construct the counter expressions. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::coverage::CounterExpressionBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">llvm/ProfileData/Coverage/CoverageMapping.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefccee22c1710a19b5024c9014ce9346">SubstMap</a> = std::map&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>K to V map. <a href="#aefccee22c1710a19b5024c9014ce9346">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02117cb1da8fb0e1b98d8dfea9d0c985">getExpressions</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e96efec662a56b7381c06e6dbaa37af">add</a> (Counter LHS, Counter RHS, bool Simplify=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a counter that represents the expression that adds LHS and RHS. <a href="#a1e96efec662a56b7381c06e6dbaa37af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da55ae07a066d293e807a99458755f0">subtract</a> (Counter LHS, Counter RHS, bool Simplify=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a counter that represents the expression that subtracts RHS from LHS. <a href="#a0da55ae07a066d293e807a99458755f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4300f33f9daba299f3b3912e07770317">subst</a> (Counter C, const SubstMap &amp;Map)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a693b36d83f032a35706bdb491298286a">get</a> (const CounterExpression &amp;E)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the counter which corresponds to the given expression. <a href="#a693b36d83f032a35706bdb491298286a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f4fd46b17bee67fd8413662759037e3">extractTerms</a> (Counter C, int Sign, SmallVectorImpl&lt; Term &gt; &amp;Terms)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gather the terms of the expression tree for processing. <a href="#a2f4fd46b17bee67fd8413662759037e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1f6add151f50b27c674fc136d94cd0e">simplify</a> (Counter ExpressionTree)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplifies the given expression tree by getting rid of algebraically redundant operations. <a href="#ac1f6add151f50b27c674fc136d94cd0e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c99b3252a46805693259277e6e20868">Expressions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A list of all the counter expressions. <a href="#a2c99b3252a46805693259277e6e20868">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a>, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07143366ff7741af19bacbc686bbebc3">ExpressionIndices</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A lookup table for the index of a given expression. <a href="#a07143366ff7741af19bacbc686bbebc3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> expression builder is used to construct the counter expressions.</p>


<p>It avoids unnecessary duplication and simplifies algebraic expressions.</p>


<p>Definition at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### SubstMap {#aefccee22c1710a19b5024c9014ce9346}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::coverage::CounterExpressionBuilder::SubstMap =  std::map&lt;Counter, Counter&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>K to V map.</p>


<p>K will be <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> in most cases. V may be <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> or <a href="/web-llvm/docs/api/classes/llvm/expression">Expression</a>.</p>


<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a1e96efec662a56b7381c06e6dbaa37af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Counter CounterExpressionBuilder::add (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> LHS, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> RHS, bool Simplify=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a counter that represents the expression that adds LHS and RHS.</p>

<p>Declaration at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49ca455946e9fb6b90813a5b9480f4063e22">llvm::coverage::CounterExpression::Add</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp/#aa56209f617200c772b32fea2947178a7">simplify</a>.</p>


<p>Referenced by <a href="#a4300f33f9daba299f3b3912e07770317">subst</a>.</p>

</div>
</div>

### getExpressions() {#a02117cb1da8fb0e1b98d8dfea9d0c985}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; CounterExpression &gt; llvm::coverage::CounterExpressionBuilder::getExpressions ()</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### subst() {#a4300f33f9daba299f3b3912e07770317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Counter CounterExpressionBuilder::subst (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> C, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#aefccee22c1710a19b5024c9014ce9346">SubstMap</a> &amp; Map)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A counter equivalent to \C, with each term in its expression replaced with term from <span class="doxyComputerOutput">Map</span>.</p></dd>
</dl>


<p>Declaration at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 138 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49ca455946e9fb6b90813a5b9480f4063e22">llvm::coverage::CounterExpression::Add</a>, <a href="#a1e96efec662a56b7381c06e6dbaa37af">add</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a4300f33f9daba299f3b3912e07770317">subst</a>, <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49cad1416de918b7a5b4457401a093632670">llvm::coverage::CounterExpression::Subtract</a> and <a href="#a0da55ae07a066d293e807a99458755f0">subtract</a>.</p>


<p>Referenced by <a href="#a4300f33f9daba299f3b3912e07770317">subst</a>.</p>

</div>
</div>

### subtract() {#a0da55ae07a066d293e807a99458755f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Counter CounterExpressionBuilder::subtract (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> LHS, <a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> RHS, bool Simplify=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a counter that represents the expression that subtracts RHS from LHS.</p>

<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonbitsimplify-cpp/#aa56209f617200c772b32fea2947178a7">simplify</a> and <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression/#ae5156429537263d93d5d165c7501e49cad1416de918b7a5b4457401a093632670">llvm::coverage::CounterExpression::Subtract</a>.</p>


<p>Referenced by <a href="#a4300f33f9daba299f3b3912e07770317">subst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### extractTerms() {#a2f4fd46b17bee67fd8413662759037e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CounterExpressionBuilder::extractTerms (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> C, int Sign, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; Term &gt; &amp; Terms)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gather the terms of the expression tree for processing.</p>


<p>This collects each addition and subtraction referenced by the counter into a sequence that can be sorted and combined to build a simplified counter expression.</p>


<p>Declaration at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 58 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### get() {#a693b36d83f032a35706bdb491298286a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Counter CounterExpressionBuilder::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/coverage/counterexpression">CounterExpression</a> &amp; E)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the counter which corresponds to the given expression.</p>


<p>If the given expression is already stored in the builder, a counter that references that expression is returned. Otherwise, the given expression is added to the builder's collection of expressions.</p>


<p>Declaration at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

### simplify() {#ac1f6add151f50b27c674fc136d94cd0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Counter CounterExpressionBuilder::simplify (<a href="/web-llvm/docs/api/structs/llvm/coverage/counter">Counter</a> ExpressionTree)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simplifies the given expression tree by getting rid of algebraically redundant operations.</p>

<p>Declaration at line 207 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>, definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ExpressionIndices {#a07143366ff7741af19bacbc686bbebc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;CounterExpression, unsigned&gt; llvm::coverage::CounterExpressionBuilder::ExpressionIndices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A lookup table for the index of a given expression.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

### Expressions {#a2c99b3252a46805693259277e6e20868}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CounterExpression&gt; llvm::coverage::CounterExpressionBuilder::Expressions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A list of all the counter expressions.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/profiledata/include/llvm/profiledata/coverage/coveragemapping-h">CoverageMapping.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/profiledata/lib/profiledata/coverage/coveragemapping-cpp">CoverageMapping.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
