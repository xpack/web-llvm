---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/yaml/machineframeinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `MachineFrameInfo` Struct Reference

<p>Serializable representation of <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo">MachineFrameInfo</a>. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct llvm::yaml::MachineFrameInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">llvm/CodeGen/MIRYamlMapping.h</a>"
</div>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a> (const MachineFrameInfo &amp;Other) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9b00eeb533d4001da1e812507e16959">IsFrameAddressTaken</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa74fd3cd131ed4389fde07f7e2b89f0">IsReturnAddressTaken</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0498221b210f6df4f02fd3add9725c29">HasStackMap</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51235e1a5d7863dc6e9933438de22e6d">HasPatchPoint</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632ec82029fec352e6e4daed322f7e7a">StackSize</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca7b8fcc1a367fef683a9da2d099d8a4">OffsetAdjustment</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d6fb6a5a29375a2921f6790102343da">MaxAlignment</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bf18fefab479cb029f0e9f108729c1d">AdjustsStack</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306aa6e7fca4dc92686608c643fcca8a">HasCalls</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b38bb0439934cfd108a4e94039817d3">StackProtector</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb21232f3c7815e299a2ac4045079ce2">FunctionContext</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44e7d9e28508a268f8b00da0eb02d792">MaxCallFrameSize</a> = ~0u</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>~0u means: not computed yet. <a href="#a44e7d9e28508a268f8b00da0eb02d792">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe8303ed6b0f0d79541058d84e663622">CVBytesOfCalleeSavedRegisters</a> = 0</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0e50d4ef5d9bc86991571c9619de069">HasOpaqueSPAdjustment</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e92ff52f16ad6886618a56be6a9d055">HasVAStart</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9016735335a3c6435f7f16116825219c">HasMustTailInVarArgFunc</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ed48d893132df78f141176402c448db">HasTailCall</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b6b5df16492bd4c6f017af899a9a146">IsCalleeSavedInfoValid</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab55df3c6c13bf6d53d1488479ea7c0bc">LocalFrameSize</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad430069d4a06a264245119f22a382968">SavePoint</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/yaml/stringvalue">StringValue</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a35e68f5c41b739bbe9c62797258568">RestorePoint</a></td>
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

<p>Serializable representation of <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo">MachineFrameInfo</a>.</p>


<p>Doesn't serialize attributes like 'StackAlignment', 'IsStackRealignable' and 'RealignOption' as they are determined by the target and LLVM function attributes. It also doesn't serialize attributes like 'NumFixedObject' and 'HasVarSizedObjects' as they are determined by the frame objects themselves.</p>


<p>Definition at line 649 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<div class="doxySectionDef">

## Public Operators

### operator==() {#a0e07aaf541a2a30bd9f4c77aa528a205}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::operator== (<a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/aarch64/aarch64promoteconstant-cpp/#a90f8350fecae261c25be85d38b451bff">const</a> <a href="/web-llvm/docs/api/structs/llvm/yaml/machineframeinfo">MachineFrameInfo</a> &amp; Other)</td>
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



