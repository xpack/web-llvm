---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/lib/lib/ir/diexpressionoptimizer-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `DIExpressionOptimizer.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/binaryformat/dwarf-h">llvm/BinaryFormat/Dwarf.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac0d81675f096becfb4ab791f569f951b">isConstantVal</a> (DIExpression::ExprOperand Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a DW_OP_constu. <a href="#ac0d81675f096becfb4ab791f569f951b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a248a6ca6aad1f955b64acfe45bc6904d">isNeutralElement</a> (uint64_t Op, uint64_t Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if an operation and operand result in a No <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>. <a href="#a248a6ca6aad1f955b64acfe45bc6904d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ececfb2077d72244a3884b39b28256e">foldOperationIfPossible</a> (uint64_t Const1, uint64_t Const2, dwarf::LocationAtom Operator)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to fold <span class="doxyComputerOutput">Const1</span> and <span class="doxyComputerOutput">Const2</span> by applying <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/operator">Operator</a></span> and returning the result, if there is an overflow, return a std::nullopt. <a href="#a4ececfb2077d72244a3884b39b28256e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16e232e62f0937139ce01ff70dbda2b7">operationsAreFoldableAndCommutative</a> (dwarf::LocationAtom Operator1, dwarf::LocationAtom Operator2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the two operations <span class="doxyComputerOutput">Operator1</span> and <span class="doxyComputerOutput">Operator2</span> are commutative and can be folded. <a href="#a16e232e62f0937139ce01ff70dbda2b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf31f517c8657e44b85f80ba0d5f41a6">consumeOneOperator</a> (DIExpressionCursor &amp;Cursor, uint64_t &amp;Loc, const DIExpression::ExprOperand &amp;Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Consume one operator and its operand(s). <a href="#abf31f517c8657e44b85f80ba0d5f41a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86609734aed6acc5528788c073e87ec3">startFromBeginning</a> (uint64_t &amp;Loc, DIExpressionCursor &amp;Cursor, ArrayRef&lt; uint64_t &gt; WorkingOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reset the Cursor to the beginning of the WorkingOps. <a href="#a86609734aed6acc5528788c073e87ec3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade8a5e3b6a082e4cb8bb4202ae7f652a">canonicalizeDwarfOperations</a> (ArrayRef&lt; uint64_t &gt; WorkingOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will canonicalize: <a href="#ade8a5e3b6a082e4cb8bb4202ae7f652a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8949a90af3c69d31f132d6933c4d5914">optimizeDwarfOperations</a> (ArrayRef&lt; uint64_t &gt; WorkingOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function will convert: <a href="#a8949a90af3c69d31f132d6933c4d5914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a067186aa899ad496af6a360ce9515eee">tryFoldNoOpMath</a> (uint64_t Const1, ArrayRef&lt; DIExpression::ExprOperand &gt; Ops, uint64_t &amp;Loc, DIExpressionCursor &amp;Cursor, SmallVectorImpl&lt; uint64_t &gt; &amp;WorkingOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{DW_OP_constu, 0, DW_OP_[plus, minus, shl, shr]} -&gt; {} {DW_OP_constu, 1, DW_OP_[mul, div]} -&gt; {} <a href="#a067186aa899ad496af6a360ce9515eee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa2373cd29671119d8d4c12077c4f9da">tryFoldConstants</a> (uint64_t Const1, ArrayRef&lt; DIExpression::ExprOperand &gt; Ops, uint64_t &amp;Loc, DIExpressionCursor &amp;Cursor, SmallVectorImpl&lt; uint64_t &gt; &amp;WorkingOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{DW_OP_constu, Const1, DW_OP_constu, Const2, DW_OP_[plus, minus, mul, div, shl, shr] -&gt; {DW_OP_constu, Const1 [+, -, *, /, &lt;&lt;, &gt;&gt;] Const2} <a href="#aaa2373cd29671119d8d4c12077c4f9da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a> (uint64_t Const1, ArrayRef&lt; DIExpression::ExprOperand &gt; Ops, uint64_t &amp;Loc, DIExpressionCursor &amp;Cursor, SmallVectorImpl&lt; uint64_t &gt; &amp;WorkingOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{DW_OP_constu, Const1, DW_OP_[plus, mul], DW_OP_constu, Const2, DW_OP_[plus, mul]} -&gt; {DW_OP_constu, Const1 [+, *] Const2, DW_OP_[plus, mul]} <a href="#a789d043cecadfc51338fee7f9683324a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a> (uint64_t Const1, ArrayRef&lt; DIExpression::ExprOperand &gt; Ops, uint64_t &amp;Loc, DIExpressionCursor &amp;Cursor, SmallVectorImpl&lt; uint64_t &gt; &amp;WorkingOps)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>{DW_OP_constu, Const1, DW_OP_[plus, mul], DW_OP_LLVM_arg, Arg1, DW_OP_[plus, mul], DW_OP_constu, Const2, DW_OP_[plus, mul]} -&gt; {DW_OP_constu, Const1 [+, *] Const2, DW_OP_[plus, mul], DW_OP_LLVM_arg, Arg1, DW_OP_[plus, mul]} <a href="#aa3f0516b6857ed87b9547d6f65dd6897">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### canonicalizeDwarfOperations() {#ade8a5e3b6a082e4cb8bb4202ae7f652a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; uint64_t &gt; canonicalizeDwarfOperations (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; WorkingOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function will canonicalize:</p>


<ol class="doxyList" type="1">
<li>DW_OP_plus_uconst to DW_OP_constu &lt;const-val&gt; DW_OP_plus</li>
<li>DW_OP_lit&lt;n&gt; to DW_OP_constu &lt;n&gt;</li>
</ol>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="#abf31f517c8657e44b85f80ba0d5f41a6">consumeOneOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a76ebfb1bca92ec8cf347deae857a2b35">llvm::DIExpressionCursor::peek</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>.</p>

</div>
</div>

### consumeOneOperator() {#abf31f517c8657e44b85f80ba0d5f41a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void consumeOneOperator (<a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; Cursor, uint64_t &amp; Loc, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">DIExpression::ExprOperand</a> &amp; Op)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Consume one operator and its operand(s).</p>

<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a83bd5b46867c5a738a0ad4ac51fc2187">llvm::DIExpressionCursor::consume</a>.</p>


<p>Referenced by <a href="#ade8a5e3b6a082e4cb8bb4202ae7f652a">canonicalizeDwarfOperations</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>, <a href="#a8949a90af3c69d31f132d6933c4d5914">optimizeDwarfOperations</a>, <a href="#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a>, <a href="#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a> and <a href="#aaa2373cd29671119d8d4c12077c4f9da">tryFoldConstants</a>.</p>

</div>
</div>

### foldOperationIfPossible() {#a4ececfb2077d72244a3884b39b28256e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; foldOperationIfPossible (uint64_t Const1, uint64_t Const2, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0c">dwarf::LocationAtom</a> Operator)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to fold <span class="doxyComputerOutput">Const1</span> and <span class="doxyComputerOutput">Const2</span> by applying <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/operator">Operator</a></span> and returning the result, if there is an overflow, return a std::nullopt.</p>

<p>Definition at line 45 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae6b6948bfc113c3aa2f2dc474496fd6e">llvm::SaturatingAdd</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa6c35ac16c3c23e443f27a025d7a1597">llvm::SaturatingMultiply</a>.</p>


<p>Referenced by <a href="#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a>, <a href="#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a> and <a href="#aaa2373cd29671119d8d4c12077c4f9da">tryFoldConstants</a>.</p>

</div>
</div>

### isConstantVal() {#ac0d81675f096becfb4ab791f569f951b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; isConstantVal (<a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">DIExpression::ExprOperand</a> Op)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a DW_OP_constu.</p>

<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>, <a href="#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a>, <a href="#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a> and <a href="#aaa2373cd29671119d8d4c12077c4f9da">tryFoldConstants</a>.</p>

</div>
</div>

### isNeutralElement() {#a248a6ca6aad1f955b64acfe45bc6904d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isNeutralElement (uint64_t Op, uint64_t Val)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if an operation and operand result in a No <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a>.</p>

<p>Definition at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>Referenced by <a href="#a067186aa899ad496af6a360ce9515eee">tryFoldNoOpMath</a>.</p>

</div>
</div>

### operationsAreFoldableAndCommutative() {#a16e232e62f0937139ce01ff70dbda2b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operationsAreFoldableAndCommutative (<a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0c">dwarf::LocationAtom</a> Operator1, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0c">dwarf::LocationAtom</a> Operator2)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if the two operations <span class="doxyComputerOutput">Operator1</span> and <span class="doxyComputerOutput">Operator2</span> are commutative and can be folded.</p>

<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>Referenced by <a href="#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a> and <a href="#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a>.</p>

</div>
</div>

### optimizeDwarfOperations() {#a8949a90af3c69d31f132d6933c4d5914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt; uint64_t &gt; optimizeDwarfOperations (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; WorkingOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function will convert:</p>


<ol class="doxyList" type="1">
<li>DW_OP_constu &lt;const-val&gt; DW_OP_plus to DW_OP_plus_uconst</li>
<li>DW_OP_constu, 0 to DW_OP_lit0</li>
</ol>

<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#aab36927882fbfdcbb860d87fd9c30da8">llvm::ArrayRef&lt; T &gt;::begin</a>, <a href="#abf31f517c8657e44b85f80ba0d5f41a6">consumeOneOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a76ebfb1bca92ec8cf347deae857a2b35">llvm::DIExpressionCursor::peek</a>, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#a01f4fc152711818825bc2fd1d279063d">llvm::DIExpressionCursor::peekNext</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>.</p>

</div>
</div>

### startFromBeginning() {#a86609734aed6acc5528788c073e87ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void startFromBeginning (uint64_t &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; Cursor, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; WorkingOps)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Reset the Cursor to the beginning of the WorkingOps.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor/#ac7dcecb4ce0bf73a49d45fd5da8ec84a">llvm::DIExpressionCursor::assignNewExpr</a>.</p>


<p>Referenced by <a href="#a789d043cecadfc51338fee7f9683324a">tryFoldCommutativeMath</a>, <a href="#aa3f0516b6857ed87b9547d6f65dd6897">tryFoldCommutativeMathWithArgInBetween</a>, <a href="#aaa2373cd29671119d8d4c12077c4f9da">tryFoldConstants</a> and <a href="#a067186aa899ad496af6a360ce9515eee">tryFoldNoOpMath</a>.</p>

</div>
</div>

### tryFoldCommutativeMath() {#a789d043cecadfc51338fee7f9683324a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryFoldCommutativeMath (uint64_t Const1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">DIExpression::ExprOperand</a> &gt; Ops, uint64_t &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; Cursor, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; WorkingOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>{DW_OP_constu, Const1, DW_OP_[plus, mul], DW_OP_constu, Const2, DW_OP_[plus, mul]} -&gt; {DW_OP_constu, Const1 [+, *] Const2, DW_OP_[plus, mul]}</p>

<p>Definition at line 234 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#abf31f517c8657e44b85f80ba0d5f41a6">consumeOneOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="#a4ececfb2077d72244a3884b39b28256e">foldOperationIfPossible</a>, <a href="#ac0d81675f096becfb4ab791f569f951b">isConstantVal</a>, <a href="#a16e232e62f0937139ce01ff70dbda2b7">operationsAreFoldableAndCommutative</a> and <a href="#a86609734aed6acc5528788c073e87ec3">startFromBeginning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>.</p>

</div>
</div>

### tryFoldCommutativeMathWithArgInBetween() {#aa3f0516b6857ed87b9547d6f65dd6897}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryFoldCommutativeMathWithArgInBetween (uint64_t Const1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">DIExpression::ExprOperand</a> &gt; Ops, uint64_t &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; Cursor, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; WorkingOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>{DW_OP_constu, Const1, DW_OP_[plus, mul], DW_OP_LLVM_arg, Arg1, DW_OP_[plus, mul], DW_OP_constu, Const2, DW_OP_[plus, mul]} -&gt; {DW_OP_constu, Const1 [+, *] Const2, DW_OP_[plus, mul], DW_OP_LLVM_arg, Arg1, DW_OP_[plus, mul]}</p>

<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#abf31f517c8657e44b85f80ba0d5f41a6">consumeOneOperator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="#a4ececfb2077d72244a3884b39b28256e">foldOperationIfPossible</a>, <a href="#ac0d81675f096becfb4ab791f569f951b">isConstantVal</a>, <a href="#a16e232e62f0937139ce01ff70dbda2b7">operationsAreFoldableAndCommutative</a> and <a href="#a86609734aed6acc5528788c073e87ec3">startFromBeginning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>.</p>

</div>
</div>

### tryFoldConstants() {#aaa2373cd29671119d8d4c12077c4f9da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryFoldConstants (uint64_t Const1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">DIExpression::ExprOperand</a> &gt; Ops, uint64_t &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; Cursor, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; WorkingOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>{DW_OP_constu, Const1, DW_OP_constu, Const2, DW_OP_[plus, minus, mul, div, shl, shr] -&gt; {DW_OP_constu, Const1 [+, -, *, /, &lt;&lt;, &gt;&gt;] Const2}</p>

<p>Definition at line 209 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="#abf31f517c8657e44b85f80ba0d5f41a6">consumeOneOperator</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="#a4ececfb2077d72244a3884b39b28256e">foldOperationIfPossible</a>, <a href="#ac0d81675f096becfb4ab791f569f951b">isConstantVal</a> and <a href="#a86609734aed6acc5528788c073e87ec3">startFromBeginning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>.</p>

</div>
</div>

### tryFoldNoOpMath() {#a067186aa899ad496af6a360ce9515eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool tryFoldNoOpMath (uint64_t Const1, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/diexpression/exproperand">DIExpression::ExprOperand</a> &gt; Ops, uint64_t &amp; Loc, <a href="/web-llvm/docs/api/classes/llvm/diexpressioncursor">DIExpressionCursor</a> &amp; Cursor, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; WorkingOps)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>{DW_OP_constu, 0, DW_OP_[plus, minus, shl, shr]} -&gt; {} {DW_OP_constu, 1, DW_OP_[mul, div]} -&gt; {}</p>

<p>Definition at line 193 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/diexpressionoptimizer-cpp">DIExpressionOptimizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a926d7ce2143863b7a2afda0fca4d2b65">AbstractManglingParser&lt; Derived, Alloc &gt;::Ops</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a8a045d250952c0867382a9840ee18fdf">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::begin</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a563ffc2ff61c499b3be2e00100cb72fa">llvm::SmallVectorImpl&lt; T &gt;::erase</a>, <a href="#a248a6ca6aad1f955b64acfe45bc6904d">isNeutralElement</a> and <a href="#a86609734aed6acc5528788c073e87ec3">startFromBeginning</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/diexpression/#a804421879fbddb541d8393ec3c3730ee">llvm::DIExpression::foldConstantMath</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
