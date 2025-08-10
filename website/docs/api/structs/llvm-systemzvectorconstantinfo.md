---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/systemzvectorconstantinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `SystemZVectorConstantInfo` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::SystemZVectorConstantInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">Target/SystemZ/SystemZISelLowering.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7da80f756644226c925de9aa4bf77d94">SystemZVectorConstantInfo</a> (APInt IntImm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a62e5d01aa7e3692c19b8fedd0e6e2333">SystemZVectorConstantInfo</a> (APFloat FPImm)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa073d1e5ff2c5e5a53876841e1ff6fad">SystemZVectorConstantInfo</a> (BuildVectorSDNode *BVN)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6ba63ef6a9e69ae5ae03797b21964fd">isVectorConstantLegal</a> (const SystemZSubtarget &amp;Subtarget)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ff1cd19df6c3e85d9548a659dc44ea3">Opcode</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; unsigned, 2 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e3980a04849dd0c23a6b3e652671cb">OpVals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3989c66a3550ee570cbe7902b9b105e5">VecVT</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa158704919e38ddda0e7195c19170b9">IntBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa973e61e6942295bb5de2d9a7cdf960d">SplatBits</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d5f5e20643e34cc5211363ff559934e">SplatUndef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a905dd8fd348678ae42b5682232d9c557">SplatBitSize</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd94b90a72d89da7fdd8a2b9cdf62ec0">isFP128</a> = false</td>
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


<p>Definition at line 827 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SystemZVectorConstantInfo() {#a7da80f756644226c925de9aa4bf77d94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZVectorConstantInfo::SystemZVectorConstantInfo (<a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> IntImm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 838 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>, definition at line 927 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a512fe2c15ea651294688eeec1341644c">llvm::APInt::getBitWidth</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a217e0207d9cc8e046c2dccbf0e4bb198">llvm::APInt::getZExtValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a5ed1d98c99f36cde30cb052c78fa5e35">llvm::APInt::isSingleWord</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#af34549c39d6f741fbdaf9a795aa306e9">llvm::APInt::lshr</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a317c64fd4cfebc88e79387b3821a629d">llvm::APInt::trunc</a> and <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a5e2f6288a79b32c4bc9f22fe3f3222b2">llvm::SystemZ::VectorBits</a>.</p>


<p>Referenced by <a href="#a62e5d01aa7e3692c19b8fedd0e6e2333">SystemZVectorConstantInfo</a>.</p>

</div>
</div>

### SystemZVectorConstantInfo() {#a62e5d01aa7e3692c19b8fedd0e6e2333}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::SystemZVectorConstantInfo::SystemZVectorConstantInfo (<a href="/web-llvm/docs/api/classes/llvm/apfloat">APFloat</a> FPImm)</td>
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



<p>Definition at line 839 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/apfloat/#a643f8cd038a6fa41604fe8e3df11f977">llvm::APFloat::getSemantics</a>, <a href="/web-llvm/docs/api/structs/llvm/apfloatbase/#a494661a175e7785032f9a05d963fc0e9">llvm::APFloatBase::IEEEquad</a> and <a href="#a7da80f756644226c925de9aa4bf77d94">SystemZVectorConstantInfo</a>.</p>

</div>
</div>

### SystemZVectorConstantInfo() {#aa073d1e5ff2c5e5a53876841e1ff6fad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SystemZVectorConstantInfo::SystemZVectorConstantInfo (<a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode">BuildVectorSDNode</a> * BVN)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 843 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>, definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#ab7448e12bb2449435bddec7d9e00564a">llvm::BuildVectorSDNode::isConstant</a> and <a href="/web-llvm/docs/api/classes/llvm/buildvectorsdnode/#a6f89a07c015a54253416b726e352bdc4">llvm::BuildVectorSDNode::isConstantSplat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isVectorConstantLegal() {#ad6ba63ef6a9e69ae5ae03797b21964fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool SystemZVectorConstantInfo::isVectorConstantLegal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget">SystemZSubtarget</a> &amp; Subtarget)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 844 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>, definition at line 852 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea7bafe6b273a2e646673197555986f636">llvm::SystemZISD::BYTE_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a66191f0bcc8c62b784819e9e96ceeba2">llvm::countl_zero</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57d2f9ee99e9e68cff564d0d579c8163">llvm::countr_zero</a>, <a href="/web-llvm/docs/api/classes/llvm/systemzsubtarget/#a14dcf0fbd3cd8fd45c8f5e915ddfaead">llvm::SystemZSubtarget::getInstrInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#aded931e298cfa08b5038ca2b63c06bb8">llvm::MVT::getIntegerVT</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#abf8d0055af4879a302268d3f834b2be5">llvm::MVT::getVectorVT</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0ab75fcdd2d72d9e000beab48622402d93">llvm::Lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac3d063b3cfffeac6b26118598d1f8413">llvm::maskLeadingOnes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a79dff91526e31b1a05f59eed6c189eb4">llvm::maskTrailingOnes</a>, <a href="#a4ff1cd19df6c3e85d9548a659dc44ea3">Opcode</a>, <a href="#ab4e3980a04849dd0c23a6b3e652671cb">OpVals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea6ec607d4e1a29496a13bf2c88943e010">llvm::SystemZISD::REPLICATE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemzisd/#a24fe7decb4ebdd8b4c7a774d65fcaa7ea39e1c54eb43a73221817d060bf5f27a1">llvm::SystemZISD::ROTATE_MASK</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad12a58d7f81a304e0c568ad2210bc4fe">llvm::SignExtend64</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncopytocombine-cpp/#a1d40004718218dbdf06b496766299101">TII</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a6893db19648a2dba0912d181aaa57ec0a19de5b94f7b83900d4b296d9fa491aec">llvm::Upper</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a5e2f6288a79b32c4bc9f22fe3f3222b2">llvm::SystemZ::VectorBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/systemz/#a8100b30b39f455a1b99d9d421a5b8f3b">llvm::SystemZ::VectorBytes</a> and <a href="#a3989c66a3550ee570cbe7902b9b105e5">VecVT</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/systemztargetlowering/#aa2888a5dd9e69f6f268ef492db22f96c">llvm::SystemZTargetLowering::isFPImmLegal</a> and <a href="/web-llvm/docs/api/classes/anonymous-systemziseldagtodag-cpp-/systemzdagtodagisel/#a977ad76f842f5addf1b023121d96465e">anonymous{SystemZISelDAGToDAG.cpp}::SystemZDAGToDAGISel::Select</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Opcode {#a4ff1cd19df6c3e85d9548a659dc44ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZVectorConstantInfo::Opcode = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 835 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>


<p>Referenced by <a href="#ad6ba63ef6a9e69ae5ae03797b21964fd">isVectorConstantLegal</a>.</p>

</div>
</div>

### OpVals {#ab4e3980a04849dd0c23a6b3e652671cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;unsigned, 2&gt; llvm::SystemZVectorConstantInfo::OpVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 836 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>


<p>Referenced by <a href="#ad6ba63ef6a9e69ae5ae03797b21964fd">isVectorConstantLegal</a>.</p>

</div>
</div>

### VecVT {#a3989c66a3550ee570cbe7902b9b105e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MVT llvm::SystemZVectorConstantInfo::VecVT</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 837 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>


<p>Referenced by <a href="#ad6ba63ef6a9e69ae5ae03797b21964fd">isVectorConstantLegal</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### IntBits {#aaa158704919e38ddda0e7195c19170b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::SystemZVectorConstantInfo::IntBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 829 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>

</div>
</div>

### isFP128 {#abd94b90a72d89da7fdd8a2b9cdf62ec0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::SystemZVectorConstantInfo::isFP128 = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 833 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>

</div>
</div>

### SplatBits {#aa973e61e6942295bb5de2d9a7cdf960d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::SystemZVectorConstantInfo::SplatBits</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 830 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>

</div>
</div>

### SplatBitSize {#a905dd8fd348678ae42b5682232d9c557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::SystemZVectorConstantInfo::SplatBitSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 832 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>

</div>
</div>

### SplatUndef {#a4d5f5e20643e34cc5211363ff559934e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">APInt llvm::SystemZVectorConstantInfo::SplatUndef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 831 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-cpp">SystemZISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/systemz/systemzisellowering-h">SystemZISelLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
