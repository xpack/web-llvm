---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/llvm/mipsccstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# `MipsCCState` Class



## Declaration

<div class="doxyDeclaration">
class llvm::MipsCCState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">Target/Mips/MipsCCState.h</a>"
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/ccstate">CCState</a> - This class holds information needed while lowering arguments and return values. <a href="/web-llvm/docs/api/classes/llvm/ccstate/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">SpecialCallingConvType { <a href="#aebe47f41b5ac2f62cb48cd64227d18e6">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec927300e4f4d5403ecf615a8b65cbb1">MipsCCState</a> (CallingConv::ID CC, bool isVarArg, MachineFunction &amp;MF, SmallVectorImpl&lt; CCValAssign &gt; &amp;locs, LLVMContext &amp;C, SpecialCallingConvType SpecialCC=NoSpecialCallingConv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4e7e0c4faafb1894a276accb6fd408c">PreAnalyzeCallOperand</a> (const Type *ArgTy, bool IsFixed, const char *Func)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7308ff84a93e55c54db394614a71a44">PreAnalyzeFormalArgument</a> (const Type *ArgTy, ISD::ArgFlagsTy Flags)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b59cb89474f9bb8123234228d0fb9de">PreAnalyzeReturnValue</a> (EVT ArgVT)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683ce79eb0199ca165f8eaa9a9746246">PreAnalyzeCallOperands</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, CCAssignFn Fn, std::vector&lt; TargetLowering::ArgListEntry &gt; &amp;FuncArgs, const char *Func)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d2b0101dc2d1a6ffa03253155f70997">AnalyzeCallOperands</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, CCAssignFn Fn, std::vector&lt; TargetLowering::ArgListEntry &gt; &amp;FuncArgs, const char *Func)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bef262276f92e09f170b0e09df88a40">AnalyzeCallOperands</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, CCAssignFn Fn)=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fc612f0c6543333b0ff5016df8e9ea5">AnalyzeCallOperands</a> (const SmallVectorImpl&lt; MVT &gt; &amp;Outs, SmallVectorImpl&lt; ISD::ArgFlagsTy &gt; &amp;Flags, CCAssignFn Fn)=delete</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8370c2aa5db7852161c806be0ed1adc7">PreAnalyzeFormalArguments</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, CCAssignFn Fn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7161379a628484c264e813f4242dcb5e">AnalyzeFormalArguments</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, CCAssignFn Fn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af242a1e8e8ffad834f2e08e506bbe09d">PreAnalyzeCallResult</a> (const Type *RetTy, const char *Func)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af883842e429421c70a58306c2dde1155">PreAnalyzeCallResult</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, CCAssignFn Fn, const Type *RetTy, const char *Func)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06fde3f9233a53ac354fb6420a863c7f">AnalyzeCallResult</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, CCAssignFn Fn, const Type *RetTy, const char *Func)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a172ed7d7e1742f65da047687072e69ed">PreAnalyzeReturn</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, CCAssignFn Fn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a636f01e99c6ad112c0418dac4bff625e">AnalyzeReturn</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, CCAssignFn Fn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28791682d69d5b455b28a779a15c177b">CheckReturn</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;ArgsFlags, CCAssignFn Fn)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ed5da268911a13c83169922a8458b3f">CheckCallReturn</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;ArgsFlags, CCAssignFn Fn, const Type *RetTy)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfb59c101fa7c9f8b819f3755ef9585a">WasOriginalArgF128</a> (unsigned ValNo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a800e4de220942b8a371d213b10cf42f3">WasOriginalArgFloat</a> (unsigned ValNo)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2b40adbd64374426f43b994f66e00d1">WasOriginalArgVectorFloat</a> (unsigned ValNo) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d8fead272a007665f00b8e981cab996">WasOriginalRetVectorFloat</a> (unsigned ValNo) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbab773af4872da633a6d1a280a5df02">IsCallOperandFixed</a> (unsigned ValNo)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aebe47f41b5ac2f62cb48cd64227d18e6">SpecialCallingConvType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8e0f314d33ffab4b75672ae9455bfc5">getSpecialCallingConv</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9185beeddda56bf88a74840adf577938">PreAnalyzeCallResultForF128</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const Type *RetTy, const char *Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify lowered values that originated from f128 arguments and record this for use by RetCC_MipsN. <a href="#a9185beeddda56bf88a74840adf577938">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7707b27234bb6e04c679c3ed525e57a8">PreAnalyzeCallReturnForF128</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, const Type *RetTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify lowered values that originated from f128 arguments and record this for use by RetCC_MipsN. <a href="#a7707b27234bb6e04c679c3ed525e57a8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07666c41756f76d7c47d26a82e66c120">PreAnalyzeCallOperands</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs, std::vector&lt; TargetLowering::ArgListEntry &gt; &amp;FuncArgs, const char *Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify lowered values that originated from f128 arguments and record this. <a href="#a07666c41756f76d7c47d26a82e66c120">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e17cac74c3876394cf6fafa76f439a4">PreAnalyzeFormalArgumentsForF128</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify lowered values that originated from f128 arguments and record this for use by RetCC_MipsN. <a href="#a3e17cac74c3876394cf6fafa76f439a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a427dc45224e5bb7c86b0255df37046">PreAnalyzeCallResultForVectorFloat</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins, const Type *RetTy)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify lower values that originated from vXfXX and record this. <a href="#a0a427dc45224e5bb7c86b0255df37046">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30bd143e443ffdb4f6569504e2c26235">PreAnalyzeFormalArgumentsForVectorFloat</a> (const SmallVectorImpl&lt; ISD::InputArg &gt; &amp;Ins)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89926782c6b1b7f4efbe1fbaf09a8366">PreAnalyzeReturnForVectorFloat</a> (const SmallVectorImpl&lt; ISD::OutputArg &gt; &amp;Outs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Identify lowered values that originated from vXfXX arguments and record this. <a href="#a89926782c6b1b7f4efbe1fbaf09a8366">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d2e01f3adceddc5842a36cb2b2bed5">OriginalArgWasF128</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records whether the value has been lowered from an f128. <a href="#a19d2e01f3adceddc5842a36cb2b2bed5">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58e4c396308147304c1cc9e581749add">OriginalArgWasFloat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records whether the value has been lowered from float. <a href="#a58e4c396308147304c1cc9e581749add">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463da33e174f5a3c9137153042fabb90">OriginalArgWasFloatVector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records whether the value has been lowered from a floating point vector. <a href="#a463da33e174f5a3c9137153042fabb90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0a9192414dd2e2a8a037f487a9b09da">OriginalRetWasFloatVector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records whether the return value has been lowered from a floating point vector. <a href="#ae0a9192414dd2e2a8a037f487a9b09da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; bool, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a4f29363ba3715c18446197ea0a1059">CallOperandIsFixed</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Records whether the value was a fixed argument. <a href="#a7a4f29363ba3715c18446197ea0a1059">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aebe47f41b5ac2f62cb48cd64227d18e6">SpecialCallingConvType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd1fa771ee609b78574621644206651c">SpecialCallingConv</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="#aebe47f41b5ac2f62cb48cd64227d18e6">SpecialCallingConvType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adffd27d3c37f8d01edff0e86ec3ff644">getSpecialCallingConvForCallee</a> (const SDNode *Callee, const MipsSubtarget &amp;Subtarget)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Determine the <a href="#aebe47f41b5ac2f62cb48cd64227d18e6">SpecialCallingConvType</a> for the given callee. <a href="#adffd27d3c37f8d01edff0e86ec3ff644">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3f63290aff1f6b522c80c818a9d025ab">isF128SoftLibCall</a> (const char *CallSym)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns true if CallSym is a long double emulation routine. <a href="#a3f63290aff1f6b522c80c818a9d025ab">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ce1e013c79a2151bb92de2c2d293f0c">originalTypeIsF128</a> (const Type *Ty, const char *Func)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This function returns true if Ty is fp128, {f128} or i128 which was originally a fp128. <a href="#a4ce1e013c79a2151bb92de2c2d293f0c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a2fb53893c831fb7b9b539f7c7cf72e">originalEVTTypeIsVectorFloat</a> (EVT Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the original type was vXfXX. <a href="#a9a2fb53893c831fb7b9b539f7c7cf72e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01ae19db281adf449c3e960be5a6da5d">originalTypeIsVectorFloat</a> (const Type *Ty)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return true if the original type was vXfXX / vXfXX. <a href="#a01ae19db281adf449c3e960be5a6da5d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### SpecialCallingConvType {#aebe47f41b5ac2f62cb48cd64227d18e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum llvm::MipsCCState::SpecialCallingConvType </td>
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
<td class="doxyEnumItemName">Mips16RetHelperConv<a id="aebe47f41b5ac2f62cb48cd64227d18e6ab733877ed3fc676a03ab0fd5bb35e856"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NoSpecialCallingConv<a id="aebe47f41b5ac2f62cb48cd64227d18e6accde6c8d8e7ef08b4c3862358ce9eaac"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### MipsCCState() {#aec927300e4f4d5403ecf615a8b65cbb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::MipsCCState::MipsCCState (<a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#abdf8cf606905c10634e831390981b0ed">CallingConv::ID</a> CC, bool isVarArg, <a href="/web-llvm/docs/api/classes/llvm/machinefunction">MachineFunction</a> &amp; MF, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/ccvalassign">CCValAssign</a> &gt; &amp; locs, <a href="/web-llvm/docs/api/classes/llvm/llvmcontext">LLVMContext</a> &amp; C, <a href="#aebe47f41b5ac2f62cb48cd64227d18e6">SpecialCallingConvType</a> SpecialCC=<a href="#aebe47f41b5ac2f62cb48cd64227d18e6accde6c8d8e7ef08b4c3862358ce9eaac">NoSpecialCallingConv</a>)</td>
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



