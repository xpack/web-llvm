---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/scev
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SCEV` Class Reference

<p>This class represents an analyzed expression in the program. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::SCEV { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">llvm/Analysis/ScalarEvolution.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node">Node</a> - This class is used to maintain the singly linked bucket list in a folding set. <a href="/web-llvm/docs/api/classes/llvm/foldingsetbase/node/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevcastexpr">SCEVCastExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This is the base class for unary cast operator classes. <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a constant integer value. <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute">SCEVCouldNotCompute</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>An object of this class is returned by queries that could not be answered. <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr">SCEVNAryExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This node is a base class providing common functionality for n'ary operators. <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevudivexpr">SCEVUDivExpr</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents a binary unsigned division operation. <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This means that we are dealing with an entirely unknown <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> value, and only represent it as its LLVM <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>. <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scevvscale">SCEVVScale</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This class represents the value of vscale, as used when defining the length of a scalable vector or returned by the llvm.vscale() intrinsic. <a href="/web-llvm/docs/api/classes/llvm/scevvscale/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">NoWrapFlags { <a href="#af43000d4dcb7d6d63cb6e36933ed3f6f">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#af43000d4dcb7d6d63cb6e36933ed3f6f">NoWrapFlags</a> are bitfield indices into SubclassData. <a href="#af43000d4dcb7d6d63cb6e36933ed3f6f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae29da85cd2dc185164c105e98fb7ec58">FoldingSetTrait&lt; SCEV &gt;</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace7f137cfb19ce8073b78b85f819430c">SCEV</a> (const FoldingSetNodeIDRef ID, SCEVTypes SCEVTy, unsigned short ExpressionSize)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7d3fc30d912cee99348a044b76f2a8">SCEV</a> (const SCEV &amp;)=delete</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17f5f384636a04166136c6b74934655b">operator=</a> (const SCEV &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4f956914bf94bdcd1058badb5bd90e6">getSCEVType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefeda9454a5e8dfcec3deb106964832a">getType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the LLVM type of this <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression. <a href="#aefeda9454a5e8dfcec3deb106964832a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b675a820ab094d694d602eb16ef02e5">operands</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return operands of this <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression. <a href="#a0b675a820ab094d694d602eb16ef02e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4541962f9c18aacceb7243520eb15e1f">isZero</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the expression is a constant zero. <a href="#a4541962f9c18aacceb7243520eb15e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ecb726f4e7b445057b795ed500546a0">isOne</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the expression is a constant one. <a href="#a1ecb726f4e7b445057b795ed500546a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac0db66a4bb6e1e1066609d5c6d28d8">isAllOnesValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the expression is a constant all-ones value. <a href="#a7ac0db66a4bb6e1e1066609d5c6d28d8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87b23e247f35b163544f1ce8e920801c">isNonConstantNegative</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified scev is negated, but not a constant. <a href="#a87b23e247f35b163544f1ce8e920801c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a102c99af586cd76e0d9ff32ac0e825e0">getExpressionSize</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdbe9e14ed6edbd5b5e3c252585902ec">print</a> (raw_ostream &amp;OS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print out the internal representation of this scalar to the specified stream. <a href="#acdbe9e14ed6edbd5b5e3c252585902ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ae35ec967d69bc1cd21ae482bbdd4a2">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This method is used for debugging. <a href="#a6ae35ec967d69bc1cd21ae482bbdd4a2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1d4f0b6eece16e8a081906d13a84f9">ExpressionSize</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade1f1b89affe842dacd20c7f950e99c9">SubclassData</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This field is initialized to zero and may be used in subclasses to store miscellaneous information. <a href="#ade1f1b89affe842dacd20c7f950e99c9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeidref">FoldingSetNodeIDRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a717659b1a38d7bb265ec0d47292f68fa">FastID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an Interned <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> for this node. <a href="#a717659b1a38d7bb265ec0d47292f68fa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93693efb507be35c82004a164ab9b4f8">SCEVType</a></td>
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

<p>This class represents an analyzed expression in the program.</p>


<p>These are opaque objects that the client is not allowed to do much with directly.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### NoWrapFlags {#af43000d4dcb7d6d63cb6e36933ed3f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::SCEV::NoWrapFlags </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#af43000d4dcb7d6d63cb6e36933ed3f6f">NoWrapFlags</a> are bitfield indices into SubclassData.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlagAnyWrap<a id="af43000d4dcb7d6d63cb6e36933ed3f6fa23e74052c4d79cfdaa23460a3c946656"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlagNW<a id="af43000d4dcb7d6d63cb6e36933ed3f6faf763167030e97d18e8f8c8ed3dba28e3"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 0))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlagNUW<a id="af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 1))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FlagNSW<a id="af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 2))</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoWrapMask<a id="af43000d4dcb7d6d63cb6e36933ed3f6fae022582ed4b56bdb108b4488809e11e6"></a></td>
<td class="doxyEnumItemDescription"> (= (1 &lt;&lt; 3) - 1)</td>
</tr>

</table>
</dd>
</dl>


<p>Add and Mul expressions may have no-unsigned-wrap &lt;NUW&gt; or no-signed-wrap &lt;NSW&gt; properties, which are derived from the IR operator. NSW is a misnomer that we use to mean no signed overflow or underflow.</p>


<p>AddRec expressions may have a no-self-wraparound &lt;NW&gt; property if, in the integer domain, abs(step) * max-iteration(loop) &lt;= unsigned-max(bitwidth). This means that the recurrence will never reach its start value if the step is non-zero. Computing the same value on each iteration is not considered wrapping, and recurrences with step = 0 are trivially &lt;NW&gt;. &lt;NW&gt; is independent of the sign of step and the value the add recurrence starts with.</p>


<p>Note that NUW and NSW are also valid properties of a recurrence, and either implies NW. For convenience, NW will be set for a recurrence whenever either NUW or NSW are set.</p>


<p>We require that the flag on a <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> apply to the entire scope in which that <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is defined. A <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a>'s scope is set of locations dominated by a defining location, which is in turn described by the following rules:</p>


<ul class="doxyList ">
<li>A <a href="/web-llvm/docs/api/classes/llvm/scevunknown">SCEVUnknown</a> is at the point of definition of the <a href="/web-llvm/docs/api/classes/llvm/value">Value</a>.</li>
<li>A <a href="/web-llvm/docs/api/classes/llvm/scevconstant">SCEVConstant</a> is defined at all points.</li>
<li>A SCEVAddRec is defined starting with the header of the associated loop.</li>
<li>All other SCEVs are defined at the earlest point all operands are defined.</li>
</ul>

<p>The above rules describe a maximally hoisted form (without regards to potential control dependence). A <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> is defined anywhere a corresponding instruction could be defined in said maximally hoisted form. Note that <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr">SCEVUDivExpr</a> (currently the only expression type which can trap) can be defined per these rules in regions where it would trap at runtime. A <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> being defined does not require the existence of any instruction within the defined scope.</p>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### FoldingSetTrait&lt; SCEV &gt; {#ae29da85cd2dc185164c105e98fb7ec58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend struct <a href="/web-llvm/docs/api/structs/llvm/foldingsettrait">FoldingSetTrait</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 412 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a>, <a href="/web-llvm/docs/api/classes/llvm/scevpredicate/#a6d2a13cb997f4164ed8d17c16b50acf1">llvm::SCEVPredicate::SCEVPredicate</a> and <a href="/web-llvm/docs/api/classes/llvm/scevunionpredicate/#aad6219405572b4180a5080b2642e020f">llvm::SCEVUnionPredicate::SCEVUnionPredicate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SCEV() {#ace7f137cfb19ce8073b78b85f819430c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEV::SCEV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeidref">FoldingSetNodeIDRef</a> ID, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5e">SCEVTypes</a> SCEVTy, unsigned short ExpressionSize)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#aaf1d4f0b6eece16e8a081906d13a84f9">ExpressionSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#aea85e11db3d72c739df477f88e3e1913">llvm::SCEVCastExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#ade52c1d7a2aba84029a91c05eae309db">llvm::SCEVConstant::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute/#ad3cca751f8e7a761a113ee2414a5c05c">llvm::SCEVCouldNotCompute::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a683f6ac8f67a2aa12754c196dc96c9e3">llvm::SCEVNAryExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a0af07c0b7413ed4f8eb74102ae19e2e7">llvm::SCEVUDivExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a4e62c555edb269cdfff199b897a12a0e">llvm::SCEVUnknown::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevvscale/#aa33a0f24ffc13ae1f926d3d9a9826202">llvm::SCEVVScale::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a64f39bbc1130d1a36d3824633863dc51">llvm::SCEVUDivExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ab6c2fb358d83304761d3848aa70ee5d6">llvm::SCEVCastExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#a23f00d09bfec103f4a500db452aaace2">llvm::SCEVCastExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ad99e00da7acb7973ae006f5b53ce04f6">llvm::SCEVNAryExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a3de87bd936348d41261ca1cd806ff819">llvm::SCEVUDivExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#ad0fdc55c45a39b722f3d990505b55dd7">llvm::SCEVUDivExpr::getRHS</a>, <a href="#a17f5f384636a04166136c6b74934655b">operator=</a>, <a href="#acdbe9e14ed6edbd5b5e3c252585902ec">print</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#a15a0237aaba54972c69acad43448c093">llvm::SCEVConstant::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a15a0237aaba54972c69acad43448c093">llvm::SCEVUDivExpr::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a15a0237aaba54972c69acad43448c093">llvm::SCEVUnknown::ScalarEvolution</a>, <a href="/web-llvm/docs/api/classes/llvm/scevvscale/#a15a0237aaba54972c69acad43448c093">llvm::SCEVVScale::ScalarEvolution</a>, <a href="#a4d7d3fc30d912cee99348a044b76f2a8">SCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#acb400ab122ec2c7e1222c7dc7eac079e">llvm::SCEVCastExpr::SCEVCastExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute/#a4879e3633c19d6a7c7b9c56cfd3cec18">llvm::SCEVCouldNotCompute::SCEVCouldNotCompute</a> and <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a76d2af00b10cda0b511a84a742d13f00">llvm::SCEVNAryExpr::SCEVNAryExpr</a>.</p>

</div>
</div>

### SCEV() {#a4d7d3fc30d912cee99348a044b76f2a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SCEV::SCEV (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#ace7f137cfb19ce8073b78b85f819430c">SCEV</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a17f5f384636a04166136c6b74934655b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEV &amp; llvm::SCEV::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#ace7f137cfb19ce8073b78b85f819430c">SCEV</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a6ae35ec967d69bc1cd21ae482bbdd4a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void SCEV::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This method is used for debugging.</p>

<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#acdbe9e14ed6edbd5b5e3c252585902ec">print</a>.</p>

</div>
</div>

### getExpressionSize() {#a102c99af586cd76e0d9ff32ac0e825e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::SCEV::getExpressionSize ()</td>
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



<p>Definition at line 169 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Reference <a href="#aaf1d4f0b6eece16e8a081906d13a84f9">ExpressionSize</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/scevdbgvaluebuilder/#ac651c1875f806ba7d3b74b6e32323048">anonymous{LoopStrengthReduce.cpp}::SCEVDbgValueBuilder::createIterCountExpr</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a81a7153270eb1fafa4502adc85f49adf">hasHugeExpression</a>.</p>

</div>
</div>

### getSCEVType() {#ad4f956914bf94bdcd1058badb5bd90e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SCEVTypes llvm::SCEV::getSCEVType ()</td>
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



<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaddexpr/#a8c1ca261e3edd4bdc20a12945e52c523">llvm::SCEVAddExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a93b096608fec2f6b2c6d5b4fec2dbb6c">llvm::SCEVAddRecExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#aea85e11db3d72c739df477f88e3e1913">llvm::SCEVCastExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcommutativeexpr/#a3a72bdabacd1814a63b8a71ce6109992">llvm::SCEVCommutativeExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevconstant/#ade52c1d7a2aba84029a91c05eae309db">llvm::SCEVConstant::classof</a>, <a href="/web-llvm/docs/api/structs/llvm/scevcouldnotcompute/#ad3cca751f8e7a761a113ee2414a5c05c">llvm::SCEVCouldNotCompute::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevintegralcastexpr/#ab8b71fdad3c03ecb7064beceb718ebea">llvm::SCEVIntegralCastExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevminmaxexpr/#aaa92ab300fe307d86daa5a5ab04e8e8e">llvm::SCEVMinMaxExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevmulexpr/#aca64f06e0f646497cff2e2160588f916">llvm::SCEVMulExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a683f6ac8f67a2aa12754c196dc96c9e3">llvm::SCEVNAryExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevptrtointexpr/#a287679cc6d0f88eaaea49ce423b421a5">llvm::SCEVPtrToIntExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#a5cb30517ec635f4dd45b75546774c62e">llvm::SCEVSequentialMinMaxExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialuminexpr/#a5427624b08a39a74a1b7c3dde28494aa">llvm::SCEVSequentialUMinExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsignextendexpr/#a7c752075048c7262ba253f020a236f93">llvm::SCEVSignExtendExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsmaxexpr/#a0187000e3bd38397580e28c6c7b62fb2">llvm::SCEVSMaxExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsminexpr/#ad2851cdb61daea9cb47e7383dfd84cdb">llvm::SCEVSMinExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevtruncateexpr/#a064e40e3128c4f3babba705c638b1af3">llvm::SCEVTruncateExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a0af07c0b7413ed4f8eb74102ae19e2e7">llvm::SCEVUDivExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevumaxexpr/#ab14e9721aabf5b7d27aa5d6fa8f8a17e">llvm::SCEVUMaxExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevuminexpr/#a53befb3a11f61891384d5959b1da44f6">llvm::SCEVUMinExpr::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevunknown/#a4e62c555edb269cdfff199b897a12a0e">llvm::SCEVUnknown::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevvscale/#aa33a0f24ffc13ae1f926d3d9a9826202">llvm::SCEVVScale::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/scevzeroextendexpr/#a0072432c384b3870d9aa40c058540947">llvm::SCEVZeroExtendExpr::classof</a>, <a href="/web-llvm/docs/api/structs/anonymous-scalarevolution-cpp-/scevpoisoncollector/#a8f7456a85b68eb2303d072fa2560c95a">anonymous{ScalarEvolution.cpp}::SCEVPoisonCollector::follow</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#af8532b54a025a850863502cadc554fdd">llvm::SCEVSequentialMinMaxExpr::getEquivalentNonSequentialSCEVType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a60008b3cbf2b4ef3e3d14af04beb6a06">getExprBase</a>, <a href="#aefeda9454a5e8dfcec3deb106964832a">getType</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a4d43163acfcdefe57d402dab3640d8be">GroupByComplexity</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7ac21134b2aaca2a7d55f6ff9d92f5b2">isHighCostExpansion</a>, <a href="#a0b675a820ab094d694d602eb16ef02e5">operands</a>, <a href="#acdbe9e14ed6edbd5b5e3c252585902ec">print</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a02c3cff4baf0eb36d46fd37369a0bb88">SCEVMinMaxExprContains</a>, <a href="/web-llvm/docs/api/structs/llvm/scevvisitor/#a1e7a5297e3ded4db5e828ee4bd651b34">llvm::SCEVVisitor&lt; SCEVSequentialMinMaxDeduplicatingVisitor, RetVal &gt;::visit</a> and <a href="/web-llvm/docs/api/classes/llvm/scevtraversal/#aa3e492f428e815c1c89e3a5625e2c233">llvm::SCEVTraversal&lt; SV &gt;::visitAll</a>.</p>

</div>
</div>

### getType() {#aefeda9454a5e8dfcec3deb106964832a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * SCEV::getType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the LLVM type of this <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression.</p>

<p>Declaration at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 386 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad4f956914bf94bdcd1058badb5bd90e6">getSCEVType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea3a80b1a7dda48464be1849ee1fb85868">llvm::scAddExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eabcb1f797cb330e61a5879fc260aaec5b">llvm::scConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eab6b4550f8ae7180f0e83ebb40a9882ec">llvm::scCouldNotCompute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eafd56f054da3d1f9b827ae1003da3a38b">llvm::scMulExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eae996cdd31b3e2df5dbd55ff638d2d456">llvm::scPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea376414ac1f3ac8cb449fd5167a2db091">llvm::scSequentialUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea684b8e2484b12d494e82f7053d005754">llvm::scSMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea88dad4534f471d79d0a7a094d809ef55">llvm::scSMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3656bcc84af213cc488acb56c60de22">llvm::scTruncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eaee62cac87c0dc1f483d783aae69101c4">llvm::scUDivExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3d0abdf8125de904320df332dbefedb">llvm::scUMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea0bf2fc9a454ce237fde0906ee24b0acc">llvm::scUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea80488550b42b6548ec4d5c7118c7ff1d">llvm::scUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea61df12d6bb21842a8f766c4433c85717">llvm::scVScale</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevaaresult/#a688068ae24921ce2ed14ca5ff0b732e2">llvm::SCEVAAResult::alias</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a55aceb0318074f694f763d011f71cd90">BinomialCoefficient</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5704370a1379cfd0062d47b73ba65cb0">llvm::cannotBeMaxInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef5f1583da883ba28cb113c02d29f1d9">llvm::cannotBeMinInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ae0ca564918ec63a9b4d2229374fec747">llvm::ScalarEvolution::computeConstantDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/classes/llvm/indexedreference/#a0182cdf55f9bfbdd904e3f5e6802316a">llvm::IndexedReference::computeRefCost</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopcacheanalysis-cpp/#a605f4ae007c6b19244c175eb1990abc1">computeTripCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looppeel-cpp/#a7098623cafc05376a44b27d202b03372">countToEliminateCompares</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a51c0653682103a713b0c3695aae3a1ff">createNodeForSelectViaUMinSeq</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a8160c4d5a8fc34f6085af951980dbaa6">createReplacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a5586ec5eac8a93b87b095f949ea8daf3">anonymous{SimplifyIndVar.cpp}::WidenIV::createWideIV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#aa59a46776e15b1f1bd597c4e1e769f59">DoInitialMatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#aac98cc9f91ac31468cb93febcd484e5b">llvm::SCEVExpander::expandCodeFor</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a202c5827957336be308d423d78ff7119">findForkedSCEVs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#adc183a6edc37f305ee9ca5ff0bc33a6e">FindLoopCounter</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aa35959e3f6bea8e35cffcfd8659e3156">llvm::ScalarEvolution::getAnyExtendExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a0f3039f831c483956c153ed9dee23dba">llvm::ScalarEvolution::getGEPExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a094d95c92490272d4b7a6bf4ab90009d">llvm::ScalarEvolution::getLoopInvariantExitCondDuringFirstIterationsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a4bab447a6422427e5fc92bbbc0c12fba">llvm::ScalarEvolution::getLosslessPtrToIntExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a765b135bf0191fca6004b4167bcfb493">llvm::ScalarEvolution::getMinTrailingZeros</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a81bada52d17e453e10221581a1bda050">anonymous{LoopStrengthReduce.cpp}::Immediate::getNegativeSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/alignmentfromassumptions-cpp/#af2917523aba1c4fae828904ab0992254">getNewAlignment</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a51c730254cd6b346d9fa4588c58a7517">anonymous{LoopStrengthReduce.cpp}::Immediate::getSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#ae8a19e1b12d26ad87bc379e576ff5a7f">getSignedOverflowLimitForStep</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a643b61ddaf17331f3ff1d4f85c7c9a23">llvm::ScalarEvolution::getSignExtendExprImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afdd1ebe6412f9afb43d0639420afffe0">llvm::getStartAndEndForAccess</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a3e3935d45c4b79b85a117b47cc1d2e61">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a17e35fd9a6e590c201fd05105589ce47">llvm::ScalarEvolution::getTripCountFromExitCount</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a1596600146d065022af8b9c4a1d0b427">llvm::SCEVAddRecExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevminmaxexpr/#a0b15683671fc89c570661c1c1783273e">llvm::SCEVMinMaxExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevmulexpr/#aeb2d92e2cfbf96877bd5c18683bf2390">llvm::SCEVMulExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevsequentialminmaxexpr/#ad62e2173f3880516093efbf3bcaf68e2">llvm::SCEVSequentialMinMaxExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a94507c7b770ce5695c0450a782050016">llvm::SCEVUDivExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aef86e2e34d31e4595f5a442fe55ecbe9">llvm::ScalarEvolution::getUMinFromMismatchedTypes</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/immediate/#a8829aacd47e6a4f3dbaf6c359d5afdfb">anonymous{LoopStrengthReduce.cpp}::Immediate::getUnknownSCEV</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#aff0515f214b4d4e5d5a3197b11d5eacc">getUnsignedOverflowLimitForStep</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#a2c90afd148f896bab791bdcad6b41dd0">anonymous{SimplifyIndVar.cpp}::WidenIV::getWideRecurrence</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a26ffa319e1953452b1d1df84923f2108">llvm::ScalarEvolution::getZeroExtendExprImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac438183b3cdb70d2fa78265512238514">llvm::hasIterationCountInvariantInParent</a>, <a href="/web-llvm/docs/api/classes/llvm/scevwrappredicate/#a1bb4ca5c2810fc70f58fcf2581fa5bca">llvm::SCEVWrapPredicate::implies</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a50702846ece6b5c6ef8826ca0e137bc5">llvm::ARMTTIImpl::isHardwareLoopProfitable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abc1d309b62fc59309659ac3fa7f3f68f">llvm::isKnownNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af042aac9d86aacb5ee9e1af24590f4c2">llvm::isKnownNonNegativeInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1dc474f11162cc2893aa0f7d208d6ea2">llvm::isKnownNonPositiveInLoop</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a947ac955070bcb92444d3bb31077eb13">llvm::isKnownPositiveInLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a8b617baf7fc5914d8a245e702ea65a7d">llvm::ScalarEvolution::isLoopBackedgeGuardedByCond</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#ac8cf3aa27282d640f5acbc3a676e03c5">isSafeDecreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/loopaccessanalysis-cpp/#a917578aa4ba03c192fa1c048ed3b5b00">isSafeDependenceDistance</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopconstrainer-cpp/#adbc17f3ace73f701522eefe28104c06c">isSafeIncreasingBound</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a6c630dc63715497e5e49ab1ca9dc6ccb">IsSimplerBaseSCEVForTarget</a>, <a href="/web-llvm/docs/api/structs/llvm/scevpatternmatch/cst-pred-ty/#ab4dc630e0981601d51bf88cf21779d7e">llvm::SCEVPatternMatch::cst_pred_ty&lt; Predicate &gt;::match</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a740a442f349b36821071c21e265e23e1">optimizeLoopExitWithUnknownExitCount</a>, <a href="/web-llvm/docs/api/structs/llvm/loopstructure/#adc8650d6098e0949f6ecc6368c2ebb99">llvm::LoopStructure::parseLoopStructure</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a6d272ad3fd2fe1420ccd7c464dfb03a3">PrintSCEVWithTypeHint</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/wideniv/#ac65b91bafca4f727e589bdfbfb79edc1">anonymous{SimplifyIndVar.cpp}::WidenIV::pushNarrowIVUsers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aaec5d8efaa82dedb3a3b23f4482f31eb">llvm::replaceSymbolicStrideSCEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2776b4c8cd41fd60781f7b9e18af9edb">llvm::splitLoopBound</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd628d451ca9d9b021876d59f46e670b">llvm::UnrollRuntimeLoopRemainder</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopflatten-cpp/#a11a65ce1550eac260dca320a7028328e">verifyTripCount</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ae8ee3aa50e72940cabb7d758613ce2cf">llvm::SCEVDivision::visitAddExpr</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#ac38f0b8f591d282177a689cabe66c392">llvm::SCEVDivision::visitAddRecExpr</a> and <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#afab4a1d0e1f34b286eec49ac8bd96ef1">llvm::SCEVDivision::visitMulExpr</a>.</p>

</div>
</div>

### isAllOnesValue() {#a7ac0db66a4bb6e1e1066609d5c6d28d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEV::isAllOnesValue ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the expression is a constant all-ones value.</p>

<p>Declaration at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 452 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/scevpatternmatch/#a1de79361b162493659d416289d71be8f">llvm::SCEVPatternMatch::m_scev_AllOnes</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#adaa8fd1f2af30380d7080ef96b976209">MatchNotExpr</a>.</p>

</div>
</div>

### isNonConstantNegative() {#a87b23e247f35b163544f1ce8e920801c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEV::isNonConstantNegative ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the specified scev is negated, but not a constant.</p>

<p>Declaration at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac36edd0f1ce976f0025c98e88d3830ea62b6d55816cf737bfc6f42e60df1a3f2">llvm::Mul</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>.</p>

</div>
</div>

### isOne() {#a1ecb726f4e7b445057b795ed500546a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEV::isOne ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the expression is a constant one.</p>

<p>Declaration at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/scevpatternmatch/#a32f18a399d4211e82f655952be83b3fe">llvm::SCEVPatternMatch::m_scev_One</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevexpander/#a16e9052fd33aedf29b009262d35d59f8">llvm::SCEVExpander::generateOverflowCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a14bc7872374f530d4ed193d9921825c5">genLoopLimit</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#ab0f2467f35df49e4d9d0c9623e2530cf">getStartForNegStride</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#a7803cd22b4405090d0cb0b87d697a612">isLoopCounter</a>.</p>

</div>
</div>

### isZero() {#a4541962f9c18aacceb7243520eb15e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SCEV::isZero ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return true if the expression is a constant zero.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 448 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/scevpatternmatch/#a62d53a67714c66eee08eeabddc553f90">llvm::SCEVPatternMatch::m_scev_Zero</a> and <a href="/web-llvm/docs/api/namespaces/llvm/patternmatch/#a25d956d9e0beadd47ce4bc255dfa811d">llvm::PatternMatch::match</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a11da3451c68e56248a152964e5915cd8">breakBackedgeIfNotTaken</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a0a8a72a5038e4a261d35418751506868">calculateRtStride</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#ad0531a07d7868c1577980524cf2add3a">CollectSubexprs</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a65ab4267c6c132d06451b5d97bc9ee83">llvm::LoopVectorizationCostModel::computeMaxVF</a>, <a href="/web-llvm/docs/api/structs/llvm/scevdivision/#a0dfe5dc28e2f4ac38e33880cfd0170ae">llvm::SCEVDivision::divide</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a174350306649bc16f97803763bcae8f7">llvm::findArrayDimensions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/indvarsimplify-cpp/#adc183a6edc37f305ee9ca5ff0bc33a6e">FindLoopCounter</a>, <a href="/web-llvm/docs/api/structs/anonymous-loopstrengthreduce-cpp-/formula/#a5e104e7ceecb5b2eddfc08e66e925c09">anonymous{LoopStrengthReduce.cpp}::Formula::initialMatch</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopstrengthreduce-cpp-/lsruse/#ab2507970e8b86d818892ad183328b450">anonymous{LoopStrengthReduce.cpp}::LSRUse::InsertFormula</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a290c161463cbfb7720d6499dba1310ad">isAlwaysFoldable</a>, <a href="/web-llvm/docs/api/structs/llvm/vplantransforms/#af25d938764b8634e70e95ff3f0c35129">llvm::VPlanTransforms::optimizeForVFAndUF</a>, <a href="/web-llvm/docs/api/classes/anonymous-indvarsimplify-cpp-/indvarsimplify/#a145b6ea5ff08ca6373ed24389ca97c40">anonymous{IndVarSimplify.cpp}::IndVarSimplify::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp/#a8fa1050509c4edb3c4683179e01035a2">SolveQuadraticAddRecRange</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff82c03c1ce8b945170bcb1f0f624c17">llvm::ScalarEvolution::verify</a>.</p>

</div>
</div>

### operands() {#a0b675a820ab094d694d602eb16ef02e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; const SCEV * &gt; SCEV::operands ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return operands of this <a href="/web-llvm/docs/api/classes/llvm/scev">SCEV</a> expression.</p>

<p>Declaration at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 420 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad4f956914bf94bdcd1058badb5bd90e6">getSCEVType</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea3a80b1a7dda48464be1849ee1fb85868">llvm::scAddExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eabcb1f797cb330e61a5879fc260aaec5b">llvm::scConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eab6b4550f8ae7180f0e83ebb40a9882ec">llvm::scCouldNotCompute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eafd56f054da3d1f9b827ae1003da3a38b">llvm::scMulExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eae996cdd31b3e2df5dbd55ff638d2d456">llvm::scPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea376414ac1f3ac8cb449fd5167a2db091">llvm::scSequentialUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea684b8e2484b12d494e82f7053d005754">llvm::scSMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea88dad4534f471d79d0a7a094d809ef55">llvm::scSMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3656bcc84af213cc488acb56c60de22">llvm::scTruncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eaee62cac87c0dc1f483d783aae69101c4">llvm::scUDivExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3d0abdf8125de904320df332dbefedb">llvm::scUMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea0bf2fc9a454ce237fde0906ee24b0acc">llvm::scUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea80488550b42b6548ec4d5c7118c7ff1d">llvm::scUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea61df12d6bb21842a8f766c4433c85717">llvm::scVScale</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ae0ca564918ec63a9b4d2229374fec747">llvm::ScalarEvolution::computeConstantDifference</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad299b0f4378f644f67168c72c763716f">llvm::ScalarEvolution::getMulExpr</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a7391ca35e3a370a408a9b1967b6a9832">llvm::ScalarEvolution::getNotSCEV</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#aff82c03c1ce8b945170bcb1f0f624c17">llvm::ScalarEvolution::verify</a> and <a href="/web-llvm/docs/api/classes/llvm/scevtraversal/#aa3e492f428e815c1c89e3a5625e2c233">llvm::SCEVTraversal&lt; SV &gt;::visitAll</a>.</p>

</div>
</div>

### print() {#acdbe9e14ed6edbd5b5e3c252585902ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SCEV::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print out the internal representation of this scalar to the specified stream.</p>


<p>This should really only be used for debugging purposes.</p>


<p>Declaration at line 175 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>, definition at line 273 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/scalarevolution-cpp">ScalarEvolution.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#af43000d4dcb7d6d63cb6e36933ed3f6fa2f7a8775a783f7ea3ad24b3f9cb5d949">FlagNSW</a>, <a href="#af43000d4dcb7d6d63cb6e36933ed3f6faafb62cd6afdc004ef6e8a1f6288eb382">FlagNUW</a>, <a href="/web-llvm/docs/api/classes/llvm/loopbase/#a4a75755081e9a3803d2f4ccf6f0cb1f8">llvm::LoopBase&lt; BlockT, LoopT &gt;::getHeader</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#a64f39bbc1130d1a36d3824633863dc51">llvm::SCEVUDivExpr::getLHS</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a99ab4a82c6d7373e2e367986b9527bf0">llvm::SCEVAddRecExpr::getLoop</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a689b72d735546bcbfc4b48a266503085">llvm::SCEVNAryExpr::getNumOperands</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ab6c2fb358d83304761d3848aa70ee5d6">llvm::SCEVCastExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ad99e00da7acb7973ae006f5b53ce04f6">llvm::SCEVNAryExpr::getOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/scevudivexpr/#ad0fdc55c45a39b722f3d990505b55dd7">llvm::SCEVUDivExpr::getRHS</a>, <a href="#ad4f956914bf94bdcd1058badb5bd90e6">getSCEVType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevcastexpr/#ae53e251228db4e03f1134e39b89a80f7">llvm::SCEVCastExpr::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a6429bca8fd0024ceb2d76ccaace43c4e">llvm::SCEVNAryExpr::hasNoSelfWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a71deee7ef49ab5407b7e1aa758b6ec0a">llvm::SCEVNAryExpr::hasNoSignedWrap</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a09cc70290a71475141063b6dff42a5d2">llvm::SCEVNAryExpr::hasNoUnsignedWrap</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#ae77d0f7b81cbde08d5fd75fcf2fcf36b">llvm::SCEVNAryExpr::operands</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a62213d5211c9d944e5ede1f0059a6ae2">llvm::Value::printAsOperand</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea3a80b1a7dda48464be1849ee1fb85868">llvm::scAddExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea222c9c7b5d5e742d5d1238a3256b1ea5">llvm::scAddRecExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eabcb1f797cb330e61a5879fc260aaec5b">llvm::scConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eab6b4550f8ae7180f0e83ebb40a9882ec">llvm::scCouldNotCompute</a>, <a href="#ace7f137cfb19ce8073b78b85f819430c">SCEV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eafd56f054da3d1f9b827ae1003da3a38b">llvm::scMulExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eae996cdd31b3e2df5dbd55ff638d2d456">llvm::scPtrToInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea376414ac1f3ac8cb449fd5167a2db091">llvm::scSequentialUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead05711646a19cb20775cfbc8ef0a8c09">llvm::scSignExtend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea684b8e2484b12d494e82f7053d005754">llvm::scSMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea88dad4534f471d79d0a7a094d809ef55">llvm::scSMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3656bcc84af213cc488acb56c60de22">llvm::scTruncate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eaee62cac87c0dc1f483d783aae69101c4">llvm::scUDivExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ead3d0abdf8125de904320df332dbefedb">llvm::scUMaxExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea0bf2fc9a454ce237fde0906ee24b0acc">llvm::scUMinExpr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea80488550b42b6548ec4d5c7118c7ff1d">llvm::scUnknown</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5ea61df12d6bb21842a8f766c4433c85717">llvm::scVScale</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ad409632178dd00316abd4c35d3e14b5eadd4a8d5cb0d78c9be22d01e1546bafc6">llvm::scZeroExtend</a>.</p>


<p>Referenced by <a href="#a6ae35ec967d69bc1cd21ae482bbdd4a2">dump</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abe2c4ad0936d39f25554aa36e8357d1f">llvm::operator&lt;&lt;</a> and <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#a77b275a78beac200ef1f703d2a5fbb7d">llvm::ScalarEvolution::print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### ExpressionSize {#aaf1d4f0b6eece16e8a081906d13a84f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned short llvm::SCEV::ExpressionSize</td>
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



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="#a102c99af586cd76e0d9ff32ac0e825e0">getExpressionSize</a> and <a href="#ace7f137cfb19ce8073b78b85f819430c">SCEV</a>.</p>

</div>
</div>

### SubclassData {#ade1f1b89affe842dacd20c7f950e99c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned short llvm::SCEV::SubclassData = 0</td>
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

<p>This field is initialized to zero and may be used in subclasses to store miscellaneous information.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/scevnaryexpr/#a7275347a4dce174f4fecd548fd3255dc">llvm::SCEVNAryExpr::getNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/scevaddrecexpr/#a5316a2763777f3670c1606452f4e99d7">llvm::SCEVAddRecExpr::setNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/scevcommutativeexpr/#a46be9fc927263a605e288de91f7c367b">llvm::SCEVCommutativeExpr::setNoWrapFlags</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### FastID {#a717659b1a38d7bb265ec0d47292f68fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FoldingSetNodeIDRef llvm::SCEV::FastID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A reference to an Interned <a href="/web-llvm/docs/api/classes/llvm/foldingsetnodeid">FoldingSetNodeID</a> for this node.</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/scalarevolution">ScalarEvolution</a>'s <a href="/web-llvm/docs/api/namespaces/llvm/#a8e612822d4ba7bb36c9c79582a567108">BumpPtrAllocator</a> holds the data.</p>


<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

</div>
</div>

### SCEVType {#a93693efb507be35c82004a164ab9b4f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SCEVTypes llvm::SCEV::SCEVType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/scalarevolution-h">ScalarEvolution.h</a>.</p>

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
