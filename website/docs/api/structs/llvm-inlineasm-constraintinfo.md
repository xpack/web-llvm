---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/structs/llvm/inlineasm/constraintinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ConstraintInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct llvm::InlineAsm::ConstraintInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">llvm/IR/InlineAsm.h</a>"
</div>

## Derived Structs

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo">AsmOperandInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>This contains information for each constraint that we are lowering. <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a929e11f775a8ed52098a6ebb9f41228a">ConstraintInfo</a> ()=default</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Default constructor. <a href="#a929e11f775a8ed52098a6ebb9f41228a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8e8a75156972d158e5d2ad295dc3abd">hasMatchingInput</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>hasMatchingInput - Return true if this is an output constraint that has a matching input constraint. <a href="#af8e8a75156972d158e5d2ad295dc3abd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a> (StringRef Str, ConstraintInfoVector &amp;ConstraintsSoFar)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse - Analyze the specified string (e.g. <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49538ed53bce83dcf52b11234d559a4">selectAlternative</a> (unsigned index)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>selectAlternative - Point this constraint to the alternative constraint indicated by the index. <a href="#af49538ed53bce83dcf52b11234d559a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbb2f32e064775612e79585ca06bb38c">hasArg</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Whether this constraint corresponds to an argument. <a href="#abbb2f32e064775612e79585ca06bb38c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34">ConstraintPrefix</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3400e49d5c9d94f96aa1117ecd0b799d">Type</a> = <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6">isInput</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> - The basic type of the constraint: input/output/clobber/label. <a href="#a3400e49d5c9d94f96aa1117ecd0b799d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8d69e9e180e95d3db75d01a377c4f7b">isEarlyClobber</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isEarlyClobber - "&amp;": output operand writes result before inputs are all read. <a href="#ad8d69e9e180e95d3db75d01a377c4f7b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45ceac563ee359193e4d45e3bafeeb64">MatchingInput</a> = -1</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>MatchingInput - If this is not -1, this is an output constraint where an input constraint is required to match it (e.g. <a href="#a45ceac563ee359193e4d45e3bafeeb64">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f648e1a394e583d417765348cf69aaa">isCommutative</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isCommutative - This is set to true for a constraint that is commutative with the next operand. <a href="#a0f648e1a394e583d417765348cf69aaa">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbf697bfd59727faf13eeb80fdf90d79">isIndirect</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isIndirect - True if this operand is an indirect operand. <a href="#acbf697bfd59727faf13eeb80fdf90d79">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#adbd59a81e5e06598a94e8b0e3b216d99">ConstraintCodeVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45da89271c079571aad8d046b1e612b9">Codes</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Code - The constraint code, either the register name (in braces) or the constraint letter/number. <a href="#a45da89271c079571aad8d046b1e612b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb37fd376d51ba0400e0d4a718b82f34">isMultipleAlternative</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>isMultipleAlternative - '|': has multiple-alternative constraints. <a href="#adb37fd376d51ba0400e0d4a718b82f34">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a50ba5ef85decec05c8ea0fc180379eeb">SubConstraintInfoVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abceda5166e96dabf2ea376669b86699d">multipleAlternatives</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>multipleAlternatives - If there are multiple alternative constraints, this array will contain them. <a href="#abceda5166e96dabf2ea376669b86699d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">unsigned</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a644cffb72161b4ee4261bbd0611851da">currentAlternativeIndex</a> = 0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>The currently selected alternative constraint index. <a href="#a644cffb72161b4ee4261bbd0611851da">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<p>Definition at line 123 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConstraintInfo() {#a929e11f775a8ed52098a6ebb9f41228a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">llvm::InlineAsm::ConstraintInfo::ConstraintInfo ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Default constructor.</p>

<p>Definition at line 167 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="/web-llvm/docs/api/structs/llvm/targetlowering/asmoperandinfo/#a298e5957360e936bbd356565a323d45b">llvm::TargetLowering::AsmOperandInfo::AsmOperandInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasArg() {#abbb2f32e064775612e79585ca06bb38c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::ConstraintInfo::hasArg ()</td>
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

<p>Whether this constraint corresponds to an argument.</p>

<p>Definition at line 179 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>References <a href="#acbf697bfd59727faf13eeb80fdf90d79">isIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6">llvm::InlineAsm::isInput</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f">llvm::InlineAsm::isOutput</a> and <a href="#a3400e49d5c9d94f96aa1117ecd0b799d">Type</a>.</p>

</div>
</div>

### hasMatchingInput() {#af8e8a75156972d158e5d2ad295dc3abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::ConstraintInfo::hasMatchingInput ()</td>
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

<p>hasMatchingInput - Return true if this is an output constraint that has a matching input constraint.</p>

<p>Definition at line 140 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Reference <a href="#a45ceac563ee359193e4d45e3bafeeb64">MatchingInput</a>.</p>


<p>Referenced by <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a>.</p>

</div>
</div>

### Parse() {#aa7d317c3dcdf1f805c995e9b3f2cba5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool InlineAsm::ConstraintInfo::Parse (<a href="/web-llvm/docs/api/classes/llvm/stringref">StringRef</a> Str, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a6698ed8a3a2b1518a9bd8af9b026bfc2">ConstraintInfoVector</a> &amp; ConstraintsSoFar)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse - Analyze the specified string (e.g.</p>


<p>"=*&amp;{eax}") and fill in the fields in this structure. If the constraint string is not understood, return true, otherwise return false.</p>


<p>"==&amp;{eax}") and fill in the fields in this structure. If the constraint string is not understood, return true, otherwise return false.</p>


