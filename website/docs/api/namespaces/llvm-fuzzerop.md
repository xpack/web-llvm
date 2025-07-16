---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/namespaces/llvm/fuzzerop
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - namespace

---

<div class="doxyPage">

# The `fuzzerop` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace llvm::fuzzerop { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A matcher/generator for finding suitable values for the next source in an operation's partially completed argument list. <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A description of some operation we can build while fuzzing IR. <a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a> (Type *T, std::vector&lt; Constant * &gt; &amp;Cs)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849d8d065430cf5846364b7f73c07416">makeConstantsWithType</a> (Type *T)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd1c4b93eb505c553b1fc21b699b9c4">selectDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Descriptors for individual operations. <a href="#a7bd1c4b93eb505c553b1fc21b699b9c4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a508380ef0b4434cd95fe0943ecc2f25b">fnegDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecee0c15c7ea2581b57ae1e0875f5df1">binOpDescriptor</a> (unsigned Weight, Instruction::BinaryOps Op)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545034b7da895280ed2c457c835d98f2">cmpOpDescriptor</a> (unsigned Weight, Instruction::OtherOps CmpOp, CmpInst::Predicate Pred)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32b5360bb5f3831163d348fc96fc1198">splitBlockDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb32da5629b40ca54fd1cae35c36d4a">gepDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e1cf7cf81a27f8f07b2369d7b8bd750">extractValueDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a621ccb7a201816191c5a584938488649">insertValueDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ae0ff5338fbc8095c360189adfff284">extractElementDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac940e3e889f8c3771434e4c7bffc1404">insertElementDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/fuzzerop/opdescriptor">OpDescriptor</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a647e63adcc4f3bde285b5119fee7477f">shuffleVectorDescriptor</a> (unsigned Weight)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8069953a59ba2891578b351ccf2a6bf3">onlyType</a> (Type *Only)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3c5de240d0947d7b2abb53690cdce7b">anyType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74472f33214ebb46699e76726ef8bffe">anyIntType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ab526916d6ddb4c3aa1208faae361e4">anyIntOrVecIntType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd08692bd6a5eaa38e9cc661b8d9209">boolOrVecBoolType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacf5a0d6dfe60cde7e213599fbdf523b">anyFloatType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38046fd387d0afa5651d245d2f3a2610">anyFloatOrVecFloatType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63e788f18762973cf9f3690fd4bbfb1">anyPtrType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a27a121df43e5e1735eb5781de56594">sizedPtrType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2bff55a07291d47843ff3e4a1548c154">matchFirstLengthWAnyType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afffaaa44175e2eeebcc852c80fb03c40">matchSecondType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match values that have the same type as the first source. <a href="#afffaaa44175e2eeebcc852c80fb03c40">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574dd51b4e96c2754eaea0e457c6f909">anyAggregateType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bf10ae2fe3339b21e42de782b5b7cb7">anyVectorType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3d7a249e54c1fd78688913ffcc2e899">matchFirstType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match values that have the same type as the first source. <a href="#ad3d7a249e54c1fd78688913ffcc2e899">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred">SourcePred</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a764af34b63a5c94bdfc643668bb4c885">matchScalarOfFirstType</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Match values that have the first source's scalar type. <a href="#a764af34b63a5c94bdfc643668bb4c885">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### anyAggregateType() {#a574dd51b4e96c2754eaea0e457c6f909}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyAggregateType ()</td>
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



<p>Definition at line 235 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/mc/mcsubtargetinfo-cpp/#a08e140d603b53c440c54cffc85131c8f">Find</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a92ca992e52dddc420f4b069cae06dfbe">llvm::isa</a>.</p>


<p>Referenced by <a href="#a2e1cf7cf81a27f8f07b2369d7b8bd750">extractValueDescriptor</a> and <a href="#a621ccb7a201816191c5a584938488649">insertValueDescriptor</a>.</p>

</div>
</div>

