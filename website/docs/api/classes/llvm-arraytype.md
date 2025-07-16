---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/arraytype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ArrayType` Class Reference

<p>Class to represent array types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::ArrayType { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">llvm/IR/DerivedTypes.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The instances of the <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> class are immutable: once they are created, they are never changed. <a href="/web-llvm/docs/api/classes/llvm/type/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a062228af5c9ff6c9536659fa7f8b5e">ArrayType</a> (const ArrayType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7318202059d0a323927ad1243b41f1aa">ArrayType</a> (Type *ElType, uint64_t NumEl)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a466d30ddfb1738350f69a19a850e7606">operator=</a> (const ArrayType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c35bd7a4fa08845607033aecc94423d">getNumElements</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed75da684d36221f1f7b9fbf5aa3aed8">getElementType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb65279052d83896c57a06bde0bcffac">ContainedType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The element type of the array. <a href="#aeb65279052d83896c57a06bde0bcffac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2030659baf30e124aa7df89e112a5e4a">NumElements</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Number of elements in the array. <a href="#a2030659baf30e124aa7df89e112a5e4a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309fed0882f9d27038ff2df2afed7a00">get</a> (Type *ElementType, uint64_t NumElements)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method is the primary way to construct an <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a>. <a href="#a309fed0882f9d27038ff2df2afed7a00">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279315ff6072c1cd5cbdff45ff97dc44">isValidElementType</a> (Type *ElemTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified type is valid as a element type. <a href="#a279315ff6072c1cd5cbdff45ff97dc44">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcb3a90e2a542325f4ac76f7154be648">classof</a> (const Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast. <a href="#adcb3a90e2a542325f4ac76f7154be648">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to represent array types.</p>

<p>Definition at line 395 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ArrayType() {#a9a062228af5c9ff6c9536659fa7f8b5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ArrayType::ArrayType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> &amp;)</td>
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



<p>Definition at line 404 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ArrayType() {#a7318202059d0a323927ad1243b41f1aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType::ArrayType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElType, uint64_t NumEl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 401 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a466d30ddfb1738350f69a19a850e7606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType &amp; llvm::ArrayType::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> &amp;)</td>
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



<p>Definition at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getElementType() {#aed75da684d36221f1f7b9fbf5aa3aed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::ArrayType::getElementType ()</td>
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



<p>Definition at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abab34b1cb73af8519772979270773492">llvm::SPIRVGlobalRegistry::getOrCreateConstIntArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af9ea314c7ebcfef667f1d7b67fe09c69">llvm::getPointerAtOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ade8f600187cb9c664701443e796111e7">llvm::isGEPBasedOnPointerToString</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>.</p>

</div>
</div>

### getNumElements() {#a1c35bd7a4fa08845607033aecc94423d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ArrayType::getNumElements ()</td>
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



<p>Definition at line 407 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1ca1f5b41c1408be83df43ab024cdd69">createRelLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#abab34b1cb73af8519772979270773492">llvm::SPIRVGlobalRegistry::getOrCreateConstIntArray</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#acf0b1898efd7f81a078e9288befd9290">llvm::DataLayout::getTypeSizeInBits</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a4f18aa17f81c88c8fa89c76563a6d510">tryWidenGlobalArraysUsedByMemcpy</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#ae73e475ff9414b97c6ad36f601179133">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitGetElementPtrInst</a> and <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### ContainedType {#aeb65279052d83896c57a06bde0bcffac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::ArrayType::ContainedType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The element type of the array.</p>

<p>Definition at line 397 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

### NumElements {#a2030659baf30e124aa7df89e112a5e4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::ArrayType::NumElements</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Number of elements in the array.</p>

<p>Definition at line 399 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#adcb3a90e2a542325f4ac76f7154be648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::ArrayType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Methods for support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 417 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa2989d3024a84b4dda9d77419b1648554">llvm::Type::ArrayTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### get() {#a309fed0882f9d27038ff2df2afed7a00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType * llvm::ArrayType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, uint64_t NumElements)</td>
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

<p>This static method is the primary way to construct an <a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a>.</p>

<p>Definition at line 411 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#a0644a32bfd97560ac89c5d6e9b0bf7ac">anonymous{CoroFrame.cpp}::FrameTypeBuilder::addFieldForAlloca</a>, <a href="/web-llvm/docs/api/namespaces/llvm/memtag/#acc2528429e7e0eb707ca49e72bb3ce49">llvm::memtag::alignAndPadAlloca</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroannotationelide-cpp/#aefcb18d60b47720b919eb6b0ce98b05e">allocateFrameInCaller</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a8508f3dbb1f9429445f50282297b4f9a">appendToGlobalArray</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a24f2551aaa1c96b279e792995deddd7f">appendToUsedList</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#af83167f66d93e94ff003e7a130b823f0">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildLookupTable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aed92c21265205e69855b23b8b25707e2">llvm::buildNDRange</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#ae277c85704c17a21f772da0aee54fbaa">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSBaseTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a3c3a71194fc12f9298575a42187928bd">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildNonKernelLDSOffsetTable</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad6c0f52a75bef49176db797774e8dc2c">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::buildRepresentativeDynamicLDSInstance</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#aa77b090b37b4ec17f23bff77ba62ed47">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::buildSwDynLDSGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/lib/target/directx/directxirpasses/pointertypeanalysis-cpp/#a86d26a3e2f2b7996916c7040cd7b40b4">classifyConstantWithOpaquePtr</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#aba3432b49d9f33e6eb7fbb4657b662b6">llvm::SanitizerStatReport::create</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a98d7c2e28dffebb3542fd7c608e6b4cc">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::createAllocaForLayout</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a6f467de3ca984f069ee86b9558388294">anonymous{OffloadWrapper.cpp}::createBinDesc</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#a4e632566b9002891ab9f5a108f3bd803">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/xcore/xcorelowerthreadlocal-cpp/#af90802d766d5ebfd966a6edbbf051331">createLoweredType</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a544a84c75ac55356516cc7365cbe6f02">llvm::OpenMPIRBuilder::createMapperAllocas</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab1aa0d632549db4855d6412f4d2d44ae">llvm::OpenMPIRBuilder::createOffloadMapnames</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a6e2bd6420d3d12339e32d4d1b3ba1394">llvm::OpenMPIRBuilder::createOrderedDepend</a>, <a href="/web-llvm/docs/api/structs/anonymous-instrorderfile-cpp-/instrorderfile/#a3b3620fdf60408799b2d1957707a81d2">anonymous{InstrOrderFile.cpp}::InstrOrderFile::createOrderFileData</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/rellookuptableconverter-cpp/#a1ca1f5b41c1408be83df43ab024cdd69">createRelLookupTable</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#a046c6262fc6fc6743bf539c87761083f">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#ad9c37680a58c2590f08d938aa1a44d6c">anonymous{CoroElide.cpp}::CoroIdElider::elideHeapAllocations</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a654b33adee2ae78ce74ecbe6aa5e5282">llvm::OpenMPIRBuilder::emitMapperCall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a827b80924bcd29f32b772a4ed162fb68">llvm::OpenMPIRBuilder::emitNonContiguousDescriptor</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a9702d30c99a5459e9565631adf1fdf1b">emitTaskDependencies</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a3bb33831dbcaa836f630ed1dc986b5c2">llvm::OpenMPIRBuilder::emitUsed</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroframe-cpp-/frametypebuilder/#abe0dacfb2237ff8fb43d5ad22ac45d5f">anonymous{CoroFrame.cpp}::FrameTypeBuilder::finish</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilflattenarrays-cpp/#ab655865aaad374f00365011edc7440da">flattenGlobalArrays</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a6553e4e7f2cae85df3c310267a3797c9">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a8d9ad0ef3d9122df6d6b4007c519c61e">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::getAddressesOfVariablesInKernel</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a6eec77c77aa76611db6766a3f205570c">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a54e552ee615150b4efe5195ac45d4389">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a3d4228cf6f5c478449deca90c6ce2255">llvm::ConstantDataArray::getFP</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a49e1f0512e7d7b37dfcecc0b25dd875b">llvm::OpenMPIRBuilder::getKernelArgsVector</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/loopidiomrecognize-cpp/#a52ab2351fc0de7ffe5198fd144d98f8b">getMemSetPatternValue</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowermatrixintrinsics-cpp-/lowermatrixintrinsics/#a7d8410ca3fc6fb227416067d3c2535d2">anonymous{LowerMatrixIntrinsics.cpp}::LowerMatrixIntrinsics::getNonAliasingPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#af023297673da795cc027d7aa8fd62817">llvm::offloading::getOffloadEntryArray</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#ae5869468359515f460a588357f1737cf">llvm::SPIRVGlobalRegistry::getOrCreateSPIRVArrayType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#ad86e02b5bee8ad12233bbf1719d1312f">llvm::ConstantDataArray::getRaw</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#a03dd63ac617c1242b7694a4b0ae4ed25">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::getShadowTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/sroa-cpp/#ad866ad1da941867a398da262103469b1">getTypePartition</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypesequential/#gabd1666e080f693e1af0b4018005cd927">LLVMArrayType</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypesequential/#gacee4abb63e2f9e0a2d7aa34d7ac19d99">LLVMArrayType2</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantcomposite/#ga1d0b985a92eb99f65e9bc4e1984ea800">LLVMConstArray</a>, <a href="/web-llvm/docs/api/groups/llvmccorevalueconstantcomposite/#ga3e37d5cc97d6e4da63f6eaa22e469075">LLVMConstArray2</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a8f69a29bf679c53a8703f5497bba92b2">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerDynamicLDSVariables</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/expandedcallframe/#aaf4615da5bb69a28fd2496f9248881bd">anonymous{ExpandVariadics.cpp}::ExpandVariadics::ExpandedCallFrame::padding</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a56b5a0fa4891dca73946affd4e6e3ffd">removeFromUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxiloplowering-cpp-/oplowerer/#a583a2a6c920de4695807c6ad35c5e35d">anonymous{DXILOpLowering.cpp}::OpLowerer::replaceResRetUses</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxildatascalarization-cpp/#af77de517fc151a087b7880eb50efe49e">replaceVectorWithArray</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-r600openclimagetypeloweringpass-cpp-/r600openclimagetypeloweringpass/#acf970c313d62e284e7c40d5dfddb1ccb">anonymous{R600OpenCLImageTypeLoweringPass.cpp}::R600OpenCLImageTypeLoweringPass::runOnModule</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a820e89d4531bed12df6050d26f6622b9">llvm::SanitizerStatReport::SanitizerStatReport</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aaf604b7b4ff087fce0b71852f5ddefbe">setUsedInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instcombine/instcombineloadstorealloca-cpp/#a25ea6e038ccdef52ab01b0ee3da9ee52">simplifyAllocaArraySize</a>, <a href="/web-llvm/docs/api/classes/anonymous-simplifycfg-cpp-/switchlookuptable/#a36955f44027693881a174e8d3f1d3854">anonymous{SimplifyCFG.cpp}::SwitchLookupTable::SwitchLookupTable</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#af7668ce8080668a4f0ceac24e70c9f00">targetParallelCallback</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a44ca78ca7013578c50cdd38647811346">transformGlobalArray</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a95b7e7311ec52352ada27699c3c9c470">llvm::UpgradeGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#a29df0cec2acb067cfcb09eeeb726c7db">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitAllocaInst</a>, <a href="/web-llvm/docs/api/classes/anonymous-dxilflattenarrays-cpp-/dxilflattenarraysvisitor/#ae73e475ff9414b97c6ad36f601179133">anonymous{DXILFlattenArrays.cpp}::DXILFlattenArraysVisitor::visitGetElementPtrInst</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#a7af99fa2202fcc7db245865dd1bcec1f">llvm::InstCombinerImpl::visitLandingPadInst</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a960e756e8b2f056fbba7baa5bdcfb769">widenDestArray</a>.</p>

</div>
</div>

### isValidElementType() {#a279315ff6072c1cd5cbdff45ff97dc44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArrayType::isValidElementType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy)</td>
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

<p>Return true if the specified type is valid as a element type.</p>

<p>Declaration at line 414 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 758 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
