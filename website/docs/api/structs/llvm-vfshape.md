---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/vfshape
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `VFShape` Struct Reference

<p>Contains the information about the kind of vectorization available. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::VFShape { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">llvm/IR/VFABIDemangler.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea3cb55414569157978afce988b13659">operator==</a> (const VFShape &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ac579f061e62acfe262be1d1906eea2">updateParam</a> (VFParameter P)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Update the parameter in position P.ParamPos to P. <a href="#a7ac579f061e62acfe262be1d1906eea2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73ecf8e2dc91bc82db95710da747b5ab">hasValidParameterList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Validation check on the Parameters in the <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a>. <a href="#a73ecf8e2dc91bc82db95710da747b5ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77688fcf1805363e5914276b0d491b63">VF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/vfparameter">VFParameter</a>, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82591e3e596fe99aebc1e2f3316ef41c">Parameters</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7db4cdbe016c25c229740fceb0bd2a1">getScalarShape</a> (const FunctionType *FTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a> that can be used to map a scalar function to itself, with VF = 1. <a href="#ac7db4cdbe016c25c229740fceb0bd2a1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacd1691cd95a1e3e538fcee4c2cc8d05">get</a> (const FunctionType *FTy, ElementCount EC, bool HasGlobalPred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieve the basic vectorization shape of the function, where all parameters are mapped to <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">VFParamKind::Vector</a> with <span class="doxyComputerOutput">EC</span> lanes. <a href="#aacd1691cd95a1e3e538fcee4c2cc8d05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Contains the information about the kind of vectorization available.</p>


<p>This object in independent on the paradigm used to represent vector functions. in particular, it is not attached to any target-specific ABI.</p>


<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#aea3cb55414569157978afce988b13659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::VFShape::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a> &amp; Other)</td>
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



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a82591e3e596fe99aebc1e2f3316ef41c">Parameters</a> and <a href="#a77688fcf1805363e5914276b0d491b63">VF</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasValidParameterList() {#a73ecf8e2dc91bc82db95710da747b5ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VFShape::hasValidParameterList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Validation check on the Parameters in the <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a>.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39adf3e3249ad10ccf5bf901eb83c105cc3">llvm::GlobalPredicate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a16454c62ab71c641dedda0971980c9d5">llvm::OMP_Linear</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39aaec63779faad458a0dc8cbd703de79cd">llvm::OMP_LinearPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a1177c82a038df4f925f122e45c6da0fa">llvm::OMP_LinearRef</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39ab411a051b5361e5fecaebbc0c09c5a32">llvm::OMP_LinearRefPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39acb8cf9f2514a0c9c419bbe481cd6043c">llvm::OMP_LinearUVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a3cb8b4a8b5f2ae8ebd7564386cf178c4">llvm::OMP_LinearUValPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a33c412d71677159e382a0a8cd9408d8a">llvm::OMP_LinearVal</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39ab5212d79459110e59ba16ff486f4a75a">llvm::OMP_LinearValPos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39acbf35bbdad5d09f9072d0e83e78e90e4">llvm::OMP_Uniform</a> and <a href="#a82591e3e596fe99aebc1e2f3316ef41c">Parameters</a>.</p>


<p>Referenced by <a href="#a7ac579f061e62acfe262be1d1906eea2">updateParam</a>.</p>

</div>
</div>

### updateParam() {#a7ac579f061e62acfe262be1d1906eea2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::VFShape::updateParam (<a href="/web-llvm/docs/api/structs/llvm/vfparameter">VFParameter</a> P)</td>
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

<p>Update the parameter in position P.ParamPos to P.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a73ecf8e2dc91bc82db95710da747b5ab">hasValidParameterList</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="#a82591e3e596fe99aebc1e2f3316ef41c">Parameters</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Parameters {#a82591e3e596fe99aebc1e2f3316ef41c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;VFParameter, 8&gt; llvm::VFShape::Parameters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#aacd1691cd95a1e3e538fcee4c2cc8d05">get</a>, <a href="#a73ecf8e2dc91bc82db95710da747b5ab">hasValidParameterList</a>, <a href="#aea3cb55414569157978afce988b13659">operator==</a> and <a href="#a7ac579f061e62acfe262be1d1906eea2">updateParam</a>.</p>

</div>
</div>

### VF {#a77688fcf1805363e5914276b0d491b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ElementCount llvm::VFShape::VF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>Referenced by <a href="#aea3cb55414569157978afce988b13659">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### get() {#aacd1691cd95a1e3e538fcee4c2cc8d05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VFShape llvm::VFShape::get (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy, <a href="/web-llvm/docs/api/classes/llvm/elementcount">ElementCount</a> EC, bool HasGlobalPred)</td>
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

<p>Retrieve the basic vectorization shape of the function, where all parameters are mapped to <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">VFParamKind::Vector</a> with <span class="doxyComputerOutput">EC</span> lanes.</p>


<p>Specifies whether the function has a Global <a href="/web-llvm/docs/api/classes/predicate">Predicate</a> argument via <span class="doxyComputerOutput">HasGlobalPred</span>.</p>


<p>Definition at line 108 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a104d6154321899b53e40455e71d8e83a">llvm::FunctionType::getNumParams</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39adf3e3249ad10ccf5bf901eb83c105cc3">llvm::GlobalPredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a82591e3e596fe99aebc1e2f3316ef41c">Parameters</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#add480f2ed87faa59c16d4c01ffb4bf39a57dea6f5039281b7fee517fc43bf3110">llvm::Vector</a>.</p>


<p>Referenced by <a href="#ac7db4cdbe016c25c229740fceb0bd2a1">getScalarShape</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/vectorize/slpvectorizer-cpp/#a8a8b818a539c2cbbe1a954a875c5fcec">getVectorCallCosts</a>.</p>

</div>
</div>

### getScalarShape() {#ac7db4cdbe016c25c229740fceb0bd2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VFShape llvm::VFShape::getScalarShape (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FTy)</td>
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

<p>Retrieve the <a href="/web-llvm/docs/api/structs/llvm/vfshape">VFShape</a> that can be used to map a scalar function to itself, with VF = 1.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a>.</p>


<p>References <a href="#aacd1691cd95a1e3e538fcee4c2cc8d05">get</a> and <a href="/web-llvm/docs/api/classes/llvm/elementcount/#a584cb8dfa0090b33a969c4dda27337f6">llvm::ElementCount::getFixed</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/vfdatabase/#ga27014498d4eea7c1e7455cc33538ca2b">llvm::VFDatabase::getVectorizedFunction</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/vfabidemangler-h">VFABIDemangler.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/vfabidemangler-cpp">VFABIDemangler.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