### anyFloatOrVecFloatType() {#a38046fd387d0afa5651d245d2f3a2610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyFloatOrVecFloatType ()</td>
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



<p>Definition at line 143 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>Referenced by <a href="#aecee0c15c7ea2581b57ae1e0875f5df1">binOpDescriptor</a>, <a href="#a545034b7da895280ed2c457c835d98f2">cmpOpDescriptor</a> and <a href="#a508380ef0b4434cd95fe0943ecc2f25b">fnegDescriptor</a>.</p>

</div>
</div>

### anyFloatType() {#aacf5a0d6dfe60cde7e213599fbdf523b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyFloatType ()</td>
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



<p>Definition at line 135 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>

</div>
</div>

### anyIntOrVecIntType() {#a9ab526916d6ddb4c3aa1208faae361e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyIntOrVecIntType ()</td>
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



<p>Definition at line 121 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>Referenced by <a href="#aecee0c15c7ea2581b57ae1e0875f5df1">binOpDescriptor</a> and <a href="#a545034b7da895280ed2c457c835d98f2">cmpOpDescriptor</a>.</p>

</div>
</div>

### anyIntType() {#a74472f33214ebb46699e76726ef8bffe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyIntType ()</td>
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



<p>Definition at line 113 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>Referenced by <a href="#a5ae0ff5338fbc8095c360189adfff284">extractElementDescriptor</a>, <a href="#aefb32da5629b40ca54fd1cae35c36d4a">gepDescriptor</a> and <a href="#ac940e3e889f8c3771434e4c7bffc1404">insertElementDescriptor</a>.</p>

</div>
</div>

### anyPtrType() {#ad63e788f18762973cf9f3690fd4bbfb1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyPtrType ()</td>
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



<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### anyType() {#af3c5de240d0947d7b2abb53690cdce7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyType ()</td>
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



<p>Definition at line 105 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a47a923aecde90d3d6e66e00bab23318d">llvm::RandomIRBuilder::findOrCreateSource</a>.</p>

</div>
</div>

### anyVectorType() {#a9bf10ae2fe3339b21e42de782b5b7cb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::anyVectorType ()</td>
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



<p>Definition at line 253 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>Referenced by <a href="#a5ae0ff5338fbc8095c360189adfff284">extractElementDescriptor</a>, <a href="#ac940e3e889f8c3771434e4c7bffc1404">insertElementDescriptor</a> and <a href="#a647e63adcc4f3bde285b5119fee7477f">shuffleVectorDescriptor</a>.</p>

</div>
</div>

### binOpDescriptor() {#aecee0c15c7ea2581b57ae1e0875f5df1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::binOpDescriptor (unsigned Weight, <a href="/web-llvm/docs/api/classes/llvm/instruction/#ac26154a24f393f523c87cc5f8239f36c">Instruction::BinaryOps</a> Op)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 41 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 116 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a38046fd387d0afa5651d245d2f3a2610">anyFloatOrVecFloatType</a>, <a href="#a9ab526916d6ddb4c3aa1208faae361e4">anyIntOrVecIntType</a>, <a href="/web-llvm/docs/api/classes/llvm/binaryoperator/#a8f385eda0f71b4e8199b296fbc8e0da9">llvm::BinaryOperator::Create</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ad3d7a249e54c1fd78688913ffcc2e899">matchFirstType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab61cdcba81cc44be5d4fdff8c5172f1d">llvm::describeFuzzerFloatOps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0854017d2b520df10302ff14d350a584">llvm::describeFuzzerIntOps</a>.</p>

</div>
</div>

### boolOrVecBoolType() {#a9cd08692bd6a5eaa38e9cc661b8d9209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::boolOrVecBoolType ()</td>
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



<p>Definition at line 128 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>Referenced by <a href="#a7bd1c4b93eb505c553b1fc21b699b9c4">selectDescriptor</a>.</p>

</div>
</div>

