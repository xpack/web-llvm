---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/machinefunction
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# `MachineFunction` Struct



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MachineFunction { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">llvm/CodeGen/MIRYamlMapping.h</a>"
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba2e8ec06abbe646d4bd35e6a6e3a97c">Name</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/maybealign">MaybeAlign</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c7726b1a6b7f283b069bbb0b635475f">Alignment</a> = std::nullopt</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeea0f7fcb710f25aae085b35964183ae">ExposesReturnsTwice</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add00963bb9e345967a5d15e26a94ea0c">Legalized</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c415cc48ef81a0d2b31ab5bd9dcf281">RegBankSelected</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c9919ff2d03b35595aa261a510e1f0d">Selected</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27d7806fe25e0c00e75bdc3a94c03c62">FailedISel</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a8c97438b408f27171481c989bf78d8">TracksRegLiveness</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3ffdf1d35d7990b7638d08bc6218a6b">HasWinCFI</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65c8e995cbc256c9fe661a05db91706c">NoPHIs</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaae3808253574ed9ae1b6297534ef2d">IsSSA</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a925ca7323b68ce24d231f0045b01b8e2">NoVRegs</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58d5289a2652958a400724277203ddcc">HasFakeUses</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f5576db3c62625645adc327ee4f5052">CallsEHReturn</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b15da483d0a8768ca941f4ca1fae7d">CallsUnwindInit</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace3586455329b8de92d6857cc4e5a255">HasEHCatchret</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a982bf1866296321d833c4c54011a9393">HasEHScopes</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accac34c441267d31490a426fa871c892">HasEHFunclets</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60e01471d2263c6c6ed653bd7d05a93">IsOutlined</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e5937af98ee91491e15bcad511fbae7">FailsVerification</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8757f3219b5b658572cec694611f0b64">TracksDebugUserValues</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a884b692c5c3ebbbfc7ac1d55b7d95ed4">UseDebugInstrRef</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/virtualregisterdefinition">VirtualRegisterDefinition</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2571f4b44b3f6a8beffcb959ca04f80">VirtualRegisters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctionlivein">MachineFunctionLiveIn</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab51f61ae0bd39115370428967ca3d51b">LiveIns</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::optional&lt; std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/flowstringvalue">FlowStringValue</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3303a0dc072a32f8f6c197a2712c40ab">CalleeSavedRegisters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo">MachineFrameInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af74e9ad9493c6d667c9ffc71941e0468">FrameInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/fixedmachinestackobject">FixedMachineStackObject</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac62b09916d93504555ac2dfebad458f0">FixedStackObjects</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/entryvalueobject">EntryValueObject</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59151a92c7061811f3634c5bb91f066d">EntryValueObjects</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/machinestackobject">MachineStackObject</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26ee805cbe23d49eeb1ec869ee64b831">StackObjects</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/machineconstantpoolvalue">MachineConstantPoolValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ebb130d06aa8c1b7de125c912bca5c0">Constants</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/machinefunctioninfo">MachineFunctionInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade5f2c6b21e9075909823e4f3383520b">MachineFuncInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> pool. <a href="#ade5f2c6b21e9075909823e4f3383520b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/callsiteinfo">CallSiteInfo</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadfb30b1968ac77ae1d8adabab992c5f">CallSitesInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/debugvaluesubstitution">DebugValueSubstitution</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add3bc1e663452cbc0efc2a9dba55b83f">DebugValueSubstitutions</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/machinejumptable">MachineJumpTable</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6bdcb605d4ef43e0e7486b009ce49a0">JumpTableInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2baf55b45f594519e22af6975eea84e2">MachineMetadataNodes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/structs/llvm/yaml/calledglobal">CalledGlobal</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c6e87eb849a07b79b7c06a19fdf659">CalledGlobals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/blockstringvalue">BlockStringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10b0117a0460fe70fd0e4740a0a41241">Body</a></td>
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


<p>Definition at line 744 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### Alignment {#a3c7726b1a6b7f283b069bbb0b635475f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MaybeAlign llvm::yaml::MachineFunction::Alignment = std::nullopt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 746 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### Body {#a10b0117a0460fe70fd0e4740a0a41241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BlockStringValue llvm::yaml::MachineFunction::Body</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 789 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### CalledGlobals {#a38c6e87eb849a07b79b7c06a19fdf659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CalledGlobal&gt; llvm::yaml::MachineFunction::CalledGlobals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 788 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a5982dea08cc92ad6fd8776a506980a69">llvm::MIRPrinter::convertCalledGlobals</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a9d55670b674a7d3bc9f2df1668d63be8">llvm::MIRParserImpl::parseCalledGlobals</a>.</p>

</div>
</div>

### CalleeSavedRegisters {#a3303a0dc072a32f8f6c197a2712c40ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;std::vector&lt;FlowStringValue&gt; &gt; llvm::yaml::MachineFunction::CalleeSavedRegisters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 775 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae0bc43ffc97603d2acaf34479afbe0c8">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>.</p>

</div>
</div>

### CallsEHReturn {#a2f5576db3c62625645adc327ee4f5052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::CallsEHReturn = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 763 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### CallSitesInfo {#aadfb30b1968ac77ae1d8adabab992c5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;CallSiteInfo&gt; llvm::yaml::MachineFunction::CallSitesInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 784 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa43a432a700f337af56c8f2d1db9fe0b">llvm::MIRPrinter::convertCallSiteObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#aea53e647298055af644a50c3a29e1411">llvm::MIRParserImpl::initializeCallSiteInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>.</p>

</div>
</div>

### CallsUnwindInit {#a31b15da483d0a8768ca941f4ca1fae7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::CallsUnwindInit = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 764 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### Constants {#a8ebb130d06aa8c1b7de125c912bca5c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineConstantPoolValue&gt; llvm::yaml::MachineFunction::Constants</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 782 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afef1b1a235ce94996013a71608e08f58">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a69398364db52b18db9d922fec6d8eb87">llvm::MIRParserImpl::initializeConstantPool</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>.</p>

</div>
</div>

### DebugValueSubstitutions {#add3bc1e663452cbc0efc2a9dba55b83f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DebugValueSubstitution&gt; llvm::yaml::MachineFunction::DebugValueSubstitutions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 785 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### EntryValueObjects {#a59151a92c7061811f3634c5bb91f066d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;EntryValueObject&gt; llvm::yaml::MachineFunction::EntryValueObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 780 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aa02f64dd0aa867287b5ad17200de097a">llvm::MIRPrinter::convertEntryValueObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>.</p>

</div>
</div>

### ExposesReturnsTwice {#aeea0f7fcb710f25aae085b35964183ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::ExposesReturnsTwice = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 747 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### FailedISel {#a27d7806fe25e0c00e75bdc3a94c03c62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::FailedISel = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 752 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### FailsVerification {#a0e5937af98ee91491e15bcad511fbae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::FailsVerification = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 770 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### FixedStackObjects {#ac62b09916d93504555ac2dfebad458f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FixedMachineStackObject&gt; llvm::yaml::MachineFunction::FixedStackObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 779 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>.</p>

</div>
</div>

### FrameInfo {#af74e9ad9493c6d667c9ffc71941e0468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineFrameInfo llvm::yaml::MachineFunction::FrameInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 778 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### HasEHCatchret {#ace3586455329b8de92d6857cc4e5a255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::HasEHCatchret = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 765 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### HasEHFunclets {#accac34c441267d31490a426fa871c892}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::HasEHFunclets = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 767 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### HasEHScopes {#a982bf1866296321d833c4c54011a9393}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::HasEHScopes = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 766 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### HasFakeUses {#a58d5289a2652958a400724277203ddcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::yaml::MachineFunction::HasFakeUses</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 761 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### HasWinCFI {#ab3ffdf1d35d7990b7638d08bc6218a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::HasWinCFI = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 755 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### IsOutlined {#ae60e01471d2263c6c6ed653bd7d05a93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::IsOutlined = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 768 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### IsSSA {#acaae3808253574ed9ae1b6297534ef2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::yaml::MachineFunction::IsSSA</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 759 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### JumpTableInfo {#ae6bdcb605d4ef43e0e7486b009ce49a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineJumpTable llvm::yaml::MachineFunction::JumpTableInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 786 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### Legalized {#add00963bb9e345967a5d15e26a94ea0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::Legalized = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 749 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### LiveIns {#ab51f61ae0bd39115370428967ca3d51b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineFunctionLiveIn&gt; llvm::yaml::MachineFunction::LiveIns</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 774 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae0bc43ffc97603d2acaf34479afbe0c8">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>.</p>

</div>
</div>

### MachineFuncInfo {#ade5f2c6b21e9075909823e4f3383520b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;MachineFunctionInfo&gt; llvm::yaml::MachineFunction::MachineFuncInfo</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> pool.</p>

<p>Definition at line 783 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### MachineMetadataNodes {#a2baf55b45f594519e22af6975eea84e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;StringValue&gt; llvm::yaml::MachineFunction::MachineMetadataNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 787 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae7de4da09df7011d92c1f4abd46134a2">llvm::MIRPrinter::convertMachineMetadataNodes</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#add4fede1a05c8d8148b6ef72f2da3494">llvm::MIRParserImpl::parseMachineMetadataNodes</a>.</p>

</div>
</div>

### Name {#aba2e8ec06abbe646d4bd35e6a6e3a97c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringRef llvm::yaml::MachineFunction::Name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 745 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#afbccb941c0215a918667f3a574b976b9">llvm::MIRParserImpl::parseMachineFunction</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### NoPHIs {#a65c8e995cbc256c9fe661a05db91706c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::yaml::MachineFunction::NoPHIs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 758 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### NoVRegs {#a925ca7323b68ce24d231f0045b01b8e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::optional&lt;bool&gt; llvm::yaml::MachineFunction::NoVRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 760 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### RegBankSelected {#a5c415cc48ef81a0d2b31ab5bd9dcf281}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::RegBankSelected = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 750 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### Selected {#a4c9919ff2d03b35595aa261a510e1f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::Selected = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 751 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### StackObjects {#a26ee805cbe23d49eeb1ec869ee64b831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;MachineStackObject&gt; llvm::yaml::MachineFunction::StackObjects</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 781 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a>.</p>

</div>
</div>

### TracksDebugUserValues {#a8757f3219b5b658572cec694611f0b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::TracksDebugUserValues = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 771 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a3518bb886d39c70ab9163440243d2d5b">llvm::MIRParserImpl::initializeMachineFunction</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### TracksRegLiveness {#a7a8c97438b408f27171481c989bf78d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::TracksRegLiveness = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 754 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae0bc43ffc97603d2acaf34479afbe0c8">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>.</p>

</div>
</div>

### UseDebugInstrRef {#a884b692c5c3ebbbfc7ac1d55b7d95ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFunction::UseDebugInstrRef = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 772 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#aad72f291464c14665189a84050f38376">llvm::MIRPrinter::print</a>.</p>

</div>
</div>

### VirtualRegisters {#ac2571f4b44b3f6a8beffcb959ca04f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;VirtualRegisterDefinition&gt; llvm::yaml::MachineFunction::VirtualRegisters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 773 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#ae0bc43ffc97603d2acaf34479afbe0c8">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-c2500bb2a5b69b206350ed65636c42b7/#a39ae0b4ae268a6b2218b64a5b94066f6">llvm::yaml::MappingTraits&lt; MachineFunction &gt;::mapping</a> and <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a0cd181d3140028362e24cdc5d675ac16">llvm::MIRParserImpl::parseRegisterInfo</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://xpack.github.io/doxygen2docusaurus">doxygen2docusaurus</a> 2.0.0 by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