<p>Definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/riscv/riscvredundantcopyelimination-cpp/#a77c69067ae8279bc00ab8757731e90d7">CC</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#abf5a0a68b80983e3e00b9107ed77e93c">llvm::CCState::CCState</a>, <a href="/web-llvm/docs/api/classes/llvm/ccstate/#ad2dd5d4efbdc498ece37be010f478f98">llvm::CCState::isVarArg</a> and <a href="#aebe47f41b5ac2f62cb48cd64227d18e6accde6c8d8e7ef08b4c3862358ce9eaac">NoSpecialCallingConv</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### AnalyzeCallOperands() {#a0d2b0101dc2d1a6ffa03253155f70997}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::AnalyzeCallOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/arglistentry">TargetLowering::ArgListEntry</a> &gt; &amp; FuncArgs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
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



<p>Definition at line 114 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a919797ac95a1d84d08e4f43eedededa4">llvm::CCState::AnalyzeCallOperands</a>.</p>

</div>
</div>

### AnalyzeCallOperands() {#a5bef262276f92e09f170b0e09df88a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::AnalyzeCallOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn)</td>
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



<p>Definition at line 125 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### AnalyzeCallOperands() {#a9fc612f0c6543333b0ff5016df8e9ea5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::AnalyzeCallOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/classes/llvm/mvt">MVT</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &gt; &amp; Flags, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn)</td>
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