<p>Definition at line 672 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>References <a href="#a5bf18fefab479cb029f0e9f108729c1d">AdjustsStack</a>, <a href="#abe8303ed6b0f0d79541058d84e663622">CVBytesOfCalleeSavedRegisters</a>, <a href="#afb21232f3c7815e299a2ac4045079ce2">FunctionContext</a>, <a href="#a306aa6e7fca4dc92686608c643fcca8a">HasCalls</a>, <a href="#a9016735335a3c6435f7f16116825219c">HasMustTailInVarArgFunc</a>, <a href="#af0e50d4ef5d9bc86991571c9619de069">HasOpaqueSPAdjustment</a>, <a href="#a51235e1a5d7863dc6e9933438de22e6d">HasPatchPoint</a>, <a href="#a0498221b210f6df4f02fd3add9725c29">HasStackMap</a>, <a href="#a5ed48d893132df78f141176402c448db">HasTailCall</a>, <a href="#a4e92ff52f16ad6886618a56be6a9d055">HasVAStart</a>, <a href="#a3b6b5df16492bd4c6f017af899a9a146">IsCalleeSavedInfoValid</a>, <a href="#aa9b00eeb533d4001da1e812507e16959">IsFrameAddressTaken</a>, <a href="#afa74fd3cd131ed4389fde07f7e2b89f0">IsReturnAddressTaken</a>, <a href="#ab55df3c6c13bf6d53d1488479ea7c0bc">LocalFrameSize</a>, <a href="#a8d6fb6a5a29375a2921f6790102343da">MaxAlignment</a>, <a href="#a44e7d9e28508a268f8b00da0eb02d792">MaxCallFrameSize</a>, <a href="#aca7b8fcc1a367fef683a9da2d099d8a4">OffsetAdjustment</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa6311ae17c1ee52b36e68aaf4ad066387">llvm::Other</a>, <a href="#a0a35e68f5c41b739bbe9c62797258568">RestorePoint</a>, <a href="#ad430069d4a06a264245119f22a382968">SavePoint</a>, <a href="#a7b38bb0439934cfd108a4e94039817d3">StackProtector</a> and <a href="#a632ec82029fec352e6e4daed322f7e7a">StackSize</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### AdjustsStack {#a5bf18fefab479cb029f0e9f108729c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::AdjustsStack = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 657 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### CVBytesOfCalleeSavedRegisters {#abe8303ed6b0f0d79541058d84e663622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::MachineFrameInfo::CVBytesOfCalleeSavedRegisters = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 662 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### FunctionContext {#afb21232f3c7815e299a2ac4045079ce2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::MachineFrameInfo::FunctionContext</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 660 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### HasCalls {#a306aa6e7fca4dc92686608c643fcca8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::HasCalls = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 658 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### HasMustTailInVarArgFunc {#a9016735335a3c6435f7f16116825219c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::HasMustTailInVarArgFunc = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 665 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### HasOpaqueSPAdjustment {#af0e50d4ef5d9bc86991571c9619de069}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::HasOpaqueSPAdjustment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 663 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### HasPatchPoint {#a51235e1a5d7863dc6e9933438de22e6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::HasPatchPoint = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 653 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### HasStackMap {#a0498221b210f6df4f02fd3add9725c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::HasStackMap = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 652 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### HasTailCall {#a5ed48d893132df78f141176402c448db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::HasTailCall = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 666 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### HasVAStart {#a4e92ff52f16ad6886618a56be6a9d055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::HasVAStart = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 664 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### IsCalleeSavedInfoValid {#a3b6b5df16492bd4c6f017af899a9a146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::IsCalleeSavedInfoValid = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 667 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### IsFrameAddressTaken {#aa9b00eeb533d4001da1e812507e16959}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::IsFrameAddressTaken = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 650 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### IsReturnAddressTaken {#afa74fd3cd131ed4389fde07f7e2b89f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::yaml::MachineFrameInfo::IsReturnAddressTaken = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 651 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### LocalFrameSize {#ab55df3c6c13bf6d53d1488479ea7c0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::MachineFrameInfo::LocalFrameSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 668 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### MaxAlignment {#a8d6fb6a5a29375a2921f6790102343da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::MachineFrameInfo::MaxAlignment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 656 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### MaxCallFrameSize {#a44e7d9e28508a268f8b00da0eb02d792}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::yaml::MachineFrameInfo::MaxCallFrameSize = ~0u</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>~0u means: not computed yet.</p>

<p>Definition at line 661 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### OffsetAdjustment {#aca7b8fcc1a367fef683a9da2d099d8a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::yaml::MachineFrameInfo::OffsetAdjustment = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 655 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### RestorePoint {#a0a35e68f5c41b739bbe9c62797258568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::MachineFrameInfo::RestorePoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 670 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### SavePoint {#ad430069d4a06a264245119f22a382968}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::MachineFrameInfo::SavePoint</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 669 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### StackProtector {#a7b38bb0439934cfd108a4e94039817d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringValue llvm::yaml::MachineFrameInfo::StackProtector</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 659 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#afb28916bca65c0b9e9ee811613c51895">llvm::MIRPrinter::convertStackObjects</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

</div>
</div>

### StackSize {#a632ec82029fec352e6e4daed322f7e7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t llvm::yaml::MachineFrameInfo::StackSize = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 654 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/codegen/miryamlmapping-h">MIRYamlMapping.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/classes/llvm/mirprinter/#a154503cbc95ef98bff03d91938d64b07">llvm::MIRPrinter::convert</a>, <a href="/web-llvm/docs/api/classes/llvm/mirparserimpl/#a14e404f789b4aa6b37a554702f0c28ae">llvm::MIRParserImpl::initializeFrameInfo</a>, <a href="/web-llvm/docs/api/structs/llvm/yaml/mappingtraits-54fd480c8e8fd1bb7b1ca4badcca8ef8/#ad47a1fb03ff140e68043caf285d58c10">llvm::yaml::MappingTraits&lt; MachineFrameInfo &gt;::mapping</a> and <a href="#a0e07aaf541a2a30bd9f4c77aa528a205">operator==</a>.</p>

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
