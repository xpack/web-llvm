---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scevnaryexpr
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SCEVNAryExpr` Class

<p>This node is a base class providing common functionality for n'ary operators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCEVNAryExpr { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">llvm/Analysis/ScalarEvolutionExpressions.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents an analyzed expression in the program. <a href="/web-llvm/docs/api/classes/llvm/scev/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node represents a polynomial recurrence on the trip count of the specified loop. <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevcommutativeexpr">SCEVCommutativeExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node is the base class for n'ary commutative operators. <a href="/web-llvm/docs/api/classes/llvm/scevcommutativeexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr">SCEVSequentialMinMaxExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node is the base class for sequential/in-order min/max selections. <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d2af00b10cda0b511a84a742d13f00">SCEVNAryExpr</a> (const FoldingSetNodeIDRef ID, enum SCEVTypes T, const SCEV *const *O, size_t N)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a689b72d735546bcbfc4b48a266503085">getNumOperands</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99e00da7acb7973ae006f5b53ce04f6">getOperand</a> (unsigned i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae77d0f7b81cbde08d5fd75fcf2fcf36b">operands</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">NoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7275347a4dce174f4fecd548fd3255dc">getNoWrapFlags</a> (NoWrapFlags Mask=NoWrapMask) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09cc70290a71475141063b6dff42a5d2">hasNoUnsignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71deee7ef49ab5407b7e1aa758b6ec0a">hasNoSignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6429bca8fd0024ceb2d76ccaace43c4e">hasNoSelfWrap</a> () const</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a>  *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb1a17a50dcac886c98f6329540e289">Operands</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e88bcd8bc5b9d3ee51b1b8b1414c387">NumOperands</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683f6ac8f67a2aa12754c196dc96c9e3">classof</a> (const SCEV *S)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a683f6ac8f67a2aa12754c196dc96c9e3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This node is a base class providing common functionality for n'ary operators.</p>

<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<div class="doxySectionDef">

## Protected Constructors

### SCEVNAryExpr() {#a76d2af00b10cda0b511a84a742d13f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEVNAryExpr::SCEVNAryExpr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeidref">FoldingSetNodeIDRef</a> ID, enum <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> * O, size_t N)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 205 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a3d8e1e329cf813ca2b411957a4d11d5d">llvm::computeExpressionSize</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="#a2e88bcd8bc5b9d3ee51b1b8b1414c387">NumOperands</a>, <a href="#adbb1a17a50dcac886c98f6329540e289">Operands</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#ace7f137cfb19ce8073b78b85f819430c">llvm::SCEV::SCEV</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVAddRecExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcommutativeexpr/#a6786459f166c925afb763d543d57daaa">llvm::SCEVCommutativeExpr::SCEVCommutativeExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#a2569193b6e3198b19ca3a210e8f450bd">llvm::SCEVSequentialMinMaxExpr::SCEVSequentialMinMaxExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNoWrapFlags() {#a7275347a4dce174f4fecd548fd3255dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NoWrapFlags llvm::SCEVNAryExpr::getNoWrapFlags (<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">NoWrapFlags</a> Mask=<a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fae022582ed4b56bdb108b4488809e11e6">NoWrapMask</a>)</td>
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



<p>Definition at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fae022582ed4b56bdb108b4488809e11e6">llvm::SCEV::NoWrapMask</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#ade1f1b89affe842dacd20c7f950e99c9">llvm::SCEV::SubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bab447a6422427e5fc92bbbc0c12fba">llvm::ScalarEvolution::getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="#a6429bca8fd0024ceb2d76ccaace43c4e">hasNoSelfWrap</a>, <a href="#a71deee7ef49ab5407b7e1aa758b6ec0a">hasNoSignedWrap</a>, <a href="#a09cc70290a71475141063b6dff42a5d2">hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a865c6ae11d94c83d4a7bcc0527f0fcef">IsKnownPredicateViaAddRecStart</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a9d9847ba3ad2bc2837b041581277a8fb">isNoWrapAddRec</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a248dea99ef1d5a864269ac3a98014b37">llvm::ScalarEvolution::setNoWrapFlags</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ac38f0b8f591d282177a689cabe66c392">llvm::SCEVDivision::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevloopaddrecrewriter/#a286583ef8d17944c4d4a4e3abcf65fef">llvm::SCEVLoopAddRecRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#ae7723e8cfb7ea733908442f8ef2d5d85">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a6d82a4b5dcc63a42638f2ee9b9c2e876">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitSignExtendExpr</a> and <a href="/web-llvm/docs/api/classes/anonymous-scalarevolution-cpp-/scevpredicaterewriter/#a169c4e815b26d46ffdd9e079a89461b8">anonymous{ScalarEvolution.cpp}::SCEVPredicateRewriter::visitZeroExtendExpr</a>.</p>

</div>
</div>

### getNumOperands() {#a689b72d735546bcbfc4b48a266503085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SCEVNAryExpr::getNumOperands ()</td>
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



<p>Definition at line 211 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Reference <a href="#a2e88bcd8bc5b9d3ee51b1b8b1414c387">NumOperands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ab1ecca94c1ac1a616d83f565a4aeaeae">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a8e3dc6f52dcd0a9cf61508d5703cbe57">llvm::SCEVAddRecExpr::getPostIncExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a99c9ef8776106c1e7b35c77a32e750e1">GetQuadraticEquation</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a54bb7394d874cbbef1d81e6bea89d4f3">llvm::SCEVAddRecExpr::isAffine</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a5e91958e021e28eb6fbd30f76c96b731">llvm::SCEVAddRecExpr::isQuadratic</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#adaa8fd1f2af30380d7080ef96b976209">MatchNotExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>.</p>

</div>
</div>

### getOperand() {#ad99e00da7acb7973ae006f5b53ce04f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * llvm::SCEVNAryExpr::getOperand (unsigned i)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a2e88bcd8bc5b9d3ee51b1b8b1414c387">NumOperands</a>, <a href="#adbb1a17a50dcac886c98f6329540e289">Operands</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#ace7f137cfb19ce8073b78b85f819430c">llvm::SCEV::SCEV</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ab1ecca94c1ac1a616d83f565a4aeaeae">extractConstantWithoutWrapping</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a8e3dc6f52dcd0a9cf61508d5703cbe57">llvm::SCEVAddRecExpr::getPostIncExpr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a99c9ef8776106c1e7b35c77a32e750e1">GetQuadraticEquation</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab10dcc08be6d7ecc655688c7f5e5fcca">getStoreStride</a>, <a href="/web-llvm/docs/api/classes/llvm/scevminmaxexpr/#a0b15683671fc89c570661c1c1783273e">llvm::SCEVMinMaxExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevmulexpr/#aeb2d92e2cfbf96877bd5c18683bf2390">llvm::SCEVMulExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#ad62e2173f3880516093efbf3bcaf68e2">llvm::SCEVSequentialMinMaxExpr::getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#adaa8fd1f2af30380d7080ef96b976209">MatchNotExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a8fa1050509c4edb3c4683179e01035a2">SolveQuadraticAddRecRange</a>.</p>

</div>
</div>

### hasNoSelfWrap() {#a6429bca8fd0024ceb2d76ccaace43c4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVNAryExpr::hasNoSelfWrap ()</td>
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



<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3">llvm::SCEV::FlagNW</a> and <a href="#a7275347a4dce174f4fecd548fd3255dc">getNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/looptermfold-cpp/#a0e67dc55f94f7419d24a39fa5b79c42f">canFoldTermCondOfLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>.</p>

</div>
</div>

### hasNoSignedWrap() {#a71deee7ef49ab5407b7e1aa758b6ec0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVNAryExpr::hasNoSignedWrap ()</td>
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



<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a> and <a href="#a7275347a4dce174f4fecd548fd3255dc">getNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>.</p>

</div>
</div>

### hasNoUnsignedWrap() {#a09cc70290a71475141063b6dff42a5d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVNAryExpr::hasNoUnsignedWrap ()</td>
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



<p>Definition at line 226 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656">llvm::SCEV::FlagAnyWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a> and <a href="#a7275347a4dce174f4fecd548fd3255dc">getNoWrapFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a741e5065c867d7dfd716eb8e16fccf12">llvm::ScalarEvolution::getLoopInvariantPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>.</p>

</div>
</div>

### operands() {#ae77d0f7b81cbde08d5fd75fcf2fcf36b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const SCEV * &gt; llvm::SCEVNAryExpr::operands ()</td>
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



<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#a2e88bcd8bc5b9d3ee51b1b8b1414c387">NumOperands</a> and <a href="#adbb1a17a50dcac886c98f6329540e289">Operands</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a54c5a810b1d6fbe75255674e7e9c40ba">BuildConstantFromSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a33583576f220997d1c415df033559a57">llvm::SCEVAddRecExpr::evaluateAtIteration</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef6d2bea715d1793e956f41ddeea2320">llvm::ScalarEvolution::getAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bab447a6422427e5fc92bbbc0c12fba">llvm::ScalarEvolution::getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ac3221ac3fcd879a1c716aa954837df79">llvm::ScalarEvolution::getMinMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a359235e468f7ab6f4dccbed37c17dee1">getPreStartForExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#acdbe9e14ed6edbd5b5e3c252585902ec">llvm::SCEV::print</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#a0b92dc455822b15a2cbfdff183ad761c">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::pushArithmeticExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/loopguards/#afc980d8379c6a1d12d091ba6b33aa05f">llvm::ScalarEvolution::LoopGuards::rewrite</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ae8ee3aa50e72940cabb7d758613ce2cf">llvm::SCEVDivision::visitAddExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a526f03cb420e8f64cd03750939bff699">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddExpr</a>, <a href="/web-llvm/docs/api/structs/anonymous-scalarevolutionnormalization-cpp-/normalizedenormalizerewriter/#ac9bcd9133d19e4e656a82dd8e900d3f8">anonymous{ScalarEvolutionNormalization.cpp}::NormalizeDenormalizeRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevloopaddrecrewriter/#a286583ef8d17944c4d4a4e3abcf65fef">llvm::SCEVLoopAddRecRewriter::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#ae7723e8cfb7ea733908442f8ef2d5d85">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitAddRecExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#afab4a1d0e1f34b286eec49ac8bd96ef1">llvm::SCEVDivision::visitMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a7ba1cee011d4868e8966a81a41ffff38">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a4a27c503b298dbe2a78b945b8c9025f6">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSequentialUMinExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#ac90f8a765813f19c8c20f90153a7cc82">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMaxExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a38b17b6e44b9937c10d4a4277a7abecb">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitSMinExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#aba42491077efa5e60b2c439f0a59a645">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMaxExpr</a> and <a href="/web-llvm/docs/api/classes/llvm/scevrewritevisitor/#a5481db1a659c011e71a0a75ce7416735">llvm::SCEVRewriteVisitor&lt; SC &gt;::visitUMinExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### NumOperands {#a2e88bcd8bc5b9d3ee51b1b8b1414c387}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::SCEVNAryExpr::NumOperands</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Referenced by <a href="#a689b72d735546bcbfc4b48a266503085">getNumOperands</a>, <a href="#ad99e00da7acb7973ae006f5b53ce04f6">getOperand</a>, <a href="#ae77d0f7b81cbde08d5fd75fcf2fcf36b">operands</a> and <a href="#a76d2af00b10cda0b511a84a742d13f00">SCEVNAryExpr</a>.</p>

</div>
</div>

### Operands {#adbb1a17a50dcac886c98f6329540e289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* const* llvm::SCEVNAryExpr::Operands</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 202 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#aa6f92c963408bac18b86bf6f0cfeb06f">llvm::SCEVAddRecExpr::evaluateAtIteration</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a7e688afe102c3fa48ea49cb972a0f00c">llvm::SCEVAddRecExpr::getNumIterationsInRange</a>, <a href="#ad99e00da7acb7973ae006f5b53ce04f6">getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a>, <a href="#ae77d0f7b81cbde08d5fd75fcf2fcf36b">operands</a> and <a href="#a76d2af00b10cda0b511a84a742d13f00">SCEVNAryExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a683f6ac8f67a2aa12754c196dc96c9e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVNAryExpr::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * S)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast:</p>

<p>Definition at line 237 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scev/#ad4f956914bf94bdcd1058badb5bd90e6">llvm::SCEV::getSCEVType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea3a80b1a7dda48464be1849ee1fb85868">llvm::scAddExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#ace7f137cfb19ce8073b78b85f819430c">llvm::SCEV::SCEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eafd56f054da3d1f9b827ae1003da3a38b">llvm::scMulExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea376414ac1f3ac8cb449fd5167a2db091">llvm::scSequentialUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea684b8e2484b12d494e82f7053d005754">llvm::scSMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea88dad4534f471d79d0a7a094d809ef55">llvm::scSMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3d0abdf8125de904320df332dbefedb">llvm::scUMaxExpr</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea0bf2fc9a454ce237fde0906ee24b0acc">llvm::scUMinExpr</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolutionexpressions-h">ScalarEvolutionExpressions.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