<p>Definition at line 127 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### AnalyzeCallResult() {#a06fde3f9233a53ac354fb6420a863c7f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::AnalyzeCallResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
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



<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a34218a663a02de9dc2d26a5639f58ebe">llvm::CCState::AnalyzeCallResult</a> and <a href="#af242a1e8e8ffad834f2e08e506bbe09d">PreAnalyzeCallResult</a>.</p>

</div>
</div>

### AnalyzeFormalArguments() {#a7161379a628484c264e813f4242dcb5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::AnalyzeFormalArguments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn)</td>
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



<p>Definition at line 139 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccstate/#aec8b01e38583a4e371e14c436324d3be">llvm::CCState::AnalyzeFormalArguments</a> and <a href="#a8370c2aa5db7852161c806be0ed1adc7">PreAnalyzeFormalArguments</a>.</p>

</div>
</div>

### AnalyzeReturn() {#a636f01e99c6ad112c0418dac4bff625e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::AnalyzeReturn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn)</td>
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



<p>Definition at line 178 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a73b07a938dd8182363ba52719d38bf53">llvm::CCState::AnalyzeReturn</a> and <a href="#a172ed7d7e1742f65da047687072e69ed">PreAnalyzeReturn</a>.</p>

</div>
</div>

### CheckCallReturn() {#a4ed5da268911a13c83169922a8458b3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsCCState::CheckCallReturn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; ArgsFlags, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
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



<p>Definition at line 196 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a687c88d4217651cc56a5a4aed7c8364f">llvm::CCState::CheckReturn</a>.</p>

</div>
</div>

### CheckReturn() {#a28791682d69d5b455b28a779a15c177b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsCCState::CheckReturn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; ArgsFlags, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn)</td>
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



