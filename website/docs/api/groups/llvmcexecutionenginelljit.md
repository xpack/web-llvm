---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/groups/llvmcexecutionenginelljit
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - group

---

<div class="doxyPage">

# The LLJIT Reference



## Topics Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">&nbsp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljitutils">LLJIT Utilities</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a>(* <a href="#ga20abb929df8d498ee59f205a897a066c">LLVMOrcLLJITBuilderObjectLinkingLayerCreatorFunction</a>)(void *Ctx, LLVMOrcExecutionSessionRef ES, const char *Triple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function for constructing an ObjectLinkingLayer instance to be used by an LLJIT instance. <a href="#ga20abb929df8d498ee59f205a897a066c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueLLJITBuilder * <a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::LLJITBuilder instance. <a href="#ga73a506a01a91405ba0548fde502df6dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueLLJIT * <a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::LLJIT instance. <a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaa5d922ee863fdc7d2dc05233ac736581">LLVMOrcCreateLLJITBuilder</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an LLVMOrcLLJITBuilder. <a href="#gaa5d922ee863fdc7d2dc05233ac736581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaacb935664319f97d76294ccbb536aa82">LLVMOrcDisposeLLJITBuilder</a> (LLVMOrcLLJITBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an <a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a>. <a href="#gaacb935664319f97d76294ccbb536aa82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga2d260f2b220e24dddae3216287134d40">LLVMOrcLLJITBuilderSetJITTargetMachineBuilder</a> (LLVMOrcLLJITBuilderRef Builder, LLVMOrcJITTargetMachineBuilderRef JTMB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the JITTargetMachineBuilder to be used when constructing the LLJIT instance. <a href="#ga2d260f2b220e24dddae3216287134d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga788e6b99d9d85377ca3e9c1c4f609de9">LLVMOrcLLJITBuilderSetObjectLinkingLayerCreator</a> (LLVMOrcLLJITBuilderRef Builder, LLVMOrcLLJITBuilderObjectLinkingLayerCreatorFunction F, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set an ObjectLinkingLayer creator function for this LLJIT instance. <a href="#ga788e6b99d9d85377ca3e9c1c4f609de9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gae5289a7cc63f872a7ba713bdaef88cd9">LLVMOrcCreateLLJIT</a> (LLVMOrcLLJITRef *Result, LLVMOrcLLJITBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an LLJIT instance from an LLJITBuilder. <a href="#gae5289a7cc63f872a7ba713bdaef88cd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga364a3b00fb6982a14e2532cec903e8ae">LLVMOrcDisposeLLJIT</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an LLJIT instance. <a href="#ga364a3b00fb6982a14e2532cec903e8ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga653c8620112eddd7c75085a0b586c97d">LLVMOrcExecutionSessionRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaae37b5fc90b38055ede42c0afa2e7583">LLVMOrcLLJITGetExecutionSession</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the ExecutionSession for this LLJIT instance. <a href="#gaae37b5fc90b38055ede42c0afa2e7583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga6c222ab7584b63113858cef2e3251013">LLVMOrcLLJITGetMainJITDylib</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the Main JITDylib. <a href="#ga6c222ab7584b63113858cef2e3251013">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga976d0d5a897124006dbbaf94395f4b80">LLVMOrcLLJITGetTripleString</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target triple for this LLJIT instance. <a href="#ga976d0d5a897124006dbbaf94395f4b80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaec73242a3ea26fcaec0d4d3565254a10">LLVMOrcLLJITGetGlobalPrefix</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the global prefix character according to the LLJIT's DataLayout. <a href="#gaec73242a3ea26fcaec0d4d3565254a10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">LLVMOrcSymbolStringPoolEntryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga53d78919ce533b45f86230a41a78c8a9">LLVMOrcLLJITMangleAndIntern</a> (LLVMOrcLLJITRef J, const char *UnmangledName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mangles the given string according to the LLJIT instance's DataLayout, then interns the result in the SymbolStringPool and returns a reference to the pool entry. <a href="#ga53d78919ce533b45f86230a41a78c8a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga10aa9d9cad65d7ef661abcf79461ee3e">LLVMOrcLLJITAddObjectFile</a> (LLVMOrcLLJITRef J, LLVMOrcJITDylibRef JD, LLVMMemoryBufferRef ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a buffer representing an object file to the given JITDylib in the given LLJIT instance. <a href="#ga10aa9d9cad65d7ef661abcf79461ee3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga4bff68f864841da604a930c5b603762b">LLVMOrcLLJITAddObjectFileWithRT</a> (LLVMOrcLLJITRef J, LLVMOrcResourceTrackerRef RT, LLVMMemoryBufferRef ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a buffer representing an object file to the given ResourceTracker's JITDylib in the given LLJIT instance. <a href="#ga4bff68f864841da604a930c5b603762b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga400c50b1c5b751715dae5ae61b3d2bb4">LLVMOrcLLJITAddLLVMIRModule</a> (LLVMOrcLLJITRef J, LLVMOrcJITDylibRef JD, LLVMOrcThreadSafeModuleRef TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an IR module to the given JITDylib in the given LLJIT instance. <a href="#ga400c50b1c5b751715dae5ae61b3d2bb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga1bb8b6fe0c4d07c2c538d6b84aac896e">LLVMOrcLLJITAddLLVMIRModuleWithRT</a> (LLVMOrcLLJITRef J, LLVMOrcResourceTrackerRef JD, LLVMOrcThreadSafeModuleRef TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an IR module to the given ResourceTracker's JITDylib in the given LLJIT instance. <a href="#ga1bb8b6fe0c4d07c2c538d6b84aac896e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaf8efaaa71b4b22ed96c3c05b93e98273">LLVMOrcLLJITLookup</a> (LLVMOrcLLJITRef J, LLVMOrcExecutorAddress *Result, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the given symbol in the main JITDylib of the given LLJIT instance. <a href="#gaf8efaaa71b4b22ed96c3c05b93e98273">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga3bbc2d2a267b064d8f9526db38fb620e">LLVMOrcLLJITGetObjLinkingLayer</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a non-owning reference to the LLJIT instance's object linking layer. <a href="#ga3bbc2d2a267b064d8f9526db38fb620e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga23625da1e5775d1b063319ee1e7ca83b">LLVMOrcObjectTransformLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gacafb1c738d5a5a1e49e34988765be396">LLVMOrcLLJITGetObjTransformLayer</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a non-owning reference to the LLJIT instance's object linking layer. <a href="#gacafb1c738d5a5a1e49e34988765be396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae01c36dccf1a785726fa3cd9e4baf54c">LLVMOrcIRTransformLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ga7a9a79c33d8117ee299c49597bc5b337">LLVMOrcLLJITGetIRTransformLayer</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a non-owning reference to the LLJIT instance's IR transform layer. <a href="#ga7a9a79c33d8117ee299c49597bc5b337">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#gaeee8a24ff1d99cfebb46b43b1a557324">LLVMOrcLLJITGetDataLayoutStr</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the LLJIT instance's default data layout string. <a href="#gaeee8a24ff1d99cfebb46b43b1a557324">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### LLVMOrcLLJITBuilderObjectLinkingLayerCreatorFunction {#ga20abb929df8d498ee59f205a897a066c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef LLVMOrcObjectLayerRef( * LLVMOrcLLJITBuilderObjectLinkingLayerCreatorFunction) (void *Ctx, LLVMOrcExecutionSessionRef ES, const char *Triple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A function for constructing an ObjectLinkingLayer instance to be used by an LLJIT instance.</p>


