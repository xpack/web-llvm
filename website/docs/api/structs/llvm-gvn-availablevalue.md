---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/gvn/availablevalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `AvailableValue` Struct

<p>Represents a particular available value that we know how to materialize. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::gvn::AvailableValue { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ValType { <a href="#a42db635c040abe996f4934c75686359c">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1957eb1d23950a66cddf35d4e62c0650">isSimpleValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4117f47b6acddc12c794b2549094ffc6">isCoercedLoadValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7d485c64e80962fadbbbfe8e1832e2f">isMemIntrinValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d3f6ea51fcb69b01486a4f6fb5c52eb">isUndefValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba901f0be98c9561867673a9057e903">isSelectValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad74ab84c725f62ca1b523eadea123fc8">getSimpleValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80c83b36272817a6a0ce3f43ff3c9ea0">getCoercedLoadValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7709891035375e6227b2f37c47e0ebc">getMemIntrinValue</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad66a6b13063b6dc386d02dae3bb33bfc">getSelectValue</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a> (LoadInst *Load, Instruction *InsertPt, GVNPass &amp;gvn) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Emit code at the specified insertion point to adjust the value defined here to the specified type. <a href="#ac96558c87ecbcc96f020a0efcaade750">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Val - The value that is live out of the block. <a href="#ab9f29688ab930e667650960bd1e3b5f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a42db635c040abe996f4934c75686359c">ValType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Kind of the live-out value. <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">Offset</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Offset - The byte offset in Val that is interesting for the load query. <a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac46064c40813ae08522074a52c486d9d">V1</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>V1, V2 - The dominating non-clobbered values of SelectVal. <a href="#ac46064c40813ae08522074a52c486d9d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b03efeb26edf19fa86bb02ae9e10c9d">V2</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e01d73dca4690562ee833fea9becbfb">get</a> (Value *V, unsigned Offset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d12af97f2ad6cbd8afde5ad3c76ce42">getMI</a> (MemIntrinsic *MI, unsigned Offset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fb90fef376df87f6cc844521cd7eb54">getLoad</a> (LoadInst *Load, unsigned Offset=0)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf794f14bc9b47394083056177f8d831">getUndef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21f6f28b6684fc17f3b56b76f379fc8d">getSelect</a> (SelectInst *Sel, Value *V1, Value *V2)</td>
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

<p>Represents a particular available value that we know how to materialize.</p>


<p>Materialization of an <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a> never fails. An <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalue">AvailableValue</a> is implicitly associated with a rematerialization point which is the location of the instruction from which it was formed.</p>


<p>Definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<div class="doxySectionDef">

## Enumerations

### ValType {#a42db635c040abe996f4934c75686359c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::gvn::AvailableValue::ValType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SimpleVal<a id="a42db635c040abe996f4934c75686359ca46063ab51f6e3c7d5e83b2b912e8ff67"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LoadVal<a id="a42db635c040abe996f4934c75686359cacebf64a7a9b11567b7250b04216f476e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MemIntrin<a id="a42db635c040abe996f4934c75686359cafb9df60f3f06499c2026f51aef6c2f68"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UndefVal<a id="a42db635c040abe996f4934c75686359cae6b3602612e62cf9eb0f56a3e0747275"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SelectVal<a id="a42db635c040abe996f4934c75686359ca5125cfc79b04e50d3d9ec9280202836a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 199 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCoercedLoadValue() {#a80c83b36272817a6a0ce3f43ff3c9ea0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LoadInst * llvm::gvn::AvailableValue::getCoercedLoadValue ()</td>
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



<p>Definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a4117f47b6acddc12c794b2549094ffc6">isCoercedLoadValue</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>


<p>Referenced by <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### getMemIntrinValue() {#ae7709891035375e6227b2f37c47e0ebc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemIntrinsic * llvm::gvn::AvailableValue::getMemIntrinValue ()</td>
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



<p>Definition at line 277 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#ad7d485c64e80962fadbbbfe8e1832e2f">isMemIntrinValue</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>


<p>Referenced by <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### getSelectValue() {#ad66a6b13063b6dc386d02dae3bb33bfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SelectInst * llvm::gvn::AvailableValue::getSelectValue ()</td>
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



<p>Definition at line 282 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#aaba901f0be98c9561867673a9057e903">isSelectValue</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>


<p>Referenced by <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### getSimpleValue() {#ad74ab84c725f62ca1b523eadea123fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::gvn::AvailableValue::getSimpleValue ()</td>
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



<p>Definition at line 267 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a1957eb1d23950a66cddf35d4e62c0650">isSimpleValue</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>


<p>Referenced by <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### isCoercedLoadValue() {#a4117f47b6acddc12c794b2549094ffc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gvn::AvailableValue::isCoercedLoadValue ()</td>
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



<p>Definition at line 262 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a> and <a href="#a42db635c040abe996f4934c75686359cacebf64a7a9b11567b7250b04216f476e">LoadVal</a>.</p>


<p>Referenced by <a href="#a80c83b36272817a6a0ce3f43ff3c9ea0">getCoercedLoadValue</a> and <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### isMemIntrinValue() {#ad7d485c64e80962fadbbbfe8e1832e2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gvn::AvailableValue::isMemIntrinValue ()</td>
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



<p>Definition at line 263 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a> and <a href="#a42db635c040abe996f4934c75686359cafb9df60f3f06499c2026f51aef6c2f68">MemIntrin</a>.</p>


<p>Referenced by <a href="#ae7709891035375e6227b2f37c47e0ebc">getMemIntrinValue</a> and <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### isSelectValue() {#aaba901f0be98c9561867673a9057e903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gvn::AvailableValue::isSelectValue ()</td>
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



<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a> and <a href="#a42db635c040abe996f4934c75686359ca5125cfc79b04e50d3d9ec9280202836a">SelectVal</a>.</p>


<p>Referenced by <a href="#ad66a6b13063b6dc386d02dae3bb33bfc">getSelectValue</a> and <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### isSimpleValue() {#a1957eb1d23950a66cddf35d4e62c0650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gvn::AvailableValue::isSimpleValue ()</td>
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



<p>Definition at line 261 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a> and <a href="#a42db635c040abe996f4934c75686359ca46063ab51f6e3c7d5e83b2b912e8ff67">SimpleVal</a>.</p>


<p>Referenced by <a href="#ad74ab84c725f62ca1b523eadea123fc8">getSimpleValue</a> and <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### isUndefValue() {#a9d3f6ea51fcb69b01486a4f6fb5c52eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::gvn::AvailableValue::isUndefValue ()</td>
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



<p>Definition at line 264 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a> and <a href="#a42db635c040abe996f4934c75686359cae6b3602612e62cf9eb0f56a3e0747275">UndefVal</a>.</p>

</div>
</div>

### MaterializeAdjustedValue() {#ac96558c87ecbcc96f020a0efcaade750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * AvailableValue::MaterializeAdjustedValue (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, <a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> * InsertPt, <a href="/web-llvm/docs/api/classes/llvm/gvnpass">GVNPass</a> &amp; gvn)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Emit code at the specified insertion point to adjust the value defined here to the specified type.</p>


<p>This handles various coercion cases.</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9b43098c569ea8289ed1ab70ee9a00af">llvm::combineMetadataForCSE</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a09d8760fa31a7b8739acf71a4d2ac9d9">llvm::SelectInst::Create</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/arm/armslshardening-cpp/#ad467c4ab9119043f9b7750ab986be61a">DL</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9c5f771f232bbd4cf6ec230bd78f9174">llvm::Instruction::dropUnknownNonDebugMetadata</a>, <a href="#a80c83b36272817a6a0ce3f43ff3c9ea0">getCoercedLoadValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a706a961e17ec4354d2174aac3ea3ecb5">llvm::SelectInst::getCondition</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a6b72d403292d9dddd1ef1ce3e8bc394c">llvm::VNCoercion::getMemInstValueForLoad</a>, <a href="#ae7709891035375e6227b2f37c47e0ebc">getMemIntrinValue</a>, <a href="#ad66a6b13063b6dc386d02dae3bb33bfc">getSelectValue</a>, <a href="#ad74ab84c725f62ca1b523eadea123fc8">getSimpleValue</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vncoercion/#a0786ad18996fdeb6bb0e33c3bfa4ce82">llvm::VNCoercion::getValueForLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a565f546ad95bd3a9bbe9a1e5040803f0">llvm::Instruction::hasMetadata</a>, <a href="#a4117f47b6acddc12c794b2549094ffc6">isCoercedLoadValue</a>, <a href="#ad7d485c64e80962fadbbbfe8e1832e2f">isMemIntrinValue</a>, <a href="#aaba901f0be98c9561867673a9057e903">isSelectValue</a>, <a href="#a1957eb1d23950a66cddf35d4e62c0650">isSimpleValue</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/debug-h/#a196897517069dda1bdb549e24468f7d7">LLVM_DEBUG</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">Offset</a>, <a href="#ac46064c40813ae08522074a52c486d9d">V1</a> and <a href="#a1b03efeb26edf19fa86bb02ae9e10c9d">V2</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Kind {#a53b4d539e0cab6b6027eb49e3291e7d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValType llvm::gvn::AvailableValue::Kind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Kind of the live-out value.</p>

<p>Definition at line 212 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Referenced by <a href="#a4e01d73dca4690562ee833fea9becbfb">get</a>, <a href="#a8fb90fef376df87f6cc844521cd7eb54">getLoad</a>, <a href="#a9d12af97f2ad6cbd8afde5ad3c76ce42">getMI</a>, <a href="#a21f6f28b6684fc17f3b56b76f379fc8d">getSelect</a>, <a href="#acf794f14bc9b47394083056177f8d831">getUndef</a>, <a href="#a4117f47b6acddc12c794b2549094ffc6">isCoercedLoadValue</a>, <a href="#ad7d485c64e80962fadbbbfe8e1832e2f">isMemIntrinValue</a>, <a href="#aaba901f0be98c9561867673a9057e903">isSelectValue</a>, <a href="#a1957eb1d23950a66cddf35d4e62c0650">isSimpleValue</a> and <a href="#a9d3f6ea51fcb69b01486a4f6fb5c52eb">isUndefValue</a>.</p>

</div>
</div>

### Offset {#a0672cd4b94a2a2a421c86c60b2ce8ae9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::gvn::AvailableValue::Offset = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Offset - The byte offset in Val that is interesting for the load query.</p>

<p>Definition at line 215 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Referenced by <a href="#a4e01d73dca4690562ee833fea9becbfb">get</a>, <a href="#a8fb90fef376df87f6cc844521cd7eb54">getLoad</a>, <a href="#a9d12af97f2ad6cbd8afde5ad3c76ce42">getMI</a>, <a href="#a21f6f28b6684fc17f3b56b76f379fc8d">getSelect</a>, <a href="#acf794f14bc9b47394083056177f8d831">getUndef</a> and <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### V1 {#ac46064c40813ae08522074a52c486d9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::gvn::AvailableValue::V1 = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>V1, V2 - The dominating non-clobbered values of SelectVal.</p>

<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Referenced by <a href="#a21f6f28b6684fc17f3b56b76f379fc8d">getSelect</a> and <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### V2 {#a1b03efeb26edf19fa86bb02ae9e10c9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value * llvm::gvn::AvailableValue::V2 = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Referenced by <a href="#a21f6f28b6684fc17f3b56b76f379fc8d">getSelect</a> and <a href="#ac96558c87ecbcc96f020a0efcaade750">MaterializeAdjustedValue</a>.</p>

</div>
</div>

### Val {#ab9f29688ab930e667650960bd1e3b5f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Value* llvm::gvn::AvailableValue::Val</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Val - The value that is live out of the block.</p>

<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>Referenced by <a href="#a4e01d73dca4690562ee833fea9becbfb">get</a>, <a href="#a80c83b36272817a6a0ce3f43ff3c9ea0">getCoercedLoadValue</a>, <a href="#a8fb90fef376df87f6cc844521cd7eb54">getLoad</a>, <a href="#ae7709891035375e6227b2f37c47e0ebc">getMemIntrinValue</a>, <a href="#a9d12af97f2ad6cbd8afde5ad3c76ce42">getMI</a>, <a href="#a21f6f28b6684fc17f3b56b76f379fc8d">getSelect</a>, <a href="#ad66a6b13063b6dc386d02dae3bb33bfc">getSelectValue</a>, <a href="#ad74ab84c725f62ca1b523eadea123fc8">getSimpleValue</a> and <a href="#acf794f14bc9b47394083056177f8d831">getUndef</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#a4e01d73dca4690562ee833fea9becbfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValue llvm::gvn::AvailableValue::get (<a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V, unsigned Offset=0)</td>
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



<p>Definition at line 219 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a>, <a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">Offset</a>, <a href="#a42db635c040abe996f4934c75686359ca46063ab51f6e3c7d5e83b2b912e8ff67">SimpleVal</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock/#a2b3759c8c4cc24dcceead45a434546d0">llvm::gvn::AvailableValueInBlock::get</a>.</p>

</div>
</div>

### getLoad() {#a8fb90fef376df87f6cc844521cd7eb54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValue llvm::gvn::AvailableValue::getLoad (<a href="/web-llvm/docs/api/classes/llvm/loadinst">LoadInst</a> * Load, unsigned Offset=0)</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a>, <a href="#a42db635c040abe996f4934c75686359cacebf64a7a9b11567b7250b04216f476e">LoadVal</a>, <a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">Offset</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>

</div>
</div>

### getMI() {#a9d12af97f2ad6cbd8afde5ad3c76ce42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValue llvm::gvn::AvailableValue::getMI (<a href="/web-llvm/docs/api/classes/llvm/memintrinsic">MemIntrinsic</a> * MI, unsigned Offset=0)</td>
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



<p>Definition at line 227 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a>, <a href="#a42db635c040abe996f4934c75686359cafb9df60f3f06499c2026f51aef6c2f68">MemIntrin</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">Offset</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>

</div>
</div>

### getSelect() {#a21f6f28b6684fc17f3b56b76f379fc8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValue llvm::gvn::AvailableValue::getSelect (<a href="/web-llvm/docs/api/classes/llvm/selectinst">SelectInst</a> * Sel, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V1, <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V2)</td>
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



<p>Definition at line 251 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a>, <a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">Offset</a>, <a href="#a42db635c040abe996f4934c75686359ca5125cfc79b04e50d3d9ec9280202836a">SelectVal</a>, <a href="#ac46064c40813ae08522074a52c486d9d">V1</a>, <a href="#a1b03efeb26edf19fa86bb02ae9e10c9d">V2</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock/#aa2a77bfeac83b06ea3d42c9ed38b511a">llvm::gvn::AvailableValueInBlock::getSelect</a>.</p>

</div>
</div>

### getUndef() {#acf794f14bc9b47394083056177f8d831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AvailableValue llvm::gvn::AvailableValue::getUndef ()</td>
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



<p>Definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a>.</p>


<p>References <a href="#a53b4d539e0cab6b6027eb49e3291e7d3">Kind</a>, <a href="#a0672cd4b94a2a2a421c86c60b2ce8ae9">Offset</a>, <a href="#a42db635c040abe996f4934c75686359cae6b3602612e62cf9eb0f56a3e0747275">UndefVal</a> and <a href="#ab9f29688ab930e667650960bd1e3b5f6">Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/gvn/availablevalueinblock/#a311f188566b0d91b585df6c8bb31eb3a">llvm::gvn::AvailableValueInBlock::getUndef</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/gvn-cpp">GVN.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
