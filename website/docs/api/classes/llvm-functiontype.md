---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/functiontype
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `FunctionType` Class

<p>Class to represent function types. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::FunctionType { ... }
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a169beeeb49e770cbdbd9448ffd2af534">param_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/type/#a5325d504915a0e903f78cd39bbc59bb5">Type::subtype_iterator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a524efbd55450b7eb7de00c8cb37e4990">FunctionType</a> (const FunctionType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9beceea14d8b32f76506332b40e17c0">FunctionType</a> (Type *Result, ArrayRef&lt; Type * &gt; Params, bool IsVarArgs)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa993cc3eabc985cb31fd0486d584d165">operator=</a> (const FunctionType &amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9d770048c7ab9e08222a50b7bc1be1c">isVarArg</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad65790aa94dd4678a1d339d8304e1965">getReturnType</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a169beeeb49e770cbdbd9448ffd2af534">param_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d5616e1422394b4d350c008b0cc5e0">param_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a169beeeb49e770cbdbd9448ffd2af534">param_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeae69a459419ec0bb738cdc73f4fc2a1">param_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dc558dee9c54b788dd559fed3c0a39a">params</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e415dc42f391c1d0cfcc1c28c00b2f4">getParamType</a> (unsigned i) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parameter type accessors. <a href="#a1e415dc42f391c1d0cfcc1c28c00b2f4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104d6154321899b53e40455e71d8e83a">getNumParams</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of fixed parameters this function type requires. <a href="#a104d6154321899b53e40455e71d8e83a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8be7844c269f201ebcee1e15048c378">get</a> (Type *Result, ArrayRef&lt; Type * &gt; Params, bool isVarArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This static method is the primary way of constructing a <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a>. <a href="#af8be7844c269f201ebcee1e15048c378">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab781285a21baf484d3023a63da798fc7">get</a> (Type *Result, bool isVarArg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> taking no parameters. <a href="#ab781285a21baf484d3023a63da798fc7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3afbe90fb46b63a247f50cadc0373397">isValidReturnType</a> (Type *RetTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified type is valid as a return type. <a href="#a3afbe90fb46b63a247f50cadc0373397">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cd1da5ae7e286d3acaf5a0aefa750f">isValidArgumentType</a> (Type *ArgTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the specified type is valid as an argument type. <a href="#a07cd1da5ae7e286d3acaf5a0aefa750f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf77cff1502d60be9249bc6ad9211812">classof</a> (const Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Methods for support type inquiry through isa, cast, and dyn_cast. <a href="#acf77cff1502d60be9249bc6ad9211812">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Class to represent function types.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### param\_iterator {#a169beeeb49e770cbdbd9448ffd2af534}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::FunctionType::param_iterator =  Type::subtype_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### FunctionType() {#a524efbd55450b7eb7de00c8cb37e4990}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FunctionType::FunctionType (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> &amp;)</td>
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



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### FunctionType() {#ac9beceea14d8b32f76506332b40e17c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType::FunctionType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Result, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Params, bool IsVarArgs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 341 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#aa993cc3eabc985cb31fd0486d584d165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType &amp; llvm::FunctionType::operator= (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> &amp;)</td>
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