### cmpOpDescriptor() {#a545034b7da895280ed2c457c835d98f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::cmpOpDescriptor (unsigned Weight, <a href="/web-llvm/docs/api/classes/llvm/instruction/#a92db6d5865b9492ef8eeedad41235d0a">Instruction::OtherOps</a> CmpOp, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a2be3583dac92a031fa1458d4d992c78b">CmpInst::Predicate</a> Pred)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 42 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 148 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a38046fd387d0afa5651d245d2f3a2610">anyFloatOrVecFloatType</a>, <a href="#a9ab526916d6ddb4c3aa1208faae361e4">anyIntOrVecIntType</a>, <a href="/web-llvm/docs/api/classes/llvm/cmpinst/#a62e2cf3675b93f0e6c07a4a00852f7cd">llvm::CmpInst::Create</a>, <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/support/errorhandling-h/#ace243f5c25697a1107cce46626b3dc94">llvm_unreachable</a> and <a href="#ad3d7a249e54c1fd78688913ffcc2e899">matchFirstType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ab61cdcba81cc44be5d4fdff8c5172f1d">llvm::describeFuzzerFloatOps</a> and <a href="/web-llvm/docs/api/namespaces/llvm/#a0854017d2b520df10302ff14d350a584">llvm::describeFuzzerIntOps</a>.</p>

</div>
</div>

### extractElementDescriptor() {#a5ae0ff5338fbc8095c360189adfff284}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::extractElementDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 48 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 316 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a74472f33214ebb46699e76726ef8bffe">anyIntType</a>, <a href="#a9bf10ae2fe3339b21e42de782b5b7cb7">anyVectorType</a> and <a href="/web-llvm/docs/api/classes/llvm/extractelementinst/#a686bd809f72a2701d97b1bbd17f7db9f">llvm::ExtractElementInst::Create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a85805fd963bb88590cfb345568b72d50">llvm::describeFuzzerVectorOps</a>.</p>

</div>
</div>

### extractValueDescriptor() {#a2e1cf7cf81a27f8f07b2369d7b8bd750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::extractValueDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 46 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 244 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a574dd51b4e96c2754eaea0e457c6f909">anyAggregateType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/extractvalueinst/#a94c8c620b21236971c734ff2913e99f3">llvm::ExtractValueInst::Create</a> and <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#acd02b84e30b7fa3fa475f938e522eb88">validExtractValueIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5a19c6aa42a42c2dc4d2aa51be8ab4c2">llvm::describeFuzzerAggregateOps</a>.</p>

</div>
</div>

### fnegDescriptor() {#a508380ef0b4434cd95fe0943ecc2f25b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::fnegDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 109 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a38046fd387d0afa5651d245d2f3a2610">anyFloatOrVecFloatType</a> and <a href="/web-llvm/docs/api/classes/llvm/unaryoperator/#a2200cefdf51f62605459b2f2cdfccfa1">llvm::UnaryOperator::Create</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a6b8034d593ee7f11fc68132b7b79dbce">llvm::describeFuzzerUnaryOperations</a>.</p>

</div>
</div>

### gepDescriptor() {#aefb32da5629b40ca54fd1cae35c36d4a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::gepDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 198 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a74472f33214ebb46699e76726ef8bffe">anyIntType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab9c6b351507d3c0730f4290919d43a12">llvm::ArrayRef</a>, <a href="/web-llvm/docs/api/classes/llvm/getelementptrinst/#a7e5d474f9fda4b2b2e5de3dcfefcc472">llvm::GetElementPtrInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a55089293ebaccd683a82d97170041376">llvm::ArrayRef&lt; T &gt;::drop_front</a> and <a href="#a4a27a121df43e5e1735eb5781de56594">sizedPtrType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#acfd13abfd4cb8422e8db63a0e668f69a">llvm::describeFuzzerPointerOps</a>.</p>

</div>
</div>

