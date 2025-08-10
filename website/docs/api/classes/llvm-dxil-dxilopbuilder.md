---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/dxil/dxilopbuilder
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `DXILOpBuilder` Class



## Declaration

<div class="doxyDeclaration">
class llvm::dxil::DXILOpBuilder { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">Target/DirectX/DXILOpBuilder.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09f956aa519d8b77e2e9b9bd261b043f">DXILOpBuilder</a> (Module &amp;M)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5964c0cb2541774138a560e934ffc0d8">getIRB</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fde2412fafaa1ea67cc7f0f2d9dda69">createOp</a> (dxil::OpCode Op, ArrayRef&lt; Value * &gt; Args, const Twine &amp;Name="", Type *RetTy=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create a call instruction for the given DXIL op. <a href="#a9fde2412fafaa1ea67cc7f0f2d9dda69">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a871def99cd40b0a7df2e3f22387198cc">tryCreateOp</a> (dxil::OpCode Op, ArrayRef&lt; Value * &gt; Args, const Twine &amp;Name="", Type *RetTy=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Try to create a call instruction for the given DXIL op. <a href="#a871def99cd40b0a7df2e3f22387198cc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a350264a5a94e6e8e4886711ad6cfcace">getResRetType</a> (Type *ElementTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <span class="doxyComputerOutput">dx.types.ResRet</span> type with the given element type. <a href="#a350264a5a94e6e8e4886711ad6cfcace">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a517e08f0af48daef89f563f763c438a7">getSplitDoubleType</a> (LLVMContext &amp;Context)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <span class="doxyComputerOutput">dx.types.splitdouble</span> type. <a href="#a517e08f0af48daef89f563f763c438a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b5e2ca52907a33f6c0ac740b2c8af1">getHandleType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <span class="doxyComputerOutput">dx.types.Handle</span> type. <a href="#af2b5e2ca52907a33f6c0ac740b2c8af1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa522833bf3162eb609d51cefb341314f">getResBind</a> (uint32_t LowerBound, uint32_t UpperBound, uint32_t SpaceID, dxil::ResourceClass RC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a constant <span class="doxyComputerOutput">dx.types.ResBind</span> value. <a href="#aa522833bf3162eb609d51cefb341314f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a45afdcb63e6c39a556e3e5b9610bc">getResProps</a> (uint32_t Word0, uint32_t Word1)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a constant <span class="doxyComputerOutput">dx.types.ResourceProperties</span> value. <a href="#ae2a45afdcb63e6c39a556e3e5b9610bc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1d18d3311224ae9bbb2384341294388">getOpFunctionType</a> (dxil::OpCode OpCode, Type *OverloadType=nullptr)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets a specific overload type of the function for the given DXIL op. <a href="#af1d18d3311224ae9bbb2384341294388">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b532459aeb6563a33e42a94b881f244">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a2e0ffc089814a86632605bdd0a3b2a">IRB</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7c055f39459feb6789ba13613ee5554">DXILVersion</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324">Triple::EnvironmentType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76be12d761f7671fda88e2a658807e0">ShaderStage</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdc5a4a36574cffe88ff21bf40bde068">getOpCodeName</a> (dxil::OpCode DXILOp)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the name of the given opcode. <a href="#abdc5a4a36574cffe88ff21bf40bde068">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DXILOpBuilder() {#a09f956aa519d8b77e2e9b9bd261b043f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::dxil::DXILOpBuilder::DXILOpBuilder (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 430 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7f2a3d4dcfee70225988aec53ff1e173">llvm::report_fatal_error</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a1778f5c464f88710033f7e11e84a9324a6c32bcd90dff79307baf3147697ae1d3">llvm::Triple::UnknownEnvironment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createOp() {#a9fde2412fafaa1ea67cc7f0f2d9dda69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallInst * llvm::dxil::DXILOpBuilder::createOp (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> Op, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create a call instruction for the given DXIL op.</p>


<p>The arguments must be valid for an overload of the operation.</p>


<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 526 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a871def99cd40b0a7df2e3f22387198cc">tryCreateOp</a>.</p>

</div>
</div>

### getHandleType() {#af2b5e2ca52907a33f6c0ac740b2c8af1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * llvm::dxil::DXILOpBuilder::getHandleType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <span class="doxyComputerOutput">dx.types.Handle</span> type.</p>

<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 542 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

### getIRB() {#a5964c0cb2541774138a560e934ffc0d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder &amp; llvm::dxil::DXILOpBuilder::getIRB ()</td>
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



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>.</p>

</div>
</div>

### getResBind() {#aa522833bf3162eb609d51cefb341314f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::dxil::DXILOpBuilder::getResBind (uint32_t LowerBound, uint32_t UpperBound, uint32_t SpaceID, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a132a161d0df9261a144e907a02141687">dxil::ResourceClass</a> RC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a constant <span class="doxyComputerOutput">dx.types.ResBind</span> value.</p>

<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a7ba5de75f50bb4a4ba920698edf39b28">llvm::Type::getInt8Ty</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#aff234d51ccd591da6c1332a3d52fbe1e">getResBindType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>.</p>

</div>
</div>

### getResProps() {#ae2a45afdcb63e6c39a556e3e5b9610bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * llvm::dxil::DXILOpBuilder::getResProps (uint32_t Word0, uint32_t Word1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a constant <span class="doxyComputerOutput">dx.types.ResourceProperties</span> value.</p>

<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 558 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#a54fcfa620deb80373f489ba2fdad7643">llvm::ConstantStruct::get</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#af69be60078714a34c733e198b5aab9af">getResPropsType</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a23f9ec4bb2576ca8738f3edc9c4f5cdf">llvm::Int32Ty</a>.</p>

</div>
</div>

### getResRetType() {#a350264a5a94e6e8e4886711ad6cfcace}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * llvm::dxil::DXILOpBuilder::getResRetType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ElementTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <span class="doxyComputerOutput">dx.types.ResRet</span> type with the given element type.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 534 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

### getSplitDoubleType() {#a517e08f0af48daef89f563f763c438a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StructType * llvm::dxil::DXILOpBuilder::getSplitDoubleType (<a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; Context)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the <span class="doxyComputerOutput">dx.types.splitdouble</span> type.</p>

<p>Declaration at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 538 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

### tryCreateOp() {#a871def99cd40b0a7df2e3f22387198cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; CallInst * &gt; llvm::dxil::DXILOpBuilder::tryCreateOp (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> Op, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * &gt; Args, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/twine">Twine</a> &amp; Name="", <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Try to create a call instruction for the given DXIL op.</p>


<p>Fails if the overload is invalid.</p>


<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 449 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a7efd1f0c1206d95e4fe01a9b49a57b82">llvm::SmallVectorImpl&lt; T &gt;::append</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#ac921fd99ff39f6037d7f82d81ee8d87a">constructOverloadName</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#acc8e6bea7e5502aec0248a1441e9b720">getDXILOpFunctionType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a6b04886780c4fb4764f2b6dbc1d3d2d9">getOverloadKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3030fa8e5d4a78aef7c5a7fa00294ac6">getPropIndex</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a18cba992d12aa58de48357908b9e1169">getShaderKindEnum</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dxil/#a22a5df2ccfebeb3582950ac081af7057">llvm::dxil::makeOpError</a>, <a href="/web-llvm/docs/api/structs/opcodeproperty/#a8ba280f33b1634d175761ec26ffb749e">OpCodeProperty::OverloadParamIndex</a>, <a href="/web-llvm/docs/api/structs/opcodeproperty/#a0f83da7b421403e184326cad9c02a2de">OpCodeProperty::Overloads</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp/#a3f67233011e3c2264e7806412baa1595">setDXILAttributes</a>, <a href="/web-llvm/docs/api/structs/opcodeproperty/#aef5a9770dd5d3385ac6d10b1dcca31f5">OpCodeProperty::Stages</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a842e49a58fb3eba4e42a8dadad77745b">llvm::to_underlying</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-dxilopbuilder-cpp-/#a3fe8fcf1f03e5da864eb86be303a3216a9045349aadd51459c6dbe4f3b1c43217">anonymous{DXILOpBuilder.cpp}::UNDEFINED</a>.</p>


<p>Referenced by <a href="#a9fde2412fafaa1ea67cc7f0f2d9dda69">createOp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getOpFunctionType() {#af1d18d3311224ae9bbb2384341294388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionType * llvm::dxil::DXILOpBuilder::getOpFunctionType (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> OpCode, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * OverloadType=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Gets a specific overload type of the function for the given DXIL op.</p>


<p>If the operation is not overloaded, <span class="doxyComputerOutput">OverloadType</span> may be nullptr.</p>


<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### DXILVersion {#af7c055f39459feb6789ba13613ee5554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple llvm::dxil::DXILOpBuilder::DXILVersion</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>.</p>

</div>
</div>

### IRB {#a5a2e0ffc089814a86632605bdd0a3b2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IRBuilder llvm::dxil::DXILOpBuilder::IRB</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>.</p>

</div>
</div>

### M {#a4b532459aeb6563a33e42a94b881f244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; llvm::dxil::DXILOpBuilder::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>.</p>

</div>
</div>

### ShaderStage {#ad76be12d761f7671fda88e2a658807e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple::EnvironmentType llvm::dxil::DXILOpBuilder::ShaderStage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getOpCodeName() {#abdc5a4a36574cffe88ff21bf40bde068}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * llvm::dxil::DXILOpBuilder::getOpCodeName (<a href="/web-llvm/docs/api/namespaces/llvm/dxil/#ac64683c1985c78d81b50819a0b733f48">dxil::OpCode</a> DXILOp)</td>
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

<p>Return the name of the given opcode.</p>

<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a>, definition at line 565 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-cpp">DXILOpBuilder.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/directx/dxilopbuilder-h">DXILOpBuilder.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
