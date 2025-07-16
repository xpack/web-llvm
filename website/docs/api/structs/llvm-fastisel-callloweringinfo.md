---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/fastisel/callloweringinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `CallLoweringInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::FastISel::CallLoweringInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">llvm/CodeGen/FastISel.h</a>"
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> (Type *ResultTy, FunctionType *FuncTy, const Value *Target, ArgListTy &amp;&amp;ArgsList, const CallBase &amp;Call)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a> (Type *ResultTy, FunctionType *FuncTy, MCSymbol *Target, ArgListTy &amp;&amp;ArgsList, const CallBase &amp;Call, unsigned FixedArgs=~0U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa75a2982525b57eeefb55d7121bc031d">setCallee</a> (CallingConv::ID CC, Type *ResultTy, const Value *Target, ArgListTy &amp;&amp;ArgsList, unsigned FixedArgs=~0U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68e52e8dcf5848c74cb89308b41cff89">setCallee</a> (const DataLayout &amp;DL, MCContext &amp;Ctx, CallingConv::ID CC, Type *ResultTy, StringRef Target, ArgListTy &amp;&amp;ArgsList, unsigned FixedArgs=~0U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a48ad50b9a935a9fd733803be475a471c">setCallee</a> (CallingConv::ID CC, Type *ResultTy, MCSymbol *Target, ArgListTy &amp;&amp;ArgsList, unsigned FixedArgs=~0U)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82dac221b85b98eb8f94ff32686bd160">setTailCall</a> (bool Value=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fastisel/callloweringinfo">CallLoweringInfo</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af043061c95e2492fc9827f4a448bd098">setIsPatchPoint</a> (bool Value=true)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel/#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9afd2f3cddf640b761675d0911849ed6">getArgs</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f045e806aefd8c423cb530fccebd43a">clearOuts</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab6aed4bf8d8c73992fcfae25770a273">clearIns</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35d74a4f3f503bb98e00ece4a618b2cf">RetTy</a> = nullptr</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e3d7941faeb1a9d4d95829e6639af2b">RetSExt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c98b4c7e3e37427d5ec2726a0c3f4c">RetZExt</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2a0b115bdda6287fac43fb71ff7352">IsVarArg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa83a71e99909a3ee88f1d987985768d3">IsInReg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae67c13ff67d4d8063eab7a86a3e1d2">DoesNotReturn</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177568b8c8fe3fb99b101a01631574a4">IsReturnValueUsed</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86c35ae83eaef63fd937b0e5d5e258ca">IsPatchPoint</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5633911fe4a62451aa4b7f69454a5751">IsTailCall</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cc29a4b5acce83cf4a83bfee78d3f22">NumFixedArgs</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a308acf766fe89d05cbfc2f59581439b3">CallConv</a> = <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">CallingConv::C</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d8e0bdad594214f654b1bb5bbd40f0a">Callee</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5d9d3725e9cf5db27852d455856d54c">Symbol</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fastisel/#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1516f730e17863515414496a4cbe3747">Args</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72f539529045e72c96f0712e812e4168">CB</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/machineinstr">MachineInstr</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83235b3d69702bbb34da1aaf32c5d683">Call</a> = nullptr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/register">Register</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a236216be5ea40fdc49efb658bf58e67b">ResultReg</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c6e80d35c80d65edc16ffa7ab0d39d">NumResultRegs</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> *, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d86d7e9ef4938e1192b4bb4e2a6507d">OutVals</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a333d2c82c193e4c258195e5f7ba3aed6">OutFlags</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 16 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5370ad419a3bd87b4499e92b1e160736">OutRegs</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afceb1c03b606771c10a049ef11f53d54">Ins</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/register">Register</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad174f5cc68bbbe72a8b902c289320b45">InRegs</a></td>
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


<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallLoweringInfo() {#a68800712c29d721bd730efc13f6836be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::FastISel::CallLoweringInfo::CallLoweringInfo ()</td>
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



<p>Definition at line 100 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a2ae67c13ff67d4d8063eab7a86a3e1d2">DoesNotReturn</a>, <a href="#aa83a71e99909a3ee88f1d987985768d3">IsInReg</a>, <a href="#a86c35ae83eaef63fd937b0e5d5e258ca">IsPatchPoint</a>, <a href="#a177568b8c8fe3fb99b101a01631574a4">IsReturnValueUsed</a>, <a href="#a3e2a0b115bdda6287fac43fb71ff7352">IsVarArg</a>, <a href="#a1e3d7941faeb1a9d4d95829e6639af2b">RetSExt</a>, <a href="#a01c98b4c7e3e37427d5ec2726a0c3f4c">RetZExt</a> and <a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>.</p>


<p>Referenced by <a href="#aa75a2982525b57eeefb55d7121bc031d">setCallee</a>, <a href="#a48ad50b9a935a9fd733803be475a471c">setCallee</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a>, <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>, <a href="#af043061c95e2492fc9827f4a448bd098">setIsPatchPoint</a> and <a href="#a82dac221b85b98eb8f94ff32686bd160">setTailCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clearIns() {#aab6aed4bf8d8c73992fcfae25770a273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastISel::CallLoweringInfo::clearIns ()</td>
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



<p>Definition at line 195 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#ad174f5cc68bbbe72a8b902c289320b45">InRegs</a> and <a href="#afceb1c03b606771c10a049ef11f53d54">Ins</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>.</p>

</div>
</div>

### clearOuts() {#a1f045e806aefd8c423cb530fccebd43a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::FastISel::CallLoweringInfo::clearOuts ()</td>
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



<p>Definition at line 189 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a333d2c82c193e4c258195e5f7ba3aed6">OutFlags</a>, <a href="#a5370ad419a3bd87b4499e92b1e160736">OutRegs</a> and <a href="#a3d86d7e9ef4938e1192b4bb4e2a6507d">OutVals</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>.</p>

</div>
</div>

### getArgs() {#a9afd2f3cddf640b761675d0911849ed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgListTy &amp; llvm::FastISel::CallLoweringInfo::getArgs ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Reference <a href="#a1516f730e17863515414496a4cbe3747">Args</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>.</p>

</div>
</div>

### setCallee() {#afcc487710e7ad6fdc2a66bcc65bd233d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::FastISel::CallLoweringInfo::setCallee (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FuncTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Target, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a> &amp;&amp; ArgsList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call)</td>
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



<p>Definition at line 104 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a1516f730e17863515414496a4cbe3747">Args</a>, <a href="#a83235b3d69702bbb34da1aaf32c5d683">Call</a>, <a href="#a308acf766fe89d05cbfc2f59581439b3">CallConv</a>, <a href="#a6d8e0bdad594214f654b1bb5bbd40f0a">Callee</a>, <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="#a72f539529045e72c96f0712e812e4168">CB</a>, <a href="#a2ae67c13ff67d4d8063eab7a86a3e1d2">DoesNotReturn</a>, <a href="#aa83a71e99909a3ee88f1d987985768d3">IsInReg</a>, <a href="#a177568b8c8fe3fb99b101a01631574a4">IsReturnValueUsed</a>, <a href="#a3e2a0b115bdda6287fac43fb71ff7352">IsVarArg</a>, <a href="#a3cc29a4b5acce83cf4a83bfee78d3f22">NumFixedArgs</a>, <a href="#a1e3d7941faeb1a9d4d95829e6639af2b">RetSExt</a>, <a href="#a35d74a4f3f503bb98e00ece4a618b2cf">RetTy</a> and <a href="#a01c98b4c7e3e37427d5ec2726a0c3f4c">RetZExt</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a429785d5b6015aff39a7a998d9e70fa3">llvm::FastISel::lowerCallTo</a> and <a href="#a68e52e8dcf5848c74cb89308b41cff89">setCallee</a>.</p>

</div>
</div>

### setCallee() {#a6fa3ab45e2761627bc094debd3044cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::FastISel::CallLoweringInfo::setCallee (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy, <a href="/web-llvm/docs/api/classes/llvm/functiontype">FunctionType</a> * FuncTy, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Target, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a> &amp;&amp; ArgsList, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/callbase">CallBase</a> &amp; Call, unsigned FixedArgs=~0U)</td>
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



<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a1516f730e17863515414496a4cbe3747">Args</a>, <a href="#a83235b3d69702bbb34da1aaf32c5d683">Call</a>, <a href="#a308acf766fe89d05cbfc2f59581439b3">CallConv</a>, <a href="#a6d8e0bdad594214f654b1bb5bbd40f0a">Callee</a>, <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="#a72f539529045e72c96f0712e812e4168">CB</a>, <a href="#a2ae67c13ff67d4d8063eab7a86a3e1d2">DoesNotReturn</a>, <a href="#aa83a71e99909a3ee88f1d987985768d3">IsInReg</a>, <a href="#a177568b8c8fe3fb99b101a01631574a4">IsReturnValueUsed</a>, <a href="#a3e2a0b115bdda6287fac43fb71ff7352">IsVarArg</a>, <a href="#a3cc29a4b5acce83cf4a83bfee78d3f22">NumFixedArgs</a>, <a href="#a1e3d7941faeb1a9d4d95829e6639af2b">RetSExt</a>, <a href="#a35d74a4f3f503bb98e00ece4a618b2cf">RetTy</a>, <a href="#a01c98b4c7e3e37427d5ec2726a0c3f4c">RetZExt</a> and <a href="#ac5d9d3725e9cf5db27852d455856d54c">Symbol</a>.</p>

</div>
</div>

### setCallee() {#aa75a2982525b57eeefb55d7121bc031d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::FastISel::CallLoweringInfo::setCallee (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/value">Value</a> * Target, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a> &amp;&amp; ArgsList, unsigned FixedArgs=~0U)</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a1516f730e17863515414496a4cbe3747">Args</a>, <a href="#a308acf766fe89d05cbfc2f59581439b3">CallConv</a>, <a href="#a6d8e0bdad594214f654b1bb5bbd40f0a">Callee</a>, <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a3cc29a4b5acce83cf4a83bfee78d3f22">NumFixedArgs</a> and <a href="#a35d74a4f3f503bb98e00ece4a618b2cf">RetTy</a>.</p>

</div>
</div>

### setCallee() {#a68e52e8dcf5848c74cb89308b41cff89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FastISel::CallLoweringInfo &amp; FastISel::CallLoweringInfo::setCallee (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/datalayout">DataLayout</a> &amp; DL, <a href="/web-llvm/docs/api/classes/llvm/mccontext">MCContext</a> &amp; Ctx, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy, <a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Target, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a> &amp;&amp; ArgsList, unsigned FixedArgs=~0U)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>, definition at line 745 of file <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a067a743bcdf919af7f64f48631be87fd">llvm::FastISel::DL</a>, <a href="/web-llvm/docs/api/classes/llvm/mangler/#aa1c9296fd511eb96bb487befbf5e7cea">llvm::Mangler::getNameWithPrefix</a> and <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a>.</p>

</div>
</div>

### setCallee() {#a48ad50b9a935a9fd733803be475a471c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::FastISel::CallLoweringInfo::setCallee (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ResultTy, <a href="/web-llvm/docs/api/classes/llvm/mcsymbol">MCSymbol</a> * Target, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a82396eecbe0fb665491b6c75be3a5713">ArgListTy</a> &amp;&amp; ArgsList, unsigned FixedArgs=~0U)</td>
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



<p>Definition at line 166 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a1516f730e17863515414496a4cbe3747">Args</a>, <a href="#a308acf766fe89d05cbfc2f59581439b3">CallConv</a>, <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="#a3cc29a4b5acce83cf4a83bfee78d3f22">NumFixedArgs</a>, <a href="#a35d74a4f3f503bb98e00ece4a618b2cf">RetTy</a> and <a href="#ac5d9d3725e9cf5db27852d455856d54c">Symbol</a>.</p>

</div>
</div>

### setIsPatchPoint() {#af043061c95e2492fc9827f4a448bd098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::FastISel::CallLoweringInfo::setIsPatchPoint (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 182 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a> and <a href="#a86c35ae83eaef63fd937b0e5d5e258ca">IsPatchPoint</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### setTailCall() {#a82dac221b85b98eb8f94ff32686bd160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallLoweringInfo &amp; llvm::FastISel::CallLoweringInfo::setTailCall (bool Value=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 177 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>References <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a> and <a href="#a5633911fe4a62451aa4b7f69454a5751">IsTailCall</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a3c0cdb3908fc8b0f795f411e32bb806e">llvm::FastISel::lowerCall</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Args {#a1516f730e17863515414496a4cbe3747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ArgListTy llvm::FastISel::CallLoweringInfo::Args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a9afd2f3cddf640b761675d0911849ed6">getArgs</a>, <a href="#aa75a2982525b57eeefb55d7121bc031d">setCallee</a>, <a href="#a48ad50b9a935a9fd733803be475a471c">setCallee</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### Call {#a83235b3d69702bbb34da1aaf32c5d683}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MachineInstr* llvm::FastISel::CallLoweringInfo::Call = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### CallConv {#a308acf766fe89d05cbfc2f59581439b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallingConv::ID llvm::FastISel::CallLoweringInfo::CallConv = <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">CallingConv::C</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 85 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#aa75a2982525b57eeefb55d7121bc031d">setCallee</a>, <a href="#a48ad50b9a935a9fd733803be475a471c">setCallee</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### Callee {#a6d8e0bdad594214f654b1bb5bbd40f0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Value* llvm::FastISel::CallLoweringInfo::Callee = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="#aa75a2982525b57eeefb55d7121bc031d">setCallee</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### CB {#a72f539529045e72c96f0712e812e4168}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const CallBase* llvm::FastISel::CallLoweringInfo::CB = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### DoesNotReturn {#a2ae67c13ff67d4d8063eab7a86a3e1d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::DoesNotReturn</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### InRegs {#ad174f5cc68bbbe72a8b902c289320b45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 4&gt; llvm::FastISel::CallLoweringInfo::InRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#aab6aed4bf8d8c73992fcfae25770a273">clearIns</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### Ins {#afceb1c03b606771c10a049ef11f53d54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ISD::InputArg, 4&gt; llvm::FastISel::CallLoweringInfo::Ins</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#aab6aed4bf8d8c73992fcfae25770a273">clearIns</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>.</p>

</div>
</div>

### IsInReg {#aa83a71e99909a3ee88f1d987985768d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::IsInReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#ae7c1fa2a94f420cac743955c3db73b28">getReturnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### IsPatchPoint {#a86c35ae83eaef63fd937b0e5d5e258ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::IsPatchPoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 78 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a> and <a href="#af043061c95e2492fc9827f4a448bd098">setIsPatchPoint</a>.</p>

</div>
</div>

### IsReturnValueUsed {#a177568b8c8fe3fb99b101a01631574a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::IsReturnValueUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### IsTailCall {#a5633911fe4a62451aa4b7f69454a5751}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::IsTailCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a> and <a href="#a82dac221b85b98eb8f94ff32686bd160">setTailCall</a>.</p>

</div>
</div>

### IsVarArg {#a3e2a0b115bdda6287fac43fb71ff7352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::IsVarArg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 74 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### NumFixedArgs {#a3cc29a4b5acce83cf4a83bfee78d3f22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FastISel::CallLoweringInfo::NumFixedArgs = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#aa75a2982525b57eeefb55d7121bc031d">setCallee</a>, <a href="#a48ad50b9a935a9fd733803be475a471c">setCallee</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### NumResultRegs {#a40c6e80d35c80d65edc16ffa7ab0d39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::FastISel::CallLoweringInfo::NumResultRegs = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### OutFlags {#a333d2c82c193e4c258195e5f7ba3aed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ISD::ArgFlagsTy, 16&gt; llvm::FastISel::CallLoweringInfo::OutFlags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a1f045e806aefd8c423cb530fccebd43a">clearOuts</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>.</p>

</div>
</div>

### OutRegs {#a5370ad419a3bd87b4499e92b1e160736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Register, 16&gt; llvm::FastISel::CallLoweringInfo::OutRegs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 96 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a1f045e806aefd8c423cb530fccebd43a">clearOuts</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### OutVals {#a3d86d7e9ef4938e1192b4bb4e2a6507d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;Value *, 16&gt; llvm::FastISel::CallLoweringInfo::OutVals</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 94 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a1f045e806aefd8c423cb530fccebd43a">clearOuts</a>, <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>.</p>

</div>
</div>

### ResultReg {#a236216be5ea40fdc49efb658bf58e67b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Register llvm::FastISel::CallLoweringInfo::ResultReg</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a> and <a href="/web-llvm/docs/api/classes/llvm/fastisel/#ac8bc20b89a02f7d1d402a9fb561d1717">llvm::FastISel::selectPatchpoint</a>.</p>

</div>
</div>

### RetSExt {#a1e3d7941faeb1a9d4d95829e6639af2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::RetSExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#ae7c1fa2a94f420cac743955c3db73b28">getReturnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### RetTy {#a35d74a4f3f503bb98e00ece4a618b2cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::FastISel::CallLoweringInfo::RetTy = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 71 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#ae7c1fa2a94f420cac743955c3db73b28">getReturnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#aa75a2982525b57eeefb55d7121bc031d">setCallee</a>, <a href="#a48ad50b9a935a9fd733803be475a471c">setCallee</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### RetZExt {#a01c98b4c7e3e37427d5ec2726a0c3f4c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::FastISel::CallLoweringInfo::RetZExt</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="#a68800712c29d721bd730efc13f6836be">CallLoweringInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp/#ae7c1fa2a94f420cac743955c3db73b28">getReturnAttrs</a>, <a href="/web-llvm/docs/api/classes/llvm/fastisel/#a284bf291d22c5fe81d9cae4b4f1a4fea">llvm::FastISel::lowerCallTo</a>, <a href="#afcc487710e7ad6fdc2a66bcc65bd233d">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

### Symbol {#ac5d9d3725e9cf5db27852d455856d54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MCSymbol* llvm::FastISel::CallLoweringInfo::Symbol = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/anonymous-x86fastisel-cpp-/x86fastisel/#ae60af15492a05f50005ff05276750228">anonymous{X86FastISel.cpp}::X86FastISel::fastLowerCall</a>, <a href="#a48ad50b9a935a9fd733803be475a471c">setCallee</a> and <a href="#a6fa3ab45e2761627bc094debd3044cf7">setCallee</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/fastisel-h">FastISel.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/selectiondag/fastisel-cpp">FastISel.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
