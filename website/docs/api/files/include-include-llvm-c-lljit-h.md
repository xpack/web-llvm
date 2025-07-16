---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/include/include/llvm-c/lljit-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `LLJIT.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/error-h">llvm-c/Error.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/orc-h">llvm-c/Orc.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/targetmachine-h">llvm-c/TargetMachine.h</a>"
#include "<a href="/web-llvm/docs/api/files/include/include/llvm-c/types-h">llvm-c/Types.h</a>"
</div>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a>(* <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga20abb929df8d498ee59f205a897a066c">LLVMOrcLLJITBuilderObjectLinkingLayerCreatorFunction</a>)(void *Ctx, LLVMOrcExecutionSessionRef ES, const char *Triple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A function for constructing an ObjectLinkingLayer instance to be used by an LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga20abb929df8d498ee59f205a897a066c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueLLJITBuilder * <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::LLJITBuilder instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga73a506a01a91405ba0548fde502df6dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">struct LLVMOrcOpaqueLLJIT * <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga1e454b80a0ff83ee40d654f9d76c99a0">LLVMOrcLLJITRef</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A reference to an orc::LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga1e454b80a0ff83ee40d654f9d76c99a0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaa5d922ee863fdc7d2dc05233ac736581">LLVMOrcCreateLLJITBuilder</a> (void)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an LLVMOrcLLJITBuilder. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaa5d922ee863fdc7d2dc05233ac736581">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaacb935664319f97d76294ccbb536aa82">LLVMOrcDisposeLLJITBuilder</a> (LLVMOrcLLJITBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga73a506a01a91405ba0548fde502df6dd">LLVMOrcLLJITBuilderRef</a>. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaacb935664319f97d76294ccbb536aa82">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga2d260f2b220e24dddae3216287134d40">LLVMOrcLLJITBuilderSetJITTargetMachineBuilder</a> (LLVMOrcLLJITBuilderRef Builder, LLVMOrcJITTargetMachineBuilderRef JTMB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the JITTargetMachineBuilder to be used when constructing the LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga2d260f2b220e24dddae3216287134d40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga788e6b99d9d85377ca3e9c1c4f609de9">LLVMOrcLLJITBuilderSetObjectLinkingLayerCreator</a> (LLVMOrcLLJITBuilderRef Builder, LLVMOrcLLJITBuilderObjectLinkingLayerCreatorFunction F, void *Ctx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set an ObjectLinkingLayer creator function for this LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga788e6b99d9d85377ca3e9c1c4f609de9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gae5289a7cc63f872a7ba713bdaef88cd9">LLVMOrcCreateLLJIT</a> (LLVMOrcLLJITRef *Result, LLVMOrcLLJITBuilderRef Builder)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create an LLJIT instance from an LLJITBuilder. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gae5289a7cc63f872a7ba713bdaef88cd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga364a3b00fb6982a14e2532cec903e8ae">LLVMOrcDisposeLLJIT</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dispose of an LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga364a3b00fb6982a14e2532cec903e8ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga653c8620112eddd7c75085a0b586c97d">LLVMOrcExecutionSessionRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaae37b5fc90b38055ede42c0afa2e7583">LLVMOrcLLJITGetExecutionSession</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a reference to the ExecutionSession for this LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaae37b5fc90b38055ede42c0afa2e7583">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaf57ee27735dc1436c076c9579d074869">LLVMOrcJITDylibRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga6c222ab7584b63113858cef2e3251013">LLVMOrcLLJITGetMainJITDylib</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a reference to the Main JITDylib. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga6c222ab7584b63113858cef2e3251013">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga976d0d5a897124006dbbaf94395f4b80">LLVMOrcLLJITGetTripleString</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the target triple for this LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga976d0d5a897124006dbbaf94395f4b80">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaec73242a3ea26fcaec0d4d3565254a10">LLVMOrcLLJITGetGlobalPrefix</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the global prefix character according to the LLJIT's DataLayout. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaec73242a3ea26fcaec0d4d3565254a10">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gab64e9fc4c88c012a3d9f6f609877f449">LLVMOrcSymbolStringPoolEntryRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga53d78919ce533b45f86230a41a78c8a9">LLVMOrcLLJITMangleAndIntern</a> (LLVMOrcLLJITRef J, const char *UnmangledName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Mangles the given string according to the LLJIT instance's DataLayout, then interns the result in the SymbolStringPool and returns a reference to the pool entry. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga53d78919ce533b45f86230a41a78c8a9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga10aa9d9cad65d7ef661abcf79461ee3e">LLVMOrcLLJITAddObjectFile</a> (LLVMOrcLLJITRef J, LLVMOrcJITDylibRef JD, LLVMMemoryBufferRef ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a buffer representing an object file to the given JITDylib in the given LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga10aa9d9cad65d7ef661abcf79461ee3e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga4bff68f864841da604a930c5b603762b">LLVMOrcLLJITAddObjectFileWithRT</a> (LLVMOrcLLJITRef J, LLVMOrcResourceTrackerRef RT, LLVMMemoryBufferRef ObjBuffer)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a buffer representing an object file to the given ResourceTracker's JITDylib in the given LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga4bff68f864841da604a930c5b603762b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga400c50b1c5b751715dae5ae61b3d2bb4">LLVMOrcLLJITAddLLVMIRModule</a> (LLVMOrcLLJITRef J, LLVMOrcJITDylibRef JD, LLVMOrcThreadSafeModuleRef TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an IR module to the given JITDylib in the given LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga400c50b1c5b751715dae5ae61b3d2bb4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga1bb8b6fe0c4d07c2c538d6b84aac896e">LLVMOrcLLJITAddLLVMIRModuleWithRT</a> (LLVMOrcLLJITRef J, LLVMOrcResourceTrackerRef JD, LLVMOrcThreadSafeModuleRef TSM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an IR module to the given ResourceTracker's JITDylib in the given LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga1bb8b6fe0c4d07c2c538d6b84aac896e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcerror/#gad81d81a316ef38888533a24b786a6605">LLVMErrorRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaf8efaaa71b4b22ed96c3c05b93e98273">LLVMOrcLLJITLookup</a> (LLVMOrcLLJITRef J, LLVMOrcExecutorAddress *Result, const char *Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the given symbol in the main JITDylib of the given LLJIT instance. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaf8efaaa71b4b22ed96c3c05b93e98273">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gaa54913a75bd017c8cc988942cac79bad">LLVMOrcObjectLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga3bbc2d2a267b064d8f9526db38fb620e">LLVMOrcLLJITGetObjLinkingLayer</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a non-owning reference to the LLJIT instance's object linking layer. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga3bbc2d2a267b064d8f9526db38fb620e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#ga23625da1e5775d1b063319ee1e7ca83b">LLVMOrcObjectTransformLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gacafb1c738d5a5a1e49e34988765be396">LLVMOrcLLJITGetObjTransformLayer</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a non-owning reference to the LLJIT instance's object linking layer. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gacafb1c738d5a5a1e49e34988765be396">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionengineorc/#gae01c36dccf1a785726fa3cd9e4baf54c">LLVMOrcIRTransformLayerRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga7a9a79c33d8117ee299c49597bc5b337">LLVMOrcLLJITGetIRTransformLayer</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a non-owning reference to the LLJIT instance's IR transform layer. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#ga7a9a79c33d8117ee299c49597bc5b337">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaeee8a24ff1d99cfebb46b43b1a557324">LLVMOrcLLJITGetDataLayoutStr</a> (LLVMOrcLLJITRef J)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the LLJIT instance's default data layout string. <a href="/web-llvm/docs/api/groups/llvmcexecutionenginelljit/#gaeee8a24ff1d99cfebb46b43b1a557324">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
