---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/gepoperator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `GEPOperator` Class



## Declaration

<div class="doxyDeclaration">
class llvm::GEPOperator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">llvm/IR/Operator.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/concreteoperator">ConcreteOperator&lt;SuperClass, Opc&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A helper template for defining operators for individual opcodes. <a href="/web-llvm/docs/api/classes/llvm/concreteoperator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd292d18cf364c2b74ce2199dd88754">DECLARE_TRANSPARENT_OPERAND_ACCESSORS</a> (Value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Transparently provide more efficient getOperand methods. <a href="#a6bd292d18cf364c2b74ce2199dd88754">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags">GEPNoWrapFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f19d28f31c79215e0e0190115b0373d">getNoWrapFlags</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3783a9756e9b9a1fe124622d27522713">isInBounds</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Test whether this is an inbounds GEP, as defined by LangRef.html. <a href="#a3783a9756e9b9a1fe124622d27522713">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02a7ce64ac78b2de107d6726b64b71a0">hasNoUnsignedSignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5efdc1f8478ba644e2413b9c143dd46c">hasNoUnsignedWrap</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/classes/llvm/constantrange">ConstantRange</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45292ea2819c68751208f629216d7248">getInRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the offset of the index with an inrange attachment, or std::nullopt if none. <a href="#a45292ea2819c68751208f629216d7248">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d4f83fc113ed4b161e4e89743efb1e4">idx_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a355becb10a5cb4996c4e543600db7d94">idx_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a630f2e601df642f71613ccf6d7ea889c">idx_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a165208bc52bf227e27432d2ca5c59943">idx_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a0126e6f10273e8db07142833979a0c8f">op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad281f19120240f5f387f716057cfbd8">indices</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/user/#a670a0fc44293ba68935a3cff3b871893">const_op_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe215e8a1517f7235e67fb9fad636211">indices</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9eed94bc40cf3c61f97c72de0b1190d8">getPointerOperand</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23458a8fae63673c8029c260ba89642b">getPointerOperand</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e0076afb4800dd00a72e0a4171f667">getPointerOperandType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method to return the pointer operand as a <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a>. <a href="#a43e0076afb4800dd00a72e0a4171f667">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58518ce0fd3570c7bfce00aa2df58e42">getSourceElementType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58ca1bd4fb202cbff3bf5930e586509d">getResultElementType</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6bfe9ceb9bb512348d3602935a747f2">getPointerAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Method to return the address space of the pointer operand. <a href="#af6bfe9ceb9bb512348d3602935a747f2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f7ebb9a6f2819acad2ea4085b8ee4d">getNumIndices</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52b529f03851cdc98af7aa85382ee93">hasIndices</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a608bf9c26922fc798bc8bd85601ce94d">hasAllZeroIndices</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all of the indices of this GEP are zeros. <a href="#a608bf9c26922fc798bc8bd85601ce94d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d79f790f6bd3fa3234d4137979215b">hasAllConstantIndices</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if all of the indices of this GEP are constant integers. <a href="#aa4d79f790f6bd3fa3234d4137979215b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57286aaebfc778a6c1215125ed8493ef">countNonConstantIndices</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/align">Align</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9df6f2ecd1b45e0f481b4f0c297a367">getMaxPreservedAlignment</a> (const DataLayout &amp;DL) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Compute the maximum alignment that this GEP is garranteed to preserve. <a href="#ad9df6f2ecd1b45e0f481b4f0c297a367">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c00e7e76ef5e98c6ffec8d31f63970a">accumulateConstantOffset</a> (const DataLayout &amp;DL, APInt &amp;Offset, function_ref&lt; bool(Value &amp;, APInt &amp;)&gt; ExternalAnalysis=nullptr) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Accumulate the constant address offset of this GEP if possible. <a href="#a5c00e7e76ef5e98c6ffec8d31f63970a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b02b875049489fedf9c500d2424fa3">collectOffset</a> (const DataLayout &amp;DL, unsigned BitWidth, SmallMapVector&lt; Value *, APInt, 4 &gt; &amp;VariableOffsets, APInt &amp;ConstantOffset) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Collect the offset of this GEP as a map of Values to their associated <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> multipliers, as well as a total <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Offset. <a href="#a19b02b875049489fedf9c500d2424fa3">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef50f11f07a98789828558ad39240ec">getPointerOperandIndex</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ef0843f4b374aae185be929453c9de5">accumulateConstantOffset</a> (Type *SourceType, ArrayRef&lt; const Value * &gt; Index, const DataLayout &amp;DL, APInt &amp;Offset, function_ref&lt; bool(Value &amp;, APInt &amp;)&gt; ExternalAnalysis=nullptr)</td>
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


<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### accumulateConstantOffset() {#a5c00e7e76ef5e98c6ffec8d31f63970a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::accumulateConstantOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;)&gt; ExternalAnalysis=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Accumulate the constant address offset of this GEP if possible.</p>


<p>This routine accepts an <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> into which it will try to accumulate the constant offset of this GEP.</p>


<p>If <span class="doxyComputerOutput">ExternalAnalysis</span> is provided it will be used to calculate a offset when a operand of GEP is not constant. For example, for a value <span class="doxyComputerOutput">ExternalAnalysis</span> might try to calculate a lower bound. If <span class="doxyComputerOutput">ExternalAnalysis</span> is successful, it should return true.</p>


<p>If the <span class="doxyComputerOutput">ExternalAnalysis</span> returns false or the value returned by <span class="doxyComputerOutput">ExternalAnalysis</span> results in a overflow/underflow, this routine returns false and the value of the offset <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> is undefined (it is <em>not</em> preserved!).</p>


<p>The <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> passed into this routine must be at exactly as wide as the IntPtr type for the address space of the base GEP pointer.</p>


<p>Declaration at line 543 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 113 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>References <a href="#a5c00e7e76ef5e98c6ffec8d31f63970a">accumulateConstantOffset</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a02981de53fb6ffd384d39addc4d25f37">llvm::drop_begin</a>, <a href="#af6bfe9ceb9bb512348d3602935a747f2">getPointerAddressSpace</a>, <a href="#a58518ce0fd3570c7bfce00aa2df58e42">getSourceElementType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a> and <a href="/web-llvm/docs/api/classes/llvm/user/#ae9c77e5d2298423b0699e93642d17f0c">llvm::User::operand_values</a>.</p>


<p>Referenced by <a href="#a5c00e7e76ef5e98c6ffec8d31f63970a">accumulateConstantOffset</a>.</p>

</div>
</div>

### collectOffset() {#a19b02b875049489fedf9c500d2424fa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::collectOffset (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, unsigned BitWidth, <a href="/web-llvm/docs/api/structs/llvm/smallmapvector">SmallMapVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a>, 4 &gt; &amp; VariableOffsets, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; ConstantOffset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Collect the offset of this GEP as a map of Values to their associated <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> multipliers, as well as a total <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> Offset.</p>

<p>Declaration at line 554 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 208 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43c6ebb4fd35ebd815d66a2df4eed0b9">llvm::gep_type_end</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="#af6bfe9ceb9bb512348d3602935a747f2">getPointerAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/mapvector/#abb6ea6cbdf19ab64bf0c8f65b2e6e8ce">llvm::MapVector&lt; KeyT, ValueT, MapType, VectorType &gt;::insert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a49cd5939942c6665aba4cae8c220dff1">llvm::APInt::isZero</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a>.</p>

</div>
</div>

### countNonConstantIndices() {#a57286aaebfc778a6c1215125ed8493ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GEPOperator::countNonConstantIndices ()</td>
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



<p>Definition at line 517 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac214df91cdc242f4710ea5a93939c678">llvm::count_if</a>, <a href="#aad281f19120240f5f387f716057cfbd8">indices</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/localizer-cpp/#a428090a453f41a199ef67fc3f2179fbc">use</a>.</p>

</div>
</div>

### DECLARE\_TRANSPARENT\_OPERAND\_ACCESSORS() {#a6bd292d18cf364c2b74ce2199dd88754}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::GEPOperator::DECLARE_TRANSPARENT_OPERAND_ACCESSORS (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Transparently provide more efficient getOperand methods.</p>

<p>Definition at line 428 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

### getInRange() {#a45292ea2819c68751208f629216d7248}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; ConstantRange &gt; llvm::GEPOperator::getInRange ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the offset of the index with an inrange attachment, or std::nullopt if none.</p>

<p>Declaration at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 82 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>.</p>

</div>
</div>

### getMaxPreservedAlignment() {#ad9df6f2ecd1b45e0f481b4f0c297a367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Align llvm::GEPOperator::getMaxPreservedAlignment (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Compute the maximum alignment that this GEP is garranteed to preserve.</p>

<p>Declaration at line 524 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac828b9b52935f87659a4adf237f820a3">llvm::gep_type_begin</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a43c6ebb4fd35ebd815d66a2df4eed0b9">llvm::gep_type_end</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/constantint/#ac09a21c371a9c535cbc13e8f82503aec">llvm::ConstantInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a089e46429cea4cfcd2ba23a6fc6aa676">llvm::Value::MaximumAlignment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59f98bbb1f440db8d5db1c8b5bd819f6">llvm::MinAlign</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>

</div>
</div>

### getNoWrapFlags() {#a9f19d28f31c79215e0e0190115b0373d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GEPNoWrapFlags llvm::GEPOperator::getNoWrapFlags ()</td>
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



<p>Definition at line 430 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a4a37d9e499f35c62e13457d1755eebf0">llvm::GEPNoWrapFlags::fromRaw</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a21e38886795ed32ec28d4eb5dc92b6a4">llvm::Value::SubclassOptionalData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instructioncombining-cpp/#afef6fefdb447008608fc826b31a49d28">getMergedGEPNoWrapFlags</a>, <a href="#a02a7ce64ac78b2de107d6726b64b71a0">hasNoUnsignedSignedWrap</a>, <a href="#a5efdc1f8478ba644e2413b9c143dd46c">hasNoUnsignedWrap</a>, <a href="#a3783a9756e9b9a1fe124622d27522713">isInBounds</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueinstructiongetelementpointer/#gaaabb47a8c98e8ec1c796b581928b4a98">LLVMGEPGetNoWrapFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a884253dce055eb76863ec81c061aef33">llvm::InstCombinerImpl::OptimizePointerDifference</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#abce78109fa7acac1ae7aa1b4ee1ce07f">transformToIndexedCompare</a>.</p>

</div>
</div>

### getNumIndices() {#a43f7ebb9a6f2819acad2ea4085b8ee4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GEPOperator::getNumIndices ()</td>
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



<p>Definition at line 485 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>

</div>
</div>

### getPointerAddressSpace() {#af6bfe9ceb9bb512348d3602935a747f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GEPOperator::getPointerAddressSpace ()</td>
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

<p>Method to return the address space of the pointer operand.</p>

<p>Definition at line 481 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5ab2d0b0f0b8ceec3b907184e7567197">llvm::Type::getPointerAddressSpace</a> and <a href="#a43e0076afb4800dd00a72e0a4171f667">getPointerOperandType</a>.</p>


<p>Referenced by <a href="#a5c00e7e76ef5e98c6ffec8d31f63970a">accumulateConstantOffset</a> and <a href="#a19b02b875049489fedf9c500d2424fa3">collectOffset</a>.</p>

</div>
</div>

### getPointerOperand() {#a9eed94bc40cf3c61f97c72de0b1190d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::GEPOperator::getPointerOperand ()</td>
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



<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a> and <a href="#a43e0076afb4800dd00a72e0a4171f667">getPointerOperandType</a>.</p>

</div>
</div>

### getPointerOperand() {#a23458a8fae63673c8029c260ba89642b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value * llvm::GEPOperator::getPointerOperand ()</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#aa0a2cb1582d1cec317bd205085469ca1">llvm::User::getOperand</a>.</p>

</div>
</div>

### getPointerOperandType() {#a43e0076afb4800dd00a72e0a4171f667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::GEPOperator::getPointerOperandType ()</td>
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

<p>Method to return the pointer operand as a <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a>.</p>

<p>Definition at line 473 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="#a9eed94bc40cf3c61f97c72de0b1190d8">getPointerOperand</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#af6bfe9ceb9bb512348d3602935a747f2">getPointerAddressSpace</a>.</p>

</div>
</div>

### getResultElementType() {#a58ca1bd4fb202cbff3bf5930e586509d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::GEPOperator::getResultElementType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 478 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### getSourceElementType() {#a58518ce0fd3570c7bfce00aa2df58e42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::GEPOperator::getSourceElementType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 477 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>


<p>Referenced by <a href="#a5c00e7e76ef5e98c6ffec8d31f63970a">accumulateConstantOffset</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>.</p>

</div>
</div>

### hasAllConstantIndices() {#aa4d79f790f6bd3fa3234d4137979215b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::hasAllConstantIndices ()</td>
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

<p>Return true if all of the indices of this GEP are constant integers.</p>


<p>If so, the result pointer and the first operand have a constant offset between them.</p>


<p>Definition at line 509 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9d4f83fc113ed4b161e4e89743efb1e4">idx_begin</a>, <a href="#a630f2e601df642f71613ccf6d7ea889c">idx_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecompares-cpp/#abce78109fa7acac1ae7aa1b4ee1ce07f">transformToIndexedCompare</a>.</p>

</div>
</div>

### hasAllZeroIndices() {#a608bf9c26922fc798bc8bd85601ce94d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::hasAllZeroIndices ()</td>
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

<p>Return true if all of the indices of this GEP are zeros.</p>


<p>If so, the result pointer and the first operand have the same value, just potentially different types.</p>


<p>Definition at line 496 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#abb2b3a60ccc38a28239e19a1646e0c8a">E</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a9d4f83fc113ed4b161e4e89743efb1e4">idx_begin</a> and <a href="#a630f2e601df642f71613ccf6d7ea889c">idx_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#aefdc5e2a3d0696ee5c5bf0b467e5f0c5">evaluateICmpRelation</a>.</p>

</div>
</div>

### hasIndices() {#ab52b529f03851cdc98af7aa85382ee93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::hasIndices ()</td>
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



<p>Definition at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#addec638786f763d967811b45cb662f1f">llvm::User::getNumOperands</a>.</p>

</div>
</div>

### hasNoUnsignedSignedWrap() {#a02a7ce64ac78b2de107d6726b64b71a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::hasNoUnsignedSignedWrap ()</td>
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



<p>Definition at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="#a9f19d28f31c79215e0e0190115b0373d">getNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a992b9efb797f896ae2cc7f1d043eb68f">llvm::GEPNoWrapFlags::hasNoUnsignedSignedWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67aa349e8bb1aefc2a8a6ca18be9b87c">llvm::emitGEPOffset</a>.</p>

</div>
</div>

### hasNoUnsignedWrap() {#a5efdc1f8478ba644e2413b9c143dd46c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::hasNoUnsignedWrap ()</td>
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



<p>Definition at line 441 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="#a9f19d28f31c79215e0e0190115b0373d">getNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#a9f5326edaaa9f5ad4e786d473b7c000a">llvm::GEPNoWrapFlags::hasNoUnsignedWrap</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a67aa349e8bb1aefc2a8a6ca18be9b87c">llvm::emitGEPOffset</a>.</p>

</div>
</div>

### idx\_begin() {#a9d4f83fc113ed4b161e4e89743efb1e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::GEPOperator::idx_begin ()</td>
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



<p>Definition at line 449 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>.</p>


<p>Referenced by <a href="#aa4d79f790f6bd3fa3234d4137979215b">hasAllConstantIndices</a>, <a href="#a608bf9c26922fc798bc8bd85601ce94d">hasAllZeroIndices</a>, <a href="#aad281f19120240f5f387f716057cfbd8">indices</a> and <a href="#abe215e8a1517f7235e67fb9fad636211">indices</a>.</p>

</div>
</div>

### idx\_begin() {#a355becb10a5cb4996c4e543600db7d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GEPOperator::idx_begin ()</td>
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



<p>Definition at line 450 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#a2eeb1c7ed1cfe403f2ae0470e36c07e2">llvm::User::op_begin</a>.</p>

</div>
</div>

### idx\_end() {#a630f2e601df642f71613ccf6d7ea889c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">op_iterator llvm::GEPOperator::idx_end ()</td>
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



<p>Definition at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>.</p>


<p>Referenced by <a href="#aa4d79f790f6bd3fa3234d4137979215b">hasAllConstantIndices</a>, <a href="#a608bf9c26922fc798bc8bd85601ce94d">hasAllZeroIndices</a>, <a href="#aad281f19120240f5f387f716057cfbd8">indices</a> and <a href="#abe215e8a1517f7235e67fb9fad636211">indices</a>.</p>

</div>
</div>

### idx\_end() {#a165208bc52bf227e27432d2ca5c59943}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_op_iterator llvm::GEPOperator::idx_end ()</td>
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



<p>Definition at line 452 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/user/#af41f58e730804d10b91fcff39b035f74">llvm::User::op_end</a>.</p>

</div>
</div>

### indices() {#aad281f19120240f5f387f716057cfbd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; op_iterator &gt; llvm::GEPOperator::indices ()</td>
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



<p>Definition at line 454 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="#a9d4f83fc113ed4b161e4e89743efb1e4">idx_begin</a>, <a href="#a630f2e601df642f71613ccf6d7ea889c">idx_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="#a57286aaebfc778a6c1215125ed8493ef">countNonConstantIndices</a>.</p>

</div>
</div>

### indices() {#abe215e8a1517f7235e67fb9fad636211}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_op_iterator &gt; llvm::GEPOperator::indices ()</td>
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



<p>Definition at line 458 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="#a9d4f83fc113ed4b161e4e89743efb1e4">idx_begin</a>, <a href="#a630f2e601df642f71613ccf6d7ea889c">idx_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### isInBounds() {#a3783a9756e9b9a1fe124622d27522713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::isInBounds ()</td>
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

<p>Test whether this is an inbounds GEP, as defined by LangRef.html.</p>

<p>Definition at line 435 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>


<p>References <a href="#a9f19d28f31c79215e0e0190115b0373d">getNoWrapFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/gepnowrapflags/#aaba6873d157dbd7f5f02da723e6ca78f">llvm::GEPNoWrapFlags::isInBounds</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/ir/constantfold-cpp/#aefdc5e2a3d0696ee5c5bf0b467e5f0c5">evaluateICmpRelation</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#afc78cb7aeb92b0fc9223239dd827f7e3">llvm::InstCombinerImpl::foldGEPICmp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### accumulateConstantOffset() {#a4ef0843f4b374aae185be929453c9de5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::GEPOperator::accumulateConstantOffset (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * SourceType, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Index, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; Offset, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; bool(<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> &amp;, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp;)&gt; ExternalAnalysis=nullptr)</td>
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



<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/structlayout/#a3932cc53acb297750961bfdaa86425bc">llvm::StructLayout::getElementOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#ac6d28a9b11139182134a9618028a0d07">llvm::Type::isIntegerTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/classes/llvm/apint/#ac155d7c568fc1aba25723e77b6888908">llvm::APInt::smul_ov</a>.</p>

</div>
</div>

### getPointerOperandIndex() {#afef50f11f07a98789828558ad39240ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::GEPOperator::getPointerOperandIndex ()</td>
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



<p>Definition at line 468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/operator-h">Operator.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/operator-cpp">Operator.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