<p>Definition at line 184 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a687c88d4217651cc56a5a4aed7c8364f">llvm::CCState::CheckReturn</a> and <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a0a00791a56db2f910830fea7c154061d">llvm::CCState::getMachineFunction</a>.</p>

</div>
</div>

### getSpecialCallingConv() {#ad8e0f314d33ffab4b75672ae9455bfc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecialCallingConvType llvm::MipsCCState::getSpecialCallingConv ()</td>
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



<p>Definition at line 217 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### IsCallOperandFixed() {#acbab773af4872da633a6d1a280a5df02}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsCCState::IsCallOperandFixed (unsigned ValNo)</td>
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



<p>Definition at line 216 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### PreAnalyzeCallOperand() {#ab4e7e0c4faafb1894a276accb6fd408c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeCallOperand (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ArgTy, bool IsFixed, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 132 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a> and <a href="#a4ce1e013c79a2151bb92de2c2d293f0c">originalTypeIsF128</a>.</p>

</div>
</div>

### PreAnalyzeCallOperands() {#a683ce79eb0199ca165f8eaa9a9746246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::PreAnalyzeCallOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/arglistentry">TargetLowering::ArgListEntry</a> &gt; &amp; FuncArgs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
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



<p>Definition at line 103 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### PreAnalyzeCallResult() {#af242a1e8e8ffad834f2e08e506bbe09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::PreAnalyzeCallResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
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



<p>Definition at line 145 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="#a4ce1e013c79a2151bb92de2c2d293f0c">originalTypeIsF128</a> and <a href="#a01ae19db281adf449c3e960be5a6da5d">originalTypeIsVectorFloat</a>.</p>


<p>Referenced by <a href="#a06fde3f9233a53ac354fb6420a863c7f">AnalyzeCallResult</a> and <a href="/web-llvm/docs/api/structs/anonymous-mipscalllowering-cpp-/mipsincomingvalueassigner/#af7adc7bea2e74a6a1b49c5543c53c119">anonymous{MipsCallLowering.cpp}::MipsIncomingValueAssigner::assignArg</a>.</p>

</div>
</div>

### PreAnalyzeCallResult() {#af883842e429421c70a58306c2dde1155}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::PreAnalyzeCallResult (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
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



<p>Definition at line 151 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### PreAnalyzeFormalArgument() {#ab7308ff84a93e55c54db394614a71a44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeFormalArgument (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * ArgTy, <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> Flags)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 156 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/type/#aac5759c83abd6a4af236401a7cfe7a0f">llvm::Type::isFloatingPointTy</a>, <a href="/web-llvm/docs/api/classes/llvm/type/#a1bc022868b23918efa44df511f4d5b61">llvm::Type::isVectorTy</a> and <a href="#a4ce1e013c79a2151bb92de2c2d293f0c">originalTypeIsF128</a>.</p>

</div>
</div>

### PreAnalyzeFormalArguments() {#a8370c2aa5db7852161c806be0ed1adc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::PreAnalyzeFormalArguments (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn)</td>
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



<p>Definition at line 131 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>Referenced by <a href="#a7161379a628484c264e813f4242dcb5e">AnalyzeFormalArguments</a>.</p>

</div>
</div>

### PreAnalyzeReturn() {#a172ed7d7e1742f65da047687072e69ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::PreAnalyzeReturn (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/namespaces/llvm/#aa555cd3eb8141809d16bcfc45ccc3715">CCAssignFn</a> Fn)</td>
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



<p>Definition at line 168 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>Reference <a href="/web-llvm/docs/api/classes/llvm/ccstate/#a0a00791a56db2f910830fea7c154061d">llvm::CCState::getMachineFunction</a>.</p>


<p>Referenced by <a href="#a636f01e99c6ad112c0418dac4bff625e">AnalyzeReturn</a>.</p>

</div>
</div>

### PreAnalyzeReturnValue() {#a4b59cb89474f9bb8123234228d0fb9de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeReturnValue (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> ArgVT)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 128 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>Reference <a href="#a9a2fb53893c831fb7b9b539f7c7cf72e">originalEVTTypeIsVectorFloat</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/anonymous-mipscalllowering-cpp-/mipsoutgoingvalueassigner/#a3df6a7e63762376a088acec41d1f3623">anonymous{MipsCallLowering.cpp}::MipsOutgoingValueAssigner::assignArg</a>.</p>

</div>
</div>

### WasOriginalArgF128() {#adfb59c101fa7c9f8b819f3755ef9585a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsCCState::WasOriginalArgF128 (unsigned ValNo)</td>
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