### insertElementDescriptor() {#ac940e3e889f8c3771434e4c7bffc1404}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::insertElementDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 49 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 325 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a74472f33214ebb46699e76726ef8bffe">anyIntType</a>, <a href="#a9bf10ae2fe3339b21e42de782b5b7cb7">anyVectorType</a>, <a href="/web-llvm/docs/api/classes/llvm/insertelementinst/#a3c7d92166c1f18129c2727c9dc808b29">llvm::InsertElementInst::Create</a> and <a href="#a764af34b63a5c94bdfc643668bb4c885">matchScalarOfFirstType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a85805fd963bb88590cfb345568b72d50">llvm::describeFuzzerVectorOps</a>.</p>

</div>
</div>

### insertValueDescriptor() {#a621ccb7a201816191c5a584938488649}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::insertValueDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 47 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 304 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a574dd51b4e96c2754eaea0e457c6f909">anyAggregateType</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ac4fc845f5ed92de63cd4474f128f5fc5">llvm::cast</a>, <a href="/web-llvm/docs/api/classes/llvm/insertvalueinst/#acc871ff3698895f1efc402d2482032b9">llvm::InsertValueInst::Create</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#ad441fdf76eac1465a3e66ea73f40bdc6">matchScalarInAggregate</a> and <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#ae2afbc4899c3d5a6034358e288eaa7c6">validInsertValueIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a5a19c6aa42a42c2dc4d2aa51be8ab4c2">llvm::describeFuzzerAggregateOps</a>.</p>

</div>
</div>

### makeConstantsWithType() {#a5172beb0382e24b2305c8bc0e46ee1f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void llvm::fuzzerop::makeConstantsWithType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T, std::vector&lt; <a href="/web-llvm/docs/api/classes/llvm/constant">Constant</a> * &gt; &amp; Cs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Populate a small list of potentially interesting constants of a given type.</p>


<p>Declaration at line 32 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>, definition at line 20 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/opdescriptor-cpp">OpDescriptor.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/undefvalue/#a4ae5ff22b700a42bcc5d889233721335">llvm::UndefValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#ab35b08ed1345493af2c69fbb71e4d0c3">llvm::APFloat::getInf</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aaa67fe0741c2b3712630ae636f8c2c20">llvm::APFloat::getLargest</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a331d69b5f93e47e7c596062b77dd5913">llvm::APInt::getMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a65a6479206acd4113b8aa1c0fbc2158c">llvm::APInt::getMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#aeecd5fa66870de83d235933a683b5952">llvm::APFloat::getNaN</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#aec662ee6ab1490a4cabebf2812e5b9ca">llvm::APInt::getOneBitSet</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a562c9513409b74f02cb3a5c9bae672ea">llvm::APInt::getSignedMaxValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apint/#a8f877403433892e14ff0c692cbe9efdf">llvm::APInt::getSignedMinValue</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#abbed2fc7a4a18eea942e56d6b7583c1e">llvm::APFloat::getSmallest</a>, <a href="/web-llvm/docs/api/classes/llvm/constantvector/#aa3b241b35b0039b413faf1ef4e873eb7">llvm::ConstantVector::getSplat</a>, <a href="/web-llvm/docs/api/classes/llvm/apfloat/#af591f8d18d0d9773192a0ffcca41796e">llvm::APFloat::getZero</a>, <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a>, <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a> and <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/opdescriptor-cpp/#aa5933e82bef31cbcd8f019095a872123">UseUndef</a>.</p>


<p>Referenced by <a href="#a849d8d065430cf5846364b7f73c07416">makeConstantsWithType</a>, <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a>, <a href="#a2bff55a07291d47843ff3e4a1548c154">matchFirstLengthWAnyType</a>, <a href="#ad3d7a249e54c1fd78688913ffcc2e899">matchFirstType</a>, <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#ad441fdf76eac1465a3e66ea73f40bdc6">matchScalarInAggregate</a>, <a href="#a764af34b63a5c94bdfc643668bb4c885">matchScalarOfFirstType</a>, <a href="#afffaaa44175e2eeebcc852c80fb03c40">matchSecondType</a>, <a href="#a8069953a59ba2891578b351ccf2a6bf3">onlyType</a> and <a href="/web-llvm/docs/api/classes/llvm/fuzzerop/sourcepred/#ac01e1d16c27a5fb94153178d64b252c6">llvm::fuzzerop::SourcePred::SourcePred</a>.</p>

