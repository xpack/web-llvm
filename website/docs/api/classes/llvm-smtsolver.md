---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/smtsolver
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `SMTSolver` Class

<p>Generic base class for SMT Solvers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SMTSolver { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">llvm/Support/SMTAPI.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd922046254e1e3b6376b4d6569f67d">SMTSolver</a> ()=default</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1dbc1dc18c003ed3e7b8e05493c22600">~SMTSolver</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc408995a4e7c9983df57a596c03fdd5">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8d27727929f7ad1ac8fd9849ec16336">getFloatSort</a> (unsigned BitWidth)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae847c2df8a1d0d6e3b10278eae64c9e7">getBoolSort</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3274e40362c55a7c1b7211f7ebccdc40">getBitvectorSort</a> (const unsigned BitWidth)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a699ee4e075d41a9fda75dcaea4d5740b">getFloat16Sort</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c2c99b8ddfeced0b541dca4ed98c207">getFloat32Sort</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3b48fdfc6153f04d7682a060600225b">getFloat64Sort</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37952bdcb1bc0abe2aec1317c14eb7f4">getFloat128Sort</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4312b780ed8f544abc945f3dfa5a42c6">getSort</a> (const SMTExprRef &amp;AST)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebeff105e9f6530e8b2db06087f2e223">addConstraint</a> (const SMTExprRef &amp;Exp) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a constraint, adds it to the solver. <a href="#aebeff105e9f6530e8b2db06087f2e223">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a274abee4ab41f9fd397e75df49dd8c">mkBVAdd</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector addition operation. <a href="#a6a274abee4ab41f9fd397e75df49dd8c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5dc9731e4832b5efd34e6182b0582a2e">mkBVSub</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector subtraction operation. <a href="#a5dc9731e4832b5efd34e6182b0582a2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299a95ad2c868e573fdffdc2ab78fa37">mkBVMul</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector multiplication operation. <a href="#a299a95ad2c868e573fdffdc2ab78fa37">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad27738ee469bd95b07021050584f836d">mkBVSRem</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector signed modulus operation. <a href="#ad27738ee469bd95b07021050584f836d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e37504ba8e7269b6b8fdcb03a5dfaef">mkBVURem</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector unsigned modulus operation. <a href="#a8e37504ba8e7269b6b8fdcb03a5dfaef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3b66b421b8cd23cfebdbac8b1ef24d5">mkBVSDiv</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector signed division operation. <a href="#ab3b66b421b8cd23cfebdbac8b1ef24d5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade84497b1d3731d1d51482dbb4b7e53f">mkBVUDiv</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector unsigned division operation. <a href="#ade84497b1d3731d1d51482dbb4b7e53f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea16c34579ca9b9355ac30dd7269eef">mkBVShl</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector logical shift left operation. <a href="#aaea16c34579ca9b9355ac30dd7269eef">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99d6ce777124e365c744251123a3794b">mkBVAshr</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector arithmetic shift right operation. <a href="#a99d6ce777124e365c744251123a3794b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a375fb97dc6104355e563ae17805fd74b">mkBVLshr</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector logical shift right operation. <a href="#a375fb97dc6104355e563ae17805fd74b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ec6828cdb1efcbe860afaca6c4a5aa4">mkBVNeg</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector negation operation. <a href="#a0ec6828cdb1efcbe860afaca6c4a5aa4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb850233fbf723aaf7d4a9caaf90250b">mkBVNot</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector not operation. <a href="#afb850233fbf723aaf7d4a9caaf90250b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83dd0ec330d1282c8184843ed71496e0">mkBVXor</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector xor operation. <a href="#a83dd0ec330d1282c8184843ed71496e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01e062ae5d23417182328926e18dc93e">mkBVOr</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector or operation. <a href="#a01e062ae5d23417182328926e18dc93e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70829abd3b0996e3c985a18487878fd3">mkBVAnd</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector and operation. <a href="#a70829abd3b0996e3c985a18487878fd3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50e3bc8231a3edf5598464ba3e9790a4">mkBVUlt</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector unsigned less-than operation. <a href="#a50e3bc8231a3edf5598464ba3e9790a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b96339136289819cf9062f27a8ecd8d">mkBVSlt</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector signed less-than operation. <a href="#a6b96339136289819cf9062f27a8ecd8d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60fe2ced7d4845edbdabe059f7c9109a">mkBVUgt</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector unsigned greater-than operation. <a href="#a60fe2ced7d4845edbdabe059f7c9109a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1adee2b849f197c23850e8e726f556be">mkBVSgt</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector signed greater-than operation. <a href="#a1adee2b849f197c23850e8e726f556be">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a095b9872aa79227b1b670532b3f6f2bf">mkBVUle</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector unsigned less-equal-than operation. <a href="#a095b9872aa79227b1b670532b3f6f2bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebe470f75e535dcd23c84d123967abf5">mkBVSle</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector signed less-equal-than operation. <a href="#aebe470f75e535dcd23c84d123967abf5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0151afa6b3450b0d7044ced4a696e3f6">mkBVUge</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector unsigned greater-equal-than operation. <a href="#a0151afa6b3450b0d7044ced4a696e3f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af70fe3af901fdc5a802604505cafeb91">mkBVSge</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector signed greater-equal-than operation. <a href="#af70fe3af901fdc5a802604505cafeb91">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7ea690e8295c6ec32bf1ea1b0f22475">mkNot</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a boolean not operation. <a href="#ab7ea690e8295c6ec32bf1ea1b0f22475">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe1d961c88df427a150a6ece903984e">mkEqual</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a boolean equality operation. <a href="#abbe1d961c88df427a150a6ece903984e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a844c94fa7f7ee1aa660dba418bc80783">mkAnd</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a boolean and operation. <a href="#a844c94fa7f7ee1aa660dba418bc80783">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9643413b00d8fc50919c2376414a04da">mkOr</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a boolean or operation. <a href="#a9643413b00d8fc50919c2376414a04da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a039f768a554dc3187f5cc4524a1d7d78">mkIte</a> (const SMTExprRef &amp;Cond, const SMTExprRef &amp;T, const SMTExprRef &amp;F)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a boolean ite operation. <a href="#a039f768a554dc3187f5cc4524a1d7d78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9949ec2159bfc54c92ed54bc08f9be25">mkBVSignExt</a> (unsigned i, const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector sign extension operation. <a href="#a9949ec2159bfc54c92ed54bc08f9be25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e97a24d39acca9bc1f27934f3544f26">mkBVZeroExt</a> (unsigned i, const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector zero extension operation. <a href="#a6e97a24d39acca9bc1f27934f3544f26">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7947a4467facfb9c7e8c66a4fe37656d">mkBVExtract</a> (unsigned High, unsigned Low, const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector extract operation. <a href="#a7947a4467facfb9c7e8c66a4fe37656d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd171556d5eb90095617d9309019ba4a">mkBVConcat</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a bitvector concat operation. <a href="#acd171556d5eb90095617d9309019ba4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8352b166b14a2e9bf776190e382b4733">mkBVAddNoOverflow</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS, bool isSigned)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for overflow in a bitvector addition operation. <a href="#a8352b166b14a2e9bf776190e382b4733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2119ecb8fc724f5e0df4012489882c65">mkBVAddNoUnderflow</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for underflow in a signed bitvector addition operation. <a href="#a2119ecb8fc724f5e0df4012489882c65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7feef17745ce4ece1307cd1ae2274281">mkBVSubNoOverflow</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for overflow in a signed bitvector subtraction operation. <a href="#a7feef17745ce4ece1307cd1ae2274281">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8993cb879dad9c5a28147852e9d681c3">mkBVSubNoUnderflow</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS, bool isSigned)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for underflow in a bitvector subtraction operation. <a href="#a8993cb879dad9c5a28147852e9d681c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af066b09bd26a987ce289aa3f8c72cd62">mkBVSDivNoOverflow</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for overflow in a signed bitvector division/modulus operation. <a href="#af066b09bd26a987ce289aa3f8c72cd62">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a146e0bb6e08947f15a98343aa9e0864f">mkBVNegNoOverflow</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for overflow in a bitvector negation operation. <a href="#a146e0bb6e08947f15a98343aa9e0864f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b2ee1269a00056acaf6364551298332">mkBVMulNoOverflow</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS, bool isSigned)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for overflow in a bitvector multiplication operation. <a href="#a6b2ee1269a00056acaf6364551298332">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3725cddde4b8a20fa712227537f3030">mkBVMulNoUnderflow</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a predicate that checks for underflow in a signed bitvector multiplication operation. <a href="#ad3725cddde4b8a20fa712227537f3030">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18519dbd3b921f0bb409dd0fca62d6a7">mkFPNeg</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point negation operation. <a href="#a18519dbd3b921f0bb409dd0fca62d6a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574c1720b54bcacd9abcce5a089b7a65">mkFPIsInfinite</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point isInfinite operation. <a href="#a574c1720b54bcacd9abcce5a089b7a65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73b3eed1937402b75ccb11f2bebc0136">mkFPIsNaN</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point isNaN operation. <a href="#a73b3eed1937402b75ccb11f2bebc0136">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a451d31550cb0371dd51ad1d90b1ecdde">mkFPIsNormal</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point isNormal operation. <a href="#a451d31550cb0371dd51ad1d90b1ecdde">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabaa97540719496024ccba3352487825">mkFPIsZero</a> (const SMTExprRef &amp;Exp)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point isZero operation. <a href="#aabaa97540719496024ccba3352487825">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c6d2da60ebe9a774f812d0aa5d10b03">mkFPMul</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point multiplication operation. <a href="#a4c6d2da60ebe9a774f812d0aa5d10b03">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b21ca751bdeba042ad80a127a228e4c">mkFPDiv</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point division operation. <a href="#a5b21ca751bdeba042ad80a127a228e4c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c6e84b2084e72c78f8e6063c302177c">mkFPRem</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point remainder operation. <a href="#a7c6e84b2084e72c78f8e6063c302177c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae93cf5d3c013ee2801972fcf50312fe4">mkFPAdd</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point addition operation. <a href="#ae93cf5d3c013ee2801972fcf50312fe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8711a1fef8b2ca33f0a649cea0b0fdc4">mkFPSub</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point subtraction operation. <a href="#a8711a1fef8b2ca33f0a649cea0b0fdc4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6409f42bb8db83355922919acadacbe4">mkFPLt</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point less-than operation. <a href="#a6409f42bb8db83355922919acadacbe4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54b6647dd1dfbc53b3246d115381842a">mkFPGt</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point greater-than operation. <a href="#a54b6647dd1dfbc53b3246d115381842a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f64b6f260dab979104c91a483656db7">mkFPLe</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point less-than-or-equal operation. <a href="#a0f64b6f260dab979104c91a483656db7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256fb0351b298ebd2f9c9f4be85cb13c">mkFPGe</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point greater-than-or-equal operation. <a href="#a256fb0351b298ebd2f9c9f4be85cb13c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea81e0730c5bc8f9ce690d4dc88b1096">mkFPEqual</a> (const SMTExprRef &amp;LHS, const SMTExprRef &amp;RHS)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point equality operation. <a href="#aea81e0730c5bc8f9ce690d4dc88b1096">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99c396bd8e0caa03680e317334ed29ae">mkFPtoFP</a> (const SMTExprRef &amp;From, const SMTSortRef &amp;To)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point conversion from floatint-point to floating-point operation. <a href="#a99c396bd8e0caa03680e317334ed29ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9445309036b793e77651d65ba7e5a733">mkSBVtoFP</a> (const SMTExprRef &amp;From, const SMTSortRef &amp;To)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point conversion from signed bitvector to floatint-point operation. <a href="#a9445309036b793e77651d65ba7e5a733">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70bfed35a0796bb14b7d0e919324e54c">mkUBVtoFP</a> (const SMTExprRef &amp;From, const SMTSortRef &amp;To)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point conversion from unsigned bitvector to floatint-point operation. <a href="#a70bfed35a0796bb14b7d0e919324e54c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb55cd6cc01187f373b72bf51883c9c3">mkFPtoSBV</a> (const SMTExprRef &amp;From, unsigned ToWidth)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point conversion from floatint-point to signed bitvector operation. <a href="#aeb55cd6cc01187f373b72bf51883c9c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1f6fd66844eb6a7a73aa3ace6363afb">mkFPtoUBV</a> (const SMTExprRef &amp;From, unsigned ToWidth)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a floating-point conversion from floatint-point to unsigned bitvector operation. <a href="#ad1f6fd66844eb6a7a73aa3ace6363afb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8bc30ec5e4a4e6b0fb7b3991a21e40db">mkSymbol</a> (const char *Name, SMTSortRef Sort)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a new symbol, given a name and a sort. <a href="#a8bc30ec5e4a4e6b0fb7b3991a21e40db">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd6de8ee051d9f4f03c3d1a764aeae2">getFloatRoundingMode</a> ()=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apsint">llvm::APSInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bb7c9c9c9a48d01afe57088f8766b8f">getBitvector</a> (const SMTExprRef &amp;Exp, unsigned BitWidth, bool isUnsigned)=0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab84ff8beb25d4f20c931a976b1ffb12e">getBoolean</a> (const SMTExprRef &amp;Exp)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c05fdaf40072df7cd61746a550209ba">mkBoolean</a> (const bool b)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> from a boolean. <a href="#a6c05fdaf40072df7cd61746a550209ba">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af65b0acc48fdaae8ca409dbcf76fd8e1">mkFloat</a> (const llvm::APFloat Float)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> from a finite <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>. <a href="#af65b0acc48fdaae8ca409dbcf76fd8e1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae27f094cbd3823209737dfaaa350d5a1">mkBitvector</a> (const llvm::APSInt Int, unsigned BitWidth)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Constructs an <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> from an <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> and its bit width. <a href="#ae27f094cbd3823209737dfaaa350d5a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2f0fbec7f4fffab6891fb2d282561a2">getInterpretation</a> (const SMTExprRef &amp;Exp, llvm::APSInt &amp;Int)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an expression, extract the value of this operand in the model. <a href="#ab2f0fbec7f4fffab6891fb2d282561a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a031828bebbbe256f82fdcbeb8c4ea1c7">getInterpretation</a> (const SMTExprRef &amp;Exp, llvm::APFloat &amp;Float)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given an expression extract the value of this operand in the model. <a href="#a031828bebbbe256f82fdcbeb8c4ea1c7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada5582a198ed0a722ae5bb626efef082">check</a> () const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the constraints are satisfiable. <a href="#ada5582a198ed0a722ae5bb626efef082">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d5c5daeb5e52142db2480d17bde0570">push</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Push the current solver state. <a href="#a2d5c5daeb5e52142db2480d17bde0570">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e9c4eeaa9edcc67332db6d00de8213c">pop</a> (unsigned NumStates=1)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Pop the previous solver state. <a href="#a6e9c4eeaa9edcc67332db6d00de8213c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa43a2c0db9871cb25506220115708b5b">reset</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the solver and remove all constraints. <a href="#aa43a2c0db9871cb25506220115708b5b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fe5133a0d7f726ef12f2c9e54b38f49">isFPSupported</a> ()=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if the solver supports floating-points. <a href="#a1fe5133a0d7f726ef12f2c9e54b38f49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c8d450e2a369207b9c83dd8f0ea3b2">print</a> (raw_ostream &amp;OS) const =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad61cef36c03ebf972783820871b2e8f5">setBoolParam</a> (StringRef Key, bool Value)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the requested option. <a href="#ad61cef36c03ebf972783820871b2e8f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67388502bd7ae4af21c266c66dd57ba8">setUnsignedParam</a> (StringRef Key, unsigned Value)=0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/smtsolverstatistics">SMTSolverStatistics</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad59142237784e949783f3d91c89448b9">getStatistics</a> () const =0</td>
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

<p>Generic base class for SMT Solvers.</p>


<p>This class is responsible for wrapping all sorts and expression generation, through the mk* methods. It also provides methods to create SMT expressions straight from clang's AST, through the from* methods.</p>


<p>Definition at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SMTSolver() {#aacd922046254e1e3b6376b4d6569f67d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SMTSolver::SMTSolver ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~SMTSolver() {#a1dbc1dc18c003ed3e7b8e05493c22600}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::SMTSolver::~SMTSolver ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addConstraint() {#aebeff105e9f6530e8b2db06087f2e223}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SMTSolver::addConstraint (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given a constraint, adds it to the solver.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### check() {#ada5582a198ed0a722ae5bb626efef082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::optional&lt; bool &gt; llvm::SMTSolver::check ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the constraints are satisfiable.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### dump() {#acc408995a4e7c9983df57a596c03fdd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SMTSolver::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>, definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/support/z3solver-cpp">Z3Solver.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#ab0c8d450e2a369207b9c83dd8f0ea3b2">print</a>.</p>

</div>
</div>

### getBitvector() {#a9bb7c9c9c9a48d01afe57088f8766b8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual llvm::APSInt llvm::SMTSolver::getBitvector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp, unsigned BitWidth, bool isUnsigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>

</div>
</div>

### getBitvectorSort() {#a3274e40362c55a7c1b7211f7ebccdc40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTSortRef llvm::SMTSolver::getBitvectorSort (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>.</p>

</div>
</div>

### getBoolean() {#ab84ff8beb25d4f20c931a976b1ffb12e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::SMTSolver::getBoolean (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 416 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### getBoolSort() {#ae847c2df8a1d0d6e3b10278eae64c9e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTSortRef llvm::SMTSolver::getBoolSort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 173 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### getFloat128Sort() {#a37952bdcb1bc0abe2aec1317c14eb7f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTSortRef llvm::SMTSolver::getFloat128Sort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Referenced by <a href="#ae8d27727929f7ad1ac8fd9849ec16336">getFloatSort</a>.</p>

</div>
</div>

### getFloat16Sort() {#a699ee4e075d41a9fda75dcaea4d5740b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTSortRef llvm::SMTSolver::getFloat16Sort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Referenced by <a href="#ae8d27727929f7ad1ac8fd9849ec16336">getFloatSort</a>.</p>

</div>
</div>

### getFloat32Sort() {#a5c2c99b8ddfeced0b541dca4ed98c207}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTSortRef llvm::SMTSolver::getFloat32Sort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Referenced by <a href="#ae8d27727929f7ad1ac8fd9849ec16336">getFloatSort</a>.</p>

</div>
</div>

### getFloat64Sort() {#ad3b48fdfc6153f04d7682a060600225b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTSortRef llvm::SMTSolver::getFloat64Sort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Referenced by <a href="#ae8d27727929f7ad1ac8fd9849ec16336">getFloatSort</a>.</p>

</div>
</div>

### getFloatRoundingMode() {#aefd6de8ee051d9f4f03c3d1a764aeae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::getFloatRoundingMode ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 409 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### getFloatSort() {#ae8d27727929f7ad1ac8fd9849ec16336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SMTSortRef llvm::SMTSolver::getFloatSort (unsigned BitWidth)</td>
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



<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a37952bdcb1bc0abe2aec1317c14eb7f4">getFloat128Sort</a>, <a href="#a699ee4e075d41a9fda75dcaea4d5740b">getFloat16Sort</a>, <a href="#a5c2c99b8ddfeced0b541dca4ed98c207">getFloat32Sort</a>, <a href="#ad3b48fdfc6153f04d7682a060600225b">getFloat64Sort</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getInterpretation() {#ab2f0fbec7f4fffab6891fb2d282561a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::SMTSolver::getInterpretation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp, <a href="/web-llvm/docs/api/classes/llvm/apsint">llvm::APSInt</a> &amp; Int)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an expression, extract the value of this operand in the model.</p>

<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>.</p>

</div>
</div>

### getInterpretation() {#a031828bebbbe256f82fdcbeb8c4ea1c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::SMTSolver::getInterpretation (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp, <a href="/web-llvm/docs/api/classes/llvm/apfloat">llvm::APFloat</a> &amp; Float)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Given an expression extract the value of this operand in the model.</p>

<p>Definition at line 431 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>.</p>

</div>
</div>

### getSort() {#a4312b780ed8f544abc945f3dfa5a42c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTSortRef llvm::SMTSolver::getSort (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; AST)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 191 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### getStatistics() {#ad59142237784e949783f3d91c89448b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual std::unique_ptr&lt; SMTSolverStatistics &gt; llvm::SMTSolver::getStatistics ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 455 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### isFPSupported() {#a1fe5133a0d7f726ef12f2c9e54b38f49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::SMTSolver::isFPSupported ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Checks if the solver supports floating-points.</p>

<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkAnd() {#a844c94fa7f7ee1aa660dba418bc80783}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a boolean and operation.</p>

<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBitvector() {#ae27f094cbd3823209737dfaaa350d5a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBitvector (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apsint">llvm::APSInt</a> Int, unsigned BitWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs an <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> from an <a href="/web-llvm/docs/api/classes/llvm/apsint">APSInt</a> and its bit width.</p>

<p>Definition at line 425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a637b69dea56f804278aa50e975337e01">Int</a>.</p>

</div>
</div>

### mkBoolean() {#a6c05fdaf40072df7cd61746a550209ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBoolean (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> bool b)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs an <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> from a boolean.</p>

<p>Definition at line 419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkBVAdd() {#a6a274abee4ab41f9fd397e75df49dd8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector addition operation.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVAddNoOverflow() {#a8352b166b14a2e9bf776190e382b4733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVAddNoOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS, bool isSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for overflow in a bitvector addition operation.</p>

<p>Definition at line 297 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVAddNoUnderflow() {#a2119ecb8fc724f5e0df4012489882c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVAddNoUnderflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for underflow in a signed bitvector addition operation.</p>

<p>Definition at line 303 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVAnd() {#a70829abd3b0996e3c985a18487878fd3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVAnd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector and operation.</p>

<p>Definition at line 239 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVAshr() {#a99d6ce777124e365c744251123a3794b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVAshr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector arithmetic shift right operation.</p>

<p>Definition at line 221 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVConcat() {#acd171556d5eb90095617d9309019ba4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVConcat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector concat operation.</p>

<p>Definition at line 292 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVExtract() {#a7947a4467facfb9c7e8c66a4fe37656d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVExtract (unsigned High, unsigned Low, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector extract operation.</p>

<p>Definition at line 288 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#a7df34dbf636f2fbbb00f2b86eccdb1eb">High</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05609d049bfe3c5c2f64711566131a86a28d0edd045e05cf5af64e35ae0c4c6ef">llvm::Low</a>.</p>

</div>
</div>

### mkBVLshr() {#a375fb97dc6104355e563ae17805fd74b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVLshr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector logical shift right operation.</p>

<p>Definition at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVMul() {#a299a95ad2c868e573fdffdc2ab78fa37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector multiplication operation.</p>

<p>Definition at line 203 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVMulNoOverflow() {#a6b2ee1269a00056acaf6364551298332}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVMulNoOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS, bool isSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for overflow in a bitvector multiplication operation.</p>

<p>Definition at line 328 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVMulNoUnderflow() {#ad3725cddde4b8a20fa712227537f3030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVMulNoUnderflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for underflow in a signed bitvector multiplication operation.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVNeg() {#a0ec6828cdb1efcbe860afaca6c4a5aa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVNeg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector negation operation.</p>

<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkBVNegNoOverflow() {#a146e0bb6e08947f15a98343aa9e0864f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVNegNoOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for overflow in a bitvector negation operation.</p>

<p>Definition at line 324 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkBVNot() {#afb850233fbf723aaf7d4a9caaf90250b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVNot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector not operation.</p>

<p>Definition at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkBVOr() {#a01e062ae5d23417182328926e18dc93e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector or operation.</p>

<p>Definition at line 236 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSDiv() {#ab3b66b421b8cd23cfebdbac8b1ef24d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector signed division operation.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSDivNoOverflow() {#af066b09bd26a987ce289aa3f8c72cd62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSDivNoOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for overflow in a signed bitvector division/modulus operation.</p>

<p>Definition at line 319 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSge() {#af70fe3af901fdc5a802604505cafeb91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector signed greater-equal-than operation.</p>

<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSgt() {#a1adee2b849f197c23850e8e726f556be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSgt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector signed greater-than operation.</p>

<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVShl() {#aaea16c34579ca9b9355ac30dd7269eef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVShl (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector logical shift left operation.</p>

<p>Definition at line 218 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSignExt() {#a9949ec2159bfc54c92ed54bc08f9be25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSignExt (unsigned i, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector sign extension operation.</p>

<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkBVSle() {#aebe470f75e535dcd23c84d123967abf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector signed less-equal-than operation.</p>

<p>Definition at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSlt() {#a6b96339136289819cf9062f27a8ecd8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSlt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector signed less-than operation.</p>

<p>Definition at line 245 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSRem() {#ad27738ee469bd95b07021050584f836d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSRem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector signed modulus operation.</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSub() {#a5dc9731e4832b5efd34e6182b0582a2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector subtraction operation.</p>

<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSubNoOverflow() {#a7feef17745ce4ece1307cd1ae2274281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSubNoOverflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for overflow in a signed bitvector subtraction operation.</p>

<p>Definition at line 308 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVSubNoUnderflow() {#a8993cb879dad9c5a28147852e9d681c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVSubNoUnderflow (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS, bool isSigned)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a predicate that checks for underflow in a bitvector subtraction operation.</p>

<p>Definition at line 313 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a49b2092a066cfbc24bc6925bdea9682a">isSigned</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVUDiv() {#ade84497b1d3731d1d51482dbb4b7e53f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVUDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector unsigned division operation.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVUge() {#a0151afa6b3450b0d7044ced4a696e3f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVUge (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector unsigned greater-equal-than operation.</p>

<p>Definition at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVUgt() {#a60fe2ced7d4845edbdabe059f7c9109a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVUgt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector unsigned greater-than operation.</p>

<p>Definition at line 248 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVUle() {#a095b9872aa79227b1b670532b3f6f2bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVUle (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector unsigned less-equal-than operation.</p>

<p>Definition at line 254 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVUlt() {#a50e3bc8231a3edf5598464ba3e9790a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVUlt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector unsigned less-than operation.</p>

<p>Definition at line 242 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVURem() {#a8e37504ba8e7269b6b8fdcb03a5dfaef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVURem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector unsigned modulus operation.</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVXor() {#a83dd0ec330d1282c8184843ed71496e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVXor (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector xor operation.</p>

<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkBVZeroExt() {#a6e97a24d39acca9bc1f27934f3544f26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkBVZeroExt (unsigned i, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a bitvector zero extension operation.</p>

<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkEqual() {#abbe1d961c88df427a150a6ece903984e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a boolean equality operation.</p>

<p>Definition at line 269 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFloat() {#af65b0acc48fdaae8ca409dbcf76fd8e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/apfloat">llvm::APFloat</a> Float)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Constructs an <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> from a finite <a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a>.</p>

<p>Definition at line 422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitnonsemanticdi-cpp/#ac168ee0c965117536e841dd35a716d36ad67b0ee7230dcecb610254e4e5e589cd">Float</a>.</p>

</div>
</div>

### mkFPAdd() {#ae93cf5d3c013ee2801972fcf50312fe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPAdd (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point addition operation.</p>

<p>Definition at line 362 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPDiv() {#a5b21ca751bdeba042ad80a127a228e4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPDiv (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point division operation.</p>

<p>Definition at line 356 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPEqual() {#aea81e0730c5bc8f9ce690d4dc88b1096}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPEqual (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point equality operation.</p>

<p>Definition at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPGe() {#a256fb0351b298ebd2f9c9f4be85cb13c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPGe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point greater-than-or-equal operation.</p>

<p>Definition at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPGt() {#a54b6647dd1dfbc53b3246d115381842a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPGt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point greater-than operation.</p>

<p>Definition at line 371 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPIsInfinite() {#a574c1720b54bcacd9abcce5a089b7a65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPIsInfinite (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point isInfinite operation.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkFPIsNaN() {#a73b3eed1937402b75ccb11f2bebc0136}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPIsNaN (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point isNaN operation.</p>

<p>Definition at line 344 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkFPIsNormal() {#a451d31550cb0371dd51ad1d90b1ecdde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPIsNormal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point isNormal operation.</p>

<p>Definition at line 347 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkFPIsZero() {#aabaa97540719496024ccba3352487825}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPIsZero (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point isZero operation.</p>

<p>Definition at line 350 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkFPLe() {#a0f64b6f260dab979104c91a483656db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPLe (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point less-than-or-equal operation.</p>

<p>Definition at line 374 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPLt() {#a6409f42bb8db83355922919acadacbe4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPLt (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point less-than operation.</p>

<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPMul() {#a4c6d2da60ebe9a774f812d0aa5d10b03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPMul (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point multiplication operation.</p>

<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPNeg() {#a18519dbd3b921f0bb409dd0fca62d6a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPNeg (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point negation operation.</p>

<p>Definition at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkFPRem() {#a7c6e84b2084e72c78f8e6063c302177c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPRem (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point remainder operation.</p>

<p>Definition at line 359 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPSub() {#a8711a1fef8b2ca33f0a649cea0b0fdc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPSub (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point subtraction operation.</p>

<p>Definition at line 365 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkFPtoFP() {#a99c396bd8e0caa03680e317334ed29ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPtoFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a> &amp; To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point conversion from floatint-point to floating-point operation.</p>

<p>Definition at line 385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkFPtoSBV() {#aeb55cd6cc01187f373b72bf51883c9c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPtoSBV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; From, unsigned ToWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point conversion from floatint-point to signed bitvector operation.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkFPtoUBV() {#ad1f6fd66844eb6a7a73aa3ace6363afb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkFPtoUBV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; From, unsigned ToWidth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point conversion from floatint-point to unsigned bitvector operation.</p>

<p>Definition at line 403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkIte() {#a039f768a554dc3187f5cc4524a1d7d78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkIte (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Cond, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; T, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a boolean ite operation.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### mkNot() {#ab7ea690e8295c6ec32bf1ea1b0f22475}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkNot (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; Exp)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a boolean not operation.</p>

<p>Definition at line 266 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkOr() {#a9643413b00d8fc50919c2376414a04da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkOr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; LHS, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; RHS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a boolean or operation.</p>

<p>Definition at line 275 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a9e1483f7215664a2315c53c3558d9a8d">LHS</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86partialreduction-cpp/#a87b8bfbbe9d8f7146d7f20a5fb42efd0">RHS</a>.</p>

</div>
</div>

### mkSBVtoFP() {#a9445309036b793e77651d65ba7e5a733}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkSBVtoFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a> &amp; To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point conversion from signed bitvector to floatint-point operation.</p>

<p>Definition at line 389 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkSymbol() {#a8bc30ec5e4a4e6b0fb7b3991a21e40db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkSymbol (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name, <a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a> Sort)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a new symbol, given a name and a sort.</p>

<p>Definition at line 406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### mkUBVtoFP() {#a70bfed35a0796bb14b7d0e919324e54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual SMTExprRef llvm::SMTSolver::mkUBVtoFP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#a330d764fcf3616a6d4a3d3f0f8009535">SMTExprRef</a> &amp; From, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#af52a443f5d77e19691f729f2c0283225">SMTSortRef</a> &amp; To)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a floating-point conversion from unsigned bitvector to floatint-point operation.</p>

<p>Definition at line 394 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### pop() {#a6e9c4eeaa9edcc67332db6d00de8213c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SMTSolver::pop (unsigned NumStates=1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Pop the previous solver state.</p>

<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### print() {#ab0c8d450e2a369207b9c83dd8f0ea3b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SMTSolver::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Referenced by <a href="#acc408995a4e7c9983df57a596c03fdd5">dump</a>.</p>

</div>
</div>

### push() {#a2d5c5daeb5e52142db2480d17bde0570}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SMTSolver::push ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Push the current solver state.</p>

<p>Definition at line 438 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### reset() {#aa43a2c0db9871cb25506220115708b5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SMTSolver::reset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the solver and remove all constraints.</p>

<p>Definition at line 444 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>

</div>
</div>

### setBoolParam() {#ad61cef36c03ebf972783820871b2e8f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SMTSolver::setBoolParam (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, bool Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the requested option.</p>

<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

### setUnsignedParam() {#a67388502bd7ae4af21c266c66dd57ba8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::SMTSolver::setUnsignedParam (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, unsigned Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a98c6256d0644613c6b5b3e2ef06ef5ce">llvm::InnerAnalysisManagerProxy&lt; AnalysisManagerT, IRUnitT, ExtraArgTs... &gt;::Key</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/smtapi-h">SMTAPI.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/support/z3solver-cpp">Z3Solver.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
