---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/anonymous-wholeprogramdevirt-cpp-/devirtmodule
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `DevirtModule` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{WholeProgramDevirt.cpp}::DevirtModule { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a> (Module &amp;M, function_ref&lt; AAResults &amp;(Function &amp;)&gt; AARGetter, function_ref&lt; OptimizationRemarkEmitter &amp;(Function *)&gt; OREGetter, function_ref&lt; DominatorTree &amp;(Function &amp;)&gt; LookupDomTree, ModuleSummaryIndex *ExportSummary, const ModuleSummaryIndex *ImportSummary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a815de9bbe3e7039e1fc916f2ea7b0">areRemarksEnabled</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">scanTypeTestUsers</a> (Function *TypeTestFunc, DenseMap&lt; Metadata *, std::set&lt; TypeMemberInfo &gt; &gt; &amp;TypeIdMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a> (Function *TypeCheckedLoadFunc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a5262b6225fdc05cfea242647c56db6">buildTypeIdentifierMap</a> (std::vector&lt; VTableBits &gt; &amp;Bits, DenseMap&lt; Metadata *, std::set&lt; TypeMemberInfo &gt; &gt; &amp;TypeIdMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfe26739ec5c54c0e4039d8e5d2d4a01">tryFindVirtualCallTargets</a> (std::vector&lt; VirtualCallTarget &gt; &amp;TargetsForSlot, const std::set&lt; TypeMemberInfo &gt; &amp;TypeMemberInfos, uint64_t ByteOffset, ModuleSummaryIndex *ExportSummary)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a> (VTableSlotInfo &amp;SlotInfo, Constant *TheFn, bool &amp;IsExported)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9f4748bfea60c7f38b8a1f4357b0150">trySingleImplDevirt</a> (ModuleSummaryIndex *ExportSummary, MutableArrayRef&lt; VirtualCallTarget &gt; TargetsForSlot, VTableSlotInfo &amp;SlotInfo, WholeProgramDevirtResolution *Res)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f2e0d9db7a457156c4377449c2e0606">applyICallBranchFunnel</a> (VTableSlotInfo &amp;SlotInfo, Constant *JT, bool &amp;IsExported)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad722656aa63d87c356ec659228865f65">tryICallBranchFunnel</a> (MutableArrayRef&lt; VirtualCallTarget &gt; TargetsForSlot, VTableSlotInfo &amp;SlotInfo, WholeProgramDevirtResolution *Res, VTableSlot Slot)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37fe954e0b01502acccf9b29943e9164">tryEvaluateFunctionsWithArgs</a> (MutableArrayRef&lt; VirtualCallTarget &gt; TargetsForSlot, ArrayRef&lt; uint64_t &gt; Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ccdbdd6f0c159f0233236dca7125328">applyUniformRetValOpt</a> (CallSiteInfo &amp;CSInfo, StringRef FnName, uint64_t TheRetVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1cb89e56d053bfe29124d830ef0ac94">tryUniformRetValOpt</a> (MutableArrayRef&lt; VirtualCallTarget &gt; TargetsForSlot, CallSiteInfo &amp;CSInfo, WholeProgramDevirtResolution::ByArg *Res)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e09219bfe5f56b557db89d9afbbbb45">getGlobalName</a> (VTableSlot Slot, ArrayRef&lt; uint64_t &gt; Args, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb57635b61137e0e4950de608225318f">shouldExportConstantsAsAbsoluteSymbols</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16a470a2b40fa6e28a35af849806450b">exportGlobal</a> (VTableSlot Slot, ArrayRef&lt; uint64_t &gt; Args, StringRef Name, Constant *C)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56e23527438631272da8c1e486c84135">exportConstant</a> (VTableSlot Slot, ArrayRef&lt; uint64_t &gt; Args, StringRef Name, uint32_t Const, uint32_t &amp;Storage)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeaa8e35cfb5c615f98eeaeeb9ab62788">importGlobal</a> (VTableSlot Slot, ArrayRef&lt; uint64_t &gt; Args, StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8d4761888824dc65c66c5a0997abb9">importConstant</a> (VTableSlot Slot, ArrayRef&lt; uint64_t &gt; Args, StringRef Name, IntegerType *IntTy, uint32_t Storage)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bfa9a83403d3c8c34a0079470468533">getMemberAddr</a> (const TypeMemberInfo *M)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f6dd5dcbaeca0d82159a5094b742672">applyUniqueRetValOpt</a> (CallSiteInfo &amp;CSInfo, StringRef FnName, bool IsOne, Constant *UniqueMemberAddr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc69b6c381a3b54539a9eff3e7d1d3f">tryUniqueRetValOpt</a> (unsigned BitWidth, MutableArrayRef&lt; VirtualCallTarget &gt; TargetsForSlot, CallSiteInfo &amp;CSInfo, WholeProgramDevirtResolution::ByArg *Res, VTableSlot Slot, ArrayRef&lt; uint64_t &gt; Args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22eb17ec5325526a386b40274ca84b63">applyVirtualConstProp</a> (CallSiteInfo &amp;CSInfo, StringRef FnName, Constant *Byte, Constant *Bit)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a> (MutableArrayRef&lt; VirtualCallTarget &gt; TargetsForSlot, VTableSlotInfo &amp;SlotInfo, WholeProgramDevirtResolution *Res, VTableSlot Slot)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cea94e94a75a84e5e5c0a649d1ef78">rebuildGlobal</a> (VTableBits &amp;B)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> (VTableSlot Slot, VTableSlotInfo &amp;SlotInfo)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30b56b2eb82bcd9691aa8ff48dde9a79">removeRedundantTypeTests</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a363028d7884038c73a4f3f2474530c33">run</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abddae483b27571fa57808aafa478d400">M</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a309a12b17b50b9b518ce1c76e251b894">AARGetter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14bdc91f8219d2ae59b20891017c6124">LookupDomTree</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c1c90daa7cee721caf0a024acf476d8">ExportSummary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44979e666f893da85650c85e378f0d3b">ImportSummary</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c0b0b7c223820064123bb4331e720cb">Int8Ty</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad262e7a3ecc8ddfc8226681b3aab8e2a">Int8PtrTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bbfced28db32119e07389fbe4626dce">Int32Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc0c8843b968e7f4e48fa682f26d17b">Int64Ty</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d63a376b59663fe5c4ac3285ca817cc">IntPtrTy</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/arraytype">ArrayType</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab74d378fee9ca19018b5edb817735067">Int8Arr0Ty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Sizeless array type, used for imported vtables. <a href="#ab74d378fee9ca19018b5edb817735067">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mapvector">MapVector</a>&lt; <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad56ef914945055b7a497b9f579e4bbe3">CallSlots</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallptrset">SmallPtrSet</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab101828488043f0890c03bad78bef1fe">OptimizedCalls</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *, 8 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af79523d3d2b675350b340fe3e7703633">CallsWithPtrAuthBundleRemoved</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; <a href="/web-llvm/docs/api/classes/llvm/callinst">CallInst</a> *, unsigned &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a381261e9d8901b0442018a690a73d2d1">NumUnsafeUsesForTypeTest</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/patternlist">PatternList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a592e91233e1b2b7daf941dee9b9267">FunctionsToSkip</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/structs/llvm/valueinfo">ValueInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf7542694401439f2f600b3890c8831">lookUpFunctionValueInfo</a> (Function *TheFn, ModuleSummaryIndex *ExportSummary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91cdd27c8deb2678870c535c9205fcc4">mustBeUnreachableFunction</a> (Function *const F, ModuleSummaryIndex *ExportSummary)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf63c9ebc3de0773617afcdbd321f43b">runForTesting</a> (Module &amp;M, function_ref&lt; AAResults &amp;(Function &amp;)&gt; AARGetter, function_ref&lt; OptimizationRemarkEmitter &amp;(Function *)&gt; OREGetter, function_ref&lt; DominatorTree &amp;(Function &amp;)&gt; LookupDomTree)</td>
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


<p>Definition at line 575 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DevirtModule() {#ac7da757da2141faa2d1d0c429bd4e1e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous{WholeProgramDevirt.cpp}::DevirtModule::DevirtModule (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; AARGetter, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)&gt; OREGetter, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupDomTree, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ImportSummary)</td>
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



<p>Definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a309a12b17b50b9b518ce1c76e251b894">AARGetter</a>, <a href="#a17a815de9bbe3e7039e1fc916f2ea7b0">areRemarksEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8c1c90daa7cee721caf0a024acf476d8">ExportSummary</a>, <a href="#a3a592e91233e1b2b7daf941dee9b9267">FunctionsToSkip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a73257f51950d9ea50955e3fb9c724a25">llvm::get</a>, <a href="#a44979e666f893da85650c85e378f0d3b">ImportSummary</a>, <a href="#a2bbfced28db32119e07389fbe4626dce">Int32Ty</a>, <a href="#acfc0c8843b968e7f4e48fa682f26d17b">Int64Ty</a>, <a href="#ab74d378fee9ca19018b5edb817735067">Int8Arr0Ty</a>, <a href="#ad262e7a3ecc8ddfc8226681b3aab8e2a">Int8PtrTy</a>, <a href="#a3c0b0b7c223820064123bb4331e720cb">Int8Ty</a>, <a href="#a9d63a376b59663fe5c4ac3285ca817cc">IntPtrTy</a>, <a href="#a14bdc91f8219d2ae59b20891017c6124">LookupDomTree</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a4acfa59172dc9825ef4c1362be8d31e7">SkipFunctionNames</a>.</p>


<p>Referenced by <a href="#adf63c9ebc3de0773617afcdbd321f43b">runForTesting</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### applyICallBranchFunnel() {#a8f2e0d9db7a457156c4377449c2e0606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::applyICallBranchFunnel (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &amp; SlotInfo, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * JT, bool &amp; IsExported)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a39d3d23a084c4544ee5903203db10e8a">llvm::append_range</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad027ea8803d83ee19b9a2e13aec6d655">llvm::CallBase::args</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ade14b26f3679a66f6b13ac9e92c19493">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::ConstCSInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a83a294111af6d4412163b209725ca556">llvm::StringRef::contains</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a49c408a438b1844778bc59b1e4bb00c9">llvm::IRBuilderBase::CreateInvoke</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ac35a781883c4aa63cacc171e98640500">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::CSInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/attributeset/#ae8ed437b15a7ca943716e5284a9cb9a6">llvm::AttributeSet::get</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ae0c55761fce39dd71617690b04385193">llvm::CallBase::getAttributes</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#afac5b39bcbb90d660f83d9b4bd8c6d95">llvm::CallBase::getCaller</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a3ff92cec76009e859cb0c419d6e8ba5f">llvm::CallBase::getCallingConv</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4c319db4fe05c27cfe55bd133a87414d">llvm::Function::getFnAttribute</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ac3c35bd078a268a207f607d0f57dadba">llvm::CallBase::getFunctionType</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#ad65790aa94dd4678a1d339d8304e1965">llvm::FunctionType::getReturnType</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a968930aea9d9efa8d46dd890fce75643">llvm::Attribute::getValueAsString</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#ad262e7a3ecc8ddfc8226681b3aab8e2a">Int8PtrTy</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#adf4d22686e85732b2fef71e3c45531c6">llvm::Attribute::isValid</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#aa9d770048c7ab9e08222a50b7bc1be1c">llvm::FunctionType::isVarArg</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#a8dc558dee9c54b788dd559fed3c0a39a">llvm::FunctionType::params</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a9da3b29e8e71b9be4645874e1721207a">llvm::CallBase::setAttributes</a> and <a href="/web-llvm/docs/api/classes/llvm/callbase/#a0851b4de29686e9c3918449b054cfada">llvm::CallBase::setCallingConv</a>.</p>


<p>Referenced by <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> and <a href="#ad722656aa63d87c356ec659228865f65">tryICallBranchFunnel</a>.</p>

</div>
</div>

### applySingleImplDevirt() {#a21ea18f2c76b35d0985927f6ffebf9ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::applySingleImplDevirt (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &amp; SlotInfo, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * TheFn, bool &amp; IsExported)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#af79523d3d2b675350b340fe3e7703633">CallsWithPtrAuthBundleRemoved</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a193847098793cdbab306803186676899">Cond</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ade14b26f3679a66f6b13ac9e92c19493">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::ConstCSInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a932f08e32ea37a7019902ee467beb268">llvm::IRBuilderBase::CreateBitCast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a6ef1729b04a4fbd6c6f27787cdd0e813">llvm::IRBuilderBase::CreateICmpNE</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#aba565f72261aa7d6207da89db949d991">llvm::MDBuilder::createLikelyBranchWeights</a>, <a href="/web-llvm/docs/api/classes/llvm/mdbuilder/#ae609aeb09c2b1c9f03fb90228654b281">llvm::MDBuilder::createUnlikelyBranchWeights</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ac35a781883c4aa63cacc171e98640500">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::CSInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a852c15f62fd7d543b4bde0c6010ba7ab">DevirtCheckMode</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a0e65aef39009b683d7acb5884ae47421aad98505ec3c6cabbb406c37037410854">Fallback</a>, <a href="#a3a592e91233e1b2b7daf941dee9b9267">FunctionsToSkip</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a2b1ae7cf1bafdd43d1fee4c6ad0a2913">llvm::CallBase::getCalledFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a8d13199cbf4d080d3b5dcf330dad5d2c">llvm::CallBase::getCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a4b8faae4ff9e7434a1d226d03d15dcd2">llvm::Instruction::getDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/ilist-node-impl/#af719fc783be6589465137d997701a432">llvm::ilist_node_impl&lt; OptionsT &gt;::getIterator</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#a23ab5f34fb7b9476d45da0102ecbfae6">llvm::CallBase::getOperandBundle</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/namespaces/anonymous-wholeprogramdevirt-cpp-/#adee1dcccb7fdefb3e52c1aeaab313fee">anonymous{WholeProgramDevirt.cpp}::NumDevirtCalls</a>, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext/#a44d727ac5fccf852bfb2bae3e06adc9cadd4d7ff61cc637f50c78417fc8e67c15">llvm::LLVMContext::OB_ptrauth</a>, <a href="#ab101828488043f0890c03bad78bef1fe">OptimizedCalls</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad82786d29c116d0bf5131f654d51e681">llvm::CallBase::removeOperandBundle</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a3ab5fc45117b450e8bb04e564cb6e5f2">llvm::Value::replaceAllUsesWith</a>, <a href="/web-llvm/docs/api/classes/llvm/callbase/#ad70fe60b7ed052c6a74863944b518251">llvm::CallBase::setCalledOperand</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ae8f5bf5cc06f696b52c709677df00fbf">llvm::Instruction::setDebugLoc</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ace45cae6925c65e9d6916e09dd5b17cc">llvm::IRBuilderBase::SetInsertPoint</a>, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a9247a212ea89acc9573fa7e7f557eaba">llvm::Instruction::setMetadata</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad957413955739c91204c96e33e0cc933">llvm::SplitBlockAndInsertIfThen</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#a6c6af867b9eca0a16600b50e31df0e33">llvm::Constant::stripPointerCasts</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a0e65aef39009b683d7acb5884ae47421a178e499decd0c21272bc34e4b3056eab">Trap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a84163d559062da6b736ab943644e0a16">llvm::versionCallSite</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#acbc86a288e23ad77b686ef73a834a4c6">WholeProgramDevirtCutoff</a>.</p>


<p>Referenced by <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> and <a href="#ae9f4748bfea60c7f38b8a1f4357b0150">trySingleImplDevirt</a>.</p>

</div>
</div>

### applyUniformRetValOpt() {#a1ccdbdd6f0c159f0233236dca7125328}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::applyUniformRetValOpt (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a> &amp; CSInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, uint64_t TheRetVal)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#a4c34f9725a50f48351c04484e7c151e0">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::CallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#af92dbd7f8b58ee509f6d50304aadf83b">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::markDevirt</a>, <a href="#ab101828488043f0890c03bad78bef1fe">OptimizedCalls</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a> and <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>.</p>


<p>Referenced by <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> and <a href="#ae1cb89e56d053bfe29124d830ef0ac94">tryUniformRetValOpt</a>.</p>

</div>
</div>

### applyUniqueRetValOpt() {#a4f6dd5dcbaeca0d82159a5094b742672}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::applyUniqueRetValOpt (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a> &amp; CSInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, bool IsOne, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * UniqueMemberAddr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 701 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#a4c34f9725a50f48351c04484e7c151e0">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::CallSites</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#af92dbd7f8b58ee509f6d50304aadf83b">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::markDevirt</a>, <a href="#ab101828488043f0890c03bad78bef1fe">OptimizedCalls</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a> and <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>.</p>


<p>Referenced by <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> and <a href="#a4dc69b6c381a3b54539a9eff3e7d1d3f">tryUniqueRetValOpt</a>.</p>

</div>
</div>

### applyVirtualConstProp() {#a22eb17ec5325526a386b40274ca84b63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::applyVirtualConstProp (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a> &amp; CSInfo, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> FnName, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Byte, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * Bit)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#a4c34f9725a50f48351c04484e7c151e0">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::CallSites</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="#a3c0b0b7c223820064123bb4331e720cb">Int8Ty</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#af92dbd7f8b58ee509f6d50304aadf83b">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::markDevirt</a>, <a href="#ab101828488043f0890c03bad78bef1fe">OptimizedCalls</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a> and <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>.</p>


<p>Referenced by <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> and <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### areRemarksEnabled() {#a17a815de9bbe3e7039e1fc916f2ea7b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::areRemarksEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 636 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/dwarf-linker/#a463a58e257d5f6fb2c39eb9a2474fc24ac2e06fc138163b7095fa483616a0a47a">llvm::dwarf_linker::DebugLoc</a> and <a href="#abddae483b27571fa57808aafa478d400">M</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>.</p>

</div>
</div>

### buildTypeIdentifierMap() {#a3a5262b6225fdc05cfea242647c56db6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::buildTypeIdentifierMap (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/vtablebits">VTableBits</a> &gt; &amp; Bits, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/typememberinfo">TypeMemberInfo</a> &gt; &gt; &amp; TypeIdMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 643 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvariable/#a0698d5bcabbfbca4f56a9d7a81cecb25">llvm::GlobalVariable::getInitializer</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#aef569d822dbf572ae71954d6831ce8a9">llvm::GlobalObject::getMetadata</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#a0344a49526443edf90cc0aef3abd3337">llvm::Value::getType</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a32e606ac4c88f71f14212e42b808e7f4">llvm::GlobalValue::isDeclaration</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### exportConstant() {#a56e23527438631272da8c1e486c84135}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::exportConstant (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, uint32_t Const, uint32_t &amp; Storage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 688 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a16a470a2b40fa6e28a35af849806450b">exportGlobal</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a02560cda155aaed54314383bed827d60">llvm::ConstantExpr::getIntToPtr</a>, <a href="#a2bbfced28db32119e07389fbe4626dce">Int32Ty</a>, <a href="#ad262e7a3ecc8ddfc8226681b3aab8e2a">Int8PtrTy</a> and <a href="#afb57635b61137e0e4950de608225318f">shouldExportConstantsAsAbsoluteSymbols</a>.</p>


<p>Referenced by <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### exportGlobal() {#a16a470a2b40fa6e28a35af849806450b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::exportGlobal (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * C)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 686 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a8a638534b520f72ab7f2c886da739a6c">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="#a3e09219bfe5f56b557db89d9afbbbb45">getGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="#a3c0b0b7c223820064123bb4331e720cb">Int8Ty</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa242d8ab89216c14beab812e07009b2a">llvm::GlobalValue::setVisibility</a>.</p>


<p>Referenced by <a href="#a56e23527438631272da8c1e486c84135">exportConstant</a> and <a href="#a4dc69b6c381a3b54539a9eff3e7d1d3f">tryUniqueRetValOpt</a>.</p>

</div>
</div>

### getGlobalName() {#a3e09219bfe5f56b557db89d9afbbbb45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string DevirtModule::getGlobalName (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 678 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a16a470a2b40fa6e28a35af849806450b">exportGlobal</a>, <a href="#aeaa8e35cfb5c615f98eeaeeb9ab62788">importGlobal</a>, <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> and <a href="#ad722656aa63d87c356ec659228865f65">tryICallBranchFunnel</a>.</p>

</div>
</div>

### getMemberAddr() {#a3bfa9a83403d3c8c34a0079470468533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DevirtModule::getMemberAddr (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/typememberinfo">TypeMemberInfo</a> * M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 699 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#ae4d4490a35a575d97166684fb15f8662">llvm::ConstantExpr::getGetElementPtr</a>, <a href="#acfc0c8843b968e7f4e48fa682f26d17b">Int64Ty</a>, <a href="#a3c0b0b7c223820064123bb4331e720cb">Int8Ty</a> and <a href="#abddae483b27571fa57808aafa478d400">M</a>.</p>


<p>Referenced by <a href="#ad722656aa63d87c356ec659228865f65">tryICallBranchFunnel</a> and <a href="#a4dc69b6c381a3b54539a9eff3e7d1d3f">tryUniqueRetValOpt</a>.</p>

</div>
</div>

### importConstant() {#a1b8d4761888824dc65c66c5a0997abb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DevirtModule::importConstant (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, <a href="/web-llvm/docs/api/classes/llvm/integertype">IntegerType</a> * IntTy, uint32_t Storage)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 695 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/constantasmetadata/#a4c720c398a263087e00d7358b05636d5">llvm::ConstantAsMetadata::get</a>, <a href="/web-llvm/docs/api/classes/llvm/mdnode/#a7d10a7b9b7f40b04d27ed97c38ea1950">llvm::MDNode::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a652380f28d1a7011e05d0787b6024d48">llvm::ConstantExpr::getPtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a1f496e54accb2cbe919fb456cb703f1a">llvm::GlobalObject::hasMetadata</a>, <a href="#aeaa8e35cfb5c615f98eeaeeb9ab62788">importGlobal</a>, <a href="#a9d63a376b59663fe5c4ac3285ca817cc">IntPtrTy</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a338590123630c357df6340c38d066572">llvm::GlobalObject::setMetadata</a> and <a href="#afb57635b61137e0e4950de608225318f">shouldExportConstantsAsAbsoluteSymbols</a>.</p>


<p>Referenced by <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a>.</p>

</div>
</div>

### importGlobal() {#aeaa8e35cfb5c615f98eeaeeb9ab62788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Constant * DevirtModule::importGlobal (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Args, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 693 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a3e09219bfe5f56b557db89d9afbbbb45">getGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="#ab74d378fee9ca19018b5edb817735067">Int8Arr0Ty</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a> and <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aa242d8ab89216c14beab812e07009b2a">llvm::GlobalValue::setVisibility</a>.</p>


<p>Referenced by <a href="#a1b8d4761888824dc65c66c5a0997abb9">importConstant</a> and <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a>.</p>

</div>
</div>

### importResolution() {#a2571433d1b220fb84bfcb7584002cb02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::importResolution (<a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &amp; SlotInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 718 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a8f2e0d9db7a457156c4377449c2e0606">applyICallBranchFunnel</a>, <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a>, <a href="#a1ccdbdd6f0c159f0233236dca7125328">applyUniformRetValOpt</a>, <a href="#a4f6dd5dcbaeca0d82159a5094b742672">applyUniqueRetValOpt</a>, <a href="#a22eb17ec5325526a386b40274ca84b63">applyVirtualConstProp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208ac74c33fab6fb30be2bf7db1f86b0853d">llvm::WholeProgramDevirtResolution::BranchFunnel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ade14b26f3679a66f6b13ac9e92c19493">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::ConstCSInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a3e09219bfe5f56b557db89d9afbbbb45">getGlobalName</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#a1b8d4761888824dc65c66c5a0997abb9">importConstant</a>, <a href="#aeaa8e35cfb5c615f98eeaeeb9ab62788">importGlobal</a>, <a href="#a44979e666f893da85650c85e378f0d3b">ImportSummary</a>, <a href="#a2bbfced28db32119e07389fbe4626dce">Int32Ty</a>, <a href="#a3c0b0b7c223820064123bb4331e720cb">Int8Ty</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a1c0a0ec1654585583572f16e799176dc">llvm::WholeProgramDevirtResolution::ResByArg</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208a05ee7e7ff849410d68ccfd73e177387f">llvm::WholeProgramDevirtResolution::SingleImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ab97c12959c5cc7b46b115da7e1ac5047">llvm::WholeProgramDevirtResolution::SingleImplName</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a11bddbadb47e3bd7803ded5d4f4248fc">llvm::WholeProgramDevirtResolution::TheKind</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea635d252c06de8cd5c96ebcf3d8989ccf">llvm::WholeProgramDevirtResolution::ByArg::UniformRetVal</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea8bf72562c0a17a25f9e07863e68543b3">llvm::WholeProgramDevirtResolution::ByArg::UniqueRetVal</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea7382e969306ae2118ae88db2a241e833">llvm::WholeProgramDevirtResolution::ByArg::VirtualConstProp</a> and <a href="/web-llvm/docs/api/structs/llvm/typeidsummary/#a01d5759cee861fcfca3b26ff5927e83c">llvm::TypeIdSummary::WPDRes</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### rebuildGlobal() {#a12cea94e94a75a84e5e5c0a649d1ef78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::rebuildGlobal (<a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/vtablebits">VTableBits</a> &amp; B)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ab102f0f12dd38aeea5906b1d80c792ff">llvm::alignTo</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/classes/llvm/globalalias/#a8a638534b520f72ab7f2c886da739a6c">llvm::GlobalAlias::create</a>, <a href="/web-llvm/docs/api/classes/llvm/constantdataarray/#a4a1000e5803e731e9dcc572042a98a0b">llvm::ConstantDataArray::get</a>, <a href="/web-llvm/docs/api/classes/llvm/constantstruct/#ab154936bb49a215c32bdbd18254fc477">llvm::ConstantStruct::getAnon</a>, <a href="/web-llvm/docs/api/classes/llvm/constantexpr/#a0fbdc8f9ebcc506b52a9f5c82feb363e">llvm::ConstantExpr::getInBoundsGetElementPtr</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca04ed141708c0fd16723d212502b046ae">llvm::GlobalValue::PrivateLinkage</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/inlineorder-cpp/#a7ee6f0cb51c3b9056199e9a0001fe8c3a6f6cb72d544962fa333e2e34ce64f719">Size</a> and <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### removeRedundantTypeTests() {#a30b56b2eb82bcd9691aa8ff48dde9a79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::removeRedundantTypeTests ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 722 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/constantint/#a82dbbd8e3688b0bc1eedb338864d0d0c">llvm::ConstantInt::getTrue</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a> and <a href="#a381261e9d8901b0442018a690a73d2d1">NumUnsafeUsesForTypeTest</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### run() {#a363028d7884038c73a4f3f2474530c33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 724 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#a2e38c85003a042421cde1647632d0b72">A</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="#a3a5262b6225fdc05cfea242647c56db6">buildTypeIdentifierMap</a>, <a href="#ad56ef914945055b7a497b9f579e4bbe3">CallSlots</a>, <a href="#af79523d3d2b675350b340fe3e7703633">CallsWithPtrAuthBundleRemoved</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/adt/genericcycleimpl-h/#ad78e062f62e0d6e453941fb4ca843e4d">DEBUG_TYPE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/densemapbase/#a49c487a9395a6c384be8544cfb2cfccf">llvm::DenseMapBase&lt; DerivedT, KeyT, ValueT, KeyInfoT, BucketT &gt;::empty</a>, <a href="/web-llvm/docs/api/classes/llvm/globalobject/#a9d88e21e9caa53945e903fd8c8700b4f">llvm::GlobalObject::eraseMetadata</a>, <a href="#a8c1c90daa7cee721caf0a024acf476d8">ExportSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#aa1731508126b77035ab3ba9d71d5374b">llvm::Intrinsic::getDeclarationIfExists</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>, <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a>, <a href="#a44979e666f893da85650c85e378f0d3b">ImportSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="#a12cea94e94a75a84e5e5c0a649d1ef78">rebuildGlobal</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>, <a href="#a30b56b2eb82bcd9691aa8ff48dde9a79">removeRedundantTypeTests</a>, <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a>, <a href="#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">scanTypeTestUsers</a>, <a href="#abfe26739ec5c54c0e4039d8e5d2d4a01">tryFindVirtualCallTargets</a>, <a href="#ad722656aa63d87c356ec659228865f65">tryICallBranchFunnel</a>, <a href="#ae9f4748bfea60c7f38b8a1f4357b0150">trySingleImplDevirt</a>, <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a9d7de807ebdfe1819df3ff6cb0f16158">llvm::Value::use_empty</a>.</p>

</div>
</div>

### scanTypeCheckedLoadUsers() {#a021e32e2bf67f331d9384a162dc402c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::scanTypeCheckedLoadUsers (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * TypeCheckedLoadFunc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 641 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="#ad56ef914945055b7a497b9f579e4bbe3">CallSlots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aada1d6d8de104a5cd1cb9a02c676cc6c">llvm::IRBuilderBase::CreateAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#ab086c5b9f9563eda0cdd703f454e041e">llvm::IRBuilderBase::CreateCall</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a53541ed6f92b18419f937f1f969aa0f6">llvm::IRBuilderBase::CreateIntToPtr</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a9b01712e5f196d6d3d021ef23aad50e4">llvm::IRBuilderBase::CreateLoad</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5b416a8603ccb844165c8df22454ac05">llvm::IRBuilderBase::CreatePtrAdd</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#aae2c1bf70058f3665edaec525457030c">llvm::IRBuilderBase::CreatePtrToInt</a>, <a href="/web-llvm/docs/api/classes/llvm/irbuilderbase/#a5253081f40ffcad9c0e8ba6a5c437006">llvm::IRBuilderBase::CreateSExt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a8148654fcf3528ef06d7a0e28b57b952">llvm::findDevirtualizableCallsForTypeCheckedLoad</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/hexagon/hexagoncommongep-cpp/#ad532e8710e50302e0a376b61c91fa91d">GEP</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a4d0a7baab8d078065b2de10e3460892a">llvm::Function::getIntrinsicID</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="#a2bbfced28db32119e07389fbe4626dce">Int32Ty</a>, <a href="#ad262e7a3ecc8ddfc8226681b3aab8e2a">Int8PtrTy</a>, <a href="#a9d63a376b59663fe5c4ac3285ca817cc">IntPtrTy</a>, <a href="#a14bdc91f8219d2ae59b20891017c6124">LookupDomTree</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="#a381261e9d8901b0442018a690a73d2d1">NumUnsafeUsesForTypeTest</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### scanTypeTestUsers() {#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::scanTypeTestUsers (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * TypeTestFunc, <a href="/web-llvm/docs/api/classes/llvm/densemap">DenseMap</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/metadata">Metadata</a> *, std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/typememberinfo">TypeMemberInfo</a> &gt; &gt; &amp; TypeIdMap)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 639 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/groups/arcopt/#ga9c9cf6ad55eb23d77d083a184e416c09">Call</a>, <a href="#ad56ef914945055b7a497b9f579e4bbe3">CallSlots</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#ad9a3c7bc26b130377bbafc170b5f88a2">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#af88f364cd09c715e8853a1027c7180ef">llvm::findDevirtualizableCallsForTypeTest</a>, <a href="#a44979e666f893da85650c85e378f0d3b">ImportSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#a14bdc91f8219d2ae59b20891017c6124">LookupDomTree</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a3d2cdc4a0db233678e7141c9d6ea3419">llvm::make_early_inc_range</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/targetlibraryinfo-cpp/#aca185e6d0e9f423dbb24440206454872a11dbf501abf829b3ab7049c2d3a8a053">Ptr</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a66ff82a2443a6f422cd95843084564f6">llvm::TypeTestResolution::TheKind</a>, <a href="/web-llvm/docs/api/structs/llvm/typeidsummary/#a80bc0b8f2041f3a3839f393f1a6aae33">llvm::TypeIdSummary::TTRes</a>, <a href="/web-llvm/docs/api/structs/llvm/typetestresolution/#a3a09256c2858f8b38ce2b9481c528beda5826b981efc11834692037f016343fca">llvm::TypeTestResolution::Unsat</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#abf855b7cd63a0cd7f73759e396f280c9">llvm::Value::uses</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### shouldExportConstantsAsAbsoluteSymbols() {#afb57635b61137e0e4950de608225318f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::shouldExportConstantsAsAbsoluteSymbols ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 681 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/triple/#a83e907e55fa50e093caa96a0aff96201a456b64e26b8bcdbd8294689615d8a055">llvm::Triple::ELF</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a56e23527438631272da8c1e486c84135">exportConstant</a> and <a href="#a1b8d4761888824dc65c66c5a0997abb9">importConstant</a>.</p>

</div>
</div>

### tryEvaluateFunctionsWithArgs() {#a37fe954e0b01502acccf9b29943e9164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::tryEvaluateFunctionsWithArgs (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/virtualcalltarget">VirtualCallTarget</a> &gt; TargetsForSlot, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/evaluator/#aac9fd94c18d93885c8d947121ab9721e">llvm::Evaluator::EvaluateFunction</a>, <a href="/web-llvm/docs/api/classes/llvm/constant/#aa6574d526b3e38a28f688a7bb4325c2c">llvm::Constant::getNullValue</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>


<p>Referenced by <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### tryFindVirtualCallTargets() {#abfe26739ec5c54c0e4039d8e5d2d4a01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::tryFindVirtualCallTargets (std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/virtualcalltarget">VirtualCallTarget</a> &gt; &amp; TargetsForSlot, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> std::set&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/typememberinfo">TypeMemberInfo</a> &gt; &amp; TypeMemberInfos, uint64_t ByteOffset, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 648 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a8c1c90daa7cee721caf0a024acf476d8">ExportSummary</a>, <a href="#a3a592e91233e1b2b7daf941dee9b9267">FunctionsToSkip</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#afc0a5ead9186ecbdc82f6ebe331c25ee">llvm::getFunctionAtVTableOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#aaeceda7c9243e01a0888f44e2f3e7ba3">mustBeUnreachableFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/globalobject/#ab0fc6ae566ff5de33790f565a2abe49aa938bd45f40d238428b91833b85ecd22a">llvm::GlobalObject::VCallVisibilityPublic</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### tryICallBranchFunnel() {#ad722656aa63d87c356ec659228865f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DevirtModule::tryICallBranchFunnel (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/virtualcalltarget">VirtualCallTarget</a> &gt; TargetsForSlot, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &amp; SlotInfo, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> * Res, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#a84d3e2451a78887146475d5f1e687b74">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::AllCallSitesDevirted</a>, <a href="#a8f2e0d9db7a457156c4377449c2e0606">applyICallBranchFunnel</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208ac74c33fab6fb30be2bf7db1f86b0853d">llvm::WholeProgramDevirtResolution::BranchFunnel</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a72816be62cfd193f3cf78d55c0b29546">ClThreshold</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ade14b26f3679a66f6b13ac9e92c19493">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::ConstCSInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/basicblock/#a4a5b798214be930cf8e133c032ba0129">llvm::BasicBlock::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#aa04721251be00370fbde6d21f47fed1a">llvm::CallInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/function/#a05d7aedbbdc0fd24e8bc27edfe9c603f">llvm::Function::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/returninst/#a932710d4c1c965497707751eb4f7948f">llvm::ReturnInst::Create</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ac35a781883c4aa63cacc171e98640500">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::CSInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/functiontype/#af8be7844c269f201ebcee1e15048c378">llvm::FunctionType::get</a>, <a href="#a3e09219bfe5f56b557db89d9afbbbb45">getGlobalName</a>, <a href="#a3bfa9a83403d3c8c34a0079470468533">getMemberAddr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/intrinsic/#a0cff8be0190d8e20b7cf13646f34afa2">llvm::Intrinsic::getOrInsertDeclaration</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a6e20e76960d952de088354cbcd14c3ab">llvm::Type::getVoidTy</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca1511edd03e02d1f3dd277a3c6abf6ad5">llvm::GlobalValue::InternalLinkage</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>, <a href="/web-llvm/docs/api/classes/llvm/callinst/#ad682514c13f12f1a8d759d422fce6aefa2c3fc2c37f5db1dd777fad4e0d33ec7e">llvm::CallInst::TCK_MustTail</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a11bddbadb47e3bd7803ded5d4f4248fc">llvm::WholeProgramDevirtResolution::TheKind</a> and <a href="/web-llvm/docs/api/classes/llvm/triple/#a547abd13f7a3c063aa72c8192a868154a13d8ce5e71051718a537277c6a594062">llvm::Triple::x86_64</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### trySingleImplDevirt() {#ae9f4748bfea60c7f38b8a1f4357b0150}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::trySingleImplDevirt (<a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/virtualcalltarget">VirtualCallTarget</a> &gt; TargetsForSlot, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &amp; SlotInfo, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> * Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#aa8309e74a87a287dfe316da0535c4722">AddCalls</a>, <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a8c1c90daa7cee721caf0a024acf476d8">ExportSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#aedfa75f0c85c4aa85b257f066fbea57ca6c93794d7b99cd433e96c53eadb15a6e">llvm::GlobalValue::ExternalLinkage</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a9141f967188383108a69cc1b8ed3c195a7eade123587a08e674f2ca72e2443771">llvm::GlobalValue::HiddenVisibility</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>, <a href="/web-llvm/docs/api/classes/llvm/comdat/#ad8e5834e05be0104c4d64a3b4edeb51b">llvm::Comdat::setSelectionKind</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ae992643f8965e97ffbc353b083615208a05ee7e7ff849410d68ccfd73e177387f">llvm::WholeProgramDevirtResolution::SingleImpl</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#ab97c12959c5cc7b46b115da7e1ac5047">llvm::WholeProgramDevirtResolution::SingleImplName</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a11bddbadb47e3bd7803ded5d4f4248fc">llvm::WholeProgramDevirtResolution::TheKind</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### tryUniformRetValOpt() {#ae1cb89e56d053bfe29124d830ef0ac94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::tryUniformRetValOpt (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/virtualcalltarget">VirtualCallTarget</a> &gt; TargetsForSlot, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a> &amp; CSInfo, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg">WholeProgramDevirtResolution::ByArg</a> * Res)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a1ccdbdd6f0c159f0233236dca7125328">applyUniformRetValOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#ac1e46342d3d79c56fb3b498722a66f18">llvm::WholeProgramDevirtResolution::ByArg::Info</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#afd1a56d2f4d852e0d29acee4882cb321">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::isExported</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#acf13a890a40972d903f329d37c5ad98a">llvm::WholeProgramDevirtResolution::ByArg::TheKind</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea635d252c06de8cd5c96ebcf3d8989ccf">llvm::WholeProgramDevirtResolution::ByArg::UniformRetVal</a>.</p>


<p>Referenced by <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### tryUniqueRetValOpt() {#a4dc69b6c381a3b54539a9eff3e7d1d3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::tryUniqueRetValOpt (unsigned BitWidth, <a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/virtualcalltarget">VirtualCallTarget</a> &gt; TargetsForSlot, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo">CallSiteInfo</a> &amp; CSInfo, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg">WholeProgramDevirtResolution::ByArg</a> * Res, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; uint64_t &gt; Args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 703 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a4f6dd5dcbaeca0d82159a5094b742672">applyUniqueRetValOpt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="#a16a470a2b40fa6e28a35af849806450b">exportGlobal</a>, <a href="#a3bfa9a83403d3c8c34a0079470468533">getMemberAddr</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#ac1e46342d3d79c56fb3b498722a66f18">llvm::WholeProgramDevirtResolution::ByArg::Info</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/callsiteinfo/#afd1a56d2f4d852e0d29acee4882cb321">anonymous{WholeProgramDevirt.cpp}::CallSiteInfo::isExported</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#acf13a890a40972d903f329d37c5ad98a">llvm::WholeProgramDevirtResolution::ByArg::TheKind</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea8bf72562c0a17a25f9e07863e68543b3">llvm::WholeProgramDevirtResolution::ByArg::UniqueRetVal</a>.</p>


<p>Referenced by <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### tryVirtualConstProp() {#a85892c8cb2a8b36248f88a963d8a09ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::tryVirtualConstProp (<a href="/web-llvm/docs/api/classes/llvm/mutablearrayref">MutableArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirt/virtualcalltarget">VirtualCallTarget</a> &gt; TargetsForSlot, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo">VTableSlotInfo</a> &amp; SlotInfo, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution">WholeProgramDevirtResolution</a> * Res, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslot">VTableSlot</a> Slot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 711 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a309a12b17b50b9b518ce1c76e251b894">AARGetter</a>, <a href="#a22eb17ec5325526a386b40274ca84b63">applyVirtualConstProp</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a846137dc22b3b399b62f606698f3ed59">llvm::AreStatisticsEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a74a555cfcbd8d83cdbf785f01b88be68">llvm::WholeProgramDevirtResolution::ByArg::Bit</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#abee0df5f7f703bb4462aba260ba0a60f">llvm::BitWidth</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#afcc8593fe943d570b5a3fe549132fdff">llvm::WholeProgramDevirtResolution::ByArg::Byte</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a12a40c8120b4946a2935d16867203310">llvm::computeFunctionBodyMemoryAccess</a>, <a href="/web-llvm/docs/api/structs/anonymous-wholeprogramdevirt-cpp-/vtableslotinfo/#ade14b26f3679a66f6b13ac9e92c19493">anonymous{WholeProgramDevirt.cpp}::VTableSlotInfo::ConstCSInfo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="#a56e23527438631272da8c1e486c84135">exportConstant</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wholeprogramdevirt/#a8ab22ea42eaf359bb9eb8382c0afc616">llvm::wholeprogramdevirt::findLowestOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a30cdafd656830b62aa8070242810c405">llvm::Target::getName</a>, <a href="#a2bbfced28db32119e07389fbe4626dce">Int32Ty</a>, <a href="#a3c0b0b7c223820064123bb4331e720cb">Int8Ty</a>, <a href="#ad11a18045a208731346a76253ba5e79a">RemarksEnabled</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/#a1c0a0ec1654585583572f16e799176dc">llvm::WholeProgramDevirtResolution::ResByArg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wholeprogramdevirt/#adbbe3d32693c7f00b25a8574e596cde8">llvm::wholeprogramdevirt::setAfterReturnValues</a>, <a href="/web-llvm/docs/api/namespaces/llvm/wholeprogramdevirt/#aec5b7edd995ed899e28075c82b29b360">llvm::wholeprogramdevirt::setBeforeReturnValues</a>, <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#acf13a890a40972d903f329d37c5ad98a">llvm::WholeProgramDevirtResolution::ByArg::TheKind</a>, <a href="#a37fe954e0b01502acccf9b29943e9164">tryEvaluateFunctionsWithArgs</a>, <a href="#ae1cb89e56d053bfe29124d830ef0ac94">tryUniformRetValOpt</a>, <a href="#a4dc69b6c381a3b54539a9eff3e7d1d3f">tryUniqueRetValOpt</a> and <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtresolution/byarg/#a73c235c3b51fc129ec890391feccd47ea7382e969306ae2118ae88db2a241e833">llvm::WholeProgramDevirtResolution::ByArg::VirtualConstProp</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AARGetter {#a309a12b17b50b9b518ce1c76e251b894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;AAResults &amp;(Function &amp;)&gt; anonymous{WholeProgramDevirt.cpp}::DevirtModule::AARGetter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 577 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#adf63c9ebc3de0773617afcdbd321f43b">runForTesting</a> and <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### CallSlots {#ad56ef914945055b7a497b9f579e4bbe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MapVector&lt;VTableSlot, VTableSlotInfo&gt; anonymous{WholeProgramDevirt.cpp}::DevirtModule::CallSlots</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 596 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a363028d7884038c73a4f3f2474530c33">run</a>, <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a> and <a href="#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">scanTypeTestUsers</a>.</p>

</div>
</div>

### CallsWithPtrAuthBundleRemoved {#af79523d3d2b675350b340fe3e7703633}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;CallBase *, 8&gt; anonymous{WholeProgramDevirt.cpp}::DevirtModule::CallsWithPtrAuthBundleRemoved</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 605 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a> and <a href="#a363028d7884038c73a4f3f2474530c33">run</a>.</p>

</div>
</div>

### ExportSummary {#a8c1c90daa7cee721caf0a024acf476d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleSummaryIndex* anonymous{WholeProgramDevirt.cpp}::DevirtModule::ExportSummary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 580 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#addf7542694401439f2f600b3890c8831">lookUpFunctionValueInfo</a>, <a href="#a91cdd27c8deb2678870c535c9205fcc4">mustBeUnreachableFunction</a>, <a href="#a363028d7884038c73a4f3f2474530c33">run</a>, <a href="#abfe26739ec5c54c0e4039d8e5d2d4a01">tryFindVirtualCallTargets</a> and <a href="#ae9f4748bfea60c7f38b8a1f4357b0150">trySingleImplDevirt</a>.</p>

</div>
</div>

### FunctionsToSkip {#a3a592e91233e1b2b7daf941dee9b9267}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PatternList anonymous{WholeProgramDevirt.cpp}::DevirtModule::FunctionsToSkip</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 616 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a>, <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a> and <a href="#abfe26739ec5c54c0e4039d8e5d2d4a01">tryFindVirtualCallTargets</a>.</p>

</div>
</div>

### ImportSummary {#a44979e666f893da85650c85e378f0d3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ModuleSummaryIndex* anonymous{WholeProgramDevirt.cpp}::DevirtModule::ImportSummary</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 581 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a>, <a href="#a363028d7884038c73a4f3f2474530c33">run</a> and <a href="#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">scanTypeTestUsers</a>.</p>

</div>
</div>

### Int32Ty {#a2bbfced28db32119e07389fbe4626dce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{WholeProgramDevirt.cpp}::DevirtModule::Int32Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 585 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a56e23527438631272da8c1e486c84135">exportConstant</a>, <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a>, <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a> and <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### Int64Ty {#acfc0c8843b968e7f4e48fa682f26d17b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{WholeProgramDevirt.cpp}::DevirtModule::Int64Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a> and <a href="#a3bfa9a83403d3c8c34a0079470468533">getMemberAddr</a>.</p>

</div>
</div>

### Int8Arr0Ty {#ab74d378fee9ca19018b5edb817735067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArrayType* anonymous{WholeProgramDevirt.cpp}::DevirtModule::Int8Arr0Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Sizeless array type, used for imported vtables.</p>


<p>This provides a signal to analyzers that these imports may alias, as they do for example when multiple unique return values occur in the same vtable.</p>


<p>Definition at line 591 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a> and <a href="#aeaa8e35cfb5c615f98eeaeeb9ab62788">importGlobal</a>.</p>

</div>
</div>

### Int8PtrTy {#ad262e7a3ecc8ddfc8226681b3aab8e2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PointerType* anonymous{WholeProgramDevirt.cpp}::DevirtModule::Int8PtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 584 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a8f2e0d9db7a457156c4377449c2e0606">applyICallBranchFunnel</a>, <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a56e23527438631272da8c1e486c84135">exportConstant</a> and <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a>.</p>

</div>
</div>

### Int8Ty {#a3c0b0b7c223820064123bb4331e720cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{WholeProgramDevirt.cpp}::DevirtModule::Int8Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 583 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a22eb17ec5325526a386b40274ca84b63">applyVirtualConstProp</a>, <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a16a470a2b40fa6e28a35af849806450b">exportGlobal</a>, <a href="#a3bfa9a83403d3c8c34a0079470468533">getMemberAddr</a>, <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a> and <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

### IntPtrTy {#a9d63a376b59663fe5c4ac3285ca817cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntegerType* anonymous{WholeProgramDevirt.cpp}::DevirtModule::IntPtrTy</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a1b8d4761888824dc65c66c5a0997abb9">importConstant</a> and <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a>.</p>

</div>
</div>

### LookupDomTree {#a14bdc91f8219d2ae59b20891017c6124}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;DominatorTree &amp;(Function &amp;)&gt; anonymous{WholeProgramDevirt.cpp}::DevirtModule::LookupDomTree</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 578 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#adf63c9ebc3de0773617afcdbd321f43b">runForTesting</a>, <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a> and <a href="#a9b3924d6dbe1bfa285ef3d3a6c3d4b6f">scanTypeTestUsers</a>.</p>

</div>
</div>

### M {#abddae483b27571fa57808aafa478d400}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Module&amp; anonymous{WholeProgramDevirt.cpp}::DevirtModule::M</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 576 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a8f2e0d9db7a457156c4377449c2e0606">applyICallBranchFunnel</a>, <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a>, <a href="#a17a815de9bbe3e7039e1fc916f2ea7b0">areRemarksEnabled</a>, <a href="#a3a5262b6225fdc05cfea242647c56db6">buildTypeIdentifierMap</a>, <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a16a470a2b40fa6e28a35af849806450b">exportGlobal</a>, <a href="#a3bfa9a83403d3c8c34a0079470468533">getMemberAddr</a>, <a href="#a1b8d4761888824dc65c66c5a0997abb9">importConstant</a>, <a href="#aeaa8e35cfb5c615f98eeaeeb9ab62788">importGlobal</a>, <a href="#a2571433d1b220fb84bfcb7584002cb02">importResolution</a>, <a href="#a12cea94e94a75a84e5e5c0a649d1ef78">rebuildGlobal</a>, <a href="#a30b56b2eb82bcd9691aa8ff48dde9a79">removeRedundantTypeTests</a>, <a href="#a363028d7884038c73a4f3f2474530c33">run</a>, <a href="#adf63c9ebc3de0773617afcdbd321f43b">runForTesting</a>, <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a>, <a href="#afb57635b61137e0e4950de608225318f">shouldExportConstantsAsAbsoluteSymbols</a>, <a href="#a37fe954e0b01502acccf9b29943e9164">tryEvaluateFunctionsWithArgs</a>, <a href="#abfe26739ec5c54c0e4039d8e5d2d4a01">tryFindVirtualCallTargets</a>, <a href="#ad722656aa63d87c356ec659228865f65">tryICallBranchFunnel</a> and <a href="#ae9f4748bfea60c7f38b8a1f4357b0150">trySingleImplDevirt</a>.</p>

</div>
</div>

### NumUnsafeUsesForTypeTest {#a381261e9d8901b0442018a690a73d2d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;CallInst *, unsigned&gt; anonymous{WholeProgramDevirt.cpp}::DevirtModule::NumUnsafeUsesForTypeTest</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a30b56b2eb82bcd9691aa8ff48dde9a79">removeRedundantTypeTests</a> and <a href="#a021e32e2bf67f331d9384a162dc402c2">scanTypeCheckedLoadUsers</a>.</p>

</div>
</div>

### OptimizedCalls {#ab101828488043f0890c03bad78bef1fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallPtrSet&lt;CallBase *, 8&gt; anonymous{WholeProgramDevirt.cpp}::DevirtModule::OptimizedCalls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 601 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a>, <a href="#a1ccdbdd6f0c159f0233236dca7125328">applyUniformRetValOpt</a>, <a href="#a4f6dd5dcbaeca0d82159a5094b742672">applyUniqueRetValOpt</a> and <a href="#a22eb17ec5325526a386b40274ca84b63">applyVirtualConstProp</a>.</p>

</div>
</div>

### OREGetter {#a4083d853fdbf017ceeed32a08c0f8718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">function_ref&lt;OptimizationRemarkEmitter &amp;(Function *)&gt; anonymous{WholeProgramDevirt.cpp}::DevirtModule::OREGetter</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 594 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a8f2e0d9db7a457156c4377449c2e0606">applyICallBranchFunnel</a>, <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a>, <a href="#a1ccdbdd6f0c159f0233236dca7125328">applyUniformRetValOpt</a>, <a href="#a4f6dd5dcbaeca0d82159a5094b742672">applyUniqueRetValOpt</a>, <a href="#a22eb17ec5325526a386b40274ca84b63">applyVirtualConstProp</a>, <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a363028d7884038c73a4f3f2474530c33">run</a> and <a href="#adf63c9ebc3de0773617afcdbd321f43b">runForTesting</a>.</p>

</div>
</div>

### RemarksEnabled {#ad11a18045a208731346a76253ba5e79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool anonymous{WholeProgramDevirt.cpp}::DevirtModule::RemarksEnabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 593 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>Referenced by <a href="#a8f2e0d9db7a457156c4377449c2e0606">applyICallBranchFunnel</a>, <a href="#a21ea18f2c76b35d0985927f6ffebf9ba">applySingleImplDevirt</a>, <a href="#a1ccdbdd6f0c159f0233236dca7125328">applyUniformRetValOpt</a>, <a href="#a4f6dd5dcbaeca0d82159a5094b742672">applyUniqueRetValOpt</a>, <a href="#a22eb17ec5325526a386b40274ca84b63">applyVirtualConstProp</a>, <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="#a363028d7884038c73a4f3f2474530c33">run</a>, <a href="#ae9f4748bfea60c7f38b8a1f4357b0150">trySingleImplDevirt</a>, <a href="#ae1cb89e56d053bfe29124d830ef0ac94">tryUniformRetValOpt</a>, <a href="#a4dc69b6c381a3b54539a9eff3e7d1d3f">tryUniqueRetValOpt</a> and <a href="#a85892c8cb2a8b36248f88a963d8a09ca">tryVirtualConstProp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### lookUpFunctionValueInfo() {#addf7542694401439f2f600b3890c8831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ValueInfo DevirtModule::lookUpFunctionValueInfo (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> * TheFn, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary)</td>
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



<p>Definition at line 729 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#a8c1c90daa7cee721caf0a024acf476d8">ExportSummary</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a71ee7e63264e4997a3340a781d44832e">llvm::GlobalValue::getGUID</a>, <a href="/web-llvm/docs/api/classes/llvm/globalvalue/#a6811428caf500217f319c74e80900c14">llvm::GlobalValue::getGUID</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#adb5c319f5905c1d3ca9eb5df546388c5">llvm::Value::getName</a>.</p>


<p>Referenced by <a href="#a91cdd27c8deb2678870c535c9205fcc4">mustBeUnreachableFunction</a>.</p>

</div>
</div>

### mustBeUnreachableFunction() {#a91cdd27c8deb2678870c535c9205fcc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::mustBeUnreachableFunction (<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> F, <a href="/web-llvm/docs/api/classes/llvm/modulesummaryindex">ModuleSummaryIndex</a> * ExportSummary)</td>
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



<p>Definition at line 740 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a8c1c90daa7cee721caf0a024acf476d8">ExportSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>, <a href="#addf7542694401439f2f600b3890c8831">lookUpFunctionValueInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/analysis/modulesummaryanalysis-cpp/#aaeceda7c9243e01a0888f44e2f3e7ba3">mustBeUnreachableFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a92e98b87a580ee2727a894cafc57a73e">WholeProgramDevirtKeepUnreachableFunction</a>.</p>

</div>
</div>

### runForTesting() {#adf63c9ebc3de0773617afcdbd321f43b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DevirtModule::runForTesting (<a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/aaresults">AAResults</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; AARGetter, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/optimizationremarkemitter">OptimizationRemarkEmitter</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> *)&gt; OREGetter, <a href="/web-llvm/docs/api/classes/llvm/function-ref">function_ref</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/dominatortree">DominatorTree</a> &amp;(<a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp;)&gt; LookupDomTree)</td>
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



<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a>.</p>


<p>References <a href="#a309a12b17b50b9b518ce1c76e251b894">AARGetter</a>, <a href="/web-llvm/docs/api/groups/arcopt/#gaa57b1a4e6a1c79233913139635169cf1">Changed</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp/#a3f84f6f1a3f90b174404388b1bce971a">checkCombinedSummaryForTesting</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a4231130e271f81a2e2b33f55e6233dae">ClReadSummary</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#a9020e4076f17c245550360c81bb4702e">ClSummaryAction</a>, <a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/lowertypetests-cpp/#ac7f3d084756d2a946dcd9c1ecd50daab">ClWriteSummary</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#aee0e70be66536b9ef7b65ae2e5a45959">llvm::consumeError</a>, <a href="#ac7da757da2141faa2d1d0c429bd4e1e2">DevirtModule</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ad10875fd499e8e285aaeef615e9b11aa">llvm::errorCodeToError</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab97c9dc8dec5b044b551639baf324053">llvm::errorOrToExpected</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38a0bdae7fb49d99f161aa6de0379d7ea0095a9fa74d1713e43e370a7d7846224">llvm::Export</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a59316b66df2176ff19458e2d624b98ad">llvm::getModuleSummaryIndex</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a38a0bdae7fb49d99f161aa6de0379d7ea72d6d7a1885885bb55a565fd1070581a">llvm::Import</a>, <a href="#a14bdc91f8219d2ae59b20891017c6124">LookupDomTree</a>, <a href="#abddae483b27571fa57808aafa478d400">M</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695a8ae6a0a158ab49e5bbe92cbc2cabcbcd">llvm::sys::fs::OF_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/fs/#a662978c0cdf81de0d448032f142a3695ab505c2c79499fbe180989bffbf108a50">llvm::sys::fs::OF_TextWithCRLF</a>, <a href="#a4083d853fdbf017ceeed32a08c0f8718">OREGetter</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a5858c9c8d861a0d36e7c8f99b8faf7fe">llvm::writeIndexToFile</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/wholeprogramdevirtpass/#af94d9399906155205bf6afa17427d5c7">llvm::WholeProgramDevirtPass::run</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/transforms/lib/transforms/ipo/wholeprogramdevirt-cpp">WholeProgramDevirt.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