</div>
</div>

### makeConstantsWithType() {#a849d8d065430cf5846364b7f73c07416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; Constant * &gt; llvm::fuzzerop::makeConstantsWithType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * T)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>, definition at line 56 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/opdescriptor-cpp">OpDescriptor.cpp</a>.</p>


<p>References <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>

</div>
</div>

### matchFirstLengthWAnyType() {#a2bff55a07291d47843ff3e4a1548c154}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::matchFirstLengthWAnyType ()</td>
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



<p>Definition at line 187 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a22eeee01734061ac1b31ccd994c49eef">llvm::dyn_cast</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#a9eb4f5b98b70ee4fab9614ed58282c1fa7fb55ed0b7a30342ba6da306428cae04">llvm::First</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a861be1e2092622462053c6d31dddbfd5">llvm::VectorType::get</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#a59632c5deb0423a518ad984bdd04d41f">llvm::VectorType::getElementCount</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="/web-llvm/docs/api/classes/llvm/vectortype/#aa6a2194fc011669faabe43322d7c6c5f">llvm::VectorType::isValidElementType</a>, <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#a7bd1c4b93eb505c553b1fc21b699b9c4">selectDescriptor</a>.</p>

</div>
</div>

### matchFirstType() {#ad3d7a249e54c1fd78688913ffcc2e899}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::matchFirstType ()</td>
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

<p>Match values that have the same type as the first source.</p>

<p>Definition at line 265 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a>.</p>


<p>Referenced by <a href="#aecee0c15c7ea2581b57ae1e0875f5df1">binOpDescriptor</a>, <a href="#a545034b7da895280ed2c457c835d98f2">cmpOpDescriptor</a> and <a href="#a647e63adcc4f3bde285b5119fee7477f">shuffleVectorDescriptor</a>.</p>

</div>
</div>

### matchScalarOfFirstType() {#a764af34b63a5c94bdfc643668bb4c885}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::matchScalarOfFirstType ()</td>
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

<p>Match values that have the first source's scalar type.</p>

<p>Definition at line 278 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/classes/llvm/arrayref/#ac835b8735b1b2faec0efdca236e37d94">llvm::ArrayRef&lt; T &gt;::empty</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a> and <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a>.</p>


<p>Referenced by <a href="#ac940e3e889f8c3771434e4c7bffc1404">insertElementDescriptor</a>.</p>

</div>
</div>

### matchSecondType() {#afffaaa44175e2eeebcc852c80fb03c40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::matchSecondType ()</td>
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

<p>Match values that have the same type as the first source.</p>

<p>Definition at line 223 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/files/lib/lib/object/tapifile-cpp/#a913a691648e20063bbd278e8f02d8430">getType</a>, <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a> and <a href="/web-llvm/docs/api/classes/llvm/arrayref/#a85ffb6531d4cda988ea81f18d4e56fb7">llvm::ArrayRef&lt; T &gt;::size</a>.</p>


<p>Referenced by <a href="#a7bd1c4b93eb505c553b1fc21b699b9c4">selectDescriptor</a>.</p>

</div>
</div>

### onlyType() {#a8069953a59ba2891578b351ccf2a6bf3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::onlyType (<a href="/web-llvm/docs/api/classes/llvm/type">Type</a> * Only)</td>
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



