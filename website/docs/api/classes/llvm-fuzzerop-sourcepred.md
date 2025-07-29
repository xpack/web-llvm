---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/fuzzerop/sourcepred
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SourcePred` Class

<p>A matcher/generator for finding suitable values for the next source in an operation's partially completed argument list. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::fuzzerop::SourcePred { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">llvm/FuzzMutate/OpDescriptor.h</a>"
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adefb837d00e2f45ea84e8153c5b157fe">PredT</a> = std::function&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Cur, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *New)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a list of already selected operands, returns whether a given new operand is suitable for the next operand. <a href="#adefb837d00e2f45ea84e8153c5b157fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4c752eaf3b250304b7bd3ceb8f920df">MakeT</a> = std::function&lt; std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;( <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Cur, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; BaseTypes)&gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a list of already selected operands and a set of valid base types for a fuzzer, generates a list of constants that could be used for the next operand. <a href="#aa4c752eaf3b250304b7bd3ceb8f920df">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1363e525ba49333460f4c13668ee52d">SourcePred</a> (PredT Pred, MakeT Make)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a fully general source predicate. <a href="#aa1363e525ba49333460f4c13668ee52d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01e1d16c27a5fb94153178d64b252c6">SourcePred</a> (PredT Pred, std::nullopt_t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3396d8b14dbd006a057abef07514d4f3">matches</a> (ArrayRef&lt; Value * &gt; Cur, const Value *New)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <span class="doxyComputerOutput">New</span> is compatible for the argument after <span class="doxyComputerOutput">Cur</span>. <a href="#a3396d8b14dbd006a057abef07514d4f3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc5c7c07ff94b9c89f3990134e6948e9">generate</a> (ArrayRef&lt; Value * &gt; Cur, ArrayRef&lt; Type * &gt; BaseTypes)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generates a list of potential values for the argument after <span class="doxyComputerOutput">Cur</span>. <a href="#acc5c7c07ff94b9c89f3990134e6948e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adefb837d00e2f45ea84e8153c5b157fe">PredT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2185f8a0bfab0a51ef0ff993c480f760">Pred</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa4c752eaf3b250304b7bd3ceb8f920df">MakeT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a024e07b601035bb708843194b92d220e">Make</a></td>
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

<p>A matcher/generator for finding suitable values for the next source in an operation's partially completed argument list.</p>


<p>Given that we're building some operation X and may have already filled some subset of its operands, this predicate determines if some value New is suitable for the next operand or generates a set of values that are suitable.</p>


<p>Definition at line 43 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### MakeT {#aa4c752eaf3b250304b7bd3ceb8f920df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::fuzzerop::SourcePred::MakeT =  std::function&lt;std::vector&lt;Constant *&gt;(
      ArrayRef&lt;Value *&gt; Cur, ArrayRef&lt;Type *&gt; BaseTypes)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a list of already selected operands and a set of valid base types for a fuzzer, generates a list of constants that could be used for the next operand.</p>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

### PredT {#adefb837d00e2f45ea84e8153c5b157fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::fuzzerop::SourcePred::PredT =  std::function&lt;bool(ArrayRef&lt;Value *&gt; Cur, const Value *New)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a list of already selected operands, returns whether a given new operand is suitable for the next operand.</p>

<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SourcePred() {#aa1363e525ba49333460f4c13668ee52d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::fuzzerop::SourcePred::SourcePred (<a href="#adefb837d00e2f45ea84e8153c5b157fe">PredT</a> Pred, <a href="#aa4c752eaf3b250304b7bd3ceb8f920df">MakeT</a> Make)</td>
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

<p>Create a fully general source predicate.</p>

<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

### SourcePred() {#ac01e1d16c27a5fb94153178d64b252c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::fuzzerop::SourcePred::SourcePred (<a href="#adefb837d00e2f45ea84e8153c5b157fe">PredT</a> Pred, std::nullopt_t)</td>
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



<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### generate() {#acc5c7c07ff94b9c89f3990134e6948e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Constant * &gt; llvm::fuzzerop::SourcePred::generate (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Cur, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; BaseTypes)</td>
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

<p>Generates a list of potential values for the argument after <span class="doxyComputerOutput">Cur</span>.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

### matches() {#a3396d8b14dbd006a057abef07514d4f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::fuzzerop::SourcePred::matches (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Cur, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * New)</td>
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

<p>Returns true if <span class="doxyComputerOutput">New</span> is compatible for the argument after <span class="doxyComputerOutput">Cur</span>.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Make {#a024e07b601035bb708843194b92d220e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MakeT llvm::fuzzerop::SourcePred::Make</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

### Pred {#a2185f8a0bfab0a51ef0ff993c480f760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredT llvm::fuzzerop::SourcePred::Pred</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 55 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
