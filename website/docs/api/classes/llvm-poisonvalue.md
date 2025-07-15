---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/poisonvalue
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PoisonValue` Class Reference

<p>In order to facilitate speculative execution, many instructions do not invoke immediate undefined behavior when provided with illegal operands, and return a poison value instead. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PoisonValue { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">llvm/IR/Constants.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/undefvalue">UndefValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>'undef' values are things that do not have specified contents. <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e3c9418e61b58dd0d1bdc34af8d687b">PoisonValue</a> (const PoisonValue &amp;)=delete</td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab86fe398be0856aae35e87971691282">PoisonValue</a> (Type *T)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92e67f7da40e1b5d1bf0163a6284fc45">getSequentialElement</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this poison has array or vector type, return a poison with the right element type. <a href="#a92e67f7da40e1b5d1bf0163a6284fc45">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91118060af65a58fffc1c8eb85912cb4">getStructElement</a> (unsigned Elt) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If this poison has struct type, return a poison with the right element type for the specified element. <a href="#a91118060af65a58fffc1c8eb85912cb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfec4ea2af1aceb0553bed871d24c67e">getElementValue</a> (Constant *C) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an poison of the right value for the specified GEP index if we can, otherwise return null (e.g. <a href="#adfec4ea2af1aceb0553bed871d24c67e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a750bda5b8bbe027514b4a11bebc5f806">getElementValue</a> (unsigned Idx) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an poison of the right value for the specified GEP index. <a href="#a750bda5b8bbe027514b4a11bebc5f806">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6544ddad8adb0fbe6ada8f073472c0e0">destroyConstantImpl</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the constant from the constant table. <a href="#a6544ddad8adb0fbe6ada8f073472c0e0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1bf08613fb664a2e377a9a72c59a6b66">get</a> (Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Static factory methods - Return an 'poison' object of the specified type. <a href="#a1bf08613fb664a2e377a9a72c59a6b66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a657063605eb064b7a1f6048aa53e25de">classof</a> (const Value *V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast: <a href="#a657063605eb064b7a1f6048aa53e25de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>In order to facilitate speculative execution, many instructions do not invoke immediate undefined behavior when provided with illegal operands, and return a poison value instead.</p>


<p>see LangRef.html#poisonvalues for details.</p>


<p>Definition at line 1460 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Constant {#a5bd16c2fbe755cda66b18d56761038ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1461 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#adfec4ea2af1aceb0553bed871d24c67e">getElementValue</a> and <a href="#a4e3c9418e61b58dd0d1bdc34af8d687b">PoisonValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PoisonValue() {#a4e3c9418e61b58dd0d1bdc34af8d687b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PoisonValue::PoisonValue (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/poisonvalue">PoisonValue</a> &amp;)</td>
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



<p>Definition at line 1468 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### PoisonValue() {#aab86fe398be0856aae35e87971691282}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PoisonValue::PoisonValue (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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



<p>Definition at line 1463 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getElementValue() {#adfec4ea2af1aceb0553bed871d24c67e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoisonValue * PoisonValue::getElementValue (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an poison of the right value for the specified GEP index if we can, otherwise return null (e.g.</p>


<p>if C is a <a href="/web-llvm/docs/api/classes/llvm/constantexpr">ConstantExpr</a>).</p>


<p>Declaration at line 1483 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1212 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>, <a href="#a92e67f7da40e1b5d1bf0163a6284fc45">getSequentialElement</a>, <a href="#a91118060af65a58fffc1c8eb85912cb4">getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getElementValue() {#a750bda5b8bbe027514b4a11bebc5f806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoisonValue * PoisonValue::getElementValue (unsigned Idx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return an poison of the right value for the specified GEP index.</p>

<p>Declaration at line 1486 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1218 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a92e67f7da40e1b5d1bf0163a6284fc45">getSequentialElement</a>, <a href="#a91118060af65a58fffc1c8eb85912cb4">getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>

</div>
</div>

### getSequentialElement() {#a92e67f7da40e1b5d1bf0163a6284fc45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoisonValue * PoisonValue::getSequentialElement ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this poison has array or vector type, return a poison with the right element type.</p>

<p>Declaration at line 1475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1202 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a1bf08613fb664a2e377a9a72c59a6b66">get</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#adfec4ea2af1aceb0553bed871d24c67e">getElementValue</a> and <a href="#a750bda5b8bbe027514b4a11bebc5f806">getElementValue</a>.</p>

</div>
</div>

### getStructElement() {#a91118060af65a58fffc1c8eb85912cb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoisonValue * PoisonValue::getStructElement (unsigned Elt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If this poison has struct type, return a poison with the right element type for the specified element.</p>

<p>Declaration at line 1479 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1208 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>References <a href="#a1bf08613fb664a2e377a9a72c59a6b66">get</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>.</p>


<p>Referenced by <a href="#adfec4ea2af1aceb0553bed871d24c67e">getElementValue</a> and <a href="#a750bda5b8bbe027514b4a11bebc5f806">getElementValue</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### destroyConstantImpl() {#a6544ddad8adb0fbe6ada8f073472c0e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PoisonValue::destroyConstantImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the constant from the constant table.</p>

<p>Declaration at line 1465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1887 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a657063605eb064b7a1f6048aa53e25de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PoisonValue::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * V)</td>
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

<p>Definition at line 1489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>.</p>

</div>
</div>

### get() {#a1bf08613fb664a2e377a9a72c59a6b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PoisonValue * PoisonValue::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Static factory methods - Return an 'poison' object of the specified type.</p>

<p>Declaration at line 1471 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a>, definition at line 1878 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad6aa61c7462784d1c9641ee501486375">llvm::InstCombinerImpl::addDeadEdge</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#ad63e788f18762973cf9f3690fd4bbfb1">llvm::fuzzerop::anyPtrType</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#af83167f66d93e94ff003e7a130b823f0">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildLookupTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/phihandler/#a013e27220db7b26ed5f0da4841c58431">anonymous{SLPVectorizer.cpp}::PHIHandler::buildOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/valuetracking-cpp/#a9ef49346139404db3757cf8ba05dc6f2">BuildSubAggregate</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a531ccf4e0c3fa8eba4a36bd8ebaad93d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildSwLDSGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a6e6cf92e2cfe0eb48abec55606e0481e">canonicalizeInsertSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#adbe30a5e0e6f5dc00dac4c72dbffb905">canProveExitOnFirstIteration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a97370114df349e0996f133e3402c1595">llvm::changeToUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/scevexpandercleaner/#ab714e94c2ba068bbd6882e560cef94e2">llvm::SCEVExpanderCleaner::cleanup</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae1a030c9a70b99fced16cc726e1ef9f9">llvm::CloneAndPruneIntoFromInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a1e502a1ec39cc64d6b86e9e68b29be89">collectShuffleElements</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a739e3cd7494ba55179722c33498e8462">llvm::InstCombinerImpl::commonIDivRemTransforms</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a1c2f554e869a846f16966f6dc06f80ee">llvm::ObjectSizeOffsetEvaluator::compute</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-scalarizer-cpp-/#a292d6186af223db779aa1afa036a509e">anonymous{Scalarizer.cpp}::concatenate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#a4ebed10d3e842e81a2df6974c2fd3760">ConnectEpilog</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/loopunrollruntime-cpp/#af700561cb065af85122cd321d6c4b989">ConnectProlog</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af6674e64f01f197cffff55abcc6d2050">llvm::ConstantFoldBinaryInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad797efb6c6fbbb2038d5ed8f8379561f">llvm::ConstantFoldCastInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a293a0cb64e182e693cdd406f8da7ced5">llvm::ConstantFoldCompareInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9f6c692bb79cca65ae3097ddd4c47e69">llvm::ConstantFoldExtractElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a491cbe61681e7c63ac7d01ce209a4682">llvm::ConstantFoldGetElementPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7bf95d0980fad19452f4c9aca445af3f">llvm::ConstantFoldInsertElementInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a72190dad796891a1a5a59d64044000dc">anonymous{ConstantFolding.cpp}::ConstantFoldIntrinsicCall2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8f2a6934eba2671f2fe2a121f2e9e4e9">llvm::ConstantFoldLoadFromConst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a65bb0005c2f40b94623bae2e9a51fe48">llvm::ConstantFoldLoadFromUniformValue</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#aa8f5a312c9865602c873621adc9d8a18">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall1</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a505a295564c761e2006b8e48647f6f7d">anonymous{ConstantFolding.cpp}::ConstantFoldScalarCall3</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a86456cb345c788177fa0b43a40519723">anonymous{ConstantFolding.cpp}::ConstantFoldScalarFrexpCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a11c89e0918b007ef2cf1d6b03c4b4948">llvm::ConstantFoldSelectInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#addd1c6bc523b9a0eb56167da95dc5156">llvm::ConstantFoldShuffleVectorInstruction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a7d0da22d172cf90028dcf5fdc8ff2cb8">anonymous{ConstantFolding.cpp}::constantFoldVectorReduce</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8946e172b10c0ef5eaebb28ebb7662ad">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a82984d4a91e7dc2072dfd8fad2854618">llvm::ConvertDebugDeclareToDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a125e2946cdcc7555d8f5c383681d7097">convertMetadataToAssumes</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/reassociate-cpp/#a5ccdf0465e957f46ac1241b63af00864">ConvertShiftToMul</a>, <a href="/web-llvm/docs/api/classes/llvm/shufflevectorinst/#ad06dcf793a8b91871327c682d6f3f909">llvm::ShuffleVectorInst::convertShuffleMaskForBitcode</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a7f4eefe9cb1d01508cce70c0aa9a9595">llvm::IRBuilderBase::CreateAggregateRet</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/mergefunctions-cpp/#ab4a9c9cd80e2c3ac08362429976322cf">createCast</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a7ea782436f7a688ebb717a91808b9c5d">llvm::AArch64TargetLowering::createComplexDeinterleavingIR</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a137cd0f2afc485fd5275c0cbfaaba6bb">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a17320ebd77e834577a5ebd1063039625">llvm::IRBuilderBase::CreateInsertElement</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ad878957c30eb65983e09b60edb0e1a1b">llvm::IRBuilderBase::CreateMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#afa922043d31aa2d3410fe0be8791b795">llvm::IRBuilderBase::CreateMaskedGather</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a483f68557374e8fc58f8a294e7f1268e">llvm::IRBuilderBase::CreateMaskedLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab464550d233a70bf18d772d204549342">llvm::InstCombinerImpl::CreateNonTerminatorUnreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecalls-cpp/#a0fd31d83dea2eadb6986c2dc8b8bd3f0">createOverflowTuple</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/instructions-cpp/#a2c53fab823052ea1278853d24a9d2731">createPlaceholderForShuffleVector</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/baseshuffleanalysis/#a8437f11cfb708e9bb288796d123e84dc">anonymous{SLPVectorizer.cpp}::BaseShuffleAnalysis::createShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a69d7b94a9dade6f0d2fd7e0b65926bf0">llvm::IRBuilderBase::CreateShuffleVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#ae919aab2dcdca2fcb21214e33822c838">createTblShuffleForSExt</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#a93cdde383eeeb3fb45851d9660891a5f">createTblShuffleForZExt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a32f45ac41ff64c32a157182ce87e6057">llvm::IRBuilderBase::CreateVectorSplat</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyfixfunctionbitcasts-cpp/#a96fb322d124e55de8f0fa2fe7e19e175">createWrapper</a>, <a href="/web-llvm/docs/api/structs/anonymous-deadstoreelimination-cpp-/dsestate/#a32e5e2e67b52bcd45fef4487f664f9ec">anonymous{DeadStoreElimination.cpp}::DSEState::deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#aebc62faf59fecc07e8471fcf035d789e">deleteDeadInstruction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a74b422e2c15d859ba49911cc329f11d7">llvm::deleteDeadLoop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopdeletion-cpp/#a49a9acd58935033c9716f1b45d7df68a">deleteLoopIfDead</a>, <a href="/web-llvm/docs/api/classes/anonymous-codegenprepare-cpp-/simplificationtracker/#a510bd9f9dcdaa582836018148bc749c0">anonymous{CodeGenPrepare.cpp}::SimplificationTracker::destroyNewNodes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22b952b9d905fdd3aaedbc2ebf426339">llvm::detachDeadBlocks</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumesimplify/#a0879506ce04a79b173daca40d1967e35">anonymous{AssumeBundleBuilder.cpp}::AssumeSimplify::dropRedundantKnowledge</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifyindvar-cpp-/simplifyindvar/#a6f5eb28a130d94e94dff2f9e798617ab">anonymous{SimplifyIndVar.cpp}::SimplifyIndvar::eliminateTrunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-assignmenttrackinganalysis-cpp-/assignmenttrackinglowering/#a81d863ec17163a5dcedc09cb1a48aadf">anonymous{AssignmentTrackingAnalysis.cpp}::AssignmentTrackingLowering::emitDbgValue</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a5bb62631ba6a4be0ae02f7365ee4a7d7">ensureValueAvailableInSuccessor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/hipstdpar/hipstdpar-cpp/#a6886c083f54f94933453834401b0e964">eraseFromModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a06358c30f3e98d9e57f4ae9162f33c72">evaluateInDifferentElementOrder</a>, <a href="/web-llvm/docs/api/structs/llvm/vpfirstorderrecurrencephirecipe/#a141e9946f635323d4da5e8b4b3f64e44">llvm::VPFirstOrderRecurrencePHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpinterleaverecipe/#ab0d48fabf61af227821d568b1c3aa4ca">llvm::VPInterleaveRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vppredinstphirecipe/#a3e63796e123d5ba9cbfa023983328c37">llvm::VPPredInstPHIRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/vpreplicaterecipe/#a2ed5b7b284097278ee4e550897b1f057">llvm::VPReplicateRecipe::execute</a>, <a href="/web-llvm/docs/api/structs/llvm/vpwidenloadrecipe/#a7c2b787dbd70d3fbd4f3699342eec925">llvm::VPWidenLoadRecipe::execute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a017054a3231506db436fdd9e8ae20ca0">llvm::expandUser</a>, <a href="/web-llvm/docs/api/classes/llvm/callgraphupdater/#adecede763aee9d37e00fee2c2328ac7e">llvm::CallGraphUpdater::finalize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a3945796ab2f46a6790343e4c6230cdc5">findBasePointer</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a45a66620cecb92a4ffdc36042859c575">llvm::RandomIRBuilder::findOrCreateGlobalVariable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab09fc7dee4f7e02c60f7a9c928dc1603">llvm::findScalarElement</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acad657182350311f85bc33387733e506">llvm::InstCombinerImpl::foldAggregateConstructionIntoAggregateReuse</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#a01aa2c4724ae9bf421d1cfff3a1c7fa5">foldConstantInsEltIntoShuffle</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#aabb5edbf6f79b04ce152f73869c1a4aa">llvm::InstCombinerImpl::foldDeadPhiWeb</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinevectorops-cpp/#ad3259dc4dae742caac6c6e4f577d1760">foldInsSequenceIntoSplat</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-constantfolding-cpp-/#a6cb1fc4464f12007218608fadbe3a3f4">anonymous{ConstantFolding.cpp}::FoldReinterpretLoadFromConst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab7e8be1d1ae7e526ea156b60c51c10e5">llvm::FoldSingleEntryPHINodes</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acbf4c17d9f1b9f6729602a3c2a6c5b9d">llvm::InstCombinerImpl::foldVectorBinop</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lcssa-cpp/#a03040e4a441982ab96f070a7f03cc910">formLCSSAForInstructionsImpl</a>, <a href="/web-llvm/docs/api/classes/boupslp/shufflecostestimator/#a7d3b40cff3ff8c00007cf9a3f0d785f1">llvm::slpvectorizer::BoUpSLP::ShuffleCostEstimator::gather</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/poisonvalue/#af4063c638dea7ebee43ca1d5aea1be10">llvm::sandboxir::PoisonValue::get</a>, <a href="/web-llvm/docs/api/structs/llvm/vptransformstate/#a48955fd76dc29a6b4391aef55ce3efd3">llvm::VPTransformState::get</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a6553e4e7f2cae85df3c310267a3797c9">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a8d9ad0ef3d9122df6d6b4007c519c61e">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinesimplifydemanded-cpp/#a110a1ec9644da2c1cd2d4068be8199db">getFPClassConstant</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abab34b1cb73af8519772979270773492">llvm::SPIRVGlobalRegistry::getOrCreateConstIntArray</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64ttiimpl/#a338bc4206ec4d19d62a2567d60c9c36c">llvm::AArch64TTIImpl::getOrCreateResultFromMemIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdatertraits-7a064c1d92ba5b8b002a38239caa8eb3/#a9c944a235e8f62b5ed7b459ce1f01072">llvm::SSAUpdaterTraits&lt; SSAUpdater &gt;::GetPoisonVal</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#ab2c5c3c0b3cd0db8b0692df8f66b6264">llvm::slpvectorizer::BoUpSLP::getReorderingData</a>, <a href="#a92e67f7da40e1b5d1bf0163a6284fc45">getSequentialElement</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="#a91118060af65a58fffc1c8eb85912cb4">getStructElement</a>, <a href="/web-llvm/docs/api/classes/llvm/ssaupdater/#a5b0e45dbba53e985f1b9c532fb5f200b">llvm::SSAUpdater::GetValueInMiddleOfBlock</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopstrengthreduce-cpp/#a7c340cc26f0c6d27219747cac55a2dc2">getValueOrPoison</a>, <a href="/web-llvm/docs/api/namespaces/llvm/aa/#af967a81762eaaf67f292abee4a00180c">llvm::AA::getWithType</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a9890e049561cd883603c6a483547b6b5">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::handleArithmeticWithOverflow</a>, <a href="/web-llvm/docs/api/classes/llvm/diarglist/#a262bd33fc97cc729eb9418cc281dc69d">llvm::DIArgList::handleChangedOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/debugvalueuser/#a51231385e9897d93b6ff7af9c96d1036">llvm::DebugValueUser::handleChangedValue</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ac42eef26cc4185a8932bc59a94dc5d16">llvm::SelectionDAGBuilder::handleKillDebugValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab7881567f602c3a94d11e2817f4464e0">handleNoSuspendCoroutine</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a352cde174c12aa24afbb7e61c22853e2">llvm::InstCombinerImpl::handleUnreachableFrom</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5698394aeae942bfac76f1f7ac4d31a7">llvm::handleUnreachableTerminator</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#ace87755a2044122196774c1cb0368fde">llvm::PHINode::hasConstantValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-structurizecfg-cpp-/structurizecfg/#a88fa969de8279bbac9d3718775723b50">anonymous{StructurizeCFG.cpp}::StructurizeCFG::init</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvregularizer-cpp/#a70c9d5004bb64ce7c4ed2dab4acda63b">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpucodegenprepare-cpp/#a33b84baa49efc1f81ba74a43da0119b5">insertValues</a>, <a href="/web-llvm/docs/api/classes/llvm/gcnttiimpl/#ae3d1835a72f8f0ba85ace9e2c0fbfc96">llvm::GCNTTIImpl::instCombineIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#afdcb3be103dc32527286d0352eeacdd6">instCombineSVEDupqLane</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targettransforminfo-cpp/#aac6aaf36d8c34dfd27b90fc04ea3c08f">instCombineSVEUzp1</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ae365293b0e4b5cb45b3af280d14b26f1">llvm::coro::Shape::invalidateCoroutine</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acab8f775ddc87695d750e4838231b3ba">llvm::isBytewiseValue</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstant/#ga535ca788cbaf067df347ec6e46939616">LLVMGetPoison</a>, <a href="/web-llvm/docs/api/structs/anonymous-corocleanup-cpp-/lowerer/#ae8263688979f1e86bc684abf99f43d61">anonymous{CoroCleanup.cpp}::Lowerer::lower</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac306f2130698421f64f8a139faf38675">llvm::lowerAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#adcc5d5714e94674aee99aacd991d2b4a">llvm::RISCVTargetLowering::lowerDeinterleaveIntrinsicToLoad</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#ab3118e33ed28deca370645b8b909fa5a">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::lowerDotProduct</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a8f69a29bf679c53a8703f5497bba92b2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerDynamicLDSVariables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/llvm/riscvtargetlowering/#a22c6a7a1925a0177519e33d49ba91cea">llvm::RISCVTargetLowering::lowerInterleaveIntrinsicToStore</a>, <a href="/web-llvm/docs/api/classes/llvm/intrinsiclowering/#a065baf0b078aae98e7c9703d6717e15e">llvm::IntrinsicLowering::LowerIntrinsicCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#aadb2a52a94fd7cf1e3f1643e0f5e2934">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::LowerTranspose</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a5172beb0382e24b2305c8bc0e46ee1f4">llvm::fuzzerop::makeConstantsWithType</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a7d5502a6047fb27d6c33ea2820608c2c">anonymous{ValueMapper.cpp}::Mapper::mapValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa16cddaa1497dc3248fc105467671e82">llvm::MergeBasicBlockIntoOnlyPred</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a4055f1bab55c76c243c3bf42c1a7e45a">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::needToDelay</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a679d0966b3083f647af785f24936d3d9">llvm::RandomIRBuilder::newSink</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#a9ace593776041510de450a2eccc56eeb">operandWithNewAddressSpaceOrCreatePoison</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scatterer/#a89022818687b50b315688ecb5b41b9b5">anonymous{Scalarizer.cpp}::Scatterer::operator[]</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombinecasts-cpp/#a75e6b6bf03adf614aaf100a9afdcd612">optimizeVectorResizeWithIntegerBitCasts</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a7bc472aa7f200453c2fb1d5fbc404b66">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::populateSwMetadataGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a51dffbda74e47e34a64858d09d456108">llvm::InstCombinerImpl::prepareWorklist</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/correlatedvaluepropagation-cpp/#a25e3db50d3aa8a3fa245e3c2d3197d7a">processOverflowIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpupromotealloca-cpp/#aff60d107b0bf41de42918c5bf046d8c3">promoteAllocaUserToVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae8cc923f4e20540201f1cd1225811b9f">llvm::promoteLoopAccessesToScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a6952450f0726bd9c26d303743522e227">promoteSingleBlockAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/controlflowutils-cpp/#a1f69c303174793beec42b1ebaf13cfb6">reconnectPhis</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad3cf19784335900227e275fd488e4727">llvm::RecursivelyDeleteDeadPHINode</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a1c9e22b633ee4e0727bba3c87db57296">llvm::removeAllNonTerminatorAndEHPadInstructions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#aedfe10b7b8a1008ddaa4104f54e0b483">removeEmptyCleanup</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a6f01dbe965b38186b1a78378689d4105">llvm::PHINode::removeIncomingValue</a>, <a href="/web-llvm/docs/api/classes/llvm/phinode/#a5197ef3eec835595e81bcecb4ee02969">llvm::PHINode::removeIncomingValueIf</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#acc169700a214095e0dca03c99ba3a9eb">llvm::InstCombinerImpl::removeInstructionsBeforeUnreachable</a>, <a href="/web-llvm/docs/api/classes/anonymous-loopdistribute-cpp-/instpartition/#a0f5acddf8fa1936f68b72eed3a1de362">anonymous{LoopDistribute.cpp}::InstPartition::removeUnusedInsts</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a14c12bda1f5a9beed612b00f3f98b888">llvm::reorderScalars</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#af678f41709f265e2589f247e883aa738">replaceAsyncResumeFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a84fbc09723655416fad6677d7fdaf8a6">replaceFallthroughCoroEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombiner/#a49f1bd0bdf0ef741bdd714cc1188d7c5">llvm::InstCombiner::replaceInstUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#accee5b18a5d340c2e2aa6ec426df1778">llvm::coro::BaseCloner::replaceRetconOrAsyncSuspendUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#ac26a57370fde8e7b017b6094a9216b77">replaceSubOverflowUses</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aavaluesimplifyimpl/#a450c2f1a2d1c2e08bf66297247baa964">anonymous{AttributorAttributes.cpp}::AAValueSimplifyImpl::reproduceValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#aa231a7e6d411bd4797afdd6f0a1f8d6a">rewriteSingleStoreAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looprotationutils-cpp/#aea660fd3de70e7854de06b7e212f0ecd">RewriteUsesOfClonedInstructions</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuunifydivergentexitnodes-cpp-/amdgpuunifydivergentexitnodesimpl/#a9779d04b57fa01538e274e830110337f">anonymous{AMDGPUUnifyDivergentExitNodes.cpp}::AMDGPUUnifyDivergentExitNodesImpl::run</a>, <a href="/web-llvm/docs/api/structs/anonymous-promotememorytoregister-cpp-/promotemem2reg/#a31d32412508ee492e69d8695f88e6dcf">anonymous{PromoteMemoryToRegister.cpp}::PromoteMem2Reg::run</a>, <a href="/web-llvm/docs/api/classes/llvm/loadandstorepromoter/#ac1da68baf80229b2d8af34499eb1c73f">llvm::LoadAndStorePromoter::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/sccp-cpp/#ab5b6f145d9308f4847a1b618123d2704">runIPSCCP</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargedivrem-cpp/#a5c0f04dd919f2fa52e52f277a68b1ac1">scalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/expandlargefpconvert-cpp/#a6b532a3420c46c6194f80f8590cd7689">scalarize</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/scalarizemaskedmemintrin-cpp/#a144649d7f3db9e7517d70398cde534d8">scalarizeMaskedExpandLoad</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a021e32e2bf67f331d9384a162dc402c2">anonymous{WholeProgramDevirt.cpp}::DevirtModule::scanTypeCheckedLoadUsers</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgassignintrinsic/#a77fca2c3fdf25a035739378ae30ec9d8">llvm::DbgAssignIntrinsic::setKillAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a9b641aa0b6a8f401fff5ba3675467835">llvm::DbgVariableRecord::setKillAddress</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariableintrinsic/#aaf2539583fcfa83b3ecdfc1fea52cff6">llvm::DbgVariableIntrinsic::setKillLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/dbgvariablerecord/#a7ec36aa642cfbc3756fab37cc97d0f86">llvm::DbgVariableRecord::setKillLocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpuinstcombineintrinsic-cpp/#aae1a4eb9b437e719a333c79f74c9a1b2">simplifyAMDGCNMemoryIntrinsicDemanded</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab720ac4c86a5f16a755b1e5cd0d32c80">llvm::simplifyBinaryIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3cc3d823b751599d37440440bd06096c">llvm::simplifyCall</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a98e8d1806c78a1e84fa32e50a41a8a62">llvm::InstCombinerImpl::SimplifyDemandedUseFPClass</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a37cce7aa1875173688e5971c5d6fa9e0">llvm::InstCombinerImpl::SimplifyDemandedVectorElts</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a2d67c7fd2789ef1dfb05513f1eb8d054">simplifyDiv</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a789b1341fc862e30623b200657911a4c">simplifyDivRem</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a48ebda753879b3d5d55fa0e1566b5439">simplifyExtractElementInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a110a350e37f3cc2ed2c603c3efde0a30">simplifyFCmpInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a7ae2d2701ffe4abf529cd4fb1ca26049">simplifyFDivInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aa6498365e4fa2bc006fc4116b4b9b990">simplifyFPOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#aab8aaa8e44e0609f7d3e9ae822f11f7e">simplifyGEPInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a47a81cb5e93cfda95b1de100dd5b9919">simplifyICmpInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abdf4b5f9e1dc6887cac393ee643c10b6">llvm::simplifyInsertElementInst</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a57feb935aaafd1bd4bfbb8dc56ad2129">llvm::simplifyInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/jumpthreadingpass/#a064ce69a10374b5342954d481e21fa25">llvm::JumpThreadingPass::simplifyPartiallyRedundantLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a308de6b87d4d431477642d086b268a7c">simplifyPHINode</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a38dc339806a701c1f11ec31cf76936ff">simplifySelectInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#ae9d2883e296d808c7a9e18efcee71049">simplifyShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0bf04415ab72b83b24140635c6a7ea52">simplifyShuffleVectorInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/instructionsimplify-cpp/#a0e278bb318fd700a9c8d4f4a7c8caba9">simplifySubInst</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a1ecff7a038229dccedd3fb1aba929059">simplifyX86addcarry</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/licm-cpp/#a52b8b307321627e612e77041260ece84">sink</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a4a27a121df43e5e1735eb5781de56594">llvm::fuzzerop::sizedPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ac8cb4401526dd424f15566e4501792f7">llvm::InstCombinerImpl::SliceUpIllegalIntegerPHI</a>, <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred/#ac01e1d16c27a5fb94153178d64b252c6">llvm::fuzzerop::SourcePred::SourcePred</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a32b5360bb5f3831163d348fc96fc1198">llvm::fuzzerop::splitBlockDescriptor</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/basicblockutils-cpp/#a02eb00498005806a0e45ac2b5b13fc70">SplitBlockPredecessorsImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/anyretconabi/#adc7bbccb30409488c60813454af8c81d">llvm::coro::AnyRetconABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalsplit-cpp/#aa0b982cd11d8eef0277074095aca3b43">splitGlobal</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a1616baf1b22efae9f17bb3d499ac8931">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::storePrimitiveShadowOrigin</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a2bf12026ed9de594d2117077b422c24d">stripNonValidDataFromBody</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifycfg-cpp/#a4abbfca67cb7fc77432aa8cd48af8b0a">switchToLookupTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-slpvectorizer-cpp-/horizontalreduction/#ab1f9d3b9bc61d6ec2606916f8d7b92f4">anonymous{SLPVectorizer.cpp}::HorizontalReduction::tryToReduce</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#aa0014a4c2da32289f871b8d5a1aa538b">unpackLoadToAggregate</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/autoupgrade-cpp/#af61729415c4cfec66c791cd52a532eb9">upgradeX86IntrinsicCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#a1fdfe91f1f9e82078936d0cde2af8a3f">validShuffleVectorIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/slpvectorizer/boupslp/#a99b79343fdc586cce804ebabf3d419e2">llvm::slpvectorizer::BoUpSLP::vectorizeTree</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a49a46654ca2c32ce99be52de089052f8">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::Visit</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ae289e620828eabb1dfe34c9ad322a81d">llvm::InstCombinerImpl::visitAllocSite</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#abf86ae2ede168d53dec70f0b0cb9d9b5">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitAtomicCmpXchgInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#a1cbb1fa4211e94aed86925b13569004a">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitBinaryOperator</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a16eb5732b0dacdde9b666ba69f630a16">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a71ef354bd1ea9e02d70146d7218a7d39">llvm::InstCombinerImpl::visitExtractElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a687fa4390149f0cb751d8ad89dca6a3c">llvm::InstCombinerImpl::visitInsertElementInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a3ba96a0d49ec5f1a062b075f54536a3c">llvm::InstCombinerImpl::visitLoadInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpucodegenprepare-cpp-/amdgpucodegenprepareimpl/#aef67bcdb0247f9b4b984725fa065e1ce">anonymous{AMDGPUCodeGenPrepare.cpp}::AMDGPUCodeGenPrepareImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a752efe4724ac3a97d07ee81d5f779c92">llvm::InstCombinerImpl::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetevaluator/#a9a06c7811f1ea67a51787ab0de806b5a">llvm::ObjectSizeOffsetEvaluator::visitPHINode</a>, <a href="/web-llvm/docs/api/classes/anonymous-scalarizer-cpp-/scalarizervisitor/#a22ba91d5d49420a24b01342672953762">anonymous{Scalarizer.cpp}::ScalarizerVisitor::visitShuffleVectorInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ad31108b4f7156db7565eadba1285c93a">llvm::InstCombinerImpl::visitShuffleVectorInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a8042dd4cb7e9772368f2808b8db577be">llvm::InstCombinerImpl::visitStoreInst</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/constants-h">Constants.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/constants-cpp">Constants.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
