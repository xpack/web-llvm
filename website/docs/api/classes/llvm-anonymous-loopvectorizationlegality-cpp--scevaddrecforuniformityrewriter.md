---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/anonymous-loopvectorizationlegality-cpp-/scevaddrecforuniformityrewriter
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCEVAddRecForUniformityRewriter` Class Reference

<p>A rewriter to build the SCEVs for each of the VF lanes in the expected vectorized loop, which can then be compared to detect their uniformity. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor">SCEVRewriteVisitor&lt;SC&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This visitor recursively visits a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression and re-writes it. <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8be59937395cb0e56939958d38a5b7">SCEVAddRecForUniformityRewriter</a> (ScalarEvolution &amp;SE, unsigned StepMultiplier, unsigned Offset, Loop *TheLoop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa2b0da5272312c302e3c605f972234b">visitAddRecExpr</a> (const SCEVAddRecExpr *Expr)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23e8bb153583ce2e09b60a7564a89d5a">visit</a> (const SCEV *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7cd2c651bc65e33b966a9a7151f5ab9">visitUnknown</a> (const SCEVUnknown *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355bcc2b60bfb51acadc1e9d236a9dd6">visitCouldNotCompute</a> (const SCEVCouldNotCompute *S)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57a191f13b509b89df5295023574a642">canAnalyze</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb784978d768159e54f598c5ed178982">StepMultiplier</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Multiplier to be applied to the step of AddRecs in TheLoop. <a href="#aeb784978d768159e54f598c5ed178982">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abaa764be22d3f0a8cbe9f6f05698027a">Offset</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset to be added to the AddRecs in TheLoop. <a href="#abaa764be22d3f0a8cbe9f6f05698027a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56f06c6667cdf64bd60b8d139c4ecdeb">TheLoop</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> for which to rewrite AddRecsFor. <a href="#a56f06c6667cdf64bd60b8d139c4ecdeb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12e0488af0e559c187c49f18aeb050fc">CannotAnalyze</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is any sub-expressions not analyzable w.r.t. uniformity? <a href="#a12e0488af0e559c187c49f18aeb050fc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30f78b1ad849ac2b8310292271d2d838">rewrite</a> (const SCEV *S, ScalarEvolution &amp;SE, unsigned StepMultiplier, unsigned Offset, Loop *TheLoop)</td>
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

<p>A rewriter to build the SCEVs for each of the VF lanes in the expected vectorized loop, which can then be compared to detect their uniformity.</p>


<p>This is done by replacing the AddRec SCEVs of the original scalar loop (TheLoop) with new AddRecs where the step is multiplied by StepMultiplier and Offset * Step is added. Also checks if all sub-expressions are analyzable w.r.t. uniformity.</p>


<p>Definition at line 483 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SCEVAddRecForUniformityRewriter() {#a1c8be59937395cb0e56939958d38a5b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::SCEVAddRecForUniformityRewriter (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, unsigned StepMultiplier, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop)</td>
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



<p>Definition at line 500 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a402d133bc2a8069432f15be4dd517589">llvm::SCEVRewriteVisitor&lt; SCEVAddRecForUniformityRewriter &gt;::SCEVRewriteVisitor</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SCEVAddRecForUniformityRewriter &gt;::SE</a>.</p>


<p>Referenced by <a href="#a30f78b1ad849ac2b8310292271d2d838">rewrite</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### visit() {#a23e8bb153583ce2e09b60a7564a89d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visit (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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



<p>Definition at line 524 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SCEVAddRecForUniformityRewriter &gt;::SE</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a242a71a1c3d798925fbaa9faba8bb5a8">llvm::SCEVRewriteVisitor&lt; SC &gt;::visit</a>.</p>

</div>
</div>

### visitAddRecExpr() {#aaa2b0da5272312c302e3c605f972234b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visitAddRecExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * Expr)</td>
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



<p>Definition at line 505 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a1596600146d065022af8b9c4a1d0b427">llvm::SCEVAddRecExpr::getType</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SCEVAddRecForUniformityRewriter &gt;::SE</a>.</p>

</div>
</div>

### visitCouldNotCompute() {#a355bcc2b60bfb51acadc1e9d236a9dd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visitCouldNotCompute (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a> * S)</td>
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



<p>Definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### visitUnknown() {#ae7cd2c651bc65e33b966a9a7151f5ab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::visitUnknown (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> * S)</td>
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



<p>Definition at line 530 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SCEVAddRecForUniformityRewriter &gt;::SE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### canAnalyze() {#a57a191f13b509b89df5295023574a642}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::canAnalyze ()</td>
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



<p>Definition at line 497 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CannotAnalyze {#a12e0488af0e559c187c49f18aeb050fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::CannotAnalyze = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is any sub-expressions not analyzable w.r.t. uniformity?</p>

<p>Definition at line 495 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### Offset {#abaa764be22d3f0a8cbe9f6f05698027a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::Offset</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset to be added to the AddRecs in TheLoop.</p>

<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### StepMultiplier {#aeb784978d768159e54f598c5ed178982}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::StepMultiplier</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Multiplier to be applied to the step of AddRecs in TheLoop.</p>

<p>Definition at line 486 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

### TheLoop {#a56f06c6667cdf64bd60b8d139c4ecdeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Loop* llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::TheLoop</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> for which to rewrite AddRecsFor.</p>

<p>Definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### rewrite() {#a30f78b1ad849ac2b8310292271d2d838}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::anonymous{LoopVectorizationLegality.cpp}::SCEVAddRecForUniformityRewriter::rewrite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, unsigned StepMultiplier, unsigned Offset, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> * TheLoop)</td>
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



<p>Definition at line 544 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/virtregmap-cpp/#a1ad52109a2ff430460c8776286b97b2e">Rewriter</a>, <a href="#a1c8be59937395cb0e56939958d38a5b7">SCEVAddRecForUniformityRewriter</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#affb88623037a9864e030154052747ba1">llvm::SCEVExprContains</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a1f75cac3a0eec736a85d996723c70e64">llvm::SCEVRewriteVisitor&lt; SCEVAddRecForUniformityRewriter &gt;::SE</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorizationlegality-cpp">LoopVectorizationLegality.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
