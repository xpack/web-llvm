---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/module
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `Module` Class

<p>A <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> instance is used to store all the information related to an LLVM module. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class llvm::Module { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">llvm/IR/Module.h</a>"
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a288bf7fe3df7b3822b5763009cc81366">dropTriviallyDeadConstantArrays</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroy ConstantArrays in <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> if they are not used. <a href="#a288bf7fe3df7b3822b5763009cc81366">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a344446b3349dc1d73464b3bb5ae0e6bf">getSemanticInterposition</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns whether semantic interposition is to be respected. <a href="#a344446b3349dc1d73464b3bb5ae0e6bf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a7684b2043eab9432d655cb4edc0c3">setSemanticInterposition</a> (bool)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set whether semantic interposition is to be respected. <a href="#a05a7684b2043eab9432d655cb4edc0c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2cbb95a96b08de2941c0531bd754e4">getRtLibUseGOT</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if PLT should be avoided for RTLib calls. <a href="#a5e2cbb95a96b08de2941c0531bd754e4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf200dbe6f728c2eb068e5b87c93024">setRtLibUseGOT</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set that PLT should be avoid for RTLib calls. <a href="#a3bf200dbe6f728c2eb068e5b87c93024">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2aac3b278b44b702ccbcce7284cdf2">getDirectAccessExternalData</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set whether referencing global variables can use direct access relocations on <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets. <a href="#afc2aac3b278b44b702ccbcce7284cdf2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1202793bde8d50983a5814cb8b1fb5dd">setDirectAccessExternalData</a> (bool Value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6113fb21d027efcf333cbe204b2e2633">getUwtable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set whether synthesized functions should get the uwtable attribute. <a href="#a6113fb21d027efcf333cbe204b2e2633">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7033a69af274cff3526d34222279863e">setUwtable</a> (UWTableKind Kind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a0c7a337870929cbf2d49865f77c42927">FramePointerKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e6e68937a2bd1ea02a5df34f3763482">getFramePointer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set whether synthesized functions should get the "frame-pointer" attribute. <a href="#a7e6e68937a2bd1ea02a5df34f3763482">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55241d651101cf9629b2a7d822904eee">setFramePointer</a> (FramePointerKind Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c95a95f585b6eae4a606ff335a3a50a">getStackProtectorGuard</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set what kind of stack protector guard to use. <a href="#a5c95a95f585b6eae4a606ff335a3a50a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64d1cac4963d3f640df8967a5caddf60">setStackProtectorGuard</a> (StringRef Kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa484c371d7b1dcdabcc96ad78c38b62b">getStackProtectorGuardReg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set which register to use as the stack protector guard register. <a href="#aa484c371d7b1dcdabcc96ad78c38b62b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a889574485e1bda76d4c2e2cfece65690">setStackProtectorGuardReg</a> (StringRef Reg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cd573d063de53b69ba0bd441c52c382">getStackProtectorGuardSymbol</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set a symbol to use as the stack protector guard. <a href="#a2cd573d063de53b69ba0bd441c52c382">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04001950ccace6c01bfb634d3a055e3a">setStackProtectorGuardSymbol</a> (StringRef Symbol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbea21913d36e4bb861d22a05ea081ae">getStackProtectorGuardOffset</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set what offset from the stack protector to use. <a href="#afbea21913d36e4bb861d22a05ea081ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf70f65e0b09aba4026bbe0009751d25">setStackProtectorGuardOffset</a> (int Offset)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb37b956b67f6a06895a1cdfa8cfd28">getOverrideStackAlignment</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get/set the stack alignment overridden from the default. <a href="#a7eb37b956b67f6a06895a1cdfa8cfd28">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a4208cd36d651811e339ddf0900d41">setOverrideStackAlignment</a> (unsigned Align)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a142c912d8ab5e38df3b8742daea8e06c">getMaxTLSAlignment</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16d6ddd53501159a453ac63113851b9b">setOwnedMemoryBuffer</a> (std::unique_ptr&lt; MemoryBuffer &gt; MB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take ownership of the given memory buffer. <a href="#a16d6ddd53501159a453ac63113851b9b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71dec001bcc3e5e68e0970e528bae35e">setPartialSampleProfileRatio</a> (const ModuleSummaryIndex &amp;Index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the partial sample profile ratio in the profile summary module flag, if applicable. <a href="#a71dec001bcc3e5e68e0970e528bae35e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6847095f6ef27e76a1336d827f45a78">getDarwinTargetVariantTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target variant triple which is a string describing a variant of the target host platform. <a href="#af6847095f6ef27e76a1336d827f45a78">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94bbecbd83ac11d59a0653ea5d4fbf8b">setDarwinTargetVariantTriple</a> (StringRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the target variant triple which is a string describing a variant of the target host platform. <a href="#a94bbecbd83ac11d59a0653ea5d4fbf8b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbcfb512d2c49571267a607e14c7f385">getDarwinTargetVariantSDKVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target variant version build SDK version metadata. <a href="#acbcfb512d2c49571267a607e14c7f385">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af036e8aea57e28daa0a63afb9c764b66">setDarwinTargetVariantSDKVersion</a> (VersionTuple Version)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the target variant version build SDK version metadata. <a href="#af036e8aea57e28daa0a63afb9c764b66">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Types And Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ModFlagBehavior { <a href="#a0a5c55e12c97b80021330fe82b642293">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This enumeration defines the supported behaviors of module flags. <a href="#a0a5c55e12c97b80021330fe82b642293">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a949869855fcd2290a285a90b2c353f1e">GlobalListType</a> = <a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for the list of global variables. <a href="#a949869855fcd2290a285a90b2c353f1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a391a6ee45603f6d05cb045d89e79f344">FunctionListType</a> = <a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for the list of functions. <a href="#a391a6ee45603f6d05cb045d89e79f344">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4736363638b8f744ae635ffda5b5b6d">AliasListType</a> = <a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for the list of aliases. <a href="#ad4736363638b8f744ae635ffda5b5b6d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf18e123231905a06aba1ff2102ab1dd">IFuncListType</a> = <a href="/web-llvm/docs/api/classes/llvm/symboltablelist">SymbolTableList</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for the list of ifuncs. <a href="#adf18e123231905a06aba1ff2102ab1dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382815cf826755c2a1c0269c7bb70a05">NamedMDListType</a> = <a href="/web-llvm/docs/api/namespaces/llvm/#a62ea5abc9af8e7ee394912e2617cf30f">ilist</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for the list of named metadata. <a href="#a382815cf826755c2a1c0269c7bb70a05">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0436d9008c05925a6e20381a1f728189">ComdatSymTabType</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type of the comdat "symbol" table. <a href="#a0436d9008c05925a6e20381a1f728189">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d2c30531f5c9d1872fdc84db1ecfb06">NamedMDSymTabType</a> = <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> * &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The type for mapping names to named metadata. <a href="#a7d2c30531f5c9d1872fdc84db1ecfb06">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fbda2aeb884e5cf4b07547bd8be6e4d">global_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">GlobalListType::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Global Variable iterator. <a href="#a7fbda2aeb884e5cf4b07547bd8be6e4d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694ea3a50ed53ee11c1f6845f91e48f7">const_global_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">GlobalListType::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Global Variable constant iterator. <a href="#a694ea3a50ed53ee11c1f6845f91e48f7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7893161303eb07ae7864db6b3d004d9e">iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">FunctionListType::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> iterators. <a href="#a7893161303eb07ae7864db6b3d004d9e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae994bfe8d35ac5ab06dca56349a30856">const_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">FunctionListType::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> constant iterator. <a href="#ae994bfe8d35ac5ab06dca56349a30856">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb72a16fe5f70a1fdc2a0065df39a266">reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3597c16fc1832e39109d9848a63cc55c">FunctionListType::reverse_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> reverse iterator. <a href="#abb72a16fe5f70a1fdc2a0065df39a266">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86490fe0fd359e23da4899ea02ca640a">const_reverse_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a297861b8ff76496286b3bea882c2969a">FunctionListType::const_reverse_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> constant reverse iterator. <a href="#a86490fe0fd359e23da4899ea02ca640a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4be791e0744fcfa52a34c3ff9f0eaae">alias_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">AliasListType::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Global Alias iterators. <a href="#aa4be791e0744fcfa52a34c3ff9f0eaae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab98e2331fe3a7ce06d273d32d69035d9">const_alias_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">AliasListType::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Global Alias constant iterator. <a href="#ab98e2331fe3a7ce06d273d32d69035d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518fb2f22337cd9308ec7dbb6fe168c1">ifunc_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">IFuncListType::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Global IFunc iterators. <a href="#a518fb2f22337cd9308ec7dbb6fe168c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93358ad3206079296f6a6e057f5ba448">const_ifunc_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">IFuncListType::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Global IFunc constant iterator. <a href="#a93358ad3206079296f6a6e057f5ba448">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1faae21f2e2c6de60ffc37e3eb029a8e">named_metadata_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">NamedMDListType::iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The named metadata iterators. <a href="#a1faae21f2e2c6de60ffc37e3eb029a8e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e9870d2286e1612feaf8ad1578ab80b">const_named_metadata_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a3a5c6f429b19022105ee49f587c7ed04">NamedMDListType::const_iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The named metadata constant iterators. <a href="#a3e9870d2286e1612feaf8ad1578ab80b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa09a52095810697305805737b3a0920">isValidModFlagBehavior</a> (Metadata *MD, ModFlagBehavior &amp;MFB)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Checks if <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> represents a valid <a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a>, and stores the converted result in MFB. <a href="#aaa09a52095810697305805737b3a0920">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Convenience iterators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9300d9104835e2925907f8541da1d187">global_object_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/concat-iterator">concat_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a>, <a href="#a7893161303eb07ae7864db6b3d004d9e">iterator</a>, <a href="#a7fbda2aeb884e5cf4b07547bd8be6e4d">global_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae619f2a56af4f4e067b672c8f3dcdcd4">const_global_object_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/concat-iterator">concat_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalobject">GlobalObject</a>, <a href="#ae994bfe8d35ac5ab06dca56349a30856">const_iterator</a>, <a href="#a694ea3a50ed53ee11c1f6845f91e48f7">const_global_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6931ca58bf137002cb2affb21594172">global_value_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/concat-iterator">concat_iterator</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>, <a href="#a7893161303eb07ae7864db6b3d004d9e">iterator</a>, <a href="#a7fbda2aeb884e5cf4b07547bd8be6e4d">global_iterator</a>, <a href="#aa4be791e0744fcfa52a34c3ff9f0eaae">alias_iterator</a>, <a href="#a518fb2f22337cd9308ec7dbb6fe168c1">ifunc_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea433ad125d2359ae11e4c22532f04c6">const_global_value_iterator</a> = <a href="/web-llvm/docs/api/classes/llvm/concat-iterator">concat_iterator</a>&lt; <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a>, <a href="#ae994bfe8d35ac5ab06dca56349a30856">const_iterator</a>, <a href="#a694ea3a50ed53ee11c1f6845f91e48f7">const_global_iterator</a>, <a href="#ab98e2331fe3a7ce06d273d32d69035d9">const_alias_iterator</a>, <a href="#a93358ad3206079296f6a6e057f5ba448">const_ifunc_iterator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a9300d9104835e2925907f8541da1d187">global_object_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab16c33bc70855b5305e19505f6dfd8f7">global_objects</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ae619f2a56af4f4e067b672c8f3dcdcd4">const_global_object_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada4ee7ed330e79fed89afc626f13644c">global_objects</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ac6931ca58bf137002cb2affb21594172">global_value_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb3c7bb41e87372e57ea465c2196b30b">global_values</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aea433ad125d2359ae11e4c22532f04c6">const_global_value_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa60e6a71a1605f3af1fa5261bc1556a2">global_values</a> () const</td>
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

## Member Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94a6309d0b887eceade042a774361d1e">Context</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> from which types and constants are allocated. <a href="#a94a6309d0b887eceade042a774361d1e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a949869855fcd2290a285a90b2c353f1e">GlobalListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2679f249b3d55dc6d388fb26168324">GlobalList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Global Variables in the module. <a href="#a3a2679f249b3d55dc6d388fb26168324">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a391a6ee45603f6d05cb045d89e79f344">FunctionListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b179a9e32b24ab570e22ae292a30389">FunctionList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Functions in the module. <a href="#a8b179a9e32b24ab570e22ae292a30389">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad4736363638b8f744ae635ffda5b5b6d">AliasListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc64f6251b296b5119ea0c6913008f8a">AliasList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The Aliases in the module. <a href="#abc64f6251b296b5119ea0c6913008f8a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adf18e123231905a06aba1ff2102ab1dd">IFuncListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2f870fffbcc7ee53bc740073c377c5">IFuncList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The IFuncs in the module. <a href="#adf2f870fffbcc7ee53bc740073c377c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a382815cf826755c2a1c0269c7bb70a05">NamedMDListType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa73858edc074cdbf65114fe3288e1ba7">NamedMDList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The named metadata in the module. <a href="#aa73858edc074cdbf65114fe3288e1ba7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f7fc085d1258fd8b3e2129c7eba820d">GlobalScopeAsm</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Inline Asm at global scope. <a href="#a6f7fc085d1258fd8b3e2129c7eba820d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a1439efc2b9ea3d386ba47501c542e7">ValSymTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol table for values. <a href="#a6a1439efc2b9ea3d386ba47501c542e7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0436d9008c05925a6e20381a1f728189">ComdatSymTabType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55028d8fa75d0a295e6c6e12b01538c">ComdatSymTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Symbol table for COMDATs. <a href="#af55028d8fa75d0a295e6c6e12b01538c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6313291b380d37b0a033ddd7b28bf926">OwnedMemoryBuffer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> buffer directly owned by this module, for legacy clients only. <a href="#a6313291b380d37b0a033ddd7b28bf926">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/gvmaterializer">GVMaterializer</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5341b0659a9e945e58bd2cf2cf24b188">Materializer</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used to materialize GlobalValues. <a href="#a5341b0659a9e945e58bd2cf2cf24b188">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0a98092f6df3048471324f7ff6da14c">ModuleID</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Human readable identifier for the module. <a href="#ab0a98092f6df3048471324f7ff6da14c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7740900a7ccfc5f7282ae665a1eecc65">SourceFileName</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Original source file name for module, recorded in bitcode. <a href="#a7740900a7ccfc5f7282ae665a1eecc65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a359beca1e7ecb854b74619c1f2e206e6">TargetTriple</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Platform target triple <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> compiled on Format: (arch)(sub)-(vendor)-(sys0-(abi) <a href="#a359beca1e7ecb854b74619c1f2e206e6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7d2c30531f5c9d1872fdc84db1ecfb06">NamedMDSymTabType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b992bd2655be6f6647c8b5a37b5a131">NamedMDSymTab</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> names. <a href="#a5b992bd2655be6f6647c8b5a37b5a131">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7f72a7f2947a0cdd39feb0a4c30618c">DL</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> associated with the module. <a href="#aa7f72a7f2947a0cdd39feb0a4c30618c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a601fcff9cc3c2a5a79bbca011165b167">CurrentIntrinsicIds</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of the current unique id count for the specified intrinsic basename. <a href="#a601fcff9cc3c2a5a79bbca011165b167">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; std::pair&lt; <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * &gt;, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73143559e72a9f148579f585081c9638">UniquedIntrinsicNames</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Keep track of uniqued names of intrinsics based on unnamed types. <a href="#a73143559e72a9f148579f585081c9638">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5902a8436605a3de99202f879f259450">ModuleFlags</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>llvm.module.flags metadata <a href="#a5902a8436605a3de99202f879f259450">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

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

## Direct access to the globals list, functions list, and symbol table Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad87cca93b972c266e973d1a0996afd00">llvm::SymbolTableListTraits&lt; llvm::GlobalVariable &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac233817c65ce7ee15cec581b62fe0ec5">llvm::SymbolTableListTraits&lt; llvm::GlobalAlias &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc1172cc3dd5889fdf379ed6dec8b81">llvm::SymbolTableListTraits&lt; llvm::GlobalIFunc &gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a391a6ee45603f6d05cb045d89e79f344">FunctionListType</a> Module::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6af060631f47797b9ed01593c0853af">getSublistAccess</a> (Function *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a391a6ee45603f6d05cb045d89e79f344">FunctionListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cbf634a57382636ca0dbbcf779655ae">getFunctionList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of functions (constant). <a href="#a8cbf634a57382636ca0dbbcf779655ae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a391a6ee45603f6d05cb045d89e79f344">FunctionListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97db845caa6bba2a5ff3ffb8a2b8c23f">getFunctionList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of functions. <a href="#a97db845caa6bba2a5ff3ffb8a2b8c23f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5724c4a6f094c94f6652a4a6c5d59f93">removeAlias</a> (GlobalAlias *Alias)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Detach <span class="doxyComputerOutput">Alias</span> from the list but don't delete it. <a href="#a5724c4a6f094c94f6652a4a6c5d59f93">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2bb9b6dfce993d3eddec7345684f42">eraseAlias</a> (GlobalAlias *Alias)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">Alias</span> from the list and delete it. <a href="#a9a2bb9b6dfce993d3eddec7345684f42">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef81cefbdf9af4e321646419b65fcbd9">insertAlias</a> (GlobalAlias *Alias)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert <span class="doxyComputerOutput">Alias</span> at the end of the alias list and take ownership. <a href="#aef81cefbdf9af4e321646419b65fcbd9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0638c1703df1253b2737c50d5f59b5a5">removeIFunc</a> (GlobalIFunc *IFunc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Detach <span class="doxyComputerOutput">IFunc</span> from the list but don't delete it. <a href="#a0638c1703df1253b2737c50d5f59b5a5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d152ee09578b75228f1412cc7fdc3c5">eraseIFunc</a> (GlobalIFunc *IFunc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput">IFunc</span> from the list and delete it. <a href="#a7d152ee09578b75228f1412cc7fdc3c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f75403ce44801b257e42ef58f5c9a24">insertIFunc</a> (GlobalIFunc *IFunc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert <span class="doxyComputerOutput">IFunc</span> at the end of the alias list and take ownership. <a href="#a0f75403ce44801b257e42ef58f5c9a24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ba8b6f2a4dc44633963071c6518495">removeNamedMDNode</a> (NamedMDNode *MDNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Detach <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></span> from the list but don't delete it. <a href="#aa0ba8b6f2a4dc44633963071c6518495">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a084ca29ed6871e115ae1434ac3f3a067">eraseNamedMDNode</a> (NamedMDNode *MDNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></span> from the list and delete it. <a href="#a084ca29ed6871e115ae1434ac3f3a067">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9daea70b0389c14792d8406d422491a7">insertNamedMDNode</a> (NamedMDNode *MDNode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></span> at the end of the alias list and take ownership. <a href="#a9daea70b0389c14792d8406d422491a7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaec6166c9567e64030e08640eec2511a">getValueSymbolTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the symbol table of global variable and function identifiers. <a href="#aaec6166c9567e64030e08640eec2511a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/valuesymboltable">ValueSymbolTable</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d58d8c32a9a4787ecc667f8495ddbc2">getValueSymbolTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s symbol table of global variable and function identifiers. <a href="#a3d58d8c32a9a4787ecc667f8495ddbc2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a0436d9008c05925a6e20381a1f728189">ComdatSymTabType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1759adeccb706c96a44484dd01bdf0de">getComdatSymbolTable</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s symbol table for COMDATs (constant). <a href="#a1759adeccb706c96a44484dd01bdf0de">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a0436d9008c05925a6e20381a1f728189">ComdatSymTabType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb586ee29080a81aacea8d66e5d03498">getComdatSymbolTable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s symbol table for COMDATs. <a href="#abb586ee29080a81aacea8d66e5d03498">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a949869855fcd2290a285a90b2c353f1e">GlobalListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a522163a84424964528f409adac032803">getGlobalList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of global variables (constant). <a href="#a522163a84424964528f409adac032803">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a949869855fcd2290a285a90b2c353f1e">GlobalListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6def4f53e01fcce273158a5bfa36c1f5">getGlobalList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of global variables. <a href="#a6def4f53e01fcce273158a5bfa36c1f5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#ad4736363638b8f744ae635ffda5b5b6d">AliasListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89edfbc5688238bdb58733514db1aa6a">getAliasList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of aliases (constant). <a href="#a89edfbc5688238bdb58733514db1aa6a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad4736363638b8f744ae635ffda5b5b6d">AliasListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65887d40ddec20928f0d304054f47c33">getAliasList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of aliases. <a href="#a65887d40ddec20928f0d304054f47c33">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#adf18e123231905a06aba1ff2102ab1dd">IFuncListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63020ec8de2922109a61bc527504df12">getIFuncList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of ifuncs (constant). <a href="#a63020ec8de2922109a61bc527504df12">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adf18e123231905a06aba1ff2102ab1dd">IFuncListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364647adc4e8b845cf4ed6d05b9c7e20">getIFuncList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of ifuncs. <a href="#a364647adc4e8b845cf4ed6d05b9c7e20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="#a382815cf826755c2a1c0269c7bb70a05">NamedMDListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa720aeae675bb283c324343ffdcf657f">getNamedMDList</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of named metadata (constant). <a href="#aa720aeae675bb283c324343ffdcf657f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a382815cf826755c2a1c0269c7bb70a05">NamedMDListType</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba96540297e2812360f71dd0a79881c1">getNamedMDList</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of named metadata. <a href="#aba96540297e2812360f71dd0a79881c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a949869855fcd2290a285a90b2c353f1e">GlobalListType</a> Module::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf4c694e6136afbc96245d473bf0bd2e">getSublistAccess</a> (GlobalVariable *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#ad4736363638b8f744ae635ffda5b5b6d">AliasListType</a> Module::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad15884cc92ca5611ca4b1f2bdd37d218">getSublistAccess</a> (GlobalAlias *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#adf18e123231905a06aba1ff2102ab1dd">IFuncListType</a> Module::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4299950620b3a5aba752c10c8eb345">getSublistAccess</a> (GlobalIFunc *)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#a382815cf826755c2a1c0269c7bb70a05">NamedMDListType</a> Module::*</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa9774bbb39354bbccc67ad3af32d35">getSublistAccess</a> (NamedMDNode *)</td>
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

## Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1901c01c9f1724db542f99882fb6ca48">IsNewDbgInfoFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Is this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> using intrinsics to record the position of debugging information, or non-intrinsic records? <a href="#a1901c01c9f1724db542f99882fb6ca48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b87b2e44ce9a2a303c79088f047082e">removeDebugIntrinsicDeclarations</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Used when printing this module in the new debug info format; removes all declarations of debug intrinsics that are replaced by non-intrinsic records in the new format. <a href="#a3b87b2e44ce9a2a303c79088f047082e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc4ac48c0468db2a9c3cda662dddb4a">convertToNewDbgValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a0c54875b7841d0222b427f0792671">convertFromNewDbgValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2fdf89ed4d5971a35c36c849956b321">setIsNewDbgInfoFormat</a> (bool UseNewFormat)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82f2e848e67d05f11845c5d49fccee3e">setNewDbgInfoFormatFlag</a> (bool NewFlag)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a378f93ece2ac999e500f07056cfe6528">Module</a> (StringRef ModuleID, LLVMContext &amp;C)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> constructor. <a href="#a378f93ece2ac999e500f07056cfe6528">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c9d9c096786d127590fdd8aa2b7d681">~Module</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The module destructor. This will dropAllReferences. <a href="#a7c9d9c096786d127590fdd8aa2b7d681">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78b9c4843c02991e755fd58d2acf064e">operator=</a> (Module &amp;&amp;Other)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Move assignment. <a href="#a78b9c4843c02991e755fd58d2acf064e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Module Level Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a4fa55f19f0d5bb47d1fe6802e18d1a">getModuleIdentifier</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the module identifier which is, essentially, the name of the module. <a href="#a9a4fa55f19f0d5bb47d1fe6802e18d1a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab21a2e0542e35ef6859e2d069ab18ca4">getInstructionCount</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of non-debug IR instructions in the module. <a href="#ab21a2e0542e35ef6859e2d069ab18ca4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb981ce623b68eea5cd781ee0ae8ddf">getSourceFileName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the module's original source file name. <a href="#a4fb981ce623b68eea5cd781ee0ae8ddf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3648156c20e8cf63c5eb07c56ab2fe">getName</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a short "name" for the module. <a href="#a4b3648156c20e8cf63c5eb07c56ab2fe">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae63fce265b79048ddac80422d1d2729e">getDataLayoutStr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the data layout string for the module's target platform. <a href="#ae63fce265b79048ddac80422d1d2729e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcbe492bce3ccc16e0bbb50292576c5c">getDataLayout</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the data layout for the module's target platform. <a href="#abcbe492bce3ccc16e0bbb50292576c5c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b882824580b4666f692474ecbae56ad">getTargetTriple</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the target triple which is a string describing the target host. <a href="#a6b882824580b4666f692474ecbae56ad">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0beddb53641a541e2238617c5fac4be7">getContext</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the global data context. <a href="#a0beddb53641a541e2238617c5fac4be7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::string &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08a39a8a62016bee607e0b28e6b54e27">getModuleInlineAsm</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get any module-scope inline assembly blocks. <a href="#a08a39a8a62016bee607e0b28e6b54e27">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/randomnumbergenerator">RandomNumberGenerator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b82325a22b25d4278a37af30b202a30">createRNG</a> (const StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get a <a href="/web-llvm/docs/api/classes/llvm/randomnumbergenerator">RandomNumberGenerator</a> salted for use with this module. <a href="#a8b82325a22b25d4278a37af30b202a30">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d28d6aff37550f9cd56074ddcea2677">shouldEmitInstrCountChangedRemark</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if size-info optimization remark is enabled, false otherwise. <a href="#a7d28d6aff37550f9cd56074ddcea2677">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Module Level Mutators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acdc9e9024fd3c1059ece16631c2d094f">setModuleIdentifier</a> (StringRef ID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the module identifier. <a href="#acdc9e9024fd3c1059ece16631c2d094f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc77fdf8a02fef55beaffb19a7087c19">setSourceFileName</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the module's original source file name. <a href="#adc77fdf8a02fef55beaffb19a7087c19">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa68647befd5b72ece9bca6f6da69e391">setDataLayout</a> (StringRef Desc)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the data layout. <a href="#aa68647befd5b72ece9bca6f6da69e391">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8931880fb7ce71e068a2ac1e704adaaf">setDataLayout</a> (const DataLayout &amp;Other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af66bad1510da8a71d20002609d3b4a25">setTargetTriple</a> (StringRef T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the target triple. <a href="#af66bad1510da8a71d20002609d3b4a25">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168c2c073b44c41dc521120bda0b1047">setModuleInlineAsm</a> (StringRef Asm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the module-scope inline assembly blocks. <a href="#a168c2c073b44c41dc521120bda0b1047">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae83cb8c91cf6fa402d682f06f7535949">appendModuleInlineAsm</a> (StringRef Asm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Append to the module-scope inline assembly blocks. <a href="#ae83cb8c91cf6fa402d682f06f7535949">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Generic Value Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1e6423b61f37584900fbdcadeedafb6">getNamedValue</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the global value in the module with the specified name, of arbitrary type. <a href="#ab1e6423b61f37584900fbdcadeedafb6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475f318372cb5b119d4f08cb5833f9e5">getNumNamedValues</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the number of global values in the module. <a href="#a475f318372cb5b119d4f08cb5833f9e5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d7039664794cb004d82570dfd00063">getMDKindID</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a unique non-zero <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the specified metadata kind. <a href="#a51d7039664794cb004d82570dfd00063">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3779e6e1fb83913e81ad3b46f059bede">getMDKindNames</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the name for custom metadata IDs registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#a3779e6e1fb83913e81ad3b46f059bede">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34623cb3c79d991ca41535635f89414">getOperandBundleTags</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Result) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the bundle tags registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. <a href="#ab34623cb3c79d991ca41535635f89414">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/structtype">StructType</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c7aeef16441f671e5e541a4f3eda0c5">getIdentifiedStructTypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b91c906088d051b49c9b7f8847ecbe0">getUniqueIntrinsicName</a> (StringRef BaseName, Intrinsic::ID Id, const FunctionType *Proto)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a unique name for an intrinsic whose mangling is based on an unnamed type. <a href="#a7b91c906088d051b49c9b7f8847ecbe0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Function Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb107e4edbf05eae92936cba6801c2d9">getOrInsertFunction</a> (StringRef Name, FunctionType *T, AttributeList AttributeList)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the specified function in the module symbol table. <a href="#abb107e4edbf05eae92936cba6801c2d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5310b7bb84192372c55cbc66cd975c59">getOrInsertFunction</a> (StringRef Name, FunctionType *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgsTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2cf6738ff24ef8e3e474763aec81b401">getOrInsertFunction</a> (StringRef Name, AttributeList AttributeList, Type *RetTy, ArgsTy... Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above, but takes a list of function arguments, which makes it easier for clients to use. <a href="#a2cf6738ff24ef8e3e474763aec81b401">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgsTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a9c362a6df0554c3d9355aadfa67a1914">getOrInsertFunction</a> (StringRef Name, Type *RetTy, ArgsTy... Args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Same as above, but without the attributes. <a href="#a9c362a6df0554c3d9355aadfa67a1914">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... ArgsTy&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a89b5f89041a0375f7ece431f29421bee">getOrInsertFunction</a> (StringRef Name, AttributeList AttributeList, FunctionType *Invalid, ArgsTy... Args)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a209a615a3a32241323420cca24b5520a">getFunction</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the specified function in the module symbol table. <a href="#a209a615a3a32241323420cca24b5520a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Global Variable Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6aa4f20a3c82e66d3e0b86a62ce2873">getGlobalVariable</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the specified global variable in the module symbol table. <a href="#aa6aa4f20a3c82e66d3e0b86a62ce2873">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8812c64092590a5ebde21f70c538d1b">getGlobalVariable</a> (StringRef Name, bool AllowInternal) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>getGlobalVariable - Look up the specified global variable in the module symbol table. <a href="#ac8812c64092590a5ebde21f70c538d1b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3df989919f622a0bdc2649a0876263">getGlobalVariable</a> (StringRef Name, bool AllowInternal=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7b871f94b33c166ef30575a247cf9c2">getNamedGlobal</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the global variable in the module with the specified name, of arbitrary type. <a href="#ab7b871f94b33c166ef30575a247cf9c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19ec326d8214646996350c9c5721102e">getNamedGlobal</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd8f7242df6ecb10f429c4d39403c334">getOrInsertGlobal</a> (StringRef Name, Type *Ty, function_ref&lt; GlobalVariable *()&gt; CreateGlobalCallback)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the specified global in the module symbol table. <a href="#abd8f7242df6ecb10f429c4d39403c334">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ec20a6f23ced1a328d4b1223fa22d96">getOrInsertGlobal</a> (StringRef Name, Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Look up the specified global in the module symbol table. <a href="#a1ec20a6f23ced1a328d4b1223fa22d96">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Global Alias Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae520fd3355e9563c528b7ff4c690ce7f">getNamedAlias</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the global alias in the module with the specified name, of arbitrary type. <a href="#ae520fd3355e9563c528b7ff4c690ce7f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Global IFunc Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8fe9473aff6bac3b9f2556407a2c86">getNamedIFunc</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the global ifunc in the module with the specified name, of arbitrary type. <a href="#a9e8fe9473aff6bac3b9f2556407a2c86">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Named Metadata Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06bb57eb1830a137e7b8f8b25908ed24">getNamedMetadata</a> (StringRef Name) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the first <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module with the specified name. <a href="#a06bb57eb1830a137e7b8f8b25908ed24">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab33e5587b25f9c80f6ea5000124d1a2b">getOrInsertNamedMetadata</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the named <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> in the module with the specified name. <a href="#ab33e5587b25f9c80f6ea5000124d1a2b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d5a31c86f52f5b535586397efa5a21">eraseNamedMetadata</a> (NamedMDNode *NMD)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove the given <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> from this module and delete it. <a href="#a46d5a31c86f52f5b535586397efa5a21">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Comdat Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab83085f68d866564c5dd63143c8cac2e">getOrInsertComdat</a> (StringRef Name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> in the module with the specified name. <a href="#ab83085f68d866564c5dd63143c8cac2e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Module Flags Accessors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add929ddb2351134fe6c351d6fd8caf6e">getModuleFlagsMetadata</a> (SmallVectorImpl&lt; ModuleFlagEntry &gt; &amp;Flags) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the module flags in the provided vector. <a href="#add929ddb2351134fe6c351d6fd8caf6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe43fb9222955bdceb316e851056f516">getModuleFlag</a> (StringRef Key) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the corresponding value if Key appears in module flags, otherwise return null. <a href="#afe43fb9222955bdceb316e851056f516">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ad813d221447b431968adf99ef7ce1">getModuleFlagsMetadata</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module that represents module-level flags. <a href="#ac6ad813d221447b431968adf99ef7ce1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a421bab6b3fc0951cfaab3b10574be5fd">getOrInsertModuleFlagsMetadata</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module that represents module-level flags. <a href="#a421bab6b3fc0951cfaab3b10574be5fd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80a42b3e2a54d45bcf647619437c6ac3">addModuleFlag</a> (ModFlagBehavior Behavior, StringRef Key, Metadata *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add a module-level flag to the module-level flags metadata. <a href="#a80a42b3e2a54d45bcf647619437c6ac3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02876ca011b3898bd050c54213f1f42f">addModuleFlag</a> (ModFlagBehavior Behavior, StringRef Key, Constant *Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58572a454a102a575543097e476b34e0">addModuleFlag</a> (ModFlagBehavior Behavior, StringRef Key, uint32_t Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afda9795063bf986d9472afdfd38947f5">addModuleFlag</a> (MDNode *Node)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6087a4906a23b4807fe6ca89b95e447e">setModuleFlag</a> (ModFlagBehavior Behavior, StringRef Key, Metadata *Val)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Like addModuleFlag but replaces the old module flag if it already exists. <a href="#a6087a4906a23b4807fe6ca89b95e447e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac16af0eab7ea5ff4233d37537cef16e0">setModuleFlag</a> (ModFlagBehavior Behavior, StringRef Key, Constant *Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f547d639d76ca60e580097b14bc8952">setModuleFlag</a> (ModFlagBehavior Behavior, StringRef Key, uint32_t Val)</td>
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

## Materialization Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a67a7e46fd17084b2ea152d2d435253">setMaterializer</a> (GVMaterializer *GVM)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sets the <a href="/web-llvm/docs/api/classes/llvm/gvmaterializer">GVMaterializer</a> to GVM. <a href="#a1a67a7e46fd17084b2ea152d2d435253">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/gvmaterializer">GVMaterializer</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4efc18e16e4bc826d1c96c833bffe3c5">getMaterializer</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Retrieves the <a href="/web-llvm/docs/api/classes/llvm/gvmaterializer">GVMaterializer</a>, if any, for this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>. <a href="#a4efc18e16e4bc826d1c96c833bffe3c5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7491e38806b98b90a690f63cb678232">isMaterialized</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f304ac10c82c01df336a728197985c1">materialize</a> (GlobalValue *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is fully read. <a href="#a1f304ac10c82c01df336a728197985c1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b0388196b68ca0fc2e187babd1a02d0">materializeAll</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Make sure all GlobalValues in this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> are fully read and clear the Materializer. <a href="#a0b0388196b68ca0fc2e187babd1a02d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/error">llvm::Error</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db6c425ae4698fdf2245b560113720b">materializeMetadata</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb5360df1b24fc7637ea22a41193674e">removeGlobalVariable</a> (GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Detach global variable <span class="doxyComputerOutput">GV</span> from the list but don't delete it. <a href="#afb5360df1b24fc7637ea22a41193674e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b8e4e706dbd7c8fadfd8593bb17979d">eraseGlobalVariable</a> (GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Remove global variable <span class="doxyComputerOutput">GV</span> from the list and delete it. <a href="#a9b8e4e706dbd7c8fadfd8593bb17979d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac75aa0b7583c039e8a9d4ccae280769">insertGlobalVariable</a> (GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert global variable <span class="doxyComputerOutput">GV</span> at the end of the global variable list and take ownership. <a href="#aac75aa0b7583c039e8a9d4ccae280769">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf41cbf5f3f2995d64e38d3d3c98d65">insertGlobalVariable</a> (GlobalListType::iterator Where, GlobalVariable *GV)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Insert global variable <span class="doxyComputerOutput">GV</span> into the global variable list before <span class="doxyComputerOutput">Where</span> and take ownership. <a href="#a6bf41cbf5f3f2995d64e38d3d3c98d65">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Global Variable Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7fbda2aeb884e5cf4b07547bd8be6e4d">global_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0567b31cf5caa26522fcc2e7cadc1dde">global_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a694ea3a50ed53ee11c1f6845f91e48f7">const_global_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a065461aba1dd9a8564d897e064c0418f">global_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7fbda2aeb884e5cf4b07547bd8be6e4d">global_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19b72cdd81bd792545e25466b43ac7c2">global_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a694ea3a50ed53ee11c1f6845f91e48f7">const_global_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a224f0cb3f8a8720f853ef21292230076">global_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e50f6ee64cb2653a50fb5c0dad6c9c">global_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a227cc1d762f784ebb21c2a2056163e20">global_empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a7fbda2aeb884e5cf4b07547bd8be6e4d">global_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c41c9882546676724cb151c9ff8723e">globals</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a694ea3a50ed53ee11c1f6845f91e48f7">const_global_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbeb92e486d706e83d7ddde18375ad13">globals</a> () const</td>
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

## Function Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7893161303eb07ae7864db6b3d004d9e">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279174d137c1ef32aa5b627f5e06620f">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae994bfe8d35ac5ab06dca56349a30856">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06b7c02a5e98060d0d56ca71fe2cf6fd">begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7893161303eb07ae7864db6b3d004d9e">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa608a2d900dd6c15c18f4236b6548496">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ae994bfe8d35ac5ab06dca56349a30856">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb6b9b90afbaa52a46e58325d94ca12d">end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abb72a16fe5f70a1fdc2a0065df39a266">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc427c11e687119cb75013d620a2f51">rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a86490fe0fd359e23da4899ea02ca640a">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a742e0736da0d59dd2bd303bbebd49f0a">rbegin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abb72a16fe5f70a1fdc2a0065df39a266">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7650724f66b289096b7fa0e949f3e0c5">rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a86490fe0fd359e23da4899ea02ca640a">const_reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8de1942d5e3a76434fe7281563d39193">rend</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8298f8e0d09cbc01af09bf2fa567dd59">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6e43cc6d546367ba5428bd4225ae80">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a7893161303eb07ae7864db6b3d004d9e">iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a446675c956107a09af38080dde388d9e">functions</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ae994bfe8d35ac5ab06dca56349a30856">const_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1245f55f582306f0241f42644275451">functions</a> () const</td>
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

## Alias Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa4be791e0744fcfa52a34c3ff9f0eaae">alias_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a755dbbd47c63c53cda3e93d9d608562a">alias_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab98e2331fe3a7ce06d273d32d69035d9">const_alias_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71edb4c45de209454f34732ee8e29d4d">alias_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aa4be791e0744fcfa52a34c3ff9f0eaae">alias_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d03597beb9097fc781a6c723cff50d6">alias_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ab98e2331fe3a7ce06d273d32d69035d9">const_alias_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5411bf6cb8994ee516b512f5a2ac7921">alias_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2130e60b0bd151d92c1eafd09dde4d91">alias_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895ac069f3bba7b395b9536c876cb2b4">alias_empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#aa4be791e0744fcfa52a34c3ff9f0eaae">alias_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a696e00bbe45dcea703f433de7b38f699">aliases</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#ab98e2331fe3a7ce06d273d32d69035d9">const_alias_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125a886cf5387bd7bc249ab43c4aecae">aliases</a> () const</td>
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

## IFunc Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a518fb2f22337cd9308ec7dbb6fe168c1">ifunc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a078bdc04f27a6002b0012692e1472a7c">ifunc_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a93358ad3206079296f6a6e057f5ba448">const_ifunc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae37fae71241018cf3acf6f73a4239b58">ifunc_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a518fb2f22337cd9308ec7dbb6fe168c1">ifunc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a620fd079c2bf4ed43399aad668ce5be5">ifunc_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a93358ad3206079296f6a6e057f5ba448">const_ifunc_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fcb9307da079106ed4f8960e36b809b">ifunc_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93b29be57202c8bc1a6ee77072de8dce">ifunc_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6d65debb5a27920461aaa21c6374a09">ifunc_empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a518fb2f22337cd9308ec7dbb6fe168c1">ifunc_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a336410508731bddd9add82863a37aaa0">ifuncs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a93358ad3206079296f6a6e057f5ba448">const_ifunc_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad032e05bf06965ec900f65ed47ec2f5f">ifuncs</a> () const</td>
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

## Named Metadata Iteration Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1faae21f2e2c6de60ffc37e3eb029a8e">named_metadata_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d052342d8cb7a6952a4c123b5385f90">named_metadata_begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3e9870d2286e1612feaf8ad1578ab80b">const_named_metadata_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40ad9ce20cb731381d062ed2cda972a6">named_metadata_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1faae21f2e2c6de60ffc37e3eb029a8e">named_metadata_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52eefaf4892829072b70e0e2e3d88bf">named_metadata_end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3e9870d2286e1612feaf8ad1578ab80b">const_named_metadata_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f2efb3a0e5809e56f54796680bc77b7">named_metadata_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab156619982240ea1c73ac9dd22a1b840">named_metadata_size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36bf9b28e4b81b5690089bb26bc4de03">named_metadata_empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a1faae21f2e2c6de60ffc37e3eb029a8e">named_metadata_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57e28660be46fe2befd3f5f04825fd00">named_metadata</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="#a3e9870d2286e1612feaf8ad1578ab80b">const_named_metadata_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9246bed13b395965d1afc1c24ec4ea74">named_metadata</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module/debug-compile-units-iterator">debug_compile_units_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af51e2d4d20061325bd7496adb08bd392">debug_compile_units_begin</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module/debug-compile-units-iterator">debug_compile_units_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff491d52bf87eb3f70bcc4fcbdc71181">debug_compile_units_end</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/iterator-range">iterator_range</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/module/debug-compile-units-iterator">debug_compile_units_iterator</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a429ef9bbd0adc89bc6f810d7798f086b">debug_compile_units</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return an iterator for all DICompileUnits listed in this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s llvm.dbg.cu named metadata node and aren't explicitly marked as NoDebug. <a href="#a429ef9bbd0adc89bc6f810d7798f086b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility functions for printing and dumping Module objects Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee5166cba8576e41617fc96aec1fb85">print</a> (raw_ostream &amp;OS, AssemblyAnnotationWriter *AAW, bool ShouldPreserveUseListOrder=false, bool IsForDebug=false) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Print the module to an output stream with an optional <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a>. <a href="#a8ee5166cba8576e41617fc96aec1fb85">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b4c67a0936fe59c9511ff591b97f260">dump</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Dump the module to stderr (for debugging). <a href="#a9b4c67a0936fe59c9511ff591b97f260">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61b1317d05efe05a549bf94bc949e0d0">dropAllReferences</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function causes all the subinstructions to "let go" of all references that they are maintaining. <a href="#a61b1317d05efe05a549bf94bc949e0d0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility functions for querying Debug information. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b5097cd5df342da24466f39ffd5ecae">getNumberRegisterParameters</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Number of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ParametersDwarf Version by checking module flags. <a href="#a9b5097cd5df342da24466f39ffd5ecae">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa5fa42829b640beda25bd5e16f7eb830">getDwarfVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the Dwarf Version by checking module flags. <a href="#aa5fa42829b640beda25bd5e16f7eb830">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa89510c798cef7265b248241964c16f0">isDwarf64</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the DWARF format by checking module flags. <a href="#aa89510c798cef7265b248241964c16f0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7133d921c103967178f1388c8f273da3">getCodeViewFlag</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the CodeView Version by checking module flags. <a href="#a7133d921c103967178f1388c8f273da3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility functions for querying and setting PIC level Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6b">PICLevel::Level</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a892dfcabd163bf60c4916e5456afedb1">getPICLevel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the PIC level (small or large model) <a href="#a892dfcabd163bf60c4916e5456afedb1">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f04f1a6786a147aa95a967478f9cbd">setPICLevel</a> (PICLevel::Level PL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the PIC level (small or large model) <a href="#a98f04f1a6786a147aa95a967478f9cbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility functions for querying and setting PIE level Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/pielevel/#ae01fe422624f3a5afd84d14146f9112c">PIELevel::Level</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3295ffffcff40d7c95aa9fb4d13256a">getPIELevel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the PIE level (small or large model) <a href="#af3295ffffcff40d7c95aa9fb4d13256a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1f343c75351052dcbb1ee866cd18347">setPIELevel</a> (PIELevel::Level PL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the PIE level (small or large model) <a href="#ae1f343c75351052dcbb1ee866cd18347">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility function for querying and setting code model Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5b21bb0de463009ae5702aa73a83657">getCodeModel</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the code model (tiny, small, kernel, medium or large model) <a href="#ac5b21bb0de463009ae5702aa73a83657">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25f29d00aa5f0cb6f79645a6225a043e">setCodeModel</a> (CodeModel::Model CL)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the code model (tiny, small, kernel, medium or large) <a href="#a25f29d00aa5f0cb6f79645a6225a043e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility function for querying and setting the large data threshold Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a565dd703d30bab94924184733ec7bf84">getLargeDataThreshold</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the code model (tiny, small, kernel, medium or large model) <a href="#a565dd703d30bab94924184733ec7bf84">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa72b06563b1a998b7e291d78eeb131d9">setLargeDataThreshold</a> (uint64_t Threshold)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set the code model (tiny, small, kernel, medium or large) <a href="#aa72b06563b1a998b7e291d78eeb131d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility functions for querying and setting PGO summary Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bf85925c8356b5aecf975112632e37a">setProfileSummary</a> (Metadata *M, ProfileSummary::Kind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attach profile summary metadata to this module. <a href="#a6bf85925c8356b5aecf975112632e37a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcbde5203650f49a414283674b9792fb">getProfileSummary</a> (bool IsCS) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns profile summary metadata. <a href="#afcbde5203650f49a414283674b9792fb">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Utility functions for querying and setting the build SDK version Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9b60984528010b0f885be0b81aa3296">setSDKVersion</a> (const VersionTuple &amp;V)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Attach a build SDK version metadata to this module. <a href="#af9b60984528010b0f885be0b81aa3296">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae31b39ce1f886a3280a0297dcfb66930">getSDKVersion</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the build SDK version metadata. <a href="#ae31b39ce1f886a3280a0297dcfb66930">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>A <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> instance is used to store all the information related to an LLVM module.</p>


<p>Modules are the top level container of all other LLVM Intermediate Representation (IR) objects. Each module directly contains a list of globals variables, a list of functions, a list of libraries (or other modules) this module depends on, a symbol table, and various data about the target's characteristics.</p>


<p>A module maintains a GlobalList object that is used to hold all constant references to global variables in the module. When a global variable is destroyed, it should have no entries in the GlobalList. The main container class for the LLVM Intermediate Representation.</p>


<p>Definition at line 65 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### dropTriviallyDeadConstantArrays() {#a288bf7fe3df7b3822b5763009cc81366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::dropTriviallyDeadConstantArrays ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Destroy ConstantArrays in <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> if they are not used.</p>


<p>ConstantArrays constructed during linking can cause quadratic memory explosion. Releasing all unused constants can cause a 20% LTO compile-time slowdown for a large application.</p>


<p>NOTE: Constants are currently owned by <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>. This can then only be called where all uses of the <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> are understood.</p>


<p>Declaration at line 885 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 173 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a>.</p>

</div>
</div>

### getDarwinTargetVariantSDKVersion() {#acbcfb512d2c49571267a607e14c7f385}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Module::getDarwinTargetVariantSDKVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the target variant version build SDK version metadata.</p>


<p>An empty version is returned if no such metadata is attached.</p>


<p>Declaration at line 1064 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 911 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getDarwinTargetVariantTriple() {#af6847095f6ef27e76a1336d827f45a78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Module::getDarwinTargetVariantTriple ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the target variant triple which is a string describing a variant of the target host platform.</p>


<p>For example, Mac Catalyst can be a variant target triple for a macOS target.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a string containing the target variant triple.</p></dd>
</dl>


<p>Declaration at line 1055 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 900 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getDirectAccessExternalData() {#afc2aac3b278b44b702ccbcce7284cdf2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Module::getDirectAccessExternalData ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set whether referencing global variables can use direct access relocations on <a href="/web-llvm/docs/api/namespaces/llvm/elf">ELF</a> targets.</p>

<p>Declaration at line 996 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 721 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getFramePointer() {#a7e6e68937a2bd1ea02a5df34f3763482}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FramePointerKind Module::getFramePointer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set whether synthesized functions should get the "frame-pointer" attribute.</p>

<p>Declaration at line 1005 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getMaxTLSAlignment() {#a142c912d8ab5e38df3b8742daea8e06c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getMaxTLSAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1030 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 807 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getOverrideStackAlignment() {#a7eb37b956b67f6a06895a1cdfa8cfd28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getOverrideStackAlignment ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set the stack alignment overridden from the default.</p>

<p>Declaration at line 1027 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 800 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getRtLibUseGOT() {#a5e2cbb95a96b08de2941c0531bd754e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Module::getRtLibUseGOT ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if PLT should be avoided for RTLib calls.</p>

<p>Declaration at line 989 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 712 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getSemanticInterposition() {#a344446b3349dc1d73464b3bb5ae0e6bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Module::getSemanticInterposition ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns whether semantic interposition is to be respected.</p>

<p>Declaration at line 983 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 694 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa1558e13ceef68db8ea9f4e3b5a64cbd">llvm::GlobalValue::isInterposable</a>.</p>

</div>
</div>

### getStackProtectorGuard() {#a5c95a95f585b6eae4a606ff335a3a50a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Module::getStackProtectorGuard ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set what kind of stack protector guard to use.</p>

<p>Declaration at line 1009 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 753 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getStackProtectorGuardOffset() {#afbea21913d36e4bb861d22a05ea081ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int Module::getStackProtectorGuardOffset ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set what offset from the stack protector to use.</p>

<p>Declaration at line 1023 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 789 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getStackProtectorGuardReg() {#aa484c371d7b1dcdabcc96ad78c38b62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Module::getStackProtectorGuardReg ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set which register to use as the stack protector guard register.</p>


<p>The empty string is equivalent to "global". Other values may be "tls" or "sysreg".</p>


<p>Declaration at line 1015 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 765 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getStackProtectorGuardSymbol() {#a2cd573d063de53b69ba0bd441c52c382}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef Module::getStackProtectorGuardSymbol ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set a symbol to use as the stack protector guard.</p>

<p>Declaration at line 1019 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 777 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getUwtable() {#a6113fb21d027efcf333cbe204b2e2633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UWTableKind Module::getUwtable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get/set whether synthesized functions should get the uwtable attribute.</p>

<p>Declaration at line 1000 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 733 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setDarwinTargetVariantSDKVersion() {#af036e8aea57e28daa0a63afb9c764b66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setDarwinTargetVariantSDKVersion (<a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> Version)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the target variant version build SDK version metadata.</p>

<p>Declaration at line 1067 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 915 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setDarwinTargetVariantTriple() {#a94bbecbd83ac11d59a0653ea5d4fbf8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setDarwinTargetVariantTriple (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the target variant triple which is a string describing a variant of the target host platform.</p>

<p>Declaration at line 1059 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 906 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setDirectAccessExternalData() {#a1202793bde8d50983a5814cb8b1fb5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setDirectAccessExternalData (bool Value)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 997 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setFramePointer() {#a55241d651101cf9629b2a7d822904eee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setFramePointer (<a href="/web-llvm/docs/api/namespaces/llvm/#a0c7a337870929cbf2d49865f77c42927">FramePointerKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1006 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 749 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setOverrideStackAlignment() {#a10a4208cd36d651811e339ddf0900d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setOverrideStackAlignment (unsigned Align)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1028 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 814 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setOwnedMemoryBuffer() {#a16d6ddd53501159a453ac63113851b9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setOwnedMemoryBuffer (std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/memorybuffer">MemoryBuffer</a> &gt; MB)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Take ownership of the given memory buffer.</p>

<p>Declaration at line 1045 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 708 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setPartialSampleProfileRatio() {#a71dec001bcc3e5e68e0970e528bae35e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setPartialSampleProfileRatio (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> &amp; Index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the partial sample profile ratio in the profile summary module flag, if applicable.</p>

<p>Declaration at line 1049 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 880 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setRtLibUseGOT() {#a3bf200dbe6f728c2eb068e5b87c93024}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setRtLibUseGOT ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set that PLT should be avoid for RTLib calls.</p>

<p>Declaration at line 992 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 717 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setSemanticInterposition() {#a05a7684b2043eab9432d655cb4edc0c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setSemanticInterposition (bool SI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set whether semantic interposition is to be respected.</p>

<p>Declaration at line 986 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 704 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setStackProtectorGuard() {#a64d1cac4963d3f640df8967a5caddf60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setStackProtectorGuard (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1010 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 760 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setStackProtectorGuardOffset() {#aaf70f65e0b09aba4026bbe0009751d25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setStackProtectorGuardOffset (int Offset)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1024 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 796 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setStackProtectorGuardReg() {#a889574485e1bda76d4c2e2cfece65690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setStackProtectorGuardReg (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Reg)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1016 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 772 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setStackProtectorGuardSymbol() {#a04001950ccace6c01bfb634d3a055e3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setStackProtectorGuardSymbol (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1020 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 784 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setUwtable() {#a7033a69af274cff3526d34222279863e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setUwtable (<a href="/web-llvm/docs/api/namespaces/llvm/#a6cdf47ba1fa5831d7c2897bc3aed77b8">UWTableKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1001 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Types And Enumerations

### alias\_iterator {#aa4be791e0744fcfa52a34c3ff9f0eaae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::alias_iterator =  AliasListType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Global Alias iterators.</p>

<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### AliasListType {#ad4736363638b8f744ae635ffda5b5b6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::AliasListType =  SymbolTableList&lt;GlobalAlias&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for the list of aliases.</p>

<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ComdatSymTabType {#a0436d9008c05925a6e20381a1f728189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::ComdatSymTabType =  StringMap&lt;Comdat&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type of the comdat "symbol" table.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### const\_alias\_iterator {#ab98e2331fe3a7ce06d273d32d69035d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_alias_iterator =  AliasListType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Global Alias constant iterator.</p>

<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### const\_global\_iterator {#a694ea3a50ed53ee11c1f6845f91e48f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_global_iterator =  GlobalListType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Global Variable constant iterator.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### const\_ifunc\_iterator {#a93358ad3206079296f6a6e057f5ba448}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_ifunc_iterator =  IFuncListType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Global IFunc constant iterator.</p>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### const\_iterator {#ae994bfe8d35ac5ab06dca56349a30856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_iterator =  FunctionListType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> constant iterator.</p>

<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### const\_named\_metadata\_iterator {#a3e9870d2286e1612feaf8ad1578ab80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_named_metadata_iterator =  NamedMDListType::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The named metadata constant iterators.</p>

<p>Definition at line 112 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### const\_reverse\_iterator {#a86490fe0fd359e23da4899ea02ca640a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_reverse_iterator =  FunctionListType::const_reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> constant reverse iterator.</p>

<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### FunctionListType {#a391a6ee45603f6d05cb045d89e79f344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::FunctionListType =  SymbolTableList&lt;Function&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for the list of functions.</p>

<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### global\_iterator {#a7fbda2aeb884e5cf4b07547bd8be6e4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::global_iterator =  GlobalListType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Global Variable iterator.</p>

<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### GlobalListType {#a949869855fcd2290a285a90b2c353f1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::GlobalListType =  SymbolTableList&lt;GlobalVariable&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for the list of global variables.</p>

<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ifunc\_iterator {#a518fb2f22337cd9308ec7dbb6fe168c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::ifunc_iterator =  IFuncListType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Global IFunc iterators.</p>

<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### IFuncListType {#adf18e123231905a06aba1ff2102ab1dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::IFuncListType =  SymbolTableList&lt;GlobalIFunc&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for the list of ifuncs.</p>

<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### isValidModFlagBehavior {#aaa09a52095810697305805737b3a0920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Module::isValidModFlagBehavior (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * MD, <a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a> &amp; MFB)</td>
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

<p>Checks if <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> represents a valid <a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a>, and stores the converted result in MFB.</p>

<p>Declaration at line 159 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### iterator {#a7893161303eb07ae7864db6b3d004d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::iterator =  FunctionListType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> iterators.</p>

<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ModFlagBehavior {#a0a5c55e12c97b80021330fe82b642293}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Module::ModFlagBehavior </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This enumeration defines the supported behaviors of module flags.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Error<a id="a0a5c55e12c97b80021330fe82b642293a4771bacd44b97e736b819b5d06b22dfe"></a></td>
<td class="doxyEnumItemDescription">Emits an error if two values disagree, otherwise the resulting value is that of the operands (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Warning<a id="a0a5c55e12c97b80021330fe82b642293a355bc901e05417401ee44323a8595131"></a></td>
<td class="doxyEnumItemDescription">Emits a warning if two values disagree (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Require<a id="a0a5c55e12c97b80021330fe82b642293aec0586c2f89c73dcc00841aa000141bb"></a></td>
<td class="doxyEnumItemDescription">Adds a requirement that another module flag be present and have a specified value after linking is performed (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Override<a id="a0a5c55e12c97b80021330fe82b642293a2aba8031539d1446aff14d13c7deea69"></a></td>
<td class="doxyEnumItemDescription">Uses the specified value, regardless of the behavior or value of the other module (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Append<a id="a0a5c55e12c97b80021330fe82b642293a7a6b9b7ed3797ab927caf581353e935a"></a></td>
<td class="doxyEnumItemDescription">Appends the two values, which are required to be metadata nodes (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AppendUnique<a id="a0a5c55e12c97b80021330fe82b642293a2486ec4ce4f33e42da3ad60d6e9eff4a"></a></td>
<td class="doxyEnumItemDescription">Appends the two values, which are required to be metadata nodes (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Max<a id="a0a5c55e12c97b80021330fe82b642293a89821032d3b24b6a135f1d5acfbcd2c8"></a></td>
<td class="doxyEnumItemDescription">Takes the max of the two values, which are required to be integers (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Min<a id="a0a5c55e12c97b80021330fe82b642293a74e5a703504f88f6b34e9f31e8ae5160"></a></td>
<td class="doxyEnumItemDescription">Takes the min of the two values, which are required to be integers (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModFlagBehaviorFirstVal<a id="a0a5c55e12c97b80021330fe82b642293a59bf24a6d7675e80c400f121f5b743b8"></a></td>
<td class="doxyEnumItemDescription"> (= Error)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ModFlagBehaviorLastVal<a id="a0a5c55e12c97b80021330fe82b642293ae2c6e1fe630700ebf839c90b6c04627e"></a></td>
<td class="doxyEnumItemDescription"> (= Min)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### named\_metadata\_iterator {#a1faae21f2e2c6de60ffc37e3eb029a8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::named_metadata_iterator =  NamedMDListType::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The named metadata iterators.</p>

<p>Definition at line 110 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### NamedMDListType {#a382815cf826755c2a1c0269c7bb70a05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::NamedMDListType =  ilist&lt;NamedMDNode&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for the list of named metadata.</p>

<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### NamedMDSymTabType {#a7d2c30531f5c9d1872fdc84db1ecfb06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::NamedMDSymTabType =  StringMap&lt;NamedMDNode *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The type for mapping names to named metadata.</p>

<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### reverse\_iterator {#abb72a16fe5f70a1fdc2a0065df39a266}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::reverse_iterator =  FunctionListType::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> reverse iterator.</p>

<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Convenience iterators

### const\_global\_object\_iterator {#ae619f2a56af4f4e067b672c8f3dcdcd4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_global_object_iterator = 
      concat_iterator&lt;const GlobalObject, const_iterator,
                      const_global_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### const\_global\_value\_iterator {#aea433ad125d2359ae11e4c22532f04c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::const_global_value_iterator = 
      concat_iterator&lt;const GlobalValue, const_iterator, const_global_iterator,
                      const_alias_iterator, const_ifunc_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### global\_object\_iterator {#a9300d9104835e2925907f8541da1d187}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::global_object_iterator = 
      concat_iterator&lt;GlobalObject, iterator, global_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### global\_objects {#ab16c33bc70855b5305e19505f6dfd8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; Module::global_object_iterator &gt; Module::global_objects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 777 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 442 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### global\_objects {#ada4ee7ed330e79fed89afc626f13644c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; Module::const_global_object_iterator &gt; Module::global_objects ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 446 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### global\_value\_iterator {#ac6931ca58bf137002cb2affb21594172}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using llvm::Module::global_value_iterator = 
      concat_iterator&lt;GlobalValue, iterator, global_iterator, alias_iterator,
                      ifunc_iterator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### global\_values {#afb3c7bb41e87372e57ea465c2196b30b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; Module::global_value_iterator &gt; Module::global_values ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 450 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>.</p>

</div>
</div>

### global\_values {#aa60e6a71a1605f3af1fa5261bc1556a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; Module::const_global_value_iterator &gt; Module::global_values ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 454 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Member Variables

### AliasList {#abc64f6251b296b5119ea0c6913008f8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasListType llvm::Module::AliasList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Aliases in the module.</p>

<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ComdatSymTab {#af55028d8fa75d0a295e6c6e12b01538c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComdatSymTabType llvm::Module::ComdatSymTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Symbol table for COMDATs.</p>

<p>Definition at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

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


<p>Definition at line 208 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>.</p>


<p>Referenced by <a href="#a5bd16c2fbe755cda66b18d56761038ea">Constant</a>.</p>

</div>
</div>

### Context {#a94a6309d0b887eceade042a774361d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext&amp; llvm::Module::Context</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> from which types and constants are allocated.</p>

<p>Definition at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### CurrentIntrinsicIds {#a601fcff9cc3c2a5a79bbca011165b167}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringMap&lt;unsigned&gt; llvm::Module::CurrentIntrinsicIds</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of the current unique id count for the specified intrinsic basename.</p>

<p>Definition at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### DL {#aa7f72a7f2947a0cdd39feb0a4c30618c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DataLayout llvm::Module::DL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> associated with the module.</p>

<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### FunctionList {#a8b179a9e32b24ab570e22ae292a30389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionListType llvm::Module::FunctionList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Functions in the module.</p>

<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### GlobalList {#a3a2679f249b3d55dc6d388fb26168324}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalListType llvm::Module::GlobalList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The Global Variables in the module.</p>

<p>Definition at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### GlobalScopeAsm {#a6f7fc085d1258fd8b3e2129c7eba820d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Module::GlobalScopeAsm</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Inline Asm at global scope.</p>

<p>Definition at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### IFuncList {#adf2f870fffbcc7ee53bc740073c377c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IFuncListType llvm::Module::IFuncList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The IFuncs in the module.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### Materializer {#a5341b0659a9e945e58bd2cf2cf24b188}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;GVMaterializer&gt; llvm::Module::Materializer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used to materialize GlobalValues.</p>

<p>Definition at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ModuleFlags {#a5902a8436605a3de99202f879f259450}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode* llvm::Module::ModuleFlags = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>llvm.module.flags metadata</p>

<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ModuleID {#ab0a98092f6df3048471324f7ff6da14c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Module::ModuleID</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Human readable identifier for the module.</p>

<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### NamedMDList {#aa73858edc074cdbf65114fe3288e1ba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDListType llvm::Module::NamedMDList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The named metadata in the module.</p>

<p>Definition at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### NamedMDSymTab {#a5b992bd2655be6f6647c8b5a37b5a131}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDSymTabType llvm::Module::NamedMDSymTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> names.</p>

<p>Definition at line 194 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### OwnedMemoryBuffer {#a6313291b380d37b0a033ddd7b28bf926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MemoryBuffer&gt; llvm::Module::OwnedMemoryBuffer</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/sys/memory">Memory</a> buffer directly owned by this module, for legacy clients only.</p>

<p>Definition at line 185 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### SourceFileName {#a7740900a7ccfc5f7282ae665a1eecc65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Module::SourceFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Original source file name for module, recorded in bitcode.</p>

<p>Definition at line 190 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### TargetTriple {#a359beca1e7ecb854b74619c1f2e206e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::Module::TargetTriple</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Platform target triple <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> compiled on Format: (arch)(sub)-(vendor)-(sys0-(abi)</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### UniquedIntrinsicNames {#a73143559e72a9f148579f585081c9638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenseMap&lt;std::pair&lt;Intrinsic::ID, const FunctionType *&gt;, unsigned&gt; llvm::Module::UniquedIntrinsicNames</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Keep track of uniqued names of intrinsics based on unnamed types.</p>


<p>The combination of <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> and <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> maps to the extension that is used to make the intrinsic name unique.</p>


<p>Definition at line 200 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ValSymTab {#a6a1439efc2b9ea3d386ba47501c542e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;ValueSymbolTable&gt; llvm::Module::ValSymTab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Symbol table for values.</p>

<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Direct access to the globals list, functions list, and symbol table

### eraseAlias {#a9a2bb9b6dfce993d3eddec7345684f42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::eraseAlias (<a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * Alias)</td>
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

<p>Remove <span class="doxyComputerOutput">Alias</span> from the list and delete it.</p>

<p>Definition at line 624 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a09b07d472515f1d307c0e8229f6856fb">llvm::GlobalAlias::eraseFromParent</a>.</p>

</div>
</div>

### eraseIFunc {#a7d152ee09578b75228f1412cc7fdc3c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::eraseIFunc (<a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> * IFunc)</td>
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

<p>Remove <span class="doxyComputerOutput">IFunc</span> from the list and delete it.</p>

<p>Definition at line 633 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#abd9f847c1058c8574d0c995f6c425fe8">llvm::GlobalIFunc::eraseFromParent</a>.</p>

</div>
</div>

### eraseNamedMDNode {#a084ca29ed6871e115ae1434ac3f3a067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::eraseNamedMDNode (<a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> * MDNode)</td>
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

<p>Remove <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></span> from the list and delete it.</p>

<p>Definition at line 642 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getAliasList {#a89edfbc5688238bdb58733514db1aa6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const AliasListType &amp; llvm::Module::getAliasList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of aliases (constant).</p>

<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getAliasList {#a65887d40ddec20928f0d304054f47c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasListType &amp; llvm::Module::getAliasList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of aliases.</p>

<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getComdatSymbolTable {#a1759adeccb706c96a44484dd01bdf0de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ComdatSymTabType &amp; llvm::Module::getComdatSymbolTable ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s symbol table for COMDATs (constant).</p>

<p>Definition at line 687 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a>.</p>

</div>
</div>

### getComdatSymbolTable {#abb586ee29080a81aacea8d66e5d03498}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ComdatSymTabType &amp; llvm::Module::getComdatSymbolTable ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s symbol table for COMDATs.</p>

<p>Definition at line 689 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getFunctionList {#a8cbf634a57382636ca0dbbcf779655ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FunctionListType &amp; llvm::Module::getFunctionList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of functions (constant).</p>

<p>Definition at line 614 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> and <a href="#a8cbf634a57382636ca0dbbcf779655ae">getFunctionList</a>.</p>


<p>Referenced by <a href="#a8cbf634a57382636ca0dbbcf779655ae">getFunctionList</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulowerbufferfatpointers-cpp/#a0c78bf7a0e55e7396a9e8ec7acf2dca5">moveFunctionAdaptingType</a>.</p>

</div>
</div>

### getFunctionList {#a97db845caa6bba2a5ff3ffb8a2b8c23f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionListType &amp; llvm::Module::getFunctionList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of functions.</p>

<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getGlobalList {#a522163a84424964528f409adac032803}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalListType &amp; llvm::Module::getGlobalList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of global variables (constant).</p>

<p>Definition at line 603 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getGlobalList {#a6def4f53e01fcce273158a5bfa36c1f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalListType &amp; llvm::Module::getGlobalList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of global variables.</p>

<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getIFuncList {#a63020ec8de2922109a61bc527504df12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const IFuncListType &amp; llvm::Module::getIFuncList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of ifuncs (constant).</p>

<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getIFuncList {#a364647adc4e8b845cf4ed6d05b9c7e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IFuncListType &amp; llvm::Module::getIFuncList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of ifuncs.</p>

<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getNamedMDList {#aa720aeae675bb283c324343ffdcf657f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const NamedMDListType &amp; llvm::Module::getNamedMDList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of named metadata (constant).</p>

<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getNamedMDList {#aba96540297e2812360f71dd0a79881c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDListType &amp; llvm::Module::getNamedMDList ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s list of named metadata.</p>

<p>Definition at line 674 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getSublistAccess {#ae6af060631f47797b9ed01593c0853af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionListType Module::* llvm::Module::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)</td>
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



<p>Definition at line 617 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a378f93ece2ac999e500f07056cfe6528">Module</a>.</p>

</div>
</div>

### getSublistAccess {#adf4c694e6136afbc96245d473bf0bd2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalListType Module::* llvm::Module::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *)</td>
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



<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getSublistAccess {#ad15884cc92ca5611ca4b1f2bdd37d218}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AliasListType Module::* llvm::Module::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> *)</td>
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



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getSublistAccess {#a3e4299950620b3a5aba752c10c8eb345}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IFuncListType Module::* llvm::Module::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> *)</td>
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



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getSublistAccess {#a2aa9774bbb39354bbccc67ad3af32d35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDListType Module::* llvm::Module::getSublistAccess (<a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> *)</td>
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



<p>Definition at line 676 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getValueSymbolTable {#aaec6166c9567e64030e08640eec2511a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ValueSymbolTable &amp; llvm::Module::getValueSymbolTable ()</td>
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

<p>Get the symbol table of global variable and function identifiers.</p>

<p>Definition at line 682 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getValueSymbolTable {#a3d58d8c32a9a4787ecc667f8495ddbc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueSymbolTable &amp; llvm::Module::getValueSymbolTable ()</td>
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

<p>Get the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s symbol table of global variable and function identifiers.</p>

<p>Definition at line 684 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### insertAlias {#aef81cefbdf9af4e321646419b65fcbd9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::insertAlias (<a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * Alias)</td>
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

<p>Insert <span class="doxyComputerOutput">Alias</span> at the end of the alias list and take ownership.</p>

<p>Definition at line 626 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### insertIFunc {#a0f75403ce44801b257e42ef58f5c9a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::insertIFunc (<a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> * IFunc)</td>
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

<p>Insert <span class="doxyComputerOutput">IFunc</span> at the end of the alias list and take ownership.</p>

<p>Definition at line 635 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### insertNamedMDNode {#a9daea70b0389c14792d8406d422491a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::insertNamedMDNode (<a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> * MDNode)</td>
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

<p>Insert <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></span> at the end of the alias list and take ownership.</p>

<p>Definition at line 644 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### llvm::SymbolTableListTraits&lt; llvm::GlobalAlias &gt; {#ac233817c65ce7ee15cec581b62fe0ec5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">llvm::SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalalias">llvm::GlobalAlias</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a378f93ece2ac999e500f07056cfe6528">Module</a>.</p>

</div>
</div>

### llvm::SymbolTableListTraits&lt; llvm::GlobalIFunc &gt; {#a2fc1172cc3dd5889fdf379ed6dec8b81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">llvm::SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalifunc">llvm::GlobalIFunc</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a378f93ece2ac999e500f07056cfe6528">Module</a>.</p>

</div>
</div>

### llvm::SymbolTableListTraits&lt; llvm::GlobalVariable &gt; {#ad87cca93b972c266e973d1a0996afd00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-llvm/docs/api/classes/llvm/symboltablelisttraits">llvm::SymbolTableListTraits</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">llvm::GlobalVariable</a> &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 607 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a378f93ece2ac999e500f07056cfe6528">Module</a>.</p>

</div>
</div>

### removeAlias {#a5724c4a6f094c94f6652a4a6c5d59f93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::removeAlias (<a href="/web-llvm/docs/api/classes/llvm/globalalias">GlobalAlias</a> * Alias)</td>
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

<p>Detach <span class="doxyComputerOutput">Alias</span> from the list but don't delete it.</p>

<p>Definition at line 622 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalalias/#aa4afd53102b414c23761c32f33b6cd08">llvm::GlobalAlias::removeFromParent</a>.</p>

</div>
</div>

### removeIFunc {#a0638c1703df1253b2737c50d5f59b5a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::removeIFunc (<a href="/web-llvm/docs/api/classes/llvm/globalifunc">GlobalIFunc</a> * IFunc)</td>
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

<p>Detach <span class="doxyComputerOutput">IFunc</span> from the list but don't delete it.</p>

<p>Definition at line 631 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalifunc/#a5892574848285e3ff045d123520a165a">llvm::GlobalIFunc::removeFromParent</a>.</p>

</div>
</div>

### removeNamedMDNode {#aa0ba8b6f2a4dc44633963071c6518495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::removeNamedMDNode (<a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> * MDNode)</td>
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

<p>Detach <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a></span> from the list but don't delete it.</p>

<p>Definition at line 640 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Constructors

### \~Module {#a7c9d9c096786d127590fdd8aa2b7d681}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module::~Module ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The module destructor. This will dropAllReferences.</p>

<p>Declaration at line 257 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### convertFromNewDbgValues {#a32a0c54875b7841d0222b427f0792671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::convertFromNewDbgValues ()</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a5753230c9e297fed32356ebf071074f0">BasicBlock::convertFromNewDbgValues</a>.</p></dd>
</dl>


<p>Definition at line 233 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a1901c01c9f1724db542f99882fb6ca48">IsNewDbgInfoFormat</a>.</p>


<p>Referenced by <a href="#ac2fdf89ed4d5971a35c36c849956b321">setIsNewDbgInfoFormat</a>.</p>

</div>
</div>

### convertToNewDbgValues {#a2cc4ac48c0468db2a9c3cda662dddb4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::convertToNewDbgValues ()</td>
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




<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/basicblock/#a3ead08d4d049585ee09421bcebd2ae25">BasicBlock::convertToNewDbgValues</a>.</p></dd>
</dl>


<p>Definition at line 225 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a1901c01c9f1724db542f99882fb6ca48">IsNewDbgInfoFormat</a>.</p>


<p>Referenced by <a href="#ac2fdf89ed4d5971a35c36c849956b321">setIsNewDbgInfoFormat</a>.</p>

</div>
</div>

### IsNewDbgInfoFormat {#a1901c01c9f1724db542f99882fb6ca48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::IsNewDbgInfoFormat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Is this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> using intrinsics to record the position of debugging information, or non-intrinsic records?</p>


<p>See IsNewDbgInfoFormat in <a href="/web-llvm/docs/api/classes/llvm/basicblock">BasicBlock</a>.</p>


<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a32a0c54875b7841d0222b427f0792671">convertFromNewDbgValues</a>, <a href="#a2cc4ac48c0468db2a9c3cda662dddb4a">convertToNewDbgValues</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a1b8715812b9f4dd2bd46163dd1b51128">llvm::FastISel::fastEmitBranch</a>, <a href="#ac2fdf89ed4d5971a35c36c849956b321">setIsNewDbgInfoFormat</a>, <a href="#a82f2e848e67d05f11845c5d49fccee3e">setNewDbgInfoFormatFlag</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a085e92ed481e12744fdf1740b4751327">llvm::UpgradeIntrinsicCall</a>.</p>

</div>
</div>

### Module {#a378f93ece2ac999e500f07056cfe6528}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module::Module (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ModuleID, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C)</td>
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

<p>The <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> constructor.</p>


<p>Note that there is no default constructor. You must provide a name for the module upon construction.</p>


<p>Declaration at line 255 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 73 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="#a7c3df989919f622a0bdc2649a0876263">getGlobalVariable</a>, <a href="#a19ec326d8214646996350c9c5721102e">getNamedGlobal</a>, <a href="#ae6af060631f47797b9ed01593c0853af">getSublistAccess</a>, <a href="#ac233817c65ce7ee15cec581b62fe0ec5">llvm::SymbolTableListTraits&lt; llvm::GlobalAlias &gt;</a>, <a href="#a2fc1172cc3dd5889fdf379ed6dec8b81">llvm::SymbolTableListTraits&lt; llvm::GlobalIFunc &gt;</a> and <a href="#ad87cca93b972c266e973d1a0996afd00">llvm::SymbolTableListTraits&lt; llvm::GlobalVariable &gt;</a>.</p>

</div>
</div>

### operator= {#a78b9c4843c02991e755fd58d2acf064e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module &amp; Module::operator= (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;&amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Move assignment.</p>

<p>Declaration at line 260 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### removeDebugIntrinsicDeclarations {#a3b87b2e44ce9a2a303c79088f047082e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::removeDebugIntrinsicDeclarations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Used when printing this module in the new debug info format; removes all declarations of debug intrinsics that are replaced by non-intrinsic records in the new format.</p>

<p>Declaration at line 222 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 124 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setIsNewDbgInfoFormat {#ac2fdf89ed4d5971a35c36c849956b321}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::setIsNewDbgInfoFormat (bool UseNewFormat)</td>
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



<p>Definition at line 240 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a32a0c54875b7841d0222b427f0792671">convertFromNewDbgValues</a>, <a href="#a2cc4ac48c0468db2a9c3cda662dddb4a">convertToNewDbgValues</a> and <a href="#a1901c01c9f1724db542f99882fb6ca48">IsNewDbgInfoFormat</a>.</p>

</div>
</div>

### setNewDbgInfoFormatFlag {#a82f2e848e67d05f11845c5d49fccee3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::setNewDbgInfoFormatFlag (bool NewFlag)</td>
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



<p>Definition at line 246 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#a1901c01c9f1724db542f99882fb6ca48">IsNewDbgInfoFormat</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Module Level Accessors

### createRNG {#a8b82325a22b25d4278a37af30b202a30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; RandomNumberGenerator &gt; Module::createRNG (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get a <a href="/web-llvm/docs/api/classes/llvm/randomnumbergenerator">RandomNumberGenerator</a> salted for use with this module.</p>


<p>The RNG can be seeded via -rng-seed=&lt;uint64&gt; and is salted with the ModuleID and the provided pass salt. The returned RNG should not be shared across threads or passes.</p>


<p>A unique RNG per pass ensures a reproducible random stream even when other randomness consuming passes are added or removed. In addition, the random stream will be reproducible across LLVM versions when the pass does not change.</p>


<p>Declaration at line 317 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getContext {#a0beddb53641a541e2238617c5fac4be7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LLVMContext &amp; llvm::Module::getContext ()</td>
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

<p>Get the global data context.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> - a container for LLVM's global information</p></dd>
</dl>


<p>Definition at line 302 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/amdgputargetlowering/#a13c4414eff134cca785b7f6e50dec7cb">llvm::AMDGPUTargetLowering::analyzeFormalArgumentsCompute</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a0386198cbc9986aa5b45f21b24b0902d">crossImportIntoModule</a>, <a href="/web-llvm/docs/api/classes/llvm/webassemblyasmprinter/#a0202522d1384c2ad88417c496ae62068">llvm::WebAssemblyAsmPrinter::emitGlobalVariable</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#ae1b1fc686e5285c37b8f51cab4d213f0">optimizeModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abf2c472d771169c6100c6302079309da">llvm::parseConstantValue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a693d5398216b0ca25097c2bde8fe6284">llvm::parseDIExpressionBodyAtBeginning</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a35d32e57764638fe887f59392490e49c">llvm::parseTypeAtBeginning</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a>, <a href="#a7d28d6aff37550f9cd56074ddcea2677">shouldEmitInstrCountChangedRemark</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a76e8066b76cac14a0fcadde226f9bf9d">verifyLoadedModule</a>.</p>

</div>
</div>

### getDataLayout {#abcbe492bce3ccc16e0bbb50292576c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DataLayout &amp; llvm::Module::getDataLayout ()</td>
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

<p>Get the data layout for the module's target platform.</p>

<p>Definition at line 294 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-assumebundlebuilder-cpp-/assumebuilderstate/#a65edce9c8505e3d3b9c0d90794458288">anonymous{AssumeBundleBuilder.cpp}::AssumeBuilderState::addAccessedPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/mustexecute-cpp/#ad908d5abcd036d7ff7e277fda6821cf0">CanProveNotTakenFirstIteration</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#a388d5a62753f4e7ff4b72e54c1233fbc">llvm::OpenMPIRBuilder::createAtomicRead</a>, <a href="/web-llvm/docs/api/classes/llvm/openmpirbuilder/#ab0996924f219129d8de3cc1b8830f768">llvm::OpenMPIRBuilder::createReductions</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64targetobjectfile-cpp/#a0e2890f613a1a43228dec112d337340d">getAuthPtrSlotSymbolHelper</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa5d2c67dadc073dac78224224ee89350">llvm::GlobalValue::getDataLayout</a>, <a href="/web-llvm/docs/api/classes/llvm/targetloweringobjectfilemacho/#a66ebd2ccd2ea699bd04b40dd95c2fee4">llvm::TargetLoweringObjectFileMachO::getIndirectSymViaGOTPCRel</a>, <a href="/web-llvm/docs/api/classes/llvm/orc/irmaterializationunit/#a6ba5ee0773bcb7bf0614f9ae9f010198">llvm::orc::IRMaterializationUnit::IRMaterializationUnit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/siisellowering-cpp/#a5ee07316c71711c956769e3dd902079e">isAtomicRMWLegalXChgTy</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64targetlowering/#ac66d3f15510c7402f2a85a87c69f1603">llvm::AArch64TargetLowering::lowerDeinterleaveIntrinsicToLoad</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/local-cpp/#a05d7d91d31a8121c140a4da8645c6474">valueCoversEntireFragment</a>.</p>

</div>
</div>

### getDataLayoutStr {#ae63fce265b79048ddac80422d1d2729e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::Module::getDataLayoutStr ()</td>
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

<p>Get the data layout string for the module's target platform.</p>


<p>This is equivalent to <a href="#abcbe492bce3ccc16e0bbb50292576c5c">getDataLayout()</a>-&gt;getStringRepresentation().</p>


<p>Definition at line 289 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getInstructionCount {#ab21a2e0542e35ef6859e2d069ab18ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getInstructionCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the number of non-debug IR instructions in the module.</p>


<p>This is equivalent to the sum of the IR instruction counts of each function contained in the module.</p>


<p>Declaration at line 273 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 604 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getModuleIdentifier {#a9a4fa55f19f0d5bb47d1fe6802e18d1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::Module::getModuleIdentifier ()</td>
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

<p>Get the module identifier which is, essentially, the name of the module.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the module identifier as a string</p></dd>
</dl>


<p>Definition at line 268 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a>, <a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">llvm::ThinLTOCodeGenerator::emitImports</a>, <a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">llvm::ThinLTOCodeGenerator::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/structs/llvm/dotgraphtraits-02fb7f36a5622815e386262c1f910406/#a1e5d2d7a177eff7597bbe96b871be19d">llvm::DOTGraphTraits&lt; CallGraphDOTInfo * &gt;::getGraphName</a>, <a href="/web-llvm/docs/api/classes/llvm/loop/#a2b4746e455f9041187249483e7f5e5f5">llvm::Loop::getLocStr</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="/web-llvm/docs/api/classes/llvm/diagnosticinfoignoringinvaliddebugmetadata/#ad2ef8b3b001f5d507c738022b5fb4a65">llvm::DiagnosticInfoIgnoringInvalidDebugMetadata::print</a>, <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a> and <a href="/web-llvm/docs/api/namespaces/llvm/cgdata/#aa073bf33e4e66824238bc510dcdf0f4e">llvm::cgdata::saveModuleForTwoRounds</a>.</p>

</div>
</div>

### getModuleInlineAsm {#a08a39a8a62016bee607e0b28e6b54e27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::Module::getModuleInlineAsm ()</td>
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

<p>Get any module-scope inline assembly blocks.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a string containing the module-scope inline assembly blocks.</p></dd>
</dl>


<p>Definition at line 306 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getName {#a4b3648156c20e8cf63c5eb07c56ab2fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::Module::getName ()</td>
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

<p>Get a short "name" for the module.</p>


<p>This is useful for debugging or logging. It is essentially a convenience wrapper around <a href="#a9a4fa55f19f0d5bb47d1fe6802e18d1a">getModuleIdentifier()</a>.</p>


<p>Definition at line 285 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/dwarfcompileunit/#af154345e2837458e53079bc2eaf50ee2">llvm::DwarfCompileUnit::constructImportedEntityDIE</a>, <a href="/web-llvm/docs/api/classes/llvm/thinltocodegenerator/#a8f109c8e5687e9ee05ee86648c229398">llvm::ThinLTOCodeGenerator::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/anonymous-amdgpusplitmodule-cpp-/#a97973584f850e83ab0c845def98d9587">llvm::anonymous{AMDGPUSplitModule.cpp}::writeDOTGraph</a>.</p>

</div>
</div>

### getSourceFileName {#a4fb981ce623b68eea5cd781ee0ae8ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::Module::getSourceFileName ()</td>
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

<p>Get the module's original source file name.</p>


<p>When compiling from bitcode, this is taken from a bitcode record where it was recorded. For other compiles it is the same as the ModuleID, which would contain the source file name.</p>


<p>Definition at line 279 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab5f5de5d32f138fc104024357905735b">llvm::getStrippedSourceFileName</a>, <a href="/web-llvm/docs/api/classes/llvm/functionimporter/#a293aab6abe312ff6dbe227a3bcde838c">llvm::FunctionImporter::importFunctions</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a1ad010e488dcef9a629eb57ccd67d32d">selectExplicitSectionGlobal</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aac69630533101ec5ba74953a63082148">llvm::thinLTOInternalizeModule</a>.</p>

</div>
</div>

### getTargetTriple {#a6b882824580b4666f692474ecbae56ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string &amp; llvm::Module::getTargetTriple ()</td>
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

<p>Get the target triple which is a string describing the target host.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>a string containing the target triple.</p></dd>
</dl>


<p>Definition at line 298 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/set/#ga68e4901342bb8259cdcea4761207f967">llvm::ThinLTOCodeGenerator::crossModuleImport</a>, <a href="/web-llvm/docs/api/groups/set/#ga925598c2c1d67f25709f0fcedad5c7ec">llvm::ThinLTOCodeGenerator::emitImports</a>, <a href="/web-llvm/docs/api/groups/set/#gab2e319464d561a1ba4a0a6d97ba77963">llvm::ThinLTOCodeGenerator::gatherImportedSummariesForModule</a>, <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#a976ee001cbab0afed3bec6f4a07c6b35">llvm::LTOModule::getTargetTriple</a>, <a href="/web-llvm/docs/api/structs/anonymous-openmpopt-cpp-/aakernelinfofunction/#ac5c4384a376959ec882f7650e427dbb5">anonymous{OpenMPOpt.cpp}::AAKernelInfoFunction::initialize</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#ad7c5a4356eb729fe374f917da7435a12">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardCheck</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguard-cpp-/cfguardimpl/#a6817bdede4df5251b8422f22617be51f">anonymous{CFGuard.cpp}::CFGuardImpl::insertCFGuardDispatch</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/simplifylibcalls-cpp/#a24da6451c0e494831c85fa96cb572c9a">insertSinCosCall</a>, <a href="/web-llvm/docs/api/groups/set/#gaaa991901a8631f1c351289f5b59b2604">llvm::ThinLTOCodeGenerator::internalize</a>, <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfoimpl/#a6fe2425902ca5775f3b350cfbe49cc8f">llvm::TargetLibraryInfoImpl::isCallingConvCCompatible</a>, <a href="/web-llvm/docs/api/classes/anonymous-aarch64arm64eccalllowering-cpp-/aarch64arm64eccalllowering/#a7791efd93b12280fdad994fb6073933d">anonymous{AArch64Arm64ECCallLowering.cpp}::AArch64Arm64ECCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/groups/set/#ga123d1e01369e5a25d44c2925ee3087f4">llvm::ThinLTOCodeGenerator::optimize</a>, <a href="/web-llvm/docs/api/groups/set/#gac8d7927c4bf52374bb20fa31df9c5b22">llvm::ThinLTOCodeGenerator::promote</a> and <a href="/web-llvm/docs/api/classes/anonymous-aarch64stacktagging-cpp-/aarch64stacktagging/#a08f16f302c998119c978d7ce93b4c569">anonymous{AArch64StackTagging.cpp}::AArch64StackTagging::tagAlloca</a>.</p>

</div>
</div>

### shouldEmitInstrCountChangedRemark {#a7d28d6aff37550f9cd56074ddcea2677}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::shouldEmitInstrCountChangedRemark ()</td>
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

<p>Return true if size-info optimization remark is enabled, false otherwise.</p>

<p>Definition at line 321 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a0beddb53641a541e2238617c5fac4be7">getContext</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Module Level Mutators

### appendModuleInlineAsm {#ae83cb8c91cf6fa402d682f06f7535949}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::appendModuleInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Asm)</td>
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

<p>Append to the module-scope inline assembly blocks.</p>


<p>A trailing newline is added if the input doesn't have one.</p>


<p>Definition at line 353 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>.</p>

</div>
</div>

### setDataLayout {#aa68647befd5b72ece9bca6f6da69e391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setDataLayout (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Desc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the data layout.</p>

<p>Declaration at line 337 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 425 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setDataLayout {#a8931880fb7ce71e068a2ac1e704adaaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setDataLayout (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; Other)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 338 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 427 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setModuleIdentifier {#acdc9e9024fd3c1059ece16631c2d094f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::setModuleIdentifier (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> ID)</td>
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

<p>Set the module identifier.</p>

<p>Definition at line 331 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### setModuleInlineAsm {#a168c2c073b44c41dc521120bda0b1047}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::setModuleInlineAsm (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Asm)</td>
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

<p>Set the module-scope inline assembly blocks.</p>


<p>A trailing newline is added if the input doesn't have one.</p>


<p>Definition at line 345 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### setSourceFileName {#adc77fdf8a02fef55beaffb19a7087c19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::setSourceFileName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Set the module's original source file name.</p>

<p>Definition at line 334 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### setTargetTriple {#af66bad1510da8a71d20002609d3b4a25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::setTargetTriple (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> T)</td>
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

<p>Set the target triple.</p>

<p>Definition at line 341 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/ltomodule/#aa9d2a4bf9ce9b085e460d172b8d4f267">llvm::LTOModule::setTargetTriple</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Generic Value Accessors

### getIdentifiedStructTypes {#a8c7aeef16441f671e5e541a4f3eda0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; StructType * &gt; Module::getIdentifiedStructTypes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 384 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 492 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getMDKindID {#a51d7039664794cb004d82570dfd00063}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getMDKindID (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a unique non-zero <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the specified metadata kind.</p>


<p>getMDKindID - Return a unique non-zero <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> for the specified metadata kind.</p>


<p>This <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> is uniqued across modules in the current <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>Declaration at line 373 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 180 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getMDKindNames {#a3779e6e1fb83913e81ad3b46f059bede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::getMDKindNames (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the name for custom metadata IDs registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>getMDKindNames - Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the name for custom metadata IDs registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">ID</a> #0 is not used, so it is filled in as an empty string.</p>


<p>Declaration at line 377 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 187 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getNamedValue {#ab1e6423b61f37584900fbdcadeedafb6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalValue * Module::getNamedValue (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the global value in the module with the specified name, of arbitrary type.</p>


<p>getNamedValue - Return the first global value in the module with the specified name, of arbitrary type.</p>


<p>This method returns null if a global with the specified name is not found.</p>


<p>Declaration at line 366 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 170 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a3fe022748964a4bdaca9fa36568ec149">anonymous{ThinLTOBitcodeWriter.cpp}::cloneUsedGlobalVariables</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/targetloweringobjectfileimpl-cpp/#a3a19103e69c6cb0ad95809d01b7b60cf">getComdatGVForCOFF</a> and <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>.</p>

</div>
</div>

### getNumNamedValues {#a475f318372cb5b119d4f08cb5833f9e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getNumNamedValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the number of global values in the module.</p>

<p>Declaration at line 369 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 174 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getOperandBundleTags {#ab34623cb3c79d991ca41535635f89414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::getOperandBundleTags (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Populate client supplied <a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a> with the bundle tags registered in this <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a>.</p>


<p>The bundle tags are ordered by increasing bundle IDs.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><p><a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a1bf5d4ba3822ef0e75e953a9d19734a5">LLVMContext::getOperandBundleTagID</a></p></dd>
</dl>


<p>Declaration at line 382 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 191 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getUniqueIntrinsicName {#a7b91c906088d051b49c9b7f8847ecbe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string Module::getUniqueIntrinsicName (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> BaseName, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a80add6b3b1cdaec560907995127adc16">Intrinsic::ID</a> Id, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Proto)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a unique name for an intrinsic whose mangling is based on an unnamed type.</p>


<p>The Proto represents the function prototype.</p>


<p>Declaration at line 388 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 506 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Function Accessors

### getFunction {#a209a615a3a32241323420cca24b5520a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Function * Module::getFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up the specified function in the module symbol table.</p>


<p>If it does not exist, return null.</p>


<p>Declaration at line 437 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 228 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86winfixupbuffersecuritycheck-cpp-/x86winfixupbuffersecuritycheckpass/#a8d1d93bb20bf72c7782cf68446e5bf9f">anonymous{X86WinFixupBufferSecurityCheck.cpp}::X86WinFixupBufferSecurityCheckPass::CreateFailCheckSequence</a>, <a href="/web-llvm/docs/api/classes/llvm/selectiondag/#a2c7b6b90ed9c390a20c7bb95dc2ec4d2">llvm::SelectionDAG::getSymbolFunctionGlobalAddress</a>, <a href="/web-llvm/docs/api/namespaces/llvm/vfabi/#a8adf44ad04562ff150b0e8e352a38d46">llvm::VFABI::getVectorVariantNames</a>, <a href="/web-llvm/docs/api/structs/anonymous-xrayinstrumentation-cpp-/xrayinstrumentation/#a4fb91ea8621a93ca73b483592ac6b061">anonymous{XRayInstrumentation.cpp}::XRayInstrumentation::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/loopvectorizationcostmodel/#a8178cc5e49d5251d7ca3413b8a434f8f">llvm::LoopVectorizationCostModel::setVectorizedCallDecision</a>.</p>

</div>
</div>

### getOrInsertFunction {#abb107e4edbf05eae92936cba6801c2d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee Module::getOrInsertFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * T, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> AttributeList)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up the specified function in the module symbol table.</p>


<p>If it does not exist, add a prototype for the function and return it. Otherwise, return the existing function.</p>


<p>In all cases, the returned value is a <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> wrapper around the '<a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> <em>T' passed in, as well as the '<a href="/web-llvm/docs/api/classes/llvm/value">Value</a></em>' of the <a href="/web-llvm/docs/api/classes/llvm/function">Function</a>. The function type of the function may differ from the function type stored in <a href="/web-llvm/docs/api/classes/llvm/functioncallee">FunctionCallee</a> if it was previously created with a different type.</p>


<p>Note: For library calls <a href="/web-llvm/docs/api/namespaces/llvm/#a87cba3c4c88ab5df01a7f7dece1e0266">getOrInsertLibFunc()</a> should be used instead.</p>


<p>Declaration at line 405 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 204 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a49b93792c9c07b4d1c53fb9c3d903e14">callAppendArgs</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#ac500e82c324a3dd8e9c5a87c256f2883">callAppendStringN</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/amdgpuemitprintf-cpp/#a9349e05033852c48c123a000e134a453">callPrintfBegin</a>, <a href="#a2cf6738ff24ef8e3e474763aec81b401">getOrInsertFunction</a>, <a href="#a9c362a6df0554c3d9355aadfa67a1914">getOrInsertFunction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/boundschecking-cpp/#a1a4145a18b32a1bc1030bf789e370963">InsertCall</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/instrumentation/realtimesanitizer-cpp/#aaf5c6a95e57ae41b1bb74e87476d3dcc">insertCallBeforeInstruction</a>.</p>

</div>
</div>

### getOrInsertFunction {#a5310b7bb84192372c55cbc66cd975c59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee Module::getOrInsertFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 408 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 221 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getOrInsertFunction {#a2cf6738ff24ef8e3e474763aec81b401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgsTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee llvm::Module::getOrInsertFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> AttributeList, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, ArgsTy... Args)</td>
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

<p>Same as above, but takes a list of function arguments, which makes it easier for clients to use.</p>

<p>Definition at line 413 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a> and <a href="#abb107e4edbf05eae92936cba6801c2d9">getOrInsertFunction</a>.</p>

</div>
</div>

### getOrInsertFunction {#a9c362a6df0554c3d9355aadfa67a1914}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgsTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee llvm::Module::getOrInsertFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, ArgsTy... Args)</td>
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

<p>Same as above, but without the attributes.</p>

<p>Definition at line 424 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#abb107e4edbf05eae92936cba6801c2d9">getOrInsertFunction</a>.</p>

</div>
</div>

### getOrInsertFunction {#a89b5f89041a0375f7ece431f29421bee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... ArgsTy&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FunctionCallee llvm::Module::getOrInsertFunction (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/attributelist">AttributeList</a> AttributeList, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * Invalid, ArgsTy... Args)</td>
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



<p>Definition at line 432 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/#af59335be18fa802d111a646be658b7d0a68a576ae5bab85b26f5e5a947d3b41e8">llvm::Invalid</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Global Variable Accessors

### getGlobalVariable {#aa6aa4f20a3c82e66d3e0b86a62ce2873}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * llvm::Module::getGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Look up the specified global variable in the module symbol table.</p>


<p>If it does not exist, return null. If AllowInternal is set to true, this function will return types that have InternalLinkage. By default, these types are not returned.</p>


<p>Definition at line 447 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#ad625ba253f12b49a01ced02c4190e22b">getGlobalVariable</a>.</p>

</div>
</div>

### getGlobalVariable {#ac8812c64092590a5ebde21f70c538d1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * Module::getGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AllowLocal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>getGlobalVariable - Look up the specified global variable in the module symbol table.</p>


<p>If it does not exist, return null. The type argument should be the underlying type of the global, i.e., it should not have the top-level <a href="/web-llvm/docs/api/classes/llvm/pointertype">PointerType</a>, which represents the address of the global. If AllowLocal is set to true, this function will return types that have an local. By default, these types are not returned.</p>


<p>Declaration at line 451 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 243 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getGlobalVariable {#a7c3df989919f622a0bdc2649a0876263}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * llvm::Module::getGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool AllowInternal=false)</td>
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



<p>Definition at line 453 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#ad625ba253f12b49a01ced02c4190e22b">getGlobalVariable</a> and <a href="#a378f93ece2ac999e500f07056cfe6528">Module</a>.</p>

</div>
</div>

### getNamedGlobal {#ab7b871f94b33c166ef30575a247cf9c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const GlobalVariable * llvm::Module::getNamedGlobal (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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

<p>Return the global variable in the module with the specified name, of arbitrary type.</p>


<p>This method returns null if a global with the specified name is not found.</p>


<p>Definition at line 462 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/webassembly/webassemblyloweremscriptenehsjlj-cpp/#ad625ba253f12b49a01ced02c4190e22b">getGlobalVariable</a>.</p>

</div>
</div>

### getNamedGlobal {#a19ec326d8214646996350c9c5721102e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalVariable * llvm::Module::getNamedGlobal (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
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



<p>Definition at line 465 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a378f93ece2ac999e500f07056cfe6528">Module</a>.</p>

</div>
</div>

### getOrInsertGlobal {#abd8f7242df6ecb10f429c4d39403c334}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * Module::getOrInsertGlobal (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> *()&gt; CreateGlobalCallback)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up the specified global in the module symbol table.</p>


<p>getOrInsertGlobal - Look up the specified global in the module symbol table.</p>


<p>If it does not exist, invoke a callback to create a declaration of the global and return it. The global is constantexpr casted to the expected type if necessary.</p>


<ol class="doxyList" type="1">
<li>If it does not exist, add a declaration of the global and return it.</li>
<li>Else, the global exists but has the wrong type: return the function with a constantexpr cast to the right type.</li>
<li>Finally, if the existing global is the correct declaration, return the existing global.</li>
</ol>

<p>Declaration at line 475 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getOrInsertGlobal {#a1ec20a6f23ced1a328d4b1223fa22d96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * Module::getOrInsertGlobal (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Look up the specified global in the module symbol table.</p>


<p>If required, this overload constructs the global variable using its constructor's defaults.</p>


<p>Declaration at line 480 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 272 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Global Alias Accessors

### getNamedAlias {#ae520fd3355e9563c528b7ff4c690ce7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalAlias * Module::getNamedAlias (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the global alias in the module with the specified name, of arbitrary type.</p>


<p>This method returns null if a global with the specified name is not found.</p>


<p>Declaration at line 489 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 286 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Global IFunc Accessors

### getNamedIFunc {#a9e8fe9473aff6bac3b9f2556407a2c86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GlobalIFunc * Module::getNamedIFunc (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the global ifunc in the module with the specified name, of arbitrary type.</p>


<p>This method returns null if a global with the specified name is not found.</p>


<p>Declaration at line 498 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Named Metadata Accessors

### eraseNamedMetadata {#a46d5a31c86f52f5b535586397efa5a21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::eraseNamedMetadata (<a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> * NMD)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Remove the given <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> from this module and delete it.</p>


<p>eraseNamedMetadata - Remove the given <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> from this module and delete it.</p>


<p>Declaration at line 514 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 318 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/namedmdnode/#a7b8c6e263c8047823d8869cc27dd8008">llvm::NamedMDNode::eraseFromParent</a>.</p>

</div>
</div>

### getNamedMetadata {#a06bb57eb1830a137e7b8f8b25908ed24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode * Module::getNamedMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the first <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module with the specified name.</p>


<p>getNamedMetadata - Return the first <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module with the specified name.</p>


<p>This method returns null if a <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> with the specified name is not found.</p>


<p>Declaration at line 506 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 297 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#afd992a2165073c9cea53128d5b6c4145">llvm::X86FrameLowering::adjustForHiPEPrologue</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3a75955141a4289e3ff78d21aea406a6">llvm::cacheAnnotationFromMD</a>, <a href="#a429ef9bbd0adc89bc6f810d7798f086b">debug_compile_units</a>, <a href="#af51e2d4d20061325bd7496adb08bd392">debug_compile_units_begin</a> and <a href="#aff491d52bf87eb3f70bcc4fcbdc71181">debug_compile_units_end</a>.</p>

</div>
</div>

### getOrInsertNamedMetadata {#ab33e5587b25f9c80f6ea5000124d1a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode * Module::getOrInsertNamedMetadata (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the named <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> in the module with the specified name.</p>


<p>getOrInsertNamedMetadata - Return the first named <a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> in the module with the specified name.</p>


<p>This method returns a new <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> if a <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> with the specified name is not found.</p>


<p>Declaration at line 511 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac1b2be839460bb277d4f07f4aa5225ac">llvm::CloneFunctionInto</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Comdat Accessors

### getOrInsertComdat {#ab83085f68d866564c5dd63143c8cac2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Comdat * Module::getOrInsertComdat (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the <a href="/web-llvm/docs/api/classes/llvm/comdat">Comdat</a> in the module with the specified name.</p>


<p>It is created if it didn't already exist.</p>


<p>Declaration at line 522 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 611 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/anonymous-thinltobitcodewriter-cpp-/#a727a05f1cb9b333d251bd1485784d039">anonymous{ThinLTOBitcodeWriter.cpp}::promoteInternals</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Module Flags Accessors

### addModuleFlag {#a80a42b3e2a54d45bcf647619437c6ac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::addModuleFlag (<a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a> Behavior, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Add a module-level flag to the module-level flags metadata.</p>


<p>addModuleFlag - Add a module-level flag to the module-level flags metadata.</p>


<p>It will create the module-level flags named metadata if it doesn't already exist.</p>


<p>Declaration at line 546 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 377 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### addModuleFlag {#a02876ca011b3898bd050c54213f1f42f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::addModuleFlag (<a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a> Behavior, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 547 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 385 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### addModuleFlag {#a58572a454a102a575543097e476b34e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::addModuleFlag (<a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a> Behavior, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, uint32_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 548 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 389 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### addModuleFlag {#afda9795063bf986d9472afdfd38947f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::addModuleFlag (<a href="/web-llvm/docs/api/classes/llvm/mdnode">MDNode</a> * Node)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 549 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 394 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getModuleFlag {#afe43fb9222955bdceb316e851056f516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * Module::getModuleFlag (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the corresponding value if Key appears in module flags, otherwise return null.</p>

<p>Declaration at line 533 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 354 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-riscvtargetmachine-cpp-/riscvpassconfig/#a373d9e90c782cb9d8d84cbe4282f10d6">anonymous{RISCVTargetMachine.cpp}::RISCVPassConfig::addPreEmitPass2</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aa75cdd420a3ce670e2c3b61046f2b8a7">llvm::calculateSEHStateNumbers</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a4547a0e8cb23afe1f8767916fd173920">llvm::calculateWinCXXEHStateNumbers</a>, <a href="/web-llvm/docs/api/classes/anonymous-cfguardlongjmp-cpp-/cfguardlongjmp/#a17b3d486f52582c92dec4b050aedb70a">anonymous{CFGuardLongjmp.cpp}::CFGuardLongjmp::runOnMachineFunction</a>, <a href="/web-llvm/docs/api/classes/anonymous-ehcontguardcatchret-cpp-/ehcontguardcatchret/#a6340bc98382b1dce1a1e8648fd72732b">anonymous{EHContGuardCatchret.cpp}::EHContGuardCatchret::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/structs/anonymous-x86returnthunks-cpp-/x86returnthunks/#ab4a10d58e295ec66ff8c9c1d3eeb0529">anonymous{X86ReturnThunks.cpp}::X86ReturnThunks::runOnMachineFunction</a>.</p>

</div>
</div>

### getModuleFlagsMetadata {#add929ddb2351134fe6c351d6fd8caf6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::getModuleFlagsMetadata (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/module/moduleflagentry">ModuleFlagEntry</a> &gt; &amp; Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the module flags in the provided vector.</p>


<p>getModuleFlagsMetadata - Returns the module flags in the provided vector.</p>


<p>Declaration at line 529 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 338 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getModuleFlagsMetadata {#ac6ad813d221447b431968adf99ef7ce1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode * llvm::Module::getModuleFlagsMetadata ()</td>
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

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module that represents module-level flags.</p>


<p>This method returns null if there are no module-level flags.</p>


<p>Definition at line 537 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### getOrInsertModuleFlagsMetadata {#a421bab6b3fc0951cfaab3b10574be5fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">NamedMDNode * Module::getOrInsertModuleFlagsMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module that represents module-level flags.</p>


<p>getOrInsertModuleFlagsMetadata - Returns the <a href="/web-llvm/docs/api/classes/llvm/namedmdnode">NamedMDNode</a> in the module that represents module-level flags.</p>


<p>If module-level flags aren't found, it creates the named metadata that contains them.</p>


<p>Declaration at line 542 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 368 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setModuleFlag {#a6087a4906a23b4807fe6ca89b95e447e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setModuleFlag (<a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a> Behavior, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Like addModuleFlag but replaces the old module flag if it already exists.</p>

<p>Declaration at line 551 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 403 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setModuleFlag {#ac16af0eab7ea5ff4233d37537cef16e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setModuleFlag (<a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a> Behavior, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 552 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 415 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setModuleFlag {#a8f547d639d76ca60e580097b14bc8952}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setModuleFlag (<a href="#a0a5c55e12c97b80021330fe82b642293">ModFlagBehavior</a> Behavior, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Key, uint32_t Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 553 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 419 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Materialization

### eraseGlobalVariable {#a9b8e4e706dbd7c8fadfd8593bb17979d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::eraseGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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

<p>Remove global variable <span class="doxyComputerOutput">GV</span> from the list and delete it.</p>

<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#ae0cf03d5de37330b1eb69dd22a1d5057">llvm::GlobalVariable::eraseFromParent</a>.</p>

</div>
</div>

### getMaterializer {#a4efc18e16e4bc826d1c96c833bffe3c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GVMaterializer * llvm::Module::getMaterializer ()</td>
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

<p>Retrieves the <a href="/web-llvm/docs/api/classes/llvm/gvmaterializer">GVMaterializer</a>, if any, for this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>.</p>

<p>Definition at line 568 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#ab7491e38806b98b90a690f63cb678232">isMaterialized</a>.</p>

</div>
</div>

### insertGlobalVariable {#aac75aa0b7583c039e8a9d4ccae280769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::insertGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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

<p>Insert global variable <span class="doxyComputerOutput">GV</span> at the end of the global variable list and take ownership.</p>

<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#aac75aa0b7583c039e8a9d4ccae280769">insertGlobalVariable</a>.</p>


<p>Referenced by <a href="#aac75aa0b7583c039e8a9d4ccae280769">insertGlobalVariable</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a31b17b67a86749cfd99e97041c819791">OptimizeGlobalAddressOfAllocation</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/utils/ctorutils-cpp/#a26771a5b06ef10e47546922cc377044b">removeGlobalCtors</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/globalopt-cpp/#a77de6d50432bef62e38fd24f2030026c">TryToShrinkGlobalToBoolean</a>.</p>

</div>
</div>

### insertGlobalVariable {#a6bf41cbf5f3f2995d64e38d3d3c98d65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::insertGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/iplist-impl/#a4563732eae31ee14694e7ce17a5a6749">GlobalListType::iterator</a> Where, <a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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

<p>Insert global variable <span class="doxyComputerOutput">GV</span> into the global variable list before <span class="doxyComputerOutput">Where</span> and take ownership.</p>

<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### isMaterialized {#ab7491e38806b98b90a690f63cb678232}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::isMaterialized ()</td>
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



<p>Definition at line 569 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a4efc18e16e4bc826d1c96c833bffe3c5">getMaterializer</a>.</p>

</div>
</div>

### materialize {#a1f304ac10c82c01df336a728197985c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error Module::materialize (<a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> * GV)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make sure the <a href="/web-llvm/docs/api/classes/llvm/globalvalue">GlobalValue</a> is fully read.</p>

<p>Declaration at line 572 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 468 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#ac1b5643f40dd3c7b92a548027eb13de0">llvm::GlobalValue::materialize</a>.</p>

</div>
</div>

### materializeAll {#a0b0388196b68ca0fc2e187babd1a02d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error Module::materializeAll ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Make sure all GlobalValues in this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> are fully read and clear the Materializer.</p>

<p>Declaration at line 576 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 475 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### materializeMetadata {#a3db6c425ae4698fdf2245b560113720b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Error Module::materializeMetadata ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 578 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 482 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### removeGlobalVariable {#afb5360df1b24fc7637ea22a41193674e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::Module::removeGlobalVariable (<a href="/web-llvm/docs/api/classes/llvm/globalvariable">GlobalVariable</a> * GV)</td>
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

<p>Detach global variable <span class="doxyComputerOutput">GV</span> from the list but don't delete it.</p>

<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a22e076c4cf000eba885dd00048641c6f">llvm::GlobalVariable::removeFromParent</a>.</p>

</div>
</div>

### setMaterializer {#a1a67a7e46fd17084b2ea152d2d435253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setMaterializer (<a href="/web-llvm/docs/api/classes/llvm/gvmaterializer">GVMaterializer</a> * GVM)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sets the <a href="/web-llvm/docs/api/classes/llvm/gvmaterializer">GVMaterializer</a> to GVM.</p>


<p>This module must not yet have a Materializer. To reset the materializer for a module that already has one, call materializeAll first. Destroying this module will destroy its materializer without materializing any more GlobalValues. Without destroying the <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>, there is no way to detach or destroy a materializer without materializing all the GVs it controls, to avoid leaving orphan unmaterialized GVs.</p>


<p>Declaration at line 566 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 461 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Global Variable Iteration

### global\_begin {#a0567b31cf5caa26522fcc2e7cadc1dde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">global_iterator llvm::Module::global_begin ()</td>
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



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a8c41c9882546676724cb151c9ff8723e">globals</a>, <a href="#acbeb92e486d706e83d7ddde18375ad13">globals</a> and <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga658b44552d64b26c308bce8b4ffa02d6">LLVMGetPreviousGlobal</a>.</p>

</div>
</div>

### global\_begin {#a065461aba1dd9a8564d897e064c0418f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_global_iterator llvm::Module::global_begin ()</td>
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



<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### global\_empty {#a227cc1d762f784ebb21c2a2056163e20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::global_empty ()</td>
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



<p>Definition at line 700 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### global\_end {#a19b72cdd81bd792545e25466b43ac7c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">global_iterator llvm::Module::global_end ()</td>
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



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a8c41c9882546676724cb151c9ff8723e">globals</a>, <a href="#acbeb92e486d706e83d7ddde18375ad13">globals</a> and <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalvariable/#ga3d3196c1f51231e2639321265f2f9ba9">LLVMGetNextGlobal</a>.</p>

</div>
</div>

### global\_end {#a224f0cb3f8a8720f853ef21292230076}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_global_iterator llvm::Module::global_end ()</td>
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



<p>Definition at line 698 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### global\_size {#a41e50f6ee64cb2653a50fb5c0dad6c9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Module::global_size ()</td>
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



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### globals {#a8c41c9882546676724cb151c9ff8723e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; global_iterator &gt; llvm::Module::globals ()</td>
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



<p>Definition at line 702 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a0567b31cf5caa26522fcc2e7cadc1dde">global_begin</a>, <a href="#a19b72cdd81bd792545e25466b43ac7c2">global_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a2604f458da0e7d0a33702d7d66d660dc">llvm::sandboxir::Context::createModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-updatecompilerused-cpp-/preservelibcallsandasmused/#a141a9f26d14fdfbae8dc42c43af92685">anonymous{UpdateCompilerUsed.cpp}::PreserveLibCallsAndAsmUsed::findInModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### globals {#acbeb92e486d706e83d7ddde18375ad13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_global_iterator &gt; llvm::Module::globals ()</td>
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



<p>Definition at line 705 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a0567b31cf5caa26522fcc2e7cadc1dde">global_begin</a>, <a href="#a19b72cdd81bd792545e25466b43ac7c2">global_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Function Iteration

### begin {#a279174d137c1ef32aa5b627f5e06620f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::Module::begin ()</td>
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



<p>Definition at line 713 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a446675c956107a09af38080dde388d9e">functions</a>, <a href="#ac1245f55f582306f0241f42644275451">functions</a> and <a href="/web-llvm/docs/api/classes/llvm/stacksafetyglobalinfo/#a138eb4d1f72b7808b5cfc34c64440007">llvm::StackSafetyGlobalInfo::print</a>.</p>

</div>
</div>

### begin {#a06b7c02a5e98060d0d56ca71fe2cf6fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::Module::begin ()</td>
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



<p>Definition at line 714 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### empty {#a9f6e43cc6d546367ba5428bd4225ae80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::empty ()</td>
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



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### end {#aa608a2d900dd6c15c18f4236b6548496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator llvm::Module::end ()</td>
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



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a446675c956107a09af38080dde388d9e">functions</a> and <a href="#ac1245f55f582306f0241f42644275451">functions</a>.</p>

</div>
</div>

### end {#adb6b9b90afbaa52a46e58325d94ca12d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator llvm::Module::end ()</td>
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



<p>Definition at line 716 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### functions {#a446675c956107a09af38080dde388d9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; iterator &gt; llvm::Module::functions ()</td>
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



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a279174d137c1ef32aa5b627f5e06620f">begin</a>, <a href="#aa608a2d900dd6c15c18f4236b6548496">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### functions {#ac1245f55f582306f0241f42644275451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_iterator &gt; llvm::Module::functions ()</td>
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



<p>Definition at line 727 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a279174d137c1ef32aa5b627f5e06620f">begin</a>, <a href="#aa608a2d900dd6c15c18f4236b6548496">end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### rbegin {#a9bc427c11e687119cb75013d620a2f51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::Module::rbegin ()</td>
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



<p>Definition at line 717 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### rbegin {#a742e0736da0d59dd2bd303bbebd49f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::Module::rbegin ()</td>
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



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### rend {#a7650724f66b289096b7fa0e949f3e0c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator llvm::Module::rend ()</td>
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



<p>Definition at line 719 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### rend {#a8de1942d5e3a76434fe7281563d39193}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_reverse_iterator llvm::Module::rend ()</td>
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



<p>Definition at line 720 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### size {#a8298f8e0d09cbc01af09bf2fa567dd59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Module::size ()</td>
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



<p>Definition at line 721 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Alias Iteration

### alias\_begin {#a755dbbd47c63c53cda3e93d9d608562a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">alias_iterator llvm::Module::alias_begin ()</td>
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



<p>Definition at line 735 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a696e00bbe45dcea703f433de7b38f699">aliases</a>, <a href="#a125a886cf5387bd7bc249ab43c4aecae">aliases</a> and <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalalias/#gab53f2ccab1363e10116a064467c4837d">LLVMGetPreviousGlobalAlias</a>.</p>

</div>
</div>

### alias\_begin {#a71edb4c45de209454f34732ee8e29d4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_alias_iterator llvm::Module::alias_begin ()</td>
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



<p>Definition at line 736 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### alias\_empty {#a895ac069f3bba7b395b9536c876cb2b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::alias_empty ()</td>
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



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### alias\_end {#a6d03597beb9097fc781a6c723cff50d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">alias_iterator llvm::Module::alias_end ()</td>
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



<p>Definition at line 737 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a696e00bbe45dcea703f433de7b38f699">aliases</a>, <a href="#a125a886cf5387bd7bc249ab43c4aecae">aliases</a> and <a href="/web-llvm/docs/api/groups/llvmcorevalueconstantglobalalias/#ga4b794045d4797dcb9ce36dac26e18341">LLVMGetNextGlobalAlias</a>.</p>

</div>
</div>

### alias\_end {#a5411bf6cb8994ee516b512f5a2ac7921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_alias_iterator llvm::Module::alias_end ()</td>
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



<p>Definition at line 738 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### alias\_size {#a2130e60b0bd151d92c1eafd09dde4d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Module::alias_size ()</td>
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



<p>Definition at line 739 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### aliases {#a696e00bbe45dcea703f433de7b38f699}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; alias_iterator &gt; llvm::Module::aliases ()</td>
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



<p>Definition at line 742 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a755dbbd47c63c53cda3e93d9d608562a">alias_begin</a>, <a href="#a6d03597beb9097fc781a6c723cff50d6">alias_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a2604f458da0e7d0a33702d7d66d660dc">llvm::sandboxir::Context::createModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-updatecompilerused-cpp-/preservelibcallsandasmused/#a141a9f26d14fdfbae8dc42c43af92685">anonymous{UpdateCompilerUsed.cpp}::PreserveLibCallsAndAsmUsed::findInModule</a>, <a href="/web-llvm/docs/api/classes/anonymous-linkmodules-cpp-/modulelinker/#a589fd28f47f98110e06d544523d59977">anonymous{LinkModules.cpp}::ModuleLinker::run</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#aff4d1b90a120cf50deb15494c801d589">llvm::thinLTOFinalizeInModule</a>.</p>

</div>
</div>

### aliases {#a125a886cf5387bd7bc249ab43c4aecae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_alias_iterator &gt; llvm::Module::aliases ()</td>
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



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a755dbbd47c63c53cda3e93d9d608562a">alias_begin</a>, <a href="#a6d03597beb9097fc781a6c723cff50d6">alias_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## IFunc Iteration

### ifunc\_begin {#a078bdc04f27a6002b0012692e1472a7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ifunc_iterator llvm::Module::ifunc_begin ()</td>
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



<p>Definition at line 753 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a336410508731bddd9add82863a37aaa0">ifuncs</a>, <a href="#ad032e05bf06965ec900f65ed47ec2f5f">ifuncs</a> and <a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc/#gae19214b102baae71f805de3544b30247">LLVMGetPreviousGlobalIFunc</a>.</p>

</div>
</div>

### ifunc\_begin {#ae37fae71241018cf3acf6f73a4239b58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_ifunc_iterator llvm::Module::ifunc_begin ()</td>
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



<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ifunc\_empty {#af6d65debb5a27920461aaa21c6374a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::ifunc_empty ()</td>
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



<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ifunc\_end {#a620fd079c2bf4ed43399aad668ce5be5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ifunc_iterator llvm::Module::ifunc_end ()</td>
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



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="#a336410508731bddd9add82863a37aaa0">ifuncs</a>, <a href="#ad032e05bf06965ec900f65ed47ec2f5f">ifuncs</a> and <a href="/web-llvm/docs/api/groups/llvmccorevalueglobalifunc/#ga26f3e0f1fb15709537936476b44da768">LLVMGetNextGlobalIFunc</a>.</p>

</div>
</div>

### ifunc\_end {#a2fcb9307da079106ed4f8960e36b809b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_ifunc_iterator llvm::Module::ifunc_end ()</td>
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



<p>Definition at line 756 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ifunc\_size {#a93b29be57202c8bc1a6ee77072de8dce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Module::ifunc_size ()</td>
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



<p>Definition at line 757 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### ifuncs {#a336410508731bddd9add82863a37aaa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; ifunc_iterator &gt; llvm::Module::ifuncs ()</td>
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



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a078bdc04f27a6002b0012692e1472a7c">ifunc_begin</a>, <a href="#a620fd079c2bf4ed43399aad668ce5be5">ifunc_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/sandboxir/context/#a2604f458da0e7d0a33702d7d66d660dc">llvm::sandboxir::Context::createModule</a>.</p>

</div>
</div>

### ifuncs {#ad032e05bf06965ec900f65ed47ec2f5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_ifunc_iterator &gt; llvm::Module::ifuncs ()</td>
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



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a078bdc04f27a6002b0012692e1472a7c">ifunc_begin</a>, <a href="#a620fd079c2bf4ed43399aad668ce5be5">ifunc_end</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Named Metadata Iteration

### debug\_compile\_units {#a429ef9bbd0adc89bc6f810d7798f086b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; debug_compile_units_iterator &gt; llvm::Module::debug_compile_units ()</td>
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

<p>Return an iterator for all DICompileUnits listed in this <a href="/web-llvm/docs/api/classes/llvm/module">Module</a>'s llvm.dbg.cu named metadata node and aren't explicitly marked as NoDebug.</p>

<p>Definition at line 870 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="#a06bb57eb1830a137e7b8f8b25908ed24">getNamedMetadata</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>.</p>

</div>
</div>

### debug\_compile\_units\_begin {#af51e2d4d20061325bd7496adb08bd392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">debug_compile_units_iterator llvm::Module::debug_compile_units_begin ()</td>
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



<p>Definition at line 857 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a06bb57eb1830a137e7b8f8b25908ed24">getNamedMetadata</a>.</p>

</div>
</div>

### debug\_compile\_units\_end {#aff491d52bf87eb3f70bcc4fcbdc71181}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">debug_compile_units_iterator llvm::Module::debug_compile_units_end ()</td>
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



<p>Definition at line 862 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Reference <a href="#a06bb57eb1830a137e7b8f8b25908ed24">getNamedMetadata</a>.</p>

</div>
</div>

### named\_metadata {#a57e28660be46fe2befd3f5f04825fd00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; named_metadata_iterator &gt; llvm::Module::named_metadata ()</td>
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



<p>Definition at line 807 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a5d052342d8cb7a6952a4c123b5385f90">named_metadata_begin</a> and <a href="#ab52eefaf4892829072b70e0e2e3d88bf">named_metadata_end</a>.</p>

</div>
</div>

### named\_metadata {#a9246bed13b395965d1afc1c24ec4ea74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator_range&lt; const_named_metadata_iterator &gt; llvm::Module::named_metadata ()</td>
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



<p>Definition at line 810 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a341215803e83773a3e97860dc291f121">llvm::make_range</a>, <a href="#a5d052342d8cb7a6952a4c123b5385f90">named_metadata_begin</a> and <a href="#ab52eefaf4892829072b70e0e2e3d88bf">named_metadata_end</a>.</p>

</div>
</div>

### named\_metadata\_begin {#a5d052342d8cb7a6952a4c123b5385f90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">named_metadata_iterator llvm::Module::named_metadata_begin ()</td>
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



<p>Definition at line 794 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoremodule/#ga26be85891d4ed0c9b687b41d35b5c6e6">LLVMGetPreviousNamedMetadata</a>, <a href="#a57e28660be46fe2befd3f5f04825fd00">named_metadata</a> and <a href="#a9246bed13b395965d1afc1c24ec4ea74">named_metadata</a>.</p>

</div>
</div>

### named\_metadata\_begin {#a40ad9ce20cb731381d062ed2cda972a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_named_metadata_iterator llvm::Module::named_metadata_begin ()</td>
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



<p>Definition at line 795 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### named\_metadata\_empty {#a36bf9b28e4b81b5690089bb26bc4de03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::Module::named_metadata_empty ()</td>
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



<p>Definition at line 805 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### named\_metadata\_end {#ab52eefaf4892829072b70e0e2e3d88bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">named_metadata_iterator llvm::Module::named_metadata_end ()</td>
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



<p>Definition at line 799 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/groups/llvmccoremodule/#gaacd234d81c636cdd202dd64dad371e1c">LLVMGetNextNamedMetadata</a>, <a href="#a57e28660be46fe2befd3f5f04825fd00">named_metadata</a> and <a href="#a9246bed13b395965d1afc1c24ec4ea74">named_metadata</a>.</p>

</div>
</div>

### named\_metadata\_end {#a9f2efb3a0e5809e56f54796680bc77b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_named_metadata_iterator llvm::Module::named_metadata_end ()</td>
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



<p>Definition at line 800 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

### named\_metadata\_size {#ab156619982240ea1c73ac9dd22a1b840}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t llvm::Module::named_metadata_size ()</td>
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



<p>Definition at line 804 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility functions for printing and dumping Module objects

### dropAllReferences {#a61b1317d05efe05a549bf94bc949e0d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::dropAllReferences ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>This function causes all the subinstructions to "let go" of all references that they are maintaining.</p>


<p>This allows one to 'delete' a whole class at a time, even though there may be circular references... first all references are dropped, and all use counts go to zero. Then everything is delete'd for real. Note that no operations are valid on an object that has "dropped all references", except operator delete.</p>


<p>Declaration at line 907 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 563 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### dump {#a9b4c67a0936fe59c9511ff591b97f260}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::dump ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Dump the module to stderr (for debugging).</p>

<p>Declaration at line 899 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 5323 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a7c46c742c31be54870e2038048e6b391">llvm::dbgs</a>, <a href="#a9b4c67a0936fe59c9511ff591b97f260">dump</a> and <a href="/web-llvm/docs/api/files/lib/lib/object/archivewriter-cpp/#aa9f638c7ae7fdd206a6c60e26bef9751">print</a>.</p>


<p>Referenced by <a href="#a9b4c67a0936fe59c9511ff591b97f260">dump</a>.</p>

</div>
</div>

### print {#a8ee5166cba8576e41617fc96aec1fb85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::print (<a href="/web-llvm/docs/api/classes/llvm/raw-ostream">raw_ostream</a> &amp; OS, <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a> * AAW, bool ShouldPreserveUseListOrder=false, bool IsForDebug=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Print the module to an output stream with an optional <a href="/web-llvm/docs/api/classes/llvm/assemblyannotationwriter">AssemblyAnnotationWriter</a>.</p>


<p>If <span class="doxyComputerOutput">ShouldPreserveUseListOrder</span>, then include uselistorder directives so that use-lists can be recreated when reading the assembly.</p>


<p>Declaration at line 894 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 4912 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a>.</p>


<p>Reference <a href="#a8ee5166cba8576e41617fc96aec1fb85">print</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/memoryssa/#afa9b4a650e1a6de2061538a19be3a234">llvm::MemorySSA::print</a> and <a href="#a8ee5166cba8576e41617fc96aec1fb85">print</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility functions for querying Debug information.

### getCodeViewFlag {#a7133d921c103967178f1388c8f273da3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getCodeViewFlag ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the CodeView Version by checking module flags.</p>


<p>Returns zero if not present in module.</p>


<p>Declaration at line 925 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 597 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86framelowering/#af2ab7cd691053c57c27e810c549a0300">llvm::X86FrameLowering::emitPrologue</a>.</p>

</div>
</div>

### getDwarfVersion {#aa5fa42829b640beda25bd5e16f7eb830}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getDwarfVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Dwarf Version by checking module flags.</p>

<p>Declaration at line 918 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### getNumberRegisterParameters {#a9b5097cd5df342da24466f39ffd5ecae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned Module::getNumberRegisterParameters ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the Number of <a href="/web-llvm/docs/api/classes/llvm/register">Register</a> ParametersDwarf Version by checking module flags.</p>

<p>Declaration at line 915 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### isDwarf64 {#aa89510c798cef7265b248241964c16f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Module::isDwarf64 ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the DWARF format by checking module flags.</p>

<p>Declaration at line 921 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 592 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility functions for querying and setting PIC level

### getPICLevel {#a892dfcabd163bf60c4916e5456afedb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PICLevel::Level Module::getPICLevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the PIC level (small or large model)</p>

<p>Declaration at line 932 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 617 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setPICLevel {#a98f04f1a6786a147aa95a967478f9cbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setPICLevel (<a href="/web-llvm/docs/api/namespaces/llvm/piclevel/#a66ddbf1bb21f90ddc44260d1ca677b6b">PICLevel::Level</a> PL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the PIC level (small or large model)</p>

<p>Declaration at line 935 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 627 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility functions for querying and setting PIE level

### getPIELevel {#af3295ffffcff40d7c95aa9fb4d13256a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PIELevel::Level Module::getPIELevel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the PIE level (small or large model)</p>

<p>Declaration at line 943 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 633 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#a07028bb765a646ca5ca5375162a93d7c">llvm::TargetMachine::getTLSModel</a> and <a href="/web-llvm/docs/api/files/lib/lib/lto/thinltocodegenerator-cpp/#a8e7fe209b55be4dfce7921829e90180c">ProcessThinLTOModule</a>.</p>

</div>
</div>

### setPIELevel {#ae1f343c75351052dcbb1ee866cd18347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setPIELevel (<a href="/web-llvm/docs/api/namespaces/llvm/pielevel/#ae01fe422624f3a5afd84d14146f9112c">PIELevel::Level</a> PL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the PIE level (small or large model)</p>

<p>Declaration at line 946 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility function for querying and setting code model

### getCodeModel {#ac5b21bb0de463009ae5702aa73a83657}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CodeModel::Model &gt; Module::getCodeModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the code model (tiny, small, kernel, medium or large model)</p>

<p>Declaration at line 954 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 647 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#aaf2ff3020b311fe77e208f80459017aa">llvm::setGlobalVariableLargeSection</a>.</p>

</div>
</div>

### setCodeModel {#a25f29d00aa5f0cb6f79645a6225a043e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setCodeModel (<a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> CL)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the code model (tiny, small, kernel, medium or large)</p>

<p>Declaration at line 957 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 657 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility function for querying and setting the large data threshold

### getLargeDataThreshold {#a565dd703d30bab94924184733ec7bf84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; Module::getLargeDataThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the code model (tiny, small, kernel, medium or large model)</p>

<p>Declaration at line 965 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 665 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setLargeDataThreshold {#aa72b06563b1a998b7e291d78eeb131d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setLargeDataThreshold (uint64_t Threshold)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set the code model (tiny, small, kernel, medium or large)</p>

<p>Declaration at line 968 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 675 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility functions for querying and setting PGO summary

### getProfileSummary {#afcbde5203650f49a414283674b9792fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Metadata * Module::getProfileSummary (bool IsCS)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns profile summary metadata.</p>


<p>When IsCS is true, use the context sensitive profile summary.</p>


<p>Declaration at line 979 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 689 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setProfileSummary {#a6bf85925c8356b5aecf975112632e37a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setProfileSummary (<a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> * M, <a href="/web-llvm/docs/api/classes/llvm/profilesummary/#aa5aa682b3904e88749fa973b3da370c2">ProfileSummary::Kind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attach profile summary metadata to this module.</p>

<p>Declaration at line 975 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 682 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Utility functions for querying and setting the build SDK version

### getSDKVersion {#ae31b39ce1f886a3280a0297dcfb66930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VersionTuple Module::getSDKVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the build SDK version metadata.</p>


<p>An empty version is returned if no such metadata is attached.</p>


<p>Declaration at line 1041 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 861 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

### setSDKVersion {#af9b60984528010b0f885be0b81aa3296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Module::setSDKVersion (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/versiontuple">VersionTuple</a> &amp; V)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Attach a build SDK version metadata to this module.</p>

<p>Declaration at line 1036 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a>, definition at line 832 of file <a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/module-h">Module.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/asmwriter-cpp">AsmWriter.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/llvmcontextimpl-cpp">LLVMContextImpl.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/sandboxir/module-cpp">Module.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
