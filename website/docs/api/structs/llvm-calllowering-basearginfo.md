---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/calllowering/basearginfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `BaseArgInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::CallLowering::BaseArgInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">llvm/CodeGen/GlobalISel/CallLowering.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo">ArgInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55702c40a4fac54592b903605db85659">BaseArgInfo</a> (Type *Ty, ArrayRef&lt; ISD::ArgFlagsTy &gt; Flags=ArrayRef&lt; ISD::ArgFlagsTy &gt;(), bool IsFixed=true)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6637109678dde4e960639baec47579e3">BaseArgInfo</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d336cffc2826cb7f708f3228dbd7231">Ty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/smallvector">SmallVector</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a>, 4 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a199d61df156e7d358ec1f18205615b1b">Flags</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbd64ada64994ff4e291f50a0b742dff">IsFixed</a></td>
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


<p>Definition at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### BaseArgInfo() {#a55702c40a4fac54592b903605db85659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallLowering::BaseArgInfo::BaseArgInfo (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Ty, <a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &gt; Flags=<a href="/web-llvm/docs/api/classes/llvm/arrayref">ArrayRef</a>&lt; <a href="/web-llvm/docs/api/structs/llvm/isd/argflagsty">ISD::ArgFlagsTy</a> &gt;(), bool IsFixed=<a href="/web-llvm/docs/api/files/lib/lib/analysis/basicaliasanalysis-cpp/#af6d5cafbdfc5313e65d990120021a3ec">true</a>)</td>
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



<p>Definition at line 54 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="#a199d61df156e7d358ec1f18205615b1b">Flags</a>, <a href="#adbd64ada64994ff4e291f50a0b742dff">IsFixed</a> and <a href="#a4d336cffc2826cb7f708f3228dbd7231">Ty</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#aaf24ebcd885e73b9c2d15bad10c4034c">llvm::CallLowering::ArgInfo::ArgInfo</a>.</p>

</div>
</div>

### BaseArgInfo() {#a6637109678dde4e960639baec47579e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::CallLowering::BaseArgInfo::BaseArgInfo ()</td>
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



<p>Definition at line 59 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>References <a href="#adbd64ada64994ff4e291f50a0b742dff">IsFixed</a> and <a href="#a4d336cffc2826cb7f708f3228dbd7231">Ty</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Flags {#a199d61df156e7d358ec1f18205615b1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SmallVector&lt;ISD::ArgFlagsTy, 4&gt; llvm::CallLowering::BaseArgInfo::Flags</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 51 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#aec3a44a4fabb326d6561308bfa0ec87c">llvm::CallLowering::ArgInfo::ArgInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#aaf24ebcd885e73b9c2d15bad10c4034c">llvm::CallLowering::ArgInfo::ArgInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvincomingvaluehandler/#a9e39af7761ce5879ceeb69d58620835c">anonymous{RISCVCallLowering.cpp}::RISCVIncomingValueHandler::assignCustomValue</a>, <a href="/web-llvm/docs/api/structs/anonymous-riscvcalllowering-cpp-/riscvoutgoingvaluehandler/#a8091aa16f8e98b91cb2e4fa858a06089">anonymous{RISCVCallLowering.cpp}::RISCVOutgoingValueHandler::assignCustomValue</a>, <a href="#a55702c40a4fac54592b903605db85659">BaseArgInfo</a>, <a href="/web-llvm/docs/api/files/lib/lib/codegen/lib/codegen/globalisel/legalizerhelper-cpp/#a3918a234a708d84f71e7eb9c07cff516">conversionLibcall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a78ca5c76a5ac76f5ad51ce5ced36fbb8">llvm::CallLowering::insertSRetIncomingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a1b22f5dbcd629f145563ba79bcb7ce9b">llvm::CallLowering::insertSRetOutgoingArgument</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af5462628f10dea9944615cd509dd3634">llvm::CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a90a141a0a4ccdd0ff757cac3d29f0ee6">llvm::AMDGPUCallLowering::lowerChainCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>.</p>

</div>
</div>

### IsFixed {#adbd64ada64994ff4e291f50a0b742dff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::CallLowering::BaseArgInfo::IsFixed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 52 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#aec3a44a4fabb326d6561308bfa0ec87c">llvm::CallLowering::ArgInfo::ArgInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#aaf24ebcd885e73b9c2d15bad10c4034c">llvm::CallLowering::ArgInfo::ArgInfo</a>, <a href="/web-llvm/docs/api/structs/anonymous-aarch64calllowering-cpp-/outgoingarghandler/#a475797835e85ab2eee4c3364cfc79a2f">anonymous{AArch64CallLowering.cpp}::OutgoingArgHandler::assignValueToAddress</a>, <a href="#a6637109678dde4e960639baec47579e3">BaseArgInfo</a>, <a href="#a55702c40a4fac54592b903605db85659">BaseArgInfo</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>.</p>

</div>
</div>

### Ty {#a4d336cffc2826cb7f708f3228dbd7231}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type* llvm::CallLowering::BaseArgInfo::Ty</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/calllowering/arginfo/#aaf24ebcd885e73b9c2d15bad10c4034c">llvm::CallLowering::ArgInfo::ArgInfo</a>, <a href="#a6637109678dde4e960639baec47579e3">BaseArgInfo</a>, <a href="#a55702c40a4fac54592b903605db85659">BaseArgInfo</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#ad995047f82b555a8ceee0fba2af41899">llvm::AArch64CallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/mipscalllowering/#a5344895d462c34e2c90e930471d8e4d9">llvm::MipsCallLowering::lowerCall</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#af647b791a2c24c4f48aa11d1a77a5bc5">llvm::AArch64CallLowering::lowerFormalArguments</a>, <a href="/web-llvm/docs/api/classes/llvm/aarch64calllowering/#a010cf32a5c68f9701c57d7a3172f1b3f">llvm::AArch64CallLowering::lowerReturn</a>, <a href="/web-llvm/docs/api/classes/llvm/amdgpucalllowering/#a0c3beb54f8fa06f2fd8074561a5a515c">llvm::AMDGPUCallLowering::lowerTailCall</a>, <a href="/web-llvm/docs/api/classes/llvm/calllowering/#af835582e4e7766298680c7d01947036e">llvm::CallLowering::setArgFlags</a> and <a href="/web-llvm/docs/api/classes/llvm/calllowering/#a57d1263b6f2a16c765d594a59c2f8130">llvm::CallLowering::splitToValueTypes</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/include/llvm/codegen/globalisel/calllowering-h">CallLowering.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
