---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/codegen
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `codegen` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::codegen { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/codegen/registercodegenflags">RegisterCodeGenFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create this object with static storage to register codegen-related command line options. <a href="/web-llvm/docs/api/structs/llvm/codegen/registercodegenflags/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ec775f7fd559840732db9d3d7db679">getMArch</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a098ec763a7e830d5b5703b3e0310599d">getMCPU</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c8613c1c9e6bb4f1c27f4fd755f85f8">getMAttrs</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b4426638dbcceb3232268f5b4b5030">getRelocModel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/reloc/#af59f6dc86e80aaf56f1afd155eebf568">Reloc::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb82198c9ef17c24236554dfbc3fbe41">getExplicitRelocModel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/threadmodel/#a299c775d35e28348ecfbe03c38c17fe1">ThreadModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbb443f8d5a8c771271dca65579ec773">getThreadModel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63e00b24221f39c72d2ff66500d1b812">getCodeModel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e763239797dd7cb27986348926c0766">getExplicitCodeModel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad929d9813dfb1ea7891fdd9ebdbe4e7f">getLargeDataThreshold</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; uint64_t &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91acc6d71c661cfa7d885391b1e9833c">getExplicitLargeDataThreshold</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a2ca3855108426698ff21517a7c884c84">llvm::ExceptionHandling</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a5ffa3158003a3a67d5543c6b555b44">getExceptionModel</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; <a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b0ffceeb60ead3347fc818f2682f1df">getExplicitFileType</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a73b761f8d40500a5a28889569526b260">CodeGenFileType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21feb4d82bab2d42675fccc5ccd76160">getFileType</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e49ecab2560cbdcda6ff4b08dccb081">getFramePointerUsage</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58dafa2045a626d96be66ae8acd6bb3">getEnableUnsafeFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0e28b0bdfe4de336d0960c12c738565">getEnableNoInfsFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea42629187535abb89fadbc99af28d92">getEnableNoNaNsFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2edbaee080d3f4653926c746a1a62206">getEnableNoSignedZerosFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691ff4984dacf7b4f27e8b0350521f0a">getEnableApproxFuncFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4fb8e62075af9452d5da53943d6a70a">getEnableNoTrappingFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893">DenormalMode::DenormalModeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a226d6d3bf846f18b7ab2746594212a94">getDenormalFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/denormalmode/#a29b26e3ae30f3f6ec4106ff181282893">DenormalMode::DenormalModeKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3cd3b022a25351c87713a0417a1bb34">getDenormalFP32Math</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae64bdb0691c2f646b81277ba22c09ead">getEnableHonorSignDependentRoundingFPMath</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/floatabi/#aea077c52d84934aabf9445cef9eab2e2">llvm::FloatABI::ABIType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a530a05cfcb84b34e1251fa7dcedff8be">getFloatABIForCalls</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/fpopfusion/#a9c71bae9f02af273833fde586d529fc5">llvm::FPOpFusion::FPOpFusionMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc67880adf1a1beba830f126b398b3b6">getFuseFPOps</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#a78637df2e0b9a5e2109af945b0baaf34">SwiftAsyncFramePointerMode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeb6eb7dfbe48fb3ef0f2cb5f72ece268">getSwiftAsyncFramePointer</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3be569dc2b2d2159ca8ac39f323694b7">getDontPlaceZerosInBSS</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a125f32703c7db054483f564eeec2415f">getEnableGuaranteedTailCallOpt</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb4f67729dab4f6ab7aeb9342abf10f8">getEnableAIXExtendedAltivecABI</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abb7ea8627703f2975049ebe75efad586">getDisableTailCalls</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf57e616420aed51492697bd2e9f2285">getStackSymbolOrdering</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8a10f776401e9fb0710a2667f9adec3">getStackRealign</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e4a8fa158773962eebeff35e1304732">getTrapFuncName</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad24646b72aaf03da094431ba8a342984">getUseCtors</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e663457cda9700f33901656f291afd0">getDisableIntegratedAS</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a645a1ab75d5e984b249dda2a10f296f5">getDataSections</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a424f07efd7eabcc59bc4baabf2f84d80">getExplicitDataSections</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50187850d5980d8fbed509ca3f598e9">getFunctionSections</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d929242205c4a42a57cfc870b30bf1b">getExplicitFunctionSections</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ca52fc0188400242c346a47729b9cc3">getIgnoreXCOFFVisibility</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef0603845494c343f152969e2c58448b">getXCOFFTracebackTable</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01423284cb4201323b6c867de7c59f73">getBBSections</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a54ccc28ad7c9cd0fb9e05c9d7ae945">getTLSSize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeba3a021435b1e0233384e87252dc5c1">getEmulatedTLS</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4449215bf59439710d0f500b7d836a49">getExplicitEmulatedTLS</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6fc778398a92d28782697b8e943c00">getEnableTLSDESC</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30d3ad309386a3575403c82dd2f9190a">getExplicitEnableTLSDESC</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a1161081d2201c5ab733a89008a36d7">getUniqueSectionNames</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab95fa39bfefbff3234ca6e5601cba879">getUniqueBasicBlockSectionNames</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafb615678bb953de89ebd1ec2ad29f46">getSeparateNamedSections</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#ada924e855250645672a493841803ff91">llvm::EABI</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf10603d743fff54e4392f6ab3f896a8">getEABIVersion</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#adc04b17f40513e658e600a26842b1ed6">llvm::DebuggerKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeabf2c4aedb6a1d1689e8d67e6dd722">getDebuggerTuningOpt</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f3fc58d3d3b03968c1b9473c2d2298f">getEnableStackSizeSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9370b49cbad17c2c86cc50e704067b35">getEnableAddrsig</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a6cb681326f5d3f56943654879171d4">getEmitCallSiteInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d34f81b8273bfb69907f9de9177a5dd">getEnableMachineFunctionSplitter</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad18c990cedef3c0529a23875dee0e4e7">getEnableDebugEntryValues</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d60090281031816426b3391012dc472">getValueTrackingVariableLocations</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8c0e8ba3831204a919311d836d7f070">getExplicitValueTrackingVariableLocations</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac098fe7e12d3f39573f9d98c43cd9a1b">getForceDwarfFrameSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70b09452206f224495ed9f0df8f287c8">getXRayFunctionIndex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad310ebc142b4faa95d11dce2e3a6b456">getDebugStrictDwarf</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a776c0922d326e96c722a355e100c3a0f">getAlignLoops</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad30abb8a5e54b7546aa2b67f1da5f892">getJMCInstrument</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab727dce0ceebeb28287f5f9d62fd4011">getXCOFFReadOnlyPointers</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9f8128eee9736ef41459f165fc2ec29">getEnableBBAddrMap</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8">llvm::BasicBlockSection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac72192305c89532b4469f8533b6ecf5b">getBBSectionsMode</a> (llvm::TargetOptions &amp;Options)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a> (const llvm::Triple &amp;TheTriple)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Common utility function tightly tied to the options listed here. <a href="#ac754b19265fec508188376da454f57f9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15043032d97d572dd021b8ca016e8be8">getCPUStr</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b18aa9e75372c814e4d5207dce6b933">getFeaturesStr</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d80984ae9400c5f6fc20ac6eec8f6e1">getFeatureList</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a369cd19a81f5a9fee165657340331984">renderBoolStringAttr</a> (AttrBuilder &amp;B, StringRef Name, bool Val)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a> (StringRef CPU, StringRef Features, Function &amp;F)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set function attributes of function <span class="doxyComputerOutput">F</span> based on CPU, Features, and command line flags. <a href="#ac12e315180fb16cb5874fb41526ca453">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae117c75f2be19f0290f82a1ff1352842">setFunctionAttributes</a> (StringRef CPU, StringRef Features, Module &amp;M)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set function attributes of functions in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M based on CPU, Features, and command line flags. <a href="#ae117c75f2be19f0290f82a1ff1352842">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abdfac1a6be86a9378f2a703dc24c3ab2">getDefaultValueTrackingVariableLocations</a> (const llvm::Triple &amp;T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Should value-tracking variable locations / instruction referencing be enabled by default for this triple? <a href="#abdfac1a6be86a9378f2a703dc24c3ab2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/expected">Expected</a>&lt; std::unique_ptr&lt; <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a> (StringRef TargetTriple, CodeGenOptLevel OptLevel=CodeGenOptLevel::Default)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> instance with the options defined on the command line. <a href="#a8f10e936389f0129adc2f5ded44fdd9a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### createTargetMachineForTriple() {#a8f10e936389f0129adc2f5ded44fdd9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Expected&lt; std::unique_ptr&lt; TargetMachine &gt; &gt; llvm::codegen::createTargetMachineForTriple (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> TargetTriple, <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2">CodeGenOptLevel</a> OptLevel=<a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">CodeGenOptLevel::Default</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Creates a <a href="/web-llvm/docs/api/classes/llvm/targetmachine">TargetMachine</a> instance with the options defined on the command line.</p>


<p>This can be used for tools that do not need further customization of the <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a>.</p>


<p>Declaration at line 197 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 750 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a4d2fd926089a58d482fb67a362e11bad">llvm::createStringError</a>, <a href="/web-llvm/docs/api/classes/llvm/target/#a97b31e68ba164458a37e49e7d1053fc1">llvm::Target::createTargetMachine</a>, <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a>, <a href="#a15043032d97d572dd021b8ca016e8be8">getCPUStr</a>, <a href="#a5e763239797dd7cb27986348926c0766">getExplicitCodeModel</a>, <a href="#abb82198c9ef17c24236554dfbc3fbe41">getExplicitRelocModel</a>, <a href="#a1b18aa9e75372c814e4d5207dce6b933">getFeaturesStr</a>, <a href="#a03ec775f7fd559840732db9d3d7db679">getMArch</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a7bc9985614536143e793244dfb66028c">llvm::Triple::getTriple</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a2b43c21951d0948b34bcf7019949032d">llvm::inconvertibleErrorCode</a>, <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a> and <a href="/web-llvm/docs/api/structs/llvm/targetregistry/#a85a69009ec328d5835241f56fb62cc6d">llvm::TargetRegistry::lookupTarget</a>.</p>


<p>Referenced by <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a>.</p>

</div>
</div>

### getAlignLoops() {#a776c0922d326e96c722a355e100c3a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::codegen::getAlignLoops ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getBBSections() {#a01423284cb4201323b6c867de7c59f73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::codegen::getBBSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac72192305c89532b4469f8533b6ecf5b">getBBSectionsMode</a>.</p>

</div>
</div>

### getBBSectionsMode() {#ac72192305c89532b4469f8533b6ecf5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::BasicBlockSection llvm::codegen::getBBSectionsMode (<a href="/web-llvm/docs/api/classes/llvm/targetoptions">llvm::TargetOptions</a> &amp; Options)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 525 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8ab1c94ca2fbc3e78fc30069c8d0f01680">llvm::All</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9a7b5c68c90f85baaedaa854cc5002cc">llvm::errs</a>, <a href="#a01423284cb4201323b6c867de7c59f73">getBBSections</a>, <a href="#ac72192305c89532b4469f8533b6ecf5b">getBBSectionsMode</a>, <a href="/web-llvm/docs/api/classes/llvm/erroror/#a8300c72908f1845c931951ed4b2a2375">llvm::ErrorOr&lt; T &gt;::getError</a>, <a href="/web-llvm/docs/api/classes/llvm/memorybuffer/#aa98611beefe78f907beeee7305cc8174">llvm::MemoryBuffer::getFile</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a4ee29ca12c7d126654bd0e5275de6135">llvm::List</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acefe92adee8725ad904c7c43649790e8a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#ac72192305c89532b4469f8533b6ecf5b">getBBSectionsMode</a> and <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getCodeModel() {#a63e00b24221f39c72d2ff66500d1b812}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeModel::Model llvm::codegen::getCodeModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getCPUStr() {#a15043032d97d572dd021b8ca016e8be8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::codegen::getCPUStr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 174 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 608 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="#a15043032d97d572dd021b8ca016e8be8">getCPUStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2e8cdc0e591685c9156af3d0d4fdae06">llvm::sys::getHostCPUName</a> and <a href="#a098ec763a7e830d5b5703b3e0310599d">getMCPU</a>.</p>


<p>Referenced by <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a> and <a href="#a15043032d97d572dd021b8ca016e8be8">getCPUStr</a>.</p>

</div>
</div>

### getDataSections() {#a645a1ab75d5e984b249dda2a10f296f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getDataSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getDebuggerTuningOpt() {#abeabf2c4aedb6a1d1689e8d67e6dd722}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::DebuggerKind llvm::codegen::getDebuggerTuningOpt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 129 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getDebugStrictDwarf() {#ad310ebc142b4faa95d11dce2e3a6b456}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getDebugStrictDwarf ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 148 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getDefaultValueTrackingVariableLocations() {#abdfac1a6be86a9378f2a703dc24c3ab2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getDefaultValueTrackingVariableLocations (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a> &amp; T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Should value-tracking variable locations / instruction referencing be enabled by default for this triple?</p>

<p>Definition at line 192 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a8ec1bf8d7b792ca9fac56f8514db18d2a7a1920d61156abc05a60135aefe8bc67">llvm::Default</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### getDenormalFP32Math() {#ac3cd3b022a25351c87713a0417a1bb34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode::DenormalModeKind llvm::codegen::getDenormalFP32Math ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>

</div>
</div>

### getDenormalFPMath() {#a226d6d3bf846f18b7ab2746594212a94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DenormalMode::DenormalModeKind llvm::codegen::getDenormalFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a> and <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>

</div>
</div>

### getDisableIntegratedAS() {#a1e663457cda9700f33901656f291afd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getDisableIntegratedAS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getDisableTailCalls() {#abb7ea8627703f2975049ebe75efad586}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getDisableTailCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>

</div>
</div>

### getDontPlaceZerosInBSS() {#a3be569dc2b2d2159ca8ac39f323694b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getDontPlaceZerosInBSS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEABIVersion() {#acf10603d743fff54e4392f6ab3f896a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::EABI llvm::codegen::getEABIVersion ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEmitCallSiteInfo() {#a3a6cb681326f5d3f56943654879171d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEmitCallSiteInfo ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEmulatedTLS() {#aeba3a021435b1e0233384e87252dc5c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEmulatedTLS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getEnableAddrsig() {#a9370b49cbad17c2c86cc50e704067b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableAddrsig ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableAIXExtendedAltivecABI() {#adb4f67729dab4f6ab7aeb9342abf10f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableAIXExtendedAltivecABI ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableApproxFuncFPMath() {#a691ff4984dacf7b4f27e8b0350521f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableApproxFuncFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableBBAddrMap() {#ac9f8128eee9736ef41459f165fc2ec29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableBBAddrMap ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 162 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableDebugEntryValues() {#ad18c990cedef3c0529a23875dee0e4e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableDebugEntryValues ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableGuaranteedTailCallOpt() {#a125f32703c7db054483f564eeec2415f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableGuaranteedTailCallOpt ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableHonorSignDependentRoundingFPMath() {#ae64bdb0691c2f646b81277ba22c09ead}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableHonorSignDependentRoundingFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableMachineFunctionSplitter() {#a4d34f81b8273bfb69907f9de9177a5dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableMachineFunctionSplitter ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 137 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableNoInfsFPMath() {#ab0e28b0bdfe4de336d0960c12c738565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableNoInfsFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableNoNaNsFPMath() {#aea42629187535abb89fadbc99af28d92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableNoNaNsFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 64 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableNoSignedZerosFPMath() {#a2edbaee080d3f4653926c746a1a62206}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableNoSignedZerosFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableNoTrappingFPMath() {#ac4fb8e62075af9452d5da53943d6a70a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableNoTrappingFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableStackSizeSection() {#a2f3fc58d3d3b03968c1b9473c2d2298f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableStackSizeSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getEnableTLSDESC() {#a6f6fc778398a92d28782697b8e943c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableTLSDESC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 118 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getEnableUnsafeFPMath() {#aa58dafa2045a626d96be66ae8acd6bb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getEnableUnsafeFPMath ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getExceptionModel() {#a8a5ffa3158003a3a67d5543c6b555b44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::ExceptionHandling llvm::codegen::getExceptionModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getExplicitCodeModel() {#a5e763239797dd7cb27986348926c0766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CodeModel::Model &gt; llvm::codegen::getExplicitCodeModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a>.</p>

</div>
</div>

### getExplicitDataSections() {#a424f07efd7eabcc59bc4baabf2f84d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; llvm::codegen::getExplicitDataSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getExplicitEmulatedTLS() {#a4449215bf59439710d0f500b7d836a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; llvm::codegen::getExplicitEmulatedTLS ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getExplicitEnableTLSDESC() {#a30d3ad309386a3575403c82dd2f9190a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; llvm::codegen::getExplicitEnableTLSDESC ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 119 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getExplicitFileType() {#a9b0ffceeb60ead3347fc818f2682f1df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; CodeGenFileType &gt; llvm::codegen::getExplicitFileType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getExplicitFunctionSections() {#a9d929242205c4a42a57cfc870b30bf1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; llvm::codegen::getExplicitFunctionSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getExplicitLargeDataThreshold() {#a91acc6d71c661cfa7d885391b1e9833c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; uint64_t &gt; llvm::codegen::getExplicitLargeDataThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getExplicitRelocModel() {#abb82198c9ef17c24236554dfbc3fbe41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; Reloc::Model &gt; llvm::codegen::getExplicitRelocModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a>.</p>

</div>
</div>

### getExplicitValueTrackingVariableLocations() {#af8c0e8ba3831204a919311d836d7f070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt; bool &gt; llvm::codegen::getExplicitValueTrackingVariableLocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 142 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getFeatureList() {#a6d80984ae9400c5f6fc20ac6eec8f6e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; llvm::codegen::getFeatureList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 178 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 635 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#af579a881fa0a6fe785ecf91fcc9ccaaa">llvm::SubtargetFeatures::AddFeature</a>, <a href="#a6d80984ae9400c5f6fc20ac6eec8f6e1">getFeatureList</a>, <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#a39a9e8ebdc3fdfb710357fdb5e724abe">llvm::SubtargetFeatures::getFeatures</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2e3453665d04910c970e81e6c2fc2f98">llvm::sys::getHostCPUFeatures</a>, <a href="#a1c8613c1c9e6bb4f1c27f4fd755f85f8">getMAttrs</a> and <a href="#a098ec763a7e830d5b5703b3e0310599d">getMCPU</a>.</p>


<p>Referenced by <a href="#a6d80984ae9400c5f6fc20ac6eec8f6e1">getFeatureList</a>.</p>

</div>
</div>

### getFeaturesStr() {#a1b18aa9e75372c814e4d5207dce6b933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::codegen::getFeaturesStr ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 618 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#af579a881fa0a6fe785ecf91fcc9ccaaa">llvm::SubtargetFeatures::AddFeature</a>, <a href="#a1b18aa9e75372c814e4d5207dce6b933">getFeaturesStr</a>, <a href="/web-llvm/docs/api/namespaces/llvm/sys/#a2e3453665d04910c970e81e6c2fc2f98">llvm::sys::getHostCPUFeatures</a>, <a href="#a1c8613c1c9e6bb4f1c27f4fd755f85f8">getMAttrs</a>, <a href="#a098ec763a7e830d5b5703b3e0310599d">getMCPU</a> and <a href="/web-llvm/docs/api/classes/llvm/subtargetfeatures/#aaa9679917091c7e93f866894599f923e">llvm::SubtargetFeatures::getString</a>.</p>


<p>Referenced by <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a> and <a href="#a1b18aa9e75372c814e4d5207dce6b933">getFeaturesStr</a>.</p>

</div>
</div>

### getFileType() {#a21feb4d82bab2d42675fccc5ccd76160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeGenFileType llvm::codegen::getFileType ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getFloatABIForCalls() {#a530a05cfcb84b34e1251fa7dcedff8be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FloatABI::ABIType llvm::codegen::getFloatABIForCalls ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getForceDwarfFrameSection() {#ac098fe7e12d3f39573f9d98c43cd9a1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getForceDwarfFrameSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getFramePointerUsage() {#a2e49ecab2560cbdcda6ff4b08dccb081}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FramePointerKind llvm::codegen::getFramePointerUsage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>

</div>
</div>

### getFunctionSections() {#ad50187850d5980d8fbed509ca3f598e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getFunctionSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getFuseFPOps() {#acc67880adf1a1beba830f126b398b3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FPOpFusion::FPOpFusionMode llvm::codegen::getFuseFPOps ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 79 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getIgnoreXCOFFVisibility() {#a3ca52fc0188400242c346a47729b9cc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getIgnoreXCOFFVisibility ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getJMCInstrument() {#ad30abb8a5e54b7546aa2b67f1da5f892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getJMCInstrument ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 152 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getLargeDataThreshold() {#ad929d9813dfb1ea7891fdd9ebdbe4e7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::codegen::getLargeDataThreshold ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getMArch() {#a03ec775f7fd559840732db9d3d7db679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::codegen::getMArch ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a>.</p>

</div>
</div>

### getMAttrs() {#a1c8613c1c9e6bb4f1c27f4fd755f85f8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::string &gt; llvm::codegen::getMAttrs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#a6d80984ae9400c5f6fc20ac6eec8f6e1">getFeatureList</a> and <a href="#a1b18aa9e75372c814e4d5207dce6b933">getFeaturesStr</a>.</p>

</div>
</div>

### getMCPU() {#a098ec763a7e830d5b5703b3e0310599d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::codegen::getMCPU ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#a15043032d97d572dd021b8ca016e8be8">getCPUStr</a>, <a href="#a6d80984ae9400c5f6fc20ac6eec8f6e1">getFeatureList</a> and <a href="#a1b18aa9e75372c814e4d5207dce6b933">getFeaturesStr</a>.</p>

</div>
</div>

### getRelocModel() {#a72b4426638dbcceb3232268f5b4b5030}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Reloc::Model llvm::codegen::getRelocModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getSeparateNamedSections() {#aafb615678bb953de89ebd1ec2ad29f46}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getSeparateNamedSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getStackRealign() {#aa8a10f776401e9fb0710a2667f9adec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getStackRealign ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 93 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>

</div>
</div>

### getStackSymbolOrdering() {#adf57e616420aed51492697bd2e9f2285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getStackSymbolOrdering ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getSwiftAsyncFramePointer() {#aeb6eb7dfbe48fb3ef0f2cb5f72ece268}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SwiftAsyncFramePointerMode llvm::codegen::getSwiftAsyncFramePointer ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getThreadModel() {#adbb443f8d5a8c771271dca65579ec773}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ThreadModel::Model llvm::codegen::getThreadModel ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getTLSSize() {#a4a54ccc28ad7c9cd0fb9e05c9d7ae945}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::codegen::getTLSSize ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getTrapFuncName() {#a7e4a8fa158773962eebeff35e1304732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string llvm::codegen::getTrapFuncName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>

</div>
</div>

### getUniqueBasicBlockSectionNames() {#ab95fa39bfefbff3234ca6e5601cba879}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getUniqueBasicBlockSectionNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getUniqueSectionNames() {#a2a1161081d2201c5ab733a89008a36d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getUniqueSectionNames ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getUseCtors() {#ad24646b72aaf03da094431ba8a342984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getUseCtors ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getValueTrackingVariableLocations() {#a8d60090281031816426b3391012dc472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getValueTrackingVariableLocations ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 141 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>

</div>
</div>

### getXCOFFReadOnlyPointers() {#ab727dce0ceebeb28287f5f9d62fd4011}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getXCOFFReadOnlyPointers ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getXCOFFTracebackTable() {#aef0603845494c343f152969e2c58448b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getXCOFFTracebackTable ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### getXRayFunctionIndex() {#a70b09452206f224495ed9f0df8f287c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::codegen::getXRayFunctionIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 146 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>.</p>


<p>Referenced by <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### InitTargetOptionsFromCodeGenFlags() {#ac754b19265fec508188376da454f57f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TargetOptions llvm::codegen::InitTargetOptionsFromCodeGenFlags (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/triple">llvm::Triple</a> &amp; TheTriple)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Common utility function tightly tied to the options listed here.</p>


<p>Initializes a <a href="/web-llvm/docs/api/classes/llvm/targetoptions">TargetOptions</a> object with CodeGen flags and returns it. <span class="doxyComputerOutput">TheTriple</span> is used to determine the default value for options if options are not explicitly specified. If those triple dependant options value do not have effect for your component, a default Triple() could be passed in.</p>


<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 546 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/floatabi/#aea077c52d84934aabf9445cef9eab2e2ae41bda228a5aa7298dc5ac9cff9414f2">llvm::FloatABI::Default</a>, <a href="#a776c0922d326e96c722a355e100c3a0f">getAlignLoops</a>, <a href="#ac72192305c89532b4469f8533b6ecf5b">getBBSectionsMode</a>, <a href="#abeabf2c4aedb6a1d1689e8d67e6dd722">getDebuggerTuningOpt</a>, <a href="#ad310ebc142b4faa95d11dce2e3a6b456">getDebugStrictDwarf</a>, <a href="#a226d6d3bf846f18b7ab2746594212a94">getDenormalFPMath</a>, <a href="#a1e663457cda9700f33901656f291afd0">getDisableIntegratedAS</a>, <a href="#a3be569dc2b2d2159ca8ac39f323694b7">getDontPlaceZerosInBSS</a>, <a href="#acf10603d743fff54e4392f6ab3f896a8">getEABIVersion</a>, <a href="#a3a6cb681326f5d3f56943654879171d4">getEmitCallSiteInfo</a>, <a href="#a9370b49cbad17c2c86cc50e704067b35">getEnableAddrsig</a>, <a href="#adb4f67729dab4f6ab7aeb9342abf10f8">getEnableAIXExtendedAltivecABI</a>, <a href="#a691ff4984dacf7b4f27e8b0350521f0a">getEnableApproxFuncFPMath</a>, <a href="#ac9f8128eee9736ef41459f165fc2ec29">getEnableBBAddrMap</a>, <a href="#ad18c990cedef3c0529a23875dee0e4e7">getEnableDebugEntryValues</a>, <a href="#a125f32703c7db054483f564eeec2415f">getEnableGuaranteedTailCallOpt</a>, <a href="#ae64bdb0691c2f646b81277ba22c09ead">getEnableHonorSignDependentRoundingFPMath</a>, <a href="#a4d34f81b8273bfb69907f9de9177a5dd">getEnableMachineFunctionSplitter</a>, <a href="#ab0e28b0bdfe4de336d0960c12c738565">getEnableNoInfsFPMath</a>, <a href="#aea42629187535abb89fadbc99af28d92">getEnableNoNaNsFPMath</a>, <a href="#a2edbaee080d3f4653926c746a1a62206">getEnableNoSignedZerosFPMath</a>, <a href="#ac4fb8e62075af9452d5da53943d6a70a">getEnableNoTrappingFPMath</a>, <a href="#a2f3fc58d3d3b03968c1b9473c2d2298f">getEnableStackSizeSection</a>, <a href="#aa58dafa2045a626d96be66ae8acd6bb3">getEnableUnsafeFPMath</a>, <a href="#a8a5ffa3158003a3a67d5543c6b555b44">getExceptionModel</a>, <a href="#a424f07efd7eabcc59bc4baabf2f84d80">getExplicitDataSections</a>, <a href="#a4449215bf59439710d0f500b7d836a49">getExplicitEmulatedTLS</a>, <a href="#a30d3ad309386a3575403c82dd2f9190a">getExplicitEnableTLSDESC</a>, <a href="#a530a05cfcb84b34e1251fa7dcedff8be">getFloatABIForCalls</a>, <a href="#ac098fe7e12d3f39573f9d98c43cd9a1b">getForceDwarfFrameSection</a>, <a href="#ad50187850d5980d8fbed509ca3f598e9">getFunctionSections</a>, <a href="#acc67880adf1a1beba830f126b398b3b6">getFuseFPOps</a>, <a href="#a3ca52fc0188400242c346a47729b9cc3">getIgnoreXCOFFVisibility</a>, <a href="#ad30abb8a5e54b7546aa2b67f1da5f892">getJMCInstrument</a>, <a href="#aafb615678bb953de89ebd1ec2ad29f46">getSeparateNamedSections</a>, <a href="#adf57e616420aed51492697bd2e9f2285">getStackSymbolOrdering</a>, <a href="#aeb6eb7dfbe48fb3ef0f2cb5f72ece268">getSwiftAsyncFramePointer</a>, <a href="#adbb443f8d5a8c771271dca65579ec773">getThreadModel</a>, <a href="#a4a54ccc28ad7c9cd0fb9e05c9d7ae945">getTLSSize</a>, <a href="#ab95fa39bfefbff3234ca6e5601cba879">getUniqueBasicBlockSectionNames</a>, <a href="#a2a1161081d2201c5ab733a89008a36d7">getUniqueSectionNames</a>, <a href="#ad24646b72aaf03da094431ba8a342984">getUseCtors</a>, <a href="#ab727dce0ceebeb28287f5f9d62fd4011">getXCOFFReadOnlyPointers</a>, <a href="#aef0603845494c343f152969e2c58448b">getXCOFFTracebackTable</a>, <a href="#a70b09452206f224495ed9f0df8f287c8">getXRayFunctionIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a553e5eede76e94cc97f728aee36cec71">llvm::Triple::hasDefaultDataSections</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#ade012f998cea3bc03f6da0b08d422e6c">llvm::Triple::hasDefaultEmulatedTLS</a>, <a href="/web-llvm/docs/api/classes/llvm/triple/#a3f39ef170cc0043edb23a89216122e18">llvm::Triple::hasDefaultTLSDESC</a>, <a href="/web-llvm/docs/api/namespaces/llvm/mc/#a40c84135f8f6afce28578f48f4b2cb15">llvm::mc::InitMCTargetOptionsFromFlags</a>, <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a> and <a href="/web-llvm/docs/api/files/lib/lib/debuginfo/lib/debuginfo/logicalview/lib/debuginfo/logicalview/core/lvoptions-cpp/#ab4088b7a11f3cbc38ac16a6e9c72494e">Options</a>.</p>


<p>Referenced by <a href="#a8f10e936389f0129adc2f5ded44fdd9a">createTargetMachineForTriple</a> and <a href="#ac754b19265fec508188376da454f57f9">InitTargetOptionsFromCodeGenFlags</a>.</p>

</div>
</div>

### renderBoolStringAttr() {#a369cd19a81f5a9fee165657340331984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::codegen::renderBoolStringAttr (<a href="/web-llvm/docs/api/classes/llvm/attrbuilder">AttrBuilder</a> &amp; B, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name, bool Val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 652 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a> and <a href="#a369cd19a81f5a9fee165657340331984">renderBoolStringAttr</a>.</p>


<p>Referenced by <a href="#a369cd19a81f5a9fee165657340331984">renderBoolStringAttr</a>.</p>

</div>
</div>

### setFunctionAttributes() {#ac12e315180fb16cb5874fb41526ca453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::codegen::setFunctionAttributes (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Features, <a href="/web-llvm/docs/api/classes/llvm/function">Function</a> &amp; F)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set function attributes of function <span class="doxyComputerOutput">F</span> based on CPU, Features, and command line flags.</p>

<p>Declaration at line 184 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/attrbuilder/#a59d23ba2e7eac46cbc6cd3086e013b49">llvm::AttrBuilder::addAttribute</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c7a337870929cbf2d49865f77c42927ab1c94ca2fbc3e78fc30069c8d0f01680">llvm::All</a>, <a href="/web-llvm/docs/api/classes/llvm/smallstring/#ac22cf1a1c08b7ccaefc51508536312a4">llvm::SmallString&lt; InternalLen &gt;::append</a>, <a href="/web-llvm/docs/api/files/lib/lib/ir/builtingcs-cpp/#ae76959fe811ba090de4cba69ac00f1da">B</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/stringref/#a2dc80c585ad5882da8cae7b5968f7e74">llvm::StringRef::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/classes/llvm/attribute/#a43708098bd7085788a680fd02f47c750">llvm::Attribute::get</a>, <a href="#ac3cd3b022a25351c87713a0417a1bb34">getDenormalFP32Math</a>, <a href="#a226d6d3bf846f18b7ab2746594212a94">getDenormalFPMath</a>, <a href="#abb7ea8627703f2975049ebe75efad586">getDisableTailCalls</a>, <a href="#a2e49ecab2560cbdcda6ff4b08dccb081">getFramePointerUsage</a>, <a href="#aa8a10f776401e9fb0710a2667f9adec3">getStackRealign</a>, <a href="#a7e4a8fa158773962eebeff35e1304732">getTrapFuncName</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp/#ac72d2c3ae69aab8e09c5b4d0efdd6832">HANDLE_BOOL_ATTR</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c7a337870929cbf2d49865f77c42927a6adf97f83acf6453d4a6a4b1070f3754">llvm::None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c7a337870929cbf2d49865f77c42927a805ba1a33cd069fad77f8f0f0b3401ee">llvm::NonLeaf</a>, <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a0c7a337870929cbf2d49865f77c42927a942d4e37dd5607ab68e54755540d4a47">llvm::Reserved</a> and <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>


<p>Referenced by <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a> and <a href="#ae117c75f2be19f0290f82a1ff1352842">setFunctionAttributes</a>.</p>

</div>
</div>

### setFunctionAttributes() {#ae117c75f2be19f0290f82a1ff1352842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::codegen::setFunctionAttributes (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Features, <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> &amp; M)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set function attributes of functions in <a href="/web-llvm/docs/api/classes/llvm/module">Module</a> M based on CPU, Features, and command line flags.</p>

<p>Declaration at line 188 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a>, definition at line 743 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a> and <a href="#ac12e315180fb16cb5874fb41526ca453">setFunctionAttributes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/commandflags-h">CommandFlags.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/commandflags-cpp">CommandFlags.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