<p>Clients can call LLVMOrcLLJITBuilderSetObjectLinkingLayerCreator to set the creator function to use when constructing an LLJIT instance. This can be used to override the default linking layer implementation that would otherwise be chosen by LLJITBuilder.</p>


<p>Object linking layers returned by this function will become owned by the LLJIT instance. The client is not responsible for managing their lifetimes after the function returns.</p>


<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

### LLVMOrcLLJITBuilderRef {#ga73a506a01a91405ba0548fde502df6dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOrcOpaqueLLJITBuilder* LLVMOrcLLJITBuilderRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A reference to an orc::LLJITBuilder instance.</p>

<p>Definition at line 61 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

### LLVMOrcLLJITRef {#ga1e454b80a0ff83ee40d654f9d76c99a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef struct LLVMOrcOpaqueLLJIT* LLVMOrcLLJITRef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>A reference to an orc::LLJIT instance.</p>

<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### LLVMOrcCreateLLJIT() {#gae5289a7cc63f872a7ba713bdaef88cd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcCreateLLJIT (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> * Result, <a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a> Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an LLJIT instance from an LLJITBuilder.</p>


<p>This operation takes ownership of the Builder argument: clients should not dispose of the builder after calling this function (even if the function returns an error). If a null Builder argument is provided then a default-constructed LLJITBuilder will be used.</p>


