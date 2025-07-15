---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MappingTraits` Struct Template Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MappingTraits&lt;MachineFrameInfo&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">llvm/CodeGen/MIRYamlMapping.h</a>"
</div>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad47a1fb03ff140e68043caf285d58c10">mapping</a> (IO &amp;YamlIO, MachineFrameInfo &amp;MFI)</td>
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


<p>Definition at line 696 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Static Functions

### mapping() {#ad47a1fb03ff140e68043caf285d58c10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping (<a href="/web-llvm/docs/api/classes/llvm/yaml/io">IO</a> &amp; YamlIO, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo">MachineFrameInfo</a> &amp; MFI)</td>
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



<p>Definition at line 697 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a5bf18fefab479cb029f0e9f108729c1d">llvm::yaml::MachineFrameInfo::AdjustsStack</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#abe8303ed6b0f0d79541058d84e663622">llvm::yaml::MachineFrameInfo::CVBytesOfCalleeSavedRegisters</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#afb21232f3c7815e299a2ac4045079ce2">llvm::yaml::MachineFrameInfo::FunctionContext</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a306aa6e7fca4dc92686608c643fcca8a">llvm::yaml::MachineFrameInfo::HasCalls</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a9016735335a3c6435f7f16116825219c">llvm::yaml::MachineFrameInfo::HasMustTailInVarArgFunc</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#af0e50d4ef5d9bc86991571c9619de069">llvm::yaml::MachineFrameInfo::HasOpaqueSPAdjustment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a51235e1a5d7863dc6e9933438de22e6d">llvm::yaml::MachineFrameInfo::HasPatchPoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a0498221b210f6df4f02fd3add9725c29">llvm::yaml::MachineFrameInfo::HasStackMap</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a5ed48d893132df78f141176402c448db">llvm::yaml::MachineFrameInfo::HasTailCall</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a4e92ff52f16ad6886618a56be6a9d055">llvm::yaml::MachineFrameInfo::HasVAStart</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a3b6b5df16492bd4c6f017af899a9a146">llvm::yaml::MachineFrameInfo::IsCalleeSavedInfoValid</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#aa9b00eeb533d4001da1e812507e16959">llvm::yaml::MachineFrameInfo::IsFrameAddressTaken</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#afa74fd3cd131ed4389fde07f7e2b89f0">llvm::yaml::MachineFrameInfo::IsReturnAddressTaken</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#ab55df3c6c13bf6d53d1488479ea7c0bc">llvm::yaml::MachineFrameInfo::LocalFrameSize</a>, <a href="/web-llvm/docs/api/classes/llvm/yaml/io/#a27dee5b4ee79b39bc614889a4186bbf5">llvm::yaml::IO::mapOptional</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a8d6fb6a5a29375a2921f6790102343da">llvm::yaml::MachineFrameInfo::MaxAlignment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a44e7d9e28508a268f8b00da0eb02d792">llvm::yaml::MachineFrameInfo::MaxCallFrameSize</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#aca7b8fcc1a367fef683a9da2d099d8a4">llvm::yaml::MachineFrameInfo::OffsetAdjustment</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a0a35e68f5c41b739bbe9c62797258568">llvm::yaml::MachineFrameInfo::RestorePoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#ad430069d4a06a264245119f22a382968">llvm::yaml::MachineFrameInfo::SavePoint</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a7b38bb0439934cfd108a4e94039817d3">llvm::yaml::MachineFrameInfo::StackProtector</a> and <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo/#a632ec82029fec352e6e4daed322f7e7a">llvm::yaml::MachineFrameInfo::StackSize</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