<p>Definition at line 206 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### WasOriginalArgFloat() {#a800e4de220942b8a371d213b10cf42f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsCCState::WasOriginalArgFloat (unsigned ValNo)</td>
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



<p>Definition at line 207 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### WasOriginalArgVectorFloat() {#ab2b40adbd64374426f43b994f66e00d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsCCState::WasOriginalArgVectorFloat (unsigned ValNo)</td>
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



<p>Definition at line 210 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsisellowering-cpp/#a169d373fe5dc70c88b2a47ff825e3203">CC_MipsO32</a>.</p>

</div>
</div>

### WasOriginalRetVectorFloat() {#a5d8fead272a007665f00b8e981cab996}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::MipsCCState::WasOriginalRetVectorFloat (unsigned ValNo)</td>
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



<p>Definition at line 213 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### PreAnalyzeCallOperands() {#a07666c41756f76d7c47d26a82e66c120}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeCallOperands (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/targetloweringbase/arglistentry">TargetLowering::ArgListEntry</a> &gt; &amp; FuncArgs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify lowered values that originated from f128 arguments and record this.</p>


<p>Identify lowered values that originated from f128, float and sret to vXfXX arguments and record this.</p>


<p>Declaration at line 57 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 142 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>

</div>
</div>

### PreAnalyzeCallResultForF128() {#a9185beeddda56bf88a74840adf577938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeCallResultForF128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify lowered values that originated from f128 arguments and record this for use by RetCC_MipsN.</p>

<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 86 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>

</div>
</div>

### PreAnalyzeCallResultForVectorFloat() {#a0a427dc45224e5bb7c86b0255df37046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeCallResultForVectorFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify lower values that originated from vXfXX and record this.</p>

<p>Declaration at line 67 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 110 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>

</div>
</div>

### PreAnalyzeCallReturnForF128() {#a7707b27234bb6e04c679c3ed525e57a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeCallReturnForF128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * RetTy)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify lowered values that originated from f128 arguments and record this for use by RetCC_MipsN.</p>


<p>Identify lowered values that originated from f128 or float arguments and record this for use by RetCC_MipsN.</p>


<p>Declaration at line 52 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 98 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>

</div>
</div>

### PreAnalyzeFormalArgumentsForF128() {#a3e17cac74c3876394cf6fafa76f439a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeFormalArgumentsForF128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify lowered values that originated from f128 arguments and record this for use by RetCC_MipsN.</p>


<p>Identify lowered values that originated from f128, float and vXfXX arguments and record this.</p>


<p>Declaration at line 64 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 179 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>

</div>
</div>

### PreAnalyzeFormalArgumentsForVectorFloat() {#a30bd143e443ffdb4f6569504e2c26235}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::MipsCCState::PreAnalyzeFormalArgumentsForVectorFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/inputarg">ISD::InputArg</a> &gt; &amp; Ins)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### PreAnalyzeReturnForVectorFloat() {#a89926782c6b1b7f4efbe1fbaf09a8366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void MipsCCState::PreAnalyzeReturnForVectorFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/smallvectorimpl">SmallVectorImpl</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg">ISD::OutputArg</a> &gt; &amp; Outs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Identify lowered values that originated from vXfXX arguments and record this.</p>

<p>Declaration at line 74 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 119 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### CallOperandIsFixed {#a7a4f29363ba3715c18446197ea0a1059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool, 4&gt; llvm::MipsCCState::CallOperandIsFixed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records whether the value was a fixed argument.</p>


<p>See <a href="/web-llvm/docs/api/structs/llvm/isd/outputarg/#a9bb58c151230b43fe1f83b08a3158548">ISD::OutputArg::IsFixed</a>,</p>


<p>Definition at line 91 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### OriginalArgWasF128 {#a19d2e01f3adceddc5842a36cb2b2bed5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool, 4&gt; llvm::MipsCCState::OriginalArgWasF128</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records whether the value has been lowered from an f128.</p>

<p>Definition at line 77 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### OriginalArgWasFloat {#a58e4c396308147304c1cc9e581749add}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool, 4&gt; llvm::MipsCCState::OriginalArgWasFloat</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records whether the value has been lowered from float.</p>

<p>Definition at line 80 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### OriginalArgWasFloatVector {#a463da33e174f5a3c9137153042fabb90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool, 4&gt; llvm::MipsCCState::OriginalArgWasFloatVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records whether the value has been lowered from a floating point vector.</p>