<p>On success the resulting LLJIT instance is uniquely owned by the client and automatically manages the memory of all JIT'd code and all modules that are transferred to it (e.g. via LLVMOrcLLJITAddLLVMIRModule). Disposing of the LLJIT instance will free all memory managed by the JIT, including JIT'd code and not-yet compiled modules.</p>


<p>Declaration at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 922 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/llvmcerror/#ga7073a9a5281337ab9bc306eeb567dd48">LLVMErrorSuccess</a>, <a href="#gaa5d922ee863fdc7d2dc05233ac736581">LLVMOrcCreateLLJITBuilder</a>, <a href="#gaacb935664319f97d76294ccbb536aa82">LLVMOrcDisposeLLJITBuilder</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcCreateLLJITBuilder() {#gaa5d922ee863fdc7d2dc05233ac736581}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcLLJITBuilderRef LLVMOrcCreateLLJITBuilder (void)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Create an LLVMOrcLLJITBuilder.</p>


<p>The client owns the resulting LLJITBuilder and should dispose of it using LLVMOrcDisposeLLJITBuilder once they are done with it.</p>


<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 897 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>


<p>Referenced by <a href="#gae5289a7cc63f872a7ba713bdaef88cd9">LLVMOrcCreateLLJIT</a>.</p>

</div>
</div>

### LLVMOrcDisposeLLJIT() {#ga364a3b00fb6982a14e2532cec903e8ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcDisposeLLJIT (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispose of an LLJIT instance.</p>

<p>Declaration at line 122 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 941 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/llvmcerror/#ga7073a9a5281337ab9bc306eeb567dd48">LLVMErrorSuccess</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMOrcDisposeLLJITBuilder() {#gaacb935664319f97d76294ccbb536aa82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMOrcDisposeLLJITBuilder (<a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a> Builder)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dispose of an <a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a>.</p>


<p>This should only be called if ownership has not been passed to LLVMOrcCreateLLJIT (e.g. because some error prevented that function from being called).</p>


<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 901 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>


<p>Referenced by <a href="#gae5289a7cc63f872a7ba713bdaef88cd9">LLVMOrcCreateLLJIT</a>.</p>

</div>
</div>

### LLVMOrcLLJITAddLLVMIRModule() {#ga400c50b1c5b751715dae5ae61b3d2bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcLLJITAddLLVMIRModule (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a> JD, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga648d8baae98e849c320c2cf7ec7e548e">LLVMOrcThreadSafeModuleRef</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an IR module to the given JITDylib in the given LLJIT instance.</p>


<p>This operation transfers ownership of the TSM argument to the LLJIT instance. The TSM argument should not be disposed of or referenced once this function returns.</p>


<p>Resources associated with the given Module will be tracked by the given JITDylib's default resource tracker.</p>