<p>Definition at line 95 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>Reference <a href="#a5172beb0382e24b2305c8bc0e46ee1f4">makeConstantsWithType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/randomirbuilder/#a993771e7c58c60044cbc4c57f689406e">llvm::RandomIRBuilder::connectToSink</a>, <a href="/web-llvm/docs/api/classes/llvm/insertcfgstrategy/#a4a797db667ae87ab16b62a35de4f4a01">llvm::InsertCFGStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertfunctionstrategy/#a51a23cfe8db3e31fdc6eeb8547df0d33">llvm::InsertFunctionStrategy::mutate</a>, <a href="/web-llvm/docs/api/classes/llvm/insertphistrategy/#a55f9b306ebb441abea69179650c2a4ad">llvm::InsertPHIStrategy::mutate</a> and <a href="/web-llvm/docs/api/classes/llvm/instdeleterirstrategy/#a5d0250802fc18f3e96531f43c6280c18">llvm::InstDeleterIRStrategy::mutate</a>.</p>

</div>
</div>

### selectDescriptor() {#a7bd1c4b93eb505c553b1fc21b699b9c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::selectDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Descriptors for individual operations.</p>

<p>Declaration at line 39 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 100 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a9cd08692bd6a5eaa38e9cc661b8d9209">boolOrVecBoolType</a>, <a href="/web-llvm/docs/api/classes/llvm/selectinst/#a09d8760fa31a7b8739acf71a4d2ac9d9">llvm::SelectInst::Create</a>, <a href="#a2bff55a07291d47843ff3e4a1548c154">matchFirstLengthWAnyType</a> and <a href="#afffaaa44175e2eeebcc852c80fb03c40">matchSecondType</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a3070a16759ed4e2426672bca5bbaea78">llvm::describeFuzzerOtherOps</a>.</p>

</div>
</div>

### shuffleVectorDescriptor() {#a647e63adcc4f3bde285b5119fee7477f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::shuffleVectorDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 50 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 350 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="#a9bf10ae2fe3339b21e42de782b5b7cb7">anyVectorType</a>, <a href="#ad3d7a249e54c1fd78688913ffcc2e899">matchFirstType</a> and <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp/#a1fdfe91f1f9e82078936d0cde2af8a3f">validShuffleVectorIndex</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#a85805fd963bb88590cfb345568b72d50">llvm::describeFuzzerVectorOps</a>.</p>

</div>
</div>

### sizedPtrType() {#a4a27a121df43e5e1735eb5781de56594}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SourcePred llvm::fuzzerop::sizedPtrType ()</td>
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



<p>Definition at line 165 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a>.</p>


<p>References <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/classes/llvm/pointertype/#af8a1dbdbfd89aa4899b3c0d39495d0dd">llvm::PointerType::getUnqual</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/mips/mips16isellowering-cpp/#a0acb682b8260ab1c60b918599864e2e5">T</a>.</p>


<p>Referenced by <a href="#aefb32da5629b40ca54fd1cae35c36d4a">gepDescriptor</a>.</p>

</div>
</div>

### splitBlockDescriptor() {#a32b5360bb5f3831163d348fc96fc1198}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OpDescriptor llvm::fuzzerop::splitBlockDescriptor (unsigned Weight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a>, definition at line 166 of file <a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/namespaces/llvm/#a0e00fad9c34de40b1e31f3aa6f8e024cae1e4c8c9ccd9fc39c391da4bcd093fb2">llvm::Block</a>, <a href="/web-llvm/docs/api/classes/llvm/branchinst/#a9f40e42226cee617c16cb1c447b115c5">llvm::BranchInst::Create</a>, <a href="/web-llvm/docs/api/classes/llvm/poisonvalue/#a1bf08613fb664a2e377a9a72c59a6b66">llvm::PoisonValue::get</a>, <a href="/web-llvm/docs/api/namespaces/llvm/#ab13c360340346d082b959b8cd79f2c1a">llvm::Next</a> and <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/amdgpurewriteundefforphi-cpp/#a2e83cb1bc3f5e8986cbd14575755a134">PHI</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/namespaces/llvm/#ac951769e67885a6a884fbec5c68c6930">llvm::describeFuzzerControlFlowOps</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/opdescriptor-h">OpDescriptor.h</a></li>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/fuzzmutate/operations-h">Operations.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/opdescriptor-cpp">OpDescriptor.cpp</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/fuzzmutate/operations-cpp">Operations.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.15.0.</p>

</div>
