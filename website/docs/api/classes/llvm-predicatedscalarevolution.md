---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/predicatedscalarevolution
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PredicatedScalarEvolution` Class Reference

<p>An interface layer with <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> used to manage how we see <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions for values in the context of existing predicates. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PredicatedScalarEvolution { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5de77ee377aee71f0a0a3d6650462e6">RewriteEntry</a> = std::pair&lt; unsigned, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Holds a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and the version number of the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate used to perform the rewrite of the expression. <a href="#ad5de77ee377aee71f0a0a3d6650462e6">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2b11e914798a4e54c7e640722f1b08d">PredicatedScalarEvolution</a> (ScalarEvolution &amp;SE, Loop &amp;L)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad1b5b2fb366e23d7693b5953feff806">PredicatedScalarEvolution</a> (const PredicatedScalarEvolution &amp;)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>We need to explicitly define the copy constructor because of FlagsMap. <a href="#aad1b5b2fb366e23d7693b5953feff806">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12a8ac8838fb851a2de5dc5275307bb6">getPredicate</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0994d8207b94ad22ecebc1a6bc580f1">getSCEV</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression of V, in the context of the current <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate. <a href="#ae0994d8207b94ad22ecebc1a6bc580f1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada1db826f3d2266fe2c4d06218d8d342">getBackedgeTakenCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the (predicated) backedge count for the analyzed loop. <a href="#ada1db826f3d2266fe2c4d06218d8d342">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbabf05e94f95f775d59497b6b1004d8">getSymbolicMaxBackedgeTakenCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the (predicated) symbolic max backedge count for the analyzed loop. <a href="#adbabf05e94f95f775d59497b6b1004d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacf376f9963d73732052a7362c5afabd">getSmallConstantMaxTripCount</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the upper bound of the loop trip count as a normal unsigned value, or 0 if the trip count is unknown. <a href="#aacf376f9963d73732052a7362c5afabd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b369e991301543c2120405809119d36">addPredicate</a> (const SCEVPredicate &amp;Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Adds a new predicate. <a href="#a0b369e991301543c2120405809119d36">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa364810e8fe30937277d9dd8a301c4c9">getAsAddRec</a> (Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attempts to produce an AddRecExpr for V by adding additional <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates. <a href="#aa364810e8fe30937277d9dd8a301c4c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a757ce31dd838b17c024287ce9d17c4c2">setNoOverflow</a> (Value *V, SCEVWrapPredicate::IncrementWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Proves that V doesn't overflow by adding <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate. <a href="#a757ce31dd838b17c024287ce9d17c4c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fb96c9b4d017d69818db581dae5bd96">hasNoOverflow</a> (Value *V, SCEVWrapPredicate::IncrementWrapFlags Flags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if we've proved that V doesn't wrap by means of a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate. <a href="#a6fb96c9b4d017d69818db581dae5bd96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ca5eacc61b5669880de2f8b0cff33c">getSE</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> analysis used. <a href="#a10ca5eacc61b5669880de2f8b0cff33c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84e9b8947377b33bf66815f86269e6ce">print</a> (raw_ostream &amp;OS, unsigned Depth) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> mappings done by the Predicated Scalar Evolution. <a href="#a84e9b8947377b33bf66815f86269e6ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1aac224801967b8ca7361a4a71b36f7">areAddRecsEqualWithPreds</a> (const SCEVAddRecExpr *AR1, const SCEVAddRecExpr *AR2) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">AR1</span> and <span class="doxyComputerOutput">AR2</span> are equal, while taking into account Equal predicates in Preds. <a href="#aa1aac224801967b8ca7361a4a71b36f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae477116bd023e4bf6b22d455372f0a9b">updateGeneration</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Increments the version number of the predicate. <a href="#ae477116bd023e4bf6b22d455372f0a9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *, RewriteEntry &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7f54a2245a31bbd96e21aa2e3bb092">RewriteMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Maps a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> to the rewrite result of that <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> at a certain version number. <a href="#aca7f54a2245a31bbd96e21aa2e3bb092">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuemap">ValueMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a783e7f140e48e06deef562824f097b07">FlagsMap</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records what NoWrap flags we've added to a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *. <a href="#a783e7f140e48e06deef562824f097b07">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92fadf36e058280250e65768b82ab121">SE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> analysis. <a href="#a92fadf36e058280250e65768b82ab121">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21b40ced9a059f31ede87232a7f74619">L</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The analyzed <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>. <a href="#a21b40ced9a059f31ede87232a7f74619">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/scevunionpredicate">SCEVUnionPredicate</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac354a58a85eda10ecdfd209f70d5f232">Preds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> that forms our context. <a href="#ac354a58a85eda10ecdfd209f70d5f232">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c19ab07280d9152155dbf96e2a840f0">Generation</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Marks the version of the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate used. <a href="#a9c19ab07280d9152155dbf96e2a840f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac52a78f5fdeaa198c7522937070250fe">BackedgeCount</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The backedge taken count. <a href="#ac52a78f5fdeaa198c7522937070250fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a1f3b0b6c06e85cf0cca3805c9d6a2">SymbolicMaxBackedgeCount</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The symbolic backedge taken count. <a href="#a17a1f3b0b6c06e85cf0cca3805c9d6a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74b7bbc644ab57d4162eb1fa1042df3">SmallConstantMaxTripCount</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The constant max trip count for the loop. <a href="#af74b7bbc644ab57d4162eb1fa1042df3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>An interface layer with <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> used to manage how we see <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions for values in the context of existing predicates.</p>


<p>We can add new predicates, but we cannot remove them.</p>


<p>This layer has multiple purposes:</p>


<ul class="doxyList ">
<li>provides a simple interface for <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> versioning.</li>
<li>guarantees that the order of transformations applied on a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression for a single <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> is consistent across two different getSCEV calls. This means that, for example, once we've obtained an AddRec expression for a certain value through expression rewriting, we will continue to get an AddRec expression for that <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</li>
<li>lowers the number of expression rewrites.</li>
</ul>

<p>Definition at line 2383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### RewriteEntry {#ad5de77ee377aee71f0a0a3d6650462e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::PredicatedScalarEvolution::RewriteEntry =  std::pair&lt;unsigned, const SCEV *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Holds a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> and the version number of the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate used to perform the rewrite of the expression.</p>

<p>Definition at line 2443 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PredicatedScalarEvolution() {#aa2b11e914798a4e54c7e640722f1b08d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution::PredicatedScalarEvolution (<a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE, <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a> &amp; L)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2385 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15099 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/codeview/typehashing-cpp/#a066f917f4a73ce07260b0e4262be92ba">DenseMapInfo&lt; LocallyHashedType &gt;::Empty</a>.</p>


<p>Referenced by <a href="#aad1b5b2fb366e23d7693b5953feff806">PredicatedScalarEvolution</a>.</p>

</div>
</div>

### PredicatedScalarEvolution() {#aad1b5b2fb366e23d7693b5953feff806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PredicatedScalarEvolution::PredicatedScalarEvolution (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution">PredicatedScalarEvolution</a> &amp; Init)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>We need to explicitly define the copy constructor because of FlagsMap.</p>

<p>Declaration at line 2425 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15237 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a> and <a href="#aa2b11e914798a4e54c7e640722f1b08d">PredicatedScalarEvolution</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addPredicate() {#a0b369e991301543c2120405809119d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PredicatedScalarEvolution::addPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> &amp; Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Adds a new predicate.</p>

<p>Declaration at line 2406 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15166 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#aa364810e8fe30937277d9dd8a301c4c9">getAsAddRec</a>, <a href="#ada1db826f3d2266fe2c4d06218d8d342">getBackedgeTakenCount</a>, <a href="#aacf376f9963d73732052a7362c5afabd">getSmallConstantMaxTripCount</a>, <a href="#adbabf05e94f95f775d59497b6b1004d8">getSymbolicMaxBackedgeTakenCount</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaec5d8efaa82dedb3a3b23f4482f31eb">llvm::replaceSymbolicStrideSCEV</a> and <a href="#a757ce31dd838b17c024287ce9d17c4c2">setNoOverflow</a>.</p>

</div>
</div>

### areAddRecsEqualWithPreds() {#aa1aac224801967b8ca7361a4a71b36f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PredicatedScalarEvolution::areAddRecsEqualWithPreds (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR1, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <span class="doxyComputerOutput">AR1</span> and <span class="doxyComputerOutput">AR2</span> are equal, while taking into account Equal predicates in Preds.</p>

<p>Declaration at line 2433 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 5703 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a19c13fe96d59c787e900b7bbf7173263">llvm::SCEVAddRecExpr::getStart</a> and <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a4049f7040a4628b15f182c3c9aaf802a">llvm::SCEVAddRecExpr::getStepRecurrence</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a1890db236ee0485fd31d3d99d6ad09b5">getCastsForInductionPHI</a>.</p>

</div>
</div>

### getAsAddRec() {#aa364810e8fe30937277d9dd8a301c4c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVAddRecExpr * PredicatedScalarEvolution::getAsAddRec (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attempts to produce an AddRecExpr for V by adding additional <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates.</p>


<p>If we can't transform the expression into an AddRecExpr we return nullptr and not add additional <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicates to the current context.</p>


<p>Declaration at line 2412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15222 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a0b369e991301543c2120405809119d36">addPredicate</a>, <a href="#ae0994d8207b94ad22ecebc1a6bc580f1">getSCEV</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a2d58e737d5b362a238d1b9cfbd961532">hasComputableBounds</a> and <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>.</p>

</div>
</div>

### getBackedgeTakenCount() {#ada1db826f3d2266fe2c4d06218d8d342}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * PredicatedScalarEvolution::getBackedgeTakenCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the (predicated) backedge count for the analyzed loop.</p>

<p>Declaration at line 2396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15135 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a0b369e991301543c2120405809119d36">addPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#adeb41c907ebde15846bc643325909f95">processLoopInVPlanNativePath</a>.</p>

</div>
</div>

### getPredicate() {#a12a8ac8838fb851a2de5dc5275307bb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVPredicate &amp; PredicatedScalarEvolution::getPredicate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 2387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15176 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/loopvectorizepass/#a160afa01e95095aa0c8115b6e0e6f4a6">llvm::LoopVectorizePass::processLoop</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-loopversioning-cpp-/#aed4891b5f4ab2e016fc238f42dfd939e">anonymous{LoopVersioning.cpp}::runImpl</a>.</p>

</div>
</div>

### getSCEV() {#ae0994d8207b94ad22ecebc1a6bc580f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * PredicatedScalarEvolution::getSCEV (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression of V, in the context of the current <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate.</p>


<p>The order of transformations applied on the expression of V returned by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> is guaranteed to be preserved, even when adding new predicates.</p>


<p>Declaration at line 2393 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15116 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ad27a81251d238dbfdc4d0253a64d6267">getAddressAccessSCEV</a>, <a href="#aa364810e8fe30937277d9dd8a301c4c9">getAsAddRec</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/ivdescriptors-cpp/#a1890db236ee0485fd31d3d99d6ad09b5">getCastsForInductionPHI</a>, <a href="#a6fb96c9b4d017d69818db581dae5bd96">hasNoOverflow</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af7b88a2a7449e4edc75721e2ab686d9e">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::isDependenceDistanceOfOne</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a7f4bd2b45f0af65f9dd7ac1b949b528e">isNoWrap</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a9d9847ba3ad2bc2837b041581277a8fb">isNoWrapAddRec</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaec5d8efaa82dedb3a3b23f4482f31eb">llvm::replaceSymbolicStrideSCEV</a> and <a href="#a757ce31dd838b17c024287ce9d17c4c2">setNoOverflow</a>.</p>

</div>
</div>

### getSE() {#a10ca5eacc61b5669880de2f8b0cff33c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution * llvm::PredicatedScalarEvolution::getSE ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> analysis used.</p>

<p>Definition at line 2422 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armtargettransforminfo-cpp/#a786a99e437c617417c56b4b4678138b9">canTailPredicateLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#afe024d2bcdcaa9644b7270f84edd74a5">findForkedPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#adf87a16be872504ce4d0ab9714dc6217">llvm::findHistogram</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#ad27a81251d238dbfdc4d0253a64d6267">getAddressAccessSCEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a2d58e737d5b362a238d1b9cfbd961532">hasComputableBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#abe6c75313479a0d0d8dd63b870faeeac">llvm::RuntimePointerChecking::insert</a>, <a href="/web-llvm/docs/api/structs/anonymous-looploadelimination-cpp-/storetoloadforwardingcandidate/#af7b88a2a7449e4edc75721e2ab686d9e">anonymous{LoopLoadElimination.cpp}::StoreToLoadForwardingCandidate::isDependenceDistanceOfOne</a>, <a href="/web-llvm/docs/api/classes/llvm/inductiondescriptor/#a5ed1bebb4f59394ccf2d92d0d73336bf">llvm::InductionDescriptor::isInductionPHI</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a7f4bd2b45f0af65f9dd7ac1b949b528e">isNoWrap</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aaec5d8efaa82dedb3a3b23f4482f31eb">llvm::replaceSymbolicStrideSCEV</a>.</p>

</div>
</div>

### getSmallConstantMaxTripCount() {#aacf376f9963d73732052a7362c5afabd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned PredicatedScalarEvolution::getSmallConstantMaxTripCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the upper bound of the loop trip count as a normal unsigned value, or 0 if the trip count is unknown.</p>

<p>Declaration at line 2403 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15156 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a0b369e991301543c2120405809119d36">addPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/loopvectorize-cpp/#a84375e6536d9214c7895013078055aff">getSmallBestKnownTC</a>.</p>

</div>
</div>

### getSymbolicMaxBackedgeTakenCount() {#adbabf05e94f95f775d59497b6b1004d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV * PredicatedScalarEvolution::getSymbolicMaxBackedgeTakenCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the (predicated) symbolic max backedge count for the analyzed loop.</p>

<p>Declaration at line 2399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15145 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a0b369e991301543c2120405809119d36">addPredicate</a> and <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/vplan/#a5a956378c8f267d4b2afc6e036a08d42">llvm::VPlan::createInitialVPlan</a> and <a href="/web-llvm/docs/api/classes/llvm/runtimepointerchecking/#abe6c75313479a0d0d8dd63b870faeeac">llvm::RuntimePointerChecking::insert</a>.</p>

</div>
</div>

### hasNoOverflow() {#a6fb96c9b4d017d69818db581dae5bd96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PredicatedScalarEvolution::hasNoOverflow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if we've proved that V doesn't wrap by means of a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate.</p>

<p>Declaration at line 2419 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15206 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a6075abe0816f373cb741561866f3eefa">llvm::SCEVWrapPredicate::clearFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a76a888bd97f7b7bb6b43eb4bdb9dc3bc">llvm::SCEVWrapPredicate::getImpliedFlags</a>, <a href="#ae0994d8207b94ad22ecebc1a6bc580f1">getSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a0cfd938ff9c572d287e5e7923624db70a11c850531be360193c9473b4fe240c1d">llvm::SCEVWrapPredicate::IncrementAnyWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a7f4bd2b45f0af65f9dd7ac1b949b528e">isNoWrap</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a9d9847ba3ad2bc2837b041581277a8fb">isNoWrapAddRec</a>.</p>

</div>
</div>

### print() {#a84e9b8947377b33bf66815f86269e6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PredicatedScalarEvolution::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned Depth)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> mappings done by the Predicated Scalar Evolution.</p>


<p>The printed text is indented by <span class="doxyComputerOutput">Depth</span>.</p>


<p>Declaration at line 2429 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15247 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>

</div>
</div>

### setNoOverflow() {#a757ce31dd838b17c024287ce9d17c4c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PredicatedScalarEvolution::setNoOverflow (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Proves that V doesn't overflow by adding <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate.</p>

<p>Declaration at line 2415 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15190 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a0b369e991301543c2120405809119d36">addPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a6075abe0816f373cb741561866f3eefa">llvm::SCEVWrapPredicate::clearFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a76a888bd97f7b7bb6b43eb4bdb9dc3bc">llvm::SCEVWrapPredicate::getImpliedFlags</a>, <a href="#ae0994d8207b94ad22ecebc1a6bc580f1">getSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvvmintrrange-cpp/#ac5804672fc0850438d63caec770647f8">II</a> and <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a3db937ba78ab75aa91d72c8678a28b78">llvm::SCEVWrapPredicate::setFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a8021a49018596bcbea563e6d5cac9a70">llvm::getPtrStride</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### updateGeneration() {#ae477116bd023e4bf6b22d455372f0a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PredicatedScalarEvolution::updateGeneration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Increments the version number of the predicate.</p>


<p>This needs to be called every time the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate changes.</p>


<p>Declaration at line 2439 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15180 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### BackedgeCount {#ac52a78f5fdeaa198c7522937070250fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* llvm::PredicatedScalarEvolution::BackedgeCount = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The backedge taken count.</p>

<p>Definition at line 2472 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### FlagsMap {#a783e7f140e48e06deef562824f097b07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueMap&lt;Value *, SCEVWrapPredicate::IncrementWrapFlags&gt; llvm::PredicatedScalarEvolution::FlagsMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records what NoWrap flags we've added to a <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *.</p>

<p>Definition at line 2453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### Generation {#a9c19ab07280d9152155dbf96e2a840f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PredicatedScalarEvolution::Generation = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Marks the version of the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> predicate used.</p>


<p>When rewriting a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression we mark it with the version of the predicate. We use this to figure out if the predicate has changed from the last rewrite of the <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>. If so, we need to perform a new rewrite.</p>


<p>Definition at line 2469 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### L {#a21b40ced9a059f31ede87232a7f74619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Loop&amp; llvm::PredicatedScalarEvolution::L</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The analyzed <a href="/web-llvm/docs/api/classes/llvm/loop">Loop</a>.</p>

<p>Definition at line 2459 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### Preds {#ac354a58a85eda10ecdfd209f70d5f232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;SCEVUnionPredicate&gt; llvm::PredicatedScalarEvolution::Preds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> that forms our context.</p>


<p>We will rewrite all expressions assuming that this predicate true.</p>


<p>Definition at line 2463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### RewriteMap {#aca7f54a2245a31bbd96e21aa2e3bb092}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;const SCEV *, RewriteEntry&gt; llvm::PredicatedScalarEvolution::RewriteMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Maps a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> to the rewrite result of that <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> at a certain version number.</p>


<p>If this number doesn't match the current Generation, we will need to do a rewrite. To preserve the transformation order of previous rewrites, we will rewrite the previous result instead of the original <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>.</p>


<p>Definition at line 2450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SE {#a92fadf36e058280250e65768b82ab121}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ScalarEvolution&amp; llvm::PredicatedScalarEvolution::SE</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> analysis.</p>

<p>Definition at line 2456 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SmallConstantMaxTripCount {#af74b7bbc644ab57d4162eb1fa1042df3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;unsigned&gt; llvm::PredicatedScalarEvolution::SmallConstantMaxTripCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The constant max trip count for the loop.</p>

<p>Definition at line 2478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SymbolicMaxBackedgeCount {#a17a1f3b0b6c06e85cf0cca3805c9d6a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEV* llvm::PredicatedScalarEvolution::SymbolicMaxBackedgeCount = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The symbolic backedge taken count.</p>

<p>Definition at line 2475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