<p>Declaration at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 982 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITAddLLVMIRModuleWithRT() {#ga1bb8b6fe0c4d07c2c538d6b84aac896e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcLLJITAddLLVMIRModuleWithRT (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga89e1aa5a29b792a5bfa7336ceb3dc9aa">LLVMOrcResourceTrackerRef</a> JD, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga648d8baae98e849c320c2cf7ec7e548e">LLVMOrcThreadSafeModuleRef</a> TSM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add an IR module to the given ResourceTracker's JITDylib in the given LLJIT instance.</p>


<p>This operation transfers ownership of the TSM argument to the LLJIT instance. The TSM argument should not be disposed of or referenced once this function returns.</p>


<p>Resources associated with the given Module will be tracked by ResourceTracker RT.</p>


<p>Declaration at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 989 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITAddObjectFile() {#ga10aa9d9cad65d7ef661abcf79461ee3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcLLJITAddObjectFile (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a> JD, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a> ObjBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a buffer representing an object file to the given JITDylib in the given LLJIT instance.</p>


<p>This operation transfers ownership of the buffer to the LLJIT instance. The buffer should not be disposed of or referenced once this function returns.</p>


<p>Resources associated with the given object will be tracked by the given JITDylib's default resource tracker.</p>


<p>Declaration at line 170 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 968 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITAddObjectFileWithRT() {#ga4bff68f864841da604a930c5b603762b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcLLJITAddObjectFileWithRT (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga89e1aa5a29b792a5bfa7336ceb3dc9aa">LLVMOrcResourceTrackerRef</a> RT, <a href="/web-llvm/docs/api/groups/llvmcsupporttypes/#ga9867eaa7b17ba17405cdf2539bedb108">LLVMMemoryBufferRef</a> ObjBuffer)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a buffer representing an object file to the given ResourceTracker's JITDylib in the given LLJIT instance.</p>


<p>This operation transfers ownership of the buffer to the LLJIT instance. The buffer should not be disposed of or referenced once this function returns.</p>


<p>Resources associated with the given object will be tracked by ResourceTracker RT.</p>


<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 974 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITBuilderSetJITTargetMachineBuilder() {#ga2d260f2b220e24dddae3216287134d40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMOrcLLJITBuilderSetJITTargetMachineBuilder (<a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a> Builder, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga46ed788f31d61b98c26e7db8043cfc7d">LLVMOrcJITTargetMachineBuilderRef</a> JTMB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the JITTargetMachineBuilder to be used when constructing the LLJIT instance.</p>


<p>Calling this function is optional: if it is not called then the LLJITBuilder will use JITTargeTMachineBuilder::detectHost to construct a JITTargetMachineBuilder.</p>


<p>This function takes ownership of the JTMB argument: clients should not dispose of the JITTargetMachineBuilder after calling this function.</p>


<p>Declaration at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 905 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaff9873d4cb56e4b0e91fe99b8e52a309">LLVMOrcDisposeJITTargetMachineBuilder</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITBuilderSetObjectLinkingLayerCreator() {#ga788e6b99d9d85377ca3e9c1c4f609de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LLVMOrcLLJITBuilderSetObjectLinkingLayerCreator (<a href="#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a> Builder, <a href="#ga20abb929df8d498ee59f205a897a066c">LLVMOrcLLJITBuilderObjectLinkingLayerCreatorFunction</a> F, void * Ctx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set an ObjectLinkingLayer creator function for this LLJIT instance.</p>

<p>Declaration at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetDataLayoutStr() {#gaeee8a24ff1d99cfebb46b43b1a557324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMOrcLLJITGetDataLayoutStr (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the LLJIT instance's default data layout string.</p>


<p>This string is owned by the LLJIT instance and does not need to be freed by the caller.</p>


<p>Declaration at line 243 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 1152 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetExecutionSession() {#gaae37b5fc90b38055ede42c0afa2e7583}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcExecutionSessionRef LLVMOrcLLJITGetExecutionSession (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a reference to the ExecutionSession for this LLJIT instance.</p>


<p>The ExecutionSession is owned by the LLJIT instance. The client is not responsible for managing its memory.</p>


<p>Declaration at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 946 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetGlobalPrefix() {#gaec73242a3ea26fcaec0d4d3565254a10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char LLVMOrcLLJITGetGlobalPrefix (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the global prefix character according to the LLJIT's DataLayout.</p>

<p>Declaration at line 149 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 958 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetIRTransformLayer() {#ga7a9a79c33d8117ee299c49597bc5b337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcIRTransformLayerRef LLVMOrcLLJITGetIRTransformLayer (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a non-owning reference to the LLJIT instance's IR transform layer.</p>

<p>Declaration at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 1148 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetMainJITDylib() {#ga6c222ab7584b63113858cef2e3251013}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcJITDylibRef LLVMOrcLLJITGetMainJITDylib (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a reference to the Main JITDylib.</p>


<p>The JITDylib is owned by the LLJIT instance. The client is not responsible for managing its memory.</p>


<p>Declaration at line 138 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 950 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetObjLinkingLayer() {#ga3bbc2d2a267b064d8f9526db38fb620e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcObjectLayerRef LLVMOrcLLJITGetObjLinkingLayer (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a non-owning reference to the LLJIT instance's object linking layer.</p>

<p>Declaration at line 224 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 1012 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetObjTransformLayer() {#gacafb1c738d5a5a1e49e34988765be396}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcObjectTransformLayerRef LLVMOrcLLJITGetObjTransformLayer (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns a non-owning reference to the LLJIT instance's object linking layer.</p>

<p>Declaration at line 230 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 1017 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITGetTripleString() {#ga976d0d5a897124006dbbaf94395f4b80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * LLVMOrcLLJITGetTripleString (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the target triple for this LLJIT instance.</p>


<p>This string is owned by the LLJIT instance and should not be freed by the client.</p>


<p>Declaration at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 954 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITLookup() {#gaf8efaaa71b4b22ed96c3c05b93e98273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMErrorRef LLVMOrcLLJITLookup (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J, <a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga97e95b1f18576f4c1cef9d33b11c7fe3">LLVMOrcExecutorAddress</a> * Result, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up the given symbol in the main JITDylib of the given LLJIT instance.</p>


<p>This operation does not take ownership of the Name argument.</p>


<p>Declaration at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 997 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/llvmcerror/#ga7073a9a5281337ab9bc306eeb567dd48">LLVMErrorSuccess</a>, <a href="/web-llvm/docs/api/namespaces/llvm/orc/#a1448b52253eb43f8f07b7f5d94336a47a8eea62084ca7e541d918e823422bd82e">llvm::orc::Result</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

### LLVMOrcLLJITMangleAndIntern() {#ga53d78919ce533b45f86230a41a78c8a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMOrcSymbolStringPoolEntryRef LLVMOrcLLJITMangleAndIntern (<a href="#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a> J, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * UnmangledName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Mangles the given string according to the LLJIT instance's DataLayout, then interns the result in the SymbolStringPool and returns a reference to the pool entry.</p>


<p>Clients should call LLVMOrcReleaseSymbolStringPoolEntry to decrement the ref-count on the pool entry once they are finished with this value.</p>


<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm-c/lljit-h">LLJIT.h</a>, definition at line 963 of file <a href="/web-llvm/docs/api/files/lib/lib/executionengine/lib/executionengine/orc/orcv2cbindings-cpp">OrcV2CBindings.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/orc/symbolstringpoolentryunsafe/#a9e9c4862b3a45f4e96bd602c519991c5">llvm::orc::SymbolStringPoolEntryUnsafe::take</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa3d613e3ad429bdb5b1a7d22796028e9">llvm::unwrap</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#ac9a23c88949ad27ad62f0ee03254ee3a">llvm::wrap</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