<p>Declaration at line 172 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 79 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>


<p>References <a href="/web-llvm/docs/api/files/lib/lib/target/lib/target/amdgpu/silowercontrolflow-cpp/#a4868c5d81c5ccc98c47aeab6244346a0">assert</a>, <a href="/web-llvm/docs/api/namespaces/llvm/callingconv/#ac6aa1387c4375260e2468eb5a77fdb4cafd841a49aec1539bc88abc8ff9e170fb">llvm::CallingConv::C</a>, <a href="#a45da89271c079571aad8d046b1e612b9">Codes</a>, <a href="#a644cffb72161b4ee4261bbd0611851da">currentAlternativeIndex</a>, <a href="#af8e8a75156972d158e5d2ad295dc3abd">hasMatchingInput</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/md5-cpp/#ac0eafdc9ee161b71e7af98af736952fd">I</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34adf39e7f7e158f2ccacae6d4446197322">llvm::InlineAsm::isClobber</a>, <a href="#a0f648e1a394e583d417765348cf69aaa">isCommutative</a>, <a href="#ad8d69e9e180e95d3db75d01a377c4f7b">isEarlyClobber</a>, <a href="#acbf697bfd59727faf13eeb80fdf90d79">isIndirect</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6">llvm::InlineAsm::isInput</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a2903cfed1fe44719f76b46abcac40955">llvm::InlineAsm::isLabel</a>, <a href="#adb37fd376d51ba0400e0d4a718b82f34">isMultipleAlternative</a>, <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34aabfa616f81b4833fdf462b07aabfa53f">llvm::InlineAsm::isOutput</a>, <a href="#a45ceac563ee359193e4d45e3bafeeb64">MatchingInput</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineasm/subconstraintinfo/#ac9eb2f77e099aa841114a5fa767ed406">llvm::InlineAsm::SubConstraintInfo::MatchingInput</a>, <a href="#abceda5166e96dabf2ea376669b86699d">multipleAlternatives</a>, <a href="/web-llvm/docs/api/files/lib/lib/support/regcomp-c/#a0240ac851181b84ac374872dc5434ee4">N</a> and <a href="#a3400e49d5c9d94f96aa1117ecd0b799d">Type</a>.</p>

</div>
</div>

### selectAlternative() {#af49538ed53bce83dcf52b11234d559a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void InlineAsm::ConstraintInfo::selectAlternative (unsigned index)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>selectAlternative - Point this constraint to the alternative constraint indicated by the index.</p>

<p>Declaration at line 176 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>, definition at line 225 of file <a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a>.</p>


<p>References <a href="#a45da89271c079571aad8d046b1e612b9">Codes</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineasm/subconstraintinfo/#a907e764ba5f5a8cf55fcddac6c782d53">llvm::InlineAsm::SubConstraintInfo::Codes</a>, <a href="#a644cffb72161b4ee4261bbd0611851da">currentAlternativeIndex</a>, <a href="#a45ceac563ee359193e4d45e3bafeeb64">MatchingInput</a>, <a href="/web-llvm/docs/api/structs/llvm/inlineasm/subconstraintinfo/#ac9eb2f77e099aa841114a5fa767ed406">llvm::InlineAsm::SubConstraintInfo::MatchingInput</a> and <a href="#abceda5166e96dabf2ea376669b86699d">multipleAlternatives</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### Codes {#a45da89271c079571aad8d046b1e612b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstraintCodeVector llvm::InlineAsm::ConstraintInfo::Codes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Code - The constraint code, either the register name (in braces) or the constraint letter/number.</p>

