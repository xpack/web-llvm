---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/diexpression/exproperand
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `ExprOperand` Class

<p>A lightweight wrapper around an expression operand. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::DIExpression::ExprOperand { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">llvm/IR/DebugInfoMetadata.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d356a7e21fe4e39db424351e510a337">ExprOperand</a> ()=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f6836977bbf5920c6eb028215a617da">ExprOperand</a> (const uint64_t *Op)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ba55e317d0b8844dc5c555df8835d2">get</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf88225d202669df1d9ccd94fa650f0a">getOp</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the operand code. <a href="#abf88225d202669df1d9ccd94fa650f0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a867205d897f74c5b134d6e74b94202e9">getArg</a> (unsigned I) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get an argument to the operand. <a href="#a867205d897f74c5b134d6e74b94202e9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a903b169cf27aead7914de5db2a15ef66">getNumArgs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77b3f2a2579864d7872fb273538b9192">getSize</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the size of the operand. <a href="#a77b3f2a2579864d7872fb273538b9192">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17d99fbdbe6e1ee18d5120b40b1e513">appendToVector</a> (SmallVectorImpl&lt; uint64_t &gt; &amp;V) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append the elements of this operand to <span class="doxyComputerOutput">V</span>. <a href="#ae17d99fbdbe6e1ee18d5120b40b1e513">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e50719598a0e5fa08e672a2ac46ba56">Op</a> = nullptr</td>
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

<p>A lightweight wrapper around an expression operand.</p>


<p>TODO: Store arguments directly and change <em><a href="/web-llvm/docs/api/classes/llvm/diexpression">DIExpression</a></em> to store a range of these.</p>


<p>Definition at line 2820 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ExprOperand() {#a3d356a7e21fe4e39db424351e510a337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIExpression::ExprOperand::ExprOperand ()</td>
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



<p>Definition at line 2824 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

### ExprOperand() {#a7f6836977bbf5920c6eb028215a617da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DIExpression::ExprOperand::ExprOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> uint64_t * Op)</td>
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



<p>Definition at line 2825 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendToVector() {#ae17d99fbdbe6e1ee18d5120b40b1e513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::DIExpression::ExprOperand::appendToVector (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; uint64_t &gt; &amp; V)</td>
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

<p>Append the elements of this operand to <span class="doxyComputerOutput">V</span>.</p>

<p>Definition at line 2845 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>References <a href="#ad6ba55e317d0b8844dc5c555df8835d2">get</a> and <a href="#a77b3f2a2579864d7872fb273538b9192">getSize</a>.</p>

</div>
</div>

### get() {#ad6ba55e317d0b8844dc5c555df8835d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t * llvm::DIExpression::ExprOperand::get ()</td>
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



<p>Definition at line 2827 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#ae17d99fbdbe6e1ee18d5120b40b1e513">appendToVector</a>.</p>

</div>
</div>

### getArg() {#a867205d897f74c5b134d6e74b94202e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DIExpression::ExprOperand::getArg (unsigned I)</td>
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

<p>Get an argument to the operand.</p>


<p>Never returns the operand itself.</p>


<p>Definition at line 2835 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getNumArgs() {#a903b169cf27aead7914de5db2a15ef66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::DIExpression::ExprOperand::getNumArgs ()</td>
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



<p>Definition at line 2837 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Reference <a href="#a77b3f2a2579864d7872fb273538b9192">getSize</a>.</p>

</div>
</div>

### getOp() {#abf88225d202669df1d9ccd94fa650f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::DIExpression::ExprOperand::getOp ()</td>
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

<p>Get the operand code.</p>

<p>Definition at line 2830 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>


<p>Referenced by <a href="#a77b3f2a2579864d7872fb273538b9192">getSize</a>.</p>

</div>
</div>

### getSize() {#a77b3f2a2579864d7872fb273538b9192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned DIExpression::ExprOperand::getSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the size of the operand.</p>


<p>Return the number of elements in the operand (1 + args).</p>


<p>Declaration at line 2842 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>, definition at line 1402 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cadb24b626a6ff07a122e0df22e9857a3d">llvm::dwarf::DW_OP_LLVM_arg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0caee0952c3cd8bf8106bbfa0a323c1ca82">llvm::dwarf::DW_OP_LLVM_convert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca0c7ecbb9cc8d5fb23652e00de7b288a0">llvm::dwarf::DW_OP_LLVM_entry_value</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cafa8715d4f64791c3f0b479ececa39d34">llvm::dwarf::DW_OP_LLVM_extract_bits_sext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca3d02f9a2d8b9066b6c6ef1a39018de7f">llvm::dwarf::DW_OP_LLVM_extract_bits_zext</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0cac09e4cb866e5aa9bc0480359be9e7953">llvm::dwarf::DW_OP_LLVM_fragment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf/#a78e9cb1527edb3cc1d1ee577257b5f0ca989f426170b8ef321ffeb4838b4c590f">llvm::dwarf::DW_OP_LLVM_tag_offset</a> and <a href="#abf88225d202669df1d9ccd94fa650f0a">getOp</a>.</p>


<p>Referenced by <a href="#ae17d99fbdbe6e1ee18d5120b40b1e513">appendToVector</a> and <a href="#a903b169cf27aead7914de5db2a15ef66">getNumArgs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Op {#a5e50719598a0e5fa08e672a2ac46ba56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint64_t* llvm::DIExpression::ExprOperand::Op = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2821 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/debuginfometadata-h">DebugInfoMetadata.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/debuginfometadata-cpp">DebugInfoMetadata.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
