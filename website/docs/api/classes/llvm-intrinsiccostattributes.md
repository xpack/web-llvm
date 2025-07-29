---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/intrinsiccostattributes
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `IntrinsicCostAttributes` Class



## Declaration

<div class="doxyDeclaration">
class llvm::IntrinsicCostAttributes { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">llvm/Analysis/TargetTransformInfo.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6760a5137f8e0ec21dbd7b99e61b52ed">IntrinsicCostAttributes</a> (Intrinsic::ID Id, const CallBase &amp;CI, InstructionCost ScalarCost=InstructionCost::getInvalid(), bool TypeBasedOnly=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b3fc544cd1ea3af9bff77f90b925bbf">IntrinsicCostAttributes</a> (Intrinsic::ID Id, Type *RTy, ArrayRef&lt; Type * &gt; Tys, FastMathFlags Flags=FastMathFlags(), const IntrinsicInst *I=nullptr, InstructionCost ScalarCost=InstructionCost::getInvalid())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2031b426c61bce2c9afd0f1463d109">IntrinsicCostAttributes</a> (Intrinsic::ID Id, Type *RTy, ArrayRef&lt; const Value * &gt; Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c21562a67790af89c718584d5e4a182">IntrinsicCostAttributes</a> (Intrinsic::ID Id, Type *RTy, ArrayRef&lt; const Value * &gt; Args, ArrayRef&lt; Type * &gt; Tys, FastMathFlags Flags=FastMathFlags(), const IntrinsicInst *I=nullptr, InstructionCost ScalarCost=InstructionCost::getInvalid())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12b3fb3cabe9735daed0349fae1887d">getID</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d3355876427f9e29928983238a3b51">getInst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c2339b82bd84f5ce831ebbf3e1aee5c">getReturnType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a032301475dcb14f891d0592dfaa249f3">getFlags</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8d1ad9c1a90a3040533c9d2194a4431">getScalarizationCost</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d2619377c25f857edd07f64ad567402">getArgs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a389479c79cad666d7d3c23318280cdcf">getArgTypes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aface2c2d46de2d749a3d8dd3ca8b9bfb">isTypeBasedOnly</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4baa5f0da110f6c463ecff6acc1c41d6">skipScalarizationCost</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2619fd7be8ffc320f84c14f1d454c557">II</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ca8eb46a39d45a52a8849373f3a6bb0">RetTy</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c638fcb1c083c90739a6f62b93a6d34">IID</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c38b426704a40501660a1373d3a880">ParamTys</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45567a6be4f48c3b4a399326ac0081d5">Arguments</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e45d6f8dee36ddf4349b954f1bc55d8">FMF</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41fded1a409e830ccd707cfb8927d32f">ScalarizationCost</a> = <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">InstructionCost::getInvalid</a>()</td>
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


<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### IntrinsicCostAttributes() {#a6760a5137f8e0ec21dbd7b99e61b52ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrinsicCostAttributes::IntrinsicCostAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; CI, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> ScalarCost=<a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">InstructionCost::getInvalid</a>(), bool TypeBasedOnly=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/callbase/#a4fb513d744ca72275932b2c7003f16f6">llvm::CallBase::arg_begin</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac0f11b96f81b2769dd23d028e3189075">llvm::CallBase::arg_end</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a21075305f0e463b24aafc2fb99514ace">llvm::Function::getFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="/web-llvm/docs/api/files/lib/lib/passes/passbuilderbindings-cpp/#acdfbcf188e2d4a80837e89de2ccdffab">if</a>.</p>

</div>
</div>

### IntrinsicCostAttributes() {#a8b3fc544cd1ea3af9bff77f90b925bbf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrinsicCostAttributes::IntrinsicCostAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a>(), <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * I=nullptr, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> ScalarCost=<a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">InstructionCost::getInvalid</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 85 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### IntrinsicCostAttributes() {#acd2031b426c61bce2c9afd0f1463d109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrinsicCostAttributes::IntrinsicCostAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64expandpseudoinsts-cpp/#a4cfc8b177e8521a4b496ae2edff6244f">for</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>

</div>
</div>

### IntrinsicCostAttributes() {#a2c21562a67790af89c718584d5e4a182}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntrinsicCostAttributes::IntrinsicCostAttributes (<a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RTy, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Tys, <a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a> Flags=<a href="/web-llvm/docs/api/classes/llvm/fastmathflags">FastMathFlags</a>(), <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/intrinsicinst">IntrinsicInst</a> * I=nullptr, <a href="/web-llvm/docs/api/classes/llvm/instructioncost">InstructionCost</a> ScalarCost=<a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">InstructionCost::getInvalid</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getArgs() {#a4d2619377c25f857edd07f64ad567402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; const Value * &gt; &amp; llvm::IntrinsicCostAttributes::getArgs ()</td>
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



<p>Definition at line 155 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a8965f79b48ae37911f82bc71e1433131">llvm::RISCVTTIImpl::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a>.</p>

</div>
</div>

### getArgTypes() {#a389479c79cad666d7d3c23318280cdcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SmallVectorImpl&lt; Type * &gt; &amp; llvm::IntrinsicCostAttributes::getArgTypes ()</td>
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



<p>Definition at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#a8a65916cd3a5fe149b7cee7a978a80eb">getHistogramCost</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a8965f79b48ae37911f82bc71e1433131">llvm::RISCVTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a7dafc3bb7b6d26a4ac107d35b3573670">llvm::SystemZTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>.</p>

</div>
</div>

### getFlags() {#a032301475dcb14f891d0592dfaa249f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::IntrinsicCostAttributes::getFlags ()</td>
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



<p>Definition at line 153 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>.</p>

</div>
</div>

### getID() {#af12b3fb3cabe9735daed0349fae1887d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID llvm::IntrinsicCostAttributes::getID ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a09fb36481c632cf2772ebce4492cb31e">llvm::GCNTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a8cb76eaa181555961ab6af4571017ea6">llvm::HexagonTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a8965f79b48ae37911f82bc71e1433131">llvm::RISCVTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a7dafc3bb7b6d26a4ac107d35b3573670">llvm::SystemZTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/targettransforminfoimplbase/#a4eaac4d2c1c7ce1ac8be447338a6e7e5">llvm::TargetTransformInfoImplBase::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>.</p>

</div>
</div>

### getInst() {#aa9d3355876427f9e29928983238a3b51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IntrinsicInst * llvm::IntrinsicCostAttributes::getInst ()</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a>.</p>

</div>
</div>

### getReturnType() {#a3c2339b82bd84f5ce831ebbf3e1aee5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::IntrinsicCostAttributes::getReturnType ()</td>
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



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a24393b2d81198cf0c6b844750b943292">llvm::AArch64TTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/armttiimpl/#a4ce494fdd302adc3c52bc02868f223c8">llvm::ARMTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#a09fb36481c632cf2772ebce4492cb31e">llvm::GCNTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagonttiimpl/#a8cb76eaa181555961ab6af4571017ea6">llvm::HexagonTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvttiimpl/#a8965f79b48ae37911f82bc71e1433131">llvm::RISCVTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzttiimpl/#a7dafc3bb7b6d26a4ac107d35b3573670">llvm::SystemZTTIImpl::getIntrinsicInstrCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>.</p>

</div>
</div>

### getScalarizationCost() {#aa8d1ad9c1a90a3040533c9d2194a4431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::IntrinsicCostAttributes::getScalarizationCost ()</td>
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



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>.</p>

</div>
</div>

### isTypeBasedOnly() {#aface2c2d46de2d749a3d8dd3ca8b9bfb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntrinsicCostAttributes::isTypeBasedOnly ()</td>
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



<p>Definition at line 158 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#a05184f6230f850d3f972f6d904bd2ef5">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getIntrinsicInstrCost</a> and <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a96c419a83b9a7fbb570adf7fc3f5a253">llvm::X86TTIImpl::getIntrinsicInstrCost</a>.</p>

</div>
</div>

### skipScalarizationCost() {#a4baa5f0da110f6c463ecff6acc1c41d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::IntrinsicCostAttributes::skipScalarizationCost ()</td>
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



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/basicttiimplbase/#ae2b0b2a1ae237432c1c272406a8b4667">llvm::BasicTTIImplBase&lt; BasicTTIImpl &gt;::getTypeBasedIntrinsicInstrCost</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### Arguments {#a45567a6be4f48c3b4a399326ac0081d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;const Value *, 4&gt; llvm::IntrinsicCostAttributes::Arguments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 124 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### FMF {#a3e45d6f8dee36ddf4349b954f1bc55d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastMathFlags llvm::IntrinsicCostAttributes::FMF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### II {#a2619fd7be8ffc320f84c14f1d454c557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IntrinsicInst* llvm::IntrinsicCostAttributes::II = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### IID {#a0c638fcb1c083c90739a6f62b93a6d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Intrinsic::ID llvm::IntrinsicCostAttributes::IID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### ParamTys {#a65c38b426704a40501660a1373d3a880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Type *, 4&gt; llvm::IntrinsicCostAttributes::ParamTys</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### RetTy {#a4ca8eb46a39d45a52a8849373f3a6bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::IntrinsicCostAttributes::RetTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

### ScalarizationCost {#a41fded1a409e830ccd707cfb8927d32f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">InstructionCost llvm::IntrinsicCostAttributes::ScalarizationCost = <a href="/web-llvm/docs/api/classes/llvm/instructioncost/#a57207993e2fe6ec98912e8072e4600bc">InstructionCost::getInvalid</a>()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/analysis/targettransforminfo-h">TargetTransformInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/analysis/targettransforminfo-cpp">TargetTransformInfo.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