<p>Definition at line 83 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### OriginalRetWasFloatVector {#ae0a9192414dd2e2a8a037f487a9b09da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;bool, 4&gt; llvm::MipsCCState::OriginalRetWasFloatVector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Records whether the return value has been lowered from a floating point vector.</p>

<p>Definition at line 87 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

### SpecialCallingConv {#afd1fa771ee609b78574621644206651c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SpecialCallingConvType llvm::MipsCCState::SpecialCallingConv</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### getSpecialCallingConvForCallee() {#adffd27d3c37f8d01edff0e86ec3ff644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MipsCCState::SpecialCallingConvType MipsCCState::getSpecialCallingConvForCallee (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/sdnode">SDNode</a> * Callee, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget">MipsSubtarget</a> &amp; Subtarget)</td>
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

<p>Determine the <a href="#aebe47f41b5ac2f62cb48cd64227d18e6">SpecialCallingConvType</a> for the given callee.</p>

<p>Declaration at line 26 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 70 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#a96d73bbd7af15cb1fc38c3f4a3bd82e9">F</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ad96b7cf3182ce2ba85e5a7a93b12c441">G</a>, <a href="/web-llvm/docs/api/classes/llvm/mipssubtarget/#ac77c16f733d57892503f227844026d5e">llvm::MipsSubtarget::inMips16HardFloat</a>, <a href="#aebe47f41b5ac2f62cb48cd64227d18e6ab733877ed3fc676a03ab0fd5bb35e856">Mips16RetHelperConv</a> and <a href="#aebe47f41b5ac2f62cb48cd64227d18e6accde6c8d8e7ef08b4c3862358ce9eaac">NoSpecialCallingConv</a>.</p>

</div>
</div>

### isF128SoftLibCall() {#a3f63290aff1f6b522c80c818a9d025ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsCCState::isF128SoftLibCall (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * CallSym)</td>
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

<p>This function returns true if CallSym is a long double emulation routine.</p>


<p>FIXME: Changing the ABI based on the callee name is unsound. The lib func address could be captured.</p>


<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 15 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a864e071375fea140a5441a243372ff81">llvm::is_sorted</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpulegalizerinfo-cpp/#a22eabd3566ae5f32cb6f594f4f343399">S1</a>.</p>


<p>Referenced by <a href="#a4ce1e013c79a2151bb92de2c2d293f0c">originalTypeIsF128</a>.</p>

</div>
</div>

### originalEVTTypeIsVectorFloat() {#a9a2fb53893c831fb7b9b539f7c7cf72e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsCCState::originalEVTTypeIsVectorFloat (<a href="/web-llvm/docs/api/structs/llvm/evt">EVT</a> Ty)</td>
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

<p>Return true if the original type was vXfXX.</p>

<p>Declaration at line 36 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 54 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>Referenced by <a href="#a4b59cb89474f9bb8123234228d0fb9de">PreAnalyzeReturnValue</a>.</p>

</div>
</div>

### originalTypeIsF128() {#a4ce1e013c79a2151bb92de2c2d293f0c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsCCState::originalTypeIsF128 (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> char * Func)</td>
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

<p>This function returns true if Ty is fp128, {f128} or i128 which was originally a fp128.</p>

<p>Declaration at line 35 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 39 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>Reference <a href="#a3f63290aff1f6b522c80c818a9d025ab">isF128SoftLibCall</a>.</p>


<p>Referenced by <a href="#ab4e7e0c4faafb1894a276accb6fd408c">PreAnalyzeCallOperand</a>, <a href="#af242a1e8e8ffad834f2e08e506bbe09d">PreAnalyzeCallResult</a> and <a href="#ab7308ff84a93e55c54db394614a71a44">PreAnalyzeFormalArgument</a>.</p>

</div>
</div>

### originalTypeIsVectorFloat() {#a01ae19db281adf449c3e960be5a6da5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool MipsCCState::originalTypeIsVectorFloat (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty)</td>
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

<p>Return true if the original type was vXfXX / vXfXX.</p>

<p>Declaration at line 37 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a>, definition at line 62 of file <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a>.</p>


<p>Referenced by <a href="#af242a1e8e8ffad834f2e08e506bbe09d">PreAnalyzeCallResult</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-cpp">MipsCCState.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mipsccstate-h">MipsCCState.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