<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getNumParams() {#a104d6154321899b53e40455e71d8e83a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FunctionType::getNumParams ()</td>
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

<p>Return the number of fixed parameters this function type requires.</p>


<p>This does not consider varargs.</p>


<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a679d8ea00092eb9cd392643bb2d1b7f9">llvm::Type::NumContainedTys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a584bad5329b738a08334d55310c2a94b">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#ac134215053dd186eca7bdd553eabc68c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildExitThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a8d179b8dd229c1d46eee4c257e717e25">createThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac4cd023a642d3b6295e4c1c6db359460">anonymous{ExpandVariadics.cpp}::ExpandVariadics::expandCall</a>, <a href="/web-llvm/docs/api/structs/llvm/vfshape/#aacd1691cd95a1e3e538fcee4c2cc8d05">llvm::VFShape::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="#a1e415dc42f391c1d0cfcc1c28c00b2f4">getParamType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab5a3ac0a249da0743dac1bd816d8e5d5">llvm::InlineFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d6c5795c1fbe672abaadd824bf08b76">llvm::isLibFreeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a8bf369675e5b6f65ee56064965ee9ee6">llvm::HexagonTargetLowering::LowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/hexagontargetlowering/#a41f0cd699a3f8d909d1864c270081883">llvm::HexagonTargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a66c07f0f69fee1125fecb13109da5c7b">anonymous{ValueMapper.cpp}::Mapper::remapInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#aaa1cdfbf8bbbb3d37466c44f0b8a403b">anonymous{ExpandVariadics.cpp}::ExpandVariadics::replaceAllUsesWithNewDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a1ddc9a64edbc2fbd4ddef5dce758fbd0">llvm::TargetLowering::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-dataflowsanitizer-cpp-/#a284ebf18528088df1b6da4af334a545b">anonymous{DataFlowSanitizer.cpp}::transformFunctionAttributes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a46c9ccb087f925d00317f16577410a13">llvm::VFABI::tryDemangleForVFABI</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargaarch64helper/#a41ca0d5d12f5940de41f29cf08066e00">anonymous{MemorySanitizer.cpp}::VarArgAArch64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargamd64helper/#acc81d19554e4eb245d659a89a2fd6f37">anonymous{MemorySanitizer.cpp}::VarArgAMD64Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/vararggenerichelper/#ab229cd82fd788028a0ff3a1f1957e7f9">anonymous{MemorySanitizer.cpp}::VarArgGenericHelper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargi386helper/#a372b313738e7d6b96b0ef622ce60890c">anonymous{MemorySanitizer.cpp}::VarArgI386Helper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargpowerpchelper/#a8e4ae572b54705c019d49eaed31ce04f">anonymous{MemorySanitizer.cpp}::VarArgPowerPCHelper::visitCallBase</a>, <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/varargsystemzhelper/#af0bc023f29f779469e5e8e3f92b9db0f">anonymous{MemorySanitizer.cpp}::VarArgSystemZHelper::visitCallBase</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### getParamType() {#a1e415dc42f391c1d0cfcc1c28c00b2f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::FunctionType::getParamType (unsigned i)</td>
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

<p>Parameter type accessors.</p>

<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a96d2037eb473457f3222e5cbe7ea22b5">llvm::Type::ContainedTys</a>, <a href="#a104d6154321899b53e40455e71d8e83a">getNumParams</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#a584bad5329b738a08334d55310c2a94b">llvm::AMDGPUMangledLibFunc::AMDGPUMangledLibFunc</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a101a4250b1fd5a230a766de2a14cb271">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildEntryThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a7ae16889db439f8fbb234fe3de672d11">llvm::VFABI::createFunctionType</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a0fb8bf2cae796307f012fc621678642f">llvm::IRBuilderBase::CreateLaunderInvariantGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#af9f3d0f2901feeff9d52b95e58fbb49b">llvm::IRBuilderBase::CreateStripInvariantGroup</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#a6245f16ff5b8230d2ed89127bf27efa8">llvm::AArch64TargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/armtargetlowering/#a68bc08431f00987920ce19e9a458e86d">llvm::ARMTargetLowering::emitStoreConditional</a>, <a href="/web-llvm/docs/api/classes/llvm/vpwidencallrecipe/#acd93ffe413319e78d7c62688cc86eb6c">llvm::VPWidenCallRecipe::execute</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpulibcalls/#a615317b48f533b3087abb06d3a96319c">llvm::AMDGPULibCalls::fold</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ab5e88a19352e7dce1b0115f5e6b37b47">getArgSPIRVType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a0a09a1144b3dbb1ddc00f0ced5030522">anonymous{VFABIDemangler.cpp}::getScalableECFromSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d6c5795c1fbe672abaadd824bf08b76">llvm::isLibFreeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/sitargetlowering/#a9854eddb8a07891be9aa4af0da56f198">llvm::SITargetLowering::LowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dfsanvisitor/#a403e1aa9c70e24ee0798d163ce9e0229">anonymous{DataFlowSanitizer.cpp}::DFSanVisitor::visitCallBase</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### getReturnType() {#ad65790aa94dd4678a1d339d8304e1965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type * llvm::FunctionType::getReturnType ()</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a96d2037eb473457f3222e5cbe7ea22b5">llvm::Type::ContainedTys</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lljit-cpp-/#a02c5eacc8cf66436f8d0f722263b9494">anonymous{LLJIT.cpp}::addHelperAndWrapper</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a101a4250b1fd5a230a766de2a14cb271">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildEntryThunk</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#ac134215053dd186eca7bdd553eabc68c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildExitThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a7ae16889db439f8fbb234fe3de672d11">llvm::VFABI::createFunctionType</a>, <a href="/web-llvm/docs/api/classes/anonymous-hexagonvectorcombine-cpp-/hexagonvectorcombine/#afc83c1972006a05871f65fdf15ade10f">anonymous{HexagonVectorCombine.cpp}::HexagonVectorCombine::createHvxIntrinsic</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-vfabidemangler-cpp-/#a0a09a1144b3dbb1ddc00f0ced5030522">anonymous{VFABIDemangler.cpp}::getScalableECFromSignature</a>, <a href="/web-llvm/docs/api/namespaces/llvm/objcarc/#aefba9af2f61452f20f4c947b4c2e5f4e">llvm::objcarc::hasAttachedCallOpBundle</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a0574a5dd4c78099285b317d60d28a966">anonymous{ExpandVariadics.cpp}::ExpandVariadics::inlinableVariadicFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4d6c5795c1fbe672abaadd824bf08b76">llvm::isLibFreeFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/spirvcalllowering/#af4911ff1c4fabd84b05d4529da80021e">llvm::SPIRVCallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a17dfad57f1487bb34ef68784a2e878c8">llvm::Intrinsic::matchIntrinsicSignature</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a84fbc09723655416fad6677d7fdaf8a6">replaceFallthroughCoroEnd</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/executionengine/#a97bbf524ee03354bb73dce9614b0e959">llvm::ExecutionEngine::runFunctionAsMain</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-inlinecost-cpp-/callanalyzer/#a020bb3b63fcf4ec2941fd868101f8914">anonymous{InlineCost.cpp}::CallAnalyzer::simplifyIntrinsicCallIsConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ea82b63a4aa1e4c73df257ffc9b7ec6">llvm::toTypedFunPointer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aef10fb11205c2a096e040dd6b75148eb">llvm::UpgradeARCRuntime</a> and <a href="/web-llvm/docs/api/classes/llvm/selectiondagbuilder/#ae8662f747218aee8ddeb4cdfbd1435a7">llvm::SelectionDAGBuilder::visitSPDescriptorParent</a>.</p>

</div>
</div>

### isVarArg() {#aa9d770048c7ab9e08222a50b7bc1be1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionType::isVarArg ()</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a977023a135a15dc3aadcf1e8246631f8">llvm::Type::getSubclassData</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/llvm/functioncomparator/#a96167048c547bb562d69720cee2a48a6">llvm::FunctionComparator::cmpTypes</a>, <a href="#af8be7844c269f201ebcee1e15048c378">get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#adce8df27d44de3e02c13209348660f0e">llvm::Intrinsic::getIntrinsicSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#ace495e41b614e9f54d0ae8c8ea318fcd">anonymous{AsmWriter.cpp}::AssemblyWriter::printFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/assemblywriter/#a27130c5f74c2f20dd183f5ab83f54e6c">anonymous{AsmWriter.cpp}::AssemblyWriter::printInstruction</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a66c07f0f69fee1125fecb13109da5c7b">anonymous{ValueMapper.cpp}::Mapper::remapInstruction</a>, <a href="/web-llvm/docs/api/classes/llvm/mcjit/#a0198943262fb715d77dfd24ef32f9399">llvm::MCJIT::runFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-dataflowsanitizer-cpp-/dataflowsanitizer/#ab4d94a2774e8420abe5e331d94334cec">anonymous{DataFlowSanitizer.cpp}::DataFlowSanitizer::runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a0664c52131a50e24aa68c8a4c9ed4311">anonymous{ExpandVariadics.cpp}::ExpandVariadics::runOnModule</a>, <a href="/web-llvm/docs/api/structs/llvm/targetlowering/callloweringinfo/#a1ddc9a64edbc2fbd4ddef5dce758fbd0">llvm::TargetLowering::CallLoweringInfo::setCallee</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ea82b63a4aa1e4c73df257ffc9b7ec6">llvm::toTypedFunPointer</a> and <a href="/web-llvm/docs/api/structs/anonymous-memorysanitizer-cpp-/memorysanitizervisitor/#adefa3ab29c92a0c9a23851fd393e5c0d">anonymous{MemorySanitizer.cpp}::MemorySanitizerVisitor::visitCallBase</a>.</p>

</div>
</div>

### param\_begin() {#a05d5616e1422394b4d350c008b0cc5e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">param_iterator llvm::FunctionType::param_begin ()</td>
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



<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/type/#a96d2037eb473457f3222e5cbe7ea22b5">llvm::Type::ContainedTys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#ac134215053dd186eca7bdd553eabc68c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildExitThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5abced3ab870d7abf57f2b35a02cd041">llvm::LoopVectorizationCostModel::getVectorIntrinsicCost</a> and <a href="#a8dc558dee9c54b788dd559fed3c0a39a">params</a>.</p>

</div>
</div>

### param\_end() {#aeae69a459419ec0bb738cdc73f4fc2a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">param_iterator llvm::FunctionType::param_end ()</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a96d2037eb473457f3222e5cbe7ea22b5">llvm::Type::ContainedTys</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a679d8ea00092eb9cd392643bb2d1b7f9">llvm::Type::NumContainedTys</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#ac134215053dd186eca7bdd553eabc68c">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::buildExitThunk</a>, <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a5abced3ab870d7abf57f2b35a02cd041">llvm::LoopVectorizationCostModel::getVectorIntrinsicCost</a> and <a href="#a8dc558dee9c54b788dd559fed3c0a39a">params</a>.</p>

</div>
</div>

### params() {#a8dc558dee9c54b788dd559fed3c0a39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayRef&lt; Type * &gt; llvm::FunctionType::params ()</td>
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



<p>Definition at line 132 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="#a05d5616e1422394b4d350c008b0cc5e0">param_begin</a> and <a href="#aeae69a459419ec0bb738cdc73f4fc2a1">param_end</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lljit-cpp-/#a02c5eacc8cf66436f8d0f722263b9494">anonymous{LLJIT.cpp}::addHelperAndWrapper</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#ac800803b298b2e26368a3cc770279945">anonymous{ExpandVariadics.cpp}::ExpandVariadics::deriveFixedArityReplacement</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a0574a5dd4c78099285b317d60d28a966">anonymous{ExpandVariadics.cpp}::ExpandVariadics::inlinableVariadicFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a17dfad57f1487bb34ef68784a2e878c8">llvm::Intrinsic::matchIntrinsicSignature</a>, <a href="/web-llvm/docs/api/classes/llvm/insertfunctionstrategy/#a51a23cfe8db3e31fdc6eeb8547df0d33">llvm::InsertFunctionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/anonymous-asmwriter-cpp-/typeprinting/#a0ec5edfa2f5d23c2b6b630469f22e875">anonymous{AsmWriter.cpp}::TypePrinting::print</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a66c07f0f69fee1125fecb13109da5c7b">anonymous{ValueMapper.cpp}::Mapper::remapInstruction</a>, <a href="/web-llvm/docs/api/structs/llvm/irsimilarity/irinstructiondata/#ae0683ad49b9a0ccca8bd1c97987a8cf9">llvm::IRSimilarity::IRInstructionData::setCalleeName</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a3ea82b63a4aa1e4c73df257ffc9b7ec6">llvm::toTypedFunPointer</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### classof() {#acf77cff1502d60be9249bc6ad9211812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FunctionType::classof (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
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

<p>Definition at line 147 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#a5e9e1c0dd93557be1b4ad72860f3cbdaa0ec130d9ce9883b3e9c6071ee19a4b16">llvm::Type::FunctionTyID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>

</div>
</div>

### get() {#af8be7844c269f201ebcee1e15048c378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * llvm::FunctionType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Result, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * &gt; Params, bool isVarArg)</td>
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

<p>This static method is the primary way of constructing a <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a>.</p>

<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>.</p>


<p>References <a href="#aa9d770048c7ab9e08222a50b7bc1be1c">isVarArg</a> and <a href="/web-llvm/docs/api/classes/llvm/type/#a817dfd76b27697e96a20f80f7bb68251">llvm::Type::Type</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-lljit-cpp-/#a02c5eacc8cf66436f8d0f722263b9494">anonymous{LLJIT.cpp}::addHelperAndWrapper</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#a8f2e0d9db7a457156c4377449c2e0606">anonymous{WholeProgramDevirt.cpp}::DevirtModule::applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#a16144b1e0f0bc86c81b262b2f82c44df">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::buildCustomStateMachine</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49077c24022f5ec4c84d809abf92e91e">callBufferedPrintfStart</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-pointertypeanalysis-cpp-/#ac10c52fc6c6c8328779f3175fce68067">anonymous{PointerTypeAnalysis.cpp}::classifyFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aedeb89fa4ceb608d9d49bcd53ddcd2c1">llvm::CloneFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#aba3432b49d9f33e6eb7fbb4657b662b6">llvm::SanitizerStatReport::create</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a2bd6903bee5451ebaffd790ccf869664">llvm::MIRParserImpl::createDummyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64lowerhomogeneousprologepilog-cpp/#acb76fa37c3f506da974ee1932b37eeaa">createFrameHelperMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a272d004d22ae2326fa35628cff91dd69">llvm::RandomIRBuilder::createFunctionDeclaration</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a7ae16889db439f8fbb234fe3de672d11">llvm::VFABI::createFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#a4e632566b9002891ab9f5a108f3bd803">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a083d4808926043b15fdd4acbccc863d1">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniCalls</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-amdgpuctordtorlowering-cpp-/#aa82200436735a7e7831e52db45ae4580">anonymous{AMDGPUCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-nvptxctordtorlowering-cpp-/#a4f767db6edfa57ac38c654668e19b385">anonymous{NVPTXCtorDtorLowering.cpp}::createInitOrFiniKernelFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aef9c35f13cf93ffcc6bafb8a210d842e">llvm::IRBuilderBase::CreateIntrinsic</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/globalmergefunctions-cpp/#a89a4b57af49436df2fd5796f26a34dc5">createMergedFunction</a>, <a href="/web-llvm/docs/api/structs/anonymous-corosplit-cpp-/switchcoroutinesplitter/#af0793991541abccfec5c0d8831612b7b">anonymous{CoroSplit.cpp}::SwitchCoroutineSplitter::createNoAllocVariant</a>, <a href="/web-llvm/docs/api/structs/anonymous-machineoutliner-cpp-/machineoutliner/#a272487247e40605fc8a0ee848d4dcf44">anonymous{MachineOutliner.cpp}::MachineOutliner::createOutlinedFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3ea33750ee7de55492a5083c347e2ddb">createOutlinedFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a274467e5dc615c3f67e96d645c6b9cd3">anonymous{OffloadWrapper.cpp}::createRegisterFatbinFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#afb5a26693a2aa4ccb54923bf6a6e86d6">anonymous{OffloadWrapper.cpp}::createRegisterFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#aa95d3be8182edf7e68419d38f31dc9de">anonymous{OffloadWrapper.cpp}::createRegisterGlobalsFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/reoptimizelayer/#a7c9e3a3c2e449cbc1dfebc37503af252">llvm::orc::ReOptimizeLayer::createReoptimizeCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a256980e987af753b4c497757fad18000">llvm::createSanitizerCtor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/classes/llvm/thunkinserter/#a1a95b72d4c28ba76251171967da03b01">llvm::ThunkInserter&lt; Derived, InsertedThunksTy &gt;::createThunkFunction</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-offloadwrapper-cpp-/#a483af07ad9cee019751803fda2e04d1e">anonymous{OffloadWrapper.cpp}::createUnregisterFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-pgoctxproflowering-cpp-/ctxinstrumentationlowerer/#a52c340457da98320b6872f2c0ccbae1b">anonymous{PGOCtxProfLowering.cpp}::CtxInstrumentationLowerer::CtxInstrumentationLowerer</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a67d90c79914c0bdfadad630647f8843b">llvm::declareSanitizerInitFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a27b401b3a141c64a98a51bafa9c8efdc">anonymous{CFGuard.cpp}::CFGuardImpl::doInitialization</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/argumentpromotion-cpp/#a48b0c9b087f506b1c0071e7da6054e0f">doPromotion</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irspeculationlayer/#ac443c17bb572b2276321acc44b417ec7">llvm::orc::IRSpeculationLayer::emit</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#ad915c31dcf8d35cf0affa3f8f13a043b">llvm::AtomicInfo::EmitAtomicLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/atomicinfo/#a5df935e7c87e3e1dc8b3d7e1870ee1c9">llvm::AtomicInfo::EmitAtomicLoadLibcall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#ad7795d2b31b375031144ce50d0f6fa34">emitGetSwiftErrorValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16hardfloat-cpp/#aa22cef0c6abab1ef18f9e35efc2b537e">emitInlineAsm</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/buildlibcalls-cpp/#a62d6c0a5c9dd42949245eb28ab9c37c8">emitLibCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/coroframe-cpp/#a3d306b9a19fc37d00329692ef499b1b1">emitSetSwiftErrorValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a3fb4884285f5bcb9a37d9378d1e33cd5">emitTargetTaskProxyFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/smeabipass-cpp/#a925bbfb44898a7e8da7d6170278aaf71">emitTPIDR2Save</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#aad01bd2643d37f64f9d9a2933b8ddfc2">llvm::OpenMPIRBuilder::emitUserDefinedMapper</a>, <a href="/web-llvm/docs/api/structs/llvm/sanitizerstatreport/#a0c8e1730578d5e4181a2bd1502328802">llvm::SanitizerStatReport::finish</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#ad57fd622877d2a50e1a312be6b4a409d">fixFunctionTypeIfPtrArgs</a>, <a href="/web-llvm/docs/api/namespaces/llvm/amdgpu/#a69996d98ab94d8335d082aabd9b1c12a">llvm::AMDGPU::generateCrashCode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/constraintelimination-cpp/#a7ea4fb4d6b0198f2b6eac325a8d93031">generateReproducer</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-jmcinstrumenter-cpp-/#a7704ada0af8cb169e6cf9dd2dec6171c">anonymous{JMCInstrumenter.cpp}::getCheckFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/escapeenumerator-cpp/#a7bc16e748f040714b2a1e334af45ac4f">getDefaultPersonalityFn</a>, <a href="/web-llvm/docs/api/files/lib/lib/frontend/lib/frontend/openmp/ompirbuilder-cpp/#a669fae0a15d7219ef3ca3f3b16e3f5a0">getFreshReductionFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvemitintrinsics-cpp/#ac2f8a243eec640b2ebf8e022d57c9411">getFunctionPointerElemType</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpumangledlibfunc/#aa6728197a535e01349675bcc721e56c3">llvm::AMDGPUMangledLibFunc::getFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#a492e33f38ce495d0143f95092cfd0595">getFunctionTypeFromAsyncSuspend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvpreparefunctions-cpp/#afb5c7d9f47f77651e28e14b6e715badf">getOrCreateFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/spirv/spirvcalllowering-cpp/#a3d3f9a7f2fef13c8261fa2d3175a4cca">getOriginalFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/module/#a2cf6738ff24ef8e3e474763aec81b401">llvm::Module::getOrInsertFunction</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad238b1acbeef49e9e1304a56bc19b0b1">llvm::getOrInsertLibFunc</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/instrprofiling-cpp/#acad385080d103af2e3c47f9d4124827a">getOrInsertValueProfilingCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulibcalls-cpp/#adfa93be20aafc0740ce9e4d48640406c">getPownType</a>, <a href="/web-llvm/docs/api/structs/llvm/coro/shape/#a1a578073d9d2487a3806e8a51abb1b6e">llvm::coro::Shape::getResumeFunctionType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aca1828635e30f34e4958afeb5541766e">llvm::Intrinsic::getType</a>, <a href="/web-llvm/docs/api/classes/anonymous-expandvariadics-cpp-/expandvariadics/#a0574a5dd4c78099285b317d60d28a966">anonymous{ExpandVariadics.cpp}::ExpandVariadics::inlinableVariadicFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/entryexitinstrumenter-cpp/#afaedc942c49991373fe6f32bc580b29b">insertCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/placesafepoints-cpp/#a05dd87a2da7ddff8ce97716e3b479b2e">InsertSafepointPoll</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a6b7912ea5edc4563fe03afc57fa9b0c6">insertUseHolderAfter</a>, <a href="/web-llvm/docs/api/structs/anonymous-typesanitizer-cpp-/typesanitizer/#aa8094f0b4dd7316f56198f0e4760b9b4">anonymous{TypeSanitizer.cpp}::TypeSanitizer::instrumentGlobals</a>, <a href="/web-llvm/docs/api/groups/llvmccoretypefunction/#ga8b0c32e7322e5c6c1bf7eb95b0961707">LLVMFunctionType</a>, <a href="/web-llvm/docs/api/classes/anonymous-lowertypetests-cpp-/lowertypetestsmodule/#a7c206887f3f0887f2c6ac58910c09c41">anonymous{LowerTypeTests.cpp}::LowerTypeTestsModule::lower</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/coroutines/corosplit-cpp/#ab5b261757331e18b934bba9c3d3e6b69">lowerAwaitSuspend</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae819b62ec706cb229654ea5fb6553501">llvm::lowerGlobalIFuncUsersAsGlobalCtor</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a2f68fd99d1f5c6c8326be57c2963306d">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::lowerKernelLDSAccesses</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a34a6720f55cf4ef2114d657d9e14ff7a">makeDoubleDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#aa0c7ee5148fe48f9b0bba95da880df23">makeDoubleDoubleDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#ace45799dce23f34a9cedcef38cc282aa">makeDoubleDoubleDoubleDouble</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#af1c79d13b3cabe136b1bfb07cce0b1d3">makeDoubleDoubleI32</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/scalar/rewritestatepointsforgc-cpp/#a03f51e12bc910c9dc19f38b36f58a223">makeStatepointExplicitImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a496789388d8c1c5a81723b3e3adedf10">makeX86FP80X86FP80</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a528a5eb1adc41c313f4e35df8bf6e1d1">makeX86FP80X86FP80I32</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a76f9ac4919f0df94ddb092037bbc9e21">makeX86FP80X86FP80X86FP80</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/numericalstabilitysanitizer-cpp/#a7a0bc2534f4e5813219d15c836636c8e">makeX86FP80X86FP80X86FP80X86FP80</a>, <a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/addresssanitizer/#abc1dbfd3922f952c6e5edbed42521c54">anonymous{AddressSanitizer.cpp}::AddressSanitizer::maybeInsertDynamicShadowAtFunctionEntry</a>, <a href="/web-llvm/docs/api/classes/anonymous-numericalstabilitysanitizer-cpp-/nsanmemopfn/#a85787eb1162b7d741f8f3b29601e7860">anonymous{NumericalStabilitySanitizer.cpp}::NsanMemOpFn::NsanMemOpFn</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/globalctordtorscraper/#a5f8ea04329212b479fa473a5b324153c">anonymous{LLJIT.cpp}::GlobalCtorDtorScraper::operator()</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpuswlowerlds-cpp-/amdgpuswlowerlds/#a0a4ed9d0b5d054ee811d2d8fecb35626">anonymous{AMDGPUSwLowerLDS.cpp}::AMDGPUSwLowerLDS::poisonRedzones</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a75ab07a3bb2b992b551be9596d21f0fd">llvm::reconstructFunctionType</a>, <a href="/web-llvm/docs/api/classes/anonymous-valuemapper-cpp-/mapper/#a66c07f0f69fee1125fecb13109da5c7b">anonymous{ValueMapper.cpp}::Mapper::remapInstruction</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/intrinsiclowering-cpp/#a97741acf9b0e38ab508c939d99e53767">ReplaceCallWith</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/replacewithveclib-cpp/#a27cad9bebff39ed9ba603074dda1335e">replaceWithCallToVeclib</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/lowerglobaldtors-cpp/#aa2a67dbc6220273da3430b0a15735487">runImpl</a>, <a href="/web-llvm/docs/api/classes/anonymous-amdgpurewriteoutarguments-cpp-/amdgpurewriteoutarguments/#af9d46a08167454a31f6a9157eb65a44a">anonymous{AMDGPURewriteOutArguments.cpp}::AMDGPURewriteOutArguments::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86winehstate-cpp-/winehstatepass/#acbb400505dff72ce49663ae73e4d7399">anonymous{X86WinEHState.cpp}::WinEHStatePass::runOnFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7b0a136ac6a10743ef5d3cbc1ee0190e">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-webassemblyloweremscriptenehsjlj-cpp-/webassemblyloweremscriptenehsjlj/#a4e54683754f6664c17d470ae3a097486">anonymous{WebAssemblyLowerEmscriptenEHSjLj.cpp}::WebAssemblyLowerEmscriptenEHSjLj::runOnModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-lljit-cpp-/genericllvmirplatformsupport/#a27bbd3687e81d99d0ad1333b8f5e7f08">anonymous{LLJIT.cpp}::GenericLLVMIRPlatformSupport::setupJITDylib</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a64cd5b79789610d81be5d0b2633868ae">anonymous{ThinLTOBitcodeWriter.cpp}::simplifyExternals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3ea82b63a4aa1e4c73df257ffc9b7ec6">llvm::toTypedFunPointer</a> and <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule/#ad722656aa63d87c356ec659228865f65">anonymous{WholeProgramDevirt.cpp}::DevirtModule::tryICallBranchFunnel</a>.</p>

</div>
</div>

### get() {#ab781285a21baf484d3023a63da798fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * FunctionType::get (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Result, bool isVarArg)</td>
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

<p>Create a <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> taking no parameters.</p>

<p>Declaration at line 117 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 387 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isValidArgumentType() {#a07cd1da5ae7e286d3acaf5a0aefa750f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FunctionType::isValidArgumentType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ArgTy)</td>
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

<p>Return true if the specified type is valid as an argument type.</p>

<p>Declaration at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 396 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

</div>
</div>

### isValidReturnType() {#a3afbe90fb46b63a247f50cadc0373397}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FunctionType::isValidReturnType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
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

<p>Return true if the specified type is valid as a return type.</p>

<p>Declaration at line 120 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/derivedtypes-h">DerivedTypes.h</a>, definition at line 391 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/type-cpp">Type.cpp</a>.</p>

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
