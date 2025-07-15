---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scevwrappredicate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCEVWrapPredicate` Class Reference

<p>This class represents an assumption made on an AddRec expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCEVWrapPredicate { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents an assumption made using <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions which can be checked at run-time. <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IncrementWrapFlags { <a href="#a0cfd938ff9c572d287e5e7923624db70">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Similar to <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a>, but with slightly different semantics for FlagNUSW. <a href="#a0cfd938ff9c572d287e5e7923624db70">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1434e18d5ff272c4b7bfb27e519dee42">SCEVWrapPredicate</a> (const FoldingSetNodeIDRef ID, const SCEVAddRecExpr *AR, IncrementWrapFlags Flags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0cfd938ff9c572d287e5e7923624db70">IncrementWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd0469a627ab55aaa6789c3d6dec0fa9">getFlags</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the set assumed no overflow flags. <a href="#abd0469a627ab55aaa6789c3d6dec0fa9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fadcc50dcb3839af0bfcb62d2cb20b9">getExpr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation of the <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> interface. <a href="#a5fadcc50dcb3839af0bfcb62d2cb20b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bb4ca5c2810fc70f58fcf2581fa5bca">implies</a> (const SCEVPredicate *N, ScalarEvolution &amp;SE) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if this predicate implies <span class="doxyComputerOutput">N</span>. <a href="#a1bb4ca5c2810fc70f58fcf2581fa5bca">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42276b9ddf5e782e18683908a626466a">print</a> (raw_ostream &amp;OS, unsigned Depth=0) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Prints a textual representation of this predicate with an indentation of <span class="doxyComputerOutput">Depth</span>. <a href="#a42276b9ddf5e782e18683908a626466a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55e760ed817efd182374bddd96c0725d">isAlwaysTrue</a> () const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the predicate is always true. <a href="#a55e760ed817efd182374bddd96c0725d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe15431c61eb6e43dafd635afc9d42b4">AR</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0cfd938ff9c572d287e5e7923624db70">IncrementWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43cd4e72320a52b35e6b98b4ae7f1204">Flags</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6075abe0816f373cb741561866f3eefa">clearFlags</a> (SCEVWrapPredicate::IncrementWrapFlags Flags, SCEVWrapPredicate::IncrementWrapFlags OffFlags)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Convenient <a href="#a0cfd938ff9c572d287e5e7923624db70">IncrementWrapFlags</a> manipulation methods. <a href="#a6075abe0816f373cb741561866f3eefa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cce06456a0642612f73e03dfc3af23">maskFlags</a> (SCEVWrapPredicate::IncrementWrapFlags Flags, int Mask)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db937ba78ab75aa91d72c8678a28b78">setFlags</a> (SCEVWrapPredicate::IncrementWrapFlags Flags, SCEVWrapPredicate::IncrementWrapFlags OnFlags)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76a888bd97f7b7bb6b43eb4bdb9dc3bc">getImpliedFlags</a> (const SCEVAddRecExpr *AR, ScalarEvolution &amp;SE)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the set of <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate">SCEVWrapPredicate</a> no wrap flags implied by a <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a>. <a href="#a76a888bd97f7b7bb6b43eb4bdb9dc3bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6348b250afd77c2b910448605b06f309">classof</a> (const SCEVPredicate *P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a6348b250afd77c2b910448605b06f309">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>This class represents an assumption made on an AddRec expression.</p>


<p>Given an affine AddRec expression {a,+,b}, we assume that it has the nssw or nusw flags (defined below) in the first X iterations of the loop, where X is a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression returned by getPredicatedBackedgeTakenCount).</p>


<p>Note that this does not imply that X is equal to the backedge taken count. This means that if we have a nusw predicate for i32 {0,+,1} with a predicated backedge taken count of X, we only guarantee that {0,+,1} has nusw in the first X iterations. {0,+,1} may still wrap in the loop if we have more than X iterations.</p>


<p>Definition at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### IncrementWrapFlags {#a0cfd938ff9c572d287e5e7923624db70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SCEVWrapPredicate::IncrementWrapFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Similar to <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6f">SCEV::NoWrapFlags</a>, but with slightly different semantics for FlagNUSW.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IncrementAnyWrap<a id="a0cfd938ff9c572d287e5e7923624db70a11c850531be360193c9473b4fe240c1d"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IncrementNUSW<a id="a0cfd938ff9c572d287e5e7923624db70a17e825823d4b6a92c1b221c4460c91a3"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IncrementNSSW<a id="a0cfd938ff9c572d287e5e7923624db70aa4c321f736f542d50b81bb06351f7fce"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IncrementNoWrapMask<a id="a0cfd938ff9c572d287e5e7923624db70a230598aea93080d7f8204727504352e7"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2) - 1)</td>
</tr>

</table>
</dd>
</dl>


<p>The increment is considered to be signed, and a + b (where b is the increment) is considered to wrap if: zext(a + b) != zext(a) + sext(b)</p>


<p>If Signed is a function that takes an n-bit tuple and maps to the integer domain as the tuples value interpreted as twos complement, and Unsigned a function that takes an n-bit tuple and maps to the integer domain as the base two value of input tuple, then a + b has IncrementNUSW iff:</p>


<p>0 &lt;= <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13fac837bff23a12c3735d463020f37979de">Unsigned(a)</a> + <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxisellowering-cpp/#ae1a90b5d85643644483b2ca70da4d13faed3fa7a5efe80dad3ea3d86cc14be246">Signed(b)</a> &lt; 2^n</p>


<p>The IncrementNSSW flag has identical semantics with <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">SCEV::FlagNSW</a>.</p>


<p>Note that the IncrementNUSW flag is not commutative: if base + inc has IncrementNUSW, then inc + base doesn't neccessarily have this property. The reason for this is that this is used for sign/zero extending affine AddRec <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expressions when a <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate">SCEVWrapPredicate</a> is assumed. A {base,+,inc} expression is already non-commutative with regards to base and inc, since it is interpreted as: (((base + inc) + inc) + inc) ...</p>


<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SCEVWrapPredicate() {#a1434e18d5ff272c4b7bfb27e519dee42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVWrapPredicate::SCEVWrapPredicate (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeidref">FoldingSetNodeIDRef</a> ID, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR, <a href="#a0cfd938ff9c572d287e5e7923624db70">IncrementWrapFlags</a> Flags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 387 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14961 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a75f4943e861ac0b6d41439c7d5c07adbaac3069eca0cb48a03eaa7d95fb84829c">llvm::SCEVPredicate::P_Wrap</a> and <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a6d2a13cb997f4164ed8d17c16b50acf1">llvm::SCEVPredicate::SCEVPredicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getExpr() {#a5fadcc50dcb3839af0bfcb62d2cb20b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVAddRecExpr * SCEVWrapPredicate::getExpr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Implementation of the <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> interface.</p>

<p>Declaration at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14966 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>Referenced by <a href="#a42276b9ddf5e782e18683908a626466a">print</a>.</p>

</div>
</div>

### getFlags() {#abd0469a627ab55aaa6789c3d6dec0fa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IncrementWrapFlags llvm::SCEVWrapPredicate::getFlags ()</td>
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

<p>Returns the set assumed no overflow flags.</p>

<p>Definition at line 392 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#a42276b9ddf5e782e18683908a626466a">print</a>.</p>

</div>
</div>

### implies() {#a1bb4ca5c2810fc70f58fcf2581fa5bca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVWrapPredicate::implies (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * N, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
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

<p>Returns true if this predicate implies <span class="doxyComputerOutput">N</span>.</p>

<p>Declaration at line 396 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 14968 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a38c440751f1bf5f19bc12b95f8f0f2a6">llvm::ScalarEvolution::getNoopOrSignExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a933eb87303a6ce51c8894e431fbc389b">llvm::ScalarEvolution::getNoopOrZeroExtend</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#aefeda9454a5e8dfcec3deb106964832a">llvm::SCEV::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a10cde7087f90dc664b6799814aa28584">llvm::ScalarEvolution::getWiderType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70aa4c321f736f542d50b81bb06351f7fce">IncrementNSSW</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70a17e825823d4b6a92c1b221c4460c91a3">IncrementNUSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a5a672708a81ae8da8fb56e32638ca9b3">llvm::ScalarEvolution::isKnownPositive</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#af74112dae88db73eb5484821b6f0fccd">llvm::ScalarEvolution::isKnownPredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a3b996fbf8458aafffc86cb98a68d0a47">llvm::Type::isPointerTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a6d2a13cb997f4164ed8d17c16b50acf1">llvm::SCEVPredicate::SCEVPredicate</a> and <a href="#a3db937ba78ab75aa91d72c8678a28b78">setFlags</a>.</p>

</div>
</div>

### isAlwaysTrue() {#a55e760ed817efd182374bddd96c0725d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEVWrapPredicate::isAlwaysTrue ()</td>
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

<p>Returns true if the predicate is always true.</p>


<p>This means that no assumptions were made and nothing needs to be checked at run-time.</p>


<p>Declaration at line 398 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15007 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="#a6075abe0816f373cb741561866f3eefa">clearFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70a11c850531be360193c9473b4fe240c1d">IncrementAnyWrap</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70aa4c321f736f542d50b81bb06351f7fce">IncrementNSSW</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8fed3b807739f2ff6942c12407ab00fa">llvm::ScalarEvolution::setFlags</a>.</p>

</div>
</div>

### print() {#a42276b9ddf5e782e18683908a626466a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCEVWrapPredicate::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, unsigned Depth=0)</td>
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

<p>Prints a textual representation of this predicate with an indentation of <span class="doxyComputerOutput">Depth</span>.</p>

<p>Declaration at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15017 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1eb5609345b906d024fbf9e4bc1adc06afe578efb7ca235af77fb0eef7edcf639">llvm::Depth</a>, <a href="#a5fadcc50dcb3839af0bfcb62d2cb20b9">getExpr</a>, <a href="#abd0469a627ab55aaa6789c3d6dec0fa9">getFlags</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70aa4c321f736f542d50b81bb06351f7fce">IncrementNSSW</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70a17e825823d4b6a92c1b221c4460c91a3">IncrementNUSW</a> and <a href="/web-llvm/docs/api/classes/llvm/raw-ostream/#a8fdf5cdf041c8aded7e3308c1c3efacc">llvm::raw_ostream::indent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AR {#afe15431c61eb6e43dafd635afc9d42b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVAddRecExpr* llvm::SCEVWrapPredicate::AR</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 383 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### Flags {#a43cd4e72320a52b35e6b98b4ae7f1204}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IncrementWrapFlags llvm::SCEVWrapPredicate::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a6348b250afd77c2b910448605b06f309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SCEVWrapPredicate::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevpredicate">SCEVPredicate</a> * P)</td>
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

<p>Definition at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a75f4943e861ac0b6d41439c7d5c07adbaac3069eca0cb48a03eaa7d95fb84829c">llvm::SCEVPredicate::P_Wrap</a> and <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a6d2a13cb997f4164ed8d17c16b50acf1">llvm::SCEVPredicate::SCEVPredicate</a>.</p>

</div>
</div>

### clearFlags() {#a6075abe0816f373cb741561866f3eefa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVWrapPredicate::IncrementWrapFlags llvm::SCEVWrapPredicate::clearFlags (<a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> Flags, <a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> OffFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Convenient <a href="#a0cfd938ff9c572d287e5e7923624db70">IncrementWrapFlags</a> manipulation methods.</p>

<p>Definition at line 351 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0cfd938ff9c572d287e5e7923624db70a230598aea93080d7f8204727504352e7">IncrementNoWrapMask</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a6fb96c9b4d017d69818db581dae5bd96">llvm::PredicatedScalarEvolution::hasNoOverflow</a>, <a href="#a55e760ed817efd182374bddd96c0725d">isAlwaysTrue</a> and <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a757ce31dd838b17c024287ce9d17c4c2">llvm::PredicatedScalarEvolution::setNoOverflow</a>.</p>

</div>
</div>

### getImpliedFlags() {#a76a888bd97f7b7bb6b43eb4bdb9dc3bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVWrapPredicate::IncrementWrapFlags SCEVWrapPredicate::getImpliedFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a> * AR, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a> &amp; SE)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the set of <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate">SCEVWrapPredicate</a> no wrap flags implied by a <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr">SCEVAddRecExpr</a>.</p>

<p>Declaration at line 380 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 15027 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">llvm::SCEV::FlagNSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scev/#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">llvm::SCEV::FlagNUW</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70a11c850531be360193c9473b4fe240c1d">IncrementAnyWrap</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70aa4c321f736f542d50b81bb06351f7fce">IncrementNSSW</a>, <a href="#a0cfd938ff9c572d287e5e7923624db70a17e825823d4b6a92c1b221c4460c91a3">IncrementNUSW</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8fed3b807739f2ff6942c12407ab00fa">llvm::ScalarEvolution::setFlags</a> and <a href="#a3db937ba78ab75aa91d72c8678a28b78">setFlags</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a6fb96c9b4d017d69818db581dae5bd96">llvm::PredicatedScalarEvolution::hasNoOverflow</a> and <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a757ce31dd838b17c024287ce9d17c4c2">llvm::PredicatedScalarEvolution::setNoOverflow</a>.</p>

</div>
</div>

### maskFlags() {#af2cce06456a0642612f73e03dfc3af23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVWrapPredicate::IncrementWrapFlags llvm::SCEVWrapPredicate::maskFlags (<a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> Flags, int Mask)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 360 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0cfd938ff9c572d287e5e7923624db70a230598aea93080d7f8204727504352e7">IncrementNoWrapMask</a>.</p>

</div>
</div>

### setFlags() {#a3db937ba78ab75aa91d72c8678a28b78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVWrapPredicate::IncrementWrapFlags llvm::SCEVWrapPredicate::setFlags (<a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> Flags, <a href="#a0cfd938ff9c572d287e5e7923624db70">SCEVWrapPredicate::IncrementWrapFlags</a> OnFlags)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel nodiscard">nodiscard</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 368 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="#a0cfd938ff9c572d287e5e7923624db70a230598aea93080d7f8204727504352e7">IncrementNoWrapMask</a>.</p>


<p>Referenced by <a href="#a76a888bd97f7b7bb6b43eb4bdb9dc3bc">getImpliedFlags</a>, <a href="#a1bb4ca5c2810fc70f58fcf2581fa5bca">implies</a> and <a href="/web-llvm/docs/api/classes/llvm/predicatedscalarevolution/#a757ce31dd838b17c024287ce9d17c4c2">llvm::PredicatedScalarEvolution::setNoOverflow</a>.</p>

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
