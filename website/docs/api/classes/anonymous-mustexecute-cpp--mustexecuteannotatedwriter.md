---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-mustexecute-cpp-/mustexecuteannotatedwriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MustExecuteAnnotatedWriter` Class

<p>An assembly annotator class to print must execute information in comments. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class anonymous{MustExecute.cpp}::MustExecuteAnnotatedWriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a></td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b34c31c5be4ebfbfd92dd26bfbfbcc8">MustExecuteAnnotatedWriter</a> (const Function &amp;F, DominatorTree &amp;DT, LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae51e275dafe1a9e854c2cba79f8d6b15">MustExecuteAnnotatedWriter</a> (const Module &amp;M, DominatorTree &amp;DT, LoopInfo &amp;LI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ec9d1378f7a38ca516bfc751764765d">printInfoComment</a> (const Value &amp;V, formatted_raw_ostream &amp;OS) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>printInfoComment - This may be implemented to emit a comment to the right of an instruction or global value. <a href="#a5ec9d1378f7a38ca516bfc751764765d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *, 4 &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1a1782c0a21240984c7b44f6df5602e">MustExec</a></td>
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

<p>An assembly annotator class to print must execute information in comments.</p>

<p>Definition at line 333 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### MustExecuteAnnotatedWriter() {#a5b34c31c5be4ebfbfd92dd26bfbfbcc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MustExecute.cpp}::MustExecuteAnnotatedWriter::MustExecuteAnnotatedWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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



<p>Definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#aa4c6b9df27c53571f2a5d32e59f07a4d">isMustExecuteIn</a>.</p>

</div>
</div>

### MustExecuteAnnotatedWriter() {#ae51e275dafe1a9e854c2cba79f8d6b15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{MustExecute.cpp}::MustExecuteAnnotatedWriter::MustExecuteAnnotatedWriter (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp; DT, <a href="/web-llvm/docs/api/classes/llvm/loopinfo">LoopInfo</a> &amp; LI)</td>
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



<p>Definition at line 349 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/loopinfobase/#ad61bd84d4988c90bf6c5cd62d8e7fb00">llvm::LoopInfoBase&lt; BlockT, LoopT &gt;::getLoopFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/atomicexpandpass-cpp/#a1bcc06b1cb86bd0ea08f33323190bdaa">instructions</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#aa4c6b9df27c53571f2a5d32e59f07a4d">isMustExecuteIn</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### printInfoComment() {#a5ec9d1378f7a38ca516bfc751764765d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void anonymous{MustExecute.cpp}::MustExecuteAnnotatedWriter::printInfoComment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/formatted-raw-ostream">formatted_raw_ostream</a> &amp;)</td>
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

<p>printInfoComment - This may be implemented to emit a comment to the right of an instruction or global value.</p>

<p>Definition at line 364 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagonhardwareloops-cpp/#ada7c1594a393ede3ce32602d64d7ddb2">Loops</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### MustExec {#ad1a1782c0a21240984c7b44f6df5602e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const Value*, SmallVector&lt;Loop*, 4&gt; &gt; anonymous{MustExecute.cpp}::MustExecuteAnnotatedWriter::MustExec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp">MustExecute.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
