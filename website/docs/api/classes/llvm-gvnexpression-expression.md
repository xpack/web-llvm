---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gvnexpression/expression
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Expression` Class Reference



## Declaration

<div class="doxyDeclaration">
class llvm::GVNExpression::Expression { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">llvm/Transforms/Scalar/GVNExpression.h</a>"
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression">BasicExpression</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression">ConstantExpression</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvnexpression/deadexpression">DeadExpression</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvnexpression/unknownexpression">UnknownExpression</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvnexpression/variableexpression">VariableExpression</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a787a246bfbfbb41fc10ebde0f4570b5a">Expression</a> (ExpressionType ET=ET_Base, unsigned O=~2U)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb2eb01edde3acfcc968dfdfeca355b">Expression</a> (const Expression &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a406740c556bd24343673f20682fa7eac">~Expression</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">Expression</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a2781405591e74ce6b443ce866756c5">operator=</a> (const Expression &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ab1b52450580df6d24a7645ccaccf64">operator!=</a> (const Expression &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1870f4f8e78c43659365a016f3a511b8">operator==</a> (const Expression &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7dd92c7387bd995225b8b3c45f3ca86">getComputedHash</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1b27c041170876afe8587179b5b6a47">equals</a> (const Expression &amp;Other) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a512bcf6cf0049817864392b4d57bfd6b">exactlyEquals</a> (const Expression &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82379348cbf959795efbb61dc1524b7b">getOpcode</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5e6b8ef7b13729502e65d4eb0dc3d28">setOpcode</a> (unsigned opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/gvnexpression/#a9cd4cc3194b27369463957a5c3b5a472">ExpressionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ca04efeb44d56779b472167e362c507">getExpressionType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a245a3504951e225a154367323265bc32">getHashValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab15438d68a4be5111a6a81a4956371a6">printInternal</a> (raw_ostream &amp;OS, bool PrintEType) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8d1be38bee19b5aea33c961958c3468">print</a> (raw_ostream &amp;OS) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9877ce60232c11ec7ef6030cf99a9655">dump</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/gvnexpression/#a9cd4cc3194b27369463957a5c3b5a472">ExpressionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad29f30c3be06121ccf07c5990d165483">EType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434b1f2f2f502079ded965f2e554bdb7">Opcode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/hash-code">hash_code</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7be9cf83561a63ffe62aff33cb69439b">HashVal</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ae8c54efc6a512337da3fb6c05634e">getEmptyKey</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96b79ea4a9dce380cd75c8132396b267">getTombstoneKey</a> ()</td>
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


<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Expression() {#a787a246bfbfbb41fc10ebde0f4570b5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GVNExpression::Expression::Expression (<a href="/web-llvm/docs/api/namespaces/llvm/gvnexpression/#a9cd4cc3194b27369463957a5c3b5a472">ExpressionType</a> ET=<a href="/web-llvm/docs/api/namespaces/llvm/gvnexpression/#a9cd4cc3194b27369463957a5c3b5a472a2c9d00f4e139cb1f9845eec79837154a">ET_Base</a>, unsigned O=~2U)</td>
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



<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/gvnexpression/#a9cd4cc3194b27369463957a5c3b5a472a2c9d00f4e139cb1f9845eec79837154a">llvm::GVNExpression::ET_Base</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#a7e12bfe1fb241e896e6cbf2c523b273b">llvm::GVNExpression::BasicExpression::BasicExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#acf2a0e609887159c90ac986045110730">llvm::GVNExpression::BasicExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression/#a13fb923b31ce5d0db5b468ca26aab619">llvm::GVNExpression::ConstantExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/deadexpression/#a3f41d75568be65b2db9b94f357f749e1">llvm::GVNExpression::DeadExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/unknownexpression/#a69bbd21e70d99581dd6d6c4ee35b68df">llvm::GVNExpression::UnknownExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/variableexpression/#aa02f080d18e281db0c55284f04644aba">llvm::GVNExpression::VariableExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression/#a7b909d796f99d018321b330f5553b49a">llvm::GVNExpression::ConstantExpression::ConstantExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression/#aeeeaafa4af8306e2ba4c15f40622f492">llvm::GVNExpression::ConstantExpression::ConstantExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/deadexpression/#a86bda13da71677d87459ade91f7de5f5">llvm::GVNExpression::DeadExpression::DeadExpression</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#a6b9dd1383508ae071869d0760a1dd539">llvm::GVNExpression::BasicExpression::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression/#a8cce277947f01298e72c3b2a04cdf206">llvm::GVNExpression::ConstantExpression::equals</a>, <a href="#ad1b27c041170876afe8587179b5b6a47">equals</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/unknownexpression/#a41bc87bd9ec1cdea283cb0dc12de8470">llvm::GVNExpression::UnknownExpression::equals</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/variableexpression/#a4923f6e0c6133b16dceb8d5e9186748f">llvm::GVNExpression::VariableExpression::equals</a>, <a href="#a512bcf6cf0049817864392b4d57bfd6b">exactlyEquals</a>, <a href="#a5fb2eb01edde3acfcc968dfdfeca355b">Expression</a>, <a href="#a7ab1b52450580df6d24a7645ccaccf64">operator!=</a>, <a href="#a4a2781405591e74ce6b443ce866756c5">operator=</a>, <a href="#a1870f4f8e78c43659365a016f3a511b8">operator==</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/unknownexpression/#a96f37480e57082c247a85ef668533337">llvm::GVNExpression::UnknownExpression::UnknownExpression</a> and <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/variableexpression/#ae3edc06c0447e03cb16b487bb21920e8">llvm::GVNExpression::VariableExpression::VariableExpression</a>.</p>

</div>
</div>

### Expression() {#a5fb2eb01edde3acfcc968dfdfeca355b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GVNExpression::Expression::Expression (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">Expression</a> &amp;)</td>
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



<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Reference <a href="#a787a246bfbfbb41fc10ebde0f4570b5a">Expression</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Expression() {#a406740c556bd24343673f20682fa7eac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GVNExpression::Expression::~Expression ()</td>
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



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator!=() {#a7ab1b52450580df6d24a7645ccaccf64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GVNExpression::Expression::operator!= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">Expression</a> &amp; Other)</td>
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



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>References <a href="#a787a246bfbfbb41fc10ebde0f4570b5a">Expression</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

### operator=() {#a4a2781405591e74ce6b443ce866756c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expression &amp; llvm::GVNExpression::Expression::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">Expression</a> &amp;)</td>
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



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Reference <a href="#a787a246bfbfbb41fc10ebde0f4570b5a">Expression</a>.</p>

</div>
</div>

### operator==() {#a1870f4f8e78c43659365a016f3a511b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GVNExpression::Expression::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">Expression</a> &amp; Other)</td>
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



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>References <a href="#ad1b27c041170876afe8587179b5b6a47">equals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gvnexpression/#a9cd4cc3194b27369463957a5c3b5a472a505b460274ff339700845292f5114a3a">llvm::GVNExpression::ET_Load</a>, <a href="/web-llvm/docs/api/namespaces/llvm/gvnexpression/#a9cd4cc3194b27369463957a5c3b5a472a2a5400a48ae1ead2fc8b9e73a90c680c">llvm::GVNExpression::ET_Store</a>, <a href="#a787a246bfbfbb41fc10ebde0f4570b5a">Expression</a>, <a href="#a54ae8c54efc6a512337da3fb6c05634e">getEmptyKey</a>, <a href="#a8ca04efeb44d56779b472167e362c507">getExpressionType</a>, <a href="#a82379348cbf959795efbb61dc1524b7b">getOpcode</a>, <a href="#a96b79ea4a9dce380cd75c8132396b267">getTombstoneKey</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dump() {#a9877ce60232c11ec7ef6030cf99a9655}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVM_DUMP_METHOD void llvm::GVNExpression::Expression::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>, definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/compiler-h/#aa863693eef567397d9c292da5bf22d34">LLVM_DUMP_METHOD</a> and <a href="#af8d1be38bee19b5aea33c961958c3468">print</a>.</p>

</div>
</div>

### equals() {#ad1b27c041170876afe8587179b5b6a47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GVNExpression::Expression::equals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">Expression</a> &amp; Other)</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>References <a href="#a787a246bfbfbb41fc10ebde0f4570b5a">Expression</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="#a512bcf6cf0049817864392b4d57bfd6b">exactlyEquals</a> and <a href="#a1870f4f8e78c43659365a016f3a511b8">operator==</a>.</p>

</div>
</div>

### exactlyEquals() {#a512bcf6cf0049817864392b4d57bfd6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool llvm::GVNExpression::Expression::exactlyEquals (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/expression">Expression</a> &amp; Other)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>References <a href="#ad1b27c041170876afe8587179b5b6a47">equals</a>, <a href="#a787a246bfbfbb41fc10ebde0f4570b5a">Expression</a>, <a href="#a8ca04efeb44d56779b472167e362c507">getExpressionType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/callexpression/#af7aea09832796e05d0055f3d4e714954">llvm::GVNExpression::CallExpression::exactlyEquals</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/loadexpression/#af231723048acfd77bf11fdabcebb6fcf">llvm::GVNExpression::LoadExpression::exactlyEquals</a> and <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/storeexpression/#a27ed3a5ef040e79335b79c3d10033d1d">llvm::GVNExpression::StoreExpression::exactlyEquals</a>.</p>

</div>
</div>

### getComputedHash() {#ab7dd92c7387bd995225b8b3c45f3ca86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code llvm::GVNExpression::Expression::getComputedHash ()</td>
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



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Reference <a href="#a245a3504951e225a154367323265bc32">getHashValue</a>.</p>

</div>
</div>

### getExpressionType() {#a8ca04efeb44d56779b472167e362c507}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExpressionType llvm::GVNExpression::Expression::getExpressionType ()</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/aggregatevalueexpression/#a3b4542c5a1f8b4061ff8c277a2405e9f">llvm::GVNExpression::AggregateValueExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#acf2a0e609887159c90ac986045110730">llvm::GVNExpression::BasicExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/callexpression/#a937e1e6b46daa9fb304b0b363a4ad8d0">llvm::GVNExpression::CallExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression/#a13fb923b31ce5d0db5b468ca26aab619">llvm::GVNExpression::ConstantExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/loadexpression/#a074a48e1d6b4facb0716e256ffb1292b">llvm::GVNExpression::LoadExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/memoryexpression/#a3d628f23cb0e5c1c41982a8157b5af16">llvm::GVNExpression::MemoryExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/phiexpression/#ae10ddd978bb9a51961351d4f9283a1c8">llvm::GVNExpression::PHIExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/storeexpression/#a8fdd3629def6b796f4c4d95dcaf82238">llvm::GVNExpression::StoreExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/unknownexpression/#a69bbd21e70d99581dd6d6c4ee35b68df">llvm::GVNExpression::UnknownExpression::classof</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/variableexpression/#aa02f080d18e281db0c55284f04644aba">llvm::GVNExpression::VariableExpression::classof</a>, <a href="#a512bcf6cf0049817864392b4d57bfd6b">exactlyEquals</a>, <a href="#a1870f4f8e78c43659365a016f3a511b8">operator==</a> and <a href="#ab15438d68a4be5111a6a81a4956371a6">printInternal</a>.</p>

</div>
</div>

### getHashValue() {#a245a3504951e225a154367323265bc32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual hash_code llvm::GVNExpression::Expression::getHashValue ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Reference <a href="#a82379348cbf959795efbb61dc1524b7b">getOpcode</a>.</p>


<p>Referenced by <a href="#ab7dd92c7387bd995225b8b3c45f3ca86">getComputedHash</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#a9290bc82244d3f98e3cbfd5e3b7bfe87">llvm::GVNExpression::BasicExpression::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression/#a07ae666503a3516fcaff399e3891a90b">llvm::GVNExpression::ConstantExpression::getHashValue</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/unknownexpression/#a09339e2dbdfbab608aff8731f420b687">llvm::GVNExpression::UnknownExpression::getHashValue</a> and <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/variableexpression/#afddb79448decb56416883834c1e55b93">llvm::GVNExpression::VariableExpression::getHashValue</a>.</p>

</div>
</div>

### getOpcode() {#a82379348cbf959795efbb61dc1524b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GVNExpression::Expression::getOpcode ()</td>
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



<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#a6b9dd1383508ae071869d0760a1dd539">llvm::GVNExpression::BasicExpression::equals</a>, <a href="#a245a3504951e225a154367323265bc32">getHashValue</a>, <a href="#a1870f4f8e78c43659365a016f3a511b8">operator==</a> and <a href="#ab15438d68a4be5111a6a81a4956371a6">printInternal</a>.</p>

</div>
</div>

### print() {#af8d1be38bee19b5aea33c961958c3468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GVNExpression::Expression::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS)</td>
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



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Reference <a href="#ab15438d68a4be5111a6a81a4956371a6">printInternal</a>.</p>


<p>Referenced by <a href="#a9877ce60232c11ec7ef6030cf99a9655">dump</a>.</p>

</div>
</div>

### printInternal() {#ab15438d68a4be5111a6a81a4956371a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void llvm::GVNExpression::Expression::printInternal (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, bool PrintEType)</td>
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



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>References <a href="#a8ca04efeb44d56779b472167e362c507">getExpressionType</a> and <a href="#a82379348cbf959795efbb61dc1524b7b">getOpcode</a>.</p>


<p>Referenced by <a href="#af8d1be38bee19b5aea33c961958c3468">print</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/basicexpression/#af56a40df31c33706815723c1ce842ca0">llvm::GVNExpression::BasicExpression::printInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/constantexpression/#a0d50821bc399da9844b58c02d279b9ca">llvm::GVNExpression::ConstantExpression::printInternal</a>, <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/unknownexpression/#acebeba87c37af7365a7f129c9711ec13">llvm::GVNExpression::UnknownExpression::printInternal</a> and <a href="/web-llvm/docs/api/classes/llvm/gvnexpression/variableexpression/#af3401221f0c9eb5dc68fa881537d4cbe">llvm::GVNExpression::VariableExpression::printInternal</a>.</p>

</div>
</div>

### setOpcode() {#ae5e6b8ef7b13729502e65d4eb0dc3d28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::GVNExpression::Expression::setOpcode (unsigned opcode)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-gvnsink-cpp-/instructionuseexpr/#ad9b0ad642953907e85b91f72e26ba37a">anonymous{GVNSink.cpp}::InstructionUseExpr::InstructionUseExpr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### EType {#ad29f30c3be06121ccf07c5990d165483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ExpressionType llvm::GVNExpression::Expression::EType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>

</div>
</div>

### HashVal {#a7be9cf83561a63ffe62aff33cb69439b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">hash_code llvm::GVNExpression::Expression::HashVal = 0</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel mutable">mutable</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>

</div>
</div>

### Opcode {#a434b1f2f2f502079ded965f2e554bdb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GVNExpression::Expression::Opcode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getEmptyKey() {#a54ae8c54efc6a512337da3fb6c05634e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GVNExpression::Expression::getEmptyKey ()</td>
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



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Referenced by <a href="#a1870f4f8e78c43659365a016f3a511b8">operator==</a>.</p>

</div>
</div>

### getTombstoneKey() {#a96b79ea4a9dce380cd75c8132396b267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GVNExpression::Expression::getTombstoneKey ()</td>
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



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a>.</p>


<p>Referenced by <a href="#a1870f4f8e78c43659365a016f3a511b8">operator==</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/transforms/include/llvm/transforms/scalar/gvnexpression-h">GVNExpression.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvnsink-cpp">GVNSink.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