<p>Definition at line 154 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a> and <a href="#af49538ed53bce83dcf52b11234d559a4">selectAlternative</a>.</p>

</div>
</div>

### currentAlternativeIndex {#a644cffb72161b4ee4261bbd0611851da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">unsigned llvm::InlineAsm::ConstraintInfo::currentAlternativeIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>The currently selected alternative constraint index.</p>

<p>Definition at line 164 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a> and <a href="#af49538ed53bce83dcf52b11234d559a4">selectAlternative</a>.</p>

</div>
</div>

### isCommutative {#a0f648e1a394e583d417765348cf69aaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::ConstraintInfo::isCommutative = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isCommutative - This is set to true for a constraint that is commutative with the next operand.</p>

<p>Definition at line 144 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a>.</p>

</div>
</div>

### isEarlyClobber {#ad8d69e9e180e95d3db75d01a377c4f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::ConstraintInfo::isEarlyClobber = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isEarlyClobber - "&amp;": output operand writes result before inputs are all read.</p>


<p>This is only ever set for an output operand.</p>


<p>Definition at line 130 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a>.</p>

</div>
</div>

### isIndirect {#acbf697bfd59727faf13eeb80fdf90d79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::ConstraintInfo::isIndirect = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isIndirect - True if this operand is an indirect operand.</p>


<p>This means that the address of the source or destination is present in the call instruction, instead of it being returned or passed in explicitly. This is represented with a '*' in the asm string.</p>


<p>Definition at line 150 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#abbb2f32e064775612e79585ca06bb38c">hasArg</a> and <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a>.</p>

</div>
</div>

### isMultipleAlternative {#adb37fd376d51ba0400e0d4a718b82f34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool llvm::InlineAsm::ConstraintInfo::isMultipleAlternative = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>isMultipleAlternative - '|': has multiple-alternative constraints.</p>

<p>Definition at line 157 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a>.</p>

</div>
</div>

### MatchingInput {#a45ceac563ee359193e4d45e3bafeeb64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int llvm::InlineAsm::ConstraintInfo::MatchingInput = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>MatchingInput - If this is not -1, this is an output constraint where an input constraint is required to match it (e.g.</p>


<p>"0"). The value is the constraint number that matches this one (for example, if this is constraint #0 and constraint #4 has the value "0", this will be 4).</p>


<p>Definition at line 136 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#af8e8a75156972d158e5d2ad295dc3abd">hasMatchingInput</a>, <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a> and <a href="#af49538ed53bce83dcf52b11234d559a4">selectAlternative</a>.</p>

</div>
</div>

### multipleAlternatives {#abceda5166e96dabf2ea376669b86699d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubConstraintInfoVector llvm::InlineAsm::ConstraintInfo::multipleAlternatives</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>multipleAlternatives - If there are multiple alternative constraints, this array will contain them.</p>


<p>Otherwise it will be empty.</p>


<p>Definition at line 161 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a> and <a href="#af49538ed53bce83dcf52b11234d559a4">selectAlternative</a>.</p>

</div>
</div>

### Type {#a3400e49d5c9d94f96aa1117ecd0b799d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConstraintPrefix llvm::InlineAsm::ConstraintInfo::Type = <a href="/web-llvm/docs/api/classes/llvm/inlineasm/#a511f48809ad14f13e50b957a137a9d34a79ca3881430605a6c7da5227cfb115d6">isInput</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p><a href="/web-llvm/docs/api/classes/llvm/type">Type</a> - The basic type of the constraint: input/output/clobber/label.</p>

<p>Definition at line 126 of file <a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a>.</p>


<p>Referenced by <a href="#abbb2f32e064775612e79585ca06bb38c">hasArg</a> and <a href="#aa7d317c3dcdf1f805c995e9b3f2cba5f">Parse</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-llvm/docs/api/files/include/include/llvm/include/llvm/ir/inlineasm-h">InlineAsm.h</a></li>
<li><a href="/web-llvm/docs/api/files/lib/lib/ir/inlineasm-cpp">InlineAsm.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
