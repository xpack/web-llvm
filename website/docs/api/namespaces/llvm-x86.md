---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/x86
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `X86` Namespace Reference

<p>Define some predicates that are used for node matching. <a href="#details">More...</a></p>

## Definition

<div class="doxyDefinition">
namespace llvm::X86 { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProcessorVendors : unsigned { <a href="#a10bb9c1f7f54a5dfca9e11ab46dbea63">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProcessorTypes : unsigned { <a href="#adc617f881cab7ced514a31d188549455">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProcessorSubtypes : unsigned { <a href="#ac0d054a76f2d9b9a8966e040df061340">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">ProcessorFeatures { <a href="#abd1f712df4639ee306f3295384cb9a49">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CPUKind { <a href="#aaf0c3e7727bf6e2922b7f28dd49cc9be">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a9521379dc6a712ea55b832e0dfb859e7">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a2a5aec578e2e391e99e1705012752d84">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">STATIC_ROUNDING { <a href="#a2a6ba37884c11b538aa6ebb0a4a8fa08">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>AVX512 static rounding constants. <a href="#a2a6ba37884c11b538aa6ebb0a4a8fa08">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">IPREFIXES { <a href="#ab45f29eafca4acc2a7240156af5ec350">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The constants to describe instr prefixes if there are. <a href="#ab45f29eafca4acc2a7240156af5ec350">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">OperandType : unsigned { <a href="#a14391534703c3dd099e58439c6709c58">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CondCode { <a href="#a1a356a51a1fb4cc3c427599082cf1d2e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">FirstMacroFusionInstKind { <a href="#a86730e94ae6fdf0fe3145b2acc88dea8">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">SecondMacroFusionInstKind { <a href="#a3674fa9b225c107451c80b215815a31e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AlignBranchBoundaryKind : uint8_t { <a href="#a1fe75f600f6eea354189c898829a9465">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines the possible values of the branch boundary alignment mask. <a href="#a1fe75f600f6eea354189c898829a9465">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EncodingOfSegmentOverridePrefix : uint8_t { <a href="#a320797eb50409965820a431a75d69645">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Defines the encoding values for segment override prefix. <a href="#a320797eb50409965820a431a75d69645">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Fixups { <a href="#af437e70f011e7e19b5614a0b8f9531fc">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">AsmComments { <a href="#ac6417d5ffb5083fa98bcae081c2c75aa">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">anonymous enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"> { <a href="#a2ede8334e026220fc2f2884ba0aba7b6">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">RoundingMode { <a href="#a0910938d5634351e328c24b302cf2df0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Current rounding mode is represented in bits 11:10 of FPSR. <a href="#a0910938d5634351e328c24b302cf2df0">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaf0c3e7727bf6e2922b7f28dd49cc9be">CPUKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b9cff715f1fc97546de75b2b79d03af">parseArchX86</a> (StringRef CPU, bool Only64Bit=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse <span class="doxyComputerOutput">CPU</span> string into a <a href="#aaf0c3e7727bf6e2922b7f28dd49cc9be">CPUKind</a>. <a href="#a5b9cff715f1fc97546de75b2b79d03af">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaf0c3e7727bf6e2922b7f28dd49cc9be">CPUKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a320e1de56e30c1bb64817f68d5db20bd">parseTuneCPU</a> (StringRef CPU, bool Only64Bit=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0d434e57456cc7f4c031e7fd01d48c3">fillValidCPUArchList</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Values, bool Only64Bit=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a list of valid CPU names. <a href="#af0d434e57456cc7f4c031e7fd01d48c3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cf2bfeeb9890df12a673f10933a34b4">fillValidTuneCPUList</a> (SmallVectorImpl&lt; StringRef &gt; &amp;Values, bool Only64Bit=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Provide a list of valid -mtune names. <a href="#a8cf2bfeeb9890df12a673f10933a34b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abd1f712df4639ee306f3295384cb9a49">ProcessorFeatures</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd96c9db878796ece2654dde1588338">getKeyFeature</a> (CPUKind Kind)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the key feature prioritizing target multiversioning. <a href="#afcd96c9db878796ece2654dde1588338">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a64d327c5a0be28d5936e30ff02709a">getFeaturesForCPU</a> (StringRef CPU, SmallVectorImpl&lt; StringRef &gt; &amp;Features, bool NeedPlus=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Fill in the features that <span class="doxyComputerOutput">CPU</span> supports into <span class="doxyComputerOutput">Features</span>. <a href="#a9a64d327c5a0be28d5936e30ff02709a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a506819ac2ff216f44dd9674f2bebd80b">updateImpliedFeatures</a> (StringRef Feature, bool Enabled, StringMap&lt; bool &gt; &amp;Features)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Set or clear entries in <span class="doxyComputerOutput">Features</span> that are implied to be enabled/disabled by the provided <span class="doxyComputerOutput">Feature</span>. <a href="#a506819ac2ff216f44dd9674f2bebd80b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20c881595243317947b9fbce4e8556da">getCPUDispatchMangling</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3cedda0cef897f8206784454d65b91b">validateCPUSpecificCPUDispatch</a> (StringRef Name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; uint32_t, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16daa0658cce2a2c4465febd770d8aca">getCpuSupportsMask</a> (ArrayRef&lt; StringRef &gt; FeatureStrs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad77822367a3ea927da01c1b89ee4e415">getFeaturePriority</a> (ProcessorFeatures Feat)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a86730e94ae6fdf0fe3145b2acc88dea8">FirstMacroFusionInstKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c23473fe38a9c1e631c30965c4ca469">classifyFirstOpcodeInMacroFusion</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3674fa9b225c107451c80b215815a31e">SecondMacroFusionInstKind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca38f4b2343c6b84e1eb8b91fbc8d5c0">classifySecondCondCodeInMacroFusion</a> (X86::CondCode CC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee53d7204e2f79dea3df2633db61b104">isMacroFused</a> (FirstMacroFusionInstKind FirstKind, SecondMacroFusionInstKind SecondKind)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a320797eb50409965820a431a75d69645">EncodingOfSegmentOverridePrefix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a223fa35bcfebf3149a762a7ede4303">getSegmentOverridePrefixForReg</a> (MCRegister Reg)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Given a segment register, return the encoding of the segment override prefix for it. <a href="#a5a223fa35bcfebf3149a762a7ede4303">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aade8574cba756ffdc426344718ada414">optimizeInstFromVEX3ToVEX2</a> (MCInst &amp;MI, const MCInstrDesc &amp;Desc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88575ba0f198af79c61ba3a8c27a69d8">optimizeShiftRotateWithImmediateOne</a> (MCInst &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a76d5022aceb3599fdcaf0ef25ee3ce73">optimizeVPCMPWithImmediateOneOrSix</a> (MCInst &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a690516c8cb802c97acc69f6363735984">optimizeMOVSX</a> (MCInst &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0e27cbc3acd22d76564e1f3ac9b8311">optimizeINCDEC</a> (MCInst &amp;MI, bool In64BitMode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e5a30d596e5e8933a926e2d14d5227f">optimizeMOV</a> (MCInst &amp;MI, bool In64BitMode)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Simplify things like MOV32rm to MOV32o32a. <a href="#a3e5a30d596e5e8933a926e2d14d5227f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0256d671ff2830d0ada28b07b9c7ab25">optimizeToFixedRegisterOrShortImmediateForm</a> (MCInst &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af62df4b10560106717f6147a74bf446d">getOpcodeForShortImmediateForm</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4ef8f6d88ba8604aa83ce35440fd8fb">getOpcodeForLongImmediateForm</a> (unsigned Opcode)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::pair&lt; <a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a>, bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a973a0a53d9270a750d4c8a117fa71317">getX86ConditionCode</a> (CmpInst::Predicate Predicate)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a pair of condition code for the given predicate and whether the instruction operands should be swaped to match the condition code. <a href="#a973a0a53d9270a750d4c8a117fa71317">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af569f4e4b0acf498c83fa0e58e2eb364">getCMovOpcode</a> (unsigned RegBytes, bool HasMemoryOperand=false, bool HasNDD=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a cmov opcode for the given register size in bytes, and operand type. <a href="#af569f4e4b0acf498c83fa0e58e2eb364">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae0006f60cff07edc54c729003feab6c">getCondSrcNoFromDesc</a> (const MCInstrDesc &amp;MCID)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the source operand # for condition code by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/mcid">MCID</a></span>. <a href="#aae0006f60cff07edc54c729003feab6c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20086d3d5e4bf090cf298a125fab1b89">getCondFromMI</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the condition code of the instruction. <a href="#a20086d3d5e4bf090cf298a125fab1b89">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f2b2ef8f4560ffd46c7966e8315142f">getCondFromBranch</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4843a98a8b18a9d745dfe2a882ccf3b">getCondFromSETCC</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff28d9a4811f627c5254a305f36b55cd">getCondFromCMov</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13508fbf99bc5c958d5b14ffbfdef94b">getCondFromCFCMov</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad0de83dbe4b099f263fa9c08f7aa818">getCondFromCCMP</a> (const MachineInstr &amp;MI)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaddbb5e92a9b873f175fff89399245d1">getCCMPCondFlagsFromCondCode</a> (CondCode CC)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8606eab304dcbb9e0bb4b3597c49675">getNFVariant</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f5a82ba9421c1c89257282ca65b4c23">getNonNDVariant</a> (unsigned Opc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c06f5a972e8a78052103840a8c98a3f">GetOppositeBranchCondition</a> (CondCode CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>GetOppositeBranchCondition - Return the inverse of the specified cond, e.g. <a href="#a5c06f5a972e8a78052103840a8c98a3f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fcee8e11458a08892fc937a9f428966">getVPCMPImmForCond</a> (ISD::CondCode CC)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the VPCMP immediate for the given condition. <a href="#a8fcee8e11458a08892fc937a9f428966">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa640b399dea5c08e52b71c3a2736d61c">getSwappedVPCMPImm</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the VPCMP immediate if the opcodes are swapped. <a href="#aa640b399dea5c08e52b71c3a2736d61c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a654d8db751a92fed6c83508010b3de64">getSwappedVPCOMImm</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the VPCOM immediate if the opcodes are swapped. <a href="#a654d8db751a92fed6c83508010b3de64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4da6ce26c64d4eaea82afb6f37f4125a">getSwappedVCMPImm</a> (unsigned Imm)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the VCMP immediate if the opcodes are swapped. <a href="#a4da6ce26c64d4eaea82afb6f37f4125a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9123ce22c3cada196c14e31be149c6e">getVectorRegisterWidth</a> (const MCOperandInfo &amp;Info)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the width of the vector register operand. <a href="#af9123ce22c3cada196c14e31be149c6e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a740bc8dd5f4846acc274f39b05c1ac14">isX87Instruction</a> (MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction is X87 instruction. <a href="#a740bc8dd5f4846acc274f39b05c1ac14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a279395a00a782f7e3d6141bc3328a249">getFirstAddrOperandIdx</a> (const MachineInstr &amp;MI)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the index of the instruction's first address operand, if it has a memory reference, or -1 if it has none. <a href="#a279395a00a782f7e3d6141bc3328a249">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7d20e7a4f79f39c97b3329389c8db88">getConstantFromPool</a> (const MachineInstr &amp;MI, unsigned OpNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Find any constant pool entry associated with a specific instruction operand. <a href="#ab7d20e7a4f79f39c97b3329389c8db88">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae914ecbf92d09be7f8da203ec3dd5bbc">isConstantSplat</a> (SDValue Op, APInt &amp;SplatVal, bool AllowPartialUndefs=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>If <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a constant whose elements are all the same constant or undefined, return true and return the constant value in <span class="doxyComputerOutput">SplatVal</span>. <a href="#ae914ecbf92d09be7f8da203ec3dd5bbc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43e102a1c33f2dffc750026a05828f52">isZeroNode</a> (SDValue Elt)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if Elt is a constant zero or floating point constant +0.0. <a href="#a43e102a1c33f2dffc750026a05828f52">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d9870049dd4eaa5938dd4e920d354a">isOffsetSuitableForCodeModel</a> (int64_t Offset, CodeModel::Model M, bool hasSymbolicDisplacement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true of the given offset can be fit into displacement field of the instruction. <a href="#ac5d9870049dd4eaa5938dd4e920d354a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98bec313edd88412de74ae369ce47005">isCalleePop</a> (CallingConv::ID CallingConv, bool is64Bit, bool IsVarArg, bool GuaranteeTCO)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determines whether the callee is required to pop its own arguments. <a href="#a98bec313edd88412de74ae369ce47005">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aafd16108bb2bfb19eed47e23dcbee3dd">mayFoldLoad</a> (SDValue Op, const X86Subtarget &amp;Subtarget, bool AssumeSingleUse=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a load operation that could be folded into some other x86 instruction as a memory operand. <a href="#aafd16108bb2bfb19eed47e23dcbee3dd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316352587c836a0388b90aec4531450a">mayFoldLoadIntoBroadcastFromMem</a> (SDValue Op, MVT EltVT, const X86Subtarget &amp;Subtarget, bool AssumeSingleUse=false)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a load operation that could be folded into a vector splat instruction as a memory operand. <a href="#a316352587c836a0388b90aec4531450a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a670aa0012e26bf3d40dfa5068743ac48">mayFoldIntoStore</a> (SDValue Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a value that could be used to fold a store into some other x86 instruction as a memory operand. <a href="#a670aa0012e26bf3d40dfa5068743ac48">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60cb51706fb77e669933216aaf2c1e1f">mayFoldIntoZeroExtend</a> (SDValue Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is an operation that could be folded into a zero extend x86 instruction. <a href="#a60cb51706fb77e669933216aaf2c1e1f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a738e789cdbd35bf07b744925b6f6ae4e">isExtendedSwiftAsyncFrameSupported</a> (const X86Subtarget &amp;Subtarget, const MachineFunction &amp;MF)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>True if the target supports the extended frame for async Swift functions. <a href="#a738e789cdbd35bf07b744925b6f6ae4e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel">FastISel</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac370a59c2440ede047ceeea4ac9e9f77">createFastISel</a> (FunctionLoweringInfo &amp;funcInfo, const TargetLibraryInfo *libInfo)</td>
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

## Description {#details}

<p>Define some predicates that are used for node matching.</p>

<div class="doxySectionDef">

## Enumerations

### anonymous enum  {#a9521379dc6a712ea55b832e0dfb859e7}

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
<td class="doxyEnumItemName">BX_SI<a id="a9521379dc6a712ea55b832e0dfb859e7a054eabdfa18b90440948ed7de90566f6"></a></td>
<td class="doxyEnumItemDescription"> (= 500)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BX_DI<a id="a9521379dc6a712ea55b832e0dfb859e7a479de3ea37ad5b24dd2965b879747f6b"></a></td>
<td class="doxyEnumItemDescription"> (= 501)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BP_SI<a id="a9521379dc6a712ea55b832e0dfb859e7a9ab738e845db4698317ac000ef40e1fa"></a></td>
<td class="doxyEnumItemDescription"> (= 502)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BP_DI<a id="a9521379dc6a712ea55b832e0dfb859e7a08bf612dd15d4704289288f0e2467158"></a></td>
<td class="doxyEnumItemDescription"> (= 503)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">sib<a id="a9521379dc6a712ea55b832e0dfb859e7ac3848eebb47273fc0d103aa6e8f2b792"></a></td>
<td class="doxyEnumItemDescription"> (= 504)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">sib64<a id="a9521379dc6a712ea55b832e0dfb859e7a3988fbb34b7d4089448cf3bf2c2e21d2"></a></td>
<td class="doxyEnumItemDescription"> (= 505)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1817 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a>.</p>

</div>
</div>

### anonymous enum  {#a2a5aec578e2e391e99e1705012752d84}

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
<td class="doxyEnumItemName">AddrBaseReg<a id="a2a5aec578e2e391e99e1705012752d84a319f0e99a1ac9396659683d2638d4f45"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrScaleAmt<a id="a2a5aec578e2e391e99e1705012752d84a353f20f0404222671129b3d31f7ffc7b"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrIndexReg<a id="a2a5aec578e2e391e99e1705012752d84aba7ebe0e28a2c1c4c14343f549c01462"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrDisp<a id="a2a5aec578e2e391e99e1705012752d84a93474770cf1401679ba37e1833632e58"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrSegmentReg<a id="a2a5aec578e2e391e99e1705012752d84a8fed367c46e025e4269e9725a94391b6"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddrNumOperands<a id="a2a5aec578e2e391e99e1705012752d84ac4169d78e1c6de9b189f31b90f1c2691"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### anonymous enum  {#a2ede8334e026220fc2f2884ba0aba7b6}

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
<td class="doxyEnumItemName">MaxShuffleCombineDepth<a id="a2ede8334e026220fc2f2884ba0aba7b6af20ba120fee712e351cd784e6142a6e6"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 40709 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>

</div>
</div>

### AlignBranchBoundaryKind {#a1fe75f600f6eea354189c898829a9465}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::AlignBranchBoundaryKind : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Defines the possible values of the branch boundary alignment mask.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignBranchNone<a id="a1fe75f600f6eea354189c898829a9465ad1140457ba32a450d106fc2010ff66db"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignBranchFused<a id="a1fe75f600f6eea354189c898829a9465aee32f1149f4d72dc0e46c30ef99b842b"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignBranchJcc<a id="a1fe75f600f6eea354189c898829a9465a7904634a4e129754fb211d0354b3a6bb"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignBranchJmp<a id="a1fe75f600f6eea354189c898829a9465a1dc5d1078370bcbec902b4f77717fcbb"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignBranchCall<a id="a1fe75f600f6eea354189c898829a9465a811cb1d3685783424b497490d8160748"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignBranchRet<a id="a1fe75f600f6eea354189c898829a9465a9388c83a18d9ce13014ece823bd6f38f"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlignBranchIndirect<a id="a1fe75f600f6eea354189c898829a9465a60803679066b49a1f08d68aae9f57000"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 5)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 309 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### AsmComments {#ac6417d5ffb5083fa98bcae081c2c75aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::AsmComments </td>
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
<td class="doxyEnumItemName">AC_EVEX_2_LEGACY<a id="ac6417d5ffb5083fa98bcae081c2c75aaab5e973c821bc6607bd92a290f63a3cbd"></a></td>
<td class="doxyEnumItemDescription"> (= MachineInstr::TAsmComments)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AC_EVEX_2_VEX<a id="ac6417d5ffb5083fa98bcae081c2c75aaa8bd2d6952c01be113164446873c84c66"></a></td>
<td class="doxyEnumItemDescription"> (= AC_EVEX_2_LEGACY &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AC_EVEX_2_EVEX<a id="ac6417d5ffb5083fa98bcae081c2c75aaa125f1c180c3593a7ac6a2b350cc3d75a"></a></td>
<td class="doxyEnumItemDescription"> (= AC_EVEX_2_VEX &lt;&lt; 1)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>.</p>

</div>
</div>

### CondCode {#a1a356a51a1fb4cc3c427599082cf1d2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::CondCode </td>
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
<td class="doxyEnumItemName">COND_O<a id="a1a356a51a1fb4cc3c427599082cf1d2ea914c19eb31606e70fd4f8dfff6d86038"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_NO<a id="a1a356a51a1fb4cc3c427599082cf1d2eade1f36af81eae7e7b5b333d77de5feeb"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_B<a id="a1a356a51a1fb4cc3c427599082cf1d2eac9ae7c779ffc6865536d9f164ebf09b9"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_AE<a id="a1a356a51a1fb4cc3c427599082cf1d2eafeeb44274a14a14010dc990daecb39a0"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_E<a id="a1a356a51a1fb4cc3c427599082cf1d2ea80da60ed5c7b20653afe0b4b21a91ec1"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_NE<a id="a1a356a51a1fb4cc3c427599082cf1d2eacb2f86eaebe8b719f743d17a2d5a5f3d"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_BE<a id="a1a356a51a1fb4cc3c427599082cf1d2eaaf9d50e29346a1094fb35045851db856"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_A<a id="a1a356a51a1fb4cc3c427599082cf1d2eade92e2f17ca0acdd1ffa23d01df381df"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_S<a id="a1a356a51a1fb4cc3c427599082cf1d2eaeb72ca445848c39685fff16f97825475"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_NS<a id="a1a356a51a1fb4cc3c427599082cf1d2ea73469030600320118cd4a02f934ca9bc"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_P<a id="a1a356a51a1fb4cc3c427599082cf1d2eaff7502cc3be1c359dca73814c6c34c6f"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_NP<a id="a1a356a51a1fb4cc3c427599082cf1d2ea4af201423e9be297ec72e1ac6ad77063"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_L<a id="a1a356a51a1fb4cc3c427599082cf1d2eaf40beda0a4322699215cb85d7d6667b6"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_GE<a id="a1a356a51a1fb4cc3c427599082cf1d2ea3547c8602aab6b0319c8052f8583613b"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_LE<a id="a1a356a51a1fb4cc3c427599082cf1d2eae364c60967a7bc453d49caffc07d7bef"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_G<a id="a1a356a51a1fb4cc3c427599082cf1d2ea874bd4784391ae60bfdbc12d1f10bc73"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LAST_VALID_COND<a id="a1a356a51a1fb4cc3c427599082cf1d2ea2484e939ba4da4cd9030456de2f5fb75"></a></td>
<td class="doxyEnumItemDescription"> (= COND_G)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_NE_OR_P<a id="a1a356a51a1fb4cc3c427599082cf1d2ea8b47d4d3f261caf07338c6775a08a2bc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_E_AND_NP<a id="a1a356a51a1fb4cc3c427599082cf1d2ea4244390c8621e6f061fad8fe2f6fc3a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">COND_INVALID<a id="a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### CPUKind {#aaf0c3e7727bf6e2922b7f28dd49cc9be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::CPUKind </td>
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
<td class="doxyEnumItemName">CK_None<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beab9c9853de4af742b0ccd4dbc9e38c7c9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_i386<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaa6d26d5623069057a0197fb396c271f9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_i486<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea253f6a25c93eb7f93c687370724eea91"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_WinChipC6<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea02d0f2327c50b9692b83f2bf98a0aa41"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_WinChip2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaffcf6ce39f8bd4374062e6ea12cf6dbb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_C3<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea6555884747dd519f14d8768ecb8845d4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_i586<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beacc6eabab93c0437f1520a619fcd510b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Pentium<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea985488b80dfc57cf1cef660c0b3dd24d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_PentiumMMX<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea0670d3bea5523a391c44bf4af20492e8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_PentiumPro<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea184ff21b1c6e26e2288b498e1e0672ee"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_i686<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beac80ec761c9e99c240e99089444619b5e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Pentium2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea7b33b19d366043f801b3efa6e3e0b38c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Pentium3<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea3210b8ce456fb9273193856a014f9dbc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_PentiumM<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea3a08889386cfc9f9141970fe41d3498a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_C3_2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea760c4349cb5884077afecb8604e095fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Yonah<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaa9bb27ddc785b44128e842c0fdff34c4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Pentium4<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea0addc57edd39564e9d519acc926e09b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Prescott<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beab7c66e1a549bbbc9eff2540874a1ea34"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Nocona<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beafa33cd8fa5cce9751eb6786998cd3145"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Core2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea28be2a8469df72959f0a512116478c0f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Penryn<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beabb04a68e7555b10edbb1f422a082d2f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Bonnell<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beace078b71da2753df10706ff7a66d3fab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Silvermont<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea6d9e85b021577f3c8b61f31567dc44aa"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Goldmont<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea1ab46c36f978d67d8659169d16f371ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_GoldmontPlus<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beac48eb11e3534f709b641d23703faa6ab"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Tremont<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea1b6f184cfbc99e0265bdc13fa450a528"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Gracemont<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea5f337b9f730f6bbe33faf1d60c2f500b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Nehalem<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea06dea2197c752c27e20424638fafc5b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Westmere<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beafccbcbdc1564a06191020f1c7e2c63b4"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_SandyBridge<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea67a8e735df8aa4029f9581cb8d12739f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_IvyBridge<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea10d737512974da874ee4bf56c2b03502"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Haswell<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bead3113d0c281d722c3eec633c774f2106"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Broadwell<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea6259b545df1c3ed08adf2dc2096234a7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_SkylakeClient<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea6000435f57c7c1f058575aa312d5b8f6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_SkylakeServer<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea8eff090eeaa710e3fd57a3772d14d67c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Cascadelake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaac08f1c6e57c8ac50640cc9b88fc42fb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Cooperlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea8b81e116e493006161a127dc576b84cf"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Cannonlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea0ff5f88357ea173140a83e2786d3b449"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_IcelakeClient<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea830633ccdbd5e57c047ec2c29a1bc01c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Rocketlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beac2f78482e0ee952a4eecbd4f45d15036"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_IcelakeServer<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beab5fd63c7a3d71f218898b848b1754d3b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Tigerlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea4f3389d6524bae1b5c14eb72bd12e4fc"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_SapphireRapids<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea1404d1d0bfc50a7064558155e8f276cb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Alderlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beae86e3a04c8718020fe61a25847770f35"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Raptorlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea6f590413cadbf3712b2c357031b2ddfe"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Meteorlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bead30f816b4d3d6e4491c42c954757f722"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Arrowlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea9fb8cba5c0c339ca3da72e777b25b799"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_ArrowlakeS<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea2a67a46c0061bef6c7cd304871afb614"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Lunarlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea31702b05b724ffcab9301e225f95fbe1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Pantherlake<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beae6a45bf4f4bc22ff460480a201173d9f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Sierraforest<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea579688800a17307d2d2e82168fd1f3e2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Grandridge<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea989584e08f3f2851ed1b1ab4d6203d4b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Graniterapids<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea2b264e757bd6939677451e1c194ba9fd"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_GraniterapidsD<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea61d795cc1153759636d028262cd32108"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Emeraldrapids<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beadae31db8dab236ee6ead656b61bd91d3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Clearwaterforest<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beafa283478f0b65681a77afde6ab09694d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Diamondrapids<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea3b8b58a629ae2b4c2233e4da28046c86"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_KNL<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea9c32c313b679be0052d0762340a493f8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_KNM<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beac76e24b32233c53d4f6630b1a7df25b5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Lakemont<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea0bd2c23328f9164b8987c01d8e16b613"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_K6<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea695211d3e5f51ad026c1130be968085c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_K6_2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea9901a052017976934db7ea86094fd744"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_K6_3<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea0e0b397b4d88930d25d597976c599894"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Athlon<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea1438583b134b7c4a26d71ebfcc5b2576"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_AthlonXP<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaf09468fab845c56fb572ed8b44c1e80a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_K8<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beae8a02d74fdfbc0f32e96aa166781ec36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_K8SSE3<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaae152f2fa95f2344677369b77b7eef93"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_AMDFAM10<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea9636f9aeb702fa8d4c06dc43138ca613"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_BTVER1<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea093344ab97a4715b87bbd7ccf997a2a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_BTVER2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea7ff298ce0815a6a36e7d99bd458a86a6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_BDVER1<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea0adbd63f913e03edd3b01c46746402bb"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_BDVER2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea9346f9464158af2a636dc811d9480ac0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_BDVER3<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaff20d8fd099c212c4c482d81522f5649"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_BDVER4<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beab3d6f5d265a673e3e86557269d57c252"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_ZNVER1<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea2956afa289808ac16809ecdb58d20fa9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_ZNVER2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beae96349ffa6d50b65b3438da29a1826e1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_ZNVER3<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea02ae376955ed3aed27a0110ab7a06155"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_ZNVER4<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea706fc45e026136fbb77aadf139ab1846"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_ZNVER5<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beae683617c23a991fcf85f5f93e6855e63"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_x86_64<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beaada756391911f145a28b57b534b120e5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_x86_64_v2<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beafa2f6a18196e8d7c19142b734b25295f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_x86_64_v3<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea699a63cef51206ab439ecd38735e5b07"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_x86_64_v4<a id="aaf0c3e7727bf6e2922b7f28dd49cc9beac76e6f66dab76514eaaa618422510530"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CK_Geode<a id="aaf0c3e7727bf6e2922b7f28dd49cc9bea7d680e617b33cb8875c4e7f77ff898f2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 67 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>.</p>

</div>
</div>

### EncodingOfSegmentOverridePrefix {#a320797eb50409965820a431a75d69645}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::EncodingOfSegmentOverridePrefix : uint8_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Defines the encoding values for segment override prefix.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CS_Encoding<a id="a320797eb50409965820a431a75d69645a6b07c0b372000f1c9d4dc8aad224c513"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2E)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DS_Encoding<a id="a320797eb50409965820a431a75d69645ae6eef90bcf399314a8e7038d721aa6de"></a></td>
<td class="doxyEnumItemDescription"> (= 0x3E)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ES_Encoding<a id="a320797eb50409965820a431a75d69645a5517951ce8dbe938c85f5e966dfc0a11"></a></td>
<td class="doxyEnumItemDescription"> (= 0x26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FS_Encoding<a id="a320797eb50409965820a431a75d69645ad149e634798a2cca9126fba777295803"></a></td>
<td class="doxyEnumItemDescription"> (= 0x64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GS_Encoding<a id="a320797eb50409965820a431a75d69645a2f9896117daa729a2c816d010be4cf2b"></a></td>
<td class="doxyEnumItemDescription"> (= 0x65)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SS_Encoding<a id="a320797eb50409965820a431a75d69645a9398d374cb6482bfc772443c98b46eb6"></a></td>
<td class="doxyEnumItemDescription"> (= 0x36)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 320 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### FirstMacroFusionInstKind {#a86730e94ae6fdf0fe3145b2acc88dea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::X86::FirstMacroFusionInstKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Test<a id="a86730e94ae6fdf0fe3145b2acc88dea8a0cbc6611f5540bd0809a388dc95a615b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Cmp<a id="a86730e94ae6fdf0fe3145b2acc88dea8ac9b4c62f6dc1bc5caf3c768b687cbf7e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">And<a id="a86730e94ae6fdf0fe3145b2acc88dea8ac33315685a0cba3ce53be378b3c7874b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AddSub<a id="a86730e94ae6fdf0fe3145b2acc88dea8aeec8d71daba88ee810b0d97fe8aa3c7b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IncDec<a id="a86730e94ae6fdf0fe3145b2acc88dea8a484d31015dbdf6199510633f4f3446be"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a86730e94ae6fdf0fe3145b2acc88dea8a4bbb8f967da6d1a610596d7257179c2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 107 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### Fixups {#af437e70f011e7e19b5614a0b8f9531fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::Fixups </td>
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
<td class="doxyEnumItemName">reloc_riprel_4byte<a id="af437e70f011e7e19b5614a0b8f9531fcaea3ac30c46fc4086e0fac8473ece1f8b"></a></td>
<td class="doxyEnumItemDescription"> (= FirstTargetFixupKind)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_riprel_4byte_movq_load<a id="af437e70f011e7e19b5614a0b8f9531fcacd0ed684ad2d4c067ca938d45567540c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_riprel_4byte_movq_load_rex2<a id="af437e70f011e7e19b5614a0b8f9531fca303862a22911ad0a16f5f88c89d7c105"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_riprel_4byte_relax<a id="af437e70f011e7e19b5614a0b8f9531fca711b77689359fcf4cb49f96b5571d5c0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_riprel_4byte_relax_rex<a id="af437e70f011e7e19b5614a0b8f9531fca962ed593088a527512dad825d971922e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_riprel_4byte_relax_rex2<a id="af437e70f011e7e19b5614a0b8f9531fcaea71f97aa32a2a3fabf01372d4079a5c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_riprel_4byte_relax_evex<a id="af437e70f011e7e19b5614a0b8f9531fca7b4bcca3a40ad945a73f1c1d199c6362"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_signed_4byte<a id="af437e70f011e7e19b5614a0b8f9531fca8b029ea6e687fd2d4caf13cbbe2cde08"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_signed_4byte_relax<a id="af437e70f011e7e19b5614a0b8f9531fca372de3ecc0967f0c818089f93138a0de"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_global_offset_table<a id="af437e70f011e7e19b5614a0b8f9531fcac5689c8a9dd3bf74dbf81b1f3d34b158"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_global_offset_table8<a id="af437e70f011e7e19b5614a0b8f9531fca178b428b67d947f825484889ea7fae1a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">reloc_branch_4byte_pcrel<a id="af437e70f011e7e19b5614a0b8f9531fca3b2a5a68543379e2c0ecada70a114244"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LastTargetFixupKind<a id="af437e70f011e7e19b5614a0b8f9531fca0ac8d42d49ef30f20a3ecfb831c18c11"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NumTargetFixupKinds<a id="af437e70f011e7e19b5614a0b8f9531fca60d9caee92edd1c41f6c7955833953be"></a></td>
<td class="doxyEnumItemDescription"> (= LastTargetFixupKind - FirstTargetFixupKind)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 16 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86fixupkinds-h">X86FixupKinds.h</a>.</p>

</div>
</div>

### IPREFIXES {#ab45f29eafca4acc2a7240156af5ec350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::IPREFIXES </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The constants to describe instr prefixes if there are.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_NO_PREFIX<a id="ab45f29eafca4acc2a7240156af5ec350aec5df73a7c3497a61671eda217adc7ab"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_HAS_OP_SIZE<a id="ab45f29eafca4acc2a7240156af5ec350a823f82d1e68539ba7da81b79246d2ae0"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_HAS_AD_SIZE<a id="ab45f29eafca4acc2a7240156af5ec350a67cfccc16f5e2e2e69d3f20804774ff9"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_HAS_REPEAT_NE<a id="ab45f29eafca4acc2a7240156af5ec350aecd65b1d4484960a4b47c1ec3fbe5e75"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_HAS_REPEAT<a id="ab45f29eafca4acc2a7240156af5ec350a6afdb4f34129d1756d5983acde2125ea"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_HAS_LOCK<a id="ab45f29eafca4acc2a7240156af5ec350a21f6d8d4fc6a58587a2b022eb048a3bc"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_HAS_NOTRACK<a id="ab45f29eafca4acc2a7240156af5ec350a2352c35cf1f63002a6e595d1d1700dee"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_REX<a id="ab45f29eafca4acc2a7240156af5ec350a704b97a624cec998a46cf517308d3c2e"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_REX2<a id="ab45f29eafca4acc2a7240156af5ec350a72b79c46a4cc9c0f804c471e659ba490"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_VEX<a id="ab45f29eafca4acc2a7240156af5ec350af006bc8e41a4d11f85d5488509b7557f"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_VEX2<a id="ab45f29eafca4acc2a7240156af5ec350a70e8344da9bc21d69afa3dff5b8b7e0f"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_VEX3<a id="ab45f29eafca4acc2a7240156af5ec350a309a39ffd8ae143f947c54ae406451b5"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_EVEX<a id="ab45f29eafca4acc2a7240156af5ec350a5b424e0d4678febe99aa9677d425bc23"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_DISP8<a id="ab45f29eafca4acc2a7240156af5ec350a52397487434744d19d6d9f30a549c68e"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IP_USE_DISP32<a id="ab45f29eafca4acc2a7240156af5ec350a79e1d8eec35d00c93ca8ae774d1c8fe7"></a></td>
<td class="doxyEnumItemDescription"> (= 1U &lt;&lt; 13)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### OperandType {#a14391534703c3dd099e58439c6709c58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::OperandType : unsigned</td>
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
<td class="doxyEnumItemName">OPERAND_ROUNDING_CONTROL<a id="a14391534703c3dd099e58439c6709c58ab22d9f720d3247b2dadd99930befd489"></a></td>
<td class="doxyEnumItemDescription"> (= MCOI::OPERAND_FIRST_TARGET)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">OPERAND_COND_CODE<a id="a14391534703c3dd099e58439c6709c58aa5751737f17884658c827de6d3e2cc16"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### ProcessorFeatures {#abd1f712df4639ee306f3295384cb9a49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::ProcessorFeatures </td>
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
<td class="doxyEnumItemName">CPU_FEATURE_MAX<a id="abd1f712df4639ee306f3295384cb9a49ae2889a8b028db56ebebbeffd03557952"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>.</p>

</div>
</div>

### ProcessorSubtypes {#ac0d054a76f2d9b9a8966e040df061340}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::ProcessorSubtypes : unsigned</td>
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
<td class="doxyEnumItemName">CPU_SUBTYPE_DUMMY<a id="ac0d054a76f2d9b9a8966e040df061340ac334827d01355e8a6e732491d1bea82c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPU_SUBTYPE_MAX<a id="ac0d054a76f2d9b9a8966e040df061340aa68d419fcc728b90248fc483e9dfc96b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>.</p>

</div>
</div>

### ProcessorTypes {#adc617f881cab7ced514a31d188549455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::ProcessorTypes : unsigned</td>
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
<td class="doxyEnumItemName">CPU_TYPE_DUMMY<a id="adc617f881cab7ced514a31d188549455a06885d412ff41fbb163820b3383a5379"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CPU_TYPE_MAX<a id="adc617f881cab7ced514a31d188549455a67471f9ab757b037d43b934dc1fc79ea"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 38 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>.</p>

</div>
</div>

### ProcessorVendors {#a10bb9c1f7f54a5dfca9e11ab46dbea63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::ProcessorVendors : unsigned</td>
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
<td class="doxyEnumItemName">VENDOR_DUMMY<a id="a10bb9c1f7f54a5dfca9e11ab46dbea63aa510a89f7188d94ce4966a2b2c586022"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VENDOR_OTHER<a id="a10bb9c1f7f54a5dfca9e11ab46dbea63a4dc1d19ad35232cdae5152e83669a1a3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>.</p>

</div>
</div>

### RoundingMode {#a0910938d5634351e328c24b302cf2df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::RoundingMode </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Current rounding mode is represented in bits 11:10 of FPSR.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rmToNearest<a id="a0910938d5634351e328c24b302cf2df0a6d605619a48c41db01c31057483896d9"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rmDownward<a id="a0910938d5634351e328c24b302cf2df0a8e1b23b37b2a7543d850424b17bf71cf"></a></td>
<td class="doxyEnumItemDescription"> (= 1 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rmUpward<a id="a0910938d5634351e328c24b302cf2df0ae009d26d961ae327339ab4684c69563d"></a></td>
<td class="doxyEnumItemDescription"> (= 2 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rmTowardZero<a id="a0910938d5634351e328c24b302cf2df0a62bb5b98e004748fa06dbf0ce64662d8"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">rmMask<a id="a0910938d5634351e328c24b302cf2df0a574b896c88d746f57a4918bc9ca5437e"></a></td>
<td class="doxyEnumItemDescription"> (= 3 &lt;&lt; 10)</td>
</tr>

</table>
</dd>
</dl>


<p>These values are same as corresponding constants for rounding mode used in glibc.</p>


<p>Definition at line 994 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>.</p>

</div>
</div>

### SecondMacroFusionInstKind {#a3674fa9b225c107451c80b215815a31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class llvm::X86::SecondMacroFusionInstKind </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">AB<a id="a3674fa9b225c107451c80b215815a31eab86fc6b051f63d73de262d4c34e3a0a9"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">ELG<a id="a3674fa9b225c107451c80b215815a31eafced319b6d524eb5d758cbb125553cb2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SPO<a id="a3674fa9b225c107451c80b215815a31ea6e5dc41f4b0668252380ee328824505a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invalid<a id="a3674fa9b225c107451c80b215815a31ea4bbb8f967da6d1a610596d7257179c2b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

### STATIC\_ROUNDING {#a2a6ba37884c11b538aa6ebb0a4a8fa08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::X86::STATIC_ROUNDING </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>AVX512 static rounding constants.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TO_NEAREST_INT<a id="a2a6ba37884c11b538aa6ebb0a4a8fa08a1e511826050323db2b7a888c4eeb0977"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TO_NEG_INF<a id="a2a6ba37884c11b538aa6ebb0a4a8fa08a861c571d263e3ba1627fb148ff60b7f4"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TO_POS_INF<a id="a2a6ba37884c11b538aa6ebb0a4a8fa08a026139d1dd4eaa48af322e2bb4198903"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TO_ZERO<a id="a2a6ba37884c11b538aa6ebb0a4a8fa08a76b73a77ab384ff5b8ffbb033da9575d"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CUR_DIRECTION<a id="a2a6ba37884c11b538aa6ebb0a4a8fa08a74e9b89272f44a91ce8f058b8094c60f"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NO_EXC<a id="a2a6ba37884c11b538aa6ebb0a4a8fa08a33a922742c0ad232555087cf9af16669"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

</table>
</dd>
</dl>


<p>These need to match the values in avx512fintrin.h.</p>


<p>Definition at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### classifyFirstOpcodeInMacroFusion() {#a0c23473fe38a9c1e631c30965c4ca469}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FirstMacroFusionInstKind llvm::X86::classifyFirstOpcodeInMacroFusion (unsigned Opcode)</td>
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
<dt>Returns</dt>
<dd><p>the type of the first instruction in macro-fusion.</p></dd>
</dl>


<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a86730e94ae6fdf0fe3145b2acc88dea8aeec8d71daba88ee810b0d97fe8aa3c7b">AddSub</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8ac33315685a0cba3ce53be378b3c7874b">And</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8ac9b4c62f6dc1bc5caf3c768b687cbf7e">Cmp</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8a484d31015dbdf6199510633f4f3446be">IncDec</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8a4bbb8f967da6d1a610596d7257179c2b">Invalid</a> and <a href="#a86730e94ae6fdf0fe3145b2acc88dea8a0cbc6611f5540bd0809a388dc95a615b">Test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86macrofusion-cpp/#aaf2f3229a36c3e02d790d9d3cd72c53c">classifyFirst</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a819849ddb360be005e7c78fad31f754d">isFirstMacroFusibleInst</a>.</p>

</div>
</div>

### classifySecondCondCodeInMacroFusion() {#aca38f4b2343c6b84e1eb8b91fbc8d5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SecondMacroFusionInstKind llvm::X86::classifySecondCondCodeInMacroFusion (<a href="#a1a356a51a1fb4cc3c427599082cf1d2e">X86::CondCode</a> CC)</td>
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
<dt>Returns</dt>
<dd><p>the type of the second instruction in macro-fusion.</p></dd>
</dl>


<p>Definition at line 258 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a3674fa9b225c107451c80b215815a31eab86fc6b051f63d73de262d4c34e3a0a9">AB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eade92e2f17ca0acdd1ffa23d01df381df">COND_A</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eafeeb44274a14a14010dc990daecb39a0">COND_AE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eac9ae7c779ffc6865536d9f164ebf09b9">COND_B</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaaf9d50e29346a1094fb35045851db856">COND_BE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea80da60ed5c7b20653afe0b4b21a91ec1">COND_E</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea874bd4784391ae60bfdbc12d1f10bc73">COND_G</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea3547c8602aab6b0319c8052f8583613b">COND_GE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaf40beda0a4322699215cb85d7d6667b6">COND_L</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eae364c60967a7bc453d49caffc07d7bef">COND_LE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eacb2f86eaebe8b719f743d17a2d5a5f3d">COND_NE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eade1f36af81eae7e7b5b333d77de5feeb">COND_NO</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea4af201423e9be297ec72e1ac6ad77063">COND_NP</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea73469030600320118cd4a02f934ca9bc">COND_NS</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea914c19eb31606e70fd4f8dfff6d86038">COND_O</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaff7502cc3be1c359dca73814c6c34c6f">COND_P</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaeb72ca445848c39685fff16f97825475">COND_S</a>, <a href="#a3674fa9b225c107451c80b215815a31eafced319b6d524eb5d758cbb125553cb2">ELG</a>, <a href="#a3674fa9b225c107451c80b215815a31ea4bbb8f967da6d1a610596d7257179c2b">Invalid</a> and <a href="#a3674fa9b225c107451c80b215815a31ea6e5dc41f4b0668252380ee328824505a">SPO</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86macrofusion-cpp/#a5f1f11ad56c717567430d3e1315c9e27">classifySecond</a>.</p>

</div>
</div>

### createFastISel() {#ac370a59c2440ede047ceeea4ac9e9f77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel * llvm::X86::createFastISel (<a href="/web-llvm/docs/api/classes/llvm/functionloweringinfo">FunctionLoweringInfo</a> &amp; funcInfo, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/targetlibraryinfo">TargetLibraryInfo</a> * libInfo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1912 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 4069 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae0a481e8df0f6d0d536fa71fa5c5f3d9">llvm::X86TargetLowering::createFastISel</a>.</p>

</div>
</div>

### fillValidCPUArchList() {#af0d434e57456cc7f4c031e7fd01d48c3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86::fillValidCPUArchList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Values, bool Only64Bit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide a list of valid CPU names.</p>


<p>If <span class="doxyComputerOutput">Only64Bit</span> is true, the list will only contain 64-bit capable CPUs.</p>


<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a9a2ed16b3022bea6ce35ceb75c1ac2b3">Processors</a>.</p>

</div>
</div>

### fillValidTuneCPUList() {#a8cf2bfeeb9890df12a673f10933a34b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86::fillValidTuneCPUList (<a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Values, bool Only64Bit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Provide a list of valid -mtune names.</p>

<p>Declaration at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 470 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl/#a396fcfee6914c76974b73c3d203da6a5">llvm::SmallVectorImpl&lt; T &gt;::emplace_back</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a7cc0c41eb311684446c226218a357e54">NoTuneList</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a9a2ed16b3022bea6ce35ceb75c1ac2b3">Processors</a>.</p>

</div>
</div>

### getCCMPCondFlagsFromCondCode() {#aaddbb5e92a9b873f175fff89399245d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86::getCCMPCondFlagsFromCondCode (<a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 78 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3222 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eade92e2f17ca0acdd1ffa23d01df381df">COND_A</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eafeeb44274a14a14010dc990daecb39a0">COND_AE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eac9ae7c779ffc6865536d9f164ebf09b9">COND_B</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaaf9d50e29346a1094fb35045851db856">COND_BE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea80da60ed5c7b20653afe0b4b21a91ec1">COND_E</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea874bd4784391ae60bfdbc12d1f10bc73">COND_G</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea3547c8602aab6b0319c8052f8583613b">COND_GE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaf40beda0a4322699215cb85d7d6667b6">COND_L</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eae364c60967a7bc453d49caffc07d7bef">COND_LE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eacb2f86eaebe8b719f743d17a2d5a5f3d">COND_NE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eade1f36af81eae7e7b5b333d77de5feeb">COND_NO</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea4af201423e9be297ec72e1ac6ad77063">COND_NP</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea73469030600320118cd4a02f934ca9bc">COND_NS</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea914c19eb31606e70fd4f8dfff6d86038">COND_O</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaff7502cc3be1c359dca73814c6c34c6f">COND_P</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaeb72ca445848c39685fff16f97825475">COND_S</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#add97272311c92ae6e05533bf8718447f">combineAndOrForCcmpCtest</a>.</p>

</div>
</div>

### getCMovOpcode() {#af569f4e4b0acf498c83fa0e58e2eb364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getCMovOpcode (unsigned RegBytes, bool HasMemoryOperand=false, bool HasNDD=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a cmov opcode for the given register size in bytes, and operand type.</p>

<p>Declaration at line 51 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3457 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a818f94f18ecfd6b7751ca028087447bf">GET_ND_IF_ENABLED</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a29c37970b1c079bbbc4515cb00e112fe">llvm::X86InstrInfo::insertSelect</a>.</p>

</div>
</div>

### getCondFromBranch() {#a0f2b2ef8f4560ffd46c7966e8315142f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode llvm::X86::getCondFromBranch (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 63 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3195 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#a20086d3d5e4bf090cf298a125fab1b89">getCondFromMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86macrofusion-cpp/#a5f1f11ad56c717567430d3e1315c9e27">classifySecond</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#af0257906f462ffadf000fbdcdd4ecabd">llvm::X86InstrInfo::removeBranch</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a20d1f65e3dcb870550c1c8340fc7a286">llvm::X86InstrInfo::replaceBranchWithTailCall</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#a9d9c7bebc5b5d451511265937418ed6a">splitBlock</a>.</p>

</div>
</div>

### getCondFromCCMP() {#aad0de83dbe4b099f263fa9c08f7aa818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode llvm::X86::getCondFromCCMP (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 75 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#a20086d3d5e4bf090cf298a125fab1b89">getCondFromMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getCondFromCFCMov() {#a13508fbf99bc5c958d5b14ffbfdef94b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode llvm::X86::getCondFromCFCMov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3211 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#a20086d3d5e4bf090cf298a125fab1b89">getCondFromMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getCondFromCMov() {#aff28d9a4811f627c5254a305f36b55cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode llvm::X86::getCondFromCMov (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 69 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#a20086d3d5e4bf090cf298a125fab1b89">getCondFromMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86cmovconversion-cpp/#aba46d9b0861c1e010f4bb946e5806415">packCmovGroup</a>.</p>

</div>
</div>

### getCondFromMI() {#a20086d3d5e4bf090cf298a125fab1b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode llvm::X86::getCondFromMI (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the condition code of the instruction.</p>


<p>If the instruction doesn't have a condition code, return <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">X86::COND_INVALID</a>.</p>


<p>Declaration at line 60 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3186 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#aae0006f60cff07edc54c729003feab6c">getCondSrcNoFromDesc</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="#a0f2b2ef8f4560ffd46c7966e8315142f">getCondFromBranch</a>, <a href="#aad0de83dbe4b099f263fa9c08f7aa818">getCondFromCCMP</a>, <a href="#a13508fbf99bc5c958d5b14ffbfdef94b">getCondFromCFCMov</a>, <a href="#aff28d9a4811f627c5254a305f36b55cd">getCondFromCMov</a>, <a href="#aa4843a98a8b18a9d745dfe2a882ccf3b">getCondFromSETCC</a> and <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a08a488100b4cc4464d879a987e490915">llvm::X86InstrInfo::optimizeCompareInstr</a>.</p>

</div>
</div>

### getCondFromSETCC() {#aa4843a98a8b18a9d745dfe2a882ccf3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode llvm::X86::getCondFromSETCC (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3200 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#a20086d3d5e4bf090cf298a125fab1b89">getCondFromMI</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>

</div>
</div>

### getCondSrcNoFromDesc() {#aae0006f60cff07edc54c729003feab6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86::getCondSrcNoFromDesc (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; MCID)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the source operand # for condition code by <span class="doxyComputerOutput"><a href="/web-llvm/docs/api/namespaces/llvm/mcid">MCID</a></span>.</p>


<p>If the instruction doesn't have a condition code, return -1.</p>


<p>Declaration at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3175 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>Referenced by <a href="#a20086d3d5e4bf090cf298a125fab1b89">getCondFromMI</a>.</p>

</div>
</div>

### getConstantFromPool() {#ab7d20e7a4f79f39c97b3329389c8db88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Constant * llvm::X86::getConstantFromPool (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI, unsigned OpNo)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Find any constant pool entry associated with a specific instruction operand.</p>

<p>Declaration at line 115 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3658 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="#a2a5aec578e2e391e99e1705012752d84a93474770cf1401679ba37e1833632e58">AddrDisp</a>, <a href="#a2a5aec578e2e391e99e1705012752d84aba7ebe0e28a2c1c4c14343f549c01462">AddrIndexReg</a>, <a href="#a2a5aec578e2e391e99e1705012752d84ac4169d78e1c6de9b189f31b90f1c2691">AddrNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#acaa82b4be1aefa234c71323630c2e63f">llvm::MachineConstantPoolEntry::ConstVal</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#aaa68daaf8d7b773d012887c92c2023ce">llvm::MachineOperand::getIndex</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#af624ff47eaa512dbe23866accb3837c1">llvm::MachineOperand::getOffset</a>, <a href="/web-llvm/docs/api/classes/llvm/machineoperand/#a5b401e780c5eed0aca1cfbf44d36a545">llvm::MachineOperand::isCPI</a>, <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#a1c9559c3abf75a6df6bd2abe7131f277">llvm::MachineConstantPoolEntry::isMachineConstantPoolEntry</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/classes/llvm/machineconstantpoolentry/#a020d97c78e923fb96910f087012f9be5">llvm::MachineConstantPoolEntry::Val</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a5bd11f377f141eaca592b06fff653370">printBroadcast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a60061d374eb7273d11025f881472a4d8">printExtend</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a6132fb3423ce0d8846f93102d9658bc4">printZeroUpperMove</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86fixupvectorconstants-cpp-/x86fixupvectorconstantspass/#a82e64653e573981933ea8bdc240fad3c">anonymous{X86FixupVectorConstants.cpp}::X86FixupVectorConstantsPass::processInstruction</a>.</p>

</div>
</div>

### getCPUDispatchMangling() {#a20c881595243317947b9fbce4e8556da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char llvm::X86::getCPUDispatchMangling (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 180 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 739 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a9a2ed16b3022bea6ce35ceb75c1ac2b3">Processors</a>.</p>

</div>
</div>

### getCpuSupportsMask() {#a16daa0658cce2a2c4465febd770d8aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt; uint32_t, 4 &gt; llvm::X86::getCpuSupportsMask (<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; FeatureStrs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 754 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>.</p>

</div>
</div>

### getFeaturePriority() {#ad77822367a3ea927da01c1b89ee4e415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getFeaturePriority (<a href="#abd1f712df4639ee306f3295384cb9a49">ProcessorFeatures</a> Feat)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 183 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 771 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>

</div>
</div>

### getFeaturesForCPU() {#a9a64d327c5a0be28d5936e30ff02709a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86::getFeaturesForCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> &gt; &amp; Features, bool NeedPlus=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Fill in the features that <span class="doxyComputerOutput">CPU</span> supports into <span class="doxyComputerOutput">Features</span>.</p>


<p>"+" will be append in front of each feature if NeedPlus is true.</p>


<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 664 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="#abd1f712df4639ee306f3295384cb9a49ae2889a8b028db56ebebbeffd03557952">CPU_FEATURE_MAX</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#aec187f4ac003e463a259d0f2e0490e18">FeatureInfos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86targetparser-cpp-/featureinfo/#a8bb4c489f3b7136becc840b8e2916008">anonymous{X86TargetParser.cpp}::FeatureInfo::getName</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a9a2ed16b3022bea6ce35ceb75c1ac2b3">Processors</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatebase/#af42bfbc067df27c19ee2fc859df58799">llvm::SmallVectorTemplateBase&lt; T, bool &gt;::push_back</a>.</p>

</div>
</div>

### getFirstAddrOperandIdx() {#a279395a00a782f7e3d6141bc3328a249}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::X86::getFirstAddrOperandIdx (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return the index of the instruction's first address operand, if it has a memory reference, or -1 if it has none.</p>


<p>Unlike <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ad571a5a542b484586224d3a8df631646">X86II::getMemoryOperandNo()</a>, this also works for both pseudo instructions (e.g., TCRETURNmi) as well as real instructions (e.g., JMP64m).</p>


<p>Declaration at line 112 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3607 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/demangle/itaniumdemangle-h/#a536e22898d28a9340a4204407a75ad5d">AbstractManglingParser&lt; Derived, Alloc &gt;::NumOps</a>, <a href="#a2a5aec578e2e391e99e1705012752d84ac4169d78e1c6de9b189f31b90f1c2691">AddrNumOperands</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ad571a5a542b484586224d3a8df631646">llvm::X86II::getMemoryOperandNo</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#af0baab1b1dfea49cbffeb8727aebd429">llvm::X86II::getOperandBias</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a8da88ee0688eaec097d62d33fff86992">llvm::X86II::isPseudo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a7dc3069afa2ce5ea62ac2eb183e51c00">llvm::none_of</a> and <a href="/web-llvm/docs/api/namespaces/llvm/mcoi/#ad9dfed338ec3d47f30c593ee49cbf96da777022119f804325c388f44ccd8524e5">llvm::MCOI::OPERAND_MEMORY</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>.</p>

</div>
</div>

### getKeyFeature() {#afcd96c9db878796ece2654dde1588338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ProcessorFeatures llvm::X86::getKeyFeature (<a href="#aaf0c3e7727bf6e2922b7f28dd49cc9be">CPUKind</a> Kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the key feature prioritizing target multiversioning.</p>

<p>Declaration at line 168 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 479 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a9a2ed16b3022bea6ce35ceb75c1ac2b3">Processors</a>.</p>

</div>
</div>

### getNFVariant() {#af8606eab304dcbb9e0bb4b3597c49675}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getNFVariant (unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3288 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a210188f72593e018067353026bdd4fe3">getNewOpcFromTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86flagscopylowering-cpp/#adcc6b20dc2c8fad2a6aac24e970f15c7">getClobberType</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86flagscopylowering-cpp-/x86flagscopyloweringpass/#a30d90e84a3faa0cd7aa2c3b96d65c232">anonymous{X86FlagsCopyLowering.cpp}::X86FlagsCopyLoweringPass::runOnMachineFunction</a>.</p>

</div>
</div>

### getNonNDVariant() {#a7f5a82ba9421c1c89257282ca65b4c23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getNonNDVariant (unsigned Opc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3292 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#a210188f72593e018067353026bdd4fe3">getNewOpcFromTable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86compressevex-cpp/#a9d982c894cfe302bb2d90c1f5d4c1c37">CompressEVEXImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a7cfc0ecfec922ebf19bd023f3b675604">llvm::X86InstrInfo::foldMemoryOperandImpl</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#aec4538d6aec6f79de5c3b56115fd2c78">llvm::X86InstrInfo::foldMemoryOperandImpl</a> and <a href="/web-llvm/docs/api/classes/llvm/x86registerinfo/#ada2b3cb4854ef22758c48e3721ddb1e2">llvm::X86RegisterInfo::getRegAllocationHints</a>.</p>

</div>
</div>

### getOpcodeForLongImmediateForm() {#ab4ef8f6d88ba8604aa83ce35440fd8fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getOpcodeForLongImmediateForm (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 462 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86asmbackend-cpp/#a9091bc00a994cdb96d1133c21d1f41ec">getRelaxedOpcode</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86asmbackend-cpp-/x86asmbackend/#ae14243cebfb18dca997cdca22b151245">anonymous{X86AsmBackend.cpp}::X86AsmBackend::mayNeedRelaxation</a>.</p>

</div>
</div>

### getOpcodeForShortImmediateForm() {#af62df4b10560106717f6147a74bf446d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getOpcodeForShortImmediateForm (unsigned Opcode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 451 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>

</div>
</div>

### GetOppositeBranchCondition() {#a5c06f5a972e8a78052103840a8c98a3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CondCode llvm::X86::GetOppositeBranchCondition (<a href="#a1a356a51a1fb4cc3c427599082cf1d2e">CondCode</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>GetOppositeBranchCondition - Return the inverse of the specified cond, e.g.</p>


<p>Return the inverse of the specified condition, e.g.</p>


<p>turning COND_E to COND_NE.</p>


<p>Declaration at line 88 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3298 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eade92e2f17ca0acdd1ffa23d01df381df">COND_A</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eafeeb44274a14a14010dc990daecb39a0">COND_AE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eac9ae7c779ffc6865536d9f164ebf09b9">COND_B</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaaf9d50e29346a1094fb35045851db856">COND_BE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea80da60ed5c7b20653afe0b4b21a91ec1">COND_E</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea4244390c8621e6f061fad8fe2f6fc3a3">COND_E_AND_NP</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea874bd4784391ae60bfdbc12d1f10bc73">COND_G</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea3547c8602aab6b0319c8052f8583613b">COND_GE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaf40beda0a4322699215cb85d7d6667b6">COND_L</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eae364c60967a7bc453d49caffc07d7bef">COND_LE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eacb2f86eaebe8b719f743d17a2d5a5f3d">COND_NE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea8b47d4d3f261caf07338c6775a08a2bc">COND_NE_OR_P</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eade1f36af81eae7e7b5b333d77de5feeb">COND_NO</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea4af201423e9be297ec72e1ac6ad77063">COND_NP</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea73469030600320118cd4a02f934ca9bc">COND_NS</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea914c19eb31606e70fd4f8dfff6d86038">COND_O</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaff7502cc3be1c359dca73814c6c34c6f">COND_P</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaeb72ca445848c39685fff16f97825475">COND_S</a> and <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0870a92dd3a0e71116be6fa3f545fe90">checkBoolTestSetCCCombine</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#add97272311c92ae6e05533bf8718447f">combineAndOrForCcmpCtest</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af0fb4a30e359345f1f6c967488cd37ab">combineCMov</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a81ff8e0a240cf80ff42fcb1a6c796b33">combineOr</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0bce091105ff422dbffc7677d698e455">combineSubSetcc</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4f4cf2e3dcecef6763caca7fd8949d76">combineX86SubCmpForFlags</a>, <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a22444fb95050a5bef1c689e5bc9b064e">createPHIsForCMOVsInSinkBB</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#adb73c9adac12d432923cc883aa607798">foldXor1SetCC</a>.</p>

</div>
</div>

### getSegmentOverridePrefixForReg() {#a5a223fa35bcfebf3149a762a7ede4303}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EncodingOfSegmentOverridePrefix llvm::X86::getSegmentOverridePrefixForReg (<a href="/web-llvm/docs/api/classes/llvm/mcregister">MCRegister</a> Reg)</td>
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

<p>Given a segment register, return the encoding of the segment override prefix for it.</p>

<p>Definition at line 332 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a320797eb50409965820a431a75d69645a6b07c0b372000f1c9d4dc8aad224c513">CS_Encoding</a>, <a href="#a320797eb50409965820a431a75d69645ae6eef90bcf399314a8e7038d721aa6de">DS_Encoding</a>, <a href="#a320797eb50409965820a431a75d69645a5517951ce8dbe938c85f5e966dfc0a11">ES_Encoding</a>, <a href="#a320797eb50409965820a431a75d69645ad149e634798a2cca9126fba777295803">FS_Encoding</a>, <a href="#a320797eb50409965820a431a75d69645a2f9896117daa729a2c816d010be4cf2b">GS_Encoding</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/machinesink-cpp/#a359e1ff26f6d466d927a61aae45b05c3">Reg</a> and <a href="#a320797eb50409965820a431a75d69645a9398d374cb6482bfc772443c98b46eb6">SS_Encoding</a>.</p>

</div>
</div>

### getSwappedVCMPImm() {#a4da6ce26c64d4eaea82afb6f37f4125a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getSwappedVCMPImm (unsigned Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the VCMP immediate if the opcodes are swapped.</p>


<p>Get the VCMP immediate if the operands are swapped.</p>


<p>Declaration at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3554 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### getSwappedVPCMPImm() {#aa640b399dea5c08e52b71c3a2736d61c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getSwappedVPCMPImm (unsigned Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the VPCMP immediate if the opcodes are swapped.</p>


<p>Get the VPCMP immediate if the operands are swapped.</p>


<p>Declaration at line 94 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3500 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### getSwappedVPCOMImm() {#a654d8db751a92fed6c83508010b3de64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getSwappedVPCOMImm (unsigned Imm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the VPCOM immediate if the opcodes are swapped.</p>


<p>Get the VPCOM immediate if the operands are swapped.</p>


<p>Declaration at line 97 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3527 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86instrinfo/#a36ea25402e8a11de5c94bfeb152ea063">llvm::X86InstrInfo::commuteInstructionImpl</a>.</p>

</div>
</div>

### getVectorRegisterWidth() {#af9123ce22c3cada196c14e31be149c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getVectorRegisterWidth (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcoperandinfo">MCOperandInfo</a> &amp; Info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the width of the vector register operand.</p>

<p>Declaration at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3573 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#a72515d2f0a6b48c9949ac83674b46a89">addConstantComments</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86mcinstlower-cpp/#adf508d7280c5a6d9fb7d0e2cf2f426c4">printZeroExtend</a>.</p>

</div>
</div>

### getVPCMPImmForCond() {#a8fcee8e11458a08892fc937a9f428966}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::X86::getVPCMPImmForCond (<a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07">ISD::CondCode</a> CC)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Get the VPCMP immediate for the given condition.</p>

<p>Declaration at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3476 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ae2e6a5e32087b9f65bd51585a6a5afb4">llvm::ISD::SETEQ</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a7f47862de23f7210f88ccf98ae1efbe4">llvm::ISD::SETGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a5ad12b466e3a5900d0c307b301465d25">llvm::ISD::SETGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ab49f81c2ecbbff3d0fbe55dd46353774">llvm::ISD::SETLE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a6f05a09edb671910f85f8665981cbde9">llvm::ISD::SETLT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a2887cc8b39915a25180f4bca0026a15e">llvm::ISD::SETNE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a9dff1dcbac65852b71473818c11869b1">llvm::ISD::SETUGE</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a292be4a9782030bfad637581d25a5897">llvm::ISD::SETUGT</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07ac538f0b432df970cbaaf6b81d777c6a7">llvm::ISD::SETULE</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#ac3c3cf58d6d631af6a172457304d3d07a473200f06bdd611fdbed43d908b84305">llvm::ISD::SETULT</a>.</p>

</div>
</div>

### getX86ConditionCode() {#a973a0a53d9270a750d4c8a117fa71317}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::pair&lt; X86::CondCode, bool &gt; llvm::X86::getX86ConditionCode (<a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Predicate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Return a pair of condition code for the given predicate and whether the instruction operands should be swaped to match the condition code.</p>

<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3371 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eade92e2f17ca0acdd1ffa23d01df381df">COND_A</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eafeeb44274a14a14010dc990daecb39a0">COND_AE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eac9ae7c779ffc6865536d9f164ebf09b9">COND_B</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaaf9d50e29346a1094fb35045851db856">COND_BE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea80da60ed5c7b20653afe0b4b21a91ec1">COND_E</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea874bd4784391ae60bfdbc12d1f10bc73">COND_G</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea3547c8602aab6b0319c8052f8583613b">COND_GE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eab1840bfcd789713b29a40d9d55cb41e3">COND_INVALID</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaf40beda0a4322699215cb85d7d6667b6">COND_L</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eae364c60967a7bc453d49caffc07d7bef">COND_LE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eacb2f86eaebe8b719f743d17a2d5a5f3d">COND_NE</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2ea4af201423e9be297ec72e1ac6ad77063">COND_NP</a>, <a href="#a1a356a51a1fb4cc3c427599082cf1d2eaff7502cc3be1c359dca73814c6c34c6f">COND_P</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba024db78a5ed74f64666f3ca4955e6eca">llvm::CmpInst::FCMP_OEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba541533f34077bbbcfb703a90f6d2da9b">llvm::CmpInst::FCMP_OGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba4c399f525bbcf03d72af4b303e6eeca8">llvm::CmpInst::FCMP_OGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba9835cfe02fb5027680bd7203b024f77a">llvm::CmpInst::FCMP_OLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba326bee0a4a424cef21c1cf8adb8b8dd8">llvm::CmpInst::FCMP_OLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba8a80b27ca29fe2076b9bbdee02c65464">llvm::CmpInst::FCMP_ONE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa3213b645e029aba8bb1b85213607d5e">llvm::CmpInst::FCMP_ORD</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba919643b83ce3c9af2e4296ed5e413a1f">llvm::CmpInst::FCMP_UEQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bae51609fc6a425f849d37c28cb9bc0344">llvm::CmpInst::FCMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba959268ceeae23abe5c9ad9e895669d0c">llvm::CmpInst::FCMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba396dda2571cd3c575f1d9cb44dc2cc09">llvm::CmpInst::FCMP_ULE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba75016d5872d90adf89cc1cbf5763f474">llvm::CmpInst::FCMP_ULT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad601460c9371d0f0ada5ae006bdba2bd">llvm::CmpInst::FCMP_UNE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baf0159e4005258dc54f20b6fc227d19ed">llvm::CmpInst::FCMP_UNO</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78baa719225e2de4059f93fd3209e1f48218">llvm::CmpInst::ICMP_EQ</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac17897ebf2f6a6986280fc3bdf28a30a">llvm::CmpInst::ICMP_NE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bac1aa7b798ba11d2e497d5cce6ce6d3dc">llvm::CmpInst::ICMP_SGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba720a42e85f7e981afd61e28473b0000a">llvm::CmpInst::ICMP_SGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba2751d6136a2819749dcef65dc19a4246">llvm::CmpInst::ICMP_SLE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba15ae464950ac676919c2f0c7aafc706c">llvm::CmpInst::ICMP_SLT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba573bcd571c938fce863525330bbfc4b8">llvm::CmpInst::ICMP_UGE</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba607cecdc5172814382033e001ed11fad">llvm::CmpInst::ICMP_UGT</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78bad92f160316221fd4090520bb2b3cefc5">llvm::CmpInst::ICMP_ULE</a> and <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78ba91d86a4753c8bd7624e01bf565d87f8e">llvm::CmpInst::ICMP_ULT</a>.</p>

</div>
</div>

### isCalleePop() {#a98bec313edd88412de74ae369ce47005}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::isCalleePop (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CallingConv, bool is64Bit, bool IsVarArg, bool GuaranteeTCO)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Determines whether the callee is required to pop its own arguments.</p>


<p>Callee pop is necessary to support tail calls.</p>


<p>Declaration at line 1015 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2946 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp/#a652270ec0bdb03b5a7f934524412aa7f">is64Bit</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/m68k/m68kisellowering-cpp/#a6bae7076c284f85288d5edb636823176">shouldGuaranteeTCO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafde87569738f9e23963e8735f71c33eb">llvm::CallingConv::X86_FastCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4caa88ccf4313b5bc700dec76fd9bc5d40e">llvm::CallingConv::X86_StdCall</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4ca97109ccd68cac64fb38dbd24fc4589c6">llvm::CallingConv::X86_ThisCall</a> and <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cacfa4cc9bcdaefd5e969c258c994052b9">llvm::CallingConv::X86_VectorCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>.</p>

</div>
</div>

### isConstantSplat() {#ae914ecbf92d09be7f8da203ec3dd5bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::isConstantSplat (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/apint">APInt</a> &amp; SplatVal, bool AllowPartialUndefs=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>If <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a constant whose elements are all the same constant or undefined, return true and return the constant value in <span class="doxyComputerOutput">SplatVal</span>.</p>


<p>If we have undef bits that don't cover an entire element, we treat these as zero if AllowPartialUndefs is set, else we fail and return false.</p>


<p>Definition at line 5227 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ab52de97c38dc9f2c7ce80a6811fac2e9">getTargetConstantBitsFromNode</a> and <a href="/web-llvm/docs/api/classes/llvm/smallvectortemplatecommon/#a1c479a8c434377c2b8cb056bdfdfc201">llvm::SmallVectorTemplateCommon&lt; T, typename &gt;::size</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aaa27af54b7ba8fa7ee30cc6d7f729207">combineAndMaskToShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a1278833d086e5f200fcc7e576d2efa17">LowerFunnelShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4871d6290298d9eaae5b5da0160e5a21">LowerRotate</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a5b1dfb57da0320c661933ff2d6d7cde7">LowerShift</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae061deb7e1ce634d402090342aeccda7">LowerShiftByScalarImmediate</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a>.</p>

</div>
</div>

### isExtendedSwiftAsyncFrameSupported() {#a738e789cdbd35bf07b744925b6f6ae4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::isExtendedSwiftAsyncFrameSupported (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; Subtarget, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>True if the target supports the extended frame for async Swift functions.</p>

<p>Declaration at line 1046 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 27299 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/targetmachine/#afb72c5626afbc815284e2b26bb0663f8">llvm::TargetMachine::getMCAsmInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/machinefunction/#af777ff93c9e07a6ff5ffe3226deb3e76">llvm::MachineFunction::getTarget</a> and <a href="/web-llvm/docs/api/classes/llvm/mcasminfo/#ac158349781823fe8ff9e02d3a3533d55">llvm::MCAsmInfo::usesWindowsCFI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a25a5e94166cf78354826b46e402ebcd9">LowerINTRINSIC_W_CHAIN</a>.</p>

</div>
</div>

### isMacroFused() {#aee53d7204e2f79dea3df2633db61b104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::isMacroFused (<a href="#a86730e94ae6fdf0fe3145b2acc88dea8">FirstMacroFusionInstKind</a> FirstKind, <a href="#a3674fa9b225c107451c80b215815a31e">SecondMacroFusionInstKind</a> SecondKind)</td>
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




<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">FirstKind</td>
<td class="doxyParamItemDescription"><p>kind of the first instruction in macro fusion.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">SecondKind</td>
<td class="doxyParamItemDescription"><p>kind of the second instruction in macro fusion.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>true if the two instruction can be macro fused.</p></dd>
</dl>


<p>Definition at line 290 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a>.</p>


<p>References <a href="#a3674fa9b225c107451c80b215815a31eab86fc6b051f63d73de262d4c34e3a0a9">AB</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8aeec8d71daba88ee810b0d97fe8aa3c7b">AddSub</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8ac33315685a0cba3ce53be378b3c7874b">And</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8ac9b4c62f6dc1bc5caf3c768b687cbf7e">Cmp</a>, <a href="#a3674fa9b225c107451c80b215815a31eafced319b6d524eb5d758cbb125553cb2">ELG</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8a484d31015dbdf6199510633f4f3446be">IncDec</a>, <a href="#a86730e94ae6fdf0fe3145b2acc88dea8a4bbb8f967da6d1a610596d7257179c2b">Invalid</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#a86730e94ae6fdf0fe3145b2acc88dea8a0cbc6611f5540bd0809a388dc95a615b">Test</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86macrofusion-cpp/#a7e77f4c39d6175deb3eee55c6ce77932">shouldScheduleAdjacent</a>.</p>

</div>
</div>

### isOffsetSuitableForCodeModel() {#ac5d9870049dd4eaa5938dd4e920d354a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::isOffsetSuitableForCodeModel (int64_t Offset, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8df">CodeModel::Model</a> M, bool hasSymbolicDisplacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true of the given offset can be fit into displacement field of the instruction.</p>

<p>Declaration at line 1010 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2917 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1a1e51a5952c3afa00875df90e7ae6f8">llvm::isInt</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfaa6a2e45ae404e3f797d2d7e9f3a48949">llvm::CodeModel::Kernel</a>, <a href="/web-llvm/docs/api/namespaces/llvm/codemodel/#afc59396a9e5809fc92938e203d91a8dfa5208f558fccf9f63423fb5385bb3e75c">llvm::CodeModel::Large</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a05f5b9a11bdcc5feba62899f95dcf878a3134224cba2545bc57954d3b072aebb4">llvm::Offset</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ad1a79970217e7be886648d06d5fded3c">llvm::X86TargetLowering::isLegalAddressingMode</a>.</p>

</div>
</div>

### isX87Instruction() {#a740bc8dd5f4846acc274f39b05c1ac14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::isX87Instruction (<a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if the instruction is X87 instruction.</p>


<p>check if the instruction is X87 instruction</p>


<p>Declaration at line 106 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a>, definition at line 3592 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp/#addd65697e241d821dc9f036f85799be9">isX87Reg</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86floatingpoint-cpp/#afe8ca3964c0db321aa6637100efa65dc">getNextFPInstruction</a> and <a href="/web-llvm/docs/api/classes/anonymous-x86insertwait-cpp-/waitinsert/#acddf9e1c3a065fa8960fee98505de360">anonymous{X86InsertWait.cpp}::WaitInsert::runOnMachineFunction</a>.</p>

</div>
</div>

### isZeroNode() {#a43e102a1c33f2dffc750026a05828f52}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::isZeroNode (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Elt)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns true if Elt is a constant zero or floating point constant +0.0.</p>


<p>Returns true if Elt is a constant zero or a floating point constant +0.0.</p>


<p>Declaration at line 1006 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 3932 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a1a86775f3d85d98a31b2751e1eb348ea">llvm::isNullConstant</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#acfd2e840c7c480f45753b81b504ff587">llvm::isNullFPConstant</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4585b76cee25b89a8706715217a1c743">combineAdd</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a064060d88e13e0fe28415d9bb1683b4f">combineAddOrSubToADCOrSBB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a0a830cdb7a7691a1d390be839ff5859f">combineSub</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6038cc86e3b86730ea40b4ee63200f40">combineX86CloadCstore</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ac21ca860de08b06c8c3d51c536ba0c90">computeZeroableShuffleElements</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a4fc43ca790e9a82ad51249f2e93d2e17">getFauxShuffleMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a7fb1a2451497dfdf1119bd9343bd3052">getMaskNode</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af71303967827d0c63f1caa626e59aa38">getTargetShuffleAndZeroables</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af7efcd13ccffb0fae2b3ef52bde4b6d7">LowerBuildVectorv4x32</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#ae1e26c281236fd29f5a93e58a4397601">LowerSCALAR_TO_VECTOR</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a6edfdb2ee22d183ae51d57796e56f8e3">widenSubVector</a>.</p>

</div>
</div>

### mayFoldIntoStore() {#a670aa0012e26bf3d40dfa5068743ac48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::mayFoldIntoStore (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a value that could be used to fold a store into some other x86 instruction as a memory operand.</p>


<p>Ex: pextrb $0, xmm0, (rdi).</p>


<p>Declaration at line 1038 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2813 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/value/#a3a402430a1bbe70a9282dcb0e0b6a2cd">llvm::Value::hasOneUse</a>, <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a308088c2d65f8f3955f5fb0f6aca7ccc">llvm::ISD::isNormalStore</a> and <a href="/web-llvm/docs/api/classes/llvm/value/#a158da2b6d3d938aaa15b6acd00150e2c">llvm::Value::user_begin</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d6a6ccf92180726bf08404b1e112fe3">LowerEXTRACT_VECTOR_ELT_SSE4</a>.</p>

</div>
</div>

### mayFoldIntoZeroExtend() {#a60cb51706fb77e669933216aaf2c1e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::mayFoldIntoZeroExtend (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is an operation that could be folded into a zero extend x86 instruction.</p>

<p>Declaration at line 1042 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2826 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/namespaces/llvm/isd/#a22ea9cec080dd5f4f47ba234c2f59110a93fdf85eff945f1a668b4915a051453e">llvm::ISD::ZERO_EXTEND</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a3d6a6ccf92180726bf08404b1e112fe3">LowerEXTRACT_VECTOR_ELT_SSE4</a>.</p>

</div>
</div>

### mayFoldLoad() {#aafd16108bb2bfb19eed47e23dcbee3dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::mayFoldLoad (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; Subtarget, bool AssumeSingleUse=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a load operation that could be folded into some other x86 instruction as a memory operand.</p>


<p>Example: vpaddd (rdi), xmm0, xmm0.</p>


<p>Declaration at line 1027 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2780 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#ad53602fc659b337387df05d2f8f0aac5">llvm::X86Subtarget::hasAVX</a> and <a href="/web-llvm/docs/api/namespaces/llvm/isd/#afaaeadcd82b42fc0d385a6247bf7bb52">llvm::ISD::isNormalLoad</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a454834aa3770b553c5365fa2460a7687">combineCommutableSHUFP</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a8593ba64bae1cbd8bc4243743289dab9">combineX86ShuffleChain</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#aa4a1701790033b3d84938d44c913da11">EmitCmp</a>, <a href="/web-llvm/docs/api/classes/llvm/x86targetlowering/#ae344bf38282de26bb4d5783114a65eaf">llvm::X86TargetLowering::IsDesirableToPromoteOp</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#acf1af491be6e63a41199ac997611c54a">lowerShuffleAsDecomposedShuffleMerge</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#abf10af4763fc3f16c6e810e203b343ee">lowerV2X128Shuffle</a>, <a href="#a316352587c836a0388b90aec4531450a">mayFoldLoadIntoBroadcastFromMem</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86iseldagtodag-cpp-/x86dagtodagisel/#a621eb8645a9f80882b80ac3c6d4e0091">anonymous{X86ISelDAGToDAG.cpp}::X86DAGToDAGISel::PreprocessISelDAG</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#af99172dc0d0e9814f6b7138987c3b0f6">pushAddIntoCmovOfConsts</a>.</p>

</div>
</div>

### mayFoldLoadIntoBroadcastFromMem() {#a316352587c836a0388b90aec4531450a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::mayFoldLoadIntoBroadcastFromMem (<a href="/web-llvm/docs/api/classes/llvm/sdvalue">SDValue</a> Op, <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> EltVT, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/x86subtarget">X86Subtarget</a> &amp; Subtarget, bool AssumeSingleUse=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/namespaces/llvm/check">Check</a> if <a href="/web-llvm/docs/api/namespaces/llvm/#ab471937b9a227e70c7fe8bd9604014d6">Op</a> is a load operation that could be folded into a vector splat instruction as a memory operand.</p>


<p>Example: vbroadcastss 16(rdi), xmm2.</p>


<p>Declaration at line 1032 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a>, definition at line 2799 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/mvt/#a2e101ce5736aa0643639fd3adae18088">llvm::MVT::getScalarSizeInBits</a>, <a href="/web-llvm/docs/api/classes/llvm/x86subtarget/#ad53602fc659b337387df05d2f8f0aac5">llvm::X86Subtarget::hasAVX</a> and <a href="#aafd16108bb2bfb19eed47e23dcbee3dd">mayFoldLoad</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a9dfbf1a0e6b79ef994d2a89cb596f959">combineConcatVectorOps</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp/#a13b5b432c1ab8d4774bfcfea2e7fc323">EltsFromConsecutiveLoads</a>.</p>

</div>
</div>

### optimizeINCDEC() {#ae0e27cbc3acd22d76564e1f3ac9b8311}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::optimizeINCDEC (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, bool In64BitMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 23 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 311 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a64c5a9b119e0a1455b1889cf280e9de9">FROM_TO</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### optimizeInstFromVEX3ToVEX2() {#aade8574cba756ffdc426344718ada414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::optimizeInstFromVEX3ToVEX2 (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mcinstrdesc">MCInstrDesc</a> &amp; Desc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 19 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ead5bbb0f8b7dfd268d7ca01219b5ec3aa">llvm::X86II::EncodingMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea3ae6529df02b311ddca2a678a0bfaf64">llvm::X86II::FormMask</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a64c5a9b119e0a1455b1889cf280e9de9">FROM_TO</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#ae63be8b012497f28a863be8cfa255a87">llvm::X86II::isX86_64ExtendedReg</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285eab5eb1a156b44a8263348720cefb0f078">llvm::X86II::MRMSrcReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea17bada293123ac2f889d0dece275027d">llvm::X86II::OpMapMask</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea12e1b321252ff4c31f9a6b563d8d18b7">llvm::X86II::REX_W</a>, <a href="/web-llvm/docs/api/namespaces/std/#ab8424022895aee3e366fb9a32f2883cb">std::swap</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6ba65e174dfdcdb111e1aea6b4299b16">llvm::X86II::TB</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a997d8e46d018e151ea881069ba44e495">TO_REV</a>, <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea6702853ec24d45d810d71e321eb9e256">llvm::X86II::VEX</a> and <a href="/web-llvm/docs/api/namespaces/llvm/x86ii/#a74027296f130de8cbbe7bc543dc4285ea8a71098306ad6ceef2c5cde6440f81ff">llvm::X86II::VEX_4V</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### optimizeMOV() {#a3e5a30d596e5e8933a926e2d14d5227f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::optimizeMOV (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI, bool In64BitMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Simplify things like MOV32rm to MOV32o32a.</p>

<p>Declaration at line 24 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 337 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="#a2a5aec578e2e391e99e1705012752d84a319f0e99a1ac9396659683d2638d4f45">AddrBaseReg</a>, <a href="#a2a5aec578e2e391e99e1705012752d84aba7ebe0e28a2c1c4c14343f549c01462">AddrIndexReg</a>, <a href="#a2a5aec578e2e391e99e1705012752d84a353f20f0404222671129b3d31f7ffc7b">AddrScaleAmt</a>, <a href="#a2a5aec578e2e391e99e1705012752d84a8fed367c46e025e4269e9725a94391b6">AddrSegmentReg</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a64c5a9b119e0a1455b1889cf280e9de9">FROM_TO</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#ab6dbd93dfb585d2714b508b45e7c72ad">isARegister</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/fixupstatepointcallersaved-cpp/#ad94b44823fa05679a48c3addadb05c75">Saved</a> and <a href="/web-llvm/docs/api/classes/llvm/mcsymbolrefexpr/#a5c463f6352570ee778c35c40949c4985a5d7dc0ab54306dc5d9af486598f7d26d">llvm::MCSymbolRefExpr::VK_TLVP</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### optimizeMOVSX() {#a690516c8cb802c97acc69f6363735984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::optimizeMOVSX (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 289 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a64c5a9b119e0a1455b1889cf280e9de9">FROM_TO</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### optimizeShiftRotateWithImmediateOne() {#a88575ba0f198af79c61ba3a8c27a69d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::optimizeShiftRotateWithImmediateOne (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 104 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a5f639fdcd3fc673fcbdb47f2e88b2b41">llvm::MCOperand::isImm</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a8594870b8d76b0c22f33b1e5799456fe">TO_IMM1</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### optimizeToFixedRegisterOrShortImmediateForm() {#a0256d671ff2830d0ada28b07b9c7ab25}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::optimizeToFixedRegisterOrShortImmediateForm (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 498 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a714428af145d6964f0312a163f7d3bf0">optimizeToFixedRegisterForm</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a35779cde38be2f4c81791032dcf33b10">optimizeToShortImmediateForm</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### optimizeVPCMPWithImmediateOneOrSix() {#a76d5022aceb3599fdcaf0ef25ee3ce73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::optimizeVPCMPWithImmediateOneOrSix (<a href="/web-llvm/docs/api/classes/llvm/mcinst">MCInst</a> &amp; MI)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 21 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a>, definition at line 202 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp/#a64c5a9b119e0a1455b1889cf280e9de9">FROM_TO</a>, <a href="/web-llvm/docs/api/classes/llvm/mcoperand/#a4509c43893edc940979f690c468664c1">llvm::MCOperand::getImm</a> and <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/irtranslator-cpp/#abe44dfdea65b4f7e11e0a608ab708b76">MI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86mcinstlower-cpp-/x86mcinstlower/#a74bd673118d2cbb40d776bb1726d4c95">anonymous{X86MCInstLower.cpp}::X86MCInstLower::Lower</a>.</p>

</div>
</div>

### parseArchX86() {#a5b9cff715f1fc97546de75b2b79d03af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CPUKind llvm::X86::parseArchX86 (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, bool Only64Bit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse <span class="doxyComputerOutput">CPU</span> string into a <a href="#aaf0c3e7727bf6e2922b7f28dd49cc9be">CPUKind</a>.</p>


<p>Will only accept 64-bit capable CPUs if <span class="doxyComputerOutput">Only64Bit</span> is true.</p>


<p>Declaration at line 156 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 447 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="#aaf0c3e7727bf6e2922b7f28dd49cc9beab9c9853de4af742b0ccd4dbc9e38c7c9">CK_None</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a9a2ed16b3022bea6ce35ceb75c1ac2b3">Processors</a>.</p>


<p>Referenced by <a href="#a320e1de56e30c1bb64817f68d5db20bd">parseTuneCPU</a>.</p>

</div>
</div>

### parseTuneCPU() {#a320e1de56e30c1bb64817f68d5db20bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">X86::CPUKind llvm::X86::parseTuneCPU (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> CPU, bool Only64Bit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 456 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="#aaf0c3e7727bf6e2922b7f28dd49cc9beab9c9853de4af742b0ccd4dbc9e38c7c9">CK_None</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#acd1cd968cb420c82d70926920fcdc7d7">llvm::is_contained</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a7cc0c41eb311684446c226218a357e54">NoTuneList</a> and <a href="#a5b9cff715f1fc97546de75b2b79d03af">parseArchX86</a>.</p>

</div>
</div>

### updateImpliedFeatures() {#a506819ac2ff216f44dd9674f2bebd80b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::X86::updateImpliedFeatures (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Feature, bool Enabled, <a href="/web-llvm/docs/api/classes/llvm/stringmap">StringMap</a>&lt; bool &gt; &amp; Features)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Set or clear entries in <span class="doxyComputerOutput">Features</span> that are implied to be enabled/disabled by the provided <span class="doxyComputerOutput">Feature</span>.</p>

<p>Declaration at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 714 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="#abd1f712df4639ee306f3295384cb9a49ae2889a8b028db56ebebbeffd03557952">CPU_FEATURE_MAX</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/statistic-cpp/#a558f5c44426d0eb7abb82a65e8892d9a">Enabled</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#aec187f4ac003e463a259d0f2e0490e18">FeatureInfos</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a781fc76399744689194cd5f6e6f11a64">getImpliedDisabledFeatures</a>, <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a8dae1243f4742fb2ffa555c4b220c4b4">getImpliedEnabledFeatures</a>, <a href="/web-llvm/docs/api/structs/anonymous-x86targetparser-cpp-/featureinfo/#a8bb4c489f3b7136becc840b8e2916008">anonymous{X86TargetParser.cpp}::FeatureInfo::getName</a> and <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>.</p>

</div>
</div>

### validateCPUSpecificCPUDispatch() {#af3cedda0cef897f8206784454d65b91b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::X86::validateCPUSpecificCPUDispatch (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 181 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a>, definition at line 747 of file <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#ac78c09ae232b2ce188ff590d51e3c268">llvm::find_if</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/files/lib/lib/option/option-cpp/#a04665169063c8ca1f2ea96c27fc7c2b2">P</a> and <a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp/#a9a2ed16b3022bea6ce35ceb75c1ac2b3">Processors</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/targetparser/x86targetparser-h">X86TargetParser.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/disassembler/x86disassembler-cpp">X86Disassembler.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86baseinfo-h">X86BaseInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-cpp">X86EncodingOptimization.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86encodingoptimization-h">X86EncodingOptimization.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/lib/target/x86/mctargetdesc/x86fixupkinds-h">X86FixupKinds.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86fastisel-cpp">X86FastISel.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-cpp">X86InstrInfo.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86instrinfo-h">X86InstrInfo.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-cpp">X86ISelLowering.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86isellowering-h">X86ISelLowering.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/x86/x86iselloweringcall-cpp">X86ISelLoweringCall.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/targetparser/x86targetparser-cpp">X86TargetParser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
