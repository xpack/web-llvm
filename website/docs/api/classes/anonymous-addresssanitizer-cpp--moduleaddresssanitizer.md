---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/anonymous-addresssanitizer-cpp-/moduleaddresssanitizer
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ModuleAddressSanitizer` Class Reference



## Declaration

<div class="doxyDeclaration">
class anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff0e7e435e8bbd930b71c32df8f2c421">ModuleAddressSanitizer</a> (Module &amp;M, bool InsertVersionCheck, bool CompileKernel=false, bool Recover=false, bool UseGlobalsGC=true, bool UseOdrIndicator=true, AsanDtorKind DestructorKind=AsanDtorKind::Global, AsanCtorKind ConstructorKind=AsanCtorKind::Global)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa85ee3a1ece5874da0e12dc71778c036">instrumentModule</a> ()</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c704f997dadfbca95e82ab248aecb2c">initializeCallbacks</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398d3d7b986ed012d00f703689658721">instrumentGlobals</a> (IRBuilder&lt;&gt; &amp;IRB, bool *CtorComdat)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ef75a0c5aafebeb33042c1f3bc1126f">InstrumentGlobalsCOFF</a> (IRBuilder&lt;&gt; &amp;IRB, ArrayRef&lt; GlobalVariable * &gt; ExtendedGlobals, ArrayRef&lt; Constant * &gt; MetadataInitializers)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe8be22c58a4ea90e52dcea63da1a111">instrumentGlobalsELF</a> (IRBuilder&lt;&gt; &amp;IRB, ArrayRef&lt; GlobalVariable * &gt; ExtendedGlobals, ArrayRef&lt; Constant * &gt; MetadataInitializers, const std::string &amp;UniqueModuleId)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf97dffc45b9d20e51ea4098575368dc">InstrumentGlobalsMachO</a> (IRBuilder&lt;&gt; &amp;IRB, ArrayRef&lt; GlobalVariable * &gt; ExtendedGlobals, ArrayRef&lt; Constant * &gt; MetadataInitializers)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa023a4129ca3631ac2a0273e6a0c1659">InstrumentGlobalsWithMetadataArray</a> (IRBuilder&lt;&gt; &amp;IRB, ArrayRef&lt; GlobalVariable * &gt; ExtendedGlobals, ArrayRef&lt; Constant * &gt; MetadataInitializers)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac19ee12c4da4a3c92c43ff1bd0dda328">CreateMetadataGlobal</a> (Constant *Initializer, StringRef OriginalName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38638f8ba1148e6953e1abff327bda70">SetComdatForGlobalMetadata</a> (GlobalVariable *G, GlobalVariable *Metadata, StringRef InternalSuffix)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/instruction">Instruction</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4a95b2167cdd9c0600a601e3258ba92">CreateAsanModuleDtor</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da77eff16f49bb4406a55ed90c4bf67">getExcludedAliasedGlobal</a> (const GlobalAlias &amp;GA) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac19eb7e03814944d2aeedabc9b5ccb5a">shouldInstrumentGlobal</a> (GlobalVariable *G) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc7871d4ff3e28540dcc29f79143e203">ShouldUseMachOGlobalsSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a009f24efd94802103a7b512ce9ba080a">getGlobalMetadataSection</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d30d1193a070d3dd5a558baae42c153">poisonOneInitializer</a> (Function &amp;GlobalInit)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae70a704c7420561f2303f55d011ef1c1">createInitializerPoisonCalls</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5b90349c908edc93ced7da731f344a">getMinRedzoneSizeForGlobal</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253cd399869f78531159418ce47ecd3d">getRedzoneSizeForGlobal</a> (uint64_t SizeInBytes) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38bd1f12cdaf0a62c25596f0ed02de66">GetAsanVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a816785c22691b09413f97226db3113bb">getOrCreateModuleName</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cf9073905fad18a1924f2f389635e47">M</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea07cae6e3a22b3cffed58cd32430f7d">CompileKernel</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98b6cebd4c24048bb14be4df34f762f5">InsertVersionCheck</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a202744b22192367185ad1ca3a8538a6b">Recover</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab27738fd1e4db89a744bee52f2d070a2">UseGlobalsGC</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada3e0c11d5f3b8bd99e16a0b339e87c5">UsePrivateAlias</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59274969e97e0e44920ce8e2ed730425">UseOdrIndicator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4762c982a57b08fe4334730cbc9890b8">UseCtorComdat</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bf">AsanDtorKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2abf9cf8f7b5c385a5947a8e2e1f7d36">DestructorKind</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ae42efdb5798a010a1c768129ea7ddf08">AsanCtorKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72ac308c3eb13146bc639706dff4c1a0">ConstructorKind</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63d13043be732dc34ea4631ce5932734">IntptrTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d314f8f8ccad4ae92428733e4737e13">PtrTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe620942ef4b181278a39c1601f0f85b">C</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/triple">Triple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3197944b170fdaedfd94bb3e87fb648f">TargetTriple</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-addresssanitizer-cpp-/shadowmapping">ShadowMapping</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20f5d33534b1307da5db5a5df416418a">Mapping</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d083faedcf4c7568483685e62d6cc0e">AsanPoisonGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b8e95787f4cc2c43fa5152f70ee8e5">AsanUnpoisonGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae65787bab9378a5a0dde0ea9983fd2d8">AsanRegisterGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97758ce2a800f659330dd57eb1b124d">AsanUnregisterGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab698d395638aa6bccf644b79f43bd336">AsanRegisterImageGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03a7385fea012d4f0329e0b205ea7171">AsanUnregisterImageGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab015cfeabdb10857ed693a6b1e129752">AsanRegisterElfGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a3365fba48445b463e6ba9780f0b515">AsanUnregisterElfGlobals</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f79466ed930876c2240c3fdf109e4e9">AsanCtorFunction</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd517eadc3f0f778bb9360be7ccc8ddc">AsanDtorFunction</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a259331da5f895b8ef87a17330511cbb8">ModuleName</a> = nullptr</td>
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


<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ModuleAddressSanitizer() {#aff0e7e435e8bbd930b71c32df8f2c421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::ModuleAddressSanitizer (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, bool InsertVersionCheck, bool CompileKernel=false, bool Recover=false, bool UseGlobalsGC=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, bool UseOdrIndicator=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bf">AsanDtorKind</a> DestructorKind=AsanDtorKind::Global, <a href="/web-llvm/docs/api/namespaces/llvm/#ae42efdb5798a010a1c768129ea7ddf08">AsanCtorKind</a> ConstructorKind=AsanCtorKind::Global)</td>
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



<p>Definition at line 872 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aca33036eb9649523a6345787acc33d29">ClConstructorKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aa09777d1507554d2873581bb83442022">ClEnableKasan</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a2a1656d1f4ddeb386daf49396b178ab3">ClInsertVersionCheck</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a2ca87f4ce47405a2ebd8d6e0ab259d65">ClOverrideDestructorKind</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ab07c89b5ab3621d59817baefdae128cb">ClRecover</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aa612bd13cbe0dc1e574383f4eddc0760">ClUseGlobalsGC</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a7499c29bb36dd906803322453ac406ad">ClUseOdrIndicator</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a108a44e27f64b25d5be99eab0c12b840">ClUsePrivateAlias</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aeded18588e9deea14f9c30eb995da5bb">ClWithComdat</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#acaf8e4c3e40e01e848c1fad5f05b81cd">llvm::Type::getIntNTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ac4b45ab450a043187e92eaace7d62018">getShadowMapping</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a9aa6dce3613309b3509522a00d6569bfa4bbb8f967da6d1a610596d7257179c2b">llvm::Invalid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### instrumentModule() {#aa85ee3a1ece5874da0e12dc71778c036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleAddressSanitizer::instrumentModule ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 916 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac030f6d03b674c2d132fd54fb60c9f26">llvm::appendToGlobalCtors</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aece96440bab42936aa9cf334fb0054cc">llvm::appendToGlobalDtors</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a37e75a212ee37baa76869a8d0195d9e6">ClGlobals</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a256980e987af753b4c497757fad18000">llvm::createSanitizerCtor</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7260773aac0c8769857f551c78b439a3">llvm::createSanitizerCtorAndInitFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a30ad890949cdfd6777919b71f4d09dfe">GetCtorAndDtorPriority</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ae42efdb5798a010a1c768129ea7ddf08a4cc6684df7b4a92b1dec6fce3264fac8">llvm::Global</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a361b5f11d7b296279f45007be01c2913">kAsanInitName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#aad3e6eabecd50c9664b21071407c2267">kAsanModuleCtorName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#a8bcb2cf7d004c924b63f1a9d0dfa2847">kAsanModuleDtorName</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp/#ae54fd57142396b1edba3f62247d5a176">kAsanVersionCheckNamePrefix</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ae42efdb5798a010a1c768129ea7ddf08a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### CreateAsanModuleDtor() {#ad4a95b2167cdd9c0600a601e3258ba92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Instruction * ModuleAddressSanitizer::CreateAsanModuleDtor ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### createInitializerPoisonCalls() {#ae70a704c7420561f2303f55d011ef1c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::createInitializerPoisonCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 948 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### CreateMetadataGlobal() {#ac19ee12c4da4a3c92c43ff1bd0dda328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * ModuleAddressSanitizer::CreateMetadataGlobal (<a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Initializer, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> OriginalName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 937 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### GetAsanVersion() {#a38bd1f12cdaf0a62c25596f0ed02de66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ModuleAddressSanitizer::GetAsanVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 953 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### getExcludedAliasedGlobal() {#a9da77eff16f49bb4406a55ed90c4bf67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalVariable * ModuleAddressSanitizer::getExcludedAliasedGlobal (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &amp; GA)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 943 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### getGlobalMetadataSection() {#a009f24efd94802103a7b512ce9ba080a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef ModuleAddressSanitizer::getGlobalMetadataSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### getMinRedzoneSizeForGlobal() {#ade5b90349c908edc93ced7da731f344a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::getMinRedzoneSizeForGlobal ()</td>
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



<p>Definition at line 949 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### getOrCreateModuleName() {#a816785c22691b09413f97226db3113bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * ModuleAddressSanitizer::getOrCreateModuleName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### getRedzoneSizeForGlobal() {#a253cd399869f78531159418ce47ecd3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t ModuleAddressSanitizer::getRedzoneSizeForGlobal (uint64_t SizeInBytes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 952 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### initializeCallbacks() {#a1c704f997dadfbca95e82ab248aecb2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::initializeCallbacks ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 919 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### instrumentGlobals() {#a398d3d7b986ed012d00f703689658721}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::instrumentGlobals (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, bool * CtorComdat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 921 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### InstrumentGlobalsCOFF() {#a6ef75a0c5aafebeb33042c1f3bc1126f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::InstrumentGlobalsCOFF (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; ExtendedGlobals, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; MetadataInitializers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### instrumentGlobalsELF() {#afe8be22c58a4ea90e52dcea63da1a111}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::instrumentGlobalsELF (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; ExtendedGlobals, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; MetadataInitializers, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp; UniqueModuleId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 925 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### InstrumentGlobalsMachO() {#abf97dffc45b9d20e51ea4098575368dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::InstrumentGlobalsMachO (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; ExtendedGlobals, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; MetadataInitializers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 929 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### InstrumentGlobalsWithMetadataArray() {#aa023a4129ca3631ac2a0273e6a0c1659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::InstrumentGlobalsWithMetadataArray (<a href="/web-llvm/docs/api/classes/llvm/irbuilder">IRBuilder</a>&lt;&gt; &amp; IRB, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * &gt; ExtendedGlobals, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; MetadataInitializers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 933 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### poisonOneInitializer() {#a7d30d1193a070d3dd5a558baae42c153}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::poisonOneInitializer (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; GlobalInit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 947 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### SetComdatForGlobalMetadata() {#a38638f8ba1148e6953e1abff327bda70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ModuleAddressSanitizer::SetComdatForGlobalMetadata (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * G, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * Metadata, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> InternalSuffix)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 939 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### shouldInstrumentGlobal() {#ac19eb7e03814944d2aeedabc9b5ccb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleAddressSanitizer::shouldInstrumentGlobal (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * G)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 944 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### ShouldUseMachOGlobalsSection() {#adc7871d4ff3e28540dcc29f79143e203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ModuleAddressSanitizer::ShouldUseMachOGlobalsSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 945 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### AsanCtorFunction {#a8f79466ed930876c2240c3fdf109e4e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanCtorFunction = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 980 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanDtorFunction {#acd517eadc3f0f778bb9360be7ccc8ddc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function* anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanDtorFunction = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 981 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanPoisonGlobals {#a4d083faedcf4c7568483685e62d6cc0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanPoisonGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 971 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanRegisterElfGlobals {#ab015cfeabdb10857ed693a6b1e129752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanRegisterElfGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 977 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanRegisterGlobals {#ae65787bab9378a5a0dde0ea9983fd2d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanRegisterGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 973 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanRegisterImageGlobals {#ab698d395638aa6bccf644b79f43bd336}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanRegisterImageGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 975 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanUnpoisonGlobals {#a78b8e95787f4cc2c43fa5152f70ee8e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanUnpoisonGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 972 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanUnregisterElfGlobals {#a5a3365fba48445b463e6ba9780f0b515}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanUnregisterElfGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 978 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanUnregisterGlobals {#aa97758ce2a800f659330dd57eb1b124d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanUnregisterGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### AsanUnregisterImageGlobals {#a03a7385fea012d4f0329e0b205ea7171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::AsanUnregisterImageGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 976 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### C {#abe620942ef4b181278a39c1601f0f85b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext* anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### CompileKernel {#aea07cae6e3a22b3cffed58cd32430f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::CompileKernel</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 957 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### ConstructorKind {#a72ac308c3eb13146bc639706dff4c1a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsanCtorKind anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::ConstructorKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 965 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### DestructorKind {#a2abf9cf8f7b5c385a5947a8e2e1f7d36}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AsanDtorKind anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::DestructorKind</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 964 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### InsertVersionCheck {#a98b6cebd4c24048bb14be4df34f762f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::InsertVersionCheck</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### IntptrTy {#a63d13043be732dc34ea4631ce5932734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::IntptrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 966 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### M {#a1cf9073905fad18a1924f2f389635e47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 956 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### Mapping {#a20f5d33534b1307da5db5a5df416418a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ShadowMapping anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::Mapping</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 970 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### ModuleName {#a259331da5f895b8ef87a17330511cbb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable* anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::ModuleName = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 982 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### PtrTy {#a2d314f8f8ccad4ae92428733e4737e13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::PtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 967 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### Recover {#a202744b22192367185ad1ca3a8538a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::Recover</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 959 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### TargetTriple {#a3197944b170fdaedfd94bb3e87fb648f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Triple anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 969 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### UseCtorComdat {#a4762c982a57b08fe4334730cbc9890b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::UseCtorComdat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 963 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### UseGlobalsGC {#ab27738fd1e4db89a744bee52f2d070a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::UseGlobalsGC</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 960 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### UseOdrIndicator {#a59274969e97e0e44920ce8e2ed730425}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::UseOdrIndicator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 962 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

### UsePrivateAlias {#ada3e0c11d5f3b8bd99e16a0b339e87c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{AddressSanitizer.cpp}::ModuleAddressSanitizer::UsePrivateAlias</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 961 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/addresssanitizer-cpp">AddressSanitizer.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
