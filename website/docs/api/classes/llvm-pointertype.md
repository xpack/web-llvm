---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/pointertype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `PointerType` Class Reference

<p>Class to represent pointers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::PointerType { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a629785da2701fa92f41fe7914fd79c22">PointerType</a> (const PointerType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d95ab800f3bfa5c85fba362f3c420e3">PointerType</a> (LLVMContext &amp;C, unsigned AddrSpace)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb2eec607f1d5c3b7e9f863bb13b5514">operator=</a> (const PointerType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8aeced5e71d2589fa3e9791043af5cb">getAddressSpace</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the address space of the Pointer type. <a href="#af8aeced5e71d2589fa3e9791043af5cb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">get</a> (Type *ElementType, unsigned AddressSpace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructs a pointer to an object of the specified type in a numbered address space. <a href="#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a758cf1dd3334e907ae3abe49e07f5441">get</a> (LLVMContext &amp;C, unsigned AddressSpace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructs an opaque pointer to an object in a numbered address space. <a href="#a758cf1dd3334e907ae3abe49e07f5441">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a1dbdbfd89aa4899b3c0d39495d0dd">getUnqual</a> (Type *ElementType)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructs a pointer to an object of the specified type in the default address space (address space zero). <a href="#af8a1dbdbfd89aa4899b3c0d39495d0dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a638fb3e006ef04d82cb245a50bcd41c5">getUnqual</a> (LLVMContext &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This constructs an opaque pointer to an object in the default address space (address space zero). <a href="#a638fb3e006ef04d82cb245a50bcd41c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac306fd31390128f9c2557c889a19146">isValidElementType</a> (Type *ElemTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified type is valid as a element type. <a href="#aac306fd31390128f9c2557c889a19146">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fe3c6f782b08dd490ec007de7ff6ac0">isLoadableOrStorableType</a> (Type *ElemTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if we can load or store from a pointer to this type. <a href="#a2fe3c6f782b08dd490ec007de7ff6ac0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ec3ee498cc15a71a684a86aaf377ae1">classof</a> (const Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implement support type inquiry through isa, cast, and dyn_cast. <a href="#a8ec3ee498cc15a71a684a86aaf377ae1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to represent pointers.</p>

<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### PointerType() {#a629785da2701fa92f41fe7914fd79c22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::PointerType::PointerType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> &amp;)</td>
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



<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### PointerType() {#a3d95ab800f3bfa5c85fba362f3c420e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType::PointerType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned AddrSpace)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 671 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 854 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#adb2eec607f1d5c3b7e9f863bb13b5514}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType &amp; llvm::PointerType::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> &amp;)</td>
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



<p>Definition at line 675 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getAddressSpace() {#af8aeced5e71d2589fa3e9791043af5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::PointerType::getAddressSpace ()</td>
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

<p>Return the address space of the Pointer type.</p>

<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a977023a135a15dc3aadcf1e8246631f8">llvm::Type::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/machineirbuilder/#a0ac2ceaa32ba0511bb9e14e6edfbc329">llvm::MachineIRBuilder::buildGlobalValue</a>, <a href="/web-llvm/docs/api/classes/llvm/castinst/#af0e9f16b79d49af44209f202b31290a1">llvm::CastInst::castIsValid</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a88db5656a6723001ab395e9db68094c2">llvm::orc::cloneGlobalVariableDecl</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#aecc5ef45f49070634ddd53a04ed5548e">llvm::FunctionComparator::cmpConstants</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3e9604d679f4806943544dceaeb68149">llvm::convertToDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/loongarchtargetlowering/#ad3d0b842e1c779edc912cf2863bd5fcd">llvm::LoongArchTargetLowering::emitExpandAtomicRMW</a>, <a href="/web-llvm/docs/api/classes/llvm/allocainst/#ad2fb148dfac3182fce33be95fc4e9159">llvm::AllocaInst::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globaladdresssdnode/#a92c5f6f2c447c5979d74ac07b552ba1e">llvm::GlobalAddressSDNode::getAddressSpace</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a702d4986803a1782ba305b1c7a0f1c21">llvm::GlobalValue::getAddressSpace</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa41f9508130468035e0087f7cbdffa14">llvm::getAttributeBasedInliningDecision</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abac7688a1d6c52dc96e04dd56827df60">llvm::getCallsiteCost</a>, <a href="/web-llvm/docs/api/classes/llvm/x86ttiimpl/#a767fc4c72294e9754b83fe1d325b0493">llvm::X86TTIImpl::getGatherScatterOpCost</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/coreclrgc/#a7b5844a0f3f8ef4d67cd6603f7ab3e49">anonymous{BuiltinGCs.cpp}::CoreCLRGC::isGCManagedPointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-builtingcs-cpp-/statepointgc/#a32fa2acd693359684d5659d41ef2f02e">anonymous{BuiltinGCs.cpp}::StatepointGC::isGCManagedPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0e5b9e42ea84622605acea0b0d721fda">llvm::isLegalToPromote</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#ac51c315bfb66e68f32b03862fe849658">llvm::DataLayout::isNonIntegralPointerType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/constantmerge-cpp/#a6ebdfd799686fe407798a4d503a41cd9">isUnmergeableGlobal</a>, <a href="/web-llvm/docs/api/structs/anonymous-xcorelowerthreadlocal-cpp-/xcorelowerthreadlocal/#adb1323a587666f6b6a98e4d7c2ba24af">anonymous{XCoreLowerThreadLocal.cpp}::XCoreLowerThreadLocal::lowerGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a5529011752e50f62b1108a018df5e751">anonymous{AsmWriter.cpp}::AssemblyWriter::printGlobal</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#adf0a129dd6c07827f4a8a5914f2d8b5b">processInternalGlobal</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpupromotekernelarguments-cpp-/amdgpupromotekernelarguments/#aba6a5d42dccb898c13809cd1d7ac99b0">anonymous{AMDGPUPromoteKernelArguments.cpp}::AMDGPUPromoteKernelArguments::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-globalmerge-cpp-/globalmergeimpl/#a9fbe2dcb11cb3bb78be4d97f388b0c5d">anonymous{GlobalMerge.cpp}::GlobalMergeImpl::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#a9a13dab9647bddbb0cce81565a8249a1">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::uniquifyGVPerKernel</a> and <a href="/web-llvm/docs/api/classes/llvm/objectsizeoffsetvisitor/#a1cc16b0d0db7fe60390a13fa3d11dd89">llvm::ObjectSizeOffsetVisitor::visitConstantPointerNull</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#a8ec3ee498cc15a71a684a86aaf377ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::PointerType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Implement support type inquiry through isa, cast, and dyn_cast.</p>

<p>Definition at line 706 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaae68df805bc15b023748c2a78b80563ff">llvm::Type::PointerTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### get() {#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::PointerType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType, unsigned AddressSpace)</td>
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

<p>This constructs a pointer to an object of the specified type in a numbered address space.</p>

<p>Definition at line 679 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a8508f3dbb1f9429445f50282297b4f9a">appendToGlobalArray</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxlowerargs-cpp/#a944b77cb28ad77cdf28380c4453f8d02">convertToParamAS</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxlowerargs-cpp-/#aafd9b42c5de69fbe2a25e6b94f8cc299">anonymous{NVPTXLowerArgs.cpp}::copyByValParam</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#aa386a0afb3210b56c30181f93a434ed3">createAtomicLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#ace7e2f01b65afba76343f22d042a12df">CreateGCRelocates</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a083d4808926043b15fdd4acbccc863d1">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a78f018d0c5133b2d60d092d68f6b046b">llvm::orc::createIRTypedAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a524d3d59c93afc0f68256056ba5bfa0b">llvm::createMemLibcall</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a7c9e3a3c2e449cbc1dfebc37503af252">llvm::orc::ReOptimizeLayer::createReoptimizeCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a52c340457da98320b6872f2c0ccbae1b">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::CtxInstrumentationLowerer</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/intrinsics-cpp/#ad2818cfb16c332aba0ca0ae99d9e40a7">DecodeFixedType</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a27b401b3a141c64a98a51bafa9c8efdc">anonymous{CFGuard.cpp}::CFGuardImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#aa7f6ff2830d775cf0c6a4052836c2552">llvm::SITargetLowering::emitExpandAtomicAddrSpacePredicate</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv4/#ae25976638e06c5f87d1dd439602f1f8c">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV4::emitHiddenKernelArgs</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpu/hsamd/metadatastreamermsgpackv5/#a00df0d04b86c6d3d0d027c912afb7282">llvm::AMDGPU::HSAMD::MetadataStreamerMsgPackV5::emitHiddenKernelArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/looputils-cpp/#a43288882d546aed1ef0a23ffc620ddff">expandBounds</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a4d2bb9dec836bd0ea02b120f68c28425">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandVAIntrinsicUsersWithAddrspace</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararggenerichelper/#a3d0c6a7511c4672829252c0ce65c58c3">anonymous{MemorySanitizer.cpp}::VarArgGenericHelper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a5442ec4868113ee36c2380a1b919e103">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/iroutliner-cpp/#a4eb66b98a828331ed6cb79ae82c0336f">findExtractedOutputToOverallOutputMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/sandboxir/pointertype/#a6339a17772e61656c08fd77a488c9a50">llvm::sandboxir::PointerType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/datalayout/#a82e740747e70f962da8e6d26a2a86379">llvm::DataLayout::getAllocaPtrType</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#a5759fab5ef52a7e3ee96af7eb5e42c64">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::getArgTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a467226658bbb3854ea3e1f625a73a128">llvm::SelectionDAG::getEVTAlign</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvglobalregistry/#af99db04834e1ae3fc23466a80045a4d9">llvm::SPIRVGlobalRegistry::getOrCreateConstNullPtr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aadf38ec8e97afd05668e524d9ab0e60d">llvm::getOrCreateSPIRVDeviceEventPointer</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/inferaddressspaces-cpp/#abed64d6b010990757d04adb1c7a33c20">getPtrOrVecOfPtrsWithNewAS</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab73bb6948312ca0f98055c6a74c37045">llvm::IRBuilderBase::getPtrTy</a>, <a href="/web-llvm/docs/api/structs/anonymous-dataflowsanitizer-cpp-/dfsanfunction/#ae1eff2ac03032a7ba69baaaa62904ca0">anonymous{DataFlowSanitizer.cpp}::DFSanFunction::getRetvalTLS</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a145b3f6dbbafb7b1e7644c3c90fdaf3f">GetTLSADDR</a>, <a href="#a638fb3e006ef04d82cb245a50bcd41c5">getUnqual</a>, <a href="#af8a1dbdbfd89aa4899b3c0d39495d0dd">getUnqual</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/inlinefunction-cpp/#afaa78d0b3224d3175937f997dc2bc688">hasLifetimeMarkers</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/nvptx/nvptxloweralloca-cpp/#a76288e65bf2155a44597a9ffb783d25a">INITIALIZE_PASS</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a78ca5c76a5ac76f5ad51ce5ced36fbb8">llvm::CallLowering::insertSRetIncomingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a33a30176a7fd636333a4e618ef109f57">llvm::CallLowering::insertSRetLoads</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoinstrumentation-cpp-/functioninstrumenter/#ad8a93caaba7e38b078b14a134f5f46f8">anonymous{PGOInstrumentation.cpp}::FunctionInstrumenter::instrument</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#a9b79beccbeb33ff89c797f5ac7b3fce3">anonymous{AddressSanitizer.cpp}::AddressSanitizer::instrumentAddress</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#abb10d6b403863597e459061c0d8e1dd7">anonymous{MemProfiler.cpp}::MemProfiler::instrumentAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#af414e22c02fcc9ff3ce2d81ee8d3cfcb">llvm::AMDGPU::instrumentAddressImpl</a>, <a href="/web-llvm/docs/api/structs/anonymous-pgoinstrumentation-cpp-/selectinstvisitor/#a0cf4e2368dd2503ba7992b09322cf97a">anonymous{PGOInstrumentation.cpp}::SelectInstVisitor::instrumentOneSelectInst</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#ae365293b0e4b5cb45b3af280d14b26f1">llvm::coro::Shape::invalidateCoroutine</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#abb3e0c28998ff9684b75e9efa0697919">isValidProtoForSizeReturningNew</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypesequential/#ga299fe6147083678d0494b1b875f542fa">LLVMPointerType</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypesequential/#ga6a39c9a86e6f013a2146b206fc537c2c">LLVMPointerTypeInContext</a>, <a href="/web-llvm/docs/api/classes/llvm/nvptxtargetlowering/#a6107db1593ae7bb4074d606368898747">llvm::NVPTXTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7092b8371f80f3acf826e7bfc1e00d92">LowerToTLSExecModel</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaaddressspaceimpl/#a53cdd0197a337c06817844761012a6e0">anonymous{AttributorAttributes.cpp}::AAAddressSpaceImpl::manifest</a>, <a href="/web-llvm/docs/api/structs/anonymous-attributorattributes-cpp-/aaindirectcallinfocallsite/#afc99e48bf0eed3b2fc9a2c3b25e3bd73">anonymous{AttributorAttributes.cpp}::AAIndirectCallInfoCallSite::manifest</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a679d0966b3083f647af785f24936d3d9">llvm::RandomIRBuilder::newSink</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a520d2b97d6b2eb0958cc182161938cd1">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapScalar</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/bufferfatptrtostructtypemap/#a0b50be89487f7186a5eb7ff1bc82efc0">anonymous{AMDGPULowerBufferFatPointers.cpp}::BufferFatPtrToStructTypeMap::remapVector</a>, <a href="/web-llvm/docs/api/namespaces/llvm/coro/#abf799de7147065c0e7f525e1b6009dde">llvm::coro::replaceCoroFree</a>, <a href="/web-llvm/docs/api/classes/llvm/wasmehpreparepass/#a2cbdc4bc7c2c1dc4c48d00376ab271a1">llvm::WasmEHPreparePass::run</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#aaf604b7b4ff087fce0b71852f5ddefbe">setUsedInitializer</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instcombineintrinsic-cpp/#a708996b12b1b5e6ac2555880bdaeda64">simplifyX86MaskedStore</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowerbufferfatpointers-cpp-/splitptrstructs/#a28d5aaadc2b319f9ac050aa712e49a76">anonymous{AMDGPULowerBufferFatPointers.cpp}::SplitPtrStructs::visitIntrinsicInst</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### get() {#a758cf1dd3334e907ae3abe49e07f5441}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * PointerType::get (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, unsigned AddressSpace)</td>
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

<p>This constructs an opaque pointer to an object in a numbered address space.</p>

<p>Declaration at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 842 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### getUnqual() {#af8a1dbdbfd89aa4899b3c0d39495d0dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::PointerType::getUnqual (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementType)</td>
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

<p>This constructs a pointer to an object of the specified type in the default address space (address space zero).</p>

<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">get</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/codegen/loweremutls-cpp/#aeddd04f458fd6e9db5a892543636e240">addEmuTlsVar</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#ae700acd5d174922e475ea31fdb8fe51f">anonymous{AddressSanitizer.cpp}::AddressSanitizer::AddressSanitizer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#ad63e788f18762973cf9f3690fd4bbfb1">llvm::fuzzerop::anyPtrType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/moduleutils-cpp/#a24f2551aaa1c96b279e792995deddd7f">appendToUsedList</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/bpf/bpfcheckandadjustir-cpp/#a90036e9bed7ce7e86007bd8d83dd2d21">aspaceWrapValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-crossdsocfi-cpp-/crossdsocfi/#ab29f15fad3f35ea8248e93e3dc805224">anonymous{CrossDSOCFI.cpp}::CrossDSOCFI::buildCFICheck</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a712c7e27f92253c99bcc20689a4e93b0">buildFrameType</a>, <a href="/web-llvm/docs/api/classes/llvm/coroidinst/#ab330f042033636da90859626bc4dc542">llvm::CoroIdInst::clearPromise</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/promotememorytoregister-cpp/#a125e2946cdcc7555d8f5c383681d7097">convertMetadataToAssumes</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/functionstackpoisoner/#a20e0bf83ea626a73aedc5bc770c461bd">anonymous{AddressSanitizer.cpp}::FunctionStackPoisoner::copyToShadowInline</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#acfb266590cdac3ed6480244efcd5899c">llvm::coro::BaseCloner::create</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineasmkeytype/#a9d02d69969b472643cf2089965f7b2cc">llvm::InlineAsmKeyType::create</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#a826f32ce82e4b2605718fedddba8a055">CreateFailBB</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a251d6cd85b676ea4be1e4c2c263494db">anonymous{OffloadWrapper.cpp}::createFatbinDesc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a83935060c1ded86b574493d5fbefeef9">llvm::IRBuilderBase::CreateFree</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a792b08a6322bb539ee5ce2f754588c8c">llvm::IRBuilderBase::CreateMalloc</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/classes/llvm/instcombinerimpl/#ab464550d233a70bf18d772d204549342">llvm::InstCombinerImpl::CreateNonTerminatorUnreachable</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#acc290ce16055813d4ee68af4c8023a09">llvm::OpenMPIRBuilder::createOffloadEntriesAndInfoMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab1aa0d632549db4855d6412f4d2d44ae">llvm::OpenMPIRBuilder::createOffloadMapnames</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a38345e93229faed92e719f1793807bb1">llvm::OpenMPIRBuilder::createOMPInteropDestroy</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a7709370a0f6564aa772ce20caa45337e">llvm::OpenMPIRBuilder::createOMPInteropInit</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaef3fb3339c2ade5ffffccdd177e465c">llvm::OpenMPIRBuilder::createOMPInteropUse</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/stackprotector-cpp/#ab96042c1f6f237fe85abc4ec3ceb88d3">CreatePrologue</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aaa655ca8bca40c564d0b7c81ebaf8ff9">llvm::OpenMPIRBuilder::createReductionsGPU</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#afb5a26693a2aa4ccb54923bf6a6e86d6">anonymous{OffloadWrapper.cpp}::createRegisterFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a0af3c7a02c1325c04c59f857604bd4f3">llvm::OpenMPIRBuilder::createTask</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/basecloner/#a2039a88cc5cd331c4012e856dde33eed">llvm::coro::BaseCloner::deriveNewFramePointer</a>, <a href="/web-llvm/docs/api/classes/anonymous-instrprofiling-cpp-/pgocounterpromoterhelper/#afb93c0389fa161c51b25541def502b89">anonymous{InstrProfiling.cpp}::PGOCounterPromoterHelper::doExtraRewritesBeforeFinalDeletion</a>, <a href="/web-llvm/docs/api/classes/llvm/asmprinter/#aa9a2aed0d26a4fca41f8fc0986a3f12b">llvm::AsmPrinter::doFinalization</a>, <a href="/web-llvm/docs/api/classes/anonymous-shadowstackgclowering-cpp-/shadowstackgcloweringimpl/#a285f4b41becdfd4385ddb237bfc744fc">anonymous{ShadowStackGCLowering.cpp}::ShadowStackGCLoweringImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#a046c6262fc6fc6743bf539c87761083f">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::doInitialization</a>, <a href="/web-llvm/docs/api/classes/anonymous-coroelide-cpp-/coroidelider/#ad9c37680a58c2590f08d938aa1a44d6c">anonymous{CoroElide.cpp}::CoroIdElider::elideHeapAllocations</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a8356860a8bef082ff15df896ecec7732">eliminateSwiftErrorArgument</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a5c9bfa48812691afd87e3c2a7abcd6ad">llvm::embedBitcodeInModule</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a654b33adee2ae78ce74ecbe6aa5e5282">llvm::OpenMPIRBuilder::emitMapperCall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a752e863c1af5fe463d0f08574492c12f">llvm::OpenMPIRBuilder::emitOffloadingArrays</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#adb95f78638066c9b6ccba6e3a7d335da">llvm::OpenMPIRBuilder::emitOffloadingArraysArgument</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64isellowering-cpp/#af13091d8b3eced08538be82392dc7d43">emitSMEStateSaveRestore</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64selectiondaginfo/#a4f4d5344fa41e237eb9a60c7b62975b8">llvm::AArch64SelectionDAGInfo::EmitStreamingCompatibleMemLibCall</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a2841680b34ec9c2c7185a877f8f8b4c8">llvm::OpenMPIRBuilder::emitTargetTask</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#adaa729f57e0b62f0dd995c6f5e3df8b7">llvm::SelectionDAG::expandMultipleResultFPLibCall</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararggenerichelper/#a3d0c6a7511c4672829252c0ce65c58c3">anonymous{MemorySanitizer.cpp}::VarArgGenericHelper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a5442ec4868113ee36c2380a1b919e103">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::finalizeInstrumentation</a>, <a href="/web-llvm/docs/api/classes/llvm/codeextractor/#a537993928c8af5b0d064fcd5ce1dec2f">llvm::CodeExtractor::findAllocas</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a0c8e1730578d5e4181a2bd1502328802">llvm::SanitizerStatReport::finish</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a44dec91bb943f56f8bba3e9171a76947">llvm::InlineAsm::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#a59656c1055ce3a231bba72ea31edfb14">getAddrPtrType</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0af04c89840d424b7b33ae71d7c8cd28">llvm::ConstantExpr::getAlignOf</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#ab2b810a52c1fec67f50c9c4af0d60abe">anonymous{OffloadWrapper.cpp}::getBinDescPtrTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a604c924e11ca5df4475086acc8db0f4e">anonymous{OffloadWrapper.cpp}::getBinDescTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#a7704ada0af8cb169e6cf9dd2dec6171c">anonymous{JMCInstrumenter.cpp}::getCheckFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#ad4020d9f897807c61a6c30e270ef7e1c">anonymous{OffloadWrapper.cpp}::getDeviceImagePtrTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a8ba7541c9160f54941d8b6029ec4d2ae">anonymous{OffloadWrapper.cpp}::getDeviceImageTy</a>, <a href="/web-llvm/docs/api/classes/llvm/scalarevolution/#ad61acd1c9fda9921a30f3ff510509873">llvm::ScalarEvolution::getElementSize</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a6955657cb7867972e6b8f046e9cf5a02">llvm::offloading::getEntryTy</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#ad046f69ab8abe8d2605589e6daf42612">anonymous{OffloadWrapper.cpp}::getFatbinWrapperTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a669fae0a15d7219ef3ca3f3b16e3f5a0">getFreshReductionFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#a97235ab99e26ebd8fe54f629666f6bd2">getFuncAddrForProfData</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#aa998073715bffba8d6e44ddcf3e19f2b">getHandleType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibfunc-cpp/#ad618098d4191356253e5694fd90a4634">getIntrinsicParamType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a784589f886057bdb03273b8bb07deb2b">llvm::TargetLoweringBase::getIRStackGuard</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a4590e453df8847d8d5eda7e37ae9dffa">llvm::SelectionDAG::getMemcpy</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#ac3f766fb181e521628094d9a9e461606">llvm::SelectionDAG::getMemmove</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2150ad6f255dd827e24a5b76ec58d802">llvm::SelectionDAG::getMemset</a>, <a href="/web-llvm/docs/api/namespaces/llvm/offloading/#a68d20206b060ac3ad19f416ed5a4899b">llvm::offloading::getOffloadingEntryInitializer</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a1a578073d9d2487a3806e8a51abb1b6e">llvm::coro::Shape::getResumeFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#a1b127c37d77da045cea07e787e2d1e48">llvm::TargetLoweringBase::getSafeStackPointerLocation</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ae19488d3493945579ed3987ce14c6ff2">llvm::OpenMPIRBuilder::getSizeInBytes</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a778163e6ec80716a12ab3282cb97f0d9">llvm::ConstantExpr::getSizeOf</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#acea86ec3d4961375fa6135e67111884b">getVTableAddrForProfData</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a859081e342a8a97b3648873ae3df252d">llvm::AArch64TargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a3f1fdc55e21406f8dd4612925fbe86a8">llvm::ARMTargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/llvm/ppctargetlowering/#a6651f5dc988cb00064896052b5f7a42d">llvm::PPCTargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/#af3e31a71f6d0e55d41956d5b20ed7989">llvm::TargetLoweringBase::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#af30042e4c09138928b477e3834f0a13e">llvm::X86TargetLowering::insertSSPDeclarations</a>, <a href="/web-llvm/docs/api/classes/anonymous-sanitizercoverage-cpp-/modulesanitizercoverage/#a00b535566c2050fdc979d248b4dae4b8">anonymous{SanitizerCoverage.cpp}::ModuleSanitizerCoverage::instrumentModule</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a525e9355bccd735cf648afbde45acfc5">llvm::SparcTargetLowering::LowerF128_LibCallArg</a>, <a href="/web-llvm/docs/api/classes/llvm/sparctargetlowering/#a85b82d7c69a744603ea8eccd2c40d52e">llvm::SparcTargetLowering::LowerF128Op</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a0106bab2d4d5ef7149415e2af1dfb180">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::lowerFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpulowermoduleldspass-cpp-/amdgpulowermodulelds/#ad11ddce57e4edaea36cc0aa3f123b003">anonymous{AMDGPULowerModuleLDSPass.cpp}::AMDGPULowerModuleLDS::lowerModuleScopeStructVariables</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aaheaptosharedfunction/#a2c8f5eab9499a8b7a3238177f2ecf52c">anonymous{OpenMPOpt.cpp}::AAHeapToSharedFunction::manifest</a>, <a href="/web-llvm/docs/api/classes/anonymous-memprofiler-cpp-/memprofiler/#a77802cf83b248213a74db75d5850ab4b">anonymous{MemProfiler.cpp}::MemProfiler::MemProfiler</a>, <a href="/web-llvm/docs/api/classes/anonymous-addresssanitizer-cpp-/moduleaddresssanitizer/#aff0e7e435e8bbd930b71c32df8f2c421">anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::ModuleAddressSanitizer</a>, <a href="/web-llvm/docs/api/classes/boupslp/shuffleinstructionbuilder/#a4055f1bab55c76c243c3bf42c1a7e45a">llvm::slpvectorizer::BoUpSLP::ShuffleInstructionBuilder::needToDelay</a>, <a href="/web-llvm/docs/api/classes/llvm/escapeenumerator/#ac63ecd195310b8a31b445bb613028893">llvm::EscapeEnumerator::Next</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/nsanmemopfn/#a85787eb1162b7d741f8f3b29601e7860">anonymous{NumericalStabilitySanitizer.cpp}::NsanMemOpFn::NsanMemOpFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#af678f41709f265e2589f247e883aa738">replaceAsyncResumeFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-executionengine-cpp-/argvarray/#a3b5f64c809ca91e2a09b5b97d80e23a7">anonymous{ExecutionEngine.cpp}::ArgvArray::reset</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuopenclenqueuedblocklowering-cpp-/amdgpuopenclenqueuedblocklowering/#ac3eeb5c96b81aa7ad07041b3c20eeb04">anonymous{AMDGPUOpenCLEnqueuedBlockLowering.cpp}::AMDGPUOpenCLEnqueuedBlockLowering::run</a>, <a href="/web-llvm/docs/api/classes/anonymous-passbuilder-cpp-/triggerverifiererrorpass/#ada1d133949e3d808f4e13f5cadf21495">anonymous{PassBuilder.cpp}::TriggerVerifierErrorPass::run</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-sjljehprepare-cpp-/sjljehprepareimpl/#aafb9808e3b375710c68b44c507cd9c3d">anonymous{SjLjEHPrepare.cpp}::SjLjEHPrepareImpl::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winehstate-cpp-/winehstatepass/#acbb400505dff72ce49663ae73e4d7399">anonymous{X86WinEHState.cpp}::WinEHStatePass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a820e89d4531bed12df6050d26f6622b9">llvm::SanitizerStatReport::SanitizerStatReport</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>, <a href="/web-llvm/docs/api/namespaces/llvm/fuzzerop/#a4a27a121df43e5e1735eb5781de56594">llvm::fuzzerop::sizedPtrType</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/wasm/#af399440b56a4fd5fa0af52bdb1bc8243">anonymous{ExpandVariadics.cpp}::Wasm::slotInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/coro/asyncabi/#ae51f7f2d35223ec01d09e205c757a4df">llvm::coro::AsyncABI::splitCoroutine</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/amdgpu/#ab49c3554f0048977809ea9724d0d6292">anonymous{ExpandVariadics.cpp}::Amdgpu::vaListParameterType</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/nvptx/#a1e7d8ec265e51272fff98a174293aa6f">anonymous{ExpandVariadics.cpp}::NVPTX::vaListParameterType</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/wasm/#afd407096890ba22f8766999b01400b71">anonymous{ExpandVariadics.cpp}::Wasm::vaListParameterType</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/amdgpu/#a8c60a65389bc1ccc2114e0a2ee3ff409">anonymous{ExpandVariadics.cpp}::Amdgpu::vaListType</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/nvptx/#a49e9a6a77d6f712fcca2211c7d43def6">anonymous{ExpandVariadics.cpp}::NVPTX::vaListType</a>, <a href="/web-llvm/docs/api/structs/anonymous-expandvariadics-cpp-/wasm/#a83443dc3bc8d4a8c405c7a5069903afe">anonymous{ExpandVariadics.cpp}::Wasm::vaListType</a> and <a href="/web-llvm/docs/api/classes/anonymous-spirvemitintrinsics-cpp-/spirvemitintrinsics/#a4a4171890acb275f5a66288e91a8d5ca">anonymous{SPIRVEmitIntrinsics.cpp}::SPIRVEmitIntrinsics::visitSwitchInst</a>.</p>

</div>
</div>

### getUnqual() {#a638fb3e006ef04d82cb245a50bcd41c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType * llvm::PointerType::getUnqual (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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

<p>This constructs an opaque pointer to an object in the default address space (address space zero).</p>

<p>Definition at line 692 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a> and <a href="#a8d7f800be5fd53dcfcdcbdc6fd9ccfe3">get</a>.</p>

</div>
</div>

### isLoadableOrStorableType() {#a2fe3c6f782b08dd490ec007de7ff6ac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PointerType::isLoadableOrStorableType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy)</td>
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

<p>Return true if we can load or store from a pointer to this type.</p>

<p>Declaration at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 869 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isValidElementType() {#aac306fd31390128f9c2557c889a19146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PointerType::isValidElementType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElemTy)</td>
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

<p>Declaration at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 863 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#af9ea64c7dae47dcfa2c9f5775fb5915d">llvm::GlobalVariable::GlobalVariable</a>.</p>

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
