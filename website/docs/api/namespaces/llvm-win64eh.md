---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/win64eh
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# `Win64EH` Namespace



## Definition

<div class="doxyDefinition">
namespace llvm::Win64EH { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/win64eh/instruction">Instruction</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/win64eh/unwindemitter">UnwindEmitter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/win64eh/armunwindemitter">ARMUnwindEmitter</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/win64eh/arm64unwindemitter">ARM64UnwindEmitter</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">union</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/unions/llvm/win64eh/unwindcode">UnwindCode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/unions/llvm/win64eh/unwindcode">UnwindCode</a> - This union describes a single operation in a function prolog, or part thereof. <a href="/web-llvm/docs/api/unions/llvm/win64eh/unwindcode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/win64eh/runtimefunction">RuntimeFunction</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/win64eh/runtimefunction">RuntimeFunction</a> - An entry in the table of functions with unwind info. <a href="/web-llvm/docs/api/structs/llvm/win64eh/runtimefunction/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a> - An entry in the exception table. <a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">UnwindOpcodes { <a href="#a6147069c8d9fb51bcbc2ec9ff447a21e">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="#a6147069c8d9fb51bcbc2ec9ff447a21e">UnwindOpcodes</a> - Enumeration whose values specify a single operation in the prolog of a function. <a href="#a6147069c8d9fb51bcbc2ec9ff447a21e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a5cbd04acfda223b46bb9c21e15d9e2fb">...</a> }</td>
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


<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a5cbd04acfda223b46bb9c21e15d9e2fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous enum </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNW_ExceptionHandler<a id="a5cbd04acfda223b46bb9c21e15d9e2fbac7a3e9484b4f8694d3070df883125725"></a></td>
<td class="doxyEnumItemDescription">UNW_ExceptionHandler - Specifies that this function has an exception handler (= 0x01)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNW_TerminateHandler<a id="a5cbd04acfda223b46bb9c21e15d9e2fba19aa3cc5317963c4b698291979bdbd45"></a></td>
<td class="doxyEnumItemDescription">UNW_TerminateHandler - Specifies that this function has a termination handler (= 0x02)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNW_ChainInfo<a id="a5cbd04acfda223b46bb9c21e15d9e2fbad1f4738b73956f7f48051202ebbe58e6"></a></td>
<td class="doxyEnumItemDescription">UNW_ChainInfo - Specifies that this <a href="/web-llvm/docs/api/structs/llvm/win64eh/unwindinfo">UnwindInfo</a> structure is chained to another one (= 0x04)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 134 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>

</div>
</div>

### UnwindOpcodes {#a6147069c8d9fb51bcbc2ec9ff447a21e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::Win64EH::UnwindOpcodes </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="#a6147069c8d9fb51bcbc2ec9ff447a21e">UnwindOpcodes</a> - Enumeration whose values specify a single operation in the prolog of a function.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_PushNonVol<a id="a6147069c8d9fb51bcbc2ec9ff447a21eaae7e62281f7ac9af9a2305acf345e30c"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_AllocLarge<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea696f26056e05c65dd7c1bb6da6bb6c94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_AllocSmall<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea852e7cdf29ed57cc4c6fe34fbe236166"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SetFPReg<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea6a008a4f48e5b08f2f1ea75159e5fee3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveNonVol<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea4e13ff9dd4e7826d85bbdd2671d1aa24"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveNonVolBig<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea20d9d4f8ad4a32c577c3c3af202df151"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_Epilog<a id="a6147069c8d9fb51bcbc2ec9ff447a21eaf26c651e85bacedb1532dee0ef1ebe3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SpareCode<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea495365f90c9a991b1e0067a1332c4289"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveXMM128<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea7e9f984ddcbc105b772e19e4b095cffc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveXMM128Big<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea91d84d5df0879f33b1770710b7705c7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_PushMachFrame<a id="a6147069c8d9fb51bcbc2ec9ff447a21eabb99442c04b0287262dcb4395886bd7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_AllocMedium<a id="a6147069c8d9fb51bcbc2ec9ff447a21eae2ba520dfe4a97772ebb8e010f14b90e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveR19R20X<a id="a6147069c8d9fb51bcbc2ec9ff447a21eabcce408cff8a8caddd672fcf9d5f7c4d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFPLRX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea1c1e91f085207677f6a87f72211a8e7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFPLR<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea40d470d658f8310637362abe42236e5a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveReg<a id="a6147069c8d9fb51bcbc2ec9ff447a21eabd688d6bb3a01916b39bbf1d073ec4c1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveRegX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea6177f784f0f7ad77aeda554a1bec7bc6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveRegP<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea8c6bd0c4141baac292a758ad1e4ed2d2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveRegPX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea9f7d600586e92963f5881e13cb4886ce"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveLRPair<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea77b13b268267acfad2a633a4207d695b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFReg<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea0ff61e9c16bb520f1195c5892ff628ec"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFRegX<a id="a6147069c8d9fb51bcbc2ec9ff447a21eaf3b908c7dcda8acf3116614dc1874bd8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFRegP<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea080b3b9cd2397e7ce59bfbd8d50220da"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFRegPX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea17274b8b2b523abe03e911ad420586bf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SetFP<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea643ab7c0e9d1180026aeb5526d64afa9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_AddFP<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea5bf832be598907276533805261b14c94"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_Nop<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea370cb5b95f05480a329dbc936969d5d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_End<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea87d69becc531e1d468e00f36b1d0c5dd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveNext<a id="a6147069c8d9fb51bcbc2ec9ff447a21eaa0e067e95931107f1361a0853805202b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_TrapFrame<a id="a6147069c8d9fb51bcbc2ec9ff447a21eae869ae7d5bcd450c29ee40c32c15f971"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_Context<a id="a6147069c8d9fb51bcbc2ec9ff447a21eaf3c84a367e177cb35173b55701e59b62"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_ECContext<a id="a6147069c8d9fb51bcbc2ec9ff447a21eacaef82dc45b07cc681ade2a07b365961"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_ClearUnwoundToCall<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea1d63b21ce3a3530dc0992c9545532657"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_PACSignLR<a id="a6147069c8d9fb51bcbc2ec9ff447a21eabfe110fe2ab3ff5ef9141ceeb2fd0c7d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegI<a id="a6147069c8d9fb51bcbc2ec9ff447a21eafd194f2c1971298fa3ed259340dc7af0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegIP<a id="a6147069c8d9fb51bcbc2ec9ff447a21eae8425317799d828362a3615b816ec496"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegD<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea3ecd6abb34b66d0cea4a285a43ca62eb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegDP<a id="a6147069c8d9fb51bcbc2ec9ff447a21eaa32738827eafd247a5db8ccacf84ea84"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegQ<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea9fdabb65c8f4afc6d98b0997df0f4bc1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegQP<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea3a9d85a19d84843f629750bfa002ab9b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegIX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea7d52165a373988e5acd605fd09b65638"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegIPX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea54d0faec96686043b538bac78fe185d6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegDX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea30be100959f86a48264856eb0130185e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegDPX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea143dd0f1157957f6d74230edfbdace28"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegQX<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea62df2c37135f5fa1bad0434bede59e70"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveAnyRegQPX<a id="a6147069c8d9fb51bcbc2ec9ff447a21eabda3f39fe0a0b595e2a21968c3cd83d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_AllocHuge<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea3380a84eb648ca0ee05c138bb4e59c48"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_WideAllocMedium<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea2b7d6e82d9ab706a4ed67f4214efefe5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_WideAllocLarge<a id="a6147069c8d9fb51bcbc2ec9ff447a21eac65a3d732455e48352266b753b1a90e6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_WideAllocHuge<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea60b7e4a0be5c03d2ec6fadf011036552"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_WideSaveRegMask<a id="a6147069c8d9fb51bcbc2ec9ff447a21eae14d06b7d47c095bd18678232bfd5148"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveSP<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea73e5f2ff29af4a2c90c8711b8a6780e4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveRegsR4R7LR<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea16cfe12e38096341a1a273a904ef0d31"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_WideSaveRegsR4R11LR<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea444955343875efc999ae15232dca1d16"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFRegD8D15<a id="a6147069c8d9fb51bcbc2ec9ff447a21eab3bc8467e0977cc0f9426032256c5540"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveRegMask<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea727048e9b2c0d090a5797b13e1c5c827"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveLR<a id="a6147069c8d9fb51bcbc2ec9ff447a21eabe9ce7cc4dc6542d11f840cc8e51a6f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFRegD0D15<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea35a232904dcd802033ea03851f7838b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_SaveFRegD16D31<a id="a6147069c8d9fb51bcbc2ec9ff447a21eaf6e5478d3596267b0b6340a415e93f45"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_WideNop<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea055da35948045301bbb791b59fda7948"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_EndNop<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea2c1e73f96a3eb49c02ea5e2c23582c60"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_WideEndNop<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea122a936a6e1d854afed8b6ecc54faec0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UOP_Custom<a id="a6147069c8d9fb51bcbc2ec9ff447a21ea459472d4a0e3cd23f8448702e0f84325"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 26 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/win64eh-h">Win64EH.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
